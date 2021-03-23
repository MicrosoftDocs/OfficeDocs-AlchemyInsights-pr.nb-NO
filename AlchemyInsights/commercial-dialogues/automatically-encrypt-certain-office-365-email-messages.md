---
title: Kryptere bestemte Office 365-e-postmeldinger automatisk
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 02/24/2021
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000078"
- "7342"
ms.openlocfilehash: e4b2f4ffcacf03e145b4c6d5ff6e73a75cb7c184
ms.sourcegitcommit: 6312ee31561db36104f32282d019d069ede69174
ms.translationtype: MT
ms.contentlocale: nb-NO
ms.lasthandoff: 03/11/2021
ms.locfileid: "50749439"
---
# <a name="automatically-encrypt-certain-office-365-email-messages"></a><span data-ttu-id="7c5dd-102">Kryptere bestemte Office 365-e-postmeldinger automatisk</span><span class="sxs-lookup"><span data-stu-id="7c5dd-102">Automatically encrypt certain Office 365 email messages</span></span>

<span data-ttu-id="7c5dd-103">Du kan automatisk kryptere meldinger som brukere sender til bestemte eksterne personer eller organisasjoner.</span><span class="sxs-lookup"><span data-stu-id="7c5dd-103">You can automatically encrypt messages that users send to certain external people or organizations.</span></span> <span data-ttu-id="7c5dd-104">Hvis du vil gjøre dette, utfører du følgende trinn:</span><span class="sxs-lookup"><span data-stu-id="7c5dd-104">To do this, perform the following steps:</span></span>

1. <span data-ttu-id="7c5dd-105">Velg [e-postflyt i](https://outlook.office365.com/ecp/) **administrasjonssenteret for** Exchange > regler .</span><span class="sxs-lookup"><span data-stu-id="7c5dd-105">From the [Exchange admin center](https://outlook.office365.com/ecp/), choose **mail flow > rules**.</span></span> 
2. <span data-ttu-id="7c5dd-106">Klikk på **Nytt (+)-ikonet,** og klikk deretter Bruk Meldingskryptering og rettighetsbeskyttelse for **Office 365 på meldinger.**</span><span class="sxs-lookup"><span data-stu-id="7c5dd-106">Click the **New (+)** icon, and then click **Apply Office 365 Message Encryption and rights protection to messages**.</span></span>
3. <span data-ttu-id="7c5dd-107">Skriv **inn** et navn på regelen i Navn, for eksempel Krypter *meldinger som sendes til DrToniRamos@gmail.com*.</span><span class="sxs-lookup"><span data-stu-id="7c5dd-107">In **Name**, enter a name for the rule, such as *Encrypt messages sent to DrToniRamos@gmail.com*.</span></span>
4. <span data-ttu-id="7c5dd-108">I **Bruk denne regelen hvis** velger du Mottakeren > denne **personen**.</span><span class="sxs-lookup"><span data-stu-id="7c5dd-108">In **Apply this rule if**, choose **The recipient > is this person**.</span></span> 
5. <span data-ttu-id="7c5dd-109">Velg navnet **på** personen du vil at krypteringsregelen skal gjelde for, i Velg **medlemmer-vinduet,** og klikk deretter legg til .</span><span class="sxs-lookup"><span data-stu-id="7c5dd-109">In the **Select Members** window, select the name of the person you want the encryption rule to apply to, and then click **add**.</span></span> 
6. <span data-ttu-id="7c5dd-110">Når du er ferdig med å legge til brukere, klikker du **OK**.</span><span class="sxs-lookup"><span data-stu-id="7c5dd-110">When you're done adding users, click **OK**.</span></span>
7. <span data-ttu-id="7c5dd-111">Klikk Velg et ved siden **av** Gjør **følgende-feltet.**</span><span class="sxs-lookup"><span data-stu-id="7c5dd-111">Next to the **Do the following** field, click **Select one**.</span></span> 
8. <span data-ttu-id="7c5dd-112">Velg Krypter på rullegardinmenyen for **RMS-malen,** og klikk deretter **OK**.</span><span class="sxs-lookup"><span data-stu-id="7c5dd-112">In the **RMS template** drop-down menu, select **Encrypt**, and then click **OK**.</span></span> <span data-ttu-id="7c5dd-113">(Hvis du ikke ser dette alternativet, betyr det at planen ikke inkluderer automatisk kryptering.</span><span class="sxs-lookup"><span data-stu-id="7c5dd-113">(If you don't see this option, it means your plan doesn't include automatic encryption.</span></span> <span data-ttu-id="7c5dd-114">Men du kan legge den til!)</span><span class="sxs-lookup"><span data-stu-id="7c5dd-114">But you can add it!)</span></span>
9. <span data-ttu-id="7c5dd-115">Velg et valgfritt utvalg (fra en liste over valgfrie valg som du kan gjøre på dette tidspunktet, hvorav mange kan stå igjen med standardinnstillingen for enkelhet).</span><span class="sxs-lookup"><span data-stu-id="7c5dd-115">Choose any optional selection (from a list of optional selections that you can make at this point, many of which can be left with the default setting for simplicity).</span></span>
10. <span data-ttu-id="7c5dd-116">Klikk på **Lagre**.</span><span class="sxs-lookup"><span data-stu-id="7c5dd-116">Click **Save**.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="7c5dd-117">Du kan alltid komme tilbake og redigere denne regelen senere.</span><span class="sxs-lookup"><span data-stu-id="7c5dd-117">You can always come back and edit this rule later.</span></span>

<span data-ttu-id="7c5dd-118">Hvis du vil ha mer informasjon om hvordan du oppretter regler for kryptering, kan du se Definere regler for e-postflyt for [å kryptere e-postmeldinger i Office 365](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email).</span><span class="sxs-lookup"><span data-stu-id="7c5dd-118">For more information about creating rules for encryption, see [Define mail flow rules to encrypt email messages in Office 365](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email).</span></span>
