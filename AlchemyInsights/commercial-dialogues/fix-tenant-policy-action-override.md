---
title: Løse tenantpolicy (handlingsoverstyring)
ms.author: v-jmathew
author: v-jmathew
manager: dansimp
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000760"
- "7391"
ms.openlocfilehash: bc7ad8acd86c9d5b2f99ffdc6fe8a8b53e1fcb8b
ms.sourcegitcommit: 6312ee31561db36104f32282d019d069ede69174
ms.translationtype: MT
ms.contentlocale: nb-NO
ms.lasthandoff: 03/11/2021
ms.locfileid: "50748994"
---
# <a name="fix-tenant-policy-action-override"></a>Løse tenantpolicy (handlingsoverstyring)

En policy for søppelpost i tenanten påvirket denne meldingen. Gjør følgende for å se gjennom policyen:

1. Gå til sikkerhets- og samsvarssenteret [for Office 365 &](https://go.microsoft.com/fwlink/p/?linkid=2077143), og gå deretter til Policy for beskyttelse mot søppelpost for   >    >  [trusler.](https://go.microsoft.com/fwlink/?linkid=2101518)
2. Kontroller om **Policykilde** angir følgende:  **Add-Xheader/ModifySubject/Redirect/Delete/No action/ Blindkopi-melding**

    Hvis dette er det, **kontrollerer** du innstillingene for policyen som påvirket meldingen, på Egendefinert-fanen. Det er mulig at **standardinnstillingene som** ble brukt på alle Exchange Online Protection-kunder, påvirket meldingen.

Hvis du vil ha mer informasjon om hvordan du konfigurerer policyer for søppelpostfilter, kan [du se Konfigurere policyer for søppelpostfilter .](https://go.microsoft.com/fwlink/?linkid=2101431)
