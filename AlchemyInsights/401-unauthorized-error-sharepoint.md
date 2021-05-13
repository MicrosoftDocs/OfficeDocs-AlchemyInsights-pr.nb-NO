---
title: 401 Uautorisert feil i SharePoint
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 04/14/2021
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "10935"
- "9001435"
ms.openlocfilehash: 6799b2112458a7ab3715c9b63e03c2c7ca3fe6be
ms.sourcegitcommit: 6c6b0c3885f33b08db929fe0b6496508d31fa2d6
ms.translationtype: MT
ms.contentlocale: nb-NO
ms.lasthandoff: 05/06/2021
ms.locfileid: "52233515"
---
# <a name="401-unauthorized-error-in-sharepoint"></a>401 Uautorisert feil i SharePoint

Hvis du får feilmeldingen «(401) Uautorisert» i SharePoint kan den være relatert til avviklingen av TLS 1.0/1.1. Hvis du vil ha mer informasjon, kan du ta en titt på:

[Klargjøre for TLS 1.2 i Office 365 og Office 365 GCC](https://docs.microsoft.com/microsoft-365/compliance/prepare-tls-1.2-in-office-365)

[Godkjenningsfeil oppstår hvis klienten ikke har støtte for TLS 1.2](https://review.docs.microsoft.com/sharepoint/troubleshoot/administration/authentication-errors-tls12-support)

Hvis brukerne er på Windows 7, må du kontrollere at de kontrollerer [TLS Cipher Suites i Windows 7](https://docs.microsoft.com/windows/win32/secauthn/tls-cipher-suites-in-windows-7).