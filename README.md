# mcp-hci
Mirantis Cloud Platform Hyper Converged Infrastructure

MCP hyper-converged reference archtecture standard.

Features:
- Full HA implmentation of MCP 2019.2.7 + OpenStack Queens
- 40 GbE SR-IOV + 10 GbE OVS Guest Networking
- 40 GbE Ceph Cluster
- Wireguard VPN

Provides:
- 3x Compute nodes
- 3x KVM control plane nodes
- 3x Ceph OSD nodes
- 3x Vyos router nodes
- 3x OVS gateway nodes
- 1x OPNsense firewall node
- 3x RDP remote desktop endpoints
- 2x Wireguard VPN HA service
    
Target hardware:
- 3x Dell R820 16-bay:
  - 4x Intel Xeon E5-4640
  - 32x 16GB DIMMs
  - 1x PERC H710
  - 2x Mellanox ConnectX-3 VPI Dual Port, MCX354A-FCBT
  - 1x Dell QLogic BCM57840S Quad 10 GbE Port rNDC, DP/N: XGRFF
  - 2x Samsung 850 Pro 256GB SATA 2.5" SSD
  - 7x Dell Seagate ST600MM0006 600GB SAS 10k RPM 2.5" HDD
  - 7x Seagate Barracuda ST5000LM000 5TB SATA 5.4k RPM 2.5" HDD
- 1x Mellanox SX6018 18 port 40 GbE Switch
- 1x Mellanox SX6036 36 port 40 GbE Switch
- 1x Dell R620 4-bay:
  - 1x Intel Xeon E5-2630
  - 4x 4GB DIMMs
  - 2x Dell Toshiba AL13SEB300 300GB SAS 10k RPM 2.5" HDD, DP/N: MTV7G
  - 1x PERC H710
  - 1x Dell Intel X520 DP 10 GbE + i350 DP 1 GbE rDNC, DP/N: C63DV
  - 1x Mellanox ConnectX-3 VPI Single Port, MCX353A-FCBT
- 1x AT&T Fiber + Arris BGW210-700 Residential Gateway + Public Static IP Block
   
    
