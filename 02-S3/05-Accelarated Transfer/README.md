## Accelerated Transfer

* S3 Transfer Acceleration utilizes the CloudFront Edge Network to accelerate uploads to S3 from every region

* Instead of directly uploading the file to S3 bucket, you will get a distinct URL that will upload the data to the nearest edge location which in turn transfer the file to S3 bucket. 

* We got an S3 bucket hosted outside the Ireland region, and we have different users all around the world. If users try to upload the file to S3 bucket, it would be done through an internet connection.

* Transfer Acceleration utilizes the local edge location, and they use the distinct URL that we saw earlier will upload the file to their nearest edge location.

* The edge location will then send the file up to the S3 bucket. Therefore, we can say that Amazon optimizes the process by using the Transfer Acceleration service