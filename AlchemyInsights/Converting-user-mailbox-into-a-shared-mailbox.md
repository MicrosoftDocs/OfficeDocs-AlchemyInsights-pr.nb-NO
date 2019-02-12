---
title: Konverterer brukerens postboks til en delt postboks?
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ROBOTS: NOINDEX, NOFOLLOW
description: ''
ms.openlocfilehash: 4da54121763fd33aa111f3bb3c26963cd271dc51
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: nb-NO
ms.lasthandoff: 02/12/2019
ms.locfileid: "29906741"
---
<span data-ttu-id="67d75-p101">Du kan bare konvertere en Brukerpostboks til en delt postboks Hvis brukeren har en lisens for Exchange. Når postboksen er konvertert, vil den fortsette å vises i brukerlisten over aktive fordi listen inneholder delte postbokser. Imidlertid vil konverterte postboksen også vises i listen over delte postbokser.</span><span class="sxs-lookup"><span data-stu-id="67d75-p101">You can only convert a user mailbox to a shared mailbox if the user has an Exchange license. After the mailbox is converted, it will continue to show up in the active users list because that list includes shared mailboxes. However, the converted mailbox will also show up in the shared mailbox list.</span></span> 
  
<span data-ttu-id="67d75-p102">Hvis du prøver å konvertere en postboks i Exchange Administrator-konsollen, og konverteringen mislykkes, tømme hurtigbufferen og informasjonskapslene, og prøv på nytt. Hvis det fortsatt ikke fungerer, kan du prøve å konvertere postboks i Exchange Management Shell ved å kjøre følgende kommando:</span><span class="sxs-lookup"><span data-stu-id="67d75-p102">If you try to convert a mailbox in the Exchange Admin Console and the conversion fails, clear your browser cache and cookies and try again. If it still isn't working, try converting the mailbox in the Exchange Management Shell by running the following command:</span></span>
  
```
Set-Mailbox -Type Shared
```

<span data-ttu-id="67d75-107">Mer informasjon om konvertering av postboksen er tilgjengelig i [konvertere en Brukerpostboks til en delt postboks](https://support.office.com/client/2e122487-e1f5-4f26-ba41-5689249d93ba).</span><span class="sxs-lookup"><span data-stu-id="67d75-107">More mailbox conversion information is available in [Convert a user mailbox to a shared mailbox](https://support.office.com/client/2e122487-e1f5-4f26-ba41-5689249d93ba).</span></span>
  
