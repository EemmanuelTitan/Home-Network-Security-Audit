# Home-Network-Security-Audit

Objective
Assess a local network to identify active hosts, open ports, and exposed services on the network gateway.

Tools Used
• Kali Linux
• Nmap

Methodology

IP Address Identification
Identified the local IP address and network range using the ip a command to understand the network scope.

Network Discovery
Performed host discovery using Nmap to identify active devices within the local subnet.

Port and Service Scanning
Conducted a SYN and service version scan on the network gateway to identify open ports and running services.

Findings
• Multiple active hosts were discovered on the local network.
• The gateway device was identified and audited.
• Open ports 135 and 445 were detected, associated with RPC and SMB services.

Security Analysis
• Exposed SMB and RPC services increase attack surface.
• In real environments, these services should be restricted or protected by firewall rules.

Mitigation Recommendations
• Limit access to SMB and RPC services.
• Apply firewall rules to restrict unnecessary exposure.
• Regularly audit gateway devices for exposed services.

Evidence
• Step1_IP_Address_Identification.png
• Step2_Network_Discovery.png
• Step3_Port_and_Service_Scan.png
