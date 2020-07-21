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
# <a name="single-user-not-seeing-add-ins-in-outlook"></a>Enkeltbrukere ser ikke tillegg i Outlook

Brukeren kan være en del av en rolle som ikke har den riktige AppsForOfficeEnabled-parameteren. Kjør denne cmdleten for å finne ut om den riktige rollen er knyttet til brukeren:

Get-ManagementRoleAssignment -RoleAssignee user@domain.com -Delegering $false | Format-Tabell -Auto Rolle,RoleAssigneeName,RoleAssigneeType

Hvis du vil ha mer informasjon, kan du se [Angi administratorer og brukere som kan installere og administrere tillegg for Outlook](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/add-ins-for-outlook/specify-who-can-install-and-manage-add-ins).
