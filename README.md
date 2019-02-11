# terraform_AWS_provider

### Purpose of the repsoitory
- The repository create EC2 instance in AWS using terraform tool.

### List of files files in respository.
- main.tf - file with terraform configuration code.

### How to use this repository
- Install `terraform` by following this [instructions](https://www.terraform.io/intro/getting-started/install.html).
- Clone the repository to your local computer: `git clone git@github.com:nikcbg/tfe_variables_aws`.
- Go into the cloned repo on your computer: `cd tfe_variables_aws`.

### Note: NEVER make your AWS access keys public so you can prevent your account from been compromised.
- To be able to authenticate to your AWS account without compromising your credentials you need to use environment variables.
- You need to get your secret access and access keys form your AWS account, you can follow this [instructions](https://docs.aws.amazon.com/general/latest/gr/managing-aws-access-keys.html)
- Execute `export AWS_ACCESS_KEY_ID=your_access_key_here` 
- Execute `export AWS_SECRET_ACCESS_KEY=your_secret_access_key_here` 

### Commands needed to build the EC2 instance.
Command execution	| Command outcome
------------------|----------------
terraform init	| to initialize the working directory
terraform plan	| to create execution plan for changes to be applied.
terraform apply	| to apply the desired changes.
terraform destroy | to destroy the infrastructure that was created.
   



