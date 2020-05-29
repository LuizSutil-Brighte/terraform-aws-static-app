# terraform-aws-static-app

[![Lint Status](https://github.com/DNXLabs/terraform-aws-static-app/workflows/Lint/badge.svg)](https://github.com/DNXLabs/terraform-aws-static-app/actions)
[![LICENSE](https://img.shields.io/github/license/DNXLabs/terraform-aws-static-app)](https://github.com/DNXLabs/terraform-aws-static-app/blob/master/LICENSE)

<!--- BEGIN_TF_DOCS --->

## Requirements

| Name | Version |
|------|---------|
| terraform | >= 0.12.20 |

## Providers

| Name | Version |
|------|---------|
| aws | n/a |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| certificate\_arn | n/a | `any` | n/a | yes |
| cloudfront\_logging\_bucket | Bucket to store logs from app | `string` | `""` | no |
| cloudfront\_logging\_prefix | Logging prefix | `string` | `""` | no |
| cloudfront\_web\_acl\_id | Optional web acl (WAF) to attach to CloudFront | `string` | `""` | no |
| hosted\_zone | n/a | `any` | n/a | yes |
| hostname\_create | Create hostname in the hosted zone passed? | `bool` | `true` | no |
| hostnames | n/a | `list(string)` | n/a | yes |
| name | n/a | `any` | n/a | yes |
| s3\_bucket\_id | n/a | `any` | n/a | yes |

## Outputs

No output.

<!--- END_TF_DOCS --->

## Author
Module managed by [DNX Solutions](https://github.com/DNXLabs).

## License
Apache 2 Licensed. See [LICENSE](https://github.com/DNXLabs/terraform-aws-static-app/blob/master/LICENSE) for full details.