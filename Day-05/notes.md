# Day 5 — AWS EBS + AMI

## EBS (Elastic Block Store)

- EC2 এর hard disk
- Type: gp3 (default, free tier 30GB)
- Persistent: server stop এ data থাকে
- Snapshot: EBS এর backup

## EBS Commands

- lsblk → volumes দেখো
- mkfs -t ext4 /dev/xvdf → format
- mount /dev/xvdf /data → mount
- df -h → space দেখো

## AMI (Amazon Machine Image)

- পুরো server এর template
- OS + Config + Data সব
- Custom AMI বানিয়ে রাখো

## AMI vs Snapshot

- Snapshot = EBS backup
- AMI = পুরো server template

## Use Cases

- Auto Scaling এ AMI use হয়
- Disaster recovery
- Identical environments বানাতে

## Hands-on Done ✅

- EBS volume বানিয়েছি
- EC2 তে attach করেছি
- Snapshot নিয়েছি
- Custom AMI বানিয়েছি
- AMI থেকে নতুন EC2 launch করেছি
