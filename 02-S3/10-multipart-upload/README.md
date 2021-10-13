# Multi-part upload

* we can use multi part upload for long data uploads

* the data will be broken up to pieces

* minimum data 100mb for muti-part

* maximum 10,000 parts from (5 mb -5 gb)

## Why we use this ?

* when we upload large amounts of data if anything fails to upload 
  - due to network issues or any other issues

* we need to start uploading again (from start)

* so we use this method to upload large amounts of data 

* if any part fails, we can again upload that certain part

* no risk of uploading again