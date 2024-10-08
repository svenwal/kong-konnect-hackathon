# Challenge 2 - enable key authentication

The service create in [challenge 1](../1-proxy-service/README.md) is now exposed to the outside world. However, we want to secure it with an API key. This means that only requests that include a valid API key should be allowed to access the service.

Your challenge is to enable API key based authentication for the route you created in previous step.

## Useful links:

* [Key Authentication plugin](https://docs.konghq.com/hub/kong-inc/key-auth/how-to/basic-example/)

Each plugin's documentation has configuration examples - use the tab for `Kubernetes` (ingress controller) or `Declarative` to get example YAML files.

![Getting example YAML](../../images/plugin-examples.jpeg)

## Solution

For both [ingress controller](../../ingress-controller/2-enable-key-auth/) as well as [decK](../../deck/2-enable-key-auth/) there is a solution available following the links

You should try first without looking at the solution. If you get stuck, you can always come back here.