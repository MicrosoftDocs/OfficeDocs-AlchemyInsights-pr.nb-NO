---
title: En bruker får ingen tilgang når du legger til tillegg i Outlook
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 07/23/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "5892"
- "6700008"
ms.openlocfilehash: 355f37386e0a498185e195c1d715386785d0b54b
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: nb-NO
ms.lasthandoff: 09/14/2020
ms.locfileid: "47673290"
---
# <a name="one-user-gets-access-denied-error-while-adding-add-ins-in-outlook"></a>En bruker får ingen tilgang når du legger til tillegg i Outlook

Bruker PowerShell for å finne tillatelser:

Get-ManagementRoleAssignment-RoleAssignee [User@domain.com](mailto:user@domain.com "mailto:user@domain.com") -delegering $false | Format-table-automatisk rolle, RoleAssigneeName, RoleAssigneeType