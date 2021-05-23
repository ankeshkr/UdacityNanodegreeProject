# Cloud Devops Engineer Nanodegree
# UdacityNanodegreeProject2- Deploy a high-availability web app using CloudFormation
Scenario
Your company is creating an Instagram clone called Udagram. Developers pushed the latest version of their code in a zip file located in a public S3 Bucket.

You have been tasked with deploying the application, along with the necessary supporting software into its matching infrastructure.

This needs to be done in an automated fashion so that the infrastructure can be discarded as soon as the testing team finishes their tests and gathers their results.
************************************************************************************
CloudFormation - CreateStack: aws cloudformation create-stack --stack-name Udacity-Prj2 --template-body file://Udacity_Project2.yml  --parameters file://project2.json --profile ankesh  --region=us-west-2 --capabilities "CAPABILITY_IAM" "CAPABILITY_NAMED_IAM" 
CloudFormation - UpdateStack: aws cloudformation create-stack --stack-name Udacity-Prj2 --template-body file://Udacity_Project2.yml  --parameters file://project2.json --profile ankesh  --region=us-west-2 --capabilities "CAPABILITY_IAM" "CAPABILITY_NAMED_IAM" 
*************************************************************************************
LoadBalancer DNS: http://udaci-webap-ykjcr179h1by-1138023692.us-west-2.elb.amazonaws.com/ 
Lucid Chart: Infrasturucture_design.pdf






