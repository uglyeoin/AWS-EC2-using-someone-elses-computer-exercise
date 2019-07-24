# AWS-EC2-using-someone-elses-computer-exercise
Step through the process of manually launching a ec2 instance and deploying an app to it with circleci

In this exercise you're tasked to make app that runs on elastic cloud compute (a virtual machine in the cloud). 
- write a small java / python hello world app. 
- run a small server on amazon to host your app. 
- (optional) create the platform using infrastructure as code. 

Let's get started:
1) Create a GitHub repository to hold the application code. 
2) Make a 'hello world' app in python, javascript java or languages of your choice - commit and push the changes to GitHub. 
3) make the hello world app run as a webserver returning hello world on a Web request 
4) check calling your web app via the browser that it works
5) open amazon management console and create a ec2 instance using a t2.micro sized machine (you MUST delete this at the end of the session or it will eventually cost money). 
6) use ssh to log into the machine and check the machine is running java/python by printing the version. 
7) write a job in circleci that deploys your application to the ec2 instance. 

Awesome we can run our application in the cloud! 

Wrapping up the technology and purpose:
- java/python to run a application that returns a message. 
- Configuration of a virtual machine running in aws to serve traffic. 
- Git committing and pushing to GitHub. 
- manually deploying an app to AWS EC2

Optional: write a circleci deployment pipeline for continuously delivering changes to the machine.
