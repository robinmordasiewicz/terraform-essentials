Modules
=======

A Terraform `module <https://www.terraform.io/docs/glossary#module>`_ is a collection of Terraform `configurations <https://www.terraform.io/docs/glossary#terraform-configuration>`_ that manage a particular type of infrastructure resource. For example, you may write a module to configure an Azure Resource-Group, or a module to provide configure the virtual-network and subnets that a BIG-IP is deployed to. For example, you may have a module called "virtual_network" that configures an Azure Virtual Network, then call that same module to create a client network, server network, and BIG-IP network. The code to create a virtual-network is only written once, as a module, but then executed multiple times with different input variables.

Modules are to Terraform what library files are to programming languages. They allow you to configure one or more elements, and then can be re-used multiple times in the same Terraform run to configure those elements multiple times.

Demonstrating Terraform modules is beyond the scope of this guide, but I may add a simple example if there is demand.

