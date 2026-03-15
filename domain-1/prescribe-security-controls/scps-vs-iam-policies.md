# SCPs vs IAM Policies

## Overview
Service Control Policies (SCPs) and IAM Policies are both authorization mechanisms in AWS, but they serve different purposes and operate at different scopes.

## IAM Policies

### Purpose
- Control access within individual accounts
- Grant specific permissions to IAM entities
- Fine-grained access control

### Scope
- Account-level
- User, group, role specific
- Permission-based

### Characteristics
- Allow by default
- Explicit deny overrides allow
- JSON-based syntax
- Resource-level permissions

## Service Control Policies (SCPs)

### Purpose
- Set guardrails for accounts in an organization
- Restrict permissions across accounts
- Maximum permissions boundary

### Scope
- Organization level
- Organizational Unit (OU) level
- Account level

### Characteristics
- Allow by default
- Explicit deny overrides allow
- JSON-based syntax
- Service and action restrictions

## Key Differences

| Aspect | IAM Policies | SCPs |
|--------|--------------|------|
| Scope | Account | Organization |
| Default | Deny all | Allow all |
| Purpose | Grant permissions | Set guardrails |
| Override | Allow can override deny | Deny overrides allow |
| Resource control | Yes | No |

## Use Cases

### IAM Policies
- Application access control
- User permission management
- Resource-specific access
- Temporary access grants

### SCPs
- Compliance enforcement
- Service restrictions
- Account-level guardrails
- Centralized governance

## Best Practices
- Use SCPs for organization-wide controls
- Use IAM policies for account-specific access
- Implement defense in depth
- Regular policy reviews and audits
- Document policy purposes and scope
