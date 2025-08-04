# Task-1

**Scan Your Local Network for Open Ports**

First=> Find IP Address for local network that I run ip addr command in kali linux
Second=> Now I run sudo nmap 192.168.1.0/24 
or sudo nmap -sS 192.168.1.0/24
Now IP Addresses and open ports 
192.168.1.1 open ports = 23/tcp 53/tcp 80/tcp 443/tcp
192.168.1.2 open ports = 80/tcp 554/tcp 
192.168.1.3 open ports = 902/tcp 912/tcp 5357/tcp 7070/tcp
192.168.1.7 open ports = 1080/tcp 8008/tcp 8009/tcp 8443/tcp 9000/tcp 
and I have also save the "scan_results.txt" file for nmap scanning 
