---
title: Arbeidsflyten starter ikke
ms.author: efrene
author: efrene
manager: pamgreen
ms.date: 8/2/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000144"
- "1670"
ms.openlocfilehash: 2d85dcf9111d48cb529c583c733823b404eb3188
ms.sourcegitcommit: a256e8680379c006287ae30996763051c4d9ff85
ms.translationtype: MT
ms.contentlocale: nb-NO
ms.lasthandoff: 09/04/2019
ms.locfileid: "36738098"
---
# <a name="workflow-is-not-starting"></a><span data-ttu-id="3dafe-102">Arbeidsflyten starter ikke</span><span class="sxs-lookup"><span data-stu-id="3dafe-102">Workflow is not starting</span></span>

- <span data-ttu-id="3dafe-103">SharePoint 2010-og SharePoint 2013-arbeidsflyter starter ikke.</span><span class="sxs-lookup"><span data-stu-id="3dafe-103">SharePoint 2010 and SharePoint 2013 workflows are not starting.</span></span>

    - <span data-ttu-id="3dafe-104">Hvis arbeidsflyten ikke starter, kan det være et midlertidig problem med tjenesten der brukere kan oppleve uregelmessige forsinkelser med fremdrift for arbeidsflyten.</span><span class="sxs-lookup"><span data-stu-id="3dafe-104">If your workflow is not starting, there may be a temporary service issue where users may experience intermittent delays with workflow progress.</span></span> <span data-ttu-id="3dafe-105">Kontroller [helse instrumentbordet for tjenesten](https:/admin.microsoft.com/AdminPortal/Home#/servicehealth) for å se om organisasjonen er berørt.</span><span class="sxs-lookup"><span data-stu-id="3dafe-105">Check the [Service Health Dashboard](https:/admin.microsoft.com/AdminPortal/Home#/servicehealth) to see if your organization is impacted.</span></span>

    - <span data-ttu-id="3dafe-106">Hvis det har gått mer enn 24 timer siden du først så dette problemet, kan du logge en support billett.</span><span class="sxs-lookup"><span data-stu-id="3dafe-106">If more than 24 hours have passed since you first saw this issue, please log a support ticket.</span></span> <span data-ttu-id="3dafe-107">I mange tilfeller er vi allerede jobber med en løsning.</span><span class="sxs-lookup"><span data-stu-id="3dafe-107">In many cases, we're already working on a solution.</span></span> <span data-ttu-id="3dafe-108">Vennligst gi oss minst 24 timer for å fullføre en løsning.</span><span class="sxs-lookup"><span data-stu-id="3dafe-108">Please give us at least 24 hours to complete a solution.</span></span>

- <span data-ttu-id="3dafe-109">Arbeidsflyter for SharePoint 2010 forsinket ved oppstart.</span><span class="sxs-lookup"><span data-stu-id="3dafe-109">SharePoint 2010 workflows delayed on start.</span></span>

    - <span data-ttu-id="3dafe-110">Dette skjer hvis arbeidsflyten utløses i store partier.</span><span class="sxs-lookup"><span data-stu-id="3dafe-110">This occurs if the workflow is triggered in large batches.</span></span> <span data-ttu-id="3dafe-111">(for eksempel når flere elementer er lagt til samtidig).</span><span class="sxs-lookup"><span data-stu-id="3dafe-111">(for example, when several items are added at once).</span></span>

    - <span data-ttu-id="3dafe-112">Arbeidsflyter er ikke laget for å kjøre i sanntid, slik at en forsinkelse er etter utformings virkemåte.</span><span class="sxs-lookup"><span data-stu-id="3dafe-112">Workflows are not designed to run real-time, so a delay is by-design behavior.</span></span>

   -  <span data-ttu-id="3dafe-113">Hvis arbeidsflyten er kompleks Extensible Object Markup Language (XMOL), kan kompilering være treg.</span><span class="sxs-lookup"><span data-stu-id="3dafe-113">If the Workflow is complex Extensible Object Markup Language (XMOL), compilation can be slow.</span></span> <span data-ttu-id="3dafe-114">Sjekk [denne](https://support.microsoft.com//kb/3043697) artikkelen.</span><span class="sxs-lookup"><span data-stu-id="3dafe-114">Check [this](https://support.microsoft.com//kb/3043697) article.</span></span>

    - <span data-ttu-id="3dafe-115">Du bør forenkle arbeidsflyten eller utforme den på ny ved hjelp av typen Microsoft SharePoint 2013 arbeidsflyt plattform.</span><span class="sxs-lookup"><span data-stu-id="3dafe-115">You should simplify the workflow or redesign it using the Microsoft SharePoint 2013 Workflow platform type.</span></span>

    - <span data-ttu-id="3dafe-116">Hvis arbeidsflytloggen er blitt stor, kan det hende du vil tømme elementene eller opprette en ny loggliste.</span><span class="sxs-lookup"><span data-stu-id="3dafe-116">If your workflow history has grown large, you may want to purge the items or create a new history list.</span></span>

        <span data-ttu-id="3dafe-117">Mer informasjon: [tømme Arbeidsflytlogg](https://blogs.technet.microsoft.com/marj/2015/08/07/sharepoint-2010-workflows-best-practice-purge-workflow-history-list-items/)</span><span class="sxs-lookup"><span data-stu-id="3dafe-117">More Information : [Purge Workflow History](https://blogs.technet.microsoft.com/marj/2015/08/07/sharepoint-2010-workflows-best-practice-purge-workflow-history-list-items/)</span></span>


## <a name="related-topics"></a><span data-ttu-id="3dafe-118">Beslektede emner</span><span class="sxs-lookup"><span data-stu-id="3dafe-118">Related topics</span></span>
<span data-ttu-id="3dafe-119">Vil du prøve Microsoft Flow i SharePoint Online?</span><span class="sxs-lookup"><span data-stu-id="3dafe-119">Want to try Microsoft Flow in SharePoint Online?</span></span>
- [<span data-ttu-id="3dafe-120">Opprett flyt</span><span class="sxs-lookup"><span data-stu-id="3dafe-120">Create Flow</span></span>](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [<span data-ttu-id="3dafe-121">SharePoint og Flow</span><span class="sxs-lookup"><span data-stu-id="3dafe-121">SharePoint and Flow</span></span>](https://flow.microsoft.com/blog/sharepoint-and-flow/) 


