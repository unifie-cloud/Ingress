# How to add letsencrypt certificates


Install manually [cert-manager](https://cert-manager.io/docs/installation/kubectl/#steps)

```bash
kubectl apply -f https://github.com/cert-manager/cert-manager/releases/download/v1.14.4/cert-manager.yaml
```

Go to service settings tab and ternon 
Please add to the service settings you own email for letsencrypt