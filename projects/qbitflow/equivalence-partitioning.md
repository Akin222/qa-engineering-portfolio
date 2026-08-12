# QBitFlow Equivalence Partitioning

## Objective

Equivalence partitioning reduces redundant testing by grouping inputs expected to behave similarly.

## Payment Amount Partitions

Potential partitions include:

- Valid payment amount
- Below required amount
- Zero amount
- Negative amount
- Excessively large amount
- Invalid format

## Network Partitions

- Supported network
- Unsupported network
- Missing network
- Invalid network identifier

## Asset Partitions

- Supported asset
- Unsupported asset
- Missing asset
- Invalid asset identifier

## QA Principle

Representative values from each meaningful partition can provide efficient coverage while maintaining focus on high-risk behavior.
