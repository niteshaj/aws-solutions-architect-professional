# Aurora Serverless

## Overview
Amazon Aurora Serverless is an on-demand, auto-scaling configuration for Aurora that automatically starts up, shuts down, and scales capacity based on application demand.

## Key Features
- Automatic scaling based on workload
- Pay-per-use pricing model
- No infrastructure management
- Data API for direct access

## Scaling Behavior
- **ACU (Aurora Capacity Units)**: Measures compute and memory
- **Automatic scaling**: Adjusts based on CPU utilization
- **Warm-up pool**: Pre-warmed capacity for instant scaling
- **Pause/resume**: Pauses during inactivity to save costs

## Use Cases
- Infrequent or unpredictable workloads
- Development and testing environments
- Applications with variable traffic patterns
- Cost-sensitive workloads

## Benefits
- Cost optimization for variable workloads
- Simplified operations
- High availability
- Automatic scaling

## Integration
- Lambda functions
- API Gateway
- CloudFormation
- AWS SDKs
