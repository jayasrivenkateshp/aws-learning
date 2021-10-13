# IAM POLICY

- IAM lets you create these policies  

- which can be used to **Allow or Deny** Access to AWS services

- **IAM policy can`t do anything alone**

- Only when you attach the policies to other **Identities**(User Groups,Roles)

* Policies are type of policies which get attached to identities inside Aws  

   - Identities are IAM users, 
   - IAM groups and IAM roles.

## IAM policy : 
  
- IAM policy or Identity policy is Just a set of Security Statements to Aws

- it grants access and denies access to Aws services, which uses that policy

- identity policies are also known as policy Documents are created using **JSON**

- so, it will help you a lot 

## IAM Policy document :

- every interaction that you have with Aws is a Combination of two main things

- the resource that you're interacting with, 

- and the actions that you're attempting to perform, on that resource

      Ex: - you are attempting to perform with an S3 bucket and the action you might be attempting to perform, in add an object into the bucket

- The Statement only applies if the interaction that you're having with Aws match the action and the resource

- the action part of statement matches one or more actions

- It can be very specific and lists specific individual action.

## IAM policies :

   * Inline policies 
   * Managed policies

* Inline policies:
    - you are applying the JSON to each account individually, it become isolated bits of JSON 

* Managed policies:
    - Managed policies are created as their own object

* first you'd create the managed policy. JSON they can attach that policy to any identities 

       * Reusable
       * Low Management overhead

## It can be two policies

  * Trust policy        }   
                        }  **Secure Token Service**
  * permission policy   }