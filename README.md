# My Home Lab

Hi there! This is my small home lab.

## Network Topology

![](/static/images/homelab-network.drawio.svg)

## Server Specs

| Component | Description |
| --- | --- |
| Brand | Apple Mac Mini 2018 |
| Processor | Intel i7-8700B (6 Cores) @ 3.2 GHz |
| RAM | [OWC 64GB Upgrade Kit](https://eshop.macsales.com/shop/memory/owc/apple-mac-mini/2018) |
| IP | DHCP |
| Storage 0 | M.2 1TB |
| NIC | x1 GbE |
| OS | MacOS Sequoia |

| Component | Description |
| --- | --- |
| Brand | Raspberry Pi 4B |
| Processor | Broadcom BCM2711, Cortex-A72 (64-bit ARM SOC) @ 1.8GHz |
| RAM | 4GB LPDDR4-3200 |
| IP | 192.168.4.37 |
| Storage 0 | microSDXC 64GB |
| Storage 1 | M.2 500GB via NVMe Adapter |
| NIC | x1 GbE |
| OS | Raspberry Pi OS Lite running [OpenMediaVault](https://www.openmediavault.org/) |

## Systems/Apps Running

### Virtual Machines

* Ubuntu Server 24.04 (via [UTM App](https://getutm.app/) on Mac Mini)

### Docker Stack(s)

* Ubuntu Server
    * PiHole (Primary)

* Raspberry Pi
    * PiHole (Secondary)