# WIP

### Simple Web App

A simple web application that takes the base and exponent numbers and finds the result using the following AWS services.

- **AWS Amplify**: Build full-stack web and mobile apps 

- **Amazon API Gateway**: It is a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs.

- **AWS Lambda**: It is a cloud service that lets you run code without provisioning or managing servers (serverless).

- **Amazon DynamoDB**: Serverless, NoSQL database.

- **AWS IAM**:  Manage identities and access to AWS services and resources

### How to

1. Create a web page (check the index.html)

2. Create a zip file of the index.html

3. Deploy the zip file (index.zip) using AWS amplify

![deploy_app.png](deploy_app.png)

4. Create a Lambda function called powerOfNumbers

    - paste the python code (powerOfNumbers.py) to the code part like below

      - ![powerOfNumbers.png](powerOfNumbers.png) 

    - Press the "Deploy" to deploy the code.S

5. Create a Rest API using Amazon API Gateway

  - ![restAPI.png](restAPI.png) 

  - Create a method and call the lambda function

    - ![createMethod.png](createMethod.png)

  - Finally Deploy the API.
   


### Resources

1. [AWS Project - Architect and Build an End-to-End AWS Web Application from Scratch, Step by Step - Tiny Technical Tutorials](https://www.youtube.com/watch?v=7m_q1ldzw0U)

2. https://aws.amazon.com/pm/lambda/

3. https://aws.amazon.com/amplify/

4. https://aws.amazon.com/api-gateway/

5. https://aws.amazon.com/dynamodb/

6. https://aws.amazon.com/iam/