---
title: Environment Setup
weight: 1
---

# Environment Setup
We need to install two CLI's to work with Terraform
- AWS CLI
- Terraform CLI
- A Code Editor

## AWS CLI
First you'll need to install the [AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html)

Once you have that installed you'll need to run ``aws configure``. It will ask for your **AWS Access Key**, your **AWS Secret Key**, and your **AWS Region**. 
{{< hint info >}}
You will only need to configure this once.
{{< /hint >}}


## Terraform CLI

Next after you have the AWS CLI configured you'll need to intall the [Terraform CLI](https://www.terraform.io/downloads.html)

To confirm installation just run this command:

```
terraform -v
```

## Code Editor

You can use just about any editor you want to modify terraform scripts. I would recommend using [Visual Studio Code](https://code.visualstudio.com/) by Microsoft. It's free and it has excellent support for Terraform. 