---
title: Politikas iestatījumu izmantošana konfidencialitātes kontroles līdzekļus Office programmās tīmeklim
ms.author: danbrown
author: DHB-MSFT
manager: laurawi
audience: ITPro
ms.topic: article
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection: Ent_O365
ms.custom:
- Ent_Office_ProPlus
- Ent_Office_Privacy
description: Nodrošina Office administratoriem informāciju par to, kā pārvaldīt Office konfidencialitātes kontroles līdzekļus tīmekļa programmās.
hideEdit: true
ms.openlocfilehash: b5131d5ffc09b28a3b5731a417fcd6d383fb7d01
ms.sourcegitcommit: da41d41b443c8392c96e64a4d2fc674957abddf5
ms.translationtype: HT
ms.contentlocale: lv-LV
ms.lasthandoff: 09/11/2020
ms.locfileid: "47431953"
---
# <a name="use-policy-settings-to-manage-privacy-controls-for-office-for-the-web-applications"></a><span data-ttu-id="d5055-103">Politikas iestatījumu izmantošana konfidencialitātes kontroles līdzekļus Office programmās tīmeklim</span><span class="sxs-lookup"><span data-stu-id="d5055-103">Use policy settings to manage privacy controls for Office for the web applications</span></span>

> [!NOTE]
> <span data-ttu-id="d5055-104">Office produktu, uz kuriem attiecas šī konfidencialitātes informācija, saraksts ir pieejams [Konfidencialitātes kontroles līdzekļi Office produktiem](products-versions-privacy-controls.md).</span><span class="sxs-lookup"><span data-stu-id="d5055-104">For a list of Office products covered by this privacy information, see [Privacy controls available for Office products](products-versions-privacy-controls.md).</span></span>

<span data-ttu-id="d5055-105">Kā jūsu organizācijas administrators, jūs varat noteikti, vai jūsu lietotājiem būs izvēles iespējas izmantot neobligātos saistītos līdzekļus, kad lietotāji izmanto Office programmas tīmeklī, piemēram, Word tīmeklī vai PowerPoint tīmeklī.</span><span class="sxs-lookup"><span data-stu-id="d5055-105">As an administrator for your organization, you can control whether your users have the choice to use optional connected experiences when they use Office for the web applications, such as Word for the web or PowerPoint for the web.</span></span> <span data-ttu-id="d5055-106">Šī izvēle ir pieejama lietotājiem tikai, ja lietotājs ir pierakstījies ar savu darba vai skolas kontu, lai izmantotu Office tīmeklī.</span><span class="sxs-lookup"><span data-stu-id="d5055-106">This choice is available to your users only if they're signed in with their work or school account when they use Office for the web applications.</span></span> <span data-ttu-id="d5055-107">Lai kontrolētu, vai lietotājiem ir pieejami šāda veida saistītie līdzekļi, var izmantot politikas iestatījumu *Atļaut Office izmantot papildu neobligātos saistītos līdzekļus*. </span><span class="sxs-lookup"><span data-stu-id="d5055-107">To control whether your users have the choice to use optional connected experiences, you use the *Allow the use of additional optional connected experiences in Office* policy setting.</span></span>

## <a name="overview-of-optional-connected-experiences"></a><span data-ttu-id="d5055-108">Neobligāto saistīto līdzekļu pārskats</span><span class="sxs-lookup"><span data-stu-id="d5055-108">Overview of optional connected experiences</span></span>

<span data-ttu-id="d5055-109">Papildu saistītie līdzekļi ir mākonī izvietoti pakalpojumi, kas ir pieejami jūsu lietotājiem, kad viņi izmanto Office.</span><span class="sxs-lookup"><span data-stu-id="d5055-109">Optional connected experiences are cloud-backed services that are available to your users when they’re using Office.</span></span> <span data-ttu-id="d5055-110">Neobligātu saistīto līdzekļu piemēri: karšu diagrammas izveide programmā Excel vai tiešsaistes attēla ievietošana Word dokumentā; abi šie līdzekļi izmanto Microsoft Bing nodrošinātos pakalpojumus.</span><span class="sxs-lookup"><span data-stu-id="d5055-110">Examples of optional connected experiences include creating a map chart in Excel or inserting an online picture into your Word document, both of which rely on services provided by Microsoft Bing.</span></span> <span data-ttu-id="d5055-111">Šo mākoņa pakalpojumu izmantošana nav obligāta.</span><span class="sxs-lookup"><span data-stu-id="d5055-111">The use of these cloud-backed services is optional.</span></span> 

<span data-ttu-id="d5055-112">Uz šiem neobligātajiem saistītajiem līdzekļiem neattiecas jūsu organizācijas komerclīgums ar korporāciju Microsoft.</span><span class="sxs-lookup"><span data-stu-id="d5055-112">Optional connected experiences are not covered by your organization’s commercial agreement with Microsoft.</span></span> <span data-ttu-id="d5055-113">Tā vietā neobligātos saistītos līdzekļus Microsoft piedāvā tieši lietotājiem, un to darbību regulē [Microsoft pakalpojumu līgums](https://www.microsoft.com/servicesagreement).</span><span class="sxs-lookup"><span data-stu-id="d5055-113">Instead, optional connected experiences are offered by Microsoft directly to your users and are governed by the [Microsoft Services Agreement](https://www.microsoft.com/servicesagreement).</span></span> <span data-ttu-id="d5055-114">Dažos gadījumos šo neobligāto saistīto līdzekļu ietvaros tiek nodrošināts trešo pušu saturs vai funkcijas un ir spēkā citi nosacījumi.</span><span class="sxs-lookup"><span data-stu-id="d5055-114">In some cases, third-party content or functionality are provided through these optional connected experiences and other terms may also apply.</span></span>

<span data-ttu-id="d5055-115">Daži neobligātie saistītie līdzekļi var nebūt pieejami Office tīmekļa programmām, bet ir pieejami citās Office versijās, piemēram, versijās darbam ar Windows datoru.</span><span class="sxs-lookup"><span data-stu-id="d5055-115">Some optional connected experiences might not be available in Office for the web applications, but are available when using other versions of Office, such as the desktop version on a device running Windows.</span></span>

<span data-ttu-id="d5055-116">Papildinformāciju skatiet rakstā [Office neobligāto saistīto līdzekļu pārskats](optional-connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="d5055-116">For more information, see [Overview of optional connected experiences in Office](optional-connected-experiences.md).</span></span>

## <a name="configure-the-policy-setting-by-using-the-office-cloud-policy-service"></a><span data-ttu-id="d5055-117">Politikas iestatījuma konfigurēšana, izmantojot Office politiku mākoņpakalpojumu</span><span class="sxs-lookup"><span data-stu-id="d5055-117">Configure the policy setting by using the Office cloud policy service</span></span>

<span data-ttu-id="d5055-118">Ir iespējams izmantot politikas iestatījumu *Atļaut Office izmantot papildu neobligātos saistītos līdzekļus*, lai kontrolētu, vai lietotājiem ir izvēle izmantot papildu saistītos līdzekļus. </span><span class="sxs-lookup"><span data-stu-id="d5055-118">You can use the *Allow the use of additional optional connected experiences in Office* policy setting to control whether your users have the choice to use optional connected experiences.</span></span> <span data-ttu-id="d5055-119">Lai konfigurētu šo politikas iestatījumu Office darbam tīmeklī programmām, ir jāizmanto [Office mākoņa politikas pakalpojums](../overview-office-cloud-policy-service.md).</span><span class="sxs-lookup"><span data-stu-id="d5055-119">To configure this policy setting for Office for the web applications, you need to use the [Office cloud policy service](../overview-office-cloud-policy-service.md).</span></span>  

<span data-ttu-id="d5055-120">Ja nekonfigurēsit šo politikas iestatījumu, jūsu lietotājiem būs iespēja izmantot šos neobligātos saistītos līdzekļus.</span><span class="sxs-lookup"><span data-stu-id="d5055-120">If you don’t configure this policy setting, the choice to use optional connected experiences will be available to your users.</span></span> <span data-ttu-id="d5055-121">Ja atspējosit šo politikas iestatījumu, jūsu lietotājiem nebūs iespējas izmantot neobligātos saistītos līdzekļus.</span><span class="sxs-lookup"><span data-stu-id="d5055-121">If you disable this policy setting, your users won’t be able to use any of the optional connected experiences.</span></span>

<span data-ttu-id="d5055-122">Office programmās tīmeklī šis politikas iestatījums tiek piemērots tad, kad jūsu lietotāji strādā ar Office dokumentiem, kas ir saglabāti Microsoft tīmekļa krātuvē, piemēram, OneDrive darbam vai SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="d5055-122">For Office for the web applications, the policy setting applies to when your users are working on Office documents that are saved to web-based storage from Microsoft, such as OneDrive for Business or SharePoint Online.</span></span>

<span data-ttu-id="d5055-123">Tāpēc, ka izmantojat Office politiku mākoņpakalpojums, šis politikas iestatījums tiek piemērots arī tad, kad jūsu lietotāji izmanto Office programmas Windows, Mac, iOS vai Android ierīcēs.</span><span class="sxs-lookup"><span data-stu-id="d5055-123">Because you’re using the Office cloud policy service, this policy setting also applies to when your users are using Office on Windows, Mac, iOS, or Android devices.</span></span> <span data-ttu-id="d5055-124">Jūs nevarat konfigurēt šo politikas iestatījumu tikai gadījumiem, kad jūsu lietotāji izmanto Office programmas tīmeklī.</span><span class="sxs-lookup"><span data-stu-id="d5055-124">You can’t configure this policy setting just for when your users are using Office for the web applications.</span></span> <span data-ttu-id="d5055-125">Jūs varat izveidot tādu politikas konfigurāciju, kas iekļauj šo politikas iestatījumu, un pielietot šo politikas konfigurāciju tikai lietotājiem, kas piekļūst dokumentiem anonīmi ar Office programmām tīmeklī.</span><span class="sxs-lookup"><span data-stu-id="d5055-125">But, you can create a policy configuration that includes this policy setting and have that policy configuration only apply to users that access documents anonymously using Office for the web applications.</span></span>

<span data-ttu-id="d5055-126">Ja padarīsiet papildu neobligātos saistītos līdzekļus pieejamus saviem lietotājiem, tad jūsu lietotājiem tiks parādīts paziņojums par konfidencialitāti, kad viņi pirmo reizi izmantos Office programmu tīmeklī.</span><span class="sxs-lookup"><span data-stu-id="d5055-126">If you choose to make optional connected experiences available to your users, your users will be shown a privacy notification the first time they use an Office for the web app.</span></span> <span data-ttu-id="d5055-127">Šis paziņojums informēs jūsu lietotājus par to, ka jūs sniedzāt tiem iespēju izmantot šos papildu neobligātos līdzekļus.</span><span class="sxs-lookup"><span data-stu-id="d5055-127">This notification lets your users know that you’ve given them the option to use these optional connected experiences.</span></span> <span data-ttu-id="d5055-128">Šis paziņojums informē jūsu lietotājus arī par to, ka papildu neobligātie saistītie līdzekļi tiek nodrošināti saskaņā ar Microsoft pakalpojumu līgumu.</span><span class="sxs-lookup"><span data-stu-id="d5055-128">The notification also informs your users that the optional connected experiences are provided under the Microsoft Services Agreement.</span></span> <span data-ttu-id="d5055-129">Ņemot vērā to, ka šis paziņojums ir jūsu lietotājiem svarīga informācija, šis paziņojums ir jāparāda obligāti un to nav iespējams izslēgt, slēpt vai tam piekrist jūsu lietotāju vārdā.</span><span class="sxs-lookup"><span data-stu-id="d5055-129">Because this notification is important information for your users, this notification must be shown and can't be turned off, hidden, or accepted on behalf of your users.</span></span>

## <a name="users-can-choose-to-turn-off-optional-connected-experiences"></a><span data-ttu-id="d5055-130">Lietotāji var izvēlēties izslēgt neobligātos papildu saistītos līdzekļus</span><span class="sxs-lookup"><span data-stu-id="d5055-130">Users can choose to turn off optional connected experiences</span></span>

<span data-ttu-id="d5055-131">Ja izvēlēsities padarīt neobligātos papildu saistītos līdzekļus pieejamus jūsu lietotājiem, jūsu lietotāji var izslēgt piekļuvi neobligātiem saistītajiem līdzekļiem [sava konta konfidencialitātes iestatījumos](https://support.microsoft.com/office/3e7bc183-bf52-4fd0-8e6b-78978f7f121b#ID0EAADAAA=Online).</span><span class="sxs-lookup"><span data-stu-id="d5055-131">If you choose to make optional connected experiences available to your users, your users can go to their [account privacy settings](https://support.microsoft.com/office/3e7bc183-bf52-4fd0-8e6b-78978f7f121b#ID0EAADAAA=Online) and choose to turn off their access to optional connected experiences.</span></span> <span data-ttu-id="d5055-132">Šī izvēles iespēja ir pieejama konta konfidencialitātes iestatījumos tikai, ja jūsu lietotāji ir pierakstījušies ar savu darba vai mācību kontu.</span><span class="sxs-lookup"><span data-stu-id="d5055-132">This choice is available in the account privacy settings only if your users are signed in with their work or school account.</span></span> <span data-ttu-id="d5055-133">Jums kā administratoram nav iespēju liegt lietotājiem jūsu organizācijā izslēgt piekļuvi papildu saistītajiem līdzekļiem savu kontu konfidencialitātes iestatījumu sadaļās, ja ļāvāt saviem lietotājiem iespēju izmantot neobligātos papildu saistītos līdzekļus.</span><span class="sxs-lookup"><span data-stu-id="d5055-133">There is no way that you, as the admin, can prevent individual users in your organization from turning off their access to optional connected experience in their account privacy settings if you've given your users the choice to use optional connected experiences.</span></span>

## <a name="related-articles"></a><span data-ttu-id="d5055-134">Saistītie raksti</span><span class="sxs-lookup"><span data-stu-id="d5055-134">Related articles</span></span>

- [<span data-ttu-id="d5055-135">Microsoft 365 programmu lieluzņēmumiem konfidencialitātes vadīklu pārskats</span><span class="sxs-lookup"><span data-stu-id="d5055-135">Overview of privacy controls for Microsoft 365 Apps for enterprise</span></span>](overview-privacy-controls.md)
- [<span data-ttu-id="d5055-136">Politikas iestatījumu izmantošana, lai pārvaldītu Microsoft 365 programmu lieluzņēmumiem konfidencialitātes vadīklas</span><span class="sxs-lookup"><span data-stu-id="d5055-136">Use policy settings to manage privacy controls for Microsoft 365 Apps for enterprise</span></span>](manage-privacy-controls.md)
- [<span data-ttu-id="d5055-137">Preferenču izmantošana Office darbam ar Mac konfidencialitātes kontroles līdzekļu pārvaldībai</span><span class="sxs-lookup"><span data-stu-id="d5055-137">Use preferences to manage privacy controls for Office for Mac</span></span>](mac-privacy-preferences.md)
- [<span data-ttu-id="d5055-138">Preferenču izmantošana Office darbam ar iOS ierīcēm konfidencialitātes kontroles līdzekļu pārvaldībai</span><span class="sxs-lookup"><span data-stu-id="d5055-138">Use preferences to manage privacy controls for Office on iOS devices</span></span>](ios-privacy-preferences.md)
- [<span data-ttu-id="d5055-139">Politikas iestatījumu izmantošana Office konfidencialitātes kontroles līdzekļu pārvaldībai Android ierīcēs</span><span class="sxs-lookup"><span data-stu-id="d5055-139">Use policy settings to manage privacy controls for Office on Android devices</span></span>](android-privacy-controls.md)