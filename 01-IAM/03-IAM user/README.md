# IAM USER

**Identities which represent humans or applications that need access to your account**

IAM users are an Identity used for anything requiring long - term credentials for Aws access

 Eg: Humanys, Applications or Service Accounts

⇒ if you need to give something access to your -Aws Account, you can picture one thing,
    IAM user

⇒ IAM starts with a principal an entity trying to access an Aws Account

    * principals can be computers, sevices, or a group have any of those services

    * principle needs to authorize and be authorized 

⇒ 5000 IAM users per one account IAM is a Global Service.

⇒ 1 User can add upto 10 IAM Groups

⇒ A user group can contain many users, and a user can belong to multiple user groups.

⇒ when you are creating a user Grant access (Programmatic & Console access)

     - users need to reset the password during next sign-up

⇒ permissions:
     - create policies and assign policies 
     - it will create access key and secret key
