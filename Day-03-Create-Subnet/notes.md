Interview Question

Why is a subnet always associated with a single Availability Zone in AWS?

🧠 Simple Explanation (First)

Think of it like this:

An Availability Zone (AZ) is a separate data center.
A subnet is a logical network inside that data center.

You cannot stretch one local network across multiple physical locations.

✅ Correct Interview-Ready Answer (Use This)

“A subnet in AWS is always associated with a single Availability Zone because it represents a logical network within a specific physical data center. This design ensures low latency, fault isolation, and high availability. To achieve high availability across zones, AWS uses multiple subnets—one per Availability Zone.”

⭐ Short Answer (Quick Round)

“Because a subnet is a network tied to a single physical Availability Zone, and spreading it across zones would break isolation and reliability.”

🧠 What Interviewers Are Really Testing

Do you understand AZ isolation? ✅

Do you understand high availability design? ✅

Do you know why multiple subnets are needed? ✅

# Day 3: Create Subnet

## 🎯 Objective
To create a subnet within a VPC to organize and isolate AWS resources.

## 🛠️ Steps Performed
- Opened VPC Dashboard
- Selected an existing VPC
- Created a subnet with a valid CIDR block
- Chose a specific Availability Zone
- Verified subnet creation

## 🧠 Key Learnings
- Subnets are restricted to a single Availability Zone
- This design improves fault isolation and availability
- Proper CIDR planning avoids IP conflicts

## 📌 Real-World Use Case
Subnets are used to separate public and private resources and to design highly available architectures across multiple Availability Zones.

## ✅ Status
Completed

