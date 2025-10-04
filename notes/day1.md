# Day 1 — 2025-10-04

## Activities
1. Read OSI/TCP-IP overview
  - [Physical — cables/wireless, bits on wire  
  - Data Link — MAC, switches, frames 
  - Network — IP, routing 
  - Transport — TCP/UDP, ports 
  - Session — sessions/flows 
  - Presentation — encoding/encryption 
  - Application — HTTP/SMTP/DNS]  
https://www.geeksforgeeks.org/computer-networks/open-systems-interconnection-model-osi/
  
- Started TryHackMe Pre-Security modules  
- Ran network commands: `ping`, `traceroute`, `dig`  
- Captured HTTP GET request in Wireshark  

## Observations / Outputs
- ping to google.com: 4 packets, avg ~30 ms  
- traceroute: ~10 hops  
- dig google.com: returned multiple IPs  
- In Wireshark: saw GET / HTTP/1.1, Host, User-Agent headers  

## Next steps
- Complete remaining Pre-Security modules  
- Learn `nmap` basics
