# Data Migration

## Source

Existing TrueNAS NAS with approximately 11TB of data.

## Target

New TrueNAS VM running on Project Whirlpool.

## Preferred Methods

1. ZFS replication
2. Rsync over SSH

## Plan

- Build new pool
- Create datasets
- Copy data
- Verify data
- Keep old NAS untouched for a few weeks before decommissioning
