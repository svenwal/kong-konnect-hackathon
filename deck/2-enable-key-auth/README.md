# Solution challenge 2 - enable key authentication

In this folder there is a working example in the file [key-auth.yaml](./key-auth.yaml) which you can apply like this:

```shell
deck gateway sync --konnect-addr "https://eu.api.konghq.com" --konnect-control-plane-name "gateway" --konnect-token $KONNECT_TOKEN --select-tag $DECK_USERNAME key-auth.yaml
```