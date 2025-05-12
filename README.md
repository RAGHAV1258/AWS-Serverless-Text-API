# 🧠 Serverless Text Analyzer (AWS Lambda + API Gateway + DynamoDB)

This project is a **serverless REST API** built using **AWS Lambda**, **API Gateway**, and **DynamoDB**. It receives a text input, analyzes it (e.g., word and character count), and stores the result in a DynamoDB table.

---

## 📌 Features

- Serverless architecture using AWS services
- REST API endpoint using API Gateway
- Text analysis (word count & character count)
- Stores data in a DynamoDB table
- Written in Python using Boto3 SDK
- Error handling and validation built-in

---

## 🧱 Architecture Diagram

![System DataFlow Diagram -> ](DFD.png)


---

## 🚀 Technologies Used

- **AWS Lambda** – for running serverless backend logic
- **Amazon API Gateway** – for exposing the API endpoint
- **Amazon DynamoDB** – for persistent NoSQL data storage
- **IAM** – for permission management
- **Boto3** – AWS SDK for Python
- **Python 3.9+**

---

## 🛠️ Setup Instructions

### 1. 🗃️ Create DynamoDB Table
- Table Name: `TextAnalysis`
- Primary key: `id` (String)

---

### 2. 🧠 Lambda Function

- 
Paste the following code into your Lambda function:

