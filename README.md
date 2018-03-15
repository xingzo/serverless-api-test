# ![](https://xingzo.github.io/assets/images/xingzo-crown-white-sm.png) Serverless + AWS Lambda

## Overview
- In this morning's session, we'll explore the different technologies used, process/approach, unsolved problems and some wins and challenges that went along in creating my first serverless app.


<a name="jquery"></a>
## What problem does serverless solve?

#### Definition
Serverless is not really serverless...It is a way of programming that allows developers to run functions on a remote third party server.
This method is also known as Function as a Service where you are only billed for the compute time you consume - there is no charge when your code is not running.

As per my research on how to deploy a node.js web app, it seems as if going serverless allows you to not worry about managing and provivisoning your servers which will save a lot of time in the end! 

Official Lambda Site
https://aws.amazon.com/lambda/

Pricing
https://aws.amazon.com/lambda/pricing/
    

- Advantages
	- Pros
		- no need to update operating systems of servers
		- no need to scale and provision servers
		- monitor servers for performance and availablity
    
 	- Cons
		- you have to give up your secret keys and credentials in order for Lambda to listen to your resources.
    - this is needed so lambda can grab pictures on S3 and run functions on your behalf
		- new technology so potential for bugs
    - installs alot of packages
    


    
## How did I use serverless?
  Created a simple api endpoint that returns a success message in JSON format.
  
#### Technologies used

  - Node.js
  - AWS account
  - Terminal
  
  - Watch this video to set up your first serverless app
  https://www.youtube.com/watch?v=71cd5XerKss&t=218s
  
  - Visit the Serverless framework github repo for more resources
  https://github.com/serverless/serverless
  
  - How to set up AWS credentials
  https://www.youtube.com/watch?v=HSd9uYj2LJA
  
  - AWS credentials GUI to keep you signed in
  https://github.com/DavidWells/aws-profile-manager
  
  
## Not interested in serverless?
 
 
 Setting up MERN Stack on AWS EC2 by Keith Weaver
 
 - Youtube
 https://www.youtube.com/watch?v=GKIIL743Gjo
 
 - Medium
 https://medium.com/@Keithweaver_/setting-up-mern-stack-on-aws-ec2-6dc599be4737
 
 
 ## How to set up youe static front end website
 
 https://docs.aws.amazon.com/AmazonS3/latest/dev/website-hosting-custom-domain-walkthrough.html
 
 	- Very descriptive but contact me if you have issues redirecting
  
