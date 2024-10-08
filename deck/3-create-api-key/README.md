# Solution challenge 3 - create an API key

In this folder there is a working example in the two files [key-auth.yaml](./key-auth.yaml) and [consumer-and-key](./consumer-and-key.yaml) which you can apply like this:

```shell
deck gateway sync --konnect-addr "https://eu.api.konghq.com" --konnect-control-plane-name "gateway" --konnect-token $KONNECT_TOKEN --select-tag $DECK_USERNAME key-auth.yaml consumer-and-key.yaml
```

Note: in the example we have split the config into two YAML files - you could also merge them into one file.