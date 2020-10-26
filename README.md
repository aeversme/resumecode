This repository contains the necessary code for a serverless back-end website hit counter using AWS Lambda, DynamoDB, and API Gateway. Upon pushing code updates to the repository, a GitHub Action processes the code using AWS SAM (Serverless Application Model) to deploy the stack in CloudFormation, creating all necessary resources, permissions, and connections.

Things to work on:

- Python unit tests between git push and sam deploy.