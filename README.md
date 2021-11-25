# helm

helm add repo https://raw.githubusercontent.com/CoP-SolutionArchitect/helm/main/
helm install \
    --set my-argo-cd.server.ingress.hosts={argo.137-184-240-69.nip.io}      \
    --set my-argo-cd.server.ingress.hosts=argo.137-184-240-69.nip.io        \
    --set my-argo-cd.server.ingressGrpc.hosts={argo.137-184-240-69.nip.io}  \
    --set my-argo-cd.server.ingressGrpc.hostname=argo.137-184-240-69.nip.io  \
    argo-cd my-argo-cd 