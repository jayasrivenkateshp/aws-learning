## ARN (AMAZON Resource Name)

* Amazon Resource Names (ARNs) are uniques identifiers assigned to individual AWS resources.

    - It can be an ec2 instance, EBS Volumes, S3 bucket, load balancers, VPCs, route tables, etc.

     **AWS ARN FORMET**

most cases, you can build the ARN URL yourself following the below format.

---
**arn:aws:service:region:account-id:resource-id**
**arn:aws:service:region:account-id:resource-type/resource-id**
**arn:aws:service:region:account-id:resource-type:resource-id**
**In the above formats, towards the end, you can see the difference in the formats which changes as per the resource types**
---

**S3 ARN Example**:
       S3 has a flat hierarchy of buckets and associated objects. Here is how an s3 arn would look like

   **arn:aws:s3:::devopscube-bucket**

**EC2 ARN Example**:
       ec2 service has sub resource-types like image, security groups etc. The following example uses the instance resource-type.

   **arn:aws:ec2:us-east-1:4575734578134:instance/i-054dsfg34gdsfg38**

**Lambda ARN Example**: 
       Lambda functions can have multiple versions. Here the version is the qualifier. To have arn of the specific Lambda version, you need to mention the version number at the last as shown below

   **arn:aws:lambda:us-east-1:4575734578134:function:api-fucntion:1**