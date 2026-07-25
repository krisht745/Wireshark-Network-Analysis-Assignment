# Wireshark Network Analysis Assignment

**Name:** Krishna Kumar Tiwari  
**Batch:** Ethical Hacking JOVAC  

## Network Traffic Analysis
Analysis of the provided PCAP file using Wireshark.
## Wireshark Analysis Results

### E1. Number of DHCP messages
**Answer:** 5  
**Wireshark Filter:** `dhcp`

### E2. Number of ARP messages
**Answer:** 680  
**Wireshark Filter:** `arp`

### E3. IP address that accessed baidu.com
**Answer:** 10.103.51.159

### E4. Number of packets sent by 10.103.0.20
**Answer:** 469  
**Wireshark Filter:** `ip.src == 10.103.0.20`

### E5. Number of UDP packets
**Answer:** 8610  
**Wireshark Filter:** `udp`

### E6. Number of SMB packets
**Answer:** 518  
**Wireshark Filter:** `smb || smb2`

### E7. Number of packets sent to 10.103.0.20
**Answer:** 547  
**Wireshark Filter:** `ip.dst == 10.103.0.20`

### E8. Number of IPv4 packets
**Answer:** 24906  
**Wireshark Filter:** `ip`

### E9. Source IP address of the last SMB packet
**Answer:** 10.103.50.202

### E10. MAC address associated with 151.139.128.14
**Answer:** 00:1c:7f:6c:96:3f

### E11. Protocol used in packet 416
**Answer:** UDP

### E12. Destination IP address of packet 416
**Answer:** 10.103.0.20

### E13. Source IP address of the first HTTP packet
**Answer:** 10.103.51.159  
**Wireshark Filter:** `http`

### E14. Source port of the first HTTP packet
**Answer:** 64079

### E15. Duration of the capture
**Answer:** 348.109916 seconds (approximately 348.11 seconds)

### E16. Number of NBNS packets
**Answer:** 963  
**Wireshark Filter:** `nbns`

### E17. Number of TCP packets with source port 443
**Answer:** 7275  
**Wireshark Filter:** `tcp.srcport == 443`

### E18. Number of TCP packets with destination port 443
**Answer:** 5966  
**Wireshark Filter:** `tcp.dstport == 443`

### E19. Number of packets sent to 204.79.197.200
**Answer:** 116  
**Wireshark Filter:** `ip.dst == 204.79.197.200`

### E20. MAC address and vendor associated with 204.79.197.200
**MAC Address:** 00:1c:7f:6c:96:3f  
**Vendor:** Check Point Software Technologies

## Tools Used
- Wireshark
- PCAP/PCAPNG network capture analysis
- Wireshark Display Filters
