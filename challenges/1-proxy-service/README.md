# Challenge 1 - proxy a service

A hello world service has been deployed in your cluster. The service is called `hello-world-service` and is available in the namespace `app`. The service is exposed on port `80` (so it's URL is http://hello-world-service.app from within the cluster).

Your challenge now to is expose this service to the outside world using Kong. On the exposed proxy it should then be accessible under the path `/YOUR_USERNAME`. Also please keep in mind to use your unique username in the service and route names.

For example, if your username is `johndoe`, the service should be accessible under the path `/johndoe`.

## Useful links

* [Services and routes](https://docs.konghq.com/gateway/latest/get-started/services-and-routes/#main)
* [decK gateway sync](https://docs.konghq.com/deck/latest/reference/deck_gateway_sync/)
* [Ingress controller](https://docs.konghq.com/kubernetes-ingress-controller/latest/get-started/services-and-routes/) - there are two options GatewayAPI and Ingress - all examples provided in the solutions of this hackathon use Ingress

## Solution

For both [ingress controller](../../ingress-controller/1-proxy-service/) as well as [decK](../../deck/1-proxy-service/) there is a solution available following the links

You should try first without looking at the solution. If you get stuck, you can always come back here.