# AWS Cloud Projects 🚀

This repository contains a set of hands-on AWS cloud infrastructure projects demonstrating networking, scalability, and high-availability configurations. These are real-world deployment scenarios useful for both beginners and intermediate-level cloud practitioners.

---

## 📌 List of Projects

### ✅ Project 1: Configure Elastic IP Address to Windows Webserver in AWS
- Launch a Windows EC2 instance.
- Install IIS (Internet Information Services) to host a sample website.
- Allocate and associate an Elastic IP (EIP) for consistent access.

### ✅ Project 2: Configure Elastic IP Address to Linux Webserver in AWS
- Launch a Linux EC2 instance (Amazon Linux / Ubuntu).
- Install Apache or NGINX to host a static web page.
- Allocate and assign an Elastic IP for stable external access.

### ✅ Project 3: Configure SFTP for Linux WebServer in AWS
- Set up a secure EC2 instance with Linux.
- Install and configure SFTP (vsftpd / OpenSSH).
- Add users and set directory permissions for secure file transfers.

### ✅ Project 4: Configure Network Load Balancer with 3 Servers
- Launch 3 backend EC2 instances with a web service.
- Configure a **Network Load Balancer (NLB)** for high throughput and TCP-based load balancing.
- Test traffic distribution and failover scenarios.

### ✅ Project 5: Configure Application Load Balancer with 3 Servers
- Launch 3 backend EC2 servers (with HTTP apps).
- Create an **Application Load Balancer (ALB)** with target groups.
- Test load balancing based on HTTP requests and health checks.

### ✅ Project 6: Configure Auto Scaling with Fault Tolerance
- Launch an Auto Scaling Group with a launch template.
- Set scaling policies (scale out/in based on CPU).
- Use health checks and load balancers to maintain fault tolerance.

---

## 🧰 Tools & Services Used

- **Amazon EC2**
- **Elastic IPs**
- **Security Groups & Key Pairs**
- **Application Load Balancer (ALB)**
- **Network Load Balancer (NLB)**
- **Auto Scaling Groups**
- **SFTP configuration (Linux)**

---

## 📚 Concepts Demonstrated

- Public IP vs Elastic IP
- Web server setup (Linux & Windows)
- Load balancing architectures
- Secure file transfer (SFTP)
- Auto Scaling with Health Checks
- Fault Tolerant deployments in AWS

---

## 🏁 How to Use

Each project has its own step-by-step setup. Clone this repository and follow instructions inside respective folders.

```bash
git clone https://github.com/Pradeep106-R/Aws_Cloud_Project.git
cd Aws_Cloud_Project/
