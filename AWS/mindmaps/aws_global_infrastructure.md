
# AWS Global Infrastructure

## AWS Global Infrastructure
- **Regions**
  - Physical location of data centers worldwide
  - Composed of multiple Availability Zones (AZs)
  - Example Regions
    - US East (N. Virginia)
    - Europe (Frankfurt)
    - Asia Pacific (Singapore)
- **Availability Zones (AZs)**
  - Isolated locations within each region
  - Connected by low-latency links
- **Edge Locations**
  - Part of Amazon CloudFront for caching and content delivery

## Factors to Choose the Right Region
- **Compliance**
  - Data Residency Requirements
  - GDPR Compliance in Europe
  - Industry-specific certifications (HIPAA, PCI-DSS)
- **Latency**
  - Proximity to End Users
  - Lower latency for better user experience
- **Cost**
  - Pricing varies between regions
  - Data Transfer Costs
- **Service Availability**
  - Newer services may be available only in specific regions initially
  - Check if the required AWS services are offered
- **Redundancy and Resilience**
  - Multi-region deployment for disaster recovery
  - Avoid regions with known geophysical risks
- **Geopolitical Stability**
  - Consider political stability to avoid potential disruptions
- **Business Continuity**
  - Selecting regions across different continents to prevent impact from local failures

## Other Considerations
- **Data Transfer and Bandwidth**
  - Intra-region vs. inter-region data transfer costs
- **Special Region Requirements**
  - AWS GovCloud for government workloads
  - China regions with separate management and compliance
