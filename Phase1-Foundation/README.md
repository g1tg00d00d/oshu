# Phase 1: Foundation

## Security Mindset & Threat Modeling
| Type          | Resource                                                                                                                                                                                                                  | Status    |
| ------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------- |
| **Book**      | [Security Engineering 3rd Edition]() - Chapters 1-3, 22                                                                                                                                                                   | ⏳ Pending |
| **Framework** | [MITRE ATT&CK]() - Study Enterprise Matrix                                                                                                                                                                                | ⏳ Pending |
| **Paper**     | ["The Protection of Information in Computer Systems" (Saltzer & Schroeder, 1975]()                                                                                                                                        | ⏳ Pending |
| **Lab**       | Set up isolated security lab (VirtualBox + pfSense)<br><br>- Kali Linux 2024.4 (primary attack)<br>- Ubuntu 20.04 (target web server)<br>- Windows 10 (target desktop)<br>- pfSense (network segmentation and monitoring) |           |
| **Lab**       | Deploy DVWA and WebGoat in lab environment                                                                                                                                                                                |           |
| **Lab**       | Basic network reconnaissance using Nmap                                                                                                                                                                                   |           |
**Assessment**:
- Document 5 different attack vectors against your lab setup
- Create threat model diagram for a simple web application

---

## Web Application Security Deep Dive
| Type       | Resource                                                                                                                                                                          | Status    |
| ---------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------- |
| **Course** | [PortSwigger Web Security Academy]() - All labs in:<br>- SQL Injection<br>- Cross-site scripting (XSS)<br>- Cross-site request forgery (CSRF)<br>- Authentication vulnerabilities | ⏳ Pending |
| **Book**   | [The Web Application Hacker's Handbook]() - Chapters 1-9                                                                                                                          | ⏳ Pending |
| **Lab**    | Complete all DVWA challenges (low, medium, high security)                                                                                                                         | ⏳ Pending |
| **Lab**    | PortSwigger Academy labs - minimum 20 labs completed                                                                                                                              |           |
| **Lab**    | Burp Suite certification preparation                                                                                                                                              |           |
| **Lab**    | Build a vulnerable web app with 5 different vulnerability types                                                                                                                   |           
**Assessment**:
- Burp Suite Certified Practitioner exam (target: 80%+)
- Document 10 unique XSS payloads you've crafted
- Write technical blog post: "My First 30 Web Vulnerabilities"

**Monthly Publishing Requirement**: Technical writeup on web security fundamentals

---

## Network Protocols & Analysis
| Type        | Resource                                                                                                                                    | Status    |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------- | --------- |
| **Book**    | [TCP/IP Illustrated Volume 1](https://www.informit.com/store/tcp-ip-illustrated-volume-1-the-protocols-9780321336316) - Chapters 1-6, 17-20 | ⏳ Pending |
| **Study**   | RFC 793 (TCP), RFC 791 (IPv4), RFC 2616 (HTTP/1.1)                                                                                          | ⏳ Pending |
| **Lab**     | Wireshark mastery - analyze 10 different protocol captures                                                                                  | ⏳ Pending |
| **Lab**     | Build custom packet crafting tools with Scapy                                                                                               | ⏳ Pending |
| **Lab**     | Network reconnaissance methodology development                                                                                              | ⏳ Pending |
| **Project** | Python packet analyzer with protocol detection                                                                                              | ⏳ Pending |

---

## Wireless Security & Network Attacks
| Type         | Resource                                                 | Status    |
| ------------ | -------------------------------------------------------- | --------- |
| **Study**    | WPA/WPA2/WPA3 protocol specifications                    | ⏳ Pending |
| **Research** | Recent wireless attack papers (KRACK, DragonBlood, etc.) | ⏳ Pending |
| **Lab**      | Set up wireless security testing lab                     | ⏳ Pending |
| **Lab**      | WPA2 handshake capture and cracking                      | ⏳ Pending |
| **Lab**      | Evil twin and captive portal attacks                     | ⏳ Pending |
| **Lab**      | ARP poisoning and traffic interception                   | ⏳ Pending |
| **Project**  | Automated wireless security assessment tool              | ⏳ Pending |

---

## Linux Security Hardening & Exploitation
| Type      | Resource                                                                               | Status    |
| --------- | -------------------------------------------------------------------------------------- | --------- |
| **Book**  | [The Linux Programming Interface](https://man7.org/tlpi/) - Chapters 1-3, 15-17, 38-39 | ⏳ Pending |
| **Guide** | Linux Privilege Escalation                                                             | ⏳ Pending |
| **Lab**   | Build vulnerable Linux VMs with various misconfigurations                              | ⏳ Pending |
| **Lab**   | LinPEAS and LinEnum usage and analysis                                                 | ⏳ Pending |
| **Lab**   | Manual privilege escalation hunting                                                    | ⏳ Pending |
| **CTF**   | HTB: Own 5 Linux machines focusing on privesc                                          | ⏳ Pending |

---

## Windows Security & Active Directory
| Type         | Resource                                                                   | Status    |
| ------------ | -------------------------------------------------------------------------- | --------- |
| **Course**   | [Active Directory Security](https://www.pentesteracademy.com/course?id=47) | ⏳ Pending |
| **Research** | BloodHound methodology and common AD attack paths                          | ⏳ Pending |
| **Lab**      | Build Windows AD lab environment                                           | ⏳ Pending |
| **Lab**      | Kerberoasting and ASREPRoasting attacks                                    | ⏳ Pending |
| **Lab**      | BloodHound data collection and analysis                                    | ⏳ Pending |
| **CTF**      | HTB: Own 3 Windows machines with AD components                             | ⏳ Pending |
**Assessment**:
- Demonstrate complete domain compromise from unprivileged user
- Document 10 different Windows privilege escalation techniques

**Monthly Publishing Requirement**: "Active Directory Attack Chains: A Practical Analysis"

---

## Advanced Web Attacks
| Type      | Resource                                                                               | Status    |
| --------- | -------------------------------------------------------------------------------------- | --------- |
| **Book**  | [The Linux Programming Interface](https://man7.org/tlpi/) - Chapters 1-3, 15-17, 38-39 | ⏳ Pending |
| **Guide** | Linux Privilege Escalation                                                             | ⏳ Pending |
| **Lab**   | Build vulnerable Linux VMs with various misconfigurations                              | ⏳ Pending |
| **Lab**   | LinPEAS and LinEnum usage and analysis                                                 | ⏳ Pending |
| **Lab**   | Manual privilege escalation hunting                                                    | ⏳ Pending |
| **CTF**   | HTB: Own 5 Linux machines focusing on privesc                                          | ⏳ Pending |

---

#### JavaScript Security & Client-Side Attacks
| Type         | Resource                                                                   | Status    |
| ------------ | -------------------------------------------------------------------------- | --------- |
| **Course**   | [Active Directory Security](https://www.pentesteracademy.com/course?id=47) | ⏳ Pending |
| **Research** | BloodHound methodology and common AD attack paths                          | ⏳ Pending |
| **Lab**      | Build Windows AD lab environment                                           | ⏳ Pending |
| **Lab**      | Kerberoasting and ASREPRoasting attacks                                    | ⏳ Pending |
| **Lab**      | BloodHound data collection and analysis                                    | ⏳ Pending |
| **CTF**      | HTB: Own 3 Windows machines with AD components                             | ⏳ Pending |
**Assessment**:
- Demonstrate complete domain compromise from unprivileged user
- Document 10 different Windows privilege escalation techniques

**Monthly Publishing Requirement**: "Active Directory Attack Chains: A Practical Analysis"
