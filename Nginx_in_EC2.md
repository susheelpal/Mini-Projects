# Problem statement
## Create an Amazon EC2 Instances with the following parameters

- Region: N. Virginia (us-east-1)
- Name: Ubuntu-VM-Server
- Add additional tags: Instances, Volumes, Network Interfaces
- AMI: Ubuntu Server 20.04 LTS (HVM), SSD Volume Type
- Architecture: 64-bit (x86)
- Instance Type: t2.micro
- Key pair: Create new key pair
- VPC: Default VPC
- Security Group: Create security group
- Security group name: Ubuntu-VM-Server
- Inbound rule: Allow SSH, HTTP
- Source: 0.0.0.0/0
- Disk Size: 30 GB
- Volume Type: General Purpose SSD (gp2)
- Number of instances: 1
- Install Nginx web server in Ubuntu-VM-Server
- Command: sudo apt update; sudo apt install nginx -y
- Visit http://{your-ec2-ip-address} and ensure that Nginx web server is running successful.
