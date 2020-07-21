---
title: Enkeltbrukere ser ikke tillegg i Outlook
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 07/16/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: ''
ms.openlocfilehash: 1f547c3f593b3256bd44f518aacbc36ed1c4c848
ms.sourcegitcommit: a05276bd623466ad211e1f8d9f0c616672dd3640
ms.translationtype: MT
ms.contentlocale: nb-NO
ms.lasthandoff: 07/16/2020
ms.locfileid: "45197965"
---
# <a name="single-user-not-seeing-add-ins-in-outlook"></a><span data-ttu-id="c17f0-102">Enkeltbrukere ser ikke tillegg i Outlook</span><span class="sxs-lookup"><span data-stu-id="c17f0-102">Single user not seeing add-ins in Outlook</span></span>

<span data-ttu-id="c17f0-103">Brukeren kan være en del av en rolle som ikke har den riktige AppsForOfficeEnabled-parameteren.</span><span class="sxs-lookup"><span data-stu-id="c17f0-103">The user might be part of a role that doesn’t have the correct AppsForOfficeEnabled parameter.</span></span> <span data-ttu-id="c17f0-104">Kjør denne cmdleten for å finne ut om den riktige rollen er knyttet til brukeren:</span><span class="sxs-lookup"><span data-stu-id="c17f0-104">Run this cmdlet to find out if the correct role is associated with the user:</span></span>

<span data-ttu-id="c17f0-105">Get-ManagementRoleAssignment -RoleAssignee user@domain.com -Delegering $false | Format-Tabell -Auto Rolle,RoleAssigneeName,RoleAssigneeType</span><span class="sxs-lookup"><span data-stu-id="c17f0-105">Get-ManagementRoleAssignment -RoleAssignee user@domain.com -Delegating $false | Format-Table -Auto Role,RoleAssigneeName,RoleAssigneeType</span></span>

<span data-ttu-id="c17f0-106">Hvis du vil ha mer informasjon, kan du se [Angi administratorer og brukere som kan installere og administrere tillegg for Outlook](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/add-ins-for-outlook/specify-who-can-install-and-manage-add-ins).</span><span class="sxs-lookup"><span data-stu-id="c17f0-106">For more info, see [Specify the administrators and users who can install and manage add-ins for Outlook](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/add-ins-for-outlook/specify-who-can-install-and-manage-add-ins).</span></span>
