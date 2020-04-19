# Lambda Functions
This class is an introduction to Lambda Functions.
The main goal is to explain the purpose, the benefits and how to use it.

***Contents***
- [What is Lambda Functions?](#what-is-lambda-functions)
- [Benefits](#benefits)
- [Event Sources](#event-sources)
- [Execution Role](#execution-role)
- [Common Use Cases](#common-use-cases)


## What is Lambda Functions?
Lambda Functions is one of the services part of the AWS Compute Services Family. Similar to the EC2 service, where you can run your application code, the purpose of the Lambda Function service is also to run application code, but in a different way. 

With Lambda Functions, your code does not need a server. At least nothing that you need to provision or manage. That's why Lambda Functions is a serverless service. You upload your code (list of languages can be found [here](https://aws.amazon.com/lambda/faqs/)) and your code will be execued when invoked.

## Benefits

The biggest benefit of using Lambda Function is the fact that you only pay for what you use. For services like EC2, you pay for the time your instance is up, which already provide you with a lot of cost benefits, since you can turn some of your servers down when your application load is reduced.

This cost reduction that can be achieved with EC2 instances can be even more benefitial when using Lambda Functions to run your applications, since you'll only pay for the time your application is being executed. If your application has no requests, there is no invocations of your Lambda Function and no costs to you.

It's important to make clear that in order to move your application to a service like this, some code transformations might be required, so it will require somework to just move an existing application running on VMs to run on this AWS service.

## Event Sources

## Execution Role

## Common Use Cases

