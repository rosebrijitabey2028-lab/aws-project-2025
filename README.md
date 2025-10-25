# AWS Project Deployment

## 🚀 Project Overview

This repository contains the infrastructure configuration and deployment logic for a scalable, event-driven data pipeline designed to ingest, transform, and store real-time IoT sensor data using AWS Kinesis and DynamoDB.

## 🛠 Prerequisites

1.  **AWS Account:** A fully activated AWS account.
2.  **AWS CLI:** Configured and installed locally.
3.  **IAM Role:** An IAM Role named `ProjectDeployerRole` with the policy defined in `iam-deployer-policy.json` attached.
4.  **Deployment Tool:** [E.g., Terraform, Serverless Framework, or AWS CLI scripts].

## 🚧 Current Blocker: Account Activation

The primary blocker preventing deployment and infrastructure setup is an issue with the AWS root account activation. **No infrastructure deployment can proceed until AWS Support resolves the verification error.**

## ⚙️ Initial Setup (Post-Activation)

Once the AWS account is active:

1.  **Create IAM Policy:** Use the JSON document provided in `iam-deployer-policy.json` to create a new Policy in the IAM console.
2.  **Create IAM Role:** Create an IAM Role (e.g., `ProjectDeployerRole`) and attach the policy created in Step 1.
