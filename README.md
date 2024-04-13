# Grafana Dashboards Collection

Grafana Dashboards Collection.

## Table of Content

- [Nextcloud Logs](#nextcloud-logs)
- [PrivateBin Access Logs](#privatebin-access-logs)
- [Promtail Metrics and Logs](#promtail-metrics-and-logs)
- [SSH Logs](#ssh-logs)
- [SUDO Logs](#sudo-logs)
- [Author Information](#author-information)

## Nextcloud Logs

Nextcloud Application and Audit Logs dashboard.

Log shipper: `promtail`

Log aggregator: `loki`

Grafana dashboard URL: [Dashboard ID 17821](https://grafana.com/grafana/dashboards/17821-nextcloud-log/)

How to use this dashboard is described in blog: [Parsing Nextcloud Audit Logs with Grafana Loki](https://voidquark.com/blog/parsing-nextcloud-audit-logs-with-grafana-loki/).

## PrivateBin Access Logs

Monitoring PrivateBin Application NGINX Access Logs for paste statistics.

Log shipper: `promtail`

Log aggregator: `loki`

Grafana dashboard URL: [Dashboard ID 19507](https://grafana.com/grafana/dashboards/19507-privatebin-access-log/)

How to use this dashboard is described in blog: [PrivateBin NGINX Access Log](https://voidquark.com/blog/privatebin-nginx-access-log-dashboard/).

## Promtail Metrics and Logs

Promtail Metrics and Logs dashboard.

Log shipper: `promtail`

Log aggregator: `loki`

Datasources: `prometheus, loki` (mixed)

Grafana dashboard URL: [Dashboard ID 20881](https://grafana.com/grafana/dashboards/20881-promtail-monitoring-metrics-and-logs/)

How to use this dashboard is described in blog: [Grafana Dashboard for Promtail Metrics and Logs](https://voidquark.com/blog/promtail-grafana-dashboard/).

## SSH Logs

Linux SSH Logs dashboard.

Log shipper: `promtail`

Log aggregator: `loki`

Grafana dashboard URL: [Dashboard ID 17514](https://grafana.com/grafana/dashboards/17514-ssh-logs/)

How to use this dashboard is described in blog: [Parsing SSH Logs with Grafana Loki](https://voidquark.com/blog/parsing-ssh-logs-with-grafana-loki/).

## SUDO Logs

Linux SUDO Logs dashboard. Track both accepted and rejected SUDO events.

Log shipper: `promtail`

Log aggregator: `loki`

Grafana dashboard URL: [Dashboard ID 19816](https://grafana.com/grafana/dashboards/19816-sudo-logs-json-version/)

How to use this dashboard is described in blog: [Parsing SUDO Logs with Grafana Loki](https://voidquark.com/blog/parsing-sudo-logs-with-grafana-loki).

## Author Information

Created by [VoidQuark](https://voidquark.com)
