# Shared VPC Host Project

This example illustrates how to create a [Shared VPC](https://cloud.google.com/vpc/docs/shared-vpc) host project.

It includes creating the host project and using the [network module](https://github.com/terraform-google-modules/terraform-google-network) to create network.

[^]: (autogen_docs_start)

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|:----:|:-----:|:-----:|
| billing\_account | The ID of the billing account to associate this project with | string | - | yes |
| credentials\_path | Path to a Service Account credentials file with permissions documented in the readme | string | - | yes |
| host\_project\_name | Name for Shared VPC host project | string | `shared-vpc-host` | no |
| network\_name | Name for Shared VPC network | string | `shared-network` | no |
| organization\_id | The organization id for the associated services | string | - | yes |

## Outputs

| Name | Description |
|------|-------------|
| host\_project\_id | The ID of the created project |
| network\_name | The name of the VPC being created |
| network\_self\_link | The URI of the VPC being created |

[^]: (autogen_docs_end)