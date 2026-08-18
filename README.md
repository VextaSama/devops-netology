# devops-netology
git for learning

first modified


Гит проигнорирует конкретные файлы:
crash.log
crash.*.log
.terraform.tfstate.lock.info
.terraformrc
terraform.rc
override.tf
override.tf.json

Гит проигнорирует все файлы конкретных типов:
*.tfstate
*.tfstate.*
*.tfvars
*.tfvars.json
*_override.tf
*_override.tf.json

Гит проигнорирует директорию:
.terraform/