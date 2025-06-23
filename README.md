# task-1
TASK 1

I have installed Nmap from official website i.e. Nmap.Org through a browser. Nmap is an open source tool used for network scanning and host discovery. It has various features such as TCP scan, Ping scan, Host discovery etc.
I found my local IP address through Command Prompt in my device.
I ran intense scan for all TCP ports and identified 12 open ports after the scan.
Common services on these ports are:

•	Port 135 (RPC Endpoint Mapper)
Helps Windows find which dynamic port an RPC service (like WMI, DCOM, Netlogon) is using 

•	Ports 49664–49671 (Dynamic RPC Ports)
These are temporary ports (in the 49152–65535 range) where the actual RPC services listen after connecting via port 135 

•	Port 139 (NetBIOS Session Service)
Older protocol used for Windows file and printer sharing via NetBIOS—it’s mostly out of use now .

•	Port 445 (SMB over TCP/IP)
Used for modern Windows file sharing, Active Directory, Group Policy—frequently targeted by malware 

•	Port 137 (NetBIOS Name Service)
Legacy service for name resolution in NetBIOS; usually blocked for security 

•	Port 5040 (Connected Devices Platform Service)
This Windows service (CDPSvc) helps connect Bluetooth devices, printers, cameras, phones, etc. 

•	Ports 9012 & 9013 (WebSocket++)
Custom ports typically used by WebSocket++ servers for real-time web apps or dev/debug purposes. Their exact use depends on your setup.
I have installed Wireshark application through it’s official website i.e. Wireshark.org through a browser. Wireshark is a software tool used to monitor the network traffic through a network interface. It captures packets from the network which could further be used for data analysis.
After installation I have selected the network from which I want to capture data. After selection of the network I run the tool till I got sufficient amount of packets. Late I tried to analyze few captured packets. 
	

I have saved the scan results as a text file.
