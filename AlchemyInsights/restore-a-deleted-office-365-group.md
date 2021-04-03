---
title: Gjenopprette en slettet Microsoft 365-gruppe
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "98"
- "1200024"
ms.assetid: bc0396ea-c426-4d1d-bb89-ced602d06fb6
ms.openlocfilehash: 6f640093cd099f20d3a95eede5c141ad74838b0b
ms.sourcegitcommit: 7b2e5078dd65f11af6650e692a7ea48e91f544e0
ms.translationtype: MT
ms.contentlocale: nb-NO
ms.lasthandoff: 04/02/2021
ms.locfileid: "51505695"
---
# <a name="restore-a-deleted-microsoft-365-group"></a><span data-ttu-id="775af-102">Gjenopprette en slettet Microsoft 365-gruppe</span><span class="sxs-lookup"><span data-stu-id="775af-102">Restore a deleted Microsoft 365 group</span></span>

<span data-ttu-id="775af-103">Du kan gjenopprette en slettet Microsoft 365-gruppe eller Microsoft Teams innen 30 dager etter slettingen.</span><span class="sxs-lookup"><span data-stu-id="775af-103">You can restore a deleted Microsoft 365 group or Microsoft Teams within 30 days from the deletion.</span></span>

1. <span data-ttu-id="775af-104">Hvis du vil logge på administrasjonssenteret for Microsoft 365 og vise slettede grupper og team, går du til [administrasjonssenteret for Microsoft 365](https://aka.ms/RestoreDeletedGroup).</span><span class="sxs-lookup"><span data-stu-id="775af-104">To login to Microsoft 365 admin center and list the deleted groups and teams, go to the [Microsoft 365 admin center](https://aka.ms/RestoreDeletedGroup).</span></span>

    <span data-ttu-id="775af-105">**Obs!** Logg på med kontoen som er tilordnet til enten leieradministratoren eller administratorrollen for gruppene.</span><span class="sxs-lookup"><span data-stu-id="775af-105">**Note:** Log in using the account that is assigned to either the tenant administrator or the groups admin role.</span></span>

1. <span data-ttu-id="775af-106">Velg den slettede Microsoft 365-gruppen/Teams som skal gjenopprettes, og klikk **gjenopprett gruppe.**</span><span class="sxs-lookup"><span data-stu-id="775af-106">Select the deleted Microsoft 365 group/Teams to be restored and click **restore group**.</span></span>

    <span data-ttu-id="775af-107">Hvis gruppen ikke kan gjenopprettes på grunn av en motstridende SMTP-adresse, bruker du følgende kommando til å finne objektet som forårsaker konflikt, og fjerne SMTP-adressen:</span><span class="sxs-lookup"><span data-stu-id="775af-107">If the group can't be restored because of a conflicting SMTP address, use following command to find the object that’s causing conflict and remove the SMTP address:</span></span>

    `Get-Recipient -Filter "EmailAddresses -eq '<conflictingsmtpaddress>'"`

    <span data-ttu-id="775af-108">**Obs!** I noen tilfeller kan det ta så lang tid som 24 timer før gruppen og alle dataene gjenopprettes.</span><span class="sxs-lookup"><span data-stu-id="775af-108">**Note:** In some cases, it might take as long as 24 hours for the group and all of its data to be restored.</span></span>

    <span data-ttu-id="775af-109">Hvis du vil ha mer informasjon, eller hvis du vil lære hvordan du gjenoppretter grupper ved hjelp av PowerShell, kan du se Gjenopprette en [slettet Microsoft 365-gruppe.](https://go.microsoft.com/fwlink/?linkid=867802)</span><span class="sxs-lookup"><span data-stu-id="775af-109">For more info, or to learn how to restore groups using PowerShell, see [Restore a deleted Microsoft 365 group](https://go.microsoft.com/fwlink/?linkid=867802).</span></span>