# P2 Node.js Application Deployment with Helm and Kubernetes

## Overview
This project demonstrates the deployment of a Node.js application using Docker, Kubernetes, and Helm for efficient application management and deployment.

## Project Steps
1. **Node.js Application**: Created a simple Node.js application.
2. **Containerization**: Built a Docker image for the application.
3. **Kubernetes Deployment**: Deployed the application to a local Minikube Kubernetes cluster.
4. **Deployment Enhancements**:
   - Configured replicas for high availability.
   - Set resource limits and requests for CPU and memory usage.
   - Configured liveness and readiness probes for health checks.
5. **Helm Chart Creation**:
   - Packaged the Kubernetes manifests into a Helm chart for easy management.
   - Successfully deployed the application using Helm.

## Running the Application
1. **Deploy the Application**:
   ```bash
   helm install p2-nodejs-app ./p2-nodejs-app
