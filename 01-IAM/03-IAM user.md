### IAM USER

**Identities which represent humans or applications that need access to your account**

IAM users are an Identity used for anything requiring long - term Aws access
 Eg: Humanys, Applications or Service Accounts

⇒ if you need to give something access to your -Aws Account, you can picture one thing,
   one appliication IAM user

⇒ IAM starts with a principal an entity trying to access an Aws Account

    * principals can be computers, sevices, or a group have any of those services

    * principle needs to authorize and be authorized 

⇒ 5000 IAM users per one account IAM Global Service.

⇒ 1 User can add upto 10 IAM Groups

⇒ A user group can contain many users, and a user can belong to multiple user groups.

⇒ when you are creating a user Grant access (Programmatic & Console access)
     - users need to reset the password during next sign-up
* permissions:
     - create policies and assign policies 
     - it will create access key and secret key

## Users and credentials

You can access AWS in different ways depending on the user credentials:

Console password: A password that the user can type to sign in to interactive sessions such as the AWS Management Console. Disabling the password (console access) for a user prevents them from signing in the to the AWS Management Console using their user name and password. It does not change their permissions or prevent them from accessing the console using an assumed role.

Access keys: A combination of an access key ID and a secret access key. You can assign two to a user at a time. These can be used to make programmatic calls to AWS. If the user has active access keys, they continue to function and allow access through the AWS CLI, Tools for Windows PowerShell, AWS API, or the AWS Console Mobile Application.