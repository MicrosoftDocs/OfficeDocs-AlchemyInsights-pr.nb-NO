---
title: AggregateGroupMailbox full NDR mottatt for e-post sendt til Microsoft 365-gruppe
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 12/18/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004286"
- "7656"
ms.openlocfilehash: 9de09ab4cbd2f09648305b11da6273ed990907cf
ms.sourcegitcommit: 2ffdf6096de5608b117c6677d3cd7dd4c23ea024
ms.translationtype: MT
ms.contentlocale: nb-NO
ms.lasthandoff: 12/18/2020
ms.locfileid: "49722084"
---
# <a name="aggregategroupmailbox-full-ndr-received-for-email-sent-to-microsoft-365-group"></a>AggregateGroupMailbox full NDR mottatt for e-post sendt til Microsoft 365-gruppe

Bruk følgende EXO-skall kommando for å opprette en Exchange-transport regel for å slette e-post sendt til aggregert gruppe post boks:

`New-TransportRule -SentTo @("AggregateGroupMailbox.A.201708181918@contoso.onmicrosoft.com") -DeleteMessage:$true -Name 'Agg1' -StopRuleProcessing:$false -Mode 'Enforce' -Comments '' -RuleErrorAction 'Ignore' -SenderAddressLocation 'Header'`

> [!NOTE]
> Erstatt SMTP-adressen i **-SentTo** med SMTP-adressen til aggregat gruppe post boksen i leieren. Du kan få SMTP-adressen til aggregat Group-postboksen fra NDR Received.



