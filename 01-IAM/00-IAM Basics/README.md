# IAM Identity Access Management

1. IAM ia a **globally resilient service**

   - No cost for IAM 
   - Allows and denys its identities on its AWS console (via Policies)
   - No direct control on external accounts or users
   - **IAM only controls local identities in your account**
   - **IAM lets you create Identity Federation(facebook,google) and MFA**

2. IAM has its own database

3. Any data is always secured secure across all AWS regions

4. IAM we see in our account has its own dedicated instance of AMI

5. With IAM account Root User cn do anything in the account 

6. IAM of your account trusted fully by the account

7. IAM as a service can do much as root User

8. Inside IAM you can create other Identites (multiple Identities)

9. IAM can allow these identities to do certain things

## IAM allows you to create Three different types of objects


| IAM Users | IAM Groups | IAM Roles
| -------- | ---------- | ---------- |
| Identities which represent humans or applications that need access to your account | Collection of related users EX: development team,finance team,HR team | Can be used by services,or granting external access to your account |


