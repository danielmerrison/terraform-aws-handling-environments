# Examples

## Apply development configuration

```bash
cd dev
terraform init
terraform apply
# output: 
# response = {
#   "external-module-response" = "EXTENRAL-MODULE: hello, development"
#   "internal-module-response" = "INTERNAL-MODULE: hello, development"
#   "this" = "main.tf: production"
# }
```

## Apply production configuration

```bash
cd prod
terraform init
terraform apply
# output: 
# response = {
#   "external-module-response" = "EXTENRAL-MODULE: hello, production"
#   "internal-module-response" = "INTERNAL-MODULE: hello, production"
#   "this" = "main.tf: production"
# }
```
