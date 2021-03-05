---
title: 'Slik konfigurerer du automatisk svar for alle e-postmeldinger som sendes til Microsoft 365-gruppen:'
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 02/19/2021
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "8586"
- "9003200"
ms.openlocfilehash: c3c1d4e6b16b54d92771d7bdecdc9cb12bbf888c
ms.sourcegitcommit: 379e132c4d21ecf703d5506484ec96a767fdda39
ms.translationtype: MT
ms.contentlocale: nb-NO
ms.lasthandoff: 03/04/2021
ms.locfileid: "50481864"
---
# <a name="to-configure-auto-reply-for-all-emails-sent-to-microsoft-365-group"></a>Slik konfigurerer du automatisk svar for alle e-postmeldinger som sendes til Microsoft 365-gruppen:

**Koble til EXO PowerShell ved hjelp av administratorkontoen for leieren, og bruk følgende kommando:**

`Set-MailboxAutoReplyConfiguration -Identity groupmailbox -AutoReplyState Enabled -InternalMessage "Internal auto-reply message." -ExternalMessage "External auto-reply message`

> [!NOTE]
> Endre **gruppepostboksen** til et gruppenavn som du vil konfigurere automatisk svar på.

