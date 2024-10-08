# Challenge 1 - proxy a service

A hello world service has been deployed in your cluster. The service is called `hello-world-service` and is available in the namespace `app`. The service is exposed on port `80` (so it's URL is http://hello-world-service.app from within the cluster).

Your challenge now to is expose this service to the outside world using Kong. On the exposed proxy it should then be accessible under the path `/YOUR_USERNAME`. Also please keep in mind to use your unique username in the service and route names.

For example, if your username is `johndoe`, the service should be accessible under the path `/johndoe`.

## Solution

For both [ingress controller](../../ingress-controller/1-proxy-service/) as well as [decK](../../deck/1-proxy-service/) there is a solution available following the linkgs

You should try first without looking at the solution. If you get stuck, you can always come back here.