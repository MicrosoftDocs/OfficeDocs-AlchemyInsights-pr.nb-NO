---
title: DLP-regel for oss bankkontonummeret fungerer ikke
ms.author: cmcatee
author: cmcatee-MSFT
manager: mnirkhe
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 80b40145-8376-4c3a-8d22-6efb9f9cb271
ms.openlocfilehash: 6eae9146d33f5fc307085dbf931d57bdbb28b82e
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: nb-NO
ms.lasthandoff: 01/15/2019
ms.locfileid: "28303751"
---
Har du problemer med **Data tap forebygging (DLP)** fungerer ikke for innhold som inneholder et **Amerikansk bankkontonummeret** når du bruker en type for DLP sensitiv informasjon i O365? Hvis dette er tilfelle, kontroller at innholdet inneholder nødvendig informasjon for det DLP-policyen er ute etter når de evalueres. 
  
For eksempel, for en **Amerikansk bankkontonummeret** policy konfigurert med en konfidenskoeffisienten for 85%, følgende evalueres og må registreres for at regelen skal utløse: 
  
- **[Format:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** 8-17-sifre 
    
- **[Mønster:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** 8-17 etterfølgende sifre. 
    
- **[Kontrollsum:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** Nei, det finnes ingen kontrollsum 
    
- **[Definisjon:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for)** DLP-policy er 75% sikker på at det har oppdaget at sensitive opplysninger hvis, i en avstand på 300 tegn: 
    
  - Det vanlige uttrykket Regex_usa_bank_account_number finner innhold som samsvarer med mønsteret
    
  - Det finnes et nøkkelord fra Keyword_usa_Bank_Account.
    
    Hvis du for eksempel følgende eksempel vil utløse for **Amerikanske bankkontonummeret** policyen: sjekkonto 78344011 
    
Hvis du vil ha mer informasjon om hva som trengs for et **Amerikansk bankkontonummeret** kan oppdages for innholdet, kan du se delen nedenfor i denne artikkelen: [Hva the Sensitive informasjonstyper se etter Amerikanske bankkontonummer](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#us-bank-account-number)
  
Å bruke en annen innebygd sensitiv informasjon, se følgende artikkel for å få informasjon på det som er nødvendig for andre typer: [se hva den Sensitive informasjonstyper](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for)
  
