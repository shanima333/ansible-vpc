# Ansible - To create an VPC , Subnets, Security group & EC2

Playbook to create a VPC 2 Subnets & one Security group and configure an EC2 with the created VPC and SG.

##Files

  -  ec2.vars
  - vpc_ec2.yaml
 
#  ec2.vars
All variables declared on this file

### 8 tasks
  -  Create a new ec2 VPC
  - Create ec2 vpc internet gateway
  - Create ec2 vpc subnet1
  - Create ec2 vpc subnet2
  - Create ec2 security group
  - Create ec2 VPC public subnet route table
  - Create a new EC2 key pair
  - Create EC2 instances

There should be a key folder under the working directory to store the newly created keys.
