# Hands-on-C2-Infrastructure-Setup-Evasion-Internal-Network-Pivoting-CTF-Labs-SecByte-Index
A practical collection of cybersecurity CTF labs covering Command &amp; Control (C2) infrastructure design, initial access weaponization (macros, phishing), defense evasion (AMSI bypass, payload obfuscation, LOLBins), and internal network pivoting (SOCKS, SSH port forwarding, Chisel tunneling).
# C2 Infrastructure Setup, Defense Evasion & Internal Network Pivoting CTF Labs

Welcome to the **C2 Infrastructure Setup, Defense Evasion & Internal Network Pivoting CTF Lab Collection**. This repository serves as an organized, searchable catalog of practical cybersecurity labs hosted on Learn SecByte.

This collection focuses on technical offensive tradecraft and red team infrastructure engineering—including **Command & Control (C2) Redirector & Beacon Design**, **Initial Access Delivery (Phishing, Office Macros, Weaponized Docs)**, **Advanced Defense Evasion (AMSI Bypasses, Payload Obfuscation, LOLBins)**, and **Internal Network Pivoting & Tunneling (SOCKS, Port Forwarding, Chisel)**.

---

## Lab Collection Index

### 1. C2 Infrastructure & Initial Access Weaponization
* **C2 Infrastructure Setup: From Beacon Design to Operational Hygiene**  
  *Lab Link:* [https://learn.secbyte.org/ctf/c2-infrastructure-setup-from-beacon-design-to-operational-hy](https://learn.secbyte.org/ctf/c2-infrastructure-setup-from-beacon-design-to-operational-hy)  
  *Focus:* Setting up multi-tiered C2 architectures using redirectors (Apache/Nginx/CDN), custom malleable HTTP profiles, beacon staging, and operational hygiene practices.

<Image src="image_agent_tag_2240526297491839909" alt="Diagram showing C2 infrastructure redirector setup and secure operational channels" caption="Multi-Tiered C2 Infrastructure & Redirector Setup" />

---

* **Phishing Simulation Lab**  
  *Lab Link:* [https://learn.secbyte.org/ctf/phishing-simulation-lab](https://learn.secbyte.org/ctf/phishing-simulation-lab)  
  *Focus:* Building realistic social engineering campaigns, setting up SMTP relays, configuring SPF/DKIM/DMARC records for domain spoofing tests, and tracking click rates.

* **Weaponized Documents: The Hidden Chain**  
  *Lab Link:* [https://learn.secbyte.org/ctf/weaponized-documents-the-hidden-chain](https://learn.secbyte.org/ctf/weaponized-documents-the-hidden-chain)  
  *Focus:* Constructing multi-stage delivery payloads using malicious PDFs, ISO/LNK shortcuts, and embedded object execution chains.

* **Office Macro Attacks: From Suspicion to Detection**  
  *Lab Link:* [https://learn.secbyte.org/ctf/office-macro-attacks-from-suspicion-to-detection](https://learn.secbyte.org/ctf/office-macro-attacks-from-suspicion-to-detection)  
  *Focus:* Authoring VBA macros for shellcode execution, macro obfuscation techniques, bypassing trust center restrictions, and analyzing macro execution telemetry.

### 2. Defense Evasion, AMSI Bypass & Obfuscation
* **Payload Obfuscation Lab**  
  *Lab Link:* [https://learn.secbyte.org/ctf/payload-obfuscation-lab](https://learn.secbyte.org/ctf/payload-obfuscation-lab)  
  *Focus:* Obfuscating shellcode and binary executables using XOR/AES encryption, dynamic API resolution, string encoding, and anti-analysis routines.

* **AMSI Bypass Foundations: Defeating Script Scanning in Windows**  
  *Lab Link:* [https://learn.secbyte.org/ctf/amsi-bypass-foundations-defeating-script-scanning-in-windows](https://learn.secbyte.org/ctf/amsi-bypass-foundations-defeating-script-scanning-in-windows)  
  *Focus:* Understanding the Antimalware Scan Interface (AMSI) architecture, memory patching `AmsiScanBuffer`, string manipulation, and obfuscating PowerShell scripts.

* **Defense Evasion: Living Off The Land**  
  *Lab Link:* [https://learn.secbyte.org/ctf/defense-evasion-living-off-the-land](https://learn.secbyte.org/ctf/defense-evasion-living-off-the-land)  
  *Focus:* Executing attacks using legitimate Windows binaries (LOLBins such as `certutil`, `mshta`, `rundll32`, `bitsadmin`) to bypass application whitelisting.

* **AV Evasion Basics: Living Off The Land**  
  *Lab Link:* [https://learn.secbyte.org/ctf/av-evasion-basics-living-off-the-land](https://learn.secbyte.org/ctf/av-evasion-basics-living-off-the-land)  
  *Focus:* Bypassing static signature-based Antivirus scanning using native system utilities, unhooking user-mode APIs, and executing code in memory.

### 3. Internal Network Reconnaissance, Pivoting & Tunneling
* **Internal Network Exploration**  
  *Lab Link:* [https://learn.secbyte.org/ctf/internal-network-exploration](https://learn.secbyte.org/ctf/internal-network-exploration)  
  *Focus:* Conducting stealthy post-exploitation discovery across dual-homed subnets, ARP sweeping, DNS enumeration, and active host discovery.

* **Port Forwarding Lab**  
  *Lab Link:* [https://learn.secbyte.org/ctf/port-forwarding-lab](https://learn.secbyte.org/ctf/port-forwarding-lab)  
  *Focus:* Configuring local and remote SSH port forwarding (`ssh -L/-R`), `netsh interface portproxy`, and forwarding isolated internal services to external attack hosts.

<Image src="image_agent_tag_2240526297491838912" alt="Diagram showing network pivoting and SOCKS proxy tunneling through compromised dual-homed hosts" caption="Internal Network Pivoting & SOCKS Tunneling Flow" />

---

* **SOCKS Pivoting: The Internal Network Relay**  
  *Lab Link:* [https://learn.secbyte.org/ctf/socks-pivoting-the-internal-network-relay](https://learn.secbyte.org/ctf/socks-pivoting-the-internal-network-relay)  
  *Focus:* Establishing dynamic SOCKS4a/SOCKS5 proxies via SSH, Metasploit route management, Proxychains configuration, and routing attack tools through compromised hosts.

* **Chisel Tunneling: Pivoting Through a Dead-End Host**  
  *Lab Link:* [https://learn.secbyte.org/ctf/chisel-tunneling-pivoting-through-a-dead-end-host](https://learn.secbyte.org/ctf/chisel-tunneling-pivoting-through-a-dead-end-host)  
  *Focus:* Operationalizing Chisel over HTTP/S, bypassing strict egress firewall rules via TCP/UDP tunneling, and creating multi-hop pivot chains across segmented internal networks.

---

## Learning Path

### Path A: Red Team Infrastructure & Access Developer
1. **Infrastructure & Delivery:** Start with [C2 Infrastructure Setup](https://learn.secbyte.org/ctf/c2-infrastructure-setup-from-beacon-design-to-operational-hy), [Phishing Simulation Lab](https://learn.secbyte.org/ctf/phishing-simulation-lab), [Weaponized Documents](https://learn.secbyte.org/ctf/weaponized-documents-the-hidden-chain), and [Office Macro Attacks](https://learn.secbyte.org/ctf/office-macro-attacks-from-suspicion-to-detection).
2. **Evasion Engineering:** Master payload stealth via [Payload Obfuscation Lab](https://learn.secbyte.org/ctf/payload-obfuscation-lab), [AMSI Bypass Foundations](https://learn.secbyte.org/ctf/amsi-bypass-foundations-defeating-script-scanning-in-windows), [Defense Evasion: Living Off The Land](https://learn.secbyte.org/ctf/defense-evasion-living-off-the-land), and [AV Evasion Basics](https://learn.secbyte.org/ctf/av-evasion-basics-living-off-the-land).

### Path B: Network Movement & Tunneling Specialist
1. **Discovery:** Begin post-exploitation recon in [Internal Network Exploration](https://learn.secbyte.org/ctf/internal-network-exploration).
2. **Port Redirection:** Master port access in [Port Forwarding Lab](https://learn.secbyte.org/ctf/port-forwarding-lab).
3. **Advanced Pivoting:** Relay traffic through isolated networks using [SOCKS Pivoting: The Internal Network Relay](https://learn.secbyte.org/ctf/socks-pivoting-the-internal-network-relay) and [Chisel Tunneling](https://learn.secbyte.org/ctf/chisel-tunneling-pivoting-through-a-dead-end-host).

---

## How to Use the Labs

1. Select a practice scenario from the **Lab Collection Index**.
2. Click the direct link to launch the exercise environment on Learn SecByte.
3. Review scenario directives, execution flags, target system IPs, and network topologies.
4. Set up C2 redirectors, bypass AMSI script scanning, obfuscate payloads, or configure Chisel tunnels to route traffic across dual-homed targets to capture flags.

---

## Target Audience

* **Red Team Operators & Ethical Hackers:** Build resilient C2 infrastructure, bypass modern endpoint defenses (AMSI/AV), and master multi-hop pivoting.
* **Penetration Testers:** Tunnel security tooling through compromised pivot hosts into restricted internal subnets.
* **Detection Engineers & Blue Teamers:** Understand red team tradecraft, C2 egress signatures, AMSI bypass vectors, and tunneling behavior to build stronger detections.
* **Cybersecurity Students:** Acquire practical experience in advanced post-exploitation, proxying, and stealth payload delivery.

---

## Disclaimer

All lab links in this repository direct to official training environments hosted on Learn SecByte. All materials and exercises are provided strictly for educational purposes, defensive skill building, and authorized security research. Unauthorized testing against external systems or networks is strictly prohibited.
