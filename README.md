### CURD operations API using AWS(Amazon Web Services).
#### The API uses the AWS CloudFormation,DynamoDB and Amazon S3.
##### API created with Node JS.
##### Required Node Modules are
###### 1.AWS-SDK for NodeJS, 
       npm install aws-sdk (or) AWS-SDK https://aws.amazon.com/sdk-for-node-js
###### 2.Node Serverless,
       npm install -g serverless (or) https://serverless.com/framework/docs/getting-started/
###### 3.Node UUID Generator,
       npm install uuid (or) https://www.npmjs.com/package/uuid
##### Just need to create an AWS Account. 
##### Login to your Account,Click on Username move to My Security Credentials->Access Keys->Create access keys.
##### Copy the Access Key ID and Secret Key for Deployment.

##### Open the Aws-Sdk and configure the Credentials.
##### In Project folder Cmd run following command,
          serverless config credentials --provider aws --key {Access Key ID} --secret {Secret Key} -o
##### Then deploy our Project to Aws by the command,
          sls deploy
          
