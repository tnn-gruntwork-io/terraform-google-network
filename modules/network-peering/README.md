# Network Peering Module

The Network Peering module creates [VPC network peering connections](https://cloud.google.com/vpc/docs/vpc-peering)
between networks. Normal networks are isolated, but some traffic may need to flow between them, such as allowing DevOps
tools running in a [management network](https://github.com/tnn-gruntwork-io/terraform-google-network/tree/master/examples/network-management)
to talk to apps or services in an [application network](https://github.com/tnn-gruntwork-io/terraform-google-network/tree/master/examples/network-host-application).

When using a [host project](https://github.com/tnn-gruntwork-io/terraform-google-network/tree/master/modules/project-host-configuration) with component host networks, peerings should be made in the
host project.

## How do you use this module?

* See the [root README](https://github.com/tnn-gruntwork-io/terraform-google-network/blob/master/README.md) for instructions
on using Terraform modules.
* See the [examples](https://github.com/tnn-gruntwork-io/terraform-google-network/tree/master/examples) folder for example
usage.
* See [variables.tf](https://github.com/tnn-gruntwork-io/terraform-google-network/blob/master/modules/network-peering/variables.tf)
for all the variables you can set on this module.
