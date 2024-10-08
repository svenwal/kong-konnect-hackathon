# Challange 4 - attach ACL

In [challenge 4](../4-attach-acl/README.md) you have create an api key and have been able to access you service.

This has been a great success and now you want to add more security to your service (currently **all api keys are allowed** as we have "only" done authentication so far). 

You want to make sure that only a certain group of users can access your service - meaning authorization.

For this you apply the ACL plugin on your route and attach your already created consumer to a unique group (like `johndoe_group`).

You can verify your success by trying to access the service with your consumer and afterwards a different consumer and see that you are denied access for the later. For this we have created a second consumer for you with the api key `another_consumer_key`.