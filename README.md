# Azure Project: Windows Server 2022 VM with Alerts

## 📘 Overview
This project demonstrates the deployment of a Windows Server 2022 Virtual Machine (VM) on Microsoft Azure, configuring alert rules, and enabling public access for remote management and monitoring.

## 🎯 Purpose of the Project
The purpose of this project is to simulate a real-world scenario where a cloud administrator needs to:
- Deploy a secure and accessible Windows Server 2022 virtual machine,
- Set up proactive monitoring using Azure Monitor Alerts, and
- Ensure high availability and remote access through public networking.

This project helps demonstrate practical skills in VM provisioning, system monitoring, and infrastructure configuration — which are essential for Azure administrators and IT support engineers in enterprise environments.


## 🧰 Tools & Services Used
- Azure Portal
- Windows Server 2022 (VM)
- Network Security Group (NSG)
- Azure Monitor Alerts
- Public IP & Inbound Rules

---


## ⚙️ Steps Performed

### ✅ Step 1: Create a Windows Server 2022 Virtual Machine
- Selected region, size, OS, and configured admin credentials.
- <img width="1920" height="1020" alt="Screenshot 2025-07-21 201248" src="https://github.com/user-attachments/assets/302dc9e9-3d26-4074-bc7e-f34708b69207" />
- <img width="1920" height="1020" alt="Screenshot 2025-07-21 201258" src="https://github.com/user-attachments/assets/f72c9cbc-cd21-43b1-9414-21614c77a1cb" />
- <img width="1920" height="1020" alt="Screenshot 2025-07-21 201309" src="https://github.com/user-attachments/assets/e56a5372-8708-467a-8832-a154af3cb761" />
- <img width="1920" height="1020" alt="Screenshot 2025-07-21 201318" src="https://github.com/user-attachments/assets/319b67e9-f14d-4e40-a4a9-de1e3172182b" />
- <img width="1920" height="1020" alt="Screenshot 2025-07-21 201333" src="https://github.com/user-attachments/assets/b83ae37f-8df5-4583-8c65-d704136d03ba" />
- <img width="1920" height="1020" alt="Screenshot 2025-07-21 201510" src="https://github.com/user-attachments/assets/07006880-5df7-4435-864b-3b10cf4505ea" />




### ✅ Step 2: Configure NSG & Public Inbound Access
- Allowed RDP (port 3389) and HTTP (if required) access via NSG.
- <img width="1920" height="1020" alt="Screenshot 2025-07-21 201510" src="https://github.com/user-attachments/assets/871f8b65-6e74-463a-b875-0c8ea4f7e5cf" />


### ✅ Step 3: Set Up Alert Conditions
- Created an Azure Monitor alert rule.
- Example: Trigger alert if CPU usage > 75%.
- <img width="1920" height="1020" alt="Screenshot 2025-07-21 202029" src="https://github.com/user-attachments/assets/0116e057-e58f-41af-bf53-4a7a942c7a4f" />


### ✅ Step 4: Create Users and Assign Roles (RBAC)
- Created Azure AD users from the portal.
- Assigned roles such as **Reader** and **Virtual Machine Contributor** to test scoped access.
- Verified that access was restricted according to role permissions.
- <img width="1920" height="1020" alt="Screenshot 2025-07-21 202222" src="https://github.com/user-attachments/assets/884fbc74-a2ee-4952-aaf9-ecae13ee235d" />



### ✅ Step 5: Deployment Testing of the VM
- <img width="1920" height="1020" alt="Screenshot 2025-07-21 202102" src="https://github.com/user-attachments/assets/1127b4aa-5162-4556-880d-4532d930eaee" />
- <img width="1920" height="1020" alt="Screenshot 2025-07-21 202307" src="https://github.com/user-attachments/assets/229669c6-e2e4-4def-9b4a-5fbf8207e6e2" />
- ![WhatsApp Image 2025-07-21 at 20 25 46_3c4a0680](https://github.com/user-attachments/assets/b5961909-89d2-4a51-96ba-bc601ed49762)
- ![WhatsApp Image 2025-07-21 at 20 25 47_5a0bb67e](https://github.com/user-attachments/assets/8e764b4c-3a63-4f7b-8a75-4b4927ae158b)


---


## ✅ Skills Gained
- Azure VM provisioning with Windows Server 2022
- NSG configuration for public access (RDP, HTTP)
- Azure Monitor Alerts & Action Groups
- Azure AD user creation and RBAC role assignment
- Testing deployment and alert notification

---

## 📅 Completion Date
July 2025

---

## 👤 Author
Mohammed Afnaan
