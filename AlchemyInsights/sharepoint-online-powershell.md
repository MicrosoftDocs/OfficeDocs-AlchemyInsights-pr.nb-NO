---
title: Sharepoint Online PowerShell
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
- "9000266"
- "1867"
ms.openlocfilehash: 839a70282b4dd619e9dbe8167ef0e409e468b1ad
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: nb-NO
ms.lasthandoff: 04/15/2021
ms.locfileid: "51830591"
---
# <a name="sharepoint-online-powershell"></a>Sharepoint Online PowerShell

Arbeider du med PowerShell eller Skript i Sharepoint Online? Gå til koblingene nedenfor for mer informasjon.
- [Komme i gang med Administrasjonsskall for SharePoint Online](https://docs.microsoft.com/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps)
- [Koble til SPO PowerShell med godkjenning med flere faktorer (MFA)](https://docs.microsoft.com/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps#to-connect-with-multifactor-authentication-mfa)
- [SharePoint-mønstre og -praksiser (PnP)](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps) inneholder et bibliotek med PowerShell-kommandoer som lar deg utføre komplekse administrasjonshandlinger mot SPO.

> [!NOTE]
> - Hvis du har problemer med å koble til SPO-administrasjonsskallet, [](https://docs.microsoft.com/powershell/scripting/developer/module/importing-a-powershell-module?view=powershell-7.1) må du kontrollere at du har oppdatert til den nyeste versjonen og prøve å importere modulen på nytt ved hjelp av *Import-Module Microsoft.Online.SharePoint.PowerShell.*
> - Hvis du prøver å kjøre skript for klientobjektmodell, må du ha SDK-en for [Sharepoint Online-klientkomponenter](https://www.microsoft.com/download/details.aspx?id=42038) installert på den lokale maskinen.
> - Hvis du har problemer med å kjøre skript fra PowerShell, bør du vurdere å kjøre PowerShell som administrator og endre [kjøringspolicyen](https://docs.microsoft.com/powershell/module/microsoft.powershell.core/about/about_execution_policies?view=powershell-6).