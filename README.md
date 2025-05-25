# AWS-AI_AGENT
This project is an AI-powered agent interface built using LangChain and OpenAI GPT, enabling natural language interaction with AWS services. Currently, it supports core operations on Amazon S3.
The following operations are implemented and callable by the agent:

Assume role to start working with AWS

Initialize S3 client

Create Bucket – Create a new S3 bucket in a specified region

List Buckets – View all S3 buckets in your AWS account

Upload File – Upload a file to the currently selected S3 bucket

Delete File – Delete a file from a specified S3 bucket

Download File – Download a file from a bucket to local storage

Delete Bucket – Delete a specified S3 bucket

Set Bucket Policy – Apply a custom policy to an S3 bucket

This agent uses AWS STS to assume a role and access AWS securely.
