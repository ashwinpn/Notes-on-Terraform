# Notes-on-Terraform
Learnings, Experiments and Readings on Terraform.

- HashiCorp Configuration Language.
 [ami, instance_type]


## Resource Graph
Terraform creates a graph of all the resources, and parallelizes the modification / creation of non-dependent resources. Hence, Terraform builds infrastructure as efficiently as is possible, and operators also get valubale information about the dependencies in their infrastructure. 

## Infrastructure as Code
