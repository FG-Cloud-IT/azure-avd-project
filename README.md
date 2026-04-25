# Azure Virtual Desktop (AVD) Deployment Lab

This project demonstrates a full deployment of an Azure Virtual Desktop (AVD) environment, including networking, identity management, and workspace configuration.

---

## 🚀 Project Overview

In this lab, I built a complete AVD environment in Microsoft Azure from scratch, configuring:

- Resource Group
- Virtual Network (VNet)
- NAT Gateway for outbound connectivity
- Azure Virtual Desktop host pool
- Microsoft Entra ID (Azure AD) groups and access control
- AVD Workspace and application access
- User authentication and testing

---

## 🏗️ Architecture

- Azure Virtual Network with subnet configuration
- NAT Gateway for secure outbound traffic
- Session host virtual machines
- Microsoft Entra ID for identity and access management
- Azure Virtual Desktop Workspace for user access

---

## 📋 Deployment Steps

### 1. Create Resource Group
- Organized all resources under a centralized resource group

### 2. Configure Virtual Network
- Created VNet and subnet for AVD infrastructure

### 3. Deploy NAT Gateway
- Configured outbound internet access

### 4. Create Azure Virtual Desktop
- Deployed host pool and session hosts

### 5. Configure Microsoft Entra ID
- Created groups and assigned users

### 6. Create AVD Workspace
- Linked application groups

### 7. Configure Authentication
- Enabled Entra ID login

### 8. Testing
- Verified access through Remote Desktop Web Client

### 9. Cost Optimization
- Deallocated VMs when not in use

---

## 📄 Full Documentation

👉 [AVD-Project.pdf](./AVD-Project.pdf)

---

## 🛠️ Technologies Used

- Microsoft Azure
- Azure Virtual Desktop (AVD)
- Microsoft Entra ID
- Virtual Networking
- NAT Gateway

---

## 🎯 Skills Demonstrated

- Cloud Infrastructure Deployment
- Identity and Access Management
- Azure Networking
- Virtual Desktop Environments

---

## 📌 Future Improvements

- Automate with Bicep or Terraform
- Add monitoring with Azure Monitor
