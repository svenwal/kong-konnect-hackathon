# Using the ingress controller

## Getting started

The Kong Ingress Controller is already installed in the cluster. Please validate you have access to it using `kubectl get services -n app` and validate you see the `hello-world-service` service.

```shell
> kubectl get services -n app   

NAME                  TYPE       CLUSTER-IP      <none>        80:12345/TCP   79m
hello-world-service   NodePort   1.2.3.4    <none>        80:12345/TCP   49s
```

Let us know if you have any issues.

You can use the provided ingress resources in this directory to complete the challenges. You can apply the resources using `kubectl apply -f <resource-file>`. 

### 🚨 Very important

For the actual syncing of configurations you will use a command like 

```shell
> kubectl apply -f your-file.yaml
```

ALWAYS have unique names for routes, services and plugins in place with you username in them - for example:

```yaml
apiVersion: networking.k8s.io/v1
kind: Ingress
metadata:
  name: hello-world-service-xxxxxx-your-username
(...)
spec:
(...)
      paths:
      - path: /xxxxxx-your-username
(...)
```
 🚨