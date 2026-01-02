# Day 1: Create Key Pair

## 🎯 Objective
To create an EC2 key pair for secure SSH access to Amazon EC2 instances.

## 🛠️ Steps Performed
- Navigated to EC2 Dashboard
- Opened Key Pairs section
- Created a new key pair
- Selected key type as RSA
- Downloaded and securely stored the private key (.pem)

## 🧠 Key Learnings
- Key pairs are used for secure, password-less authentication
- Private keys must be stored securely and cannot be retrieved again
- Key pairs are region-specific

## 📌 Real-World Use Case
Key pairs are used by DevOps and cloud engineers to securely access EC2 instances without exposing passwords.

## ✅ Status
Completed

🎤 Interviewer Question

“How did you create the EC2 key pair, and what format did you choose?”

🧠 Interviewer Expectation

Interviewers want to hear:

Why RSA?

Why .pem?

Security considerations

What happens if it’s lost?

✅ Improved Interview-Ready Answer (Use This)

“I created an EC2 key pair using the RSA algorithm and downloaded the private key in .pem format, which is required for SSH access to Linux-based EC2 instances. The .pem file is stored securely because AWS does not allow it to be downloaded again. RSA is commonly used because it’s widely supported and secure. If the key is lost, access must be recovered using methods like creating a new key pair and attaching it via a new instance or using EC2 Instance Connect.”

🧠 Bonus: One-Line Answer (Quick Round)

“I created an RSA key pair and downloaded the .pem file for secure SSH access to a Linux EC2 instance.”
