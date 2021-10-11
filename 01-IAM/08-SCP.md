### SCP (Service Control Policies)

* SCP are account permissions bounderies

* they limit wt the account (including account root user) can do

* SCP don`t grant any permissions 
    - allow list or deny list

* Service control policies (SCPs) are a type of organization policy that you can use to manage permissions in your organization. 

* SCPs offer central control over the maximum available permissions for all accounts in your organization. 

* SCPs help you to ensure your accounts stay within your organization’s access control guidelines.

* SCPs are available only in an organization that has all features enabled. 
 
* SCPs aren't available if your organization has enabled only the consolidated billing features. 
 
* For instructions on enabling SCPs, see Enabling and disabling policy types.

* SCPs alone are not sufficient to granting permissions to the accounts in your organization. 

* No permissions are granted by an SCP. An SCP defines a guardrail, or sets limits, on the actions that the account's administrator can delegate to the IAM users and roles in the affected accounts.

* The administrator must still attach identity-based or resource-based policies to IAM users or roles, or to the resources in your accounts to actually grant permissions. 
 
* The effective permissions are the logical intersection between what is allowed by the SCP and what is allowed by the IAM and resource-based policies.