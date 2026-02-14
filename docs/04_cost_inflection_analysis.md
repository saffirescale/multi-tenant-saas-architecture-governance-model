
# Cost Inflection Analysis

Scalability must align with commercial reality.

## Primary Cost Drivers
- Compute scaling (EKS/ECS/EC2)
- Database I/O and storage
- Cross-region replication
- NAT gateway traffic

## Inflection Points
- 10 tenants → Optimize compute pooling
- 50 tenants → Introduce read replicas
- 100+ tenants → Reassess isolation strategy
- Enterprise onboarding → Consider account-level isolation

Architecture must evolve with revenue tiers.
