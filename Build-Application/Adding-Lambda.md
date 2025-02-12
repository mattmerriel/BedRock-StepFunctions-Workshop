# Adding a Lambda Function
With our Step Function now in place, it's time to add the Lambda function that will fetch the records from the RSS feed for us.

Much like the Step function, we have multiple things we need to do in order to deploy a new function:
1. Write the Lambda function and define it's dependancies.
2. Add it's definition to the CloudFormation Template

## Creating the Lambda Function
Firstly, let's add a new Lambda Function code to the project. To do this, all we need to do is create a new 