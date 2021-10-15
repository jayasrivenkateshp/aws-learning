# CIDR classless interdomain routing 

* CIDR block size can be between /16 and /28

* the CIDR block must not overlap with any existing CIDR block that`s associated with the vpc

* you cannot increase or decrease the size of an existing CIDR block

* the first four and last ip address are not availabe for use

# VPC CIDR blocks and subnets

* vpc CIDR block 10.0.0.0   ---- 10.0.00/16
* /16 subnet mask 255.255.0.0 

* VPC subnets have a longer subnet mask than the CIDR block by using additional bits from the host portion

   - subnets
* 10.0.1.0/24
* 10.0.2.0/24
* 10.0.3.0/24

* ensure you have enough networks and hosts

* bigger CIDR blocks are typically netter (more flexibility)

* smaller subnets are ok for most use cases

* consider deploying application tiers per subnet

* split your HA resources across subnets in different AZs

* VPC peering requires non-overlapping CIDR blocks