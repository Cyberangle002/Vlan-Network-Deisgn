
# Go Subnet – Network Subnetting Project

This project demonstrates how to design and simulate a subnetted network using Cisco Packet Tracer. It includes subnet calculations, device configuration, and connectivity validation.

---

## 🧠 Project Objectives

- Understand and implement IP subnetting.
- Configure routers, switches, and PCs with proper IP addresses.
- Verify connectivity using simulation mode in Cisco Packet Tracer.
- Test ping responses across subnets.

---

## 🛠️ Tools Used

- Cisco Packet Tracer
- Windows OS
- Basic Networking Devices (Router, Switches, PCs)
- Ethernet Cables


## 📄 Configuration Snippets (Optional)

Router> enable
Router# configure terminal 
Router(config)# interface g0/0 
Router(config-if)# ip address 192.168.1.1 255.255.255.224
Router(config-if)# no shutdown

## 👩‍💻 Author

**Aditi Shyam Pandit**  
📧 [aditipandit1331@gmail.com](mailto:aditipandit1331@gmail.com)  
🔗 [GitHub: Cyberangle002](https://github.com/Cyberangle002)  
🔗 [LinkedIn: aditipandit002](https://www.linkedin.com/in/aditipandit002)

---

## 📂 Report Download

👉 Full PDF Report: [Subnetting_Project_Report_Aditi_Shyam_Pandit.pdf](./Subnetting_Project_Report_Aditi_Shyam_Pandit.pdf)

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


=======

# 🖧 Office Network Simulation using Cisco Packet Tracer

This project showcases a simulated office network designed using **Cisco Packet Tracer**. It demonstrates a structured layout of routers, switches, and end devices connected with proper IP addressing, routing, and connectivity protocols.

## 📁 Files Included

- `Office Network Simulation.pkt`: The main Cisco Packet Tracer simulation file.

## 📝 Project Overview

The purpose of this simulation is to:

- Design a functional small-to-medium office network
- Implement static/dynamic routing between routers
- Ensure communication between PCs in different departments
- Use switches to manage LAN traffic
- Practice IP addressing and subnetting skills

## 🔧 Features

- 🛠 2 Routers, multiple switches, and PCs
- 🌐 Inter-VLAN Routing (if applicable)
- 📶 DHCP or Static IP addressing
- 🔁 RIP/EIGRP/OSPF or Static Routing
- 🧪 End-to-End Connectivity Testing with `ping`

## 📋 Device IP Address Table

| Device        | Interface       | IP Address      | Subnet Mask     |
|---------------|------------------|------------------|------------------|
| Router0       | G0/0             | 192.168.1.1      | 255.255.255.0    |
| Router0       | G0/1             | 10.0.0.1         | 255.255.255.252  |
| Router1       | G0/0             | 10.0.0.2         | 255.255.255.252  |
| Router1       | G0/1             | 192.168.2.1      | 255.255.255.0    |
| PC0           | NIC              | 192.168.1.10     | 255.255.255.0    |
| PC1           | NIC              | 192.168.1.11     | 255.255.255.0    |
| PC2           | NIC              | 192.168.2.10     | 255.255.255.0    |
| PC3           | NIC              | 192.168.2.11     | 255.255.255.0    |

## 📌 Static Routing Configuration

Here’s how static routing is configured between the two routers:

### On **Router0**
conf t
ip route 192.168.2.0 255.255.255.0 10.0.0.2
end
```

### On **Router1**
conf t
ip route 192.168.1.0 255.255.255.0 10.0.0.1
end
```

## 🚀 How to Use

1. Open Cisco Packet Tracer.
2. Load the `Office Network Simulation.pkt` file.
3. Explore device configurations, routing tables, and IP settings.
4. Use `ping` commands to test connectivity between devices.
5. Modify or extend the topology for deeper understanding.

## 🧠 Skills Practiced

- Network topology planning
- Static routing and IP subnetting
- Router & switch configuration
- Troubleshooting with Packet Tracer

## 📚 Requirements

- Cisco Packet Tracer 7.x or later
- Basic knowledge of networking concepts

## 🙋‍♀️ Author

**Aditi Shyam Pandit**  
Cybersecurity Student  
[LinkedIn](https://www.linkedin.com/in/aditipandit002/) | GitHub: [Cyberangle002](https://github.com/Cyberangle002)

---

Feel free to clone or fork this repository to explore and build upon the design!

