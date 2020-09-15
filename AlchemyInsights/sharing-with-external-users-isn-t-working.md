---
title: Deling med eksterne brukere fungerer ikke
ms.author: mikeplum
author: MikePlumleyMSFT
manager: scotv
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: d3d0b69b-214e-4859-8957-621fd6306b30
ms.openlocfilehash: bd3a6c0d7206801ff76be121c4878b8343cc9886
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: nb-NO
ms.lasthandoff: 09/14/2020
ms.locfileid: "47691584"
---
# <a name="fix-problems-sharing-sharepoint-content-with-external-users"></a><span data-ttu-id="21053-102">Løse problemer med å dele SharePoint-innhold med eksterne brukere</span><span class="sxs-lookup"><span data-stu-id="21053-102">Fix problems sharing SharePoint content with external users</span></span>

<span data-ttu-id="21053-103">Kontroller at ekstern deling er aktivert for organisasjonen din:</span><span class="sxs-lookup"><span data-stu-id="21053-103">Make sure external sharing is turned on for your organization:</span></span>
  
1. <span data-ttu-id="21053-104">Gå til [siden tjenester &amp; -tillegg i administrasjons senteret for Microsoft 365](https://portal.office.com/adminportal/home#/Settings/ServicesAndAddIns), og klikk **områder**.</span><span class="sxs-lookup"><span data-stu-id="21053-104">Go to the [Services &amp; add-ins page in the Microsoft 365 admin center](https://portal.office.com/adminportal/home#/Settings/ServicesAndAddIns), and click **Sites**.</span></span>
    
2. <span data-ttu-id="21053-105">Kontroller at innstillingen er slått på.</span><span class="sxs-lookup"><span data-stu-id="21053-105">Make sure the setting is turned to "On."</span></span> <span data-ttu-id="21053-106">Hvis det er merket av for bare eksisterende eksterne brukere, må du kontrollere at den eksterne brukeren er oppført i administrasjons senteret for Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="21053-106">If "Only existing external users" is selected, make sure the external user is listed in the Microsoft 365 admin center.</span></span>
    
<span data-ttu-id="21053-107">Kontroller at ekstern deling den er slått på for området.</span><span class="sxs-lookup"><span data-stu-id="21053-107">Make sure external sharing it turned on for the site.</span></span> <span data-ttu-id="21053-108">For en klassisk område samling:</span><span class="sxs-lookup"><span data-stu-id="21053-108">For a classic site collection:</span></span>
  
1. <span data-ttu-id="21053-109">Klikk **områder**i den venstre ruten i det nye administrasjons senteret for SharePoint.</span><span class="sxs-lookup"><span data-stu-id="21053-109">In the new SharePoint admin center, in the left pane, click **sites**.</span></span>
    
2. <span data-ttu-id="21053-110">Velg nettstedet eller nett stedene, og klikk **deling**på båndet.</span><span class="sxs-lookup"><span data-stu-id="21053-110">Select the site or sites, and on the ribbon, click **Sharing**.</span></span>
    
<span data-ttu-id="21053-111">For et gruppe nettsted som tilhører en Microsoft 365-gruppe eller et kommunikasjons område:</span><span class="sxs-lookup"><span data-stu-id="21053-111">For a team site that belongs to a Microsoft 365 group, or a communication site:</span></span>
  
- <span data-ttu-id="21053-112">Disse nye område typene har samme Delings innstilling som hele organisasjonen, med mindre innstillingen for hele organisasjonen tillater deling av filer ved hjelp av koblinger som ikke krever pålogging.</span><span class="sxs-lookup"><span data-stu-id="21053-112">These new site types have the same sharing setting as your organization-wide setting, unless the organization-wide setting allows sharing files using links that don't require sign-in.</span></span> <span data-ttu-id="21053-113">I dette tilfellet tillater områdene deling med nye og eksisterende eksterne brukere som logger seg på.</span><span class="sxs-lookup"><span data-stu-id="21053-113">In this case, the sites allow sharing with new and existing external users who sign in.</span></span> <span data-ttu-id="21053-114">Hvis du vil endre innstillingen for bestemte nett steder, bruker du det nye administrasjons senteret for SharePoint eller PowerShell.</span><span class="sxs-lookup"><span data-stu-id="21053-114">To change the setting for specific sites, use the new SharePoint admin center or PowerShell.</span></span> <span data-ttu-id="21053-115">[Finn ut mer](https://go.microsoft.com/fwlink/?linkid=871863).</span><span class="sxs-lookup"><span data-stu-id="21053-115">[Learn more](https://go.microsoft.com/fwlink/?linkid=871863).</span></span>
    
> [!NOTE]
> <span data-ttu-id="21053-116">Innstillingen for ekstern deling for et nettsted kan være mer begrenset enn organisasjonens omfattende innstilling, men ikke mer tolerant enn innstillingen for hele organisasjonen.</span><span class="sxs-lookup"><span data-stu-id="21053-116">The external sharing setting for any site can be more restrictive than your organization-wide setting, but not more permissive than the organization-wide setting.</span></span> 
  

