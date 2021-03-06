---
title: Løse transportregler
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
ms.openlocfilehash: 635009ed4b78d2b05b0eef1f3298765b10f86ede
ms.sourcegitcommit: 6312ee31561db36104f32282d019d069ede69174
ms.translationtype: MT
ms.contentlocale: nb-NO
ms.lasthandoff: 03/11/2021
ms.locfileid: "50750580"
---
# <a name="fix-transport-rules"></a>Løse transportregler

En egendefinert e-postflytregel påvirket denne meldingen. Hvis du vil se gjennom den nøyaktige regelen, gjør du følgende:

1. Legg merke til GUID-en eller  policynavnet under **Tilleggsinformasjon** i **innsendingsresultatene.**
2. Start Skallet for Exchange-administrasjon. Hvis du vil ha mer informasjon, [kan du se Åpne Exchange Management Shell](https://go.microsoft.com/fwlink/?linkid=2101432).
3. Kjør denne kommandoen (ved hjelp av GUID fra innsendingen):  **Get-TransportRule -identity "GUID" | fl * Description***
4. Se gjennom beskrivelsen for å se de konfigurerte betingelsene som påvirket meldingen.

Hvis du vil ha mer informasjon, [kan du se Get-TransportRule](https://go.microsoft.com/fwlink/?linkid=2101523).
