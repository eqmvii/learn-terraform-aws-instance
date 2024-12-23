# Notes

To set up AWS CLI: 

export AWS_ACCESS_KEY_ID=$ACCESS_KEY

export AWS_SECRET_ACCESS_KEY=$SECRET_ACCESS_KEY

terraform init 
terraform fmt
terraform validate
terraform plan
terraform apply

or

terraform apply -var "instance_name=YetAnotherName"

# examine terraform.tfstate file - which is sensative and should always be git-ignored!
terraform show

terraform state list