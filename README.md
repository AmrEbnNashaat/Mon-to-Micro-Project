# Mon-to-Micro-Project
Monolith to Microservice Project

## PROJECT OUTLINE
This project is done to demonstrate my ability to use DevOps tools such as Travis CI, Docker, and K8s to deploy a web application called Udagram using EKS and AWS. 

## WHAT TO DO?
You can use the external IP of the frontend to interact with the application, which in turn interacts with a reverseproxy. The reverseproxy interacts with 2 microservices,
one for the user, and the other is for the feed available to the end user's browser.
LINK to the frontend pod: http://ad82252aade074cddb79ec90545f31e2-1591424661.us-west-1.elb.amazonaws.com

## DATABASE
The project's database is hosted on RDS on AWS. And is connected to the backend of the application.

### NOTE
Inside the Screenshots folder are screenshots documenting each step of the way, starting from deconstructing a monolith application into seperate microservices,
till deploying it and checking user pods for confirmation of succesful backend integration
