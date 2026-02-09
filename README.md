This repository contains working codes for CloudFormation Templates in AWS Free Tier.

##########
CFTwithALB.json - This code Creates key pairs, Security Groups with port 80 Allow, two EC2 instances in different AZ (subnets) with Web server with index page giving Webserver1 and Webserver2 as output with Automatic Load Balancers.  Writes the DNS name of the ALB to the output.

##########
ec2-httpd-index.json - This code creates EC2 instance and installs Webserver (httpd) with an index.html file with purpose.  Key pair and the Security group are precreated in this scenario.

##########



