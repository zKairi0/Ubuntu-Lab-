# 🧪 Lab 01: Ubuntu VM Setup and SSH Activation

**Date:** October 3, 2025  
**System:** Ubuntu VM  
**Purpose:** Initial system setup and SSH configuration

---

## 🔐 Step 1: Confirm Sudo Privileges
**Command:**
```
whoami
```
```
groups
```
```
sudo whoami
```
**Outcome:**
Confirmed sudo access and administrative privilages

![Confirming Sudo Privilages](Screenshots/Confirm%20Admin%20Permissions.png) 

---

## 🛠️ Step 2: Updating Ubuntu
**Command:**
```
sudo apt update && sudo apt upgrade -y
```
**Outcome:**
System packages successfully updated to the latest versions.

![Ubuntu Update](Screenshots/Updating%20Ubuntu.png)

---

## 📦 Step 3: SSH Installation
**Command:**
```
sudo apt install openssh-server -y
```
**Outcome:**
SSH server installed and ready for activation.

![SSH Installation](Screenshots/SSH%20Installation.png)

---

## 🚀 Step 4: SSH Activation
**Commands:**
```
systemctl status ssh
```
```
systemctl enable ssh
```
**Outcome:**
SSH service is active and enabled to start on boot.

![SSH Activation](Screenshots/SSH%20Activation.png)





