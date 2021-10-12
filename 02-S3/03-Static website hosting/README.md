# Static Website Hosting

You can use Amazon S3 to host a static website

## Create a bucket:

* The following instructions provide an overview of how to create your buckets for website hosting. For detailed, step-by-step instructions on creating a bucket, see Creating a bucket.

* To create a bucket

* Sign in to the AWS Management Console and open the Amazon S3 console at https://console.aws.amazon.com/s3/.

* Choose Create bucket.

* Enter the Bucket name (for example, example.com).

*  Choose the Region where you want to create the bucket.

*  Choose a Region that is geographically close to you to minimize latency and costs, or to address regulatory requirements. The Region that you choose determines your Amazon S3 website endpoint. For more information, see Website endpoints.

*  To accept the default settings and create the bucket, choose Create.

# Enable static website hosting:

* After you create a bucket, you can enable static website hosting for your bucket. You can create a new bucket or use an existing bucket.

* To enable static website hosting

* Sign in to the AWS Management Console and open the Amazon S3 console at https://console.aws.amazon.com/s3/.

* In the Buckets list, choose the name of the bucket that you want to enable static website hosting for.

* Choose Properties.

* Under Static website hosting, choose Edit.

* Choose Use this bucket to host a website.

* Under Static website hosting, choose Enable.

* In Index document, enter the file name of the index document, typically index.html.

* The index document name is case sensitive and must exactly match the file name of the HTML index document that you plan to upload to your S3 bucket. When you configure a bucket for website hosting, you must specify an index document. Amazon S3 returns this index document when requests are made to the root domain or any of the subfolders. For more information, see Configuring an index document.

* To provide your own custom error document for 4XX class errors, in Error document, enter the custom error document file name.

* The error document name is case sensitive and must exactly match the file name of the HTML error document that you plan to upload to your S3 bucket. If you don't specify a custom error document and an error occurs, Amazon S3 returns a default HTML error document. For more information, see Configuring a custom error document.

    - (Optional) If you want to specify advanced redirection rules, in Redirection rules, enter XML to describe the rules.

* For example, you can conditionally route requests according to specific object key names or prefixes in the request. For more information, see Configure redirection rules to use advanced conditional redirects.

    - Choose Save changes.

*  Amazon S3 enables static website hosting for your bucket. At the bottom of the page, under Static website hosting, you see the website endpoint for your bucket.

# Under Static website hosting, note the Endpoint:

* The Endpoint is the Amazon S3 website endpoint for your bucket. After you finish configuring your bucket as a static website, you can use this endpoint to test your website.

# Edit Block Public Access settings:

* By default, Amazon S3 blocks public access to your account and buckets. If you want to use a bucket to host a static website, you can use these steps to edit your block public access settings.

* Warning
    Before you complete this step, review Blocking public access to your Amazon S3 storage to ensure that you understand and accept the risks involved with allowing public access. When you turn off block public access settings to make your bucket public, anyone on the internet can access your bucket. We recommend that you block all public access to your buckets.

* Open the Amazon S3 console at https://console.aws.amazon.com/s3/.

* Choose the name of the bucket that you have configured as a static website.

* Choose Permissions.

* Under Block public access (bucket settings), choose Edit.

* Clear Block all public access, and choose Save changes.

 