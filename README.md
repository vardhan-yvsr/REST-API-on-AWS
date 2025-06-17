# REST-API-on-AWS

## Overview
A serverless REST API built using AWS Lambda (Python), DynamoDB, API Gateway, and IAM roles. The project demonstrates secure, scalable, and fully managed backend architecture, with deployments and management streamlined via MobaXterm.

## Architecture

| Component        | Purpose                                                    |
|------------------|-----------------------------------------------------------|
| IAM Roles        | Securely grant permissions to Lambda and API Gateway       |
| Lambda Functions | Handle HTTP requests and interact with DynamoDB            |
| DynamoDB         | NoSQL database for structured, scalable data storage       |
| API Gateway      | Expose RESTful endpoints for external access               |
| MobaXterm        | Remote AWS management and deployment automation            |

## Features

- Secure, role-based access control using IAM
- RESTful API endpoints for CRUD operations
- Lambda functions in Python for backend logic
- Scalable, schema-less data storage with DynamoDB
- Automated deployment and management with MobaXterm

## Deployment Steps

1. **Define IAM roles and policies** for Lambda and API Gateway.
2. **Create DynamoDB tables** with appropriate partition and sort keys.
3. **Develop Lambda functions** to handle GET/POST requests and interact with DynamoDB.
4. **Configure API Gateway** to route HTTP requests to Lambda.
5. **Deploy and manage resources** using MobaXterm for streamlined operations.

## Example API Usage

- **GET** `/dev/resource?operation=read&CustomerId=123&LastName=Smith`  
  Retrieves a specific item from DynamoDB.
- **GET** `/dev/resource?operation=query_all`  
  Retrieves all items from the table.
- **POST** `/dev/resource`  
  Adds a new item to DynamoDB (JSON body required).

## Technologies

- AWS Lambda (Python)
- Amazon DynamoDB
- Amazon API Gateway
- AWS IAM
- MobaXterm

## Live Demo

[API Endpoint](https://bgfpwy9xyk.execute-api.ap-south-1.amazonaws.com/dev)
