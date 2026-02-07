# Cloud Deployment Spec

## Kubernetes
- Cluster: AKS, GKE, or Oracle OKE
- Helm charts deploy frontend/backend
- Dapr sidecar runs with each pod
- Kafka topics created via Redpanda Cloud or Strimzi operator

## Pub/Sub
- Topics: task-events, reminders, task-updates
- Services: Notification, Recurring Task, Audit, WebSocket

## Secrets Management
- Dapr secrets component
- Kubernetes Secrets

## State Management
- Dapr state store (PostgreSQL/Neon)

## CI/CD
- GitHub Actions deploy Helm chart to cluster

