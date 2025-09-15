# Implementing WAN for Remote Branch Connectivity

This repository contains our **Computer Networks Mini Project** demonstrating a full Wide Area Network (WAN) setup using **Cisco Packet Tracer**.

## 📋 Project Overview
The goal is to establish **secure and efficient connectivity** between two remote branches and a central Data Centre (DC).  
A **hub-and-spoke** topology is implemented where the DC router acts as the core, connecting all branch routers via WAN links.

### Key Features
- **Static Routing** for predictable packet delivery.
- **Wireless Connectivity** using WEP encryption.
- **Firewall Protection** in front of the web server.
- End-to-end **HTTP/HTTPS/TCP/IP** communication.
- Full configuration of routers, switches, access points, and end devices.

## 🖥️ Network Devices
- **Routers:** ISR series for branch and DC connectivity.
- **Switches:** 2960 for internal branch communication.
- **Wireless Access Points:** Provide Wi-Fi access with WEP encryption.
- **Firewall:** Secures the web server.

## ⚙️ IP Addressing (Examples)
- **Branch 1 Router:** 192.168.1.1 /24  
- **Branch 2 Router:** 192.168.2.1 /24  
- **DC Router (GigE):** 192.168.3.1 /24  
- **Web Server:** 192.168.3.2 /24

(See `CN_Miniproject_TEAM21.pdf` for full addressing tables.)

## 🚀 Results
- Verified connectivity between all branches and the DC.
- Successful wireless access and WEP authentication.
- Firewall rules applied to secure the web server.

## 🧰 Tools & Technologies
- **Cisco Packet Tracer** (simulation and configuration)
- Protocols: **TCP/IP, HTTP, HTTPS, ICMP, WEP**

## 📂 Repository Contents
- `CN_Miniproject_TEAM21.pdf` – Full project report with configurations.
- `network_topology.pkt` – Cisco Packet Tracer file .
  
## ▶️ How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/wan-remote-branch-connectivity.git
Open the .pkt file in Cisco Packet Tracer (version 8.x or later).

Follow the PDF report for configuration details.
