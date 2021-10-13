# Static Website Hosting

You can use Amazon S3 to host a static website

## Create a bucket:

* Creating a bucket.

* To create a bucket

* Sign in to the AWS Management Console and open the Amazon S3 console at https://console.aws.amazon.com/s3/.

* Choose Create bucket.

* Enter the Bucket name (for example, example.com).

*  Choose the Region where you want to create the bucket.

*  To accept the default settings and create the bucket, choose Create.

# Enable static website hosting:

* After you create a bucket, you can enable static website hosting for your bucket. 

* To enable static website hosting

* choose the your bucket that you want to enable static website hosting for.

* Choose Properties.

* Under Static website hosting, choose Edit.

* Choose Use this bucket to host a website.

* Under Static website hosting, choose Enable.

* In Index document, enter the file name of the index document, typically index.html.

* give your error document

    - Choose Save changes.

*   S3 enables static website hosting for your bucket. At the bottom of the page, under Static website hosting, you see the website endpoint for your bucket.

# Under Static website hosting, note the Endpoint:

* The Endpoint is the S3 website endpoint for your bucket. After you finish configuring your bucket as a static website, you can use this endpoint to test your website.

# Edit Block Public Access settings:

* By default, Amazon S3 blocks public access to your account and buckets. If you want to use a bucket to host a static website.

* choose your bucket

* Choose Permissions.

* Under Block public access (bucket settings), choose Edit.

* Clear Block all public access, 

* and edit public access policy in down

* and choose Save changes.

 