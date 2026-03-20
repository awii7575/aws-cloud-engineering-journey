# 🚀 EC2 Nginx Web Server Setup (AWS)

## 📌 Task Objective
Launch an EC2 instance, configure networking and security, install Nginx, and verify the web server using browser.

---

## 🖥 EC2 Configuration

- Instance Type: t2.micro / t3.micro
- Operating System: Amazon Linux 2023
- Public IP: Enabled

---

## 🌐 Web Server Setup

- Installed Nginx using package manager
- Started and enabled Nginx service
- Verified web server using browser with EC2 public IP

---

## 🔐 Security Configuration

- SSH (Port 22) allowed from My IP
- HTTP (Port 80) allowed from Anywhere (0.0.0.0/0)

---

## 🌍 Networking Configuration

- Created and attached Internet Gateway
- Added route:
  - 0.0.0.0/0 → Internet Gateway
- Ensured instance is in public subnet

---

## 🔗 SSH Connection

```bash
ssh -i my-key.pem ec2-user@<public-ip>

## 💰 Cleanup
All resources were terminated after testing to avoid unnecessary AWS charges.
