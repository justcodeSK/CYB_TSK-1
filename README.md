# Task 1: Local Network Port Scanning using Nmap

## Objective:
Learn to discover open ports on devices in your local network to understand
network exposure

## Tools Used:
- Nmap - Learn to discover open ports on devices in your local network to understand
network exposure
- Wireshark - Wireshark is a free and open-source network protocol analyzer. It allows users to capture and inspect network traffic, providing a detailed view of what's happening on a network. 

## Steps Performed:
1. Installed Windows based Nmap on my system from nmaps official website https://nmap.org/download.html.
2. Hence there is no prefered OS usage specified ,i setup a Virtualbox LAN Enviornment.
   ### VM Setup:
   - Identified local subnet using 'ipconfig' (cmd) in my windows System 'ifconfig' (linux)
   - Setup 2 Virtual ISO images for a simple LAN setup (Windows-XP, Kali-Linux 2025).
   - Then for a LAN connection i created an internal network named -innet, and manually configured the ipaddress for both windows xp and kali-linux.
   - Used Promiscuous Mode in kali linux for packet sniffing and monitoring purpose.
   - Used Ping to verify the connection and both systems are listning.
   - Learned different nmap commands and used them in my scan.
   - While testing Nmap commands i used wireshark to discover packets send and recieved, which gave and basic knowledge of TCP 3-Way HandShake(SYN,ACK,RST,FIN).
   - Used TCP (Full open scan) to find all open ports and closed portes and all hosted systems (2 systems) in my network.
   - 
   ### Windows Installation:
   - 
