# Questions/Answers

# Q1. What does 0.0.0.0/0 means?
Solu- The address 0.0.0.0 generally means “any address”. This is a default route in IPv4 and is an address that contains all other ip addresses.

# Q2. What is NAT Gateway?
Solu- A NAT gateway is a Network Address Translation (NAT) service. You can use a NAT gateway so that instances in a private subnet can connect to services outside your VPC but external services cannot initiate a connection with those instances. A NAT device forwards traffic from the instances in the private subnet to the internet or other AWS services, and then sends the response back to the instances while Internet Gateway is used to allow resources in your VPC to access internet.

# Q3. What is Subnet and is it zone specific?
Solu- A subnet is a range of IP addresses in your VPC. You can launch AWS resources, such as EC2 instances, into a specific subnet. When you create a subnet, you specify the IPv4 CIDR block for the subnet, which is a subset of the VPC CIDR block. Each subnet must reside entirely within one Availability Zone and cannot span zones. 
