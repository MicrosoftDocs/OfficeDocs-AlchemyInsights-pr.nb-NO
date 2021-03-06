---
title: Manglende e-postmeldinger i karantene
ms.author: pebaum
author: pebaum
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "5668"
- "9002625"
ms.openlocfilehash: 563f76f624f428a46894268b478cf05eb757b497
ms.sourcegitcommit: f4866e94918c7b591ad0cd3b58169d340bcc7f00
ms.translationtype: MT
ms.contentlocale: nb-NO
ms.lasthandoff: 05/19/2021
ms.locfileid: "52539833"
---
# <a name="missing-emails-in-quarantine"></a>Manglende e-postmeldinger i karantene"

Administratorer kan [vise, frigi eller slette disse meldingene.](/microsoft-365/security/office-365-security/manage-quarantined-messages-and-files)

Hvis du vil åpne sikkerhetssenteret & samsvarssenteret, går du til [https://protection.office.com](https://protection.office.com/) . Hvis du vil åpne Karantenesiden direkte, går du til [https://protection.office.com/quarantine](https://protection.office.com/quarantine) .  

Du kan søke etter følgende verdier:  

- **Meldings-ID:** Den globalt unike identifikatoren for meldingen. Hvis du velger en melding i listen, vises  **Meldings-ID-verdien**  i  **detaljer-undermenyen**  som vises. Administratorer kan bruke [meldingssporing til](/microsoft-365/security/office-365-security/message-trace-scc) å finne meldinger og tilhørende meldings-ID-verdier.
- **Avsenderens e-postadresse:** En enkelt avsenders e-postadresse.
- **E-postadresse for** mottaker: Én enkelt mottakers e-postadresse.
- **Emne:** Bruk hele emnet i meldingen. Søket skiller ikke mellom store og små bokstaver.

Når du har angitt søkekriteriene, klikker du ![ Oppdater-knappen ](/microsoft-365/media/scc-quarantine-refresh.png?view=o365-worldwide) **Oppdater for** å filtrere resultatene.

Cmdletene du bruker til å vise og behandle meldinger og filer i karantene, er:
- [Delete-QuarantineMessage](/powershell/module/exchange/delete-quarantinemessage)
- [Export-QuarantineMessage](/powershell/module/exchange/export-quarantinemessage)
- [Get-QuarantineMessage](/powershell/module/exchange/get-quarantinemessage)
- [Preview-QuarantineMessage:](/powershell/module/exchange/preview-quarantinemessage)Vær oppmerksom på at denne cmdleten bare er for meldinger, ikke skadelig programvarefiler fra Microsoft Defender for Office 365 for SharePoint Online, OneDrive for Business eller Teams.
- [Release-QuarantineMessage](/powershell/module/exchange/release-quarantinemessage)