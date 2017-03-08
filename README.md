# influxdb_granafa_demo
基于influxdb和granafa搭建可视化监控系统，甚至是小的调用链跟踪系统

## influxdb可以做什么?
> 存储时间序列数据

如:
- nginx访问日志。
- sql访问日志
- 业务性能日志
通过脚本，或收集类的agent，定期入库influxdb即可，其它的统计工作，就可以交给granafa了。

## granafa是什么

> granafa是可定制的可视化工具，内置了influxdb接口。通过写sql语句，即可完成展示功能。

举例如下：
- nginx慢查询
- nginx url波动曲线
- nginx带宽
- 业务日志平均响应时间，最大响应时间，调用次数等。
上述数据，可以发现系统性能瓶颈，从而为性能优化，设计优化提供指导依据。

