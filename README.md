# Networkwalks-B084-Week2-Penetration-Testing-Report
# PENETRATION TESTING REPORT 
### Footprinting & Network Scanning Phases

**W2-PM-FINAL  |  CYBERSECURITY  |  NETWORKWALKS**

| Field | Detail |
|---|---|
| **Pentester Name (Cybersecurity Professional)** | **Masonwabe Manana** |
| **Program/Batch** | B084-Networkwalks |
| **Date** | 14 November 2026 |
| **Modules completed** | W2-PM1 (Multiple Kali Tools)<br>W2-PM5 (Zenmap Scanning)<br> Pentesting Report|
| **Client/Target** | 1. Networkwalks (written permission granted)<br>2. My own local LAN Network |
| **Permission secured from client?** | Yes |
| **Phases covered** | **Phase 1:**  Footprinting & Reconnaissance<br>**Phase 2:** Network scanning with Zenmap

# 1. Liability Disclaimer

This project involves footprinting, reconnaissance, and network scanning using Zenmap. Prior authorization was obtained for all devices scanned, and all materials are utilised strictly for educational and research purposes.

# 2. Introduction

This report covers footprinting and reconnaissance on the 'networkwalks.com' domain using multiple Kali Linux tools. It also includes scanning of local IP addresses using Zenmap. Footprinting and reconnaisance allows vulnerabilities in systems to be detected quickly.
Commands for footprinting were ran on kali linux, while scanning was through Zenmap installed on windows.

# 3. Tools Used

| Kali Linux & Windows            
| WHOIS                
| whatweb            
| nslookup             
| curl -I              
| wafw00f              
| dnsrecon             
| Zenmap (Nmap GUI)    
| Windows CMD          

# 4. Activities Performed

 4.1 Footprinting & Reconnaissance

'Networkwalks.com' was used as the target network for this project, therefore will be referred to as the 'target' through its entirety. The first step was to gather information about the target. I used six kali linux tools for this; they include whois, whatweb, nslookup, curl, waf00f and dnsrecon. Whois was used to find out who owns the website, by showing the domain registration information. Whatweb identified the technologies used to build the website. Nslookup was used to collect basic domain name system (DNS) of the target network. 
Curl was used to detect the responding HTTP headers. Waf00f was used to list and identify firewalls protecting the target. Dnsrecon was used to dig all DNS of the target.


# 5. Network Scanning with Zenmap

Zenmap was used to scan local network. Here, I identified my local IP address and subnet, local live hosts, with their IP and MAC addresses generated on a network topology.

I first used the Windows `ipconfig` command to identify my local IP address and LAN subnet. I then entered the subnet into Zenmap and selected **Ping Scan** to identify active hosts.

The example results provided in the practical identified four live hosts:

- `10.0.0.1`
- `10.0.0.4`
- `10.0.0.19`
- `10.0.0.5`


# 8. Evidences Collected

*Screenshots for the activities*

Domain registration details of the target

![image alt](https://github.com/Masonwabeshana/Networkwalks-B084-Week2-Penetration-Testing-Report/blob/1bcfaa7c57036f9767e906035efc9dc2eaf0c6be/Screenshot%202026-11-14%20192223.png)

![image alt](https://github.com/Masonwabeshana/Networkwalks-B084-Week2-Penetration-Testing-Report/blob/1243b33e974783548dd06cb1e30de2d466e97be6/Screenshot%202026-11-14%20192941.png)



Fingerprinting the target website

![image alt](https://github.com/Masonwabeshana/Networkwalks-B084-Week2-Penetration-Testing-Report/blob/a8e2b6fd53545c6712d555c5865870f9c631c1e4/Screenshot%202026-11-14%20192655.png)


DNS information of the target

![image alt](https://github.com/Masonwabeshana/Networkwalks-B084-Week2-Penetration-Testing-Report/blob/2e21cac3dcc0d8635afe463345ccc9c186859be9/Screenshot%202026-11-14%20193223.png)

HTTP response headers of the target

![image alt](https://github.com/Masonwabeshana/Networkwalks-B084-Week2-Penetration-Testing-Report/blob/23877a2654eb9c6bda6673cbba398b9a21af607b/Screenshot%202026-11-14%20193516.png)

Detecting Web application firewall of the target

![image alt](https://github.com/Masonwabeshana/Networkwalks-B084-Week2-Penetration-Testing-Report/blob/2bf22aff5fb7c0e4b9a724a80dac2b4305d0ea78/Screenshot%202026-11-14%20193731.png)

Finding hidden subdomains and servers of the target


![image alt](https://github.com/Masonwabeshana/Networkwalks-B084-Week2-Penetration-Testing-Report/blob/d98be6ff91ea2cea894f069f7cd83d5fbe7cbbab/Screenshot%202026-11-14%20193948.png)


*Scanning local IP addresses using Zenmap*

![image alt](https://github.com/Masonwabeshana/Networkwalks-B084-Week2-Penetration-Testing-Report/blob/e1acd27a8859fa6f2e9fc3fc604b4888996621c6/Screenshot%202026-11-14%20180530.png)

IP address Topology for live hosts

![image alt](https://github.com/Masonwabeshana/Networkwalks-B084-Week2-Penetration-Testing-Report/blob/f964f2ca28c42339346a4c60524ce14c6f9a352a/Screenshot%202026-11-14%20180921.png)


