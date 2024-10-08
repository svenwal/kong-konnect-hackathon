# Challenge 1 - proxy a service

A hello world service has been deployed in your cluster. The service is called `hello-world-service` and is available in the namespace `app`. The service is exposed on port `80`.

```shell
> kubectl get services -n app   

NAME                  TYPE       CLUSTER-IP      <none>        80:12345/TCP   79m
hello-world-service   NodePort   1.2.3.4    <none>        80:12345/TCP   49s
```

Your challenge now to is expose this service to the outside world using Kong. On the exposed proxy it should then be accessible under the path `/YOUR_USERNAME`. Also please keep in mind to use your unique username in the service and route names.

For example, if your username is `johndoe`, the service should be accessible under the path `/johndoe`.

## Solution

In this folder there is a working example in the file [proxy.yaml](./proxy.yaml) which you can apply like this:

```shell
kubectl apply -f proxy.yaml
```

🚨 remember to change all occurances of `xxxxxx-your-username` to your actual username like `johndoe` before applying the file