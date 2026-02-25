# AWS Security Lab - S3 Least Privilege

##Objective
Demonstrate implementing least priivilege access to an S3 buckeet using IAM.

## Seervices Used
- IAM
- S3

## Security Controls
- Custom IAM policy allowing only GetObject and PutObject
- Access restricted to a single bucket
- Block Public Access enabled

## Key Learning
Object-Level permissions require specifying:
arn:aws:s3:::vibesafe/*
