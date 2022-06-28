# kubernetes-argocd

Continuous Deployment has  been managed well within the Kubernetes architecture along with ArgoCD and Minikube cluster

##### To get help with the ArgoCD, follow this link:
https://argo-cd.readthedocs.io/en/stable/getting_started/

##### To access the ArgoCD UI, do the following

kubectl port-forward -n argocd svc/argocd-server 8081:443

##### Please note: Need to forward the port to access the service

kubectl port-forward -n ptc svc/hello-ptc-service 8080:8080
