# terraform-jenkins-eks
Deploy EKS Cluster using Terraform and Jenkins

Step 1. Create a new Github Repo "Terraform-jenkins-eks" Copy and clone on your Desktop and open With VS-Code
**Create backend/data/main/provider/terraform and provider.tf Folder
![image](https://github.com/rogerbarrow/terraform-jenkins-eks/assets/46138186/28f539ef-4b33-42b7-bc04-2cf5e4eb5cd0)


Make sure you currently have a S3 bucket created in AWS

![image](https://github.com/rogerbarrow/terraform-jenkins-eks/assets/46138186/0227f41a-28f6-4ee7-bfb4-46549c2183ef)

Imput data into backend.tf file

![image](https://github.com/rogerbarrow/terraform-jenkins-eks/assets/46138186/f7add93d-3567-4442-b764-8ab01fca3f02)

Next confirm the data source by going to google and type aws ami data source terraform

![image](https://github.com/rogerbarrow/terraform-jenkins-eks/assets/46138186/1f9a7211-623c-4b3a-8660-720e06d17571)


![image](https://github.com/rogerbarrow/terraform-jenkins-eks/assets/46138186/9e4d29b1-cafb-4170-b61f-d63d5b5c3a92)


Next in the main.tf you will want to create a VPC using Terraform modules


![image](https://github.com/rogerbarrow/terraform-jenkins-eks/assets/46138186/66b674e6-3343-42d6-838e-23dab8992447)

Initializing Terraform with command terraform init

![image](https://github.com/rogerbarrow/terraform-jenkins-eks/assets/46138186/012a7a85-1575-49a3-9d98-8f025725da2d)


Initializing Terraform with command terraform plan  command

Initializing Terraform with command terraform apply Command


![image](https://github.com/rogerbarrow/terraform-jenkins-eks/assets/46138186/d320fdb7-a575-4d9d-9c95-9d378b7bfde6)

![image](https://github.com/rogerbarrow/terraform-jenkins-eks/assets/46138186/a0a7beb2-86b7-4657-8b6b-62697d973db1)
