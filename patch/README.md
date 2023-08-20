# https://codefresh.io/blog/argo-cd-application-dependencies/
kubectl patch cm/argocd-cm --type=merge --patch-file patch-argocd.yaml

