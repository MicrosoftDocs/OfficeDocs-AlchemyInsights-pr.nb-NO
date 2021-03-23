---
title: Løse problemer med å installere Windows 10-enheter eksternt til Microsoft Defender Advanced Threat Protection
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
ms.openlocfilehash: 5473d090f6d4680f9a62f34f943ac6cea53b2079
ms.sourcegitcommit: 6312ee31561db36104f32282d019d069ede69174
ms.translationtype: MT
ms.contentlocale: nb-NO
ms.lasthandoff: 03/11/2021
ms.locfileid: "50750037"
---
# <a name="remotely-fix-problems-with-onboarding-windows-10-devices-to-microsoft-defender-advanced-threat-protection"></a><span data-ttu-id="dfd61-102">Løse problemer med å installere Windows 10-enheter eksternt til Microsoft Defender Advanced Threat Protection</span><span class="sxs-lookup"><span data-stu-id="dfd61-102">Remotely fix problems with onboarding Windows 10 devices to Microsoft Defender Advanced Threat Protection</span></span>

<span data-ttu-id="dfd61-103">Hvis du har tilgang til den eksterne datamaskinen, følger du disse trinnene:</span><span class="sxs-lookup"><span data-stu-id="dfd61-103">If you can access the remote computer, follow these steps:</span></span>

1. <span data-ttu-id="dfd61-104">Last ned [diagnoseverktøyet for Klienttilkoblingsanalyse.](https://go.microsoft.com/fwlink/?linkid=2143466)</span><span class="sxs-lookup"><span data-stu-id="dfd61-104">Download the [Client Connectivity Analyzer](https://go.microsoft.com/fwlink/?linkid=2143466) diagnostic tool.</span></span>
2. <span data-ttu-id="dfd61-105">Pakk ut og kjør MDATPAnalyzer.cmd.</span><span class="sxs-lookup"><span data-stu-id="dfd61-105">Extract and run MDATPAnalyzer.cmd.</span></span>
3. <span data-ttu-id="dfd61-106">Finn diagnoseloggen i MDATPClientAnalyzerResult-mappen, som er den samme mappen der analyseverktøyet ble lastet ned.</span><span class="sxs-lookup"><span data-stu-id="dfd61-106">Locate the diagnostic log in the MDATPClientAnalyzerResult folder, which is the same folder where the Analyzer tool was downloaded.</span></span>
4. <span data-ttu-id="dfd61-107">Hvis du vil finne problemer med tilkoblings- eller Internett-proxy-innstillinger, kan du se gjennom loggfilen MDATPClientAnalyzer.txt.</span><span class="sxs-lookup"><span data-stu-id="dfd61-107">To find issues with connectivity or Internet proxy settings, review the log file MDATPClientAnalyzer.txt.</span></span>

<span data-ttu-id="dfd61-108">Hvis du vil ha mer informasjon, [kan du se Problemer med introduksjonsmaskiner](https://go.microsoft.com/fwlink/?linkid=2143634).</span><span class="sxs-lookup"><span data-stu-id="dfd61-108">To learn more, see [Issues with onboarding machines](https://go.microsoft.com/fwlink/?linkid=2143634).</span></span>