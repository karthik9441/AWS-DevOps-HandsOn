RDS + EC2 within VPC
This project demonstrates how to connect an EC2 instance to a MySQL RDS database within a VPC, ensuring secure and private communication.

Steps:
Create Custom VPC:
Set up a VPC with both public and private subnets.

Launch EC2 Instance:
Deploy an EC2 instance in the public subnet for database access.

Launch RDS Instance:
Deploy MySQL RDS in the private subnet to keep it isolated from the public internet.

Connect EC2 to RDS:
Use MySQL CLI on EC2 to connect securely to the RDS instance within the VPC.

Learnings:
Understanding VPC structure with public and private subnets.

Managing RDS and EC2 security using security groups and IAM roles.

Ensuring secure, private database connectivity within a VPC.
