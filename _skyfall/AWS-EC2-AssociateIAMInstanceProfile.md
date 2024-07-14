---
description: |
  Associates an IAM instance profile with a running or stopped instance.
command: |
  aws ec2 associate-iam-instance-profile --instance-id <Ec2 Instance ID> --iam-instance-profile Name=<Instance Profile>
items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Exploitation
references:
  - https://docs.aws.amazon.com/cli/latest/reference/ec2/associate-iam-instance-profile.html
---
