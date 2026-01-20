# kubernetes
A beginner-friendly Kubernetes repository covering core concepts, kubectl commands, deployments, services, and real-world examples for learning and practice.

------- Step-1 Ingress-Nginx Installation---------
kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v1.9.6/deploy/static/provider/cloud/deploy.yaml

-----Step 2: Verify Installation------
kubectl get ns

----- Step-3 Check ingress controller pod-----
kubectl get pods -n ingress-nginx
