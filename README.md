# Deployment of Prometheus-and-grafana-on-kubernetes

Grafana Password Retrive
```
kubectl get secret prometheus-grafana -n <namespace_name> -o jsonpath="{.data.admin-password}" | base64 --decode ; echo
```
