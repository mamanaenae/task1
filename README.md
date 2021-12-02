# task1
- create a VPC in two AZ's for high availabily
- in each AZ, create 1 private SN and 1 public SN
- on each Public SN, have a NAT gateway that will allow the resources in the Private SN to access internet
- have a Internet gateway associated with the VPC to access outside internet
- create two route tables and associate one with the private SN and the other one with public SN
Allocate a EIP to the NAT-GW