# Working with Elastic Load balancing
## Tasks: 

Using AWS CLI,

Create an Application Load Balancer
Create a Network Load Balancer
Create a Gateway Load Balancer
Create a Classic Load Balancer
Perform clean up operations
NB: You need to launch at least two instances to do this.

Guide https://docs.aws.amazon.com/elasticloadbalancing/latest/userguide/load-balancer-getting-started.html

Firstly, I launched to two instances with i will be running my Load Balancers;  
![Alt text](../../images/Screenshot%20(1175).png)
1. I created an Application load balancer
In this I used two availablity zones, A target group and 5 security groups

![Alt text](../../images/Screenshot%20(1177).png)
![Alt text](../../images/Screenshot%20(1178).png)
![Alt text](../../images/Screenshot%20(1179).png)


2. I created a Network Load Balancer 
![Alt text](../../images/Screenshot%20(1180).png)
![Alt text](../../images/Screenshot%20(1181).png)

3. I created a gateway Load Balancer
![Alt text](../../images/Screenshot%20(1183).png)
![Alt text](../../images/Screenshot%20(1184).png)

4. Creating the classic Load load Balancer took me to the Old console because it still uses the old console because it's an older version of the Load Balancer, it has been around for so many years before the arrival of the network, application and gateway load balancers.
![Alt text](../../images/Screenshot%20(1185).png)
![Alt text](../../images/Screenshot%20(1186).png)
![Alt text](../../images/Screenshot%20(1188).png)

After these, I cleaned up
![Alt text](../../images/Screenshot%20(1182).png)
![Alt text](../../images/Screenshot%20(1189).png)
![Alt text](../../images/Screenshot%20(1190).png)
![Alt text](../../images/Screenshot%20(1191).png)





