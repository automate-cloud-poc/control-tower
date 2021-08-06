# Control Tower

This is the main resource for:
* manage all apps deploy configurations
* manage all apis deploys / releases 

first login:

* kubectl port-forward svc/argocd-server -n argocd 8080:443
* kubectl -n argocd get secret argocd-initial-admin-secret -o jsonpath="{.data.password}" | base64 -d
