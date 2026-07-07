# Storage Diagram

```text
NVMe 1
  |-- Proxmox OS
  |-- VM disks
  |-- Containers

NVMe 2
  |-- Future mirror or additional VM storage

LSI HBA
  |-- HDD 1
  |-- HDD 2
  |-- HDD 3
  |-- HDD 4
  |-- HDD 5
  |-- HDD 6
      |
      |-- TrueNAS RAIDZ2 Pool

Motherboard SATA
  |-- 10TB Proxmox Backup Drive
  |-- Optional offline/cold backup drive
```
