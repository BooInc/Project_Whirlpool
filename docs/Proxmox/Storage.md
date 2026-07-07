# Proxmox Storage

## NVMe

Used for:

- Proxmox OS
- VM disks
- Containers
- ISOs
- Templates

## Backup HDD

A motherboard-connected HDD will later be used for Proxmox backups.

## TrueNAS Storage

The HDD pool will not be managed directly by Proxmox. It will be passed through to the TrueNAS VM using the HBA.
