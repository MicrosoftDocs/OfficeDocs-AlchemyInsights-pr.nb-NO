---
title: Åpne med Explorer fungerer ikke
ms.author: toresing
author: tomresing
manager: scotv
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: b8f07022-69fe-4112-a2f6-d3a6cedb966c
ms.openlocfilehash: 5bf28982533d8ca9998605cf3592f317c0ef99b0
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: nb-NO
ms.lasthandoff: 09/14/2020
ms.locfileid: "47694465"
---
# <a name="open-with-explorer-isnt-working"></a>Åpne med Explorer fungerer ikke

Hvis **Åpne med Utforsker** eller **Vis i fil Utforsker** ikke fungerer, kan du ikke sørge for at WebClient-tjenesten er satt til å **kjøre** ved å følge Fremgangs måten nedenfor. Det kan for eksempel gå lang tid å åpne et SharePoint-eller OneDrive-bibliotek når tjenesten ikke kjører. 
  
1. Skriv inn Kjør i Windows Search-boksen, velg Kjør skrive bords-appen, Skriv inn Services. msc, og velg deretter **Enter**.
    
2. Rull ned til WebClient-tjenesten, og kontroller **status** -kolonnen. Hvis tjeneste statusen WebClient ikke **kjører**, dobbelt klikker du tjenesten, klikker **Start**og deretter **OK**. Aktiver tjenesten, hvis nødvendig, ved å velge enten **manuell** eller **automatisk** i boksen **oppstarts type** . 
    
> [!NOTE]
> Hvis du vil feilsøke problemer med å åpne i fil Utforsker, kan du se [Åpne i Explorer](https://go.microsoft.com/fwlink/?linkid=871665). Utforsk synkronisering som et bedre alternativ: [synkronisere SharePoint-filer med den nye synkroniserings klienten for OneDrive](https://go.microsoft.com/fwlink/?linkid=871666). 
  

