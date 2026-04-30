# 🚀 AWS EC2 + NGINX + HTTPS Deployment (DevOps Project)

## 📌 Project Overview

This project demonstrates a full DevOps-style cloud deployment on AWS using EC2, NGINX, and SSL (Let's Encrypt).

It includes:
- Cloud server provisioning
- Web server setup
- Domain mapping
- HTTPS configuration
- Production-level deployment practices

---

## 🌐 Live Demo

👉 https://awsbilal.duckdns.org

---

## 🧠 Architecture Flow

Client Browser  
↓  
DuckDNS Domain (awsbilal.duckdns.org)  
↓  
AWS EC2 Ubuntu Server  
↓  
NGINX Web Server  
↓  
HTTPS (Let's Encrypt SSL)

---

## ⚙️ Tech Stack

- AWS EC2 (Ubuntu)
- NGINX
- DuckDNS (Dynamic DNS)
- Certbot (Let's Encrypt SSL)
- Linux CLI
- SSH

---

## 🚀 Step-by-Step Implementation

### 1. Launch EC2 Instance
- Ubuntu Server (t2.micro - Free Tier)
- Security Group Rules:
  - HTTP (80)
  - HTTPS (443)
  - SSH (22)

---

### 2. Connect to Server

```bash
ssh -i your-key.pem ubuntu@<EC2_PUBLIC_IP>
