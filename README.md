# Notes-on-Terraform
Learnings, Experiments and Readings on Terraform.

- HashiCorp Configuration Language.
 [ami, instance_type]


## Resource Graph
Terraform creates a graph of all the resources, and parallelizes the modification / creation of non-dependent resources. Hence, Terraform builds infrastructure as efficiently as is possible, and operators also get valubale information about the dependencies in their infrastructure. 

## Infrastructure as Code
- Save Time: Easy to Reuse.
- High readability.
- Make operations more structured with terraform plan.


Also,
- Platfrom Agnostic - Define configuration files to manage different cloud porviders (an heterogeneous environment) without the need to curate the workflow for each different provider. 
- Operator Confidence

## Commands
- ``` terraform plan```
- ```terraform init```
- ```terraform apply```
