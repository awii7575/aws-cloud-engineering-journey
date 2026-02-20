# Multi-Region VPC Architecture with Peering (AWS)

## 📌 Overview
Designed and implemented a multi-region AWS network architecture using VPC, subnets, NAT Gateway, Internet Gateway, and VPC Peering.

---

## 🌎 Regions
- us-east-1
- us-west-1

---

## 🏗 Architecture Details

### VPC 1 (us-east-1)
- CIDR: 10.0.0.0/16
- 3 Public Subnets
- 3 Private Subnets
- Internet Gateway attached
- NAT Gateway configured

### VPC 2 (us-west-1)
- CIDR: 172.0.0.0/16

---

## 🔐 Security Group Rules
- SSH (22) allowed from my IP
- HTTP (80) allowed from anywhere

---

## 🔗 VPC Peering
- Created cross-region peering connection
- Updated route tables on both VPCs

---

## 🧠 Skills Demonstrated
- VPC Design
- Subnet Architecture
- Route Tables
- NAT Gateway
- Internet Gateway
- Security Groups
- Cross-Region Peering

---

## 💰 Cost Optimization
All resources were terminated after testing to avoid unnecessary AWS charges.
