# cfn-drift-detection

`cfn-drift-detection` is a simplified AWS CloudFormation template delivering an AWS Config Rule with IAM role to detect CloudFormation drift in an account. The template is to be deployed to a target region and will check all CloudFormation stacks for drift.

## Prerequisites

The template requires `Config` to be deployed in the region.
