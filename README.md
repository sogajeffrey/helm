# Helm Repository 

## Charts
* Wyze Bridge - Creates a secret, deployment and service for wyze bridge
* secure-ingressroute - Creates a Cert manager certificate and Traefik Ingressroute 
* cloudflare-ddns - Creates a Secret, configmap, and deployment for https://github.com/oznu/docker-cloudflare-ddns 

## To Use 

```
helm repo add jeffhelm https://helm.jeffreyjsu.com
helm search repo jeffhelm
```