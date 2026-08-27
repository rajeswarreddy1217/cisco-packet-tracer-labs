# VLAN Network Segmentation & Isolation

## 🎯 Objective
Create two separate VLANs on a single switch and demonstrate network segmentation.

## 🖥️ Devices
- 2 PCs
- 1 Cisco 2960 Switch

## 🌐 VLAN Configuration

| Device | VLAN | IP Address |
|---|---|---|
| PC0 | VLAN 10 (USERS) | 192.168.10.10 |
| PC1 | VLAN 20 (GUESTS) | 192.168.20.10 |

## 🔧 Configuration
- VLAN 10 was created and named USERS.
- VLAN 20 was created and named GUESTS.
- PC0 was assigned to VLAN 10.
- PC1 was assigned to VLAN 20.

## 🧪 Testing
A ping was performed from PC0 to PC1.

The ping failed because the PCs belong to different VLANs and no inter-VLAN routing was configured.

## ✅ Result
Successfully demonstrated VLAN-based network segmentation and isolation.

## 📚 What I Learned
- How to create VLANs
- How to assign switch ports to VLANs
- How VLANs provide network segmentation
- Why inter-VLAN communication requires Layer 3 routing
