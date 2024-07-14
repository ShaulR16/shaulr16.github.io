---
layout: page
title: Contribute
---

## Structure

Each Command is defined in a file in the [`_cloudcmd`] folder named as `<Provider-Service-Name_of_command>.md`, such file consists only of a [YAML] front matter which describes the command and its attributes.

The full syntax is the following:

```
---
description: |
  AWS CLI command to delete a CloudTrail trail named "replace_with_CloudTrail_name" using the "administrator" profile.

  Reference:

    Cloudguard Name: replace_with_CloudTrail_name

command: |
  aws cloudtrail delete-trail --name replace_with_CloudTrail_name --profile administrator
items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - DefenseEvasion
references:
  - https://docs.aws.amazon.com/cli/latest/reference/cloudtrail/delete-trail.html
---

```

Where `ITEM` is one of the values described in the [`_data/items.yml`] file, `SERVICE` is one of the values described in the [`_data/services.yml`] file, `OS` (Owned Position) is one of the values described in the [`_data/OS.yml`] file, `ATTACK_TYPE` is one of the values described in the [`_data/attack_types.yml`] file, and `LINK` is a link to download the related tool for that command as well as links to any other relevant information about what the command is doing. 

Feel free to use any file in the [`_cloudcmd/`] folder as an example.

## Pull request process

Pull requests adding new items in [`_data/items.yml`], services in [`_data/services.yml`], OS in [`_data/OS.yml`], or attack types in [`_data/attack_types.yml`] are allowed and subjected to project maintainers vetting.

[YAML]: http://yaml.org/
[`_cloudcmd/`]: https://github.com/cloudcmd/cloudcmd.github.io/tree/master/_cloudcmd
[`_data/services.yml`]: https://github.com/cloudcmd/cloudcmd.github.io/blob/master/_data/services.yml
[`_data/items.yml`]: https://github.com/cloudcmd/cloudcmd.github.io/blob/master/_data/items.yml
[`_data/OS.yml`]: https://github.com/cloudcmd/cloudcmd.github.io/blob/master/_data/OS.yml
[`_data/attack_types.yml`]: https://github.com/cloudcmd/cloudcmd.github.io/blob/master/_data/attack_types.yml
