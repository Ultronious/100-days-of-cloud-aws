# Day 7: Change EC2 Instance Type

## 🎯 Objective
To modify the EC2 instance type in order to adjust compute resources based on workload requirements.

## 🛠️ Steps Performed
- Navigated to EC2 Dashboard
- Selected the running EC2 instance
- Stopped the instance
- Changed the instance type to a different configuration
- Started the instance after modification

## 🧠 Key Learnings
- Instance type determines CPU, memory, and network performance
- EC2 instance must be stopped before changing its type
- Changing instance type is a form of vertical scaling

## 📌 Real-World Use Case
Changing instance types is used to scale applications vertically, optimize costs, or upgrade performance during traffic spikes.

## ✅ Status
Completed
🎤 Interview Question

👉 Why must an EC2 instance be stopped before changing its instance type?

✅ Interview-Ready Answer (Use This)

“An EC2 instance must be stopped before changing its instance type because the instance type defines underlying hardware resources such as CPU, memory, and networking. These resources cannot be modified while the instance is running, so AWS requires the instance to be stopped to safely reallocate the hardware.”

⭐ Short Version (Rapid Round)

“Because instance type changes require underlying hardware reallocation, which can only be done when the instance is stopped.”

🧠 What Interviewers Are Checking

Understanding of hardware abstraction ✅

Knowledge of vertical scaling ✅

Awareness of AWS operational constraints ✅

📌 Optional Extra (If You Want to Sound Stronger)
“Stopping the instance ensures data consistency and prevents runtime failures during hardware changes.”
