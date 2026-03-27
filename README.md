# Group-Policy-GPO-Lab

# 🖥️ GPO Lab: Centralized Management in Windows Domain

## 📌 Overview

This lab demonstrates how to centrally manage users and computers in a Windows domain environment using **Group Policy Objects (GPOs)**.

It focuses on applying security policies, controlling user environments, and enforcing organizational standards from a Domain Controller.

---

## 🎯 Objectives

* Enforce password complexity requirements
* Automatically map network drives
* Deploy a standardized desktop wallpaper
* Disable Control Panel access for standard users
* Block USB storage devices
* Test GPOs using different user accounts
* Document system behavior and results

---

## 🏗️ Lab Environment

* **Domain Controller (DC)**

  * Manages Active Directory and Group Policy

* **CLIENT1 (Windows Client)**

  * Used to test applied GPOs

* **WinClient-Lab VM**

  * Additional client for multi-user testing

* **Jira Server (Optional)**

  * Used for tracking tasks and lab progress

---

## ⚙️ Key Features Implemented

* 🔐 **Security Enforcement**

  * Password complexity policies
  * USB storage restrictions

* 🧑‍💼 **User Environment Control**

  * Desktop wallpaper deployment
  * Control Panel restrictions

* 🌐 **Network Configuration**

  * Automated drive mapping

---

## 🧪 Testing & Validation

* Tested policies with multiple user accounts
* Verified GPO application using:

  * `gpupdate /force`
  * `gpresult /r`
* Observed differences between administrative and standard users

---

## ✅ Expected Outcomes

* Understand how GPOs are created and linked
* Apply and enforce policies across domain-joined systems
* Validate policy application and troubleshoot issues
* Analyze the impact of policies on user experience

---

## 📝 Notes

* Ensure all machines are joined to the domain before testing
* Run command prompt as administrator when needed
* Some policies may require a system restart to apply

