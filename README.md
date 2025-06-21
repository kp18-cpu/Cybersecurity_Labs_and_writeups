# Cybersecurity Lab Mastery: From Networking to Forensics and Beyond

This repository serves as a testament to my comprehensive understanding and practical mastery of various cybersecurity domains, as demonstrated through the successful completion of numerous hands-on labs. Each lab in this collection has allowed me to delve deep into the theoretical and practical aspects of cyber defense and offense, covering a wide spectrum of topics.

## Labs Covered:

Through these labs, I have gained extensive experience and a solid foundation in the following areas:

### Networking Fundamentals and Advanced Concepts:
* **DNS and DHCP Configuration:** I've mastered the intricacies of DNS resolution, including the step-by-step process of how a DNS client resolves a hostname, and how DNS caching works to improve performance. I've also gained practical experience in configuring DNS servers and creating DNS zones and records (A, AAAA, NS, MX, PTR).
* **DHCP Operations:** I understand the benefits of DHCP in network management, including automatic IP address assignment, centralized management, and efficient IP utilization. I've performed DHCP release and renewal operations and analyzed DHCP Discover, Offer, Request, and ACK packets.
* **Network Scanning with Nmap:** I have utilized Nmap for various scanning techniques, including SYN, Connect(), UDP, Null, FIN, and Xmas scans. I've analyzed scan reports to identify open ports, services, and operating systems, and understand the differences in how different scan types interact with firewalls.
* **Traffic Analysis with Wireshark:** I've used Wireshark to capture and analyze network traffic, including DNS queries and responses, and understood the protocols and ports involved.

### System Administration and Security:
* **User and Group Management in Linux:** I've performed user and group creation, modification, and deletion, and managed user privileges using `chmod` and `chown`. I've also explored the `/etc/shadow` file to understand password storage.
* **Password Policies:** I understand the importance of strong password policies, including length, complexity, and regular changes.
* **Firewall Configuration:** I've configured Windows Defender Firewall, enabling and disabling it to observe its impact on network connectivity (e.g., ping responses). I also understand the concept of Stateful Packet Inspection (SPI).
* **Security Policies and Procedures:** I've analyzed acceptable use policies (AUPs) and their importance in an organizational setting. I also have a foundational understanding of disaster recovery and business continuity planning, identifying crucial data for backup and key personnel involved.

### Digital Forensics:
* **Registry Analysis:** I've explored various Windows Registry keys to uncover valuable forensic artifacts, including Wi-Fi connection history, network adapter configurations, recently accessed files (`RecentDocs`, `OpenSavePidIMRU`, `LastVisitedPidIMRU`), and connected USB devices (both general and specific models). This demonstrates the ability to reconstruct user activity and identify external device connections.
* **Memory and Disk Forensics (HxD and Autopsy):** I've used HxD to examine raw disk images and executables (e.g., `msedge.exe`, `calc.exe`, `Nature-Wallpaper.jpg`) to identify embedded strings, file headers (magic numbers), and other hidden data. I've also utilized Autopsy for a more in-depth analysis of disk images, including identifying file types, recovering deleted files, and detecting encrypted data.
* **Steganography:** I've performed and analyzed steganography techniques using tools like Hide'n'Send and S-Tools, demonstrating the ability to conceal and extract hidden messages within image files.

### Exploitation and Attack Mitigation:
* **Metasploit Framework:** I've used Metasploit to perform various offensive operations, including:
    * **Payload Generation:** Creating executable payloads (e.g., `windows/x64/meterpreter/reverse_tcp`) for remote access.
    * **Listener Setup:** Configuring multi/handler listeners to receive reverse shell connections.
    * **System Information Gathering:** Using Meterpreter commands (`sysinfo`, `idletime`, `arp`, `ifconfig`, `ipconfig`, `netstat`, `route`, `shell`) to gather detailed information about the compromised system.
    * **Post-Exploitation Techniques:** Demonstrating keystroke sniffing (`keyscan_start`, `keyscan_dump`, `keyscan_stop`) to capture user input [cite: 902, 921, 922], and clearing event logs (`clearev`) to cover tracks. I've also explored enabling Remote Desktop Protocol (RDP) on a target machine.
* **Vulnerability Analysis (Metasploit Search):** I've used Metasploit's search capabilities to identify exploits for known vulnerabilities like EternalBlue (MS17-010) and MS08-067.
* **Understanding Cyber Threats:** I have a strong grasp of various malware types (Virus, Worm, Logic Bomb, Trojan Horse, Rootkit, Ransomware) and their definitions. I also understand different social engineering techniques (Phishing, Spear Phishing, Whaling) and their impact. I can differentiate between DoS and DDoS attacks.

### Cryptography:
* **Public Key Infrastructure (PKI) in Email:** I've practically applied OpenPGP for email encryption and digital signatures using Thunderbird, understanding the roles of public and private keys, session keys, and how they ensure confidentiality, integrity, and non-repudiation.
* **Ethical Considerations in Cryptography:** I've reflected on significant cases like the Apple vs. FBI debate and Australia's encryption laws, considering the balance between privacy and national security.
* **Conceptual Understanding of Cryptography:** I've analyzed the abstract nature of cryptography through a science fiction lens, understanding how seemingly innocuous information can hide deeper, critical meanings.

### Security Tools and Techniques:
* **Netcat (ncat):** I've used Netcat for establishing listening ports, transferring files, and creating simple command shells between machines.
* **Hping3:** I've utilized Hping3 for crafting custom TCP/IP packets to test firewall rules, perform advanced port scanning, and even transfer files.
* **Scapy:** I've employed Scapy for crafting and manipulating network packets at a high level, demonstrating the ability to send custom ICMP and TCP packets.

## Demonstrations of Mastery:

* **Hands-on Practicality:** All labs involved direct interaction with various operating systems (Kali Linux, Windows) and cybersecurity tools, solidifying theoretical knowledge with practical application.
* **Troubleshooting Expertise:** Encountered and successfully resolved issues, such as network connectivity problems in virtual environments and configuration challenges with security tools.
* **In-depth Analysis:** Provided detailed analyses of network traffic, system behavior, and forensic artifacts, demonstrating a keen eye for detail and strong analytical skills.
* **Comprehensive Understanding:** The breadth of topics covered, from fundamental networking to advanced exploitation and forensics, showcases a holistic understanding of the cybersecurity landscape.

This repository serves as a robust portfolio of my capabilities and dedication to the field of cybersecurity.
