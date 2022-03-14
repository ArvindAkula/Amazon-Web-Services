# Amazon-Web-Services

Amazon VPC (Virtual Priviate Cloud) - Build using VPC

Amazon EC2 Instance - We will host Applications on Amazon EC2(Elastic Compute Cloud) Instance this offers Virtual machines on AWS

- This application will be built in a private network using Amazon Virtual Private Cloud or VPC. 

- We will host the application's backend code on Amazon Elastic Compute Cloud or EC2, which is a service that essentially offers virtual machines on AWS. 
 
-The data will be stored in a database which will also live inside of this network. And this will be hosted using a service called Amazon Relational Database Service or RDS, or we might be hosting it on Amazon DynamoDB. 
 
-The images for the employees will be stored using the object storage service Amazon Simple Storage Service, or what we call S3, which will allow the unlimited storage of any file type like the images in this example. So these are the basic building blocks of our application, but we're not done yet.

-We are also going to use Amazon CloudWatch for monitoring the solution. And we want to ensure that our application is scalable and fault-tolerant. So I'm also going to add an Elastic Load Balancer here which will distribute the traffic across the EC2 instances. 

-We will also add Amazon EC2 Auto Scaling to this diagram, so that way our solution can scale out with demand and scale in when demand decreases.

-For security and identity, we will be using Amazon Identity and Access Management or IAM. 

![image](https://user-images.githubusercontent.com/12073210/158121184-b9f8109b-1dce-4f87-ac11-b3c09821d1f3.png)

