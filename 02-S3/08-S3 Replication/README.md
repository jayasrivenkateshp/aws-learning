# S3 Replication 

* S3 replication allows automatic replication of obejects from one bucket to another bucket

* s3 repliction have two types of buckets 

    - source bucket
    - destination bucket

* source bucket will be the primary bucket

* and destination bucket is were the copies are present (replicatd)

* s3 rplication can be

   - cross region 
   - same region
   - cross account replication

this is only one way communication 

**source bucket ------------>destination bucket**

* if you want to change destination bucket to source bucket you can change that

* An AWS Identity and Access Management (IAM) role that Amazon S3 can assume to replicate objects on your behalf

* when we wre replication objects or files it will take 15 mins to replicate in destination buket

* in destination bucket we give manual settings for (size of objects,storage class)


