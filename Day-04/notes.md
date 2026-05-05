# Day 4 — AWS EC2 Service

## EC2 কী?

AWS এর Virtual Server।
Minutes এ server ready, per hour pay।

## Main Components

- AMI: OS template (Ubuntu, Amazon Linux)
- Instance Type: Server এর size (t2.micro = free)
- Security Group: Firewall (port control)
- Key Pair: SSH login এর চাবি (.pem)
- EBS: Server এর hard disk

## SSH Connect

ssh -i "key.pem" ubuntu@public-ip

## Node.js Deploy Steps

1. sudo apt update
2. Node.js install
3. git clone
4. npm install
5. pm2 start

## Pricing

- Free Tier: t2.micro, 750hrs/month
- On-Demand: যতক্ষণ চালাও ততক্ষণ pay

## Important

- Stop ≠ Terminate (Terminate মানে সব শেষ!)
- Elastic IP = fixed public IP
- .pem file হারানো যাবে না!

## Hands-on Done ✅

- EC2 instance launch করেছি
- SSH দিয়ে connect করেছি
- Node.js install করেছি
- Express app deploy করেছি
