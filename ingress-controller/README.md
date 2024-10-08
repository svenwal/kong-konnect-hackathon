# Using the ingress controller

## Getting started

The Kong Ingress Controller is already installed in the cluster. Please validate you have access to it using `kubectl get services -n app` and validate you see the `hello-world-service` service.

Let us know if you have any issues.

You can use the provided ingress resources in this directory to complete the challenges. You can apply the resources using `kubectl apply -f <resource-file>`. 