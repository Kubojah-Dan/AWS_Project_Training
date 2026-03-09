# AWS Cloud Practitioner - EC2 Web Server & SFTP Configuration

A comprehensive guide demonstrating the setup and configuration of EC2 instances, web servers, and secure file transfer on AWS.

---

## 📋 Table of Contents

1. [EC2 Windows Instance Setup](#1-ec2-windows-instance-setup)
2. [IIS Web Server Configuration](#2-iis-web-server-configuration)
3. [Elastic IP for Windows Server](#3-elastic-ip-for-windows-server)
4. [EC2 Linux Instance Setup](#4-ec2-linux-instance-setup)
5. [Apache Web Server Configuration](#5-apache-web-server-configuration)
6. [Elastic IP for Linux Server](#6-elastic-ip-for-linux-server)
7. [SFTP Configuration](#7-sftp-configuration)

---

## 1. EC2 Windows Instance Setup

### Objective
Deploy a Windows-based virtual machine on AWS EC2 to run Microsoft applications and services in the cloud.

### Key Features
- Virtual Windows Server environment
- Scalable compute capacity
- Integration with Microsoft software (SQL Server, IIS, .NET)

### Use Cases
- **Web Hosting**: IIS-based web applications
- **Database Servers**: SQL Server hosting
- **Remote Desktop**: RDS for cloud-based Windows desktops
- **Development**: Testing .NET and Windows applications

---

## 2. IIS Web Server Configuration

### Objective
Configure Internet Information Services (IIS) on Windows Server to host websites and web applications.

### What is IIS?
Microsoft's web server software for hosting and managing web applications on Windows Server, supporting HTTP, HTTPS, FTP, and more.

### Use Cases
- ASP.NET website hosting
- RESTful API deployment
- Secure file sharing via FTP
- Enterprise applications (SharePoint, Exchange)
- Web service hosting

---

## 3. Elastic IP for Windows Server

### Objective
Assign a static public IP address to maintain consistent accessibility for the Windows web server.

### Benefits
- **Persistent IP**: Remains constant across instance restarts
- **High Availability**: Quick reassignment during failover
- **Disaster Recovery**: Seamless IP migration to backup instances

### Best Practices
- Use only when necessary to minimize costs
- Release unused Elastic IPs
- Monitor usage regularly
- Implement as failover mechanism

---

## 4. EC2 Linux Instance Setup

### Objective
Deploy a Linux-based virtual machine on AWS EC2 for open-source application hosting.

### Key Features
- Linux operating system environment
- Support for Apache, MySQL, PHP stack
- SSH-based remote access

### Use Cases
- **Web Hosting**: Apache-based applications
- **Database Servers**: MySQL/PostgreSQL hosting
- **SSH Access**: Secure remote management
- **Development**: PHP, Python, Node.js applications

---

## 5. Apache Web Server Configuration

### Objective
Install and configure Apache HTTP Server on Linux instance for web application hosting.

### What is Apache?
Open-source web server software widely used for hosting websites and web applications on Linux systems.

### Use Cases
- Dynamic website hosting
- PHP application deployment
- RESTful API services
- Static content delivery
- Multi-site hosting with virtual hosts

---

## 6. Elastic IP for Linux Server

### Objective
Assign a static public IP address to the Linux web server for consistent network accessibility.

### Benefits
- **Stability**: Fixed IP for DNS configuration
- **Failover**: Quick instance replacement
- **Reliability**: Uninterrupted service during maintenance

### Best Practices
- Associate only with active instances
- Document IP assignments
- Implement monitoring and alerts
- Plan for disaster recovery scenarios

---

## 7. SFTP Configuration

### Objective
Enable Secure File Transfer Protocol (SFTP) on Linux server for encrypted file transfers.

### What is SFTP?
Secure network protocol for transferring files over SSH with encryption, providing a secure alternative to FTP.

### Key Features
- **Encryption**: All data encrypted during transmission
- **SSH Authentication**: Public key and password support
- **File Management**: Upload, download, rename, delete operations
- **Security**: Protection against eavesdropping and tampering

### Use Cases
- Secure file uploads to web server
- Automated backup transfers
- Content management for websites
- Secure data exchange between systems

---

## 🛠️ Technologies Used

- **AWS EC2**: Elastic Compute Cloud
- **Windows Server**: Microsoft IIS
- **Linux**: Apache HTTP Server
- **Elastic IP**: Static IP addressing
- **SFTP**: Secure file transfer over SSH

---

## 📝 Key Learnings

- EC2 instance provisioning and management
- Web server configuration (IIS and Apache)
- Network configuration with Elastic IPs
- Secure file transfer implementation
- AWS cloud infrastructure best practices

---

## 🔒 Security Considerations

- Use security groups to restrict access
- Enable encryption for data in transit
- Implement SSH key-based authentication
- Regular security updates and patches
- Monitor access logs and usage patterns

---

## 📚 Additional Resources

- [AWS EC2 Documentation](https://docs.aws.amazon.com/ec2/)
- [IIS Documentation](https://docs.microsoft.com/iis/)
- [Apache HTTP Server Documentation](https://httpd.apache.org/docs/)
- [AWS Elastic IP Guide](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/elastic-ip-addresses-eip.html)

---

**Project Status**: ✅ Completed

**Author**: AWS Cloud Practitioner (KUBOJA DANIEL)

**Year**: 2026
