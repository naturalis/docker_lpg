# docker_lpg
Puppet role definition for deployment of naturalis loki+prometheus+grafana server

Docker-compose
--------------

This puppet script configures a complete docker-compose setup.

The following folders need to be created:
- /opt/monitoring/datasources
- /data/monitoring/{[loki/prometheus/grafana/datasources]}

## Grafana

As datasources you can set:

- Loki >>
`http://loki:3100`

- Prometheus >
`server: http://prometheus:9090/`
