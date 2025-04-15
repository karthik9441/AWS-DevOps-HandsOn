RDS + EC2 within VPC
This project demonstrates how to securely connect an EC2 instance to a MySQL RDS database inside a custom VPC. The setup ensures secure communication between EC2 and RDS through private networking.

Steps Taken:
Custom VPC Setup:

Created a VPC with public and private subnets to isolate the RDS instance for security.

EC2 Instance Launch:

Launched an EC2 instance in the public subnet to act as the access point for the database.

Configured security groups to allow communication from the EC2 to the RDS.

RDS Instance Setup:

Created an RDS MySQL instance in the private subnet to avoid exposure to the internet.

Enabled IAM roles and policies for secure access.

Database Connectivity:

Used MySQL CLI on the EC2 instance to connect to the RDS instance privately.

Verified secure communication within the VPC without needing public IPs.

Key Learnings:
VPC Networking: Understanding how private and public subnets work within a VPC for secure architecture.

RDS and EC2 Security: Setting up security groups, IAM roles, and private communication for safe data access.

Best Practices: Ensuring that the database remains isolated within the private subnet while maintaining efficient access from EC2.
