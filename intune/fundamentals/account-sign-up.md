---
# required metadata

title: Sign up or sign in to Microsoft Intune
description: How to sign up for an Microsoft Intune subscription or sign in to start with your subscription.
keywords:
author: ErikjeMS
ms.author: erikje
manager: dougeby
ms.date: 01/02/2018
ms.topic: conceptual
ms.service: microsoft-intune
ms.subservice: fundamentals
ms.localizationpriority: high
ms.technology:
ms.assetid: 0f3ce07a-b718-42a9-bace-f99a8b8abd94

# optional metadata

#ROBOTS:
#audience:
#ms.devlang:
ms.reviewer: angerobe
ms.suite: ems
search.appverid: MET150
#ms.tgt_pltfrm:
ms.custom: intune-classic
ms.collection: M365-identity-device-management
---


# Sign up or sign in to Microsoft Intune

[!INCLUDE [both-portals](../../intune-classic/includes/note-for-both-portals.md)]

This topic tells system administrators how you can sign up for an Intune account.

Before you sign up for Intune, determine whether you already have a Microsoft Online Services account, Enterprise Agreement, or equivalent volume licensing agreement. A Microsoft volume licensing agreement or other Microsoft cloud services subscription like Office 365 usually includes a work or school account.

If you already have a work or school account, **sign in** with that account and add Intune to your subscription. Otherwise, you can **sign up** for a new account to use Intune for your organization.

>[!WARNING]
>You can't combine an existing work or school account after you sign up for a new account.

## How to sign up for Intune

1. Visit the [Intune Sign-up page](https://admin.microsoft.com/Signup/Signup.aspx?OfferId=40BE278A-DFD1-470a-9EF7-9F2596EA7FF9&dl=INTUNE_A&ali=1#0%20).

   ![Screenshot of the Microsoft Intune Trial account signup web page](./media/account-sign-up/account-sign-up-site.png)

2. On the Sign-up page, sign in or sign up to manage a new subscription of Intune.

## Post sign up considerations
After you sign up for a new subscription, you receive an email message that contains your account information at the email address that you provided during the sign-up process. This email confirms your subscription is active.

After completing the sign-up process you are directed to the Microsoft 365 admin center, used to add users and assign them licenses. If you only have cloud-based accounts using your default onmicrosoft.com domain name, then you can go ahead and add users and assign licenses at this point. However, if you plan to use your organization's [custom domain name](custom-domain-name-configure.md) or [synchronize user account information](users-add.md#sync-active-directory-and-add-users-to-intune) from on-premises Active Directory, then you can close that browser window.

## Sign in to Microsoft Intune
Once you have signed up for Intune, you can use any device with a [supported browser](supported-devices-browsers.md#intune-supported-web-browsers) to sign in to [Intune](https://go.microsoft.com/fwlink/?linkid=2090973) to administer the service.

By default, your account must have one of the following permissions in Azure AD:
- Global Administrator
- Intune Service Administrator (also known as Intune Administrator)

To grant access to administer the service for users with other permissions, then See [Role Based Access Control](role-based-access-control.md)

### Intune Admin portal URL

Microsoft 365 Admin Center: https://devicemanagement.microsoft.com

Intune Azure portal: https://portal.azure.com/#blade/Microsoft_Intune_DeviceSettings/ExtensionLandingBlade

Intune for Education: https://intuneeducation.portal.azure.com

Intune classic portal: https://manage.microsoft.com
The Intune classic portal is only used for managing devices enrolled with the Intune PC software client

### URLs for Intune services provided by Office 365

Microsoft 365 Business: https://portal.microsoft.com/adminportal

Office 365 Mobile Device Management: https://portal.office.com/adminportal/home#/MifoDevices

## See also
[You can't sign in to Office 365, Azure, or Intune](https://support.microsoft.com/help/2412085)
