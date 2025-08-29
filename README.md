# GCP Kubernetes Cost Optimizer 🚀 (In Progress)

Analyze and optimize Kubernetes (GKE Autopilot) clusters by collecting Prometheus metrics and generating cost/scale recommendations. Deployed via Helm with CI/CD automation.

## Status
🟡 In Progress – scaffolding and Helm chart in place. Next: implement metrics collection and basic recommendations.

## Tech Stack
- Go (CLI & analyzer)
- Kubernetes (GKE Autopilot)
- Helm
- Prometheus & Grafana (observability)
- GitHub Actions (CI/CD)

## Roadmap
- [ ] Collect CPU/memory usage from pods/nodes
- [ ] Generate right-sizing & autoscaling recommendations
- [ ] Deploy analyzer as CronJob via Helm
- [ ] Add Grafana dashboards for efficiency KPIs

## License
MIT