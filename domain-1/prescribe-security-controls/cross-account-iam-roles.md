# Cross-Account IAM Roles

## Overview
Cross-account IAM roles enable secure access to resources across different AWS accounts without sharing long-term credentials.

## Key Features
- Temporary access credentials
- Role-based access control
- Trust relationship management
- Fine-grained permissions
- Audit trail and logging

## Components

### Role Trust Policy
- Defines who can assume the role
- Specifies trusted accounts
- Condition-based access
- MFA requirements

### Role Permissions Policy
- Defines what the role can do
- Resource-based permissions
- Action restrictions
- Condition-based permissions

## Use Cases
- Multi-account environments
- Third-party access
- Application integration
- Cross-account resource sharing
- Centralized administration

## Implementation Patterns

### Resource Access Pattern
- Resource account hosts resources
- Consumer account assumes role
- Limited scope permissions
- Time-bound access

### Service Account Pattern
- Central service account
- Application roles in target accounts
- Automated workflows
- Service-to-service communication

## Best Practices
- Principle of least privilege
- Use MFA for human access
- Implement session timeouts
- Regular role reviews
- Monitor role usage

## Security Considerations
- Trust policy configuration
- Permission boundary implementation
- Cross-account confusion deputy
- Credential management
- Audit and monitoring

## Common Patterns
- Cross-account S3 access
- Cross-account API calls
- Cross-account resource sharing
- Cross-account deployment
- Cross-account monitoring
