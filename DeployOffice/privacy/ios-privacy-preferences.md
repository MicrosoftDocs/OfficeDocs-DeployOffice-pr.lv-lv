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
# <a name="use-preferences-to-manage-privacy-controls-for-office-on-ios-devices"></a>Izmantojiet preferences Office darbam ar iOS ierīcēm konfidencialitātes kontroles līdzekļu pārvaldībai

Office darbam ar iOS ierīcēm ir jauni preferenču iestatījumi, ar kuriem varat mainīt preferences attiecībā uz turpmāko:

- ***Diagnostikas dati***, kas tiek apkopoti un nosūtīti korporācijai Microsoft par izmantoto Office klienta programmatūru.

- ***Saistītie līdzekļi***, kas izmanto mākoņa funkcionalitāti, lai nodrošinātu uzlabotus Office līdzekļus jums un jūsu lietotājiem.

Papildinformāciju par diagnostikas datiem un saistītajiem līdzekļiem skatiet rakstā [Pārskats par konfidencialitātes kontroles līdzekļiem](overview-privacy-controls.md).

Šie preferenču iestatījumi attiecas uz šādām lietojumprogrammām:
- Word darbam ar iOS, Excel darbam ar iOS un PowerPoint darbam ar iOS versija 2.30 vai jaunāka.
- OneNote darbam ar iOS versija 16.30 vai jaunāka.
- Visio Viewer darbam ar iOS versija 1.17 vai jaunāka.

> [!NOTE]
> Papildinformāciju par līdzīgu Office iestatījumu izmantošanu datoros, kuros darbojas operētājsistēma macOS, skatiet rakstā [Preferenču izmantošana Office darbam ar Mac konfidencialitātes kontroles līdzekļu pārvaldībai](mac-privacy-preferences.md).


## <a name="setting-device-preferences"></a>Ierīces preferenču iestatīšana
Šie jaunie preferenču iestatījumi, instalējot Office programmu, var tikt iestatīti arī ierīces līmenī, izmantojot mobilo ierīču pārvaldības (Mobile Device Management — MDM) serveri. Daudzi MDM serveri ļauj IT administratoriem pievienot neobligātu konfigurācijas vārdnīcu, kad serveris nosūta `InstallApplication` MDM komandu uz iOS ierīci. Lai saņemtu papildinformāciju, skatiet savu MDM servera dokumentāciju.

Vārdnīca tiek parādīta kā galveno/vērtību pāru kopu XML formātā. Piemērs:

```xml
<dict>
    <key>DiagnosticDataTypePreference</key>
    <string>BasicDiagnosticData</string>
</dict>
```

Pēc nosūtīšanas uz ierīci konfigurācijas vārdnīca atrodas zem `com.apple.managed.configuration` taustiņa, kur tā tiks lasīta, kad tiek palaista Office programma.

## <a name="preference-setting-for-diagnostic-data"></a>Diagnostikas datu preferenču iestatījums

Diagnostikas dati tiek izmantoti, lai uzturētu Office drošu un atjauninātu, noteiktu, diagnosticētu un novērstu problēmas, kā arī uzlabotu produktu. Papildinformāciju skatiet rakstā [Diagnostikas dati, kas no Office 365 ProPlus tiek nosūtīti Microsoft](overview-privacy-controls.md#diagnostic-data-sent-from-office-365-proplus-to-microsoft).

|||
|:-----|:-----|
|**Taustiņš**  | `DiagnosticDataTypePreference`  |
|**Datu tips**  | Virkne |
|**Iespējamās vērtības**  | `BasicDiagnosticData` *(tiek iestatīts līmenis, kas nepieciešams)* <br/> `FullDiagnosticData` *(tiek iestatīts līmenis kā neobligāts)* <br/> `ZeroDiagnosticData` *(līmenis netiek iestatīts)* |

Ja neiestatīsit šo preferenci, Microsoft tiks sūtīti tikai nepieciešamie diagnostikas dati, ja lietotāji ar Office 365 abonementu būs pierakstījušies, izmantojot darba vai mācību kontu. Tāpat šie lietotāji nevar mainīt diagnostikas datu līmeni neatkarīgi no tā, kā iestatāt šo preferenci.

Citiem lietotājiem, piemēram, mājas lietotājiem ar Office 365 abonementu, tiek sūtīti tikai nepieciešamie diagnostikas dati, izņemot gadījumus, kad lietotājs izvēlas sūtīt neobligātos diagnostikas datus, dodoties uz **Iestatījumi** > **Konfidencialitātes iestatījumi**.


## <a name="preference-setting-for-connected-experiences-that-analyze-your-content"></a>Preferences iestatījums saistītajiem līdzekļiem, kuri analizē jūsu saturu

Saistīti līdzekļi, kas analizē jūsu saturu ir līdzekļi, kas izmanto jūsu Office saturu, lai sniegtu noformējuma ieteikumus, rediģēšanas ieteikumus, datu ieskatus un līdzīgus līdzekļus. Piemēram, noformējiet idejas programmā PowerPoint. Saistīto līdzekļu sarakstu skatiet rakstā [Office saistītie līdzekļi](connected-experiences.md).

|||
|:-----|:-----|
|**Taustiņš**  | `OfficeExperiencesAnalyzingContentPreference`  |
|**Datu tips**  | Būla izteiksme |
|**Iespējamās vērtības**  | `TRUE` *(iespējots)* <br/> `FALSE` *(atspējots)*|


Ja neiestatīsit šo preferenci, lietotāji varēs izmantot saistītos līdzekļus, kas analizē saturu.

Ja lietotājam ir Office 365 abonements un ir pierakstījies ar darba vai mācību kontu, lietotājs nevar izslēgt saistītos līdzekļus, kas analizē saturu.

Citiem lietotājiem, piemēram, mājas lietotājiem ar Office 365 abonementu, lietotājs var izvēlēties izslēgt saistītos līdzekļus, kas analizē saturu, dodoties uz **Iestatījumi** > **Konfidencialitāte**.

## <a name="preference-setting-for-connected-experiences-that-download-online-content"></a>Politikas iestatījums saistītajiem līdzekļiem, kas lejupielādē tiešsaistes saturu

Saistīti līdzekļi, kas lejupielādē tiešsaistes saturu, ir līdzekļi, kas jums ļauj meklēt un lejupielādēt tiešsaistes saturu, tostarp veidnes, attēlus, video un atsauces materiālus, lai uzlabotu jūsu dokumentus. Piemēram, Office veidnes vai ievietojot tiešsaistes ikonu. Saistīto līdzekļu sarakstu skatiet rakstā [Office saistītie līdzekļi](connected-experiences.md).

|||
|:-----|:-----|
|**Taustiņš**  | `OfficeExperiencesDownloadingContentPreference`  |
|**Datu tips**  | Būla izteiksme |
|**Iespējamās vērtības**  | `TRUE` *(iespējots)* <br/> `FALSE` *(atspējots)*|


Ja neiestatīsit šo preferenci, lietotāji varēs izmantot saistītos līdzekļus, kas lejuplādē tiešsaistes saturu.

Ja lietotājam ir Office 365 abonements un ir pierakstījies ar darba vai mācību kontu, lietotājs nevar izslēgt saistītos līdzekļus, kas lejuplādē tiešsaistes saturu.

Citiem lietotājiem, piemēram, mājas lietotājiem ar Office 365 abonementu, lietotājs var izvēlēties izslēgt saistītos līdzekļus, kas lejuplādē tiešsaistes saturu, dodoties uz **Iestatījumi** > **Konfidencialitātes iestatījumi**.

## <a name="preference-setting-for-optional-connected-experiences"></a>Preferences iestatījums neobligātajiem saistītajiem līdzekļiem

Papildus iepriekš minētajiem saistītajiem līdzekļiem, pastāv daži papildu saistītie līdzekļi, kurus varat atļaut lietotājiem izmantot, lietojot organizācijas kontu, kas dažkārt tiek dēvēts par darba vai mācību kontu. Piemēram, sistēmas Office pievienojumprogrammas, kas tiek lejupielādētas no Office veikala uz jūsu ierīci. Citus piemērus skatiet rakstā [Pārskats par Office neobligātajiem saistītajiem līdzekļiem](optional-connected-experiences.md).

|||
|:-----|:-----|
|**Taustiņš**  | `OptionalConnectedExperiencesPreference`  |
|**Datu tips**  | Būla izteiksme |
|**Iespējamās vērtības**  | `TRUE` *(iespējots)* <br/> `FALSE` *(atspējots)*|


Ja neiestatīsit šo preferenci, lietotājiem ar Office 365 abonementu, kas būs pierakstījušies, izmantojot darba vai mācību kontu, būs pieejami neobligātie saistītie līdzekļi. Ja vien neesat iestatījis šo preferenci uz APLAMI, šie lietotāji var izvēlēties izslēgt neobligātos saistītos līdzekļus, dodoties uz **Iestatījumi** > **Konfidencialitātes iestatījumi**.

Citiem lietotājiem, piemēram, mājas lietotājiem ar Office 365 abonementu, nav pieejama opcija izslēgt neobligātos saistītos līdzekļus.