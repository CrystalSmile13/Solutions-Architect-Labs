Task: Create a nondefault VPC using AWS CLI

1. Open your CLI and run a configuration setting
2. Lauch a VPC 
3. Create two subnets (a public and a private subnet)
4. Make your subnet public by creating and attaching an internet gateway
5. Create a security group and add a SSH access from anywhere
6. Lauch an instance into your subnet 
7. Clean Up

https://docs.aws.amazon.com/vpc/latest/userguide/vpc-subnets-commands-example.html

https://docs.aws.amazon.com/vpc/latest/userguide/vpc-subnets-commands-example-ipv6.html

https://docs.aws.amazon.com/vpc/index.html





I created a VPC with a 10.0.0.0/16 CIDR block,
copied the ID; vpc-04cff87b6dccf6c15, use it to create subnet
created anothder subnet using the same vpc

I made the subnet a public subnet
by creating  an internet gateway, used the ID of the internet gateway; igw-0288114c911204f21 to attach internet gateway command,
created a custom route table
