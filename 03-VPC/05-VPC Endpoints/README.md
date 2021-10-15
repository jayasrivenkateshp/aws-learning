# VPC endpoints

* VPC endpoint enables you to directly connect to aws resources

* VPC interface endpoint
* VPC gateway endpoint

## VPC interface endpoints

* a ec2 instance is placed in vpc and we create a endpoint ENI in the subnet

* instance can connect by that ENI to public services 

* each endpoint can connect to one of many aws services

* this is the way we can connect ec2 instances to public aws service using a private ip

## VPC gateway endpoints

* a ec2 instance is placed in vpc and we create a s3 gateway endpoint  in the subnet

* a routetable entry is required with the prefix llist for s3 and the gateway id

* ec2 instance conects to s3 using a private ip

* finally ec32 instance connects s3 gateway  and it connects to amazon s3

* you can secure with IAM policies can be applied to endpoints

* we can alo apply bucket policies can limit access to endpoint source

### difference between Interface endpoint and gateway endpoint

|    | Interface endpoint | gateway endpoint
| ------ | ------- | ------
| what | elastic network interface with a private ip | a gateway that is target for a specific route
| how | uses DNS entries to redirect traffic | uss prefix lists in the route table to redirect traffic
| thich services | API gateway, cloudformation, cloud watch etc | amazon S3, dynamoDB
| security | security groups | VPC endpoint policies

