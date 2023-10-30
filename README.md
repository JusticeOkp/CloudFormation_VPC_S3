# CloudFormation_VPC_S3
Creating a vpc with a s3 bucket that has get and put permissions with cloudformation using a pipeline for staging and approvals via aws code pipeline 

## Steps 
1. Create a VPC: Define your VPC, subnets, route tables, and security groups.
2. Create an S3 Bucket: Define an S3 bucket and configure permissions for GET and PUT requests.
3. Set Up CodePipeline: Create a CodePipeline that includes the following stages:Source Stage (GitHub), Build Stage (infrastructure code), Staging Stage (deploying your application), Approval Stage (manual approvals), Production Stage (final deployment).
4. Define IAM Roles and Policies: Create IAM roles and policies for your EC2 instances to interact with the S3 bucket and execute deployments through CodePipeline.
## Creating YAML code
1.Define Parameters and Input Values: If your CloudFormation template requires input values, make sure to specify them when creating the stack.
2.IAM Roles and Permissions:  Ensure that the AWS account or IAM user you are using to create the CloudFormation stack has the necessary permissions to create the specified AWS resources and configurations. 
3.Resource Naming: Make sure that the resource names you define in your YAML template are unique within your AWS account and adhere to AWS naming conventions.
4.Testing and Validation: Use the AWS CloudFormation Template Validator to catch any syntax or logical errors in your template.
