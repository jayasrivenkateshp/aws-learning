# Multi Factor authentication

**MFA ia implemented within AWS**

## Why MFA is needed ?

 * The way that you usually log in to any web-based applications, Generally you use usernames and passwords.
 * If both of this is leaked any one can be you, anyone can take your username and password and use them to      
   log into an application and impersonate as you as an identity

# Factor (or) factors

 * Factors are pieces of evidnce which prove identity, and there are identified types of factors
 * so, when you hear the term **Single Factor Authentication**. It means one of these factors

# Multi-factor Authentication

→ It is when you use Multiple factors or multiple types of factory to log in to an application.

  There are four common factors that you use to Log in to **any web Application** 
 
    Knowledge:- The knowledge factor Includey usegname and passwords 

    possession :- This in Something that you have bank card, MF A device or an MFA application

    Inherent :- so this in Somsthing you have, so a So a fingerprint, or an is gean face scan's 
                voice identification

    Location: This can be either physical location, so particular set of co ordinates anywhere in the world or
              It can be type of network - that you currently Logged into accen a system either Logged into
              (corporate network) or home wifi network.

→ various Security procedures, taighty require Certain location which is a factor to age as past of  
  authentication process

This meany more factors that your authentication process cused this means more Security.. It also means that it's harder to fake your

# MFA in Aws Account -

→ By default you Log into this with a username and password
→ This is **single factor or one factor authentication**

# We can improve this using MFA:

  **MFA can be activated using physical MFA dovice**

    which is a key-fob-Style device, which generates ever-changing codes or Virtual MFA device
    
* which is added to an MFA application such as **google authenticator Virtual MFA Sevice** and there applicatiors run on phone or other devices can stole lolx of MFA&. So, that they can be used lote of different accounty when those services
    
* Now, to configure MFA within Aws for a specitic identity (root account user) you activate
   MFA for the user

* when you do So Aws generates a secret key, randomly generated key and it also generaty all the associated  
  information such as username it links to and the name of the service.

* This information need to be manually entered into an MFA application such as **google authentication**

* Aws use all of this information together the secrete key and additional information to generate a **QR code** and this QR code encodes all of this information in visual pattern

* So, once you got this QR code wing MFA application on your phone, you Scan thix code which trans fere the information into the MFA application.

* The entry in the application with a code which regenerats periodically.

* it never the Same, new code is generated every Single time the code refreshes.

* Different virtual devices are used for different accoud/servicey such as Aws, Gep, Azure 

* The MFA ix configured

* The next time you log into Acos as well as being required to enter the username and password for the specific user that you're using you will also be Promted to enter the MFA Code.

* showing for that one specific vistual MFA within your authentication application 

* it needs to be current code for correct virtual MFA on your specific authenticator application on your phone or other device.

* This means your identity inside Aws is seared using MFA.

