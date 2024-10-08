# Challenge 5 - apply rate limit

In [challenge 4](../4-attach-acl/README.md) you have enforced access control list enforcement for authorization. In this challenge you will apply a rate limit to the route you created in the previous step.

Apply the rate limiting advanced plugin to the route and limit the requests to 3 requests per minute.

Make 4 or more calls and see being denied with a `429` status code.