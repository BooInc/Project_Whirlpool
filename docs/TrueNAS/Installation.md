# TrueNAS Installation

## Goal

Run TrueNAS as a VM inside Proxmox.

## Planned Setup

- Create TrueNAS VM
- Assign CPU and RAM
- Pass through the LSI HBA
- Install TrueNAS to a virtual boot disk
- Import or create ZFS pool

## Important

The HBA must be passed through directly to TrueNAS so TrueNAS can manage the HDDs.
