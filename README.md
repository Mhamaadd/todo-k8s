# ✅ Part 4: Kubernetes + ArgoCD (Continuous Delivery)

☸️ **Kubernetes Setup:**  
Installed k3s (lightweight Kubernetes) on the local machine.

🔐 **Dashboard Access:**  
kubectl port-forward svc/argocd-server -n argocd 8080:443

🔁 **CD Pipeline:**
A separate GitHub repo contains the Kubernetes manifests:
- deployment.yaml, service.yaml
- ArgoCD continuously watches the repo and syncs changes automatically

🌍 **Access the App:**
kubectl port-forward svc/todo-app-service 8081:80  
Open: http://localhost:8081

🔗 (Main Repo)
https://github.com/Mhamaadd/devops-todo-app
