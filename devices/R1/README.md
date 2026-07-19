# R1 — Cisco 1941 Router

## Device Overview

| Field | Value |
|---|---|
| Lab identifier | `R1` |
| Manufacturer | Cisco |
| Model | Cisco 1941 |
| Product ID | `CISCO1941/K9` |
| Device type | Router |
| Hardware revision | `1.0` |
| Chassis version ID | `V04` |
| Serial numbers | Redacted |

## Software and Licensing

| Field | Value |
|---|---|
| IOS software family | `C1900-UNIVERSALK9-M` |
| IOS version | `15.0(1)M6` |
| Release | `RELEASE SOFTWARE (fc1)` |
| IOS compilation date | 1 June 2011, 15:31 |
| ROM bootstrap version | `15.0(1r)M15` |
| System image | `flash0:c1900-universalk9-mz.SPA.150-1.M6.bin` |
| Configuration register | `0x2102` |
| IP Base package | `ipbasek9` — `Permanent` |
| Security package | `securityk9` — `Permanent` |
| Data package | `None` reported |

## Memory and Storage

| Resource | Reported value |
|---|---|
| Processor/I/O memory | `475136K / 49152K` |
| Combined reported memory | `524288K` total — 512 MiB (calculated) |
| DRAM configuration | 64-bit wide; parity disabled |
| Non-volatile configuration memory | `255K` bytes |
| CompactFlash capacity reported by IOS | `250880K` bytes, read/write |
| Flash filesystem capacity | `256487424` bytes total |
| Flash filesystem free space | `210661376` bytes |
| IOS image size | `45825224` bytes |

## Installed Hardware

| Component | Quantity | Product ID / Details | Location |
|---|---:|---|---|
| Cisco 1941 chassis | 1 | `CISCO1941/K9`, VID `V04` | Chassis |
| Serial WAN interface card | 2 | `HWIC-1T`, VID `V04` | Slot 0, SubSlots 0 and 1 |
| AC power supply | 1 | `PWR-1941-2901-AC` | Not specified |
| VPN module | 1 | Reported by IOS; PID and VID not listed | Not specified |

## Interface Inventory

| Interfaces | Quantity | Type | Source |
|---|---:|---|---|
| `GigabitEthernet0/0`, `GigabitEthernet0/1` | 2 | Gigabit Ethernet | Reported by IOS |
| `Serial0/0/0`, `Serial0/1/0` | 2 | Synchronous/asynchronous serial | Two `HWIC-1T` cards |
