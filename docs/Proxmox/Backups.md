# Proxmox Backups

## Backup Plan

A dedicated HDD will be connected to the motherboard SATA ports and used for Proxmox backups.

## What to back up

- TrueNAS VM boot disk
- Windows Server VM
- Linux VMs
- Docker VM
- Home Assistant VM

## Important

The TrueNAS data pool lives on the HDDs attached to the HBA, not inside the TrueNAS VM boot disk.
