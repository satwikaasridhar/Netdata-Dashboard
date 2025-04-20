# Netdata-Dashboard

## 📌 Objective
Install and run Netdata on an EC2 instance using Docker to visualize system and application performance metrics through a real-time web dashboard.

## 🛠 Tools Used
- **Netdata** – Open-source system monitoring tool  
- **Docker** – Containerization platform to run Netdata  
- **Amazon EC2** – Virtual Machine instance on AWS  

## ⚙️ Setup Instructions

###  Step 1: Connect to EC2 via SSH

###  Step 2: Install Docker (if not already installed)

###  Step 3: Run Netdata Containe

### Step 4: Configure EC2 Security Group
Update your EC2 security group to allow TCP traffic on port 19999:

Type: Custom TCP

Port: 19999

Source: Your IP (for security)

### Step 5: Access Netdata Dashboard
Open a browser and visit:
http://13.201.132.218:19999
