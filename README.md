# serverless-api-test

What problem does this technology solve?
How do you use it? (Is there a "cheatsheet" you found or made that others can reference?)
What did you build?

# ![](https://xingzo.github.io/assets/images/xingzo-crown-white-sm.png) Serverless + AWS Lambda

## Overview
- In this morning's session, we'll explore the different technologies used, process/approach, unsolved problems and some wins and challenges that went along in creating my personal about me portfolio site.


<a name="jquery"></a>
## What problem does serverless solve?

#### Definition
Serverless is not really serverless...It is a way of programming that allows developers to run functions on a remote third party server.
This method is also known as Function as a Service where you are only billed for the compute time you consume - there is no charge when your code is not running.

As per my research on how to deploy a node.js web app, it seems as if going serverless allows you to not worry about managing and provivisoning your servers which will save a lot of time in the end! 

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
    
    
https://aws.amazon.com/lambda/

Pricing
https://aws.amazon.com/lambda/pricing/
    
    
## How did I use serverless?
  Created a simple api endpoint that returns a success message in JSON format.
  
#### Technologies used

  - Node.js
  - AWS account
  - Terminal
  
  -Youtube Tutorials
  Serverless 101 in 10 mins
  https://www.youtube.com/watch?v=71cd5XerKss&t=218s
  
  Serverless framework github repo
  https://github.com/serverless/serverless
  
  How to set up AWS credentials
  https://www.youtube.com/watch?v=HSd9uYj2LJA
  
  AWS credentials GUI to keep you signed in
  https://github.com/DavidWells/aws-profile-manager
  
