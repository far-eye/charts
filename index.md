# FarEye Helm Repository

![FarEye](assets/logo_login.png)

### This is a generic helm chart repository
* Cluster Role
* Cluster Role Binding
* Config Maps
* Deployment
* Horizontal Pod Autoscalar
* Ingress
* Service
* Service Account
* Jobs
* Cron Jobs

<br>

### How To Use?

###### Add FarEye repository to Helm repos:

```bash
helm repo add fareye-microservices-charts https://far-eye.github.io/charts
```

Copy The `values.yaml` from [here](https://github.com/far-eye/charts/blob/master/helm-chart/values.yaml)

Install the helm chart

```bash
helm install <deployment> -n=<Namespace> fareye-microservices-charts/helm-chart -f values.yaml
```