# Working with Autoscaling group and Load balancer

## Tasks

1. Create a VPC with 4 subnets in 2 avaialbility zones using your most preferred CIDR block
2. Lauch 1 instance using a predefined user data
3. Create a template from the instance.
4. Use this template to configured your elastic load balancer and auto scaling group.
5. The minimum instance you set is 2 and maximum is 5.
6. Take screenshots of compelete steps and attached it in a folder in this lab and name it screenshots
7. Perform clean up operations


Guide:  https://docs.aws.amazon.com/autoscaling/ec2/userguide/create-asg-launch-template.html
https://docs.aws.amazon.com/autoscaling/ec2/userguide/autoscaling-load-balancer.html

1. I created a VPC with 4 subnets in 2 availability zones using preferred CIDR blocks of my choice
![Alt text](../Screenshots/Screenshot%20(1136).png)
![Alt text](../Screenshots/Screenshot%20(1137).png)
![Alt text](../Screenshots/Screenshot%20(1138).png)
![Alt text](../Screenshots/Screenshot%20(1139).png)

2. I also created my Internet gateway, NAT gatway attached them to my to the route table and my VPC  became functional
![Alt text](../Screenshots/Screenshot%20(1140).png)
![Alt text](../Screenshots/Screenshot%20(1141).png)
![Alt text](../Screenshots/Screenshot%20(1149).png)
![Alt text](../Screenshots/Screenshot%20(1150).png)

3. I then create a template from the instance of which i launched in the VPC
![Alt text](../Screenshots/Screenshot%20(1151).png)
![Alt text](../Screenshots/Screenshot%20(1152).png)

4. With this template I configured a load balancer and also an Auto scaling group
![Alt text](../Screenshots/Screenshot%20(1154).png)

Setting configurations for the ASG, the desired instances I want of which Max is 5 and Min is 2

![Alt text](../Screenshots/Screenshot%20(1160).png)
![Alt text](../Screenshots/Screenshot%20(1161).png)

5. Here are my screenshots in the folder of this lab of which I attached

6.I cleaned to avoid billing

![Alt text](../Screenshots/Screenshot%20(1162).png)
![Alt text](../Screenshots/Screenshot%20(1163).png)
