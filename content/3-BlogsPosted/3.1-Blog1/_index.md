---
title: "Blog 1"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 3.2. </b> "
---
# SERVERLESS BOOKSTORE: GETTING STARTED WITH AWS LAMBDA FUNCTIONS

AWS Lambda is a Serverless Computing service provided by AWS that allows you to run code without provisioning or managing servers. Instead of preparing infrastructure, setting up environments, or monitoring resources as you would with EC2, Lambda executes strictly when triggered by events and automatically reclaims resources upon completion. This optimizes costs and makes it an ideal fit for event-driven tasks such as file uploads, email sending, or image processing.

Key takeaways:

* AWS Lambda is a **Serverless Computing** service that enables code execution without managing, configuring, or maintaining servers.
* It operates on an **Event-driven** model: Lambda executes only upon receiving an event signal from other AWS services.
* It can be triggered by various event sources, including **Amazon S3, DynamoDB, API Gateway, EventBridge, SNS, and SQS**.
* By default, Lambda has no permission to access other AWS services; permissions must be granted via an **IAM Execution Role**.
* **Amazon CloudWatch** automatically records execution metrics, invocation counts, success/failure statuses, and application logs.
* Beware of **infinite loops** when configuring S3 triggers: if Lambda writes output back to the same bucket that triggered it, the new file will trigger Lambda again, causing thousands of unwanted executions.
* Save outputs to a separate bucket or configure triggers to filter specific file prefixes/suffixes to avoid loop issues.

AWS Lambda is particularly suited for small, event-driven, intermittent workloads. It allows developers to focus on writing code rather than managing infrastructure while improving cost efficiency and scalability in modern cloud architectures.

## Step-by-Step Guide

### Step 1: Explore AWS Lambda

- Access the **AWS Lambda** service in the AWS Management Console.
- Learn about Serverless Computing concepts and key differences between Lambda and EC2.
- Identify suitable use cases for Lambda (e.g., generating image thumbnails, validating file formats, sending order confirmation emails).

### Step 2: Create a Lambda Function

- Choose **Create function**.
- Select an appropriate runtime (e.g., Python, Node.js).
- Write the function logic for your task.

### Step 3: Configure the Execution Role

- Create or select an existing **IAM Role** for the Lambda Function.
- Attach the necessary permissions so Lambda can access required AWS services (e.g., Amazon S3).

### Step 4: Configure Triggers

- Set up an event trigger for Lambda, such as an object creation event in **Amazon S3**.
- Carefully verify the configuration to prevent infinite execution loops if writing output back to S3.

### Step 5: Test and Monitor

- Trigger the event (e.g., upload a file to S3).
- Open **Amazon CloudWatch** to inspect execution logs, duration, and status.
- Review log streams to troubleshoot and resolve any runtime errors.

### Key Outcomes

- Understand the core concepts and role of **AWS Lambda** in serverless architectures.
- Differentiate between **Lambda** and **EC2** operational models.
- Grasp **Event-driven** processing and common event sources.
- Understand the role of **IAM Execution Roles** in granting secure permissions.
- Learn how to use **CloudWatch** for monitoring and debugging.
- Identify and prevent **infinite loops** when configuring S3 triggers.

## References

- Workshop: https://000078.awsstudygroup.com/
- Video Tutorial: https://youtu.be/eOBq__h4OJ4?si=ulpAoOrEMKxXV9iq

![](/images/3-Blog/Blog-1/blog-1.png)