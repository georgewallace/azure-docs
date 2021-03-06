---
title: Azure AD Connect and Federation | Microsoft Docs
description: This page is the central location for all documentation regarding AD FS operations using Azure AD Connect
services: active-directory
documentationcenter: ''
author: anandyadavmsft
manager: femila
editor: ''

ms.assetid: f9107cf5-0131-499a-9edf-616bf3afef4d
ms.service: active-directory
ms.workload: identity
ms.tgt_pltfrm: na
ms.devlang: na
ms.topic: article
ms.date: 10/31/2016
ms.author: anandy

---
# Azure AD Connect and federation
Azure AD Connect lets you configure federation with the on-premises AD FS and Azure AD. With federation sign on, you can enable users to sign on to Azure AD based services with their on-premises passwords and, while on the corporate network, without having to enter their passwords again. The federation option with AD FS allows you to deploy a new or specify an existing AD FS in Windows Server 2012 R2 farm.

This topic is the home for information on Federation related functionalities for Azure AD Connect and lists links to all other topics related to it. For links to Azure AD Connect, see Integrating your on-premises identities with Azure Active Directory.

## Azure AD Connect - federation topics
| Topic | What it covers and when to read |
|:--- |:--- |
| **Azure AD Connect user sign-in options** | |
| [Understanding User sign-in options](active-directory-aadconnect-user-signin.md) |Description of various user sign-in options and how they affect Azure sign-in user experience |
| **AD FS installation using Azure AD Connect** | |
| [Pre-requisites](active-directory-aadconnect-get-started-custom.md#ad-fs-configuration-pre-requisites) |Pre-requisites for a successful AD FS installation via Azure AD Connect |
| [Configure AD FS farm](active-directory-aadconnect-get-started-custom.md#configuring-federation-with-ad-fs) |How to install a new AD FS farm using Azure AD Connect |
| **Modifying the AD FS configuration** | |
| [Repairing the trust](active-directory-aadconnect-federation-management.md#repairthetrust) |How to repair current trust between on-premises AD FS and Office 365 / Azure |
| [Adding a new AD FS server](active-directory-aadconnect-federation-management.md#addadfsserver) |Expanding AD FS farm with additional AD FS server post initial installation |
| [Adding a new AD FS WAP server](active-directory-aadconnect-federation-management.md#addwapserver) |Expanding AD FS farm with additional WAP server post initial installation |
| [Add a new federated domain](active-directory-aadconnect-federation-management.md#addfeddomain) |Add another domain to be federated with Azure AD |
| **Post installation tasks** | |
| [Add custom company logo / illustration](active-directory-aadconnect-federation-management.md#customlogo) |Modify the sign-in experience by specifying the custom logo that will be shown on the AD FS sign-in page |
| [Add sign-in description](active-directory-aadconnect-federation-management.md#addsignindescription) |Changing sign-in description on the AD FS sign-in page |
| [Modifying AD FS claim rules](active-directory-aadconnect-federation-management.md#modclaims) |Modify / add claim rules in AD FS corresponding to Azure AD Connect sync configuration |

## Additional resources
* [Integrating your on-premises identities with Azure Active Directory](active-directory-aadconnect.md)
* [AD FS deployment in Azure](active-directory-aadconnect-
* azure-adfs.md)
* [High availability cross-geographic AD FS deployment in Azure with Azure Traffic Manager](../active-directory-adfs-in-azure-with-azure-traffic-manager.md)

