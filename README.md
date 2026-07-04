# AWS Python HTTP API using Serverless Framework

## Project Overview

This project demonstrates how to build and deploy a **serverless HTTP API** using **Python**, **AWS Lambda**, **Amazon API Gateway**, and the **Serverless Framework**.

Instead of managing servers, the application uses AWS Lambda to execute Python code only when an HTTP request is received, making it scalable and cost-effective.

---

## Architecture

```
Client
   │
   ▼
Amazon API Gateway
   │
   ▼
AWS Lambda
   │
   ▼
Python Handler (handler.py)
   │
   ▼
JSON Response
```

---

## AWS Services Used

- AWS Lambda
- Amazon API Gateway (HTTP API)
- AWS CloudFormation (via Serverless Framework)

---

## Technologies Used

- Python
- Serverless Framework
- YAML
- Git
- GitHub
- AWS Cloud

---

## Features

- Serverless architecture
- HTTP API endpoint
- Event-driven execution
- Automatic deployment
- JSON response
- No server management

---

## Project Structure

```
aws-python-http-api/
│
├── handler.py
├── serverless.yml
├── README.md
├── .gitignore
└── screenshots/
```

---

## Lambda Function

The Lambda function returns a JSON response when an HTTP GET request is received.

Example Response:

```json
{
  "message": "Welcome to my AWS Serverless HTTP API!",
  "developer": "Vedashri Giri",
  "technology": "Python + AWS Lambda + API Gateway",
  "status": "Success"
}
```

---

## Deployment Steps

Clone the repository

```bash
git clone https://github.com/Vedashri28/aws-python-http-api.git
```

Go to the project

```bash
cd aws-python-http-api
```

Deploy

```bash
serverless deploy
```

View service information

```bash
serverless info
```

Remove the deployment

```bash
serverless remove
```

---

## Learning Outcomes

Through this project, I learned:

- AWS Lambda fundamentals
- API Gateway integration
- Serverless Framework deployment
- Infrastructure as Code (IaC)
- Event-driven architecture
- Deploying cloud-native applications
- Git and GitHub version control

---

## Future Improvements

- Add multiple API endpoints
- Connect DynamoDB
- Implement CRUD operations
- Add authentication using Amazon Cognito
- Add CloudWatch logging and monitoring

---

## Author

Vedashri Giri

Aspiring Cloud & DevOps Engineer
