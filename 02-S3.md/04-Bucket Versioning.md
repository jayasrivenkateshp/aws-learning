## S3 Versioning

> Versioning is a means of keeping the multiple forms of an object in the same S3 bucket. 

> Versioning can be used to retrieve, preserve and restore every version of an object in S3 bucket.

  - For example, bucket consists of two objects with the same key but with different version ID's such as photo.jpg (version ID is 11) and photo.jpg (version ID is 12).

> Versioning-enabled buckets allow you to recover the objects from the deletion or overwrite. It serves two purposes:

> If you delete an object, instead of deleting the object permanently, it creates a delete marker which becomes a current version of an object.

> If you overwrite an object, it creates a new version of the object and also restores the previous version of the object