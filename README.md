<!-- note marker start -->
NOTE: This repo contains only the documentation for the private BoltsOps repo code.
Original file: https://github.com/boltops-learn/terraspace-azure-network/blob/master/README.md
The docs are publish so they are available for interested subscribers.
For access to the source code, you can become a BoltOps subscriber.
See: https://learn.boltops.com

<!-- note marker end -->

# Terraspace Azure Network Example

[![BoltOps Badge](https://img.boltops.com/boltops/badges/boltops-badge.png)](https://www.boltops.com)

This contains example code that creates:

* Azure Network

It uses:

* Terraform Registry Module: [boltops-tools/network/azure](https://registry.terraform.io/modules/boltops-tools/network/azure/latest)

## Env Vars

You should configure these env vars:

* ARM_CLIENT_ID
* ARM_CLIENT_SECRET
* ARM_SUBSCRIPTION_ID
* ARM_TENANT_ID

As covered in: [Terraspace Azure Getting Started Docs: Configure Azure](https://terraspace.cloud/docs/learn/azure/configure/)

## Deploy

To deploy:

    terraspace up network

## Video

[![Watch the video](https://uploads-learn.boltops.com/7p5wdi7y363gpt4zi9t6dpiwbn1f)](https://learn.boltops.com/courses/terraspace-azure/lessons/terraspace-azure-network)

Note: Premium video content requires a subscription.
