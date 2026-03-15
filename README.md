# Domain 1: Design Solutions for Organizational Complexity

## Architect network connectivity strategies

- [Transit Gateway](domain-1/architect-network-connectivity-strategies/transit-gateway.md)
- [VPC Peering](domain-1/architect-network-connectivity-strategies/vpc-peering.md)
- [Direct Connect](domain-1/architect-network-connectivity-strategies/direct-connect.md)
- [Site-to-Site VPN](domain-1/architect-network-connectivity-strategies/site-to-site-vpn.md)
- [Route 53 Resolver](domain-1/architect-network-connectivity-strategies/route-53-resolver.md)
- [PrivateLink & VPC Endpoints](domain-1/architect-network-connectivity-strategies/privatelink-vpc-endpoints.md)
- [Hybrid DNS](domain-1/architect-network-connectivity-strategies/hybrid-dns.md)
- [Network Firewall](domain-1/architect-network-connectivity-strategies/network-firewall.md)
- [Shared Services VPC](domain-1/architect-network-connectivity-strategies/shared-services-vpc.md)

## Prescribe security controls

- [SCPs vs IAM Policies](domain-1/prescribe-security-controls/scps-vs-iam-policies.md)
- [AWS Control Tower](domain-1/prescribe-security-controls/aws-control-tower.md)
- [Cross-account IAM Roles](domain-1/prescribe-security-controls/cross-account-iam-roles.md)
- [SSO & Identity Federation](domain-1/prescribe-security-controls/sso-identity-federation.md)
- [Security Hub & GuardDuty](domain-1/prescribe-security-controls/security-hub-guardduty.md)
- [KMS Multi-Region](domain-1/prescribe-security-controls/kms-multi-region.md)
- [Data Perimeters](domain-1/prescribe-security-controls/data-perimeters.md)

## Design reliable and resilient architectures

- [Multi-region Active/Passive](domain-1/design-reliable-resilient-architectures/multi-region-active-passive.md)
- [RTO & RPO](domain-1/design-reliable-resilient-architectures/rto-rpo.md)
- [Route 53 Failover](domain-1/design-reliable-resilient-architectures/route-53-failover.md)
- [AWS Backup](domain-1/design-reliable-resilient-architectures/aws-backup.md)
- [DR Patterns](domain-1/design-reliable-resilient-architectures/dr-patterns.md)

## Design a multi-account AWS environment

- [AWS Organizations & OUs](domain-1/design-multi-account-aws-environment/aws-organizations-ous.md)
- [Landing Zone](domain-1/design-multi-account-aws-environment/landing-zone.md)
- [AWS Resource Access Manager - RAM](domain-1/design-multi-account-aws-environment/aws-resource-access-manager-ram.md)
- [Consolidated Billing](domain-1/design-multi-account-aws-environment/consolidated-billing.md)
- [Delegated Admin](domain-1/design-multi-account-aws-environment/delegated-admin.md)

## Cost optimization and visibility strategies

- [Cost Explorer & Tags](domain-1/cost-optimization-visibility-strategies/cost-explorer-tags.md)
- [AWS Budgets](domain-1/cost-optimization-visibility-strategies/aws-budgets.md)
- [Savings Plans vs RIs](domain-1/cost-optimization-visibility-strategies/savings-plans-vs-ris.md)
- [Compute Optimizer](domain-1/cost-optimization-visibility-strategies/compute-optimizer.md)

# Domain 2 Design for New Solutions

## Design a deployment strategy to meet business requirements

- [Blue/Green Deployment](domain-2/design-deployment-strategy/blue-green-deployment.md)
- [Canary Deployments](domain-2/design-deployment-strategy/canary-deployments.md)
- [CI/CD with CodePipeline](domain-2/design-deployment-strategy/cicd-codepipeline.md)
- [CloudFormation StackSets](domain-2/design-deployment-strategy/cloudformation-stacksets.md)
- [Service Catalog](domain-2/design-deployment-strategy/service-catalog.md)
- [CDK vs CloudFormation](domain-2/design-deployment-strategy/cdk-vs-cloudformation.md)

## Design a solution to ensure business continuity

- [Warm Standby DR](domain-2/design-solution-business-continuity/warm-standby-dr.md)
- [Pilot Light DR](domain-2/design-solution-business-continuity/pilot-light-dr.md)
- [Multi-site Active/Active](domain-2/design-solution-business-continuity/multi-site-active-active.md)
- [Route 53 Routing Policies](domain-2/design-solution-business-continuity/route-53-routing-policies.md)
- [S3 Cross-Region Replication](domain-2/design-solution-business-continuity/s3-cross-region-replication.md)
- [RDS Multi-AZ & Replicas](domain-2/design-solution-business-continuity/rds-multi-az-replicas.md)

## Determine security controls based on requirements

- [S3 Security & Encryption](domain-2/determine-security-controls/s3-security-encryption.md)
- [WAF & Shield](domain-2/determine-security-controls/waf-shield.md)
- [Security Groups vs NACLs](domain-2/determine-security-controls/security-groups-vs-nacls.md)
- [Secrets Manager](domain-2/determine-security-controls/secrets-manager.md)
- [Amazon Macie](domain-2/determine-security-controls/amazon-macie.md)
- [Encryption at rest/transit](domain-2/determine-security-controls/encryption-rest-transit.md)
- [ACM (TLS/SSL)](domain-2/determine-security-controls/acm-tls-ssl.md)

## Design a strategy to meet reliability requirements

- [Auto Scaling](domain-2/design-strategy-reliability-requirements/auto-scaling.md)
- [SQS Decoupling](domain-2/design-strategy-reliability-requirements/sqs-decoupling.md)
- [SNS Fanout](domain-2/design-strategy-reliability-requirements/sns-fanout.md)
- [EventBridge](domain-2/design-strategy-reliability-requirements/eventbridge.md)
- [ECS Fargate vs EC2](domain-2/design-strategy-reliability-requirements/ecs-fargate-vs-ec2.md)
- [EKS Architecture](domain-2/design-strategy-reliability-requirements/eks-architecture.md)
- [Lambda Concurrency](domain-2/design-strategy-reliability-requirements/lambda-concurrency.md)

## Design a solution to meet performance objectives

- [CloudFront CDN](domain-2/design-solution-performance-objectives/cloudfront-cdn.md)
- [ElastiCache](domain-2/design-solution-performance-objectives/elasticache.md)
- [Aurora Serverless](domain-2/design-solution-performance-objectives/aurora-serverless.md)
- [DynamoDB DAX](domain-2/design-solution-performance-objectives/dynamodb-dax.md)
- [S3 Transfer Acceleration](domain-2/design-solution-performance-objectives/s3-transfer-acceleration.md)
- [Global Accelerator](domain-2/design-solution-performance-objectives/global-accelerator.md)
- [Load Balancer Types](domain-2/design-solution-performance-objectives/load-balancer-types.md)

# Domain 3 Continuous Improvement for Existing Solutions

## Improve overall operational excellence

- [Systems Manager](domain-3/improve-operational-excellence/systems-manager.md)
- [CloudWatch](domain-3/improve-operational-excellence/cloudwatch.md)
- [AWS Config](domain-3/improve-operational-excellence/aws-config.md)
- [CloudTrail](domain-3/improve-operational-excellence/cloudtrail.md)
- [Trusted Advisor](domain-3/improve-operational-excellence/trusted-advisor.md)
- [Infrastructure as Code](domain-3/improve-operational-excellence/infrastructure-as-code.md)
- [Well-Architected Tool](domain-3/improve-operational-excellence/well-architected-tool.md)

## Improve security

- [IAM Access Analyzer](domain-3/improve-security/iam-access-analyzer.md)
- [Amazon Inspector](domain-3/improve-security/amazon-inspector.md)
- [Amazon Detective](domain-3/improve-security/amazon-detective.md)
- [VPC Flow Logs](domain-3/improve-security/vpc-flow-logs.md)
- [Patch Manager](domain-3/improve-security/patch-manager.md)
- [Firewall Manager](domain-3/improve-security/firewall-manager.md)

## Improve performance

- [EC2 Instance Families](domain-3/improve-performance/ec2-instance-families.md)
- [RDS Performance Insights](domain-3/improve-performance/rds-performance-insights.md)
- [AWS X-Ray](domain-3/improve-performance/aws-x-ray.md)
- [S3 Intelligent Tiering](domain-3/improve-performance/s3-intelligent-tiering.md)
- [Amazon FSx](domain-3/improve-performance/amazon-fsx.md)

## Improve reliability

- [Resilience Hub](domain-3/improve-reliability/resilience-hub.md)
- [Chaos Engineering (FIS)](domain-3/improve-reliability/chaos-engineering-fis.md)
- [Aurora Global Database](domain-3/improve-reliability/aurora-global-database.md)
- [DynamoDB Global Tables](domain-3/improve-reliability/dynamodb-global-tables.md)

## Improve cost optimization

- [Spot Instances & Fleet](domain-3/improve-cost-optimization/spot-instances-fleet.md)
- [Cost Anomaly Detection](domain-3/improve-cost-optimization/cost-anomaly-detection.md)
- [S3 Lifecycle Policies](domain-3/improve-cost-optimization/s3-lifecycle-policies.md)
- [Data Transfer Costs](domain-3/improve-cost-optimization/data-transfer-costs.md)
- [Rightsizing](domain-3/improve-cost-optimization/rightsizing.md)

# Domain 4 Accelerate Workload Migration & Modernization

## Select existing workloads for migration

- [7Rs Migration Strategy](domain-4/select-existing-workloads-migration/7rs-migration-strategy.md)
- [AWS Migration Hub](domain-4/select-existing-workloads-migration/aws-migration-hub.md)
- [App Discovery Service](domain-4/select-existing-workloads-migration/app-discovery-service.md)
- [MGN vs SMS](domain-4/select-existing-workloads-migration/mgn-vs-sms.md)

## Determine an optimal migration approach

- [AWS DataSync](domain-4/determine-optimal-migration-approach/aws-datasync.md)
- [AWS DMS](domain-4/determine-optimal-migration-approach/aws-dms.md)
- [Snow Family](domain-4/determine-optimal-migration-approach/snow-family.md)
- [Online vs Offline Migration](domain-4/determine-optimal-migration-approach/online-vs-offline-migration.md)
- [AWS Transfer Family](domain-4/determine-optimal-migration-approach/aws-transfer-family.md)

## Determine a new architecture for existing workloads

- [Containerization](domain-4/determine-new-architecture-existing-workloads/containerization.md)
- [Monolith to Microservices](domain-4/determine-new-architecture-existing-workloads/monolith-to-microservices.md)
- [Serverless Migration](domain-4/determine-new-architecture-existing-workloads/serverless-migration.md)
- [DB Modernization](domain-4/determine-new-architecture-existing-workloads/db-modernization.md)
- [App2Container](domain-4/determine-new-architecture-existing-workloads/app2container.md)

## Determine opportunities for modernization and managed services

- [Aurora vs RDS](domain-4/determine-opportunities-modernization-managed-services/aurora-vs-rds.md)
- [AWS Glue & ETL](domain-4/determine-opportunities-modernization-managed-services/aws-glue-etl.md)
- [Amazon Redshift](domain-4/determine-opportunities-modernization-managed-services/amazon-redshift.md)
- [Amazon MSK](domain-4/determine-opportunities-modernization-managed-services/amazon-msk.md)
- [Elastic Beanstalk](domain-4/determine-opportunities-modernization-managed-services/elastic-beanstalk.md)
- [Step Functions](domain-4/determine-opportunities-modernization-managed-services/step-functions.md)
