# Challange 4 - attach ACL

In [challenge 4](../4-attach-acl/README.md) you have create an api key and have been able to access you service.

This has been a great success and now you want to add more security to your service (currently **all api keys are allowed** as we have "only" done authentication so far). 

You want to make sure that only a certain group of users can access your service - meaning authorization.

For this you apply the ACL plugin on your route and attach your already created consumer to a unique group (like `johndoe_group`).

You can verify your success by trying to access the service with your consumer and afterwards a different consumer and see that you are denied access for the later. For this we have created a second consumer for you with the api key `another_consumer_key`.

## Useful links

* [ACL plugin](https://docs.konghq.com/hub/kong-inc/acl/how-to/basic-example/)
* Hint: your previously created consumer needs to be added to an ACL in addition to having an api key.

Each plugin's documentation has configuration examples - use the tab for `Kubernetes` (ingress controller) or `Declarative` to get example YAML files.

![Getting example YAML](../../images/plugin-examples.jpeg)

## Solution

For both [ingress controller](../../ingress-controller/4-attach-acl/) as well as [decK](../../deck/4-attach-acl/) there is a solution available following the links

You should try first without looking at the solution. If you get stuck, you can always come back here.