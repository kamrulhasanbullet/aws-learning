# Day 6 — AWS ELB + Auto Scaling Group

## ELB (Elastic Load Balancer)

- Traffic কে multiple server এ ভাগ করে
- Types: ALB (HTTP), NLB (TCP), GLB (Security)
- MERN app এর জন্য ALB ✅

## ALB Components

- Target Group: কোন servers এ traffic যাবে
- Health Check: server alive কিনা check করে
- Listener Rules: URL অনুযায়ী routing

## Auto Scaling Group (ASG)

- Traffic অনুযায়ী server automatically বাড়ায়/কমায়
- Min / Desired / Max capacity
- Launch Template দিয়ে নতুন server বানায়

## Scaling Policies

- Target Tracking: CPU % based (সহজ) ✅
- Step Scaling: step by step বাড়ে
- Scheduled: সময় অনুযায়ী

## ELB + ASG Flow

Internet → ALB → ASG (EC2 instances)

## Hands-on Done ✅

- Target Group বানিয়েছি
- ALB বানিয়েছি
- Auto Scaling Group বানিয়েছি
- Server terminate করে auto-recovery দেখেছি
