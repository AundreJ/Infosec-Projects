# 🔐 Azure Project: Self-Service Password Reset (SSPR)

## 📌 Overview
This project demonstrates how to configure and test Self-Service Password Reset (SSPR) using Microsoft Entra ID (formerly Azure AD). SSPR allows users to securely reset their passwords without IT intervention.

---

## ✅ Setup Steps

### 1. Enable SSPR
- Set to "Selected" and create a security group and name it. My is named `Interns`
- Assign test user to the group

### 2. Configure Authentication Methods
- Require 1 method. I added 2 methods for added layer of security
- Enabled: Email, Phone

### 3. Register as User
- URL: https://aka.ms/ssprsetup
- Register authentication methods

### 4. Reset Password
- URL: https://aka.ms/sspr
- Use phone or email to reset password

### 5. Audit
- Confirm SSPR events in Azure logs

---

## 🖼️ Screenshots
- Registration page
- Reset process
- Successful login
- Audit logs

---

## 🧠 What I Learned
- How to configure SSPR for specific users
- How to simulate a real user password reset
- Where to audit self-service security events in Entra!
