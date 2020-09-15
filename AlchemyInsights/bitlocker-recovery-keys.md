---
title: BitLocker-gjenopprettings nøkler
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
- "1922"
- "9000220"
ms.openlocfilehash: 7c56e68cf303939d8e7d4ee0a7301e367ecfe9f9
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: nb-NO
ms.lasthandoff: 09/14/2020
ms.locfileid: "47685895"
---
# <a name="accessing-bitlocker-recovery-keys"></a><span data-ttu-id="e5775-102">Få tilgang til BitLocker-gjenopprettings nøklene</span><span class="sxs-lookup"><span data-stu-id="e5775-102">Accessing Bitlocker recovery keys</span></span>

<span data-ttu-id="e5775-103">Når du konfigurerer BitLocker-innstillinger Intune Endpoint Protection-policyen, kan du definere om BitLocker-gjenopprettingsinformasjon skal lagres i Azure Active Directory.</span><span class="sxs-lookup"><span data-stu-id="e5775-103">When configuring Bitlocker settings Intune Endpoint Protection Policy, it is possible to define whether Bitlocker recovery information should be stored in Azure Active Directory.</span></span>

<span data-ttu-id="e5775-104">Hvis denne innstillingen er konfigurert, skal lagrede gjenopprettings data være synlige for en Intune-administrator som en del av enhets post dataene i Intune-enheter blad på to måter:</span><span class="sxs-lookup"><span data-stu-id="e5775-104">If that setting is configured, the stored recovery data should be visible to an Intune admin as part of the device record data in Intune Devices blade in two ways:</span></span>

<span data-ttu-id="e5775-105">Enheter – Azure AD-enheter – > "enhet" eller enheter-> alle enheter-> "enhet" – > gjenopprettings nøkler</span><span class="sxs-lookup"><span data-stu-id="e5775-105">Devices - Azure AD devices -> "Device"  OR Devices -> All Devices -> "Device" -> Recovery keys</span></span>

<span data-ttu-id="e5775-106">Hvis det er administrator tilgang til selve enheten, kan du eventuelt se gjenopprettings nøkkelen (passord) ved å kjøre følgende kommando fra en hevet lede tekst:</span><span class="sxs-lookup"><span data-stu-id="e5775-106">Alternatively, if there is administrative access to the device itself, the recovery key (Password) can be seen by running the following command from an elevated command prompt:</span></span>

```
manage-bde -protectors c: -get
Example
Volume C: []
All Key Protectors
    TPM:
      ID: {8A5D13D6-7ED9-46C8-A74F-AC3ADF016EC8}
      PCR Validation Profile:
        0, 2, 4, 8, 9, 10, 11
    Numerical Password:
      ID: {DFA26333-XXXX-402C-YYYY-A8C40AF3ZZZZ}
      Password:
        393943-22222-281721-555554-577984-77777-194700-99999
```
<span data-ttu-id="e5775-107">Hvis enheten ble kryptert før enrolment i Intune, kan gjenopprettings nøkkelen ha blitt tilknyttet "Microsoft-kontoen" (MSA) som brukes til å logge på enheten under OOBE-prosessen.</span><span class="sxs-lookup"><span data-stu-id="e5775-107">If the device was encrypted prior to enrolment in Intune, the recovery key may have been associated with the "Microsoft Account" (MSA) used to sign in to the device during the OOBE process.</span></span> <span data-ttu-id="e5775-108">Hvis dette var tilfelle, kan du få tilgang til  https://onedrive.live.com/recoverykey og logge på med denne MSA for å vise enhetene som gjenopprettings nøklene ble lagret i.</span><span class="sxs-lookup"><span data-stu-id="e5775-108">If that was the case, accessing  https://onedrive.live.com/recoverykey and signing in with that MSA should show the devices for which recovery keys were stored.</span></span>
 
<span data-ttu-id="e5775-109">Hvis enheten ble kryptert som et resultat av konfigurasjon via domene BAS ert gruppe policy, kan gjenopprettings informasjonen være lagret i den lokale Active Directory.</span><span class="sxs-lookup"><span data-stu-id="e5775-109">If the device was encrypted as a result of configuration through domain-based group policy, the recovery information may be stored in the on-premise Active Directory.</span></span>
 

