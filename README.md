# sensor_exporter

Containerised version of [sensor_exporter](https://github.com/andmarios/sensor_exporter)

sensor_exporter is a metrics exporter for [Prometheus](https://prometheus.io/)

Set $ARGUMENTS with your desired command arguments to pass to sensor_exporter

---
#### 0.0.1

- 2017-12-14 :: Initial release
---


#### Example Run Command

```
docker run -d -p 9091:9091 -v /sys:/sys:ro b3vis/sensor_exporter
```
---
