# FortiGate VLAN Lab

## Overview
This lab demonstrates VLAN configuration and inter-VLAN routing using FortiGate and Cisco switch in an EVE-NG environment.

## Topology
- **VLAN 10 (HR)** – 192.168.1.0/24
- **VLAN 20 (IT)** – 192.168.2.0/24
- **FortiGate Port1** – 192.168.233.134/24 (WAN)
- **FortiGate Port2** – VLAN Trunk (HR/IT VLANs)

## Goals
1. Configure VLANs on Cisco switch (HR, IT).
2. Trunk connection between switch and FortiGate.
3. Inter-VLAN routing using FortiGate.
4. Internet access via Port1.

## Files
- `configs/fgt-config.txt` → FortiGate CLI backup.
- `configs/switch-config.txt` → Switch CLI configuration.
- `eve-ng/fortigate-vlan-lab.unl` → EVE-NG topology file.
- `eve-ng/screenshots/` → GUI interface & policy screenshots.
