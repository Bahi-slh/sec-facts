# 💀 CyberSec+Life Facts — Serverless GenAI Project 

This project blends **cybersecurity principles** with **golden life lessons**.  
It’s built on AWS using a **serverless architecture** and GenAI to make each fact witty and fun.

## What It Does

- Serves random cybersecurity-inspired life lessons through a **Lambda** API
- Stores and manages all facts in **DynamoDB**
- Uses **Amazon Bedrock** (Claude 4.5 Sonnet) to rewrite facts with flair
- Exposes the API through **API Gateway** for easy integration with web apps or front-ends
- Runs fully **serverless** — no infrastructure to babysit 

## Why It’s Cool

- Every fact ties a **real security concept** (e.g. firewalls, zero trust, pen testing) to a **real-world mindset** (boundaries, trust, self-defense)
- Uses GenAI for dynamic text transformation
- Deployable in minutes, scalable to thousands of requests
- Great base project for learning serverless and AI integration

##  Tech Stack

- **AWS Lambda** — backend logic  
- **Amazon DynamoDB** — fact storage  
- **Amazon API Gateway** — public API endpoint  
- **Amazon Bedrock** — witty fact generation  
- **Python** — Lambda function code

##  Architecture Flow

1. Lambda fetches a random fact from DynamoDB.  
2. Sends it to Amazon Bedrock (Claude 4.5) to rewrite in a fun tone.  
3. Returns the rephrased fact as the API response.  
4. Optional — can easily plug into a front-end or chatbot.

##  How to Run

Since this project is fully powered by AWS serverless services and already deployed, you can skip the setup and **check it out live** 👉 [https://main.d3w3hvnu7ed1sa.amplifyapp.com/](https://main.d3w3hvnu7ed1sa.amplifyapp.com/)

