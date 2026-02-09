This repository contains working codes for CloudFormation Templates in AWS Free Tier.

##########
**ec2-httpd-index.json** - This code creates EC2 instance and installs Webserver (httpd) with an index.html file with purpose.  Key pair and the Security group are precreated in this scenario.

##########
**ec2-httpd-s3.json** - This code creates an EC2 instance, install Webserver and creates a S3 backet.  The security group and Key pair are pre created.

##########
**ec2-kp-sg-ec2-s3-website.json** - This code creates Key pair, Security Group, EC2 instance, install Webserver and also creates S3 bucket with versioning enabled.

##########
**CFTwithALB.json**- This code Creates key pairs, Security Groups with port 80 Allow, two EC2 instances in different AZ (subnets) with Web server with index page giving Webserver1 and Webserver2 as output with Automatic Load Balancers.  Writes the DNS name of the ALB to the output.

