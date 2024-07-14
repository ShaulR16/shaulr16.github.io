---
description: |
  Launches the specified number of instances using an AMI for which you have permissions.
command: |
  aws ec2 run-instances --count 1 --instance-type t2.micro --image-id <Image ID>
items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Exploitation
references:
  - https://docs.aws.amazon.com/cli/latest/reference/ec2/run-instances.html
---
