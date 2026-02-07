# Feature: Local Kubernetes Deployment

## Objective
Deploy the Todo Chatbot (frontend + backend) on a local Kubernetes cluster using Minikube and Helm.

## Components
- Frontend: Next.js 14
- Backend: FastAPI
- Containerization: Docker
- Orchestration: Kubernetes (Minikube)
- Package Manager: Helm Charts

## Requirements
1. Both services must run as containers
2. Services must communicate via internal Kubernetes DNS
3. Expose frontend using NodePort
4. Backend should not be publicly exposed
5. Use 2 replicas for frontend
6. Use 1 replica for backend

## AI DevOps Tools
- Docker AI Agent (Gordon) for Docker commands
- kubectl-ai for Kubernetes operations
- kagent for cluster analysis
