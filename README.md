# helm

helm add repo https://raw.githubusercontent.com/CoP-SolutionArchitect/helm/main/
helm install \
    --set my-argo-cd.server.ingress.hosts={argo.137-184-240-69.nip.io}      \
    --set my-argo-cd.server.ingress.hosts=argo.137-184-240-69.nip.io        \
    --set my-argo-cd.server.ingressGrpc.hosts={argo.137-184-240-69.nip.io}  \
    --set my-argo-cd.server.ingressGrpc.hostname=argo.137-184-240-69.nip.io  \
    argo-cd my-argo-cd 


helm repo list 
help add repo name URL
helm create name 
helm dep update ./kafka
helm package ./my-dapr
helm repo index --url https://raw.githubusercontent.com/CoP-SolutionArchitect/helm/main/ .