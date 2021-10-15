# security groups

* security groups  ca be applied to instance in any subnet

* security groups allow in instance level 

* security groups are statefull

* security groups are boundaries which can filter traffic

* at instance, it can going to filter the traffic going between instances in same subnet or across the subnet

* swcurity group has 2 sets of rules 
- inbound rule - traffic coming in
- outbound set - traffic going back

## difference between Stateful and stateless

| protocol | sorce ip |destination ip | source port | destination port
| ---- | ---- | ----- | ---- | --- |
| HTTP | 10.1.1.1 | 10.2.1.10 | 65188 | 80
| HTTP | 10.2.1.10 | 10.1.1.1 | 80 | 65188

web server<----------- firewall ---------------> client
(10.2.1.10)                                      (10.2.1.10)

| stateful | stateless
| ------- | -------- |
| a stateful firewall allows the return traffic automatically| a stateless checks for an allow rule for both connections
| only one rule is required for inbound communication | both rules applies
| you can only allow traffic | you can allow traffic and deny traffic
| security groups has no explicit deny | Nacls can explicitly allow and explicitly deny traffic

# NACLs

* network access control lists

* NACLs can through of firewalls which surrounded by vpc subnets

* all vpcs are created within a default network acl

* acl is associated with all subnets in vpc

* NACLs are used when traffic enter are leaves a subnet

* these are only used when data croses the traffic

* NACLs cannot be associted with any aws resources only for `subnets`

* 1 subnet = 1 NACL at a time
* subnet needs 1 NACL at all times

* 1 NACL = multiple subnets