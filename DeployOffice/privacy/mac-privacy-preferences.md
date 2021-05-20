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
ms.openlocfilehash: b7beda7409cff00d54f36851eb21e4d66a8cacce
ms.sourcegitcommit: 9b5f18c543c286c95e546e22fc8edb60ef541030
ms.translationtype: HT
ms.contentlocale: lv-LV
ms.lasthandoff: 05/20/2021
ms.locfileid: "52578379"
---
# <a name="use-preferences-to-manage-privacy-controls-for-office-for-mac"></a>Preferenču izmantošana Office darbam ar Mac konfidencialitātes kontroles līdzekļu pārvaldībai

> [!NOTE]
> Sarakstu ar Office produktiem, uz kuriem attiecas šī konfidencialitātes informācija, skatiet rakstā [Konfidencialitātes kontroles līdzekļi, kas pieejami Office produktiem](products-versions-privacy-controls.md).

Sākot ar Office versiju 16.28 darbam ar Mac, ir jauni politikas iestatījumi, kuri nodrošina iespēju kontrolēt ar šo saistītus iestatījumus:

- ***Diagnostikas dati***, kas tiek apkopoti un nosūtīti korporācijai Microsoft par izmantoto Office klienta programmatūru.

- ***Saistītie līdzekļi***, kas izmanto mākoņa funkcionalitāti, lai nodrošinātu uzlabotus Office līdzekļus jums un jūsu lietotājiem.

Papildus pastāv jauns preferenču iestatījums, kas saistīts ar **Nepieciešamo datu paziņojumu** dialogu Microsoft AutoUpdate (MAU).

Papildinformāciju par diagnostikas datiem un saistītajiem līdzekļiem skatiet rakstā [Pārskats par konfidencialitātes kontroles līdzekļiem](overview-privacy-controls.md).

> [!NOTE]
> - Papildinformāciju par līdzīgu Office iestatījumu izmantošanu datoros, kuri darbojas ar Windows operētājsistēmu, skatiet rakstā [Politikas iestatījumu izmantošana Microsoft 365 programmās lieluzņēmumiem konfidencialitātes kontroles līdzekļu pārvaldībai](manage-privacy-controls.md).
> - Papildinformāciju par līdzīgu Office iestatījumu izmantošanu iOS ierīcēs, skatiet rakstā [Preferenču izmantošana iOS ierīcēs konfidencialitātes kontroles līdzekļu pārvaldībai](ios-privacy-preferences.md).

## <a name="setting-preferences"></a>Preferenču iestatīšana

Šie jaunie preferenču iestatījumi ir saderīgi ar CFPreferences API, un tos var iestatīt, izmantojot `defaults` komandu terminālī, vai arī to var ieviest, izmantojot konfigurācijas profilu vai mobilo ierīču pārvaldības (Mobile Device Management — MDM) serveri. Kad preferences ir ieviestas, lietotājs nevar mainīt vērtības, un visas programmā esošās vadīklas tiks rādītas kā atspējotas.

> [!NOTE]
> Jūs varat izmantot arī Office politiku mākoņpakalpojumu un tālāk minētos 5 politikas iestatījumus.
> - Konfigurēt to klienta programmatūras diagnostikas datu līmeni, kurus Office nosūta korporācijai Microsoft
> - Atļaut Office izmantot saistītos līdzekļus, kuri analizē saturu
> - Atļaut Office izmantot saistītos līdzekļus, kuri lejupielādē tiešsaistes saturu
> - Atļaut Office izmantot papildu neobligātos saistītos līdzekļus
> - Atļaut Office izmantot saistītos līdzekļus
>
> Papildinformāciju par to, kā izmantot Office politiku mākoņpakalpojumu, skatiet rakstā [Pārskats par Office politiku mākoņpakalpojumu](../overview-office-cloud-policy-service.md).


## <a name="preference-setting-for-diagnostic-data"></a>Diagnostikas datu preferenču iestatījums

Diagnostikas dati tiek izmantoti, lai uzturētu Office drošu un atjauninātu, noteiktu, diagnosticētu un novērstu problēmas, kā arī uzlabotu produktu. Papildinformāciju skatiet rakstā [Diagnostikas dati, kas no Microsoft 365 programmām lieluzņēmumiem tiek nosūtīti Microsoft](overview-privacy-controls.md#diagnostic-data-sent-from-microsoft-365-apps-for-enterprise-to-microsoft).

|Kategorija|Detalizēta informācija|
|:-----|:-----|
|**Preferenču domēns**  | `com.microsoft.office` |
|**Taustiņš**  | `DiagnosticDataTypePreference`  |
|**Datu tips**  | Virkne |
|**Iespējamās vērtības**  | `BasicDiagnosticData` *(šī vērtība iestata līmeni, kas nepieciešams)* <br/> `FullDiagnosticData` *(šī vērtība iestata līmeni, kas ir neobligāts)* <br/> `ZeroDiagnosticData` *(šī vērtība iestata līmeni, kas ir neviens)* |
|**Pieejamība** |16.28 un jaunākas versijas |

Ja jūs neiestatāt šo preferenci, korporācijai Microsoft tiek sūtīti gan obligātie, gan neobligātie diagnostikas dati, ja Office 365 (vai Microsoft 365) abonementa lietotāji tiek pierakstīti ar darba vai mācību kontu vai ja lietotāji izmanto Office 2019 darbam ar Mac lielapjoma licencēšanas versiju. Tāpat šie lietotāji nevar mainīt diagnostikas datu līmeni neatkarīgi no tā, kā iestatāt šo preferenci.

> [!NOTE]
> Esam atjauninājuši iepriekšējo rindkopu, lai precizētu, ka neobligāti diagnostikas dati tiek nosūtīti arī Microsoft, ja neietatat šo preferenci.

Citiem lietotājiem, piemēram, mājas lietotājiem ar Office 365 (vai Microsoft 365) abonementu, tiek sūtīti tikai obligātie diagnostikas dati, izņemot gadījumus, kad lietotājs izvēlas sūtīt arī neobligātos diagnostikas datus, atverot **Preferences** > **Konfidencialitāte**.

## <a name="preference-setting-for-connected-experiences-that-analyze-your-content"></a>Preferences iestatījums saistītajiem līdzekļiem, kuri analizē jūsu saturu

Saistīti līdzekļi, kas analizē jūsu saturu ir līdzekļi, kas izmanto jūsu Office saturu, lai sniegtu noformējuma ieteikumus, rediģēšanas ieteikumus, datu ieskatus un līdzīgus līdzekļus. Piemēram, PowerPoint noformētājs vai redaktors programmā Word. Saistīto līdzekļu sarakstu skatiet rakstā [Office saistītie līdzekļi](connected-experiences.md).

|Kategorija|Detalizēta informācija|
|:-----|:-----|
|**Preferenču domēns**  | `com.microsoft.office` |
|**Taustiņš**  | `OfficeExperiencesAnalyzingContentPreference`  |
|**Datu tips**  | Būla izteiksme |
|**Iespējamās vērtības**  | `TRUE` *(iespējots)* <br/> `FALSE` *(atspējots)*|
|**Pieejamība** |16.28 un jaunākas versijas |

Ja neiestatīsit šo preferenci, lietotāji varēs izmantot saistītos līdzekļus, kas analizē saturu. 

Ja lietotājam ir Office 365 (vai Microsoft 365) abonements un tas ir pierakstījies ar darba vai mācību kontu vai ja lietotājam ir Office 2019 darbam ar Mac lielapjoma licencēšanas versija, lietotājs nevar izslēgt saistītos līdzekļus, kas analizē saturu.

Citiem lietotājiem, piemēram, mājas lietotājiem ar Office 365 (vai Microsoft 365) abonementu, lietotājs var izvēlēties izslēgt saistītos līdzekļus, kas analizē saturu, dodoties uz **Preferences** > **Konfidencialitāte**.

## <a name="preference-setting-for-connected-experiences-that-download-online-content"></a>Politikas iestatījums saistītajiem līdzekļiem, kas lejupielādē tiešsaistes saturu

Saistīti līdzekļi, kas lejupielādē tiešsaistes saturu, ir līdzekļi, kas jums ļauj meklēt un lejupielādēt tiešsaistes saturu, tostarp veidnes, attēlus, 3D modeļus, video un atsauces materiālus, lai uzlabotu jūsu dokumentus. Piemēram, Office veidnes vai PowerPoint ātrais sākums. Pilnīgāku saistīto līdzekļu sarakstu skatiet rakstā [Office saistītie līdzekļi](connected-experiences.md).

|Kategorija|Detalizēta informācija|
|:-----|:-----|
|**Preferenču domēns**  | `com.microsoft.office` |
|**Taustiņš**  | `OfficeExperiencesDownloadingContentPreference`  |
|**Datu tips**  | Būla izteiksme |
|**Iespējamās vērtības**  | `TRUE` *(iespējots)* <br/> `FALSE` *(atspējots)*|
|**Pieejamība** |16.28 un jaunākas versijas |

Ja neiestatīsit šo preferenci, lietotāji varēs izmantot saistītos līdzekļus, kas lejuplādē tiešsaistes saturu.

Ja lietotājam ir Office 365 (vai Microsoft 365) abonements un tas ir pierakstījies ar darba vai mācību kontu vai ja lietotājam ir Office 2019 darbam ar Mac lielapjoma licencēšanas versija, lietotājs nevar izslēgt saistītos līdzekļus, kas lejuplādē tiešsaistes saturu.

Citiem lietotājiem, piemēram, mājas lietotājiem ar Office 365 (vai Microsoft 365) abonementu, lietotājs var izvēlēties izslēgt saistītos līdzekļus, kas lejuplādē tiešsaistes saturu, dodoties uz **Preferences** > **Konfidencialitāte**.

## <a name="preference-setting-for-optional-connected-experiences"></a>Preferences iestatījums neobligātajiem saistītajiem līdzekļiem

Papildus iepriekš minētajiem saistītajiem līdzekļiem, pastāv daži papildu saistītie līdzekļi, kurus varat atļaut lietotājiem izmantot, lietojot organizācijas kontu, kas dažkārt tiek dēvēts par darba vai mācību kontu. Piemēram, CV palīga LinkedIn līdzekļi programmā Word vai laikapstākļu josla programmā Outlook, kas izmanto MSN laika ziņas. Citus piemērus skatiet rakstā [Pārskats par Office neobligātajiem saistītajiem līdzekļiem](optional-connected-experiences.md).

|Kategorija|Detalizēta informācija|
|:-----|:-----|
|**Preferenču domēns**  | `com.microsoft.office` |
|**Taustiņš**  | `OptionalConnectedExperiencesPreference`  |
|**Datu tips**  | Būla izteiksme |
|**Iespējamās vērtības**  | `TRUE` *(iespējots)* <br/> `FALSE` *(atspējots)*|
|**Pieejamība** |16.28 un jaunākas versijas |

Ja neiestatīsit šo preferenci, neobligātie saistītie līdzekļi ir pieejami lietotājiem ar Office 365 (vai Microsoft 365) abonementu, kas ir pierakstījušies, izmantojot darba vai mācību kontu, vai lietotājiem, kuriem ir Office 2019 darbam ar Mac lielapjoma licenzētā versija. Ja vien neesat iestatījis šo preferenci uz `FALSE`, šie lietotāji var izvēlēties izslēgt neobligātos saistītos līdzekļus, dodoties uz **Preferences** > **Konfidencialitāte**.

Citiem lietotājiem, piemēram, mājas lietotājiem ar Office 365 (vai Microsoft 365) abonementu, nav pieejama opcija izslēgt neobligātos saistītos līdzekļus.

## <a name="preference-setting-for-most-connected-experiences"></a>Preferenču iestatījums lielākajai daļai saistīto līdzekļu

Šo preferenci varat izmantot, lai kontrolētu, vai lietotājiem ir pieejamas visvairāk saistītie līdzekļi.

|Kategorija|Detalizēta informācija|
|:-----|:-----|
|**Preferenču domēns**  | `com.microsoft.office` |
|**Taustiņš**  | `ConnectedOfficeExperiencesPreference`  |
|**Datu tips**  | Būla izteiksme |
|**Iespējamās vērtības**  | `TRUE` *(iespējots)* <br/> `FALSE` *(atspējots)*|
|**Pieejamība** |16.28 un jaunākas versijas |

Ja neiestatāt šo preferenci, visas saistītie līdzekļi ir pieejami jūsu lietotājiem, izņemot gadījumus, kad esat iestatījis vienu no pārējām preferencēm saistītajiem līdzekļiem, kas iepriekš norādītas, piemēram, `OfficeExperiencesAnalyzingContentPreference`.

Piemēram, ja iestatāt šo preferenci uz `FALSE`, lietotājiem nebūs pieejami tālāk norādītie saistīto līdzekļu veidi:
- Lietošanas iespējas, kas analizē jūsu saturu
- Lietošanas iespējas, kas lejupielādē tiešsaistes saturu
- Neobligātie saistītie līdzekļi

Turklāt, ja iestatāt šo preferenci uz `FALSE`, arī lielākā daļā citu saistīto līdzekļu ir izslēgti, piemēram, koprediģēšana un tiešsaistes failu krātuve. Pilnīgāku šo pārējo saistīto līdzekļu sarakstu skatiet rakstā [Office saistītie līdzekļi](connected-experiences.md).

Tomēr pat tad `FALSE`, ja iestatīsiet šo preferenci, būs pieejama tikai ierobežota Office funkcionalitāte, piemēram, pastkastes sinhronizēšana programmā Outlook, un darba grupas un Skype darbam joprojām darbosies. Joprojām būs pieejami arī [būtiskie pakalpojumi](essential-services.md), piemēram, licencēšanas pakalpojums, kurš apstiprina, ka pakalpojums Office ir atbilstoši licencēts.

Ja lietotājam ir Office 365 (vai Microsoft 365) abonements un tas ir pierakstījies ar darba vai mācību kontu vai ja lietotājam ir Office 2019 darbam ar Mac lielapjoma licencēšanas versija, lietotājs nevar izslēgt lielāko daļu saistīto līdzekļu.

Citiem lietotājiem, piemēram, mājas lietotājiem ar Office 365 (vai Microsoft 365) abonementu, lietotājs var izvēlēties izslēgt lielāko daļu saistītos līdzekļus, dodoties uz **Preferences** > **Konfidencialitāte**.

## <a name="preference-setting-for-the-required-data-notice-dialog-for-microsoft-autoupdate"></a>Preferenču iestatījums nepieciešamajam datu paziņojumu dialogam Microsoft AutoUpdate

Microsoft AutoUpdate (MAU) pirmo reizi tiek palaista versija 4.12 vai jaunāka versija, un lietotāji redzēs **nepieciešamo datu paziņojumu** dialoglodziņu, kurā ir sniegta informācija par to, kādi dati no MAU tiek sūtīti Microsoft.

Ja nevēlaties, lai lietotāji redzētu šo **pieprasīto datu paziņojumu** dialoglodziņu Microsoft AutoUpdate, varat iestatīt tālāk norādīto preferenci. Neatkarīgi no tā, kuru vērtību iestatāt, šis dialoglodziņš netiks rādīts jūsu lietotājiem.

|Kategorija|Detalizēta informācija|
|:-----|:-----|
|**Preferenču domēns**  | `com.microsoft.autoupdate2` |
|**Taustiņš**  | `AcknowledgedDataCollectionPolicy`  |
|**Datu tips**  | Virkne |
|**Iespējamās vērtības**  | `RequiredDataOnly` <br/> `RequiredAndOptionalData`|
|**Pieejamība** |4.12 un jaunākas versijas |

Ja ļaujat lietotājiem redzēt šo dialoglodziņu, pēc tam, kad lietotājs izvēlas **Labi**, tiek ierakstīta `AcknowledgedDataCollectionPolicy` vērtība `RequiredDataOnly`, un dialoglodziņš lietotājam netiks rādīts vēlreiz.


## <a name="related-articles"></a>Saistītie raksti

- [Konfigurācijas profila atsauce (Apple Developer dokumentācija)](https://go.microsoft.com/fwlink/p/?linkid=852998)
- [Office darbam ar Mac preferenču izvietošana](../mac/deploy-preferences-for-office-for-mac.md)
- [Konta konfidencialitātes iestatījumi](https://support.office.com/article/3e7bc183-bf52-4fd0-8e6b-78978f7f121b#ID0EAADAAA=Mac)
