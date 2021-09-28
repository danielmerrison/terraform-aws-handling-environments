# Examples

## Apply development configuration

```bash
cd dev
# You only need to do terragrunt apply as it will automatically initialise the project
terragrunt apply 
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
# You only need to do terragrunt apply as it will automatically initialise the project
terragrunt apply 
# output: 
# response = {
#   "external-module-response" = "EXTENRAL-MODULE: hello, production"
#   "internal-module-response" = "INTERNAL-MODULE: hello, production"
#   "this" = "main.tf: production"
# }
```
