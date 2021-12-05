# task1
- Create a VPC in two AZ's for high availabily
- On each AZ, create 1 private SN and 1 public SN
- On each Public SN, have a NAT gateway that will allow the resources in the Private SN to access internet
- Have a Internet gateway associated with the VPC to access outside internet
- Create two route tables and associate one with the private SN and the other one with public SN
Allocate a EIP to the NAT-GW
-   Create a load balancer and place it on the two public subnets that are on different AZ's, Direct the traffic flow from the LB to the auto scaling group. The instences created by ASG are running the an Apache Web Server. 
- This application is configured to span all Availability Zones in the region and is auto-scaled based on the CPU utilization of the web servers. The instances are load balanced with a simple health check against the default web page. 

