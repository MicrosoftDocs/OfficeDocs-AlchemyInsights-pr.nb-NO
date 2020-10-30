---
title: Endre krav til sterkt passord
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000105"
- "1600"
ms.openlocfilehash: 8ce331275e066b5a4f177ae27178ec726f90762f
ms.sourcegitcommit: aa35d2e1829f7d07f64fb891bf73b1fd80f0864c
ms.translationtype: MT
ms.contentlocale: nb-NO
ms.lasthandoff: 10/30/2020
ms.locfileid: "48804432"
---
# <a name="change-strong-password-requirement"></a>Endre krav til sterkt passord

Microsoft krever sterke passord som standard.

Ved hjelp av PowerShell kan du deaktivere sterke passord for bestemte brukere med disse kommandoene:

`Set-MsolUser –UserPrincipalName <UserPrincipalName> –StrongPasswordRequired  $false`

Hvis du vil deaktivere sterke passord for alle brukere, bruker du:

`Get-MsolUser | Set-MsolUser -StrongPasswordRequired $false`

- [Mer informasjon om passord policy](https://docs.microsoft.com/azure/active-directory/authentication/concept-sspr-policy#password-policies-that-only-apply-to-cloud-user-accounts)
- [Slik kobler du til Microsoft 365 med PowerShell](https://docs.microsoft.com/office365/enterprise/powershell/connect-to-office-365-powershell#connect-with-the-microsoft-azure-active-directory-module-for-windows-powershell)
- [Mer informasjon om PowerShell MsolUser-kommandoer](https://docs.microsoft.com/powershell/module/msonline/set-msoluser?view=azureadps-1.0)
