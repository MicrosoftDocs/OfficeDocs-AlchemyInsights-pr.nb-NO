---
title: Aktivere overvåking av postbokser
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 4/5/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 19997b0a-394f-4943-8908-c601696a332c
ms.openlocfilehash: 73517f46935a67a4a8a3e4770090ac897fe67979
ms.sourcegitcommit: a256e8680379c006287ae30996763051c4d9ff85
ms.translationtype: MT
ms.contentlocale: nb-NO
ms.lasthandoff: 09/04/2019
ms.locfileid: "36736262"
---
# <a name="enable-mailbox-auditing"></a>Aktivere overvåking av postbokser

Hvis du vil aktivere postboksovervåking for én enkelt bruker eller en hel organisasjon, må følgende cmdleter kjøres fra Remote Power Shell:
  
 **Enkelt bruker**
  
Sett-postkasse-identitet "Jane Dow"-AuditEnabled $true
  
 **Organisasjon**
  
Get-postboks-ResultSize Unlimited-filter {RecipientTypeDetails-EQ "UserMailbox"} | Sett postboks-AuditEnabled $true
  
[få mer informasjon](https://docs.microsoft.com/office365/securitycompliance/enable-mailbox-auditing)
  

