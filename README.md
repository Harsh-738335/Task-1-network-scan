# Task-1-network-scan
Cybersecurity Internship Task-1 Port Scanning 
Scan the local network to discover open ports and analyze security exposure.
## Tools Used Nmap (Zenmap) Wireshark (optional)
##" Steps Taken
1. Found my IP range using ipconfig - 192.168.215.0/24
2. Ran Nmap TCP SYN scan using Zenmap
3. Saved scan resultc .. .txt" and ".htmi`.
4. Took screenshots of scan results.
5. Analyzed open ports and identified possible risks
6.
## Open Ports Found
| Port | Service -------|Description      
|------|----------------|------------------------------------------------------------|

|135  |  MSRPC          | windows RPC- internal use                                     |
|139  |  NetBioc -.     | File sharing (legacy)                                         |
|445| |  Microsoft-DS   | SMB file sharing 903 ISS Console Mgr Rare service-admin use?  |
|1117 |  Ardus-MTRNS    | Unknown- likely custon service                                |

7.
## lock Risk Analysis
|Port | Risk Level   | Recommendation
|-----|--------------|-----------------------------------------------------------|

|135  |   Medium     |        Block externally                   |
|139  |   High       |        Disable if not in use              |
|445  |   High       |        Restrict to trusted devices        |
|903  |   Medium     |        Investigate purpose                |
|1117 |   Medium     |        Block unless explicitly required   | 

## Screenshot 
![scan result]
## Conclusion
This task helped me understand port scanning, open port risks, and basic network security assessment.
