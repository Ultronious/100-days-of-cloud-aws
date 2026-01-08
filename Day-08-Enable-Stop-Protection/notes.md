# Day 8: Enable Stop Protection for EC2 Instance

## 🎯 Objective
To prevent accidental stopping of a critical EC2 instance by enabling stop protection.

## 🛠️ Steps Performed
- Navigated to EC2 Dashboard
- Selected the EC2 instance
- Opened Instance settings
- Enabled Stop Protection
- Verified the protection setting

## 🧠 Key Learnings
- Stop protection prevents an instance from being stopped accidentally
- It adds an extra safety layer for critical workloads
- The instance must be running to enable stop protection

## 📌 Real-World Use Case
Stop protection is used for production or critical EC2 instances where accidental downtime could impact business operations.

## ✅ Status
Completed
What is Stop Protection in EC2, and how is it different from Termination Protection?
🧠 Simple Explanation (No Jargon)

Stop Protection
→ Prevents someone from stopping an EC2 instance by mistake

Termination Protection
→ Prevents someone from deleting (terminating) an EC2 instance by mistake

They protect against two different actions.

✅ Interview-Ready Answer (Use This)

“Stop protection prevents an EC2 instance from being accidentally stopped, while termination protection prevents the instance from being permanently deleted. Both are safety features used to protect critical workloads, but they guard against different lifecycle actions.”
- Stop protection and termination protection serve different purposes
- Both help prevent human error in production environments
