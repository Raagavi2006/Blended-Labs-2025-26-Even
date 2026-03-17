# Lab 5 – Build a Database Server (AWS)

## Author

* **Name**: RAAGAVI R M
* **Register Number**: 212224220074
* **Date of Submission**: 17-03-2026

---

## Objective

The objective of this experiment is to understand how to deploy and configure a database server in AWS. This lab focuses on launching an EC2 instance, installing a database management system (DBMS), configuring basic database settings, creating a sample database, and validating connectivity to the database server.

---

## Prerequisites

* Basic understanding of cloud computing concepts
* AWS account or AWS Academy Lab access
* An existing VPC and EC2 knowledge (from previous labs)
* Basic knowledge of Linux commands and SQL

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Security Groups
* SSH Client (Terminal / PuTTY)
* MySQL / MariaDB / PostgreSQL (any one)

---

## Tasks Performed

### Task 1: Launch EC2 Instance for Database Server

Launch a new EC2 instance using Amazon Linux 2 AMI. Select an appropriate instance type and configure key pair and security group.

---

### Task 2: Configure Security Group for Database Access

Modify the security group to allow:

* SSH (Port 22) for remote access
* Database port (e.g., MySQL – 3306 or PostgreSQL – 5432)

---

### Task 3: Connect to EC2 Instance

Connect to the EC2 instance using SSH from your local machine.

---

### Task 4: Install Database Server

Install a database server software such as MySQL, MariaDB, or PostgreSQL on the EC2 instance using package manager commands.

---

### Task 5: Start and Configure Database Service

Start the database service and configure basic settings such as root password and user privileges.

---

### Task 6: Create a Sample Database

Create a sample database and a table inside it. Insert a few records into the table.

---

### Task 7: Test Database Connectivity

Test the database server by connecting to it locally or remotely and performing basic SQL queries.

---

## Workflow (Student Explanation)

1. The workflow begins by launching a new EC2 instance through the AWS Management Console using the Amazon Linux 2 AMI, where an appropriate instance type is selected along with configuration of a key pair and security group for secure access.
2. Next, the security group is modified to allow inbound SSH access on port 22 for remote login and database access through the required port such as 3306 for MySQL or 5432 for PostgreSQL, ensuring proper connectivity to the database server.
3. The user then connects to the EC2 instance using SSH from the local machine, establishing a secure terminal session to perform further configurations and installations.
4. After connecting, a database server such as MySQL, MariaDB, or PostgreSQL is installed using the system’s package manager, enabling database functionality on the instance.
5. The database service is then started and configured by setting a root password and defining user privileges, followed by creating a sample database with a table and inserting records to test functionality, and finally verifying connectivity by executing basic SQL queries locally or remotely.

---

## Output Screenshots (Attach 3)

### Screenshot 1: EC2 Instance for Database Server

<img width="1919" height="1017" alt="Screenshot 2026-03-12 151350" src="https://github.com/user-attachments/assets/b3f4410f-70f3-4b87-b1d7-ffe3c7bd6b9a" />

---

### Screenshot 2: Database Service Running

<img width="1912" height="982" alt="Screenshot 2026-03-12 152949" src="https://github.com/user-attachments/assets/426d1673-6a80-47ac-b7c0-3928b2339af3" />

---

### Screenshot 3: Sample Database and Table

<img width="1909" height="1123" alt="Screenshot 2026-03-12 153600" src="https://github.com/user-attachments/assets/3ce5f236-6efe-4ada-a505-f5092390ed6b" />

---

## Result

This experiment demonstrated how to build a database server in AWS using an EC2 instance. By installing and configuring a DBMS, creating a sample database, and testing connectivity, the fundamentals of hosting and managing a cloud-based database server were underst
