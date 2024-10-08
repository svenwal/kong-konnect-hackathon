# Challenge 4 - attach an ACL

## Solution

In this folder there is a working example in the files and [key-auth-acl.yaml](./key-auth-acl.yaml) and [consumer-and-api-key-and-acl.yaml](./consumer-and-api-key-and-acl.yaml) which you can apply like this:

```shell
kubectl apply -f key-auth-acl.yaml -f consumer-and-api-key-and-acl.yaml
```

🚨 remember to change all occurances of `xxxxxx-your-username` to your actual username like `johndoe` before applying the file. This includes the base64 encoded apikey and group name in the **two secrets**!