<!-- note marker start -->
NOTE: This repo contains only the documentation for the private BoltsOps repo code.
Original file: https://github.com/boltops-learn/terraspace-azure-network/blob/master/vendor/modules/network/README.md
The docs are publish so they are available for interested subscribers.
For access to the source code, you can become a BoltOps subscriber.
See: https://learn.boltops.com

<!-- note marker end -->

# Terraform Azure Network

[![BoltOps Badge](https://img.boltops.com/boltops/badges/boltops-badge.png)](https://www.boltops.com)

Simple example with:

* [azurerm_virtual_network](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/virtual_network)
* [azurerm_subnet](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/subnet)


## Add to Terrafile

```ruby
mod "network", source: "boltops-tools/terraform-azure-network/aws"
```

## Import Example

    terraspace bundle # installs to vendor/modules/network
    terraspace bundle example network # imports to app/stacks/network

## Configure Tfvars

    terraspace seed network # creates starter app/stacks/network/tfvars/dev.tfvars

## Deploy

    terraspace up network

## Clean Up

    terraspace down network

