# Can we just start building please?
I promise we're almost at the point where we can start doing things, just one more hurdle to clear first.

We need to setup our tools so that they can talk to the AWS environment. Authentication is a hugly complex and variable topic and one that I'm keen to avoid for the purposes of this workshop. So, for the last time today... I'm going to point you to the AWS website for you to folllow some more of their instructions.

## Do you already have credentials setup on your machine
If you already have credentials setup, and can access your AWS account... then your good to process to the next part by clicking [here](../Setup-New-SAM-Project/index.md).

You can verify if you've already got credentials setup by running the following command:
```
aws sts get-caller-identity
```

If you've got valid credentials already setup, this command should return with the **Account**, **UserId** and **Arn** of the credentials your using, like what's shown below
```
{
  "Account": "123456789012", 
  "UserId": "AR#####:#####", 
  "Arn": "arn:aws:sts::123456789012:assumed-role/role-name/role-session-name"
}
```

If you don't get valid details back, you receive and error message or you don't recognise the details presented to you, then go ahead and follow the AWS instructions on setting up [AWS SAM prerequisites](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/prerequisites.html).

And that's it! It's time for us to actually start work on setting up you new project by following the instructions [here](../Setup-New-SAM-Project/index.md).