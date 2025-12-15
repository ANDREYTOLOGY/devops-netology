# devops-netology
one breanch

## Паттерны игнорирования в Terraform/.gitignore

Файл `Terraform/.gitignore` использует следующие паттерны:

- `**/.terraform/*` — любые файлы в папке `.terraform` на любом уровне вложенности
- `*.tfstate` — все файлы, заканчивающиеся на `.tfstate`
- `*.tfstate.*` — все файлы, содержащие `.tfstate.` в имени (например, `file.tfstate.backup`)
- `crash.*.log` — файлы, где между `crash.` и `.log` есть один сегмент (например, `crash.2023.log`)
- `*.tfvars` — все файлы с расширением `.tfvars`
- `*_override.tf` — файлы, заканчивающиеся на `_override.tf`
- `.terraformrc` — файл с точным именем `.terraformrc`
