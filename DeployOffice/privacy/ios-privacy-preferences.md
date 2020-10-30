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
ms.openlocfilehash: ed24ac934625bba61eac25e764a892d48365c005
ms.sourcegitcommit: 596a0a60394011aafe1119f353ac76f27e1a4d1b
ms.translationtype: HT
ms.contentlocale: lv-LV
ms.lasthandoff: 10/29/2020
ms.locfileid: "48794664"
---
# <a name="use-preferences-to-manage-privacy-controls-for-office-on-ios-devices"></a>Izmantojiet preferences Office darbam ar iOS ierīcēm konfidencialitātes kontroles līdzekļu pārvaldībai

> [!NOTE]
> Sarakstu ar Office produktiem, uz kuriem attiecas šī konfidencialitātes informācija, skatiet rakstā [Konfidencialitātes kontroles līdzekļi, kas pieejami Office produktiem](products-versions-privacy-controls.md).

Office darbam ar iOS ierīcēm ir jauni preferenču iestatījumi, ar kuriem varat kontrolēt iestatījumus attiecībā uz turpmāko:

- ***Diagnostikas dati** _, kas tiek apkopoti un nosūtīti korporācijai Microsoft par izmantoto Office klienta programmatūru.

- _*_Saistītie līdzekļi_*_ , kas izmanto mākoņa funkcionalitāti, lai nodrošinātu uzlabotus Office līdzekļus jums un jūsu lietotājiem.

Papildinformāciju par diagnostikas datiem un saistītajiem līdzekļiem skatiet rakstā [Pārskats par konfidencialitātes kontroles līdzekļiem](overview-privacy-controls.md).

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

> [!NOTE]
> Jūs varat izmantot arī Office politiku mākoņpakalpojumu un tālāk minētos 4 politikas iestatījumus.
> - Konfigurēt to klienta programmatūras diagnostikas datu līmeni, kurus Office nosūta korporācijai Microsoft
> - Atļaut Office izmantot saistītos līdzekļus, kuri analizē saturu
> - Atļaut Office izmantot saistītos līdzekļus, kuri lejupielādē tiešsaistes saturu
> - Atļaut Office izmantot papildu neobligātos saistītos līdzekļus
>
> Konfidencialitātes iestatījumus Outlook darbam ar iOS un OneDrive darbam ar iOS ir iespējams konfigurēt tikai izmantojot Office mākoņa politikas pakalpojumu.
>
> Papildinformāciju par to, kā izmantot Office politiku mākoņpakalpojumu, skatiet rakstā [Pārskats par Office politiku mākoņpakalpojumu](../overview-office-cloud-policy-service.md).

## <a name="preference-setting-for-diagnostic-data"></a>Diagnostikas datu preferenču iestatījums

Diagnostikas dati tiek izmantoti, lai uzturētu Office drošu un atjauninātu, noteiktu, diagnosticētu un novērstu problēmas, kā arī uzlabotu produktu. Papildinformāciju skatiet rakstā [Diagnostikas dati, kas no Microsoft 365 programmām lieluzņēmumiem tiek nosūtīti Microsoft](overview-privacy-controls.md#diagnostic-data-sent-from-microsoft-365-apps-for-enterprise-to-microsoft).

|||
|:-----|:-----|
|_ *Taustiņš**  | `DiagnosticDataTypePreference`  |
|**Datu tips**  | Virkne |
|**Iespējamās vērtības**  | `BasicDiagnosticData` *(tiek iestatīts līmenis, kas nepieciešams)* <br/> `FullDiagnosticData` *(tiek iestatīts līmenis kā neobligāts)* <br/> `ZeroDiagnosticData` *(līmenis netiek iestatīts)* |

Ja neiestatīsit šo preferenci, Microsoft tiks sūtīti tikai nepieciešamie diagnostikas dati, ja lietotāji ar Office 365 (vai Microsoft 365) abonementu būs pierakstījušies, izmantojot darba vai mācību kontu. Tāpat šie lietotāji nevar mainīt diagnostikas datu līmeni neatkarīgi no tā, kā iestatāt šo preferenci.

Citiem lietotājiem, piemēram, mājas lietotājiem ar Office 365 (vai Microsoft 365) abonementu, tiek sūtīti tikai nepieciešamie diagnostikas dati, izņemot gadījumus, kad lietotājs izvēlas sūtīt neobligātos diagnostikas datus, dodoties uz **Iestatījumi** > **Konfidencialitātes iestatījumi** .


## <a name="preference-setting-for-connected-experiences-that-analyze-your-content"></a>Preferences iestatījums saistītajiem līdzekļiem, kuri analizē jūsu saturu

Saistīti līdzekļi, kas analizē jūsu saturu ir līdzekļi, kas izmanto jūsu Office saturu, lai sniegtu noformējuma ieteikumus, rediģēšanas ieteikumus, datu ieskatus un līdzīgus līdzekļus. Piemēram, noformējiet idejas programmā PowerPoint. Saistīto līdzekļu sarakstu skatiet rakstā [Office saistītie līdzekļi](connected-experiences.md).

|||
|:-----|:-----|
|**Taustiņš**  | `OfficeExperiencesAnalyzingContentPreference`  |
|**Datu tips**  | Būla izteiksme |
|**Iespējamās vērtības**  | `TRUE` *(iespējots)* <br/> `FALSE` *(atspējots)*|


Ja neiestatīsit šo preferenci, lietotāji varēs izmantot saistītos līdzekļus, kas analizē saturu.

Ja lietotājam ir Office 365 (vai Microsoft 365) abonements un ir pierakstījies ar darba vai mācību kontu, lietotājs nevar izslēgt saistītos līdzekļus, kas analizē saturu.

Citiem lietotājiem, piemēram, mājas lietotājiem ar Office 365 (vai Microsoft 365) abonementu, lietotājs var izvēlēties izslēgt saistītos līdzekļus, kas analizē saturu, dodoties uz **Iestatījumi** > **Konfidencialitāte** .

## <a name="preference-setting-for-connected-experiences-that-download-online-content"></a>Politikas iestatījums saistītajiem līdzekļiem, kas lejupielādē tiešsaistes saturu

Saistīti līdzekļi, kas lejupielādē tiešsaistes saturu, ir līdzekļi, kas jums ļauj meklēt un lejupielādēt tiešsaistes saturu, tostarp veidnes, attēlus, video un atsauces materiālus, lai uzlabotu jūsu dokumentus. Piemēram, Office veidnes vai ievietojot tiešsaistes ikonu. Saistīto līdzekļu sarakstu skatiet rakstā [Office saistītie līdzekļi](connected-experiences.md).

|||
|:-----|:-----|
|**Taustiņš**  | `OfficeExperiencesDownloadingContentPreference`  |
|**Datu tips**  | Būla izteiksme |
|**Iespējamās vērtības**  | `TRUE` *(iespējots)* <br/> `FALSE` *(atspējots)*|


Ja neiestatīsit šo preferenci, lietotāji varēs izmantot saistītos līdzekļus, kas lejuplādē tiešsaistes saturu.

Ja lietotājam ir Office 365 (vai Microsoft 365) abonements un ir pierakstījies ar darba vai mācību kontu, lietotājs nevar izslēgt saistītos līdzekļus, kas lejuplādē tiešsaistes saturu.

Citiem lietotājiem, piemēram, mājas lietotājiem ar Office 365 (vai Microsoft 365) abonementu, lietotājs var izvēlēties izslēgt saistītos līdzekļus, kas lejuplādē tiešsaistes saturu, dodoties uz **Iestatījumi** > **Konfidencialitāte** .

## <a name="preference-setting-for-optional-connected-experiences"></a>Preferences iestatījums neobligātajiem saistītajiem līdzekļiem

Papildus iepriekš minētajiem saistītajiem līdzekļiem, pastāv daži papildu saistītie līdzekļi, kurus varat atļaut lietotājiem izmantot, lietojot organizācijas kontu, kas dažkārt tiek dēvēts par darba vai mācību kontu. Piemēram, sistēmas Office pievienojumprogrammas, kas tiek lejupielādētas no Office veikala uz jūsu ierīci. Citus piemērus skatiet rakstā [Pārskats par Office neobligātajiem saistītajiem līdzekļiem](optional-connected-experiences.md).

|||
|:-----|:-----|
|**Taustiņš**  | `OptionalConnectedExperiencesPreference`  |
|**Datu tips**  | Būla izteiksme |
|**Iespējamās vērtības**  | `TRUE` *(iespējots)* <br/> `FALSE` *(atspējots)*|


Ja neiestatīsit šo preferenci, lietotājiem ar Office 365 (vai Microsoft 365) abonementu, kas būs pierakstījušies, izmantojot darba vai mācību kontu, būs pieejami neobligātie saistītie līdzekļi. Ja vien neesat iestatījis šo preferenci uz APLAMI, šie lietotāji var izvēlēties izslēgt neobligātos saistītos līdzekļus, dodoties uz **Iestatījumi** > **Konfidencialitātes iestatījumi** .

Citiem lietotājiem, piemēram, mājas lietotājiem ar Office 365 (vai Microsoft 365) abonementu, nav pieejama opcija izslēgt neobligātos saistītos līdzekļus.