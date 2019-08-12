---
title: Preferenču izmantošana Office darbam ar Mac konfidencialitātes kontroles līdzekļu pārvaldībai
ms.author: danbrown
author: pbowden-msft
manager: laurawi
audience: ITPro
ms.topic: article
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection: Ent_O365
ms.custom:
- Ent_Office_ProPlus
- Ent_Office_Privacy
- Ent_Office_Mac
description: Nodrošina Office administratoriem informāciju par to, kā pārvaldīt konfidencialitātes kontroles līdzekļus Office darbam ar Mac.
hideEdit: true
ms.openlocfilehash: 01bb31f3b6c307ec1dc4762b54fea17185dcf27d
ms.sourcegitcommit: 0fd23324ba1364fa1f8dd1578adf25946adde90f
ms.translationtype: HT
ms.contentlocale: lv-LV
ms.lasthandoff: 08/07/2019
ms.locfileid: "36246298"
---
# <a name="use-preferences-to-manage-privacy-controls-for-office-for-mac"></a><span data-ttu-id="6611f-103">Preferenču izmantošana Office darbam ar Mac konfidencialitātes kontroles līdzekļu pārvaldībai</span><span class="sxs-lookup"><span data-stu-id="6611f-103">Use preferences to manage privacy controls for Office for Mac</span></span>

<span data-ttu-id="6611f-104">Sākot ar Office versiju 16.28 darbam ar Mac, ir jauni politikas iestatījumi, kuri nodrošina iespēju kontrolēt ar šo saistītus iestatījumus:</span><span class="sxs-lookup"><span data-stu-id="6611f-104">Starting with Version 1904 of Office 365 ProPlus, there are new policy settings that will allow you to control settings related to the following:</span></span>

- <span data-ttu-id="6611f-105">***Diagnostikas dati***, kas tiek apkopoti un nosūtīti korporācijai Microsoft par izmantoto Office klienta programmatūru.</span><span class="sxs-lookup"><span data-stu-id="6611f-105">***Diagnostic data*** that is collected and sent to Microsoft about Office client software being used</span></span>

- <span data-ttu-id="6611f-106">***Saistītie līdzekļi***, kas izmanto mākoņa funkcionalitāti, lai nodrošinātu uzlabotus Office līdzekļus jums un jūsu lietotājiem.</span><span class="sxs-lookup"><span data-stu-id="6611f-106">***Connected experiences*** that use cloud-based functionality to provide enhanced Office features to you and your users.</span></span>

<span data-ttu-id="6611f-107">Papildus pastāv jauns preferenču iestatījums, kas saistīts ar **Nepieciešamo datu paziņojumu** dialogu Microsoft AutoUpdate (MAU).</span><span class="sxs-lookup"><span data-stu-id="6611f-107">In addition, there is a new preference setting related to a **Required Data Notice** dialog for Microsoft AutoUpdate (MAU).</span></span>

<span data-ttu-id="6611f-108">Papildinformāciju par diagnostikas datiem un saistītajām darbībām skatiet rakstā [Pārskats par konfidencialitātes vadīklām](overview-privacy-controls.md).</span><span class="sxs-lookup"><span data-stu-id="6611f-108">For more information about diagnostic data and connected experiences, see [Overview of privacy controls](overview-privacy-controls.md).</span></span>

> [!NOTE]
> <span data-ttu-id="6611f-109">Papildinformāciju par līdzīgu Office iestatījumu izmantošanu datoros, kuros darbojas ar Windows operētājsistēmu, skatiet rakstā [Politikas iestatījumu izmantošana Office 365 ProPlus konfidencialitātes kontroles līdzekļu pārvaldībai](manage-privacy-controls.md)</span><span class="sxs-lookup"><span data-stu-id="6611f-109">For information about similar settings for Office on computers running Windows, see [Use policy settings to manage privacy controls for Office 365 ProPlus](manage-privacy-controls.md)</span></span>

## <a name="setting-preferences"></a><span data-ttu-id="6611f-110">Preferenču iestatīšana</span><span class="sxs-lookup"><span data-stu-id="6611f-110">Setting preferences</span></span>

<span data-ttu-id="6611f-111">Šie jaunie preferenču iestatījumi ir saderīgi ar CFPreferences API, un tos var iestatīt, izmantojot `defaults` komandu terminālī, vai arī to var ieviest, izmantojot konfigurācijas profilu vai mobilo ierīču pārvaldības (Mobile Device Management — MDM) serveri.</span><span class="sxs-lookup"><span data-stu-id="6611f-111">These new preference settings are CFPreferences API compatible and can be set using the `defaults` command in Terminal, or enforced through a Configuration Profile or Mobile Device Management (MDM) server.</span></span> <span data-ttu-id="6611f-112">Kad preferences ir ieviestas, lietotājs nevar mainīt vērtības, un visas programmā esošās vadīklas tiks rādītas kā atspējotas.</span><span class="sxs-lookup"><span data-stu-id="6611f-112">When the preferences are enforced, the user cannot change the values, and any in-app controls will appear disabled.</span></span>

## <a name="preference-setting-for-diagnostic-data"></a><span data-ttu-id="6611f-113">Diagnostikas datu preferenču iestatījums</span><span class="sxs-lookup"><span data-stu-id="6611f-113">Policy setting for diagnostic data</span></span>

<span data-ttu-id="6611f-114">Diagnostikas dati tiek izmantoti, lai uzturētu Office drošu un atjauninātu, noteiktu, diagnosticētu un novērstu problēmas, kā arī uzlabotu produktu.</span><span class="sxs-lookup"><span data-stu-id="6611f-114">Diagnostic data is used to keep Office secure and up-to-date, detect, diagnose and remediate problems, and also make product improvements.</span></span> <span data-ttu-id="6611f-115">Papildinformāciju skatiet rakstā [Diagnostikas dati, kas no Office 365 ProPlus tiek nosūtīti Microsoft](overview-privacy-controls.md#diagnostic-data-sent-from-office-365-proplus-to-microsoft).</span><span class="sxs-lookup"><span data-stu-id="6611f-115">Diagnostic data sent from Office 365 ProPlus to Microsoft</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="6611f-116">**Preferenču domēns**</span><span class="sxs-lookup"><span data-stu-id="6611f-116">**Preference Domain**</span></span>  | `com.microsoft.office` |
|<span data-ttu-id="6611f-117">**Taustiņš**</span><span class="sxs-lookup"><span data-stu-id="6611f-117">**Key**</span></span>  | `DiagnosticDataTypePreference`  |
|<span data-ttu-id="6611f-118">**Datu tips**</span><span class="sxs-lookup"><span data-stu-id="6611f-118">**Data Type**</span></span>  | <span data-ttu-id="6611f-119">Virkne</span><span class="sxs-lookup"><span data-stu-id="6611f-119">String</span></span> |
|<span data-ttu-id="6611f-120">**Iespējamās vērtības**</span><span class="sxs-lookup"><span data-stu-id="6611f-120">**Possible values**</span></span>  | <span data-ttu-id="6611f-121">`BasicDiagnosticData` *(tiek iestatīts līmenis, kas nepieciešams)*</span><span class="sxs-lookup"><span data-stu-id="6611f-121">`BasicDiagnosticData` *(this sets the level to Required)*</span></span> <br/> <span data-ttu-id="6611f-122">`FullDiagnosticData` *(tiek iestatīts līmenis kā neobligāts)*</span><span class="sxs-lookup"><span data-stu-id="6611f-122">`FullDiagnosticData` *(this sets the level to Optional)*</span></span> <br/> <span data-ttu-id="6611f-123">`ZeroDiagnosticData` *(līmenis netiek iestatīts)*</span><span class="sxs-lookup"><span data-stu-id="6611f-123">`ZeroDiagnosticData` *(this sets the level to Neither)*</span></span> |
|<span data-ttu-id="6611f-124">**Pieejamība**</span><span class="sxs-lookup"><span data-stu-id="6611f-124">**Availability**</span></span> |<span data-ttu-id="6611f-125">16.28 un jaunākas versijas</span><span class="sxs-lookup"><span data-stu-id="6611f-125">16.28 and later</span></span> |

> [!NOTE]
> <span data-ttu-id="6611f-126">Ja iestatāt šo preferenci, tas attiecas arī uz šādiem produktiem:</span><span class="sxs-lookup"><span data-stu-id="6611f-126">If you set this preference, it also will apply to the following products:</span></span>
> - <span data-ttu-id="6611f-127">Teams versija 1.00.217856 un jaunākas versijas darbam ar Mac</span><span class="sxs-lookup"><span data-stu-id="6611f-127">Version 1.00.217856 and later of Teams for Mac</span></span>
> - <span data-ttu-id="6611f-128">Skype darbam versija 16.28 un jaunāka versija darbam ar Mac</span><span class="sxs-lookup"><span data-stu-id="6611f-128">Version 16.28 and later of Skype for Business for Mac</span></span>

<span data-ttu-id="6611f-129">Ja neiestatīsit šo preferenci, Microsoft tiek sūtīti neobligātie un nepieciešamie diagnostikas dati, ja lietotāji ar Office 365 abonementu ir pierakstījušies, izmantojot darba vai mācību kontu, vai ja lietotājiem ir Office 2019 darbam ar Mac lielapjoma licencēšanas versija.</span><span class="sxs-lookup"><span data-stu-id="6611f-129">If you don't set this preference, both optional and required diagnostic data is sent to Microsoft if users with an Office 365 subscription are signed in with a work or school account or if users have a volume licensed version of Office 2019 for Mac.</span></span> <span data-ttu-id="6611f-130">Tāpat šie lietotāji nevar mainīt diagnostikas datu līmeni neatkarīgi no tā, kā iestatāt šo preferenci.</span><span class="sxs-lookup"><span data-stu-id="6611f-130">Also, these users can't change the level of diagnostic data regardless of how you set this preference.</span></span>

<span data-ttu-id="6611f-131">Citiem lietotājiem, piemēram, mājas lietotājiem ar Office 365 abonementu, tiek sūtīti tikai nepieciešamie diagnostikas dati, izņemot gadījumus, kad lietotājs izvēlas sūtīt neobligātus diagnostikas datus, dodoties uz **Preferences** > **Konfidencialitāte**.</span><span class="sxs-lookup"><span data-stu-id="6611f-131">For other users, such as home users with an Office 365 subscription, only required diagnostic data is sent, unless the user chooses to also send optional diagnostic data by going to **Preferences** > **Privacy**.</span></span>

## <a name="preference-setting-for-connected-experiences-that-analyze-your-content"></a><span data-ttu-id="6611f-132">Preferences iestatījums saistītajiem līdzekļiem, kuri analizē jūsu saturu</span><span class="sxs-lookup"><span data-stu-id="6611f-132">Policy setting for connected experiences that analyze your content</span></span>

<span data-ttu-id="6611f-133">Saistīti līdzekļi, kas analizē jūsu saturu ir līdzekļi, kas izmanto jūsu Office saturu, lai sniegtu noformējuma ieteikumus, rediģēšanas ieteikumus, datu ieskatus un līdzīgus līdzekļus.</span><span class="sxs-lookup"><span data-stu-id="6611f-133">Connected experiences that analyze your content are experiences that use your Office content to provide you with design recommendations, editing suggestions, data insights, and similar features.</span></span> <span data-ttu-id="6611f-134">Piemēram, PowerPoint noformētājs vai redaktors programmā Word.</span><span class="sxs-lookup"><span data-stu-id="6611f-134">For example, PowerPoint Designer or Editor in Word.</span></span> <span data-ttu-id="6611f-135">Saistīto līdzekļu sarakstu skatiet rakstā [Office saistītie līdzekļi](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="6611f-135">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="6611f-136">**Preferenču domēns**</span><span class="sxs-lookup"><span data-stu-id="6611f-136">**Preference Domain**</span></span>  | `com.microsoft.office` |
|<span data-ttu-id="6611f-137">**Taustiņš**</span><span class="sxs-lookup"><span data-stu-id="6611f-137">**Key**</span></span>  | `OfficeExperiencesAnalyzingContentPreference`  |
|<span data-ttu-id="6611f-138">**Datu tips**</span><span class="sxs-lookup"><span data-stu-id="6611f-138">**Data Type**</span></span>  | <span data-ttu-id="6611f-139">Būla izteiksme</span><span class="sxs-lookup"><span data-stu-id="6611f-139">Boolean</span></span> |
|<span data-ttu-id="6611f-140">**Iespējamās vērtības**</span><span class="sxs-lookup"><span data-stu-id="6611f-140">**Possible values**</span></span>  | <span data-ttu-id="6611f-141">`TRUE` *(iespējots)*</span><span class="sxs-lookup"><span data-stu-id="6611f-141">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="6611f-142">`FALSE` *(atspējots)*</span><span class="sxs-lookup"><span data-stu-id="6611f-142">`FALSE` *(disabled)*</span></span>|
|<span data-ttu-id="6611f-143">**Pieejamība**</span><span class="sxs-lookup"><span data-stu-id="6611f-143">**Availability**</span></span> |<span data-ttu-id="6611f-144">16.28 un jaunākas versijas</span><span class="sxs-lookup"><span data-stu-id="6611f-144">16.28 and later</span></span> |

<span data-ttu-id="6611f-145">Ja neiestatīsit šo preferenci, lietotāji varēs izmantot saistītos līdzekļus, kas analizē saturu.</span><span class="sxs-lookup"><span data-stu-id="6611f-145">If you don't set this preference, connected experiences that analyze content are available to users.</span></span> 

<span data-ttu-id="6611f-146">Ja lietotājam ir Office 365 abonements un esat pierakstījies ar darba vai mācību kontu vai ja lietotājam ir Office 2019 darbam ar Mac lielapjoma licencēšanas versija, lietotājs nevar izslēgt saistītos līdzekļus, kas analizē saturu.</span><span class="sxs-lookup"><span data-stu-id="6611f-146">If the user has an Office 365 subscription and is signed in with a work or school account or if the user has a volume licensed version of Office 2019 for Mac, then the user can't turn off connected experiences that analyze content.</span></span>

<span data-ttu-id="6611f-147">Citiem lietotājiem, piemēram, mājas lietotājiem ar Office 365 abonementu, lietotājs var izvēlēties izslēgt saistītos līdzekļus, kas analizē saturu, dodoties uz **Preferences** > **Konfidencialitāte**.</span><span class="sxs-lookup"><span data-stu-id="6611f-147">For other users, such as home users with an Office 365 subscription, the user can choose to turn off connected experiences that analyze content by going to **Preferences** > **Privacy**.</span></span>

## <a name="preference-setting-for-connected-experiences-that-download-online-content"></a><span data-ttu-id="6611f-148">Politikas iestatījums saistītajiem līdzekļiem, kas lejupielādē tiešsaistes saturu</span><span class="sxs-lookup"><span data-stu-id="6611f-148">Policy setting for connected experiences that download online content</span></span>

<span data-ttu-id="6611f-149">Saistīti līdzekļi, kas lejupielādē tiešsaistes saturu, ir līdzekļi, kas jums ļauj meklēt un lejupielādēt tiešsaistes saturu, tostarp veidnes, attēlus, 3D modeļus, video un atsauces materiālus, lai uzlabotu jūsu dokumentus.</span><span class="sxs-lookup"><span data-stu-id="6611f-149">Connected experiences that download online content are experiences that allow you to search and download online content including templates, images, 3D models, videos, and reference materials to enhance your documents.</span></span> <span data-ttu-id="6611f-150">Piemēram, Office veidnes vai PowerPoint ātrais sākums.</span><span class="sxs-lookup"><span data-stu-id="6611f-150">For example, Office templates or PowerPoint QuickStarter.</span></span> <span data-ttu-id="6611f-151">Pilnīgāku saistīto līdzekļu sarakstu skatiet rakstā [Office saistītie līdzekļi](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="6611f-151">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="6611f-152">**Preferenču domēns**</span><span class="sxs-lookup"><span data-stu-id="6611f-152">**Preference Domain**</span></span>  | `com.microsoft.office` |
|<span data-ttu-id="6611f-153">**Taustiņš**</span><span class="sxs-lookup"><span data-stu-id="6611f-153">**Key**</span></span>  | `OfficeExperiencesDownloadingContentPreference`  |
|<span data-ttu-id="6611f-154">**Datu tips**</span><span class="sxs-lookup"><span data-stu-id="6611f-154">**Data Type**</span></span>  | <span data-ttu-id="6611f-155">Būla izteiksme</span><span class="sxs-lookup"><span data-stu-id="6611f-155">Boolean</span></span> |
|<span data-ttu-id="6611f-156">**Iespējamās vērtības**</span><span class="sxs-lookup"><span data-stu-id="6611f-156">**Possible values**</span></span>  | <span data-ttu-id="6611f-157">`TRUE` *(iespējots)*</span><span class="sxs-lookup"><span data-stu-id="6611f-157">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="6611f-158">`FALSE` *(atspējots)*</span><span class="sxs-lookup"><span data-stu-id="6611f-158">`FALSE` *(disabled)*</span></span>|
|<span data-ttu-id="6611f-159">**Pieejamība**</span><span class="sxs-lookup"><span data-stu-id="6611f-159">**Availability**</span></span> |<span data-ttu-id="6611f-160">16.28 un jaunākas versijas</span><span class="sxs-lookup"><span data-stu-id="6611f-160">16.28 and later</span></span> |

<span data-ttu-id="6611f-161">Ja neiestatīsit šo preferenci, lietotāji varēs izmantot saistītos līdzekļus, kas lejuplādē tiešsaistes saturu.</span><span class="sxs-lookup"><span data-stu-id="6611f-161">If you don't set this preference, connected experiences that download online content are available to users.</span></span>

<span data-ttu-id="6611f-162">Ja lietotājam ir Office 365 abonements un esat pierakstījies ar darba vai mācību kontu vai ja lietotājam ir Office 2019 darbam ar Mac lielapjoma licencēšanas versija, lietotājs nevar izslēgt saistītos līdzekļus, kas lejuplādē tiešsaistes saturu.</span><span class="sxs-lookup"><span data-stu-id="6611f-162">If the user has an Office 365 subscription and is signed in with a work or school account or if the user has a volume licensed version of Office 2019 for Mac, then the user can't turn off connected experiences that download online content.</span></span>

<span data-ttu-id="6611f-163">Citiem lietotājiem, piemēram, mājas lietotājiem ar Office 365 abonementu, lietotājs var izvēlēties izslēgt saistītos līdzekļus, kas lejuplādē tiešsaistes saturu, dodoties uz **Preferences** > **Konfidencialitāte**.</span><span class="sxs-lookup"><span data-stu-id="6611f-163">For other users, such as home users with an Office 365 subscription, a user can choose to turn off connected experiences that download online content by going to **Preferences** > **Privacy**.</span></span>

## <a name="preference-setting-for-optional-connected-experiences"></a><span data-ttu-id="6611f-164">Politikas iestatījums neobligātajiem saistītajiem līdzekļiem</span><span class="sxs-lookup"><span data-stu-id="6611f-164">Policy setting for optional connected experiences</span></span>

<span data-ttu-id="6611f-165">Papildus iepriekš minētajiem saistītajiem līdzekļiem, pastāv daži papildu saistītie līdzekļi, kurus varat atļaut lietotājiem izmantot, lietojot organizācijas kontu, kas dažkārt tiek dēvēts par darba vai mācību kontu.</span><span class="sxs-lookup"><span data-stu-id="6611f-165">In addition to the connected experiences mentioned above, there are some optional connected experiences that you may choose to allow your users to access with their organization account, which is sometimes referred to as a work or school account.</span></span> <span data-ttu-id="6611f-166">Piemēram, CV palīga LinkedIn līdzekļi programmā Word vai laikapstākļu josla programmā Outlook, kas izmanto MSN laika ziņas.</span><span class="sxs-lookup"><span data-stu-id="6611f-166">For example, the LinkedIn features of the Resume Assistant in Word or the 3D Maps feature in Excel, which uses Bing.</span></span> <span data-ttu-id="6611f-167">Citus piemērus skatiet rakstā [Pārskats par Office neobligātajiem saistītajiem līdzekļiem](optional-connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="6611f-167">For more examples, see [Overview of optional connected experiences in Office](optional-connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="6611f-168">**Preferenču domēns**</span><span class="sxs-lookup"><span data-stu-id="6611f-168">**Preference Domain**</span></span>  | `com.microsoft.office` |
|<span data-ttu-id="6611f-169">**Taustiņš**</span><span class="sxs-lookup"><span data-stu-id="6611f-169">**Key**</span></span>  | `OptionalConnectedExperiencesPreference`  |
|<span data-ttu-id="6611f-170">**Datu tips**</span><span class="sxs-lookup"><span data-stu-id="6611f-170">**Data Type**</span></span>  | <span data-ttu-id="6611f-171">Būla izteiksme</span><span class="sxs-lookup"><span data-stu-id="6611f-171">Boolean</span></span> |
|<span data-ttu-id="6611f-172">**Iespējamās vērtības**</span><span class="sxs-lookup"><span data-stu-id="6611f-172">**Possible values**</span></span>  | <span data-ttu-id="6611f-173">`TRUE` *(iespējots)*</span><span class="sxs-lookup"><span data-stu-id="6611f-173">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="6611f-174">`FALSE` *(atspējots)*</span><span class="sxs-lookup"><span data-stu-id="6611f-174">`FALSE` *(disabled)*</span></span>|
|<span data-ttu-id="6611f-175">**Pieejamība**</span><span class="sxs-lookup"><span data-stu-id="6611f-175">**Availability**</span></span> |<span data-ttu-id="6611f-176">16.28 un jaunākas versijas</span><span class="sxs-lookup"><span data-stu-id="6611f-176">16.28 and later</span></span> |

<span data-ttu-id="6611f-177">Ja neiestatīsit šo preferenci, neobligātie saistītie līdzekļi ir pieejami lietotājiem ar Office 365 abonementu, kas ir pierakstījušies, izmantojot darba vai mācību kontu, vai lietotājiem, kuriem ir Office 2019 darbam ar Mac lielapjoma licenzētā versija.</span><span class="sxs-lookup"><span data-stu-id="6611f-177">If you don't set this preference, optional connected experiences are available to users with an Office 365 subscription that are signed in with a work or school account or users who have a volume licensed version of Office 2019 for Mac.</span></span> <span data-ttu-id="6611f-178">Ja vien neesat iestatījis šo preferenci uz `FALSE`, šie lietotāji var izvēlēties izslēgt neobligātos saistītos līdzekļus, dodoties uz **Preferences** > **Konfidencialitāte**.</span><span class="sxs-lookup"><span data-stu-id="6611f-178">Unless you have set this preference to `FALSE`, these users can choose to turn off optional connected experiences by going to **Preferences** > **Privacy**.</span></span>

<span data-ttu-id="6611f-179">Citiem lietotājiem, piemēram, mājas lietotājiem ar Office 365 abonementu, nav pieejama opcija izslēgt neobligātos saistītos līdzekļus.</span><span class="sxs-lookup"><span data-stu-id="6611f-179">For other users, such as home users with an Office 365 subscription, there isn't an option to turn off optional connected experiences.</span></span>

## <a name="preference-setting-for-most-connected-experiences"></a><span data-ttu-id="6611f-180">Preferenču iestatījums lielākajai daļai saistīto līdzekļu</span><span class="sxs-lookup"><span data-stu-id="6611f-180">Policy setting for most connected experiences</span></span>

<span data-ttu-id="6611f-181">Šo preferenci varat izmantot, lai kontrolētu, vai lietotājiem ir pieejamas visvairāk saistītie līdzekļi.</span><span class="sxs-lookup"><span data-stu-id="6611f-181">You can use this preference to control whether most connected experiences are available to your users.</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="6611f-182">**Preferenču domēns**</span><span class="sxs-lookup"><span data-stu-id="6611f-182">**Preference Domain**</span></span>  | `com.microsoft.office` |
|<span data-ttu-id="6611f-183">**Taustiņš**</span><span class="sxs-lookup"><span data-stu-id="6611f-183">**Key**</span></span>  | `ConnectedOfficeExperiencesPreference`  |
|<span data-ttu-id="6611f-184">**Datu tips**</span><span class="sxs-lookup"><span data-stu-id="6611f-184">**Data Type**</span></span>  | <span data-ttu-id="6611f-185">Būla izteiksme</span><span class="sxs-lookup"><span data-stu-id="6611f-185">Boolean</span></span> |
|<span data-ttu-id="6611f-186">**Iespējamās vērtības**</span><span class="sxs-lookup"><span data-stu-id="6611f-186">**Possible values**</span></span>  | <span data-ttu-id="6611f-187">`TRUE` *(iespējots)*</span><span class="sxs-lookup"><span data-stu-id="6611f-187">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="6611f-188">`FALSE` *(atspējots)*</span><span class="sxs-lookup"><span data-stu-id="6611f-188">`FALSE` *(disabled)*</span></span>|
|<span data-ttu-id="6611f-189">**Pieejamība**</span><span class="sxs-lookup"><span data-stu-id="6611f-189">**Availability**</span></span> |<span data-ttu-id="6611f-190">16.28 un jaunākas versijas</span><span class="sxs-lookup"><span data-stu-id="6611f-190">16.28 and later</span></span> |

<span data-ttu-id="6611f-191">Ja neiestatāt šo preferenci, visas saistītie līdzekļi ir pieejami jūsu lietotājiem, izņemot gadījumus, kad esat iestatījis vienu no pārējām preferencēm saistītajiem līdzekļiem, kas iepriekš norādītas, piemēram, `OfficeExperiencesAnalyzingContentPreference`.</span><span class="sxs-lookup"><span data-stu-id="6611f-191">If you don't set this preference, all connected experiences are available to your users, unless you have set one of the other preferences for connected experiences previously mentioned, such as `OfficeExperiencesAnalyzingContentPreference`.</span></span>

<span data-ttu-id="6611f-192">Piemēram, ja iestatāt šo preferenci uz `FALSE`, lietotājiem nebūs pieejami tālāk norādītie saistīto līdzekļu veidi:</span><span class="sxs-lookup"><span data-stu-id="6611f-192">For example, if you set this preference to `FALSE`, the following types of connected experiences won't be available to your users:</span></span>
- <span data-ttu-id="6611f-193">Lietošanas iespējas, kas analizē jūsu saturu</span><span class="sxs-lookup"><span data-stu-id="6611f-193">Experiences that analyze your content</span></span>
- <span data-ttu-id="6611f-194">Lietošanas iespējas, kas lejupielādē tiešsaistes saturu</span><span class="sxs-lookup"><span data-stu-id="6611f-194">Experiences that download online content</span></span>
- <span data-ttu-id="6611f-195">Neobligātie saistītie līdzekļi</span><span class="sxs-lookup"><span data-stu-id="6611f-195">Optional connected experiences</span></span>

<span data-ttu-id="6611f-196">Turklāt, ja iestatāt šo preferenci uz `FALSE`, arī lielākā daļā citu saistīto līdzekļu ir izslēgti, piemēram, koprediģēšana un tiešsaistes failu krātuve.</span><span class="sxs-lookup"><span data-stu-id="6611f-196">In addition, if you disable this policy setting, most other connected experiences are also turned off, such as co-authoring and online file storage.</span></span> <span data-ttu-id="6611f-197">Pilnīgāku šo pārējo saistīto līdzekļu sarakstu skatiet rakstā [Office saistītie līdzekļi](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="6611f-197">For a list of these other connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

<span data-ttu-id="6611f-198">Tomēr pat tad `FALSE`, ja iestatīsiet šo preferenci, būs pieejama tikai ierobežota Office funkcionalitāte, piemēram, pastkastes sinhronizēšana programmā Outlook, un darba grupas un Skype darbam joprojām darbosies.</span><span class="sxs-lookup"><span data-stu-id="6611f-198">But even if you disable this policy setting, limited Office functionality will remain available, such as synching a mailbox in Outlook, and Teams and Skype for Business will continue to work.</span></span> <span data-ttu-id="6611f-199">Joprojām būs pieejami arī [Būtiskie pakalpojumi](essential-services.md), piemēram, licencēšanas pakalpojums, kurš apstiprina, ka pakalpojums Office ir atbilstoši licencēts.</span><span class="sxs-lookup"><span data-stu-id="6611f-199">[Essential services](essential-services.md), such as the licensing service that confirms that you’re properly licensed to use Office, will also remain available.</span></span>

<span data-ttu-id="6611f-200">Ja lietotājam ir Office 365 abonements un esat pierakstījies ar darba vai mācību kontu vai ja lietotājam ir Office 2019 darbam ar Mac lielapjoma licencēšanas versija, lietotājs nevar izslēgt lielāko daļu saistīto līdzekļu.</span><span class="sxs-lookup"><span data-stu-id="6611f-200">If the user has an Office 365 subscription and is signed in with a work or school account or if the user has a volume licensed version of Office 2019 for Mac, then the user can't turn off most connected experiences.</span></span>

<span data-ttu-id="6611f-201">Citiem lietotājiem, piemēram, mājas lietotājiem ar Office 365 abonementu, lietotājs var izvēlēties izslēgt lielāko daļu saistītos līdzekļus, dodoties uz **Preferences** > **Konfidencialitāte**.</span><span class="sxs-lookup"><span data-stu-id="6611f-201">For other users, such as home users with an Office 365 subscription, a user can choose to turn off most connected experiences by going to **Preferences** > **Privacy**.</span></span>

## <a name="preference-setting-for-the-required-data-notice-dialog-for-microsoft-autoupdate"></a><span data-ttu-id="6611f-202">Preferenču iestatījums nepieciešamajam datu paziņojumu dialogam Microsoft AutoUpdate</span><span class="sxs-lookup"><span data-stu-id="6611f-202">Preference setting for the Required Data Notice dialog for Microsoft AutoUpdate</span></span>

<span data-ttu-id="6611f-203">Microsoft AutoUpdate (MAU) pirmo reizi tiek palaista versija 4.12 vai jaunāka versija, un lietotāji redzēs **nepieciešamo datu paziņojumu** dialoglodziņu, kurā ir sniegta informācija par to, kādi dati no MAU tiek sūtīti Microsoft.</span><span class="sxs-lookup"><span data-stu-id="6611f-203">The first time Version 4.12 or later of Microsoft AutoUpdate (MAU) is launched, users will see a **Required Data Notice** dialog which provides them with information about what data from MAU is sent to Microsoft.</span></span>

<span data-ttu-id="6611f-204">Ja nevēlaties, lai lietotāji redzētu šo **pieprasīto datu paziņojumu** dialoglodziņu Microsoft AutoUpdate, varat iestatīt tālāk norādīto preferenci.</span><span class="sxs-lookup"><span data-stu-id="6611f-204">If you don't want your users to see this **Required Data Notice** dialog for Microsoft AutoUpdate, you can set the following preference.</span></span> <span data-ttu-id="6611f-205">Neatkarīgi no tā, kuru vērtību iestatāt, šis dialoglodziņš netiks rādīts jūsu lietotājiem.</span><span class="sxs-lookup"><span data-stu-id="6611f-205">Regardless of which value you set, the dialog won't be shown to your users.</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="6611f-206">**Preferenču domēns**</span><span class="sxs-lookup"><span data-stu-id="6611f-206">**Preference Domain**</span></span>  | `com.microsoft.autoupdate2` |
|<span data-ttu-id="6611f-207">**Taustiņš**</span><span class="sxs-lookup"><span data-stu-id="6611f-207">**Key**</span></span>  | `AcknowledgedDataCollectionPolicy`  |
|<span data-ttu-id="6611f-208">**Datu tips**</span><span class="sxs-lookup"><span data-stu-id="6611f-208">**Data Type**</span></span>  | <span data-ttu-id="6611f-209">Virkne</span><span class="sxs-lookup"><span data-stu-id="6611f-209">String</span></span> |
|<span data-ttu-id="6611f-210">**Iespējamās vērtības**</span><span class="sxs-lookup"><span data-stu-id="6611f-210">**Possible values**</span></span>  | `RequiredDataOnly` <br/> `RequiredAndOptionalData`|
|<span data-ttu-id="6611f-211">**Pieejamība**</span><span class="sxs-lookup"><span data-stu-id="6611f-211">**Availability**</span></span> |<span data-ttu-id="6611f-212">4.12 un jaunākas versijas</span><span class="sxs-lookup"><span data-stu-id="6611f-212">4.12 and later</span></span> |

<span data-ttu-id="6611f-213">Ja ļaujat lietotājiem redzēt šo dialoglodziņu, pēc tam, kad lietotājs izvēlas **Labi**, tiek ierakstīta `AcknowledgedDataCollectionPolicy` vērtība `RequiredDataOnly`, un dialoglodziņš lietotājam netiks rādīts vēlreiz.</span><span class="sxs-lookup"><span data-stu-id="6611f-213">If you let your users see this dialog, then when the user chooses **OK**, the value `RequiredDataOnly` is written to `AcknowledgedDataCollectionPolicy` and the dialog is not shown to the user again.</span></span>


## <a name="related-topics"></a><span data-ttu-id="6611f-214">Saistītās tēmas</span><span class="sxs-lookup"><span data-stu-id="6611f-214">Related topics</span></span>

- [<span data-ttu-id="6611f-215">Konfigurācijas profila atsauce (Apple Developer dokumentācija)</span><span class="sxs-lookup"><span data-stu-id="6611f-215">Configuration Profile Reference (Apple developer documentation)</span></span>](https://go.microsoft.com/fwlink/p/?linkid=852998)
- [<span data-ttu-id="6611f-216">Office darbam ar Mac preferenču izvietošana</span><span class="sxs-lookup"><span data-stu-id="6611f-216">Deploy preferences for Office for Mac</span></span>](../mac/deploy-preferences-for-office-for-mac.md)
- [<span data-ttu-id="6611f-217">Konta konfidencialitātes iestatījumi</span><span class="sxs-lookup"><span data-stu-id="6611f-217">Account Privacy Settings</span></span>](https://support.office.com/article/3e7bc183-bf52-4fd0-8e6b-78978f7f121b#ID0EAADAAA=Mac)
