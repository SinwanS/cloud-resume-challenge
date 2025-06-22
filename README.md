# cloud-resume-challenge

This is my attempt at the cloud resume challenge in AWS.
[The Cloud Resume Challenge](https://cloudresumechallenge.dev/docs/the-challenge/aws/) is a multiple-step resume project that helps build and demonstrate skills fundamental to building in the Cloud. The project was published by Forrest Brazeal.
Currently, I have the site deployed using S3 and AWS CloudFront with GitHub actions to automatically update any front-end changes I push to the site repository. I have also set up an AWS Lambda function to pull and update the view counter data from 
DynamoDB. The next step I am currently working on is setting up Infrastructure as Code. I will be creating all my AWS resources entirely using Terraform rather than creating them in the AWS console as I have currently. 

**Services Used**:

- S3
- AWS CloudFront
- Certificate Manager
- AWS Lambda
- Dynamo DB
- GitHub Actions

## [Live Demo 🔗](https://resume.sinwansaeed.com)
