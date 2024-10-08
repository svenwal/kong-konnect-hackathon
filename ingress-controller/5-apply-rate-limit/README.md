# Challeng 5 - apply rate limit

## Solution

In this folder there is a working example in the files and [key-auth-acl-rate-limit.yaml](./key-auth-acl-rate-limit.yaml) and [consumer-and-api-key-and-acl.yaml](./consumer-and-api-key-and-acl.yaml) which you can apply like this:

```shell
kubectl apply -f key-auth-acl-rate-limit.yaml
```
(the consumer already has been configured in the previous challenge and does not need to be updated)

🚨 remember to change all occurances of `xxxxxx-your-username` to your actual username like `johndoe` before applying the file. This includes the base64 encoded apikey and group name in the **two secrets**!