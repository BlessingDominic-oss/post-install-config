# osTicket - Post-Install Configuration

This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.

---

![osTicket logo](https://i.imgur.com/Clzj7Xs.png)

## Environments and Technologies Used
- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

## Operating Systems Used
- Windows 10 (21H2)

## Post-Install Configuration Objectives
- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents
- Configure Users
- Configure SLA
- Configure Help Topics

---

## Configure Roles
**Path:** Admin Panel → Agents → Roles  

**Example: Supreme Admin**

![Definitions](https://i.imgur.com/SXpTf20.png)  
![Permissions](https://i.imgur.com/9fBmrZj.png)  
![More Permissions](https://i.imgur.com/1sDBsuZ.png)  
![Even More Permissions](https://i.imgur.com/2SVt7rt.png)  
![Sys Admin Success](https://i.imgur.com/vJl5MPw.png)

---

## Configure Departments
**Path:** Admin Panel → Agents → Departments  

**Example: System Administrators**

![System Administrators](https://i.imgur.com/83gWQsO.png)  
![System Administrators](https://i.imgur.com/oGLXmQv.png)

---

## Configure Teams
**Path:** Admin Panel → Agents → Teams  

**Example: Level II Support**

![Level II Support](https://i.imgur.com/BnPrcDH.png)

---

## Allow Anyone to Create Tickets
**Path:** Admin Panel → Settings → User Settings  

Make sure **"Require registration and login to create tickets"** is **not selected**:

![ticket creations](https://i.imgur.com/QsJjOuM.png)

---

## Configure Agents (Workers)
**Path:** Admin Panel → Agents → Add New  

**Example: Jane Doe**  
![Agent One Access](https://i.imgur.com/ujpOdKM.png)  

**Example: John Doe**  
![Agent Two](https://i.imgur.com/NcCP0v9.png)  
![Agent Two Access](https://i.imgur.com/aKTJ01A.png)

---

## Configure Users (Customers)
**Path:** Admin Panel → Users → Add New  

**Example: Ken User**  
![User Access](https://i.imgur.com/vbPd3uK.png)  

Repeat the same steps for **Karen User**.

---

## Configure SLA
**Path:** Admin Panel → Manage → SLA  

- **Sev-A**: 1 hour, 24/7  
- **Sev-B**: 4 hours, 24/7  
- **Sev-C**: 8 hours, business hours  

![Sev A](https://i.imgur.com/6AAF3Ju.png)  
![Sev B](https://i.imgur.com/izcD74X.png)  
![Sev C](https://i.imgur.com/xKzdp7w.png)

---

## Configure Help Topics
**Path:** Admin Panel → Manage → Help Topics  

Examples:  
- Business Critical Outage  
- Personal Computer Issues  
- Equipment Request  
- Password Reset  

![Business Critical Outage](https://i.imgur.com/Xdhp63v.png)  
![Personal Computer Issues](https://i.imgur.com/3Y7k2o1.png)  
![Equipment Request](https://i.imgur.com/Z0eIGea.png)  
![Password Reset](https://i.imgur.com/ndOdtTZ.png)

---

## Final Notes
This now fully configures osTicket.  
It is recommended to practice triaging and solving tickets.  

This is a very important skill to have for any help desk specialist, as they are the first line of communication between a company and its customers when it comes to handling issues regarding a product or service they provide.

