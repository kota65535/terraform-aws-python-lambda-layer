# terraform-aws-python-lambda-layer

<!-- BEGIN_TF_DOCS -->
## Requirements

| Name | Version |
|------|---------|
| <a name="requirement_terraform"></a> [terraform](#requirement\_terraform) | >= 1.4.0 |

## Providers

| Name | Version |
|------|---------|
| <a name="provider_aws"></a> [aws](#provider\_aws) | n/a |
| <a name="provider_terraform"></a> [terraform](#provider\_terraform) | n/a |

## Modules

No modules.

## Resources

| Name | Type |
|------|------|
| [aws_lambda_layer_version.main](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/lambda_layer_version) | resource |
| [terraform_data.create_lambda_layer](https://registry.terraform.io/providers/hashicorp/terraform/latest/docs/resources/data) | resource |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_name"></a> [name](#input\_name) | Lambda layer name | `string` | n/a | yes |
| <a name="input_output_path"></a> [output\_path](#input\_output\_path) | Output file path | `string` | n/a | yes |
| <a name="input_python_version"></a> [python\_version](#input\_python\_version) | Python version | `string` | n/a | yes |
| <a name="input_requirements_path"></a> [requirements\_path](#input\_requirements\_path) | requirements.txt file path | `string` | n/a | yes |

## Outputs

| Name | Description |
|------|-------------|
| <a name="output_lambda_layer_version"></a> [lambda\_layer\_version](#output\_lambda\_layer\_version) | n/a |
<!-- END_TF_DOCS -->