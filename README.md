# Labs
For my Project ( Creating a 2-tier Amazon VPC using Terraform )

What is VPC?
VPC stands for Virtual Private Cloud.

It’s a custom-defined virtual network within the AWS Cloud.

Users can logically create their personal network, designing and implementing a separate and independent network that would operate in the AWS Cloud.

Primary components are Subnets, IP addresses, NAT Devices (Instances & Gateways), Route Tables, Internet & Virtual Private Gateways, Access Control Lists, Security groups, VPC Endpoints.

A subnet is a segment of the VPC IP address range, where we can launch EC2 Instances, RDS, and other AWS resources.

Subnet are further classified as Public and Private.


Basic Understanding before we start building VPC from scratch
When you create an Amazon AWS VPC, you specify a set of IP addresses in the form of a Classless Inter-Domain Routing (CIDR) block (Ex: 10.0.0.0/16).

You can assign a single CIDR block to a VPC. The allowed block size is between a /28 netmask and /16 netmask. In other words, the VPC can contain from 16 to 65,536 IP addresses.

What is Terraform?
It is an open-source IaaC (Infrastructure as a code) software tool where you define and create resources using providers in the declarative configuration language example JSON.

With Terraform, You can package and reuse the code in form of modules.

