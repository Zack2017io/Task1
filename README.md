Network Scanning with Nmap & Wireshark

Overview
This task involves scanning a local network using Nmap, analyzing packets using Wireshark, identifying common services and risks, and saving the results.

Tools Used
Nmap: Network scanning

Wireshark: Packet analysis

Commands Used
Nmap Scan: nmap -sS 192.168.1.0/24 

Wireshark Filters:
ip.addr == <target IP>

tcp.port == <port>

Next Steps
Research services found on open ports

Disable unused ports

Use firewalls to block risky services

Files Included
scan_results.txt — Nmap scan results

scan_results.html — Nmap results (HTML, optional)

wireshark_capture.pcap — Packet capture (optional)

Screenshot
