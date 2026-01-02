Interview Question
What is a security group in AWS, and why is it called a stateful firewall?
“A security group in AWS acts as a virtual firewall for EC2 instances, controlling inbound and outbound traffic. It is called stateful because when an inbound rule allows traffic, the corresponding outbound response is automatically allowed, even if no outbound rule is explicitly defined.”

Stronger Answer (Stand-Out Version)
“A security group is a stateful virtual firewall attached to EC2 instances that controls inbound and outbound traffic using allow rules. Because it is stateful, return traffic is automatically permitted. Security groups operate at the instance level and are used to enforce least-privilege network access in AWS.”

# Day 2: Create Security Group

## 🎯 Objective
To control inbound and outbound network traffic for EC2 instances using security groups.

## 🛠️ Steps Performed
- Navigated to EC2 Dashboard
- Opened Security Groups section
- Created a new security group
- Added inbound rules for SSH (port 22)
- Restricted access using a specific IP range
- Associated the security group with an EC2 instance

## 🧠 Key Learnings
- Security groups act as virtual firewalls at the instance level
- They are stateful, allowing return traffic automatically
- Only allow rules are supported

## 📌 Real-World Use Case
Security groups are used to secure EC2 instances, databases, and load balancers by permitting only required network traffic.

## ✅ Status
Completed
