---
title: Neobligātie Office diagnostikas dati
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
description: Office administratoriem sniedz informāciju par neobligātajiem Office diagnostikas datiem, tostarp dažus notikumu piemērus.
hideEdit: true
ms.openlocfilehash: d772a649a78a88112a270e839834cbe48141217f
ms.sourcegitcommit: 02c4120c0b10bfe378d21d60699ae49aaef97834
ms.translationtype: HT
ms.contentlocale: lv-LV
ms.lasthandoff: 10/15/2019
ms.locfileid: "37510155"
---
# <a name="optional-diagnostic-data-for-office"></a>Neobligātie Office diagnostikas dati

> [!IMPORTANT]
> Informācija šajā rakstā attiecas uz tālāk minētās Office klienta programmatūras versiju 1904 vai jaunāku versiju, kas instalēta datorā, kurā darbojas sistēma Windows:
> - Office 365 ProPlus un Office 365 Business
> - Office 365 individuālai lietošanai, Office 365 mājas lietošanai vai citas Office versijas, kas ir daļa no Office 365 abonementa.
> - Project un Visio, kas ir iekļautas dažos abonēšanas plānos, piemēram, Project Online Professional plānā vai Visio Online 2. plānā.
>
> Šī informācija attiecas arī uz tālāk norādīto sistēmas Office darbam ar Mac programmu versiju 16.28 vai jaunākām versijām: Excel, Outlook, OneNote, PowerPoint un Word.

Diagnostikas dati tiek izmantoti, lai uzturētu Office drošu un atjauninātu, noteiktu, diagnosticētu un novērstu problēmas, kā arī uzlabotu produktu. Šie dati neietver lietotāja vārdu vai e-pasta adresi, failu saturu vai informāciju par programmām, kas nav saistītas ar Office.

Šie diagnostikas dati tiek apkopoti un nosūtīti korporācijai Microsoft par Office klienta programmatūru, kas tiek lietota datoros, kuros darbojas operētājsistēma Windows. Daži diagnostikas dati ir nepieciešami, bet daži diagnostikas dati ir neobligāti. Piedāvājam jums iespēju izvēlēties, vai sūtīt mums nepieciešamos vai neobligātos diagnostikas datus, izmantojot tādus konfidencialitātes kontroles līdzekļus kā organizācijas politikas iestatījumus. Mums sūtāmos diagnostikas datus varat skatīt, izmantojot diagnostikas datu skatītāju.

***Neobligātie diagnostikas dati*** ir papildu dati, kas palīdz mums uzlabot produktu un nodrošina papildu informāciju, kura palīdz noteikt, diagnosticēt un novērst problēmas.

Ja izvēlaties nosūtīt mums neobligātos diagnostikas datus, tiek iekļauti arī nepieciešamie diagnostikas dati.

Neobligātās diagnostikas datu piemēri ietver datus, kurus iegūstam par formām, ko lietotāji ievieto Word dokumentos, un kuri ļauj mums sniegt labākas opcijas, kā arī datus, kurus apkopojam par laiku, kas nepieciešams PowerPoint slaida parādīšanai ekrānā (ja tas notiek lēni), lai tā varētu uzlabot lietošanas pieredzi.

Papildinformāciju par diagnostikas datiem lasiet šajos rakstos:

- [Nepieciešamie Office diagnostikas dati](required-diagnostic-data.md)
- [Diagnostikas datu skatītāja izmantošana ar Office](https://support.office.com/article/cf761ce9-d805-4c60-a339-4e07f3182855)

Ja esat organizācijas administrators, iespējams, jūs interesēs arī šie raksti:

- [Pārskats par konfidencialitātes kontroles līdzekļiem pakalpojumā Office 365 ProPlus](overview-privacy-controls.md)
- [Politikas iestatījumu izmantošana Office 365 ProPlus konfidencialitātes kontroles pārvaldībai](manage-privacy-controls.md)
- [Preferenču izmantošana Office darbam ar Mac konfidencialitātes kontroles līdzekļu pārvaldībai](mac-privacy-preferences.md)
- [Preferenču izmantošana Office darbam ar iOS ierīcēm konfidencialitātes kontroles līdzekļu pārvaldībai](ios-privacy-preferences.md)

## <a name="categories-of-optional-diagnostic-data"></a>Neobligāto diagnostikas datu kategorijas

Neobligātie diagnostikas dati ir izkārtoti šādās kategorijās:

- Programmatūras iestatīšana un inventārs
- Produktu un pakalpojumu lietojums
- Produktu un pakalpojumu veiktspēja
- Ierīču savienojamība un konfigurācija

Šīs kategorijas tiek rādītas diagnostikas datu skatītājā un ir tās pašas kategorijas, kas tiek izmantotas, runājot par nepieciešamajiem diagnostikas datiem.

Nākamajās sadaļās ir sniegts katras kategorijas apraksts un notikumu piemēri.

## <a name="software-setup-and-inventory-events"></a>Programmatūras iestatīšanas un inventāra notikumi

Šī kategorija ietver notikumus, kas var attiekties uz šādām jomām:

- Instalētais produkts un versija un instalēšanas statuss
- Programmatūras pievienojumprogrammas un to iestatījumi.
- Dokumenta, līdzekļa un pievienojumprogrammas kļūdas nosacījumi, kas var negatīvi ietekmēt drošību, tostarp produktu atjauninājumu gatavību.

Nākamajā tabulā ir sniegti šīs kategorijas notikumu piemēri un šo notikumu apraksti.

| **Notikuma nosaukums**   | **Notikuma apraksts**  |
| ---- | ---- |
| Office.Extensibility.AppCommands.GetRibbonUpdatesForUserId | Šis notikums norāda, vai Word sekmīgi atjaunina lenti Word lietotāja interfeisā, kad lietotājs maina savu identitāti. Šo gadījumu izmantojam, lai noteiktu nepareizas iestatīšanas un citas problēmas, kas var ietekmēt Office lietotāja interfeisu. |
| Office.Extensibility.AppCommands.AppCmdInstall   | Šis notikums sniedz informāciju par Office pievienojumprogrammu, kas lietotājam ir instalēta, tostarp programma ID, operētājsistēmas būvējumu un versiju, instalēšanas sekmēm un instalēšanas ilgumu.  |

## <a name="product-and-service-usage-events"></a>Produktu un pakalpojumu lietojuma notikumi

Šī kategorija ietver notikumus, kas var attiekties uz šādām jomām:

- Programmas funkcionalitātes sekmes. Attiecas tikai uz programmas un dokumentu atvēršanu un aizvēršanu, failu rediģēšana un failu koplietošanu (sadarbību).
- Nosaka, vai ir notikuši konkrēti līdzekļu notikumi, piemēram, startēšana vai apturēšana, un vai līdzeklis darbojas.
- Office pieejamības līdzekļi

Nākamajā tabulā ir sniegti šīs kategorijas notikumu piemēri un šo notikumu apraksti.

| **Notikuma nosaukums**   | **Notikuma apraksts**  |
| ------ | ------- |
| Office.Word.Commanding.Highlight  | Šis notikums norāda, ka programma Word ir izpildījusi komandu, lai iezīmētu tekstu. Šo notikumu izmantojam kļūdu noteikšanai teksta iezīmēšana komandā.  |
| Office.Translator.AddInLoaded   | Periodiskais kontrolziņojums, lai norādītu, ka tulkošanas līdzeklis ir ielādēts un sekmīgi atveidots.  |
| Office.Graphics.GVizInsertShape |Izseko formas ievietošanas līdzekļa darbības programmā Word, kā arī ziņo, norādot detalizētu informāciju par ievietoto formu veidiem un avotu.| 
| Office.PowerPoint.PPT.Desktop.SummaryZoomInsertionRule   | Šis notikums nosaka, vai dokumentā ir kādas sadaļas, kad lietotājs ievieto kopsavilkuma tuvinājumu, un to, vai lietotājs izvēlas dzēst esošās sadaļas. |
| Office.Security.SecureReaderHost.ProtectedViewValidation | Seko, kad un kāpēc fails tiek atvērts aizsargātā skatā. Tiek izmantots, lai noteiktu nosacījumus, kur aizsargātais skats, iespējams, netiek pareizi izraisīts, lai pārliecinātos, vai šis līdzeklis darbojas pareizi. |

## <a name="product-and-service-performance-events"></a>Produktu un pakalpojumu veiktspējas notikumi

Šī kategorija ietver notikumus, kas var attiekties uz šādām jomām:

- Neparedzēta iziešana no programmas (avārijas) un programmas stāvoklis brīdī, kad tas notika.
- Slikts atbildes laiks vai slikta veiktspēja tādos scenārijos kā programmas startēšana vai faila atvēršana.
- Līdzekļa funkcionalitātes vai lietošanas iespēju kļūdas.

Nākamajā tabulā ir sniegti šīs kategorijas notikumu piemēri un šo notikumu apraksti.

| **Notikuma nosaukums**    | **Notikuma apraksts**   |
| --------------- | -------------- |
| Office.Word.Word.CoreSaveTime100ns     | Šis notikums reģistrē dokumenta saglabāšanas darbības veiktspēju programmā Word. Šo notikumu izmantojam, lai noteiktu kļūdas un veiktspējas problēmas saistībā ar Word dokumenta saglabāšanas darbību.|
| Office.Identity.SignInForWamAccountAad  | Šis notikums tiek nosūtīts, ja lietotājs Azure Active Directory kontā ir pierakstījies ar tīmekļa konta pārvaldnieka (WAM) bibliotēku. Šis notikums nosūta tādus metadatus kā AppName, AppVersion un ErrorCode, ja notikums neizdevās. |
| Office.PowerPoint.PPT.Desktop.FileOpen.FirstSlideMasterThumbnailRenderTime | Šis notikums apkopo pirmā slaidu šablona sīktēla atveidei programmā PowerPoint nepieciešamo laika ilgumu.  |
| Office.Extensibility.Diagnostics   | Šis notikums sniedz vispārīgu diagnostikas informāciju par Office pievienojumprogrammām, piemēram, avārijas atskaites atkļūdošanas vajadzībām.|

## <a name="device-connectivity-and-configuration-events"></a>Ierīču savienojamības un konfigurācijas notikumi

Šī kategorija ietver notikumus, kas var attiekties uz šādām jomām:

- Tīkla savienojuma statuss un ierīces iestatījumi, piemēram, atmiņas iestatījumi.

Nākamajā tabulā ir sniegti šīs kategorijas notikumu piemēri un šo notikumu apraksti.

| **Notikuma nosaukums**                    | **Notikuma apraksts**                                                                                                                                                     |
| ------ | ----- |
| Office.Graphics.ArtViewValidate | Šis notikums reģistrē grafiskā skata, kas atbalsta grafikas lietotāja interfeisu, validācijas rezultātus. Šo notikumu izmantojam, lai apkopotu lietojuma un kļūdu datus saistībā ar grafikas atveidi. |
| Office.Graphics.ARCExceptionScope | Šis notikums izseko atveides kļūmes, kas rodas atveides programmā. |
| Office.Extensibility.ODPLatency   | Šis notikums sniedz informāciju par lietotāja tīkla savienojumu un ātrumu.     |
