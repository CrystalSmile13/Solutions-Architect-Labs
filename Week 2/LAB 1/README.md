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

i clicked on aws management console and i clicked on create vpc **vpc-0488f9adca83b20a0 with private subnet **00125b6946fc1cc72 and public subnet **06fed634934b85b99


**create two route table and associate each one to each subnets
i created two route table rtb-03e8bd869a2d52e57 for private subnet **00125b6946fc1cc72 and route table 2 rtb-02bc0b825f1a0abe1 to public subnet **06fed634934b85b99  .


**Attach an internet gateway to the VPC and a NAT gateway to the private subnet.

i created internet gateway **igw-0dbb3f44c8dccf130 attached to the vpc 0488f9adca83b20a0 and i created NAT gateway **nat-0d3214db7c6328ed8 to a private subnet  **00125b6946fc1cc72



**5. Lauch a Linux instance into this VPC and attach the subnet
i clicked on ec2 and launch instances i-0a37d5c6c5fceaed2 which was attached to the vpc **vpc-0488f9adca83b20a0 and public subnet  **06fed634934b85b99 was attached to it.

**6. Test the network connectivity

I tested the internet gateway **igw-0dbb3f44c8dccf130 on the browser for connectivity and it was successfully connnected.



