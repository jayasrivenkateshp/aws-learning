# Amazon VPC 

* a vpc is a logically isolated portion of the AWS cloud within a region 

* `Subnets are created within AZs`

* subnets can be
   - `private subnet`
   - `public subnet`

* Route table makes sure the data sending is in right place (we need to give destinations or targets)

* Route tables are configuring route for vpc

* the vpc route takes care of routing within the vpc and outside of vpc

* if we want to access internet we need `IGW`

* `IGW` is attached to your vpc

* one IGW for vpc

* IGW is used for sending data out to the internal that is ` egress traffic` and in form the internet `ingress topic`

* with IGW you can create multiple vpc`s in one region (default 5)

* vpc is a master block of address

* CIDR routing from the overall cides block we can then create the networking for our subnets

* subnets is subset of over ip addresses

* when you create a vpc, you must specify a range of ipv4 addresses in the form of CIDR

* you have full control over who has access to the aws resources inside your vpc

* a default vpc is created in each region with a subnet in each AZ