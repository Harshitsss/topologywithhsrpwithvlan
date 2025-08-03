# topologywithhsrpwithvlan




# 🖧 Network Topology (Without DHCP)

This project simulates a basic  network using **Cisco Packet Tracer**. It includes VLAN segmentation, HSRP for redundancy, and static IP addressing (no DHCP).

## 🔧 Devices Used
- 2 Multilayer Switches
- 1 Router
- 3 Access Switches
- 3 PCs (Admin, HR, IT)

## 📌 VLANs
| VLAN | Department |
|------|------------|
| 10   | Admin      |
| 20   | HR         |
| 30   | IT         |

## 🔐 Features
- VLAN segmentation
- HSRP configuration for gateway redundancy
- OSPF routing between devices
- Static IP configuration (no DHCP)
- All roles performed using PCs (no dedicated servers)

## 🧪 Verification
Use `ping` and `show` commands like:
```bash
ping 10.10.10.254
show standby
show ip ospf neighbor
