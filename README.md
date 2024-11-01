# Kubernetes Learning Repository

This repository captures my learning journey in Kubernetes, showcasing projects and setups to understand core concepts. Key examples include:

1. **Single-Pod Multi-Container Setup**: Demonstrates a Node.js app and MongoDB database in a single pod, highlighting data loss issues when the application pod stops.

2. **Separate Application and Database Pods**: Runs the Node.js app and MongoDB in separate pods, ensuring data persists even if the app pod stops.

### Prerequisites
- Docker, Node.js, kubectl, and Minikube

### Deployment
1. Start Minikube: `minikube start`
2. Apply manifests for each setup (e.g., `kubectl apply -f <manifest.yml>`)

### Docker Images
- Single-Pod: `tauqueer/my-nodejs:single-pod-v1`
- Multi-Pod: `tauqueer/my-nodejs:multi-pod-v1`

### Manifests
- Single-Pod: `deployement-node-app.yml`, `service-node-app.yml`
- Separate Pods: `mongo-config.yml`, `mongo-db.yml`, `node-app.yml`

![Screenshot](https://github.com/user-attachments/assets/81df8d69-edd1-45ae-abc3-232f4af8de72)

![Screenshot 2024-10-24 203001](https://github.com/user-attachments/assets/7cdcdd72-9b80-44b3-8449-9eb4007cc7a8)

![Screenshot 2024-10-24 203417](https://github.com/user-attachments/assets/2c44da66-48bf-4382-81c5-7870f16991a7)
