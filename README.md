AWS Project Deployment

🚀 Project Overview

This repository contains the infrastructure configuration and deployment logic for a scalable, event-driven data pipeline designed to ingest, transform, and store real-time IoT sensor data using AWS Kinesis and DynamoDB.

🛠 Prerequisites

AWS Account: A fully activated AWS account.

AWS CLI: Configured and installed locally.

Deployment Tool: [E.g., Terraform, Serverless Framework, or AWS CLI scripts].

🚧 Current Blocker: New Account Activation

The primary blocker preventing deployment and infrastructure setup is the creation and activation of a new AWS root account. No infrastructure deployment can proceed until the new account is fully set up and verified.

⚙️ Initial Next Steps (Post-Activation)

Once the new AWS account is active and you have confirmed root access:

Review Security: Immediately configure Multi-Factor Authentication (MFA) on the root user.

Create Admin User: Create a dedicated IAM user for daily administrative tasks.
