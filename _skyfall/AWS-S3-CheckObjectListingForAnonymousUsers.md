---
description: |
  Check if object listing is allowed for anonymous users by accessing the bucket URL via curl.

  Command Reference:

  	Domain: replace_with_domain
  	Bucket Name: replace_with_bucket_name

command: |
  curl http://replace_with_domain/replace_with_bucket_name | xmllint --format -f

items:
  - Object Listing for Anonymous Users
services:
  - AWS S3
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - No specific CLI reference; external command usage
---