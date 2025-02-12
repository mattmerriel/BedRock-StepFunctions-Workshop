# Just what you've already wanted... Another command line application
In the section, we'll go ahead an install the AWS SAM CLI.

For those who are not aware, the AWS Serverless Application Model (AWS SAM) consists of two parts: AWS SAM templates and the AWS Serverless Application Model Command Line Interface (AWS SAM CLI). AWS SAM templates provide a short-hand syntax, optimized for defining Infrastructure as Code (IaC) for serverless applications. An extension of AWS CloudFormation, you deploy AWS SAM templates directly to CloudFormation, benefiting from its extensive IaC support on AWS. The AWS SAM CLI is a developer tool that puts AWS SAM features at your fingertips. Use it to quickly create, develop, and deploy serverless applications. Some of the many features of AWS SAM include AWS Serverless Application Model Accelerate (AWS SAM Accelerate), which speeds up local development and cloud testing, and AWS SAM CLI integrations, extending AWS SAM to other tools such as the AWS Cloud Development Kit (AWS CDK) and Terraform.

We're going to use it in this project to craft up the various serverless components that we'll need for our workflow. In a future itteration of this workshop I'll look to migraet to CDK so you can compare the various approaches.

Just like in the last section, you can confirm if you already have the SAM CLI installed by running the below command from the terminal.
```
sam --version
```

if you get back something that looks like
```
SAM CLI, version 1.124.0
```

You know that you've already got the SAM CLI installed. if you get back an error or not found message, you can browse to [Install the AWS SAM CLI](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/install-sam-cli.html) and follow the instructions.

> IMPORTANT NOTE: Starting September 2023, AWS will no longer maintain the AWS managed Homebrew installer for the AWS SAM CLI (aws/tap/aws-sam-cli). Instructions on how to remediate an existing HomeBrew installation can be found at the above link. (and for those who have no idea what HomeBrew is... you can disregard).

Once you've got a happy and working SAM CLI installed on your machine, We have one more step to do before we can start building. Now that we have the AWS and SAM CLI's installed on our machines, we need to configure access into our AWS account so that they can start taking actions on our behalf. Click [here](Setup-AWS-Account-Access.md) to setup access into AWS from your local machine.




