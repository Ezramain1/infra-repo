Terraform code for cloud infrastructure
- **Structure**:  ```
  infra-repo/
  ├── modules/
  │   └── eks-platform/
  │       ├── main.tf
  │       ├── variables.tf
  │       └── outputs.tf
  ├── environments/
  │   ├── dev/
  │   │   └── main.tf
  │   ├── staging/
  │   │   └── main.tf
  │   └── production/
  │       └── main.tf 
