CURD operations API using AWS(Amazon Web Services).
The API uses the AWS CloudFormation,DynamoDB and Amazon S3.
API created with Node JS.
Required Node Modules are
          AWS-SDK for NodeJS,
          Node Serverless,
          Node UUID Generator
Just need to create an AWS Account 
Login to your Account,Click on Username move to My Security Credentials->Access Keys->Create access keys.
Copy the Access Key ID and Secret Key for Deployment.

Open the Aws-Sdk and configure the Credentials.
In Project folder Cmd run following command,
          serverless config credentials --provider aws --key {Access Key ID} --secret {Secret Key} -o
Then deploy our Project to Aws by the command
          sls deploy
          
