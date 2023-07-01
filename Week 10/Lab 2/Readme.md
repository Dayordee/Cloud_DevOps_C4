# Working with RDS in AWS
## Tasks:

Create an Amazon VPC for use with a DB instance Create a VPC with private and public subnets and multiple subnets Create a VPC security group for a public web server Create a VPC security group for a private DB instance Create a DB subnet group Performn Clean up actions

NB: If you fail to perform clean up actions, costs are usually incurred.

Here is the framework we followed
![Alt text](../../images/Screenshot%20(1239).png)


1. We created an Amazon VPC for use with a DB instance and an EC2 instance
![Alt text](../../images/Screenshot%20(1240).png)
![Alt text](../../images/Screenshot%20(1241).png)


2. We created a VPC with private and public subnets and multiple subnets to launch both our webserver and the DB instance, created a VPC security group for a public web server and also created a security group for a private DB instance

![Alt text](../../images/Screenshot%20(1240).png)
![Alt text](../../images/Screenshot%20(1241).png)
![Alt text](../../images/Screenshot%20(1242).png)
![Alt text](../../images/Screenshot%20(1243).png)
![Alt text](../../images/Screenshot%20(1244).png)

and created a DB subnet group


We now launched an Ec2 instance to the public subnet
![Alt text](../../images/Screenshot%20(1245).png)


and launched a a DB instance into the private subnet

![Alt text](../../Week%2010/Lab%202/images/Screenshot%202023-06-25%20at%209.02.59%20PM.png)
![Alt text](../../Week%2010/Lab%202/images/Screenshot%202023-06-25%20at%209.36.34%20PM.png)
![Alt text](../../Week%2010/Lab%202/images/Screenshot%202023-06-25%20at%209.36.58%20PM.png)
And performed clean up









Guide:

https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/TUT_WebAppWithRDS.html

https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/CHAP_Tutorials.