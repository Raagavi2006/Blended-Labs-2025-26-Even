# Lab 3 – Introduction to Amazon Elastic Compute Cloud (EC2)

## Author

* **Name**: RAAGAVI R M
* **Register Number**: 212224220074
* **Date of Submission**: 17-03-2026

---

## Objective

The objective of this experiment is to understand the fundamentals of Amazon Elastic Compute Cloud (EC2). This lab focuses on launching and managing a virtual server, understanding instance types and AMIs, connecting to an EC2 instance, monitoring its status, and performing basic instance operations such as start, stop, and terminate.

---

## Prerequisites

* Basic understanding of cloud computing concepts
* AWS account or AWS Academy Lab access
* Web browser with internet connectivity
* Basic knowledge of Linux commands (optional)

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Key Pair
* Security Group
* SSH Client (PuTTY / Terminal)

---

## Tasks Performed

### Task 1: Explore Amazon EC2 Dashboard

Explore the EC2 service dashboard in the AWS Management Console. Observe the different sections such as Instances, AMIs, Instance Types, Key Pairs, Security Groups, and Elastic IPs.

---

### Task 2: Launch an EC2 Instance

Launch a new EC2 instance using Amazon Linux 2 AMI. Select an appropriate instance type (t2.micro) under the free tier. Configure basic settings such as instance name, key pair, and security group.

---

### Task 3: Configure Security Group

Configure a security group to allow inbound access:

* SSH (Port 22) from your IP address
* HTTP (Port 80) from anywhere (0.0.0.0/0)

This security group acts as a firewall for the instance.

---

### Task 4: Connect to EC2 Instance

Connect to the running EC2 instance using SSH. Use the downloaded key pair and connect via terminal or PuTTY.

For Amazon Linux:

```
ssh -i "keyname.pem" ec2-user@<Public-IP>
```

---

### Task 5: Perform Basic Instance Operations

Perform the following operations from the EC2 console:

* Stop the instance
* Start the instance
* Reboot the instance

Observe the state changes of the instance.

---

### Task 6: Monitor EC2 Instance

Monitor the EC2 instance using the Monitoring tab. Observe metrics such as CPU utilization, network in/out, and instance status checks.

---

### Task 7: Terminate EC2 Instance

Terminate the EC2 instance after completing the experiment to avoid unnecessary AWS charges.

---

## Workflow (Student Explanation)

1. The workflow begins by logging into the AWS Management Console and accessing the EC2 dashboard, where the user explores key components such as Instances, AMIs, Instance Types, Key Pairs, Security Groups, and Elastic IPs to understand the environment.
2. Next, a new EC2 instance is launched by selecting the Amazon Linux 2 AMI and choosing the t2.micro instance type under the free tier, followed by configuring basic settings including the instance name, key pair for secure access, and default options.
3. After launching, a security group is configured to act as a firewall by allowing inbound SSH access on port 22 from the user’s IP address and HTTP access on port 80 from anywhere, ensuring both secure and web-based connectivity.
4. The user then connects to the running instance using SSH with the downloaded key pair and performs basic operations such as stopping, starting, and rebooting the instance while observing its state transitions in the EC2 console.
5. Finally, the instance is monitored using the monitoring tab to view metrics like CPU utilization and network activity, and once the experiment is complete, the instance is terminated to prevent unnecessary charges.

---

## Output Screenshots (Attach 3)

### Screenshot 1: EC2 Dashboard / Instance List

<img width="1914" height="1011" alt="Screenshot 2026-02-17 111252" src="https://github.com/user-attachments/assets/0b21143e-2e60-48ff-ac3c-50aee0f37574" />

---

### Screenshot 2: SSH Connection to Instance

<img width="1910" height="1009" alt="Screenshot 2026-02-17 110950" src="https://github.com/user-attachments/assets/11540079-4255-4678-9c95-ea81e9010c81" />

---

### Screenshot 3: Instance Monitoring / Status

<img width="1919" height="1013" alt="Screenshot 2026-02-17 111422" src="https://github.com/user-attachments/assets/e3c04426-12c0-47a5-9383-145eeed4cb43" />

---

## Result 

This experiment provided hands-on experience with Amazon EC2 by demonstrating how to launch, connect, manage, and monitor a virtual server in AWS. It helped in understanding the concept of Infrastructure as a Service (IaaS) and how compute resources can be provisioned and controlled on demand in the cloud.
