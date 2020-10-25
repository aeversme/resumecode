This repository contains the necessary code for a serverless back-end website hit counter using AWS Lambda, DynamoDB, and API Gateway. Upon pushing code updates to the repository, a GitHub Action will process the code using AWS SAM (Serverless Application Model) and deploy the stack in CloudFormation, creating all necessary resources, permissions, and connections.

Things to work on:

- Python unit tests between git push and sam deploy.

- Conditional DDB item create, instead of having to fudge things by uploading static update_item followed by  an atomic update_item code revision.