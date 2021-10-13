## Accelerated Transfer

* S3 Transfer Acceleration uses the CloudFront Edge Network to perform uploads to S3 from all regions

* Instead of directly uploading the file to S3 bucket, you will get a distinct URL that will upload the data to the nearest edge location which in turn transfer the file to S3 bucket. 

* We got an S3 bucket hosted outside the India region, and we have different users all around the world. If users try to upload the file to S3 bucket, it would be done through an internet connection.

* Transfer Acceleration uses the local edge location, and they use the distinct URL that we said will upload the file to their nearest edge location.

* The edge location will then send the file up to the S3 bucket. 

* using accelerated transfer the network speed is very high to send objects to other regions

* it will use edge locations present in every region to transfer data
   - high network speed
   - low latency
   - high availability
   - no disturbance