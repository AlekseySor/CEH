# CEH
snow.exe -C -p "password" file.txt

To scan the live Host
nmap -sP x.x.x.1/24                 
nmap -sn x.x.x.1/24

To find the Specific open port
nmap -p port x.x.x.1/24 --open

To find the OS
nmap -O x.x.x.x 

Comprehensive Scan
nmap -Pn -A x.x.x.1/24 -vv --open   

nmap -sC -sV -p- -A -v -T4 192.168.1.*


nmap -sU -p 161 --script=snmp-processes ip

hydra -P /usr/share/wordlist/metasploit/common_users.txt -U /usr/share/wordlist/metasploit/unux.password.txt 192.168.0.0 
