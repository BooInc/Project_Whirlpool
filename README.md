# Project Whirlpool

## Overview

Project Whirlpool is my enterprise-inspired homelab project.

The goal is to build a reliable home server while gaining practical experience with virtualisation, storage, networking, Windows Server, Linux, Docker, backups and system administration.

This repository documents the planning, hardware, configuration, mistakes, fixes and lessons learned throughout the build.

## Goals

- Learn Proxmox VE
- Learn TrueNAS
- Learn Docker
- Learn Windows Server
- Learn Linux administration
- Learn networking and VLANs
- Learn Active Directory
- Learn backup and disaster recovery
- Build a practical IT portfolio

## Current Hardware

| Component | Model | Status |
|---|---|---|
| Case | Jonsbo N6 | Purchased |
| Motherboard | ASUS Pro WS W680M-ACE SE | Purchased |
| CPU | Intel Core i7-14700 | Purchased |
| CPU Cooler | Thermalright Phantom Spirit 120 SE | Purchased |
| Power Supply | SilverStone SX750 Platinum | Purchased |
| Memory | 64GB DDR5 non-ECC | Planned |
| Boot Storage | 2 x 2TB NVMe SSD | Planned |
| Storage Controller | LSI 9300-16i IT Mode | Planned |
| Main Storage | 6 x 8TB to 10TB HDDs | Planned |
| Backup Storage | 10TB HDD connected to motherboard SATA | Planned |

## Planned Architecture

```text
Hardware
  |
  |-- Proxmox VE
      |
      |-- TrueNAS VM
      |     |-- LSI HBA passthrough
      |     |-- RAIDZ2 storage pool
      |
      |-- Windows Server VM
      |-- Linux VM
      |-- Docker VM
      |-- Home Assistant VM
```

## Current Progress

- [x] Repository created
- [x] Hardware planning started
- [x] Case purchased
- [x] Motherboard purchased
- [x] CPU purchased
- [x] Cooler purchased
- [x] Power supply purchased
- [ ] RAM purchased
- [ ] NVMe purchased
- [ ] System assembled
- [ ] BIOS updated
- [ ] Proxmox installed
- [ ] TrueNAS VM created
- [ ] HBA installed
- [ ] HDD pool created
- [ ] Data migrated from old NAS

## Why this project exists

I am building this homelab to gain practical, hands-on IT experience and document the process properly. The aim is not only to build a NAS, but to create a learning platform for real IT skills.
