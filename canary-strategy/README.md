# installation
```
helm install nginx-release ./canary-strategy
```
# status
```
helm status nginx-release
```
# show list
```
helm list
```
# upgrade
```
helm upgrade nginx-release ./nginx-chart
```
# uninstall
```
helm uninstall nginx-release
```

# for override value
```
helm install nginx-release ./nginx-chart -f my-values.yaml
```

```
helm install nginx-release ./nginx-chart --set nginx.replicas.canary=2
```
