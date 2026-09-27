# Task 1 — Foundations & Environment Setup

## Objective
Build foundations in cybersecurity, networking, cryptography, Linux, and an isolated professional hacking lab.

## Covered topics
- CIA Triad: Confidentiality, Integrity, Availability
- Threats: phishing, malware, DDoS, SQL injection, brute force, ransomware
- Attack vectors: social engineering, wireless attacks, insider threats
- VirtualBox/VMware
- Kali Linux
- DVWA or Metasploitable2
- Host-only/private lab networking
- Linux navigation, permissions, package management, networking commands
- OSI/TCP-IP, DNS, HTTP/HTTPS, IP addressing, subnetting, NAT
- Symmetric/asymmetric cryptography, hashing, certificates, TLS
- Wireshark, Nmap, Burp Suite, Netcat

## Safe lab architecture
Internet (optional for updates only)
        |
   Host Computer
        |
  Host-only network
     /       \
   Kali     DVWA/Metasploitable2

Do not bridge the vulnerable VM directly to an untrusted network.

## Evidence checklist
- [ ] Kali VM desktop
- [ ] Target VM running
- [ ] Host-only adapter configuration
- [ ] Kali IP and target IP in the same private lab subnet
- [ ] Wireshark sample capture
- [ ] Nmap scan against the local target
- [ ] OpenSSL encryption/decryption demonstration
- [ ] Linux command cheat sheet

## Expected learning outcomes
Explain the CIA triad, basic threats, networking layers, common security tools, and why isolation matters.

## Video
Use `video/task1_narration.txt` for the 5-minute walkthrough.
