---
title: Et av de lokale Forbunds tjeneste sertifikatene utløper
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 172084b7-68a1-42a5-944d-2e871eaa2972
ms.openlocfilehash: a4c78f3fdbba7786785f31098c9e80e77a165623
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: nb-NO
ms.lasthandoff: 09/14/2020
ms.locfileid: "47673506"
---
# <a name="one-of-your-on-premises-federation-service-certificates-is-expiring"></a><span data-ttu-id="5899c-102">Et av de lokale Forbunds tjeneste sertifikatene utløper</span><span class="sxs-lookup"><span data-stu-id="5899c-102">One of your on-premises Federation Service Certificates is expiring</span></span>

<span data-ttu-id="5899c-103">Følg denne Fremgangs måten for å løse dette problemet:</span><span class="sxs-lookup"><span data-stu-id="5899c-103">To resolve this issue, follow these steps:</span></span>
  
- <span data-ttu-id="5899c-104">Installer Microsoft Azure Active Directory-modulen for Windows PowerShell på data maskinen (Hvis modulen ikke allerede er installert).</span><span class="sxs-lookup"><span data-stu-id="5899c-104">Install the Microsoft Azure Active Directory Module for Windows PowerShell on the computer (if the module isn't already installed).</span></span> <span data-ttu-id="5899c-105">Hvis du vil gjøre dette, går du til [Azure Active Directory PowerShell for Graph ](https://docs.microsoft.com/powershell/azure/active-directory/install-adv2?view=azureadps-2.0)</span><span class="sxs-lookup"><span data-stu-id="5899c-105">To do this, go to [Azure Active Directory PowerShell for Graph ](https://docs.microsoft.com/powershell/azure/active-directory/install-adv2?view=azureadps-2.0)</span></span>
    
- <span data-ttu-id="5899c-106">Følg Fremgangs måten i delen "scenario 1: signerings sertifikatet for AD FS token utløpt" i [«det oppstod et problem under tilgang til nettstedet» fra AD FS når en Forbunds bruker logger seg på Microsoft 365, Azure eller Intune](https://support.microsoft.com/help/2713898/there-was-a-problem-accessing-the-site-error-from-ad-fs-when-a-federat).</span><span class="sxs-lookup"><span data-stu-id="5899c-106">Follow the steps in the "Scenario 1: The AD FS token-signing certificate expired" section of ["There was a problem accessing the site" error from AD FS when a federated user signs in to Microsoft 365, Azure, or Intune](https://support.microsoft.com/help/2713898/there-was-a-problem-accessing-the-site-error-from-ad-fs-when-a-federat).</span></span>
    
- <span data-ttu-id="5899c-107">Følg trinnene i [hvordan du oppdaterer eller reparerer innstillingene for et organisasjons nettverk i Microsoft 365, Azure eller Intune](https://support.microsoft.com/help/2647048/how-to-update-or-repair-the-settings-of-a-federated-domain-in-office-3).</span><span class="sxs-lookup"><span data-stu-id="5899c-107">Follow the steps in [How to update or repair the settings of a federated domain in Microsoft 365, Azure, or Intune](https://support.microsoft.com/help/2647048/how-to-update-or-repair-the-settings-of-a-federated-domain-in-office-3).</span></span>
    
<span data-ttu-id="5899c-108">Hvis du vil ha mer informasjon om hvordan du fornyer forbundede sertifikater, kan du se [sertifikat fornyelse for O365 og Azure ad](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-o365-certs).</span><span class="sxs-lookup"><span data-stu-id="5899c-108">For more information about renewing Federation certificates, see [Certificate renewal for O365 and Azure AD](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-o365-certs).</span></span>
  

