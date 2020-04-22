---
title: Aktivere Atp for Office 365 for SharePoint, OneDrive og Microsoft Teams
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Admin_O365
ms.custom: 3100021
ms.openlocfilehash: fdfdc97a198898051a3388672d01994d96dd5e97
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: nb-NO
ms.lasthandoff: 04/22/2020
ms.locfileid: "43703435"
---
# <a name="enable-office-365-advanced-threat-protection-for-sharepoint-online-onedrive-and-microsoft-teams"></a>Aktivere avansert trusselbeskyttelse for Office 365 for SharePoint Online, OneDrive og Microsoft Teams

1. Gå https://protection.office.com til og logg på.
2. Velg Policy for **Threat management** > **trusselstyring** > **sikre vedlegg**.
3. Velg **Aktiver ATP for SharePoint, OneDrive og Microsoft Teams**, og klikk deretter **Lagre**.
4. (Anbefales) Som global administrator eller SharePoint Online-administrator kjører du cmdleten [Set-SPOTenant](https://docs.microsoft.com/powershell/module/sharepoint-online/Set-SPOTenant?view=sharepoint-ps) med parameteren **DisallowInfectedFileDownload** satt til *true*.
5. (Anbefales) [Konfigurer varsler](https://docs.microsoft.com/office365/securitycompliance/turn-on-atp-for-spo-odb-and-teams#set-up-alerts-for-detected-files) for oppdagede filer.

> [!NOTE]
> ATP vil ikke skanne hver enkelt fil i SharePoint Online, OneDrive eller Microsoft Teams. Filer skannes asynkront, gjennom en prosess som bruker deling og gjesteaktivitetshendelser, sammen med smarte heuristikk og trusselsignaler for å identifisere skadelige filer. Se [https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams).