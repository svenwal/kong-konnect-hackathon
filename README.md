# Kong Konnect Hackathon

This repository hosts all ressources for the Kong Konnect Hackathon. This includes a README of general instructions (this file) and ressources to complete the example challenges both using the automation with decK as well as with the Kong Ingress Controller.

## Hackathon setup

An AKS cluster has been provisioned for you to use during the hackathon. You should already have credentials to access the cluster with `kubectl` as well as well as a login to Kong Konnect at [https://cloud.konghq.com/](https://cloud.konghq.com/). The AKS cluster has been pre-configured with both an Kong Ingress Controller and the Kong Gateway.

## The example challenges

The following use cases are covered in the example challenges for both ingress controller and decK:

- Proxy a service
- Enforce an api key based authentication
- Creating an api key and associating it with a consumer
- Enforce access control list enforcement for authorization
- Applying a rate limit

## Getting started

### Conventions

In order to avoid conflicts between participants, please use a unique username in services, routes and consumers. This username should be all lowercase and have no special characters or spaces. For example, if your name is John Doe, you could use `johndoe` as your username.

### Using the Kong Ingress Controller

The Kong Ingress Controller is already installed in the cluster. Please validate you have access to it using `kubectl get nodes` and let us know if you have any issues.

You can use the provided ingress resources in the `ingress-controller` directory to complete the challenges. You can apply the resources using `kubectl apply -f <resource-file>`. Detailed instructions are provided in the README.md file in the `ingress-controller` directory.

### Using decK

decK is a tool to manage Kong configuration as code. You can use decK to complete the challenges. You can find the decK configuration in the `deck` directory. Detailed instructions are provided in the README.md file in the `deck` directory.

### Using user interface

This is the most lightweight but also least challenging way to complete the challenges. You can access the Kong Konnect UI at the following URL: [https://cloud.konghq.com/](https://cloud.konghq.com/). You should have received credentials to access the UI. If you have not, please let us know.