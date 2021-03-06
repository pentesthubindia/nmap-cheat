# NMAP CHEATSHEET
---
* **Nmap Target Selection**

   **Scan a single IP :--** nmap 192.168.1.1 
   **Scan a host :--** nmap www .yourtarget. com
   **Scan a range of IP's :--** nmap 192.168.1.1-20
   **Scan a subnet :--** nmap 192.168.1.0/24
   **Scan a target from a text file :--** nmap iL iplist.txt
   
* **Nmap Port Selection**

   **Scan a single port :--** nmap -p 22 192.168.1.1
   **Scan a range of ports :--** nmap -p 1-100 192.168.1.1
   **Scan 100 most common ports (Fast) :--** nmap -F 192.168.1.1
   **Scan all 65535 ports :--** nmap -p- 192.168.1.1
   
* **Nmap Port Scan Types**
 
     **Scan using TCP connect :--** nmap -sT 192.168.1.1
     **Scan using TCP SYN scan (default) :--** nmap -sS 192.168.1.1
     **Scan UDP ports :--** nmap -sU -p 123,161,162 192.168.1.1
     **Scan selected ports - ignore discovery :--** nmap -Pn -F 192.168.1.1
     
* **Service and Os Detection**
      
      **Detect OS and Services :--** nmap -A 192.168.1.1
      **Standard service detection :--** nmap -sV 192.168.1.1
      **More aggressive Service Detection :--** nmap -sV --version-intensity 5 192.168.1.1
     
     
     
     
     
     
     
     
     
     
     
     
     
     
     
     
     
     
     