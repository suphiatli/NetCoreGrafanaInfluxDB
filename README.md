# NetCoreGrafanaInfluxDB


-imported package
App.Metrics.AspNetCore.Mvc
App.Metrics.Reporting.InfluxDB

-run grafana and influxdb on docker container
docker run -d --name=docker_grafana -p 3000:3000 grafana/grafana
docker run -d --name=docker_influxdb -p 8086:8086 -v /docker-volumes/influxdb:/var/lib/influxdb influxdb

-v 
create volume for bind influxdb on host disc

-create database in influxdb container
create database ArticleDB

