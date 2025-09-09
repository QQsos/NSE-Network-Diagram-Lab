# NSE - Lab 1: Network Diagram

## 📘 Objective
The goal of this lab was to create a logical network diagram representing how traffic flows between internal and external systems, while practicing visualization of secure network design.

## 🖥️ Components Used
- 🌐 Internet  
- 🔥 Firewall  
- 📡 Router  
- 🔀 Switch  
- ⚖️ Load Balancer  
- 🌍 Web Servers  
- 💾 Database Server  
- 🖥️ End-user devices (PCs, VoIP, Wireless AP with Laptop, Smartphone, Printer)

## 📸 Network Diagram
![Network Diagram](./screenshots/task3_network_diagram.png)

## 📝 Lab Write-up
**1. Why did you construct your network the way that you did?**  
I designed my network with the firewall positioned between the Internet and the router to filter traffic. The switch serves as the hub for internal devices, while the load balancer distributes traffic to web servers. The database server is placed behind the web servers for security.  

**2. What did you learn about constructing a secure network?**  
I learned that segmentation and proper placement of firewalls, load balancers, and servers are critical for security. Visualizing the topology helps identify how traffic flows and where protections should be applied.  

## 📂 Deliverables
- `NSE-Lab1-Anthony-Escobar.pdf` – Final PDF submission for school.  
- `screenshots/task3_network_diagram.png` – Completed network diagram.  
