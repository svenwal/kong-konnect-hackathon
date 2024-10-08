# Solution challenge 1 - proxy a service

In this folder there is a working example in the file [proxy.yaml](./proxy.yaml) which you can apply like this:

```shell
deck gateway sync --konnect-addr "https://eu.api.konghq.com" --konnect-control-plane-name "gateway" --konnect-token $KONNECT_TOKEN --select-tag $DECK_USERNAME proxy.yaml
```