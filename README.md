# Creating a basic Redshift Cluster

## Install terraform
```
brew install terraform
```

## Terraform init
```
terraform init \
    -var-file="dev.tfvars"
```

## Terraform plan
```
terraform plan \
    -var-file="dev.tfvars"
```

## Terraform apply
```
terraform apply \
    -var-file="dev.tfvars"
```