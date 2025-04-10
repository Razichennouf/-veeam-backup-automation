# Veeam Backup & Disaster Recovery Automation

## 📌 Project Overview
This project automates backup and disaster recovery operations using **Veeam Backup & Replication**. It ensures **secure, efficient, and automated data protection** for Windows/Linux servers and MySQL/MariaDB databases, leveraging **Ansible** for deployment.
## Project Terms
- Long term retention
- Tiering 
- Lower Cost
- Backups
## Project Requirements
-  This project is not prod, it is meant for learning purposes and be cost effective for learners.
- **Instances**: t3.small: 2 vCPUs, 2GB RAM | t3.medium: 2 vCPUs, 4GB RAM
# 🎯 Key Features
- **Automated Backup & Recovery** using Veeam
- **Support for Windows/Linux Servers & MySQL/MariaDB**
- **Backup Storage Options**: AWS S3 & Local Storage (NAS)
- **Ansible Automation** for Deployment & Configuration
- **Compression & Deduplication** to Optimize Storage

## 🏗️ Architecture
- **Backup Sources:** Windows/Linux servers, MySQL/MariaDB
- **Backup Management:** Veeam Backup & Replication
- **Storage:** AWS S3 & Local NAS
- **Automation:** Ansible for automated deployment

## 🔧 Technologies Used
- **Veeam Backup & Replication**
- **Windows Server / Linux**
- **MySQL / MariaDB**
- **Ansible & Ansible Galaxy**
- **AWS S3 for Cloud Backup**
- **PowerShell & Bash for Scripting**
- **Deduplication & Compression Techniques**

## 🚀 Deployment Steps
1. **Install Ansible & Dependencies**
   ```bash
   sudo apt update && sudo apt install ansible -y
   ansible-galaxy install community.general
