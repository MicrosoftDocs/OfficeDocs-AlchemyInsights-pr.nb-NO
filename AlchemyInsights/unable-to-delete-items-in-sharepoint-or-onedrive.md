---
title: Kan ikke slette elementer i SharePoint eller OneDrive
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1851"
- "2377"
- "9000255"
ms.assetid: ''
ms.openlocfilehash: fd12115214cc28b822cf7fa57fe9b86f76f7beb1
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: nb-NO
ms.lasthandoff: 09/15/2020
ms.locfileid: "47806120"
---
# <a name="unable-to-delete-items"></a><span data-ttu-id="918ab-102">Kan ikke slette elementer</span><span class="sxs-lookup"><span data-stu-id="918ab-102">Unable to delete items</span></span>

<span data-ttu-id="918ab-103">Oppbevarings policyer kan føre til dette, enten må du deaktivere eller utelukke den respektive sperringen som for år saker Dette problemet.</span><span class="sxs-lookup"><span data-stu-id="918ab-103">Retention policies can cause this, you need to either disable or exclude respective hold that's causing this issue.</span></span> <span data-ttu-id="918ab-104">Etter en oppbevarings policy eller sperring er fjernet, kan det ta opptil 24 timer før endringen trer i kraft.</span><span class="sxs-lookup"><span data-stu-id="918ab-104">After a retention policy or hold is removed, it may take up to 24 hours for the change to take effect.</span></span> <span data-ttu-id="918ab-105">Kontroller at det ikke finnes et oppsett for [oppbevarings policy](https://docs.microsoft.com/microsoft-365/compliance/retention-policies) for elementet.</span><span class="sxs-lookup"><span data-stu-id="918ab-105">Ensure that there is not a [retention policy](https://docs.microsoft.com/microsoft-365/compliance/retention-policies) setup on the item.</span></span>

<span data-ttu-id="918ab-106">Nettstedet kan ha overskredet lagrings grensen, øke [område kvoten](https://docs.microsoft.com/powershell/module/sharepoint-online/set-sposite?view=sharepoint-ps) og slette elementet.</span><span class="sxs-lookup"><span data-stu-id="918ab-106">The site might have exceeded storage limit, increase the [site quota](https://docs.microsoft.com/powershell/module/sharepoint-online/set-sposite?view=sharepoint-ps) and delete the item.</span></span>

<span data-ttu-id="918ab-107">Kontroller at elementet ikke er [sjekket ut](https://support.office.com/article/check-out-check-in-or-discard-changes-to-files-in-a-library-7e2c12a9-a874-4393-9511-1378a700f6de) til en annen bruker.</span><span class="sxs-lookup"><span data-stu-id="918ab-107">Ensure the item is not [checked out](https://support.office.com/article/check-out-check-in-or-discard-changes-to-files-in-a-library-7e2c12a9-a874-4393-9511-1378a700f6de) to another user.</span></span>

<span data-ttu-id="918ab-108">Til slutt kan administratorer bruke [SharePoint-mønstre og-rutiner](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps#installation) (PnP) som inneholder et bibliotek med PowerShell-kommandoer som gjør at du kan utføre komplekse administrasjons handlinger, for eksempel tvinge sletting av stubborn-elementer.</span><span class="sxs-lookup"><span data-stu-id="918ab-108">Finally, administrators can use [SharePoint Patterns and Practices](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps#installation) (PnP) which contains a library of PowerShell commands that allow you to perform complex management actions such as force deleting stubborn items.</span></span>
- [<span data-ttu-id="918ab-109">Fjern PNP-fil</span><span class="sxs-lookup"><span data-stu-id="918ab-109">Remove PNP File</span></span>](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfile?view=sharepoint-ps)
- [<span data-ttu-id="918ab-110">Fjern PNP-mappe</span><span class="sxs-lookup"><span data-stu-id="918ab-110">Remove PNP Folder</span></span>](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfolder?view=sharepoint-ps)
- [<span data-ttu-id="918ab-111">Fjern liste element for PNP</span><span class="sxs-lookup"><span data-stu-id="918ab-111">Remove PNP List Item</span></span>](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnplistitem?view=sharepoint-ps)
- [<span data-ttu-id="918ab-112">Fjern PNP-liste</span><span class="sxs-lookup"><span data-stu-id="918ab-112">Remove PNP List</span></span>](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnplist?view=sharepoint-ps)
- [<span data-ttu-id="918ab-113">Fjern PNP-felt (kolonne)</span><span class="sxs-lookup"><span data-stu-id="918ab-113">Remove PNP Field (Column)</span></span>](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfield?view=sharepoint-ps)