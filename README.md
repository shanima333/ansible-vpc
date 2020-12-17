# Ansible - To create an VPC , Subnets (Both Private & Public), Security group & EC2

Playbook to create 
 - VPC 
 - 4 Subnets 
      2 public 
      2 Private
 - Security groups 
 - Bastion Server
 - Webserver

##Files

  -  ec2.vars
  - vpc_new.yaml
 
#  ec2.vars
All variables declared on this file

### 12 tasks
  -  Create a new ec2 VPC
  - Create ec2 vpc internet gateway
  - Create ec2 vpc subnet1
  - Create ec2 vpc subnet2
  - Create ec2 security group for bastion
  - create ec2 vpc private subnet
  - create ec2 vpc private subnet2
  - Create ec2 VPC public subnet route table
  - Create ec2 VPC private subnet route table
  - Create a new EC2 key pair
  - Create bastion server
  - Create webserver server

There should be a key folder under the working directory to store the newly created keys.
