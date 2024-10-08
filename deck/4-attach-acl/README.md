# Solution challenge 4 - attach ACL

In this folder there is a working example in the two files [key-auth-acl.yaml](./key-auth-acl.yaml) and [consumer-and-key-and-group.yaml](././consumer-and-key-and-group.yaml) which you can apply like this:

```shell
deck gateway sync --konnect-addr "https://eu.api.konghq.com" --konnect-control-plane-name "gateway" --konnect-token $KONNECT_TOKEN --select-tag $DECK_USERNAME key-auth-acl.yaml consumer-and-key-and-group.yaml
```

Note: in the example we have split the config into two YAML files - you could also merge them into one file.