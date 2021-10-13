# ARN (AMAZON Resource Name)

* Amazon Resource Names (ARNs) are unique identities to give each AWS resources.

    - It can be an ec2 instance, EBS Volumes, S3 bucket, load balancers, VPCs, route tables, etc.

     **AWS ARN FORMET**

* we use ARN when we need to specify a certain resource across all regions

* you use ARN when your creating bucket policy in S3

* and you use ARN in route53

these are some examples given below

```
arn:aws:service:region:account-id:resource-id
arn:aws:service:region:account-id:resource-type/resource-id
arn:aws:service:region:account-id:resource-type:resource-id 
```

