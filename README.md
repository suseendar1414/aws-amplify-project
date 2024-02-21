# aws-amplify-project
# AWS Services Project

## Overview
This project is a demonstration of building a web application using various AWS services, including AWS Amplify, Amazon API Gateway, AWS Lambda, Amazon DynamoDB, and AWS Identity and Access Management (IAM). It showcases how these services can be integrated to create a fully functional application.

## Features
- Frontend built with AWS Amplify
- Backend logic handled by AWS Lambda functions
- API endpoints managed through Amazon API Gateway
- Data storage and retrieval managed by Amazon DynamoDB
- IAM used for access control and security management

## Getting Started
1. Clone the repository: `git clone git@github.com:suseendar1414/aws-amplify-project.git`
2. Install dependencies for frontend: `cd frontend && npm install`
3. Configure AWS Amplify: `amplify configure`
4. Initialize the Amplify project: `amplify init`
5. Deploy the frontend: `amplify publish`
6. Update `lambda_function.py` with your desired logic for Lambda functions
7. Deploy the backend: `amplify push`

## Resources
- [AWS Amplify Documentation](https://docs.amplify.aws/)
- [Amazon API Gateway Documentation](https://docs.aws.amazon.com/apigateway/)
- [AWS Lambda Documentation](https://docs.aws.amazon.com/lambda/)
- [Amazon DynamoDB Documentation](https://docs.aws.amazon.com/dynamodb/)
- [AWS IAM Documentation](https://docs.aws.amazon.com/iam/)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
