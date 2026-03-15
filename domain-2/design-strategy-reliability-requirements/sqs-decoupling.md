# SQS Decoupling

## Overview
Amazon SQS provides fully managed message queues for decoupling and scaling microservices, distributed systems, and serverless applications.

## Key Features
- Fully managed message queuing
- High throughput and scalability
- Message retention and durability
- Dead-letter queue support

## Queue Types
- **Standard Queues**: Maximum throughput, at-least-once delivery
- **FIFO Queues**: Exactly-once processing, message ordering

## Use Cases
- Decoupling microservices
- Asynchronous task processing
- Load leveling for applications
- Buffer for database operations

## Benefits
- Improved system resilience
- Better resource utilization
- Simplified architecture
- Enhanced fault tolerance

## Integration
- Lambda functions
- EC2 instances
- ECS/EKS containers
- API Gateway
