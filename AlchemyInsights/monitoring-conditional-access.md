---
title: Overvåke betinget tilgang
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: dcb86c54-769e-4832-9f88-bc45f1e5f36c
ms.openlocfilehash: 6083fc427e3791fdb0907198b525337a0c987c4e
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: nb-NO
ms.lasthandoff: 09/14/2020
ms.locfileid: "47702912"
---
# <a name="monitoring-conditional-access-for-exchange"></a><span data-ttu-id="6260e-102">Overvåke betinget tilgang for Exchange</span><span class="sxs-lookup"><span data-stu-id="6260e-102">Monitoring Conditional Access for Exchange</span></span>

<span data-ttu-id="6260e-103">Brukere som er rettet mot betinget tilgang, mottar en e-postvarsling hvis de ikke oppfyller organisasjonens tilgangs krav.</span><span class="sxs-lookup"><span data-stu-id="6260e-103">Users targeted with conditional access will receive a notification email if they do not meet your organization's access requirements.</span></span> <span data-ttu-id="6260e-104">Vi anbefaler en eller flere av følgende løsninger for å løse:</span><span class="sxs-lookup"><span data-stu-id="6260e-104">To resolve, we recommend one or more of the following solutions:</span></span>
  
- <span data-ttu-id="6260e-105">Hvis enheten er Presumed for å bli registrert, ber du brukeren om å gå til Firmaportal-appen og kontrollere at den vises i firma portalen.</span><span class="sxs-lookup"><span data-stu-id="6260e-105">If the device is presumed to be enrolled, advise the user to go to the Company Portal app and verify that it appears in the Company Portal.</span></span> <span data-ttu-id="6260e-106">Hvis den ikke gjør det, skal brukeren registrere enheten.</span><span class="sxs-lookup"><span data-stu-id="6260e-106">If it doesn't, the user should enroll the device.</span></span>
    
- <span data-ttu-id="6260e-107">I Azure-portalen går du **til \> enhets samsvar for Intune**.</span><span class="sxs-lookup"><span data-stu-id="6260e-107">In the Azure portal go to **Intune \> Device compliance**.</span></span> <span data-ttu-id="6260e-108">Under **skjerm** Klikk **enhets samsvar**.</span><span class="sxs-lookup"><span data-stu-id="6260e-108">Under **Monitor** click **Device compliance**.</span></span> <span data-ttu-id="6260e-109">Vis samsvars rapporten for enheten for å bekrefte at brukerens enhet er merket som kompatibel.</span><span class="sxs-lookup"><span data-stu-id="6260e-109">View your device compliance report to verify that the user's device is marked as compliant.</span></span> 
    
- <span data-ttu-id="6260e-110">I Azure-portalen går du **til \> enhets samsvar for Intune**.</span><span class="sxs-lookup"><span data-stu-id="6260e-110">In the Azure portal go to **Intune \> Device compliance**.</span></span> <span data-ttu-id="6260e-111">Klikk **policyer**under **Behandle**.</span><span class="sxs-lookup"><span data-stu-id="6260e-111">Under **Manage**, click **Policies**.</span></span> <span data-ttu-id="6260e-112">Kontroller at en profil er tilordnet til brukerens enhet i listen over samsvars policyer.</span><span class="sxs-lookup"><span data-stu-id="6260e-112">In the list of compliance policies, verify that a profile is assigned to your user's device.</span></span> <span data-ttu-id="6260e-113">Hvis ingen profil er tilordnet, vil ikke Intune kunne bekrefte enhetens samsvars status.</span><span class="sxs-lookup"><span data-stu-id="6260e-113">If no profile is assigned, then Intune will not be able to confirm the device's compliance status.</span></span> 
    
- <span data-ttu-id="6260e-114">Rediger brukerens tilordningen for betinget tilgang.</span><span class="sxs-lookup"><span data-stu-id="6260e-114">Edit the user's conditional access assignment.</span></span>
    
1. <span data-ttu-id="6260e-115">Gå til **Intune- \> \> policyer for betinget tilgang** i Azure-portalen</span><span class="sxs-lookup"><span data-stu-id="6260e-115">In the Azure portal go to **Intune \> Conditional access \> Policies**</span></span>
    
2. <span data-ttu-id="6260e-116">Velg en policy fra listen</span><span class="sxs-lookup"><span data-stu-id="6260e-116">Select a policy from the list</span></span>
    
3. <span data-ttu-id="6260e-117">Klikk **brukere og grupper**</span><span class="sxs-lookup"><span data-stu-id="6260e-117">Click **Users and groups**</span></span>
    
4. <span data-ttu-id="6260e-118">Hvis du vil angi en bestemt policy for noen, kan du legge dem til i **inkluderings** listen.</span><span class="sxs-lookup"><span data-stu-id="6260e-118">To target a certain policy at someone, add them to the **Include** list.</span></span> <span data-ttu-id="6260e-119">Hvis du vil sikre at en person utelates fra policyen, legger du dem til i **ekskluderings** listen.</span><span class="sxs-lookup"><span data-stu-id="6260e-119">To ensure that a person is omitted from the policy, add them to the **Exclude** list.</span></span> 
    
<span data-ttu-id="6260e-120">Les mer: [Slik overvåker du enheter for betinget tilgang](https://docs.microsoft.com/intune/conditional-access-exchange-monitor)</span><span class="sxs-lookup"><span data-stu-id="6260e-120">Read more: [How to Monitor Conditional Access devices](https://docs.microsoft.com/intune/conditional-access-exchange-monitor)</span></span>
  

