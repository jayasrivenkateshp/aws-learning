# AWS Organization

* aws organization can be created for having more aws accounts in business company

* for creating aws organization you need one root user aws account

* in that root user account you create organization 

   - master account (root user)
   - member account

* in this process member account create trusted plicies for organization 

* and also create permission policies for organization 

* then you need to attah policies for master account

* for giving the full access to master account 

* and also you can create organization units 

* in organization units you can add your members 

* the bill only be generated to master account ( if member account uses)

* policies apply to master account can be applied to all the member accounts (ou)

* SCPs specify the maximum permissions for an organization, organizational unit (OU), or account. When you attach an SCP to your organization root or an OU,

* the SCP limits permissions for entities in member accounts.
