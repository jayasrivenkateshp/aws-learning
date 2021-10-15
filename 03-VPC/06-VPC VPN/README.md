# AWS client VPN

* this a way that you can connect client computer to AWS data center to a VPC via VPN connection

* in aregion we have vpc and it has 2 subnets

* VPN creates a VPN endpoint 

* the VPN endpoint is associated with subnets in VPC (client VPN network interfaces created in subnet)

* we have client VPn placed in a place 

* this client VPN is conneted to this VPN endpoint through VPN client connects over SSL/TLS(443)

* VPN endpoint performs as Source address translation with CIDR block associated between the client VPN to VPC

* local route of associated subnet is added to client route table

# AWS Site-to-Site VPN

* you will connect a customer data ceter or office location to AWS 