---
title: Se etter videresending av adresser på postbokser
ms.author: v-aiyengar
author: AshaIyengar21
manager: dansimp
ms.date: 02/17/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9002486"
- "7524"
ms.openlocfilehash: 3abd45230360c61ecb62e4b7a39d1b0b547271fc
ms.sourcegitcommit: db908b3da2c7a6508a77bf4f2c80afb294fadbd1
ms.translationtype: MT
ms.contentlocale: nb-NO
ms.lasthandoff: 03/29/2021
ms.locfileid: "51403320"
---
# <a name="check-for-forwarding-addresses-on-mailboxes"></a><span data-ttu-id="6c6a8-102">Se etter videresending av adresser på postbokser</span><span class="sxs-lookup"><span data-stu-id="6c6a8-102">Check for forwarding addresses on mailboxes</span></span>

<span data-ttu-id="6c6a8-103">Noen ganger videresender hackere brukernes e-postmeldinger til seg selv, så først ser vi etter videresending av adresser og regler på postboksen.</span><span class="sxs-lookup"><span data-stu-id="6c6a8-103">Sometimes hackers forward users' email messages to themselves, so first we'll check for forwarding addresses and rules on the mailbox.</span></span> <span data-ttu-id="6c6a8-104">Deretter kontrollerer vi overvåkingsloggene.</span><span class="sxs-lookup"><span data-stu-id="6c6a8-104">Then we'll check the audit logs.</span></span> <span data-ttu-id="6c6a8-105">Slik ser du etter videresendingsadresser:</span><span class="sxs-lookup"><span data-stu-id="6c6a8-105">Here's how to check for forwarding addresses:</span></span>

1. <span data-ttu-id="6c6a8-106">Velg **Brukere Aktive**  >  **brukere**.</span><span class="sxs-lookup"><span data-stu-id="6c6a8-106">Select **Users** > **Active users**.</span></span>
1. <span data-ttu-id="6c6a8-107">Velg brukeren der kontoen er kompromittert.</span><span class="sxs-lookup"><span data-stu-id="6c6a8-107">Select the user whose account has been compromised.</span></span>
1. <span data-ttu-id="6c6a8-108">Utvid E-postinnstillinger på undermenyen som **vises,** og klikk deretter **Rediger** for videresending av **e-post.**</span><span class="sxs-lookup"><span data-stu-id="6c6a8-108">In the flyout that appears, expand **Mail Settings**, and then click **Edit** for **Email forwarding**.</span></span>
1. <span data-ttu-id="6c6a8-109">Fjern eventuelle videresendingsadresser du ikke gjenkjenner.</span><span class="sxs-lookup"><span data-stu-id="6c6a8-109">Remove any forwarding addresses you don't recognize.</span></span>