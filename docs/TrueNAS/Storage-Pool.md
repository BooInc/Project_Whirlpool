# TrueNAS Storage Pool

## Planned Pool

- 6 x HDDs
- RAIDZ2

## Why RAIDZ2

RAIDZ2 allows any two drives to fail without losing the pool. This is safer than RAIDZ1 for larger drives.

## Notes

Replacement drives can be larger than the original drives. ZFS will only use the size of the smallest drive until all drives are upgraded.
