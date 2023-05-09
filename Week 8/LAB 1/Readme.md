# Working with EBS
## Tasks:

Create an Amazon EBS volume
Attach and mount your volume to an EC2 instance
Create a snapshot of your volume
Create a new volume from your snapshot
Attach and mount the new volume to your EC2 instance
Guide:

https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ebs-volumes.html

https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ebs-attaching-volume.html

1. I created an Amazon EBS volume and also launched a Linux  instance 
![Alt text](../../images/Screenshot%20(1118).png)
![Alt text](../../images/Screenshot%20(1119).png)

2. I attached and mount the volume to an Ec2 instance
![Alt text](../../images/Screenshot%20(1120).png)
![Alt text](../../images/Screenshot%20(1110).png)

3. I connected to my instance, so i can mount my instance
![Alt text](../../images/Screenshot%20(1121).png)
![Alt text](../../images/Screenshot%20(1122).png)

4. I used the 'lsblk' to check the volumes i have attched to the instance
![Alt text](../../images/Screenshot%20(1123).png)

4. I made the 'ext4 /dev/xvdf' file to mount the volume
![Alt text](../../images/Screenshot%20(1124).png)

5. I created the directoy '/mnt/data' which the volume is to be mounted

![Alt text](../../images/Screenshot%20(1125).png)

6. I mounted the volume inside the directory i created 

![Alt text](../../images/Screenshot%20(1126).png)

7. I confirmed the mount by using the list of the volumes

![Alt text](../../images/Screenshot%20(1127).png)

8. I took a snapshot of the volume and created a volume from the snapshot i took
![Alt text](../../images/Screenshot%20(1128).png)
![Alt text](../../images/Screenshot%20(1129).png)

9. I made another directory for the volume 'mnt/data2' which is different from the previous directory
![Alt text](../../images/Screenshot%20(1132).png)

10. I confirmed the mount with the list mount command 'df'

![Alt text](../../images/Screenshot%20(1133).png)