# AWS-VPC
AWS VPC setup in production Eviornment

About the Project
 This example demostrates how to create a VPC that you can use for a service in production enviorment.

To improve the resilience, I deployed the services in 2 Availablity Zones, by using an auto-scaling group and an Application-Loadbalancer.
For additional security, I deployed the server in private subnet. The server recieves request through the loadbalancer and the server can connect to the internet through the NAT Gateway'
To improve resilience, I have deployed the NAT gateway in both Availability zones.


