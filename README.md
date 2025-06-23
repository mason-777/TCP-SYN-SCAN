# TCP-SYN-SCAN
Discovered my IP range in power shell using command "ipconfig" - 192.168.0.191
Used zenmap i.e nmap GUI to syn scan the ip range using command nmap -sS 192.168.0.0/24
 Result:
ip-192.168.0.1
tcp port 80 http -open
port 443 https - open
port 9000 cslistener - open - can be a malware -(Goip Global Services Pvt.)

192.168.0.195
no open ports - host is not up

192.168.0.200
no open ports -router- tp link technologies

192.168.0.191- MY system
35/tcp  open  msrpc
139/tcp  open  netbios-ssn
445/tcp  open  microsoft-ds
902/tcp  open  iss-realsecure
912/tcp  open  apex-mesh
5357/tcp open  wsdapi
