---
name: aws-serverless
description: Design AWS serverless applications using services such as Lambda, API Gateway, S3, DynamoDB, EventBridge and Step Functions.
---

# AWS Serverless

## Objective
Design event-driven, managed AWS workloads with appropriate reliability and cost controls.

## Evaluate
- API Gateway and Lambda integration.
- EventBridge, SQS and SNS patterns.
- Step Functions orchestration.
- S3 storage and event notifications.
- DynamoDB data modelling and access patterns.
- IAM least privilege.
- VPC connectivity where required.
- Retries, dead-letter queues and idempotency.
- Concurrency, quotas and timeout limits.
- CloudWatch metrics, logs and alarms.
- Infrastructure as code and deployment strategy.

## Rules
Verify service quotas and regional support.
Do not expose public endpoints without an explicit security design.
Estimate costs only when workload assumptions are supplied.

## Output
Return architecture, event flow, IAM considerations,
failure handling, observability and deployment plan.
