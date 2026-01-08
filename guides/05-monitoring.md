# Monitoring and Observability

Core stack: Prometheus, Alertmanager, Grafana, and a logging solution (Loki/ELK).

Recommendations:
- Instrument apps with OpenTelemetry or Prometheus client libraries.
- Define SLOs and alerting rules tied to them.
- Use dashboards for key metrics: latency, error rate, resource usage.
