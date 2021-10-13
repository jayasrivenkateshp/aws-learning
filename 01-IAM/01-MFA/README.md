# Multi Factor authentication

**MFA is implemented within AWS**

## Why MFA is needed ?

 * The way that you usually log in to any web-based applications, Generally you use usernames and passwords.
 * If both of this is leaked any one can be you, anyone can take your username and password and use them to log into an application and impersonate as you as an identity

## Multi-factor Authentication

→ It is when you use Multiple factors or multiple types of factory to log in to an application.

### Factor (or) factors

 * Factors are pieces of evidnce which prove identity, and there are identified types of factors
 * so, when you hear the term **Single Factor Authentication**. It means one of these factors

  There are four common factors that you use to Log in to **any web Application** 
 
    Knowledge:- The knowledge factor Includes username and passwords 

    possession :- This in Something that you have bank card, MFA device or an MFA application

    Inherent :- so this is Something you have, so a So a fingerprint, or an is gean face scan's 
                voice identification

    Location: This can be either physical location, 
               - that you currently Logged into accen a system either Logged into
               (corporate network) or home wifi network.

* By default you Log into this with a username and password
* This is **single factor or one factor authentication**

## We can improve this using MFA:

  **MFA can be activated using virtual MFA**

* which is added to an MFA application such as **google authenticator Virtual MFA Sevice** 

* open IAM console and add click on MFA in your account

* Click on assign MFA device

* And then click on virtual MFA device

* we need to download Google authenticator in our mobile phone 

* then scan the QR code present  in the AWS console

* finally MFA is attached to your AWS Account

* After this whenever you are going to login to your console (username and password) it also aks MFA code

* now , your account is secured with MFA 

