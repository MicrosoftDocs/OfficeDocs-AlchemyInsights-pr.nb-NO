---
title: Feilsøke problemer med MDATP-installasjonen på en Mac
ms.author: v-jmathew
author: v-jmathew
manager: dansimp
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000760"
- "7391"
ms.openlocfilehash: 4b03361666f950a2010e4c4d8e78d156438d9e90
ms.sourcegitcommit: bd6a9cb5d357baee5134c0dea430afc2a035c810
ms.translationtype: MT
ms.contentlocale: nb-NO
ms.lasthandoff: 03/09/2021
ms.locfileid: "50696090"
---
# <a name="troubleshoot-mdatp-installation-problems-on-a-mac"></a><span data-ttu-id="d17ab-102">Feilsøke problemer med MDATP-installasjonen på en Mac</span><span class="sxs-lookup"><span data-stu-id="d17ab-102">Troubleshoot MDATP installation problems on a Mac</span></span>

<span data-ttu-id="d17ab-103">Hvis manuell installasjon mislykkes, viser **Sammendrag-siden** i installasjonsveiviseren følgende feil:</span><span class="sxs-lookup"><span data-stu-id="d17ab-103">If manual installation fails, the **Summary** page of the installation wizard shows the following error:</span></span>

<span data-ttu-id="d17ab-104">«Det oppstod en feil under installasjonen.</span><span class="sxs-lookup"><span data-stu-id="d17ab-104">"An error occurred during installation.</span></span> <span data-ttu-id="d17ab-105">Installasjonsprogrammet oppdaget en feil som førte til at installasjonen mislyktes.</span><span class="sxs-lookup"><span data-stu-id="d17ab-105">The Installer encountered an error that caused the installation to fail.</span></span> <span data-ttu-id="d17ab-106">Kontakt programvareprodusenten for å få hjelp.»</span><span class="sxs-lookup"><span data-stu-id="d17ab-106">Contact the software manufacturer for assistance."</span></span>

<span data-ttu-id="d17ab-107">For MDM-distribusjoner viser siden også en generell installasjonsfeil.</span><span class="sxs-lookup"><span data-stu-id="d17ab-107">For MDM deployments, the page shows a generic installation failure, too.</span></span>

<span data-ttu-id="d17ab-108">Selv om vi ikke viser nøyaktige feil til sluttbrukere, holder vi en loggfil med installasjonsfremdrift i **/Bibliotek/Logger/Microsoft/mdatp/install.log.**</span><span class="sxs-lookup"><span data-stu-id="d17ab-108">Although we don't display exact errors to end users, we keep a log file with installation progress, in **/Library/Logs/Microsoft/mdatp/install.log**.</span></span> <span data-ttu-id="d17ab-109">Hver installasjonsøkt legges til denne loggfilen.</span><span class="sxs-lookup"><span data-stu-id="d17ab-109">Each installation session appends to this log file.</span></span> <span data-ttu-id="d17ab-110">Hvis du bare vil sende ut den siste installasjonsøkten, bruker du `sed` .</span><span class="sxs-lookup"><span data-stu-id="d17ab-110">To output the last installation session only, use `sed`.</span></span>

<span data-ttu-id="d17ab-111">Hvis du vil ha mer informasjon, kan du se Feilsøke installasjonsproblemer [for Microsoft Defender ATP for Mac.](https://go.microsoft.com/fwlink/?linkid=2144615)</span><span class="sxs-lookup"><span data-stu-id="d17ab-111">To learn more, see [Troubleshoot installation issues for Microsoft Defender ATP for Mac](https://go.microsoft.com/fwlink/?linkid=2144615).</span></span>
