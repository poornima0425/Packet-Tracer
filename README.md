 WPA2-Enterprise WLAN Configuration on Cisco WLC (Packet Tracer)

## 📌 Project Overview
This project demonstrates the configuration of a secure enterprise wireless LAN using Cisco Wireless LAN Controller (WLC) in Packet Tracer. The system is designed using WPA2-Enterprise security with RADIUS authentication, replacing traditional WPA2-PSK for better scalability and centralized user management.

---

## 🎯 Objectives
- Configure a new VLAN interface on WLC
- Create and deploy a new WLAN (SSID-5)
- Configure internal DHCP scope for network devices
- Integrate RADIUS server for authentication
- Secure WLAN using WPA2-Enterprise (802.1X)
- Enable SNMP monitoring on WLC
- Connect and test wireless clients

---

## 🛠️ Technologies Used
- Cisco Packet Tracer
- Cisco Wireless LAN Controller (WLC)
- RADIUS Server (AAA Authentication)
- WPA2-Enterprise (802.1X)
- VLAN Configuration
- DHCP (Internal & Router-based)
- SNMP

---

## ⚙️ Configuration Summary

### VLAN Interface
- VLAN ID: 5  
- IP Address: 192.168.5.254/24  
- Gateway: 192.168.5.1  
- DHCP Server: 192.168.5.1  

### WLAN Setup
- SSID: SSID-5  
- Profile Name: Floor 2 Employees  
- Security: WPA2-Enterprise  
- Authentication: RADIUS (802.1X)  

### DHCP Scope (WLC Internal)
- Pool Range: 192.168.200.240 – 192.168.200.249  
- Network: 192.168.200.0/24  
- Status: Enabled  

### SNMP Configuration
- Community String: WLAN_SNMP  
- Trap Receiver: 172.31.1.254  

---

## 🔐 Key Features
- Centralized authentication using RADIUS server  
- Secure enterprise-grade wireless access  
- VLAN-based traffic segmentation  
- Automatic IP assignment via DHCP  
- Network monitoring via SNMP  

---

## 📡 Outcome
Successfully deployed a secure WPA2-Enterprise wireless network where clients authenticate using individual credentials and receive IP addresses dynamically, ensuring scalability, security, and centralized control.

---

## 👨‍💻 Author
Student Project – Cisco Networking Lab (Packet Tracer)
