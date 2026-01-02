Interview Question

What problem does gp3 EBS volume solve compared to gp2?

What gp2’s Limitation Was (Quick Context)

In gp2, performance (IOPS) scaled with volume size

To get higher IOPS, you had to increase storage

This caused unnecessary cost

✅ Interview-Ready Answer (Use This)

“gp3 solves the limitation of gp2 by decoupling performance from storage size. With gp3, IOPS and throughput can be configured independently of volume size, providing better performance control and lower cost compared to gp2.”

⭐ Short Version (Rapid Round)

“gp3 allows independent scaling of performance and storage, unlike gp2.”

🧠 What Interviewers Want to Hear

Performance vs storage decoupling ✅

Cost optimization ✅

Predictable performance ✅

# Day 5: Create GP3 Volume

## 🎯 Objective
To create a cost-effective EBS gp3 volume for scalable block storage.

## 🛠️ Steps Performed
- Opened EC2 Dashboard
- Navigated to Elastic Block Store → Volumes
- Created a new volume with:
  - Type: gp3
  - Size: 2 GiB
- Added Name tag for identification

## 🧠 Key Learnings
- gp3 decouples performance from storage size
- Offers better cost efficiency than gp2
- Provides predictable baseline performance

## 📌 Real-World Use Case
gp3 volumes are commonly used for application data, logs, and databases requiring consistent performance.

## ✅ Status
Completed

