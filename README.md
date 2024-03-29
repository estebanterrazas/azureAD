# Azure Active Directory 
---

Azure AD is at the core of Azure and Microsoft 365, as it is the repository for user identities, device identities, and groups. Azure AD also has the ability to allow us to configure enterprise applications, manage security and authentication, and numerous other technologies and services. 

This is a list of the topics covered in Azure Active Directory:

- [Understanding Azure AD](https://github.com/estebanterrazas/azureAD#understanding-azure-ad)

- Azure AD Tenants and Custom Domain Names

- Azure AD Licensing

- Creating and Managing Azure AD Users

- Creating and Managing Azure AD Groups

- Managing Users and Groups using PowerShell

- Managing Users and Groups using Cloud Shell

- Self-Service Password Reset

- [How do I connect devices to Azure AD] (https://github.com/estebanterrazas/azureAD#how-do-i-connect-devices-to-azure-ad)

- Azure AD Registered Devices

- Azure AD Joined Devices

- Azure AD Hybrid Devices

- Roles for Azure AD

- Administrative Units

- Authentication Methods

- Azure Multi-Factor Authentication (MFA)

- Authenticator App

- Security Defaults

- Privileged Identity Management (PIM)

- Azure Identity Protection Risk

- User Risk Policy

- Sign-in Risk Policy

- Conditional Access

- Access Reviews

- Azure AD Design and Planning

- Break-Glass Accounts

- Auditing

- Identity Secure Score

- Enterprise Applications

- Enterprise Applications using Single Sign-On (SSO)

- Entitlement Management

- Catalogs

- Access Packages

- Understanding the types of Active Directory Services

- Azure AD Domain Services

- Azure AD versus Active Directory Domain Services

- Azure AD Connect

- Authentication Options

- Password Hash Sync (PHS)

- Pass-Through Authentication (PTA)

- Password Writeback

- Azure AD Cloud Sync

- Integration with Microsoft 365

- Planning and Design Review


---
## Understanding Azure AD
---
Azure AD is a cloud-based identity and access management service, helps with sign in and access multiple vendor resources and apps, included Azure and Microsoft 365.

If you have on premise environment and a domain in your on premise environment you can let your users automatically synchronize out to Azure Active Directory.

---
## How do I connect devices to Azure AD
First you need to set a policy for digital signatures
In PowerShell
```
Set-ExecutionPolicy RemoteSigned
```

In your local machine you need to install Azure and AzureAD modules
In PowerShell:
```
Install-Module Az
Install-Module AzureAD
Connect-AzAccount
```
Now connect to your Azure Account
```
Connect-AzAccount
```
---