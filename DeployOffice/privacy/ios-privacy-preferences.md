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
ms.openlocfilehash: 40fc1ec1f5b2abc587e1b5224dc7fe0a5a656f33
ms.sourcegitcommit: 3890a23390edd0b5fdb2cf33613ec0778566cf97
ms.translationtype: HT
ms.contentlocale: lv-LV
ms.lasthandoff: 05/01/2020
ms.locfileid: "43992113"
---
# <a name="use-preferences-to-manage-privacy-controls-for-office-on-ios-devices"></a><span data-ttu-id="02ebd-103">Izmantojiet preferences Office darbam ar iOS ierīcēm konfidencialitātes kontroles līdzekļu pārvaldībai</span><span class="sxs-lookup"><span data-stu-id="02ebd-103">Use preferences to manage privacy controls for Office on iOS devices</span></span>

<span data-ttu-id="02ebd-104">Office darbam ar iOS ierīcēm ir jauni preferenču iestatījumi, ar kuriem varat mainīt preferences attiecībā uz turpmāko:</span><span class="sxs-lookup"><span data-stu-id="02ebd-104">There are new preference settings for Office on iOS devices that allow you to control settings related to the following:</span></span>

- <span data-ttu-id="02ebd-105">***Diagnostikas dati***, kas tiek apkopoti un nosūtīti korporācijai Microsoft par izmantoto Office klienta programmatūru.</span><span class="sxs-lookup"><span data-stu-id="02ebd-105">***Diagnostic data*** that is collected and sent to Microsoft about Office client software being used.</span></span>

- <span data-ttu-id="02ebd-106">***Saistītie līdzekļi***, kas izmanto mākoņa funkcionalitāti, lai nodrošinātu uzlabotus Office līdzekļus jums un jūsu lietotājiem.</span><span class="sxs-lookup"><span data-stu-id="02ebd-106">***Connected experiences*** that use cloud-based functionality to provide enhanced Office features to you and your users.</span></span>

<span data-ttu-id="02ebd-107">Papildinformāciju par diagnostikas datiem un saistītajiem līdzekļiem skatiet rakstā [Pārskats par konfidencialitātes kontroles līdzekļiem](overview-privacy-controls.md).</span><span class="sxs-lookup"><span data-stu-id="02ebd-107">For more information about diagnostic data and connected experiences, see [Overview of privacy controls](overview-privacy-controls.md).</span></span>

<span data-ttu-id="02ebd-108">Šie preferenču iestatījumi attiecas uz šādām lietojumprogrammām:</span><span class="sxs-lookup"><span data-stu-id="02ebd-108">These preference settings apply to the following applications:</span></span>
- <span data-ttu-id="02ebd-109">Word darbam ar iOS, Excel darbam ar iOS un PowerPoint darbam ar iOS versija 2.30 vai jaunāka.</span><span class="sxs-lookup"><span data-stu-id="02ebd-109">Version 2.30 and later of Word for iOS, Excel for iOS, and PowerPoint for iOS.</span></span>
- <span data-ttu-id="02ebd-110">OneNote darbam ar iOS versija 16.30 vai jaunāka.</span><span class="sxs-lookup"><span data-stu-id="02ebd-110">Version 16.30 and later of OneNote for iOS.</span></span>
- <span data-ttu-id="02ebd-111">Visio Viewer darbam ar iOS versija 1.17 vai jaunāka.</span><span class="sxs-lookup"><span data-stu-id="02ebd-111">Version 1.17 and later of Visio Viewer for iOS.</span></span>

> [!NOTE]
> <span data-ttu-id="02ebd-112">Papildinformāciju par līdzīgu Office iestatījumu izmantošanu datoros, kuros darbojas operētājsistēma macOS, skatiet rakstā [Preferenču izmantošana Office darbam ar Mac konfidencialitātes kontroles līdzekļu pārvaldībai](mac-privacy-preferences.md).</span><span class="sxs-lookup"><span data-stu-id="02ebd-112">For information about similar settings for Office on computers running macOS, see [Use preferences to manage privacy controls for Office for Mac](mac-privacy-preferences.md)</span></span>


## <a name="setting-device-preferences"></a><span data-ttu-id="02ebd-113">Ierīces preferenču iestatīšana</span><span class="sxs-lookup"><span data-stu-id="02ebd-113">Setting device preferences</span></span>
<span data-ttu-id="02ebd-114">Šie jaunie preferenču iestatījumi, instalējot Office programmu, var tikt iestatīti arī ierīces līmenī, izmantojot mobilo ierīču pārvaldības (Mobile Device Management — MDM) serveri.</span><span class="sxs-lookup"><span data-stu-id="02ebd-114">These new preference settings can also be set at the device level by a Mobile Device Management (MDM) server when the Office application is installed.</span></span> <span data-ttu-id="02ebd-115">Daudzi MDM serveri ļauj IT administratoriem pievienot neobligātu konfigurācijas vārdnīcu, kad serveris nosūta `InstallApplication` MDM komandu uz iOS ierīci.</span><span class="sxs-lookup"><span data-stu-id="02ebd-115">Many MDM servers allow IT administrators to add an optional configuration dictionary when the server sends the `InstallApplication` MDM command to an iOS device.</span></span> <span data-ttu-id="02ebd-116">Lai saņemtu papildinformāciju, skatiet savu MDM servera dokumentāciju.</span><span class="sxs-lookup"><span data-stu-id="02ebd-116">Refer to your MDM server documentation for more details.</span></span>

<span data-ttu-id="02ebd-117">Vārdnīca tiek parādīta kā galveno/vērtību pāru kopu XML formātā.</span><span class="sxs-lookup"><span data-stu-id="02ebd-117">The dictionary is represented as a set of key/value pairs in XML format.</span></span> <span data-ttu-id="02ebd-118">Piemērs:</span><span class="sxs-lookup"><span data-stu-id="02ebd-118">For example:</span></span>

```xml
<dict>
    <key>DiagnosticDataTypePreference</key>
    <string>BasicDiagnosticData</string>
</dict>
```

<span data-ttu-id="02ebd-119">Pēc nosūtīšanas uz ierīci konfigurācijas vārdnīca atrodas zem `com.apple.managed.configuration` taustiņa, kur tā tiks lasīta, kad tiek palaista Office programma.</span><span class="sxs-lookup"><span data-stu-id="02ebd-119">Once sent to the device, the configuration dictionary will reside under the `com.apple.managed.configuration` key, where it will be read when the Office application is launched.</span></span>

> [!NOTE]
> <span data-ttu-id="02ebd-120">Jūs varat izmantot arī Office politiku mākoņpakalpojumu un tālāk minētos 4 politikas iestatījumus.</span><span class="sxs-lookup"><span data-stu-id="02ebd-120">You can also use the Office cloud policy service and these 4 policy settings:</span></span>
> - <span data-ttu-id="02ebd-121">Konfigurēt to klienta programmatūras diagnostikas datu līmeni, kurus Office nosūta korporācijai Microsoft</span><span class="sxs-lookup"><span data-stu-id="02ebd-121">Configure the level of client software diagnostic data sent by Office to Microsoft</span></span>
> - <span data-ttu-id="02ebd-122">Atļaut Office izmantot saistītos līdzekļus, kuri analizē saturu</span><span class="sxs-lookup"><span data-stu-id="02ebd-122">Allow the use of connected experiences in Office that analyze content</span></span>
> - <span data-ttu-id="02ebd-123">Atļaut Office izmantot saistītos līdzekļus, kuri lejupielādē tiešsaistes saturu</span><span class="sxs-lookup"><span data-stu-id="02ebd-123">Allow the use of connected experiences in Office that download online content</span></span>
> - <span data-ttu-id="02ebd-124">Atļaut Office izmantot papildu neobligātos saistītos līdzekļus</span><span class="sxs-lookup"><span data-stu-id="02ebd-124">Allow the use of additional optional connected experiences in Office</span></span>
>
> <span data-ttu-id="02ebd-125">Papildinformāciju par to, kā izmantot Office politiku mākoņpakalpojumu, skatiet rakstā [Pārskats par Office politiku mākoņpakalpojumu](../overview-office-cloud-policy-service.md).</span><span class="sxs-lookup"><span data-stu-id="02ebd-125">For more information on using the Office cloud policy service, see [Overview of the Office cloud policy service](../overview-office-cloud-policy-service.md).</span></span>

## <a name="preference-setting-for-diagnostic-data"></a><span data-ttu-id="02ebd-126">Diagnostikas datu preferenču iestatījums</span><span class="sxs-lookup"><span data-stu-id="02ebd-126">Preference setting for diagnostic data</span></span>

<span data-ttu-id="02ebd-127">Diagnostikas dati tiek izmantoti, lai uzturētu Office drošu un atjauninātu, noteiktu, diagnosticētu un novērstu problēmas, kā arī uzlabotu produktu.</span><span class="sxs-lookup"><span data-stu-id="02ebd-127">Diagnostic data is used to keep Office secure and up-to-date, detect, diagnose and remediate problems, and also make product improvements.</span></span> <span data-ttu-id="02ebd-128">Papildinformāciju skatiet rakstā [Diagnostikas dati, kas no Microsoft 365 programmām lieluzņēmumiem tiek nosūtīti Microsoft](overview-privacy-controls.md#diagnostic-data-sent-from-microsoft-365-apps-for-enterprise-to-microsoft).</span><span class="sxs-lookup"><span data-stu-id="02ebd-128">For more information, see [Diagnostic data sent from Microsoft 365 Apps for enterprise to Microsoft](overview-privacy-controls.md#diagnostic-data-sent-from-microsoft-365-apps-for-enterprise-to-microsoft).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="02ebd-129">**Taustiņš**</span><span class="sxs-lookup"><span data-stu-id="02ebd-129">**Key**</span></span>  | `DiagnosticDataTypePreference`  |
|<span data-ttu-id="02ebd-130">**Datu tips**</span><span class="sxs-lookup"><span data-stu-id="02ebd-130">**Data Type**</span></span>  | <span data-ttu-id="02ebd-131">Virkne</span><span class="sxs-lookup"><span data-stu-id="02ebd-131">String</span></span> |
|<span data-ttu-id="02ebd-132">**Iespējamās vērtības**</span><span class="sxs-lookup"><span data-stu-id="02ebd-132">**Possible values**</span></span>  | <span data-ttu-id="02ebd-133">`BasicDiagnosticData` *(tiek iestatīts līmenis, kas nepieciešams)*</span><span class="sxs-lookup"><span data-stu-id="02ebd-133">`BasicDiagnosticData` *(this sets the level to Required)*</span></span> <br/> <span data-ttu-id="02ebd-134">`FullDiagnosticData` *(tiek iestatīts līmenis kā neobligāts)*</span><span class="sxs-lookup"><span data-stu-id="02ebd-134">`FullDiagnosticData` *(this sets the level to Optional)*</span></span> <br/> <span data-ttu-id="02ebd-135">`ZeroDiagnosticData` *(līmenis netiek iestatīts)*</span><span class="sxs-lookup"><span data-stu-id="02ebd-135">`ZeroDiagnosticData` *(this sets the level to Neither)*</span></span> |

<span data-ttu-id="02ebd-136">Ja neiestatīsit šo preferenci, Microsoft tiks sūtīti tikai nepieciešamie diagnostikas dati, ja lietotāji ar Office 365 (vai Microsoft 365) abonementu būs pierakstījušies, izmantojot darba vai mācību kontu.</span><span class="sxs-lookup"><span data-stu-id="02ebd-136">If you don't set this preference, only required diagnostic data is sent to Microsoft if users with an Office 365 (or Microsoft 365) subscription are signed in with a work or school account.</span></span> <span data-ttu-id="02ebd-137">Tāpat šie lietotāji nevar mainīt diagnostikas datu līmeni neatkarīgi no tā, kā iestatāt šo preferenci.</span><span class="sxs-lookup"><span data-stu-id="02ebd-137">Also, these users can't change the level of diagnostic data regardless of how you set this preference.</span></span>

<span data-ttu-id="02ebd-138">Citiem lietotājiem, piemēram, mājas lietotājiem ar Office 365 (vai Microsoft 365) abonementu, tiek sūtīti tikai nepieciešamie diagnostikas dati, izņemot gadījumus, kad lietotājs izvēlas sūtīt neobligātos diagnostikas datus, dodoties uz **Iestatījumi** > **Konfidencialitātes iestatījumi**.</span><span class="sxs-lookup"><span data-stu-id="02ebd-138">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, only required diagnostic data is sent, unless the user chooses to also send optional diagnostic data by going to **Settings** > **Privacy Settings**.</span></span>


## <a name="preference-setting-for-connected-experiences-that-analyze-your-content"></a><span data-ttu-id="02ebd-139">Preferences iestatījums saistītajiem līdzekļiem, kuri analizē jūsu saturu</span><span class="sxs-lookup"><span data-stu-id="02ebd-139">Preference setting for connected experiences that analyze your content</span></span>

<span data-ttu-id="02ebd-140">Saistīti līdzekļi, kas analizē jūsu saturu ir līdzekļi, kas izmanto jūsu Office saturu, lai sniegtu noformējuma ieteikumus, rediģēšanas ieteikumus, datu ieskatus un līdzīgus līdzekļus.</span><span class="sxs-lookup"><span data-stu-id="02ebd-140">Connected experiences that analyze your content are experiences that use your Office content to provide you with design recommendations, editing suggestions, data insights, and similar features.</span></span> <span data-ttu-id="02ebd-141">Piemēram, noformējiet idejas programmā PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="02ebd-141">For example, Design Ideas in PowerPoint.</span></span> <span data-ttu-id="02ebd-142">Saistīto līdzekļu sarakstu skatiet rakstā [Office saistītie līdzekļi](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="02ebd-142">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="02ebd-143">**Taustiņš**</span><span class="sxs-lookup"><span data-stu-id="02ebd-143">**Key**</span></span>  | `OfficeExperiencesAnalyzingContentPreference`  |
|<span data-ttu-id="02ebd-144">**Datu tips**</span><span class="sxs-lookup"><span data-stu-id="02ebd-144">**Data Type**</span></span>  | <span data-ttu-id="02ebd-145">Būla izteiksme</span><span class="sxs-lookup"><span data-stu-id="02ebd-145">Boolean</span></span> |
|<span data-ttu-id="02ebd-146">**Iespējamās vērtības**</span><span class="sxs-lookup"><span data-stu-id="02ebd-146">**Possible values**</span></span>  | <span data-ttu-id="02ebd-147">`TRUE` *(iespējots)*</span><span class="sxs-lookup"><span data-stu-id="02ebd-147">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="02ebd-148">`FALSE` *(atspējots)*</span><span class="sxs-lookup"><span data-stu-id="02ebd-148">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="02ebd-149">Ja neiestatīsit šo preferenci, lietotāji varēs izmantot saistītos līdzekļus, kas analizē saturu.</span><span class="sxs-lookup"><span data-stu-id="02ebd-149">If you don't set this preference, connected experiences that analyze content are available to users.</span></span>

<span data-ttu-id="02ebd-150">Ja lietotājam ir Office 365 (vai Microsoft 365) abonements un ir pierakstījies ar darba vai mācību kontu, lietotājs nevar izslēgt saistītos līdzekļus, kas analizē saturu.</span><span class="sxs-lookup"><span data-stu-id="02ebd-150">If the user has an Office 365 (or Microsoft 365) subscription and is signed in with a work or school account, then the user can't turn off connected experiences that analyze content.</span></span>

<span data-ttu-id="02ebd-151">Citiem lietotājiem, piemēram, mājas lietotājiem ar Office 365 (vai Microsoft 365) abonementu, lietotājs var izvēlēties izslēgt saistītos līdzekļus, kas analizē saturu, dodoties uz **Iestatījumi** > **Konfidencialitāte**.</span><span class="sxs-lookup"><span data-stu-id="02ebd-151">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, the user can choose to turn off connected experiences that analyze content by going to **Settings** > **Privacy Settings**.</span></span>

## <a name="preference-setting-for-connected-experiences-that-download-online-content"></a><span data-ttu-id="02ebd-152">Politikas iestatījums saistītajiem līdzekļiem, kas lejupielādē tiešsaistes saturu</span><span class="sxs-lookup"><span data-stu-id="02ebd-152">Preference setting for connected experiences that download online content</span></span>

<span data-ttu-id="02ebd-153">Saistīti līdzekļi, kas lejupielādē tiešsaistes saturu, ir līdzekļi, kas jums ļauj meklēt un lejupielādēt tiešsaistes saturu, tostarp veidnes, attēlus, video un atsauces materiālus, lai uzlabotu jūsu dokumentus.</span><span class="sxs-lookup"><span data-stu-id="02ebd-153">Connected experiences that download online content are experiences that allow you to search and download online content including templates, images, videos, and reference materials to enhance your documents.</span></span> <span data-ttu-id="02ebd-154">Piemēram, Office veidnes vai ievietojot tiešsaistes ikonu.</span><span class="sxs-lookup"><span data-stu-id="02ebd-154">For example, Office templates or inserting an online icon.</span></span> <span data-ttu-id="02ebd-155">Saistīto līdzekļu sarakstu skatiet rakstā [Office saistītie līdzekļi](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="02ebd-155">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="02ebd-156">**Taustiņš**</span><span class="sxs-lookup"><span data-stu-id="02ebd-156">**Key**</span></span>  | `OfficeExperiencesDownloadingContentPreference`  |
|<span data-ttu-id="02ebd-157">**Datu tips**</span><span class="sxs-lookup"><span data-stu-id="02ebd-157">**Data Type**</span></span>  | <span data-ttu-id="02ebd-158">Būla izteiksme</span><span class="sxs-lookup"><span data-stu-id="02ebd-158">Boolean</span></span> |
|<span data-ttu-id="02ebd-159">**Iespējamās vērtības**</span><span class="sxs-lookup"><span data-stu-id="02ebd-159">**Possible values**</span></span>  | <span data-ttu-id="02ebd-160">`TRUE` *(iespējots)*</span><span class="sxs-lookup"><span data-stu-id="02ebd-160">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="02ebd-161">`FALSE` *(atspējots)*</span><span class="sxs-lookup"><span data-stu-id="02ebd-161">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="02ebd-162">Ja neiestatīsit šo preferenci, lietotāji varēs izmantot saistītos līdzekļus, kas lejuplādē tiešsaistes saturu.</span><span class="sxs-lookup"><span data-stu-id="02ebd-162">If you don't set this preference, connected experiences that download online content are available to users.</span></span>

<span data-ttu-id="02ebd-163">Ja lietotājam ir Office 365 (vai Microsoft 365) abonements un ir pierakstījies ar darba vai mācību kontu, lietotājs nevar izslēgt saistītos līdzekļus, kas lejuplādē tiešsaistes saturu.</span><span class="sxs-lookup"><span data-stu-id="02ebd-163">If the user has an Office 365 (or Microsoft 365) subscription and is signed in with a work or school account, then the user can't turn off connected experiences that download online content.</span></span>

<span data-ttu-id="02ebd-164">Citiem lietotājiem, piemēram, mājas lietotājiem ar Office 365 (vai Microsoft 365) abonementu, lietotājs var izvēlēties izslēgt saistītos līdzekļus, kas lejuplādē tiešsaistes saturu, dodoties uz **Iestatījumi** > **Konfidencialitāte**.</span><span class="sxs-lookup"><span data-stu-id="02ebd-164">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, the user can choose to turn off connected experiences that download online content by going to **Settings** > **Privacy Settings**.</span></span>

## <a name="preference-setting-for-optional-connected-experiences"></a><span data-ttu-id="02ebd-165">Preferences iestatījums neobligātajiem saistītajiem līdzekļiem</span><span class="sxs-lookup"><span data-stu-id="02ebd-165">Preference setting for optional connected experiences</span></span>

<span data-ttu-id="02ebd-166">Papildus iepriekš minētajiem saistītajiem līdzekļiem, pastāv daži papildu saistītie līdzekļi, kurus varat atļaut lietotājiem izmantot, lietojot organizācijas kontu, kas dažkārt tiek dēvēts par darba vai mācību kontu.</span><span class="sxs-lookup"><span data-stu-id="02ebd-166">In addition to the connected experiences mentioned above, there are some optional connected experiences that you may choose to allow your users to access with their organization account, which is sometimes referred to as a work or school account.</span></span> <span data-ttu-id="02ebd-167">Piemēram, sistēmas Office pievienojumprogrammas, kas tiek lejupielādētas no Office veikala uz jūsu ierīci.</span><span class="sxs-lookup"><span data-stu-id="02ebd-167">For example, Office add-ins that are downloaded through the Office Store to your device.</span></span> <span data-ttu-id="02ebd-168">Citus piemērus skatiet rakstā [Pārskats par Office neobligātajiem saistītajiem līdzekļiem](optional-connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="02ebd-168">For more examples, see [Overview of optional connected experiences in Office](optional-connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="02ebd-169">**Taustiņš**</span><span class="sxs-lookup"><span data-stu-id="02ebd-169">**Key**</span></span>  | `OptionalConnectedExperiencesPreference`  |
|<span data-ttu-id="02ebd-170">**Datu tips**</span><span class="sxs-lookup"><span data-stu-id="02ebd-170">**Data Type**</span></span>  | <span data-ttu-id="02ebd-171">Būla izteiksme</span><span class="sxs-lookup"><span data-stu-id="02ebd-171">Boolean</span></span> |
|<span data-ttu-id="02ebd-172">**Iespējamās vērtības**</span><span class="sxs-lookup"><span data-stu-id="02ebd-172">**Possible values**</span></span>  | <span data-ttu-id="02ebd-173">`TRUE` *(iespējots)*</span><span class="sxs-lookup"><span data-stu-id="02ebd-173">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="02ebd-174">`FALSE` *(atspējots)*</span><span class="sxs-lookup"><span data-stu-id="02ebd-174">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="02ebd-175">Ja neiestatīsit šo preferenci, lietotājiem ar Office 365 (vai Microsoft 365) abonementu, kas būs pierakstījušies, izmantojot darba vai mācību kontu, būs pieejami neobligātie saistītie līdzekļi.</span><span class="sxs-lookup"><span data-stu-id="02ebd-175">If you don't set this preference, optional connected experiences are available to users with an Office 365 (or Microsoft 365) subscription that are signed in with a work or school account.</span></span> <span data-ttu-id="02ebd-176">Ja vien neesat iestatījis šo preferenci uz APLAMI, šie lietotāji var izvēlēties izslēgt neobligātos saistītos līdzekļus, dodoties uz **Iestatījumi** > **Konfidencialitātes iestatījumi**.</span><span class="sxs-lookup"><span data-stu-id="02ebd-176">Unless you have set this preference to FALSE, these users can choose to turn off optional connected experiences by going to **Settings** > **Privacy Settings**.</span></span>

<span data-ttu-id="02ebd-177">Citiem lietotājiem, piemēram, mājas lietotājiem ar Office 365 (vai Microsoft 365) abonementu, nav pieejama opcija izslēgt neobligātos saistītos līdzekļus.</span><span class="sxs-lookup"><span data-stu-id="02ebd-177">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, there isn't an option to turn off optional connected experiences.</span></span>