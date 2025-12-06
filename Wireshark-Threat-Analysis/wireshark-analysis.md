# Wireshark Threat Analysis – Shashank Budhlakoti

## Objective
To capture and analyze network packets to identify threats, anomalies, and suspicious behavior.

## Tools Used
- Wireshark  
- TCPDump  
- Tshark  

## Filters Used
- SYN scan detection: `tcp.flags.syn == 1 && tcp.flags.ack == 0`
- Suspicious DNS query: `dns.qry.name contains ".ru"`
- HTTP analysis: `http.request`
- ICMP traffic: `icmp`

## Observations
- Repeated SYN packets indicating scanning  
- DNS queries to unusual domains  
- Abnormal TTL values  
- Suspicious traffic flow patterns  

## Outcome
Improved capability in packet inspection, forensic analysis, and SOC-style threat detection.
