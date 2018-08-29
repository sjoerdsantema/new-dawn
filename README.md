# nestedstacks
Set of 1 parent stack with 3 nested stacks (rds, skeleton, app/ec2)

This template creates:
- 1 VPC
- Bastion host (in autoscaling group)
- Autoscaling group with apache servers (2 AZ's, 2 private subnets)
- NAT gateway
- RDS cluster
- ELB
