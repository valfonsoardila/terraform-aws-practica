﻿# Terraform Practica AWS (Levantamiento de infraestructura con codigo)

![logo](https://github.com/user-attachments/assets/458e8672-2463-49f9-880e-c4beb3118674)

![VPC](https://github.com/user-attachments/assets/a29276c3-2d05-4c81-b1dd-5f1565d9f7c6)

### Estructura de archivo de credenciale

Debe proporconar un archivo de credenciales con este formato y colocarlo a nivel del proyecto asegurese llamarlo, `credentials.tfvars`:

```bash
access_key = "*********"
secret_key = "*********"
```

- ### Ejecutar Terraform con las variables

```bash
terraform init
terraform plan -var-file="credentials.tfvars"
terraform apply -var-file="credentials.tfvars"
```
