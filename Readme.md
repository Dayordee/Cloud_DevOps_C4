# Task: Deploying a Static Web Application using S3 and Cloudfront

## Steps:

1. Create a S3 bucket and give it a unique name
2. During creating, ensure you enable the public access to the bucket objects via the S3 object URL. 
3. Secure the bucket by editting the bucket policy to allow api calls to "Getobject" in the bucket 
Read more via: https://docs.aws.amazon.com/AmazonS3/latest/userguide/add-bucket-policy.html
4. Upload the files in the static website folder to your bucket. NB: Do not upload the folder. Remember, you can play with the static website index html.
5. Configure  the bucket properties to allow for static website hosting
6. Copy the arn generated and keep to use in the cloudfront ditribution creation
7. Test the arn if it is working (You should see your static webpage)
8. Create a cloudfront distribution using the arn you copied. Guide : https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/GettingStarted.SimpleDistribution.html
9. Use the cloudfront DNS to check if your static webpage has been successfully deployed.
10. When done, get the following screenshort
    i. The S3 arn showing your webpage is deployed
    ii. The Cloudfront DNS showing your webpage
    iii. A screenshoot of successful upload of files to s3 bucket
11. Created a folder in your capstone project 1, name it, "image,". Upload your screenshots and push to your git repo. 
12. Perform clean up operations.

Good Luck!

Note: This project was done by a triad which is TRIAD 7
1.  We created a S3 bucket giving it a unique (triad7-capstoneproject) 
![Alt text](../image/Screenshot%20(1214).png)

2   During creating, we enabled the public access to the bucket objects via the S3 object URL.
![Alt text](../image/Screenshot%20(1215).png)
![Alt text](../image/Screenshot%20(1216).png)

3. We Secured the bucket by editing the bucket policy to allow API calls to "Getobject" in the bucket
![Alt text](../image/Screenshot%20(1217).png)
![Alt text](../image/Screenshot%20(1219).png)
![Alt text](../image/Screenshot%20(1220).png)


4. We Uploaded the files in the static website folder to your bucket. We kind of tweaked the site a little bit.
![Alt text](../image/Screenshot%20(1221).png)
![Alt text](../image/Screenshot%20(1222).png)
![Alt text](../image/Screenshot%20(1223).png)

5.  We Configured  the bucket properties to allow for static website hosting
![Alt text](../image/Screenshot%20(1224).png)
![Alt text](../image/Screenshot%20(1225).png)
![Alt text](../image/Screenshot%20(1226).png)

6. We Copied the arn generated to use in the cloudfront ditribution creation
![Alt text](../image/Screenshot%20(1229).png)

7. We Tested the arn to if it is working (We saw our static webpage)
![Alt text](../image/Screenshot%20(1230).png)


8. We Created a cloudfront distribution using the arn we copied.
![Alt text](../image/Screenshot%20(1231).png)
![Alt text](../image/Screenshot%20(1232).png)
![Alt text](../image/Screenshot%20(1233).png)
![Alt text](../image/Screenshot%20(1234).png)

9. We Used the cloudfront DNS to check if the static webpage has been successfully deployed.

So by adding the the path of the  to the homepage of the static website to the DNS of the cloudfront we will get our static website

![Alt text](../image/Screenshot%20(1237).png)



11. I Created a folder in the capstone project 1, named it, "image,".  and I Uploaded the screenshots and push to your git repo.


12. We Performed clean up operations so we would not be billed
![Alt text](../image/Screenshot%20(1238).png)





