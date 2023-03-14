# Lab 3: Manage Packages and Services on a Linux VM (Azure or AWS)


1. Create a Linux VM
2. Install the Apache Web Server
3. Start the service status via command line
4. Investigate the service status via command line
5. Stop the service

1. I created a Linux Vm
![Alt text](../../images/Screenshot%20(984).png)

2. I installed the Apache Web server, I bootstrapped into the virtual machine as described in the lab
![Alt text](../../images/Screenshot%20(986).png)
3. I started the service status via command line
![Alt text](../../images/Screenshot%20(990).png)
![Alt text](../../images/Screenshot%20(991).png)
4. I was able to investigate the service status via command line and 'grep ' to know the specific status of the unit or services enable and grepped static to know the services static 
![Alt text](../../images/Screenshot%20(992).png)
![Alt text](../../images/Screenshot%20(994).png)
![Alt text](../../images/Screenshot%20(995).png)
5. I stop the service and shutdown the virtual machine and also shutdown the VM
![Alt text](../../images/Screenshot%20(996).png)
![Alt text](../../images/Screenshot%20(996).png)


Challenge: Create a boostrapping script that will install and start this service on new EC2 VMs

Notes:

Install and Configure Apache (Ubuntu)

https://ubuntu.com/tutorials/install-and-configure-apache#1-overview
How to install Apache on RHEL 8 / CentOS 8 Linux

https://linuxconfig.org/installing-apache-on-linux-redhat-8
How to use cloud-init to customize a Linux virtual machine in Azure on first boot

https://docs.microsoft.com/en-us/azure/virtual-machines/linux/tutorial-automate-vm-deployment
Create bootstrap actions to install additional software

https://docs.aws.amazon.com/emr/latest/ManagementGuide/emr-plan-bootstrap.html