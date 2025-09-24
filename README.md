# pfSense OpenVPN Project

This project demonstrates the configuration of **pfSense** with **OpenVPN**, using certificate-based authentication and firewall rules to enable secure client-to-LAN connectivity.  

The environment was built in **Oracle VirtualBox** with multiple Ubuntu VMs to simulate WAN and LAN clients. The project includes:  

- Setting up pfSense with WAN and LAN interfaces  
- Creating a Certificate Authority (CA), CRL, and server/client certificates  
- Deploying an OpenVPN server with tunnel and LAN networks  
- Configuring firewall rules for secure access  
- Exporting and importing OpenVPN client profiles  
- Verifying VPN connectivity with successful LAN access  

📸 Screenshots and documentation of the configuration process and troubleshooting steps are included in this repository.  

---

## Why This Project Matters

VPNs are a cornerstone of secure remote access. Configuring pfSense with OpenVPN provided hands-on experience
