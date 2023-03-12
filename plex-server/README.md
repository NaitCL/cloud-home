# plex-server

GitLab : https://github.com/k8s-at-home/charts/tree/master/charts/stable/plex

```
helm repo add k8s-at-home https://k8s-at-home.com/charts/
helm repo update
helm install plex-server k8s-at-home/plex -f plex-values.yml
helm delete plex-server
```

```
kubectl apply -f plex-pv.yaml
k apply -f plex-pv.yaml

kubectl apply -f plex-pvc.yaml
k apply -f plex-pvc.yaml
```
