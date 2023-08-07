# Creating and Pushing Container Images to ECR
In this lab, you will containarize any application of your choice and push the image to AWS ECR(private regsitry) 
## Tasks: 
- Create any application in any programming language of your choice (*it can be as simple as **hello world***)
- Create a `Dockerfile` to build the application
- Build the application locally using `docker build` commands and tag the image appropriately
- Run the image locally to ensure it's running well
- Push the image to AWS ECR (**You will need to login to AWS ECR**)


### Guides:
[Containarize an application](https://docs.docker.com/get-started/02_our_app/)
<br/>
[Pushing Images to AWS ECR](https://docs.aws.amazon.com/AmazonECR/latest/userguide/docker-push-ecr-image.html)


I made use of an amazon linux virtual machine 
![Alt text](<../imgs/Screenshot (19).png>)

I installed docker on it
![Alt text](<../imgs/Screenshot (20).png>)
![Alt text](<../imgs/Screenshot (21).png>)

I started the docker seervice
![Alt text](<../imgs/Screenshot (22).png>)

I made sure docker service was running
![Alt text](<../imgs/Screenshot (23).png>)

I created the .py file for my app and also created a dockerfile
![Alt text](<../imgs/Screenshot (24).png>)
![Alt text](<../imgs/Screenshot (25).png>)


I built my app using the docker build command

![Alt text](<../imgs/Screenshot (26).png>)
![Alt text](<../imgs/Screenshot (28).png>)
![Alt text](<../imgs/Screenshot (29).png>)
![Alt text](<../imgs/Screenshot (30).png>)
![Alt text](<../imgs/Screenshot (31).png>)


![Alt text](<../imgs/Screenshot (34).png>)

I ran my app on port 80:80
![Alt text](<../imgs/Screenshot (36).png>)

I logged into my Amazon ECR using the cli 
![Alt text](<../imgs/Screenshot (37).png>)

I created A repository
![Alt text](<../imgs/Screenshot (38).png>)
![Alt text](<../imgs/Screenshot (39).png>)
I pushed my containerized
![Alt text](<../imgs/Screenshot (41).png>)


