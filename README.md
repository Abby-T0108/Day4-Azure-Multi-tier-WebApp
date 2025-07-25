Day 4: Secure Multi-Tier Web Application on Azure

Objective:
Successfully deployed a secure, multi-tier web application on Azure with a web server and an app server using Azure Load Balancer, Network Security Groups (NSGs), Azure SQL Database and Azure Firewall.

Key Achievements:
•	Deployed a multi-tier web application on Azure  
•	Configured load balancing for high availability  
•	Implemented network security with NSGs and Firewall
•	Set up a managed database with proper security 
•	Created network segmentation with subnets  
•	Tested end-to-end functionality
•	Documented the architecture  
•	Cleaned up resources to avoid charges

Skills Learned:
•	Azure Virtual Networks and subnet design
•	Virtual Machine deployment and management
•	Load Balancer configuration
•	Azure SQL Database setup and security
•	Network Security Groups (NSG) rule creation
•	Azure Firewall deployment
•	SSH connectivity and Linux administration
•	Cost management and resource cleanup

Architecture Overview:
•	Virtual Network (VNet): Segregated into Public and Private subnets.
•	Web Server: Deployed in the Public subnet with Load Balancer.
•	App Server: Deployed in the Private subnet, accessible only through the Web Server.
•	Database: Configured with Azure SQL Database, secured with firewall rules.
•	Security: Managed with NSGs and Azure Firewall to protect resources.

Testing:
•	SSH Access: Validated that the app server is not directly accessible via SSH (as expected, no public IP).
•	Port Blocking: Validated that RDP on port 3389 was blocked externally.
•	End-to-End Connectivity: Ensured proper communication between the web server and app server using private IPs.


Screenshots:
screenshots for each deployed resource (VNet, Load Balancer, Web/App Servers, NSG settings, Firewall, and SQL Database).
