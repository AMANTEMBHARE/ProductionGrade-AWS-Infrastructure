# Production-Grade AWS Infrastructure

A concise reference and checklist for designing production-ready AWS infrastructure.

## Table of contents
- [Architecture design](#architecture-design)
- [CIDR planning](#cidr-planning)
- [Subnet design](#subnet-design)
- [Security groups](#security-groups)
- [Traffic flow](#traffic-flow)
- [Cost estimation](#cost-estimation)
- [AWS knowledge checklist](#aws-knowledge-checklist)
- [Next steps](#next-steps)

---

## Architecture design

High-level architecture considerations: availability zones, fault domains, service boundaries, and resilience patterns.

## CIDR planning

Guidelines for IP addressing, VPC sizing, and overlap avoidance when peering or connecting on-premises networks.

## Subnet design

Public vs private subnets, NAT placement, route tables, and recommended subnet sizing per availability zone.

## Security groups

Principles for least-privilege rules, segmentation, and managing inbound/outbound access.

## Traffic flow

Typical traffic flow patterns: internet ingress/egress, internal service-to-service, and cross-account or cross-VPC routing.

## Cost estimation

Considerations for component costs (gateways, NAT, load balancers, data transfer), scaling, and cost-optimization opportunities.

## AWS knowledge checklist

- EC2
- VPC
- Public/Private Subnets
- Route Tables
- Internet Gateway
- NAT Gateway
- VPC Peering
- Security Groups
- Load Balancer
- Auto Scaling
- Route 53
- CloudFront
- S3
- EBS
- EFS
- Databases (basic understanding)
- Monitoring
- Security & Compliance
- Infrastructure as Code concepts

## Next steps

1. Convert these design notes into Infrastructure-as-Code (Terraform / CloudFormation).
2. Add architecture diagrams (draw.io, Lucidchart, or Mermaid).
3. Create example modules for VPC, subnets, and security groups.
4. Add a `CONTRIBUTING.md` with how to propose changes.

---

If you want, I can also generate a Terraform starter layout or add diagrams — tell me which one to do next.