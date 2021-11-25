# helm

helm add repo https://raw.githubusercontent.com/CoP-SolutionArchitect/helm/main/
helm install argo-cd my-argo-cd \
    --set my-argo-cd.server.ingress.hosts={argo.137-184-240-69.nip.io} 