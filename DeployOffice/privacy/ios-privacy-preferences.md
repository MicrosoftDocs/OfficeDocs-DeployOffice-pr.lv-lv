---
title: Izmantojiet preferences Office darbam ar iOS ierīcēm konfidencialitātes kontroles līdzekļu pārvaldībai
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
description: Nodrošina Office administratoriem informāciju par to, kā pārvaldīt konfidencialitātes kontroles līdzekļus darbam ar iOS ierīcēm.
hideEdit: true
ms.openlocfilehash: d1a14d2e1bfe45710255467fcbce9ac4af2c9cb7
ms.sourcegitcommit: 903d6bac7d8b7d8003863ac778c0b5bbdfa7a62a
ms.translationtype: HT
ms.contentlocale: lv-LV
ms.lasthandoff: 10/21/2019
ms.locfileid: "37604290"
---
# <a name="use-preferences-to-manage-privacy-controls-for-office-on-ios-devices"></a><span data-ttu-id="17bfd-103">Izmantojiet preferences Office darbam ar iOS ierīcēm konfidencialitātes kontroles līdzekļu pārvaldībai</span><span class="sxs-lookup"><span data-stu-id="17bfd-103">Use preferences to manage privacy controls for Office on iOS devices</span></span>

<span data-ttu-id="17bfd-104">Office darbam ar iOS ierīcēm ir jauni preferenču iestatījumi, ar kuriem varat mainīt preferences attiecībā uz turpmāko:</span><span class="sxs-lookup"><span data-stu-id="17bfd-104">There are new preference settings for Office on iOS devices that allow you to control settings related to the following:</span></span>

- <span data-ttu-id="17bfd-105">***Diagnostikas dati***, kas tiek apkopoti un nosūtīti korporācijai Microsoft par izmantoto Office klienta programmatūru.</span><span class="sxs-lookup"><span data-stu-id="17bfd-105">***Diagnostic data*** that is collected and sent to Microsoft about Office client software being used.</span></span>

- <span data-ttu-id="17bfd-106">***Saistītie līdzekļi***, kas izmanto mākoņa funkcionalitāti, lai nodrošinātu uzlabotus Office līdzekļus jums un jūsu lietotājiem.</span><span class="sxs-lookup"><span data-stu-id="17bfd-106">***Connected experiences*** that use cloud-based functionality to provide enhanced Office features to you and your users.</span></span>

<span data-ttu-id="17bfd-107">Papildinformāciju par diagnostikas datiem un saistītajiem līdzekļiem skatiet rakstā [Pārskats par konfidencialitātes kontroles līdzekļiem](overview-privacy-controls.md).</span><span class="sxs-lookup"><span data-stu-id="17bfd-107">For more information about diagnostic data and connected experiences, see [Overview of privacy controls](overview-privacy-controls.md).</span></span>

<span data-ttu-id="17bfd-108">Šie preferenču iestatījumi attiecas uz šādām lietojumprogrammām:</span><span class="sxs-lookup"><span data-stu-id="17bfd-108">These preference settings apply to the following applications:</span></span>
- <span data-ttu-id="17bfd-109">Word darbam ar iOS, Excel darbam ar iOS un PowerPoint darbam ar iOS versija 2.30 vai jaunāka.</span><span class="sxs-lookup"><span data-stu-id="17bfd-109">Version 2.30 and later of Word for iOS, Excel for iOS, and PowerPoint for iOS.</span></span>
- <span data-ttu-id="17bfd-110">OneNote darbam ar iOS versija 16.30 vai jaunāka.</span><span class="sxs-lookup"><span data-stu-id="17bfd-110">Version 16.30 and later of OneNote for iOS.</span></span>
- <span data-ttu-id="17bfd-111">Visio Viewer darbam ar iOS versija 1.17 vai jaunāka.</span><span class="sxs-lookup"><span data-stu-id="17bfd-111">Version 1.17 and later of Visio Viewer for iOS.</span></span>

> [!NOTE]
> <span data-ttu-id="17bfd-112">Papildinformāciju par līdzīgu Office iestatījumu izmantošanu datoros, kuros darbojas operētājsistēma macOS, skatiet rakstā [Preferenču izmantošana Office darbam ar Mac konfidencialitātes kontroles līdzekļu pārvaldībai](mac-privacy-preferences.md).</span><span class="sxs-lookup"><span data-stu-id="17bfd-112">For information about similar settings for Office on computers running Windows, see [Use policy settings to manage privacy controls for Office 365 ProPlus](mac-privacy-preferences.md).</span></span>


## <a name="setting-device-preferences"></a><span data-ttu-id="17bfd-113">Ierīces preferenču iestatīšana</span><span class="sxs-lookup"><span data-stu-id="17bfd-113">Setting device preferences</span></span>
<span data-ttu-id="17bfd-114">Šie jaunie preferenču iestatījumi, instalējot Office programmu, var tikt iestatīti arī ierīces līmenī, izmantojot mobilo ierīču pārvaldības (Mobile Device Management — MDM) serveri.</span><span class="sxs-lookup"><span data-stu-id="17bfd-114">These new preference settings can also be set at the device level by a Mobile Device Management (MDM) server when the Office application is installed.</span></span> <span data-ttu-id="17bfd-115">Daudzi MDM serveri ļauj IT administratoriem pievienot neobligātu konfigurācijas vārdnīcu, kad serveris nosūta `InstallApplication` MDM komandu uz iOS ierīci.</span><span class="sxs-lookup"><span data-stu-id="17bfd-115">Many MDM servers allow IT administrators to add an optional configuration dictionary when the server sends the `InstallApplication` MDM command to an iOS device.</span></span> <span data-ttu-id="17bfd-116">Lai saņemtu papildinformāciju, skatiet savu MDM servera dokumentāciju.</span><span class="sxs-lookup"><span data-stu-id="17bfd-116">Refer to your MDM server documentation for more details.</span></span>

<span data-ttu-id="17bfd-117">Vārdnīca tiek parādīta kā galveno/vērtību pāru kopu XML formātā.</span><span class="sxs-lookup"><span data-stu-id="17bfd-117">The dictionary is represented as a set of key/value pairs in XML format.</span></span> <span data-ttu-id="17bfd-118">Piemērs:</span><span class="sxs-lookup"><span data-stu-id="17bfd-118">For example:</span></span>

```xml
<dict>
    <key>DiagnosticDataTypePreference</key>
    <string>BasicDiagnosticData</string>
</dict>
```

<span data-ttu-id="17bfd-119">Pēc nosūtīšanas uz ierīci konfigurācijas vārdnīca atrodas zem `com.apple.managed.configuration` taustiņa, kur tā tiks lasīta, kad tiek palaista Office programma.</span><span class="sxs-lookup"><span data-stu-id="17bfd-119">Once sent to the device, the configuration dictionary will reside under the `com.apple.managed.configuration` key, where it will be read when the Office application is launched.</span></span>

## <a name="preference-setting-for-diagnostic-data"></a><span data-ttu-id="17bfd-120">Diagnostikas datu preferenču iestatījums</span><span class="sxs-lookup"><span data-stu-id="17bfd-120">Preference setting for diagnostic data</span></span>

<span data-ttu-id="17bfd-121">Diagnostikas dati tiek izmantoti, lai uzturētu Office drošu un atjauninātu, noteiktu, diagnosticētu un novērstu problēmas, kā arī uzlabotu produktu.</span><span class="sxs-lookup"><span data-stu-id="17bfd-121">Diagnostic data is used to keep Office secure and up-to-date, detect, diagnose and remediate problems, and also make product improvements.</span></span> <span data-ttu-id="17bfd-122">Papildinformāciju skatiet rakstā [Diagnostikas dati, kas no Office 365 ProPlus tiek nosūtīti Microsoft](overview-privacy-controls.md#diagnostic-data-sent-from-office-365-proplus-to-microsoft).</span><span class="sxs-lookup"><span data-stu-id="17bfd-122">For more information, see [Diagnostic data sent from Office 365 ProPlus to Microsoft](overview-privacy-controls.md#diagnostic-data-sent-from-office-365-proplus-to-microsoft).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="17bfd-123">**Taustiņš**</span><span class="sxs-lookup"><span data-stu-id="17bfd-123">**Key**</span></span>  | `DiagnosticDataTypePreference`  |
|<span data-ttu-id="17bfd-124">**Datu tips**</span><span class="sxs-lookup"><span data-stu-id="17bfd-124">**Data Type**</span></span>  | <span data-ttu-id="17bfd-125">Virkne</span><span class="sxs-lookup"><span data-stu-id="17bfd-125">String</span></span> |
|<span data-ttu-id="17bfd-126">**Iespējamās vērtības**</span><span class="sxs-lookup"><span data-stu-id="17bfd-126">**Possible values**</span></span>  | <span data-ttu-id="17bfd-127">`BasicDiagnosticData` *(tiek iestatīts līmenis, kas nepieciešams)*</span><span class="sxs-lookup"><span data-stu-id="17bfd-127">`BasicDiagnosticData` *(this sets the level to Required)*</span></span> <br/> <span data-ttu-id="17bfd-128">`FullDiagnosticData` *(tiek iestatīts līmenis kā neobligāts)*</span><span class="sxs-lookup"><span data-stu-id="17bfd-128">`FullDiagnosticData` *(this sets the level to Optional)*</span></span> <br/> <span data-ttu-id="17bfd-129">`ZeroDiagnosticData` *(līmenis netiek iestatīts)*</span><span class="sxs-lookup"><span data-stu-id="17bfd-129">`ZeroDiagnosticData` *(this sets the level to Neither)*</span></span> |

<span data-ttu-id="17bfd-130">Ja neiestatīsit šo preferenci, Microsoft tiks sūtīti tikai nepieciešamie diagnostikas dati, ja lietotāji ar Office 365 abonementu būs pierakstījušies, izmantojot darba vai mācību kontu.</span><span class="sxs-lookup"><span data-stu-id="17bfd-130">Starting with new installations of Version 16.30, if you don't set this preference, only required diagnostic data is sent to Microsoft if users with an Office 365 subscription are signed in with a work or school account or if users have a volume licensed version of Office 2019 for Mac.</span></span> <span data-ttu-id="17bfd-131">Tāpat šie lietotāji nevar mainīt diagnostikas datu līmeni neatkarīgi no tā, kā iestatāt šo preferenci.</span><span class="sxs-lookup"><span data-stu-id="17bfd-131">Also, these users can't change the level of diagnostic data regardless of how you set this preference.</span></span>

<span data-ttu-id="17bfd-132">Citiem lietotājiem, piemēram, mājas lietotājiem ar Office 365 abonementu, tiek sūtīti tikai nepieciešamie diagnostikas dati, izņemot gadījumus, kad lietotājs izvēlas sūtīt neobligātos diagnostikas datus, dodoties uz **Iestatījumi** > **Konfidencialitātes iestatījumi**.</span><span class="sxs-lookup"><span data-stu-id="17bfd-132">For other users, such as home users with an Office 365 subscription, only required diagnostic data is sent, unless the user chooses to also send optional diagnostic data by going to **Preferences** > **Privacy**.</span></span>


## <a name="preference-setting-for-connected-experiences-that-analyze-your-content"></a><span data-ttu-id="17bfd-133">Preferences iestatījums saistītajiem līdzekļiem, kuri analizē jūsu saturu</span><span class="sxs-lookup"><span data-stu-id="17bfd-133">Preference setting for connected experiences that analyze your content</span></span>

<span data-ttu-id="17bfd-134">Saistīti līdzekļi, kas analizē jūsu saturu ir līdzekļi, kas izmanto jūsu Office saturu, lai sniegtu noformējuma ieteikumus, rediģēšanas ieteikumus, datu ieskatus un līdzīgus līdzekļus.</span><span class="sxs-lookup"><span data-stu-id="17bfd-134">Connected experiences that analyze your content are experiences that use your Office content to provide you with design recommendations, editing suggestions, data insights, and similar features.</span></span> <span data-ttu-id="17bfd-135">Piemēram, noformējiet idejas programmā PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="17bfd-135">For example, Design Ideas in PowerPoint.</span></span> <span data-ttu-id="17bfd-136">Saistīto līdzekļu sarakstu skatiet rakstā [Office saistītie līdzekļi](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="17bfd-136">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="17bfd-137">**Taustiņš**</span><span class="sxs-lookup"><span data-stu-id="17bfd-137">**Key**</span></span>  | `OfficeExperiencesAnalyzingContentPreference`  |
|<span data-ttu-id="17bfd-138">**Datu tips**</span><span class="sxs-lookup"><span data-stu-id="17bfd-138">**Data Type**</span></span>  | <span data-ttu-id="17bfd-139">Būla izteiksme</span><span class="sxs-lookup"><span data-stu-id="17bfd-139">Boolean</span></span> |
|<span data-ttu-id="17bfd-140">**Iespējamās vērtības**</span><span class="sxs-lookup"><span data-stu-id="17bfd-140">**Possible values**</span></span>  | <span data-ttu-id="17bfd-141">`TRUE` *(iespējots)*</span><span class="sxs-lookup"><span data-stu-id="17bfd-141">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="17bfd-142">`FALSE` *(atspējots)*</span><span class="sxs-lookup"><span data-stu-id="17bfd-142">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="17bfd-143">Ja neiestatīsit šo preferenci, lietotāji varēs izmantot saistītos līdzekļus, kas analizē saturu.</span><span class="sxs-lookup"><span data-stu-id="17bfd-143">If you don't set this preference, connected experiences that analyze content are available to users.</span></span>

<span data-ttu-id="17bfd-144">Ja lietotājam ir Office 365 abonements un ir pierakstījies ar darba vai mācību kontu, lietotājs nevar izslēgt saistītos līdzekļus, kas analizē saturu.</span><span class="sxs-lookup"><span data-stu-id="17bfd-144">If the user has an Office 365 subscription and is signed in with a work or school account or if the user has a volume licensed version of Office 2019 for Mac, then the user can't turn off connected experiences that analyze content.</span></span>

<span data-ttu-id="17bfd-145">Citiem lietotājiem, piemēram, mājas lietotājiem ar Office 365 abonementu, lietotājs var izvēlēties izslēgt saistītos līdzekļus, kas analizē saturu, dodoties uz **Iestatījumi** > **Konfidencialitāte**.</span><span class="sxs-lookup"><span data-stu-id="17bfd-145">For other users, such as home users with an Office 365 subscription, the user can choose to turn off connected experiences that analyze content by going to **Preferences** > **Privacy**.</span></span>

## <a name="preference-setting-for-connected-experiences-that-download-online-content"></a><span data-ttu-id="17bfd-146">Politikas iestatījums saistītajiem līdzekļiem, kas lejupielādē tiešsaistes saturu</span><span class="sxs-lookup"><span data-stu-id="17bfd-146">Preference setting for connected experiences that download online content</span></span>

<span data-ttu-id="17bfd-147">Saistīti līdzekļi, kas lejupielādē tiešsaistes saturu, ir līdzekļi, kas jums ļauj meklēt un lejupielādēt tiešsaistes saturu, tostarp veidnes, attēlus, video un atsauces materiālus, lai uzlabotu jūsu dokumentus.</span><span class="sxs-lookup"><span data-stu-id="17bfd-147">Connected experiences that download online content are experiences that allow you to search and download online content including templates, images, 3D models, videos, and reference materials to enhance your documents.</span></span> <span data-ttu-id="17bfd-148">Piemēram, Office veidnes vai ievietojot tiešsaistes ikonu.</span><span class="sxs-lookup"><span data-stu-id="17bfd-148">For example, Office templates or inserting an online icon.</span></span> <span data-ttu-id="17bfd-149">Saistīto līdzekļu sarakstu skatiet rakstā [Office saistītie līdzekļi](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="17bfd-149">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="17bfd-150">**Taustiņš**</span><span class="sxs-lookup"><span data-stu-id="17bfd-150">**Key**</span></span>  | `OfficeExperiencesDownloadingContentPreference`  |
|<span data-ttu-id="17bfd-151">**Datu tips**</span><span class="sxs-lookup"><span data-stu-id="17bfd-151">**Data Type**</span></span>  | <span data-ttu-id="17bfd-152">Būla izteiksme</span><span class="sxs-lookup"><span data-stu-id="17bfd-152">Boolean</span></span> |
|<span data-ttu-id="17bfd-153">**Iespējamās vērtības**</span><span class="sxs-lookup"><span data-stu-id="17bfd-153">**Possible values**</span></span>  | <span data-ttu-id="17bfd-154">`TRUE` *(iespējots)*</span><span class="sxs-lookup"><span data-stu-id="17bfd-154">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="17bfd-155">`FALSE` *(atspējots)*</span><span class="sxs-lookup"><span data-stu-id="17bfd-155">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="17bfd-156">Ja neiestatīsit šo preferenci, lietotāji varēs izmantot saistītos līdzekļus, kas lejuplādē tiešsaistes saturu.</span><span class="sxs-lookup"><span data-stu-id="17bfd-156">If you don't set this preference, connected experiences that download online content are available to users.</span></span>

<span data-ttu-id="17bfd-157">Ja lietotājam ir Office 365 abonements un ir pierakstījies ar darba vai mācību kontu, lietotājs nevar izslēgt saistītos līdzekļus, kas lejuplādē tiešsaistes saturu.</span><span class="sxs-lookup"><span data-stu-id="17bfd-157">If the user has an Office 365 subscription and is signed in with a work or school account or if the user has a volume licensed version of Office 2019 for Mac, then the user can't turn off connected experiences that download online content.</span></span>

<span data-ttu-id="17bfd-158">Citiem lietotājiem, piemēram, mājas lietotājiem ar Office 365 abonementu, lietotājs var izvēlēties izslēgt saistītos līdzekļus, kas lejuplādē tiešsaistes saturu, dodoties uz **Iestatījumi** > **Konfidencialitātes iestatījumi**.</span><span class="sxs-lookup"><span data-stu-id="17bfd-158">For other users, such as home users with an Office 365 subscription, a user can choose to turn off connected experiences that download online content by going to **Preferences** > **Privacy**.</span></span>

## <a name="preference-setting-for-optional-connected-experiences"></a><span data-ttu-id="17bfd-159">Preferences iestatījums neobligātajiem saistītajiem līdzekļiem</span><span class="sxs-lookup"><span data-stu-id="17bfd-159">Preference setting for optional connected experiences</span></span>

<span data-ttu-id="17bfd-160">Papildus iepriekš minētajiem saistītajiem līdzekļiem, pastāv daži papildu saistītie līdzekļi, kurus varat atļaut lietotājiem izmantot, lietojot organizācijas kontu, kas dažkārt tiek dēvēts par darba vai mācību kontu.</span><span class="sxs-lookup"><span data-stu-id="17bfd-160">In addition to the connected experiences mentioned above, there are some optional connected experiences that you may choose to allow your users to access with their organization account, which is sometimes referred to as a work or school account.</span></span> <span data-ttu-id="17bfd-161">Piemēram, sistēmas Office pievienojumprogrammas, kas tiek lejupielādētas no Office veikala uz jūsu ierīci.</span><span class="sxs-lookup"><span data-stu-id="17bfd-161">For example, Office add-ins that are downloaded through the Office Store to your device.</span></span> <span data-ttu-id="17bfd-162">Citus piemērus skatiet rakstā [Pārskats par Office neobligātajiem saistītajiem līdzekļiem](optional-connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="17bfd-162">For more examples, see [Overview of optional connected experiences in Office](optional-connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="17bfd-163">**Taustiņš**</span><span class="sxs-lookup"><span data-stu-id="17bfd-163">**Key**</span></span>  | `OptionalConnectedExperiencesPreference`  |
|<span data-ttu-id="17bfd-164">**Datu tips**</span><span class="sxs-lookup"><span data-stu-id="17bfd-164">**Data Type**</span></span>  | <span data-ttu-id="17bfd-165">Būla izteiksme</span><span class="sxs-lookup"><span data-stu-id="17bfd-165">Boolean</span></span> |
|<span data-ttu-id="17bfd-166">**Iespējamās vērtības**</span><span class="sxs-lookup"><span data-stu-id="17bfd-166">**Possible values**</span></span>  | <span data-ttu-id="17bfd-167">`TRUE` *(iespējots)*</span><span class="sxs-lookup"><span data-stu-id="17bfd-167">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="17bfd-168">`FALSE` *(atspējots)*</span><span class="sxs-lookup"><span data-stu-id="17bfd-168">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="17bfd-169">Ja neiestatīsit šo preferenci, lietotājiem ar Office 365 abonementu, kas būs pierakstījušies, izmantojot darba vai mācību kontu, būs pieejami neobligātie saistītie līdzekļi.</span><span class="sxs-lookup"><span data-stu-id="17bfd-169">If you don't set this preference, optional connected experiences are available to users with an Office 365 subscription that are signed in with a work or school account or users who have a volume licensed version of Office 2019 for Mac.</span></span> <span data-ttu-id="17bfd-170">Ja vien neesat iestatījis šo preferenci uz APLAMI, šie lietotāji var izvēlēties izslēgt neobligātos saistītos līdzekļus, dodoties uz **Iestatījumi** > **Konfidencialitātes iestatījumi**.</span><span class="sxs-lookup"><span data-stu-id="17bfd-170">Unless you have set this preference to , these users can choose to turn off optional connected experiences by going to Preferences  Privacy.</span></span>

<span data-ttu-id="17bfd-171">Citiem lietotājiem, piemēram, mājas lietotājiem ar Office 365 abonementu, nav pieejama opcija izslēgt neobligātos saistītos līdzekļus.</span><span class="sxs-lookup"><span data-stu-id="17bfd-171">For other users, such as home users with an Office 365 subscription, there isn't an option to turn off optional connected experiences.</span></span>