# Task 1: Local Network Port Scanning using Nmap

## Objective:
Learn to discover open ports on devices in your local network to understand
network exposure

## Tools Used:
- Nmap - Learn to discover open ports on devices in your local network to understand
network exposure
- Wireshark - Wireshark is a free and open-source network protocol analyzer. It allows users to capture and inspect network traffic, providing a detailed view of what's happening on a network. 

## Steps Performed:
1. Installed Windows based Nmap on my system from Nmap's official website https://nmap.org/download.html.
2. Hence there is no preferred OS usage specified, I setup a VirtualBox LAN Environment.
   ### VM Setup:
   - Identified local subnet using 'ipconfig' (cmd) in my Windows System 'ifconfig' (Linux)
   - Setup 2 Virtual ISO images for a simple LAN setup (Windows-XP, Kali-Linux 2025).
   - Then for a LAN connection I created an internal network named -innet, and manually configured the IP address for both Windows XP and Kali-Linux.
   - Used Promiscuous Mode in Kali Linux for packet sniffing and monitoring purpose.
   - Used Ping to verify the connection and both systems are listening.
   - Learned different Nmap commands and used them in my scan.
   - While testing Nmap commands I used Wireshark to discover packets sent and received, which gave a basic knowledge of TCP 3-Way Handshake (SYN, ACK, RST, FIN).
   - Used TCP (Full open scan) to find all open ports and closed ports and all hosted systems (2 systems) in my network.
   - Found all the possible vulnerabilities.
   - Most common ports are 80 (HTTP), 443 (HTTPS),  21 (FTP), 22 (SSH), 25 (SMTP), 53 (DNS).
   ### Windows Based:
   - Used the GUI to do the scan
   - Used the cmd and Administrator controlled cmd to run command line Nmap.
## Wire shark
- Found several packet sharing and receiving and learned the 3 way handshake.
- The protocols, packet size, packets per second, bytes per second and detailed information at the end etc, of each packet was really useful to learn a network packet.
- Found several filters and loopback traffic which is the system's own traffic are also shown.
