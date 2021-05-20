---
title: Microsoft Defender for Office 365 for SharePoint, OneDrive og Microsoft Teams
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1037
ms.assetid: ''
ms.openlocfilehash: 7d2ed7bc4c7d99cd01dadc12e38762903d6d8ab3
ms.sourcegitcommit: f4866e94918c7b591ad0cd3b58169d340bcc7f00
ms.translationtype: MT
ms.contentlocale: nb-NO
ms.lasthandoff: 05/19/2021
ms.locfileid: "52543586"
---
# <a name="microsoft-defender-for-office-365-for-sharepoint-onedrive-and-microsoft-teams"></a><span data-ttu-id="c47a9-102">Microsoft Defender for Office 365 for SharePoint, OneDrive og Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="c47a9-102">Microsoft Defender for Office 365 for SharePoint, OneDrive, and Microsoft Teams</span></span>

<span data-ttu-id="c47a9-103">Følg disse trinnene for å aktivere Microsoft Defender for Office 365:</span><span class="sxs-lookup"><span data-stu-id="c47a9-103">Follow these steps to enable Microsoft Defender for Office 365:</span></span>

1. <span data-ttu-id="c47a9-104">Gå til [https://protection.office.com](https://protection.office.com) og logg på med en global administrator- eller sikkerhetsadministratorkonto.</span><span class="sxs-lookup"><span data-stu-id="c47a9-104">Go to [https://protection.office.com](https://protection.office.com) and sign in with a global administrator or security administrator account.</span></span>

2. <span data-ttu-id="c47a9-105">Velg Policysikkert vedlegg **i** den venstre navigasjonsruten under Trusselbehandling  \> .</span><span class="sxs-lookup"><span data-stu-id="c47a9-105">In the left navigation pane under **Threat management**, choose **Policy** \> **Safe Attachments**.</span></span>

3. <span data-ttu-id="c47a9-106">Velg **Aktiver Defender for Office 365 for SharePoint, OneDrive og Microsoft Teams**.</span><span class="sxs-lookup"><span data-stu-id="c47a9-106">Select **Turn on Defender for Office 365 for SharePoint, OneDrive, and Microsoft Teams**.</span></span>

4. <span data-ttu-id="c47a9-107">[Opprett en policy for aktivitetsvarsling](/microsoft-365/compliance/create-activity-alerts) for å motta varsler når vi oppdager skadelige filer.</span><span class="sxs-lookup"><span data-stu-id="c47a9-107">[Create an activity alert policy](/microsoft-365/compliance/create-activity-alerts) to receive notifications when we detect malicious files.</span></span>

<span data-ttu-id="c47a9-108">Hvis du vil ha fullstendige instruksjoner, kan du se slå [på klarerte vedlegg for SharePoint, OneDrive og Microsoft Teams](/microsoft-365/security/office-365-security/turn-on-atp-for-spo-odb-and-teams).</span><span class="sxs-lookup"><span data-stu-id="c47a9-108">For complete instructions, see this [Turn on Safe Attachments for SharePoint, OneDrive, and Microsoft Teams](/microsoft-365/security/office-365-security/turn-on-atp-for-spo-odb-and-teams).</span></span>

<span data-ttu-id="c47a9-109">**Obs!** Microsoft Defender for Office 365 skanner ikke hver enkelt fil i SharePoint Online, OneDrive for Business eller Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="c47a9-109">**Note**: By design, Microsoft Defender for Office 365 doesn't scan every single file in SharePoint Online, OneDrive for Business, or Microsoft Teams.</span></span> <span data-ttu-id="c47a9-110">Filer skannes asynkront av en prosess som bruker delingsaktivitet, gjesteaktivitet og trusselsignaler til å identifisere skadelige filer.</span><span class="sxs-lookup"><span data-stu-id="c47a9-110">Files are scanned asynchronously by a process that uses sharing activity, guest activity, and threat signals to identify malicious files.</span></span> <span data-ttu-id="c47a9-111">Hvis du vil ha mer informasjon, kan du [se Klarerte vedlegg for SharePoint, OneDrive og Microsoft Teams](/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams).</span><span class="sxs-lookup"><span data-stu-id="c47a9-111">For more information, see [Safe Attachments for SharePoint, OneDrive, and Microsoft Teams](/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams).</span></span>
