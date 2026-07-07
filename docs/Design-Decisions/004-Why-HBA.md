# Design Decision: Dedicated HBA

## Decision

Use an LSI HBA for the TrueNAS HDDs.

## Reason

Passing the HBA directly to TrueNAS gives TrueNAS direct control of the disks and keeps the main storage pool separate from Proxmox.

## Trade-off

Adds another component and requires PCI passthrough configuration.
