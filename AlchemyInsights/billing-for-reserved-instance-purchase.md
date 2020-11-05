---
title: Fakturering for å kjøpe reservert forekomst
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
- "6814"
- "9003552"
ms.openlocfilehash: 6cdcb5af27a475cc838eb434ff025eb18356360c
ms.sourcegitcommit: 1ac3474897abb7c4969e222f934294e05f468536
ms.translationtype: MT
ms.contentlocale: nb-NO
ms.lasthandoff: 10/30/2020
ms.locfileid: "48823164"
---
# <a name="billing-for-reserved-instance-purchase"></a><span data-ttu-id="3c43d-102">Fakturering for å kjøpe reservert forekomst</span><span class="sxs-lookup"><span data-stu-id="3c43d-102">Billing for Reserved Instance purchase</span></span>

<span data-ttu-id="3c43d-103">Det reserverte forekomst innkjøpet belastes betalings metoden knyttet til abonnementet du velger på kjøps tidspunktet.</span><span class="sxs-lookup"><span data-stu-id="3c43d-103">The reserved instance purchase is charged to the payment method tied to the subscription that you select at the time of purchase.</span></span> <span data-ttu-id="3c43d-104">Abonnements typen må være en Enterprise Agreement (tilbuds nummer: MS-AZR-0017P), Betal etter hvert-(tilbuds nummer: MS-AZR-0003P), Microsoft Customer Agreement eller CSP.</span><span class="sxs-lookup"><span data-stu-id="3c43d-104">The subscription type must be an enterprise agreement (offer number: MS-AZR-0017P), Pay-As-You-Go (offer number: MS-AZR-0003P), Microsoft Customer Agreement or CSP.</span></span>

- <span data-ttu-id="3c43d-105">For et bedrifts abonnement trekkes kostnadene fra registreringens penge forpliktelses saldo eller belastet som over</span><span class="sxs-lookup"><span data-stu-id="3c43d-105">For an enterprise subscription, the charges are deducted from the enrollment's monetary commitment balance or charged as overage</span></span>
- <span data-ttu-id="3c43d-106">For Betal etter hvert-abonnement faktureres kostnadene til kreditt kortet eller betalings metoden for fakturaer i abonnementet</span><span class="sxs-lookup"><span data-stu-id="3c43d-106">For Pay-As-You-Go subscription, the charges are billed to the credit card or invoice payment method on the subscription</span></span>

<span data-ttu-id="3c43d-107">**Kansellere reservasjon**</span><span class="sxs-lookup"><span data-stu-id="3c43d-107">**Cancelling Reservation**</span></span>

- <span data-ttu-id="3c43d-108">**Self-Service:** Du kan avbryte eller utveksle en reservert forekomst selv om du bruker [Azure-portalen](https://portal.azure.com/#blade/Microsoft_Azure_Reservations/ReservationsBrowseBlade).</span><span class="sxs-lookup"><span data-stu-id="3c43d-108">**Self-service:** You can cancel or exchange a reserved instance yourself using [Azure portal](https://portal.azure.com/#blade/Microsoft_Azure_Reservations/ReservationsBrowseBlade).</span></span> <span data-ttu-id="3c43d-109">Velg reservasjonen, og klikk på refusjon eller Exchange.</span><span class="sxs-lookup"><span data-stu-id="3c43d-109">Select the reservation and click on refund or exchange.</span></span> <span data-ttu-id="3c43d-110">Vær oppmerksom på at du må ha eier tilgang til reservasjons ordren til Exchange eller refusjon.</span><span class="sxs-lookup"><span data-stu-id="3c43d-110">Note that you must have owner access on the Reservation Order to exchange or refund.</span></span> <span data-ttu-id="3c43d-111">Bare tilgang til reservasjonen vil ikke la deg fortsette med refusjon eller Exchange.</span><span class="sxs-lookup"><span data-stu-id="3c43d-111">Access to only the Reservation will not let you proceed with refund or exchange.</span></span> <span data-ttu-id="3c43d-112">Be eieren av reservasjons ordren om å gi deg eier tilgang til reservasjons ordren</span><span class="sxs-lookup"><span data-stu-id="3c43d-112">Ask the Reservation Order owner to give you owner access to the Reservation Order</span></span>
- <span data-ttu-id="3c43d-113">**Exchange-policy:** Du kan utveksle en reservasjon for en annen reservasjon av samme type – det er **ingen straffer** om reserverings utveksling.</span><span class="sxs-lookup"><span data-stu-id="3c43d-113">**Exchange policy:** You can exchange a reservation for another reservation of the same type – there are **no penalties** on reservation exchange.</span></span> <span data-ttu-id="3c43d-114">Den totale forpliktelsen med ny reservasjon må være større enn summen av beløp som er omsluttet av prochanged reservat ion, og de månedlige betalings betalingene (Hvis dette gjelder)</span><span class="sxs-lookup"><span data-stu-id="3c43d-114">The total commitment with new reservation should be greater than the sum of exchanged reservation’s refund amount and the future monthly payments (if applicable)</span></span>
- <span data-ttu-id="3c43d-115">**Refusjons policy:** Summen av refundering og annullerte fremtidige betalinger kan ikke overskride $50 000 KRONER i et rullende vindu på 12 måneder.</span><span class="sxs-lookup"><span data-stu-id="3c43d-115">**Refund policy:** Sum of refund and the cancelled future payments cannot exceed $50,000 USD in a 12-month rolling window.</span></span> <span data-ttu-id="3c43d-116">Vi **lader for øyeblikket ikke noen straffer** på refunderinger, men kan belaste det på fremtidige tilbake betalinger</span><span class="sxs-lookup"><span data-stu-id="3c43d-116">We are **currently not charging any penalty** on refunds but could charge it on future refunds</span></span>

<span data-ttu-id="3c43d-117">**Unntak:** Selv betjent Exchange og Cancel-funksjonen er ikke tilgjengelig for amerikanske Enterprise Agreement-kunder</span><span class="sxs-lookup"><span data-stu-id="3c43d-117">**Exceptions:** Self-service exchange and cancel capability isn't available for US Government Enterprise Agreement customers</span></span>

- <span data-ttu-id="3c43d-118">Støtte for **API/PS/CLI** er ikke tilgjengelig for annulleringer og refusjoner [selv betjening og refusjon for Azure reserveringer](https://docs.microsoft.com/azure/cost-management-billing/reservations/exchange-and-refund-azure-reservations?WT.mc_id=Portal-Microsoft_Azure_Support)</span><span class="sxs-lookup"><span data-stu-id="3c43d-118">**API / PS / CLI** support is not available for cancellation and refunds [Self-service exchanges and refunds for Azure Reservations](https://docs.microsoft.com/azure/cost-management-billing/reservations/exchange-and-refund-azure-reservations?WT.mc_id=Portal-Microsoft_Azure_Support)</span></span>
- <span data-ttu-id="3c43d-119">Selv betjent Exchange og Cancel-funksjonen er ikke tilgjengelig for amerikanske Enterprise Agreement-kunder.</span><span class="sxs-lookup"><span data-stu-id="3c43d-119">Self-service exchange and cancel capability isn't available for US Government Enterprise Agreement customers.</span></span> <span data-ttu-id="3c43d-120">Andre US-myndighets abonnements typer, inkludert Betal etter hvert-og kryptografi tjeneste støttes</span><span class="sxs-lookup"><span data-stu-id="3c43d-120">Other US Government subscription types including Pay-As-You-Go and CSP are supported</span></span>

<span data-ttu-id="3c43d-121">Finn ut mer: [hvordan retur-og Exchange-transaksjoner behandles](https://docs.microsoft.com/azure/billing/billing-azure-reservations-self-service-exchange-and-refund?WT.mc_id=Portal-Microsoft_Azure_Support#how-return-and-exchange-transactions-are-processed) Finn ut mer: [policyer for Exchange og refusjon](https://docs.microsoft.com/azure/billing/billing-azure-reservations-self-service-exchange-and-refund?WT.mc_id=Portal-Microsoft_Azure_Support#exchange-policies) andre spørsmål: [gå til reserverte forekomst dokumenter](https://docs.microsoft.com/azure/billing/billing-save-compute-costs-reservations?WT.mc_id=Portal-Microsoft_Azure_Support)</span><span class="sxs-lookup"><span data-stu-id="3c43d-121">Learn more : [How return and exchange transactions are processed](https://docs.microsoft.com/azure/billing/billing-azure-reservations-self-service-exchange-and-refund?WT.mc_id=Portal-Microsoft_Azure_Support#how-return-and-exchange-transactions-are-processed) Learn more : [Exchange and Refund policies](https://docs.microsoft.com/azure/billing/billing-azure-reservations-self-service-exchange-and-refund?WT.mc_id=Portal-Microsoft_Azure_Support#exchange-policies) Other questions: [Visit reserved instance docs](https://docs.microsoft.com/azure/billing/billing-save-compute-costs-reservations?WT.mc_id=Portal-Microsoft_Azure_Support)</span></span>

<span data-ttu-id="3c43d-122">**Utveksle en eksisterende reservert forekomst (selv betjening)**</span><span class="sxs-lookup"><span data-stu-id="3c43d-122">**Exchange an existing reserved instance (Self-service)**</span></span>

<span data-ttu-id="3c43d-123">Du kan utveksle en reservasjon for en annen reservasjon av samme type.</span><span class="sxs-lookup"><span data-stu-id="3c43d-123">You can exchange a reservation for another reservation of the same type.</span></span> <span data-ttu-id="3c43d-124">Du kan også refundere en reservasjon på opptil $50 000 KRONER per år hvis du ikke trenger den lenger.</span><span class="sxs-lookup"><span data-stu-id="3c43d-124">You can also refund a reservation, up to $50,000 USD per year, if you no longer need it.</span></span> <span data-ttu-id="3c43d-125">Selv betjent Exchange og Cancel-funksjonen er ikke tilgjengelig for amerikanske Enterprise Agreement-kunder.</span><span class="sxs-lookup"><span data-stu-id="3c43d-125">Self-service exchange and cancel capability isn't available for US Government Enterprise Agreement customers.</span></span> <span data-ttu-id="3c43d-126">Andre US-offentlige abonnements typer, inkludert Betal etter hvert-og kryptografi tjeneste støttes.</span><span class="sxs-lookup"><span data-stu-id="3c43d-126">Other US Government subscription types including Pay-As-You-Go and CSP are supported.</span></span> <span data-ttu-id="3c43d-127">Du må ha eier tilgang til reservasjons ordren for å kunne utveksle eller refundere en eksisterende reservasjon.</span><span class="sxs-lookup"><span data-stu-id="3c43d-127">You must have owner access on the Reservation Order to exchange or refund an existing reservation.</span></span>

<span data-ttu-id="3c43d-128">Følgende Fremgangs måte fører til hvordan du kan fullføre transaksjonen</span><span class="sxs-lookup"><span data-stu-id="3c43d-128">The following steps will guide on the procedure to complete the transaction</span></span>

<span data-ttu-id="3c43d-129">1. Logg deg på [Azure-portalen](https://portal.azure.com/#blade/Microsoft_Azure_Reservations/ReservationsBrowseBlade).</span><span class="sxs-lookup"><span data-stu-id="3c43d-129">1.Log in to your [Azure portal](https://portal.azure.com/#blade/Microsoft_Azure_Reservations/ReservationsBrowseBlade).</span></span> <span data-ttu-id="3c43d-130">Velg reservasjonene du vil refundere, og klikk **Exchange** 2. Velg det virtuelle produktet du vil kjøpe, og skriv inn et antall.</span><span class="sxs-lookup"><span data-stu-id="3c43d-130">Select the reservations that you want to refund and click **Exchange** 2.Select the VM product that you want to purchase and type a quantity.</span></span> <span data-ttu-id="3c43d-131">Kontroller at den nye kjøps summen er mer enn den returnerte summen [avgjør riktig størrelse før du kjøper](https://docs.microsoft.com/azure/virtual-machines/windows/prepay-reserved-vm-instances?WT.mc_id=Portal-Microsoft_Azure_Support#determine-the-right-vm-size-before-you-buy).</span><span class="sxs-lookup"><span data-stu-id="3c43d-131">Make sure that the new purchase total is more than the return total [Determine the right size before you purchase](https://docs.microsoft.com/azure/virtual-machines/windows/prepay-reserved-vm-instances?WT.mc_id=Portal-Microsoft_Azure_Support#determine-the-right-vm-size-before-you-buy).</span></span>
<span data-ttu-id="3c43d-132">3. se gjennom og Fullfør transaksjonen</span><span class="sxs-lookup"><span data-stu-id="3c43d-132">3.Review and complete the transaction</span></span>

<span data-ttu-id="3c43d-133">**Refusjon for en reservert forekomst**</span><span class="sxs-lookup"><span data-stu-id="3c43d-133">**Refund for a reserved instance**</span></span>

<span data-ttu-id="3c43d-134">Hvis du vil refundere en reservasjon, går du til **reservasjons detaljer** og klikker **refusjon**</span><span class="sxs-lookup"><span data-stu-id="3c43d-134">To refund a reservation, go to **Reservation Details** and click **Refund**</span></span>

<span data-ttu-id="3c43d-135">**Pro-klassifisert for pengene:**</span><span class="sxs-lookup"><span data-stu-id="3c43d-135">**Pro-rated refund:**</span></span>

<span data-ttu-id="3c43d-136">**Eksempler på forhold og minimums krav for refusjon og utveksling** Forskudds reservasjon, eksempel:</span><span class="sxs-lookup"><span data-stu-id="3c43d-136">**Pro-ration and minimum requirement examples for refund and exchange** Upfront reservation example:</span></span>

- <span data-ttu-id="3c43d-137">Du kjøper en langsiktig RI for $120 på 1. januar</span><span class="sxs-lookup"><span data-stu-id="3c43d-137">You purchase a one-year term RI for $120 on January 1</span></span>
- <span data-ttu-id="3c43d-138">I syvende sjuende vil du refundere eller utveksle denne reservasjonen</span><span class="sxs-lookup"><span data-stu-id="3c43d-138">On April 7th you want to refund or exchange this reservation</span></span>
- <span data-ttu-id="3c43d-139">Siden reservasjonen er live i 97 dager, får du (1-97/365) \* $120 tilbake.</span><span class="sxs-lookup"><span data-stu-id="3c43d-139">Since the reservation has been live for 97 days, you will get (1-97/365) \* $120 back.</span></span> <span data-ttu-id="3c43d-140">(for eksempel $88,1).</span><span class="sxs-lookup"><span data-stu-id="3c43d-140">(i.e. $88.1).</span></span> <span data-ttu-id="3c43d-141">Det er for øyeblikket ingen straff for refunderinger</span><span class="sxs-lookup"><span data-stu-id="3c43d-141">There is currently no penalty on refunds</span></span>
- <span data-ttu-id="3c43d-142">Hvis du utveksler, må det nye kjøpet være større enn $88,1</span><span class="sxs-lookup"><span data-stu-id="3c43d-142">If exchanging, your new purchase should be greater than $88.1</span></span>
- <span data-ttu-id="3c43d-143">Det er ingen straff for påfylling for øyeblikket</span><span class="sxs-lookup"><span data-stu-id="3c43d-143">There is no penalty on refunds currently</span></span>

<span data-ttu-id="3c43d-144">**Eksempel på reservasjon av fakturerings plan:**</span><span class="sxs-lookup"><span data-stu-id="3c43d-144">**Billing plan reservation example:**</span></span>

- <span data-ttu-id="3c43d-145">Du kjøper en langsiktig RI for $10 per måned</span><span class="sxs-lookup"><span data-stu-id="3c43d-145">You purchase a one-year term RI for $10 per month</span></span>
- <span data-ttu-id="3c43d-146">I syvende sjuende vil du refundere eller utveksle denne reservasjonen</span><span class="sxs-lookup"><span data-stu-id="3c43d-146">On April 7th you want to refund or exchange this reservation</span></span>
- <span data-ttu-id="3c43d-147">Siden den siste betalingen skjedde 7 dager, får du (1-7/31) \* $10 tilbake.</span><span class="sxs-lookup"><span data-stu-id="3c43d-147">Since the last payment happened 7 days, you will get (1-7/31) \* $10 back.</span></span> <span data-ttu-id="3c43d-148">(for eksempel $7,74)</span><span class="sxs-lookup"><span data-stu-id="3c43d-148">(i.e. $7.74)</span></span>
- <span data-ttu-id="3c43d-149">Fremtidige betalinger som ble avbrutt er $80.</span><span class="sxs-lookup"><span data-stu-id="3c43d-149">The future payments cancelled are $ 80.</span></span> <span data-ttu-id="3c43d-150">Det er for øyeblikket ingen straff for refunderinger</span><span class="sxs-lookup"><span data-stu-id="3c43d-150">There is currently no penalty on refunds</span></span>
- <span data-ttu-id="3c43d-151">Denne annulleringen vil trekke $87,74 fra deg er grensen på $50 000-refundering</span><span class="sxs-lookup"><span data-stu-id="3c43d-151">This cancellation will deduct $87.74 from you’re the $50,000 refund limit</span></span>
- <span data-ttu-id="3c43d-152">Hvis du utveksler, må den totale verdien for nytt Kjøp være større enn $87,74</span><span class="sxs-lookup"><span data-stu-id="3c43d-152">If exchanging, the total value of new purchase should be greater than $87.74</span></span>

<span data-ttu-id="3c43d-153">**Kan ikke se fakturaen for den siste fakturerings perioden**</span><span class="sxs-lookup"><span data-stu-id="3c43d-153">**Unable to see invoice for the last billing period**</span></span>

<span data-ttu-id="3c43d-154">Noen mulige årsaker til at du kanskje ikke ser en faktura:</span><span class="sxs-lookup"><span data-stu-id="3c43d-154">Some possible reasons you might not see an invoice:</span></span>

- <span data-ttu-id="3c43d-155">Du har et månedlig kredit beløp med abonnementet du ikke har overskredet, eller du har en gratis prøve periode.</span><span class="sxs-lookup"><span data-stu-id="3c43d-155">You have a monthly credit amount with your subscription that you didn't exceed or you have a Free Trial.</span></span> <span data-ttu-id="3c43d-156">En faktura genereres bare når du skylder penger</span><span class="sxs-lookup"><span data-stu-id="3c43d-156">An invoice is only generated when you owe money</span></span>
- <span data-ttu-id="3c43d-157">Det er mindre enn 30 dager fra dagen du abonnerer på Azure</span><span class="sxs-lookup"><span data-stu-id="3c43d-157">It's less than 30 days from the day you subscribed to Azure</span></span>
- <span data-ttu-id="3c43d-158">Fakturaen er ennå ikke generert.</span><span class="sxs-lookup"><span data-stu-id="3c43d-158">The invoice isn't generated yet.</span></span> <span data-ttu-id="3c43d-159">Vente til slutten av fakturerings perioden</span><span class="sxs-lookup"><span data-stu-id="3c43d-159">Wait until the end of the billing period</span></span>
- <span data-ttu-id="3c43d-160">Hvis du ikke er konto administrator, kan det hende at eldre fakturaer ikke er tilgjengelige for deg</span><span class="sxs-lookup"><span data-stu-id="3c43d-160">If you're not the Account Administrator, older invoices may not be available to you</span></span>

<span data-ttu-id="3c43d-161">**Last ned fakturaen fra Azure-portalen (PDF)**</span><span class="sxs-lookup"><span data-stu-id="3c43d-161">**Download your invoice from Azure portal (.pdf)**</span></span>

- <span data-ttu-id="3c43d-162">Velg abonnementet fra [abonnementer](https://portal.azure.com/#blade/Microsoft_Azure_Billing/SubscriptionsBlade) -siden i Azure-portalen som [en bruker med tilgang til fakturaer](https://docs.microsoft.com/azure/billing/billing-manage-access?WT.mc_id=Portal-Microsoft_Azure_Support)</span><span class="sxs-lookup"><span data-stu-id="3c43d-162">Select your subscription from the [Subscriptions](https://portal.azure.com/#blade/Microsoft_Azure_Billing/SubscriptionsBlade) page in Azure portal as [a user with access to invoices](https://docs.microsoft.com/azure/billing/billing-manage-access?WT.mc_id=Portal-Microsoft_Azure_Support)</span></span>
- <span data-ttu-id="3c43d-163">Velg **fakturaer**</span><span class="sxs-lookup"><span data-stu-id="3c43d-163">Select **Invoices**</span></span>
- <span data-ttu-id="3c43d-164">Klikk **Last ned faktura** for å vise en kopi av PDF-fakturaen.</span><span class="sxs-lookup"><span data-stu-id="3c43d-164">Click **Download Invoice** to view a copy of your PDF invoice.</span></span> <span data-ttu-id="3c43d-165">Hvis det **ikke er tilgjengelig** , kan du se [Hvorfor kan jeg ikke se en faktura for den siste fakturerings perioden?](https://docs.microsoft.com/azure/billing/billing-download-azure-invoice-daily-usage-date?WT.mc_id=Portal-Microsoft_Azure_Support#noinvoice)</span><span class="sxs-lookup"><span data-stu-id="3c43d-165">If it says **Not available** , see [Why don't I see an invoice for the last billing period?](https://docs.microsoft.com/azure/billing/billing-download-azure-invoice-daily-usage-date?WT.mc_id=Portal-Microsoft_Azure_Support#noinvoice)</span></span>

<span data-ttu-id="3c43d-166">**Motta fakturaen i e-post (PDF)**</span><span class="sxs-lookup"><span data-stu-id="3c43d-166">**Receive your invoice in email (.pdf)**</span></span>

- <span data-ttu-id="3c43d-167">Velg abonnementet ditt fra [abonnementer](https://portal.azure.com/#blade/Microsoft_Azure_Billing/SubscriptionsBlade) -siden.</span><span class="sxs-lookup"><span data-stu-id="3c43d-167">Select your subscription from the [Subscriptions](https://portal.azure.com/#blade/Microsoft_Azure_Billing/SubscriptionsBlade) page.</span></span> <span data-ttu-id="3c43d-168">Klikk **fakturaer** og send deretter e-post til fakturaen min</span><span class="sxs-lookup"><span data-stu-id="3c43d-168">Click **Invoices** then Email my invoice</span></span>
- <span data-ttu-id="3c43d-169">Klikk **på Velg i** og godta vilkårene.</span><span class="sxs-lookup"><span data-stu-id="3c43d-169">Click **opt in** and accept the terms.</span></span> <span data-ttu-id="3c43d-170">Du må velge for hvert abonnement du eier</span><span class="sxs-lookup"><span data-stu-id="3c43d-170">You will have to opt in for each subscription you own</span></span>

<span data-ttu-id="3c43d-171">Obs! hvis du ikke får en e-post når du følger trinnene, må du kontrollere at e-postadressen din er riktig i [kommunikasjons innstillingene i profilen din](https://account.windowsazure.com/profile)</span><span class="sxs-lookup"><span data-stu-id="3c43d-171">Note: If you don't get an email after following the steps, make sure your email address is correct in the [communication preferences on your profile](https://account.windowsazure.com/profile)</span></span>

<span data-ttu-id="3c43d-172">**Last ned bruks dataene fra Azure-portalen**</span><span class="sxs-lookup"><span data-stu-id="3c43d-172">**Download your usage data from the Azure portal**</span></span>

- <span data-ttu-id="3c43d-173">Logg på [Azure Account Center](https://account.windowsazure.com/Subscriptions) som [konto administrator](https://docs.microsoft.com/azure/billing/billing-subscription-transfer?WT.mc_id=Portal-Microsoft_Azure_Support#whoisaa)</span><span class="sxs-lookup"><span data-stu-id="3c43d-173">Sign into the [Azure Account Center](https://account.windowsazure.com/Subscriptions) as the [Account Admin](https://docs.microsoft.com/azure/billing/billing-subscription-transfer?WT.mc_id=Portal-Microsoft_Azure_Support#whoisaa)</span></span>
- <span data-ttu-id="3c43d-174">Velg abonnementet du vil ha informasjon om faktura og bruk</span><span class="sxs-lookup"><span data-stu-id="3c43d-174">Select the subscription for which you want the invoice and usage information</span></span>
- <span data-ttu-id="3c43d-175">Velg **fakturerings Logg**</span><span class="sxs-lookup"><span data-stu-id="3c43d-175">Select **Billing History**</span></span>
- <span data-ttu-id="3c43d-176">Velg **Vis gjeldende utdrag** for å se en beregning av kostnadene dine på det tidspunktet estimatet ble generert</span><span class="sxs-lookup"><span data-stu-id="3c43d-176">Select **View Current Statement** to see an estimate of your charges at the time the estimate was generated</span></span>
- <span data-ttu-id="3c43d-177">Velg **Last ned bruk** for å laste ned de daglige bruks dataene som en CSV-fil.</span><span class="sxs-lookup"><span data-stu-id="3c43d-177">Select **Download Usage** to download the daily usage data as a CSV file.</span></span> <span data-ttu-id="3c43d-178">Hvis du ser to versjoner tilgjengelig, kan du laste ned versjon 2</span><span class="sxs-lookup"><span data-stu-id="3c43d-178">If you see two versions available, download version 2</span></span>

<span data-ttu-id="3c43d-179">Andre spørsmål: [gå til reserverte forekomst dokumenter](https://docs.microsoft.com/azure/billing/billing-save-compute-costs-reservations?WT.mc_id=Portal-Microsoft_Azure_Support)</span><span class="sxs-lookup"><span data-stu-id="3c43d-179">Other questions: [Visit reserved instance docs](https://docs.microsoft.com/azure/billing/billing-save-compute-costs-reservations?WT.mc_id=Portal-Microsoft_Azure_Support)</span></span>

<span data-ttu-id="3c43d-180">**Anbefalte dokumenter**</span><span class="sxs-lookup"><span data-stu-id="3c43d-180">**Recommended Documents**</span></span>

- [<span data-ttu-id="3c43d-181">Grunnleggende om fakturering</span><span class="sxs-lookup"><span data-stu-id="3c43d-181">Billing basics</span></span>](https://docs.microsoft.com/partner-center/billing-basics/?WT.mc_id=Portal-Microsoft_Azure_Support)
- [<span data-ttu-id="3c43d-182">Forstå hvordan rabatten for reservert forekomst brukes</span><span class="sxs-lookup"><span data-stu-id="3c43d-182">Understand how the Reserved Instance discount is applied</span></span>](https://docs.microsoft.com/azure/billing/billing-understand-vm-reservation-charges/?WT.mc_id=Portal-Microsoft_Azure_Support)
- [<span data-ttu-id="3c43d-183">Last ned eller Vis faktura-og daglig bruks data for Azure-fakturering</span><span class="sxs-lookup"><span data-stu-id="3c43d-183">Download or view your Azure billing invoice and daily usage data</span></span>](https://docs.microsoft.com/azure/billing/billing-download-azure-invoice-daily-usage-date?WT.mc_id=Portal-Microsoft_Azure_Support)
- [<span data-ttu-id="3c43d-184">Forstå hvordan rabatten for reservert forekomst brukes</span><span class="sxs-lookup"><span data-stu-id="3c43d-184">Understand how the Reserved Instance discount is applied</span></span>](https://docs.microsoft.com/azure/billing/billing-understand-vm-reservation-charges/?WT.mc_id=Portal-Microsoft_Azure_Support)
- [<span data-ttu-id="3c43d-185">Forstå reservert forekomst av bruk av abonnementet for Betal etter hvert</span><span class="sxs-lookup"><span data-stu-id="3c43d-185">Understand Reserved Instance usage for your Pay-As-You-Go subscription</span></span>](https://docs.microsoft.com/azure/billing/billing-understand-reserved-instance-usage/?WT.mc_id=Portal-Microsoft_Azure_Support)
- [<span data-ttu-id="3c43d-186">Forstå reservert forekomst av bruk av bedrifts registrering</span><span class="sxs-lookup"><span data-stu-id="3c43d-186">Understand Reserved Instance usage for your Enterprise enrollment</span></span>](https://docs.microsoft.com/azure/billing/billing-understand-reserved-instance-usage-ea/?WT.mc_id=Portal-Microsoft_Azure_Support)
- [<span data-ttu-id="3c43d-187">Program vare kostnader i Windows som ikke er inkludert i reserverte forekomster</span><span class="sxs-lookup"><span data-stu-id="3c43d-187">Windows software costs not included with Reserved instances</span></span>](https://docs.microsoft.com/azure/billing/billing-reserved-instance-windows-software-costs/?WT.mc_id=Portal-Microsoft_Azure_Support)
- [<span data-ttu-id="3c43d-188">Reserverte forekomster i partner sentral Sky løsning leverandør (CSP) program</span><span class="sxs-lookup"><span data-stu-id="3c43d-188">Reserved Instances in Partner Central Cloud Solution Provider (CSP) program</span></span>](https://docs.microsoft.com/partner-center/azure-reservations/?WT.mc_id=Portal-Microsoft_Azure_Support)