---
title: Office nepieciešamie pakalpojuma dati
ms.author: danbrown
author: DHB-MSFT
manager: laurawi
audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection: Ent_O365
ms.custom:
- Ent_Office_ProPlus
- Ent_Office_Privacy
description: Office administratoriem sniedz pārskatu par nepieciešamajiem pakalpojuma datiem, kas tiek apkopoti saistībā ar Office saistītajiem līdzekļiem.
hideEdit: true
ms.openlocfilehash: eaa659e375d3d5c29d5410ab53db7ae583df6e9d
ms.sourcegitcommit: 02c4120c0b10bfe378d21d60699ae49aaef97834
ms.translationtype: HT
ms.contentlocale: lv-LV
ms.lasthandoff: 10/15/2019
ms.locfileid: "37510613"
---
# <a name="required-service-data-for-office"></a>Office nepieciešamie pakalpojuma dati 

> [!IMPORTANT]
> Informācija šajā rakstā attiecas uz tālāk minētās Office klienta programmatūras versiju 1904 vai jaunāku versiju, kas instalēta datorā, kurā darbojas sistēma Windows:
> - Office 365 ProPlus un Office 365 Business
> - Office 365 individuālai lietošanai, Office 365 mājas lietošanai vai citas Office versijas, kas ir daļa no Office 365 abonementa.
> - Project un Visio, kas ir iekļautas dažos abonēšanas plānos, piemēram, Project Online Professional plānā vai Visio Online 2. plānā.
>
> Šī informācija attiecas arī uz tālāk norādīto sistēmas Office darbam ar Mac lietojumprogrammu versiju 16.28 vai jaunākām versijām: Excel, Outlook, OneNote, PowerPoint un Word.

Office sastāv no klienta programmām un saistītajiem līdzekļiem, kas paredzēti, lai jūs varētu efektīvāk veidot, sazināties un sadarboties. Darbs kopā ar citiem lietotājiem, strādājot pie dokumenta, kas glabājas OneDrive darbam krātuvē, vai Word dokumenta satura tulkošana citā valodā ir saistīto līdzekļu piemēri.

Nepieciešamie pakalpojuma dati ir svarīgi, jo tie mums ļauj klientiem nodrošināt šos mākoņa saistītos līdzekļus un palīdz šos līdzekļus padarīt drošus, kā arī ļauj tiem darboties, kā paredzēts. Nepieciešamos pakalpojuma datus veido trīs veidu informācija.

- **Klienta saturs**, kas ir saturs, kuru veidojat, izmantojot Office, piemēram, Word dokumentā rakstītais teksts, un lietojat saistībā ar saistīto līdzekli.
- **Funkcionālie dati**, kas ietver saistīto līdzekļu darbībai nepieciešamo informāciju, piemēram, konfigurācijas informācija saistībā ar programmu.
- **Pakalpojuma diagnostikas dati**, kas ir dati, kuri ir nepieciešami, lai pakalpojumu uzturētu drošu, atjauninātu un tādu, kas darbojas, kā paredzēts. Tā kā šie dati ir saistīti tikai ar atbilstošo saistīto līdzekli, tie ir nodalīti no nepieciešamā un neobligātā diagnostikas datu līmeņa.

## <a name="example-of-required-service-data-for-a-connected-experience"></a>Saistītajam līdzeklim nepieciešamo pakalpojuma datu piemērs

Lai palīdzētu jums izprast nepieciešamos pakalpojuma datus, tālāk ir sniegts scenārija piemērs, izmantojot PowerPoint noformētāju, kas ir saistītais līdzeklis, kuru varat izmantot, veidojot prezentācijas slaidus. PowerPoint noformētājs palīdz uzlabot jūsu slaidus, automātiski ģenerējot noformējuma idejas, no kurām varat izvēlēties. Kad ievietojat saturu slaidā, noformētājs darbojas fonā, lai šo saturu saskaņotu ar profesionāli noformētiem izkārtojumiem.

Nepieciešamie pakalpojuma dati, kas tiek nosūtīti korporācijai Microsoft, lai iespējotu šo saistīto līdzekli, var ietvert:

- *Klienta saturs*, piemēram, teksts vai attēli, kuru pievienojāt slaidam.
- *Funkcionālie dati*, piemēram, ar kuru slaidu strādājat, kā arī slaida izkārtojums.
- *Pakalpojuma diagnostikas dati*, piemēram, notikumi, kas mums pastāsta, vai slaidam tika pareizi lietota noformējuma ideja un vai pakalpojuma izsaukumi tika veikti pareizi.

## <a name="view-and-manage-required-service-data"></a>Nepieciešamo pakalpojuma datu skatīšana un pārvaldība

Pakalpojuma diagnostikas datus varat skatīt, izmantojot diagnostikas datu skatītāju. Lai iegūtu papildinformāciju, skatiet rakstu [Pakalpojuma diagnostikas datu notikumu piemēri](#examples-of-events-for-service-diagnostic-data).

Sniedzam jums iespēju izvēlēties, kāda veida Office saistītos līdzekļus vēlaties izmantot, un tas pēc tam nosaka, kādi nepieciešamie pakalpojuma dati mums tiek nosūtīti. Piemēram, PowerPoint noformētājs ir viens no vairākiem saistītajiem līdzekļiem, kas analizē jūsu saturu. Ja izvēlaties izslēgt saistīto līdzekli, kas analizē saturu, nekādi nepieciešamie pakalpojuma dati par PowerPoint noformētāju mums netiek sūtīti, jo PowerPoint noformētājs nav pieejams lietošanai.

Nepieciešamie pakalpojuma dati tiek apkopoti un nosūtīti korporācijai Microsoft saistībā ar Office būtiskajiem pakalpojumiem, piemēram, licencēšanas pakalpojumu, kas apstiprina, ka esat pareizi licencēts Office izmantošanai. Šie būtisko pakalpojumu dati tiek nosūtīti neatkarīgi no citiem ar konfidencialitāti saistītajiem iestatījumiem, kas jums ir konfigurēti.

Papildinformāciju skatiet šeit:

- [Office saistītie līdzekļi](connected-experiences.md)
- [Office būtiskie pakalpojumi](essential-services.md)
- [Diagnostikas datu skatītāja izmantošana ar Office](https://support.office.com/article/cf761ce9-d805-4c60-a339-4e07f3182855)

Ja esat organizācijas administrators, iespējams, jūs interesēs arī šie raksti:

- [Pārskats par konfidencialitātes kontroles līdzekļiem pakalpojumā Office 365 ProPlus](overview-privacy-controls.md)
- [Politikas iestatījumu izmantošana Office 365 ProPlus konfidencialitātes kontroles pārvaldībai](manage-privacy-controls.md)
- [Preferenču izmantošana Office darbam ar Mac konfidencialitātes kontroles līdzekļu pārvaldībai](mac-privacy-preferences.md)
- [Preferenču izmantošana Office darbam ar iOS ierīcēm konfidencialitātes kontroles līdzekļu pārvaldībai](ios-privacy-preferences.md)

## <a name="examples-of-events-for-service-diagnostic-data"></a>Pakalpojuma diagnostikas datu notikumu piemēri

Pakalpojuma diagnostikas dati ir redzami diagnostikas datu skatītājā un ir izkārtoti tajās pašās kategorijās, kuras izmanto nepieciešamie un neobligātie diagnostikas dati. Piemēram *Produktu un pakalpojumu lietojums* vai *Produktu un pakalpojumu veiktspēja.*

Pakalpojuma diagnostikas datu notikumi sniedz mums nepieciešamo informāciju par to, vai saistītais līdzeklis darbojas tā, kā to varētu sagaidīt klients. Piemēram, vai pakalpojums, ko izmanto saistītais līdzeklis, tika sekmīgi startēts un bija pieejams, kad tas bija nepieciešams, vai, mijiedarbojoties ar pakalpojumu, radās kļūdas vai citas neparedzētas problēmas (avārijas) un kāda bija pakalpojuma atsaucība vai veiktspēja.

Nākamajā tabulā sniegti daži pakalpojuma diagnostikas datu notikumu piemēri.

| **Nosaukums**      | **Apraksts**    |
| ---------- | --------------------- |
| Office.Excel.Coauth.SaveXrr     | Notikums, kas tiek izraisīts programmā Excel, izmantojot sadarbības pakalpojumu, un kas sniedz detalizētu informāciju par atsevišķajiem pārskatījumiem, kas tiek rakstīti pārskatījumu žurnālā. Tas nodrošina latentuma pārraudzību un norāda Excel kļūdas, kas ir saistītas ar sadarbību  |
| Office.Excel.Coauth.CloseWorkbook  | Notikums, izraisīts programmā Excel, izmantojot sadarbības pakalpojumu, kas ziņo par darbgrāmatas aizvēršanu. Tas ir nepieciešams, lai noteiktu atkārtotas ielādes un automātiskās atsvaidzināšanas kļūdas. Tas nodrošina sadarbības pakalpojuma darbību sekmju mērījumu.   |
| Office.Security.OCX.NonTrustedEncounter    | Notikums, kas tiek izraisīts Office programmās (tostarp Word, Excel, Outlook, PowerPoint un Visio), kad lietotājs atver neuzticamu dokumentu, kurā ir ActiveX vadīkla. Tas tiek izmantots, lai vispārīgi novērtētu to ActiveX vadīklu lietojumu, kas ir iegultas Office dokumentos, un veicinātu drošības uzlabojumus, reaģējot uz drošības incidentiem.  |
| Office.Security.UrlReputation.GetUrlReputation | Notikums, kas tiek izraisīts Office programmās (tostarp Word, Excel, PowerPoint, Visio un Publisher) un kas izseko drošo saišu izsaukumu izdošanos vai kļūmi. Tas tiek izmantots, lai pārliecinātos, vai drošo saišu pakalpojums darbojas pareizi, un lai noteiktu problēmas.  |
| Office.Voice.VoiceManager.StreamingAudio   | Notikums, kas tiek izraisīts Office programmās (tostarp Word, Outlook un PowerPoint) un kas sniedz informāciju par audio straumēšanas runas pakalpojumam darbspēju. Tajā ir informācija par straumētā audio lielumu un visām kļūdām, kas varētu būt radušās. Šī informācija tiek izmantota, lai pārraudzītu pakalpojuma darbspēju un noteiktu problēmas, par kurām varētu būt ziņojuši klienti. |
