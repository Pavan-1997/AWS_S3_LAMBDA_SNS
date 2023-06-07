# AWS S3 - LAMDBA - SNS Using Shell Scripting 

In this project we are using Shell Scripting with AWS CLI to create S3 Bucket , assign Roles, create a Lambda function such that it triggers the SNS where there is a email notification sent whenever the user tries to upload any file to the S3 bucket, prior to uploading the file to S3 the user must subscribe to the SNS Topic once the shell script is run.

Make sure there is a EC2 instace with you and have AWS CLI configured with Access Key and Secret Key.

The Script and the Lambda function files are present in the repo.

This project can be considered as an analogy where say Netflix whenever they upload any new content we get notification.

![image](https://github.com/Pavan-1997/AWS_S3_Lambda_SNS/assets/32020205/d41f5970-0ab7-48f0-a74e-950c04e06e3f)
