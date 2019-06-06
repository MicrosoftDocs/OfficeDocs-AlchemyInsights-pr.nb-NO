---
title: Ytelse problemer-SharePoint eller OneDrive
ms.author: kirks
author: Techwriter40
ms.date: 1/3/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 9225ec0f-771f-4d7a-8157-e188953107aa
ms.openlocfilehash: 3b04e811b69a1f9d652abbd603c3c09df068480c
ms.sourcegitcommit: 6d341637dbb14e90726a1ce1d68f077ace9bb765
ms.translationtype: MT
ms.contentlocale: nb-NO
ms.lasthandoff: 06/04/2019
ms.locfileid: "34719525"
---
# <a name="sharepoint-or-onedrive-slow-inaccessible-or-unavailable-for-multiple-users"></a><span data-ttu-id="a36fb-102">SharePoint eller OneDrive langsom, utilgjengelig eller ikke tilgjengelig for flere brukere</span><span class="sxs-lookup"><span data-stu-id="a36fb-102">SharePoint or OneDrive Slow, Inaccessible or Unavailable for Multiple Users</span></span>

<span data-ttu-id="a36fb-103">Hvis et OneDrive eller SharePoint-område ikke er tilgjengelig for flere brukere som tidligere hadde tilgang, kan det være et problem med tjenesten midlertidig.</span><span class="sxs-lookup"><span data-stu-id="a36fb-103">If a OneDrive or SharePoint site is not available to multiple users who previously had access, there may be a temporary service issue.</span></span> <span data-ttu-id="a36fb-104">[Kontroller service helse instrumentbordet](https://portal.office.com/adminportal/home#/servicehealth).</span><span class="sxs-lookup"><span data-stu-id="a36fb-104">[Check the service health dashboard](https://portal.office.com/adminportal/home#/servicehealth).</span></span>

## <a name="add-and-license-the-user"></a><span data-ttu-id="a36fb-105">Legg til og lisensier brukeren</span><span class="sxs-lookup"><span data-stu-id="a36fb-105">Add and license the user</span></span>

<span data-ttu-id="a36fb-106">Forsikre deg om at du [tilordne lisenser til brukere i Office 365 for bedrifter](https://docs.microsoft.com/en-us/office365/admin/subscriptions-and-billing/assign-licenses-to-users?view=o365-worldwide&amp;tabs=One).</span><span class="sxs-lookup"><span data-stu-id="a36fb-106">Ensure that you [Assign licenses to users in Office 365 for business](https://docs.microsoft.com/en-us/office365/admin/subscriptions-and-billing/assign-licenses-to-users?view=o365-worldwide&amp;tabs=One).</span></span>


## <a name="assign-permissions"></a><span data-ttu-id="a36fb-107">Tilordne tillatelser</span><span class="sxs-lookup"><span data-stu-id="a36fb-107">Assign Permissions</span></span>

<span data-ttu-id="a36fb-108">Hvis brukeren har blitt tilordnet en lisens for Sharepoint og fortsatt mottar meldingen Ingen tilgang, pass på at de har [riktig tillatelsesnivå](https://docs.microsoft.com/en-us/sharepoint/understanding-permission-levels) som er tilordnet.</span><span class="sxs-lookup"><span data-stu-id="a36fb-108">If the user has been assigned a Sharepoint license and is still receiving an access denied message, please ensure they have the [appropriate permission level](https://docs.microsoft.com/en-us/sharepoint/understanding-permission-levels) assigned.</span></span>

## <a name="consider-using-the-access-request-feature"></a><span data-ttu-id="a36fb-109">Vurder å bruke funksjonen for forespørsel</span><span class="sxs-lookup"><span data-stu-id="a36fb-109">Consider using the access request feature</span></span>

<span data-ttu-id="a36fb-110">[Forespørsel om funksjonen](https://support.office.com/en-us/article/Set-up-and-manage-access-requests-94B26E0B-2822-49D4-929A-8455698654B3) kan personer til å be om tilgang til innhold som de ikke har tillatelse til å se.</span><span class="sxs-lookup"><span data-stu-id="a36fb-110">The [access request feature](https://support.office.com/en-us/article/Set-up-and-manage-access-requests-94B26E0B-2822-49D4-929A-8455698654B3) allows people to request access to content that they do not currently have permission to see.</span></span>

## <a name="allow-custom-script-may-cause-access-denied-issues"></a><span data-ttu-id="a36fb-111">Tillat egendefinert skript kan føre til problemer med tilgang</span><span class="sxs-lookup"><span data-stu-id="a36fb-111">Allow custom script may cause access denied issues</span></span>

<span data-ttu-id="a36fb-112">Det finnes visse scenarier der funksjonen *Tillat egendefinert skript* kan presentere en tilgang.</span><span class="sxs-lookup"><span data-stu-id="a36fb-112">There are certain scenarios where the *Allow custom script* feature may be presenting an access denied.</span></span> <span data-ttu-id="a36fb-113">For en liste over funksjoner som påvirkes, Sikkerhetsvurderinger og muligheten til å deaktivere funksjonen.</span><span class="sxs-lookup"><span data-stu-id="a36fb-113">For a list of features affected, security considerations and the ability to disable the feature.</span></span> <span data-ttu-id="a36fb-114">Besøk [Tillat eller forby egendefinert skript](https://docs.microsoft.com/en-us/sharepoint/allow-or-prevent-custom-script).</span><span class="sxs-lookup"><span data-stu-id="a36fb-114">Please visit [Allow or prevent custom script](https://docs.microsoft.com/en-us/sharepoint/allow-or-prevent-custom-script).</span></span>
