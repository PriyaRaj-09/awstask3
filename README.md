# awstask3
task 1 
Steps
1. Create S3 Bucket

Create an S3 bucket

Enable Block all public access

2. Enable CloudTrail

Create a CloudTrail trail

Enable CloudWatch Logs

Add S3 Data Events (Write) for the bucket
3. Upload File

Upload a file (example: test.txt) to the S3 bucket

4. View Logs

Go to CloudWatch → Logs

Open the CloudTrail log group

Find the PutObject event


task 2

Steps
1. Launch EC2 Instances

Launch two EC2 instances

Use the same VPC and subnet

Install a web server (Apache/Nginx)

Ensure the application is running

2. Create Target Group

Create a target group (type: Instance)

Register both EC2 instances

Configure health checks

3. Create Application Load Balancer

Create an Application Load Balancer

Select internet-facing

Attach the target group

Configure listener on port 80

4. Test Access

Copy the Load Balancer DNS name

Open it in a browser

Traffic is distributed between both EC2 instances
