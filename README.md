# Kubernetes Minikube Demo

This project demonstrates how to deploy and manage a simple application using Kubernetes locally with Minikube.

## Tools Used
- Minikube
- kubectl
- Docker

## Steps

1. Start Minikube:
   ```bash
   minikube start
   ```

2. Deploy the app:
   ```bash
   kubectl apply -f deployment.yaml
   ```

3. Expose the app:
   ```bash
   kubectl apply -f service.yaml
   ```

4. Check pods and services:
   ```bash
   kubectl get pods
   kubectl get services
   ```

5. Access the app:
   ```bash
   minikube service nginx-service
   ```

6. Scale the deployment:
   ```bash
   kubectl scale deployment nginx-deployment --replicas=4
   ```

7. Describe pods or view logs:
   ```bash
   kubectl describe pod <pod-name>
   kubectl logs <pod-name>
   ```

## Screenshots
Add your screenshots in the `screenshots/` folder.

