# 🔐 Flowchart – User Authentication Process

## 🎯 Objective

This document describes the flowchart outlining the **User Authentication** process for the Airbnb Clone backend. Authentication is a core feature that ensures secure access to the platform for both guests and hosts.

---

## 🧭 Flowchart Overview: User Login & Authentication

This flowchart demonstrates the step-by-step backend logic when a user attempts to log into the platform.

### ✅ Workflow Steps

1. **Start**
2. **Display Login Form**
3. **User Enters Email and Password**
4. **Validate Input Format**
5. **Check if User Exists in Database**
6. **If user not found:**
   - Return error: *"User not registered"*
7. **If user found:**
   - Compare input password with stored hashed password
8. **If password mismatch:**
   - Return error: *"Invalid credentials"*
9. **If credentials match:**
   - Generate JWT access token
   - Store login session (if applicable)
10. **Send success response & redirect user to dashboard**
11. **End**
