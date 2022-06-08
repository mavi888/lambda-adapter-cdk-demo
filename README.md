# AWS Lambda Adapter CDK Demo - Lift and Shift a Node- Express App

_Infrastructure as code framework used_: AWS CDK
_AWS Services used_: AWS Lambda

## Summary of the demo

In this demo you will see:

- How to create a Lambda function that uses the AWS Lambda Adapter extension to lift and shift a Node-Express app

This demo is part of a video posted in FooBar Serverless channel. You can check the video to see the whole demo.

Important: this application uses various AWS services and there are costs associated with these services after the Free Tier usage - please see the AWS Pricing page for details. You are responsible for any AWS costs incurred. No warranty is implied in this example.

## Requirements

- AWS CLI already configured with Administrator permission
- AWS CDK - v2
- NodeJS 16.x installed
- CDK bootstrapped in your account

## Deploy this demo

Deploy the project to the cloud:

```
cdk synth
cdk deploy
```

When asked about functions that may not have authorization defined, answer (y)es. The access to those functions will be open to anyone, so keep the app deployed only for the time you need this demo running.

To delete the app:

```
cdk destroy
```

## Links related to this code

- Video with more details: https://youtu.be/MvVaFPCdiZY
- AWS Lambda adapter: https://github.com/aws-samples/aws-lambda-adapter

### AWS CDK useful commands

- `npm run build` compile typescript to js
- `npm run watch` watch for changes and compile
- `npm run test` perform the jest unit tests
- `cdk deploy` deploy this stack to your default AWS account/region
- `cdk diff` compare deployed stack with current state
- `cdk synth` emits the synthesized CloudFormation template
