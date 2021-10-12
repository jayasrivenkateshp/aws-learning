## S3 Life Cycle Configuration

* You can create an S3 lifecycle configuration to control when specific objects are deleted from the StorageGRID system.

* The simple example in this section illustrates how an S3 lifecycle configuration can control when certain objects are deleted (expired) from specific S3 buckets

* A lifecycle configuration is a set of rules that are applied to the objects in specific S3 buckets. Each rule specifies which objects are affected and when those objects will expire (on a specific date or after some number of days).

> StorageGRID supports up to 1,000 lifecycle rules in a lifecycle configuration. Each rule can include the following XML elements:
  - Expiration: Delete an object when a specified date is reached or when a specified number of days is reached, starting from when the object was ingested.
  - NoncurrentVersionExpiration: Delete an object when a specified number of days is reached,  starting from when the object became noncurrent.
  - Filter (Prefix, Tag)
  -  Status
  -  ID