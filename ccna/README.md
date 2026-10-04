# 🌐 CCNA 200-301 Study Notes

**Comprehensive study notes for Cisco Certified Network Associate (CCNA) certification**

[![License](https://img.shields.io/badge/License-CC_BY--NC--SA_4.0-blue.svg)](../LICENSE)
[![Status](https://img.shields.io/badge/Status-Complete-brightgreen.svg)]()
[![Chapters](https://img.shields.io/badge/Chapters-53-blue.svg)]()
[![CCNA](https://img.shields.io/badge/Certification-CCNA_200--301-orange.svg)]()

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Topics Covered](#-topics-covered)
- [Chapter Index](#-chapter-index)
- [Usage](#-usage)
- [Structure](#-structure)
- [Source Material](#-source-material)
- [License](#-license)
- [Author](#-author)

---

## 🎯 Overview

This repository contains **comprehensive study notes** for the **Cisco CCNA 200-301** certification exam. The notes cover all major networking topics required for the certification, including **networking fundamentals, IP connectivity, IP services, security fundamentals, automation, and programmability**.

These notes are structured following the official CCNA curriculum and are designed as a complete reference for anyone preparing for the CCNA exam or looking to deepen their understanding of enterprise networking.

### Why These Notes?

- **📚 Complete Coverage**: All 53 chapters covering the entire CCNA blueprint
- **🎯 Exam-Focused**: Aligned with CCNA 200-301 exam topics
- **📝 Well-Structured**: Clear formatting with examples, tables, and diagrams
- **🔍 Easy Navigation**: Sequential chapter numbering for quick reference
- **💡 Practical**: Real-world configurations and troubleshooting scenarios
- **🆓 Open Source**: Freely available for educational purposes

---

## 🛠 Topics Covered

### **Networking Fundamentals**
- TCP/IP Model and OSI Model
- Ethernet LANs and WANs
- IPv4 and IPv6 Addressing
- Subnetting and VLSM

### **Network Access**
- Ethernet Switching (Layer 2)
- VLANs and Trunking
- Spanning Tree Protocol (STP/RSTP)
- EtherChannel Configuration
- Wireless LANs (802.11)

### **IP Connectivity**
- IPv4 and IPv6 Routing
- Static and Dynamic Routing
- OSPF Configuration and Troubleshooting
- First Hop Redundancy Protocols (HSRP, VRRP, GLBP)

### **IP Services**
- NAT and PAT
- DHCP and DNS
- NTP and SNMP
- Quality of Service (QoS)
- TFTP and FTP

### **Security Fundamentals**
- Access Control Lists (ACLs)
- Port Security
- DHCP Snooping
- Dynamic ARP Inspection
- AAA and 802.1X
- Wireless Security (WPA2, WPA3)

### **Automation and Programmability**
- Controller-Based Networking
- Cisco DNA Center
- REST APIs and JSON
- Ansible and Terraform Basics

---

## 📚 Chapter Index

### **Part I: Networking Fundamentals (Chapters 1-5)**
1. [Introduction to TCP/IP Networking](1.md)
2. [Fundamentals of Ethernet LANs](2.md)
3. [Fundamentals of WANs and IP Routing](3.md)
4. [Using the Command-Line Interface (CLI)](4.md)
5. [Analyzing Ethernet LAN Switching](5.md)

### **Part II: Implementing Ethernet LANs (Chapters 6-10)**
6. [Configuring Basic Switch Management](6.md)
7. [Configuring and Verifying Switch Interfaces](7.md)
8. [Implementing Ethernet Virtual LANs](8.md)
9. [Spanning Tree Protocol Concepts](9.md)
10. [RSTP and EtherChannel Configuration](10.md)

### **Part III: IPv4 Addressing and Subnetting (Chapters 11-15)**
11. [Perspectives on IPv4 Subnetting](11.md)
12. [Analyzing Classful IPv4 Networks](12.md)
13. [Analyzing Subnet Masks](13.md)
14. [Analyzing Existing Subnets](14.md)
15. [Subnet Design](15.md)

### **Part IV: IPv4 Routing (Chapters 16-24)**
16. [Operating Cisco Routers](16.md)
17. [Configuring IPv4 Addresses and Static Routes](17.md)
18. [IP Routing in the LAN](18.md)
19. [IP Addressing on Hosts](19.md)
20. [Troubleshooting IPv4 Routing](20.md)
21. [Understanding OSPF Concepts](21.md)
22. [Implementing Basic OSPF Features](22.md)
23. [Implementing Optional OSPF Features](23.md)
24. [OSPF Neighbors and Route Selection](24.md)

### **Part V: IPv6 (Chapters 25-29)**
25. [Fundamentals of IP Version 6](25.md)
26. [IPv6 Addressing and Subnetting](26.md)
27. [Implementing IPv6 Addressing on Routers](27.md)
28. [Implementing IPv6 Addressing on Hosts](28.md)
29. [Implementing IPv6 Routing](29.md)

### **Part VI: Wireless LANs (Chapters 30-33)**
30. [Fundamentals of Wireless Networks](30.md)
31. [Analyzing Cisco Wireless Architectures](31.md)
32. [Securing Wireless Networks](32.md)
33. [Building a Wireless LAN](33.md)

### **Part VII: Network Services and Security (Chapters 34-43)**
34. [Introduction to TCP/IP Transport and Applications](34.md)
35. [Basic IPv4 Access Control Lists](35.md)
36. [Named and Extended IP ACLs](36.md)
37. [Applied IP ACLs](37.md)
38. [Security Architectures](38.md)
39. [Securing Network Devices](39.md)
40. [Implementing Switch Port Security](40.md)
41. [DHCP Snooping and ARP Inspection](41.md)
42. [Device Management Protocols](42.md)
43. [Network Address Translation](43.md)

### **Part VIII: Advanced Topics (Chapters 44-53)**
44. [Quality of Service (QoS)](44.md)
45. [First Hop Redundancy Protocols (FHRP)](45.md)
46. [SNMP, FTP, and TFTP](46.md)
47. [LAN Architecture](47.md)
48. [WAN Architecture](48.md)
49. [Cloud Architecture](49.md)
50. [Introduction to Controller-Based Networking](50.md)
51. [Cisco Software-Defined Access](51.md)
52. [Understanding REST and JSON](52.md)
53. [Understanding Ansible and Terraform](53.md)

---

## 💻 Usage

### Browsing Notes

Each chapter is a standalone Markdown file that can be viewed directly on GitHub or in any Markdown reader.

```bash
# Clone the repository
git clone https://github.com/ulpati/certifications.git
cd certifications/ccna

# View a specific chapter
cat 1.md     # Chapter 1: TCP/IP Networking
cat 21.md    # Chapter 21: OSPF Concepts
cat 53.md    # Chapter 53: Ansible and Terraform
```

### Searching for Topics

```bash
# Search across all chapters
grep -i "spanning tree" *.md
grep -i "OSPF" *.md
grep -i "VLAN" *.md

# Find chapters containing specific keywords
grep -l "access control" *.md
```

### Converting to PDF (Optional)

If you want to convert notes to PDF for offline reading:

```bash
# Using pandoc (install first: apt install pandoc)
pandoc 1.md -o chapter1.pdf
pandoc *.md -o ccna_complete_notes.pdf
```

---

## 📁 Structure

```
ccna/
├── README.md              # This file
├── 1.md                   # Chapter 1: TCP/IP Networking
├── 2.md                   # Chapter 2: Ethernet LANs
├── 3.md                   # Chapter 3: WANs and IP Routing
├── ...                    # Chapters 4-52
└── 53.md                  # Chapter 53: Ansible and Terraform
```

**File Naming Convention:**
- Files are numbered sequentially (1.md through 53.md)
- Numbers correspond to official CCNA chapter order
- Use this README's [Chapter Index](#-chapter-index) for descriptive titles

---

## 📖 Source Material

These study notes are adapted and rewritten for educational purposes from:

**📚 CCNA 200-301 Official Cert Guide Library**
- **Author**: Wendell Odom
- **Publisher**: Cisco Press
- **Edition**: CCNA 200-301 (Current version)
- **Volumes**: Volume 1 & Volume 2

> **Note**: These notes are personal study materials created for educational purposes. For the official curriculum and certification details, visit [Cisco's CCNA page](https://www.cisco.com/c/en/us/training-events/training-certifications/certifications/associate/ccna.html).
>
> **Copyright and trademarks**: the chapters summarise and adapt *CCNA 200-301 Official Cert Guide* by Wendell Odom (Cisco Press). The original text, figures and structure remain the property of their copyright holders, and the license of this repository applies only to the author's own wording. CCNA and Cisco are trademarks of Cisco Systems, Inc.; this project is not affiliated with or endorsed by Cisco.

---

## 📄 License

This project is licensed under the **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)**.

You are free to:
- **Share** — copy and redistribute the material in any medium or format
- **Adapt** — remix, transform, and build upon the material

Under the following terms:
- **Attribution** — You must give appropriate credit
- **NonCommercial** — You may not use the material for commercial purposes
- **ShareAlike** — If you remix, transform, or build upon the material, you must distribute your contributions under the same license

See the [LICENSE](../LICENSE) file for complete details.

---

## 🙏 Acknowledgements

- **Wendell Odom** for the comprehensive CCNA Official Cert Guide
- **Cisco Systems** for the CCNA certification program
- **Cisco Press** for publishing quality networking education materials
- The networking community for continuous learning and support

---

## 👤 Author

**ulpati**

- 🐙 GitHub: [@ulpati](https://github.com/ulpati)
- 📦 Repository: [certifications](https://github.com/ulpati/certifications)

---

## 📊 Study Tips

### Recommended Study Approach

1. **Sequential Learning**: Follow chapters in order (1-53) for structured learning
2. **Hands-On Practice**: Use GNS3, Packet Tracer, or EVE-NG for configuration practice
3. **Review Regularly**: Revisit chapters periodically to reinforce concepts
4. **Lab Practice**: Build real networks or virtual labs to apply concepts
5. **Practice Exams**: Use Boson ExSim or Pearson practice tests

### Key Focus Areas

- ⭐ **Subnetting**: Master chapters 11-15 thoroughly
- ⭐ **OSPF**: Chapters 21-24 are critical for routing
- ⭐ **VLANs and Trunking**: Essential switching concepts (chapters 8-9)
- ⭐ **IPv6**: Growing importance (chapters 25-29)
- ⭐ **Security**: ACLs and port security (chapters 35-41)
- ⭐ **Automation**: New CCNA topics (chapters 50-53)

---

**Good luck with your CCNA studies!** 🎓🚀

*Last updated: December 2025*
