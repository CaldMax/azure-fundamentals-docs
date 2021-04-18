# Storage Services

## Azure Storage Account
- preliminar to every Azure Store data object
- provides unique namespace for data

## Azure Blob Storage
- unstructured
- massive amount of data
- ideal for:
  - serving images of docs to a browser
  - storing files for distributed access
  - streaming audio/video
  - storing data for backup/restore/DR/analysis
  - storing up to 8 TB for VMs
- tiers based on access
  - hot: accessed frequently
    - can be set at account level
    - can be set at blob level during up/down load
  - cool: infrequently accessed and stored at least 30 days
    - lower availability
    - still high durability/latency/throughput
    - can be set at account level
    - can be set at blob level during up/down load
  - archive: rarely accessed and stored at least 180 days
    - can be set at blob level during up/down load

![Blob hierarchy](./Images/account-container-blob.png)

## Azure Files Storage
- Use case scenarios:
  - many on prem applications using file shares
  - store configuration files on a file share and access via multiple VMs
  - write to file share to analyze later