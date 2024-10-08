# Challenge 5 - apply rate limit

In [challenge 4](../4-attach-acl/README.md) you have enforced access control list enforcement for authorization. In this challenge you will apply a rate limit to the route you created in the previous step.

Apply the rate limiting advanced plugin to the route and limit the requests to 3 requests per minute.

Make 4 or more calls and see being denied with a `429` status code.

## Useful links

* [Rate limiting advanced plugin](https://docs.konghq.com/hub/kong-inc/rate-limiting-advanced/)

Each plugin's documentation has configuration examples - use the tab for `Kubernetes` (ingress controller) or `Declarative` to get example YAML files.

![Getting example YAML](../../images/plugin-examples.jpeg)

## Solution

For both [ingress controller](../../ingress-controller/5-apply-rate-limit/) as well as [decK](../../deck/5-apply-rate-limit/) there is a solution available following the links

You should try first without looking at the solution. If you get stuck, you can always come back here.