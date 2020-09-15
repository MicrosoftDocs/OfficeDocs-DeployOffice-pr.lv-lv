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
# <a name="use-policy-settings-to-manage-privacy-controls-for-office-for-the-web-applications"></a>Politikas iestatījumu izmantošana konfidencialitātes kontroles līdzekļus Office programmās tīmeklim

> [!NOTE]
> Office produktu, uz kuriem attiecas šī konfidencialitātes informācija, saraksts ir pieejams [Konfidencialitātes kontroles līdzekļi Office produktiem](products-versions-privacy-controls.md).

Kā jūsu organizācijas administrators, jūs varat noteikti, vai jūsu lietotājiem būs izvēles iespējas izmantot neobligātos saistītos līdzekļus, kad lietotāji izmanto Office programmas tīmeklī, piemēram, Word tīmeklī vai PowerPoint tīmeklī. Šī izvēle ir pieejama lietotājiem tikai, ja lietotājs ir pierakstījies ar savu darba vai skolas kontu, lai izmantotu Office tīmeklī. Lai kontrolētu, vai lietotājiem ir pieejami šāda veida saistītie līdzekļi, var izmantot politikas iestatījumu *Atļaut Office izmantot papildu neobligātos saistītos līdzekļus*. 

## <a name="overview-of-optional-connected-experiences"></a>Neobligāto saistīto līdzekļu pārskats

Papildu saistītie līdzekļi ir mākonī izvietoti pakalpojumi, kas ir pieejami jūsu lietotājiem, kad viņi izmanto Office. Neobligātu saistīto līdzekļu piemēri: karšu diagrammas izveide programmā Excel vai tiešsaistes attēla ievietošana Word dokumentā; abi šie līdzekļi izmanto Microsoft Bing nodrošinātos pakalpojumus. Šo mākoņa pakalpojumu izmantošana nav obligāta. 

Uz šiem neobligātajiem saistītajiem līdzekļiem neattiecas jūsu organizācijas komerclīgums ar korporāciju Microsoft. Tā vietā neobligātos saistītos līdzekļus Microsoft piedāvā tieši lietotājiem, un to darbību regulē [Microsoft pakalpojumu līgums](https://www.microsoft.com/servicesagreement). Dažos gadījumos šo neobligāto saistīto līdzekļu ietvaros tiek nodrošināts trešo pušu saturs vai funkcijas un ir spēkā citi nosacījumi.

Daži neobligātie saistītie līdzekļi var nebūt pieejami Office tīmekļa programmām, bet ir pieejami citās Office versijās, piemēram, versijās darbam ar Windows datoru.

Papildinformāciju skatiet rakstā [Office neobligāto saistīto līdzekļu pārskats](optional-connected-experiences.md).

## <a name="configure-the-policy-setting-by-using-the-office-cloud-policy-service"></a>Politikas iestatījuma konfigurēšana, izmantojot Office politiku mākoņpakalpojumu

Ir iespējams izmantot politikas iestatījumu *Atļaut Office izmantot papildu neobligātos saistītos līdzekļus*, lai kontrolētu, vai lietotājiem ir izvēle izmantot papildu saistītos līdzekļus.  Lai konfigurētu šo politikas iestatījumu Office darbam tīmeklī programmām, ir jāizmanto [Office mākoņa politikas pakalpojums](../overview-office-cloud-policy-service.md).  

Ja nekonfigurēsit šo politikas iestatījumu, jūsu lietotājiem būs iespēja izmantot šos neobligātos saistītos līdzekļus. Ja atspējosit šo politikas iestatījumu, jūsu lietotājiem nebūs iespējas izmantot neobligātos saistītos līdzekļus.

Office programmās tīmeklī šis politikas iestatījums tiek piemērots tad, kad jūsu lietotāji strādā ar Office dokumentiem, kas ir saglabāti Microsoft tīmekļa krātuvē, piemēram, OneDrive darbam vai SharePoint Online.

Tāpēc, ka izmantojat Office politiku mākoņpakalpojums, šis politikas iestatījums tiek piemērots arī tad, kad jūsu lietotāji izmanto Office programmas Windows, Mac, iOS vai Android ierīcēs. Jūs nevarat konfigurēt šo politikas iestatījumu tikai gadījumiem, kad jūsu lietotāji izmanto Office programmas tīmeklī. Jūs varat izveidot tādu politikas konfigurāciju, kas iekļauj šo politikas iestatījumu, un pielietot šo politikas konfigurāciju tikai lietotājiem, kas piekļūst dokumentiem anonīmi ar Office programmām tīmeklī.

Ja padarīsiet papildu neobligātos saistītos līdzekļus pieejamus saviem lietotājiem, tad jūsu lietotājiem tiks parādīts paziņojums par konfidencialitāti, kad viņi pirmo reizi izmantos Office programmu tīmeklī. Šis paziņojums informēs jūsu lietotājus par to, ka jūs sniedzāt tiem iespēju izmantot šos papildu neobligātos līdzekļus. Šis paziņojums informē jūsu lietotājus arī par to, ka papildu neobligātie saistītie līdzekļi tiek nodrošināti saskaņā ar Microsoft pakalpojumu līgumu. Ņemot vērā to, ka šis paziņojums ir jūsu lietotājiem svarīga informācija, šis paziņojums ir jāparāda obligāti un to nav iespējams izslēgt, slēpt vai tam piekrist jūsu lietotāju vārdā.

## <a name="users-can-choose-to-turn-off-optional-connected-experiences"></a>Lietotāji var izvēlēties izslēgt neobligātos papildu saistītos līdzekļus

Ja izvēlēsities padarīt neobligātos papildu saistītos līdzekļus pieejamus jūsu lietotājiem, jūsu lietotāji var izslēgt piekļuvi neobligātiem saistītajiem līdzekļiem [sava konta konfidencialitātes iestatījumos](https://support.microsoft.com/office/3e7bc183-bf52-4fd0-8e6b-78978f7f121b#ID0EAADAAA=Online). Šī izvēles iespēja ir pieejama konta konfidencialitātes iestatījumos tikai, ja jūsu lietotāji ir pierakstījušies ar savu darba vai mācību kontu. Jums kā administratoram nav iespēju liegt lietotājiem jūsu organizācijā izslēgt piekļuvi papildu saistītajiem līdzekļiem savu kontu konfidencialitātes iestatījumu sadaļās, ja ļāvāt saviem lietotājiem iespēju izmantot neobligātos papildu saistītos līdzekļus.

## <a name="related-articles"></a>Saistītie raksti

- [Microsoft 365 programmu lieluzņēmumiem konfidencialitātes vadīklu pārskats](overview-privacy-controls.md)
- [Politikas iestatījumu izmantošana, lai pārvaldītu Microsoft 365 programmu lieluzņēmumiem konfidencialitātes vadīklas](manage-privacy-controls.md)
- [Preferenču izmantošana Office darbam ar Mac konfidencialitātes kontroles līdzekļu pārvaldībai](mac-privacy-preferences.md)
- [Preferenču izmantošana Office darbam ar iOS ierīcēm konfidencialitātes kontroles līdzekļu pārvaldībai](ios-privacy-preferences.md)
- [Politikas iestatījumu izmantošana Office konfidencialitātes kontroles līdzekļu pārvaldībai Android ierīcēs](android-privacy-controls.md)