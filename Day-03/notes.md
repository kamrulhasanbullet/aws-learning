# Day 3 — AWS CLI Configuration

## CLI কী?

Terminal দিয়ে AWS control করা।
Browser এর চেয়ে fast + automatable।

## Install

- aws.amazon.com/cli থেকে download
- aws --version দিয়ে verify

## Configure

- IAM তে Access Key বানাতে হয়
- aws configure দিয়ে setup
- Region: ap-south-1 (Mumbai)

## Important Commands

- aws sts get-caller-identity → account verify
- aws s3 ls → buckets দেখো
- aws s3 mb s3://name → bucket বানাও
- aws ec2 describe-instances → servers দেখো

## Structure

aws [service] [action] [options]

## Hands-on Done ✅

- CLI install করেছি
- Access Key বানিয়েছি
- aws configure করেছি
- Test bucket বানিয়ে delete করেছি
