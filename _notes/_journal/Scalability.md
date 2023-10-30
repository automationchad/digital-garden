Easiest way to scale a system is vertically. 

A user accesses a single API, you just put it on a faster server.

Example of vertical scaling: You upgrade your machine from 4GB of ram to 16GB.

Vertical scaling approach doesn't work for large scaling because there's a limit to how fast a server we can buy.

1M requests per second is hard to handle on a single node.

Horizontal scaling is where we can distribute the API.

Need a load balancer that will accept all the requests and route them to the API with availablity. 

How do you scale the load balancer?

APIs now have to be stateless. 

