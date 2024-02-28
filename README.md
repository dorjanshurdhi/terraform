## Terraform Commands

|   COMMAND     |  DESCRIPTION  |
|---------------|---------------|
|  `terraform init`  |  Initializes a working directory containing Terraform configuration files. |
|  `terraform plan`  |  Generates an execution plan, outlining actions Terraform will take. |
|  `terraform apply`  |  Applies the changes described in the Terraform configuration. |
|  `terraform destroy`  |  Destroys all resources described in the Terraform configuration. |
|  `terraform validate`  |  Checks the syntax and validity of Terraform configuration files. |
|  `terraform refresh`  |  Updates the state file against real resources in the provider. |
|  `terraform output`  |  Displays the output values from the Terraform state. |
|  `terraform state list`  |  Lists resources within the Terraform state. |
|  `terraform import`  |  Imports existing infrastructure into Terraform state. |
|  `terraform fmt`  |  Rewrites Terraform configuration files to a canonical format. |
|  `terraform graph`  |  Generates a visual representation of the Terraform dependency graph. |
|  `terraform providers`  |  Prints a tree of the providers used in the configuration. |
|  `terraform workspace list`  |  Lists available workspaces. |
|  `terraform workspace select`  |  Switches to another existing workspace. |
|  `terraform workspace new`  |  Creates a new workspace. |
|  `terraform workspace delete`  |  Deletes an existing workspace. |
|  `terraform output`  |  Retrieves output values from a module. |
|  `terraform state mv`  |  Moves an item in the state. |
|  `terraform state pull`  |  Pulls the state from a remote backend. |
|  `terraform state push`  |  Pushes the state to a remote backend. |
|  `terraform state rm`  |  Removes items from the state. |
|  `terraform taint`  |  Manually marks a resource for recreation. |
|  `terraform untaint`  |  Removes the ‘tainted’ state from a resource. |
|  `terraform login`  |  Saves credentials for Terraform Cloud. |
|  `terraform logout`  |  Removes credentials for Terraform Cloud. |
|  `terraform force -unlock`  |  Releases a locked state. |
|  `terraform import`  |  Imports existing infrastructure into your Terraform state. |
|  `terraform plan -out`  |  Saves the generated plan to a file. |
|  `terraform apply --auto -approve`  |  Initializes a working directory containing Terraform configuration files. |
|  `terraform apply -target=resource`  |  Applies changes only to a specific resource. |
|  `terraform destroy -target=resource`  |  Destroys a specific resource. |
|  `terraform apply -var=”key=value”`  |  Sets a variable’s value directly in the command line. |
|  `terraform apply -var -file=filename.tfvars`  |  Specifies a file containing variable definitions. |
|  `terraform apply -var -file=filename.auto.tfvars`  |  Automatically loads variables from a file. |
