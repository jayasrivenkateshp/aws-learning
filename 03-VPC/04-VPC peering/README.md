# VPC peering  

* to connect instances running in different vpcs together with IPV4 and IPV6 addresses

* VPC peeering allows route to ip addresses internally between those vpcs

* its using aws global network to communicate betweeen different vpcs

* peering does`nt aupport transitive peering - it will go by step by step - not transitive - mesh required

* vpcs can be different accounts or regions

* `VPC peering`
 - vpc peering can be between regions

 * security groups are required for vpc peering

 * and a route table attached to this peering
