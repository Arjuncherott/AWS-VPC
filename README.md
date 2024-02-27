# AWS-VPC for production enviornment

About the Project
 This example demostrates how to create a VPC that you can use for a service in production enviorment.

To improve the resilience, I deployed the services in 2 Availablity Zones, by using an auto-scaling group and an Application-Loadbalancer.
For additional security, I deployed the server in private subnet. The server recieves request through the loadbalancer and the server can connect to the internet through the NAT Gateway'
To improve resilience, I have deployed the NAT gateway in both Availability zones.

![vpc-example-private-subnets](https://github.com/Arjuncherott/AWS-VPC/assets/127583316/d029423d-1620-4849-b1f0-4bc456f248e1)
