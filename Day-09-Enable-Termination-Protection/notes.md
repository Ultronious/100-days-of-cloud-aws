# Day 9: Enable Termination Protection for EC2 Instance

## 🎯 Objective
To prevent accidental deletion of an EC2 instance by enabling termination protection.

## 🛠️ Steps Performed
- Navigated to EC2 Dashboard
- Selected the EC2 instance
- Opened Instance settings
- Enabled Termination Protection
- Verified that termination was blocked

## 🧠 Key Learnings
- Termination protection prevents accidental deletion of EC2 instances
- It must be disabled before an instance can be terminated
- Useful for safeguarding critical or production workloads

## 📌 Real-World Use Case
Termination protection is commonly enabled on production EC2 instances to avoid accidental data loss or service disruption caused by human error.

## ✅ Status
Completed
🎤 Interview Question
👉 Can an EC2 instance with termination protection enabled be deleted? If yes, how?
✅ Interview-Ready Answer (Use This)
“An EC2 instance with termination protection enabled cannot be deleted until termination protection is explicitly disabled. Once the protection is turned off, the instance can then be terminated.”

- Termination protection must be disabled before deleting an EC2 instance
