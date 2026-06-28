# AWS vs Azure Cloud Pricing Comparison

This repository contains a cloud pricing comparison report for hosting a small web application on Amazon Web Services (AWS) and Microsoft Azure.

## Project Objective

The objective of this project is to estimate and compare monthly cloud hosting costs for a small web application using AWS and Azure pricing calculators. The comparison covers compute, storage, networking, discount options, and final cost recommendations.

## Application Specifications

| Component | Specification |
|---|---|
| Application Type | Small Web Application |
| Compute | 1 Virtual Machine |
| CPU | 2 vCPU |
| RAM | 4 GB |
| VM Storage | 50 GB |
| Object Storage | 100 GB |
| Monthly Data Transfer | 100 GB outbound |
| Deployment Type | Single availability zone |

## Cost Summary

| Provider | Scenario | Estimated Monthly Cost |
|---|---:|---:|
| AWS | Linux EC2 + S3 Storage | $17.34 |
| Azure | Linux VM + Storage | $42.76 |
| Azure | Windows VM + Storage | $49.48 |

## Main Finding

Based on the calculator estimates, AWS is the most cost-effective option for the selected small Linux-based web application scenario. Azure is more expensive in this comparison, but it may be more suitable for organizations already using Microsoft technologies, especially when Azure Hybrid Benefit or Reserved VM Instances are available.

## Repository Structure

```text
AWS-Azure-Cost-Comparison/
├── README.md
├── Calculator-Notes.md
├── REPORT/
│   ├── AWS_vs_Azure_Comparison_Report.docx
│   └── AWS_vs_Azure_Comparison_Report.pdf
├── Screenshots/
│   ├── aws-ec2-estimate.jpg
│   ├── aws-total-estimate.jpg
│   ├── aws-savings-plan-options.jpg
│   ├── aws-s3-storage.jpg
│   ├── azure-linux-estimate.jpg
│   ├── azure-windows-estimate.jpg
│   ├── azure-inter-zone-cost.jpg
│   └── aws-inter-zone-cost.jpg
└── docs/
    └── Submission-Guide.md
```

## References

- AWS Pricing Calculator: https://calculator.aws/
- Azure Pricing Calculator: https://azure.microsoft.com/en-us/pricing/calculator/
- AWS EC2 Pricing: https://aws.amazon.com/ec2/pricing/
- AWS S3 Pricing: https://aws.amazon.com/s3/pricing/
- Azure Virtual Machines Pricing: https://azure.microsoft.com/en-us/pricing/details/virtual-machines/
