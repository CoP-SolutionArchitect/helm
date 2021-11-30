# helm

helm add repo https://raw.githubusercontent.com/CoP-SolutionArchitect/helm/main/
helm install \
    --set argo-cd.server.ingress.enabled=false      \
    --set argo-cd.server.ingressGrpc.enabled=false       \
  
    argo-cd my-argo-cd 

https://argo.127-0-0-1.nip.io/
helm repo list 
help add repo name URL
helm create name 
helm dep update ./kafka
helm package ./my-dapr
helm repo index --url https://raw.githubusercontent.com/CoP-SolutionArchitect/helm/main/ .