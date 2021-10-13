## S3 Versioning

* Versioning is keeping the multiple forms of an object in the same S3 bucket. 

* Versioning can be used to retrieve, preserve and restore every version of an object in S3 bucket.

* with out versioning u dint get a version id of a object in ur account

* when you enable versioning u get version id for every object in yout account
 - like this (image.jpg - vsid oo1, image2.jpg - vsid 002 )

* Versioning-enabled buckets allow you to recover the objects from the deletion or overwrite.
* It serves two purposes:

* If you delete an object, instead of deleting the object permanently, it creates a delete marker which becomes a current version of an object.

* there is a option you can get to retrive your objects or files from delete makr

* If you overwrite an object, it creates a new version of the object and also restores the previous version of the object