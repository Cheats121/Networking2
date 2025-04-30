# Networking2
Basic Networking (Router + 2PCs)
-----------------------------------
# Lab 2: Inter-VLAN Routing

### Overview
This lab introduced a router-on-a-stick to route between two distinct subnets.

### Topology
- **PC1**: 192.168.1.10/24, GW 192.168.1.254  
- **PC2**: 192.168.2.10/24, GW 192.168.2.254  
- **Router**  
  - Fa0/0: 192.168.1.254/24  
  - Fa0/1: 192.168.2.254/24  

### Tasks & Results
1. **Initial Ping Failures**  
   - PC1→PC2 failed (different networks).

2. **Router Interface Config**  
   - Assigned sub‐interface addresses; verified PC↔router pings.

3. **Default Gateway Setup**  
   - Set PC1 & PC2 to use respective router interfaces; full connectivity achieved.

### Lessons Learned
- Role of default gateway in inter‐network communication.
- Basics of router‐on‐a‐stick.
