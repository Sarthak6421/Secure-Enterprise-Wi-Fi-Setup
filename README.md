# Secure-Enterprise-Wi-Fi-Setup
This project was developed during my internship at "Cisco" 
## 📌 Project Summary

## The goal was to:
- Secure the internal wireless network
- Prevent intruders from accessing company data
- Ensure uninterrupted connectivity for authorized employees


## 🔐 Key Implementations
✅ **Configured Static WAN IP**  
Ensured reliable and consistent external internet access by assigning a static WAN IP address.

✅ **Secured Wireless SSID**  
Created a protected SSID: `IT_Dept` with WPA2 encryption and updated default password from factory default to a custom password: `cisco123`.

✅ **MAC Address Filtering**  
Allowed only authorized employee devices (PC-PT Emp1, Emp2, Emp3) by enabling MAC filtering on the wireless router.

✅ **Hardened Router Login**  
Changed default admin credentials to strong, unique ones to protect the router from unauthorized configuration access.


## 🖥️ Network Topology Overview
- **Main Devices**:
  - DNS & Web Server (www.cisco.com)
  - Cisco ISR Router
  - Cisco Switch (2960)
  - Wireless Router (HomeRouter-PT)
  - PCs for Employees
  - One Intruder Laptop (blocked)
- **SSID**: IT_Dept  
- **Password**: cisco123 (secured using WPA2)

![Network Layout](./preview/network-layout.png)




## 🎯 Results
- Unauthorized device (Intruder Laptop) was successfully blocked.
- Internal Wi-Fi access is now limited to trusted employee devices.
- Secure, encrypted Wi-Fi connectivity enabled for all users.
- Router hardened against admin-level attacks.


## 🔗 Links
- 🌐 [GitHub Repo](https://github.com/your-username/secure-enterprise-wifi) *(Update this after uploading)*
- 💼 [LinkedIn Post](https://www.linkedin.com/in/sarthak-jadhav-128637306/) *(Share your achievement!)*


## 🛠️ Tools & Skills Used
- Cisco Packet Tracer
- Wireless Network Configuration
- MAC Address Filtering
- Router Security Best Practices
- Static IP & SSID Setup


## 📎 How to Use
1. Clone or download the repository.
2. Open the `.pkt` file in Cisco Packet Tracer (if shared).
3. Review Wi-Fi router settings and MAC filter list.
4. Simulate a connection from the intruder device to test protection.

