Welcome to the "Using Step Functions and Bedrock for Smarter Data Feeds" workshop. 

The goal of this workshop is to introduce you a number of AWS tools and services that allow you to create flexible, powerful applications that can manipulate and analysis unstructured data. 


The key Tools/Services we'll be looking at include:
* AWS CLI (AWS Command Line Interface)
* AWS SAM (Serverless Application Model)
* AWS CloudFormation
* AWS Step Functions
* Amazon Bedrock
* AWS Lambda
* Amazon DynamoDB

We will start off by setting up your local development machine with the **AWS CLI** and **AWS SAM (Serverless Application Model) CLI** applications and set them up to talk to an AWS Account. THis will ensure you have everything you need locally to build and deploy the solution throughout the rest of the Workshop.

Once you've got your local machine configured correctly, the next step is to setup a new SAM application. We'll look at the **AWS SAM CLI** tool, create a new Serverless application using an AWS provided quickstart and test the deployment of it into an AWS Account.

From here, we can start adding the various components that the application will need, like an **AWS Lambda** function to fetch the required data, a **Step Function** workflow to co-ordinate all the various activities, a **DynamoDB** table to host our results and an **Amazon BedRock** implementation that will perform the bulk of the data analysis.

Finally, we'll look at what we can do with the processed data once it's been written to the database.

Throughout the course of the workshop, each section will detail some of the reasons for making various design/architectural decisions and provide links to resources you can read after the workshop to get further information.

To get started, [Here](./overview/index.md) to progress to the next chapter where we'll walk through what it is we will actually be building throughout the workshop and the problem that we are trying to solve.
