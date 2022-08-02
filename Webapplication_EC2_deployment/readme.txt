================
Part 1
===================
--> Using Amazon S3 we have created a bucket for uploading the index file of the website and have uploaded the error  with  associated images for the webpage
--> The webpage varun.html references directly to the image link for the location in Amazon S3 bucket

URL for the website: https://swe645-varun-hw.s3.amazonaws.com/varun.html

================
Part 2
===================

--> The application with form for student survey has been deployed on Amazon EC2 instance
--> The styling sheet associated to the webpage and images required for the webpage are available in the war file 
--> Reference of the survey application has been provided in the Homepage of website.

Deployment instructions: 

--> Create an EC2 instance 
--> Create Key pair and save it on your local machine  
--> Login to EC2 instance on your desktop through winscp or command line interface using the .pem file generated for the EC2 instance, using default username or bitnami as user name
--> sudo for root level permissions 
--> Provide permission to place the file in the path /opt/bitnami/tomcat/webapps
--> Place the war file in the path /opt/bitnami/tomcat/webapps

URL for deployed Website: https://swe645-varun-hw.s3.amazonaws.com/varun.html
URL for Deployed application : http://ec2-34-226-154-151.compute-1.amazonaws.com/varun_hw1/


Note: Tested for functionality on local machine using Tomcat server