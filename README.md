# nmap-scanner-automation-tool
My very first nmap automation tool with Python, educating myself in order to keep everyone else cyber-tight! 

3 scanning variables:
Syn Ack Scan - Determines state of a communcations port without establishing a full conection - if server.response() = true means port is open.

UDP Scan - Sends a UDP packet to every targeted port. For most ports, this packet will be empty (no payload), but for a few of the more common ports a protocol-specific payload will be sent. Based on the response, or lack thereof, the port is assigned to one of four states.

Comprehensive Scan - Full on network scanning.

*This script is under development
Any contributions to this project will be most appreciated.

