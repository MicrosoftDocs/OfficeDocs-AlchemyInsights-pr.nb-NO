---
title: DLP-regel for amerikansk bankkontonummer fungerer ikke
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1287"
- "3200001"
ms.assetid: 80b40145-8376-4c3a-8d22-6efb9f9cb271
ms.openlocfilehash: b032a7c80e8b387114aeda95c4f6af7e57225517
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: nb-NO
ms.lasthandoff: 06/02/2020
ms.locfileid: "44507343"
---
# <a name="dlp-issues-with-us-bank-account-numbers"></a><span data-ttu-id="2cae5-102">DLP-problemer med amerikanske bankkontonumre</span><span class="sxs-lookup"><span data-stu-id="2cae5-102">DLP issues with US bank account numbers</span></span>

<span data-ttu-id="2cae5-103">**Viktig**: I disse enestående tidene tar vi grep for å sikre at SharePoint Online-og OneDrive-tjenester forblir svært tilgjengelige – Gå til [Midlertidige SharePoint Online-funksjoner](https://aka.ms/ODSPAdjustments) for mer informasjon.</span><span class="sxs-lookup"><span data-stu-id="2cae5-103">**Important**: During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available – Please visit [SharePoint Online Temporary Feature Adjustments](https://aka.ms/ODSPAdjustments) for more information.</span></span>

<span data-ttu-id="2cae5-104">**DLP-problemer med amerikanske bankkontonumre**</span><span class="sxs-lookup"><span data-stu-id="2cae5-104">**DLP issues with US bank account numbers**</span></span>

<span data-ttu-id="2cae5-105">Har du problemer med **at Data Loss Prevention (DLP)** ikke fungerer for innhold som inneholder et amerikansk **bankkontonummer** når du bruker en DLP-sensitiv informasjonstype i O365?</span><span class="sxs-lookup"><span data-stu-id="2cae5-105">Are you having problems with **Data Loss Prevention (DLP)** not working for content containing a **US Bank Account Number** when using a DLP sensitive information type in O365?</span></span> <span data-ttu-id="2cae5-106">I så fall må du kontrollere at innholdet inneholder den nødvendige informasjonen for hva DLP-policyen ser etter når det evalueres.</span><span class="sxs-lookup"><span data-stu-id="2cae5-106">If so, make sure your content contains the needed information for what the DLP policy is looking for when it is evaluated.</span></span>
  
<span data-ttu-id="2cae5-107">For en policy for **amerikansk bankkontonummer** som er konfigurert med et konfidensnivå på 85 %, evalueres følgende og må oppdages for at regelen skal utløses:</span><span class="sxs-lookup"><span data-stu-id="2cae5-107">For example, for a **US Bank Account Number** policy configured with a confidence level of 85%, the following are evaluated and must be detected for the rule to trigger:</span></span>
  
- <span data-ttu-id="2cae5-108">**[Format:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#format-77)** 8-17 sifre</span><span class="sxs-lookup"><span data-stu-id="2cae5-108">**[Format:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#format-77)** 8-17 digits</span></span>

- <span data-ttu-id="2cae5-109">**[Mønster:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#pattern-77)** 8-17 sifre på rad.</span><span class="sxs-lookup"><span data-stu-id="2cae5-109">**[Pattern:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#pattern-77)** 8-17 consecutive digits.</span></span>

- <span data-ttu-id="2cae5-110">**[Sjekksum:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#checksum-76)** Nei, det er ingen kontrollsum</span><span class="sxs-lookup"><span data-stu-id="2cae5-110">**[Checksum:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#checksum-76)** No, there is no Checksum</span></span>

- <span data-ttu-id="2cae5-111">**[Definisjon:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions)** En DLP-policy er 75 % sikker på at den oppdages denne typen sensitiv informasjon hvis, i nærheten av 300 tegn:</span><span class="sxs-lookup"><span data-stu-id="2cae5-111">**[Definition:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions)** A DLP policy is 75% confident that it's detected this type of sensitive information if, within a proximity of 300 characters:</span></span>

  - <span data-ttu-id="2cae5-112">Det regulære uttrykket Regex_usa_bank_account_number finner innhold som samsvarer med mønsteret</span><span class="sxs-lookup"><span data-stu-id="2cae5-112">The regular expression Regex_usa_bank_account_number finds content that matches the pattern</span></span>

  - <span data-ttu-id="2cae5-113">Du finner et nøkkelord fra Keyword_usa_Bank_Account.</span><span class="sxs-lookup"><span data-stu-id="2cae5-113">A keyword from Keyword_usa_Bank_Account is found.</span></span>

    <span data-ttu-id="2cae5-114">Følgende eksempel utløses for eksempel for policyen **for us bankkontonummer:** Kontrollere konto 78344011</span><span class="sxs-lookup"><span data-stu-id="2cae5-114">For example, the following sample would trigger for the **US Bank Account Number** policy: Checking Account 78344011</span></span>

<span data-ttu-id="2cae5-115">Hvis du vil ha mer informasjon om hva som kreves for at et **amerikansk bankkontonummer** skal oppdages for innholdet ditt, kan du se følgende del i denne artikkelen: [Hva sensitive informasjonstyper ser etter amerikansk bankkontonummer](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#us-bank-account-number)</span><span class="sxs-lookup"><span data-stu-id="2cae5-115">For more information on what is required for a **US Bank Account Number** to be detected for your content, see the following section in this article: [What the Sensitive Information Types look for US Bank Account Number](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#us-bank-account-number)</span></span>
  
<span data-ttu-id="2cae5-116">Hvis du bruker en annen innebygd sensitiv informasjonstype, kan du se følgende artikkel for informasjon om hva som kreves for andre typer: [Hva sensitive informasjonstyper ser etter](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions)</span><span class="sxs-lookup"><span data-stu-id="2cae5-116">Using a different built-in sensitive information type, see the following article for information on what is required for other types: [What the Sensitive Information Types look for](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions)</span></span>
  