# Design Decision: RAIDZ2

## Decision

Use RAIDZ2 for the main TrueNAS pool.

## Reason

RAIDZ2 allows two drives to fail without losing the pool. This is safer than RAIDZ1, especially with larger HDDs.

## Trade-off

RAIDZ2 uses the capacity of two drives for parity.
