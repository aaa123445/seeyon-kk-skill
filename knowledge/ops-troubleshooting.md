# V5 运维 / 性能 / 宕机排查整理

## 系统监控

位置：系统管理员后台 → 系统监控。

系统监控提供：产品运行时间、在线人数、JVM 运行状态、JDBC Dump、Thread Dump 等，是日常运维第一入口。

关注：

- 产品线、版本、BuildID。
- Online Users、Peak Online Users。
- PC/M3/UC 在线人数。
- StartTime、Runtime。
- JVM Heap / Non-Heap。
- Connection Pooling。
- Mode 是否为生产 `product`。

## G1GC 检查

V5 产品要求使用 G1GC。系统监控 JVM 表格最后一行 Gen：

- `G1...`：配置正确。
- `PS...` 等：可能是 Parallel Scavenge，存在频繁 Full GC 和卡顿风险，需要修正。

非标中间件/老版本手工信创部署尤其要核查 G1GC。

## JVM 内存判断

Heap：重点看 G1 Old Gen。

- 正常：Used Ratio 长期 40%~70%。
- 风险：长期约 80%，Peak Ratio 超过 80%。
- 危险：接近 100%，且频繁 Full GC。

Non-Heap：关注 Metaspace、Code Cache。

参考参数：

```text
-XX:ReservedCodeCacheSize=1024m
-XX:MaxMetaspaceSize=2048m
-XX:MetaspaceSize=2048m
```

## 通用宕机排查

先判断 OA/中间件进程是否存活。

### 进程不存在

1. 检查宕机文件：`.hprof`、`hs_err_pidxxxx.txt`、`mdmp`、`core dump`。
2. 检查 OS：oom kill、java crash、core dump、系统重启记录、`last` 登录退出。
3. 检查应用日志：`ctp.log` 是否有 `System destoryed`，中间件日志是否有 Exit/halt。
4. 检查 S1/备份任务、杀软、安全软件、堡垒机审计。

### 进程存在但不可用

1. 检查是否生成 hprof。
2. 检查 CPU/内存/磁盘 IO/网络。
3. 查看 JVM 内存、GC 状态。
4. 抓取 Thread Dump 和内存 dump。
5. 检查应用/中间件日志是否有 OOM、StackOverflow。
6. 检查 JDK 版本。
7. 检查数据库、Redis 等依赖。

## CPU 高

Linux：

```bash
top -n 1 -o %CPU
top -Hp <java_pid>
```

CPU 状态判断：

- `us`：应用计算。
- `sy`：内核处理。
- `wa`：I/O 等待。
- `hi/si`：硬/软中断。
- `st`：虚拟化宿主机抢占。

Java 进程 CPU 高：

- Arthas：`dashboard`、`thread -n 10 >> thread_cpu.txt`。
- 或 `top -Hp` 找线程 ID，转十六进制后在 jstack 中定位。

## 内存高

Linux 看 `available`，不要只看 `free`，buffer/cache 是 Linux 正常机制。

```bash
free -h
top -n 1 -o %MEM
```

OA 进程内存高：

- 比较进程 RSS 与 `-Xmx`，进程内存理论会大于堆，但远大于堆可能是非堆/直接内存/本地内存异常。
- 最大堆配置要结合手册和 G1 Old Gen 使用率判断。
- 老年代峰值约 70% 时不建议降低堆。
- 老年代过高或 OOM 时按内存泄漏/溢出流程导 dump 分析。

## 图片资料补充：DM 数据库连接

图片显示配置工具中有达梦 DM 数据库连接和“数据库连接成功”提示。信创/国产化环境要核查：

- DB 类型 DM。
- JDBC URL，如 `jdbc:dm://host:5236/...`。
- 用户名/密码。
- 驱动包、方言、连接池配置。
- 测试连接功能。

## 核验清单

- [ ] 先确认进程存活，再决定走 crash 还是 hang 排查。
- [ ] 保存现场：日志、dump、top/free、系统监控截图。
- [ ] CPU 高要定位到线程栈，不只看进程。
- [ ] 内存高要区分 heap/non-heap/native/buffer-cache。
- [ ] G1GC、product mode、连接池状态已确认。
- [ ] 信创/DM/中间件环境核查驱动和 JVM 参数。
