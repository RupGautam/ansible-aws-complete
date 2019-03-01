### Variables
All the variables you can change:

```
 vars file for aws-vpc
aws_region: "us-east-1"

#VPC
aws_vpc_cidr: 10.10.0.0/24
aws_vpc_name: "changme"

#Subnet
aws_subnet_name: "changeme"
aws_subnet_cidr: 10.10.0.0/26

#Gateway Name
aws_igw_name: "changeme"
aws_security_group_name: "changeme SG"

#Routing table
aws_route_name: "change table name"

#Tags
aws_ec2_tag: "tag name"

#Path to save key pair
aws_ec2_key_directory: "~/.ssh/aws/"  
aws_keypair_name: "development-key-name"

#ami id 
aws_ami_id: ami-0ac019f4fcb7cb7e6 #ubuntu 16.04
aws_instance_type: t2.micro #changeme
aws_instance_count: 1 #number of instances 

#Key vars
ec2_key_directory: "~/.ssh/aws/"
```