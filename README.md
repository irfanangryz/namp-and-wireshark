To find the ipaddress in terminal 
1.ifconfig - LINUX
2.ipconfig - WINDOWS

NAMP
Nmap is a powerful open-source network scanning tool used for discovering hosts and services on a network.
It offers a wide range of commands and options for various network scanning tasks.

resource : https://medium.com/@dilipyadav90382/nmap-commands-76c08d3d6a53

tryhackme : https://tryhackme.com/room/furthernmap

syntax 

nmap -sS ipaddress

common options

nmap <target> -T4                                      # Fast scan to identify open ports quickly only 1000 common ports!
nmap <target> -p-                                      # Scan all ports 1-65,535
nmap <target> -sV -p <port numbers that opend>         # Detects versions of services running on open ports
nmap <target> -sU                                      # Scans for open UDP ports
nmap --script ftp-* <target> -p21                      # Uses Nmap’s scripting engine to check for known vulnerabilities, this is an example for port 21 open and run all scripts of ftp.
nmap -A -p- <target>                                   # Combines OS detection, version detection, script scanning, and traceroute, Notice that it takes time!

for more resources : nmap --help

Wireshark 

Wireshark is a free and open-source network protocol analyzer. It's primarily used for capturing and inspecting network traffic, making it a powerful tool for troubleshooting, analysis, and security purposes. Network professionals, security engineers, and software developers all utilize Wireshark for various tasks, including identifying network problems, analyzing security threats, and debugging network applications

Wireshark cheet sheets  https://www.stationx.net/wireshark-cheat-sheet/

Essential Filters  : https://iritt.medium.com/wireshark-essential-filters-for-network-analysis-a64239f44bfd


