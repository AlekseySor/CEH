# CEH

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
