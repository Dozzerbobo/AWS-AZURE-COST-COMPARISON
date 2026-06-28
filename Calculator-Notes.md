# Calculator Notes

## AWS Estimate

Services included:

- Amazon EC2 Linux instance
- Amazon S3 Standard storage

AWS monthly estimate:

- EC2: $15.04/month
- S3 Standard Storage: $2.30/month
- Total: $17.34/month

## Azure Estimate

Services included:

- Azure Virtual Machine
- Azure Storage Account / Blob Storage

Azure monthly estimate:

- Linux VM + Storage: $42.76/month
- Windows VM + Storage: $49.48/month

## Networking Comparison

Both AWS and Azure charge for data transfer between availability zones. The screenshots used in this project show that inter-zone transfer is approximately $0.01 per GB. Because this project assumes a single availability zone deployment, inter-zone networking cost is expected to be low.

## Discount Mechanisms

AWS offers Savings Plans for predictable compute usage. Azure offers Reserved Virtual Machine Instances and Azure Hybrid Benefit for eligible Microsoft licenses.
