# Challenge 3 - create an API key

## Solution

In this folder there is a working example in the file [consumer-and-api-key.yaml](./consumer-and-api-key.yaml) which you can apply like this:

```shell
kubectl apply -f consumer-and-api-key.yaml
```

(the key-auth plugin already has been configured in the previous challenge and does not need to be updated)

🚨 remember to change all occurances of `xxxxxx-your-username` to your actual username like `johndoe` before applying the file. This includes the base64 encoded apikey in the secret!