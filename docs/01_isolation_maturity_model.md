
# Isolation Maturity Model

Multi-tenant SaaS platforms evolve through defined isolation stages.

## Level 1 – Logical Isolation (Shared Database)
- Single database
- tenant_id column enforcement
- Application-level validation
- Row-Level Security (RLS)

Blast Radius: Medium  
Cost: Low  
Operational Complexity: Low  

## Level 2 – Schema per Tenant
- Dedicated schema per tenant
- Improved data separation
- Better audit boundaries

Blast Radius: Lower  
Cost: Moderate  

## Level 3 – Database per Tenant
- Dedicated database instances
- Stronger performance isolation
- Independent backup policies

Blast Radius: Low  
Cost: Higher  

## Level 4 – Account per Tenant
- Separate AWS account
- Dedicated IAM, KMS, networking
- Enterprise onboarding model

Blast Radius: Very Low  
Cost: Highest  

Isolation escalation must be strategic, not reactive.
