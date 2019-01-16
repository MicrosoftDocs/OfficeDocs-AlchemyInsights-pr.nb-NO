---
title: Manglende arbeidsflyten kan ikke aktivere
ms.author: kirks
author: Techwriter40
ms.date: 12/3/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: e46ae8c5-3d81-457e-8c77-f7c1cbe267c4
ms.openlocfilehash: 33b92c2cae1f641b0cd88c82fd4ae5e8632d76c2
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: nb-NO
ms.lasthandoff: 01/15/2019
ms.locfileid: "28303615"
---
# <a name="missing-workflow-failed-to-activate"></a><span data-ttu-id="1b5b4-102">Manglende arbeidsflyten kan ikke aktivere</span><span class="sxs-lookup"><span data-stu-id="1b5b4-102">Missing Workflow Failed to Activate</span></span>

<span data-ttu-id="1b5b4-103">Du kan legge et globalt gjenbrukbar arbeidsflyt (for eksempel "godkjenning - SharePoint 2010") til lister eller biblioteker i en områdesamling for Microsoft SharePoint.</span><span class="sxs-lookup"><span data-stu-id="1b5b4-103">In a Microsoft SharePoint site collection, you can't add a globally reusable workflow (such as "Approval - SharePoint 2010") to a list or library.</span></span>
  
<span data-ttu-id="1b5b4-104">Hvis du vil løse dette problemet, gjør du følgende:</span><span class="sxs-lookup"><span data-stu-id="1b5b4-104">To resolve this issue, follow these steps:</span></span> 
  
1. <span data-ttu-id="1b5b4-105">Åpne webområdet til roten av områdesamlingen i SharePoint Designer 2013.</span><span class="sxs-lookup"><span data-stu-id="1b5b4-105">Open the root website of the site collection in SharePoint Designer 2013.</span></span>
  
2. <span data-ttu-id="1b5b4-106">Under **Områdeobjekter**, velger du **arbeidsflyter**.</span><span class="sxs-lookup"><span data-stu-id="1b5b4-106">Under **Site Objects**, select **Workflows**.</span></span> 
  
3. <span data-ttu-id="1b5b4-107">Velg **Gjenbrukbare arbeidsflyt**i **Ny** -delen av båndet **arbeidsflyter** .</span><span class="sxs-lookup"><span data-stu-id="1b5b4-107">In the **New** section of the **Workflows** ribbon, select **Reusable Workflow**.</span></span> 
  
4. <span data-ttu-id="1b5b4-p101">Angi navnet på skjemaet **Opprett gjenbrukbare arbeidsflyten** \*\* *Repair2010* \*\*. Klikk **SharePoint 2010 arbeidsflyt**for **Plattformen**, og klikk deretter **OK**.</span><span class="sxs-lookup"><span data-stu-id="1b5b4-p101">On the **Create Reusable Workflow** form, enter the name \*\* *Repair2010* \*\*. For **Platform Type**, click **SharePoint 2010 Workflow**, and then click **OK**.</span></span> 
  
1. <span data-ttu-id="1b5b4-110">Velg **Publiser**i delen **Lagre** **arbeidsflyt** -båndet.</span><span class="sxs-lookup"><span data-stu-id="1b5b4-110">In the **Save** section of the **Workflow** ribbon, select **Publish**.</span></span> 
  
2. <span data-ttu-id="1b5b4-p102">Velg **Publiser globalt**i delen **Behandle** **arbeidsflyt** -båndet. I bekreftelsesdialogboksen som vises, velger du **OK**.</span><span class="sxs-lookup"><span data-stu-id="1b5b4-p102">In the **Manage** section of the **Workflow** ribbon, select **Publish Globally**. In the confirmation dialog box that appears, select **OK**.</span></span> 
  
3. <span data-ttu-id="1b5b4-p103">Finne webområdet til roten av områdesamlingen i en webleser, og deretter bruker du **Områdeinnstillinger** \> **Funksjoner i områdesamling**. Deretter Aktiver/deaktiver funksjonen **arbeidsflyter** :</span><span class="sxs-lookup"><span data-stu-id="1b5b4-p103">In a web browser, locate the root website of the site collection, and then access **Site Settings** \> **Site Collection Features**. Then, toggle the **Workflows** feature:</span></span> 
  
<span data-ttu-id="1b5b4-115">· Hvis funksjonen er *aktivert* , klikker du **Deaktiver,** og klikk deretter **Aktiver**.</span><span class="sxs-lookup"><span data-stu-id="1b5b4-115">· If the feature is  *Activated*  , click **Deactivate,** and then click **Activate**.</span></span> 
  
<span data-ttu-id="1b5b4-116">· Hvis funksjonen er *deaktivert* , klikker du **Aktiver**.</span><span class="sxs-lookup"><span data-stu-id="1b5b4-116">· If the feature is  *Deactivated*  , click **Activate**.</span></span> 
  
<span data-ttu-id="1b5b4-117">For mer informasjon kan du se følgende [artikkel](https://go.microsoft.com/fwlink/?linkid=2047770&amp;clcid=0x409).</span><span class="sxs-lookup"><span data-stu-id="1b5b4-117">For more information please refer to the following [article](https://go.microsoft.com/fwlink/?linkid=2047770&amp;clcid=0x409).</span></span>
  

