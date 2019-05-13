# docker-lpg
Puppet role definition for deployment of naturalis loki+prometheus+grafana server

As an extra alertmanager is added.

Docker-compose
--------------

This puppet script configures a complete docker-compose setup.

The following folders need to be created:
- /opt/monitoring/
- /data/monitoring/{[loki/prometheus/grafana]}

## Grafana

- Loki datasource >
`http://loki:3100`

- Prometheus datasource (server) >
`http://prometheus:9090/`

- Alertmanager url >
`http://alertmanager:9093`
