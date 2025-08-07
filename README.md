# 🌍 Inter-Region VPC Peering on AWS

This intermediate-level AWS networking project demonstrates how to create **Virtual Private Clouds (VPCs)** in **two different regions**, launch EC2 instances, and connect them using **Inter-Region VPC Peering**.

> 🎓 Cloud Project | AWS re/Start Journey  
> 🌐 Regions Used: Mumbai (ap-south-1) & Singapore (ap-southeast-1)  
> 🧑‍💻 Focus: VPC, Subnets, EC2, Route Tables, VPC Peering

---

## 📋 Project Steps

| Step | Action |
|------|--------|
| ✅ | Created `VPC-Mumbai` (10.0.0.0/16) with subnet `10.0.1.0/24` |
| ✅ | Launched Windows EC2 with public IP in Mumbai |
| ✅ | Created `VPC-Singapore` (20.0.0.0/16) with subnet `20.0.1.0/24` |
| ✅ | Launched Windows EC2 with public IP in Singapore |
| ✅ | Set up **Inter-Region VPC Peering** (Mumbai → Singapore) |
| ✅ | Accepted peering request in Singapore region |
| ✅ | Updated route tables in both VPCs |
| ✅ | Verified inter-region **ping/RDP connectivity** between EC2s |

📄 [View the detailed PDF report here](Inter-Region-VPC-Peering-AWS.pdf)

---

## 🧠 Key Learning Outcomes

- Created VPCs across **multiple AWS regions**
- Understood **VPC peering** architecture and setup
- Practiced **routing configuration** across regions
- Verified connectivity using **real EC2 testing**
- Gained insight into **multi-region AWS architecture**

---

## 🌐 Architecture Overview

> (Optional – Want me to generate a clean diagram of the multi-region VPC setup?)

---

## 🔐 Security Best Practices

- RDP allowed only from my IP
- No public IP on peered subnets except for testing
- Terminated all resources post-testing to avoid charges

---

## 🔄 What's Next?

- Setup peering using **Terraform**
- Use **Linux EC2 + SSH** across regions
- Add **cloud monitoring (CloudWatch)** for peered traffic

---

## 🙋‍♂️ About Me

I’m **Sayyed Hasir**, documenting and sharing my AWS learning journey through hands-on cloud projects.

This is my **4th project**, focusing on **real-world networking use cases** in the cloud.

---

## 🔗 Connect With Me

- 💼 [LinkedIn](https://www.linkedin.com/in/hasir-sayyed-b16520245?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app) 

