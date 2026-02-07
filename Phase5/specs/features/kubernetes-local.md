# Local Kubernetes Cluster Spec

Cluster Tool: Minikube  
Node Count: 1  
Purpose: Local development and testing  

Services:
- Frontend exposed via NodePort
- Backend internal ClusterIP

Scaling:
- Frontend replicas: 2
- Backend replicas: 1
