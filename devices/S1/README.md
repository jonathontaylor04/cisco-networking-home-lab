# S1 — Cisco Catalyst 3560 Switch

## Device Overview

| Field | Value |
|---|---|
| Lab identifier | `S1` |
| Manufacturer | Cisco |
| Series | Cisco Catalyst 3560 |
| Platform model | `WS-C3560-48PS` |
| Product ID | `WS-C3560-48PS-E` |
| Device type | Network switch |
| Processor | `PowerPC405` |
| Processor revision | `R0` |
| Version ID | `V06` |
| Hardware board revision | `0x01` |
| Serial numbers and MAC address | Redacted |

## Software and Boot Information

| Field | Value |
|---|---|
| IOS software family | `C3560-IPSERVICESK9-M` |
| IOS version | `12.2(55)SE10` |
| Release | `RELEASE SOFTWARE (fc2)` |
| IOS compilation date | 11 February 2015, 11:34 |
| Boot loader | `C3560-HBOOT-M` |
| Boot-loader version | `12.2(44)SE6` |
| Boot-loader release | `RELEASE SOFTWARE (fc1)` |
| Active system image | `flash:/c3560-ipservicesk9-mz.122-55.SE10.bin` |
| Configuration register | `0xF` |
| Password recovery | Enabled |

## Memory and Storage

| Resource | Reported value |
|---|---|
| System memory | `131072K` bytes — 128 MiB (calculated) |
| Flash-simulated non-volatile configuration memory | `512K` bytes |
| Flash filesystem capacity | `15998976` bytes total |
| Flash filesystem free space | `3246592` bytes |
| IOS image size | `12749374` bytes |

## Hardware Details

| Component | Reported identifier |
|---|---|
| Motherboard assembly | `73-9676-14` |
| Motherboard revision | `A0` |
| Power supply | `341-0029-05` |
| SFP module assembly | `73-7757-03` |
| SFP module assembly revision | `A0` |
| Top assembly | `800-26378-04` |
| Top assembly revision | `B0` |
| CLEI code | `COMU110ARA` |

## Interface Inventory

| Interfaces | Quantity | Type | Baseline status |
|---|---:|---|---|
| `FastEthernet0/1`–`FastEthernet0/48` | 48 | `10/100BaseTX` | `notconnect` |
| `GigabitEthernet0/1`–`GigabitEthernet0/4` | 4 | Gigabit Ethernet interfaces | `notconnect`; Type field reported as `Not Present` |
| `Vlan1` | 1 | Switched virtual interface | Unassigned and administratively down |

## Switching Configuration

| Setting | Baseline value |
|---|---|
| Spanning Tree mode | `pvst` |
| Spanning Tree extended system ID | Enabled |
| Routing MTU | `1500` |
| Internal VLAN allocation policy | Ascending |
| Active user VLAN | VLAN 1, `default` |
| Physical port VLAN assignment | All 52 physical interfaces assigned to VLAN 1 |
| Default legacy VLANs | VLANs `1002`–`1005`, reported as `act/unsup` |
