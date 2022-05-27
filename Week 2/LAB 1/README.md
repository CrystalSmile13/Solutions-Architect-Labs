This task will get you acquainted on how to deploy VPC 


Task 1: Deploy VPC using Management console
1. Launch the AWS Management Console
2. Launch a VPC with one public and one private subnets.
3. Create two route table and associate  each one to each subnets
4. Attach an internet gateway to the VPC and a NAT gateway to the private subnet.
5. Lauch a Linux instance into this VPC and attach the subnet
6. Test the network connectivity
7. Perform clean up actions







For guide, you are check the links below:

https://docs.aws.amazon.com/cli/latest/reference/ec2/

https://docs.aws.amazon.com/cli/latest/reference/ec2/describe-vpcs.html




**launched AWS management console

**launch a VPC with one public and one private subnet:

In the panel, I choose VPC dashboard, launched the VPC wizard, choose VPC
with the IPv4 10.0.0.0/16

on the control panel, I picked the subnets

created a new subnet, selsected the vpc previously created; vpc 1

picked the avaiability zone, IPv4 CIDR block; 10.0.0.0/24

subnet 2
add new subnet

name; private subnet, picked availabilty zone, IPv4 CIDR block 10.0.1.0/24

created the subnets.


**create two route table and associate each one to each subnets

