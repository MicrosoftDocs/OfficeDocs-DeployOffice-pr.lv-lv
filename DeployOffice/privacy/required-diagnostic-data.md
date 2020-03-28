---
title: Nepieciešamie Office diagnostikas dati
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
description: Sniedz informāciju Office administratoriem par nepieciešamajiem Office diagnostikas datiem un nodrošina notikumu un datu lauku sarakstu.
hideEdit: true
ms.openlocfilehash: fbb0e7b095becb664ff05fef67cd47f3360130b2
ms.sourcegitcommit: 269825241b1fa1831655ff599c97d5afa85b3895
ms.translationtype: HT
ms.contentlocale: lv-LV
ms.lasthandoff: 03/27/2020
ms.locfileid: "42983741"
---
# <a name="required-diagnostic-data-for-office"></a>Nepieciešamie Office diagnostikas dati

> [!IMPORTANT]
> Informācija šajā rakstā attiecas uz tālāk minētās Office klienta programmatūras versiju 1904 vai jaunāku versiju, kas instalēta datorā, kurā darbojas sistēma Windows:
> - Office 365 ProPlus un Office 365 Business
> - Office 365 individuālai lietošanai, Office 365 mājas lietošanai vai citas Office versijas, kas ir daļa no Office 365 abonementa.
> - Project un Visio, kas ir iekļautas dažos abonēšanas plānos, piemēram, Project Online Professional plānā vai Visio Online 2. plānā.
>
> Šī informācija attiecas arī uz tālāk norādīto sistēmas Office darbam ar Mac programmu versiju 16.28 vai jaunākām versijām: Excel, Outlook, OneNote, PowerPoint un Word.

Diagnostikas dati tiek izmantoti, lai uzturētu Office drošu un atjauninātu, noteiktu, diagnosticētu un novērstu problēmas, kā arī uzlabotu produktu. Šie dati neietver lietotāja vārdu vai e-pasta adresi, failu saturu vai informāciju par programmām, kas nav saistītas ar Office.

Šie diagnostikas dati tiek apkopoti un nosūtīti korporācijai Microsoft par Office klienta programmatūru, kas tiek lietota datoros, kuros darbojas operētājsistēma Windows. Daži diagnostikas dati ir nepieciešami, bet daži diagnostikas dati ir neobligāti. Piedāvājam jums iespēju izvēlēties, vai sūtīt mums nepieciešamos vai neobligātos diagnostikas datus, izmantojot tādus konfidencialitātes kontroles līdzekļus kā organizācijas politikas iestatījumus. Mums sūtāmos diagnostikas datus varat skatīt, izmantojot diagnostikas datu skatītāju.

***Nepieciešamie diagnostikas dati*** ir minimālie dati, kas nepieciešami, lai Office uzturētu drošu, atjauninātu un ar paredzēto veiktspēju atbilstošajā ierīcē.

Nepieciešamie diagnostikas dati palīdz noteikt ar Office saistītas problēmas, kuru cēlonis var būt saistīts ar ierīces vai programmatūras konfigurāciju. Piemēram, tie var palīdzēt noteikt, vai Office līdzeklis biežāk avarē noteiktā operētājsistēmas versijā, kopā ar nesen ieviestiem līdzekļiem vai tad, kad ir atspējoti konkrēti Office līdzekļi. Nepieciešamie diagnostikas dati palīdz mums ātrāk noteikt, diagnosticēt un novērst problēmas, lai mazinātu ietekmi uz lietotājiem vai organizācijām.

Papildinformāciju par diagnostikas datiem lasiet šajos rakstos:

- [Neobligātie Office diagnostikas dati](optional-diagnostic-data.md)
- [Diagnostikas datu skatītāja izmantošana ar Office](https://support.office.com/article/cf761ce9-d805-4c60-a339-4e07f3182855)

Ja esat organizācijas administrators, iespējams, jūs interesēs arī šie raksti:

- [Pārskats par konfidencialitātes kontroles līdzekļiem pakalpojumā Office 365 ProPlus](overview-privacy-controls.md)
- [Politikas iestatījumu izmantošana Office 365 ProPlus konfidencialitātes kontroles pārvaldībai](manage-privacy-controls.md)
- [Preferenču izmantošana Office darbam ar Mac konfidencialitātes kontroles līdzekļu pārvaldībai](mac-privacy-preferences.md)
- [Preferenču izmantošana Office darbam ar iOS ierīcēm konfidencialitātes kontroles līdzekļu pārvaldībai](ios-privacy-preferences.md)
- [Politikas iestatījumu izmantošana Office konfidencialitātes kontroles līdzekļu pārvaldībai Android ierīcēs](android-privacy-controls.md)

## <a name="categories-data-subtypes-events-and-data-fields-for-required-diagnostic-data"></a>Nepieciešamo diagnostikas datu kategorijas, datu apakštipi, notikumi un datu lauki

Nepieciešamie diagnostikas dati tiek organizēti kategorijās un datu apakštipos. Katrā datu apakštipā ir notikumi, kuros ir datu lauki, kas attiecas uz konkrēto notikumu.

Tālāk tabulā ir sniegts saraksts, kurā ir norādītas nepieciešamo diagnostikas datu kategorijas. Ir uzskaitīti katras kategorijas datu apakštipi un datu apakštipa svarīgāko aspektu apraksts. Norādītas arī saites uz katru datu apakštipa sadaļu, kurā var atrast tālāk norādīto informāciju.

- Notikumu saraksts konkrētajā datu apakštipā
- Katra notikuma apraksts
- Datu lauku saraksts katrā notikumā
- Katra datu lauka apraksts

| **Kategorija**       | **Datu apakštips**| **Apraksts**    |
| ---------- | ------------- | ---- |
| **Programmatūras iestatīšana un inventārs** | [Office iestatīšana un inventārs](#office-setup-and-inventory-subtype)   | Instalētais produkts, versija un instalēšanas statuss.  |
| | [Office pievienojumprogrammu konfigurācija](#office-add-in-configuration-subtype)  | Programmatūras pievienojumprogrammas un to iestatījumi.     |
| | [Drošība](#security-subtype)  | Dokumenta, līdzekļa un pievienojumprogrammas kļūdas nosacījumi, kas var negatīvi ietekmēt drošību, tostarp produktu atjauninājumu gatavību.  |
| **Produktu un pakalpojumu lietojums**    | [Lietojumprogrammas līdzekļu sekmju novērtējums](#application-feature-success-subtype)   | Informācija par sekmīgu lietojumprogrammas funkcionalitāti. Attiecas tikai uz programmas un dokumentu atvēršanu un aizvēršanu, failu rediģēšana un failu koplietošanu (sadarbību). |
| | [Lietojumprogrammas statuss un palaišana](#application-status-and-boot-subtype)    | Nosaka, vai ir notikuši konkrēti līdzekļu notikumi, piemēram, startēšana vai apturēšana, un vai līdzeklis darbojas.   |
| | [Office pieejamības konfigurācija](#office-accessibility-configuration-subtype)  | Office pieejamības līdzekļi       |
| | [Konfidencialitāte](#privacy-subtype)| Office konfidencialitātes iestatījumi|
| **Produktu un pakalpojumu veiktspēja**       | [Neparedzēts lietojumprogrammas darbības pārtraukums (avārijas)](#unexpected-application-exit-crash-subtype)  | Neparedzēts lietojumprogrammas darbības pārtraukums un programmas statuss brīdī, kad tas notika.    |
|  | [Lietojumprogrammas līdzekļu novērtējums](#application-feature-performance-subtype)  | Slikts atbildes laiks vai slikta veiktspēja tādos scenārijos kā programmas startēšana vai faila atvēršana. |
|  | [Lietojumprogrammas darbības kļūda](#application-activity-error-subtype)   | Līdzekļa funkcionalitātes vai lietošanas iespēju kļūdas.  |
| **Ierīču savienojamība un konfigurācija** | [Ierīču savienojamība un konfigurācija](#device-connectivity-and-configuration-subtype) | Tīkla savienojuma statuss un ierīces iestatījumi, piemēram, atmiņas iestatījumi. |


> [!NOTE]
> - Kategorijas tiek rādītas datu diagnostikas skatītājā, bet datu apakštipi netiek rādīti.
> - Datu lauks, kas atzīmēts kā *novecojis*, ir noņemts vai drīz tiks noņemts no nepieciešamajiem diagnostikas datiem. Daži no šiem datu laukiem ir dublikāti, kas tika izveidoti diagnostikas datu modernizēšanas rezultātā un kas tika izmantoti, lai nodrošinātu nepārtrauktu pakalpojuma darbību reāllaika diagnostikas pārraudzības atskaitēm.

## <a name="categories-and-data-fields-that-are-common-for-all-events"></a>Kategorijas un datu lauki, kas ir kopīgi visiem notikumiem

Neatkarīgi no kategorijas vai datu apakštipa pastāv informācija par notikumiem, kas attiecas uz visiem notikumiem. Šī kopīgā informācija, ko dažkārt dēvē par *datu līgumiem*, ir sakārtota kategorijās. Katrā kategorijā ir lauki, un šie lauki ir atsevišķa notikuma metadati un rekvizīti. Šo informāciju varat skatīt, izmantojot diagnostikas datu skatītāju.

Kategorijas, kurās ir apkopota informācija par notikumiem, var iedalīt divās grupās:

  - [Informācija, kas ir kopīga visiem notikumiem](#information-common-to-all-events)
  - [Informācija, kas īpaši atbalsta diagnostikas datu apkopošanu](#information-that-specifically-supports-diagnostic-data-collection)

### <a name="information-common-to-all-events"></a>*Informācija, kas ir kopīga visiem notikumiem*

Informācija, kas ir kopīga visiem notikumiem, tiek apkopota tālāk norādītajās kategorijās.

#### <a name="app"></a>Programma 

Informācija par lietojumprogrammu. Visi lauki ir konstanti visām attiecīgās lietojumprogrammas versijas sesijām.

Šajā kategorijā ir šādi lauki:

  - **Branch** — zars, no kura nāk attiecīgā būvējuma versija. Ļauj mums noteikt, no kāda zara tipa nāk attiecīgais būvējums, lai mēs varētu pareizi piemērot labojumus.
  - **InstallType** — skaitītājs, kas norāda, kā lietotājs ir instalējis lietojumprogrammu. Ļauj mums noteikt, vai konkrēti instalēšanas mehānismi rada problēmas, kas nav sastopamas citos instalēšanas mehānismos.
  - **Name** — tās lietojumprogrammas nosaukums, kas nodrošina datus. Ļauj mums noteikt, kuras lietojumprogrammas darbībā ir radušās problēmas, lai mēs tās varētu atrisināt.
  - **Platform** — tās platformas plašā klasifikācija, kurā darbojas programma. Ļauj mums noteikt platformas, kurās, iespējams, ir radusies problēma, lai mēs varētu pareizi noteikt problēmas prioritāti.
  - **Version** — lietojumprogrammas versija. Ļauj mums noteikt, kurās produkta versijās ir radusies problēma, lai mēs varētu pareizi noteikt tās prioritāti.

#### <a name="client"></a>Klients 

Identifikators, kas ir saistīts ar Office instanci ierīcē. Konstants visām attiecīgās vairāku programmu komplektu instalācijas versijas programmu sesijām vai arī visām attiecīgās lietojumprogrammas versijas sesijām.

Šajā kategorijā ir šādi lauki:

  - **Id** — unikāls identifikators, kas ir piešķirts klientam Office instalēšanas laikā. Ļauj mums noteikt, vai problēmas ietekmē atlasītu instalāciju kopu, un ietekmēto lietotāju skaitu.

#### <a name="consent"></a>Atļauja

Informācija saistībā ar lietotāja piekrišanu diagnostikas datiem un saistītajiem līdzekļiem.

Šajā kategorijā ir šādi lauki:

  - **UserCategory** — norāda tā lietotāja tipu, kas sniedza atļauju. Kāds no MSAUser, AADUser vai LocalDeviceUser

  - **DiagnosticConsentLevel** — norāda, kāds diagnostikas datu atļaujas līmenis ir piešķirts lietotājam

  - **DiagnosticConsentSourceLocation** — norāda, kā lietotājs ir iesniedzis atļauju diagnostikas datiem

  - **DiagnosticConsentConsentTime** — norāda, kad lietotājs ir iesniedzis atļauju diagnostikas datiem. Datums tiks rādīts kā cilvēka lasāms datums vai kā datora kodēts datums, kas izskatās pēc liela skaitļa.

  - **ServiceConnectionState** — norāda, vai lietotājs ir izvēlējies lietot vai nelietot visus saistītos līdzekļus

  - **ServiceConnectionStateSourceLocation** — norāda, kā lietotājs ir izvēlējies lietot vai nelietot visus saistītos līdzekļus

  - **ServiceConnectionStateConsentTime** — norāda, kad lietotājs ir izvēlējies lietot vai nelietot visus saistītos līdzekļus. Datums tiks rādīts kā cilvēka lasāms datums vai kā datora kodēts datums, kas izskatās pēc liela skaitļa.

  - **ControllerConnectedServicesState** — norāda, vai lietotājam ir piekļuve neobligātajiem saistītajiem līdzekļiem

  - **ControllerConnectedServicesStateSourceLocation** — norāda, kā tika veikta lietotāja izvēle lietot neobligātos saistītos līdzekļus

  - **ControllerConnectedServicesStateConsentTime** — norāda, kad lietotājs izvēlējās neobligāto saistīto līdzekļu statusu. Datums tiks rādīts kā cilvēka lasāms datums vai kā datora kodēts datums, kas izskatās pēc liela skaitļa.

  - **UserContentDependentState** — norāda, vai lietotājs ir izvēlējies iespējot vai atspējot saistītos līdzekļus, kas analizē saturu

  - **UserContentDependentStateSourceLocation** — norāda, kā tika veikta lietotāja izvēle iespējot vai atspējot saistītos līdzekļus, kas analizē saturu

  - **UserContentDependentStateConsentTime** — norāda, kad lietotājs izvēlējās iespējot vai atspējot saistītos līdzekļus, kas analizē saturu. Datums tiks rādīts kā cilvēka lasāms datums vai kā datora kodēts datums, kas izskatās pēc liela skaitļa.

  - **DownloadContentState** — norāda, vai lietotājs ir izvēlējies iespējot vai atspējot saistītos līdzekļus, kas lejupielādē tiešsaistes saturu

  - **DownloadContentStateSourceLocation** — norāda, kā lietotājs izvēlējās iespējot vai atspējot saistītos līdzekļus, kas lejupielādē tiešsaistes saturu

  - **DownloadContentStateConsentTime** — norāda, kad lietotājs izvēlējās iespējot vai atspējot saistītos līdzekļus, kas lejupielādē tiešsaistes saturu. Datums tiks rādīts kā cilvēka lasāms datums vai kā datora kodēts datums, kas izskatās pēc liela skaitļa.

#### <a name="device"></a>Ierīce 

Informācija par operētājsistēmu un būvējumu.

Šajā kategorijā ir šādi lauki:

  - **OsBuild** — ierīcē instalētās operētājsistēmas būvējuma numurs. Ļauj mums noteikt, vai problēmas ietekmē atsevišķas konkrētās operētājsistēmas servisa pakotnes vai versijas citādi nekā pārējās, lai mēs varētu noteikt problēmu prioritāti.

  - **OsVersion** — ierīcē instalētās galvenās operētājsistēmas versija. Ļauj mums noteikt, vai problēmas ietekmē konkrētu operētājsistēmas versiju vairāk par citām, lai mēs varētu noteikt problēmu prioritāti.

#### <a name="legacy"></a>Mantotie vienumi 

Nodrošina programmas ID un operētājsistēmas versiju saderībai ar esošajām mantotās kolekcijas darbībām.

Šajā kategorijā ir šādi lauki:

  - **AppId** — skaitītāja vērtība, kas apzīmē lietojumprogrammu, kas sūta datus. Ļauj mums noteikt, kuras lietojumprogrammas darbībā ir radušās problēmas, lai mēs tās varētu atrisināt.

  - **OsEnv** — skaitītājs, kas norāda operētājsistēmu, kurā darbojas sesija. Ļauj mums noteikt, kurā operētājsistēmā ir radusies problēma, lai mēs varētu noteikt problēmu prioritāti.

#### <a name="release"></a>Laidiens 

Informācija saistībā ar laidiena kanālu. Visi lauki ir konstanti visām attiecīgās instalācijas versijas programmu sesijām. Norāda to ierīču grupu, kas atrodas vienā produkta laidiena cikla posmā.

Šajā kategorijā ir šādi lauki:

  - **Audience** — norāda konkrētās auditorijas grupas apakšauditoriju. Ļauj mums izsekot auditorijas grupu apakškopām, lai novērtētu problēmu izplatību un noteiktu to prioritāti.

  - **AudienceGroup** — norāda loku, no kura nāk dati. Ļauj mums pakāpeniski izlaist līdzekļus un identificēt potenciālās problēmas, pirms lielākā daļa lietotāju ir ar tām saskārušās.

  - **Channel** — kanāls, kurā tiek izlaists produkts. Ļauj mums noteikt, vai problēma ietekmē kādu no mūsu izlaišanas kanāliem citādi nekā citus.

  - **Fork** — norāda produkta sazarojumu. Ļauj izmantot mehānismu, lai apkopotu būvējumu numuru kopu datus nolūkā identificēt problēmas saistībā ar konkrēto laidienu.

#### <a name="session"></a>Sesija 

Informācija par procesa sesiju. Visi šīs sesijas lauki ir konstanti.

Šajā kategorijā ir šādi lauki:

  - **ABConfigs** — norāda testējamo variantu kopu, kas darbojas konkrētajā sesijā. Ļauj mums noteikt, kuri konkrētie testējamie varianti darbojas sesijā, lai mēs varētu noteikt, vai testējamā versija ir tās problēmas cēlonis, kas ietekmē lietotājus.

  - **EcsETag** — indikators no testējamo variantu sistēmas, kas apzīmē mašīnai nosūtītos testējamos variantus. Ļauj mums noteikt, kuri testējamie varianti, iespējams, ietekmē attiecīgo sesiju.

  - **Flags** — karodziņi, kas izseko bitmasku un attiecas uz visu sesiju. Pašlaik galvenā uzmanība tiek pievērsta iztveršanai un diagnostikas datu opcijām. Ļauj mums kontrolēt attiecīgās sesijas darbību saistībā ar sesijas ģenerētajiem diagnostikas datiem.

  - **Id** — unikāli identificē attiecīgo datu sesiju. Ļauj mums noteikt problēmu ietekmi, izvērtējot ietekmēto sesiju skaitu un nosakot, vai šīm sesijām ir kopīgi līdzekļi.

  - **ImpressionId** — norāda testējamo variantu kopu, kas darbojas konkrētajā sesijā. Ļauj mums noteikt, kuri konkrētie testējamie varianti darbojas sesijā, lai mēs varētu noteikt, vai testējamā versija ir tās problēmas cēlonis, kas ietekmē lietotājus.

  - **MeasuresEnabled** — karodziņš, kas norāda, vai pašreizējie sesijas dati tiek iztverti. Ļauj mums noteikt, kā statistiski izvērtēt datus, kas tiek apkopoti no attiecīgās sesijas.

  - **SamplingClientId** — klienta ID, kas tiek izmantots, lai noteiktu, vai tas ir daļa no iztveršanas. Ļauj mums noteikt, kāpēc konkrēta sesija tika iekļauta vai neiekļauta iztveršanā.

#### <a name="user"></a>Lietotājs

Sniedz komerciālās programmatūras SKU informāciju par nomnieku.

Šajā kategorijā ir šādi lauki:

  - **PrimaryIdentityHash** — identifikatora pseidonīms, kas apzīmē pašreizējo lietotāju.

  - **PrimaryIdentitySpace** — tās identitātes tips, kas atrodas šeit: PrimaryIdentityHash. Kāds no MASCID, OrgIdCID vai UserObjectId.

  - **TenantGroup** — tā nomnieka tips, kam pieder abonements. Ļauj mums klasificēt problēmas un noteikt, vai problēma ir plaši izplatīta vai izolēta lietotāju kopā.

  - **TenantId** — nomnieks, ar kuru ir saistīts lietotāja abonements. Ļauj mums klasificēt problēmas un noteikt, vai problēma ir plaši izplatīta vai izolēta konkrēta nomnieka lietotāju kopā.

### <a name="information-that-specifically-supports-diagnostic-data-collection"></a>*Informācija, kas īpaši atbalsta diagnostikas datu apkopošanu*

Informācija, kas īpaši atbalsta diagnostikas datu apkopošanu, tiek apkopota tālāk norādītajās kategorijās.

#### <a name="activity"></a>Darbība

Informācija, lai izprastu paša pasākuma apkopošanas panākumus.

Šajā kategorijā ir šādi lauki:

  - **AggMode** — nosaka, kā sistēmai jāapkopo darbības rezultāti. Ļauj mums samazināt no lietotāja mašīnas augšupielādētās informācijas apjomu, apkopojot darbības rezultātus vienā notikumā, kas tiek periodiski nosūtīts.

  - **Count** — notikušās darbības reižu skaits, ja skaits ir no apkopotā notikuma. Ļauj mums noteikt, cik bieži darbība izdevās vai neizdevās, pamatojoties uz darbības apkopošanas režīmu.

  - **CV** — vērtība, kas norāda relāciju starp darbībām un pakārtotajām darbībām. Ļauj mums atjaunot relāciju starp ligzdotajām darbībām.

  - **Duration** — darbības izpildei nepieciešamais laiks. Ļauj mums noteikt veiktspējas problēmas, kas negatīvi ietekmē lietotāju pieredzi.

  - **Result**.**Code** — lietojumprogrammas definēts kods, lai identificētu noteiktus rezultātus. Ļauj mums noteikt specifiskāku informāciju par konkrēto kļūmi, piemēram, kļūmes kodu, ko var izmantot, lai klasificētu un novērstu problēmas.

  - **Result.Tag** — vesela skaitļa tags, kas nosaka atrašanās vietu kodā, kurā tika ģenerēts rezultāts. Ļauj mums skaidri noteikt atrašanās vietu kodā, kurā tika ģenerēts rezultāts, kas iespējo kļūmju klasifikāciju.

  - **Result**.**Type** — rezultāta koda tips. Norāda nosūtītā rezultātu koda tipu, lai varētu pareizi interpretēt vērtību.

  - **Success** — karodziņš, kas norāda, vai darbība izdevās vai neizdevās. Ļauj mums noteikt, vai lietotāja veiktās darbības produktā ir sekmīgas vai nesekmīgas. Ļauj mums noteikt problēmas, kas ietekmē lietotāju.

#### <a name="application"></a>Lietojumprogramma 

Informācija par tās lietojumprogrammas instalēšanu, par kuru tiek apkopoti notikumi.

Šajā kategorijā ir šādi lauki:

  - **Architecture** — lietojumprogrammas arhitektūra. Ļauj mums klasificēt kļūdas, kas var būt specifiskas lietojumprogrammas arhitektūrai.

  - **Click2RunPackageVersion** — tās tehnoloģijas Click-To-Run pakotnes versijas numurs, kas tika izmantota, lai instalētu programmu. Ļauj mums identificēt ar iestatīšanu saistītās problēmas, nosakot tās instalēšanas programmas versiju, kas tika izmantota, lai instalētu Office.

  - **DistributionChannel** — kanāls, kurā ir izvietota programma. Ļauj mums sadalīt ienākošos datus, lai mēs varētu noteikt, vai problēmas ietekmē auditoriju.

  - **InstallMethod** — vai pašreizējais Office būvējums tika jaunināts, atritināts vai instalēts no jauna.

  - **IsClickToRunInstall** — karodziņš, kas norāda, vai tika veikta Click-To-Run instalācija. Ļauj mums noteikt problēmas, kas varētu būt specifiskas Click-To-Run instalēšanas mehānismam.

  - **IsDebug** — karodziņš, kas norāda, vai Office būvējums ir atkļūdošanas būvējums. Ļauj mums noteikt, vai problēmas rodas no atkļūdošanas būvējumiem, kas, iespējams, darbojas atšķirīgi.

  - **IsInstalledOnExternalStorage** — karodziņš, kas norāda, vai Office ir instalēts ārējās atmiņas ierīcē. Ļauj mums noteikt, vai problēmas ir saistītas ar ārējās atmiņas ierīces atrašanās vietu.

  - **IsOEMInstalled** — karodziņš, kas norāda, vai Office instalēja oriģinālā aprīkojuma ražotājs (OEM). Ļauj mums noteikt, vai lietojumprogramma tika instalēta, izmantojot OEM. Tas mums var palīdzēt klasificēt un noteikt problēmas.

  - **PreviousVersion** — Tā Office versija, kas bija iepriekš instalēta datorā. Ļauj atgriezties uz iepriekšējo versiju, ja pašreizējā versijā ir radusies problēma.

  - **ProcessFileName** — lietojumprogrammas faila nosaukums. Ļauj mums noteikt tās izpildāmā procesa nosaukumu, kas ģenerē datus, jo var būt vairāki dažādu procesu failu nosaukumi, kuriem ir tās pašas programmas nosaukums.

#### <a name="client"></a>Klients

Informācija par Office klientu.

Šajā kategorijā ir šādi lauki:

  - **FirstRunTime** — pirmā reize, kad tika palaists klients. Ļauj izprast, cik ilgi klientā bija instalēta sistēma Office.

#### <a name="device"></a>Ierīce

Informācija par ierīces konfigurāciju un iespējām.

Šajā kategorijā ir šādi lauki:

  - **DigitizerInfo** — informācija par mašīnas izmantoto ciparotāju. Ļauj mums klasificēt datus atkarībā no ierīces rakursa.

  - **FormFactor** — norāda, kādam formas faktoram atbilst ierīce, kas sūta informāciju. Ļauj mums klasificēt datus atkarībā no ierīces rakursa.

  - **FormFactorFamily** — norāda, kādam formas faktoram atbilst ierīce, kas sūta informāciju. Ļauj mums klasificēt datus atkarībā no ierīces rakursa.

  - **HorizontalResolution** — horizontālā ierīces ekrāna izšķirtspēja. Ļauj mums klasificēt datus atkarībā no ierīces rakursa.

  - **Id** — unikāls ierīces identifikators. Ļauj mums noteikt problēmu izplatību ierīču kopā.

  - **IsEDPPolicyEnabled** — karodziņš, kas norāda, vai mašīnā ir iespējota uzlabotā datu aizsardzība. Ļauj mums klasificēt datus atkarībā no ierīces rakursa.

  - **IsTerminalServer** — karodziņš, kas ļauj noteikt, vai mašīna ir termināļa serveris. Ļauj mums klasificēt datus atkarībā no ierīces rakursa.

  - **Manufacturer** — ierīces ražotājs. Ļauj mums klasificēt datus atkarībā no ierīces rakursa.

  - **Model** — ierīces modelis. Ļauj mums klasificēt datus atkarībā no ierīces rakursa.

  - **MotherboardUUIDHash** — mātesplates unikālā identifikatora jaucējkods. Ļauj mums klasificēt datus atkarībā no ierīces rakursa.

  - **Name** — ierīces nosaukums. Ļauj mums klasificēt datus atkarībā no ierīces rakursa.
  
  - **NetworkCost** — norāda tīkla izmaksas vai tipu, piemēram, mērāms vai mērāms virs ierobežojuma.
  
  - **NetworkCountry** — sūtītāja valsts kods, kura pamatā ir neizlaista klienta IP adrese.

  - **NumProcPhysCores** — fizisko kodolu skaits mašīnā. Ļauj mums klasificēt datus atkarībā no ierīces rakursa.

  - **OsLocale** — instalētās operētājsistēmas lokalizācija. Ļauj mums klasificēt datus atkarībā no ierīces rakursa.

  - **ProcessorArchitecture** — procesora arhitektūra. Ļauj mums klasificēt datus atkarībā no ierīces rakursa.

  - **ProcessorCount** — mašīnas procesoru skaits. Ļauj mums klasificēt datus atkarībā no ierīces rakursa.

  - **ProcSpeedMHz** — procesora ātrums. Ļauj mums klasificēt datus atkarībā no ierīces rakursa.

  - **RamMB** — ierīces atmiņas apjoms. Ļauj mums klasificēt datus atkarībā no ierīces rakursa.

  - **ScreenDepth** — ļauj mums klasificēt datus atkarībā no ierīces rakursa.

  - **ScreenDPI** — ekrāna DPI vērtība. Ļauj mums klasificēt datus atkarībā no ierīces rakursa.

  - **SusClientId** — tās ierīces Windows Update ID, kurā Office darbojas.

  - **SystemVolumeFreeSpaceMB** — sistēmas sējumā pieejamā brīvā vieta. Ļauj mums klasificēt datus atkarībā no ierīces rakursa.

  - **SystemVolumeSizeMB** — mašīnas sistēmas sējuma apjoms. Ļauj mums klasificēt datus atkarībā no ierīces rakursa.

  - **VerticalResolution** — vertikālā ierīces ekrāna izšķirtspēja. Ļauj mums klasificēt datus atkarībā no ierīces rakursa.

  - **WindowErrorReportingMachineId** — unikāls mašīnas identifikators, ko nodrošina Windows kļūdu uzrādīšana. Ļauj mums klasificēt datus atkarībā no ierīces rakursa.

  - **WindowSqmMachineId** — unikāls mašīnas identifikators, ko nodrošina Windows SQM. Ļauj mums klasificēt datus atkarībā no ierīces rakursa.

#### <a name="event"></a>Notikums 

Notikumam raksturīga informācija, tostarp tā unikālais identifikators sesijā.

Šajā kategorijā ir šādi lauki:

  - **Contract** — to līgumu saraksts, kurus ievieš notikums. Ļauj mums novērtēt, kādi dati ir daļa no atsevišķā notikuma, lai mēs to varētu efektīvi apstrādāt.

  - **CV** — vērtība, kas ļauj mums noteikt savstarpēji saistītus notikumus. Tiek izmantota diagnostikā, ļaujot mums noteikt saistīto darbību vai notikumu modeļus.

  - **Flags** — informācija, kas tiek izmantota, lai mainītu attiecīgā notikuma atbildi. Tiek izmantots nolūkā pārvaldīt veidu, kā notikums tiek apstrādāts, lai augšupielādētu datus korporācijai Microsoft.

  - **Id** — unikāls notikuma identifikators. Ļauj mums unikāli identificēt saņemtos notikumus.

  - **Name** — notikuma nosaukums. Ļauj noteikt notikumu, kas tiek nosūtīts no klienta.

  - **Rule** — tās kārtulas identifikators, kas ģenerēja datus, ja tos ģenerēja kārtula. Ļauj mums noteikt datu avotu, lai mēs varētu pārbaudīt un pārvaldīt notikuma parametrus

  - **RuleId** — tās kārtulas identifikators, kas ģenerēja datus, ja tos ģenerēja kārtula. Ļauj mums noteikt datu avotu, lai mēs varētu pārbaudīt un pārvaldīt notikuma parametrus.

  - **RuleInterfaces** — jebkurš interfeiss, kuru ievieš konkrēta kārtula. Ļauj mums klasificēt un importēt datus atbilstoši to struktūrai, kas vienkāršo datu apstrādi.

  - **RuleVersion** — tās kārtulas identifikators, kas ģenerēja datus, ja tos ģenerēja kārtula. Ļauj mums noteikt datu avotu, lai mēs varētu pārbaudīt un pārvaldīt notikuma parametrus.

  - **SampleRate** — norāda, cik liels lietotāju skaits (procentos) sūta šos datus. Tas ļauj mums veikt datu statistisko analīzi un nodrošina, ka ne visiem lietotājiem ir jānosūta biežāk izmantotie datu punkti.

  - **SchemaVersion** — tās shēmas versija, kas tiek izmantota, lai ģenerētu diagnostikas datus. Nepieciešama, lai pārvaldītu datus, kas tiek sūtīti no klienta. Tādējādi laika gaitā var mainīt, kādi dati tiek sūtīti no katra klienta.

  - **Sequence** — skaitītājs, kas identificē secību, kādā tika ģenerēts notikums klientā. Ļauj kārtot saņemtos datus, lai mēs varētu noteikt darbības, kas, iespējams, izraisīja problēmu, kas ietekmē klientus.

  - **Source** — avota kanāls, kas tika izmantots, lai augšupielādētu datus. Nepieciešams, lai pārraudzītu mūsu augšupielādes kanālu vispārējo darbspēju un palīdzētu noteikt problēmas saistībā ar augšupielādes kanālu. Tas ļauj kontrolēt atsevišķus augšupielādes kanālus, lai nodrošinātu to atbilstību prasībām.

  - **Time** — laiks, kad klientā tika ģenerēts notikums. Ļauj mums sinhronizēt un pārbaudīt to notikumu secību, kas ir ģenerēti klientā, kā arī izveidot veiktspējas rādītājus lietošanas norādījumiem. 

#### <a name="host"></a>Viesošana

Informācija par lietojumprogrammu, kurā tiek viesota iegulta lietojumprogramma

Šajā kategorijā ir šādi lauki:

  - **Id** — unikāls identifikators, kuru iegultā lietojumprogramma piešķir programmai, kas kalpo kā viesotājs.

  - **SessionId** — globāli unikāls identifikators resursdatora sesijai.

  - **Version** — resursdatora galvenās izpildāmās programmas versijas identifikators.

#### <a name="legacy"></a>Mantotie vienumi

Mantotās sistēmas saderībai nepieciešamā informācija.

Šajā kategorijā ir šādi lauki:

  - **OsBuild** — konkrētais operētājsistēmas būvējuma numurs. Ļauj mums noteikt, kurai operētājsistēmas versijai pieder diagnostikas dati, lai noteiktu problēmas prioritāti.

  - **OsBuildRevision** — operētājsistēmas būvējuma pārskatījuma numurs. Ļauj mums noteikt, kurai operētājsistēmas versijai pieder diagnostikas dati, lai noteiktu problēmas prioritāti.

  - **OsMinorVersion** — operētājsistēmas papildversija. Ļauj mums noteikt, kurai operētājsistēmas versijai pieder diagnostikas dati, lai noteiktu problēmas prioritāti.

  - **OsVersionString** — vienota virkne, kas norāda operētājsistēmas būvējuma numuru. Ļauj mums noteikt, kurai operētājsistēmas versijai pieder diagnostikas dati, lai noteiktu problēmas prioritāti.

#### <a name="session"></a>Sesija

Informācija par procesa sesiju.

Šajā kategorijā ir šādi lauki:

  - **ABConfigsDelta** — izseko atšķirībai starp pašreizējiem ABConfigs datiem un iepriekšējo vērtību. Ļauj mums izsekot jauniem mašīnā esošiem testējamiem variantiem, lai palīdzētu noteikt, vai problēma ir radusies jauna testējamā varianta dēļ.

  - **CollectibleClassification** — informācijas klases, kuras sesija var apkopot. Atļauj sesiju filtrēšanu, pamatojoties uz sesiju datiem.

  - **DisableTelemetry** — karodziņš, kas norāda, vai ir iestatīta atslēga DisableTelemetry. Ļauj mums uzzināt, vai sesija ziņo par citiem diagnostikas datiem, kas nav EssentialServiceMetadata.

  - **SamplingKey** — atslēga, kas tiek izmantota, lai noteiktu, vai sesija ir iztverta. Ļauj mums saprast, kā atsevišķas sesijas izvēlas savu iztveršanas statusu.

  - **SamplingMethod** — metode, kas tiek izmantota, lai noteiktu iztveršanas politiku. Ļauj mums saprast, kādi dati nāk no sesijas.

  - **Sequence** — unikāls skaitlisks sesijas identifikators. Ļauj kārtot sesijas, lai analizētu iespējamās problēmas.

  - **Start** — procesa sesijas palaišanas laiks. Ļauj mums noteikt sesijas sākumu.

  - **TimeZoneBiasInMinutes** — starpība minūtēs starp UTC un vietējo laiku. Ļauj normalizēt UTC laiku atpakaļ uz vietējo laiku.

  - **SamplingClientIdValue** — tās atslēgas vērtība, kas tiek izmantota iztveršanas noteikšanai. Ļauj mums noteikt, kāpēc tika iztverta (vai neiztverta) sesija.

  - **SamplingDeviceIdValue** — tās atslēgas vērtība, kas tiek izmantota iztveršanas noteikšanai. Ļauj mums noteikt, kāpēc tika iztverta (vai neiztverta) sesija.

  - **SamplingSessionKValue** — papildu iztveršanas metadati. Izmanto, lai palīdzētu novērtēt saņemto datu statistikas nozīmi.

  - **SamplingSessionNValue** — papildu iztveršanas metadati. Izmanto, lai palīdzētu novērtēt saņemto datu statistikas nozīmi.

  - **TelemetryPermissionLevel** — vērtība, kas norāda, kāda līmeņa diagnostikas datiem ir piekritis lietotājs. Ļauj mums saprast, kāda līmeņa diagnostikas datus var sagaidīt no sesijas.

## <a name="data-fields-that-are-common-for-onenote-events"></a>OneNote notikumiem kopīgie datu lauki

Zemāk norādītie datu lauki ir kopīgi visiem OneNote notikumiem Mac, iOS un Android operētājsistēmās.

> [!NOTE]
> Izmantojot Diagnostikas datu skatītāju, OneNote notikumi Mac, iOS un Android operētājsistēmās tiek saukti par Activity, ReportData vai Unexpected. Faktiskā notikuma nosaukuma meklēšanai atlasiet notikumu un apskatiet lauku EventName.

- **Activity_ActivityType** —  norāda uz šīs darbības notikuma veidu. Darbība var būt normāla vai augstvērtīga.

- **Activity_AggMode** —  norāda sistēmai, kā apkopot darbības rezultātus. Ļauj mums samazināt no lietotāja mašīnas augšupielādētās informācijas apjomu, apkopojot darbības rezultātus vienā notikumā, kas tiek periodiski nosūtīts.

- **Count** — notikušās darbības reižu skaits, ja skaits ir no apkopotā notikuma. Ļauj mums noteikt, cik bieži darbība izdevās vai neizdevās, pamatojoties uz darbības apkopošanas režīmu.

- **Activity_CV** — vērtība, kas identificē saistību starp darbībām un pakārtotajām darbībām. Ļauj mums atjaunot relāciju starp ligzdotajām darbībām.

- **Activity_DetachedDurationInMicroseconds** — laiks, kad darbība ir dīkstāvē un faktiski neveic darbu, bet šis laiks joprojām ieskaitītas darbības kopējā laikā.  

- **Activity_DurationInMicroseconds** — darbības izpildei nepieciešamais laiks. Ļauj mums noteikt veiktspējas problēmas, kas negatīvi ietekmē lietotāju pieredzi.

- **Activity_Expiration** — datums skaitliskā formātā, kas norāda laiku, kad šis notikums pārtrauks sūtīšanu no klientiem

- **Activity_FailCount** — darbības neizdošanās reižu skaits

- **Activity_Name** — īss notikuma nosaukums. Ļauj noteikt notikumu, kas tiek nosūtīts no klienta.

- **Activity_Namespace** — notikuma nosaukumu apgabals. Ļauj grupēt notikumu grupās.

- **Activity_Reason** — virkne, kas norāda uz iemeslu, kura dēļ darbība beidzas ar konkrēto rezultātu.

- **Activity_Result** — karodziņš, kas norāda, vai darbība izdevās, neizdevās vai negaidīti neizdevās. Ļauj mums noteikt, vai lietotāja veiktās darbības produktā ir sekmīgas vai nesekmīgas. Ļauj mums noteikt problēmas, kas ietekmē lietotāju.

- **Activity_State** — karodziņš, kas norāda uz to, vai notikums ir lietotāja darbības sākums vai beigas.

- **Activity_SucceedCount** — darbības izdošanās reižu skaits.

- **ErrorCode** —  norāda kļūdas kodu, ja ir.

- **ErrorCode2** —  norāda otro kļūdas kodu, ja ir.

- **ErrorCode3** —  norāda trešo kļūdas kodu, ja ir.

- **ErrorTag** — norāda ar kļūdas kodu saistīto atzīmi, ja ir.

- **ErrorType** — norāda kļūdas veidu, ja ir.

- **EventName** — unikāls OneNote notikuma nosaukums. Pagātnes inženierijas ierobežojumu dēļ, OneNote notikumi izmanto šo pielāgoto lauku unikālā nosaukuma norādīšanai.

- **ExpFeatures** — norāda uz to, vai lietotājs OneNote lietojumprogrammā ir ieslēdzis eksperimentālā līdzekļa slēdzi.

- **ExpirationDate** —  datums skaitliskā formātā, kas norāda laiku, kad šis notikums pārtrauks sūtīšanu no klientiem.

- **IsConsumer** —  norāda uz to, vai lietotājs ir patērētājs.

- **IsEdu** — norāda, vai lietotājs ir Education nomnieks.

- **IsIW** — norāda, vai lietotājs ir Enterprise lietotājs.

- **IsMsftInternal** —  norāda, vai lietotājs ir Microsoft darbinieks.

- **IsPremiumUser** — norāda, vai lietotājam ir Premium licence.

- **Namespace** —  notikuma nosaukumu apgabals. Ļauj grupēt notikumu grupās.

- **Release_AppStore** — karodziņš, kas norāda uz to, vai būvējums nāk no AppStore.

- **Release_Audience** — norāda konkrētās auditorijas grupas apakšauditoriju. Ļauj mums izsekot auditorijas grupu apakškopām, lai novērtētu problēmu izplatību un noteiktu to prioritāti.

- **Release_AudienceGroup** — norāda loku, no kura nāk dati. Ļauj mums pakāpeniski izlaist līdzekļus un identificēt potenciālās problēmas, pirms lielākā daļa lietotāju ir ar tām saskārušās.

- **Release_Channel** — kanāls, kurā tiek izlaists produkts. Ļauj mums noteikt, vai problēma ietekmē kādu no mūsu izlaišanas kanāliem citādi nekā citus.

- **RunningMode** — norāda, vai lietojumprogrammu palaiž lietotājs vai sistēmas process.

- **SchemaVersion** — norāda pašreizējo telemetrijas shēmas versiju OneNote telemetrijas kanālā.

- **session_EcsETag** — indikators no testējamo variantu sistēmas, kas apzīmē mašīnai nosūtītos testējamos variantus. Ļauj mums noteikt, kuri testējamie varianti, iespējams, ietekmē attiecīgo sesiju.

- **Session_ImpressionId** — norāda testējamo variantu kopu, kas darbojas konkrētajā sesijā. Ļauj mums noteikt, kuri konkrētie testējamie varianti darbojas sesijā, lai mēs varētu noteikt, vai testējamā versija ir tās problēmas cēlonis, kas ietekmē lietotājus.

- **SessionCorrelationId** — globāli unikāls identifikators resursdatora sesijai.

- **SH_ErrorCode** —  darbības neizdošanās gadījumā norāda kļūdas kodu, ja ir.

- **Tag** — vesela skaitļa tags, kas nosaka atrašanās vietu kodā, kurā tiek ģenerēts telemetrijas notikums.

- **UserInfo_IdType** — virkne, kas norāda lietotāja konta veidu.

- **UserInfo.OMSTenantId** — nomnieks, kuram ir piesaistīts lietotāja abonements. Ļauj mums klasificēt problēmas un noteikt, vai problēma ir plaši izplatīta vai izolēta konkrēta nomnieka lietotāju kopā.

- **UserInfo_OtherId** — lietotāja kontus identificējošo pseidonīmu identifikatoru, kas nav primāri, saraksts.

- **UserInfo_OtherIdType** —  kontu veidu, kas nav primāri, saraksts.

## <a name="data-fields-that-are-common-for-outlook-mobile-events"></a>Outlook mobilo notikumu kopīgie datu lauki

Outlook mobilā versija apkopo kopīgos laukus katram mūsu notikumam, kas ļauj mums nodrošināt to, ka lietojumprogramma ir atjaunināta uz jaunāko versiju, darbojas atbilstošā un drošā veidā. 

Tālāk norādītie datu lauki ir kopīgi visiem Outlook notikumiem iOS un Android operētājsistēmās.

- **aad_tenant_id** — klienta nomnieka ID, ja ir pieejams

- **account_cid** — identifikatora pseidonīms, kas apzīmē pašreizējo lietotāju

- **account_domain** — konta domēna nosaukums

- **account_puid** — globāli unikāls lietotāja identifikators Microsoft lietotāja kontam

- **account_type** — seko konta veidam, piemēram, Office 365, Google Cloud Cache, Outlook.com utt.

- **action** — notikuma darbības nosaukums (piemēram, arhivēšana, dzēšana utt.), lai mēs spētu atklāt problēmas ar konkrētām veiktajām darbībām

- **ad_id** — unikālais reklāmas identifikators

- **app_version**— instalētās lietojumprogrammas pašreizējā versija palīdz mums noteikt problēmas ar konkrētām lietojumprogrammu versijām

- **AppInfo.ETag** — unikāls identifikators mūsu līdzekļu laidienu pārvaldībai, kas palīdz mums atklāt problēmas, kas ietekmē konkrētu līdzekļu izlaišanu

- **AppInfo.Language** — pašreizējais ierīces valodas iestatījums, kas palīdz mums atklāt problēmas, kas ietekmē konkrētas valodas

- **AppInfo.Version**— instalētās lietojumprogrammas pašreizējā versija palīdz mums noteikt problēmas ar konkrētām lietojumprogrammu versijām

- **customer_type** — norāda klienta tipu (patērētājs, komerciālais, trešā puse utt.), kas palīdz mums atklāt problēmas ar konkrētie klientu veidiem

- **device_category** — norāda, kāda veida ierīce tā ir (tālrunis, planšetdators utt.) un palīdz mums atklāt ierīču kategorijām raksturīgas problēmas

- **DeviceInfo.Id** — unikāls ierīces identifikators, kas palīdz mums atklāt konkrētas problēmas

- **DeviceInfo.Make** — ierīces marka (piem., Apple, Samsung utt.) palīdz mums noteikt konkrētām ierīču markām raksturīgas problēmas

- **DeviceInfo.Model** — ierīces modelis (piem., iPhone 6s) palīdz atklāt konkrētiem ierīces modeļiem raksturīgas problēmas

- **DeviceInfo.NetworkType** — tīkls, kuru ierīce pašlaik izmanto (WiFi, mobilo datu tīkls, utt.), palīdz mums atklāt konkrētiem tīkliem raksturīgas problēmas

- **DeviceInfo.OsBuild** — pašreizējās ierīces operētājsistēmas būvējums palīdz mums atklāt problēmas, kas ietekmē konkrētus operētājsistēmu būvējumus

- **DeviceInfo.OsName** — operētājsistēmas nosaukums (piemēram, iOS) palīdz mums atklāt problēmas, kas ietekmē konkrētas platformas

- **DeviceInfo.OsVersion** — pašreizējās ierīces operētājsistēmas versija palīdz mums atklāt problēmas, kas ietekmē konkrētas operētājsistēmas versijas

- **DeviceInfo.SDKUid** — ierīces unikālais identifikators (līdzīgs DeviceInfo.Id)

- **EventInfo.InitId** — ID izmanto kā daļu no notikumu secības noteikšanas mūsu telemetrijas kanālā, lai palīdzētu mums atklāt kanāla problēmas galveno cēloni

- **EventInfo.SdkVersion** — SDK versija, ko izmantojam, lai nosūtītu mūsu telemetrijas datus, lai atklātu kanāla problēmas galveno cēloni

- **EventInfo.Sequence** — secība notikumu secības noteikšanai mūsu telemetrijas kanālā, lai palīdzētu mums atklāt kanāla problēmas galveno cēloni

- **EventInfo.Source** — norāda uz koda daļu, kas nosūtīja notikumu, lai palīdzētu mums atklāt problēmas galveno cēloni

- **EventInfo.Time** — datums un laiks, kad notikums tika pārraidīts no ierīces, lai mūsu sistēmas spētu veiksmīgi pārvaldīt ienākošos notikumus

- **eventpriority** — telemetrijas notikuma prioritāte attiecībā pret citiem notikumiem, lai mūsu sistēmas varētu veiksmīgi pārvaldīt ienākošos notikumus

- **first_launch_date** — laiks, kad ierīce tika palaista pirmo reizi, palīdz mums saprast, kad sākās problēmas

- **hashed_email** — identifikatora pseidonīms, kas apzīmē pašreizējo lietotājā e-pastu

- **is_first_session** — atkļūdošanas vajadzībām izseko, vai šī ir lietojumprogrammas pirmā sesija

- **origin** — darbības izcelsme. Piemēram, ziņojuma atzīmēšana kā lasīta var izcelties no ziņojumu saraksta vai paziņojuma par jaunu e-pasta ziņojumu. Palīdz mums atklāt problēmas, kas ir saistītas ar darbības izcelsmi

- **PipelineInfo.AccountId** — identifikatora pseidonīms, kas apzīmē pašreizējo lietotāju

- **PipelineInfo.ClientCountry** — pašreizējā ierīces valsts, lai noteiktu valstij vai reģionam raksturīgas problēmas un traucējumus

- **PipelineInfo.ClientIp** — ierīces IP adrese, kurai ierīce ir pieslēgta, lai atkļūdotu savienojuma problēmas

- **PipelineInfo.IngestionTime** — laikspiedols, kad notiek šī notikuma telemetrijas uzņemšana

- **Session.Id** — unikāls lietojumprogrammas sesijas identifikators, kas palīdz mums atklāt ar sesiju saistītas problēmas

- **Session.ImpressionId** — unikāls identifikators, lai pārvaldītu mūsu līdzekļu laidienus un nodrošinātu, ka līdzekļi tiek sekmīgi izlaisti visiem lietotājiem un ierīcēm

- **ui_mode** — norāda, vai lietotājs izmanto gaišo vai tumšo saskarnes režīmu, un palīdz mums diagnosticēt UX kļūdas tumšajā režīmā

- **UserInfo.Language** — lietotāja valoda palīdz mums atkļūdot tulkojumu teksta problēmas

- **UserInfo.TimeZone** — lietotāja laika josla palīdz mums atkļūdot kalendāra problēmas


Tālāk norādītie lauki ir kopīgi visiem Outlook darbam ar iOS notikumiem.

- **cloud** — kur šajā ierīcē atrodas pastkaste, lai palīdzētu mums atklāt problēmas, kas ir raksturīgas konkrētai mākoņa pastkastei, piemēram, Office 365 vai GCC.

- **DeviceInfo.NetworkProvider** — tīkla, kuram pieslēgta ierīce, operators (piem., Verizon)

- **gcc_restrictions_enabled** — norāda, vai GCC ierobežojumi tika piemēroti lietojumprogrammai, lai mēs spētu nodrošināt to, ka mūsu GCC klienti izmanto mūsu lietojumprogrammu drošā veidā

- **office_session_id** — unikāls ID, kas izseko sesijai pievienotajiem Office pakalpojumiem, lai palīdzētu mums atklāt Office pakalpojumu integrēšanai Outlook, piemēram, Word, raksturīgas problēmas

- **state** — norāda, vai lietojumprogramma bija aktīva, kad šis notikums tika nosūtīts, lai palīdzētu atklāt problēmas, kas raksturīgas aktīvajiem vai neaktīvajiem lietojumprogrammu stāvokļiem


Tālāk norādītie lauki ir kopīgi visiem Outlook darbam ar Android notikumiem.

- **DeviceInfo.NetworkCost** — norāda ierīces pašreizējā tīkla izmaksas, kas atspoguļo WiFi/mobilo datu tīkla/viesabonēšanas statusu, lai palīdzētu atklāt ierīces tīklam raksturīgas problēmas

- **is_app_in_duo_split_view_mode** — informē mūs par to, ka ierīce bija Duo dalītā ekrāna režīmā.  Šis rekvizīts ir iestatīts tikai Duo ierīcēm (tikai Android).

- **is_dex_mode_enabled** — norāda, vai Samsung DeX režīms ir iespējots, lai palīdzētu noteikt problēmas, kas raksturīgas DeX režīmam Samsung ierīcēs

- **is_sliding_drawer_enabled** — vai bīdāmās atvilktnes saskarne ir iespējota, lai palīdzētu mums atklāt problēmas ar mūsu bīdāmās atvilktnes saskarni

- **orientation** — ekrāna fiziskais novietojums (portrets/ainava), kas palīdz mums atklāt ierīces novietojumam raksturīgas problēmas

- **os_arch** — ierīces operētājsistēmas arhitektūra palīdz mums atklāt ierīču operētājsistēmām raksturīgas problēmas

- **process_bitness** — procesa bitu skaits (32 vai 64 biti) lietojumprogrammai palīdz mums atklāt ierīces bitu skaitam raksturīgas problēmas

## <a name="software-setup-and-inventory-data-events"></a>Programmatūras iestatīšanas un inventāra datu notikumi

Tālāk ir norādīti šīs kategorijas datu apakštipi.
- [Office iestatīšana un inventārs](#office-setup-and-inventory-subtype)
- [Office pievienojumprogrammu konfigurācija](#office-add-in-configuration-subtype)
- [Drošība](#security-subtype)  

### <a name="office-setup-and-inventory-subtype"></a>*Office iestatīšana un inventāra apakštips*

Instalētais produkts, versija un instalēšanas statuss.

#### <a name="officeclicktorunupdatestatus"></a>Office.ClickToRun.UpdateStatus

Attiecas uz visām win32 lietojumprogrammām. Palīdz mums noteikt Office komplekta atjaunināšanas procesa statusu (izdošanās vai neizdošanās ar detalizētu informāciju par kļūdām)

Tiek apkopoti šādi lauki:

- **build** — pašreiz instalētā Office versija

- **channel** — Office izplatīšanas kanāls

- **errorCode** — kļūdas kods, kas norāda uz kļūmi

- **errorMessage** — papildu informācija par kļūdu

- **status** — pašreizējais atjauninājuma statuss

- **targetBuild** — versija, uz kuru tiek atjaunināta sistēma Office

#### <a name="officecompliancefileformatballotdisplayedonfirstboot"></a>Office.Compliance.FileFormatBallotDisplayedOnFirstBoot

Norāda, vai Office faila formāta izvēles dialoglodziņš tika parādīts lietotājam pirmo/otro reizi palaižot Word, Excel PowerPoint Win32 sistēmā.  Seko tam, vai tiek parādīts faila formāta izvēles dialoglodziņš — notikums tiek nosūtīts pirmajā/otrajā Word, Excel vai PPT palaišanas reizē Win32 sistēmā.

Tiek apkopoti tālāk norādītie lauki.

- **CountryRegion** — lietotāja valsts/reģiona iestatījums Windows sistēmā.

- **FileFormatBallotBoxAppIDBootedOnce** — kurā lietojumprogrammā (Word, Excel, PPT) tika apstrādāta faila formāta izvēles dialogloga parādīšanas loģika.

- **FileFormatBallotBoxDisplayedOnFirstBoot** — kāds ir faila formāta izvēles dialoglodziņa (parādīts/nav parādīts kā paredzēts/nav parādīts licences dēļ/nav parādīts atrašanās vietas dēļ) parādīšanas rezultāts.

#### <a name="officecompliancefileformatballotoption"></a>Office.Compliance.FileFormatBallotOption

Seko tam, vai tiek parādīts faila formāta izvēles dialoglodziņš — notikums tiek nosūtīts pirmajā/otrajā Word, Excel vai PPT palaišanas reizē Win32 sistēmā.  Norāda, vai Office faila formāta izvēles dialoglodziņš tika parādīts pirmajā Word, Excel vai PowerPoint palaišanas reizē Win32 sistēmā.

Tiek apkopoti tālāk norādītie lauki.

- **FileFormatBallotSelectedOption** — nosaka faila formāta opciju (OOXML/ODF), kuru lietotājs izvēlējās faila formāta izvēles dialoglodziņā.


#### <a name="officecorrelationmetadatautccorrelationmetadata"></a>Office.CorrelationMetadata.UTCCorrelationMetadata

Nolūkā izlabot un pabeigt datus apkopo Office metadatus, izmantojot UTC, lai salīdzinātu ar līdzīgiem datiem, kas ir apkopoti, izmantojot Office telemetrijas kanālu.

Tiek apkopoti tālāk norādītie lauki.

- **abConfigs** — saraksts, kurā ir uzskaitīti līdzekļu ID, lai noteiktu, kādi līdzekļi ir iespējoti klientā vai kuri līdzekļi ir tukši, ja dati netiek apkopoti.

- **abFlights** — "NoNL:NoFlights", ja nav iestatīti līdzekļu testējamie varianti. Pretējā gadījumā: "holdoutinfo=unknown".

- **AppSessionGuid** — tās attiecīgās lietojumprogrammas sesijas identifikators, kuras sākums ir procesa izveides laiks un kas ilgst līdz procesa beigām. Tas ir formatēts kā standarta 128 bitu GUID, ko veido četras daļas. Šo četru daļu secība ir: (1) 32 bitu procesa ID (2) 16 bitu sesijas ID (3) 16 bitu palaišanas ID (4) 64 bitu procesa izveides laiks: UTC 100ns

- **appVersionBuild** — programmas būvējuma versijas numurs.

- **appVersionMajor** — programmas galvenās versijas numurs.

- **appVersionMinor** — programmas papildversijas numurs.

- **appVersionRevision** — programmas pārskatītās versijas numurs.

- **audienceGroup** — laidiena auditorijas grupas nosaukums

- **audienceId** — laidiena auditorijas nosaukums

- **channel** — Office izplatīšanas kanāls

- **deviceClass** — ierīces formas faktors no operētājsistēmas

- **ecsETag** — procesa eksperimenta identifikators

- **impressionId** — GUID, kas norāda pašreizējo līdzekļu kopu.

- **languageTag** — pašreizējā Office IETF lietotāja interfeisa valodas tags

- **officeUserID** — nejauši ģenerēts GUID šai Office instalācijai

- **osArchitecture** — operētājsistēmas arhitektūra

- **osEnvironment** — vesels skaitlis, kas norāda operētājsistēmu (Windows, Android, iOS, Mac u.c.).

- **osVersionString** — operētājsistēmas versija

- **sessionID** — nejauši ģenerēts GUID, lai noteiktu programmas sesiju

- **UTCReplace_AppSessionGuid** — konstanta Būla vērtība. Vienmēr patiess.

#### <a name="officeonenotefirstrunfirstrun"></a>Office.OneNote.FirstRun.FirstRun

Kritiskais signāls, kas tiek lietots, lai nodrošinātu, ka jaunie lietotāji var sekmīgi palaist un lietot OneNote pirmo reizi.  Telemetrija, kas tiek apkopota kritiskas regresijas atklāšanai OneNote lietojumprogrammā un pakalpojuma darbspējā. Ja lietotājiem pirmo reizi neizdodas palaist lietojumprogrammu, tiks aktivizēts kritiskais incidents.

- **AfterOneDriveFrozenAccountError** — norāda kļūdu no OneDrive, kad konts ir sasaldēts.

- **Attempt** — reižu skaits, cik ir jāatkārto pirmās palaišanas pieredze.

- **IsDefaultNotebookCreated** — norāda, vai programma OneNote ir izveidojusi lietotāja noklusējuma piezīmju grāmatiņu.

- **IsDelayedSignIn** — norāda, vai pirmā palaišana ir aizkavētas pierakstīšanās režīmā, kur lietotājam nav nepieciešams pierakstīties.

- **IsMSA** — norāda, vai konts ir Microsoft konts.

#### <a name="officeonenotefirstrunfirstrunformsa"></a>Office.OneNote.FirstRun.FirstRunForMSA

Kritiskais signāls, kas tiek lietots, lai nodrošinātu, ka jaunie lietotāji (Microsoft konts) var sekmīgi palaist un lietot OneNote pirmo reizi.
Telemetrija, kas tiek izmantota kritiskas regresijas atklāšanai OneNote lietotnē un pakalpojuma darbspējā. Ja lietotājiem pirmo reizi neizdodas palaist lietojumprogrammu, tiks aktivizēts kritiskais incidents.

Tiek apkopoti šādi lauki:

- **Attempt** — reižu skaits, cik ir jāatkārto pirmās palaišanas pieredze.

- **Error A** — OneNote kļūdas objekts norāda kļūdu, kas radusies pirmās palaišanas laikā.

- **FAllowAddingGuide** — norāda, vai OneNote ļauj izveidot piezīmju grāmatiņu.

- **FrozenOneDriveAccount** — norāda, vai OneDrive konts ir sasaldēts.

- **IsDefaultNotebookCreated** — norāda, vai programma OneNote ir izveidojusi lietotāja noklusējuma piezīmju grāmatiņu.

- **NoInternetConnection** — norāda, vai ierīcei nav interneta savienojuma.

- **ProvisioningFailure** — OneNote kļūdas objekts, kas norāda nodrošinājuma kļūdu, ja tāda ir.

- **ProvisioningFinishedTime** — norāda beigu laiku, kad programma OneNote pabeigs savas piezīmju grāmatiņas nodrošināšanu pirmās palaišanas laikā.

- **ProvisioningStartedTime** — norāda sākuma laiku, kad programma OneNote sāk savas piezīmju grāmatiņas nodrošināšanu pirmās palaišanas laikā.

- **ShowSuggestedNotebooks** — norāda, vai OneNote parādīs ieteikto piezīmju grāmatiņas līdzekli.

#### <a name="officeonenotefirstrunfirstrunfororgid"></a>Office.OneNote.FirstRun.FirstRunForOrgId

Kritiskais signāls, kas tiek lietots, lai nodrošinātu, ka jaunie uzņēmuma lietotāji (AAD/OrganizācijasID) var sekmīgi palaist un lietot OneNote pirmo reizi.  Telemetrija, kas tiek izmantota kritiskas regresijas atklāšanai OneNote lietotnē un pakalpojuma darbspējā. Ja lietotājiem pirmo reizi neizdodas palaist lietojumprogrammu, tiks aktivizēts kritiskais incidents.

- **Attempt** — reižu skaits, cik ir jāatkārto pirmās palaišanas pieredze.

- **Error** — OneNote kļūdas objekts norāda kļūdu, kas radusies pirmās palaišanas laikā.

- **FAllowAddingGuide** — norāda, vai OneNote ļauj izveidot piezīmju grāmatiņu.

- **IsDefaultNotebookCreated** — norāda, vai programma OneNote ir izveidojusi lietotāja noklusējuma piezīmju grāmatiņu.

- **ProvisioningFailure** — OneNote kļūdas objekts, kas norāda nodrošinājuma kļūdu, ja tāda ir.

- **ProvisioningFinishedTime** — norāda beigu laiku, kad programma OneNote pabeigs savas piezīmju grāmatiņas nodrošināšanu pirmās palaišanas laikā.

- **ProvisioningStartedTime** — norāda sākuma laiku, kad programma OneNote sāk savas piezīmju grāmatiņas nodrošināšanu pirmās palaišanas laikā.

#### <a name="officeonenotefirstrunmrureadernotebookentries"></a>Office.OneNote.FirstRun.MruReaderNoteBookEntries 

Šis signāls tiek izmantots, lai fiksētu jebkādas problēmas piezīmju grāmatiņu pirmajā palaišanas reizē.  Telemetriju izmanto, lai pirmajā palaišanas reizē pārraudzītu, noteiktu un novērstu jebkādas problēmas.

Tiek apkopoti tālāk norādītie lauki: 

- **OnPremNBCount** — Piezīmju grāmatiņu skaits On Prem serverī

- **TotalNBCount** — Ar lietotāja kontu saistīto piezīmju grāmatiņu kopējais skaits

#### <a name="officetargetedmessagingensurecached"></a>Office.TargetedMessaging.EnsureCached 

Izseko, vai tika lejupielādēta dinamiskās pamatnes pakotne. Tiek uzskatīta par programmatūras konfigurāciju, jo pakotne ir sekmīgi jālejupielādē, lai iespējotu klientu atveidot pareizās iespējas. Tas ir īpaši būtiski patērētāju abonementos, kur mēs izmantojam pamatni, lai paziņotu lietotājam par licences derīguma termiņa beigām. Izmanto, lai izsekotu produkta lejupielādētās un kešotās dinamiskā satura pakotnes metadatiem, kā arī to darbību rezultātiem, kam tika pakļauta pakotne: lejupielādes kļūmēm, pakotnes atvēršanas kļūmēm, konsekvences pārbaudes kļūmēm, kešatmiņas trāpījumiem, pakotnes lietojumam un lejupielādes avotiem.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_CacheFolderNotCreated —** Būla karodziņš, kas norāda, vai izdevās izveidot kešatmiņas mapi

  - **Data\_CdnPath — pakotnes avota adrese —**

  - **Data\_EnsureCached —** Būla karodziņš, kas norāda, vai tika kešota satura pakotne

  - **Data\_ExistsAlready —** Būla karodziņš, kas norāda, ka pakotne jau tika iepriekš lejupielādēta un pastāv vēl viens lejupielādes mēģinājums

  - **Data\_GetFileStreamFailed —** avota pakotne nav pieejama avotā

  - **Data\_GetFileStreamFailedToCreateLocalFolder —** lokālā diska problēmas, kas izraisa kļūmes direktorija izveides laikā

  - **Data\_GetFileStreamFromPackageFailed —** karodziņš, kas norāda, vai pakotne ir lejupielādēta, bet klients nevar to nolasīt

  - **Data\_GetFileStreamFromPackageSuccess —** veiksmīgi mēģinājumi lasīt pakotni

  - **Data\_GetFileStreamSuccess —** nepastāv neviena ar disku vai konfigurāciju saistīta problēma, kas neatļauj lasīt failu plūsmu

  - **Data\_GetRelativePathsFailed —** relatīvais ceļš nenorāda uz pieejamu atrašanās vietu

  - **Data\_HashActualValue —** jaukšanas vērtība, kas tika iegūta no faila nosaukuma, lietojot pakotni

  - **Data\_HashCalculationFailed —** jaukšanas aprēķina kļūda

  - **Data\_HashMatchFailed —** jaukšanas neatbilstība starp pakotnes nosaukumu un kešotajām reģistra vērtībām

  - **Data\_HashMatchSuccess —** sekmīga jaukšanas konsekvences pārbaude

  - **Data\_PackageDownloadRequestFailed —** nevar lejupielādēt pakotni

  - **Data\_PackageDownloadRequestNoData —** lejupielādētajā pakotnē nav datu

  - **Data\_PackageDownloadRequestSuccess —** sekmīgi lejupielādēta pakotne

  - **Data\_PackageExplodedSuccess —** pakotnes atvēršanas mēģinājumu statuss

  - **Data\_PackageOpenFailed —** nesekmīgie pakotnes faila atvēršanas mēģinājumi

  - **Data\_PackageOpenSuccess —** sekmīgie pakotnes faila atvēršanas mēģinājumi

  - **Data\_SuccessHashValue —** jaukšanas vērtība, kas tika iegūta no faila nosaukuma, lejupielādējot pakotni

  - **Data\_SuccessSource —** virsma, kam tika lejupielādēta pakotne

#### <a name="officevisiovisiosku"></a>Office.Visio.VisioSKU

Nosaka, vai Visio SKU ir standarta vai profesionālā versija. Tas ir svarīgi, lai varētu kategorizēt problēmas, kuru pamatā ir SKU.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_VisioSKU**:**integer** — Standard SKU ir 0, bet Professional SKU — 1

#### <a name="onenoteapponenotelaunchednonactivated-previous-name-officeonenoteandroidapponenotelaunchednonactivated"></a>OneNote.App.OneNoteLaunchedNonActivated *(iepriekšējais nosaukums)*, Office.OneNote.Android.App.OneNoteLaunchedNonActivated

Ieraksta informācija par lietojumprogrammas aktivizēšanas statusu.  Dati tiek pārraudzīti, lai garantētu, ka mēs identificējam aktivizēšanas problēmu pieaugumu. Mēs arī analizējam datus, lai atrastu jomas, kurās nepieciešami uzlabojumi.

Tiek apkopoti šādi lauki: 

- **INSTALL_LOCATION** — norāda, vai lietojumprogramma ir sākotnēji instalēta vai lejupielādēta veikalā

#### <a name="onenoteresetstatus-previous-name-officeonenoteandroidresetstatus"></a>OneNote.ResetStatus *(iepriekšējais nosaukums)*, Office.OneNote.Android.ResetStatus

Šis signāls tiek izmantots, lai fiksētu jebkādas problēmas, kad lietotājs mēģina atiestatīt lietojumprogrammu.  Telemetriju izmanto, lai pārraudzītu, atklātu un novērstu jebkādas atiestatīšanas laikā radušās problēmas. 

Tiek apkopoti tālāk norādītie lauki: 

- **Accounts** — norāda uz kontu veidiem, kas tiek izmantoti, lai pieteiktos lietojumprogrammā

- **Generic String Type** — atgriež, ja tā ir pilna notes_light_data atiestatīšana

- **LaunchPoint** — punkts, no kura tiek sākta atiestatīšana. Iespējamās vērtības: poga Izrakstīties, izrakstīšanās kļūme, nostrādāja Intune

- **Pass** — norāda, vai atiestatīšana bija sekmīga

#### <a name="onenotesigninsignincompleted-previous-name-officeonenoteandroidsigninsignincompleted"></a>OneNote.SignIn.SignInCompleted *(iepriekšējais nosaukums)*, Office.OneNote.Android.SignIn.SignInCompleted

Kritiskais signāls, kas tiek izmantots, lai nodrošinātu, ka pierakstīšanās ir sekmīga vai nē. Telemetrija, kas tiek apkopota kritiskas regresijas atklāšanai OneNote lietojumprogrammā un pakalpojuma darbspējā.

Tiek apkopoti tālāk norādītie lauki: 

- **CompletionState** — pierakstīšanās beigu stāvoklis, sekmīga vai nesekmīga. Un kļūmju gadījumi

- **EntryPoint**— norāda pierakstīšanās sākuma vietu

- **Hresult** — kļūdas kods

- **Provider Package ID** — automātiskās pierakstīšanās gadījumā

- **Rezultāts** — izdevās, neizdevās, nezināms, atcelts

- **ServerType** — atgriež tā servera tipu, kas piedāvā pakalpojumu 

- **SignInMode** — paātrināta pierakstīšanās vai reģistrācija vai automātiska pierakstīšanās vai reģistrācija

#### <a name="onenotesigninsigninstarted-previous-name-officeonenoteandroidsigninsigninstarted"></a>OneNote.SignIn.SignInStarted *(iepriekšējais nosaukums)*, Office.OneNote.Android.SignIn.SignInStarted

Šis signāls tie izmantots, lai norādītu uz jebkādām problēmām, kas rodas izmantojot ziņojumu joslu.  Telemetriju izmanto, lai pārraudzītu, atklātu un novērstu jebkādas ziņojumu joslas izmantošanas laikā radušās problēmas

Tiek apkopoti tālāk norādītie lauki: 

- **EntryPoint**— norāda pierakstīšanās sākuma vietu

- **Result** — pierakstīšanās plūsmas rezultāts

- **ServerType** — atgriež tā servera tipu, kas piedāvā pakalpojumu 

- **SignInMode** — paātrināta pierakstīšanās vai reģistrācija vai automātiska pierakstīšanās vai reģistrācija


### <a name="office-add-in-configuration-subtype"></a>*Office pievienojumprogrammu konfigurācijas apakštips*

Programmatūras pievienojumprogrammas un to iestatījumi.

#### <a name="exceladdindefinedfunctioncustomfunctionsallinone"></a>Excel.AddinDefinedFunction.CustomFunctionsAllInOne

Apkopo informāciju par pielāgoto pievienojumprogrammu funkciju darbību izpildlaikā. Uztur izpildes mēģinājumu, veiksmīgas pabeigšanas, infrastruktūras kļūdu un lietotāja koda kļūdu skaitītājus. Tas tiek izmantots, lai noteiktu produktu uzticamības problēmas un izlabotu lietotāju ietekmējošas problēmas.
 
Tiek apkopoti tālāk norādītie lauki.

- **AsyncBegin** — asinhrono funkciju skaits, kas sākas.

- **AsyncEndAddinError** — asinhrono funkciju skaits, kas beidzas ar kļūdu.

- **AsyncEndInfraFailure** — asinhrono funkciju skaits, kas beidzas ar infrastruktūras kļūmi.

- **AsyncEndSuccess** — asinhrono funkciju skaits, kas beidzas veiksmīgi.

- **AsyncRemoveCancel** — atcelto asinhrono funkciju skaits. 

- **AsyncRemoveRecycle** — asinhrono funkciju skaits, kas tika noņemtas pārvietošanas uz atkritni dēļ. 

- **StreamingCycles1** — straumēšanas ciklu skaitītājs.

#### <a name="officeextensibilityappcommandsappcmdprojectionstatus"></a>Office.Extensibility.AppCommands.AppCmdProjectionStatus

Apkopo informāciju, lai izsekotu, kuras Office pievienojumprogrammu instalācijas sekmīgi atjaunināja lenti un kurām tas neizdevās.

Izmanto bieži sastopamu ar reģistrāciju saistītu problēmu novēršanai, ja pievienojumprogrammas tiek nepareizi instalētas un nekad neparādās, kā rezultātā kļūst nelietojamas.

Tiek apkopoti tālāk norādītie lauki.

  - Nav

#### <a name="officeextensibilityappcommandsaddsolution"></a>Office.Extensibility.AppCommands.AddSolution

Apkopo instalēšanas informāciju par Office pievienojumprogrammām, kas pielāgo lenti.  Tiek izmantots, lai atklātu problēmas ar to, kā pielāgotās pievienojumprogrammas modificē Office lenti.
 
Tiek apkopoti šādi lauki:

- **AppVersion** — lietojumprogrammas versija.

- **SolutionId** — risinājuma ID.

- **StoreType** — norāda programmas izcelsmi.

- **TelemetryId** — identitātes, ar kuru veikta pierakstīšanās, telemetrijas ID.


#### <a name="officeextensibilitycatalogexchangegetentitlements"></a>Office.Extensibility.Catalog.ExchangeGetEntitlements

Dati par sekmīgu vai nesekmīgu Office 365 nomnieka administratora piešķirto pievienojumprogrammu pilnvaru datu izgūšanu. Izmanto darbspējas rādītājiem, diagrammām un klientu problēmu analīzei.

Tiek apkopoti tālāk norādītie lauki.

  - **CachingResult —** rezultāts šādai darbībai: mēģinājums saglabāt pakalpojuma izsaukuma atgriezto vērtību

  - **ClientParameter —** klienta identifikators, kas nosūtīts pakalpojuma izsaukumā

  - **EntitlementsCount —** to pilnvaru skaits, kas ir paredzētas izsaukuma atbildē

  - **EntitlementsParsed —** to pilnvaru skaits, kas tiek parsēts no atbildes

  - **IsAllEntitlementsParsed —** informācija par to, vai paredzēto pilnvaru skaits atbilst parsēto pilnvaru skaitam

  - **ServiceCallHResult —** pakalpojuma izsaukuma API atgrieztais rezultāts

  - **TelemetryId —** GUID, kas apzīmē unikālu lietotāju

  - **UsedCache —** informācija par to, vai kešotā atbilde tika izmantota pakalpojuma izsaukuma vietā

  - **VersionParameter —** pakalpojuma izsaukumā nosūtītais Office versijas numurs

#### <a name="officeextensibilitycatalogexchangegetlastupdate"></a>Office.Extensibility.Catalog.ExchangeGetLastUpdate

Dati par sekmīgu vai nesekmīgu atjaunināto datu vajadzības izgūšanu attiecībā uz Office 365 nomnieka administratora piešķirtajām pievienojumprogrammām. Izmanto darbspējas rādītājiem, diagrammām un klientu problēmu analīzei. ExchangeGetLastUpdate vienmēr tiek izpildīts palaišanas laikā kā daļa no resursa koda un nosaka, vai ir mainījušās pievienojumprogrammu piešķires lietotājam.  Ja tā ir, tad tiek ielādēts osf.DLL, lai mēs varētu izsaukt ExchangeGetEntitlements ar mērķi iegūt konkrētas piešķires (tiek izsaukts arī ExchangeGetManifests, lai izgūtu jebkuru jaunu nepieciešamo manifestu).  ExchangeGetEntitlements (un ExchangeGetManifests) var izsaukt arī pēc pieprasījuma pēc tam, kad ir darbojusies viesošanas lietojumprogramma. Mērķis ir neielādēt lielu DLL, ja tas nav nepieciešams.  Ja šis notikums nebūtu nepieciešams, mēs nevarētu noteikt, vai lietotājiem izdodas iegūt viņiem piešķirtās pievienojumprogrammas, ja neizdodas pirmais pakalpojuma izsaukums. Tas ir arī galvenais veids, kā mēs uzzinām, vai pastāv kādas autorizācijas problēmas saistībā ar mūsu pakalpojumu izsaukšanu.

Tiek apkopoti šādi lauki:

  - **Abort —** informācija par to, vai pakalpojuma izsaukuma laikā tika izslēgta viesošana

  - **AllowPrompt —** informācija par to, vai tika atļauts autorizācijas vaicājums

  - **AuthScheme —** apmaiņas servera pieprasītā autentifikācijas shēma

  - **BackEndHttpStatus —** ziņotais HTTP kods, kad tiek izsaukts aizmugursistēmas apmaiņas serveris

  - **BackupUrl —** sekundārais apmaiņas URL, kas jāizsauc

  - **BEServer —** aizmugursistēmas apmaiņas servera nosaukums

  - **CalculatedBETarget —** pilnais aizmugursistēmas apmaiņas mašīnas nosaukums

  - **Call(n)\_TokenAuthError —** n-tā pakalpojuma izsaukuma mēģinājuma autentifikācijas kļūda

  - **Call(n)\_TokenIsValid —** informācija par to, vai n-tā pakalpojuma izsaukuma mēģinājuma autorizācijas pilnvara ir derīga

  - **CallMethod —** virkne, kas norāda, kuru ceļu izvēlējās kods

  - **ConfigSvcReady —** informācija par to, vai konfigurācijas pakalpojums jau ir iespējots

  - **Date —** apmaiņas servera atgrieztā vērtība

  - **DiagInfo —** apmaiņas servera atgrieztā informācija

  - **End\_TicketAuthError —** jebkura kļūda, kas radās, iegūstot autentifikācijas biļeti pēc pakalpojuma izsaukuma

  - **End\_TokenIsValid —** informācija par to, vai autentifikācijas biļete ir derīga pēc pakalpojuma izsaukuma

  - **EndingIdentityState —** identitātes objektu ziņotais statuss pēc pakalpojuma izsaukumu veikšanas

  - **EwsHandler —** apmaiņas servera atgrieztā vērtība

  - **FEServer —** priekšgalsistēmas apmaiņas serveris, kas apkalpo pieprasījumu

  - **HResult —** rezultāta kods

  - **HttpStatus —** apmaiņas servera atgrieztais HTTP statusa kods

  - **IsSupportedAuthResponse —** informācija par to, vai varam izmantot autentifikācijas tipu

  - **LastUpdateValueRegistry —** no reģistra atgrieztā jaukšanas vērtība

  - **LastUpdateValueRetrieved —** no pakalpojuma izsaukuma atgrieztā jaukšanas vērtība

  - **MSDiagnostics —** apmaiņas servera atgrieztā vērtība

  - **MsoHttpResult —** no HTTP API atgrieztā skaitītāja vērtība

  - **NeedRefresh —-** Šis ir patiess vai aplams lauks, kas norāda, vai pievienojumprogrammas dati ir novecojuši un ir jāatjaunina.

  - **PrimaryUrl —** galvenais URL, kam jāveic pakalpojuma izsaukums

  - **RequestId —** apmaiņas servera atgrieztā vērtība

  - **RequestTryCount —** pakalpojuma izsaukumu mēģinājumu skaits

  - **RequestTryCount —** apmaiņas servera izsaukumu mēģinājumu skaits

  - **ResultChain —** rezultātu kodu sērija no katra pakalpojuma izsaukuma mēģinājuma

  - **StartingIdentityState —** identitātes objektu ziņotais statuss pirms pakalpojuma izsaukumu veikšanas

  - **TelemetryId —** GUID, kas apzīmē unikālu lietotāju un nosaka, vai ir jāveic citi pakalpojuma izsaukumi

#### <a name="officeextensibilitycatalogexchangegetmanifests"></a>Office.Extensibility.Catalog.ExchangeGetManifests

Dati par sekmīgu vai nesekmīgu Office 365 nomnieka administratora piešķirto pievienojumprogrammu manifestu datu izgūšanu. Izmanto darbspējas rādītājiem, diagrammām un klientu problēmu analīzei.

Tiek apkopoti tālāk norādītie lauki.

  - **CachedManifestsParsed** — kešatmiņā atrasto manifestu skaits

  - **IsAllReturnedManifestsParsed** — informācija par to, vai visi atgrieztie manifesti tika parsēti

  - **ManifestsRequested** — nepieciešams manifestu skaits

  - **ManifestsReturned** — no servera atgriezto manifestu skaits

  - **ManifestsToRetrieve** — no servera izgūstamo manifestu skaits

  - **ReturnedManifestsParsed** — to manifestu skaits, kas tika atgriezti no servera un sekmīgi parsēti

  - **TelemetryId —** GUID, kas apzīmē unikālu lietotāju

#### <a name="officeextensibilityuxfensureloadosfdll"></a>Office.Extensibility.UX.FEnsureLoadOsfDLL 

Izseko nesekmīgi ielādētos Osf.DLL ierakstus. Nosaka DLL ielādes kļūmi, kas neļauj līdzeklim darboties.

Tiek apkopoti tālāk norādītie lauki.

  - Nav

#### <a name="officeextensibilityuxfensureloadosfuidll"></a>Office.Extensibility.UX.FEnsureLoadOsfUIDLL 

Izseko nesekmīgi ielādētos OsfUI.DLL ierakstus. Nosaka DLL ielādes kļūmi, kas neļauj līdzeklim darboties.

Tiek apkopoti tālāk norādītie lauki.

  - Nav

#### <a name="officeextensibilityuxfensureosfshareddllload"></a>Office.Extensibility.UX.FEnsureOsfSharedDLLLoad 

Izseko nesekmīgi ielādētos OsfShared.DLL ierakstus. Nosaka DLL ielādes kļūmi, kas neļauj līdzeklim darboties.

Tiek apkopoti tālāk norādītie lauki.

  - Nav

#### <a name="officeextensibilityvbatelemetrycomobjectinstantiated"></a>Office.Extensibility.VBATelemetryComObjectInstantiated

Apkopo informāciju par automatizācijas servera vai klienta aktivizēšanu VBA risinājumos. Izmanto, lai izprastu mijiedarbību starp VBA un COM objektiem.

Tiek apkopoti tālāk norādītie lauki.

  - **ComObjectInstantiatedCount** — COM objektu gadījumu izveides skaits

  - **HashComObjectInstantiatedClsid** — COM objektu klases identifikatora jaukšana

  - **HashProjectName** — VBA projekta nosaukuma jaukšana

  - **TagId** — unikāls tags

#### <a name="officeextensibilityvbatelemetrydeclare"></a>Office.Extensibility.VBATelemetryDeclare 

Apkopo informāciju par Win32 API aktivizēšanu VBA risinājumos. Izmanto, lai izprastu VBA un lietojuma mijiedarbību un lai papildinātu drošības izmeklēšanu.

Tiek apkopoti tālāk norādītie lauki.

  - **DeclareCount** – deklarāciju skaits

  - **HashDeclare** — DLL nosaukuma jaukšana

  - **HashEntryPoint** — API nosaukuma jaukšana

  - **HashProjectName** — VBA projekta nosaukuma jaukšana

  - **IsPtrSafe** — informācija par to, vai deklarācijas paziņojums ir saderīgs ar citu arhitektūru

  - **TagId** — unikāls tags

#### <a name="officeoutlookdesktopadd-insadd-inloaded"></a>Office.Outlook.Desktop.Add-ins.Add-inLoaded

Apkopo informāciju par to, vai Outlook ir sekmīgi vai nesekmīgi ielādējusi pievienojumprogrammu. Aktīvi pārrauga datus, lai nodrošinātu Outlook pareizu darbību ar klienta pievienojumprogrammām. Šie dati tiek izmantoti, lai noteiktu un izpētītu kļūmes.

Tiek apkopoti tālāk norādītie lauki.

  - **Standarta HVA darbība** ar lietderīgajiem datiem, kas nav pielāgoti.

#### <a name="officeoutlookmacaddinapiusage"></a>Office.Outlook.Mac.AddinAPIUsage

Apkopo pievienojumprogrammu veiksmīgu un neveiksmīgu izpildi Outlook programmā. Aktīvi pārrauga datus, lai nodrošinātu pareizu Outlook darbību ar pievienojumprogrammām. Šie dati tiek izmantoti, lai noteiktu un izpētītu kļūmes.

Tiek apkopoti tālāk norādītie lauki.

- **AccountType** — ar pievienojumprogrammām saistītā konta veids. 

- **Cookie** — pievienojumprogrammas izmantotais sīkfails.

- **DispId** — izsūtīšanas identifikators. 

- **EndTime** — pievienojumprogrammas beigšanās laiks. 

- **ExecutionTime** — pievienojumprogrammas izpildes laiks. 

- **Result** —  pievienojumprogrammas izmantošanas Outlook programmā rezultāts. 

- **StartTime** — pievienojumprogrammas palaišanas laiks.


#### <a name="officeoutlookmacaddineventapisusage"></a>Office.Outlook.Mac.AddinEventAPIsUsage

Apkopo pievienojumprogrammu veiksmīgu vai neveiksmīgu izpildi Outlook programmā. Aktīvi pārrauga datus, lai nodrošinātu pareizu Outlook darbību ar pievienojumprogrammām. Šie dati tiek izmantoti, lai noteiktu un izpētītu kļūmes.

Tiek apkopoti tālāk norādītie lauki.

- **AddinType** — pievienojumprogrammas veids. 

- **EventAction** — pievienojumprogrammas veiktā darbība. 

- **EventDispid** — izsūtīšanas identifikators.

- **EventResult** — pievienojumprogrammas veiktās darbības rezultāts. 

#### <a name="officeoutlookmacaddininstallationfrominclientstore"></a>Office.Outlook.Mac.AddInInstallationFromInClientStore

Apkopo pievienojumprogrammu instalēšanas veiksmes vai neveiksmes Outlook programmā. Aktīvi pārrauga datus, lai nodrošinātu pareizu Outlook darbību ar pievienojumprogrammām. Šie dati tiek izmantoti, lai noteiktu un izpētītu kļūmes.

Tiek apkopoti tālāk norādītie lauki.

- **AccountType** — ar pievienojumprogrammām saistītā konta veids. 

- **FailureReason** — pievienojumprogrammas instalēšanas neizdošanās iemesls. 

- **MarketplaceAssetId** — pievienojumprogrammas veikala identifikators. 

- **Status** — pievienojumprogrammas instalēšanas statuss.


#### <a name="officeprogrammabilityadd-insinternalsetconnectenterprise"></a>Office.Programmability.Add-ins.InternalSetConnectEnterprise

Notikums, kas tiek ģenerēts, ja COM pievienojumprogramma tiek ielādēta uzņēmuma ierīcē. 

Tiek apkopoti tālāk norādītie lauki.

  - **Activity Result** — savienojuma izveidošanas stāvoklis.

  - **Add-inconnectFlag** — pašreizējās ielādes darbība.

  - **Add-inId** — pievienojumprogrammas klases ID.

  - **Add-inTimeDateStamp** — pievienojumprogrammas laikspiedols no DLL metadatiem.

  - **IsBootInProgress** — norāda, vai Office lietojumprogramma ir ielādes procesā.

#### <a name="officevisiovisioaddonload"></a>Office.Visio.Visio.AddonLoad

Tver kļūdas, ja neizdodas ielādēt risinājumu. Nepieciešams pievienojumprogrammas ielādes kļūdu atkļūdošanai programmatūrā Visio.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_Load1Error:integer** — kļūdas vērtība Visio pievienojumprogrammas ielādes laikā.

#### <a name="officevisiovisioaddonusage"></a>Office.Visio.Visio.AddonUsage

Tver kļūdas, ja risinājuma funkcionalitātē pastāv kļūdas. Nepieciešams pievienojumprogrammas kļūdu atkļūdošanai.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_DocumentSessionLogID:string** — dokumenta sesijas identifikators

  - **Data\_IsEnabled**:**bool** — patiess, ja ir iespējots risinājums

  - **Data\_TemplateID:string** — veidnes GUID, kura tika ielādēts risinājums. Reģistrēts kā 0 pielāgotam risinājumam

  - **Data\_AddOnID**:**string** — GUID, lai identificētu ielādēto pievienojumprogrammu

  - **Data\_Error**:**integer** — kļūdas ID

### <a name="security-subtype"></a>*Drošības apakštips*

Dokumenta, līdzekļa un pievienojumprogrammas kļūdas nosacījumi, kas var negatīvi ietekmēt drošību, tostarp produktu atjauninājumu gatavību.

#### <a name="officesecurityactivationfilterclsidactivated"></a>Office.Security.ActivationFilter.CLSIDActivated

Izseko sistēmā Office aktivizētu konkrētu klases identifikatoru (Flash, Silverlight u.c.) Izmanto, lai izsekotu Flash, Silverlight un Shockwave bloķēto vadīklu ietekmi uz lietotājiem.

Tiek apkopoti tālāk norādītie lauki.

  - **ActivationType** — vadīklas aktivizācijas tips

  - **Blocked** — informācija par to, vai Office bloķēja vadīklu

  - **CLSID** — vadīklas klases identifikators

  - **Count** — cik reižu tika aktivizēta vadīkla

#### <a name="officesecurityactivationfilterfailedtoregister"></a>Office.Security.ActivationFilter.FailedToRegister

Izseko kļūdas stāvokli drošības uzlabojumā, kas bloķē bīstamu Office vadīklu aktivizēšanu.

Izmanto, lai diagnosticētu kļūdas stāvokli drošības uzlabojumā, kas var ietekmēt lietotāju drošību.

Tiek apkopoti tālāk norādītie lauki.

  - Nav

#### <a name="officesecuritycomsecurityfileextensionlistfromservice"></a>Office.Security.ComSecurity.FileExtensionListFromService

Izseko informācijai par to, vai konfigurācijas pakalpojumā tika lasīti pakotāja bloķēšanas paplašinājumi vai arī mēs izmantojām klienta noklusējuma sarakstu. Izmanto, lai nodrošinātu drošības uzlabojuma efektivitāti un aizsargātu Office lietotājus.

Tiek apkopoti tālāk norādītie lauki.

  - **RetrievedFromServiceStatus** — informācija par to, vai mums izdevās izgūt bloķējamo failu paplašinājumu sarakstu; ja neizdevās, kāds bija kļūdas iemesls

#### <a name="officesecuritycomsecurityload"></a>Office.Security.ComSecurity.Load

Izseko informācijai par to, vai dokumentā ir ielādēts OLE objekts. Izmanto, lai nodrošinātu drošības uzlabojuma efektivitāti un aizsargātu Office lietotājus.

Tiek apkopoti tālāk norādītie lauki.

  - **Clsid** — OLE vadīklas klases identifikators

  - **Count** — cik reižu tika ielādēta OLE vadīkla

  - **DocUrlHash** — jaukšana, kas unikāli apzīmē dokumentu. (Piezīme. No šī nevar noskaidrot faktisko detalizēto informāciju par dokumentu. Tas ir tikai unikāls dokumenta attēlojums.)

  - **IsCategorized** — informācija par to, vai OLE vadīkla ir kategorizēta ielādei sistēmā Office

  - **IsInsertable** — informācija par to, vai OLE vadīkla ir ievietojama vai nē

#### <a name="officesecuritycomsecurityobjdetected"></a>Office.Security.ComSecurity.ObjDetected

Izseko informācijai par to, vai dokumentā ir identificēts OLE objekts. Izmanto, lai nodrošinātu drošības uzlabojuma efektivitāti un aizsargātu Office lietotājus.

Tiek apkopoti tālāk norādītie lauki.

  - **Clsid** — OLE vadīklas klases identifikators

  - **Count** — cik reižu tika noteikts OLE objekts

  - **DocUrlHash** — jaukšana, kas unikāli apzīmē dokumentu. (Piezīme. No šī nevar noskaidrot faktisko detalizēto informāciju par dokumentu. Tas ir tikai unikāls dokumenta attēlojums.)

  - **IsCategorized** — informācija par to, vai OLE vadīkla ir kategorizēta ielādei sistēmā Office

  - **IsInsertable** — informācija par to, vai OLE vadīkla ir ievietojama vai nē

#### <a name="officesecuritycomsecuritypackageractivation"></a>Office.Security.ComSecurity.PackagerActivation

Izseko tāda drošības uzlabojuma rezultātam, kas bloķē bīstamu paplašinājumu iegulšanu Office dokumentos. Izmanto, lai nodrošinātu drošības uzlabojuma efektivitāti un aizsargātu Office lietotājus.

Tiek apkopoti tālāk norādītie lauki.

  - **FromInternet** — vai dokuments ir no interneta

  - **PackagerSetting** — kāds ir pašreizējā pakotāja iestatījums

  - **TrustedDocument** — vai dokuments ir uzticams

#### <a name="officesecuritycomsecuritypackageractivationerrors"></a>Office.Security.ComSecurity.PackagerActivationErrors

Izseko kļūdu stāvoklim drošības uzlabojumā, kas bloķē bīstamu paplašinājumu iegulšanu Office dokumentos. Izmanto, lai nodrošinātu drošības uzlabojuma efektivitāti un aizsargātu Office lietotājus.

Tiek apkopoti tālāk norādītie lauki.

  - **Error** — kļūdas kods

  - **Extension** — kāds ir faila paplašinājums

  - **FromInternet** — vai dokuments ir no interneta

  - **LinkedDocument** — vai dokuments ir saistīts vai nē

  - **PackagerSetting** — kāds ir pašreizējā pakotāja iestatījums

  - **TrustedDocument** — vai dokuments ir uzticams


#### <a name="officesecuritymacrointernetvbablockenabled"></a>Office.Security.Macro.InternetVBABlockEnabled

Izseko, vai bloķēšanas makro no interneta iestatījuma ir iespējots klientā. Novērtē drošības uzlabojuma lietojumu, lai aizsargātu pret ļaunprātīgiem makro.

Tiek apkopoti tālāk norādītie lauki.

  - Nav

#### <a name="officesecuritymacropolicydigsigtrustedpublishers"></a>Office.Security.Macro.PolicyDigSigTrustedPublishers

Izseko, vai makro pieder uzticamam izdevējam. Izmanto, lai nodrošinātu drošības uzlabojuma efektivitāti un aizsargātu Office lietotājus.

Tiek apkopoti tālāk norādītie lauki.

  - **Policy** — vai politika ir iestatīta un pieejama vai nē

#### <a name="officesecuritymacroprompted"></a>Office.Security.Macro.Prompted

Izseko informācijai par to, vai lietotājam tiek parādīta uzvedne iespējot VBA makro. Izmanto, lai novērtētu VBA makro izplatību un veicinātu nākotnes drošības uzlabojumus, kas ierobežo makro izpildi, reaģējot uz drošības pārkāpumiem.

Tiek apkopoti tālāk norādītie lauki.

  - **PromptType** — kāds uzvednes tips tika parādīts

  - **VBAMacroAntiVirusHash** — makro pretvīrusu jaukšana

  - **VBAMacroAntiVirusHRESULT** — pretvīrusu novērtēšanas rezultāts

#### <a name="officesecuritymacrovbasecureruntimesessionenablestate"></a>Office.Security.Macro.VBASecureRuntimeSessionEnableState

Izseko katrai AMSI izpildlaika pārbaudei, kas tika veikta makro izpildes laikā. Izseko makro izpildes AMSI izpildlaika pārbaudes efektivitātei un nosaka kļūdas, kas var ietekmēt lietotāju drošību.

Tiek apkopoti tālāk norādītie lauki.

  - **IsRegistry** — vai administrators ir iestatījis reģistra ignorēšanu

  - **State** — kāds ir droša izpildlaika statuss

#### <a name="officesecuritymacroxl4prompted"></a>Office.Security.Macro.XL4Prompted

Izseko informācijai par to, vai lietotājam tiek parādīta uzvedne iespējot XL4 makro. Izmanto, lai novērtētu XL4 makro izplatību programmā Excel nolūkā veicināt nākotnes drošības uzlabojumus, kas bloķē XL4 pēc noklusējuma, reaģējot uz drošības incidentiem, kas ietver XL4 makro nepareizu izmantošanu.

Tiek apkopoti tālāk norādītie lauki.

  - **PromptType** — kāds uzvednes tips tika parādīts


#### <a name="officesecurityocxufiprompt"></a>Office.Security.OCX.UFIPrompt

Izseko informācijai par to, vai, ielādējot ActiveX vadīklu, kas ir atzīmēta kā nedroša inicializēšanai, lietotājam tiek parādīta drošības uzvedne. Izmanto, lai izsekotu UFI ActiveX vadīklu izplatībai Office dokumentos nolūkā veicināt uzlabojumus (piemēram, Killbitt vadīklas), reaģējot uz drošības incidentiem.

Tiek apkopoti tālāk norādītie lauki.

  - **IsFromInternet** — vai atvērtais dokuments ir no interneta

  - **IsSecureReaderMode** — dokuments ir atvērts drošā lasītājā

  - **OcxTrustCenterSettings** — kāds ir pašreizējais ActiveX iestatījums


#### <a name="officesecuritysecurereaderhostopeninosr"></a>Office.Security.SecureReaderHost.OpenInOSR

Izseko atvēršanas izpildei aizsargātajā skatā. Izmanto, lai noteiktu nosacījumus, kas izraisa kļūmes, atverot failu aizsargātajā skatā, un ietekmē klientu drošību un produktivitāti.

Tiek apkopoti tālāk norādītie lauki.

  - Nav

## <a name="product-and-service-usage-data-events"></a>Produktu un pakalpojumu lietojuma datu notikumi

Tālāk ir norādīti šīs kategorijas datu apakštipi.

- [Lietojumprogrammas līdzekļu sekmju novērtējums](#application-feature-success-subtype)
- [Lietojumprogrammas statuss un palaišana](#application-status-and-boot-subtype)
- [Office pieejamības konfigurācija](#office-accessibility-configuration-subtype)
- [Konfidencialitāte](#privacy-subtype)


### <a name="application-feature-success-subtype"></a>*Lietojumprogrammas līdzekļu sekmju apakštips*

Informācija par sekmīgu lietojumprogrammas funkcionalitāti. Attiecas tikai uz programmas un dokumentu atvēršanu un aizvēršanu, failu rediģēšana un failu koplietošanu (sadarbību).

#### <a name="account_action"></a>account_action

Nepieciešams, lai nodrošinātu veiksmīgu konta konfigurācijas darbību, un tiek izmantots, lai pārraudzītu konta izveides stāvokli, spēju pievienot jaunus e-pastu kontus un uzraudzītu mīkstos kontu atiestatījumus 

Tiek apkopoti šādi lauki: 

- **account_calendar_count** — cik daudz kalendāru ir kontam
 
- **action** — veicamās darbības veids, piemēram, izveidot kontu, dzēst kontu.
 
- **duration_seconds** — darbības ilgums
 
- **entry_point** — darbības ievades punkts, kā lietotājs uzsāka darbību
 
- **has_hx** — nosaka, vai ierīcei ir konts, kas izmanto jaunu e-pasta sinhronizācija pakalpojumu, bet ne obligāti konts, uz kuru tika vērsta darbība
 
- **is_hx** — nosaka, vai konts izmantot mūsu jauno e-pastu sinhronizācijas pakalpojumu
 
- **is_shared_mailbox** — vai darbība ir saistīta ar koplietotu pastkasti
 
- **number_of_accounts** — kopējais kontu skaits, attiecībā uz kuriem tiek veikta darbība
 
- **result** — darbības rezultāts, piemēram, izdevās, neizdevās.
   
- **server_type** — konta servera veids, līdzīgs konta tipam
 
- **shared_type** — koplietotā konta tips (ja konts ir koplietots)
 
- **scope** — darbības apjoms; konta dzēšanai šajā ierīcē vai visās ierīcēs
 
- **total_calendar_accounts** — kalendāra kontu skaits lietojumprogrammā darbības veikšanas brīdī
 
- **total_email_accounts** — e-pasta kontu skaits lietojumprogrammā darbības veikšanas brīdī
 
- **total_file_accounts** — failu kontu skaits lietojumprogrammā darbības veikšanas brīdī

#### <a name="account_lifecycle"></a>account_lifecycle

Šis notikums tiek apkopots, lai nodrošinātu veiksmīgu konta konfigurācijas darbību, un tiek izmantots, lai pārraudzītu konta izveides stāvokli, spēju pievienot jaunus e-pastu kontus un uzraudzītu mīkstos kontu atiestatījumus.

Tiek apkopoti šādi lauki: 

- **action** — kontā veiktās darbības veids, piemēram, pievienot, dzēst vai atiestatīt

#### <a name="add_new_account_step"></a>add_new_account_step

Šis pasākums ļauj mums noteikt, cik tālu lietotājs ir aizpildījis jauna konta izveides veidlapu.  Tas norāda, vai lietotājs ir pārgājis uz nākamo soli vai pārtraucis reģistrācijas procesu.  Šī informācija mums ir nepieciešama, lai noteiktu, vai visi soļi darbojas atbilstoši, un nodrošinātu veiksmīgu lietotāja konta izveidi. 

Tiek apkopots tālāk norādītais lauks: 

- **OTAddAccountCurrentStep** — tam var būt šādas vērtības: profile_form, redirect_mobile_check, mobile_check_success

#### <a name="app_error"></a>app_error

Izseko kritiskās lietojumprogrammu kļūdas, lai mēs spētu novērst problēmas, kas var izraisīt jūsu lietojumprogrammu avārijas vai traucēt jums lasīt e-pasta ziņojumus.

Tiek apkopoti šādi lauki: 

- **clientName** — mākoņa faila, kurā notika kļūda, klienta nosaukums, ja attiecināms.

- **cloudfile_error_type** — mākoņa failā notikušās kļūdas tips, ja attiecināms.

- **cloudfile_response_name** — mākoņa failā notikušās kļūdas atbildes nosaukums, ja attiecināms.

- **component_name** — lietojumprogrammas komponenta, kurā notika kļūda, nosaukums, piemēram, e-pasts vai kalendārs.

- **debug_info** — informācija par mākoņa failā notikušo kļūdu, kas tiek izmantota, lai noteiktu kļūdas iemeslu.

- **error_origin_identifier** — kļūdas, kas notika melnrakstā, izcelsme, ja attiecināms.

- **error_type** — notikušās kļūdas tips. Daži no paraugiem iekļauj saglabāt melnrakstu, sūtīt melnrakstu un mākoņa faila kļūda.

- **exrule** — paplašinātā kārtulas vērība (tiek pielietota tikai atkārtotām tikšanās kļūdām)

- **exrule** — paplašinātais kārtulas datums (tiek pielietots tikai atkārtotām tikšanās kļūdām)

- **has_attachments** — parāda, vai melnraksts, kurā notika kļūda, satur pielikumus, ja attiecināms.

- **is_IRM_protected** — parāda, ja melnraksts, kurā notika kļūda, ir aizsargāts ar informācijas tiesību pārvaldību, ja attiecināms.

- **is_legitimate** — parāda, vai kļūdas iemesls ir programmēšanas kļūda. Programmēšanas kļūdas tiek uzskatītas par nederīgām.

- **is_local** — parāda, vai melnraksts, kurā notika kļūda, tika sinhronizēts ar serveri, ja attiecināms.

- **is_recoverable** — parāda, vai no kļūdas ir iespējams atkopties vai tā ir fatāla kļūda.

- **rdate** — atkārtošanās kārtulas datums (tiek pielietots tikai atkārtotām tikšanās kļūdām) 

- **rrule** — atkārtošanās kārtula (tiek pielietots tikai atkārtotām tikšanās kļūdām) 

- **rrule_error_message** — atkārtošanās kārtulas parsēšanas kļūdas ziņojums (tiek pielietots tikai atkārtotām tikšanās kļūdām)

- **rrule_error_type** — atkārtošanās kārtulas parsēšanas kļūdas tips (tiek pielietots tikai atkārtotām tikšanās kļūdām)

- **status_code** — notikušās kļūdas statusa kods. Palīdz mums saprast kļūdas iemeslu.

Visas rakstzīmes ir arī iespējamie rekvizīti. Tas palīdz mums saprast rakstzīmes melnraksta ziņojumā kļūdas rašanās brīdī. Piemēram, “a”, “b” un “c” ir iespējamie rekvizīti.

#### <a name="app_launch_report"></a>app_launch_report

Šis notikums ļauj mums atklāt un novērst problēmas, ja Outlook palaišana notiek lēni vai nepilnīgi, apgrūtinot mūsu lietotājiem mūsu lietojumprogrammas izmantošanu. Tiek iekļauta informācija par konkrētiem iespējotajiem līdzekļiem un to, cik ilgu laiku aizņēma atsevišķi palaišanas posmi.

Tiek apkopoti šādi lauki: 

- **is_agenda_widget_active** — norāda, vai darba kārtības logrīks ir aktīvs.

- **is_alert_available** — norāda, vai lietojumprogramma ir konfigurēta, lai atļautu brīdinājumus paziņojumos.

- **is_background_refresh_available** — norāda, vai lietojumprogramma ir konfigurēta atsvaidzināties fonā.

- **is_badge_available** — norāda, vai lietojumprogramma ir konfigurēta, lai atļautu žetonus paziņojumos.

- **is_intune_managed** — norāda, vai lietojumprogramma ir Intune pārvaldīta.

- **is_registered_for_remote_notifications** — norāda, vai lietojumprogramma ir konfigurēta attālinātajiem paziņojumiem.

- **is_sound_available** — norāda, vai lietojumprogramma ir konfigurēta, lai atļautu skaņu paziņojumos.

- **is_watch_app_installed** — norāda, vai ir instalēta Outlook lietojumprogramma.

- **is_watch_paired** — norāda, vai Outlook lietojumprogramma pulkstenī ir piesaistīta galvenajai Outlook lietojumprogrammai.

- **launch_to_db_ready_ms** — norāda laiku, kas pagāja no Outlook lietojumprogrammas palaišanas brīža līdz datubāzes sagatavošanai.

- **num_calendar_accounts** — norāda kalendāra kontu skaitu lietojumprogrammā.

- **num_cloud_file_accounts** — norāda krātuves kontu skaitu lietojumprogrammā.

- **num_hx_calendar_accounts** — norāda kalendāra kontu skaitu, kas ir pieslēgti pie mūsu jaunā sinhronizācijas pakalpojuma.

- **num_hx_mail_accounts** — norāda e-pasta kontu skaitu, kas ir pieslēgti pie mūsu jaunā sinhronizācijas pakalpojuma.

- **num_mail_accounts** — norāda e-pasta kontu skaitu lietojumprogrammā.

#### <a name="calendar_action"></a>calendar_action

Izmanto, lai uzraudzītu jebkādu iespējamo negatīvu ietekmi uz jūsu spēju veikt galvenās kalendāra darbības, piemēram, notikumu izveidošana vai rediģēšana.  Šis notikums var iekļaut arī rekvizītu nosaukumu sērijas un informāciju par to, vai tie ir mainījušies. Piemēram, “title_changed”, “online_meeting_changed” un “description_changed” ir rekvizītu nosaukumi, kas palīdz mums noteikt, vai pastāv problēmas ar noteiktu rekvizītu rediģēšanu.

Tiek apkopoti šādi lauki: 

- **account_sfb_enabled** — palīdz mums pārliecināties par to, ka Skype darbam ir konfigurēts pareizi. 

- **action** — attiecībā pret kalendāru veiktās darbības veids. Iekļauj tādas darbības kā atvēršana, rediģēšana, saīsņu pievienošana, atlikšana utt. Palīdz mums nodrošināt atbilstošu kalendāra darbību un stabilitāti. 

- **action_result** — attiecībā pret kalendāra komponentēm veiktās darbības rezultāts. Šeit var tikt iekļautas tādas vērtības kā sekmīga vai nesekmīga izpilde, nezināms un noilgums. Izmanto, lai izsekotu darbību sekmīgas izpildes attiecībai un noteiktu, vai pastāv liela apjoma problēma ar kalendāra darbībām. 

- **attendee_busy_status** — ar darbību saistītā dalībnieka statuss brīvs/aizņemts. Šī vērtība var būt brīvs, aizņemts vai nezināms. Norāda, vai pastāv problēma ar darbībām, kas ir saistītas ar noteiktu aizņemtības statusu. 

- **availability** — pieejamības vērtība, ja vērtība brīvs/aizņemts ir mainījusies sapulces laikā. Norāda, vai ir problēmas ar konkrētas pieejamības vērtības iestatīšanu. 

- **calendar_onlinemeeting_default_provider** — satur noklusējuma tiešsaistes sapulču nodrošinātāju, izmantošanai ar servera atbalstītu tiešsaistes sapulču veidošanu. Iekļauj Skype, Skype darbam, Hangout un Teams darbam tipus. Palīdz atklāt potenciālās problēmas ar tiešsaistes sapulču veidošanu, izmantojot noteiktus nodrošinātājus. 

- **calendar_onlinemeeting_enabled** — patiess, ja kalendārs atbalsta servera atbalstītu tiešsaistes sapulču izveidošanu, balstoties uz noklusējuma sapulces nodrošinātāja. Norāda, vai pastāv problēmas ar kalendāriem ar iespējotām tiešsaistes sapulcēm. 

- **calendar_type** — kalendāra tips, kurā ir norādīts notikums pēc tam, kad lietotājs ir veicis sapulces rediģēšanu. Iespējamās vērtības iekļauj primārs, sekundārs, koplietots un grupas. Norāda, vai pastāv problēmas ar noteiktu kalendāru tipu. 

- **delete_action_origin** — veiktās dzēšanas darbības izcelsme. Iekļauj tādas vērtības kā navigācijas joslas rīkjosla un kapsulas rīkjosla.  Norāda, vai pastāv problēma ar sapulces dzēšanu no noteiktas atrašanās vietas. 

- **distribution_list_count** — adresātu sarakstā norādītais dalībnieku skaits. Palīdz mums noteikt, vai pastāv problēmas ar adresātu sarakstā esošajiem dalībniekiem. 

- **guest_count** — sapulces viesu skaits.  Ļauj mums pārliecināties par to, ka viesi tiek pievienoti pareizi. 

- **is_all_day** — izmanto kopā ar “meeting_duration”, lai norādītu, vai sapulce ilgst visu dienu. Norāda, vai pastāv problēmas ar darbībām, kas tiek veiktas attiecībā uz visu dienu ilgām sapulcēm. 

- **is_organizer** — palīdz mums noteikt, vai organizators spēj rediģēt un veidot sapulces atbilstošā veidā. 

- **is_recurring** — norāda, vai pastāv problēma, kas ietekmē tieši regulāri notiekošās sapulces. 

- **launch_point** — darbības palaišanas punkts. Var būt tādas vērtības kā logrīka galvene, logrīka kājene, visas dienas logrīks un kalendāra saīsne.  Norāda uz kontekstu, no kura tika sākta darbība. 

- **location_count** — atrašanās vietu skaits, kas ir iestatītas notikuma izveidošanas un rediģēšanas brīdī. Norāda, vai pastāv problēmas ar notikumu ar noteiktu atrašanās vietu skaitu veidošanu vai rediģēšanu. 

- **location_selection_source_type** — atrašanās vietas atlases avota tips. Var iekļaut tādas vērtības kā atrašanās vietas ieteikums, pielāgots vai esošs. Palīdz mums atklāt jebkāda veida problēmas ar atrašanās vietas atlasi no noteikta avota. 

- **location_session_id** — sapulces vietu atlasītāja ID. Palīdz mums atklāt problēmas ar atrašanās vietas pievienošanu sapulcei. 

- **location_type** — atlasītās atrašanās vietas tips.  Satur tādus tipus kā pielāgota atrašanās vieta, konferenču telpa un Bing. Palīdz mums izprast problēmas ar noteiktu atrašanās vietu pievienošanu sapulcēm. 

- **meeting_duration** — sapulces garums.  Palīdz mums pārliecināties par to, ka sapulces tiek konfigurētas ar pareizajiem laikiem. 

- **meeting_insights_type** — sapulču ieskatu tips notikuma detalizētajā informācijā.  Iekļauj failu un ziņojumu. Palīdz mums noteikt parādīto sapulču ieskatu skaitu. 

- **meeting_type** — ar darbību saistītās tiešsaistes sapulces tips.  Iekļauj Skype, Skype darbam, Hangout un Teams darbam tipus. Palīdz mums noteikt, vai tiešsaistes sapulces ir konfigurētas pareizi. 

- **origin** — kalendāra darbības izcelsme. Iekļauj tādus tipus kā darba kārtība, kalendārs, darba kārtības logrīks utt. Palīdz mums pārliecināties par to, ka mijiedarbība ar kalendāra komponentēm darbojas pareizi. 

- **recurrence_scope** — sapulces biežuma tips, regulāras vai sērijveida sapulces.  Palīdz noteikt, vai pastāv problēmas ar dažādu biežuma tipu sapulču rediģēšanu. 

- **reminder_time** — sapulces atgādinājuma laiks, ja tas ir mainīts.  Izmanto, lai pārliecinātos par to, ka sapulces atgādinājuma laiks ir saglabāts pareizi. 

- **reminders_count** — atgādinājumu skaits notikumā, ja atgādinājumi ir mainīti. Palīdz mums atklāt problēmas ar vairākiem atgādinājumiem notikumā. 

- **sensitivity** — sapulces konfidencialitātes līmenis. Iekļauj tipus normāla, personiska, privāta un konfidenciāla. Palīdz mums noteikt, vai sapulces konfidencialitātes līmenis tiek konfigurēts pareizi. 

- **session_duration** — sesijas ilgums milisekundēs. Palīdz mums noteikt, vai pastāv problēmas ar pieaugošo kalendāra darbību veikšanas laiku. 

- **shared_calendar_result** — kopīgotā kalendārā veiktās darbības rezultāts. Iespējamās vērtības iekļauj labi, nav atļaujas, nezināms, lokālais īpašnieks vai īpašnieks ir grupa. Palīdz mums noteikt kopīgotajos kalendāros veikto darbību uzticamību. 

- **time_picker_origin** — saglabāšanas darbības laika atlasītāja izcelsme. Iekļauj tādas vērtības kā vairāk opciju un mazāk opciju. Palīdz mums noteikt, kā lietotājs pārvietojās plūsmā, lai saglabātu sapulci, un nodrošināt pareizu darbību 

- **nosaukums** — automātiski ieteiktais nosaukums no lietojumprogrammā definētajām vērtībām. Iekļauj tādas vērtības kā “zvans”, “pusdienas” un “Skype”. Palīdz noteikt, vai nosaukuma automātiskā ieteikšana ir konfigurēta pareizi. 

- **txp** — rezervācijas vai notikuma rezervācijas tips, ja ir. Iekļauj tādus tipus kā pasākumu rezervācija, lidojumu rezervācija, automašīnu nomas rezervācija utt. Palīdz mums noteikt, vai rezervācijas/rezervēšanas kartītes darbojas pareizi. 

- **upcoming_event_count** — plānoto notikumu skaits, kas tiek parādīts plānoto notikumu skatā. Norāda, vai pastāv problēmas ar plānoto notikumu skatu. 

- **upcoming_event_seconds_until_event** — sekunžu skaits līdz nākamā plānotā notikuma sākumam. Palīdz mums noteikt tipiskos notikumus, kas tiek parādīti plānoto notikumu skatā. 

- **value** — darbībai specifiska detalizēta informācija, piemēram, aizkaves likums vai “atkārtot līdz” kategorija.  Norāda uz kontekstu, kurā tika veikta darbība. 

#### <a name="combined_search_use"></a>combined_search_use

Izmanto, lai noteiktu iespējamo negatīvo ietekmi uz jūsu spēju izmantot galvenās meklēšanas funkcijas, piemēram, e-pastu, kontaktpersonu vai notikumu meklēšana.

Tiek apkopoti šādi lauki:  

- **account_switcher_action_type** – šis darbības tips seko tam, vai lietotājs izmantoja kontu pārslēdzēju, lai pārslēgtu kontus nejauši vai apzināti.

- **action** — meklēšanai veiktās darbības tips. Nosaka, vai meklēšana tika sākta, notiek vai ir beigusies un kādas darbības notika meklēšanas laikā, piemēram, vai tika izmantots mikrofons. Kritiski svarīgs, lai nodrošinātu precīzu un lietderīgu meklēšanu.

- **action_type** — meklēšanai veiktās darbības tips. Nosaka, vai meklēšana tika sākta, notiek vai ir beigusies un kādas darbības notika meklēšanas laikā, piemēram, vai tika izmantots mikrofons. Kritiski svarīgs, lai nodrošinātu precīzu un lietderīgu meklēšanu. 

- **answer_result_selected_count** — izseko, cik daudz reižu meklēšana bija “veiksmīga”, t.i., vai lietotājs atrada meklēto personu? Uzrakstīja e-pasta ziņojumu? Atzīmēja ziņojumu ar grāmatzīmi? 

- **contact_result_in_full_list_selected_count** — izseko, cik reizes lietotājs pieprasīja “apskatīt visas kontaktpersonas” pilnā sarakstā kombinētās meklēšanas sesijas laikā

- **contact_result_selected_count** — izseko, cik kontaktpersonu rezultāti tika atlasīti kombinētās meklēšanas sesijas laikā

- **conversation_result_selected_count** — izseko, cik sarunas tika atlasītas kombinētās meklēšanas sesijas laikā

- **entrance_type** — nosaka, kā lietotājs uzsāka meklēšanas pieprasījumu, piemēram, no meklēšanas cilnes, nulles vaicājuma, meklēšanas galvenes vai meklēšanas rezultāta. 

- **has_contact_results** — norāda, vai kontaktpersonu rezultāti tiek parādīti meklēšanas vaicājumā

- **include_deleted** — norāda, vai meklēšana rāda dzēstās opcijas meklēšanas rezultātos 

- **re_enter_search_tab** — Būla vērtība, kas norāda, vai lietotājs ir pārslēdzis cilnes pirms meklēšanas rezultāta atlases

- **result_selected_type** — norāda attēloto datu veidu, ar kuru mijiedarbojas lietotājs, piemēram, skatīt visas kontaktpersonas, sarunas, notikumus utt. 

- **search_conversation_result_data** — satur datus par no meklēšanas rezultātiem atlasīto sarunu, tai skaitā konta tips (hx, ac, utt.), vai ziņojums atrodas mākoņa pakalpojumā un vai parādītā lapas nobīde atrodas vienā lapā ar pirmo ziņojumu. 

- **search_origin** — norāda uz meklēšanas izcelsmi, piemēram, balss asistents, Cortana, ievade ar tastatūru utt. 

- **search_request_reason** — norāda iemeslu, kura dēļ meklēšanas pieprasījums tika nosūtīts no lietojumprogrammas, norādot komponentu vai lietotāja darbību, kas uzsāka meklēšanu.

- **search_result_filter_type** — norāda, kāda veida filtrs tika piemērots meklēšanai, piem., rādīt visu vai tikai pielikumus

- **search_scope** — virkne norāda, kāda veida kontu meklēja lietotājs (piem., Exchange, Gmail utt.) vai tas bija meklējums visos kontos. 

- **search_session_ended_type** — norāda, kur beidzās meklēšana, jo tā tika atcelta vai vaicājums tika atjaunināts

- **search_suggestion_type**— norāda, kāds ir meklēšanas ieteikuma pamatojums, piemēram, vai tas ir pareizrakstības labojums? Balstīts vēsturē? Automātiskā pabeigšana?

- **see_all_contacts_selected_count** — izseko, cik reizes kombinētās meklēšanas sesijas laikā tika atlasīts “skatīt visas kontaktpersonas”

- **subtab_type** — izseko gadījumus, kad lietotājs atlasīja rezultātu no rezultātu cilnes

- **top_mail_result_selected_count** — izseko, cik reizes lietotājs atlasa populārākos rezultātus. 

#### <a name="compose_mail_accessory"></a>compose_mail_accessory

Šis notikums ļauj mums atklāt un novērst problēmas ar galvenajām e-pasta ziņojumu sastādīšanas darbībām, lai novērstu problēmas ar failu pievienošanu, fotoattēlu uzņemšanu un pievienošanu pielikumā vai jūsu pieejamības informācijas nosūtīšanu.

Tiek apkopoti šādi lauki: 

- **action** — norāda uz darbību, kuru bija mēģinājums veikt brīdī, kad darbība reģistrēta. Piemēram, faila pievienošana un papildu opciju piedāvāšana.

- **icon_name** — norāda ikonas nosaukumu, kas tiek parādīta brīdī, kad darbība tiek reģistrēta.

#### <a name="conversation_view_action"></a>conversation_view_action

Izmanto, lai uzraudzītu iespējamo negatīvo ietekmi uz jūsu spēju skatīt un atbildēt uz e-pasta ziņojumiem.

Tiek apkopoti šādi lauki:

- **contains_mention** — norāda, vai sarunā bija pielietots @ pieminējums, lai palīdzētu mums noteikt problēmas ar pieminējumiem e-pasta ziņojumos.

- **conversation_type** — norāda, kāda veida e-pasta ziņojuma skats tika renderēts, piemēram, viena ziņojuma skats vai vairāku ziņojumu skats. Palīdz atklāt ar konkrētiem ziņojumu veidiem saistītas problēmas mūsu e-pasta sarunu skatā.

- **suggested_reply_char_count** — parāda, cik rakstzīmes ieteiktās atbildes piedāvā (ja ir), lai palīdzētu mums atklāt ar ieteikumiem saistītas anomālijas un problēmas

- **suggested_reply_click_pos** — norāda, kurā pozīcijā ir norādīta ieteiktā atbilde (ja pieejama), lai mēs spētu atklāt problēmas ar konkrēto ieteikumu

- **use_default_quick_reply_mode** — norāda, vai tika izmantots ātrās noklusējuma atbildes režīms, lai palīdzētu mums atklāt ar ātrajām atbildēm e-pasta ziņojumos saistītās problēmas

#### <a name="draft_action"></a>draft_action

Izmanto, lai uzraudzītu iespējamo negatīvo ietekmi uz jūsu spēju veidot un saglabāt e-pasta ziņojumu melnrakstus.

Tiek apkopoti šādi lauki: 

- **action** — darbības veids, piemēram, saglabāt, atmest.
 
- **draft_message_id** — melnraksta ziņojuma ID

- **is_groups** — norāda, vai melnraksts tiek sūtīts no/uz grupas mapi
 
- **origin** — norāda melnraksta sākšanas vietu, piemēram, detalizēta ziņojuma informācija, sastādīšana.
 
- **thread_id** — sarunas, ar kuru ir saistīts melnraksts, pavediena ID

#### <a name="drag_and_drop"></a>drag_and_drop

Šis notikums ļauj mums noteikt, vai vilkšanas un nomešanas darbība bija veiksmīga.  Tiek izmantots, lai pārliecinātos par to, ka vilkšanas un nomešanas funkcija darbojas pareizi visās lietojumprogrammās, tai skaitā kā nomešanas iekš Outlook notikums un vilkšanas ārpus Outlook notikums.  Ar šo datu palīdzību mēs varam pārliecināties par pilnvērtīgu darbību ar citām lietojumprogrammām.

Tiek apkopoti šādi lauki: 

- **action** — darbība būs vilkt vai nomest

- **location** — vilkšanas darbības gadījumā informē mūs par vietu, kur lietotājs uzsāka vilkšanu.  Nomešanas darbības gadījumā informē mūs par vietu, kur lietotājs nometa vilkto failu. 

#### <a name="drawer_event"></a>drawer_event

Izmanto, lai uzraudzītu iespējamo negatīvo ietekmi uz jūsu piekļūt mapēm jūsu iesūtnē

Tiek apkopoti šādi lauki:

- **add_calendar_option** — norāda no atvilktnes pievienojamā kalendāra tipu, piemēram, interesējošais kalendārs, e-pasta kalendārs, kopīgots kalendārs, lai palīdzētu mums atklāt ar specifiskiem kalendāru veidiem saistītās problēmas

- **calendar_accounts_count** — norāda kalendāra kontu skaitu, kas palīdz mums atklāt problēmas ar jūsu kontu skaitu saistītās problēmas

- **calendar_apps_count** — norāda kalendāra lietojumprogrammu skaitu lietotāja ierīcē, lai palīdzētu mums atklāt ar kalendāra lietojumprogrammām saistītās problēmas

- **drawer_type** — norāda atvilktnes tipu: kalendārs, e-pasts vai nulles vaicājums, lai palīdzētu mums atklāt ar atvilktnes tipu saistītās problēmas

- **from_favorites** — norāda, vai darbība tika veikta no izlases, lai palīdzētu mums atklāt ar izlasi saistītās problēmas

- **group_calendar_count** — norāda uz konta kalendāru skaitu, lai palīdzētu mums atklāt ar grupu kalendāriem saistītās problēmas

- **inbox_unread_count** — norāda nelasīto ziņojumu skaitu iesūtnē, lai palīdzētu mums atklāt problēmas ar nelasīto ziņojumu skaita parādīšanu.

- **interesting_calendar_accounts_count** — norāda kontu skaitu, kas ir piemēroti interesējošiem kalendāriem ierīcē, lai palīdzētu mums atklāt ar interesējošiem kalendāriem saistītās problēmas

- **is_group_calendar** — norāda, vai kalendārs ir grupas kalendārs, lai palīdzētu mums atklāt ar grupas kalendāriem saistītās problēmas

- **mail_folder_type** — norāda pasta mapes veidu, piemēram, iesūtne, melnraksti utt., lai palīdzētu mums atklāt ar mapju tipiem saistītās problēmas.

- **mail_accounts_count** — norāda e-pasta kontu skaitu, lai palīdzētu mums atklāt ar e-pasta kontiem saistītās problēmas.

- **selected_group_calendar_count** — norāda UI atlasīto un aktīvo grupas kalendāru skaitu

- **visibility_toggle** — norāda, vai lietotājs ieslēdz vai izslēdz konkrētu kalendāru, lai palīdzētu mums atklāt ar kalendāru rādīšanu vai slēpšanu saistītās problēmas

#### <a name="ipccreaterepublishinglicense"></a>IpcCreateRepublishingLicense

Tiek apkopots, kad lietotājs mēģina atvērt ar IRM aizsargātu dokumentu vai lietot IRM aizsardzību. Tas satur informāciju, kas ir nepieciešama pareizai tādu problēmu izmeklēšanai un diagnosticēšanai, kas notiek IpcCreateRepublishingLicense API izsaukuma laikā.

Tiek apkopoti tālāk norādītie lauki.

- **AppInfo.ClientHierarchy** — klienta hierarhija, kas norāda, ka lietojumprogramma darbojas ražošanas vidē vai izstrādātāja vidē

- **AppInfo.Name** — lietojumprogrammas nosaukums

- **AppInfo.Version** — lietojumprogrammas versija

- **iKey** — pieteikšanās pakalpojuma servera ID

- **RMS.Duration** — kopējais laiks API izsaukuma veikšanai

- **RMS.DurationWithoutExternalOps** — kopējais patērētais laiks mīnus ārējās operācijas, piemēram, tīkla latentums.

- **RMS.ErrorCode** — atgrieztais kļūdas kods, ja tāds ir, no API izsaukuma

- **RMS.HttpCall** — norāda, vai ir HTTP operācija

- **RMS.Result** — API izsaukums sekmīgs vai neizdevās

- **RMS.ScenarioId** — scenārija ID, ko definē API

- **RMS.SDKVersion** — tiesību pārvaldības pakalpojuma klienta versija

- **RMS.StatusCode** — atgrieztā rezultāta statusa kods

#### <a name="ipcgetlicenseproperty"></a>IpcGetLicenseProperty

Tiek apkopots, kad lietotājs mēģina atvērt ar IRM aizsargātu dokumentu vai lietot IRM aizsardzību. Tas satur informāciju, kas ir nepieciešama pareizai tādu problēmu izmeklēšanai un diagnosticēšanai, kas notiek IpcGetLicenseProperty API izsaukuma laikā.

Tiek apkopoti tālāk norādītie lauki.

- **AppInfo.ClientHierarchy** — klienta hierarhija, kas norāda, ka lietojumprogramma darbojas ražošanas vidē vai izstrādātāja vidē

- **AppInfo.Name** — lietojumprogrammas nosaukums

- **AppInfo.Version** — lietojumprogrammas versija

- **iKey** — pieteikšanās pakalpojuma servera ID

- **RMS.Duration** — kopējais laiks API izsaukuma veikšanai

- **RMS.DurationWithoutExternalOps** — kopējais patērētais laiks mīnus ārējās operācijas, piemēram, tīkla latentums.

- **RMS.ErrorCode** — atgrieztais kļūdas kods, ja tāds ir, no API izsaukuma

- **RMS.HttpCall** — norāda, vai ir HTTP operācija

- **RMS.LicensePropertyType** — licences rekvizīta tips

- **RMS.Result** — API izsaukums sekmīgs vai neizdevās

- **RMS.ScenarioId** — scenārija ID, ko definē API

- **RMS.SDKVersion** — tiesību pārvaldības pakalpojuma klienta versija

- **RMS.StatusCode** — atgrieztā rezultāta statusa kods

#### <a name="ipcgetserializedlicenseproperty"></a>IpcGetSerializedLicenseProperty

Tiek apkopots, kad lietotājs mēģina atvērt ar IRM aizsargātu dokumentu vai lietot IRM aizsardzību. Tas satur informāciju, kas ir nepieciešama pareizai tādu problēmu izmeklēšanai un diagnosticēšanai, kas notiek IpcGetSerializedLicenseProperty API izsaukuma laikā.

Tiek apkopoti tālāk norādītie lauki.

- **AppInfo.ClientHierarchy** — klienta hierarhija, kas norāda, ka lietojumprogramma darbojas ražošanas vidē vai izstrādātāja vidē

- **AppInfo.Name** — lietojumprogrammas nosaukums

- **AppInfo.Version** — lietojumprogrammas versija

- **iKey** — pieteikšanās pakalpojuma servera ID

- **RMS.Duration** — kopējais laiks API izsaukuma veikšanai

- **RMS.DurationWithoutExternalOps** — kopējais patērētais laiks mīnus ārējās operācijas, piemēram, tīkla latentums.

- **RMS.ErrorCode** — atgrieztais kļūdas kods, ja tāds ir, no API izsaukuma

- **RMS.HttpCall** — norāda, vai ir HTTP operācija

- **RMS.LicensePropertyType** — licences rekvizīta tips

- **RMS.Result** — API izsaukums sekmīgs vai neizdevās

- **RMS.ScenarioId** — scenārija ID, ko definē API

- **RMS.SDKVersion** — tiesību pārvaldības pakalpojuma klienta versija

- **RMS.StatusCode** — atgrieztā rezultāta statusa kods

#### <a name="ipcgettemplateissuerlist"></a>IpcGetTemplateIssuerList

Tiek apkopots, kad lietotājs mēģina atvērt ar IRM aizsargātu dokumentu vai lietot IRM aizsardzību. Tas satur informāciju, kas ir nepieciešama pareizai tādu problēmu izmeklēšanai un diagnosticēšanai, kas notiek IpcGetTemplateIssuerList API izsaukuma laikā.

Tiek apkopoti tālāk norādītie lauki.

- **AppInfo.ClientHierarchy** — klienta hierarhija, kas norāda, ka lietojumprogramma darbojas ražošanas vidē vai izstrādātāja vidē

- **AppInfo.Name** — lietojumprogrammas nosaukums

- **AppInfo.Version** — lietojumprogrammas versija

- **iKey** — pieteikšanās pakalpojuma servera ID

- **RMS.AuthCallbackProvided** — norāda, vai autentificēšanas atzvanīšana tiek nodrošināta kā API izsaukuma ievade

- **RMS.ConnectionInfo.ExtranetUrl** — ārtīkla savienojuma informācijas vietrādis URL

- **RMS.ConnectionInfo.IntranetUrl** — iekštīkla savienojuma informācijas vietrādis URL

- **RMS.ConnectionMode** — savienojuma režīms starp tiesību pārvaldības pakalpojuma klientu un serveri: tiešsaistē vai bezsaistē

- **RMS.Duration** — kopējais laiks API izsaukuma veikšanai

- **RMS.DurationWithoutExternalOps** — kopējais patērētais laiks mīnus ārējās operācijas, piemēram, tīkla latentums.

- **RMS.ErrorCode** — atgrieztais kļūdas kods, ja tāds ir, no API izsaukuma

- **RMS.GuestTenant** — lietotāja viesa nomnieka ID

- **RMS.HomeTenant** — lietotāja vietējā nomnieka ID

- **RMS.HttpCall** — norāda, vai ir HTTP operācija

- **RMS.Identity.ExtranetUrl** — lietotāja tiesību pārvaldības pakalpojuma servera ārtīkla URL, kas tiek apkopots, iegūstot jaunu tiesību konta sertifikātu no servera
 
- **RMS.Identity.IntranetUrl** — lietotāja tiesību pārvaldības pakalpojuma servera iekštīkla URL, kas tiek apkopots, iegūstot jaunu tiesību konta sertifikātu no servera

- **RMS.Identity.Status** — pirmā reize, lai iegūtu tiesību konta sertifikātu no servera vai atjaunotu tiesību konta sertifikātu 

- **RMS.Identity.Type** — lietotāja konta tips, piemēram, Windows konts vai Live konts

- **RMS.Identity.UserProvided** — norāda, vai lietotāja e-pasta adrese ir nodrošināta, kad saņemat jaunu tiesību konta sertifikātu no servera

- **RMS.IssuerId** — tiesību pārvaldības pakalpojuma servera ID, kas izsniedz tiesību konta sertifikātu 

- **RMS.LicenseFormat** — licences formāts: XrML vai JSON

- **RMS.RACType** — tiesību konta sertifikāta tips

- **RMS.Result** — API izsaukums sekmīgs vai neizdevās

- **RMS.ScenarioId** — scenārija ID, ko definē API

- **RMS.SDKVersion** — tiesību pārvaldības pakalpojuma klienta versija

- **RMS.ServerType** — tiesību pārvaldības pakalpojuma servera tips

- **RMS.StatusCode** — atgrieztā rezultāta statusa kods

- **UserInfo.UserObjectId** — lietotāja objekta ID

#### <a name="ipcgettemplatelist"></a>IpcGetTemplateList

Tiek apkopots, kad lietotājs mēģina atvērt ar IRM aizsargātu dokumentu vai lietot IRM aizsardzību. Tas satur informāciju, kas ir nepieciešama pareizai tādu problēmu izmeklēšanai un diagnosticēšanai, kas notiek IpcGetTemplateList API izsaukuma laikā.

Tiek apkopoti tālāk norādītie lauki.

- **AppInfo.ClientHierarchy** — klienta hierarhija, kas norāda, ka lietojumprogramma darbojas ražošanas vidē vai izstrādātāja vidē

- **AppInfo.Name** — lietojumprogrammas nosaukums

- **AppInfo.Version** — lietojumprogrammas versija

- **iKey** — pieteikšanās pakalpojuma servera ID

- **RMS.AuthCallbackProvided** — norāda, vai autentificēšanas atzvanīšana tiek nodrošināta kā API izsaukuma ievade

- **RMS.ConnectionInfo.ExtranetUrl** — ārtīkla savienojuma informācijas vietrādis URL

- **RMS.ConnectionInfo.IntranetUrl** — iekštīkla savienojuma informācijas vietrādis URL

- **RMS.ConnectionMode** — savienojuma režīms starp tiesību pārvaldības pakalpojuma klientu un serveri: tiešsaistē vai bezsaistē

- **RMS.Duration** — kopējais laiks API izsaukuma veikšanai

- **RMS.DurationWithoutExternalOps** — kopējais patērētais laiks mīnus ārējās operācijas, piemēram, tīkla latentums.

- **RMS.ErrorCode** — atgrieztais kļūdas kods, ja tāds ir, no API izsaukuma

- **RMS.GuestTenant** — lietotāja viesa nomnieka ID

- **RMS.HomeTenant** — lietotāja vietējā nomnieka ID

- **RMS.HttpCall** — norāda, vai pastāv HTTP operācija

- **RMS.Identity.ExtranetUrl** — lietotāja tiesību pārvaldības pakalpojuma servera ārtīkla URL, kas tiek apkopots, iegūstot jaunu tiesību konta sertifikātu no servera
 
- **RMS.Identity.IntranetUrl** — lietotāja tiesību pārvaldības pakalpojuma servera iekštīkla URL, kas tiek apkopots, iegūstot jaunu tiesību konta sertifikātu no servera

- **RMS.Identity.Status** — pirmā reize, lai iegūtu tiesību konta sertifikātu no servera vai atjaunotu tiesību konta sertifikātu 

- **RMS.Identity.Type** — lietotāja konta tips, piemēram, Windows konts vai Live konts

- **RMS.Identity.UserProvided** — norāda, vai lietotāja e-pasta adrese ir nodrošināta, kad saņemat jaunu tiesību konta sertifikātu no servera

- **RMS.IssuerId** — tiesību pārvaldības pakalpojuma servera ID, kas izsniedz tiesību konta sertifikātu 

- **RMS.LicenseFormat** — licences formāts: XrML vai JSON

- **RMS.RACType** — tiesību konta sertifikāta tips

- **RMS.Result** — API izsaukums sekmīgs vai neizdevās

- **RMS.ScenarioId** — scenārija ID, ko definē API

- **RMS.SDKVersion** — tiesību pārvaldības pakalpojuma klienta versija

- **RMS.ServerType** — tiesību pārvaldības pakalpojuma servera tips

- **RMS.StatusCode** — atgrieztā rezultāta statusa kods

- **RMS.TemplatesCount** — veidņu skaits

- **UserInfo.UserObjectId** — lietotāja objekta ID

#### <a name="ipcpcreatelicensefromscratch"></a>IpcpCreateLicenseFromScratch

Tiek apkopots, kad lietotājs mēģina atvērt ar IRM aizsargātu dokumentu vai lietot IRM aizsardzību. Tas satur informāciju, kas ir nepieciešama pareizai tādu problēmu izmeklēšanai un diagnosticēšanai, kas notiek IpcpCreateLicenseFromScratch API izsaukuma laikā.

Tiek apkopoti tālāk norādītie lauki.

- **AppInfo.ClientHierarchy** — klienta hierarhija, kas norāda, ka lietojumprogramma darbojas ražošanas vidē vai izstrādātāja vidē

- **AppInfo.Name** — lietojumprogrammas nosaukums

- **AppInfo.Version** — lietojumprogrammas versija

- **iKey** — pieteikšanās pakalpojuma servera ID

- **RMS.Duration** — kopējais laiks API izsaukuma veikšanai

- **RMS.DurationWithoutExternalOps** — kopējais patērētais laiks mīnus ārējās operācijas, piemēram, tīkla latentums.

- **RMS.ErrorCode** — atgrieztais kļūdas kods, ja tāds ir, no API izsaukuma

- **RMS.GuestTenant** — lietotāja viesa nomnieka ID

- **RMS.HomeTenant** — lietotāja vietējā nomnieka ID

- **RMS.HttpCall** — norāda, vai ir HTTP operācija

- **RMS.Identity.ExtranetUrl** — lietotāja tiesību pārvaldības pakalpojuma servera ārtīkla URL, kas tiek apkopots, iegūstot jaunu tiesību konta sertifikātu no servera

- **RMS.Identity.IntranetUrl** — lietotāja tiesību pārvaldības pakalpojuma servera iekštīkla URL, kas tiek apkopots, iegūstot jaunu tiesību konta sertifikātu no servera

- **RMS.Identity.UserProvided** — norāda, vai lietotāja e-pasta adrese ir nodrošināta, kad saņemat jaunu tiesību konta sertifikātu no servera

- **RMS.IssuerId** — tiesību pārvaldības pakalpojuma servera ID, kas izsniedz tiesību konta sertifikātu 

- **RMS.LicenseFormat** — licences formāts: XrML vai JSON

- **RMS.RACType** — tiesību konta sertifikāta tips

- **RMS.Result** — API izsaukums sekmīgs vai neizdevās

- **RMS.ScenarioId** — scenārija ID, ko definē API

- **RMS.SDKVersion** — tiesību pārvaldības pakalpojuma klienta versija

- **RMS.ServerType** — tiesību pārvaldības pakalpojuma servera tips

- **RMS.StatusCode** — atgrieztā rezultāta statusa kods

- **RMS.TokenProvided** — norāda, vai ir nodrošināts marķieris kā API izsaukuma ievade 

- **RMS.UserProvided** — norāda, vai ir nodrošināts klients kā API izsaukuma ievade 

- **UserInfo.UserObjectId** — lietotāja objekta ID 

#### <a name="ipcpcreatelicensefromtemplate"></a>IpcpCreateLicenseFromTemplate

Tiek apkopots, kad lietotājs mēģina atvērt ar IRM aizsargātu dokumentu vai lietot IRM aizsardzību. Tas satur informāciju, kas ir nepieciešama pareizai tādu problēmu izmeklēšanai un diagnosticēšanai, kas notiek IpcpCreateLicenseFromTemplate API izsaukuma laikā. 

Tiek apkopoti tālāk norādītie lauki.

- **AppInfo.ClientHierarchy** — klienta hierarhija, kas norāda, ka lietojumprogramma darbojas ražošanas vidē vai izstrādātāja vidē

- **AppInfo.Name** — lietojumprogrammas nosaukums

- **AppInfo.Version** — lietojumprogrammas versija

- **iKey** — pieteikšanās pakalpojuma servera ID

- **RMS.AuthCallbackProvided** — norāda, vai autentificēšanas atzvanīšana tiek nodrošināta kā API izsaukuma ievade

- **RMS.ConnectionMode** — savienojuma režīms starp tiesību pārvaldības pakalpojuma klientu un serveri: tiešsaistē vai bezsaistē

- **RMS.Duration** — kopējais laiks API izsaukuma veikšanai

- **RMS.DurationWithoutExternalOps** — kopējais patērētais laiks mīnus ārējās operācijas, piemēram, tīkla latentums.

- **RMS.ErrorCode** — atgrieztais kļūdas kods, ja tāds ir, no API izsaukuma

- **RMS.HttpCall** — norāda, vai pastāv HTTP operācija

- **RMS.Result** — API izsaukums sekmīgs vai neizdevās

- **RMS.ScenarioId** — scenārija ID, ko definē API

- **RMS.SDKVersion** — tiesību pārvaldības pakalpojuma klienta versija

- **RMS.StatusCode** — atgrieztā rezultāta statusa kods

- **RMS.TokenProvided** — norāda, vai ir nodrošināts marķieris kā API izsaukuma ievade 

- **RMS.UserProvided** — norāda, vai ir nodrošināts klients kā API izsaukuma ievade 

#### <a name="ipcpgettemplatelistforuser"></a>IpcpGetTemplateListForUser

Tiek apkopots, kad lietotājs mēģina atvērt ar IRM aizsargātu dokumentu vai lietot IRM aizsardzību. Tas satur informāciju, kas ir nepieciešama pareizai tādu problēmu izmeklēšanai un diagnosticēšanai, kas notiek IpcpGetTemplateListForUser API izsaukuma laikā. 

Tiek apkopoti šādi lauki:

- **AppInfo.ClientHierarchy** — klienta hierarhija, kas norāda, ka lietojumprogramma darbojas ražošanas vidē vai izstrādātāja vidē

- **AppInfo.Name** — lietojumprogrammas nosaukums

- **AppInfo.Version** — lietojumprogrammas versija

- **iKey** — pieteikšanās pakalpojuma servera ID

- **RMS.ApplicationScenarioId** — scenārija ID, ko nodrošina lietojumprogramma

- **RMS.AuthCallbackProvided** — norāda, vai autentificēšanas atzvanīšana tiek nodrošināta kā API izsaukuma ievade

- **RMS.ConnectionInfo.ExtranetUrl** — ārtīkla savienojuma informācijas vietrādis URL

- **RMS.ConnectionInfo.IntranetUrl** — iekštīkla savienojuma informācijas vietrādis URL

- **RMS.ConnectionMode** — savienojuma režīms starp tiesību pārvaldības pakalpojuma klientu un serveri: tiešsaistē vai bezsaistē

- **RMS.Duration** — kopējais laiks API izsaukuma veikšanai

- **RMS.DurationWithoutExternalOps** — kopējais patērētais laiks mīnus ārējās operācijas, piemēram, tīkla latentums.

- **RMS.ErrorCode** — atgrieztais kļūdas kods, ja tāds ir, no API izsaukuma

- **RMS.GuestTenant** — lietotāja viesa nomnieka ID

- **RMS.HomeTenant** — lietotāja vietējā nomnieka ID

- **RMS.HttpCall** — norāda, vai ir HTTP operācija

- **RMS.Identity.ExtranetUrl** — lietotāja tiesību pārvaldības pakalpojuma servera ārtīkla URL, kas tiek apkopots, iegūstot jaunu tiesību konta sertifikātu no servera

- **RMS.Identity.IntranetUrl** — lietotāja tiesību pārvaldības pakalpojuma servera iekštīkla URL, kas tiek apkopots, iegūstot jaunu tiesību konta sertifikātu no servera

- **RMS.Identity.Status** — pirmā reize, lai iegūtu tiesību konta sertifikātu no servera vai atjaunotu tiesību konta sertifikātu 

- **RMS.Identity.Type** — lietotāja konta tips, piemēram, Windows konts vai Live konts

- **RMS.Identity.UserProvided** — norāda, vai lietotāja e-pasta adrese ir nodrošināta, kad saņemat jaunu tiesību konta sertifikātu no servera

- **RMS.IssuerId** — tiesību pārvaldības pakalpojuma servera ID, kas izsniedz tiesību konta sertifikātu 

- **RMS.LicenseFormat** — licences formāts: XrML vai JSON

- **RMS.RACType** — tiesību konta sertifikāta tips

- **RMS.Result** — API izsaukums sekmīgs vai neizdevās

- **RMS.ScenarioId** — scenārija ID, ko definē API

- **RMS.SDKVersion** — tiesību pārvaldības pakalpojuma klienta versija

- **RMS.ServerType** — tiesību pārvaldības pakalpojuma servera tips

- **RMS.StatusCode** — atgrieztā rezultāta statusa kods

- **RMS.TemplatesCount** — veidņu skaits

- **RMS.TokenProvided** — norāda, vai ir nodrošināts marķieris kā API izsaukuma ievade 
    
- **RMS.UserProvided** — norāda, vai ir nodrošināts klients kā API izsaukuma ievade 

- **UserInfo.UserObjectId** — lietotāja objekta ID 

#### <a name="ipcpserializelicense"></a>IpcpSerializeLicense

Tiek apkopots, kad lietotājs mēģina lietot IRM aizsardzību dokumentā. Tas satur informāciju, kas ir nepieciešama pareizai tādu problēmu izmeklēšanai un diagnosticēšanai, kas notiek IpcpSerializeLicense API izsaukuma laikā.

Tiek apkopoti tālāk norādītie lauki.

- **AppInfo.ClientHierarchy** — klienta hierarhija, kas norāda, ka lietojumprogramma darbojas ražošanas vidē vai izstrādātāja vidē

- **AppInfo.Name** — lietojumprogrammas nosaukums

- **AppInfo.Version** — lietojumprogrammas versija

- **iKey** — pieteikšanās pakalpojuma servera ID

- **RMS.ApplicationScenarioId** — scenārija ID, ko nodrošina lietojumprogramma

- **RMS.AuthCallbackProvided** — norāda, vai autentificēšanas atzvanīšana tiek nodrošināta kā API izsaukuma ievade

- **RMS.ConnectionMode** — savienojuma režīms starp tiesību pārvaldības pakalpojuma klientu un serveri: tiešsaistē vai bezsaistē

- **RMS.ContentId** — dokumenta satura ID

- **RMS.Duration** — kopējais laiks API izsaukuma veikšanai

- **RMS.DurationWithoutExternalOps** — kopējais patērētais laiks mīnus ārējās operācijas, piemēram, tīkla latentums.

- **RMS.ErrorCode** — atgrieztais kļūdas kods, ja tāds ir, no API izsaukuma

- **RMS.GuestTenant** — lietotāja viesa nomnieka ID

- **RMS.HomeTenant** — lietotāja vietējā nomnieka ID

- **RMS.HttpCall** — norāda, vai pastāv HTTP operācija

- **RMS.Identity.ExtranetUrl** — lietotāja tiesību pārvaldības pakalpojuma servera ārtīkla URL, kas tiek apkopots, iegūstot jaunu tiesību konta sertifikātu no servera

- **RMS.Identity.IntranetUrl** — lietotāja tiesību pārvaldības pakalpojuma servera iekštīkla URL, kas tiek apkopots, iegūstot jaunu tiesību konta sertifikātu no servera

- **RMS.Identity.Status** — pirmā reize, lai iegūtu tiesību konta sertifikātu no servera vai atjaunotu tiesību konta sertifikātu 

- **RMS.Identity.Type** — lietotāja konta tips, piemēram, Windows konts vai Live konts

- **RMS.Identity.UserProvided** — norāda, vai lietotāja e-pasta adrese ir nodrošināta, kad saņemat jaunu tiesību konta sertifikātu no servera

- **RMS.IssuerId** — tiesību pārvaldības pakalpojuma servera ID, kas izsniedz tiesību konta sertifikātu 

- **RMS.KeyHandle** — atslēgas tura atmiņas adrese

- **RMS.LicenseFormat** — licences formāts: XrML vai JSON

- **RMS.PL.KeyType** — vērtības 'vienkāršas' vai 'divkāršs'. Norāda, vai PL bija aizsargāts ar vienkāršas atslēgas vai divkāršas atslēgas aizsardzību.

- **RMS.RACType** — tiesību konta sertifikāta tips

- **RMS.Result** — API izsaukums sekmīgs vai neizdevās

- **RMS.ScenarioId** — scenārija ID, ko definē API

- **RMS.SDKVersion** — tiesību pārvaldības pakalpojuma klienta versija

- **RMS.ServerType** — tiesību pārvaldības pakalpojuma servera tips

- **RMS.StatusCode** — atgrieztā rezultāta statusa kods

- **RMS.TokenProvided** — norāda, vai ir nodrošināts marķieris kā API izsaukuma ievade 

- **RMS.UserProvided** — norāda, vai ir nodrošināts klients kā API izsaukuma ievade 

- **UserInfo.UserObjectId** — lietotāja objekta ID 

#### <a name="ipcsetlicenseproperty"></a>IpcSetLicenseProperty

Tiek apkopots, kad lietotājs mēģina atvērt ar IRM aizsargātu dokumentu vai lietot IRM aizsardzību. Tas satur informāciju, kas ir nepieciešama pareizai tādu problēmu izmeklēšanai un diagnosticēšanai, kas notiek IpcSetLicenseProperty API izsaukuma laikā. 

Tiek apkopoti tālāk norādītie lauki.

- **AppInfo.ClientHierarchy** — klienta hierarhija, kas norāda, ka lietojumprogramma darbojas ražošanas vidē vai izstrādātāja vidē

- **AppInfo.Name** — lietojumprogrammas nosaukums

- **AppInfo.Version** — lietojumprogrammas versija

- **iKey** — pieteikšanās pakalpojuma servera ID

- **RMS.Duration** — kopējais laiks API izsaukuma veikšanai

- **RMS.DurationWithoutExternalOps** — kopējais patērētais laiks mīnus ārējās operācijas, piemēram, tīkla latentums.

- **RMS.ErrorCode** — atgrieztais kļūdas kods, ja tāds ir, no API izsaukuma 

- **RMS.HttpCall** — norāda, vai pastāv HTTP operācija

- **RMS.LicensePropertyType** — licences rekvizīta tips

- **RMS.Result** — API izsaukums sekmīgs vai neizdevās

- **RMS.ScenarioId** — scenārija ID, ko definē API

- **RMS.SDKVersion** — tiesību pārvaldības pakalpojuma klienta versija

- **RMS.StatusCode** — scenārija ID, ko definē API

#### <a name="mail_action"></a>mail_action

Izmanto, lai uzraudzītu iespējamo negatīvo ietekmi uz jūsu spēju veikt kritiskas e-pasta darbības (piemēram, e-pasta darbība pavediena režīmā, pasta šķirošanas darbību izpilde), lai nodrošinātu mūsu lietojumprogrammas pareizu darbību ar e-pastu.

Tiek apkopoti šādi lauki:

- **account** — konts, kas veica darbību

- **action** — izseko veiktās darbības veidu, piem., arhivēt, dzēst, atzīmēt kā lasītu utt. 

- **attachment_content_type** — lejupielādētā pielikuma satura tips 

- **attachment_content_type_with_count** — seko pielikumu skaitam e-pasta ziņojumā

- **attachment_download_result** — pielikuma lejupielādes darbības rezultāts (piem., izdevās/neizdevās)

- **attachment_download_time** — pielikuma lejupielādes darbības laiks

- **attachment_extn** — lejupielādētā pielikuma faila paplašinājums

- **attachment_id** — lejupielādētā pielikuma sistēmas identifikators 

- **attachment_size** — lejupielādētā pielikuma izmērs

- **domain** — atveramā dokumenta domēns

- **duration** — izseko darbības ilgumam cilvēkam salasāmas virknes formātā (piem., 1 s, 4h) 

- **error** — ar darbību saistītās kļūdas ziņojums 

- **event_mode** — kāda veida notikuma režīmā tas bija, grupas vai cits. 

- **Extension** — ar šo darbību saistītā faila paplašinājuma saite vai pielikums 

- **internet_message_id** — ziņojuma izsekošanas ID

- **is_group_escalation** — norāda, vai ziņojums par darbības veikšanu tika nosūtīts uz lietotāja pastkasti eskalācijas dēļ (abonēta grupa)

- **is_rule** — norāda, vai veiktā e-pasta darbība atiestata svarīgo/citu klasifikāciju

- **is_threaded_mode** — norāda, vai ziņojums bija pavediena režīmā, t.i., kā ir grupēti ziņojumi

- **is_unread** — norāda, vai ziņojums, saistībā ar kuru tika veikta darbība, ir nelasīts

- **left_swipe_setting** — norāda, kāda darbība ir iestatīta kā pavilkšana pa kreisi

- **message_id** — servera ziņojuma ID, kas ir vērsts uz darbību, vai ar komatiem atdalīts saraksts, ja darbībā bija vairāki vienumi. 

- **message_type** — norāda, kāda tipa ziņojumā tika veikta darbība* * — grupas vai cits

- **origin** — darbības izcelsme, piem., šūnu pavilkšana, nulles vaicājums, dziļā saite, e-pasta skats, e-pastu saraksts utt.

- **reported_to_msft** — izvēle ziņot Microsoft par darbību pēc e-pasta ziņojuma nosūtīšanas uz mēstuļu mapi (surogātpasts) vai atkritni (pikšķerēšana).

- **retry** — norāda, vai darbība tika atkārtota

- **right_swipe_setting** — norāda, kāda darbība ir iestatīta kā pavilkšana pa labi 

- **shortcut** — norāda, vai tika izmantota saīsne un, kāda saīsne tika izmantota, lai ieplānotu ziņojumu, piemēram, vēlāk, rītdien, noteiktā laikā utt.

- **size** — ar šo darbību saistītās saites vai pielikuma izmērs

- **source_folder** — izseko avota mapes tipam, kad darbība norāda uz pārvietošanu no vienas mapes uz citu, piemēram, uz iesūtni, atkritni utt. 

- **source_inbox** — norāda, kurā iesūtnē notiek pasta darbība (piemēram, galvenajā, citā utt.)
state — darbības statuss, piem., izpildīta veiksmīgi vai neveiksmīgi

- **target_folder** — norāda mērķa mapes tipu, pārvietojot e-pasta ziņojumus no vienas mapes uz citu

- **thread_id** — darbībai pakļautās sarunas pavediena ID vai ar komatiem atdalīts saraksts, ja darbība tika piemērota vairākiem vienumiem. 

- **time_taken_to_fetch_access_token** — laiks sistēmas piekļuves marķiera izgūšanai, lai atvērtu saiti

- **time_taken_to_fetch_drive_item** — OneDrive resursa izgūšanas laiks noklikšķinot

- **time_taken_to_fetch_embed_viewer_resource** — iegultā skatītāja inicializācijai nepieciešamais laiks, atverot saites

- **time_taken_to_load_embed_viewer** — iegultā skatītāja inicializācijai nepieciešamais laiks, atverot saites

- **time_taken_to_load_link** — saites ielādes darbības pabeigšanai nepieciešamais laiks

- **time_taken_to_tap_attachment** — laiks no ziņojuma atvēršanas brīža līdz noklikšķināšanai uz pielikuma

- **time_taken_to_tap_link** — laiks, kas lietotājam pagāja no ziņojuma apskatīšanas līdz noklikšķināšanai uz saites

- **txp** — norāda, vai pastāv txp tipa vienums, kas ir saistīts ar e-pastu, kurā tika veikta darbība, piemēram, pasākuma rezervācija, lidojuma rezervācija utt. 

- **type** — caur saiti atveramā dokumenta tips

#### <a name="mail_compose"></a>mail_compose

Izmanto, lai uzraudzītu iespējamo negatīvo ietekmi uz jūsu spēju sastādīt un atbildēt uz e-pastiem, piemēram, problēmas ar atbildi visiem, jūsu e-pasta ziņojumu formatēšanu vai nosūtīšanu.

Tiek apkopoti šādi lauki: 

- **draft_message_id** — kā melnraksta izveidotās sarunas melnraksta ID, lai palīdzētu mums atklāt ar e-pastu ziņojumu melnrakstiem saistītās problēmas

- **message_id** — ziņojuma ID sarunai, uz kuru tiek atbildēts vai no kuras tiek pārsūtīts, lai palīdzētu mums atklāt ar konkrētu ziņojumu saistītās problēmas

- **origin** — norāda uz ziņojuma sastādīšanas izcelsmi, piemēram, atbildēt visiem, rakstīt jaunu vai ātrā atbilde. Palīdz mums atklāt problēmas, kas saistītas ar konkrētu atbildes izcelsmes tipu.

- **is_group_escalation** — norāda, vai ziņojums ir eskalēts grupas ziņojums, lai mēs varētu atklāt ar grupām saistītas sastādīšanas problēmas.

- **is_link** — norāda, vai jaunizveidotais melnraksts tika izveidots no saites. Palīdz mums atklāt problēmas, kas saistītas ar no saitēm veidotajiem melnrakstiem.

- **is_force_touch** — norāda, vai jauns melnraksts tika izveidots no piespied darbības.  Palīdz mums atklāt problēmas, kas saistītas melnrakstiem no šīs konkrētās darbības.

- **is_groups** — vai notikums tika sākts no grupu telpas, lai mēs varētu atklāt ar grupām saistītās sastādīšanas problēmas.

- **source_inbox** — norāda avota iesūtni, piemēram, vai tā ir galvenā vai cita iesūtne

- **thread_id** — pavedina ID sarunai, uz kuru tiek atbildēts vai no kuras tiek pārsūtīts, lai palīdzētu mums atklāt ar konkrētu pavedienu saistītās problēmas

#### <a name="meeting_call_to_action"></a>meeting_call_to_action

Izmanto, lai uzraudzīto iespējamo negatīvo ietekmi uz jūsu spēju veikt kritiskas sapulču darbības, piemēram, izveidošana, rediģēšana un atbilde uz sapulcēm.

Tiek apkopoti šādi lauki:

- **event_mode** — norāda, vai šis notikums ir no grupas, lai palīdzētu mums atklāt problēmas ar grupu notikumiem

- **meeting_id** — sapulces ID, kas palīdz mums izsekot problēmām sanāksmes darbības laikā, lai palīdzētu mums atklāt problēmas ar konkrētām sapulcēm

- **meeting_provider** — norāda tiešsaistes sapulces nodrošinātāju, piemēram, Teams, Skype darbam, lai palīdzētu mums atklāt problēmas ar konkrētiem sapulču nodrošinātājiem

- **notify_type** — norāda atbildes tipu citu kontu tipiem, lai palīdzētu mums atklāt problēmas ar dažādiem kontu tipiem

- **recurrence** — norāda, cik bieži notiek šī sapulce, piemēram, regulāri vai sērijveida, lai palīdzētu mums atklāt problēmas ar atkārtoti notiekošām sapulcēm

- **response** — norāda atbildes tipu, piemēram, piekrist vai noraidīt noteiktos kontu tipos, lai palīdzētu mums atklāt ar atbildēm uz notikumiem saistītās problēmas

- **response_message_length** — norāda ziņojuma garumu, lai palīdzētu mums atklāt problēmas ar sapulču atbildēm

- **review_time_proposal_action_type** — norāda lietotāja atbildi uz jauna laika piedāvājumu, lai palīdzētu mums atklāt problēmas ar jauna laika piedāvāšanu

- **send_response** — norāda, vai atbilde tika nosūtīta, lai palīdzētu mums atklāt problēmas ar atbilžu uz sapulču uzaicinājumiem nosūtīšanu

- **txp** — norāda sapulces tipu, no kura tas tika ģenerēts, no lidojumu rezervācijām un piegādēm, lai palīdzētu mums atklāt problēmas ar šī tipa sapulcēm

- **with_message_enabled** — norāda, vai lietotājs var atbildēt ar ziņojumu, lai palīdzētu mums atklāt problēmas ar atbildēšanu uz sapulču uzaicinājumiem

#### <a name="office_android_docsui_fileoperations_opendocumentmeasurements"></a>Office_Android_DocsUI_FileOperations_OpenDocumentMeasurements

Šis notikums tiek apkopots Office lietojumprogrammām, kas darbojas uz Android platformas, un reģistrē faila atvēršanas darbības. Šis notikums palīdz nodrošināt faila atvēršanas darbības drošību, atjauninājumus un pareizu darbību. Šo datu apkopošanas mērķis ir turpināt uzlabot failu atvēršanas veiktspēju. 

Tiek apkopoti šādi lauki:

- **Data_AppDocsOperationDuration** — apakšslānī pavadītais laiks faila atvēršanas darbības laikā.

- **Data_AppDuration** — lietojumprogrammā, kas veic faila atvēršanu, pavadītais laiks. 

- **Data_AppWarmUpGain** — lietojumprogrammas startēšanas laika pieaugums, kas notiek tāpēc, ka veicam lietojumprogrammas pirmsāknēšanas daļu.

- **Data_BootDuration** — lietojumprogrammas palaišanas ilgums faila atvēršanas procesā.

- **Data_Doc_AccessMode** — uzskaitījums, kas norāda uz faila piekļuves režīmu, piemēram, tikai lasāms, lasāms-rakstāms.

- **Data_Doc_AsyncOpenKind**— uzskaitījums, kas norāda asinhronās plūsmas veidu, kas tika izmantota faila atvēršanai.

- **Data_Doc_ChunkingType** — uzskaitījums, kas norāda faila dalīšanas algoritma veidu.

- **Data_Doc_EdpState** — uzskaitījums, kas norāda faila uzņēmuma datu aizsardzības statusu.

- **Data_Doc_Ext** — faila paplašinājums.

- **Data_Doc_Fqdn** — faila servera resursdatora nosaukums.

- **Data_Doc_FqdnHash** — globāli unikāls identifikators (GUID), kas unikāli identificē servera resursdatoru.

- **Data_Doc_IdentityTelemetryId** — GUID, kas unikāli identificē identitāti, kas tika izmantota, lai atvērtu failu. 

- **Data_Doc_InitializationScenario** — uzskaitījums, kas norāda detalizēto faila atvēršanas darbības scenārija veidu.

- **Data_Doc_IOFlags** — uzskaitījums, kas norāda faila atvēršanas darbības ievadizvades karodziņus, piemēram, vai fails ir kešots.

- **Data_Doc_IsCloudCollabEnabled** — vai failam ir iespējota sadarbība mākonī.

- **Data_Doc_IsIncrementalOpen** — vai fails tika atvērts ar inkrementālo atvēršanu.

- **Data_Doc_IsOcsSupported** — vai fails atbalsta Office sadarbības pakalpojumu.

- **Data_Doc_IsOpeningOfflineCopy** — vai fails tiek atvērts no bezsaistes kešatmiņas kopijas.

- **Data_Doc_IsPrefetched** — vai fails tika iepriekš ielādēts pirms atvēršanas darbības.

- **Data_Doc_IsSyncBacked** — vai mākonī esošajam failam ir lokālā versija un, vai tā ir sinhronizēta ar serveri.

- **Data_Doc_Location** — uzskaitījums, kas norāda uz faila atrašanās vietu, piemēram, atrodas lokāli vai mākonī.

- **Data_Doc_ReadOnlyReasons** — uzskaitījums, kas norāda faila tikai lasīšanas iemeslu.

- **Data_Doc_ResourceIdHash** — GUID, kas unikāli identificē faila servera resursa ID.

- **Data_Doc_RtcType** — uzskaitījums, kas norāda faila izmantotā reāllaika kanāla (RTC) veidu.

- **Data_Doc_ServerDocId** — GUID, kas unikāli identificē servera dokumenta ID.

- **Data_Doc_ServerProtocol** — uzskaitījums, kas norāda mākoņa faila servera protokolu.

- **Data_Doc_ServerType** — uzskaitījums, kas norāda mākoņa faila servera veidu.

- **Data_Doc_ServerVersion** — uzskaitījums, kas norāda mākoņa faila servera versiju.

- **Data_Doc_SessionId** — vesels skaitlis, kas pieaug par 1 ar katru faila atvēršanas darbību sesijas laikā.

- **Data_Doc_SharePointServiceContext** — virkne, kas tiek izmantota, lai savstarpēji saistītu klienta un servera žurnālus; parasti tas ir kāds ID veids.

- **Data_Doc_SizeInBytes** — dokumenta lielums baitos.

- **Data_Doc_SpecialChars** — uzskaitījums, kas norāda īpašās rakstzīmes veidu faila URL adresē.

- **Data_Doc_UrlHash** — GUID, kas unikāli identificē faila URL.

- **Data_Doc_UsedWrsDataOnOpen** — norāda, vai fails tika atvērts inkrementāli, izmantojot iepriekš kešotus WRS datus.

- **Data_Doc_WopiServiceId** — virkne, kas norāda, no kura pakalpojuma ir tīmekļa lietojumprogrammas atvērtās platformas interfeisa protokola (WOPI) fails.

- **Data_ErrorId_Code** — kļūdas kods, kas norāda uz datu vākšanas darbības kļūmi

- **Data_ErrorId_Tag** — atzīme kodā, kas palīdz noteikt kļūmes punktu

- **Data_InclusiveMeasurements** — virknes vērtība, kas uzskaita atsevišķu funkciju pieprasījumā pavadīto laiku formātā ar funkcijas birku un ilgumu, kas iekļauj apakšfunkciju pieprasījumu ilgumu. 

- **Data_InitializationReason** — uzskaitījums, kas norāda uz faila atvēršanas veidu, piemēram, lietotāja interfeisa elements vai citas lietojumprogrammas izsaukuma rezultātā utt.

- **Data_Measurements** — virknes vērtība, kas uzskaita atsevišķu funkciju pieprasījumā pavadīto laiku formātā ar funkcijas atzīmi un ilgumu, kas neiekļauj apakšfunkciju pieprasījumu ilgumu.

- **Data_OfficeMobileInitReason** — uzskaitījums, kas norāda faila atvēršanas ieejas punktu. 

- **Data_SilhouetteDuration** — faila atvēršanas renderēšanas ilgums.

- **Data_TimeSplitMeasurements**— virknes vērtība, kas uzskaita atsevišķu funkciju pieprasījumu ilgumu formātā ar funkcija birku, sākuma laikspiedolu un ilgumu. 

#### <a name="office_android_earlytelemetry_expansionfilesavailability"></a>Office_Android_EarlyTelemetry_ExpansionFilesAvailability

Mēs iespējojam Android pakotņu komplektu (APK) paplašināšanas failus mobilajai Office lietojumprogrammai. APK paplašināšanas faili ir papildu resursu faili, kurus Android lietojumprogrammu izstrādātāji var publicēt kopā ar savu lietojumprogrammu. Lai noteiktu paplašināšanas failu uzticamību, mēs reģistrējam karodziņu, kas norāda uz to, vai paplašināšanas faili ir vai nav pieejami katrā sāknēšanas reizē.

Tiek apkopoti šādi lauki:

- **Data_ExpansionFilesAvailable** — Būla karodziņš, kas norāda vai APK izplešanās faili ir pieejami ierīcē lietojumprogrammas sāknēšanas brīdī.

#### <a name="office_android_earlytelemetry_expansionfilesdownloader"></a>Office_Android_EarlyTelemetry_ExpansionFilesDownloader

Mēs iespējojam Android pakotņu komplektu (APK) paplašināšanas failus mobilajai Office lietojumprogrammai. APK paplašināšanas faili ir papildu resursu faili, kurus Android lietojumprogrammu izstrādātāji var publicēt kopā ar savu lietojumprogrammu.  Lai izprastu mūsu paplašināšanas faila lejupielādes mehānisma uzticamību, mēs reģistrējam karodziņu, kurš norāda, vai mēs spējam veiksmīgi lejupielādēt paplašināšanas failus.

Tiek apkopoti šādi lauki: 

- **Data_DownloadSuccess** — Būla karodziņš, kas norāda, vai APK paplašināšanas failu lejupielāde ir veiksmīga katru reizi, kad mēģinām veikt lejupielādi lietojumprogrammas sāknēšanas laikā.


#### <a name="office_android_intune_intunecompliancerequest"></a>Office_Android_Intune_IntuneComplianceRequest

Šis notikums tiek apkopots Office lietojumprogrammām, kas darbojas ar Android, tai skaitā Office mobilajām ierīcēm, Word, Excel, PowerPoint un OneNote. Šis notikums norāda uz mēģinājumu pierakstīties Intune licencētā organizācijas kontā, kuram organizācijas administrators ir konfigurējis politiku piekļuvei lietojumprogrammai ar nosacījumu. To izmanto, lai noteiktu gala lietotāju skaitu, kas mēģina izmantot lietojumprogrammas šajā politikas konfigurācijā, un šo notikumu apvieno ar citu notikumu, Office_Android_Intune_IntuneComplianceStatus, lai pārliecinātos par to, ka konfigurētā politika tiek ievērota. 

Datu lauki netiek apkopoti.

#### <a name="office_android_intune_intunecompliancestatus"></a>Office_Android_Intune_IntuneComplianceStatus

Šis notikums tiek apkopots Office lietojumprogrammām, kas darbojas ar Android, tai skaitā Office mobilajām ierīcēm, Word, Excel, PowerPoint un OneNote. Šis notikums norāda uz mēģinājumu pierakstīties Intune licencētā organizācijas kontā, kuram organizācijas administrators ir konfigurējis politiku piekļuvei lietojumprogrammai ar nosacījumu. Šis notikums norāda uz lietojumprogrammas, kurā lietotājs ir pierakstījies, atbilstības statusu un tiek izmantots, lai izmeklētu kļūmes. Tas tiek apvienots ar citu notikumu, Office_Android_Intune_IntuneComplianceRequest, lai nodrošinātu konfigurētās politikas ievērošanu.
  
Tiek apkopoti šādi lauki:

- **Data_ComplianceStatus** — norāda uz lietojumprogrammas atbilstības status pierakstīšanās laikā, izmantojot izdošanās vai kļūmes kodu.
  - -1 – Nezināma kļūda
  -    0 – lietojumprogramma atbilst organizācijas politikām
  - 1 – lietojumprogramma neatbilst organizācijas politikām
  - 2 — ar pakalpojumu saistītas kļūmes
  - 3 — ar tīklu saistītas kļūmes
  - 4 — lietojumprogrammai neizdevās izgūt autentifikācijas marķieri 
  - 5 — atbilde no pakalpojuma vēl nav saņemta
  - 6 — ir jāinstalē uzņēmuma portāla lietojumprogramma

#### <a name="officeandroidodwxpssotelemetry"></a>Office.Android.ODWXPSSO.Telemetry

Šis notikums palīdz izprast, ar kuru citu Microsoft lietojumprogrammu ierīcē mūsu lietojumprogramma saņēma kluso pierakstīšanos, no kura ieejas punkta un tā tālāk. Palīdz izprast klusās pierakstīšanās kļūmes iemeslu.  Mēs saņemam plašāku ieskatu par to, no kuras Microsoft lietojumprogramma ierīcē mēs saņemam vienotu pierakstīšanās pieredzi. Rīkoties reaģējot uz kļūmēm, kad vienotā pierakstīšanās nedarbojas, kā paredzēts.

Tiek apkopoti tālāk norādītie lauki:

- **AccountType** — norāda konta veidu, ar kuru notiek vienotā pierakstīšanās, piemēram, personiskais Microsoft konts vai darba konts.

- **EntryPoint** — norāda ieejas punktu lietojumprogrammā, no kura tika uzsākts vienotās pierakstīšanās mēģinājums.

- **ErrorCode** — norāda vienotās pierakstīšanās mēģinājuma kļūdas kodu.

- **ErrorDescription** — norāda vienotās pierakstīšanās mēģinājuma kļūdas ziņojumu.

- **HResult**— norāda vienotās pierakstīšanās mēģinājuma rezultāta statusa kodu.

- **ProviderPackageId** — cita Microsoft lietojumprogramma ierīcē, no kuras notiek vienotā pierakstīšanās.

#### <a name="officeandroidphonenumbersignins"></a>Office.Android.PhoneNumberSignIns

Šis notikums palīdz saprast, vai lietotājs ir pierakstījies vai pierakstījies ar tālruņa numuru saistītu kontu, vai ar personisko e-astu saistītu Microsoft kontu.  Šis notikums palīdz noteikt lietotāju pierakstīšanos vai reģistrāciju ar mobilo tālruņa numuru saistītu personisko Microsoft kontu.

Tiek apkopoti tālāk norādītie lauki:

- **EntryPoint** — norāda ieejas punktu lietojumprogrammā, no kura tika uzsākts pierakstīšanās mēģinājums.

- **IsEmailMissing** — vai konta profila informācijā trūkst e-pasta adreses?

- **IsPhoneNumberMissing** — vai konta profila informācijā trūkst tālruņa numura?

- **UserDecision** — norāda lietotāja veikto izvēli, piemēram, pierakstīšanās vai reģistrācija, vai pierakstīties vēlāk.

#### <a name="officeandroidusersignindecision"></a>Office.Android.UserSignInDecision

Šis notikums palīdz saprast, kura posmā lietotājs pārtrauc pierakstīšanās plūsmu, kāpēc pierakstīšanās neizdodas, cik daudz lietotājiem izdodas veiksmīgi pierakstīties no kura lietojumprogrammas ieejas punkta un tā tālāk.  Šis pasākums palīdz ar pierakstīšanās piltuves datiem, kas palīdz saprast, kurā posmā rodas kļūmes lielākam lietotāju skaitam un tā tālāk.

Tiek apkopoti tālāk norādītie lauki:

- **AccountType** — norāda konta veidu, ar kuru notiek pierakstīšanās mēģinājums, piemēram, personiskais konts vai darba konts.

- **AfterLicensingState** — norāda lietojumprogrammas licencēšanas statusu pēc pierakstīšanās pabeigšanas.

- **AllowedEditsWithoutSignIn** — norāda bezmaksas rediģējumu skaitu pirms pierakstīšanās mēģinājuma.

- **BeforeLicensingState** — norāda lietojumprogrammas licencēšanas statusu pirms pierakstīšanās mēģinājuma.

- **CompletionState** — norāda pierakstīšanās pabeigšanas posmu.

- **EntryPoint** — norāda ieejas punktu lietojumprogrammā, no kura tika uzsākts pierakstīšanās mēģinājums.

- **HRDAutoAcceleratedSignUpAttemptCount** — norāda uz paātrinātās pierakstīšanās mēģinājumu skaitu.

- **HRDAutoAcceleratedSignUpQuitCount** — norāda uz atcelto paātrinātās pierakstīšanās mēģinājumu skaitu.

- **HResult** — norāda pierakstīšanās darbības rezultāta statusa kodu.

- **IsPhoneOnlyAuthFeatureEnabled** — vai pierakstīšanās ar tālruņa numuru ir atļauta?

- **LicenseActivationHResult** — norāda licences aktivizēšanas mēģinājuma statusa kodu.

- **LicenseActivationMessageCode** — norāda licencēšanas pakalpojuma ziņojuma kodu.

- **NoFreeEditsTreatmentValue** — vai bezmaksas rediģēšana ir atļauta?

- **SignUpAttemptCount** — norāda uz pierakstīšanās mēģinājumu skaitu.

- **StartMode** — norāda režīmu, kurā tika sākts pierakstīšanās mēģinājums.

- **UserDecision** — norāda lietotāja veikto izvēli, piemēram, pierakstīšanās vai reģistrācija, vai pierakstīties vēlāk.

#### <a name="officeappcompatappcompatagentupload"></a>Office.AppCompat.AppCompat.AgentUpload

Tiek ģenerēts klienta palaišanas laikā, ja gala lietotājs ir iespējojis Office telemetrijas informācijas paneli.  Apkopo informāciju par to, kad Office telemetrijas aģents augšupielādē datus koplietošanas mapē. Šī notikuma primārais izmantošanas veids ir uzraudzīt Office telemetrijas aģenta stāvokli, bet sekundārais izmantošanas veids ir noteikt Office telemetrijas informācijas paneļa izmantošanu.

Tiek apkopoti tālāk norādītie lauki.

- **UploadTime** — Telemetrijas aģenta pēdējās veiksmīgās augšupielādes laikspiedols.


#### <a name="officeappcompatappcompatagentscanandupload"></a>Office.AppCompat.AppCompat.AgentScanAndUpload

Tiek apkopots tikai tad, ja lietotājs ir iespējojis Office telemetrijas informācijas paneli. Tas apkopo informāciju par to, kad tiek izpildīts Office telemetrijas aģents. Tiek apkopots tikai tad, ja ir iespējots Office telemetrijas informācijas panelis, un tiek izmantots, lai noteiktu Office telemetrijas aģenta darbspēju.

Tiek apkopoti tālāk norādītie lauki.

  - **Data.AgentExit** — laikspiedols, kas apzīmē sekmīgu telemetrijas aģenta iziešanu

  - **Data.AgentScan** — laikspiedols, kas apzīmē sekmīgu telemetrijas aģenta pabeigtu skenēšanu

  - **Data.AgentUpload** — laikspiedols, kas apzīmē sekmīgu telemetrijas aģenta pabeigtu augšupielādi

#### <a name="officeappcompatappcompattelemetrydashboardresiliencycrashlog"></a>Office.AppCompat.AppCompat.TelemetryDashboardResiliencyCrashLog

Tiek apkopts tikai tad, ja lietotājs (parasti administrators) ir iespējojis Office telemetrijas informācijas paneli. Tas apkopo Office pievienojumprogrammu un dokumentu avāriju gadījumus. Tas tiek apkopots tikai tad, ja lietotājs ir iespējojis Office telemetrijas informācijas paneli, un tiek izmantots, lai noteiktu, vai ir palielinājies pievienojumprogrammu vai dokumentu avārijas gadījumu skaits.

Tiek apkopoti tālāk norādītie lauki.

  - **Data.CollectionTime** — laikspiedols, kas apzīmē reģistrētu avārijas notikumu

#### <a name="office_apple_activateperpetual"></a>Office_Apple_ActivatePerpetual

Šo notikumu apkopo Office programmām, kas tiek lietotas Apple platformās. Pasākums tiek lietots, lai pārraudzītu pastāvīgā aktivizēšanas plūsmas darbspēju, kā arī izskatītu neveiksmes iemeslus, pārskatot FailedAt vērtības.

Tiek apkopoti šādi lauki:

- **Data_FailedAt** — mēs apkopojam virkni, kas norāda, kur pastāvīgās licences plūsmas aktivizēšanā radās kļūme.

#### <a name="office_apple_activatesubscription"></a>Office_Apple_ActivateSubscription

Šo notikumu apkopo Office programmām, kas tiek lietotas Apple platformās. Mēs apkopojam informāciju, kas saistīta ar migrāciju no mantotā licencēšanas koda steka uz vNext licencēšanas koda steku. To var izmantot, lai pārraudzītu abonementa aktivizēšanas plūsmas darbspēju, kā arī izsekošanu, ja šī ir migrācija uz licencēšanas vNext, un, ja tiek lietota primārā identitāte.

Tiek apkopoti šādi lauki:

- **Data_ActivatingPrimaryIdentity** — Patiesa/Nepatiesa vērtība, kas norāda, vai primārā identitāte tika lietota. 

- **Data_NULSubscriptionLicensed** — Patiesa/Nepatiesa, kas apzīmē abonementa statusu

#### <a name="office_apple_cisauthticketwithidentity"></a>Office.AppCompat.AppCompat.AgentUpload

Šis notikums tiek apkopots Office lietojumprogrammām, kas tiek darbinātas Apple platformās. Šis notikums tiek izmantots, lai tvertu autorizācijas marķiera ģenerēšanas kļūmes InAppPurchase notikuma laikā Mac datorā (notikums reģistrē saņemto kļūdas kodu).  Šis notikums tiek izmantots, lai noteiktu un palīdzētu novērst problēmas ar autorizācijas marķiera ģenerēšanas kļūmēm

Tiek apkopoti tālāk norādītie lauki.

- **Data_EmptyAuthToken** — mēs apkopojam virkni, kas norāda, kur pastāvīgās licences plūsmas aktivizēšanā radās kļūme.

- **Data_TicketAuthError** — kļūdas kods, kas norāda kļūmes cēloni

- **Data_ValidIdentity** — ja klientam ir derīga identitāte

#### <a name="office_apple_inappassociationactivity"></a>Office_Apple_InAppAssociationActivity

Šo notikumu apkopo Office programmām, kas tiek lietotas Apple platformās. Mēs apkopojam informāciju, kas saistīta ar produktu asociāciju pēc iegādes programmā. Mēs reģistrējam, kuru abonementu SKU apvienojam.  Šis līdzeklis tiek lietots, lai pārraudzītu, kāda ir iepirkuma produktu asociāciju darbspēja programmā.

Tiek apkopoti šādi lauki:

- **Data_ProductID** — abonementu SKU, ko cenšamies piesaistīt produktam.

#### <a name="office_apple_inapppurchaseactivity"></a>Office_Apple_InAppPurchaseActivity

Šo notikumu apkopo Office programmām, kas tiek lietotas Apple platformās. 

Mēs apkopojam informāciju, kas saistīta ar produktu pirkumiem AppStore. Mēs izsekojam iegādes rezultātu (neveiksmes, izdošanās, maksājuma problēma utt.), pirkšanas pieprasījuma tipu (atjaunošana, iepirkums) un iegādāto SKU/produktu (Office 365 mājas lietošanai utt.).  Šie dati tiek izmantoti, lai pārraudzītu iegādes plūsmas darbspēju programmā.

Tiek apkopoti šādi lauki:

- **Data_ Data_PurchaseResult** — pirkšanas rezultāts

- **Data_ProductID** — iegādātais produkts

- **Data_PurchaseRequestType** — pirkšanas pieprasījuma tips

#### <a name="office_apple_intune"></a>Office_Apple_InTune

Šo notikumu apkopo Office programmām, kas tiek lietotas Apple platformās. Mēs apkopojam, vai pašreizējai sesijai ir veikta Intune pārvaldība. Šis līdzeklis tiek lietots, lai rādītu rakursā/filtrētu Intune pārvldītās sesijas un ļauj mums izpētīt iespējamās problēmas, kas saistītas ar Office kā Intune pārvaldītai programmai.

Tiek apkopoti šādi lauki:

- **Data_EventID** — mēs apkopojam virkni, kas apzīmē kodu, kas norāda, vai sesija ir pārvaldīta kā Intune.

#### <a name="office_apple_licensing_mac_licensingstate"></a>Office_Apple_Licensing_Mac_LicensingState

Šo notikumu apkopo Office programmām, kas tiek lietotas Apple platformās. Pasākums tver pašreizējās sesijas licences statusu, kas tiek lietota sesijā (OLS licences ID, tiek lietots SKU, pagarinājuma periods vai nē, RFM utt.). Apkopotie dati tiek izmantoti kļūdu noteikšanai un neveiksmes cēloņu novēršanai. 

Tiek apkopoti šādi lauki:

- **Data_DidRunPreview** — virkne, kas norāda, vai šī sesija tiek palaista sadaļā priekšskatījums

- **Data_LicensingACID** — virkne, kas apzīmē licencēšanas sistēmas iekšējo identifikatoru

- **Data_LicensingType** — virkne, kas apzīmē licences tipu

- **Data_OLSLicenseId** — virkne, kas apzīmē licences identifikatoru

- **Data_State** — virkne, kas norāda licences pašreizējo statusu

#### <a name="officeconnectdeviceactivitystart"></a>Office.ConnectDevice.Activity.Start

Ļauj mums uzzināt, vai savienojums ar programmu vai ierīci ir sekmīgs.  Izmanto līdzekļu darbspējas veicināšanai un pārraudzībai. Šo notikumu ģenerē Microsoft Data Streamer Excel pievienojumprogrammai.

Tiek apkopoti tālāk norādītie lauki.

- **Datasource_Type** — sērijas ierīce vai programmas pakalpojuma informācija

- **DataSource_Name** — pievienoto datu avota nosaukums

- **Activity_Name** — darbības "ConnectDevice" nosaukums

- **Activity_CV** — ID, kas saista savienojuma sesijas notikumus

- **Activity_StartStopType** — sākums

- **Activity_DateTimeTicks** — darbības datums un laiks
 
#### <a name="officeconnectdeviceactivitystop"></a>Office.ConnectDevice.Activity.Stop

Ļauj mums uzzināt, vai savienojums ar programmu vai ierīci ir sekmīgs. Izmanto līdzekļa darbspējas veicināšanai un pārraudzībai. Šo notikumu ģenerē Microsoft Data Streamer Excel pievienojumprogrammai.

Tiek apkopoti tālāk norādītie lauki.

- **Datasource_Type** — sērijas ierīce vai programmas pakalpojuma informācija

- **DataSource_Name** — pievienoto datu avota nosaukums

- **Activity_Name** — darbības "ConnectDevice" nosaukums

- **Activity_CV** — ID, kas saista savienojuma sesijas notikumus

- **Activity_StartStopType** — apturēšana

- **Activity_DateTimeTicks** — darbības datums un laiks

#### <a name="office_docs_apple_docsuxiossaveasthroughfilemenu"></a>Office_Docs_Apple_DocsUXiOSSaveAsThroughFileMenu 

Šo notikumu apkopo Office programmām, kas darbojas Apple platformās. Pasākumu ieraksti, veicot darbību "Saglabāt kā" un tiek izmantoti, lai izprastu un noteiktu lietotāja pieredzes prioritāti, pamatojoties uz failu darbības informāciju, piemēram, atrašanās vietas kategorijām.  Darbība "Saglabāt kā" tiek veikta katru reizi, kad lietotājs izveido jaunu failu un saglabā to pirmo reizi vai saglabā esošā faila kopiju jaunā atrašanās vietā.

Tiek apkopoti šādi lauki:

- **Data_OriginServiceType** — sākotnējās faila atrašanās vietas abstrakta kategorizēšana, piemēram, "SharePoint", "OneDrive", "Local", "WOPI" utt. un kas nav faila faktiskā atrašanās vieta.

- **Data_ServiceType** — abstrakta jaunās atrašanās vietas kategorizēšana pēc saglabāšanas, piemēram, "SharePoint", "OneDrive", "Local", "WOPI" utt. un kas nav faila faktiskā atrašanās vieta.

#### <a name="office_docs_apple_docsuxmacatmentioninsertedatmention"></a>Office_Docs_Apple_DocsUXMacAtMentionInsertedAtMention 

Šo notikumu vāc Office programmām, kas darbojas Apple platformās. Šis notikums ieraksta, kad lietotājs "@" piemin citu lietotāju un izmanto, lai izprastu un noteiktu prioritāti lietotāja pieredzei, pamatojoties uz to, kā lietotāji sadarbojas ar citiem lietotājiem.

Tiek apkopoti šādi lauki:

- **Data_CharactersTyped** — skaitliska vērtība, kas norāda kopējo rakstzīmju skaitu "@" pieminēšanas tekstā.

#### <a name="office_docs_apple_docsuxmacodspsharingwebviewsharingcompleted"></a>Office_Docs_Apple_DocsUXMacODSPSharingWebViewSharingCompleted 

Šo notikumu apkopo Office programmām, kas tiek lietotas Apple platformās. Šis notikums ieraksta, ja lietotājs izvēlas koplietot mākoņa dokumentu, izmantojot OneDrive koplietošanas pieredzi, un tas tiek izmantots, lai labāk izprastu un noteiktu prioritātes lietotāja pieredzi, pamatojoties uz dokumentu koplietošanu.

Tiek apkopoti šādi lauki:

- **Data_ShareType** — stingri kodēta virkne, kas norāda, kāda veida kopīgošanas darbība ir pabeigta, tostarp, bet ne tikai, "Kopēt saiti", "Citas programmas", "Teams".

- **Data_ShareWebViewMode** — stingri kodēta virkne, kas norāda, kāda veida kopīgošana bija aktīva, kad kopīgošana bija pabeigta, ieskaitot ne tikai "ManageAccess", "AtMentions", "Share".

#### <a name="office_docsui_collaboration_coauthorgalleryrowtapped"></a>Office_DocsUI_Collaboration_CoauthorGalleryRowTapped 

Šo notikumu apkopo Office programmām, kas tiek lietotas Apple platformās. Šī notikums ieraksta, kad lietotājs atlasa, lai aplūkotu pašreizējo līdzautoru sarakstu.  Šie dati tiek izmantoti, lai labāk izprastu un noteiktu prioritātes lietotājam, kas saistīti ar dokumentu vienlaicīgu koprediģēšanu.

Tiek apkopoti šādi lauki:

- **Data_CoauthorCount** — skaitliska vērtība, kas apzīmē kopējo personu skaitu, kuras pašlaik rediģē to pašu dokumentu, ko lietotājs.

#### <a name="office_docsui_collaboration_collabcornerpeoplegallerycoauthorsupdated"></a>Office_DocsUI_Collaboration_CollabCornerPeopleGalleryCoauthorsUpdated 

Šo notikumu apkopo Office programmām, kas tiek lietotas Apple platformās. Notikums ieraksta, kad tiek mainīts aktīvo līdzautoru skaits mākonī.  Šie dati tiek izmantoti, lai labāk izprastu un noteiktu prioritātes lietotājam, kas saistīti ar dokumentu vienlaicīgu koprediģēšanu.

Tiek apkopoti šādi lauki:

- **Data_CoauthorsJoined** — līdzautoru skaits, kas pievienojās dokumentam.

- **Data_CoauthorsJoined** — līdzautoru skaits, kas pameta dokumentu.

- **Data_NewCoauthorCount** — jaunais aktīvo līdzautoru skaits dokumentā. 

- **Data_OldCoauthorCount** — iepriekšējo aktīvo līdzautoru skaits pirms atjauninājuma.

- **Data_ ServiceType** — abstrakta faila atrašanās vietas kategorizēšana, piemēram, "SharePoint", "OneDrive", "Local", "WOPI" utt., nevis faktiskā faila atrašanās vieta.

#### <a name="office_docsui_docstage_docstagecreatenewfromtemplate"></a>Office_DocsUI_DocStage_DocStageCreateNewFromTemplate 

Šo notikumu apkopo Office programmām, kas darbojas Apple platformās. Notikums ieraksta, kad tiek izveidots jauns fails, no darbības "Jauns no veidnes", un to izmanto, lai labāk izprastu un noteiktu prioritātes lietotāja pieredzei, pamatojoties uz dokumentu izveides informāciju.

Tiek apkopoti šādi lauki:

- **Data_InHomeTab** — Būla vērtība, kas norāda, vai jaunais fails no veidnes tika izveidots no faila jaunās pieredzes cilnes Sākums.

- **Data_InSearch** — Būla vērtība, kas norāda, vai fails tika izveidots, kad lietotājs meklēja veidni.

- **Data_IsHomeTabEnabled** — Būla vērtība, kas norāda, ja cilne Sākums pašlaik ir pieejama lietotājam.

- **Data_IsRecommendedEnabled** — Būla vērtība, kas norāda, ja pieredze "Ieteicams" pašlaik ir pieejama lietotājam.

- **Data_TemplateIndex** — veidnes faila skaitliskais indekss, kas tiek rādīts vizuāli lietotājam.

- **Data_TemplateType** — klasifikācija, kas palīdz atšķirt veidnes tipu, piemēram, bet ne tikai "Tiešsaistes" veidnes, "Tiešsaistes meklēšanas" veidnes, "Lokālās" veidnes.

#### <a name="office_docsui_docstage_recommendedopen"></a>Office_DocsUI_DocStage_RecommendedOpen

Šo notikumu apkopo Office programmām, kas tiek lietotas Apple platformās. Notikums ieraksta, ja fails tiek atvērts, izmantojot dokumentu galerijas ieteicamo failu sadaļas, un tiek izmantots, lai izprastu un noteiktu prioritātes lietotāju pieredzei, pamatojoties uz informāciju par failu atvēršanas darbību.

Tiek apkopoti šādi lauki:

- **Data_Success** — Būla vērtība, kas norāda, vai operācija bija sekmīga.

#### <a name="office_docsui_fileoperations_docsuifileopenmacrequired"></a>Office_DocsUI_FileOperations_DocsUIFileOpenMacRequired

Šo notikumu apkopo Office programmām, kas darbojas Apple platformās. Notikums ieraksta, kad notiek failu atvēršanas darbība, un tiek izmantots, lai izprastu un noteiktu prioritātes lietotāja pieredzi, pamatojoties uz failu atvēršanas informāciju, piemēram, atrašanās vietas kategorijas "Pakalpojuma tips" un paplašinājuma pirmās četras rakstzīmes.

Tiek apkopoti šādi lauki:

- **Data_Ext** — faila paplašinājums attiecas tikai uz pirmajiem četriem paplašinājuma simboliem vai mazāk.

- **Data_ServiceType** — faila atrašanās vietas abstrakta kategorizēšana, piemēram, "SharePoint", "OneDrive", "Local", "WOPI" utt.

#### <a name="office_docsui_fileoperations_opendocumentmeasurements"></a>Office_DocsUI_FileOperations_OpenDocumentMeasurements

Šis notikums tiek apkopots Office lietojumprogrammām, kas darbojas iOS platformā. Notikuma ieraksti brīdī, kad notiek faila atvēršanas darbība, tiek izmantoti, lai saprastu un noteiktu prioritāti lietotāju pieredzēm, balstoties uz informāciju par faila atvēršanu, it īpaši veiktspējas informāciju. 

Tiek apkopoti tālāk norādītie lauki:

- **Data_AppDuration** — lietojumprogrammā, kas veic faila atvēršanu, pavadītais laiks.

- **Data_BootDuration** — faila atvēršanas palaišanas procesa ilgums.

- **Data_ClickOrigin** — virkne, kas norāda uz saites daļas izcelsmi brīdī, kad lietotājs noklikšķināja uz saites iOS Outlook, lai atvērtu failu Office lietojumprogrammā.

- **Data_ClickTime** — Unix diskretizācijas laiks, kad lietotājs noklikšķināja uz saites iOS Outlook, lai atvērtu failu Office lietojumprogrammā.

- **Data_ClosePreviouslyOpenedMarkers**— virknes vērtība, kas uzskaita ilgumu starp atsevišķu funkciju izsaukumiem formātā ar funkcijas ID un ilgumu.

- **Data_DetachedDuration** — notikuma atvienošanas procesa ilgums. 

- **Data_Doc_AccessMode** — uzskaitījums, kas norāda uz faila piekļuves režīmu, piemēram, tikai lasāms, lasāms-rakstāms.

- **Data_Doc_AsyncOpenKind**— uzskaitījums, kas norāda asinhronās plūsmas veidu, kas tika izmantota faila atvēršanai.

- **Data_Doc_ChunkingType** — uzskaitījums, kas norāda faila dalīšanas algoritma veidu.

- **Data_Doc_EdpState** — uzskaitījums, kas norāda faila uzņēmuma datu aizsardzības statusu.

- **Data_Doc_Ext** — faila paplašinājums.

- **Data_Doc_Fqdn** — faila servera resursdatora nosaukums.

- **Data_Doc_FqdnHash** — GUID, kas unikāli identificē servera resursdatora nosaukumu.

- **Data_Doc_IdentityTelemetryId** — GUID, kas unikāli identificē identitāti, kas tika izmantota, lai atvērtu failu.

- **Data_Doc_InitializationScenario** — uzskaitījums, kas norāda detalizēto faila atvēršanas darbības scenārija veidu.

- **Data_Doc_IOFlags** — uzskaitījums, kas norāda faila atvēršanas darbības ievadizvades karodziņus, piemēram, vai fails ir kešots.

- **Data_Doc_IsCloudCollabEnabled** — vai failam ir iespējota sadarbība mākonī.

- **Data_Doc_IsIncrementalOpen** — vai fails tika atvērts ar inkrementālo atvēršanu.

- **Data_Doc_IsOcsSupported** — vai fails atbalsta Office sadarbības pakalpojumu.

- **Data_Doc_IsOpeningOfflineCopy** — vai fails tiek atvērts no bezsaistes kešatmiņas kopijas.

- **Data_Doc_IsPrefetched** — vai fails tika iepriekš ielādēts pirms atvēršanas darbības.

- **Data_Doc_IsSyncBacked** — vai mākonī esošajam failam ir lokālā versija un, vai tā ir sinhronizēta ar serveri.

- **Data_Doc_Location** — uzskaitījums, kas norāda uz faila atrašanās vietu, piemēram, atrodas lokāli vai mākonī.

- **Data_Doc_ReadOnlyReasons** — uzskaitījums, kas norāda faila tikai lasīšanas iemeslu.

- **Data_Doc_ResourceIdHash** — GUID, kas unikāli identificē faila servera resursa ID.

- **Data_Doc_RtcType** — uzskaitījums, kas norāda faila izmantotā reāllaika kanāla (RTC) veidu.

- **Data_Doc_ServerDocId** — GUID, kas unikāli identificē servera dokumenta ID.

- **Data_Doc_ServerProtocol** — uzskaitījums, kas norāda mākoņa faila servera protokolu.

- **Data_Doc_ServerType** — uzskaitījums, kas norāda mākoņa faila servera veidu.

- **Data_Doc_ServerVersion** — uzskaitījums, kas norāda mākoņa faila servera versiju.

- **Data_Doc_SessionId** — vesels skaitlis, kas pieaug par 1 ar katru faila atvēršanas darbību sesijas laikā.

- **Data_Doc_SharePointServiceContext** — virkne, kas tiek izmantota, lai savstarpēji saistītu klienta un servera žurnālus; parasti tas ir kāds ID veids.

- **Data_Doc_SizeInBytes** — dokumenta lielums baitos.

- **Data_Doc_SpecialChars** — uzskaitījums, kas norāda īpašās rakstzīmes veidu faila URL adresē.

- **Data_Doc_UrlHash** — GUID, kas unikāli identificē faila URL.

- **Data_Doc_UsedWrsDataOnOpen** — norāda, vai fails tika atvērts inkrementāli, izmantojot iepriekš kešotus WRS datus.

- **Data_Doc_WopiServiceId** — virkne, kas norāda, no kura pakalpojuma ir WOPI (tīmekļa lietojumprogrammas atvērtās platformas interfeisa protokols) fails.

- **Data_InclusiveMeasurements** — virknes vērtība, kas uzskaita atsevišķu funkciju pieprasījumā pavadīto laiku formātā ar funkcijas birku un ilgumu, kas iekļauj apakšfunkciju pieprasījumu ilgumu.

- **Data_InitializationReason** — uzskaitījums, kas norāda uz faila atvēršanas veidu, piemēram, no lietotāja interfeisa elementa vai citas lietojumprogrammas izsaukuma rezultātā.

- **Data_Measurements** — virknes vērtība, kas uzskaita atsevišķu funkciju pieprasījumā pavadīto laiku formātā ar funkcijas birku un ilgumu, kas neiekļauj apakšfunkciju pieprasījumu ilgumu.

- **Data_OpenInPlace** — vai fails ir jākopē Office smilškastes konteinerā, pirms lietotājs var to atvērt.

- **Data_OpenStartTime** — Unix diskretizācijas laiks, kad tika sākta faila atvēršana.

- **Data_SilhouetteDuration** — faila atvēršanas renderēšanas ilgums.

- **Data_SourceApplication** — virkne, kas norāda avota lietojumprogrammas komplekta ID, kad faila atvēršanu uzsāk cita lietojumprogramma.

- **Data_StopwatchDuration** — laiks no notikuma sākuma līdz notikuma beigām.

- **Data_TimeSplitMeasurements**— virknes vērtība, kas uzskaita atsevišķu funkciju pieprasījumu ilgumu formātā ar funkcija birku, sākuma laikspiedolu un ilgumu.

#### <a name="office_docsui_fileoperations_openfilewithreason"></a>Office_DocsUI_FileOperations_OpenFileWithReason 

Šo notikumu vāc Office programmām, kas darbojas Apple platformās. Notikums ieraksta, kad notiek failu atvēršana, un tiek izmantots, lai izprastu un noteiktu prioritātes lietotāja pieredzi, pamatojoties uz failu atvēršanas informāciju, piemēram, atrašanās vietas kategorijas "Pakalpojuma tips" un no kurienes lietotājs pieprasīja atvērt failu programmā.

Tiek apkopoti šādi lauki:

- **Data_IsCandidateDropboxFile** — šī ir Būla vērtība, kas tiek reģistrēta, ja, pārbaudot faila ceļu, mūsuprāt, tas var būt no mapes, kas tiek sinhronizēta ar Dropbox.

- **Data_IsSignedIn** — neatkarīgi no tā, vai tiek pierakstīts lietotājs, kad fails ir saglabāts.

- **Data_OpenReason** — atvērtais iemesls ir skaitliska vērtība, kas norāda, no kurienes programmā lietotājs ir atvēris failu.

- **Data_ServiceType** — sākotnējās faila atrašanās vietas abstrakta kategorizēšana, piemēram, "SharePoint", "OneDrive", "Local", "WOPI" utt., un kas nav faila faktiskā atrašanās vieta.

#### <a name="office_docsui_fileoperations_savetourl"></a>Office_DocsUI_FileOperations_SaveToURL

Šo notikumu apkopo Office programmām, kas darbojas Apple platformās. Notikums ieraksta, kad notiek darbība "saglabāt kā", un tiek izmantots, lai izprastu un noteiktu prioritātes lietotāja pieredzi, pamatojoties uz failu darbības informāciju, piemēram, atrašanās vietas kategorijas un paplašinājuma pirmās četras rakstzīmes.  Darbība "Saglabāt kā" tiek veikta katru reizi, kad lietotājs izveido jaunu failu un saglabā to pirmo reizi vai saglabā esošā faila kopiju jaunā atrašanās vietā.

Tiek apkopoti šādi lauki:

- **Data_FileExtension** — pirmās četras rakstzīmes jaunā faila paplašinājumā.

- **Data_IsNewFileCreation** — norāda, vai saglabāšanas darbība ir paredzēta jaunam failam vai esoša faila kopijai.

- **Data_IsSignedIn** — neatkarīgi no tā, vai tiek pierakstīts lietotājs, kad fails ir saglabāts.

- **Data_SaveErrorCode** — skaitliska vērtība, kas ir iestatīta, ja ir kļūda, kas palīdz noteikt kļūdas veidu.

- **Data_SaveErrorDomain** — norāda tā SaveErrorCode domēnu, ko Apple SaveErrorCode domēns definē kā "patvaļīgas virknes, kas tiek izmantotas, lai diferencētu kodu grupas".

- **Data_SaveLocation** — sākotnējās faila atrašanās vietas abstrakta kategorizēšana, piemēram, "SharePoint", "OneDrive", "Local", "WOPI" utt., un kas nav faila faktiskā atrašanās vieta.

- **Data_SaveOperationType** — skaitliska vērtība, ko definē Apple NSSaveOperationType vērtību grupa.

#### <a name="office_docsui_sharingui_cloudupsellshown"></a>Office_DocsUI_SharingUI_CloudUpsellShown 

Šo notikumu apkopo Office programmām, kas tiek lietotas Apple platformās. Šis notikums ieraksta, kad lietotājs dodas caur dokumentu papildu pārdošanai uz mākoņa plūsmu.  Šie dati tiek izmantoti, lai labāk izprastu un noteiktu prioritātes lietotājam, kas saistītas ar dokumentu vienlaicīgu koprediģēšanu.

Tiek apkopoti šādi lauki:

- **Data_FileStyle** — skaitliska vērtība, kas norāda, kādā scenārijā papildu pārdošanas pieredze tika parādīta kā no automātiskās saglabāšanas slēdža vai kopīgošanas pogas.

- **Data_FileType** — pirmās četras rakstzīmes pašreizējā faila paplašinājumā.

- **Data_InDocStage** — Būla izteiksme, kas norāda, vai papildu pārdošanas pieredze tiek parādīta dokumentu galerijā vai dokumenta logā.

- **Data_IsDocumentOpened** — Būla izteiksme, kas norāda, vai ir atvērts pašreizējais dokuments, kurā redzama papildu pārdošanas pieredze.

- **Data_IsDraft** — Būla izteiksme, kas norāda, vai pašreizējais fails kaut kad ir saglabāts.

- **Data_IsSheetModal** — Būla izteiksme, kas norāda, vai papildu pārdošanas pieredze tika prezentēta modāli vai nē.

#### <a name="office_docsui_sharingui_cloudupsellupload"></a>Office_DocsUI_SharingUI_CloudUpsellUpload 

Šo notikumu apkopo Office programmām, kas tiek lietotas Apple platformās. Šis notikums ieraksta, kad lietotājs izvēlas augšupielādēt jaunu vai lokālo failu mākonī un šīs darbības rezultātu.  Šie dati tiek izmantoti, lai labāk izprastu un noteiktu prioritātes lietotājam, kas saistītas ar dokumentu vienlaicīgu koprediģēšanu.

Tiek apkopoti šādi lauki:

- **Data_FileStyle** — skaitliska vērtība, kas norāda, kādā scenārijā papildu pārdošanas pieredze tika parādīta kā no automātiskās saglabāšanas slēdža vai kopīgošanas pogas.

- **Data_FileType** — pirmās četras rakstzīmes pašreizējā faila paplašinājumā.

- **Data_InDocStage** — Būla izteiksme, kas norāda, vai papildu pārdošanas pieredze tiek parādīta dokumentu galerijā vai dokumenta logā.

- **Data_IsDefaultServiceLocation** — Būla vērtība, kas norāda, vai atlasītā atrašanās vieta, kur augšupielādēt dokumentu, ir noklusējuma atrašanās vieta.

- **Data_IsDocumentOpened** — Būla izteiksme, kas norāda, vai ir atvērts pašreizējais dokuments, kurā redzama papildu pārdošanas pieredze.

- **Data_IsDraft** — Būla izteiksme, kas norāda, vai pašreizējais fails kaut kad ir saglabāts.

- **Data_IsSheetModal** — Būla izteiksme, kas norāda, vai papildu pārdošanas pieredze tika prezentēta modāli vai nē.

- **Data_LocationServiceType** — sākotnējās faila atrašanās vietas abstrakta kategorizēšana, piemēram, "SharePoint", "OneDrive", "Local", "WOPI" utt., un kas nav faila faktiskā atrašanās vieta.

- **Data_UploadAction** — cietā kodētā virkne, kas norāda, vai augšupielāde bija pārvietošanas vai kopēšanas darbība.

- **Data_UploadResult** — cieta kodēta virkne, kas norāda mēģinājuma rezultātu, tostarp, bet ne tikai, "Izdevās", "UserCancelledUpload" un "PreAuthFailed".

#### <a name="office_docsui_sharingui_copylinkoperation"></a>Office_DocsUI_SharingUI_CopyLinkOperation

Šo notikumu apkopo Office programmām, kas tiek lietotas Apple platformās. Šī notikums ieraksta, kad lietotājs izvēlas kopīgot dokumentu, ģenerējot saiti uz mākoņa dokumentu, un tiek izmantots, lai labāk izprastu un noteiktu prioritātes lietotāja pieredzi, pamatojoties uz dokumentu koplietošanu.

Tiek apkopoti šādi lauki:

- **Data_ ServiceType** — abstrakta faila atrašanās vietas kategorizēšana, piemēram, "SharePoint", "OneDrive", "Local", "WOPI" utt., nevis faktiskā faila atrašanās vieta.

- **Data_LinkType** — cietā kodētā virkne, kas apraksta uzaicināšanas darbības veidu, piemēram, "ViewOnly" un "ViewAndEdit".

- **Data_ShareScenario** — cieti kodēts virknes apraksts, kur programmas lietotāja interfeisā fails tiek koplietots, ieskaitot, bet ne tikai "FileMenu", "OpenTabShareActionMenu", "RecentTabShareActionMenu".

#### <a name="office_docsui_sharingui_docsuionedriveshare"></a>Office_DocsUI_SharingUI_DocsUIOneDriveShare 

Šo notikumu apkopo Office programmām, kas tiek lietotas Apple platformās. Šis notikums ieraksta, ja lietotājs izvēlas koplietot mākoņa dokumentu, izmantojot OneDrive koplietošanas pieredzi, un tas tiek izmantots, lai labāk izprastu un noteiktu prioritātes lietotāja pieredzi, pamatojoties uz dokumentu koplietošanu.

Tiek apkopoti šādi lauki:

- **Data_ODSPShareWebviewShareError** — Ja koplietošanas pieredze atklāj kļūdu, tā ir skaitliska vērtība, kas palīdz noteikt kļūmes iemeslu.

- **Data_ODSPShareWebviewShareGrantAccessResult** — Būla vērtība, kas norāda, ka vieglā koplietošanas darbība ir sekmīgi pabeigta.

- **Data_ODSPShareWebviewShareSuccessType** — ja kopīgošanas darbība ir veiksmīgi pabeigta, šī ir skaitliska vērtība, kas tiek lietota, lai noteiktu, kāda veida koplietošanas darbība tika pabeigta.

- **Data_WebViewInfoResult** — ja lietotāja interfeiss nav ielādēts, šī ir skaitliska vērtība, kas palīdz identificēt kļūmes iemeslu. 

- **Data_WebViewLoadTimeInMs** — skaitliska vērtība, kas ieraksta, cik daudz laika ir nepieciešams, lai tīmekļa lietotāja interfeiss tiktu ielādēts.

#### <a name="office_docsui_sharingui_invitepeople"></a>Office_DocsUI_SharingUI_InvitePeople 

Šo notikumu apkopo Office programmām, kas tiek lietotas Apple platformās. Šis notikums ieraksta, ja lietotājs izvēlas uzaicināt lietotājus uz mākoņa dokumentu un tiek izmantots, lai labāk izprastu un noteiktu prioritātes lietotāja pieredzi, pamatojoties uz dokumentu koplietošanu.

Tiek apkopoti šādi lauki:

- **Data_ ServiceType** — abstrakta faila atrašanās vietas kategorizēšana, piemēram, "SharePoint", "OneDrive", "Local", "WOPI" utt., nevis faktiskā faila atrašanās vieta.

- **Data_InviteeCount** — kopējais kontaktpersonu skaits, kas uzaicināti uz dokumentu vienā uzaicinājuma darbībā.

- **Data_LinkType** — cietā kodētā virkne, kas apraksta uzaicināšanas darbības veidu, piemēram, "ViewOnly" un "ViewAndEdit".

- **Data_MessageLength** — uzaicinājuma ziņojumā nosūtīto rakstzīmju kopējais skaitlisks skaits.

- **Data_ShareScenario** — cieti kodēts virknes apraksts, kur programmas lietotāja interfeisā fails tiek koplietots, ieskaitot, bet ne tikai "FileMenu", "OpenTabShareActionMenu", "RecentTabShareActionMenu".

#### <a name="office_docsui_sharingui_sendacopyoperation"></a>Office_DocsUI_SharingUI_SendACopyOperation

Šo notikumu apkopo Office programmām, kas tiek lietotas Apple platformās. Notikums ieraksta, kad lietotājs izvēlas sūtīt dokumenta kopiju, un tiek izmantots, lai labāk izprastu un noteiktu prioritātes lietotāja pieredzi, pamatojoties uz dokumentu koplietošanu.

Tiek apkopoti šādi lauki:

- **Data_IsHomeTabEnabled** — Būla vērtība, kas norāda, ja cilne Sākums pašlaik ir pieejama lietotājam.

- **Data_IsRecommendedEnabled** — Būla vērtība, kas norāda, ja pieredze "Ieteicams" pašlaik ir pieejama lietotājam.

- **Data_OperationType** — skaitliska vērtība, kas norāda, kāda veida kopijas nosūtīšanas darbība tiek veikta, piemēram, nosūtot kopiju e-pastā vai nosūtot kopiju, izmantojot Apple kopīgošanas vadību.

- **Data_ ServiceType** — abstrakta faila atrašanās vietas kategorizēšana, piemēram, "SharePoint", "OneDrive", "Local", "WOPI" utt., nevis faktiskā faila atrašanās vieta.

- **Data_ShareFileType** — cietais kodētais virknes apraksts par to, kāda tipa objektu koplieto, tostarp, bet ne tikai, "Dokuments", "PDF", "Attēls".

- **Data_ShareScenario** — cieti kodēts virknes apraksts, kur programmas lietotāja interfeisā fails tiek koplietots, ieskaitot, bet ne tikai "FileMenu", "OpenTabShareActionMenu", "RecentTabShareActionMenu".

- **Data_SharingService** — Būla vērtība, kas norāda, vai fails tika izveidots, kad lietotājs meklēja veidni.

#### <a name="office_docsui_sharingui_upsellshare"></a>Office_DocsUI_SharingUI_UpsellShare 

Šo notikumu apkopo Office programmām, kas tiek lietotas Apple platformās. Šis notikums ieraksta, kad lietotājs dodas caur dokumentu papildu pārdošanai uz mākoņa plūsmu, mēģinot kopīgot dokumentu.  Šie dati tiek izmantoti, lai labāk izprastu un noteiktu prioritātes lietotāja pieredzi, kas saistīta ar dokumentu pārvietošanu uz mākoņa vietām.

Tiek apkopoti šādi lauki:

- **Data_FileOperationResult** — skaitliska vērtība, kas norāda, vai operācija bija sekmīga.

- **Data_HostedFromDocStage** — Būla izteiksme, kas norāda, vai lietotājs izmanto papildu pārdošanu, lai izveidotu mākoņa plūsmu no DocStage pieredzes vai atvērta dokumenta.

- **Data_isLocalCopyOn** — Būla izteiksme, kas norāda, vai, ja izmantojat, izvēlējās saglabāt lokālu dokumentu, kas tiek augšupielādēts mākoņa atrašanās vietā, vai pārvietojat esošo dokumentu uz mākoņa atrašanās vietu.

- **Data_NewFileType** — faila jaunas atrašanās vietas abstrakta kategorizēšana, piemēram, "SharePoint", "OneDrive", "Local", "WOPI" utt., un kas nav faila faktiskā atrašanās vieta.

- **Data_OriginalFileType** — abstrakta faila atrašanās vietas kategorizēšana, piemēram, "SharePoint", "OneDrive", "Local", "WOPI" utt., nevis faktiskā faila atrašanās vieta.

- **Data_UploadButtonPressed** — Būla izteiksme, kas norāda, vai lietotājs ir izvēlējies augšupielādēt pašreizējo dokumentu mākoņa atrašanās vietā.

- **Data_UploadError** — skaitliska vērtība, kas norāda, kāda veida kļūda radās, ja augšupielādes darbība neizdodas.

- **Data_UpsellAppearsFromDelegate** — Būla vērtība, kas norāda, vai skats ir redzams koplietošanas izvēlnē.

#### <a name="officeextensibilitycatalogexchangeprocessentitlement"></a>Office.Extensibility.Catalog.ExchangeProcessEntitlement

Dati par Office 365 nomnieka administratora piešķirtas pievienojumprogrammas atsevišķas pilnvaras apstrādi.

Izmanto tādu diagrammu izveidē (pieprasa grupas pārvaldība), kurā tiek analizēti klientu panākumi un problēmas.

Tiek apkopoti tālāk norādītie lauki.

  - **AppVersion** — pievienojumprogrammas viesošanas programmas versija.

  - **SolutionId** — GUID, kas apzīmē unikālu pievienojumprogrammu

  - **TelemetryId —** GUID, kas apzīmē unikālu lietotāju

#### <a name="officeextensibilitycatalogexchangeprocessmanifest"></a>Office.Extensibility.Catalog.ExchangeProcessManifest

Dati par Office 365 nomnieka administratoram piešķirtās individuālās pievienojumprogrammas manifesta apstrādi. Tiek izmantots klientu problēmu analīzē un klientu panākumu diagrammu izveidē.
 
Tiek apkopoti tālāk norādītie lauki.

- **AppVersion** — lietojumprogrammas versija.

- **IsAllReturnedManifestsParsed** — būla, kas norāda, ka mēs veicām visu atgriezto manifestu parsēšanu.

- **IsAppCommand** — būla norāda uz to, vai šī lietojumprogramma ir komandas lietojumprogramma. 

- **ReturnedManifestsParsed** — parsēto manifestu skaits.

- **SolutionId** — risinājuma ID.

- **TelemetryId** — identitātes, ar kuru veikta pierakstīšanās, telemetrijas ID.

#### <a name="officeextensibilityodpappcommandsribbonclick"></a>Office.Extensibility.ODPAppCommandsRibbonClick

Apkopo informāciju par veiksmīgu vai neveiksmīgu noklikšķināšanu uz pielāgotās pievienojumprogrammas. Izmanto, lai noteiktu problēmas lietotāju mijiedarbībā ar pievienojumprogrammu vadības elementiem.
 
Tiek apkopoti tālāk norādītie lauki.

- **CommandActionType** — pievienojumprogrammas komandas veids.

- **CommandLabel**— noklikšķinātās komandas etiķete.

- **SolutionId** — risinājuma ID.

#### <a name="officefeedeventsinitializing"></a>Office.Feed.Events.Initializing

Šis notikums tiek apkopots brīdī, kad sākas plūsmas inicializācija. Šis notikums tiek izmantots, lai norādītu uz to, ka ir sākusies plūsma, un veiktu uzticamības problēmu diagnostiku plūsmas palaišanas laikā.

- **AppInfo.Language** — lietojumprogrammas valoda IETF valodas atzīmes formātā.

- **AppInfo.Name** — izmantojamā komponenta nosaukums (Office plūsma).

- **AppInfo.Version** — lietojumprogrammas versija.

- **clientCorrelationId** — lietojumprogrammas sesijas globāli unikālais identifikators.

- **clientType** — lietojumprogramma, kurā darbojas komponents.

- **DeviceInfo.Make** — ierīces ražotāja vai ierīces OEM nosaukums.

- **DeviceInfo.NetworkProvider** — tīkla vai mobilo sakaru operators, piemēram, "AT&T".

- **DeviceInfo.NetworkType** — izmantojamās ierīces pieslēguma tīklam, piemēram, "ar vadu", "WiFi" vai "WWAN" (datu/mobilo datu tīkls).

- **DeviceInfo.OsName** — ierīces operētājsistēmas nosaukums.

- **DeviceInfo_SDKUid** — unikāli identificē ierīci no telemetrijas SDK perspektīvas

- **eventId** — notikuma nosaukuma identifikators. 

- **EventInfo.SdkVersion** — klienta notikuma ģenerēšanā izmantotās telemetrijas SDK versija.

- **eventpriority** — notikuma sūtīšanas prioritātes uzskaites vērtība.

- **feature** — izmanto, lai grupētu dažādus viena līdzekļa notikumus.

- **hostAppRing** — lietotāju, kuriem tika izplatīta lietojumprogramma, skaits.

- **properties** — satur papildu katram notikumam apkopotos metadatu rekvizītus.
        
    - **ClientTimeStamp** — notikuma reģistrēšanas klientā laikspiedols.

- **publicEventName** — publiski pieejamais notikuma nosaukums.  

- **reģions** — plūsmas pakalpojuma, kuram ir pieslēdzies lietotājs, ģeogrāfiskais reģions. 

- **tenantAadObjectId** — lietotāja uzņēmuma nomnieka globālais unikālais identifikators.

- **type** — reģistrētā notikuma veids, piemēram, izsekošana, kļūda, notikums, QoS.

- **userAadObjectId** — globāli unikāls lietotāja identifikators Microsoft uzņēmuma kontam.

- **UserInfo.Id** — globāli unikāls lietotāja identifikators Microsoft uzņēmuma kontam.

- **UserInfo.IdType** — norāda lietotāja ID veidu. 

- **UserInfo.Language** — lietotāja valoda IETF valodas atzīmes formātā.

- **UserInfo.MsaId** — globāli unikāls lietotāja identifikators Microsoft lietotāja kontam.

- **UserInfo.OMSTenantId** — nomnieks, kuram ir piesaistīts lietotāja abonements. Ļauj mums klasificēt problēmas un noteikt, vai problēma ir plaši izplatīta vai izolēta konkrēta nomnieka lietotāju kopā.

- **UserInfo.TimeZone** — lietotāja laika josla attiecībā pret UTC.

- **userPuid** — globāli unikāls lietotāja identifikators Microsoft lietotāja kontam.

- **version** — plūsmas klienta versija.

#### <a name="officefeedeventsofficefeeddidappear"></a>Office.Feed.Events.OfficeFeedDidAppear

Šis notikums tiek apkopots, kad plūsma tiek parādīta lietotājam. Šis notikums tiek izmantots, lai verificētu, vai plūsma pabeidza inicializācijas darbību, un diagnosticētu uzticamības problēmas plūsmas palaišanas laikā.

- **AppInfo.Language** — lietojumprogrammas valoda IETF valodas atzīmes formātā.

- **AppInfo.Name** — izmantojamā komponenta nosaukums (Office plūsma).

- **AppInfo.Version** — lietojumprogrammas versija.

- **bridgeWaitingTime** — metrika, lai diagnosticētu plūsmas renderēšanas veiktspēju.

- **clientCorrelationId** — lietojumprogrammas sesijas globāli unikālais identifikators.

- **ClientTimeStamp** — notikuma reģistrēšanas klientā laikspiedols.

- **clientType** — lietojumprogramma, kurā darbojas komponents.

- **DeviceInfo.Make** — ierīces ražotāja vai ierīces OEM nosaukums.

- **DeviceInfo.NetworkProvider** — tīkla vai mobilo sakaru operators, piemēram, "AT&T".

- **DeviceInfo.NetworkType** — izmantojamās ierīces pieslēguma tīklam, piemēram, "ar vadu", "WiFi" vai "WWAN" (datu/mobilo datu tīkls).

- **DeviceInfo.OsName** — ierīces operētājsistēmas nosaukums.

- **DeviceInfo_SDKUid** — unikāli identificē ierīci no telemetrijas SDK perspektīvas

- **eventId** — notikuma nosaukuma identifikators.

- **EventInfo.SdkVersion** — klienta notikuma ģenerēšanā izmantotās telemetrijas SDK versija.

- **eventpriority** — notikuma sūtīšanas prioritātes uzskaites vērtība.

- **feature** — izmanto, lai grupētu dažādus viena līdzekļa notikumus.

- **hostAppRing** — lietotāju, kuriem tika izplatīta lietojumprogramma, skaits.

- **properties** — satur papildu katram notikumam apkopotos metadatu rekvizītus. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*
  - **ClientTimeStamp** — notikuma reģistrēšanas klientā laikspiedols.

- **publicEventName** — publiski pieejamais notikuma nosaukums.  

- **reģions** — plūsmas pakalpojuma, kuram ir pieslēdzies lietotājs, ģeogrāfiskais reģions. 

- **renderTime** — metrika, lai diagnosticētu plūsmas renderēšanas veiktspēju.

- **tenantAadObjectId** — lietotāja uzņēmuma nomnieka globālais unikālais identifikators.

- **type** — reģistrētā notikuma veids, piemēram, izsekošana, kļūda, notikums, QoS.

- **userAadObjectId** — globāli unikāls lietotāja identifikators Microsoft uzņēmuma kontam.

- **UserInfo.Id** — globāli unikāls lietotāja identifikators Microsoft uzņēmuma kontam.

- **UserInfo.IdType** — norāda lietotāja ID veidu. 

- **UserInfo.Language** — lietotāja valoda IETF valodas atzīmes formātā.

- **UserInfo.MsaId** — globāli unikāls lietotāja identifikators Microsoft lietotāja kontam.

- **UserInfo.OMSTenantId** — nomnieks, kuram ir piesaistīts lietotāja abonements. Ļauj mums klasificēt problēmas un noteikt, vai problēma ir plaši izplatīta vai izolēta konkrēta nomnieka lietotāju kopā.

- **UserInfo.TimeZone** — lietotāja laika josla attiecībā pret UTC.

- **userPuid** — globāli unikāls lietotāja identifikators Microsoft lietotāja kontam.

- **version** — plūsmas klienta versija.


#### <a name="officefileiocsiccachedfilecsiloadfilebasic"></a>Office.FileIO.CSI.CCachedFileCsiLoadFileBasic

Ļauj uzzināt, vai fails ir veiksmīgi atvērts no FIO līmeņa. Izmanto līdzekļu darbspējas veicināšanai un pārraudzībai.

Tiek apkopoti tālāk norādītie lauki.

  - **Activity.Group —** tags, kas ļauj grupēt pārraudzības notikumu kopu, lai pārvaldītu kopējos panākumus

  - **Activity.IsHVA —** karodziņš, kas norāda, ka šis notikums ir svarīgs lietotāja panākumiem

  - **Data.AsyncOpen —** karodziņš, kas norāda atvērto saturu, kas ir pieejams pēc galvenā satura atvēršanas

  - **Data.CacheFileId —** izveido savienojumu ar Office dokumentu kešatmiņas telemetriju, lai iespējotu analīzi saistībā ar kešatmiņas problēmu ietekmi uz lietotāju pieredzi
 
  - **Dati.CFREnabled** — norāda, ka sesijai ir iespējota CacheFileRuntime.

  - **Dati.CFRFailure** — norāda, ka CacheFileRuntime radās kļūda.
  
  - **Data.CoauthStatus —** reģistrē atvērta dokumenta sadarbības statusu

  - **Data.CountOfMultiRoundTripsDownload —** to servera apmeklējumu skaits, kas tiek izmantoti veiktspējas un tīkla problēmu novēršanai

  - **Data.CountOfMultiRoundTripsUpload —** to servera apmeklējumu skaits, kas tiek izmantoti veiktspējas un tīkla problēmu novēršanai

  - **Data.DialogId —** tiek iestatīts, ja atvēršanas laikā tiek parādīts lietotāja interfeisa dialoglodziņš, norādot, ka lietotājs saņēma brīdinājuma ziņojumu

  - **Data.DidFallbackToDAV —** tiek iestatīts, ja dokuments tika atvērts, izmantojot vecāku failu pārsūtīšanas protokolu

  - **Data.Doc.AccessMode —** dokuments ir tikai lasāms/rediģējams

  - **Data.Doc.AssistedReadingReasons —** tiek iestatīts, ja dokumentā ir iespējota elektronisko datu aizsardzība

  - **Data.Doc.AsyncOpenKind —** norāda, vai tika atvērta mākoņa dokumenta kešotā versijā un kura asinhronā atsvaidzināšanas loģika tika izmantota.

  - **Data.Doc.ChunkingType —** vienības, kas tiek izmantotas inkrementālā dokumenta atvēršanā

  - **Data.Doc.EdpState —** dokumenta elektronisko datu aizsardzības iestatījums

  - **Data.Doc.Ext —** dokumentu paplašinājums (docx/xlsb/pptx utt.)

  - **Data.Doc.Extension —** novecojis

  - **Data.Doc.FileFormat —** faila formāta protokola versija

  - **Data.Doc.Fqdn —** OneDrive vai SharePoint Online domēna nosaukums

  - **Data.Doc.FqdnHash —** klientu identificējama domēna nosaukuma vienvirziena jaukšana

  - **Data.Doc.IdentityTelemetryId —** tādas lietotāja identitātes vienvirziena jaukšana, kas tiek izmantota atvēršanā

  - **Data.Doc.IdentityUniqueId —** novecojis

  - **Data.Doc.InitializationScenario —** dokumenta atvēršanas ieraksti

  - **Data.Doc.IOFlags —** atskaites par kešotajiem karodziņiem, kas tiek izmantoti pieprasījuma opciju iestatīšanai

  - **Data.Doc.IrmRights —** dokumentam/lietotājam piemērotās elektronisko datu politikas atļautās darbības

  - **Data.Doc.IsCloudCollabEnabled —** karodziņš, kas norāda, vai pakalpojums atbalsta sadarbību mākonī

  - **Data.Doc.IsIncrementalOpen —** karodziņš, kas norāda, ka dokuments ir atvērts inkrementāli

  - **Data.Doc.IsOcsSupported —** karodziņš, kas norāda, ka dokuments tiek atbalstīts sadarbības pakalpojumā

  - **Data.Doc.IsOpeningOfflineCopy —** karodziņš, kas norāda, ka tika atvērta dokumenta bezsaistes kopija

  - **Data.Doc.IsSyncBacked —** karodziņš, kas norāda, ka datorā pastāv automātiski sinhronizēta dokumenta kopija

  - **Data.Doc.Location —** norāda pakalpojumu, kurā atrodas dokuments (OneDrive, File Server, SharePoint utt.)

  - **Data.Doc.LocationDetails —** norāda, kurā zināmajā mapē atrodas lokāli saglabātais dokuments

  - **Data.Doc.NumberCoAuthors —** citu lietotāju skaits koprediģēšanas sesijā

  - **Data.Doc.PasswordFlags —** norāda lasīšanas/rakstīšanas paroles karodziņu kopu

  - **Data.Doc.ReadOnlyReasons —** iemesli, kāpēc dokuments ir atvērts tikai lasāmajā režīmā

  - **Data.Doc.ResourceIdHash —** anonimizēts dokumenta identifikators, ko izmanto problēmu noteikšanā

  - **Data.Doc.ServerDocId —** nemainīgs anonimizēts dokumenta identifikators, ko izmanto problēmu noteikšanā

  - **Data.Doc.ServerProtocol —** tā protokola versija, ko izmanto, lai sazinātos ar pakalpojumu

  - **Data.Doc.ServerType —** tā servera tips, kas nodrošina pakalpojumu (OneDrive, SharePoint, WOPI utt.)

  - **Data.Doc.ServerVersion —** tā servera versija, kas nodrošina pakalpojumu

  - **Data.Doc.SessionId —** identificē konkrētu dokumenta rediģēšanas sesiju pilnā sesijā

  - **Data.Doc.SharePointServiceContext —** diagnostikas informācija no SharePoint Online pieprasījumiem

  - **Data.Doc.SizeInBytes —** dokumenta lieluma rādītājs

  - **Data.Doc.SpecialChars —** speciālo rakstzīmju rādītājs dokumenta vietrādī URL vai ceļā

  - **Data.Doc.StorageProviderId —** novecojis

  - **Data.Doc.StreamAvailability —** norāda, vai ir pieejama/atspējota dokumenta plūsma

  - **Data.Doc.SyncBackedType —** norāda dokumenta veidu (lokālais vai servera)

  - **Data.Doc.UrlHash —** vienvirziena jaukšana vienkāršota dokumenta identifikatora izveidei

  - **Data.Doc.UsedWrsDataOnOpen —** diagnostikas indikators inkrementālai dokumentu atvēršanai

  - **Data.Doc.WopiServiceId —** satur unikālu WOPI pakalpojumu sniedzēja identifikatoru

  - **Data.DocumentLoadEndpoint —** novecojis/redundants (Data.Doc.Location un Data.Doc.IsSyncbacked) dublikāts

  - **Data.DocumentSizeInBytes —** novecojis/redundants, ko aizvieto Data.Doc. SizeInBytes

  - **Data.DocumentSizeOnDisk —** novecojis

  - **Data.DoesBaseHaveContentOnOpen —** izmaiņu izsekošanas diagnostika, lai pārliecinātos, vai mums ir koplietojamā faila jaunākā versija

  - **Data.DoesWorkingBranchHaveExcludedDataOnOpen —** izmaiņu izsekošanas diagnostika, lai pārliecinātos, vai mums ir koplietojamā faila jaunākā versija

  - **Data.DownloadFragmentSize —** apakšpieprasījumā nosūtīto datu lielums tīkla problēmu diagnosticēšanai

  - **Data.DsmcStartedTooEarly —** norāda kļūdu sadarbības sesijas sākumā

  - **Data.EditorsCount —** citu to līdzautoru skaits, kas rediģē dokumentu

  - **Data.ExcludedDataThresholdInBytes —** faila lielums, kas ir nepieciešams, lai izmantotu asinhrono atvēršanu

  - **Data.FileIOResult.Code —** pēdējā atvērtā atgriešanas koda kešatmiņa no protokola slāņa

  - **Data.FileIOResult.Success —** pēdējā atvērtā veiksmīguma indikatora kešatmiņa no protokola slāņa

  - **Data.FileIOResult.Tag —** pēdējā atvērtā kļūdas taga kešatmiņa no protokola slāņa

  - **Data.FileIOResult.Type —** pēdējā atvērtā kļūdas tipa kešatmiņa no protokola slāņa

  - **Data.FqdnHash —** novecojis, to aizvieto Data\_Doc\_FqdnHash

  - **Data.FullIError —** visu atvērto kļūdu kodu kešatmiņa no protokola slāņa

  - **Data.FullyQualifiedDomainName —** novecojis, to aizvieto Data\_Doc\_Fqdn

  - **Data.Input.FileOpenState —** statuss, ko pieprasa programma (lasīšana/lasīšana un rakstīšana utt.)

  - **Data.Input.OpenAsync —** asinhronā atvēršana, ko pieprasa programma

  - **Data.Input.OpenOfflineCopy —** programmas pieprasīta atvēršana no bezsaistes kopijas

  - **Data.IOFlags —** novecojis

  - **Data.IsBaseBranchEmptyOnOpen —** izmaiņu izsekošanas diagnostika, lai pārliecinātos, vai mums ir koplietojamā faila jaunākā versija

  - **Data.IsCachedHistoricalVersion —** kešatmiņā ir vecāka dokumenta versija

  - **Data.IsDocEnterpriseProtected —** dokuments ir šifrēts (elektronisko dokumentu aizsardzība/EDP)

  - **Data.IsDocInODC —** dokuments kādreiz ir bijis atvērts un jau atrodas kešatmiņā

  - **Data.IsMapUnMapCase —** kešotā faila statusa daļa

  - **Data.IsMapUnMapCase.End —** kešotā faila statusa daļa

  - **Data.IsOfficeHydrationInProgress —** Windows atjauno dokumentu no bezsaistes krātuves

  - **Data.isOfficeHydrationRequired —** dokuments pašlaik atrodas bezsaistes krātuvē

  - **Data.isOpenFromCollab —** jaunāka dokumenta kopija tika izgūta no koplietojama sadarbības pakalpojuma

  - **Data.isPendingNameExist —** notiek dokumenta pārdēvēšana

  - **Data.IsStubFile —** dokuments vēl nav saglabāts mākoņpakalpojumā

  - **Data.IsSyncBackedStateDifferentThanOnLastOpen —** dokumenta statuss ir mainīts, izmaiņas, iespējams, ir ieviestas, kamēr dokuments bija aizvērts

  - **Data.isTaskCanceledAfterOpenComplete —** novecojis

  - **Data.sWorkingBranchAvailableOnOpen —** izmaiņu izsekošanas diagnostika, lai pārliecinātos, vai mums ir koplietojamā faila jaunākā versija

  - **Data.LicenseStatus** — diagnostikas produkta licences statuss, kas tiek lietots, lai validētu, vai lietotāja licences tipam ir iespējoti atbilstošie produktu līdzekļi 

  - **Data.LicenseType —** norāda licences statusu (bezmaksas/maksas/izmēģinājumversija utt.)

  - **Data.Location —** norāda multivides tipu/atrašanās vietu (USB, mākonis utt.)

  - **Data.LockRequestDocMode —** norāda, vai dokuments ir pieejams citiem lietotājiem

  - **Data.MyDeferredValue —** novecojis

  - **Data.Network.BytesReceived —** novecojis

  - **Data.Network.BytesSent —** novecojis

  - **Data.Network.ConnectionsCreated —** novecojis

  - **Data.Network.ConnectionsEnded —** novecojis

  - **Data.OcsDisableReasons —** iemesls, kāpēc dokumentam nebija pieejams koplietojams sadarbības pakalpojums

  - **Data.OcsHostOnOpen —** karodziņš, kas norāda, ka atvēršanas laikā vadīkla pārslēgsies uz koplietojamo sadarbības pakalpojumu

  - **Data.OpeningOfflineCopy —** karodziņš, kas norāda, ka tiks atvēra lokālā dokumenta kopija

  - **Data.Partition —** novecojis

  - **Data.RequestTime —** novecojis

  - **Data.ResourceIdHash —** novecojis

  - **Data.ResumedIncrementalOpen —** novecojis

  - **Data.RTCEnabled —** sākts ātrais izmaiņu izplatīšanas protokols

  - **Data.SaveOnOpen —** atverot lokālo dokumentu, nesaglabātās izmaiņas tika saglabātas pakalpojumā

  - **Data.ServerProtocol —** novecojis, to aizvietoja Data\_Doc\_ServerProtocol

  - **Data.ServerType —** novecojis, to aizvietoja Data\_Doc\_ServerType

  - **Data.ServerVersion —** novecojis, to aizvietoja Data\_Doc\_ServerVersion

  - **Data.ServiceId —** novecojis, to aizvietoja Data\_Doc\_WopiServiceId

  - **Data.SessionId —** novecojis

  - **Data.ShouldSwitchToServerOnly —** nevar izmantot dokumenta lokālo kopiju, tā vietā jāizmanto servera versija

  - **Data.SpecialChars —** novecojis

  - **Data.StopwatchDuration —** novecojis

  - **Data.SyncBackedFileTelemetrySessionId —** novecojis

  - **Data.SyncElapsedTime —** novecojis

  - **Data.SyncRequestId —** novecojis

  - **Data.TestProperty —** novecojis

  - **Data.TransitionToHostOnOpen —** karodziņš, kas norāda, ka sesija izveidos savienojumu ar pakalpojumu, kas vieso dokumentu

  - **Data.TransitionToHostOnOpenResult —** pāreja uz viesošanas pakalpojumu: statuss

  - **Data.UseCachedNetworkConnection —** karodziņš, kas norāda, vai savienojums ir izmantots atkārtoti vai izveidots no jauna

  - **Data.UseClientIdAsSchemaLockId —** karodziņš, kas kontrolē, kā dokuments ir bloķēts pakalpojumā

  - **Dati. VersionType** — norāda, kura versijas tipa ir pašreizējā atvērtā darbība.

  - **Data.WopiServiceId —** novecojis, to aizvietoja Data\_Doc\_WopiServiceId

#### <a name="officefileiocsiccachedfilecsisavefilebasic"></a>Office.FileIO.CSI.CCachedFileCsiSaveFileBasic

Ļauj uzzināt, vai fails ir veiksmīgi saglabāts no FIO līmeņa. Izmanto līdzekļu darbspējas veicināšanai un pārraudzībai.

Tiek apkopoti tālāk norādītie lauki.

  - **Activity.Group —** tags, kas ļauj grupēt pārraudzības notikumu kopu, lai pārvaldītu kopējos panākumus

  - **Activity.IsHVA —** karodziņš, kas norāda, ka šis notikums ir svarīgs lietotāja panākumiem

  - **Data.AsyncOpen —** karodziņš, kas norāda, ka dokuments tika atvērts ar saturu, kas ir pieejams pēc galvenā satura atvēršanas

  - **Data.BaseDownloadTriggered —** izmaiņu izsekošanas diagnostika, kas norāda, ka tika pieprasīta dokumenta pamata versija

  - **Data.BlockAutoUploadReasons —** iemeslu kodi bloķētajam augšupielādes statusam (piemēram, ir izslēgta automātiskā saglabāšana, dokuments ir pārejas režīmā)

  - **Data.BlockUploadDueToFailedSaveAsOverExisting —** augšupielāde ir bloķēta, jo mēģinot vēlreiz tā tiktu pārtraukta

  - **Data.CacheFileId —** izveido savienojumu ar Office dokumentu kešatmiņas telemetriju, lai iespējotu analīzi saistībā ar kešatmiņas problēmu ietekmi uz lietotāju pieredzi

  - **Data.ChartType —** novecojis

  - **Data.CoauthStatus —** reģistrē saglabāta dokumenta sadarbības statusu

  - **Data.CoauthUpdatesContext —** reģistrē kontekstu (sapludināšana/inkrementāla atvēršana)

  - **Data.CountOfMultiRoundTripsDownload —** to servera apmeklējumu skaits, kas tiek izmantoti veiktspējas un tīkla problēmu novēršanai

  - **Data.CountOfMultiRoundTripsUpload —** to servera apmeklējumu skaits, kas tiek izmantoti veiktspējas un tīkla problēmu novēršanai
  
  - **Dati.CFREnabled** — norāda, ka sesijai ir iespējota CacheFileRuntime.

  - **Dati.CFRFailure** — norāda, ka CacheFileRuntime radās kļūda.

  - **Data.DialogChoice —** ierakstu izvēle kļūdu dialoglodziņos

  - **Data.DialogId —** reģistrē jebkuru saglabāšanas laikā parādīto kļūdu dialoglodziņu identifikatoru

  - **Data.Dmc.IsOcsSupported —** novecojis

  - **Data.Doc.AccessMode —** dokuments ir tikai lasāms

  - **Data.Doc.AssistedReadingReasons —** tiek iestatīts, ja dokumentā ir iespējota elektronisko datu aizsardzība

  - **Data.Doc.AsyncOpenKind —** norāda, vai tika atvērta mākoņa dokumenta kešotā versijā un kura asinhronā atsvaidzināšanas loģika tika izmantota.

  - **Data.Doc.ChunkingType —** vienības, kas tiek izmantotas inkrementālā dokumenta atvēršanā

  - **Data.Doc.EdpState —** dokumenta elektronisko datu aizsardzības iestatījums

  - **Data.Doc.Ext —** dokumentu paplašinājums (docx/xlsm/pptx utt.)

  - **Data.Doc.Extension —** novecojis

  - **Data.Doc.FileFormat —** faila formāta protokola versija

  - **Data.Doc.Fqdn —** OneDrive vai SharePoint Online domēna nosaukums

  - **Data.Doc.FqdnHash —** klientu identificējama domēna nosaukuma vienvirziena jaukšana

  - **Data.Doc.FqdnHasi —** novecojis

  - **Data.Doc.IdentityTelemetryId —** tādas lietotāja identitātes vienvirziena jaukšana, kas tiek izmantota saglabāšanā

  - **Data.Doc.IdentityUniqueId —** novecojis

  - **Data.Doc.IKFlags —** novecojis

  - **Data.Doc.InitializationScenario —** dokumenta atvēršanas ieraksti

  - **Data.Doc.IOFlags —** atskaites par kešotajiem karodziņiem, kas tiek izmantoti pieprasījuma opciju iestatīšanai

  - **Data.Doc.IrmRights —** dokumentam/lietotājam piemērotās elektronisko datu politikas atļautās darbības

  - **Data.Doc.IsCloudCollabEnabled —** karodziņš, kas norāda, vai lietojumprogramma atbalsta sadarbību mākonī

  - **Data.Doc.IsIncrementalOpen —** karodziņš, kas norāda, ka dokuments ir atvērts inkrementāli

  - **Data.Doc.IsOcsSupported —** karodziņš, kas norāda, vai dokuments atbalsta sadarbību mākonī

  - **Data.Doc.IsOpeningOfflineCopy —** karodziņš, kas norāda, ka tika atvērta dokumenta bezsaistes kopija

  - **Data.Doc.IsSyncBacked —** karodziņš, kas norāda, ka datorā pastāv automātiski sinhronizēta dokumenta kopija

  - **Data.Doc.Location —** norāda pakalpojumu, kurā atrodas dokuments (OneDrive, File Server, SharePoint utt.)

  - **Data.Doc.LocationDetails —** norāda, kurā zināmajā mapē atrodas lokāli saglabātais dokuments

  - **Data.Doc.NumberCoAuthors —** citu lietotāju skaits koprediģēšanas sesijā

  - **Data.Doc.PasswordFlags —** norāda lasīšanas/rakstīšanas paroles karodziņu kopu

  - **Data.Doc.ReadOnlyReasons —** iemesli, kāpēc dokuments ir atvērts tikai lasāmajā režīmā

  - **Data.Doc.ResourceIdHash —** anonimizēts dokumenta identifikators, ko izmanto problēmu noteikšanā

  - **Data.Doc.ServerDocId —** nemainīgs anonimizēts dokumenta identifikators, ko izmanto problēmu noteikšanā

  - **Data.Doc.ServerProtocol —** tā protokola versija, ko izmanto, lai sazinātos ar pakalpojumu

  - **Data.Doc.ServerType —** tā servera tips, kas nodrošina pakalpojumu (OneDrive, SharePoint, WOPI utt.)

  - **Data.Doc.ServerVersion —** tā servera versija, kas nodrošina pakalpojumu

  - **Data.Doc.SessionId —** identificē konkrētu dokumenta rediģēšanas sesiju pilnā sesijā

  - **Data.Doc.SharePointServiceContext —** diagnostikas informācija no SharePoint Online pieprasījumiem

  - **Data.Doc.SizeInBytes —** dokumenta lieluma rādītājs

  - **Data.Doc.SpecialChars —** speciālo rakstzīmju rādītājs dokumenta vietrādī URL vai ceļā

  - **Data.Doc.StorageProviderId —** novecojis

  - **Data.Doc.StreamAvailability —** norāda, vai ir pieejama/atspējota dokumenta plūsma

  - **Data.Doc.SussionId —** novecojis

  - **Data.Doc.SyncBackedType —** norāda dokumenta veidu (lokālais vai servera)

  - **Data.Doc.UrlHash —** vienvirziena jaukšana vienkāršota dokumenta identifikatora izveidei

  - **Data.Doc.UsedWrsDataOnOpen —** diagnostikas indikators inkrementālai dokumentu atvēršanai

  - **Data.Doc.WopiServiceId —** satur unikālu WOPI pakalpojumu sniedzēja identifikatoru

  - **Data.DocnReadOnlyReasons —** novecojis

  - **Data.DocumentSaveEndpoint —** novecojis, to aizvieto Data\_Doc\_Location

  - **Data.DocumentSaveType —** saglabāšanas tips (parasts, komanda Izveidot, Saglabāt kā)

  - **Data.DocumentSizeOnDisk —** novecojis, to aizvieto Data\_Doc\_SizeInBytes

  - **Data.DoesBaseHaveContentOnOpen —** izmaiņu izsekošanas diagnostika, lai pārliecinātos, vai mums ir koplietojamā faila jaunākā versija

  - **Data.DoesWorkingBranchHaveExcludedDataOnOpen —** izmaiņu izsekošanas diagnostika, lai pārliecinātos, vai mums ir koplietojamā faila jaunākā versija

  - **Data.DstDoc.AccessMode —** jaunais dokuments ir tikai lasāms/rediģējams

  - **Data.DstDoc.EdpState —** jaunā dokumenta elektronisko datu aizsardzības iestatījums

  - **Data.DstDoc.Extension —** jaunā dokumenta paplašinājums (docx/xlsm/pptx utt.)

  - **Data.DstDoc.FileFormat —** jaunā dokumenta faila formāta protokols

  - **Data.DstDoc.Fqdn —** jaunā dokumenta OneDrive vai SharePoint Online domēna nosaukums

  - **Data.DstDoc.FqdnHash —** jaunā dokumenta klientu identificējamā domēna nosaukuma vienvirziena jaukšana

  - **Data.DstDoc.IdentityUniqueId —** novecojis

  - **Data.DstDoc.IOFlags —** jaunā dokumenta kešoto opciju karodziņi, kas tiek izmantoti atvēršanas laikā

  - **Data.DstDoc.IsOpeningOfflineCopy —** karodziņš, kas norāda, ka tika atvērta jaunā dokumenta bezsaistes kopija

  - **Data.DstDoc.IsSyncBacked —** karodziņš, kas norāda, ka datorā pastāv automātiski sinhronizēta dokumenta kopija

  - **Data.DstDoc.Location —** norāda pakalpojumu, kurā atrodas jaunā dokuments (OneDrive, File Server, SharePoint utt.)

  - **Data.DstDoc.NumberCoAuthors —** citu lietotāju skaits jaunā dokumenta koprediģēšanas sesijā

  - **Data.DstDoc.ReadOnlyReasons —** iemesli, kāpēc jaunais dokuments ir atvērts tikai lasāmajā režīmā

  - **Data.DstDoc.ResourceIdHash —** anonimizēts dokumenta identifikators, ko izmanto jaunā dokumenta problēmu noteikšanā

  - **Data.DstDoc.ServerDocId —** nemainīgs, anonimizēts dokumenta identifikators, ko izmanto jaunā dokumenta problēmu noteikšanā

  - **Data.DstDoc.ServerProtocol —** tā protokola versija, ko izmanto, lai sazinātos ar pakalpojumu jaunā dokumenta izveides laikā

  - **Data.DstDoc.ServerType —** tā servera tips, kas nodrošina pakalpojumu (OneDrive, SharePoint, WOPI utt.) jaunajam dokumentam

  - **Data.DstDoc.ServerVersion —** tā servera versija, kas nodrošina pakalpojumu jaunajam dokumentam

  - **Data.DstDoc.SessionId —** identificē konkrētu dokumenta rediģēšanas sesiju pilnā sesijā jaunam dokumentam

  - **Data.DstDoc.SharePointServiceContext —** diagnostikas informācija no SharePoint Online pieprasījumiem jaunam dokumentam

  - **Data.DstDoc.SizeInBytes —** jaunā dokumenta lieluma rādītājs

  - **Data.DstDoc.UrlHash —** vienvirziena jaukšana vienkāršota jaunā dokumenta identifikatora izveidei

  - **Data.EditorsCount —** citu to līdzautoru skaits, kas rediģē dokumentu

  - **Data.FullIError —** visu kļūdu kodu kešatmiņa no protokola slāņa

  - **Data.HasFilteredCategories —** novecojis

  - **Data.HasFilteredCategoryNames —** novecojis

  - **Data.HasFilteredSeries —** novecojis

  - **Data.HasFilteredSeriesNames —** novecojis

  - **Data.HasPendingSaveAs —** norāda, ka notiek pieprasījums Saglabāt kā/Saglabāt kopiju

  - **Data.Input.FileOpenState —** statuss, ko pieprasa programma (lasīšana/lasīšana un rakstīšana utt.)

  - **Data.Input.FileSaveState —** statuss, ko pieprasa programma (saglabāšana atverot, saglabāt kā utt.)

  - **Data.Input.NetworkCost —** norāda tīkla izmaksu/tipu (mērāmus, mērāms virs ierobežojuma utt.)

  - **Data.Input.OpenAsync —** karodziņš, kas norāda, ka programma pieprasīja asinhrono atvēršanu

  - **Data.Input.OpenOfflineCopy —** karodziņš, kas norāda, ka programma pieprasīja atvēršanu bezsaistē

  - **Data.IsCachedHistoricalVersion —** norāda, ka šī nav jaunākā kešatmiņas faila versija.

  - **Data.IsHtml —** norāda, ka HTML formāta teksts ir ielīmēts

  - **Data.IsLegacyCode —** norāda, ka mantotā koda formāta teksts ir ielīmēts

  - **Data.IsLocalOnlyFile —** norāda, ka fails tika atvērts tikai no lokālās krātuves

  - **Data.IsLocalOrSyncBackedFile —** norāda, ka fails ir atvērts lokāli un kartēts, izmantojot pakalpojumu

  - **Data.IsMapUnMapCase —** kešotā faila statusa daļa

  - **Data.isOpenFromCollab —** norāda, ka fails ir atvērts no koplietojama sadarbības pakalpojuma

  - **Data.IsStubFile —** dokuments vēl nav koplietots mākoņpakalpojumā

  - **Data.IsSyncBackedFile —** dokuments ir mapē, kas ir atjaunināta un automātiski sinhronizēta

  - **Data.IsSyncBackedStateDifferentThanOnLastOpen —** dokumenta statuss ir mainīts, izmaiņas, iespējams, ir ieviestas, kamēr dokuments bija aizvērts

  - **Data.sWorkingBranchAvailableOnOpen —** izmaiņu izsekošanas diagnostika, lai pārliecinātos, vai mums ir koplietojamā faila jaunākā versija

  - **Data.Location —** norāda multivides tipu/atrašanās vietu (USB, mākonis utt.)

  - **Data.LockRequestDocMode —** norāda, vai dokuments ir pieejams citiem lietotājiem

  - **Data.MruRequestResult —** novecojis

  - **Data.NewDataNotAvailableReason —** novecojis

  - **Data.OcsDisableReasons —** netiek izmantots saglabātajā failā

  - **Data.OcsHostOnOpen —** netiek izmantots saglabātajā failā

  - **Data.Output.FileSaveState —** pabeigtas saglabāšanas statuss

  - **Data.PivotChart —** novecojis

  - **Data.resolveConflictState —** iemeslu kodi sapludinātu konfliktu atrisināšanas pieprasījumam

  - **Data.RTCEnabled —** sākts ātrais izmaiņu izplatīšanas protokols

  - **Data.SaveAsToCurrent —** norāda, ka aktīvais dokuments pārrakstīs saglabāto failu

  - **Data.ServiceId —** novecojis, to aizvietoja Data\_Doc\_WopiServiceId

  - **Data.SessionId —** novecojis

  - **Data.SizeInBytes —** novecojis, to aizvieto Data\_Doc\_SizeInBytes

  - **Data.StopwatchDuration —** novecojis

  - **Data.SyncBackedFileRequiresOnlineTransition —** karodziņš, kas norāda, ka tiešsaistes pāreja uz laiku bloķē saglabāšanas darbību

  - **Data.SyncBackedFileSaveOnOpen —** karodziņš, kas norāda, ka automātiski sinhronizētās izmaiņas ir nepieciešams saglabāt atvēršanas laikā

  - **Data.TelemetryId —** novecojis

  - **Data.TriggerSaveAfterBaseDownload —** izmaiņu izsekošanas diagnostika, lai pārliecinātos, vai mums ir koplietojamā faila jaunākā versija

  - **Data.UploadBlockedDueToCoherencyFailure —** saglabāšana pakalpojumā ir bloķēta, gaidot lietotāja konfliktējošo izmaiņu atrisinājumu

  - **Data.UploadBlockedDueToFailedSaveAsOverExisting —** saglabāšana pakalpojumā ir bloķēta, jo neizdevās pārrakstīt esošu failu

  - **Data.UploadPreemptedForCoherency —** saglabāšana pakalpojumā pārtraukta, jo lietotājs veic papildu izmaiņas

  - **Data.UploadPreemptedForSaveAsOverExistingFailure —** saglabāšana pakalpojumā pārtraukta iepriekšējās SaveAsOverExisting kļūdas dēļ

  - **Data.UploadScheduled —** fails ir gatavs asinhronai augšupielādei pakalpojumā

  - **Data.UseClientIdAsSchemaLockId —** karodziņš, kas kontrolē, kā dokuments ir bloķēts pakalpojumā

  - **Data.WorkingCopySaved —** izmaiņu izsekošanas diagnostika, lai pārliecinātos, vai mums ir koplietojamā faila jaunākā versija

  - **Data.ZrtSaveAsforSyncBackedBusinessEnabled —** karodziņš, kas norāda, ka pakalpojumam SharePoint Online ir iespējota ātrā saglabāšana

  - **Data.ZrtSaveAsforSyncBackedConsumerEnabled —** karodziņš, kas norāda, ka pakalpojumam OneDrive (Consumer) ir iespējota ātrā saglabāšana

  - **Data.ZrtSaveAsforSyncBackedCTBusinessEnabled —** karodziņš, kas norāda, ka pakalpojumam SharePoint Online ir iespējoti ātrās saglabāšanas satura tipi

  - **Data.ZrtSaveAsforSyncBackedCTConsumerEnabled —** karodziņš, kas norāda, ka pakalpojumam OneDrive (Consumer) ir iespējoti ātrās saglabāšanas satura tipi

  - **Data.ZrtSaveAsforSyncBackedMetaDataBusinessEnabled —** karodziņš, kas norāda, ka pakalpojumam SharePoint Online ir iespējota ātrā faila metadatu saglabāšana

  - **Data.ZrtSaveAsforSyncBackedMetaDataConsumerEnabled —** karodziņš, kas norāda, ka pakalpojumam OneDrive (Consumer) ir iespējota ātrā faila metadatu saglabāšana

#### <a name="officefindtimeappfailedtostart"></a>Office.FindTime.AppFailedToStart

Apkopo, ja programmu nevar palaist, jo startēšanas laikā radās neparedzēta kļūda. Izmantot, lai izsekotu izņēmumiem un avārijām. Palīdz pārraudzīt un atkļūdot programmas darbspēju.

Tiek apkopoti tālāk norādītie lauki.
- **DateTime** — notikuma reģistrēšanas laikspiedols

- **EventName** — reģistrētā notikuma nosaukums

#### <a name="office_firstrun_apple_activationresult"></a>Office_FirstRun_Apple_ActivationResult

Šo notikumu apkopo Office programmām, kas tiek lietotas Apple platformās. Pasākums tiek lietots, lai pārraudzītu mūsu programmas aktivizēšanas plūsmas darbspēju. Mēs apkopojam datus, lai noskaidrotu Office 365 abonementa aktivizēšanas rezultātus kopā ar plūsmu, kas tiek lietota aktivizācijai (Pirmā palaišanas pieredze, Programmas plūsma, Iegāde utt.).

Tiek apkopoti šādi lauki:

- **Data_ActivationStatusCollectionTime** — laikspiedols

- **Data_ActivationStatusError** — aktivizācijas kļūdas kods.

- **Data_ActivationStatusFlowType** – skaitliska vērtība, kas norāda aktivizēšanas plūsmas tipu

#### <a name="office_firstrun_apple_activationstatus"></a>Office_FirstRun_Apple_ActivationStatus

Šo notikumu apkopo Office programmām, kas darbojas Apple platformās. Mēs apkopojam datus, lai noskaidrotu Office 365 abonementa aktivizēšanas rezultātus kopā ar plūsmu, kas tiek lietota aktivizācijai (PPP, Programmas plūsma, Iegāde utt.). Mēs apkopojam datus, kas satur aktivizācijas tipu, plūsmas tipu (Pirmā palaišanas plūsma/DocStage/Iegāde) un Office licencēšanas pakalpojuma ID.

Tiek apkopoti šādi lauki:

- **Data_ActivationTypeCollectionTime** — laikspiedols

- **Data_ActivationTypeFlowType** — skaitliska vērtība, kas norāda aktivizēšanas plūsmas tipu

- **Data_ActivationTypeOLSLicense** — licences identifikators

- **Data_ActivationTypeStatus** — aktivizācijas statusa kods.

#### <a name="office_firstrun_apple_firstruncomplete"></a>Office_FirstRun_Apple_FirstRunComplete

Šo notikumu apkopo Office programmām, kas tiek lietotas Apple platformās. Šis notikums mūs informē, vai lietotājs izmanto freemium plūsmas tipu (PPP/DocStage/Iegāde) un identitātes tipu (PPL/OrgID). Šis notikums tiek izmantots, lai noskaidrotu, vai pirmā palaišanas pieredze (PPP) ir pabeigta un identitātes tipu, kas tiek izmantots, lai pierakstītos (MSA/OrgID).

Tiek apkopoti šādi lauki:

- **Data_FirstRunCompletedCollectionTime** — laikspiedols, kas reģistrē laiku, kad plūsma tika pabeigta

- **Data_FirstRunCompletedFlowType** — kods, kas apzīmē pabeigto lietotāja plūsmas tipu 

- **Data_FirstRunCompletedFreemiumStatus** — kods, kas apzīmē freemium lietotāja plūsmas pabeigšanas statusu

- **Data_FirstRunCompletedIdentityType** — tā lietotāja identitātes tips, kas pabeidzis plūsmu

#### <a name="office_firstrun_apple_firstrunstart"></a>Office_FirstRun_Apple_FirstRunStart

Šo notikumu apkopo Office programmām, kas tiek lietotas Apple platformās. Šis pasākums mūs informē, ka lietotājs ir iegājis pirmā palaišanas pieredze un tiek palaists plūsmas tips (PPP/DocStage/Iegāde). Šis notikums tiek izmantots, lai noskaidrotu, vai pirmā palaišanas pieredze (PPP) tika sākta sekmīgi.

Tiek apkopoti šādi lauki:

- **Data_FirstRunStartedCollectionTime** — laikspiedols, kas reģistrē laiku, kad plūsma tika pabeigta

- **Data_FirstRunStartedFlowType** — kods, kas apzīmē pabeigto lietotāja plūsmas tipu 

#### <a name="office_firstrun_apple_firstrunstartedandcompleted"></a>Office_FirstRun_Apple_FirstRunStartedAndCompleted

Šo notikumu apkopo Office programmām, kas tiek lietotas Apple platformās. Šis notikums mūs informē, vai lietotājs izmanto freemium plūsmas tipu (PPP/DocStage/Iegāde) un identitātes tipu (PPL/OrgID). Mēs izmantojam šo notikumu, lai noskaidrotu, cik mūsu pirmā palaišanas pieredzes (PPP) plūsmas darbspēju un efektivitāti.

Tiek apkopoti šādi lauki:

- **Data_FirstRunCompletedCollectionTime** — laikspiedols, kas reģistrē laiku, kad plūsma tika pabeigta

- **Data_FirstRunCompletedFlowType** — kods, kas apzīmē pabeigto lietotāja plūsmas tipu  

- **Data_FirstRunCompletedFreemiumStatus** — kods, kas apzīmē freemium lietotāja plūsmas pabeigšanas statusu

- **Data_FirstRunCompletedIdentityType** — tā lietotāja identitātes tips, kas pabeidzis plūsmu

- **Data_FirstRunCompletedCollectionTime** — laikspiedols, kas reģistrē laiku, kad plūsma tika pabeigta

- **Data_FirstRunCompletedFlowType** — kods, kas apzīmē pabeigto lietotāja plūsmas tipu

#### <a name="office_firstrun_apple_inapppurchaseactivationfail"></a>Office_FirstRun_Apple_InAppPurchaseActivationFail

Šo notikumu apkopo Office programmām, kas tiek lietotas Apple platformās. Pasākums tiek lietots, lai pārraudzītu mūsu programmas aktivizēšanas plūsmas darbspēju. Mēs apkopojam datus, lai noskaidrotu programmas iegādes aktivizēšanas rezultātus kopā ar plūsmu, kas tiek lietota aktivizācijai (Pirmā palaišanas pieredze, Programmas plūsma, Iegāde utt.). 

Tiek apkopoti šādi lauki:

- **Data_ActivationFailCollectionTime** — laikspiedols, kas reģistrē laiku, kad notika aktivizēšanas kļūme 

- **Data_ActivationFailFlowType** — kods, kas apzīmē izmantoto lietotāja plūsmas tipu

- **Data_AssoicatedSuccessfullyCollectionTime** — laikspiedols, kas reģistrē laiku, kad notika saistīšanas kļūme 

- **Data_AssoicatedSuccessfullyFlowType** — kods, kas apzīmē izmantoto lietotāja plūsmas tipu

#### <a name="office_firstrun_apple_inapppurchaseactivationsuccess"></a>Office_FirstRun_Apple_InAppPurchaseActivationSuccess

Šo notikumu apkopo Office programmām, kas tiek lietotas Apple platformās. Pasākums tiek lietots, lai pārraudzītu mūsu programmas aktivizēšanas plūsmas darbspēju. Mēs apkopojam datus, lai noskaidrotu programmas iegādes aktivizēšanas rezultātus kopā ar plūsmu, kas tiek lietota aktivizācijai (Pirmā palaišanas pieredze, Programmas plūsma, Iegāde utt.). 

Tiek apkopoti šādi lauki:

- **Data_ActivatedSuccessfullyCollectionTime** — laikspiedols, kas reģistrē laiku, kad notika aktivizēšanas kļūme 

- **Data_ActivatedSuccessfullyFlowType** — kods, kas apzīmē izmantoto lietotāja plūsmas tipu

- **Data_AssoicatedSuccessfullyCollectionTime** — laikspiedols, kas reģistrē laiku, kad notika saistīšanas kļūme 

- **Data_AssoicatedSuccessfullyFlowType** — kods, kas apzīmē izmantoto lietotāja plūsmas tipu

#### <a name="office_firstrun_apple_inapppurchaseassociationfailed"></a>Office_FirstRun_Apple_InAppPurchaseAssociationFailed

Šo notikumu apkopo Office programmām, kas tiek lietotas Apple platformās. Pasākums tiek lietots, lai pārraudzītu mūsu programmas aktivizēšanas plūsmas darbspēju. Mēs apkopojam datus, lai noskaidrotu programmas iegādes aktivizēšanas rezultātus kopā ar plūsmu, kas tiek lietota aktivizācijai (Pirmā palaišanas pieredze, Programmas plūsma, Iegāde utt.). 

Tiek apkopoti šādi lauki:

- **Data_AppChargedSuccessfullyCollectionTime** — laikspiedols, kas reģistrē laiku, kad tika iekasēta maksa par pirkumu

- **Data_AppChargedSuccessfullyFlowType** — kods, kas apzīmē izmantoto lietotāja plūsmas tipu

- **Data_AssoicationFailedCollectionTime** — laikspiedols, kas reģistrē laiku, kad notika programmas piesaistes kļūme

- **Data_AssoicationFailedFlowType** — kods, kas apzīmē izmantoto lietotāja plūsmas tipu

- **Data_AssoicationFailedResult** — kods, kas norāda neveiksmes tipu

#### <a name="office_firstrun_apple_inapppurchaseassociationsuccess"></a>Office_FirstRun_Apple_InAppPurchaseAssociationSuccess

Šo notikumu apkopo Office programmām, kas tiek lietotas Apple platformās. Pasākums tiek lietots, lai pārraudzītu mūsu programmas aktivizēšanas plūsmas darbspēju. Mēs apkopojam datus, lai noskaidrotu programmas iegādes aktivizēšanas rezultātus kopā ar plūsmu, kas tiek lietota aktivizācijai (Pirmā palaišanas pieredze, Programmas plūsma, Iegāde utt.). 

Tiek apkopoti šādi lauki:

- **Data_AppChargedSuccessfullyCollectionTime** — laikspiedols, kas reģistrē laiku, kad tika iekasēta maksa par pirkumu

- **Data_AppChargedSuccessfullyFlowType** — kods, kas apzīmē izmantoto lietotāja plūsmas tipu

- **Data_AssoicatedSuccessfullyCollectionTime** — laikspiedols, kas reģistrē laiku, kad notika programmas saistīšanas kļūme

- **Data_AssoicatedSuccessfullyFlowType** — kods, kas apzīmē izmantoto lietotāja plūsmas tipu

#### <a name="office_firstrun_apple_inapppurchasefailures"></a>Office_FirstRun_Apple_InAppPurchaseFailures

Šo notikumu apkopo Office programmām, kas tiek lietotas Apple platformās. Pasākums tiek lietots, lai pārraudzītu mūsu programmas aktivizēšanas plūsmas darbspēju. Mēs apkopojam informāciju par programmas iegādes plūsmas rezultātu.

Tiek apkopoti šādi lauki:

- **Data_AppStoreFailureFlowType** — kods, kas apzīmē izmantoto lietotāja plūsmas tipu

- **Data_AppStoreFailureResult** — novērotais neveiksmes rezultāts

- **Data_CancelRequesFlowType** — kods, kas apzīmē izmantoto lietotāja plūsmas tipu

- **Data_EventId** — kods, kas apzīmē neveiksmes tipu

#### <a name="office_firstrun_apple_inapppurchasesattempted"></a>Office_FirstRun_Apple_InAppPurchasesAttempted

Šo notikumu apkopo Office programmām, kas tiek lietotas Apple platformās. Pasākums tiek lietots, lai pārraudzītu mūsu programmas iegādes plūsmas darbspēju. Mēs apkopojam datus, lai izsekotu programmas pirkumus un to tipu, ko esat iegādājies (mēneša/gada/mājas/individuālai lietošanai).

Tiek apkopoti šādi lauki:

- **Data_EventId** — kods, kas apzīmē rezultāta tipu

- **Data_PurchasedClickedOfferType** — izmēģinātā SKU tips

- **Data_PurchaseSuccessfulFlowType** — kods, kas apzīmē izmantotā lietotāja plūsmas tipu

#### <a name="office_firstrun_apple_inapprestoreattempted"></a>Office_FirstRun_Apple_InAppRestoreAttempted

Šo notikumu apkopo Office programmām, kas tiek lietotas Apple platformās. Pasākums tiek lietots, lai pārraudzītu mūsu programmas iegādes plūsmas darbspēju. Mēs apkopojam datus, lai izsekotu programmas atjaunošanas mēģinājumus

Tiek apkopoti šādi lauki:

- **Data_EventId** — kods, kas apzīmē mēģinājuma rezultāta tipu

- **Data_RestoreAttemptFlowType** — kods, kas apzīmē izmantotā lietotāja plūsmas tipu

#### <a name="office_firstrun_apple_inapprestoreattemptfailed"></a>Office_FirstRun_Apple_InAppRestoreAttemptFailed

Šo notikumu apkopo Office programmām, kas tiek lietotas Apple platformās. Pasākums tiek lietots, lai pārraudzītu mūsu programmas iegādes plūsmas darbspēju. Mēs apkopojam datus, lai izsekotu to, kā notiek programmu atjaunošanai un ar to saistītām plūsmām un kļūdām.

Tiek apkopoti šādi lauki:

- **Data_RestoreButtonFlowType** — kods, kas apzīmē izmantotā lietotāja plūsmas tipu

- **Data_RestoredFailedPaymentCancelledFlowType** — kods, kas apzīmē izmantotā maksājuma atcelšanas plūsmas tipu

- **Data_RestoredFailedUnKnownFlowType** — vai mēģinājums neizdevās negaidītas lietotāja plūsmas dēļ

- **Data_RestoredFailedUnKnownResult** — vai mēģinājums neizdevās nezināmu iemeslu dēļ

#### <a name="office_firstrun_apple_macfirstruncompleted"></a>Office_FirstRun_Apple_MacFirstRunCompleted

Šo notikumu apkopo Office programmām, kas tiek lietotas Apple platformās. Šis pasākums mūs informē, ka lietotājs ir veicis pirmo palaišanas pieredzi. Šis notikums tiek izmantots, lai noskaidrotu, vai pirmā palaišanas pieredze (PPP) bija sekmīga.

Tiek apkopoti šādi lauki:

- **Data_FirstRunCollectionTime** — laikspiedols, kas reģistrē laiku, kad plūsma tika pabeigta.

#### <a name="office_firstrun_apple_macwxpfirstrunstarted"></a>Office_FirstRun_Apple_MacWXPFirstRunStarted

Šo notikumu apkopo Office programmām, kas tiek lietotas Apple platformās. Šis pasākums mūs informē, ka lietotājs ir veicis pirmo palaišanas pieredzi. Šis notikums tiek izmantots, lai noskaidrotu, vai pirmā palaišanas pieredze (PPP) tika sākta sekmīgi.

Tiek apkopoti šādi lauki:

- **Data_FirstRunPanelName** — tā paneļa nosaukums, no kura sākta darba pieredze

#### <a name="officelivepersonacarduseractionsclosedpersonacard"></a>Office.LivePersonaCard.UserActions.ClosedPersonaCard

Mēs reģistrējam brīdi, kad lietotājs aizver personas kartīti.  Šie dati tiek izmantoti, lai noteiktu, vai kartīte ir aizvērta pareizi. 

Tiek apkopoti šādi lauki: 

- **BatchId** — globāli unikāls identifikators, ja tika veikta pieprasījumu kopa

- **Data.appContextId** — nejauši ģenerēts ID, kas tiek lietots dažādu kontu identificēšanai vienā un tajā pašā programmā

- **Data.AppInfo.Name** — izmantojamā pakalpojuma nosaukums (profila kartīte)

- **Data.AppInfo_Id** — resursdatora lietojumprogrammas nosaukums

- **Data.AppInfo_Version** — resursdatora lietojumprogrammas versija

- **Data.cardCorrelationId** — globāli unikāls identifikators personas kartītei

- **Data.cardPersonaCorrelationId** — globālais unikālais identifikators konkrētai personai, kas redzama kartītē

- **Data.clientCorrelationId** — globāli unikāls identifikators programmas sesijai

- **Data.clientType** — ierīces, kurā darbojas lietojumprogramma, versija

- **Data.eventId** — notikuma nosaukuma identifikators, piemēram, "LivePersonaCardRenderedAction"

- **Data.feature** — tiek lietots, lai grupētu dažādus viena un tā paša līdzekļa (profila kartītes) notikumus

- **Data.OTelJS.Version** — OTel reģistrētāja versija

- **Data.properties** — katram notikumam apkopotie papildu metadati, kas aprakstīti zemāk:
  - **ClientTimeStamp** — notikuma reģistrācijas laiks lietojumprogrammā
  - **cardCorrelationId** — Data.appContextId dublikāts
  - **cardPersonaCorrelationId** — Data.cardCorrelationId dublikāts
  - **consumerCorrelationId** — Data.clientCorrelationId dublikāts
  - **externalAppSessionCorrelationId** — globāli unikāls identifikators programmai, lai identificētu visas personas kartītes, kas ir atvērtas vienā apakšsesijā
  - **immersiveProfileCorrelationId** — globāli unikāls identifikators izvērsta profila skata sesijai
  - **personaCorrelationId** — globāli unikāls identifikators unikālajām personām sesijā

- **Data.region** — tā profila kartītes aizmugursistēmas pakalpojuma ģeogrāfiskais reģions, ar kuru savienots lietotājs

- **Data.tenantAadObjectId** — nomnieks, kuram ir piesaistīts lietotāja abonements. Ļauj mums klasificēt problēmas un noteikt, vai problēma ir plaši izplatīta vai izolēta konkrēta nomnieka lietotāju kopā

- **Data.type** — reģistrētā notikuma tips, piemēram, izsekošana, kļūda, notikums

- **Data.userAadObjectId** — globāli unikālā lietotāja identifikators uzņēmuma Microsoft kontam (Data.UserInfo.Id dublikāts)

- **Data.UserInfo.Id** — globāli unikālā lietotāja identifikators uzņēmuma Microsoft kontam

- **Data.UserInfo.MsaId** — globāli unikālā lietotāja identifikators klienta Microsoft kontam

- **Data.UserInfo.OMSTenantId** — nomnieks, ar kuru ir saistīts lietotāja abonements. Ļauj mums klasificēt problēmas un noteikt, vai problēma ir plaši izplatīta vai izolēta konkrēta nomnieka lietotāju kopā

- **Data.userPuid** — globāli unikālā lietotāja identifikators klienta Microsoft kontam (Data.UserInfo.MsaId dublikāts)

- **Data.version** — pakalpojuma versija (profila kartīte)

- **Data_hostAppRing** — personas kartītes ieviešanas loks

- **Event_ReceivedTime** — notikuma reģistrēšanas laiks pakalpojumā

#### <a name="officelivepersonacarduseractionsconfigurationsetaction"></a>Office.LivePersonaCard.UserActions.ConfigurationSetAction

Mēs reģistrējam brīdi, kad lietotājs atrodas lietojumprogrammā, kas ielādē personas kartīti, sagaidot, ka lietotājs atvērs Live personas kartīti.   Šie dati tiek izmantoti, lai noteiktu, vai kartīte ir ielādēta pareizi. 

Tiek apkopoti tālāk norādītie lauki: 

- **Data.appContextId** — nejauši ģenerēts ID, kas tiek lietots dažādu kontu identificēšanai vienā un tajā pašā lietojumprogrammā

- **Data.AppInfo.Name** — izmantojamā pakalpojuma nosaukums (profila kartīte)

- **Data.AppInfo_Id** — resursdatora lietojumprogrammas nosaukums

- **Data.AppInfo_Version** — resursdatora lietojumprogrammas versija

- **Data.cardCorrelationId** — globāli unikāls identifikators personas kartītei

- **Data.cardPersonaCorrelationId** — globālais unikālais identifikators konkrētai personai, kas redzama kartītē

- **Data.clientCorrelationId** — globāli unikāls identifikators programmas sesijai

- **Data.clientType** — ierīces, kurā darbojas lietojumprogramma, versija

- **Data.eventId** — notikuma nosaukuma identifikators, piemēram, "LivePersonaCardRenderedAction"

- **Data.eventpriority** — notikuma sūtīšanas prioritātes uzskaites vērtība.

- **Data.feature** — tiek lietots, lai grupētu dažādus viena un tā paša līdzekļa (profila kartītes) notikumus

- **Data.OTelJS.Version** — OTel reģistrētāja versija

- **Data.properties** — katram notikumam apkopotie papildu metadati, kas aprakstīti zemāk:

  - **accountType** — norāda, vai lietotājs pieder organizācijai vai ir patērētājs

  - **cardCorrelationId** — Data.appContextId dublikāts

  - **cardPersonaCorrelationId** — Data.cardCorrelationId dublikāts

  - **ClientTimeStamp** — notikuma reģistrācijas laiks lietojumprogrammā

  - **consumerCorrelationId** — Data.clientCorrelationId dublikāts

  - **contextType** — no kura konteksta (lietojumprogrammas) tika palaista kartīte

  - **ecsConfigIds** — kartītē iespējoto līdzekļu versiju identifikatori

  - **ecsTagId** — atzīmes ID līdzekļiem

  - **externalAppSessionCorrelationId** — globāli unikāls identifikators programmai, lai identificētu visas personas kartītes, kas ir atvērtas vienā apakšsesijā

  - **flights** — kartītē iespējotie līdzekļi

  - **fromCache** — vai dati tika ielādēti no atmiņas

  - **hasFinePointer** — vai ierīcei ir peles rādītāja funkcionalitāte

  - **hasHoverEvents** — vai ierīcei ir norādīšanas ar peli funkcionalitāte

  - **immersiveProfileCorrelationId** — globāli unikāls identifikators izvērsta profila skata sesijai

  - **offlineResolved**— vai dati tika ielādēti bezsaistē

  - **personaCorrelationId** — globāli unikāls identifikators unikālajām personām sesijā

- **Data.region** — tā profila kartītes aizmugursistēmas pakalpojuma ģeogrāfiskais reģions, ar kuru savienots lietotājs

- **Data.tenantAadObjectId** — nomnieks, kuram ir piesaistīts lietotāja abonements. Ļauj mums klasificēt problēmas un noteikt, vai problēma ir plaši izplatīta vai izolēta konkrēta nomnieka lietotāju kopā

- **Data.type** — reģistrētā notikuma tips, piemēram, izsekošana, kļūda, notikums

- **Data.userAadObjectId** — globāli unikālā lietotāja identifikators uzņēmuma Microsoft kontam (Data.UserInfo.Id dublikāts)

- **Data.UserInfo.Id** — globāli unikālā lietotāja identifikators uzņēmuma Microsoft kontam

- **Data.UserInfo.MsaId** — globāli unikālā lietotāja identifikators klienta Microsoft kontam

- **Data.UserInfo.OMSTenantId** — nomnieks, ar kuru ir saistīts lietotāja abonements. Ļauj mums klasificēt problēmas un noteikt, vai problēma ir plaši izplatīta vai izolēta konkrēta nomnieka lietotāju kopā

- **Data.userPuid** — globāli unikālā lietotāja identifikators klienta Microsoft kontam (Data.UserInfo.MsaId dublikāts)

- **Data.version** — pakalpojuma versija (profila kartīte)

- **Data.workloadCulture** — resursdatora lietojumprogrammā iestatītā kultūra

- **DeviceInfo_Id** — globāli unikālais ierīces identifikators

- **DeviceInfo_Make** — operētājsistēmas zīmols

- **DeviceInfo_Model** — ierīces modelis

- **DeviceInfo_OsName** — ierīces operētājsistēmas nosaukums

- **DeviceInfo_OsVersion** — operētājsistēmas versija

- **DeviceInfo_SDKUid** — unikāli identificē ierīci no telemetrijas SDK perspektīvas

#### <a name="officelivepersonacarduseractionsopenedexpandedpersonacard"></a>Office.LivePersonaCard.UserActions.OpenedExpandedPersonaCard

Reģistrē, kad lietotājs atver izvērstu personas kartīti. To izmanto, lai konstatētu kritiskas anomālijas neveiksmes gadījumā, palaižot reāllaika personas kartīti.

Tiek apkopoti tālāk norādītie lauki:

- **AppInfo_Id** — resursdatora lietojumprogrammas nosaukums

- **AppInfo_Version** — resursdatora lietojumprogrammas versija

- **Data.appContextId** — nejauši ģenerēts ID, kas tiek lietots dažādu kontu identificēšanai vienā un tajā pašā programmā

- **Data.AppInfo.Name** — izmantojamā pakalpojuma nosaukums (profila kartīte)

- **Data.cardCorrelationId** — globāli unikāls identifikators personas kartītei

- **Data.cardPersonaCorrelationId** — globālais unikālais identifikators konkrētai personai, kas redzama kartītē

- **Data.clientCorrelationId** — globāli unikāls identifikators programmas sesijai

- **Data.clientType** — ierīces, kurā darbojas lietojumprogramma, versija

- **Data.eventId** — notikuma nosaukuma identifikators, piemēram, "LivePersonaCardRenderedAction"

- **Data.exportName** — lietotāja darbības notikuma lasāmais nosaukums, piemēram, "OpenedPersonaCard"

- **Data.exportType** — pasākuma kategorija VDAR eksporta pieprasījumam

- **Data.feature** — tiek lietots, lai grupētu dažādus viena un tā paša līdzekļa (profila kartītes) notikumus

- **Data.hostAppRing** — aplis, kurā programma tika izplatīta

- **Data.OTelJS.Version** — OTel reģistrētāja versija

- **Data.properties** — katram notikumam apkopotie papildu metadati, kas aprakstīti zemāk:

  - **cardCorrelationId** — Data.appContextId dublikāts 

  - **cardPersonaCorrelationId** — Data.cardCorrelationId dublikāts

  - **clientScenario** — izmanto, lai noteiktu līdzekli lietojumprogrammā, no kuras tika atvērta personas kartīte

  - **consumerCorrelationId** — Data.clientCorrelationId dublikāts 

  - **externalAppSessionCorrelationId** — globāli unikāls identifikators programmai, lai identificētu visas personas kartītes, kas ir atvērtas vienā apakšsesijā

  - **hasPersonalInsightRing** — ieskati no Office vai LinkedIn, kas var būt pieejami lietotājam

  - **immersiveProfileCorrelationId** — globāli unikāls identifikators izvērsta profila skata sesijai

  - **personaCorrelationId** — globāli unikāls identifikators unikālajām personām sesijā

  - **section** — izvērstās kartītes aktīvā sadaļa

- **Data.region** — tā profila kartītes aizmugursistēmas pakalpojuma ģeogrāfiskais reģions, ar kuru savienots lietotājs

- **Data.tenantAadObjectId** — nomnieks, kuram ir piesaistīts lietotāja abonements. Ļauj mums klasificēt problēmas un noteikt, vai problēma ir plaši izplatīta vai izolēta konkrēta nomnieka lietotāju kopā

- **Data.type** — reģistrētā notikuma tips, piemēram, izsekošana, kļūda, notikums

- **Data.userAadObjectId** — globāli unikālā lietotāja identifikators uzņēmuma Microsoft kontam (Data.UserInfo.Id dublikāts)

- **Data.UserInfo.Id** — globāli unikālā lietotāja identifikators uzņēmuma Microsoft kontam 

- **Data.UserInfo.MsaId** — globāli unikālā lietotāja identifikators klienta Microsoft kontam

- **Data.UserInfo.OMSTenantId** — nomnieks, ar kuru ir saistīts lietotāja abonements. Ļauj mums klasificēt problēmas un noteikt, vai problēma ir plaši izplatīta vai izolēta konkrēta nomnieka lietotāju kopā

- **Data.userPuid** — globāli unikālā lietotāja identifikators klienta Microsoft kontam (Data.UserInfo.MsaId dublikāts)

- **Data.version** — pakalpojuma versija (profila kartīte)

- **DeviceInfo_Id** — globāli unikālais ierīces identifikators

- **DeviceInfo_Make** — operētājsistēmas zīmols

- **DeviceInfo_Model** — ierīces modelis

- **DeviceInfo_OsName** — ierīces operētājsistēmas nosaukums

- **DeviceInfo_OsVersion** — operētājsistēmas versija

- **DeviceInfo_SDKUid** — unikāli identificē ierīci no telemetrijas SDK perspektīvas

- **NetworkCost** — norāda tīkla izmaksu/tipu (mērāmus, mērāms virs ierobežojuma utt.)

- **NetworkCountry** — sūtītāja valsts kods, kura pamatā ir neanonimizēta klienta IP adrese.


#### <a name="officelivepersonacarduseractionsopenedpersonacard"></a>Office.LivePersonaCard.UserActions.OpenedPersonaCard

Reģistrēts, kad lietotājs atver personas kartīti. To izmanto, lai konstatētu kritiskas anomālijas neveiksmes gadījumā, palaižot reāllaika personas kartīti.

Tiek apkopoti tālāk norādītie lauki.

- **Data.appContextId** — nejauši ģenerēts ID, kas tiek lietots dažādu kontu identificēšanai vienā un tajā pašā programmā

- **Data.AppInfo.Name** — izmantojamā pakalpojuma nosaukums (profila kartīte)

- **Data.cardCorrelationId** — globāli unikāls identifikators personas kartītei

- **Data.cardPersonaCorrelationId** — globālais unikālais identifikators konkrētai personai, kas redzama kartītē

- **Data.clientCorrelationId** — globāli unikāls identifikators programmas sesijai

- **Data.clientType** — ierīces tips, kurā tiek palaista programma.

- **Data.eventId** — notikuma nosaukuma identifikators, piemēram, "LivePersonaCardRenderedAction"

- **Data.exportName** — lietotāja darbības notikuma lasāmais nosaukums, piemēram, "OpenedPersonaCard"

- **Data.exportType** — pasākuma kategorija VDAR eksporta pieprasījumam

- **Data.feature** — tiek lietots, lai grupētu dažādus viena un tā paša līdzekļa (profila kartītes) notikumus

- **Data.hostAppRing** — aplis, kurā programma tika izplatīta

- **Data.OTelJS.Version** — OTel reģistrētāja versija

- **Data.region** — tā profila kartītes aizmugursistēmas pakalpojuma ģeogrāfiskais reģions, ar kuru savienots lietotājs

- **Data.tenantAadObjectId** — nomnieks, kuram ir piesaistīts lietotāja abonements. Ļauj mums klasificēt problēmas un noteikt, vai problēma ir plaši izplatīta vai izolēta konkrēta nomnieka lietotāju kopā

- **Data.type** — reģistrētā notikuma tips, piemēram, izsekošana, kļūda, notikums

- **Data.userAadObjectId** — globāli unikālā lietotāja identifikators uzņēmuma Microsoft kontam (Data.UserInfo.Id dublikāts)

- **Data.UserInfo.Id** — globāli unikālā lietotāja identifikators uzņēmuma Microsoft kontam 

- **Data.UserInfo.MsaId** — globāli unikālā lietotāja identifikators klienta Microsoft kontam

- **Data.UserInfo.OMSTenantId** — nomnieks, ar kuru ir saistīts lietotāja abonements. Ļauj mums klasificēt problēmas un noteikt, vai problēma ir plaši izplatīta vai izolēta konkrēta nomnieka lietotāju kopā

- **Data.userPuid** — globāli unikālā lietotāja identifikators klienta Microsoft kontam (Data.UserInfo.MsaId dublikāts)

- **Data.version** — pakalpojuma versija (profila kartīte)

- **Data.viewType** — nosaka attēlotās profila kartītes tipu

- **NetworkCost** — norāda tīkla izmaksu/tipu (mērāmus, mērāms virs ierobežojuma utt.)

- **NetworkCountry** — sūtītāja valsts kods, kura pamatā ir neizlaista klienta IP adrese.

- **Data.properties** — katram notikumam apkopotie papildu metadati, kā aprakstīts tālāk.

    - **bandwidthEstimateMbps** — efektīvo joslas platuma aprēķini Mb/s

    - **cardCorrelationId** — Data.appContextId dublikāts 

    - **cardPersonaCorrelationId** — Data.cardCorrelationId dublikāts

    - **consumerCorrelationId** — Data.clientCorrelationId dublikāts 

    - **externalAppSessionCorrelationId** — globāli unikāls identifikators programmai, lai identificētu visas personas kartītes, kas ir atvērtas vienā apakšsesijā

    - **immersiveProfileCorrelationId** — globāli unikāls identifikators izvērsta profila skata sesijai

    - **networkEffectiveType** — efektīvā tīkla savienojuma tips, piemēram, "slow-2g Online", lai noteiktu, vai lietotājam ir izveidots savienojums ar internetu brīdī, kad tiek parādīta personas kartīte

    - **networkType** — izmantotās ierīces tīkla savienojamības tips

    - **personaCorrelationId** — globāli unikāls identifikators unikālajām personām sesijā

    - **roundTripEstimateMs** — aprēķinātais efektīvais pašreizējā savienojuma cikls milisekundēs

    - **wasOpenedAsCompactCard** — izmanto, lai noteiktu, vai kartīte sākotnēji tika atvērta kā kompakts skats


#### <a name="officemanageabilityclient-fetchpolicyprechecks"></a>Office.Manageability.Client Fetch.PolicyPreChecks

Kritisko kļūdu telemetrija, lai izsekotu mākoņpakalpojuma politikas ieneses pirmspārbaudes validācijas panākumiem. Iziešanas iemesls satur skaitītāja karti, kas attiecas uz neizdevušos pirmspārbaudes nosacījumu.

Tiek apkopoti tālāk norādītie lauki.

  - **Data.ExitReason** — skaitītāja vērtība, kas paziņo iziešanas iemeslu, ja pirmspārbaude neizdevās

  - **Data.Log** — pielāgots žurnāla ziņojums, kas norāda pirmspārbaudes panākumus (izdošanos/neizdošanos)

#### <a name="officemanageabilityclientfetchandapplypolicy"></a>Office.Manageability.Client.Fetch.AndApplyPolicy

Kritisko kļūdu telemetrija, lai izsekotu, vai izdevās/neizdevās mākoņpakalpojuma politikas ieneses inicializēšana no programmas. Iziešanas iemesls satur skaitītāja karti, kas attiecas uz neizdošanās iemeslu.

Tiek apkopoti tālāk norādītie lauki.

  - **Data.ExitReason** — skaitītāja vērtība, kas paziņo iziešanas iemeslu, ja pirmspārbaude neizdevās

  - **Data.Log** — pielāgots žurnāla ziņojums, kas norāda pirmspārbaudes panākumus (izdošanos/neizdošanos)

#### <a name="office_officemobile_pdfviewer_pdffileoperations"></a>Office_OfficeMobile_PdfViewer_PdfFileOperations

Šis notikums tiek apkopots Office lietojumprogrammai darbam ar Android. Reģistrē, kad notiek PDF atvēršanas, aizvēršanas vai saglabāšanas darbība, un to izmanto, lai izprastu un prioritizētu lietotāja pieredzi atbilstoši informācijai par PDF failu darbību. Šis notikums ļauj mums nodrošināt atbilstošu PDF atvēršanas, aizvēršanas un saglabāšanas darbību izpildi, kā arī uzlabot PDF failu darbības veiktspēju.

Tiek apkopoti šādi lauki:

- **Data_Doc_FileOpSessionID**— unikāls ID dokumenta sesijai

- **Data_Doc_URLHash** — GUID faila URL

- **Data_ErrorCode** — kļūda faila atvēršanas kļūmes/ lejupielādes kļūmes / lejupielādes atcelšanas gadījumos

- **Data_ErrorMessage** — atbilstošais ziņojuma par kļūdu kods

- **Data_FailureReason** — atvēršanas kļūmes gadījumā, šie uzskaitījumi definē kļūmes iemeslu.

- **Data_FileLocation** — faila atrašanās vieta, piemēram: lokāli, ODSP, iCloud utt.

- **Data_FileOpenEntryPoint** — faila atvēršanas ievades punkts.

- **Data_FileSize** — faila, kurā notiek darbība, izmērs

- **Data_OpenMode** — kādā režīmā tika atvērts PDF, piem.: 0: skatīšanas režīms, 2: parakstīšanās režīms

- **Data_PageCount** — lapu skaits PDF failā.

- **Data_PasswordProtected** — marķieris, kas norāda, vai parole ir aizsargāta.

- **Data_ProviderApp** — pašreiz nodrošina pakalpojuma sniedzēja lietojumprogrammu gadījumos, kad notiek tikai faila aktivācija 

- **Data_ReadOnly** — marķieris, kas norāda, vai fails ir tikai lasāms.

- **Data_Result** — veicamās darbības statuss, piemēram: patiess: izdevās, aplams: neizdevās.

- **Data_Type** — faila darbības veids (atvēršana, aizvēršana vai saglabāšana) 

#### <a name="officeonenoteandroidappnavigationnavigationuistatechanged-onenoteappnavigationnavigationuistatechanged-previous-name"></a>Office.OneNote.Android.App.Navigation.NavigationUIStateChanged, OneNote.App.Navigation.NavigationUIStateChanged *(iepriekšējais nosaukums)*

Šis notikums apkopo kritiskos signālus, kas tiek izmantoti, lai nodrošinātu OneNote lietotāju veiksmīgu navigāciju lietojumprogrammā.  Telemetrija, kas tiek izmantota kritiskas regresijas atklāšanai OneNote lietojumprogrammā un pakalpojuma darbspējā. 

Tiek apkopoti šādi lauki: 

- **IS_SPANNED** — norāda, vai lietojumprogramma ir savienotā režīmā. Tiek īpaši uzskaitīts salokāmām ierīcēm.

- **NEW_STATE** — norāda lietojumprogrammas stāvokli uzreiz pēc navigācijas

- **OLD_STATE** — norāda lietojumprogrammas stāvokli tieši pirms navigācijas

#### <a name="officeonenoteandroidlenssdkofficelenslaunched-onenotelenssdkofficelenslaunched-previous-name"></a>Office.OneNote.Android.LensSDK.OfficeLensLaunched, OneNote.LensSDK.OfficeLensLaunched *(iepriekšējais nosaukums)*

Šis notikums apkopo kritisko signālu, kas tiek izmantots, lai nodrošinātu pareizu OfficeLens palaišanu.  Telemetrija, kas tiek izmantota kritiskas regresijas atklāšanai OneNote lietojumprogrammā un pakalpojuma darbspējā. 

Tiek apkopoti šādi lauki: 

- **CAPTURE_MODE** — norāda, kurā režīmā tika palaists OfficeLens.  Iespējamie režīmi ir noklusējuma, rediģēšanas, ātrās ievietošanas vai video importēšanas režīms.

- **ERROR_CODE** — norāda palaišanas kļūdas kodu gadījumā, ja palaišanas brīdī notika kļūda.

- **IMAGE_COUNT** — norāda uzņemto attēlu skaitu

- **LAUNCH_REASON** — norāda plūsmu, kurā tika palaists OfficeLens. Tas var notikt bloķēšanas ekrānā, StickyNotes kameras vai galerijas opcijās vai OneNote Canvas utt.

#### <a name="officeonenotecanvasinkinkstrokelogger"></a>Office.OneNote.Canvas.Ink.InkStrokeLogger 

Šis notikums tiek izmantots, lai atklātu un diagnosticētu augstfrekvences kļūdu, ar ko saskaras lietotājs, izmantojot rokraksta funkciju.  Tas tiks izmantots, lai noteiktu atbilstošāko šīs problēmas novēršanas veidu. 

Tiek apkopoti tālāk norādītie lauki:

- **CurrentCanvasZoomFactor** — pašreizējais kanvas tālummaiņas faktors.

- **CurrentNotebook** — pašreiz aktīvās piezīmju grāmatiņas identifikators.

- **CurrentPage** — pašreiz aktīvās lapas identifikators

- **CurrentSection** — pašreiz aktīvās sadaļas identifikators.

- **DefaultCanvasZoomFactor** — noklusējuma kanvas tālummaiņas faktors.

- **InkStrokeCount** — kopējais rokraksta vilkumu skaits kopš pēdējā žurnāla.

- **InkStrokeWithLayerInkEffect** — rokraksta vilkumu skaits ar slāņa efektu kopš pēdējā žurnāla.

- **InkStrokeWithoutPressureCount** — rokraksta vilkumu bez spiediena skaits kopš pēdējā žurnāla.

- **InkStrokeWithPencilInkEffect** — rokraksta vilkumu skaits ar zīmuļa efektu kopš pēdējā žurnāla.

- **InkStrokeWithTilt** — rokraksta vilkumu ar slīpumu skaits kopš pēdējā žurnāla.

#### <a name="officeonenotenavigationcreatepage"></a>Office.OneNote.Navigation.CreatePage

Kritisks signāls, kas tiek izmantots, lai uzraudzītu OneNote lietotāju spēju veidot lapas OneNote programmā.  Telemetrija, kas tiek izmantota kritiskas regresijas atklāšanai OneNote lietotnē un pakalpojuma darbspējā. Ja lietotājiem neizdodas izveidot lapu, tā aktivizēs kritisku incidentu.

Tiek apkopoti šādi lauki:

- **IsAtSectionEnd** — norāda, vai sadaļas beigās tiek izveidota jauna lapa.

- **IsBlank** — norāda, vai jaunā lapa ir tukša lapa vai izveidota no veidnes.

- **IsRecentsView** — norāda, vai lapa ir izveidota no nesenajām.

- **NavView** — norāda, vai lapa ir izveidota no navigācijas skata.

- **NoteType** — norāda lapas veidu (ātrā piezīme, saraksts vai fotogrāfija).

- **QuickNoteType** — norāda lapas veidu (ātrā piezīme, saraksts vai fotogrāfija).

- **RailState** — norāda uz OneNote navigācijas joslu lapas izveides brīdī.

- **Trigger** — norāda uz lapas izveides darbības sākuma punktu.

- **TriggerInfo** — norāda papildu informāciju par trigeri.


#### <a name="officeonenotenavigationcreatesection"></a>Office.OneNote.Navigation.CreateSection

Kritisks signāls, kas tiek izmantots, lai uzraudzītu OneNote lietotāju spēju veidot sadaļas OneNote programmā.  Telemetrija, kas tiek izmantota kritiskas regresijas atklāšanai OneNote lietotnē un pakalpojuma darbspējā. Ja lietotājiem neizdodas izveidot lapu, tā aktivizēs kritisku incidentu.

Tiek apkopoti tālāk norādītie lauki

- **NotebookID** — unikālais piezīmju grāmatiņas identifikators.

- **SectionID** — izveidotās sadaļas unikālais identifikators.

- **Trigger** — norāda uz sadaļas izveides darbības sākuma punktu.

- **TriggerInfo** — norāda papildu informāciju par trigeri.


#### <a name="officeonenotenavigationnavigate"></a>Office.OneNote.Navigation.Navigate

Kritisks signāls, kas tiek izmantots, lai uzraudzītu OneNote lietotāju naviģēšanu starp OneNote lapām.  Telemetrija, kas tiek izmantota kritiskas regresijas atklāšanai OneNote lietotnē un pakalpojuma darbspējā. Ja lietotājiem naviģēšana neizdodas, tiks aktivizēts kritiskais incidents.

Tiek apkopoti šādi lauki:

- **FromNotebook** — unikālais piezīmju grāmatiņas identifikators.

- **FromPage** — unikālais lapas identifikators.

- **FromSection** — unikālais sadaļas identifikators.

- **FromSectionGroup**— unikālais sadaļu grupas identifikators.

- **IsCurrentUserEduStudent** — norāda, vai pašreizējam lietotājam ir studenta loma izglītības piezīmju grāmatiņā.

- **IsEduNotebook** — norāda, vai pašreizējā lapa ir izglītības piezīmju grāmatiņa.

- **IsEduNotebookReadOnlyPage** — norāda, vai pašreizējā lapa ir tikai lasāma lapa izglītības piezīmju grāmatiņā.

- **ToNotebook** — unikālais piezīmju grāmatiņas identifikators.

- **ToPage** — unikālais lapas identifikators.

- **ToSection** — unikālais sadaļas identifikators.

- **ToSectionGroup** — unikālais sadaļu grupas identifikators.


#### <a name="officeonenotenotebookmanagementcreatenotebook"></a>Office.OneNote.NotebookManagement.CreateNotebook

Kritisks signāls, kas tiek izmantots, lai uzraudzītu OneNote lietotāju spēju veidot piezīmju grāmatiņas OneNote programmā.  Telemetrija, kas tiek izmantota kritiskas regresijas atklāšanai OneNote lietotnē un pakalpojuma darbspējā. Ja lietotājiem neizdodas izveidot piezīmju grāmatiņas, tiks aktivizēts kritiskais incidents.

Tiek apkopoti šādi lauki:
    
- **NotebookID** — unikālais piezīmju grāmatiņas identifikators.


#### <a name="officeonenotenotebookmanagementopennotebook"></a>Office.OneNote.NotebookManagement.OpenNotebook

Kritisks signāls, kas tiek izmantots, lai uzraudzītu OneNote lietotāju spēju atvērt piezīmju grāmatiņas OneNote programmā.  Telemetrija, kas tiek izmantota kritiskas regresijas atklāšanai OneNote lietotnē un pakalpojuma darbspējā. Ja lietotājiem neizdodas atvērt piezīmju grāmatiņas, tiks aktivizēts kritiskais incidents.

Tiek apkopoti šādi lauki:

-  **NotebookID** — unikālais piezīmju grāmatiņas identifikators.

    
#### <a name="officeonenotesearchsearch"></a>Office.OneNote.Search.Search

Kritiskā signāla ID, kas tiek izmantots, lai uzraudzītu OneNote lietotāju spēju atrast informāciju lapu un piezīmju grāmatiņu tūkstošos.   Telemetrija, kas tiek izmantota kritiskas regresijas atklāšanai OneNote lietotnē un pakalpojuma darbspējā. Ja lietotājiem neizdodas atrast informāciju piezīmju grāmatiņās, tiks aktivizēts kritiskais incidents.

Tiek apkopoti šādi lauki:

- **PageSearchResultCount** — norāda lapā meklēšanas režīmā atrasto meklēšanas rezultātu skaitu.

-  **PageTimeToFirstResultInMs** — norāda laiku, kas ir nepieciešams OneNote, lai atrastu pirmo atbilstošo rezultātu lapas meklēšanas režīmā.
    
-  **PageTimeToLastResultInMs** — norāda laiku, kas ir nepieciešams OneNote, lai atrastu pēdējo atbilstošo rezultātu lapas meklēšanas režīmā.

-  **PageTimeToMedianResultInMs** — norāda laiku, kas ir nepieciešams OneNote, lai atrastu visus atbilstošos rezultātus lapas meklēšanas režīmā.

-  **SearchResultCount** — norāda meklēšanas rezultātu skaitu.

-  **TagSearchResultCount** — norāda atzīmju meklēšanas režīmā atrasto meklēšanas rezultātu skaitu.

-  **TagTimeToFirstResultInMs** — norāda laiku, kas ir nepieciešams OneNote, lai atrastu pirmo atbilstošo rezultātu atzīmju meklēšanas režīmā.

-  **TagTimeToLastResultInMs** — norāda laiku, kas ir nepieciešams OneNote, lai atrastu pēdējo atbilstošo rezultātu atzīmju meklēšanas režīmā.

-  **TagTimeToMedianResultInMs** — norāda vidējo laiku, kas ir nepieciešams OneNote, lai atrastu visus atbilstošo rezultātus atzīmju meklēšanas režīmā.

-  **TimeToFirstResultInMs** — norāda laiku, kas ir nepieciešams OneNote, lai atrastu pirmo atbilstošo rezultātu.

-  **TimeToLastResultInMs** — norāda laiku, kas ir nepieciešams OneNote, lai atrastu pēdējo atbilstošo rezultātu.

-  **TimeToMedianResultInMs** — norāda vidējo laiku, kas ir nepieciešams OneNote, lai atrastu visus atbilstošo rezultātus.


#### <a name="officeonenotestickynotesnotecreated-on-ios-onenotestickynotesnotecreated-on-android"></a>Office.OneNote.StickyNotes.NoteCreated (iOS operētājsistēmā), OneNote.StickyNotes.NoteCreated (Android operētājsistēmā)

Šis ir kritisks signāls, kas tiek lietots, lai pārraudzītu līmpiezīmju lietotāju iespēju programmā izveidot piezīmes.  Telemetrija, kas tiek izmantota kritiskas regresijas atklāšanai OneNote lietojumprogrammā un pakalpojuma darbspējā. Ja lietotājiem neizdodas izveidot piezīmi, tā aktivizēs kritisku incidentu.

Tiek apkopoti šādi lauki:

- **NoteLocalId** — atšķirams unikāls identifikators, kas piešķirts piezīmei laikā, kad lietotājs izveido piezīmi programmā.

- **IsExportable** — karodziņš, kas norāda, vai šis notikums bija lietotāja darbības rezultāts. Jābūt iestatītam kā “True”, jo “NoteCreated” ir lietotāja izraisīta darbība.

- **StickyNotes-SDKVersion** — versijas numurs, kurā norādīta lietotāja izmantoto līmpiezīmju versija. Ļauj mums noteikt, kurās produkta versijās ir radusies problēma, lai mēs varētu pareizi noteikt tās prioritāti.


#### <a name="officeonenotestickynotesnoteviewed-on-ios-onenotestickynotesnoteviewed-on-android"></a>Office.OneNote.StickyNotes.NoteViewed (iOS operētājsistēmā), OneNote.StickyNotes.NoteViewed ( Android operētājsistēmā)

Šis ir kritisks signāls, kas tiek lietots, lai pārraudzītu līmpiezīmju lietotāju iespēju programmā izveidot piezīmes.  Telemetrija, kas tiek izmantota kritiskas regresijas atklāšanai OneNote lietojumprogrammā un pakalpojuma darbspējā. Ja lietotājiem neizdodas izveidot piezīmi, tā aktivizēs kritisku incidentu.

Tiek apkopoti šādi lauki:

- **HasImages** — karodziņš, kas norāda, vai skatītajā piezīmē ir saglabāti attēli.

- **IsExportable** — karodziņš, kas norāda, vai šis notikums bija lietotāja darbības rezultāts. Jābūt iestatītam kā “True”, jo “NoteViewed” ir lietotāja izraisīta darbība.

- **NoteLocalId** — atšķirams unikāls identifikators, kas piešķirts piezīmei laikā, kad lietotājs izveido piezīmi programmā.

- **StickyNotes-SDKVersion** — versijas numurs, kurā norādīta lietotāja izmantoto līmpiezīmju versija. Ļauj mums noteikt, kurās produkta versijās ir radusies problēma, lai mēs varētu pareizi noteikt tās prioritāti.


#### <a name="officeonenotestoragenotebooksyncresult"></a>Office.OneNote.Storage.NotebookSyncResult
 
Šis notikums reģistrē piezīmju grāmatiņas sinhronizācijas rezultātu. Tas tiek lietots, lai, aprēķinot OneNote sinhronizācijas vērtējumu, noteiktu, cik daudz ir unikālu sinhronizācijas mērķu.
 
Tiek apkopoti tālāk norādītie lauki

- **CachedError_Code** — ciparu vai burtciparu kods, kas tiek lietots, lai noteiktu kešatmiņā saglabātās kļūdas raksturu un/vai to, kāpēc tā radās.
    
- **CachedError_Description** — kešatmiņā saglabātās kļūdas apraksts.

- **CachedError_Tag** — norāda, kur kodā rodas kešatmiņā saglabātā kļūda.

- **CachedError_Type** — kešatmiņā saglabātās kļūdas tips, piemēram, Win32Error u. tml.

- **ExecutionTime** — laiks milisekundēs, kas bija nepieciešams, lai replicētu piezīmju grāmatiņu.

- **Gosid** — globālais objektu telpas ID.

- **IdentityType** — identitātes tips, piemēram, Windows Live, organizācijas ID utt.

- **InitialReplicationInSession** — norāda, vai šī replicēšana ir pirmā piezīmju grāmatiņas replicēšana pēc atvēršanas.

- **IsBackgroundSync** — norāda, vai tā ir fona sinhronizācija.

- **IsCachedErrorSuppressed** — norāda, vai kešatmiņā saglabātā kļūda tiek apspiesta.

- **IsCachedErrorUnexpected** — norāda, vai kešatmiņā saglabātā kļūda ir neparedzēta.

- **IsNotebookErrorSuppressed** — norāda, vai piezīmju grāmatiņas līmeņa sinhronizācijas kļūda tiek apspiesta.

- **IsNotebookErrorUnexpected** — norāda, vai piezīmju grāmatiņas līmeņa sinhronizācijas kļūda ir neparedzēta.

- **IsSectionErrorSuppressed** — norāda, vai sadaļu sinhronizācijas kļūdas tiek apspiestas.

- **IsSectionErrorUnexpected** — norāda, vai sadaļas sinhronizācijas kļūda bija paredzēta.

- **IsUsingRealtimeSync** — norāda, vai piezīmju grāmatiņas sinhronizēšana notiek, izmantojot moderno lapas satura sinhronizāciju.

- **LastAttemptedSync** — laikspiedols, kad piezīmju grāmatiņu tika mēģināts sinhronizēt iepriekšējo reizi.

- **LastBackgroundSync** — laikspiedols, kad notika pēdējais mēģinājums veikt sinhronizāciju fona režīmā.

- **LastNotebookViewedDate** — datums, kad piezīmju grāmatiņa pēdējoreiz tika skatīta.

- **LastSuccessfulSync** — laikspiedols, kad piezīmju grāmatiņa iepriekš sekmīgi sinhronizēta.

- **NeedToRestartBecauseOfInconsistencies** — norāda, vai sinhronizācija ir jārestartē, jo pastāv nekonsekvences.

- **NotebookErrorCode** — piezīmju grāmatiņas līmeņa sinhronizācijas kļūdas kods, kas saglabāts piezīmju grāmatiņas diagrammas apgabalā.

- **NotebookId** — piezīmju grāmatiņas ID.

- **NotebookType** — piezīmju grāmatiņas tips.

- **ReplicatingAgainBecauseOfInconsistencies** — norāda, vai sinhronizācija tiek restartēta nekonsekvenču dēļ.

- **SectionError_Code** — numurēts vai burtciparu kods, kas tiek lietots, lai noteiktu sadaļas sinhronizācijas kļūdas raksturu un/vai to, kāpēc tā radās.

- **SectionError_Description** — sadaļas sinhronizācijas kļūdas apraksts.

- **SectionError_Tag** — norāda, kur kodā rodas sadaļas sinhronizācijas kļūda.

- **SectionError_Type** — sadaļas sinhronizācijas kļūdas tips, piemēram, Win32Error u.tml.

- **Success** — norāda, vai piezīmju grāmatiņas sinhronizācija izdevās.

- **SyncDestinationType** — sinhronizācijas galamērķa tips, t.i., OneDrive vai SharePoint Online.

- **SyncId** — katrai piezīmju grāmatiņas sinhronizācijai unikāls numurs.

- **SyncWasFirstInSession** — norāda, vai šī ir pirmā sinhronizācija pašreizējā sesijā.

- **SyncWasUserInitiated** — norāda, vai šo sinhronizāciju uzsāka lietotājs.

- **TenantId** — SharePoint nomnieka ID.

- **TimeSinceLastAttemptedSync** — laiks, kas pagājis kopš pēdējā piezīmju grāmatiņas sinhronizācijas mēģinājuma.

- **TimeSinceLastSuccessfulSync** — laiks, kas pagājis kopš pēdējās sekmīgās piezīmju grāmatiņas sinhronizēšanas.


#### <a name="officeonenotesystemapplifecycleapplaunch"></a>Office.OneNote.System.AppLifeCycle.AppLaunch

Kritiskais signāls, kas tiek izmantots, lai OneNote lietotāji varētu veiksmīgi palaist lietojumprogrammu. Telemetrija, kas tiek izmantota kritiskas regresijas atklāšanai OneNote lietojumprogrammā un pakalpojuma darbspējā. Ja lietotājiem neizdodas palaist lietojumprogrammu mūsu veiktspējas logā, tiks aktivizēts kritiskais incidents.

Tiek apkopoti tālāk norādītie lauki:     Nav

#### <a name="officeoutlookdesktopaccountconfigurationcreateaccountresult"></a>Office.Outlook.Desktop.AccountConfiguration.CreateAccountResult

Tālāk norādītās darbības rezultāts: konta pievienošana programmai Outlook jaunā profilā, izmantojot Office Backstage vai konta iestatījumu dialoglodziņu. Dati tiek aktīvi pārraudzīti, lai nodrošinātu, ka kļūmju skaits nepalielinās. Mēs arī analizējam datus, lai atrastu jomas, kurās nepieciešami uzlabojumi. Mēs strādājam pie tā, lai uzlabotu panākumu rādītājus katrā laidienā.

Tiek apkopoti tālāk norādītie lauki.

  - **AccountCreationResult** — rezultāts (izdošanās, neizdošanās, atcelšana u.c.) šim: konta pievienošana programmai Outlook.

  - **AccountCreationTime** — laiks, kas tika patērēts, veidojot kontu

  - **AccountInfoSource** — konta iestatījumu avots (piemēram, automātiskā atklāšana, GuessSmart, automātiskā noteikšana utt.)

  - **AccountType** — konfigurējamā konta tips

  - **HashedEmailAddress** — jaukšanas e-pasta adrese

  - **ShowPasswordPageFlightEnabled** — indikators, kas norāda, vai ir iespējots testējamais variants ShowPopImapPasswordPage

#### <a name="officeoutlookdesktopaccountconfigurationrepairaccountresult"></a>Office.Outlook.Desktop.AccountConfiguration.RepairAccountResult

Rezultāts šim: konta labošana vai papildu konta iestatījumu maiņa. Dati tiek aktīvi pārraudzīti, lai nodrošinātu, ka kļūmju skaits nepalielinās. Mēs arī analizējam datus, lai atrastu jomas, kurās nepieciešami uzlabojumi. Tā kā šīs ir jaunas (pārstrukturētas) iespējas, mēs vēlamies būt droši, ka esam visu izdarījuši pareizi.

Tiek apkopoti tālāk norādītie lauki.

  - **AccountInfoSource** — konta informācijas avots kontam, kam tiek veikti labojumi

  - **AccountType** — tāda konta tips, kam tika veikti labojumi

  - **HashedEmailAddress** — jaukšanas e-pasta adrese

  - **ManualRepairRequested** — indikators, kas norāda, vai tika pieprasīta manuāla labošana

  - **Result** — konta labošanas mēģinājuma rezultāts Piemēram: "Success" vai "Fail\_SaveChangesToAccount"

#### <a name="officeoutlookdesktopaccountconfigurationupdatepasswordresult"></a>Office.Outlook.Desktop.AccountConfiguration.UpdatePasswordResult

Rezultāts šim: konta paroles atjaunināšana konta iestatījumu nolaižamajā sarakstā. Dati tiek aktīvi pārraudzīti, lai nodrošinātu, ka kļūmju skaits nepalielinās. Mēs arī analizējam datus, lai atrastu jomas, kurās nepieciešami uzlabojumi. Tā kā šīs ir jaunas (pārstrukturētas) iespējas, mēs vēlamies būt droši, ka esam visu izdarījuši pareizi.

Tiek apkopoti tālāk norādītie lauki.

  - **AccountType** — tāda konta tips, kam tika veikta paroles atjaunināšana

  - **HashedEmailAddress** — jaukšanas e-pasta adrese

  - **Result** — paroles atjaunināšanas mēģinājuma rezultāts Piemēram: "Success" vai "Fail\_AllowLessSecureAppsDisabled"


#### <a name="officeoutlookdesktopstorescreatenewstore"></a>Office.Outlook.Desktop.Stores.CreateNewStore

Apkopo rezultātus šim: jaunas krātuves izveide (ar tipu un versiju), kā arī rezultātu kodu. Mēs aktīvi pārraugām šo notikumu, lai izsekotu darbspējai, lietotāja spējai lokāli sinhronizēt pastu, arhivēt pastu (PST) vai izmantot grupas.

Tiek apkopoti šādi lauki:

  - **Standarta HVA darbība** ar lietderīgajiem datiem, kas ir pielāgoti

  - **StoreType** — izveidotās krātuves tips (OST/PST/NST)

  - **StoreVersion** — izveidotās krātuves versija (Small/Large/Tardis)

#### <a name="officeoutlookmacaccountaddworkflow"></a>Office.Outlook.Mac.AccountAddWorkflow

Konta pievienošanas Outlook programmā rezultāts. Dati tiek uzraudzīti, lai nodrošinātu, ka kļūmju skaits nepalielinās. Mēs arī analizējam datus, lai atrastu jomas, kurās nepieciešami uzlabojumi. Mēs strādājam pie tā, lai uzlabotu panākumu rādītājus katrā laidienā. 

Tiek apkopoti tālāk norādītie lauki.

- **AccountConfigMethod** — konta konfigurācijas metode.

- **AccountType** — konfigurējamā konta veids.

- **AccountWorkflowSession** — sesija, kurā mēģināts izveidot konta darbplūsmu.

- **SessionDuration** — sesijas ilgums. 

- **ThreadId** — pavediena identifikators.


#### <a name="officeoutlookmacaccountonboardingflow"></a>Office.Outlook.Mac.AccountOnboardingFlow

Konta pievienošanas Outlook programmā rezultāts, izmantojot jauna konta konfigurēšanas pieredzi. Dati tiek uzraudzīti, lai nodrošinātu, ka kļūmju skaits nepalielinās. Mēs arī analizējam datus, lai atrastu jomas, kurās nepieciešami uzlabojumi. Mēs strādājam pie tā, lai uzlabotu panākumu rādītājus katrā laidienā. 

Tiek apkopoti šādi lauki:

- **AccountConfigAutoSignIn** — administratora iestatītā automātiskā konfigurācija.

- **AccountConfigDomain** — konta konfigurēšanas lakā norādītais domēns. 

- **AccountConfigEntryPoint** — sākumpunkts, kurā lietotājs ievadīja konta konfigurāciju. 

- **AccountConfigErrorCode** — konta konfigurēšanas laikā notikušās kļūdas kods. 

- **AccountConfigErrorString** — konta konfigurēšanas laikā notikušās kļūdas kods.

- **AccountConfigMethod** — konta konfigurēšanas metode.

- **AccountConfigPhase** — pašreizējais konta konfigurēšanas darbplūsmas solis.

- **AccountConfigPhaseFrom** — konta konfigurēšanas darbplūsmas sākuma solis. 

- **AccountConfigPhaseTo** — konta konfigurēšanas darbplūsmas pēdējais solis. 

- **AccountType** — konfigurējamā konta veids.

- **AccountWorkflowSession** — sesija, kurā mēģināts izveidot konta darbplūsmu.

- **SessionDuration** — sesijas ilgums.


#### <a name="officeoutlookmacdeleteaccountusage"></a>Office.Outlook.Mac.DeleteAccountUsage

Konta dzēšanas Outlook programmā rezultāts. Dati tiek uzraudzīti, lai nodrošinātu, ka kļūmju skaits nepalielinās. Mēs arī analizējam datus, lai atrastu jomas, kurās nepieciešami uzlabojumi. Mēs strādājam pie tā, lai uzlabotu panākumu rādītājus katrā laidienā. 

Tiek apkopoti tālāk norādītie lauki.

- **AccountType** — konfigurējamā konta veids.

- **AccountID** — konta identifikators.

- **DeprovisionAccount** — norāda, vai konts ir noņemts no servera.

- **IsFastDelete** — norāda, vai konts ir dzēsts fona pavedienā.

#### <a name="officepowerpointdocoperationclose"></a>Office.PowerPoint.DocOperation.Close

Apkopo, kad ir aizvērtas PowerPoint prezentācijas. Tas satur informāciju, kas ir nepieciešama pareizai tādu problēmu izmeklēšanai un diagnosticēšanai, kas notiek, izmantojot aizvēršanas procesu, kas ietver lietotāja datu turpināšanu un sinhronizēšanu. Microsoft izmanto šos datus, lai nodrošinātu, ka aizvēršana darbojas, kā paredzēts, un lietotāju saturs tiek sekmīgi turpināts.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_AddDocTelemetryResult:long —** vai šim žurnāla ierakstam ir visa nepieciešamā dokumenta telemetrija (Data\_Doc\_\* lauki)? Ja tā nav, kāpēc?

  - **Data\_AutoSaveDisabledReasons:string —** vai pastāv iepriekš noteiktu vērtību kopa, kas norāda, kāpēc dokumentā tika atspējota automātiskā saglabāšana? (Sapludināšanas kļūda, saglabāšanas kļūda, grupas politika utt.)

  - **Data\_CloseReason:long -** Kā tika veikta aizvēršana? Aizverot dokumentu? Aizverot programmu?

  - **Data\_CppUncaughtExceptionCount:long —** neapstrādāto izņēmumu skaits

  - **Data\_DetachedDuration:long —** darbības atvienošanas/nedarbošanās ilgums

  - **Data\_Doc\_AccessMode:long —** kā šis dokuments ir atvērts (tikai lasāms | lasīšana un rakstīšana)

  - **Data\_Doc\_AssistedReadingReasons:long —** iepriekš definētu vērtību kopa, kas norāda, kāpēc dokuments ir atvērts pieejamā lasīšanas režīmā

  - **Data_Doc_AsyncOpenKind:long — ** norāda, vai tika atvērta mākoņa dokumenta kešotā versijā un kura asinhronā atsvaidzināšanas loģika tika izmantota.

  - **Data\_Doc\_ChunkingType:long —** kā dokuments ir saglabāts pakalpojumā SharePoint

  - **Data\_Doc\_EdpState:long —** dokumenta uzņēmuma datu aizsardzība statuss

  - **Data\_Doc\_Ext:string —** dokumenta paplašinājums

  - **Data\_Doc\_Extension:string —** dokumenta paplašinājums

  - **Data\_Doc\_FileFormat:long —** iepriekš definētu faila formāta vērtību kopa (detalizētāka par paplašinājumu).

  - **Data\_Doc\_Fqdn:string —** dokumentu glabāšanas vieta (SharePoint.com, live.net), pieejama tikai Office 365 domēniem

  - **Data\_Doc\_FqdnHash:string —** dokumenta glabāšanas vietas jaukšana

  - **Data\_Doc\_IdentityTelemetryId:string —** unikāls lietotāja GUID

  - **Data\_Doc\_IdentityUniqueId:string —** tās identitātes unikālais identifikators, kas tika izmantota koplietojamo dokumentu darbībai

  - **Data\_Doc\_IOFlags:long —** bitmaska dažādiem ar IO saistītiem karodziņiem, kas attiecas uz dokumentu

  - **Data\_Doc\_IrmRights:long —** iepriekš definētu vērtību kopa, kas attiecas uz informācijas piekļuves tiesību pārvaldības tipu, kas tiek lietots šim dokumentam (pārsūtīšana, atbildēšana, SecureReader, rediģēšana u.c.)

  - **Data\_Doc\_IsCloudCollabEnabled:bool —** patiess, ja "IsCloudCollabEnabled" HTTP galvene jau ir saņemta no pieprasījuma OPTIONS.

  - **Data\_Doc\_IsIncrementalOpen:bool —** vai dokuments tika atvērts inkrementāli (jauns līdzeklis, kas atver dokumentu bez vajadzības lejupielādēt visu dokumentu)

  - **Data\_Doc\_IsOcsSupported:bool —** vai ir dokuments atbalsta koprediģēšanu, izmantojot jauno OCS pakalpojumu

  - **Data\_Doc\_IsOpeningOfflineCopy:bool —** pārbauda, vai dokuments tiek atvērts no lokālās kešatmiņas

  - **Data\_Doc\_IsSyncBacked:bool —** pārbauda, vai ja dokuments tiek atvērts no mapes, kas izmanto OneDrive sinhronizācijas programmu

  - **Data\_Doc\_Location:long —** iepriekš definētu vērtību kopa, kas norāda dokumenta glabāšanas vietu (lokālā, SharePoint, WOPI, tīkls utt.)

  - **Data\_Doc\_LocationDetails:long —** iepriekš definētu detalizētākas atrašanās vietas vērtību kopa (mape Temp, lejupielāžu mape, OneDrive dokumenti, OneDrive attēli utt.)

  - **Data\_Doc\_NumberCoAuthors:long —** līdzautoru skaits dokumenta atvēršanas brīdī

  - **Data\_Doc\_PasswordFlags:long —** iepriekš definētu vērtību kopa, kas norāda veidu, kā dokuments ir šifrēts ar paroli (nav, parole lasīšanai, parole rediģēšanai)

  - **Data\_Doc\_ReadOnlyReasons:long —** iepriekš definētu vērtību kopa, kas norāda, kāpēc šis dokuments ir atzīmēts kā tikai lasāms (bloķēts serverī, pabeigts dokuments, aizsargāts ar paroli rediģēšanai utt.)

  - **Data\_Doc\_ResourceIdHash:string —** resursu identifikatora jaukšana mākonī saglabātajiem dokumentiem

  - **Data_Doc_RtcType —** norāda, kā reāllaika kanāls (RTC) bija iestatīts pašreizējam failam (atspējots, neatbalstīts, pēc pieprasījuma, vienmēr ieslēgts utt.).

  - **Data\_Doc\_ServerDocId:string —** nemainīgs identifikators mākonī saglabātajiem dokumentiem

  - **Data\_Doc\_ServerProtocol:long —** iepriekš definētu vērtību kopa, kas norāda, kurš protokols tiek izmantots, lai sazinātos ar serveri (HTTP, Cobalt, WOPI utt.)

  - **Data\_Doc\_ServerType:long —** iepriekš definētu vērtību kopas servera tipam (SharePoint, DropBox, WOPI)

  - **Data\_Doc\_ServerVersion:long —** pārbauda, vai servera pamatā ir Office14, Office15 vai Office 16

  - **Data\_Doc\_SessionId:long —** ģenerēts GUID, kas norāda dokumenta instanci tajā pašā procesa sesijā

  - **Data\_Doc\_SharePointServiceContext:string —** necaurspīdīga virkne, parasti GridManagerID.FarmID. Noder, lai saistītu klienta un servera žurnālu

  - **Data\_Doc\_SizeInBytes:long —** dokumenta lielums baitos

  - **Data\_Doc\_SpecialChars:long —** bitmaska, kas norāda speciālās rakstzīmes dokumenta vietrādī URL vai ceļā

  - **Data\_Doc\_StorageProviderId:string —** virkne, kas norāda dokumenta krātuves nodrošinātāju, piemēram, "DropBox"

  - **Data\_Doc\_StreamAvailability:long —** iepriekš definētu dokumenta straumēšanas vērtību kopas statuss (pieejams, neatgriezeniski atspējots, nav pieejams)

  - **Data\_Doc\_UrlHash:string —** pilna vietrāža URL jaukšana mākonī saglabātiem dokumentiem

  - **Data\_Doc\_UsedWrsDataOnOpen:bool —** patiess, ja fails tika atvērts inkrementāli, izmantojot iepriekš kešotus WRS datus resursdatorā

  - **Data\_Doc\_WopiServiceId:string —** WOPI pakalpojuma identifikators, piemēram, "Dropbox"

  - **Data\_DocHasStorage:bool —** vai šim dokumentam ir lokālā krātuve?

  - **Data\_fLifeguarded:bool —** vai dokuments kādreiz ir bijis aizsargāts (līdzeklis, lai izlabotu dokumenta kļūdas, neziņojot par to lietotājam)?

  - **Data\_IsDocAutoSaveable:bool —** vai prezentāciju var saglabāt automātiski?

  - **Data\_IsDocDirty:bool —** vai prezentācijā ir izmaiņas, kas vēl nav saglabātas?

  - **Data\_IsNewDoc:bool —** vai dokument jau pastāv vai ir jauns

  - **Data\_IsRecoveredDoc:bool —** vai dokuments ir atkopts? (Ja iepriekšējā sesija avarēja, mēs parādām dokumentu atkopšanas rūtī nākamajā sesijā)

  - **Data\_NewDocDiscarded:bool —** vai jaunā prezentācija tika atmesta, nesaglabājot izmaiņas

  - **Data\_OCSClosingDlgCanceled:bool —** ja augšupielāde gaida serverī OCS, kamēr lietotājs aizver dokumentu, tiek parādīts dialoglodziņš ar aicinājumu uzgaidīt Kādu opciju izvēlējās lietotājs?

  - **Data\_OCSClosingDlgExpired:bool —** vai dialoglodziņš aizvērās pats (pēc 1 minūtes)?

  - **Data\_OCSClosingStatus:long —** kāds ir OCS pēdējais statuss (CSI, aizverams, OCS pārejā, CSI pārejā utt.)

  - **Data\_OCSClosingWaitDurationMS:long —** cik ilgi lietotājam bija jāgaida līdz OCS augšupielādei

  - **Data\_OCSHandleTransitionResult:long —** iepriekš definētu vērtību kopa, kas norāda rezultātu šim: aizvēršanas laikā veikta pāreja (jau mēģināta, turpina aizvērt utt.)

  - **Data\_ServerDocId:string —** GUID unikālai dokumenta identificēšanai

  - **Data\_StopwatchDuration:long —** kopējais darbības ilgums

  - **Data\_UserContinuedZRTClose:bool —** vai, aizverot dokumentu, lietotājs izvēlējās "Turpināt", lai aizvērtu?

#### <a name="officepowerpointdocoperationnewdocument"></a>Office.PowerPoint.DocOperation.NewDocument

Apkopo, kad PowerPoint izveido jaunu prezentāciju. Ietver panākumus un veiktspējas rādītājus.

Šī informācija tiek izmantota, lai mēs varētu sekmīgi izveidot failus, nepasliktinot veiktspēju.

Tiek apkopoti tālāk norādītie lauki.

  - **NewDocumentType** — vai jaunais dokuments ir izveidots no veidnes vai vienkārši izveidots tukšs?

  - **FLifeguarded** — vai dokuments ir aizsargāts (līdzeklis, kas atjauno bojāta dokumenta statusu, nepaziņojot par to lietotājam)

#### <a name="officepowerpointdocoperationopencompleteprotocol"></a>Office.PowerPoint.DocOperation.OpenCompleteProtocol

Apkopo, kad PowerPoint atver prezentācijas. Tas satur informāciju, kas ir nepieciešama pareizai tādu problēmu izmeklēšanai un diagnosticēšanai, kas notiek pēdējos atvēršanas procesa posmos.

Microsoft izmanto šos datus, lai nodrošinātu līdzekļa pareizu darbību un neietekmētu prezentāciju atvēršanu.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_AntiVirusScanMethod:long —** iepriekš definētu vērtību kopa pretvīrusu programmatūras skenēšanas tipam (IOAV, AMSI, nav utt.)

  - **Data\_AntiVirusScanStatus:long —** iepriekš definētu vērtību kopa pretvīrusu programmatūras skenēšanai, kas tiek veikta katram atvērtajam dokumentam (NoThreatsDetected, neizdevās, MalwareDetected utt.)

  - **Data\_CloseAndReopen:bool —** vai dokuments tika aizvērts un atkārtoti atvērts?

  - **Data\_DetachedDuration:long —** darbības atvienošanas/nedarbošanās ilgums

  - **Data\_Doc\_AccessMode:long —** kā šis dokuments ir atvērts (tikai lasāms | lasīšana un rakstīšana)

  - **Data\_Doc\_AssistedReadingReasons:long —** iepriekš definētu vērtību kopa, kas norāda, kāpēc dokuments ir atvērts pieejamā lasīšanas režīmā

  - **Data_Doc_AsyncOpenKind:long — ** norāda, vai tika atvērta mākoņa dokumenta kešotā versijā un kura asinhronā atsvaidzināšanas loģika tika izmantota.

  - **Data\_Doc\_ChunkingType:long —** kā dokuments ir saglabāts pakalpojumā SharePoint

  - **Data\_Doc\_EdpState:long —** dokumenta uzņēmuma datu aizsardzība statuss

  - **Data\_Doc\_Ext:string —** dokumenta paplašinājums

  - **Data\_Doc\_Extension:string —** dokumenta paplašinājums

  - **Data\_Doc\_FileFormat:long —** iepriekš definētu faila formāta vērtību kopa (detalizētāka par paplašinājumu).

  - **Data\_Doc\_Fqdn:string —** dokumentu glabāšanas vieta (SharePoint.com, live.net), pieejama tikai Office 365 domēniem

  - **Data\_Doc\_FqdnHash:string —** dokumenta glabāšanas vietas jaukšana

  - **Data\_Doc\_IdentityTelemetryId:string —** unikāls lietotāja GUID

  - **Data\_Doc\_IdentityUniqueId:string —** tās identitātes unikālais identifikators, kas tika izmantota koplietojamo dokumentu darbībai

  - **Data\_Doc\_IOFlags:long —** bitmaska dažādiem ar IO saistītiem karodziņiem, kas attiecas uz dokumentu

  - **Data\_Doc\_IrmRights:long —** iepriekš definētu vērtību kopa, kas attiecas uz informācijas piekļuves tiesību pārvaldības tipu, kas tiek lietots šim dokumentam (pārsūtīšana, atbildēšana, SecureReader, rediģēšana u.c.)

  - **Data\_Doc\_IsCloudCollabEnabled:bool —** patiess, ja "IsCloudCollabEnabled" HTTP galvene jau ir saņemta no pieprasījuma OPTIONS.

  - **Data\_Doc\_IsIncrementalOpen:bool —** vai dokuments tika atvērts inkrementāli (jauns līdzeklis, kas atver dokumentu bez vajadzības lejupielādēt visu dokumentu)

  - **Data\_Doc\_IsOcsSupported:bool —** vai ir dokuments atbalsta koprediģēšanu, izmantojot jauno OCS pakalpojumu

  - **Data\_Doc\_IsOpeningOfflineCopy:bool —** vai dokuments tiek atvērts no lokālās kešatmiņas?

  - **Data\_Doc\_IsSyncBacked:bool —** vai dokuments tiek atvērts no mapes, kas izmanto OneDrive sinhronizācijas programmu

  - **Data\_Doc\_Location:long —** iepriekš definētu vērtību kopa, kas norāda dokumenta glabāšanas vietu (lokālā, SharePoint, WOPI, tīkls utt.)

  - **Data\_Doc\_LocationDetails:long —** iepriekš definētu detalizētākas atrašanās vietas vērtību kopa (mape Temp, lejupielāžu mape, OneDrive dokumenti, OneDrive attēli utt.)

  - **Data\_Doc\_NumberCoAuthors:long —** līdzautoru skaits dokumenta atvēršanas brīdī

  - **Data\_Doc\_PasswordFlags:long —** iepriekš definētu vērtību kopa, kas norāda veidu, kā dokuments ir šifrēts ar paroli (nav, parole lasīšanai, parole rediģēšanai)

  - **Data\_Doc\_ReadOnlyReasons:long —** iepriekš definētu vērtību kopa, kas norāda, kāpēc šis dokuments ir atzīmēts kā tikai lasāms (bloķēts serverī, pabeigts dokuments, aizsargāts ar paroli rediģēšanai utt.)

  - **Data\_Doc\_ResourceIdHash:string —** resursu identifikatora jaukšana mākonī saglabātajiem dokumentiem

  - **Data_Doc_RtcType —** norāda, kā reāllaika kanāls (RTC) bija iestatīts pašreizējam failam (atspējots, neatbalstīts, pēc pieprasījuma, vienmēr ieslēgts utt.).

  - **Data\_Doc\_ServerDocId:string —** nemainīgs identifikators mākonī saglabātajiem dokumentiem

  - **Data\_Doc\_ServerProtocol:long —** iepriekš definētu vērtību kopa, kas norāda, kurš protokols tiek izmantots, lai sazinātos ar serveri (HTTP, Cobalt, WOPI utt.)

  - **Data\_Doc\_ServerType:long —** iepriekš definētu vērtību kopas servera tipam (SharePoint, DropBox, WOPI)

  - **Data\_Doc\_ServerVersion:long —** pārbauda, vai servera pamatā ir Office14, Office15 vai Office 16

  - **Data\_Doc\_SessionId:long —** ģenerēts GUID, kas norāda dokumenta instanci tajā pašā procesa sesijā

  - **Data\_Doc\_SharePointServiceContext:string —** necaurspīdīga virkne, parasti GridManagerID.FarmID. Noder, lai saistītu klienta un servera žurnālu

  - **Data\_Doc\_SizeInBytes:long —** dokumenta lielums baitos

  - **Data\_Doc\_SpecialChars:long —** bitmaska, kas norāda speciālās rakstzīmes dokumenta vietrādī URL vai ceļā

  - **Data\_Doc\_StorageProviderId:string —** virkne, kas norāda dokumenta krātuves nodrošinātāju, piemēram, "DropBox"

  - **Data\_Doc\_StreamAvailability:long —** iepriekš definētu dokumenta straumēšanas vērtību kopas statuss (pieejams, neatgriezeniski atspējots, nav pieejams)

  - **Data\_Doc\_UrlHash:string —** pilna vietrāža URL jaukšana mākonī saglabātiem dokumentiem

  - **Data\_Doc\_UsedWrsDataOnOpen:bool —** patiess, ja fails tika atvērts inkrementāli, izmantojot iepriekš kešotus WRS datus resursdatorā

  - **Data\_Doc\_WopiServiceId:string —** WOPI pakalpojuma identifikators, piemēram, "Dropbox"

  - **Data\_ExecutionCount:long —** cik reižu mēs izpildījām IncOpen protokolu pirms šī protokola (OpenComplete) izpildes

  - **Data\_FailureComponent:long —** iepriekš definētu vērtību kopa, kas norāda, kurš komponents izraisīja protokola kļūmi (konflikts, CSI, iekšējais utt).

  - **Data\_FailureReason:long —** iepriekš definētu vērtību kopa, kas norāda kļūmes iemeslu (FileIsCorrupt, BlockedByAntivirus u.c.)

  - **Data_FullDownloadRoundTripCount:long —** to vēršanās pie servera ciklu skaits, kas bija nepieciešams, lai lejupielādētu visu dokumentu.
  
  - **Data_IsProtocolRunInIncOpenMode:bool —** bija protokola darbība inkrementālai lejupielādei, kas ir tāda lejupielāde, kurā dokumenta daļas tika lejupielādētas pēc dokumenta sākotnējās parādīšanas lietotājam.

  - **Data\_MethodId:long —** kura kodu rinda bija iekšēji jāizpilda pēdējā

  - **Data\_StopwatchDuration:long —** kopējais darbības ilgums

  - **Data\_TimeToEdit:long —** cik ilgā laikā dokuments kļuva rediģējams

  - **Data\_TimeToView:long —** cik ilgā laikā tika atveidots pirmais dokumenta slaids

  - **Data\_UnhandledException:bool —** vai pastāv kāds neapstrādāts vietējais izņēmums?

#### <a name="officepowerpointdocoperationsave"></a>Office.PowerPoint.DocOperation.Save

Apkopots ikreiz, kad PowerPoint veic saglabāšanu, izmantojot modernu koda ceļu. Ietver saglabāšanas veiktspējas rādītāju rezultātu tipa panākumus un saistītos dokumenta metadatus.  Saglabāšanas kļūmes var izraisīt datu zudumu. Microsoft izmanto šos datus, lai nodrošinātu, ka līdzeklis darbojas, kā paredzēts, un lietotāju saturs tiek sekmīgi turpināts.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_AddDocTelemetryResult:long —** vai šim žurnāla ierakstam ir visa nepieciešamā dokumenta telemetrija (Data\_Doc\_\* lauki)? Ja tā nav, kāpēc?

  - **Data\_BeforeSaveEvent:long —** cik ilgā laikā tika ģenerēts dokuments pirms saglabāšanas notikuma

  - **Data\_CheckDownRevSaveTimeMS:long —** cik ilga laikā tika pārbaudīta pārskatīšana

  - **Data\_CheckMacroSaveTimeMS:long —** cik ilga laikā tika saglabāts makro

  - **Data\_ClearAutoSaveTimeMS:long —** cik ilgā laikā tika noņemts automātiskās saglabāšanas karodziņš

  - **Data\_ClearDirtyFlagTimeMS:long —** cik ilgā laikā tika noņemts mainīta dokumenta karodziņš

  - **Data\_CloneDocumentTimeMS:long —** cik ilgā laikā tika klonēts dokuments pirms saglabāšanas

  - **Data\_CommitTransactionTimeMS:long —** cik ilgā laikā tika izpildīta saglabāšanas darbība

  - **Data\_CppUncaughtExceptionCount:long —** nenotverti vietējie izņēmumi darbības izpildes laikā

  - **Data\_DetachedDuration:long —** darbības atvienošanas/nedarbošanās ilgums

  - **Data\_Doc\_AccessMode:long —** kā šis dokuments ir atvērts (tikai lasāms | lasīšana un rakstīšana)

  - **Data\_Doc\_AssistedReadingReasons:long —** iepriekš definētu vērtību kopa, kas norāda, kāpēc dokuments ir atvērts pieejamā lasīšanas režīmā

  - **Data_Doc_AsyncOpenKind:long — ** norāda, vai tika atvērta mākoņa dokumenta kešotā versijā un kura asinhronā atsvaidzināšanas loģika tika izmantota.

  - **Data\_Doc\_ChunkingType:long —** kā dokuments ir saglabāts pakalpojumā SharePoint

  - **Data\_Doc\_EdpState:long —** dokumenta uzņēmuma datu aizsardzība statuss

  - **Data\_Doc\_Ext:string —** dokumenta paplašinājums

  - **Data\_Doc\_Extension:string —** dokumenta paplašinājums

  - **Data\_Doc\_FileFormat:long —** iepriekš definētu faila formāta vērtību kopa (detalizētāka par paplašinājumu).

  - **Data\_Doc\_Fqdn:string —** dokumentu glabāšanas vieta (SharePoint.com, live.net), pieejama tikai Office 365 domēniem

  - **Data\_Doc\_FqdnHash:string —** dokumenta glabāšanas vietas jaukšana

  - **Data\_Doc\_IdentityTelemetryId:string —** unikāls lietotāja GUID

  - **Data\_Doc\_IdentityUniqueId:string —** tās identitātes unikālais identifikators, kas tika izmantota koplietojamo dokumentu darbībai

  - **Data\_Doc\_IOFlags:long —** bitmaska dažādiem ar IO saistītiem karodziņiem, kas attiecas uz dokumentu

  - **Data\_Doc\_IrmRights:long —** iepriekš definētu vērtību kopa, kas attiecas uz informācijas piekļuves tiesību pārvaldības tipu, kas tiek lietots šim dokumentam (pārsūtīšana, atbildēšana, SecureReader, rediģēšana u.c.)

  - **Data\_Doc\_IsCloudCollabEnabled:bool —** patiess, ja "IsCloudCollabEnabled" HTTP galvene jau ir saņemta no pieprasījuma OPTIONS.

  - **Data\_Doc\_IsIncrementalOpen:bool —** vai dokuments tika atvērts inkrementāli (jauns līdzeklis, kas atver dokumentu bez vajadzības lejupielādēt visu dokumentu)

  - **Data\_Doc\_IsOcsSupported:bool —** vai ir dokuments atbalsta koprediģēšanu, izmantojot jauno OCS pakalpojumu

  - **Data\_Doc\_IsOpeningOfflineCopy:bool —** pārbauda, vai dokuments tiek atvērts no lokālās kešatmiņas

  - **Data\_Doc\_IsSyncBacked:bool —** vai dokuments tiek atvērts no mapes, kas izmanto OneDrive sinhronizācijas programmu

  - **Data\_Doc\_Location:long —** iepriekš definētu vērtību kopa, kas norāda dokumenta glabāšanas vietu (lokālā, SharePoint, WOPI, tīkls utt.)

  - **Data\_Doc\_LocationDetails:long —** iepriekš definētu detalizētākas atrašanās vietas vērtību kopa (mape Temp, lejupielāžu mape, OneDrive dokumenti, OneDrive attēli utt.)

  - **Data\_Doc\_NumberCoAuthors:long —** līdzautoru skaits dokumenta atvēršanas brīdī

  - **Data\_Doc\_PasswordFlags:long —** iepriekš definētu vērtību kopa, kas norāda veidu, kā dokuments ir šifrēts ar paroli (nav, parole lasīšanai, parole rediģēšanai)

  - **Data\_Doc\_ReadOnlyReasons:long —** iepriekš definētu vērtību kopa, kas norāda, kāpēc šis dokuments ir atzīmēts kā tikai lasāms (bloķēts serverī, pabeigts dokuments, aizsargāts ar paroli rediģēšanai utt.)

  - **Data\_Doc\_ResourceIdHash:string —** resursu identifikatora jaukšana mākonī saglabātajiem dokumentiem

  - **Data_Doc_RtcType —** norāda, kā reāllaika kanāls (RTC) bija iestatīts pašreizējam failam (atspējots, neatbalstīts, pēc pieprasījuma, vienmēr ieslēgts utt.).

  - **Data\_Doc\_ServerDocId:string —** nemainīgs identifikators mākonī saglabātajiem dokumentiem

  - **Data\_Doc\_ServerProtocol:long —** iepriekš definētu vērtību kopa, kas norāda, kurš protokols tiek izmantots, lai sazinātos ar serveri (HTTP, Cobalt, WOPI utt.)

  - **Data\_Doc\_ServerType:long —** iepriekš definētu vērtību kopas servera tipam (SharePoint, DropBox, WOPI)

  - **Data\_Doc\_ServerVersion:long —** pārbauda, vai servera pamatā ir Office14, Office15 vai Office 16

  - **Data\_Doc\_SessionId:long —** ģenerēts GUID, kas norāda dokumenta instanci tajā pašā procesa sesijā

  - **Data\_Doc\_SharePointServiceContext:string —** necaurspīdīga virkne, parasti GridManagerID.FarmID. Noder, lai saistītu klienta un servera žurnālu

  - **Data\_Doc\_SizeInBytes:long —** dokumenta lielums baitos

  - **Data\_Doc\_SpecialChars:long —** bitmaska, kas norāda speciālās rakstzīmes dokumenta vietrādī URL vai ceļā

  - **Data\_Doc\_StorageProviderId:string —** virkne, kas norāda dokumenta krātuves nodrošinātāju, piemēram, "DropBox"

  - **Data\_Doc\_StreamAvailability:long —** iepriekš definētu dokumenta straumēšanas vērtību kopas statuss (pieejams, neatgriezeniski atspējots, nav pieejams)

  - **Data\_Doc\_UrlHash:string —** pilna vietrāža URL jaukšana mākonī saglabātiem dokumentiem

  - **Data\_Doc\_UsedWrsDataOnOpen:bool —** patiess, ja fails tika atvērts inkrementāli, izmantojot iepriekš kešotus WRS datus resursdatorā

  - **Data\_Doc\_WopiServiceId:string —** WOPI pakalpojuma identifikators, piemēram, "Dropbox"

  - **Data\_DurationUAEOnSaveStartedMs:long —** cik ilgā laikā tika iziets no nezināmas programmas saglabāšanas laikā

  - **Data\_EnsureSaveTransactionTimeMS:long —** cik ilgā laikā tika nodrošināta saglabāšanas darbības izveide, ja tā vēl nebija pieejama

  - **Data\_FailureComponent:long —** iepriekš definētu vērtību kopa, kas norāda, kurš komponents izraisīja protokola kļūmi (konflikts, CSI, iekšējais utt).

  - **Data\_FailureReason:long —** iepriekš definētu vērtību kopa, kas norāda kļūmes iemeslu (FileIsCorrupt, BlockedByAntivirus u.c.)

  - **Data\_fLifeguarded:bool —** vai dokuments kādreiz ir bijis aizsargāts (līdzeklis, lai izlabotu dokumenta kļūdas, neziņojot par to lietotājam)?

  - **Data\_HandleEnsureContentType:long —** cik ilgā laikā tika nodrošināta visu satura tipu pareizība

  - **Data\_HandleEnsureContentTypeTimeMS:long —** cik ilgā laikā tika nodrošināta visu satura tipu pareizība

  - **Data\_HasEmbeddedFont:bool —** vai šim dokumentam ir iegulti fonti?

  - **Data\_InitializeSaveTimeMS:long —** cik ilgā laikā tika inicializēts dokumenta saturs pirms saglabāšanas

  - **Data\_InOCSTransition:bool —** vai saglabāšana tiek veikta pārejai uz OCS

  - **Data\_IsSavingWithEmbeddedFont:bool —** vai šim dokumentam ir iegulti fonti?

  - **Data\_MethodId:long —** kura kodu rinda bija iekšēji jāizpilda pēdējā

  - **Data\_PerformEmbedFontsTimeMS:long —** cik ilgā laikā tika serializēti iegultie fonti

  - **Data\_PerformModernSaveTimeMS:long —** cik ilgā laikā tika veikta modernā saglabāšana (jauns kods)

  - **Data\_PerformPostSaveTimeMS:long —** cik ilgā laikā tika veiktas pēcsaglabāšanas funkcijas (paziņojumi, ierakstu atsaukšana)

  - **Data\_PrepareForSaveTimeMS:long —** cik ilgā laikā tika sākta saglabāšana

  - **Data\_RaiseDocumentBeforeSaveEventTimeMS:long —** cik ilgā laikā tika ģenerēts notikums BeforeSave

  - **Data\_ReflectDocumentChangeTimeMS:long —** cik ilgā laikā tika atspoguļotas lietotāja interfeisā saglabātās izmaiņas (sīktēlu aizpildīšana utt.)

  - **Data\_ReportStartTimeMS:long —** cik ilgā laikā tika pabeigta saglabāšanai inicializētā telemetrija

  - **Data\_ReportSuccessTimeMS:long —** cik ilgā laikā tika pabeigta sekmīgas saglabāšanas atskaite

  - **Data\_ResetDirtyFlagOnErrorTimeMS:long —** cik ilgā laikā tika atiestatīts mainītā dokumenta karodziņš kļūdai

  - **Data\_SaveReason:long —** iepriekš definētu vērtību kopa, kas norāda, kāpēc tika veikta saglabāšana (Automātiskā saglabāšana, ToOCSTransitionSave, ToCSITransitionSave utt.)

  - **Data\_SaveType:long —** iepriekš definētu vērtību kopa saglabāšanas tipam (SaveAs, Publish, Manual, OMSave utt.)

  - **Data\_SavingWithFont:bool —** vai dokuments tiek saglabāts ar jaunajiem iegultajiem fontiem?

  - **Data\_ScrubClonedDocumentTimeMS:long —** cik ilgā laikā tika noņemta personiskā informācija klonētajā dokumenta kopijā

  - **Data\_StopwatchDuration:long —** kopējais darbības ilgums

  - **Data\_TransactionType:long —** vai tā ir saglabāšanas vai saglabāšanas un sapludināšanas darbība?

#### <a name="officepowerpointdocoperationsaveas"></a>Office.PowerPoint.DocOperation.SaveAs

Apkopots ikreiz, kad PowerPoint veic darbību Saglabāt kā. Ietver saglabāšanas veiktspējas rādītāju rezultātu tipa panākumus un saistītos dokumenta metadatus. Saglabāšanas kļūmes var izraisīt datu zudumu.  Microsoft izmanto šos datus, lai nodrošinātu, ka līdzeklis darbojas, kā paredzēts, un lietotāju saturs tiek sekmīgi turpināts.

Tiek apkopoti tālāk norādītie lauki.

- **Data_AddDocTelemetryResult:long** — vai šim žurnāla ierakstam ir visa nepieciešamā dokumenta telemetrija (Data_Doc_* lauki)? Ja nav, kāpēc?

- **Data_CppUncaughtExceptionCount:long** — darbības izpildes laikā nenotvertie vietējie izņēmumi.

- **Data_DetachedDuration:long** — darbības atvienošanas/nedarbošanās ilgums.

- **Data_DstDoc_AccessMode:long** — kā šis dokuments tika atvērts (tikai lasāms | lasīšana un rakstīšana).

- **Data_DstDoc_AssistedReadingReasons:long** — iepriekš definētu vērtību kopa, kas norāda, kāpēc dokuments ir atvērts pieejamā lasīšanas režīmā.

- **Data_DstDoc_AsyncOpenKind:long — ** norāda, vai tika atvērta jaunā mākoņa dokumenta kešotā versijā un kura asinhronā atsvaidzināšanas loģika tika izmantota.

- **Data_DstDoc_ChunkingType:long** — kā dokuments ir saglabāts pakalpojumā SharePoint.

- **Data_DstDoc_EdpState:long** — dokumenta uzņēmuma datu aizsardzība statuss.

- **Data_DstDoc_Ext:string** — dokumenta paplašinājums.

- **Data_DstDoc_Extension:string** — dokumenta paplašinājums.

- **Data_DstDoc_FileFormat:long** — iepriekš definētu faila formāta vērtību kopa (detalizētāka par paplašinājumu).

- **Data_DstDoc_Fqdn:string** — dokumentu glabāšanas vieta (SharePoint.com, live.net), pieejama tikai Office 365 domēniem.
    
- **Data_DstDoc_FqdnHash:string** — dokumenta glabāšanas vietas jaukšana.

- **Data_DstDoc_IdentityTelemetryId:string** — lietotāja unikālais GUID.

- **Data_DstDoc_IdentityUniqueId:string** — koplietojamo dokumentu darbībai izmantotās identitātes unikālais identifikators.

- **Data_DstDoc_IOFlags:long** — bitmaska dažādiem ar IO saistītiem karodziņiem, kas attiecas uz dokumentu.

- **Data_DstDoc_IrmRights:long** — iepriekš definētu vērtību kopa, kas attiecas uz informācijas piekļuves tiesību pārvaldības tipu, kas tiek lietots šim dokumentam (pārsūtīšana, atbildēšana, SecureReader, rediģēšana u.c.).
    
- **Data_DstDoc_IsCloudCollabEnabled:bool** — patiess, ja "IsCloudCollabEnabled" HTTP galvene jau ir saņemta no pieprasījuma OPTIONS.

- **Data_DstDoc_IsIncrementalOpen:bool**— vai dokuments tika atvērts inkrementāli (jauns līdzeklis, kas atver dokumentu bez vajadzības lejupielādēt visu dokumentu).

- **Data_DstDoc_IsOcsSupported:bool** — vai ir dokuments atbalsta koprediģēšanu, izmantojot jauno OCS pakalpojumu.

- **Data_DstDoc_IsOpeningOfflineCopy:bool** — pārbauda, vai dokuments tiek atvērts no lokālās kešatmiņas.

- **Data_DstDoc_IsSyncBacked:bool** — vai dokuments tiek atvērts no mapes, kas izmanto OneDrive sinhronizācijas programmu.
    
- **Data_DstDoc_Location:long** — iepriekš definētu vērtību kopa, kas norāda dokumenta glabāšanas vietu (lokālā, SharePoint, WOPI, tīkls utt.).

- **Data_DstDoc_LocationDetails:long** — iepriekš definētu detalizētākas atrašanās vietas vērtību kopa (mape Temp, lejupielāžu mape, OneDrive dokumenti, OneDrive attēli utt.).

- **Data_DstDoc_NumberCoAuthors:long** — līdzautoru skaits dokumenta atvēršanas brīdī.

- **Data_DstDoc_PasswordFlags:long** — iepriekš definētu vērtību kopa, kas norāda veidu, kā dokuments ir šifrēts ar paroli (nav, parole lasīšanai, parole rediģēšanai).

- **Data_DstDoc_ReadOnlyReasons:long** — iepriekš definētu vērtību kopa, kas norāda, kāpēc šis dokuments ir atzīmēts kā tikai lasāms (bloķēts serverī, pabeigts dokuments, aizsargāts ar paroli rediģēšanai utt.).

- **Data_DstDoc_ResourceIdHash:string** — resursu identifikatora jaukšana mākonī saglabātajiem dokumentiem.

- **Data_DstDoc_ServerDocId:string** — nemainīgs identifikators mākonī saglabātajiem dokumentiem.

- **Data_DstDoc_ServerProtocol:long** — iepriekš definētu vērtību kopa, kas norāda, kurš protokols tiek izmantots, lai sazinātos ar serveri (HTTP, Cobalt, WOPI utt.).

- **Data_DstDoc_ServerType:long** — iepriekš definētu vērtību kopas servera tipam (SharePoint, DropBox, WOPI).

- **Data_DstDoc_ServerVersion:long** — pārbauda, vai servera pamatā ir Office14, Office15 vai Office 16.

- **Data_DstDoc_SessionId:long** — ģenerēts GUID, kas norāda dokumenta instanci tajā pašā procesa sesijā.

- **Data_DstDoc_SharePointServiceContext:string**— necaurspīdīga virkne, parasti GridManagerID.FarmID. Noder, lai saistītu klienta un servera žurnālu.

- **Data_DstDoc_SizeInBytes:long** — dokumenta lielums baitos.

- **Data_DstDoc_SpecialChars:long**— bitmaska, kas norāda speciālās rakstzīmes dokumenta vietrādī URL vai ceļā.

- **Data_DstDoc_StorageProviderId:string** — virkne, kas norāda dokumenta krātuves nodrošinātāju, piemēram, "DropBox".

- **Data_DstDoc_StreamAvailability:long** — iepriekš definētu dokumenta straumēšanas vērtību kopas statuss (pieejams, neatgriezeniski atspējots, nav pieejams).

- **Data_DstDoc_UrlHash:string** — pilna vietrāža URL jaukšana mākonī saglabātiem dokumentiem.

- **Data_DstDoc_UsedWrsDataOnOpen:bool** — patiess, ja fails tika atvērts inkrementāli, izmantojot iepriekš kešotus WRS datus resursdatorā.

- **Data_DstDoc_WopiServiceId:string** — WOPI pakalpojuma identifikators, piemēram, “Dropbox”.

- **Data_FileType:long** — iepriekš definētu iekšējā faila tipa vērtību kopa.

- **Data_fLifeguarded:bool** — vai dokuments kādreiz ir bijis aizsargāts (līdzeklis, lai izlabotu dokumenta kļūdas, neziņojot par to lietotājam)?

- **Data_FWebCreated:bool** — vai dokumentam ir WebCreator karodziņš?

- **Data_SaveReason:long** — iepriekš definētu vērtību kopa, kas norāda, kāpēc tika veikta saglabāšana. (Automātiskā saglabāšana, ToOCSTransitionSave, ToCSITransitionSave utt.)

- **Data_SaveType:long** — iepriekš definētu vērtību kopa saglabāšanas tipam (SaveAs, Publish, Manual, OMSave utt.). 

- **Data_SrcDoc_AccessMode:long** — kā šis dokuments tika atvērts (tikai lasāms | lasīšana un rakstīšana).

- **Data_SrcDoc_AssistedReadingReasons:long** — iepriekš definētu vērtību kopa, kas norāda, kāpēc dokuments ir atvērts pieejamā lasīšanas režīmā.

- **Data_SrcDoc_AsyncOpenKind:long — ** norāda, vai tika atvērta oriģinālā mākoņa dokumenta kešotā versijā un kura asinhronā atsvaidzināšanas loģika tika izmantota.

- **Data_SrcDoc_ChunkingType:long** — kā dokuments ir saglabāts pakalpojumā SharePoint. 

- **Data_SrcDoc_EdpState:long** — dokumenta uzņēmuma datu aizsardzība statuss.

- **Data_SrcDoc_Ext:string** — dokumenta paplašinājums.

- **Data_SrcDoc_Extension:string** — dokumenta paplašinājums.

- **Data_SrcDoc_FileFormat:long** — iepriekš definētu faila formāta vērtību kopa (detalizētāka par paplašinājumu).

- **Data_SrcDoc_Fqdn:string** — dokumenta glabāšanas vieta (SharePoint.com, live.net), pieejama tikai Office 365 domēniem.

- **Data_SrcDoc_FqdnHash:string** — dokumenta glabāšanas vietas jaukšana.

- **Data_SrcDoc_IdentityTelemetryId:string** — lietotāja unikālais GUID.

- **Data_SrcDoc_IdentityUniqueId:string** — koplietojamo dokumentu darbībai izmantotās identitātes unikālais identifikators.

- **Data_SrcDoc_IOFlags:long** — bitmaska dažādiem ar IO saistītiem karodziņiem, kas attiecas uz dokumentu.

- **Data_SrcDoc_IrmRights:long** — iepriekš definētu vērtību kopa, kas attiecas uz informācijas piekļuves tiesību pārvaldības tipu, kas tiek lietots šim dokumentam (pārsūtīšana, atbildēšana, SecureReader, rediģēšana u.c.).

- **Data_SrcDoc_IsCloudCollabEnabled:bool** — patiess, ja "IsCloudCollabEnabled" HTTP galvene jau ir saņemta no pieprasījuma OPTIONS.

- **Data_SrcDoc_IsIncrementalOpen:bool**— vai dokuments tika atvērts inkrementāli (jauns līdzeklis, kas atver dokumentu bez vajadzības lejupielādēt visu dokumentu).

- **Data_SrcDoc_IsOcsSupported:bool** — vai ir dokuments atbalsta koprediģēšanu, izmantojot jauno OCS pakalpojumu.

- **Data_SrcDoc_IsOpeningOfflineCopy:bool** — pārbauda, vai dokuments tiek atvērts no lokālās kešatmiņas.

- **Data_SrcDoc_IsSyncBacked:bool** — vai dokuments tiek atvērts no mapes, kas izmanto OneDrive sinhronizācijas programmu.

- **Data_SrcDoc_Location:long** — iepriekš definētu vērtību kopa, kas norāda dokumenta glabāšanas vietu (lokālā, SharePoint, WOPI, tīkls utt.).

- **Data_SrcDoc_LocationDetails:long** — iepriekš definētu detalizētākas atrašanās vietas vērtību kopa (mape Temp, lejupielāžu mape, OneDrive dokumenti, OneDrive attēli utt.).

- **Data_SrcDoc_NumberCoAuthors:long** — līdzautoru skaits dokumenta atvēršanas brīdī.

- **Data_SrcDoc_PasswordFlags:long** — iepriekš definētu vērtību kopa, kas norāda veidu, kā dokuments ir šifrēts ar paroli (nav, parole lasīšanai, parole rediģēšanai).

- **Data_SrcDoc_ReadOnlyReasons:long** — iepriekš definētu vērtību kopa, kas norāda, kāpēc šis dokuments ir atzīmēts kā tikai lasāms (bloķēts serverī, pabeigts dokuments, aizsargāts ar paroli rediģēšanai utt.).

- **Data_SrcDoc_ResourceIdHash:string** — resursu identifikatora jaukšana mākonī saglabātajiem dokumentiem.

- **Data_SrcDoc_ServerDocId:string** — nemainīgs identifikators mākonī saglabātajiem dokumentiem.

- **Data_SrcDoc_ServerProtocol:long** — iepriekš definētu vērtību kopa, kas norāda, kurš protokols tiek izmantots, lai sazinātos ar serveri (HTTP, Cobalt, WOPI utt.).

- **Data_SrcDoc_ServerType:long** — iepriekš definētu vērtību kopas servera tipam (SharePoint, DropBox, WOPI).

- **Data_SrcDoc_ServerVersion:long** — pārbauda, vai servera pamatā ir Office14, Office15 vai Office 16.

- **Data_SrcDoc_SessionId:long** — ģenerēts GUID, kas identificē dokumenta instanci tajā pašā procesa sesijā

- **Data_SrcDoc_SharePointServiceContext:string**—necaurspīdīga virkne, parasti GridManagerID.FarmID. Noder, lai saistītu klienta un servera žurnālu.

- **Data_SrcDoc_SizeInBytes:long** — dokumenta lielums baitos.

- **Data_SrcDoc_SpecialChars:long**— bitmaska, kas norāda speciālās rakstzīmes dokumenta vietrādī URL vai ceļā.

- **Data_SrcDoc_StorageProviderId:string** — virkne, kas norāda dokumenta krātuves nodrošinātāju, piemēram, "DropBox".

- **Data_SrcDoc_StreamAvailability:long** — iepriekš definētu dokumenta straumēšanas vērtību kopas statuss (pieejams, neatgriezeniski atspējots, nav pieejams).

- **Data_SrcDoc_UrlHash:string** — pilna vietrāža URL jaukšana mākonī saglabātiem dokumentiem.

- **Data_SrcDoc_UsedWrsDataOnOpen:bool** — patiess, ja fails tika atvērts inkrementāli, izmantojot iepriekš kešotus WRS datus resursdatorā.

- **Data_SrcDoc_WopiServiceId:string** — WOPI pakalpojuma identifikators, piemēram, “Dropbox”.

- **Data_StopwatchDuration:long** — kopējais darbības laiks.

- **Data_TypeOfSaveDialog: Long** — iepriekš definētu dialoga vērtību kopa (RUN_SAVEAS_DLG,RUN_SAVEMEDIA_DLG, RUN_SAVEAS_VIDEO_DLG u. tml.).

- **DstDoc** — jaunā dokumenta atrašanās vieta. 

- **SrcDoc** — dokumenta oriģinālā atrašanās vieta.


#### <a name="officepowerpointdocoperationsavelegacy"></a>Office.PowerPoint.DocOperation.SaveLegacy

Apkopots ikreiz, kad PowerPoint veic saglabāšanu, izmantojot mantotā koda ceļu. Ietver saglabāšanas veiktspējas rādītāju rezultātu tipa panākumus un saistītos dokumenta metadatus.  Saglabāšanas kļūmes var izraisīt datu zudumu.  Microsoft izmanto šos datus, lai nodrošinātu, ka līdzeklis darbojas, kā paredzēts, un lietotāju saturs tiek sekmīgi turpināts.

Tiek apkopoti tālāk norādītie lauki.

- **Data_AddDocTelemetryResult:long** — vai šim žurnāla ierakstam ir visa nepieciešamā dokumenta telemetrija (Data_Doc_* lauki)? Ja nav, kāpēc?

- **Data_CppUncaughtExceptionCount:long** — darbības izpildes laikā nenotvertie vietējie izņēmumi.

- **Data_DetachedDuration:long** — darbības atvienošanas/nedarbošanās ilgums.

- **Data_Doc_AccessMode:long** — kā šis dokuments tika atvērts (tikai lasāms | lasīšana un rakstīšana).

- **Data_Doc_AssistedReadingReasons:long** — iepriekš definētu vērtību kopa, kas norāda, kāpēc dokuments ir atvērts pieejamā lasīšanas režīmā.

- **Data_Doc_AsyncOpenKind:long — ** norāda, vai tika atvērta mākoņa dokumenta kešotā versijā un kura asinhronā atsvaidzināšanas loģika tika izmantota.

- **Data_Doc_ChunkingType:long** — kā dokuments ir saglabāts pakalpojumā SharePoint.

- **Data_Doc_EdpState:long** — dokumenta uzņēmuma datu aizsardzība statuss.

- **Data_Doc_Ext:string** — dokumenta paplašinājums.

- **Data_Doc_Extension:string** — dokumenta paplašinājums.

- **Data_Doc_FileFormat:long** — iepriekš definētu faila formāta vērtību kopa (detalizētāka par paplašinājumu).

- **Data_Doc_Fqdn:string** — dokumentu glabāšanas vieta (SharePoint.com, live.net), pieejama tikai Office 365 domēniem.

- **Data_Doc_FqdnHash:string** — dokumenta glabāšanas vietas jaukšana.

- **Data_Doc_IdentityTelemetryId:string** — lietotāja unikālais GUID.

- **Data_Doc_IdentityUniqueId:string** — koplietojamo dokumentu darbībai izmantotās identitātes unikālais identifikators.

- **Data_Doc_IOFlags:long** — bitmaska dažādiem ar IO saistītiem karodziņiem, kas attiecas uz dokumentu.

- **Data_Doc_IrmRights:long** — iepriekš definētu vērtību kopa, kas attiecas uz informācijas piekļuves tiesību pārvaldības tipu, kas tiek lietots šim dokumentam (pārsūtīšana, atbildēšana, SecureReader, rediģēšana u.c.).

- **Data_Doc_IsCloudCollabEnabled:bool** — patiess, ja "IsCloudCollabEnabled" HTTP galvene jau ir saņemta no pieprasījuma OPTIONS.

- **Data_Doc_IsIncrementalOpen:bool**— vai dokuments tika atvērts inkrementāli (jauns līdzeklis, kas atver dokumentu bez vajadzības lejupielādēt visu dokumentu).

- **Data_Doc_IsOcsSupported:bool** — vai ir dokuments atbalsta koprediģēšanu, izmantojot jauno OCS pakalpojumu.

- **Data_Doc_IsOpeningOfflineCopy:bool** — pārbauda, vai dokuments tiek atvērts no lokālās kešatmiņas.

- **Data_Doc_IsSyncBacked:bool** — vai dokuments tiek atvērts no mapes, kas izmanto OneDrive sinhronizācijas programmu.

- **Data_Doc_Location:long** — iepriekš definētu vērtību kopa, kas norāda dokumenta glabāšanas vietu (lokālā, SharePoint, WOPI, tīkls utt.).

- **Data_Doc_LocationDetails:long** — iepriekš definētu detalizētākas atrašanās vietas vērtību kopa (mape Temp, lejupielāžu mape, OneDrive dokumenti, OneDrive attēli utt.).

- **Data_Doc_NumberCoAuthors:long** — līdzautoru skaits dokumenta atvēršanas brīdī.

- **Data_Doc_PasswordFlags:long** — iepriekš definētu vērtību kopa, kas norāda veidu, kā dokuments ir šifrēts ar paroli (nav, parole lasīšanai, parole rediģēšanai).

- **Data_Doc_ReadOnlyReasons:long** — iepriekš definētu vērtību kopa, kas norāda, kāpēc šis dokuments ir atzīmēts kā tikai lasāms (bloķēts serverī, pabeigts dokuments, aizsargāts ar paroli rediģēšanai utt.).

- **Data_Doc_ResourceIdHash:string** — resursu identifikatora jaukšana mākonī saglabātajiem dokumentiem.

- **Data_Doc_RtcType —** norāda, kā reāllaika kanāls (RTC) bija iestatīts pašreizējam failam (atspējots, neatbalstīts, pēc pieprasījuma, vienmēr ieslēgts utt.).

- **Data_Doc_ServerDocId:string** — nemainīgs identifikators mākonī saglabātajiem dokumentiem.

- **Data_Doc_ServerProtocol:long** — iepriekš definētu vērtību kopa, kas norāda, kurš protokols tiek izmantots, lai sazinātos ar serveri (HTTP, Cobalt, WOPI utt.).

- **Data_Doc_ServerType:long** — iepriekš definētu vērtību kopas servera tipam (SharePoint, DropBox, WOPI). 

- **Data_Doc_ServerVersion:long** — pārbauda, vai servera pamatā ir Office14, Office15 vai Office 16.

- **Data_Doc_SessionId:long** — ģenerēts GUID, kas norāda dokumenta instanci tajā pašā procesa sesijā.

- **Data_Doc_SharePointServiceContext:string**— necaurspīdīga virkne, parasti GridManagerID.FarmID. Noder, lai saistītu klienta un servera žurnālu.

- **Data_Doc_SizeInBytes:long** — dokumenta lielums baitos.

- **Data_Doc_SpecialChars:long**— bitmaska, kas norāda speciālās rakstzīmes dokumenta vietrādī URL vai ceļā.

- **Data_Doc_StorageProviderId:string** — virkne, kas norāda dokumenta krātuves nodrošinātāju, piemēram, "DropBox".

- **Data_Doc_StreamAvailability:long** — iepriekš definētu dokumenta straumēšanas vērtību kopas statuss (pieejams, neatgriezeniski atspējots, nav pieejams).

- **Data_Doc_UrlHash:string** — pilna vietrāža URL jaukšana mākonī saglabātiem dokumentiem.

- **Data_Doc_UsedWrsDataOnOpen:bool** — patiess, ja fails tika atvērts inkrementāli, izmantojot iepriekš kešotus WRS datus resursdatorā.

- **Data_Doc_WopiServiceId:string** — WOPI pakalpojuma identifikators, piemēram, “Dropbox”.

- **Data_DstDoc_AccessMode:long** — kā šis dokuments tika atvērts (tikai lasāms | lasīšana un rakstīšana).

- **Data_DstDoc_AssistedReadingReasons:long** — iepriekš definētu vērtību kopa, kas norāda, kāpēc dokuments ir atvērts pieejamā lasīšanas režīmā.

- **Data_DstDoc_AsyncOpenKind:long — ** norāda, vai tika atvērta jaunā mākoņa dokumenta kešotā versijā un kura asinhronā atsvaidzināšanas loģika tika izmantota.

- **Data_DstDoc_ChunkingType:long** — kā dokuments ir saglabāts pakalpojumā SharePoint.

- **Data_DstDoc_EdpState:long** — dokumenta uzņēmuma datu aizsardzība statuss.

- **Data_DstDoc_Ext:string** — dokumenta paplašinājums.

- **Data_DstDoc_Extension:string** — dokumenta paplašinājums.

- **Data_DstDoc_FileFormat:long** — iepriekš definētu faila formāta vērtību kopa (detalizētāka par paplašinājumu).

- **Data_DstDoc_Fqdn:string** — dokumentu glabāšanas vieta (SharePoint.com, live.net), pieejama tikai Office 365 domēniem.
    
- **Data_DstDoc_FqdnHash:string** — dokumenta glabāšanas vietas jaukšana.

- **Data_DstDoc_IdentityTelemetryId:string** — lietotāja unikālais GUID.

- **Data_DstDoc_IdentityUniqueId:string** — koplietojamo dokumentu darbībai izmantotās identitātes unikālais identifikators.

- **Data_DstDoc_IOFlags:long** — bitmaska dažādiem ar IO saistītiem karodziņiem, kas attiecas uz dokumentu.

- **Data_DstDoc_IrmRights:long** — iepriekš definētu vērtību kopa, kas attiecas uz informācijas piekļuves tiesību pārvaldības tipu, kas tiek lietots šim dokumentam (pārsūtīšana, atbildēšana, SecureReader, rediģēšana u.c.).

- **Data_DstDoc_IsCloudCollabEnabled:bool** — patiess, ja "IsCloudCollabEnabled" HTTP galvene jau ir saņemta no pieprasījuma OPTIONS.

- **Data_DstDoc_IsIncrementalOpen:bool**— vai dokuments tika atvērts inkrementāli (jauns līdzeklis, kas atver dokumentu bez vajadzības lejupielādēt visu dokumentu).

- **Data_DstDoc_IsOcsSupported:bool** — vai ir dokuments atbalsta koprediģēšanu, izmantojot jauno OCS pakalpojumu.

- **Data_DstDoc_IsOpeningOfflineCopy:bool** — pārbauda, vai dokuments tiek atvērts no lokālās kešatmiņas.

- **Data_DstDoc_IsSyncBacked:bool** — vai dokuments tiek atvērts no mapes, kas izmanto OneDrive sinhronizācijas programmu.

- **Data_DstDoc_Location:long** — iepriekš definētu vērtību kopa, kas norāda dokumenta glabāšanas vietu (lokālā, SharePoint, WOPI, tīkls utt.).

- **Data_DstDoc_LocationDetails:long** — iepriekš definētu detalizētākas atrašanās vietas vērtību kopa (mape Temp, lejupielāžu mape, OneDrive dokumenti, OneDrive attēli utt.).

- **Data_DstDoc_NumberCoAuthors:long** — līdzautoru skaits dokumenta atvēršanas brīdī.

- **Data_DstDoc_PasswordFlags:long** — iepriekš definētu vērtību kopa, kas norāda veidu, kā dokuments ir šifrēts ar paroli (nav, parole lasīšanai, parole rediģēšanai).

- **Data_DstDoc_ReadOnlyReasons:long** — iepriekš definētu vērtību kopa, kas norāda, kāpēc šis dokuments ir atzīmēts kā tikai lasāms (bloķēts serverī, pabeigts dokuments, aizsargāts ar paroli rediģēšanai utt.).

- **Data_DstDoc_ResourceIdHash:string** — resursu identifikatora jaukšana mākonī saglabātajiem dokumentiem.

- **Data_DstDoc_ServerDocId:string** — nemainīgs identifikators mākonī saglabātajiem dokumentiem.

- **Data_DstDoc_ServerProtocol:long** — iepriekš definētu vērtību kopa, kas norāda, kurš protokols tiek izmantots, lai sazinātos ar serveri (HTTP, Cobalt, WOPI utt.).

- **Data_DstDoc_ServerType:long** — iepriekš definētu vērtību kopas servera tipam (SharePoint, DropBox, WOPI).

- **Data_DstDoc_ServerVersion:long** — pārbauda, vai servera pamatā ir Office14, Office15 vai Office 16.

- **Data_DstDoc_SessionId:long** — ģenerēts GUID, kas norāda dokumenta instanci tajā pašā procesa sesijā.

- **Data_DstDoc_SharePointServiceContext:string**— necaurspīdīga virkne, parasti GridManagerID.FarmID. Noder, lai saistītu klienta un servera žurnālu.

- **Data_DstDoc_SizeInBytes:long** — dokumenta lielums baitos.

- **Data_DstDoc_SpecialChars:long**— bitmaska, kas norāda speciālās rakstzīmes dokumenta vietrādī URL vai ceļā.

- **Data_DstDoc_StorageProviderId:string** — virkne, kas norāda dokumenta krātuves nodrošinātāju, piemēram, "DropBox".

- **Data_DstDoc_StreamAvailability:long** — iepriekš definētu dokumenta straumēšanas vērtību kopas statuss (pieejams, neatgriezeniski atspējots, nav pieejams).

- **Data_DstDoc_UrlHash:string** — pilna vietrāža URL jaukšana mākonī saglabātiem dokumentiem.

- **Data_DstDoc_UsedWrsDataOnOpen:bool** — patiess, ja fails tika atvērts inkrementāli, izmantojot iepriekš kešotus WRS datus resursdatorā.

- **Data_DstDoc_WopiServiceId:string** — WOPI pakalpojuma identifikators, piemēram, “Dropbox”.

- **Data_FileType:long** — iepriekš definētu iekšējā faila tipa vērtību kopa.

- **Data_fLifeguarded:bool** — vai dokuments kādreiz ir bijis aizsargāts (līdzeklis, lai izlabotu dokumenta kļūdas, neziņojot par to lietotājam)?

- **Data_SaveReason:long** — iepriekš definētu vērtību kopa, kas norāda, kāpēc tika veikta saglabāšana. (Automātiskā saglabāšana, ToOCSTransitionSave, ToCSITransitionSave utt.)

- **Data_SaveType:long** — iepriekš definētu vērtību kopa saglabāšanas tipam (SaveAs, Publish, Manual, OMSave utt.).

- **Data_SrcDoc_AccessMode:long** — kā šis dokuments tika atvērts (tikai lasāms | lasīšana un rakstīšana).

- **Data_SrcDoc_AssistedReadingReasons:long** — iepriekš definētu vērtību kopa, kas norāda, kāpēc dokuments ir atvērts pieejamā lasīšanas režīmā.

- **Data_SrcDoc_AsyncOpenKind:long — ** norāda, vai tika atvērta oriģinālā mākoņa dokumenta kešotā versijā un kura asinhronā atsvaidzināšanas loģika tika izmantota.

- **Data_SrcDoc_ChunkingType:long** — kā dokuments ir saglabāts pakalpojumā SharePoint.

- **Data_SrcDoc_EdpState:long** — dokumenta uzņēmuma datu aizsardzība statuss.

- **Data_SrcDoc_Ext:string** — dokumenta paplašinājums.

- **Data_SrcDoc_Extension:string** — dokumenta paplašinājums.

- **Data_SrcDoc_FileFormat:long** — iepriekš definētu faila formāta vērtību kopa (detalizētāka par paplašinājumu).

- **Data_SrcDoc_Fqdn:string** — dokumenta glabāšanas vieta (SharePoint.com, live.net), pieejama tikai Office 365 domēniem.

- **Data_SrcDoc_FqdnHash:string** — dokumenta glabāšanas vietas jaukšana. 

- **Data_SrcDoc_IdentityTelemetryId:string** — lietotāja unikālais GUID.

- **Data_SrcDoc_IdentityUniqueId:string** — koplietojamo dokumentu darbībai izmantotās identitātes unikālais identifikators.

- **Data_SrcDoc_IOFlags:long** — bitmaska dažādiem ar IO saistītiem karodziņiem, kas attiecas uz dokumentu.

- **Data_SrcDoc_IrmRights:long** — iepriekš definētu vērtību kopa, kas attiecas uz informācijas piekļuves tiesību pārvaldības tipu, kas tiek lietots šim dokumentam (pārsūtīšana, atbildēšana, SecureReader, rediģēšana u.c.).
    
- **Data_SrcDoc_IsCloudCollabEnabled:bool** — patiess, ja "IsCloudCollabEnabled" HTTP galvene jau ir saņemta no pieprasījuma OPTIONS.

- **Data_SrcDoc_IsIncrementalOpen:bool**— vai dokuments tika atvērts inkrementāli (jauns līdzeklis, kas atver dokumentu bez vajadzības lejupielādēt visu dokumentu).

- **Data_SrcDoc_IsOcsSupported:bool** — vai ir dokuments atbalsta koprediģēšanu, izmantojot jauno OCS pakalpojumu.

- **Data_SrcDoc_IsOpeningOfflineCopy:bool** — pārbauda, vai dokuments tiek atvērts no lokālās kešatmiņas.

- **Data_SrcDoc_IsSyncBacked:bool** — vai dokuments tiek atvērts no mapes, kas izmanto OneDrive sinhronizācijas programmu.

- **Data_SrcDoc_Location:long** — iepriekš definētu vērtību kopa, kas norāda dokumenta glabāšanas vietu (lokālā, SharePoint, WOPI, tīkls utt.).

- **Data_SrcDoc_LocationDetails:long** — iepriekš definētu detalizētākas atrašanās vietas vērtību kopa (mape Temp, lejupielāžu mape, OneDrive dokumenti, OneDrive attēli utt.).

- **Data_SrcDoc_NumberCoAuthors:long** — līdzautoru skaits dokumenta atvēršanas brīdī.

- **Data_SrcDoc_PasswordFlags:long** — iepriekš definētu vērtību kopa, kas norāda veidu, kā dokuments ir šifrēts ar paroli (nav, parole lasīšanai, parole rediģēšanai).

- **Data_SrcDoc_ReadOnlyReasons:long** — iepriekš definētu vērtību kopa, kas norāda, kāpēc šis dokuments ir atzīmēts kā tikai lasāms (bloķēts serverī, pabeigts dokuments, aizsargāts ar paroli rediģēšanai utt.).

- **Data_SrcDoc_ResourceIdHash:string** — resursu identifikatora jaukšana mākonī saglabātajiem dokumentiem.

- **Data_SrcDoc_ServerDocId:string** — nemainīgs identifikators mākonī saglabātajiem dokumentiem.

- **Data_SrcDoc_ServerProtocol:long** — iepriekš definētu vērtību kopa, kas norāda, kurš protokols tiek izmantots, lai sazinātos ar serveri (HTTP, Cobalt, WOPI utt.).

- **Data_SrcDoc_ServerType:long** — iepriekš definētu vērtību kopas servera tipam (SharePoint, DropBox, WOPI).

- **Data_SrcDoc_ServerVersion:long** — pārbauda, vai servera pamatā ir Office14, Office15 vai Office 16.

- **Data_SrcDoc_SessionId:long** — ģenerēts GUID, kas norāda dokumenta instanci tajā pašā procesa sesijā.

- **Data_SrcDoc_SharePointServiceContext:string**—necaurspīdīga virkne, parasti GridManagerID.FarmID. Noder, lai saistītu klienta un servera žurnālu.

- **Data_SrcDoc_SizeInBytes:long** — dokumenta lielums baitos.

- **Data_SrcDoc_SpecialChars:long**— bitmaska, kas norāda speciālās rakstzīmes dokumenta vietrādī URL vai ceļā.

- **Data_SrcDoc_StorageProviderId:string** — virkne, kas norāda dokumenta krātuves nodrošinātāju, piemēram, "DropBox".

- **Data_SrcDoc_StreamAvailability:long** — iepriekš definētu dokumenta straumēšanas vērtību kopas statuss (pieejams, neatgriezeniski atspējots, nav pieejams).

- **Data_SrcDoc_UrlHash:string** — pilna vietrāža URL jaukšana mākonī saglabātiem dokumentiem.

- **Data_SrcDoc_UsedWrsDataOnOpen:bool** — patiess, ja fails tika atvērts inkrementāli, izmantojot iepriekš kešotus WRS datus resursdatorā.

- **Data_SrcDoc_WopiServiceId:string** — WOPI pakalpojuma identifikators, piemēram, “Dropbox”.

- **Data_StopwatchDuration:long** — kopējais darbības laiks.

- **Data_TypeOfSaveDialog: Long** — iepriekš definētu dialoga vērtību kopa (RUN_SAVEAS_DLG, RUN_SAVEMEDIA_DLG, RUN_SAVEAS_VIDEO_DLG u. tml.).

- **Doc** — pašreizējais dokuments saglabāšanai.

- **DstDoc** — jaunā dokumenta atrašanās vieta (darbībai Saglabāt kā).

- **SrcDoc** — sākotnējā dokumenta atrašanās vieta (darbībai Saglabāt kā).

#### <a name="officepowerpointpptmacshellprintinfo"></a>Office.PowerPoint.PPT.Mac.Shell.PrintInfo

Tiek apkopots katru reizi, kad tiek veikta PDF eksportēšanas darbība, un satur informāciju par darbības rezultātu. Mūsu lietojumprogrammā šī informācija ir kritiski svarīga PDF eksportēšanas darbību veiksmīgas izpildes noteikšanai.

Tiek apkopoti tālāk norādītie lauki.

- **Data_ExportAsPDFSucceed** — būla, kas norāda, ka PDF eksportēšana bija veiksmīga.


#### <a name="officepowerpointpptsharedslideshowfailure"></a>Office.PowerPoint.PPT.Shared.SlideShow.Failure

Svarīgs PowerPoint līdzeklis, kas apkopo kļūmes slaidrādes laikā. Microsoft apkopo datus par kļūdām slaidrādes laikā, lai palīdzētu uzlabot slaidrādes lietošanas iespējas. Microsoft izmanto šos datus, lai iegūtu diagnostikas informāciju par vietu, kur notika kļūda, kamēr lietotājs izmantoja slaidrādi.

Tiek apkopoti tālāk norādītie lauki.

- **CountOArtErrors** — kopējais OArt kļūdu skaits

- **CountOtherErrors** — kopējais pārējo kļūdu skaits

- **CountPPTErrors** — kopējais PPT kļūdu skaits.

- **CountSlideShowErrors** — kopējais slaidrādes kļūdu skaits.

- **FirstOArtError** — pirmā OArt kļūda.

- **FirstOtherError** — pirmā kļūda citā apgabalā.

- **FirstPPTError** — pirmā PPT kļūda.

- **FirstSlideShowError** — pirmā kļūda slaidrādē.

    
#### <a name="officepowerpointrunprintoperation"></a>Office.PowerPoint.RunPrintOperation

Tiek apkopots katru reizi, kad tiek pabeigta PDF drukāšanas darbība, un satur informāciju par izkārtojuma veidu, slaidrādes numuru izmantošanu, kā arī darbības rezultātu. Mūsu lietojumprogrammā šī informācija ir kritiski svarīga PDF drukāšanas darbību veiksmīgas izpildes noteikšanai.

Tiek apkopoti tālāk norādītie lauki.

- **Data_PrintWithSlideNumbers** — būla, kas norāda, ka lietotājs drukā ar slaidu numuriem.

- **Data_SavePrintLayoutType** — drukas izkārtojuma veids brīdī, kad tiek uzsākta drukāšanas vai eksportēšanas darbība. 

- **Data_Success** — būla, kas norāda uz veiksmīgu drukāšanas izpildi.


#### <a name="officeprojectprojectfilesave"></a>Office.Project.ProjectFileSave

Project saglabā failu. Šis notikums norāda Project saglabāto failu. Tas ļauj korporācijai Microsoft novērtēt Project faila saglabāšanas panākumus, kas ir svarīgi, lai novērstu datu zudumu.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_TriggerTime** — saglabāšanas laiks

  - **Data\_FileType** — saglabātā projekta faila tips
 
#### <a name="officesessionactivitystart"></a>Office.Session.Activity.Start

Ļauj uzzināt, kad tiek sākta datu straumēšanas sesija.  Izmanto līdzekļu darbspējas veicināšanai un pārraudzībai. Šo notikumu ģenerē Microsoft Data Streamer Excel pievienojumprogrammai.

Tiek apkopoti šādi lauki:

- **Activity_Name** — darbības "Session" nosaukums

- **Activity_CV** — ID, kas saista savienojuma sesijas notikumus

- **Activity_StartStopType** — sākums

- **Activity_DateTimeTicks** — darbības datums un laiks

#### <a name="officesessionactivitystop"></a>Office.Session.Activity.Stop

Ļauj uzzināt, kad tiek pārtraukta datu straumēšanas sesija. Izmanto līdzekļa veiktspējas uzlabošanai un pārraudzībai. Šo notikumu ģenerē Microsoft Data Streamer Excel pievienojumprogrammai.

Tiek apkopoti šādi lauki:

- **Activity_Name** — darbības "Session" nosaukums

- **Activity_CV** — ID, kas saista savienojuma sesijas notikumus

- **Activity_StartStopType** — apturēšana

- **Activity_DateTimeTicks** — darbības datums un laiks

#### <a name="officestreamdeviceactivitystart"></a>Office.StreamDevice.Activity.Start

Ļauj uzzināt, vai straumēšanas datu avota sākšana bija sekmīga.   Izmanto līdzekļu darbspējas veicināšanai un pārraudzībai. Šo notikumu ģenerē Microsoft Data Streamer Excel pievienojumprogrammai.

Tiek apkopoti tālāk norādītie lauki.

- **Datasource_Type** — sērijas ierīce vai programmas pakalpojuma informācija

- **DataSource_Name** — pievienoto datu avota nosaukums

- **Activity_Name** — darbības "StreamFileData" vai "StreamDeviceData" nosaukums

- **Activity_CV** — ID, kas saista savienojuma sesijas notikumus

- **Activity_StartStopType** — sākums

- **Activity_DateTimeTicks** — darbības datums un laiks

#### <a name="officestreamdeviceactivitystop"></a>Office.StreamDevice.Activity.Stop

Ļauj uzzināt, vai straumēšanas datu avota pārtraukšana bija sekmīga.   Izmanto līdzekļu darbspējas veicināšanai un pārraudzībai. Šo notikumu ģenerē Microsoft Data Streamer Excel pievienojumprogrammai.

Tiek apkopoti tālāk norādītie lauki.

- **Datasource_Type** — sērijas ierīce vai programmas pakalpojuma informācija

- **DataSource_Name** — pievienoto datu avota nosaukums

- **Activity_Name** — darbības "StreamFileData" vai "StreamDeviceData" nosaukums

- **Activity_CV** — ID, kas saista savienojuma sesijas notikumus

- **Activity_StartStopType** — apturēšana

- **Activity_DateTimeTicks** — darbības datums un laiks

#### <a name="officetargetedmessagingabexperimentmessagetrigger"></a>Office.TargetedMessaging.ABExperimentMessageTrigger

Izseko to lietotāju skaitam, kas saņem BizBar un dinamiskās pamatnes ziņojumus no TargetedMessagingService (TMS). Šie dati ir būtiski, jo ļauj saprast, kādus ziņojumus saņem lietotāji un kurā virsmā. Šādi mēs varam nodrošināt, lai lietotāji nepalaistu garām nevienu ziņojumu par produkta turpmāku izmantošanu. Tie arī palīdz pareizi novērtēt mūsu eksperimentu un TMS kampaņu panākumus.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_Surface** — tās virsmas nosaukums, kam ir paredzēts šis pakalpojuma piegādātais ziņojums

  - **Data\_Flight** — ECS/CT testējamā varianta identifikators, kas tika izmantots, lai piegādātu šo ziņojumu

  - **Data\_CampaignId** — tās kampaņas identifikators, kurai pieder šis ziņojums

  - **Data\_MessageId** — šī pakalpojuma piegādātā ziņojuma identifikators

  - **Data\_TransactionId** — šīs pakalpojuma darbības identifikators

  - **Data\_TriggerPoint** — darbība, kurā tika reģistrēts šis notikums (saņemtais ziņojums salīdzinājumā ar attēloto ziņojumu)

#### <a name="officetextfontpickerfontselectedwin32"></a>Office.Text.FontPickerFontSelected.Win32

Šis notikums norāda, vai lejupielādētais fonts ir pareizi atveidots. Izmanto, lai norādītu fontu lejupielādes panākumus.

Tiek apkopoti tālāk norādītie lauki.

  - **Font name (Data\_Font)**  — fontu atlasītājā izvēlētā fonta nosaukums

  - **User click (Data\_FClick)**  — informācija par to, vai lietotājs atlasīja vienumu, izmantojot peli

#### <a name="officetextresourceclientrequestresourceinternal"></a>Office.Text.ResourceClient.RequestResourceInternal

Šis notikums norāda, vai fonts tika pareizi lejupielādēts. Izmanto, lai norādītu lejupielādētā fonta atveidošanas panākumus.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_FontToken** — resursa faila nosaukumam tiks veikta darbība Saglabāt kā

  - **Data\_HTTPResult** — HTTP pieprasījuma rezultāts

  - **Data\_HTTPStatusCode** — no HTTP pieprasījuma atgrieztais HTTP kods

  - **Data\_isInternetOn** — vai resursa izgūšanas laikā bija izveidots savienojums

  - **Data\_RequestUrl** — tā CDN resursa URL, kuru mēs mēģinām izgūt



#### <a name="officetranslatordocumenttranslated"></a>Office.Translator.DocumentTranslated

Apkopo tā pilna dokumenta tulkojuma panākumus, kuru lietotājs izraisīja, izmantojot tulkošanas SDX Tas ir svarīgi, lai novērtētu tulkošanas līdzekļa darbspēju un reaģētu uz iespējamiem darbības pārtraukumiem. Pārrauga dokumenta tulkošanas scenārija darbspēju programmā Word.

Tiek apkopoti tālāk norādītie lauki.

- **Data.actionSource —** kā tika izraisīta tulkošanas atlase.

- **Data.bodyBackgroundColor —** Office dizaina konteinera fona krāsa.

- **Data.bodyForegroundColor —** Office dizaina konteinera priekšplāna krāsa.

- **Data.browserLang —** pašreizējā pārlūkprogrammas interfeisa valoda.

- **Data.browserOnline —** novecojis.

- **Data.browserPlatform —** pārlūkprogrammas platforma.

- **Data.browserUserAgent —** pārlūkprogrammas lietotāja aģents.

- **Data.colorDepth** — sistēmas krāsu dziļums.

- **Data.contentLanguage**— noteiktā tulkojamā satura valoda.

- **Data.controlBackgroundColor**— Office dizaina kontroles fona krāsa.

- **Data.controlForegroundColor —** Office dizaina kontroles priekšplāna krāsa.

- **Data.correlationId —** uz pakalpojumu nosūtītā pieprasījuma unikālais identifikators.

- **Data.crossSessionId** — lietotāja unikālais identifikators.

- **Data.crossSessionStartTime**— tulkošanas sesijas sākuma UTC laikspiedols.

- **Data.currentTime** — UTC laikspiedols, kas norāda, kad tika nosūtīts šis telemetrijas ziņojums.

- **Data.displayLanguage**— Office interfeisa valoda.

- **Data.documentSourceLang —** dokumenta satura valoda.

- **Data.documentTargetLang —** valoda, uz kuru ir jātulko dokuments.

- **Data.environment —** tā pakalpojuma vide, uz kuru tiek nosūtīts pieprasījums.

- **Data.errorMessage —** pakalpojuma reģistrētais kļūdas ziņojums.

- **Data.eventActionType —** telemetrijas notikuma tips.

- **Data.eventTagId —** tās kodu rindas unikālais identifikators, kas izraisīja šo telemetrijas ziņojumu.

- **Data.flights —** iespējotie testējamie varianti.

- **Data.fileSize —** tulkojamā Word faila lielums.

- **Data.fileSource —** vieta, kur tiek viesots Word fails (tiešsaistē, bezsaistē).

- **Data.fileType —** Word faila paplašinājums.

- **Data.innerHeight —** sānu rūts konteinera augstums.

- **Data.innerWidth —** sānu rūts konteinera platums.

- **Data.lookupSourceLang —** netiek izmantots dokumenta tulkošanai.

- **Data.lookupTargetLang**— netiek izmantots dokumenta tulkošanai.

- **Data.officeHost —** Office lietojumprogramma, kas vieso sānu rūti.

- **Data.officeLocale —** Office lietotāja valoda.

- **Data.officeMachineId —** ierīces unikālais identifikators.

- **Data.officePlatform —** ierīces platforma.

- **Data.officeSessionId —** Office sesijas identifikators.

- **Data.officeUserId —** Office lietotāja unikālais identifikators.

- **Data.officeVersion —** Office versija.

- **Data.pageXOffset —** rūts horizontālās ritjoslas pozīcija no rūts kreisās puses.

- **Data.pageYOffset —** rūts vertikālās ritjoslas pozīcija no rūts augšpuses.

- **Data.pixelDepth —** ekrāna krāsas izšķirtspēja.

- **Data.responseCode —** pieprasījuma atbildes kods no pakalpojuma.

- **Data.responseTime —** pieprasījuma pagājušais laiks. 

- **Data.resultType —** pieprasījuma rezultāts.

- **Data.screenHeight —** ekrāna augstums pikseļos.

- **Data.screenLeft —** loga horizontālā koordināta attiecībā pret ekrānu.

- **Data.screenTop —** loga vertikālā koordināta attiecībā pret ekrānu.

- **Data.screenWidth —** ekrāna platums pikseļos.

- **Data.selectedTab —** kura ir atlasītā cilne: atlase vai dokuments.

- **Data.serverUrl —** tulkošanas pakalpojuma URL.

- **Data.sessionId —** sānu rūts sesijas identifikators.

- **Data.SessionStartTime —** tulkošanas sesijas sākuma UTC laikspiedols.

- **Data.sourceTextHash —** tulkojamā teksta jaukšana.

- **Data.sourceTextLength —** tulkojamā teksta garums.

- **Data.sourceTextWords —** tulkojamā teksta vārdu skaits.

- **Data.warningMessage —** pakalpojuma reģistrētais brīdinājuma ziņojums.


#### <a name="officetranslatortexttranslated"></a>Office.Translator.TextTranslated

Apkopo tās atlases tulkojuma panākumus, kuru izraisīja lietotāja darbība, izmantojot tulkošanas SDX. Tas ir svarīgi, lai novērtētu tulkošanas līdzekļa darbspēju un reaģētu uz iespējamiem darbības pārtraukumiem. Izmanto, lai pārraudzītu atlases tulkošanas scenārija darbspēju programmā Excel, PowerPoint un Word.

Tiek apkopoti tālāk norādītie lauki.

- **Data.actionSource —** kā tika izraisīta tulkošanas atlase.

- **Data.bodyBackgroundColor —** Office dizaina konteinera fona krāsa.

- **Data.bodyForegroundColor —** Office dizaina konteinera priekšplāna krāsa.

- **Data.browserLang —** pašreizējā pārlūkprogrammas interfeisa valoda.

- **Data.browserOnline —** novecojis.

- **Data.browserPlatform —** pārlūkprogrammas platforma.

- **Data.browserUserAgent —** pārlūkprogrammas lietotāja aģents.

- **Data.colorDepth** — sistēmas krāsu dziļums.

- **Data.contentLanguage**— noteiktā tulkojamā satura valoda.

- **Data.controlBackgroundColor**— Office dizaina kontroles fona krāsa.

- **Data.controlForegroundColor —** Office dizaina kontroles priekšplāna krāsa.

- **Data.correlationId —** uz pakalpojumu nosūtītā pieprasījuma unikālais identifikators.

- **Data.crossSessionId** — lietotāja unikālais identifikators.

- **Data.crossSessionStartTime**— tulkošanas sesijas sākuma UTC laikspiedols.

- **Data.currentTime** — UTC laikspiedols, kas norāda, kad tika nosūtīts šis telemetrijas ziņojums.

- **Data.displayLanguage**— Office interfeisa valoda.

- **Data.documentSourceLang —** netiek izmantots atlasei.

- **Data.documentTargetLang —** netiek izmantots tulkojuma atlasei.

- **Data.environment —** tā pakalpojuma vide, uz kuru tiek nosūtīts pieprasījums.

- **Data.errorMessage —** pakalpojuma reģistrētais kļūdas ziņojums.

- **Data.eventActionType —** telemetrijas notikuma tips.

- **Data.eventTagId" —** tās kodu rindas unikālais identifikators, kas izraisīja šo telemetrijas ziņojumu.

- **Data.flights —** iespējotie testējamie varianti.

- **Data.innerHeight —** sānu rūts konteinera augstums.

- **Data.innerWidth —** sānu rūts konteinera platums.

- **Data.lookupSourceLang —** pašreiz atlasītā teksta valoda.

- **Data.lookupTargetLang —** pašlaik atlasītā teksta valoda, kurā tiks veikts tulkojums.

- **Data.officeHost —** Office lietojumprogramma, kas vieso sānu rūti.

- **Data.officeLocale —** Office lietotāja valoda.

- **Data.officeMachineId —** ierīces unikālais identifikators.

- **Data.officePlatform —** ierīces platforma.

- **Data.officeSessionId —** Office sesijas identifikators.

- **Data.officeUserId —** Office lietotāja unikālais identifikators.

- **Data.officeVersion —** Office versija.

- **Data.pageXOffset —** rūts horizontālās ritjoslas pozīcija no rūts kreisās puses.

- **Data.pageYOffset —** rūts vertikālās ritjoslas pozīcija no rūts augšpuses.

- **Data.pixelDepth —** ekrāna krāsas izšķirtspēja.

- **Data.responseCode —** pieprasījuma atbildes kods no pakalpojuma.

- **Data.responseTime —** pieprasījuma pagājušais laiks.

- **Data.resultType —** pieprasījuma rezultāts.

- **Data.screenHeight —** ekrāna augstums pikseļos.

- **Data.screenLeft —** loga horizontālā koordināta attiecībā pret ekrānu.

- **Data.screenTop —** loga vertikālā koordināta attiecībā pret ekrānu.

- **Data.screenWidth —** ekrāna platums pikseļos.

- **Data.selectedTab —** kura ir atlasītā cilne: atlase vai dokuments.

- **Data.serverUrl —** tulkošanas pakalpojuma URL.

- **Data.sessionId —** sānu rūts sesijas identifikators.

- **Data.SessionStartTime —** tulkošanas sesijas sākuma UTC laikspiedols.

- **Data.sourceTextHash —** tulkojamā teksta jaukšana.

- **Data.sourceTextLength —** tulkojamā teksta garums.

- **Data.sourceTextWords —** tulkojamā teksta vārdu skaits.

- **Data.warningMessage —** pakalpojuma reģistrētais brīdinājuma ziņojums.


#### <a name="officevisiosharedfeatureexperimentation"></a>Office.Visio.Shared.FeatureExperimentation

Reģistrē līdzekļu izmēģinājumus lietotājiem. Šis notikums palīdz mums noteikt līdzekļa izmēģinājuma izdošanos vai neveiksmi.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_Enable:bool**— patiess norāda, ka līdzeklis ir iespējots pašreizējam lietotājam

  - **Data\_Feature:string** — līdzekļa nosaukums

  - **Data\_Flighted:bool** — patiess norāda, ka šis līdzeklis ir iespējots

  - **Data\_Licensed:bool** — patiess norāda, ka šim līdzeklim tiek veikta licences pārbaude

  - **Data\_Subscriber:bool** — patiess norāda, ka lietotājam ir abonementa licence

#### <a name="officevisiosharedrefreshsmartdiagram"></a>Office.Visio.Shared.RefreshSmartDiagram

Fiksē diagrammas atsvaidzināšanas kļūmes, kad fails tiek izveidots, izmantojot DV. Tas palīdz mums atkļūdot kļūmes un problēmas ar datu atsvaidzināšanu DV shēmā.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_ConnectorsBasedOnSequence:bool** — patiess, ja atsvaidzinātā shēma tika izveidota, izmantojot savienotāju, kura pamatā ir secības opcija

  - **Data\_DialogError**:**string** — kļūda viedās shēmas atsvaidzināšanas laikā

  - **Data\_FileError:string** — kļūdas virkne, ja pievienotais Excel fails ir nederīgs

  - **Data\_OverwriteSelected**:**bool** — patiess, ja lietotājs atlasīja shēmas pārrakstīšanas opciju atsvaidzināšanas laikā

  - **Data\_WarningShown**:**bool** — patiess, ja lietotājam tika parādīts brīdinājums datu atsvaidzināšanas laikā

#### <a name="officevisiosharedwritebacktoexcel"></a>Office.Visio.Shared.WritebackToExcel

Fiksē Excel pārrakstīšanas kļūmes, kad fails tiek izveidots, izmantojot DV. Tas palīdz mums atkļūdot kļūmes un problēmas ar Excel datu pārrakstīšanu DV shēmā.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_ConnectorsBasedOnSequence:bool** — patiess nozīmē, ka savienojumi ir izveidoti, pamatojoties uz secības iestatījumiem

  - **Data\_DataSourceType:string** — šis aizpildītais lauks norāda, vai shēma tiek izveidota no tabulas vai pielāgota diapazona

  - **Data\_DialogError:string** — pielāgots kļūdas tips, izveidojot viedo shēmu programmā Excel

  - **Data\_NoOfShapesAdded:int** — formu skaits, kas pievienotas pārrakstīšanas laikā Excel funkcionalitātē

  - **Data\_NoOfShapesDeleted:int** — formu skaits, kas izdzēstas pārrakstīšanas laikā Excel funkcionalitātē

  - **Data\_OverwriteSelected:bool** — patiess norāda, ka lietotājs atlasīja datu pārrakstīšanas opciju

  - **Data\_SourceDataModified:bool** — patiess norāda, ka tiek mainīti avota dati

  - **Data\_WarningShown:bool** — patiess norāda, ka lietotājam tiek parādīts datu atjaunināšanas brīdinājums

  - **Data\_WarningShownBecauseOfPresenceOfFormula:bool** — patiess norāda, ka lietotājam tiek parādīts brīdinājums, jo programmā Excel ir ievietota formula

  - **Data\_WarningShownToAddNextStepID:bool** — patiess norāda, ka lietotājam tiek parādīts brīdinājums, jo programmā Excel trūkst nākamās darbības identifikators

  - **Data\_WarningShownToConvertToTable:bool** — patiess norāda, ka lietotājam tiek parādīts brīdinājums, lai pārvērstu Excel datus tabulas formātā


#### <a name="officewordfilenewcreatenewfile"></a>Office.Word.FileNew.CreateNewFile

Šis notikums norāda, ka ir izveidots jauns Office Word dokuments un seko šīs darbības panākumu statusam. Notikums tiek izmantots, lai pārraudzītu jaunā dokumenta izveides pareizu darbību. To izmanto arī, lai aprēķinātu mēneša aktīvos lietotājus/ierīces un mākoņpakalpojumu uzticamības rādītājus.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_DirtyState** — vai dokuments tika izveidots mainītā statusā (ar nesaglabātām izmaiņām)

  - **Data\_ErrorID** — identifikators darbības kļūmes gadījumā

  - **Data\_MainPdod —** dokumenta identifikators šī procesa laikā.

  - **Data\_UsesCustomTemplate** — norāda, vai dokuments ir izveidots, izmantojot pielāgotu veidni

#### <a name="officewordfileopenuserinitiatedopen"></a>Office.Word.FileOpen.UserInitiatedOpen 

Šis notikums norāda, ka Office Word atver dokumentu pēc lietotāja iniciētas darbības, nevis izmantojot Office Word programmiski. Tas satur arī kritiski svarīgus faila atvēršanas izpildes datus, un no lietotāja skatpunkta ir programmas startēšanas notikums.  Notikums pārrauga, vai faila atvēršana darbojas pareizi. To izmanto arī, lai aprēķinātu mēneša aktīvos lietotājus/ierīces un mākoņpakalpojumu uzticamības rādītājus. 
 
Tiek apkopoti tālāk norādītie lauki.

- **Data_AddDocTelemRes** — norāda, vai mēs varam pareizi aizpildīt citas ar dokumentu telemetriju saistītās vērtības šajā notikumā. Izmanto datu kvalitātes diagnostikai. 

- **Data_BytesAsynchronous** — baitu skaits (saspiests), bez kura uzskatām, ka varēsim atvērt failu, ja tos iegūstam pirms lietotājs vēlas sākt rediģēšanu vai saglabāšanu. 

- **Data_BytesAsynchronousWithWork** — baitu skaits (saspiests), bez kura, iespējams, varēsim atvērt failu, taču tam būs nepieciešamas būtiskas koda izmaiņas. 

- **Data_BytesSynchronous** — baitu skaits (saspiests), kuram jābūt mūsu rīcībā, pirms varam sākt faila atvēršanu. 

- **Data_BytesUnknown**— baitu skaits dokumenta daļās, kuras neplānojam atrast. 

- **Data_Doc_AccessMode —** dokuments ir tikai lasāms/rediģējams. 

- **Data_Doc_AssistedReadingReasons** — iepriekš definētu vērtību kopa, kas norāda, kāpēc dokuments ir atvērts pieejamā lasīšanas režīmā. 

- **Data_Doc_ChunkingType —** vienības, kas tiek izmantotas inkrementālā dokumenta atvēršanā. 

- **Data_Doc_EdpState —** dokumenta elektronisko datu aizsardzības iestatījums. 

- **Data_Doc_Ext —** dokumenta paplašinājums (docx/xlsb/pptx utt.) 

- **Data_Doc_FileFormat —** faila formāta protokola versija. 

- **Data_Doc_Fqdn —** OneDrive vai SharePoint Online domēna nosaukums. 

- **Data_Doc_FqdnHash —** klientu identificējama domēna nosaukuma vienvirziena jaukšana. 

- **Data_Doc_IdentityTelemetryId —** tādas lietotāja identitātes vienvirziena jaukšana, kas tiek izmantota atvēršanā. 

- **Data_Doc_InitializationScenario —** dokumenta atvēršanas ieraksti. 

- **Data_Doc_IOFlags —** atskaites par kešotajiem karodziņiem, kas tiek izmantoti atvēršanas pieprasījuma opciju iestatīšanai. 

- **Data_Doc_IrmRights —** dokumentam/lietotājam piemērotās elektronisko datu politikas atļautās darbības. 

- **Data_Doc_IsIncrementalOpen —** karodziņš, kas norāda, ka dokuments tika atvērts inkrementāli. 

- **Data_Doc_IsOcsSupported —** karodziņš, kas norāda, ka dokuments tiek atbalstīts sadarbības pakalpojumā. 

- **Data_Doc_IsOpeningOfflineCopy —** karodziņš, kas norāda, ka tika atvērta dokumenta bezsaistes kopija. 

- **Data_Doc_IsSyncBacked —** karodziņš, kas norāda, ka datorā pastāv automātiski sinhronizēta dokumenta kopija. 

- **Data_Doc_Location —** norāda pakalpojumu, kurā atrodas dokuments (OneDrive, File Server, SharePoint) 

- **Data_Doc_LocationDetails —** norāda, kurā zināmajā mapē atrodas lokāli saglabātais dokuments. 

- **Data_Doc_NumberCoAuthors —** citu lietotāju skaits koprediģēšanas sesijā. 

- **Data_Doc_PasswordFlags —** norāda lasīšanas/rakstīšanas paroles karodziņu kopu. 

- **Data_Doc_ReadOnlyReasons —** iemesli, kāpēc dokuments ir atvērts tikai lasāmajā režīmā. 

- **Data_Doc_ResourceIdHash —** anonimizēts dokumenta identifikators, ko izmanto problēmu noteikšanā. 

- **Data_Doc_ServerDocId —** nemainīgs anonimizēts dokumenta identifikators, ko izmanto problēmu noteikšanā. 

- **Data_Doc_ServerProtocol —** protokola versija, ko izmanto, lai sazinātos ar pakalpojumu. 

- **Data_Doc_ServerType —** servera tips, kas nodrošina pakalpojumu (OneDrive, SharePoint, WOPI utt.). 

- **Data_Doc_ServerVersion —** servera versija, kas nodrošina pakalpojumu. 

- **Data_Doc_SessionId** — tā servera versija, kas nodrošina pakalpojumu 

- **Data_Doc_SharePointServiceContext —** diagnostikas informācija no SharePoint Online pieprasījumiem. 

- **Data_Doc_SizeInBytes —** dokumenta lieluma rādītājs. 

- **Data_Doc_SpecialChars —** speciālo rakstzīmju rādītājs dokumenta vietrādī URL vai ceļā. 

- **Data_Doc_StreamAvailability —** norāda, vai ir pieejama/atspējota dokumenta plūsma. 

- **Data_Doc_SyncBackedType —** norāda dokumenta veidu (lokālais vai servera). 

- **Data_UrlHash —** vienvirziena jaukšana vienkāršota dokumenta identifikatora izveidei. 

- **Data.Doc.WopiServiceId —** satur unikālu WOPI pakalpojumu sniedzēja identifikatoru. 

- **Data_EditorDisablingRename** — pirmā redaktora identifikators, kas izraisīja pārdēvēšanas atspējošanu. 

- **Data_EditorsCount** — redaktoru skaits dokumentā. 

- **Data_ForceReadWriteReason** — vesela skaitļa vērtība, kas attēlo iemeslu, kāpēc fails tika atvērts lasīšanas/rakstīšanas režīmā. 

- **Data_FSucceededAfterRecoverableFailure** — norāda, ka atvēršana izdevās pēc kļūmes izlabošanas, kas radās dokumenta atvēršanas laikā. 

- **Data_LastLoggedTag** — unikāla atzīme koda izsaukuma vietā, ko izmanto, lai noteiktu, kad neizdodas atvērt divreiz (izmanto datu kvalitātes diagnostikai). 

- **Data_LinkStyles** — norāda, vai ir saite ar veidņu stiliem. 

- **Data_MainPdod** — dokumenta identifikators Office Word procesā. 

- **Data_Measurements** — kodēta virkne, kas satur dažādu daļu atvēršanas laika sadalījumu. Izmanto, lai diagnosticētu atvēršanas izpildi. 

- **Data_MoveDisabledReason** — kļūda, kas atspējo dokumenta pārvietošanu. 

- **Data_MoveFlightEnabled** — vai lidojuma opcija pārvietošanas līdzeklī ir iespējota. 

- **Data_OpenInitiateKind** — tāda scenārija tips, kur lietotāji sāka šo failu atvēršanas darbību. 

- **Data_PartsUnknown** — dokumenta daļu skaits, kurām mēs nevarējām iegūt datus. 

- **Data_RecoverableFailureInitiationLocationTag** — unikāla atzīme koda izsaukumu vietā, lai identificētu vietu kodā, kur mēs mēģināsim izlabot failu pirms tā atvēršanas. 

- **Data_RenameDisabledReason** — kļūda, kuras dēļ tiek atspējota dokumenta pārdēvēšana. 

- **Data_RenameFlightEnabled** — vai testējamā varianta opcija pārdēvēšanas līdzeklī ir iespējota. 

- **Data_SecondaryTag** — unikāla atzīme koda izsaukšanas vietai, kas tiek izmantota, lai pievienotu papildu kļūmes datus atvēršanai. 

- **Data_TemplateFormat** — tās veidnes faila formāts, kas ir dokumenta pamatā. 

- **Data_UsesNormal** — norāda, vai atvērtā dokumenta pamatā ir parasta veidne. 

- **Data_VerboseMeasurements** — kodēta virkne, kas satur detalizētu dažādu daļu atvēršanas laika sadalījumu.  Tiek izmantota, lai mērītu veiktspēju, kas iespējota tikai iekšējiem apļiem. 



#### <a name="officewordfilesaveactcmdgosubsaveas"></a>Office.Word.FileSave.ActCmdGosubSaveAs

Šis notikums norāda, ka lietotājs saglabā izmaiņas jaunā dokumentā. Notikums pārrauga jauna dokumenta saglabāšanas pareizu darbību. To izmanto arī, lai aprēķinātu mēneša aktīvos lietotājus/ierīces un mākoņpakalpojumu uzticamības rādītājus.

Tiek apkopoti tālāk norādītie lauki.

- **Data_AddDocTelemRes** — norāda, vai mēs varam pareizi aizpildīt citas ar dokumentu telemetriju saistītās vērtības šajā notikumā. Izmanto datu kvalitātes diagnostikai.

- **Data_detachedDuration** — cik ilgi darbība bija atdalīta no pavediena.

- **Data_Doc_AccessMode —** dokuments ir tikai lasāms/rediģējams.

- **Data_Doc_AssistedReadingReasons** — iepriekš definētu vērtību kopa, kas norāda, kāpēc dokuments ir atvērts pieejamā lasīšanas režīmā.

- **Data_Doc_AsyncOpenKind — ** norāda, vai tika atvērta mākoņa dokumenta kešotā versijā un kura asinhronā atsvaidzināšanas loģika tika izmantota.

- **Data_Doc_ChunkingType —** vienības, kas tiek izmantotas inkrementālā dokumenta atvēršanā.

- **Data_Doc_EdpState —** dokumenta elektronisko datu aizsardzības iestatījums.

- **Data_Doc_Ext —** dokumenta paplašinājums (docx/xlsb/pptx utt.).

- **Data_Doc_FileFormat —** faila formāta protokola versija.

- **Data_Doc_Fqdn —** OneDrive vai SharePoint Online domēna nosaukums.

- **Data_Doc_FqdnHash —** klientu identificējama domēna nosaukuma vienvirziena jaukšana.

- **Data_Doc_IdentityTelemetryId —** tādas lietotāja identitātes vienvirziena jaukšana, kas tiek izmantota atvēršanā.

- **Data_Doc_InitializationScenario —** dokumenta atvēršanas ieraksti.

- **Data_Doc_IOFlags —** atskaites par kešotajiem karodziņiem, kas tiek izmantoti atvēršanas pieprasījuma opciju iestatīšanai.

- **Data_Doc_IrmRights —** dokumentam/lietotājam piemērotās elektronisko datu politikas atļautās darbības.
    
- **Data_Doc_IsIncrementalOpen —** karodziņš, kas norāda, ka dokuments tika atvērts inkrementāli.

- **Data_Doc_IsOcsSupported —** karodziņš, kas norāda, ka dokuments tiek atbalstīts sadarbības pakalpojumā.
    
- **Data_Doc_IsOpeningOfflineCopy —** karodziņš, kas norāda, ka tika atvērta dokumenta bezsaistes kopija.

- **Data_Doc_IsSyncBacked —** karodziņš, kas norāda, ka datorā pastāv automātiski sinhronizēta dokumenta kopija.

- **Data_Doc_Location —** norāda pakalpojumu, kurā atrodas dokuments (OneDrive, File Server, SharePoint utt.).

- **Data_Doc_LocationDetails —** norāda, kurā zināmajā mapē atrodas lokāli saglabātais dokuments.

- **Data_Doc_NumberCoAuthors —** citu lietotāju skaits koprediģēšanas sesijā.

- **Data_Doc_PasswordFlags —** norāda lasīšanas/rakstīšanas paroles karodziņu kopu.

- **Data_Doc_ReadOnlyReasons —** iemesli, kāpēc dokuments ir atvērts tikai lasāmajā režīmā.

- **Data_Doc_ResourceIdHash —** anonimizēts dokumenta identifikators, ko izmanto problēmu noteikšanā.

- **Data_Doc_RtcType —** norāda, kā reāllaika kanāls (RTC) bija iestatīts pašreizējam failam (atspējots, neatbalstīts, pēc pieprasījuma, vienmēr ieslēgts utt.).

- **Data_Doc_ServerDocId —** nemainīgs anonimizēts dokumenta identifikators, ko izmanto problēmu noteikšanā.

- **Data_Doc_ServerProtocol —** protokola versija, ko izmanto, lai sazinātos ar pakalpojumu.

- **Data_Doc_ServerType —** servera tips, kas nodrošina pakalpojumu (OneDrive, SharePoint, WOPI utt.).

- **Data_Doc_ServerVersion —** servera versija, kas nodrošina pakalpojumu.

- **Data_Doc_SessionId —** identificē konkrētu dokumenta rediģēšanas sesiju pilnā sesijā.

- **Data_Doc_SharePointServiceContext —** diagnostikas informācija no SharePoint Online pieprasījumiem.

- **Data_Doc_SizeInBytes —** dokumenta lieluma rādītājs.

- **Data_Doc_SpecialChars —** speciālo rakstzīmju rādītājs dokumenta vietrādī URL vai ceļā.

- **Data_Doc_StreamAvailability —** norāda, vai ir pieejama/atspējota dokumenta plūsma.

- **Data_Doc_SyncBackedType —** norāda dokumenta veidu (lokālais vai servera).

- **Data_UrlHash —** vienvirziena jaukšana vienkāršota dokumenta identifikatora izveidei.

- **Data_EditorDisablingRename** — tā pirmā redaktora identifikators, kas izraisīja pārdēvēšanas atspējošanu.

- **Data_EditorsCount** — redaktoru skaits dokumentā.

- **Data_LastLoggedTag** — unikāla atzīme koda izsaukuma vietā, ko izmanto, lai noteiktu, kad neizdodas saglabāt divreiz (izmanto datu kvalitātes diagnostikai).

- **Data_MoveDisabledReason** — kļūda, kas atspējo dokumenta pārvietošanu.

- **Data_MoveFlightEnabled** — vai lidojuma opcija pārvietošanas līdzeklī ir iespējota.

- **Data_RenameDisabledReason** — kļūda, kuras dēļ tiek atspējota dokumenta pārdēvēšana.

- **Data_RenameFlightEnabled** — vai testējamā varianta opcija pārdēvēšanas līdzeklī ir iespējota.

    

#### <a name="officewordfilesaveactfconfirmsavedoccorequerysave"></a>Office.Word.FileSave.ActFConfirmSaveDocCoreQuerySave

Šis notikums norāda, ka Office Word aicina lietotāju saglabāt izmaiņas, kad tiek mēģināts aizvērt dokumentu. Tas ļauj korporācijai Microsoft pārraudzīt, vai saglabāšana pēc programmas aizvēršanas darbojas pareizi un netiek zaudēti dati. Notikums pārrauga, vai dokumenta saglabāšana pēc programmas aizvēršanas darbojas pareizi. To izmanto arī, lai aprēķinātu mēneša aktīvos lietotājus/ierīces un mākoņpakalpojumu uzticamības rādītājus.

Tiek apkopoti tālāk norādītie lauki.

- **Data_AddDocTelemRes** — norāda, vai mēs varam pareizi aizpildīt citas ar dokumentu telemetriju saistītās vērtības šajā notikumā. Izmanto datu kvalitātes diagnostikai.

- **Data_detachedDuration** — cik ilgi darbība bija atdalīta no pavediena.

- **Data_Doc_AccessMode —** dokuments ir tikai lasāms/rediģējams.

- **Data_Doc_AssistedReadingReasons** — iepriekš definētu vērtību kopa, kas norāda, kāpēc dokuments ir atvērts pieejamā lasīšanas režīmā.

- **Data_Doc_AsyncOpenKind — ** norāda, vai tika atvērta mākoņa dokumenta kešotā versijā un kura asinhronā atsvaidzināšanas loģika tika izmantota.

- **Data_Doc_ChunkingType —** vienības, kas tiek izmantotas inkrementālā dokumenta atvēršanā.

- **Data_Doc_EdpState —** dokumenta elektronisko datu aizsardzības iestatījums.

- **Data_Doc_Ext —** dokumenta paplašinājums (docx/xlsb/pptx utt.).

- **Data_Doc_FileFormat —** faila formāta protokola versija.

- **Data_Doc_Fqdn —** OneDrive vai SharePoint Online domēna nosaukums.

- **Data_Doc_FqdnHash —** klientu identificējama domēna nosaukuma vienvirziena jaukšana.

- **Data_Doc_IdentityTelemetryId —** tādas lietotāja identitātes vienvirziena jaukšana, kas tiek izmantota atvēršanā.

- **Data_Doc_InitializationScenario —** dokumenta atvēršanas ieraksti.

- **Data_Doc_IOFlags —** atskaites par kešotajiem karodziņiem, kas tiek izmantoti atvēršanas pieprasījuma opciju iestatīšanai.

- **Data_Doc_IrmRights —** dokumentam/lietotājam piemērotās elektronisko datu politikas atļautās darbības.

- **Data_Doc_IsIncrementalOpen —** karodziņš, kas norāda, ka dokuments tika atvērts inkrementāli.

- **Data_Doc_IsOcsSupported —** karodziņš, kas norāda, ka dokuments tiek atbalstīts sadarbības pakalpojumā.
    
- **Data_Doc_IsOpeningOfflineCopy —** karodziņš, kas norāda, ka tika atvērta dokumenta bezsaistes kopija.

- **Data_Doc_IsSyncBacked —** karodziņš, kas norāda, ka datorā pastāv automātiski sinhronizēta dokumenta kopija.

- **Data_Doc_Location —** norāda pakalpojumu, kurā atrodas dokuments (OneDrive, File Server, SharePoint utt.).

- **Data_Doc_LocationDetails —** norāda, kurā zināmajā mapē atrodas lokāli saglabātais dokuments.

- **Data_Doc_NumberCoAuthors —** citu lietotāju skaits koprediģēšanas sesijā.

- **Data_Doc_PasswordFlags —** norāda lasīšanas/rakstīšanas paroles karodziņu kopu.

- **Data_Doc_ReadOnlyReasons —** iemesli, kāpēc dokuments ir atvērts tikai lasāmajā režīmā.

- **Data_Doc_ResourceIdHash —** anonimizēts dokumenta identifikators, ko izmanto problēmu noteikšanā.

- **Data_Doc_RtcType —** norāda, kā reāllaika kanāls (RTC) bija iestatīts pašreizējam failam (atspējots, neatbalstīts, pēc pieprasījuma, vienmēr ieslēgts utt.).

- **Data_Doc_ServerDocId —** nemainīgs anonimizēts dokumenta identifikators, ko izmanto problēmu noteikšanā.

- **Data_Doc_ServerProtocol —** protokola versija, ko izmanto, lai sazinātos ar pakalpojumu.

- **Data_Doc_ServerType —** servera tips, kas nodrošina pakalpojumu (OneDrive, SharePoint, WOPI utt.).

- **Data_Doc_ServerVersion —** servera versija, kas nodrošina pakalpojumu.

- **Data_Doc_SessionId —** identificē konkrētu dokumenta rediģēšanas sesiju pilnā sesijā.

- **Data_Doc_SharePointServiceContext —** diagnostikas informācija no SharePoint Online pieprasījumiem.

- **Data_Doc_SizeInBytes —** dokumenta lieluma rādītājs.

- **Data_Doc_SpecialChars —** speciālo rakstzīmju rādītājs dokumenta vietrādī URL vai ceļā.

- **Data_Doc_StreamAvailability —** norāda, vai ir pieejama/atspējota dokumenta plūsma.

- **Data_Doc_SyncBackedType —** norāda dokumenta veidu (lokālais vai servera).

- **Data_UrlHash —** vienvirziena jaukšana vienkāršota dokumenta identifikatora izveidei.

- **Data.Doc.WopiServiceId —** satur unikālu WOPI pakalpojumu sniedzēja identifikatoru.

- **Data_DstDoc_AccessMode** — mērķa dokuments ir tikai lasāms/rediģējams.

- **Data_Doc_EdpState** — mērķa dokumenta elektronisko datu aizsardzības iestatījums.

- **Data_DstDoc_Ext** — mērķa dokumenta paplašinājums (docx/xlsb/pptx utt.).

- **Data_DstDoc_FileFormat** — mērķa dokumenta faila formāta protokola versija.

- **Data_DstDoc_Location** — norāda pakalpojumu, kurā atrodas mērķa dokuments (OneDrive, File Server, SharePoint utt.).

- **Data_DstDoc_LocationDetails** — norāda, kura lokālajā zināmajā mapē tiek glabāts mērķa dokuments.

- **Data_DstDoc_SessionId —** identificē konkrētu dokumenta rediģēšanas sesiju pilnā sesijā.

- **Data_DstDoc_UrlHash** — vienvirziena jaukšana vienkāršota mērķa dokumenta identifikatora izveidei.

- **Data_FailureClass** — skaitlis, kas atspoguļo OCS pārejas kļūmju kļūmes klasi.

- **Data_LocationPickerSaveStatus** — skaitliska vērtība, kas norāda darbību, kas aktivizēja saglabāšanu izejas dialoglodziņā.

- **Data_MainPdod** — dokumenta identifikators Office Word procesā.

- **Data_MoveFlightEnabled** — vai lidojuma opcija pārvietošanas līdzeklī ir iespējota.

- **Data_OCSSyncbackSaveStarted** — karodziņš, kas norāda, ka saglabātais dokuments ir saistīts ar sinhronizēto saglabāšanu. 

- **Data_RenameDisabledReason** — kļūda, kuras dēļ tiek atspējota dokumenta pārdēvēšana.

- **Data_RenameFlightEnabled** — vai testējamā varianta opcija pārdēvēšanas līdzeklī ir iespējota.

- **Data_SaveInitiateKind** — vesels skaitlis, kas norāda, kā tika sākta saglabāšana.

- **Data_SrcDocIsUnnamedOrNew** — norāda, vai saglabājamais dokuments ir jauns.


#### <a name="officewordfilesavesaveassavefile"></a>Office.Word.FileSave.SaveAsSaveFile

Šis notikums norāda, ka Office Word saglabā dokumentu jaunā dokumentā. Tādējādi Microsoft var noteikt darbības “saglabāt kā” kļūdas, kam ir būtiska nozīme, lai novērstu dokumenta datu zudumu. Notikums pārrauga, vai dokumenta saglabāšana darbojas pareizi. To izmanto arī, lai aprēķinātu mēneša aktīvos lietotājus/ierīces un mākoņpakalpojumu uzticamības rādītājus.

Tiek apkopoti tālāk norādītie lauki.

- **Data_AddDocTelemRes** — norāda, vai mēs varam pareizi aizpildīt citas ar dokumentu telemetriju saistītās vērtības šajā notikumā. Izmanto datu kvalitātes diagnostikai.

- **Data_AddDocTelemRes** — norāda, vai mēs varam pareizi aizpildīt citas ar dokumentu telemetriju saistītās vērtības šajā notikumā mērķa dokumentam. Izmanto datu kvalitātes diagnostikai.

- **Data_AddDocTelemRes** — norāda, vai mēs varam pareizi aizpildīt citas ar dokumentu telemetriju saistītās vērtības šajā notikumā avota dokumentam. Izmanto datu kvalitātes diagnostikai.

- **Data_detachedDuration** — cik ilgi darbība bija atdalīta no pavediena.

- **Data_Doc_AccessMode —** dokuments ir tikai lasāms/rediģējams.

- **Data_Doc_AssistedReadingReasons** — iepriekš definētu vērtību kopa, kas norāda, kāpēc dokuments ir atvērts pieejamā lasīšanas režīmā.

- **Data_Doc_AsyncOpenKind — ** norāda, vai tika atvērta mākoņa dokumenta kešotā versijā un kura asinhronā atsvaidzināšanas loģika tika izmantota.

- **Data_Doc_ChunkingType —** vienības, kas tiek izmantotas inkrementālā dokumenta atvēršanā.

- **Data_Doc_EdpState —** dokumenta elektronisko datu aizsardzības iestatījums.

- **Data_Doc_Ext —** dokumenta paplašinājums (docx/xlsb/pptx utt.).

- **Data_Doc_FileFormat —** faila formāta protokola versija.

- **Data_Doc_Fqdn —** OneDrive vai SharePoint Online domēna nosaukums.

- **Data_Doc_FqdnHash —** klientu identificējama domēna nosaukuma vienvirziena jaukšana.

- **Data_Doc_IdentityTelemetryId —** tādas lietotāja identitātes vienvirziena jaukšana, kas tiek izmantota atvēršanā.

- **Data_Doc_IOFlags —** atskaites par kešotajiem karodziņiem, kas tiek izmantoti atvēršanas pieprasījuma opciju iestatīšanai.

- **Data_Doc_IrmRights —** dokumentam/lietotājam piemērotās elektronisko datu politikas atļautās darbības.

- **Data_Doc_IsIncrementalOpen —** karodziņš, kas norāda, ka dokuments tika atvērts inkrementāli.

- **Data_Doc_IsOcsSupported —** karodziņš, kas norāda, ka dokuments tiek atbalstīts sadarbības pakalpojumā.

- **Data_Doc_IsOpeningOfflineCopy —** karodziņš, kas norāda, ka tika atvērta dokumenta bezsaistes kopija.

- **Data_Doc_IsSyncBacked —** karodziņš, kas norāda, ka datorā pastāv automātiski sinhronizēta dokumenta kopija.

- **Data_Doc_Location —** norāda pakalpojumu, kurā atrodas dokuments (OneDrive, File Server, SharePoint utt.).

- **Data_Doc_LocationDetails —** norāda, kurā zināmajā mapē atrodas lokāli saglabātais dokuments.

- **Data_Doc_NumberCoAuthors —** citu lietotāju skaits koprediģēšanas sesijā.

- **Data_Doc_ReadOnlyReasons —** iemesli, kāpēc dokuments ir atvērts tikai lasāmajā režīmā.

- **Data_Doc_ResourceIdHash —** anonimizēts dokumenta identifikators, ko izmanto problēmu noteikšanā.

- **Data_Doc_RtcType —** norāda, kā reāllaika kanāls (RTC) bija iestatīts pašreizējam failam (atspējots, neatbalstīts, pēc pieprasījuma, vienmēr ieslēgts utt.).

- **Data_Doc_ServerDocId —** nemainīgs anonimizēts dokumenta identifikators, ko izmanto problēmu noteikšanā.

- **Data_Doc_ServerProtocol —** protokola versija, ko izmanto, lai sazinātos ar pakalpojumu.

- **Data_Doc_ServerType —** servera tips, kas nodrošina pakalpojumu (OneDrive, SharePoint, WOPI utt.).

- **Data_Doc_ServerVersion —** servera versija, kas nodrošina pakalpojumu.

- **Data_Doc_SessionId —** identificē konkrētu dokumenta rediģēšanas sesiju pilnā sesijā.

- **Data_Doc_SharePointServiceContext —** diagnostikas informācija no SharePoint Online pieprasījumiem.

- **Data_Doc_SizeInBytes —** dokumenta lieluma rādītājs.

- **Data_Doc_SpecialChars —** speciālo rakstzīmju rādītājs dokumenta vietrādī URL vai ceļā.

- **Data_Doc_StreamAvailability —** norāda, vai ir pieejama/atspējota dokumenta plūsma.

- **Data_UrlHash —** vienvirziena jaukšana vienkāršota dokumenta identifikatora izveidei.

- **Data_DstDoc_AccessMode** — mērķa dokuments ir tikai lasāms/rediģējams.

- **Data_DstDoc_AssistedReadingReasons** — iepriekš definētu vērtību kopa, kas norāda, kāpēc mērķa dokuments ir atvērts pieejamā lasīšanas režīmā.

- **Data_DstDoc_AsyncOpenKind —** norāda, vai tika atvērta jaunā mākoņa dokumenta kešotā versijā un kura asinhronā atsvaidzināšanas loģika tika izmantota.
    
- **Data_DstDoc_ChunkingType —** vienības, kas tiek izmantotas inkrementālā dokumenta atvēršanā.

- **Data_DstDoc_EdpState** — mērķa dokumenta elektronisko datu aizsardzības iestatījums.

- **Data_DstDoc_Ext —** dokumenta paplašinājums (docx/xlsb/pptx utt.).

- **Data_DstDoc_FileFormat —** faila formāta protokola versija.

- **Data_DstDoc_Fqdn** — OneDrive vai SharePoint Online domēna nosaukums mērķa dokumentam.

- **Data_DstDoc_FqdnHash** — klientu identificējama domēna nosaukuma vienvirziena jaukšana mērķa dokumentam.

- **Data_DstDoc_IdentityTelemetryId —** tādas lietotāja identitātes vienvirziena jaukšana, kas tiek izmantota atvēršanā.

- **Data_DstDoc_InitializationScenario** — mērķa dokumenta atvēršanas ieraksti.

- **Data_DstDoc_IOFlags** — atskaites par kešotajiem karodziņiem, kas tiek izmantoti pieprasījuma opciju iestatīšanai mērķa dokumentam.
    
- **Data_DstDoc_IrmRights** — mērķa dokumentam/lietotājam piemērotās elektronisko datu politikas atļautās darbības.

- **Data_DstDoc_IsIncrementalOpen —** karodziņš, kas norāda, ka dokuments tika atvērts inkrementāli.

- **Data_DstDoc_IsOcsSupported —** karodziņš, kas norāda, ka dokuments tiek atbalstīts sadarbības pakalpojumā.

- **Data_DstDoc_IsOpeningOfflineCopy —** karodziņš, kas norāda, ka tika atvērta dokumenta bezsaistes kopija.

- **Data_DstDoc_IsSyncBacked —** karodziņš, kas norāda, ka datorā pastāv automātiski sinhronizēta dokumenta kopija.

- **Data_DstDoc_Location** — norāda pakalpojumu, kurā atrodas mērķa dokuments (OneDrive, File Server, SharePoint utt.).

- **Data_DstDoc_LocationDetails —** norāda, kurā zināmajā mapē atrodas lokāli saglabātais dokuments.

- **Data_DstDoc_NumberCoAuthors —** citu lietotāju skaits koprediģēšanas sesijā.

- **Data_DstDoc_PasswordFlags** — norāda lasīšanas/rakstīšanas paroles karodziņu kopu mērķa dokumentam.

- **Data_DstDoc_ReadOnlyReasons** — iemesli, kāpēc mērķa dokuments ir atvērts tikai lasāmajā režīmā. 

- **Data_DstDoc_ResourceIdHash —** anonimizēts dokumenta identifikators, ko izmanto problēmu noteikšanā.

- **Data_DstDoc_ServerDocId —** nemainīgs anonimizēts dokumenta identifikators, ko izmanto problēmu noteikšanā.

- **Data_DstDoc_ServerProtocol —** protokola versija, ko izmanto, lai sazinātos ar pakalpojumu.

- **Data_DstDoc_ServerType —** servera tips, kas nodrošina pakalpojumu (OneDrive, SharePoint, WOPI utt.).
    
- **Data_DstDoc_ServerVersion —** servera versija, kas nodrošina pakalpojumu.

- **Data_DstDoc_SessionId —** identificē konkrētu dokumenta rediģēšanas sesiju pilnā sesijā.

- **Data_DstDoc_SharePointServiceContext —** diagnostikas informācija no SharePoint Online pieprasījumiem.

- **Data_DstDoc_SizeInBytes —** dokumenta lieluma rādītājs.

- **Data_DstDoc_SpecialChars —** speciālo rakstzīmju rādītājs dokumenta vietrādī URL vai ceļā.

- **Data_DstDoc_StreamAvailability —** norāda, vai ir pieejama/atspējota dokumenta plūsma.

- **Data_DstDoc_SyncBackedType —** norāda dokumenta veidu (lokālais vai servera).

- **Data_DstDoc_UrlHash** — vienvirziena jaukšana vienkāršota mērķa dokumenta identifikatora izveidei.
    
- **Data_DstDoc_WopiServiceId —** satur unikālu WOPI pakalpojumu sniedzēja identifikatoru.

- **Data_FailureClass** — skaitlis, kas atspoguļo OCS pārejas kļūmju kļūmes klasi.

- **Data_LocationPickerPropagateToSaveTime,spLapsedMsec** — izmēra laiku milisekundēs, kas nepieciešams, līdz saglabāšanas aktivizēšanai pēc rezultāta iegūšanas no atrašanās vietas meklētāja.

- **Data_LocationPickerSaveStatus** — atrašanās vietas meklētāja atgrieztais statuss.

- **Data_MainPdod** — dokumenta identifikators Office Word procesā.

- **Data_MoveDisabledReason** — kļūda, kas atspējo dokumenta pārvietošanu.

- **Data_MoveFlightEnabled** — vai lidojuma opcija pārvietošanas līdzeklī ir iespējota.

- **Data_RenameDisabledReason** — kļūda, kuras dēļ tiek atspējota dokumenta pārdēvēšana.

- **Data_RenameFlightEnabled** — vai testējamā varianta opcija pārdēvēšanas līdzeklī ir iespējota.

- **Data_SaveInitiateKind** — vesels skaitlis, kas norāda, kā tika sākta saglabāšana.

- **Data_SrcDoc_AccessMode** — avota dokuments ir tikai lasāms/rediģējams.

- **Data_SrcDoc_AssistedReadingReasons** — iepriekš definētu vērtību kopa, kas norāda, kāpēc dokuments ir atvērts pieejamā lasīšanas režīmā.

- **Data_SrcDoc_AsyncOpenKind —** norāda, vai tika atvērta oriģinālā mākoņa dokumenta kešotā versijā un kura asinhronā atsvaidzināšanas loģika tika izmantota.

- **Data_SrcDoc_ChunkingType —** vienības, kas tiek izmantotas inkrementālā dokumenta atvēršanā.

- **Data_SrcDoc_EdpState** — avota dokumenta elektronisko datu aizsardzības iestatījums.

- **Data_SrcDoc_Ext** — avota dokumenta paplašinājums (docx/xlsb/pptx utt.).

- **Data_SrcDoc_FileFormat** — avota dokumenta faila formāta protokola versija.

- **Data_SrcDoc_Fqdn** — OneDrive vai SharePoint Online domēna nosaukums avota dokumentam.

- **Data_SrcDoc_FqdnHash** — klientu identificējama domēna nosaukuma vienvirziena jaukšana avota dokumentam.

- **Data_SrcDoc_IdentityTelemetryId —** tādas lietotāja identitātes vienvirziena jaukšana, kas tiek izmantota atvēršanā.

- **Data_SrcDoc_InitializationScenario —** dokumenta atvēršanas ieraksti.

- **Data_SrcDoc_IOFlags —** atskaites par kešotajiem karodziņiem, kas tiek izmantoti atvēršanas pieprasījuma opciju iestatīšanai.

- **Data_SrcDoc_IrmRights —** dokumentam/lietotājam piemērotās elektronisko datu politikas atļautās darbības.

- **Data_SrcDoc_IsIncrementalOpen —** karodziņš, kas norāda, ka dokuments tika atvērts inkrementāli.

- **Data_SrcDoc_IsOcsSupported —** karodziņš, kas norāda, ka dokuments tiek atbalstīts sadarbības pakalpojumā.

- **Data_SrcDoc_IsOpeningOfflineCopy —** karodziņš, kas norāda, ka tika atvērta dokumenta bezsaistes kopija.

- **Data_SrcDoc_IsSyncBacked —** karodziņš, kas norāda, ka datorā pastāv automātiski sinhronizēta dokumenta kopija.
    
- **Data_SrcDoc_Location** — norāda pakalpojumu, kurā atrodas avota dokuments (OneDrive, File Server, SharePoint utt.).

- **Data_SrcDoc_LocationDetails —** norāda, kurā zināmajā mapē atrodas lokāli saglabātais dokuments.

- **Data_SrcDoc_NumberCoAuthors —** citu lietotāju skaits koprediģēšanas sesijā.

- **Data_SrcDoc_PasswordFlags —** norāda lasīšanas/rakstīšanas paroles karodziņu kopu.

- **Data_SrcDoc_ReadOnlyReasons —** iemesli, kāpēc dokuments ir atvērts tikai lasāmajā režīmā.

- **Data_SrcDoc_ResourceIdHash —** anonimizēts dokumenta identifikators, ko izmanto problēmu noteikšanā.

- **Data_SrcDoc_ServerDocId —** nemainīgs anonimizēts dokumenta identifikators, ko izmanto problēmu noteikšanā.

- **Data_SrcDoc_ServerProtocol —** protokola versija, ko izmanto, lai sazinātos ar pakalpojumu.

- **Data_SrcDoc_ServerType —** servera tips, kas nodrošina pakalpojumu (OneDrive, SharePoint, WOPI utt.).

- **Data_SrcDoc_ServerVersion —** servera versija, kas nodrošina pakalpojumu.

- **Data_SrcDoc_SessionId —** identificē konkrētu dokumenta rediģēšanas sesiju pilnā sesijā.

- **Data_SrcDoc_SharePointServiceContext —** diagnostikas informācija no SharePoint Online pieprasījumiem.

- **Data_SrcDoc_SizeInBytes —** dokumenta lieluma rādītājs.

- **Data_SrcDoc_SpecialChars —** speciālo rakstzīmju rādītājs dokumenta vietrādī URL vai ceļā.

- **Data_SrcDoc_StreamAvailability —** norāda, vai ir pieejama/atspējota dokumenta plūsma.

- **Data_SrcDoc_SyncBackedType —** norāda dokumenta veidu (lokālais vai servera).

- **Data_SrcHash —** vienvirziena jaukšana vienkāršota dokumenta identifikatora izveidei.

- **Data_SrcDoc_WopiServiceId —** satur unikālu WOPI pakalpojumu sniedzēja identifikatoru.

- **Data_SrcDocIsUnnamedOrNew** — norāda, vai saglabājamais dokuments ir jauns.


#### <a name="officewordworddocumentdirtyflagchanged"></a>Office.Word.Word.DocumentDirtyFlagChanged

Šis notikums norāda, ka Office Word rediģē dokumentu, kas dokumenta iekšējo stāvokli padara "netīru". Tas ļauj Microsoft novērtēt dokumenta rediģēšanas līdzekļa darbspēju. Notikums ir lietotāja veikto rediģējumu periodiskais kontrolziņojums. To izmanto arī, lai aprēķinātu mēneša aktīvos lietotājus/ierīces.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_CollectionTime —** notikuma laikspiedols

  - **Data\_DocumentLocation —** dokumenta atrašanās vietas tips

  - **Data\_DocumentLocationDetails —** dokumenta atrašanās vietas apakštips

  - **Data\_FAlwaysSaveEnabled —** norāda, vai ir iespējota iespēja vienmēr saglabāt

  - **Data\_FirstEditTime —** pirmās rediģēšanas laikspiedols

  - **Data\_NumberCoAuthors —** līdzautoru skaits, kuri sesijā rediģē dokumentu

  - **Data\_NumberOfTimesDocumentDirtied —** dokumentā veikto rediģējumu skaits

  - **Data\_Pdod —** dokumenta identifikators Office Word procesā

  - **Data\_UrlHash —** dokumenta ceļa jaukšana

  - **Data\_ViewKind —** Word skata tips

#### <a name="onenotecanvaspageopened-previous-name-officeonenoteandroidcanvaspageopened"></a>OneNote.Canvas.PageOpened *(iepriekšējais nosaukums)*, Office.OneNote.Android.Canvas.PageOpened

Signāls tiek izmantots, lai ierakstītu brīdi, kad tiek atvērta lapa.  Telemetriju izmanto, lai pārraudzītu, atklātu un novērstu jebkādas problēmas. kas rodas brīdī, kad lapa tiek atvērta OneNote

Tiek apkopoti tālāk norādītie lauki: 

- **JOT_ID** — atvērtās lapas objekts

- **TIME_TAKEN_IN_MS** — lapas atvēršanai veltītais laiks

#### <a name="onenotecapturenewnotenewnotetaken-previous-name-officeonenoteandroidcapturenewnotenewnotetaken"></a>OneNote.Capture.NewNote.NewNoteTaken *(iepriekšējais nosaukums)*, Office.OneNote.Android.Capture.NewNote.NewNoteTaken

Šis signāls tiek izmantots, lai nodrošinātu to, ka pēc lietotāja pierakstīšanās OneNote Android lietojumprogrammā, piezīmju grāmatiņas tiek atbilstoši nodrošinātas un lietotājs ir veiksmīgi izveidojis jaunu piezīmi.  Tek izmantota kritiskas regresijas atklāšanai OneNote lietojumprogrammā un pakalpojuma darbspējā.

Papildu lauki netiek apkopoti.

#### <a name="onenotemessagebarmessagebarclicked-previous-name-officeonenoteandroidmessagebarmessagebarclicked"></a>OneNote.MessageBar.MessageBarClicked *(iepriekšējais nosaukums)*, Office.OneNote.Android.MessageBar.MessageBarClicked

Šis signāls tie izmantots, lai norādītu uz jebkādām problēmām, kas rodas izmantojot ziņojumu joslu.  Telemetriju izmanto, lai pārraudzītu, atklātu un novērstu jebkādas ziņojumu joslas izmantošanas laikā radušās problēmas

Tiek apkopoti tālāk norādītie lauki: 

- **Message_Bar_Type** — atgriež, ja lietotājs izmanto veco vai jauno ziņojumu joslu

- **Message_Type** — atgriež kļūdas ziņojuma ID

#### <a name="parselicenseop"></a>ParseLicenseOp

Tiek apkopots, kad lietotājs mēģina atvērt ar IRM aizsargātu dokumentu vai lietot IRM aizsardzību.  Tas satur informāciju, kas ir nepieciešama pareizai tādu problēmu izmeklēšanai un diagnosticēšanai, kas notiek licenču parsēšanas darbības laikā. 

Tiek apkopoti tālāk norādītie lauki.

- **AppInfo.ClientHierarchy** — klienta hierarhija, kas norāda, ka lietojumprogramma darbojas ražošanas vidē vai izstrādātāja vidē

- **AppInfo.Name** — lietojumprogrammas nosaukums

- **AppInfo.Version** — lietojumprogrammas versija

- **iKey** — reģistrētāja servera ID

- **RMS.ApplicationScenarioId** — scenārija ID, ko nodrošina lietojumprogramma

- **RMS.Duration** — kopējais laiks darbības veikšanai

- **RMS.DurationWithoutExternalOps** — kopējais patērētais laiks mīnus ārējās operācijas, piemēram, tīkla latentums.

- **RMS.ErrorCode** — atgrieztais kļūdas kods, ja tāds ir, no darbības

- **RMS.HttpCall** — norāda, vai ir HTTP operācija

- **RMS.LicenseFormat** — licences formāts: XrML vai JSON

- **RMS.Result** — darbība sekmīga vai neizdevās

- **RMS.ScenarioId** — scenārija ID, ko definē tiesību pārvaldības pakalpojuma klients

- **RMS.SDKVersion** — tiesību pārvaldības pakalpojuma klienta versija

- **RMS.ServerType** — tiesību pārvaldības pakalpojuma servera tips 

- **RMS.StatusCode** — darbības rezultāta statusa kods

- **RMS.VerifyCertChainDuration** — laiks, lai verificētu sertifikātu ķēdi

- **RMS.VerifySignatureDuration** — laiks, lai verificētu parakstu

#### <a name="read_conversation"></a>read_conversation

Izmanto, lai uzraudzītu iespējamo negatīvu ietekmi uz e-pasta ziņojumu renderēšanas darbspēju un veiktspēju

Tiek apkopoti šādi lauki: 

- **above_40fps** — virs 40 kadriem sekundē renderēto kadru skaits
 
- **above_50fps** — virs 50 kadriem sekundē renderēto kadru skaits
 
- **above_55fps** — virs 55 kadriem sekundē renderēto kadru skaits

- **adal_id** — konta aktīvās direktorijas autentifikācijas ID, unikāls identifikators Microsoft autentifikācijas sistēmā 

- **component_name** — tā komponenta/skata nosaukums, kas ir aktīvs filtrēšanas laikā

- **event_mode** — vieta lietojumprogrammā, kuru lietotājs ir ievadījis sarunā (grupas vai cits)

- **internet_message_id** — izsekošanas ID jaunākajam ziņojumam sarunā
      
- **orientation** — ekrāna orientācija (portrets vai ainava) notikuma laikā

- **recent_message_id** — sarunā jaunāka ziņojuma ID

- **suggested_reply_state** — šai sarunai ieteikto atbilžu stāvoklis (nav pieejams, pieejams, parādīts, izmantots vai atmests)
  
- **total_count** — kopējais komponenta attēloto kadru skaits
 
- **view_duration** — kopējais laiks, ko komponenta skatīšanai veltīja lietotājs

#### <a name="save_attempt"></a>save_attempt

Ļauj mums noteikt problēmu, kuru iemesls ir lietotāju mēģinājumi saglabāt failu, ietekmi, izvērtējot ietekmēto sesiju skaitu un nosakot, vai šīm sesijām ir kopīgas pazīmes.

Tiek apkopoti šādi lauki: 

- **file_type** — faila tips, ko lietotājs mēģināja saglabāt (piemēram,. doc)

- **origin** — norāda faila saglabāšanas mēģinājuma izcelsmi (piemēram, no e-pasta), ļaujot mums noteikt ar failu saglabāšanu konkrētajā vietā lietojumprogrammā saistītās problēmas

- **token_type** — faila saglabāšanai veiktās konta autentifikācijas marķiera veids, lai palīdzētu mums atklāt ar faila saglabāšanu saistītās autentifikācijas problēmas

#### <a name="search_subtab_selected"></a>search_subtab_selected

Šis notikums mums ļauj izsekot vienuma veida atzīmes (viss, pasts, kontakti un kalendārs), ko lietotāji izmanto meklēšanas laikā, lai mēs varētu nodrošināt atbilstošu meklēšanas filtru mehānismu darbību.

Tiek apkopoti šādi lauki:

- **properties_general** — vispārīgi rekvizīti, kurus apkopo visi Aria notikumi

- **selected_reason** — tipa atzīmes atlases iemesls, kas var būt viena no šim trim vērtībām: tap_on_header, tap_on_see_all, enter_search_mode

- **subtab_type** — tipa atzīme, kas tika atlasīta un varētu būt viena no šīm četrām vērtībām: viss, pasts, kontaktpersona, notikums.

#### <a name="send_message"></a>send_message

Izmanto, lai uzraudzītu iespējamo negatīvo ietekmi uz e-pasta ziņojumu sūtīšanas veiktspēju un darbspēju.

Tiek apkopoti šādi lauki:
  
- **account** — izseko kontam, kas veica darbību

- **compose_duration** — izseko kopējam laikam, ko lietotājs veltīja ziņojuma sastādīšanai, tai skaitā vairākas melnrakstu sesijas

- **draft_message_id** — izseko nosūtāmā ziņojuma sastādīšanas ID

- **event_mode** — izseko notikuma režīmam, ja attiecināms uz ziņojumu (“grupas” vai “cits”)

- **has_attachment** — norāda, vai ziņojumam ir pielikumi

- **has_mip_label** — norāda, vai ziņojums tika apzīmogots ar MIP etiķeti

- **is_group_escalation** — norāda, vai šis ir grupas eskalēts ziņojums; “eskalēts ziņojums” ir ziņojums, kas nosūtīts uz lietotāja pastkasti eskalācijas dēļ (abonējis grupu)

- **is_groups** — izseko, vai nosūtītais ziņojums ir grupas ziņojums vai nav

- **key_stroke_count** — seko taustiņsitienu skaitam nosūtāmajā ziņojumā

- **message_id** — izseko ziņojuma ID, uz kuru tiek atbildēts/kas tiek pārsūtīts

- **origin** — norāda, kur tika sākta sastādīšana, piemēram, jauns, atbilde, ātrā atbilde utt.

- **send_draft_origin** — norāda, kur tika sākta sūtīšana, piemēram, rakstīt vai ātrā atbilde utt.

- **source_inbox** — norāda avota iesūtnes tipu atsauces ziņojumam 

- **suggested_reply_state** — fiksē ieteiktās atbildes šim nosūtītajam e-pasta ziņojumam stāvokli, piem., nav pieejams, pieejams, parādīts, izmantots vai atmests.

- **thread_id** — norāda sarunas, uz kuru tiek atbildēts/kas tiek pārsūtīta, pavediena ID

#### <a name="session"></a>session

Ļauj mums atklāt un novērst situācijas, kurās mēs pārmērīgi izmantojam jūsu ierīces akumulatoru, kā arī palīdz mums noteikt šādu situāciju iemeslu.

Tiek apkopoti šādi lauki: 

- **battery_level** — norāda jūsu ierīces akumulatora uzlādes līmeni, lai palīdzētu mums noteikt, vai mūsu lietojumprogramma negatīvi ietekmē jūsu ierīces akumulatora uzlādes līmeni

- **has_hx** — norāda, vai konts izmanto jauno sinhronizācijas pakalpojumu, lai palīdzētu noteikt mūsu sinhronizācijas pakalpojuma radītās problēmas

#### <a name="settings_action"></a>settings_action

Ļauj mums noteikt situācijas, kad ir iespējami negatīva ietekme uz jūsu iespēju konfigurēt lietojumprogrammas iestatījumus, piemēram, paziņojumu iestatījumus, primāro pasta kontu un e-pasta paraksta konfigurēšanu.

Tiek apkopoti šādi lauki: 

- **account_order_changed** — ļauj pārbaudīt, vai jūs mainījāt savu kontu secību, lai nodrošinātu pareizu šīs konfigurācijas darbību 

- **action** — iespējamās iestatījumos veicamās darbības, piemēram, konta dzēšana, palīdz mums atklāt problēmas un izvairīties no negatīvas ietekmes

- **auth_type** — konta izmantotais autentifikācijas tips, lai mēs varētu saprast, kuru aizmugursistēmas slāni mēs izmantojam problēmu diagnostikai 

- **auth_type** — norāda aizmugursistēmas autentifikācijas tipu, ļaujot mums noskaidrot, vai pastāv problēma ar konkrēto konta veidu

- **badge_count_state** — norāda, kāda veida žetonu skaitīšanu pieprasīja lietotājs, piemēram, nav žetonu, tikai iesūtnei utt. 

- **changed_folder** — reģistrē, vai mape ir mainīta, lai palīdzētu mums diagnosticēt problēmas. 

- **changed_folder** — nosaka, vai šī darbība tika arhivēta, plānota vai cita darbība.

- **delete_scope** — konta dzēšanas laikā norāda, vai jūs dzēšat kontu tikai šajā ierīcē vai visās ierīcēs ar Outlook.  

- **delete_scope** — seko, vai šī darbība bija saistīta ar dzēšanu tikai šajā ierīcē vai visās ierīcēs, ja attiecināms. 

- **enabled_state** — norāda, vai jūsu automātiskās atbildes, kontaktpersonu saglabāšanas un ārējo attēlu saglabāšanas iestatījumi ir konfigurēti pareizi  

- **enabled_state** — norāda, vai ir iespējots ar darbību saistītais stāvoklis

- **notification_state** — norāda, kāda veida žetonu skaitīšanu pieprasīja lietotājs, piemēram, nav žetonu, tikai iesūtnei utt.

- **server_type** — līdzīgs auth_type, norāda jūsu konta veidu labākai problēmas noteikšanai. Piemēri** — Office365, Gmail, Outlook

- **server_type** — norāda aizmugursistēmas autentifikācijas tipu, ļaujot mums noskaidrot, vai pastāv problēma ar konkrēto servera veidu

- **setting_properties** — izseko rekvizīta saistībai ar iestatīšanas darbību 

- **signature_setting** — norāda, vai iestatījums tika pielietots visiem kontiem vai atsevišķam kontam

- **source** — norāda, kas ir paziņojumu avots, ja attiecināms, no iestatījumiem vai iestatījuma “netraucēt”

- **state_changed_to** — lai pārbaudītu, vai jūsu galvenās iesūtnes iesl./izsl. iestatījums ir konfigurēts pareizi 

- **swipe_action** — lai pārbaudītu, vai jūs konfigurējāt jebkādas pavilkšanas darbības e-pastu ziņojumu šķirošanai, un pārliecinātos, ka šis iestatījums darbojas pareizi 

- **swipe_action** — norāda, ko lietotājs mēģināja izdarīt, piemēram, atzīmēt ar karodziņu, dzēst, arhivēt; ļauj mums noteikt, kādu darbību lietotājs vēlējās veikt, un, vai darbība izdevās. 

- **swipe_direction** — lai pārbaudītu, vai jūsu pavilkšanas virzieni (pa kreisi vai pa labi) ir iestatīti pareizi

- **swipe_direction** — norāda, kādā virzienā lietotājs iestatīja pavilkšanu, t.i., no kreisās uz labo vai no labās uz kreiso pusi.  Ļauj mums noteikt, vai pastāv problēmas ar konkrētu pavilkšanas virzienu.

- **swipe_setting** — norāda uz ar šo darbību saistītās pavilkšanas iestatījumu detalizētu informāciju, ja attiecināms

- **ui_mode_setting** — atlasītais UI režīms (tumšs, gaišs, sistēmas noklusējuma, zems akumulatora uzlādes līmenis utt.)

#### <a name="sidebar_action"></a>sidebar_action

Ļauj mums noteikt situācijas, kad ir iespējami negatīva ietekme uz jūsu iespēju konfigurēt lietojumprogrammas iestatījumus, piemēram, paziņojumu iestatījumus, primāro pasta kontu un e-pasta paraksta konfigurēšanu.

Outlook Mobile datu lauki, kas šim notikumam ir kopīgi iOS un Android:

- **Account** — izseko ar notikumu saistītajam kontam un tā datiem; šajos datos izsekotās vērtības ir norādītas vispārīgajā lauka dokumentācijā 

- **action** — izseko sānu joslas darbības tipam, piemēram, noraidīts, atlasīta palīdzības poga, pasta sānu josla utt. 

- **from_favorites** — izseko, vai darbība ir izcēlusies no izlasē esoša vienuma 

- **mail_folder_type** — norāda mapes veidu, kas tika atlasīts sānu joslas darbības laikā, ja attiecināms.

- **sidebar_type** — izseko ar šo notikumu saistītās sānu joslas tipu, piemēram, e-pasts vai kalendārs, lai palīdzētu mums nodrošināt pareizu navigācijas no izlases iestatījuma darbību

Tiek apkopoti šādi lauki: 

- **account_type** — norāda konta autentifikācijas tipu, piemēram, Gmail, Outlook utt. 

- **account_has_groups** — palīdz mums pārliecināties par to, vai grupas ir konfigurētas pareizi, ja kontam tādas ir

- **calendar_accounts_count** — jūsu kalendāra kontu skaits, lai palīdzētu mums pārliecināties par to, ka jūsu kalendāra konti ir konfigurēti pareizi 

- **calendar_apps_count** — jūsu kalendāra lietojumprogrammu skaits, lai palīdzētu mums pārliecināties par to, ka jūs interesējošās kalendāra lietojumprogrammas ir konfigurētas pareizi 

- **calendar_type** — jūsu kalendāra tips (primārais kalendārs, grupas kalendārs utt.) 

- **cid_type** — norāda uz konta veidu, piemēram, komerciālais konts vai Outlook.com konts.

- **has_favorite_folders** — palīdz mums pārliecināties par to, ka izlases mapes ir konfigurētas pareizi 

- **has_favorite_people** — palīdz mums pārliecināties par to, ka izlases personas/kontaktpersonas ir konfigurētas pareizi 

- **has_group_calendar** — palīdz mums pārliecināties par to, ka jūsu grupu kalendāri ir konfigurēti pareizi, ja tādi ir 

- **has_group_calendar_account** — palīdz mums pārliecināties par to, ka jūsu grupu kalendāri ir konfigurēti pareizi, ja tādi ir 

- **has_group_toggled** — ja jūs pārslēdzāt grupu kalendārus, palīdz mums pārliecināties par to, ka šis iestatījums ir konfigurēts pareizi 

- **interesting_calendars_accounts_count** — jūsu interesējošo kalendāra kontu skaits, kas palīdz mums pārliecināties par to, ka jūsu interesējošo kalendāru konti ir konfigurēti pareizi 

- **mail_accounts_count** — kopējais e-pasta kontu skaits sānu joslā, lai pārliecinātos par pareizu konfigurāciju 

- **mail_folder_type** — mapes tips, kuru lietotājs nospieda, lai pārliecinātos, ka tā ir konfigurēta pareizi. Var iekļaut dzēsto ziņojumu mapi, mēstuļu mapi vai nosūtīto ziņojumu mapi. 

- **mail_inbox_unread_count** — palīdz mums pārliecināties par to, ka nelasīto ziņojumu skaits tiek ir konfigurēts un tiek parādīts pareizi 

- **mail_subfolder_depth** — palīdz mums nodrošināt sekmīgu lietotāja e-pasta apakšmapju konfigurācijas parādīšanu

#### <a name="storeop"></a>StoreOp

Tiek apkopots, kad lietotājs mēģina atvērt ar IRM aizsargātu dokumentu vai lietot IRM aizsardzību.  Tas satur informāciju, kas ir nepieciešama pareizai tādu problēmu izmeklēšanai un diagnosticēšanai, kas notiek tiesību pārvaldības pakalpojuma licences saglabāšanas darbības laikā. 

Tiek apkopoti tālāk norādītie lauki.

- **AppInfo.ClientHierarchy** — klienta hierarhija, kas norāda, ka lietojumprogramma darbojas ražošanas vidē vai izstrādātāja vidē

- **AppInfo.Name** — lietojumprogrammas nosaukums

- **AppInfo.Version** — lietojumprogrammas versija

- **iKey** — pieteikšanās pakalpojuma servera ID

- **RMS.ApplicationScenarioId** — scenārija ID, ko nodrošina lietojumprogramma

- **RMS.ContentId** — satura ID lietotāja licencē

- **RMS.Duration** — kopējais laiks API izsaukuma veikšanai

- **RMS.DurationWithoutExternalOps** — kopējais patērētais laiks mīnus ārējās operācijas, piemēram, tīkla latentums.

- **RMS.ErrorCode** — atgrieztais kļūdas kods, ja tāds ir, no darbības

- **RMS.HttpCall** — norāda, vai ir HTTP operācija

- **RMS.LicenseFormat** — licences formāts: XrML vai JSON

- **RMS.OperationName** — darbības nosaukums

- **RMS.Result** — darbība sekmīga vai neizdevās

- **RMS.ScenarioId** — scenārija ID, ko definē tiesību pārvaldības pakalpojuma klients

- **RMS.SDKVersion** — tiesību pārvaldības pakalpojuma klienta versija

- **RMS.ServerType** — tiesību pārvaldības pakalpojuma servera tips 

- **RMS.StatusCode** — darbības rezultāta statusa kods

- **RMS.Url** — tiesību pārvaldības pakalpojuma servera vietrādis URL

#### <a name="watchappv2"></a>watchAppV2

Šis notikums ļauj mums atklāt un novērst iespējamās problēmas ar jūsu Apple Watch, piemēram, ziņojumu saņemšana vai atbildēšana uz e-pasta ziņojumiem.

Tiek apkopoti šādi lauki: 

- **app_action** — norāda uz darbībām, kuras lietotājs veica Apple Watch, piemēram, “archive_message”, kas palīdz mums atklāt ar konkrētu darbību saistītas problēmas, piemēram, veiksmīga ziņojumu arhivēšana ar Apple Watch

- **is_watch_app_installed** — norāda, vai lietotājs ir instalējis mūsu Apple Watch lietojumprogrammu savā ierīcē

- **is_complication_enabled** — norāda, vai lietotājs ir pievienojis Outlook savam Apple Watch ekrānam, lai palīdzētu mums atklāt ar Apple Watch ekrāniem saistītās problēmas

- **watch_os** — norāda instalēto Apple Watch operētājsistēmas versiju, lai palīdzētu mums atklāt ar konkrētām Apple Watch operētājsistēmas versiju saistītās problēmas


### <a name="application-status-and-boot-subtype"></a>*Lietojumprogrammas statuss un palaišanas apakštips*

Nosaka, vai ir notikuši konkrēti līdzekļu notikumi, piemēram, startēšana vai apturēšana, un vai līdzeklis darbojas.

#### <a name="app_startup"></a>app_startup

Šis notikums ļauj mums atklāt un novērst problēmas, ja Outlook palaišana notiek lēni vai nepilnīgi, apgrūtinot mūsu lietotājiem mūsu lietojumprogrammas izmantošanu.  Tiek iekļauta informācija par konkrētiem iespējotajiem līdzekļiem un to, cik ilgu laiku aizņēma atsevišķi palaišanas posmi.

Tiek apkopoti šādi lauki: 

- **attach_base_context_millis** — norāda laiku starp bāzes konteksta palaišanu un OnCreate() palaišanu

- **device_ram_in_mb** — ierīcē pieejamā RAM atmiņa

- **has_company_portal** — norāda, vai ir instalēta uzņēmuma portāla lietojumprogramma

- **hx_okhttp_mode** — norāda, vai jaunā e-pasta sinhronizēšanas pakalpojuma komponents izmanto OKHttp, lai nosūtītu un saņemtu HTTP-balstītus tīkla pieprasījumus

- **initial_activity_name** — Android darbība, kas palaida lietojumprogrammu

- **manufacturer** — ierīces ražotājs

- **model** — ierīces modelis.

- **on_create_millis** — metodē onCreate() pavadītais laiks

- **on_resume_millis** — metodē onResume() pavadītais laiks

- **time_until_attach** — laiks starp klases ielādi un bāzes konteksta palaišanu

- **total_millis** — kopējais laiks no klases ielādes sākuma līdz Android darbības atsākšanas pabeigšanas

#### <a name="boot_time"></a>boot_time 

Šis notikums ļauj mums noteikt, kad notiek kritiskas lietojumprogrammas kļūdas, kas izraisa jūsu lietojumprogrammas avāriju vai nopietnas problēmas, kuru rezultātā jūs redzat tukšas rindas jūsu iesūtnē. Šis notikums apkopo informāciju, kas ļauj mums kategorizēt un klasificēt problēmas, lai noteiktu problēmu ietekmes pakāpi uz klientiem. 

Tiek apkopoti šādi lauki:

- **black_list_reason** — norāda, vai pastāv iemesls šo datu atmešanai. Daži piemēri iekļauj palaišanu attālinātā paziņojuma dēļ un fona ieneses dēļ.

- **step0_main** — norāda laiku, kas bija nepieciešams Outlook sasniegtu galveno “darbību”, kas ir Apple definēta darbība.

- **step1_appWillFinishLaunching** — norāda mums laiku, kas bija nepieciešams Outlook, lai pārietu no “galvenās” darbības līdz “appWillFinishLaunching” darbībai, kas ir Apple definēta darbība.

- **step2_appDidFinishLaunching** — norāda mums laiku, kas bija nepieciešams Outlook, lai pārietu no “appWillFinishLaunching” darbības līdz ““appDidFinishLaunching” darbībai, kas ir Apple definēta darbība.

- **step3_engineStarted** — norāda mums laiku, ka bija nepieciešams Outlook, lai pārietu no “appDidFinishLaunching” darbības līdz lietojumprogrammas dzinēja palaišanas, kas veic datu uzglabāšanu un sinhronizēšanu. 

- **step4_runLoopFirstIdle** — norāda mums laiku, kas bija nepieciešams Outlook, lai pārietu no “engineStarted” darbības līdz brīdim, kad vairs nav jāveic papildu darbi.

- **total_time** — norāda kopējo laiku, kas bija nepieciešams Outlook, lai pabeigtu sāknēšanas procesu.

#### <a name="dnslookupop"></a>DnsLookupOp

Tiek apkopots, kad lietotājs mēģina atvērt ar IRM aizsargātu dokumentu vai lietot IRM aizsardzību.  Tas satur informāciju, kas ir nepieciešama pareizai tādu problēmu izmeklēšanai un diagnosticēšanai, kas notiek DNS informācijas uzmeklēšanas darbības laikā. 

Tiek apkopoti tālāk norādītie lauki.

- **AppInfo.ClientHierarchy** — klienta hierarhija, kas norāda, ka lietojumprogramma darbojas ražošanas vidē vai izstrādātāja vidē

- **AppInfo.Name** — lietojumprogrammas nosaukums

- **AppInfo.Version** — lietojumprogrammas versija

- **iKey** — pieteikšanās pakalpojuma servera ID

- **RMS.ApplicationScenarioId** — scenārija ID, ko nodrošina lietojumprogramma

- **RMS.Duration** — kopējais laiks darbības veikšanai

- **RMS.DurationWithoutExternalOps** — kopējais patērētais laiks mīnus ārējās operācijas, piemēram, tīkla latentums.

- **RMS.ErrorCode** — atgrieztais kļūdas kods, ja tāds ir, no darbības

- **RMS.HttpCall** — norāda, vai pastāv HTTP operācija

- **RMS.LicenseFormat** — licences formāts: XrML vai JSON

- **RMS.NoOfDomainsSearched** — meklēto domēnu skaits    

- **RMS.NoOfDomainsSkipped** — izlaisto domēnu skaits 

- **RMS.Result** — darbība sekmīga vai neizdevās

- **RMS.ScenarioId** — scenārija ID, ko definē tiesību pārvaldības pakalpojuma klients

- **RMS.SDKVersion** — tiesību pārvaldības pakalpojuma klienta versija

- **RMS.ServerType** — tiesību pārvaldības pakalpojuma servera tips 

- **RMS.StatusCode** — darbības rezultāta statusa kods

#### <a name="first_visible"></a>first_visible

Šis notikums ļauj mums atklāt pirmo reizi, kad lietotājs ar nodomu palaiž lietojumprogrammu. Šis notikums ir nepieciešams, lai nodrošinātu lietojumprogrammas veiksmīgu darbību oriģinālā aprīkojuma ražotāja (OEM) būvējumos. 

Tiek apkopoti šādi lauki:

- **is_oem** — izsekošanas lauks, kas norāda uz to, vai lietojumprogramma darbojas OEM variantā

- **is_system_install** — izsekošanas lauks, kas izseko iepriekš instalēta rekvizītu failu esamību, kas norāda, ka šī instalācija ir OEM 

- **manufacturer** — ierīces ražotājs

- **model** — ierīces modelis

- **systemFlagSet** — Android sistēmas karodziņa vērtība (ApplicationInfo. FLAG_SYSTEM), kas norāda, vai lietojumprogramma ir instalēta kā daļa no ierīces sistēmas

#### <a name="getuserop"></a>GetUserOp

Tiek apkopots, kad lietotājs mēģina atvērt ar IRM aizsargātu dokumentu vai lietot IRM aizsardzību.  Tas satur informāciju, kas ir nepieciešama pareizai tādu problēmu izmeklēšanai un diagnosticēšanai, kas notiek lietotāja sertifikātu iegūšanas darbības laikā. 

Tiek apkopoti tālāk norādītie lauki.

- **AppInfo.ClientHierarchy** — klienta hierarhija, kas norāda, ka lietojumprogramma darbojas ražošanas vidē vai izstrādātāja vidē

- **AppInfo.Name** — lietojumprogrammas nosaukums

- **AppInfo.Version** — lietojumprogrammas versija

- **iKey** — pieteikšanās pakalpojuma servera ID

- **RMS.ApplicationScenarioId** — scenārija ID, ko nodrošina lietojumprogramma

- **RMS.ContentId** — satura ID

- **RMS.Duration** — kopējais laiks darbības veikšanai

- **RMS.DurationWithoutExternalOps** — kopējais patērētais laiks mīnus ārējās operācijas, piemēram, tīkla latentums.

- **RMS.ErrorCode** — atgrieztais kļūdas kods no darbības

- **RMS.HttpCall** — norāda, vai ir HTTP operācija

- **RMS.LicenseFormat** — licences formāts: XrML vai JSON

- **RMS.Result** — darbība sekmīga vai neizdevās

- **RMS.ScenarioId** — scenārija ID, ko definē tiesību pārvaldības pakalpojuma klients

- **RMS.SDKVersion** — tiesību pārvaldības pakalpojuma klienta versija

- **RMS.ServerType** — tiesību pārvaldības pakalpojuma servera tips 

- **RMS.StatusCode** — darbības rezultāta statusa kods

- **RMS.Type** — lietotāja informācijas tips

#### <a name="httpop"></a>HttpOp

Tiek apkopots, kad lietotājs mēģina atvērt ar IRM aizsargātu dokumentu vai lietot IRM aizsardzību.  Tas satur informāciju, kas ir nepieciešama pareizai tādu problēmu izmeklēšanai un diagnosticēšanai, kas notiek http pieprasījuma darbības laikā.

Tiek apkopoti tālāk norādītie lauki.

- **AppInfo.ClientHierarchy** — klienta hierarhija, kas norāda, ka lietojumprogramma darbojas ražošanas vidē vai izstrādātāja vidē
    
- **AppInfo.Name** — lietojumprogrammas nosaukums

- **AppInfo.Version** — lietojumprogrammas versija

- **iKey** — pieteikšanās pakalpojuma servera ID

- **RMS.ApplicationScenarioId** — scenārija ID, ko nodrošina lietojumprogramma

- **RMS.CallBackStatus** — autentifikācijas atzvanīšanas atgrieztā rezultāta statuss

- **RMS.CallbackTime** — autentifikācijas atzvanīšanas patērētais laiks 

- **RMS.CorrelationId** — http pieprasījuma korelācijas ID

- **RMS.DataSize** — HTTP pieprasījuma datu lielums

- **RMS.Duration** — kopējais laiks darbības veikšanai

- **RMS.DurationWithoutExternalOps** — kopējais patērētais laiks mīnus ārējās operācijas, piemēram, tīkla latentums.

- **RMS.ErrorCode** — atgrieztais kļūdas kods, ja tāds ir, no darbības

- **RMS.HttpCall** — norāda, vai pastāv ligzdota HTTP operācija 

- **RMS.LicenseFormat** — licences formāts: XrML vai JSON

- **RMS.OperationName** — darbības nosaukums

- **RMS.Result** — darbība sekmīga vai neizdevās

- **RMS.ScenarioId** — scenārija ID, ko definē tiesību pārvaldības pakalpojuma klients

- **RMS.SDKVersion** — tiesību pārvaldības pakalpojuma klienta versija

- **RMS.ServerType** — tiesību pārvaldības pakalpojuma servera tips 

- **RMS.StatusCode** — darbības rezultāta statusa kods

- **RMS.Url** — tiesību pārvaldības pakalpojuma servera vietrādis URL

- **RMS.WinhttpCallbackStatus** — WinHTTP atzvanīšanas rezultāta statuss

#### <a name="initialized"></a>Initialized

Ļauj mums analizēt saskarnes darbspēju, kas ļauj mobilajām lietojumprogrammām ienest lietotāja un konfidencialitātes iestatījumus no Office pakalpojumiem, un diagnosticēt savienojamības un konfidencialitātes iestatījumu pakalpojumu problēmas.

Tiek apkopoti šādi lauki:

- **roamingSettingType** — nosaka atrašanās vietu, no kuras tika veikts mēģinājums nolasīt iestatījumus

#### <a name="ipccreateoauth2token"></a>IpcCreateOauth2Token

Tiek apkopots, kad lietotājs mēģina atvērt ar IRM aizsargātu dokumentu vai lietot IRM aizsardzību. Tas satur informāciju, kas ir nepieciešama pareizai tādu problēmu izmeklēšanai un diagnosticēšanai, kas notiek IpcCreateOauth2Token API izsaukuma laikā.

Tiek apkopoti tālāk norādītie lauki.

- **AppInfo.ClientHierarchy** — klienta hierarhija, kas norāda, ka lietojumprogramma darbojas ražošanas vidē vai izstrādātāja vidē
    
- **AppInfo.Name** — lietojumprogrammas nosaukums

- **AppInfo.Version** — lietojumprogrammas versija

- **iKey** — pieteikšanās pakalpojuma servera ID

- **RMS.Duration** — kopējais laiks API izsaukuma veikšanai

- **RMS.DurationWithoutExternalOps** — kopējais patērētais laiks mīnus ārējās operācijas, piemēram, tīkla latentums.

- **RMS.ErrorCode** — atgrieztais kļūdas kods, ja tāds ir, no API izsaukuma

- **RMS.HttpCall** — norāda, vai ir HTTP operācija

- **RMS.Result** — API izsaukums sekmīgs vai neizdevās

- **RMS.ScenarioId** — scenārija ID, ko definē API

- **RMS.SDKVersion** — tiesību pārvaldības pakalpojuma klienta versija

- **RMS.StatusCode** — atgrieztā rezultāta statusa kods

#### <a name="officeandroidandroidoffice16bootlatency"></a>Office.Android.AndroidOffice16BootLatency

Ir būtiski svarīgs, lai fiksētu lietojumprogrammas veiktspējas rādītāju attiecībā uz lietojumprogrammas atbildes laiku no sāknēšanas.  Microsoft to izmanto, lai apkopotu laiku, kas ir nepieciešams lietojumprogrammai, lai atbildētu, kā arī, lai noteiktu scenārijus, kas varat ietekmēt sāknēšanas laiku Word, Excel vai PowerPoint lietojumprogrammās.

Tiek apkopoti šādi lauki:

- **AppLaunchResponsiveTimeInMilliSec** — lietojumprogrammas sāknēšanas atbildes laiks

- **AppSuspendedDuringBoot** — būla, kas norāda, vai lietotne tika aizturēta sāknēšanas laikā

- **CollectionTime** — notikuma laiks

- **FileActivationAttempted** — būla, kas norāda, vai notika faila aktivizēšanas mēģinājums

- **FirstIdleOnAppThreadTimeInMilliSec** — lietojumprogrammas pavediena dīkstāves laiks

- **IsThisFirstLaunch** — būla, kas norāda, vai lietojumprogrammu tiek sāknēta pirmo reizi

- **UserDialogInterruptionDuringBoot** — būla, kas norāda, vai notika lietotāja interfeisa bloķēšana sāknēšanas laikā

#### <a name="officeextensibilityofficejsappactivated"></a>Office.Extensibility.OfficeJS.Appactivated

Ieraksta informāciju par neparedzētu Office izslēgšanu. Tas ļauj mums noteikt produkta avārijas vai, ja tas pārstāj reaģēt, un atrisināt šīs problēmas.

Tiek apkopoti tālāk norādītie lauki:

  - **Data\_AirspaceInitTime:integer — ** Airspace Office komponentes inicializācijai veltītais laiks

  - **Data\_AllShapes:integer —** formu skaits dokumentā

  - **Data\_APIInitTime:integer —** laiks, lai inicializētu Visio API moduli

  - **Data\_AppSizeHeight —** pievienojumprogrammas**-** loga augstums

  - **Data\_AppSizeWidth —** pievienojumprogrammas**-** loga platums

  - **Data\_AppURL —** pievienojumprogrammas URL; reģistrē pilnu URL krātuves pievienojumprogrammām un URL domēnu pievienojumprogrammām, kas nav krātuves pievienojumprogrammas

  - **Data_Doc_AsyncOpenKind:long — ** norāda, vai tika atvērta mākoņa dokumenta kešotā versijā un kura asinhronā atsvaidzināšanas loģika tika izmantota.

  - **Data\_AuthorsCount:integer —** autoru skaits, kuri rediģēja dokumentu šajā sesijā

  - **Data\_BackgroundPages:integer —** fona lapu skaits shēmā

  - **Data\_BootTime:integer —** Visio palaišanai nepieciešamais laiks

  - **Data\_Browser —** pārlūkprogrammas virkne ar informāciju par pārlūkprogrammu, piemēram, tips un versija

  - **Data\_ChildWindowMixedModeTime:integer —** laiks, kas nepieciešams jauktā režīma iespējošanai programmā Visio (atvasinātajam logam var būt atšķirīgs DpiAwareness no primārā loga)

  - **Data\_CommentsCount:integer —** komentāru skaits dokumentā

  - **Data\_ConnectionCount:integer —** datu savienojumu skaits shēmā

  - **Data\_ContentMgrInitTim:integer —** laiks, kas nepieciešams satura pārvaldnieka inicializēšanai

  - **Data\_CreateMainFrameTime:integer —** lieldatora laika izveide

  - **Data\_CreatePaletteTime:integer —** laiks, kas nepieciešams, lai izveidotu globālo krāsu paleti

  - **Data\_DispFormatCount:integer —** datu grafiku skaits shēmā

  - **Data\_Doc\_Ext:string —** dokumenta paplašinājums

  - **Data\_Doc\_Fqdn:string —** dokumentu glabāšanas vieta (SharePoint.com, live.net), pieejama tikai Office 365 domēniem

  - **Data\_Doc\_FqdnHash:string —** dokumenta glabāšanas vietas jaukšana

  - **Data\_Doc\_IsIncrementalOpen:bool —** vai dokuments tika atvērts inkrementāli (jauns līdzeklis, kas atver dokumentu bez vajadzības lejupielādēt visu dokumentu)

  - **Data\_Doc\_IsOpeningOfflineCopy:bool —** vai dokuments tiek atvērts no lokālās kešatmiņas?

  - **Data\_Doc\_IsSyncBacked:bool —** patiess, ja šis ir servera dokuments, kas pastāv lokāli, un ir sinhronizēta ar serveri (piemēram, izmantojot OneDrive vai ODB klienta programmām)

  - **Data\_Doc\_Location:long —** iepriekš definētu vērtību kopa, kas norāda dokumenta glabāšanas vietu (lokālā, SharePoint, WOPI, tīkls utt.)

  - **Data\_Doc\_LocationDetails:long —** iepriekš definētu detalizētākas atrašanās vietas vērtību kopa (mape Temp, lejupielāžu mape, OneDrive dokumenti, OneDrive attēli)

  - **Data\_Doc\_ResourceIdHash:string —** resursu identifikatora jaukšana mākonī saglabātajiem dokumentiem

  - **Data_Doc_RtcType —** norāda, kā reāllaika kanāls (RTC) bija iestatīts pašreizējam failam (atspējots, neatbalstīts, pēc pieprasījuma, vienmēr ieslēgts utt.).

  - **Data\_Doc\_ServerDocId:string —** nemainīgs identifikators mākonī saglabātajiem dokumentiem

  - **Data\_Doc\_SessionId:long —** ģenerēts GUID, kas norāda dokumenta instanci tajā pašā procesa sesijā

  - **Data\_Doc\_SizeInBytes:long —** dokumenta lielums baitos

  - **Data\_Doc\_SpecialChars:long —** gara bitmaska, kas norāda speciālās rakstzīmes dokumenta vietrādī URL vai ceļā

  - **Data\_Doc\_SyncBackedType —** norāda dokumenta veidu (lokālais vai servera) 

  - **Data\_Doc\_UrlHash:string —** pilna vietrāža URL jaukšana mākonī saglabātiem dokumentiem

  - **Data\_DpiAwarenessTime:integer —** laiks, lai iespējotu DPI informāciju par katru monitoru

  - **Data\_DurationToCompleteInMilliseconds:double —** laiks milisekundēs, lai pabeigtu saglabāšanu

  - **Datu\_ErrorCode:int —** : 0 sekmīgai darbībai, vesels skaitlis kļūdai saglabāšanas laikā

  - **Data\_FailureReason:integer —** asinhronas saglabāšanas kļūmes iemesls

  - **Data\_FileExtension —** atvērtas shēmas faila paplašinājums

  - **Data\_FileHasDGMaster:bool —** patiess, ja failā ir datu grafika

  - **Data\_FileHasImportedData:bool —** patiess, ja failā ir importēti dati

  - **Data\_FileHasShapesLinked:bool —** patiess, ja failā ir saistītas formas ar datiem

  - **Data\_FileIOBytesRead:int —** saglabāšanas laikā nolasīto baitu kopskaits

  - **Data\_FileIOBytesReadSquared:int —** Data\_FileIOBytesRead vērtība kvadrātā

  - **Data\_FileIOBytesWritten:int —** saglabāšanas laikā ierakstīto baitu kopskaits

  - **Data\_FileIOBytesWrittenSquared:int —** Data\_FileIOBytesWritten vērtība kvadrātā

  - **Data\_FilePathHash:binary** — faila ceļa binārā jaukšana

  - **Data\_FilePathHash: binary** — faila ceļa GUID

  - **Data\_FileSize —** dokumenta lielums baitos

  - **Data\_ForegroundPages:integer —** priekšplāna lapu skaits shēmā

  - **Data\_ForegroundShapes:integer —** priekšplāna lapās esošo formu skaits ar veselu skaitli

  - **Data\_GdiInitTime:integer —** laiks, lai inicializētu GDI moduli

  - **Data\_HasCoauthUserEdit:bool —** patiess, ja dokuments tika rediģēts koprediģēšanas sesijā

  - **Data\_HasCustomPages:bool —** patiess, ja dokumentā ir pielāgotas lapas

  - **Data\_HasCustPatterns:bool —** patiess, ja failā ir pielāgotas shēmas

  - **Data\_HasDynConn:bool —** patiess, ja dokumentā ir dinamisks savienojums

  - **Data\_HasScaledPages:bool —** patiess, ja dokumentā ir mērogotas lapas

  - **Data\_HasUserWaitTime:bool —** patiess, ja saglabāšanas laikā tiek parādīts faila dialoglodziņš

  - **Data\_InitAddinsTime:integer —** laiks, lai inicializētu un ielādētu COM pievienošanu

  - **Data\_InitBrandTime:integer —** nepieciešamais laiks, lai inicializētu uzplaiksnījuma ekrānu un marķētos Office komponentus

  - **Data\_InitGimmeTime:integer — ** laiks, lai inicializētu Office komponentu

  - **Data\_InitLicensingTime:integer — ** laiks, lai inicializētu licencēšanas Office komponentu

  - **Data\_InitMsoUtilsTime:integer —** MSOUTILS Office komponenta inicializācijas laiks

  - **Data\_InitPerfTime:integer —** Office veiktspējas komponenta inicializācijas laiks

  - **Data\_InitTCOTime:integer —** nepieciešamais laiks, lai inicializētu Office komponenta pārvaldnieku

  - **Data\_InitTrustCenterTime:integer — ** laiks, lai inicializētu Office komponenta drošības kontroles centru

  - **Data\_InitVSSubSystemsTime:integer —** nepieciešamais laiks, lai inicializētu Visio komponentus

  - **Data\_InternalFile:bool —** patiess, ja fails ir iekšējais fails. Piemēram, šablons

  - **Data\_IsAsyncSave:bool —** patiess, ja saglabāšana bija asinhrona

  - **Data\_IsAutoRecoveredFile:bool —** patiess, ja fails tika automātiski atkopts

  - **Data\_IsEmbedded:bool —** patiess, ja Visio fails tika iegults citā programmā

  - **Data\_IsInfinitePageDisabledForAllPages:bool —** ja neierobežota lappuse ir atspējota visās dokumenta lapās (patiess)

  - **Data\_IsIRMProtected:bool —** patiess, ja failam ir informācijas tiesību piekļuves aizsardzība

  - **Data\_IsLocal:bool —** patiess, ja fails ir lokāls

  - **Data\_IsRecoverySave:bool —** patiess, ja atkopšana izraisīja droši stāvokli

  - **Data\_IsShapeSearchPaneHiddenState:bool —** patiess, ja dokumentā ir paslēpta formas meklēšanas rūts

  - **Data\_IsSmartDiagramPresentInActivePageOfFile:bool —** būls, patiess, ja viedā datu vizuālā shēma ir aktīvajā faila lapā

  - **Data\_IsSmartDiagramPresentInFile:bool —** būls, patiess, ja failā ir viedā datu vizuālā shēma

  - **Data\_IsUNC:bool —** patiess, ja dokumenta ceļš atbilst universālajai nosaukumdošanas metodei

  - **Data\_LandscapePgCount:integer —** shēmas lappušu skaits, kurās ir ainavas orientācija

  - **Data\_Layers:integer —** slāņu skaits shēmā

  - **Data\_LoadProfileTime:integer —** Office Profiler ielādes laiks

  - **Data\_LoadRichEditTim:integer —** bagātināta rediģēšanas komponenta ielādes laiks

  - **Data\_LoadVisIntlTime:integer —** Visio starptautiskā DLL ielādes laiks

  - **Data\_Location:integer —** faila atrašanās vieta, no kuras tas tika atvērts 0 lokāla, 1, tīkls, 2, SharePoint, 3 – tīmeklis

  - **Data\_MasterCount:integer —** šablonu skaits shēmā

  - **Data\_MaxCoauthUsers:integer —** maksimālais lietotāju skaits jebkurā brīdī koprediģēšanas sesijā Filesystem, Registry, First Party, SDX

  - **Data\_MaxTilesAutoSizeOn:integer —** maksimālais elementu skaits lapā, kurā iespējots automātiskais lielums

  - **Data\_MsoBeginBootTime:integer —** MSO palaišanas laiks

  - **Data\_MsoDllLoadTime:integer —** MSO DLL ielādes laiks

  - **Data\_MsoEndBootTime:integer —** MSO palaišanas beigu laiks

  - **Data\_MsoInitCoreTime:integer —** MSO Office komponenta inicializēšanas laiks

  - **Data\_MsoInitUITime:integer —** MSO Office komponenta UI inicializēšanas laiks

  - **Data\_MsoMigrateTime:integer —** laiks, lai migrētu lietotāja iestatījumus pirmajā sāknēšanā, ja lietotājs veica jaunināšanu no vecākas versijas

  - **Data\_NetworkIOBytesRead:int —** saglabāšanas laikā nolasīto tīkla baitu kopskaits

  - **Data\_NetworkIOBytesReadSquared:int —** Data\_NetworkIOBytesRead vērtība kvadrātā

  - **Data\_FileIOBytesWritten:int —** saglabāšanas laikā ierakstīto baitu kopskaits

  - **Data\_NetworkIOBytesWrittenSquared: int —** NetworkIOBytesWritten vērtība kvadrātā

  - **Data\_OartStartupTime:integer — ** laiks, lai inicializētu OART Office komponentu

  - **Data\_OleInitTime:integer —** OLE Office komponenta inicializācijas laiks

  - **Data\_OpenDurationTimeInMs:integer —** laiks milisekundēs, lai atvērtu failu

  - **Data\_OriginatedFromTemplateID:integer —** tās veidnes identifikators, kurā tika izveidota shēma NULL trešo pušu veidnēm

  - **Data\_Pages:integer —** lapu skaits dokumentā

  - **Data\_PositionToolbarsTime:integer —** laiks, lai rīkjoslas novietotu vietā

  - **Data\_ReadOnly:bool —** patiess, ja fails ir tikai lasāms

  - **Data\_RecordSetCount:integer —** shēmā iestatīto ierakstu skaits

  - **Data\_RecoveryTime:integer —** laiks, lai atvērtu atkopšanas failus

  - **Data\_ReviewerPages:integer —** recenzenta lapu skaits shēmā

  - **Data\_RibbonTime:integer —** laiks, lai parādītu statusa joslu

  - **Data\_RoamingSettingsStartupTime:integer —** laiks, lai izveidotu un ielādētu visus pašreiz viesabonētos Visio iestatījumus

  - **Data\_SchemeMgrStartupTime:integer —** laiks, lai inicializētu shēmu pārvaldnieku

  - **Data\_SDX\_AssetId —** pastāv TIKAI krātuves pievienojumprogrammām. OMEX nodrošina pievienojumprogrammai AssetId, kad tā tiek pārvietota uz krātuvi

  - **Data\_SDX\_BrowserToken —** identifikators, kas atrodas pārlūkprogrammas kešatmiņā

  - **Data\_SDX\_HostJsVersion —** šī ir platformai atbilstošā Office.js versija (piemēram, outlook web16.01.js); satur pievienojumprogrammas API Surface

  - **Data\_SDX\_Id —** pievienojumprogrammas GUID, kas to unikāli identificē

  - **Data\_SDX\_InstanceId —** attēlo pievienojumprogrammas dokumentu pāri

  - **Data\_SDX\_MarketplaceType —** norāda, no kurienes instalēta pievienojumprogramma

  - **Data\_SDX\_OfficeJsVersion —** šī ir Office.js versija, kas novirzīs uz platformai atbilstošo versiju.

  - **Data\_SDX\_versija —** pievienojumprogrammas versija

  - **Data\_ShellCmdLineTime:integer —** laiks, lai parsētu un izpildītu komandrindas čaulas komandas

  - **Data\_Size:long** — failu lielums baitos

  - **Data\_StartEndTransactionTime:integer —** laiks, lai inicializētu Visio komponentus

  - **Data\_STNInitTime:integer —** laiks, lai inicializētu šablona loga konfigurēšanu

  - **Data\_Tag:string —** unikālais identifikators, lai identificētu notikumu Saglabāt kā

  - **Data\_ThemeCount:integer —** dizainu skaits shēmā

  - **Data\_TimeStamp —** laikspiedols, kad dokuments tika aizvērts

  - **DataUIInitTime:integer —** UI inicializācijas laiks

  - **DataWasSuccessful:bool —** patiess, ja notikusi veiksmīga saglabāšana

  - **Data\_WinLaunchTime:integer —** laiks, lai palaistu Visio startēšanas rūti, utt.)

  - **Office.Visio.FileCharacteristicsVisio —** tver faila rekvizītus Visio C2R un Dev16 failu startēšanas laikā. Šis notikums palīdz mums kategorizēt un atkļūdot kļūdas saistībā ar dokumentu rekvizītiem, kas savukārt ļauj ātrāk atrast problēmu cēloņus un tos novērst.

  - **Office.Visio.Shared.BootStats —** šis notikums apkopo Visio Win32 lietojumprogrammas startēšanas laiku. Tas apkopo dažādus laukus saistībā ar dažādu komponentu startēšanu, piemēram, lentes ielādes laiku un programmas inicializācijas laiku. Šis notikums tiek izmantots, lai noteiktu Visio startēšanas izpildi.

  - **Office.Visio.Shared.FileOpen —** šis notikums apkopo failu atvēršanas statistiku programmā Visio. Šis notikums tiek izmantots, lai pārraudzītu failu sekmīgas/nesekmīgas atvēršanas skaitu, un kartē to ar dažiem rekvizītiem, piemēram, faila lielumu. Faila rekvizīti sniedz mums iespēju ātrāk atkļūdot problēmas un uzzināt to cēloņus.

  - **Office.Visio.Shared.Filesave —** šis notikums apkopo failu saglabāšanas statistiku programmā Visio. Šis notikums tiek izmantots, lai pārraudzītu failu sekmīgas/nesekmīgas saglabāšanas skaitu, un kartē to ar dažiem rekvizītiem, piemēram, faila lielumu un atrašanās vietu, kur tas tiek saglabāts, piemēram, mākonī/lokāli. Faila rekvizīti sniedz mums iespēju ātrāk atkļūdot problēmas un uzzināt to cēloņus.

  - **Office.Visio.Shared.FilesaveAs —** šis notikums apkopo failu “saglabāt kā” statistiku programmā Visio. Šis notikums tiek izmantots, lai pārraudzītu failu sekmīgas/nesekmīgas saglabāšanas skaitu, un kartē to ar dažiem rekvizītiem, piemēram, faila lielumu un atrašanās vietu, kur tas tiek saglabāts, piemēram, mākonī/lokāli. Faila rekvizīti sniedz mums iespēju ātrāk atkļūdot problēmas un uzzināt to cēloņus.

  - **Office.Visio.Shared.PostSave —** šis notikums tver kļūmes iemeslu saistībā ar kļūmi, izpildot darbību “saglabāt kā”.

  - **Office.Visio.VisioFileSaveAs —** šis notikums apkopo failu “saglabāt kā” statistiku programmā Visio Dev16. Šis notikums tiek izmantots, lai pārraudzītu failu sekmīgas/nesekmīgas darbības “saglabāt kā” skaitu, un kartē to ar dažiem rekvizītiem, piemēram, faila lielumu un atrašanās vietu, kur tas tiek saglabāts, piemēram, mākonī/lokāli. Faila rekvizīti sniedz mums iespēju ātrāk atkļūdot problēmas un uzzināt to cēloņus.

  - **Office.Visio.VisioFileSaveAsync —** šis notikums apkopo failu asinhronas saglabāšanas statistiku programmā Visio Dev16. Šis notikums tiek izmantots, lai pārraudzītu failu sekmīgas/nesekmīgas asinhronās saglabāšanas darbību skaitu, un kartē to ar dažiem rekvizītiem, piemēram, faila lielumu un atrašanās vietu, kur tas tiek saglabāts, piemēram, mākonī/lokāli. Faila rekvizīti sniedz mums iespēju ātrāk atkļūdot problēmas un uzzināt to cēloņus.

  - **Office.Visio.VisioFileSaveSync —** šis notikums apkopo failu sinhronas saglabāšanas statistiku programmā Visio Dev16. Šis notikums tiek izmantots, lai pārraudzītu failu sekmīgas/nesekmīgas sinhronās saglabāšanas darbību skaitu, un kartē to ar dažiem rekvizītiem, piemēram, faila lielumu un atrašanās vietu, kur tas tiek saglabāts, piemēram, mākonī/lokāli. Faila rekvizīti sniedz mums iespēju ātrāk atkļūdot problēmas un uzzināt to cēloņus. Šis notikums palīdz mums pārraudzīt faila saglabāšanas kļūmju iemeslus.

#### <a name="officeextensibilitysandboxodpactivationhanging"></a>Office.Extensibility.Sandbox.ODPActivationHanging

Apkopo gadījumus, kad Office programmas palaišana aizņem neparedzēti daudz laika (> 5 sek.). Izmanto, lai atklātu un novērstu problēmas ar Office pievienojumprogrammu palaišanu.
 
Tiek apkopoti tālāk norādītie lauki.

- **AppId** — lietojumprogrammas ID.

- **AppInfo** — dati par pievienojumprogrammas veidu (uzdevumrūts vai UILess, vai iegulšanas utt.) un nodrošinātāja veidu (omen, SharePoint, filesystem utt.).

- **AppInstanceId** — lietojumprogrammas instances ID. 

- **AssetId** — lietojumprogrammas līdzekļa ID.

- **NumberOfAddinsActivated** — aktivēto pievienojumprogrammu skaits.

- **RemoterType** — norāda pievienojumprogrammas aktivēšanai izmantotā attālinātāja veidu (uzticams, neuzticams, Win32webView, uzticams UDF utt.).

- **StoreType** — lietojumprogrammas izcelsme.

- **TimeForAuth** — autentifikācijai iztērētais laiks. 

- **TimeForSandbox** — smilškastei iztērētais laiks.

- **TimeForServerCall** — saziņai ar serveri iztērētais laiks. 

- **TotalTime** — iztērētais laiks kopā.

#### <a name="onenoteappappbootcomplete-previous-name-officeonenoteandroidappappbootcomplete"></a>OneNote.App.AppBootComplete *(iepriekšējais nosaukums)*, Office.OneNote.Android.App.AppBootComplete 

Kritiskais signāls, kas tiek lietots, lai nodrošinātu, ka jaunie lietotāji (Microsoft konts) var sekmīgi palaist un lietot OneNote pirmo reizi.  Tek izmantota kritiskas regresijas atklāšanai OneNote lietojumprogrammā un pakalpojuma darbspējā.  Ja lietotājiem pirmo reizi neizdodas palaist lietojumprogrammu, tiks aktivizēts kritiskais incidents.

Tiek apkopoti šādi lauki: 

- **ACTIVITY_BOOT_TIME_IN_MS** — aktivitātes izveides pabeigšanai veltītais laiks

- **ACTIVITY_NAME** — aktivitātes, kas tiek atvērta pēc sāknēšanas, nosaukums 

- **ANY_DIALOG_SHOWN** — norāda, vai sāknēšanas laikā tiek rādīts dialoglodziņš

- **APP_SUSPEND_DURING_EVENT** — norāda, vai sāknēšana bija paredzēta

- **APP_THREAD_CREATION_WAIT_TIME_TIME_FOR_APP_THREAD_CREATION** — laiks, kas tika veltīts lietojumprogrammas pavedienu izveidošanai

- **AVAILABLE_MEMORY_IN_MB** — ierīces kopējā pieejamā atmiņa 

- **AVG_SNAPSHOT_POPULATION_TIME** — vidējais laiks, kas veltīts piezīmju grāmatiņas struktūru ienešanai, izmantojot lietojumprogrammu

- **BOOT_END_AT_VIEW** — aktivitātes nosaukuma apakškategorija (skata nosaukums)

- **BOOT_SNAPSHOTS** — detalizēta informācija par piezīmju grāmatiņas struktūru ienešanu lietojumprogrammā izmantotajam kontam(-iem)

- **COREAPP_STARTUP_ACCOUNT_SETUP_STARTUP_ACCOUNT_SETUP** — SSO pieredzes pārbaudei un iniciēšanai nepieciešamais laiks

- **CRASH_INTERACTION_DURING_BOOT> 0** — norāda, vai lietojumprogramma avarēja pēdējās sesijas laikā

- **DALVIK_HEAP_LIMIT_IN_MB** — novecojis

- **DELAY_LOAD_STICKY_NOTES** — norāda, vai piezīmju lapiņas ir aizkavētas

- **FISHBOWL_SHOWN_DURING_EVENT** — norāda uz gadījumiem, kuros saturs nav sinhronizēts

- **HAS_LOGCAT_LOGGING_IMPACT_ON_BOOT** — norāda, ka sāknēšanas laiku ietekmē žurnāli

- **INIT_SNAPSHOT_DURATION** — piezīmju grāmatiņas struktūras iegūšanai lietotāja kontam(iem) veltītais laiks

- **IS_COLD_BOOT** — norāda, vai lietojumprogramma tiek sāknēta, kad lietojumprogramma nedarbojas fonā

- **IS_FIRST_LAUNCH** — norāda, vai šī ir pirmā reize, kad lietojumprogramma ir palaista ierīcē.

- **IS_FOLDABLE_TYPE** — norāda, vai ierīce ir salokāma ierīce

- **IS_PHONE** — norāda, vai ierīce ir tālrunis vai planšetdators

- **IS_RECENT_PAGES_AVAILABLE_ON_FRAGMENT_CREATION** — norāda, vai lietotāja interfeiss ir gatavs, un gaida, kad saturs būs pieejams 

- **IS_REHYDRATE_LAUNCH** — norāda, vai sistēma apturēja lietojumprogrammas darbību

- **IS_UPGRADE** — norāda, vai lietojumprogramma tiek palaista pēc jaunināšanas

- **JOT_MAIN_APP_CREATE_TIME_MAIN_APP_CREATE_TIME** — JOT komponenta (kopīgotā koda komponents) izveidei veltītais laiks 

- **JOT_MAIN_APP_INIT_TIME_MAIN_APP_INIT_TIME** — JOT komponenta inicializācijas laiks

- **LAUNCH_POINT** — norāda, vai lietojumprogramma ir atvērta no logrīka vai lietojumprogrammas ikonas vai hipersaites, vai koplietota utt.

- **MSO_ACTIVATION_TIME_ACTIVATION_TIME** — MSO inicializācijas laiks

- **NATIVE_LIBRARIES_LOAD_TIME** — bibliotēku ielādei veltītais laiks

- **NAVIGATION_CREATE_TO_NAVIGATION_RESUME_CREATE_TO_NAVIGATION_RESUME** — navigācijas pabeigšanas laiks

- **NAVIGATION_RESUME_TO_BOOT_END_RESUME_TO_BOOT_END** — lapas ielādes aizkaves pēc sāknēšanas noteikšanai veltītais laiks

- **NAVIGATION_SET_CONTENT_VIEW_TIME_SET_CONTENT_VIEW_TIME** — satura ienešanai veltītais laiks

- **NUMBER_Of_RUNNING_PROCESSES** — norāda aktīvo procesu skaitu

- **NUMBER_OF_SNAPSHOTS** — piezīmju grāmatiņas struktūras ielādēšanu sāknēšanas laikā skaits

- **OFFICEASSETMANAGER_INITIALIZATION_TIME**— līdzekļu pārvaldnieka izgūšanai no arhīva un inicializācijai veltītais laiks

- **PROCESS_BOOT_TIME_IN_MS** — procesa izveides pabeigšanai veltītais laiks

- **ROOT_ACTIVITY_CREATE_ACTIVITY_CREATE** — pārejai no saknes slāņa veltītais laiks 

- **ROOT_ACTIVITY_DISK_CHECK_ACTIVITY_DISK_CHECK** — novecojis

- **ROOT_ACTIVITY_LAUNCH_NEXTACTIVITY_ACTIVITY_LAUNCH_NEXTACTIVITY** — novecojis

- **ROOT_ACTIVITY_PROCESS_INTENT_ACTIVITY_PROCESS_INTENT** — novecojis 

- **ROOT_ACTIVITY_SESSION_ACTIVITY_SESSION** — pārejai no saknes slāņa veltītais laiks 

- **ROOT_TO_NAVIGATION_TRANSITION_TO_NAVIGATION_TRANSITION** — navigācijas no saknes apstrādei veltītais laiks

- **SNAPSHOT_PUBLISH_TO_RENDERING_END_PUBLISH_TO_RENDERING_END** — laiks satura renderēšanas pabeigšanai

- **SPLASH_ACTIVITY_SESSION_ACTIVITY_SESSION** — uzplaiksnījuma ekrāna parādīšanai veltītais laiks

- **SPLASH_TO_ROOT_TRANSITION_TO_ROOT_TRANSITION** — pārejai no saknes slāņa veltītais laiks 

- **TIME_BETWEEN_PROCESS_BOOT_AND_ACTIVITY_BEGIN_IN_MS** — laiks starp procesa un aktivitātes izveidi 

- **TIME_TAKEN_IN_MS** — sāknēšanas pabeigšanai veltītais laiks
 
- **TOTAL_MEMORY_IN_MB** — ierīces kopējā atmiņa
 
- **USER_INTERACTED_DURING_EVENT** — norāda, vai lietotājs ir mijiedarbojies sāknēšanas laikā

#### <a name="onenoteapponenoteappforeground-previous-name-officeonenoteandroidapponenoteappforeground"></a>OneNote.App.OneNoteAppForeground *(iepriekšējais nosaukums)*, Office.OneNote.Android.App.OneNoteAppForeground

Signāls, kas norāda, vai OneNote lietojumprogramma ir priekšplānā.  Telemetrija, kas tiek izmantota kritiskas regresijas atklāšanai OneNote lietojumprogrammā un pakalpojuma darbspējā. 

Tiek apkopoti tālāk norādītie lauki: nav

#### <a name="onenoteapplaunch-previous-name-officeandroidearlytelemetryapplaunch"></a>OneNote.AppLaunch *(iepriekšējais nosaukums)*, Office.Android.EarlyTelemetry.AppLaunch

Kritiskais signāls, kas tiek izmantots, lai OneNote lietotāji varētu veiksmīgi palaist lietojumprogrammu.  Telemetrija, kas tiek izmantota kritiskas regresijas atklāšanai OneNote lietojumprogrammā un pakalpojuma darbspējā. 

Tiek apkopoti šādi lauki: 

- **ANDROID_SDK_VERSION** — fiksē Android SDK versiju

- **FirstLaunchTime** — reģistrē laiku, kad lietojumprogramma tika palaista pirmo reizi

- **InstallLocation** — norāda, vai lietojumprogramma ir sākotnēji instalēta vai lejupielādēta veikalā

- **is_boot_completed_ever** — norāda, vai iepriekš lietojumprogramma ir veiksmīgi sāknēta ierīcē 

- **IS_DARK_MODE_ENABLED** — Būla, kas norāda, vai lietojumprogramma ir tumšajā režīmā

- **NewOneNoteUser** — Identificē, vai lietotājs ir jauns lietotājs

#### <a name="officeoutlookdesktopexchangepuidandtenantcorrelation"></a>Office.Outlook.Desktop.ExchangePuidAndTenantCorrelation

Reizi sesijā apkopo PUID un nomnieka identifikatoru. PUID un nomnieka korelācija ir nepieciešama, lai izprastu un diagnosticētu Outlook problēmas katram nomniekam.

Tiek apkopoti tālāk norādītie lauki.

  - **CollectionTime** — notikuma laikspiedols

  - **ConnId** — savienojuma identifikators: identifikators savienojuma parsēšanai starp PUID un OMS nomnieka identifikatoru

  - **OMSTenantId** — Microsoft ģenerētais nomnieka unikālais identifikators

  - **PUID** — Exchange PUID unikālai lietotāju identificēšanai


#### <a name="officeoutlookmacmacolkactivationstate"></a>Office.Outlook.Mac.MacOLKActivationState

Apkopo datus par Outlook aktivāciju, piemēram, ar abonementa vai apjoma licences palīdzību. Dati tiek uzraudzīti, lai nodrošinātu, ka kļūmju skaits nepalielinās. Mēs arī analizējam datus, lai atrastu jomas, kurās nepieciešami uzlabojumi. 

Tiek apkopoti tālāk norādītie lauki.

- **SetupUIActivationMethod** — Outlook aktivizēšanas metode, piemēram, abonements vai apjoma licence.

#### <a name="officepowerpointdocoperationopen"></a>Office.PowerPoint.DocOperation.Open 

Apkopots ikreiz, kad PowerPoint atver failu. Satur informāciju par sekmīgām darbībām, kļūmes informāciju, izpildes metriku un pamatinformāciju par failu, tostarp faila formāta tipu un dokumenta metadatus. Šī informācija ir nepieciešama, lai PowerPoint varētu sekmīgi atvērt failus, nepasliktinot izpildi. Tā ļauj mums diagnosticēt atklātās problēmas.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_AddDocTelemetryResult —** vai šim žurnāla ierakstam ir visa nepieciešamā dokumenta telemetrija (Data\_Doc\_\* lauki)

  - **Data\_AddDocumentToMruList —** metodes AddDocumentToMruList izpildes laiks

  - **Data\_AlreadyOpened —** vai šis dokuments tika atvērts iepriekš (saistībā ar vienu un to pašu procesu sesiju)

  - **Data\_AntiVirusScanMethod —** iepriekš definētu vērtību kopa pretvīrusu programmatūras skenēšanas tipam (IOAV, AMSI, nav utt.)

  - **Data\_AntiVirusScanStatus —** iepriekš definētu vērtību kopa pretvīrusu programmatūras skenēšanai, kas tiek veikta katram atvērtajam dokumentam (NoThreatsDetected, neizdevās, MalwareDetected utt.)

  - **Data\_AsyncOpenKind —** asinhronu opciju iepriekš definētu vērtību kopa (Collab, ServerOnly, SyncBacked, NotAsync)

  - **Data\_CancelBackgroundDownloadHr —** vai dokumenta lejupielāde tika pārtraukta? Ja tā ir, kāds bija pārtraukuma rezultāts?

  - **Data\_CheckForAssistedReadingReasons —** metodes CheckForAssistedReadingReasons izpildes laiks milisekundēs

  - **Data\_CheckForDisabledDocument —** metodes CheckForDisabledDocument izpildes laiks milisekundēs

  - **Data\_CheckForExistingDocument —** metodes CheckForExistingDocument izpildes laiks milisekundēs

  - **Data\_CheckIncOpenResult —** metodes CheckIncOpenResult izpildes laiks milisekundēs

  - **Data\_CheckLambdaResult —** metodes CheckLambdaResult izpildes laiks milisekundēs

  - **Data\_CheckPackageForRequiredParts —** metodes CheckPackageForRequiredParts izpildes laiks milisekundēs

  - **Data\_CheckPackageForSpecialCases —** metodes CheckPackageForSpecialCases izpildes laiks milisekundēs

  - **Data\_CheckRequiredPartsLoaded —** metodes CheckRequiredPartsLoaded izpildes laiks milisekundēs

  - **Data\_CheckWebSharingViolationForIncOpen —** metodes CheckWebSharingViolationForIncOpen izpildes laiks milisekundēs
   
  - **Data_CloseAndReopenWithoutDiscard —** Vai dokuments tika aizvērts un atkārtoti atvērts atvērtā procesa laikā, to neizdzēšot.

  - **Data\_ContentTransaction —** Iepriekš definētu vērtību kopa, kad iespējams izveidot transakciju (AllowedOnLoadDocument, AllowedOnOpenComplete, utt.)

  - **Data_CorrelationId -** GUID, kuru ProtocolHandler nodevis programmai PowerPoint, lai korelētu telemetriju. ProtocolHandler ir atsevišķs process, kas apstrādā operētājsistēmas Office saites.

  - **Data\_CppUncaughtExceptionCount:long —** nenotverti vietējie izņēmumi darbības izpildes laikā

  - **Data\_CreateDocumentTimeMS —** metodes CreateDocumentTimeMS izpildes laiks milisekundēs

  - **Data\_CreateDocumentToken —** metodes CreateDocumentToken izpildes laiks milisekundēs

  - **Data\_CreateDocumentToW —** metodes CreateDocumentToW izpildes laiks milisekundēs

  - **Data\_CreateDocWindow —** metodes CreateDocWindow izpildes laiks milisekundēs

  - **Data\_CreateLocalTempFile —** metodes CreateLocalTempFile izpildes laiks milisekundēs

  - **Data\_DetachedDuration:long —** darbības atvienošanas/nedarbošanās ilgums

  - **Data\_DetermineFileType —** metodes DetermineFileType izpildes laiks milisekundēs

  - **Data\_Doc\_AccessMode:long —** kā šis dokuments ir atvērts (tikai lasāms | lasīšana un rakstīšana)

  - **Data\_Doc\_AssistedReadingReasons:long —** iepriekš definētu vērtību kopa, kas norāda, kāpēc dokuments ir atvērts pieejamā lasīšanas režīmā

  - **Data_Doc_AsyncOpenKind:long — ** norāda, vai tika atvērta mākoņa dokumenta kešotā versijā un kura asinhronā atsvaidzināšanas loģika tika izmantota.

  - **Data\_Doc\_ChunkingType:long —** kā dokuments ir saglabāts pakalpojumā SharePoint

  - **Data\_Doc\_EdpState:long —** dokumenta uzņēmuma datu aizsardzība statuss

  - **Data\_Doc\_Ext:string —** dokumenta paplašinājums

  - **Data\_Doc\_Extension:string —** dokumenta paplašinājums

  - **Data\_Doc\_FileFormat:long —** iepriekš definētu faila formāta vērtību kopa (detalizētāka par paplašinājumu).

  - **Data\_Doc\_Fqdn:string —** dokumentu glabāšanas vieta (SharePoint.com, live.net), pieejama tikai Office 365 domēniem

  - **Data\_Doc\_FqdnHash:string —** dokumenta glabāšanas vietas jaukšana

  - **Data\_Doc\_IdentityTelemetryId:string —** unikāls lietotāja GUID

  - **Data\_Doc\_IdentityUniqueId:string —** tās identitātes unikālais identifikators, kas tika izmantota koplietojamo dokumentu darbībai

  - **Data\_Doc\_IOFlags:long —** bitmaska dažādiem ar IO saistītiem karodziņiem, kas attiecas uz dokumentu

  - **Data\_Doc\_IrmRights:long —** iepriekš definētu vērtību kopa, kas attiecas uz informācijas piekļuves tiesību pārvaldības tipu, kas tiek lietots šim dokumentam (pārsūtīšana, atbildēšana, SecureReader, rediģēšana u.c.)

  - **Data\_Doc\_IsCloudCollabEnabled:bool —** patiess, ja "IsCloudCollabEnabled" HTTP galvene jau ir saņemta no pieprasījuma OPTIONS.

  - **Data\_Doc\_IsIncrementalOpen:bool —** vai dokuments tika atvērts inkrementāli (jauns līdzeklis, kas atver dokumentu bez vajadzības lejupielādēt visu dokumentu)

  - **Data\_Doc\_IsOcsSupported:bool —** vai ir dokuments atbalsta koprediģēšanu, izmantojot jauno OCS pakalpojumu

  - **Data\_Doc\_IsOpeningOfflineCopy:bool —** vai dokuments tiek atvērts no lokālās kešatmiņas?

  - **Data\_Doc\_IsSyncBacked:bool —** vai dokuments tiek atvērts no mapes, kas izmanto OneDrive sinhronizācijas programmu

  - **Data\_Doc\_Location:long —** iepriekš definētu vērtību kopa, kas norāda dokumenta glabāšanas vietu (lokālā, SharePoint, WOPI, tīkls utt.)

  - **Data\_Doc\_LocationDetails:long —** iepriekš definētu detalizētākas atrašanās vietas vērtību kopa (mape Temp, lejupielāžu mape, OneDrive dokumenti, OneDrive attēli utt.)

  - **Data\_Doc\_NumberCoAuthors:long —** līdzautoru skaits dokumenta atvēršanas brīdī

  - **Data\_Doc\_PasswordFlags:long —** iepriekš definētu vērtību kopa, kas norāda veidu, kā dokuments ir šifrēts ar paroli (nav, parole lasīšanai, parole rediģēšanai)

  - **Data\_Doc\_ReadOnlyReasons:long —** iepriekš definētu vērtību kopa, kas norāda, kāpēc šis dokuments ir atzīmēts kā tikai lasāms (bloķēts serverī, pabeigts dokuments, aizsargāts ar paroli rediģēšanai utt.)

  - **Data\_Doc\_ResourceIdHash:string —** resursu identifikatora jaukšana mākonī saglabātajiem dokumentiem

  - **Data_Doc_RtcType —** norāda, kā reāllaika kanāls (RTC) bija iestatīts pašreizējam failam (atspējots, neatbalstīts, pēc pieprasījuma, vienmēr ieslēgts utt.).

  - **Data\_Doc\_ServerDocId:string —** nemainīgs identifikators mākonī saglabātajiem dokumentiem

  - **Data\_Doc\_ServerProtocol:long —** iepriekš definētu vērtību kopa, kas norāda, kurš protokols tiek izmantots, lai sazinātos ar serveri (HTTP, Cobalt, WOPI utt.)
 
  - **Data\_Doc\_ServerType:long —** iepriekš definētu vērtību kopas servera tipam (SharePoint, DropBox, WOPI)

  - **Data\_Doc\_ServerVersion:long —** vai servera pamatā ir Office14, Office15 vai Office16?

  - **Data\_Doc\_SessionId:long —** ģenerēts GUID, kas norāda dokumenta instanci tajā pašā procesa sesijā

  - **Data\_Doc\_SharePointServiceContext:string —** necaurspīdīga virkne, parasti GridManagerID.FarmID. Noder, lai saistītu klienta un servera žurnālu

  - **Data\_Doc\_SizeInBytes:long —** dokumenta lielums baitos

  - **Data\_Doc\_SpecialChars:long —** bitmaska, kas norāda speciālās rakstzīmes dokumenta vietrādī URL vai ceļā

  - **Data\_Doc\_StorageProviderId:string —** virkne, kas norāda dokumenta krātuves nodrošinātāju, piemēram, "DropBox"

  - **Data\_Doc\_StreamAvailability:long —** iepriekš definētu dokumenta straumēšanas vērtību kopas statuss (pieejams, neatgriezeniski atspējots, nav pieejams)

  - **Data\_Doc\_UrlHash:string —** pilna vietrāža URL jaukšana mākonī saglabātiem dokumentiem

  - **Data\_Doc\_UsedWrsDataOnOpen:bool —** patiess, ja fails tika atvērts inkrementāli, izmantojot iepriekš kešotus WRS datus resursdatorā

  - **Data\_Doc\_WopiServiceId:string —** WOPI pakalpojuma identifikators, piemēram, "Dropbox"

  - **Data\_DownloadExcludedData —** metodes DownloadExcludedData izpildes laiks milisekundēs

  - **Data\_DownloadExcludedDataTelemetry —** iepriekš definēta vērtību kopa par stāvokli, kad notiek sinhrona lejupielādes gaidīšana (SynchronousLogicHit, UserCancelled RunModalTaskUnexpectedHResult utt.)

  - **Data\_DownloadFileInBGThread —** metodes DownloadFileInBGThread izpildes laiks milisekundēs

  - **Data\_DownloadFragmentSize —** fragmenta lielums (lejupielādējamais faila apjoms) parasti 3,5 MB

  - **Data\_ExcludedEmbeddedItems —** ZIP arhīva daļas, kas nav iekļautas sākotnējā atveidē

  - **Data\_ExcludedEmbeddedItemsSize —** ZIP arhīva daļu, kas nav iekļautas sākotnējā atveidē, kopējais lielums

  - **Data\_ExcludedRequiredItems —** ZIP arhīva daļas, kas nav iekļautas, taču ir nepieciešamas sākotnējā atveidē

  - **Data\_ExcludedRequiredItemsSize —** ZIP arhīva daļu, kas nav iekļautas, taču ir nepieciešamas sākotnējā atveidē, kopējais lielums

  - **Data\_ExecutionCount —** cik reižu tika izpildīts IncOpen protokols

  - **Data\_FailureComponent:long —** iepriekš definētu vērtību kopa, kas norāda, kurš komponents izraisīja protokola kļūmi (konflikts, CSI, iekšējais utt).

  - **Data\_FailureReason:long —** iepriekš definētu vērtību kopa, kas norāda kļūmes iemeslu (FileIsCorrupt, BlockedByAntivirus u.c.)

  - **Data\_FCreateNew —** vai šis ir jauns, tukšs dokuments

  - **Data\_FCreateNewFromTemplate —** vai šis ir jauns dokuments no veidnes

  - **Data_FErrorAfterDocWinCreation:boolean —** vai pēc dokumenta loga izveides radās kāda kļūda vai izņēmums.

  - **Data\_FileUrlLocation —** iepriekš definētu vērtību kopa par to, kur dokuments ir saglabāts (NetworkShare, LocalDrive, ServerOther utt.)

  - **Data\_FirstSlideCompressedSize —** pirmā slaida ZIP daļas (parasti Slide1.xml) saspiestais lielums

  - **Data\_FIsDownloadFileInBgThreadEnabled —** vai lejupielāde fona pavedienā ir iespējota?

  - **Data\_fLifeguarded:bool —** vai dokuments kādreiz ir bijis aizsargāts (līdzeklis, lai izlabotu dokumenta kļūdas, neziņojot par to lietotājam)?

  - **Data\_ForceReopenOnIncOpenMergeFailure —** karodziņš norāda, vai bijām spiesti atvērt atkārtoti Inc Open sapludināšanas kļūmes dēļ

  - **Data\_ForegroundThreadPass0TimeMS —** (tikai Mac) kopējais pavadītais laiks priekšplāna pavedienā pirmajā piegājienā

  - **Data\_ForegroundThreadPass1TimeMS —** (tikai Mac) kopējais pavadītais laiks priekšplāna pavedienā otrajā piegājienā

  - **Data\_FWebCreatorDoc —** vai dokuments ir izveidots no veidnes vai QuickStarter

  - **Data\_HasDocToken —** vai šajā dokumentā ir CSI doc pilnvara (iekšējais kods)

  - **Data\_HasDocument —** vai šajā dokumentā ir CSI dokumenta pilnvara (iekšējais kods)

  - **Data\_InclusiveMeasurements —** vai metodes mērījumu ilgumā ir ietverts atvasinātās metodes izsaukuma ilgums

  - **Data\_IncompleteDocReasons —** iepriekš definētu vērtību kopa, kāpēc atvēršana netika pabeigta (Unknown, DiscardFailure utt.)

  - **Data\_IncOpenDisabledReasons —** iepriekš definētu vērtību kopa ar iemesliem, kāpēc tika atspējota inkrementālā atvēršana

  - **Data\_IncOpenFailureHr —** rezultāts, kāpēc neizdevās inkrementālā atvēršana

  - **Data\_IncOpenFailureTag —** atzīme (kodu atrašanās vietas rādītājs), kur neizdevās inkrementālā atvēršana

  - **Data\_IncOpenFallbackReason —** kāpēc IncOpen netika palaists

  - **Data\_IncOpenRequiredTypes —** iepriekš definētu vērtību kopa ar satura tipiem, kas nepieciešami pirmajai atveidei (RequiredXmlZipItem, RequiredNotesMaster utt.)

  - **Data\_IncOpenStatus —** iepriekš definētu vērtību kopa par inkrementālās atvēršanas statusu (Attempted, FoundExcludedItems, DocIncOpenInfoCreated utt.)

  - **Data\_InitFileContents —** metodes InitFileContents izpildes laiks milisekundēs

  - **Data\_InitialExcludedItems —** ZIP arhīva daļas, kas sākotnēji nav iekļautas

  - **Data\_InitialExcludedItemsSize —** ZIP arhīva daļu, kas sākotnēji nav iekļautas, kopējais lielums

  - **Data\_InitializationTimeMS —** (tikai Mac) inicializācijas laiks

  - **Data\_InitialRoundtripCount —** servera atbilžu skaits, kas nepieciešamas, lai izveidotu sākotnējo ZIP arhīvu

  - **Data\_InitLoadProcess —** metodes InitLoadProcess izpildes laiks milisekundēs

  - **Data\_InitPackage —** metodes InitPackage izpildes laiks milisekundēs

  - **Data\_InitSecureReaderReasons —** metodes InitSecureReaderReasons izpildes laiks milisekundēs

  - **Data\_IsIncOpenInProgressWhileOpen —** ja viens dokuments tiek atvērts vairākās instancēs, vai Inc Open protokols darbojas paralēli atvēršanas protokolam?

  - **Data\_IsMultiOpen —** vai tiek atbalstītas vairākas atvēršanas instances?

  - **Data\_IsOCS —** vai dokuments bija OCS režīmā tā pēdējā zināmajā stāvoklī

  - **Data\_IsODPFile —** vai dokuments ir formātā "Open Document Format", ko izmanto OpenOffice.org

  - **Data\_IsPPTMetroFile —** vai dokuments ir metro (pptx) faila formātā

  - **Data\_LoadDocument —** metodes LoadDocument izpildes laiks milisekundēs

  - **Data\_MeasurementBreakdown —** kodēts mērījumu sadalījums (saīsināta detalizētas metodes izpilde)

  - **Data\_Measurements —** kodēti mērījumi

  - **Data\_MethodId —** pēdējā izpildītā metode

  - **Data\_NotRequiredExcludedItems —** kopējais to PowerPoint pakotnes vienumu skaits, kas nav nepieciešami pirmajai atveidei un ir izslēgti

  - **Data\_NotRequiredExcludedItemsSize —** kopējais to PowerPoint pakotnes vienumu lielums, kas nav nepieciešami pirmajai atveidei un ir izslēgti

  - **Data\_NotRequiredExcludedParts —** kopējais to ZIP pakotnes daļu skaits, kas nav nepieciešamas pirmajai atveidei un ir izslēgtas

  - **Data\_NotRequiredExcludedPartsSize —** kopējais to ZIP pakotnes daļu lielums, kas nav nepieciešamas pirmajai atveidei un ir izslēgtas

  - **Data_OngoingBlockingOpenCount —** norāda pašlaik darbībā esošo atvēršanas bloķēšanas protokolu skaitu.
  
  - **Data_OngoingOpenCount —** norāda pašlaik darbībā esošo atvēršanas protokolu skaitu.

  - **Data\_OpenCompleteFailureHR —** rezultāts, kāpēc neizdevās OpenComplete protokols

  - **Data\_OpenCompleteFailureTag —** atzīme (koda atrašanās vietas rādītājs), kur neizdevās OpenComplete protokols

  - **Data\_OpenLifeguardOption —** iepriekš definētu vērtību kopa ar Lifeguard darbības izvēlēm (None, TryAgain, OpenInWebApp utt.)

  - **Data\_OpenReason —** iepriekš definētu vērtību kopa, kā šis dokuments tika atvērts (FilePicker, OpenFromMru, FileDrop utt.)

  - **Data\_OSRPolicy —** SecureReader politika

  - **Data\_OSRReason —** iemesli, kāpēc šis dokuments tika atvērts drošajā lasītājā

  - **Data\_OtherContentTypesWithRequiredParts —** nestandarta satura tipi, kas tika izslēgti, bet ir nepieciešami pirmajai atveidei

  - **Data\_PrepCacheAsync —** OcsiOpenPerfPrepCacheAsync karodziņš

  - **Data\_PreviousDiscardFailed —** norāda, ka iepriekšējās dokumenta atvēršanas/aizvēršanas mēģinājums nav atbrīvojis visu atmiņu

  - **Data\_PreviousFailureHr —** ja tiek atkārtoti atvērts tas pats dokuments, kāds bija pēdējās kļūmes rezultāts

  - **Data\_PreviousFailureTag —** ja tiek atkārtoti atvērts tas pats dokuments, kāda bija pēdējās kļūmes atzīme (koda atrašanās vietas rādītājs)

  - **Data\_RemoteDocToken —** vai attālā atvēršana ir iespējota (prototipa līdzeklis, kas nodrošina faila atvēršanu no pakalpojuma, nevis no resursdatora)?

  - **Data\_Repair —** vai esam dokumenta labošanas režīmā (bojātiem dokumentiem, kurus iespējams labot)

  - **Data\_RequestPauseStats —** cik reizes kods pieprasīja pauzēt izpildes ierakstīšanu

  - **Data\_RequiredPartsComressedSize —** pirmajai atveidei nepieciešamo PowerPoint daļu kopējais lielums

  - **Data\_RequiredPartsDownload —** nepieciešamo PowerPoint daļu, kas tiek lejupielādētas, kopējais lielums

  - **Data\_RequiredPartsRoundtripCount —** kopējais nepieciešamo ciklu (resursdatora izsaukumu) skaits, lai iegūtu visas nepieciešamās PowerPoint daļas pirmajai atveidei

  - **Data\_RequiredZipItemsDownload —** kopējais nepieciešamo ZIP vienumu skaits, kas nepieciešams pirmajai atveidei

  - **Data\_RequiredZipItemsRoundtripCount —** kopējais nepieciešamo ciklu (resursdatora izsaukumu) skaits, lai iegūtu visus nepieciešamos ZIP vienumus pirmajai atveidei

  - **Data\_RoundtripsAfterMissingRequiredParts —** kopējais nepieciešamo ciklu (resursdatora izsaukumu) skaits, kad konstatētas trūkstošas nepieciešamās PowerPoint daļas

  - **Data\_RoundtripsAfterMissingRequiredZipItems —** kopējais nepieciešamo ciklu (resursdatora izsaukumu) skaits, kad konstatētas trūkstoši nepieciešamie ZIP vienumi

  - **Data\_RoundtripsAfterRequiredPackage —** kopējais nepieciešamo ciklu (resursdatora izsaukumu) skaits pēc pakotnes izveides

  - **Data\_RoundtripsAfterRequiredParts —** kopējais nepieciešamo ciklu (resursdatora izsaukumu) skaits pēc visu nepieciešamo daļu lejupielādes

  - **Data\_SetDocCoAuthAutoSaveable —** metodes SetDocCoAuthAutoSaveable izpildes laiks milisekundēs

  - **Data\_SniffedFileType —** bojātā dokumenta piedāvātā faila tipa minējums

  - **Data\_StartTime —** izpildes skaitītājs, startējot atvēršanas brīdī

  - **Data\_StopwatchDuration:long —** kopējais darbības ilgums

  - **Data\_SyncSlides —** metodes SyncSlides izpildes laiks milisekundēs

  - **Data\_TimerStartReason —** iepriekš definētu vērtību kopa, kā tika startēts taimeris (CatchMissedSyncStateNotification, WaitingForFirstDownload utt.)

  - **Data\_TimeSplitMeasurements —** kodēts mērījumu sadalījums (saīsināta detalizētas metodes izpilde)

  - **Data\_TimeToInitialPackage —** laiks sākotnējās pakotnes izveidei

  - **Data\_TimeToRequiredPackage —** laiks nepieciešamās pakotnes izveidei

  - **Data\_TimeToRequiredParts —** laiks, lai izveidotu pakotni ar visiem nepieciešamajiem elementiem

  - **Data\_TotalRequiredParts —** kopējais nepieciešamo PowerPoint elementu skaits pirmajā atveidē

  - **Data\_TotalRequiredParts —** kopējais nepieciešamo PowerPoint elementu skaits pirmajai atveidei

  - **Data\_UnpackLinkWatsonId —** Vatsona identifikators par kļūdu, kad dokuments tiek atvērts, izmantojot OneDrive koplietošanas URL

  - **Data\_UnpackResultHint —** iepriekš definētu vērtību kopa ar koplietošanas URL izpakošanas rezultātiem (NavigateToWebWithoutError, UrlUnsupported, AttemptOpen utt.)

  - **Data\_UnpackUrl —** metodes UnpackUrl izpildes laiks milisekundēs

  - **Data\_UpdateAppstateTimeMS —** metodes UpdateAppstate izpildes laiks milisekundēs

  - **Data\_UpdateCoauthoringState —** metodes UpdateCoauthoringState izpildes laiks milisekundēs

  - **Data\_UpdateReadOnlyState —** metodes UpdateReadOnlyState izpildes laiks milisekundēs

  - **Data\_WACCorrelationId —** ja fails tiek atvērts pārlūkprogrammā, iegūt WebApp žurnālu korelāciju

  - **Data\_WasCachedOnInitialize —** vai šis dokuments tika saglabāts kešatmiņā inicializācijas laikā

  - **Data\_WBDirtyBeforeDiscard —** vai darba zars kļuva novecojis pirms atkārtotas dokumenta atvēršanas

  - **Data\_ZRTOpenDisabledReasons —** kāpēc mēs nevarējām atvērt dokumentu no kešatmiņas (nulles cikls)

#### <a name="officepowerpointpptdesktopbootime"></a>Office.PowerPoint.PPT.Desktop.Bootime

Apkopo, kā tiek startēts PowerPoint. Iekļauta PowerPoint startēšana aizsargātā skatā, asistētas lasīšanas režīmā, no makro, drukāšana, jauns un tukšs dokuments, dokumenta atkopšana, no automatizācijas un, ja tas ir “Click-to-Run”. Tas apkopo arī PowerPoint startēšanas laiku. Šie dati ir kritiski svarīgi, lai nodrošinātu PowerPoint sekmīgu startēšanu no dažādiem režīmiem. Microsoft izmanto šos datus, lai fiksētu ilgu startēšanas laiku, atverot PowerPoint no dažādiem režīmiem.

Tiek apkopoti tālāk norādītie lauki.

  - **AssistedReading —** asistētas lasīšanas režīmā

  - **Automation —** no automatizācijas

  - **Benchmark —** palaist izpildes kritēriju

  - **Blank —** tukšs dokuments

  - **BootTime —** sesijas startēšanas laiks

  - **Embedding —** dokumenta iegulšana

  - **IsC2R —** ir “Click-to-Run”

  - **IsNew —** jauns dokuments

  - **IsOpen —** ir atvērts

  - **Macro1 —** palaist makro

  - **Macro2 —** palaist makro

  - **NonStandardSpaceInCmdLine** — komandrindā ir nestandarta atstarpe

  - **Print —** drukāt dokumentu

  - **PrintDialog —** drukāt dokumentu ar dialoglodziņu

  - **PrintPrinter —** drukāt dokumentu ar printeri

  - **ProtectedView —** aizsargātā skatā

  - **Regserver —** reģistrēt PowerPoint kā COM serveri

  - **Restore —** atjaunot dokumentu

  - **Show —** rādīt dokumentu

  - **Time —** sesijas laiks

  - **UnprotectedView —** neaizsargātā skatā

#### <a name="officepowerpointppthasuserediteddocument"></a>Office.PowerPoint.PPT.HasUserEditedDocument

Apkopo, kad lietotājs sāk dokumenta rediģēšanu. Microsoft izmanto šos datus, lai aprēķinātu aktīvos lietotājus, kuri rediģēja PowerPoint dokumentu

Tiek apkopoti tālāk norādītie lauki.

  - **CorrelationId** — dokumentu korelācijas identifikators

#### <a name="officeprojectbootandopenproject"></a>Office.Project.BootAndOpenProject

Project tiek startēta, atverot failu. Šis notikums norāda, ka lietotājs ir atvēris Office Project ar saistīto failu. Tas satur kritiski svarīgus datus, lai varētu startēt Project un ielādēt failu.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_AlertTime —** laika periods, kad bija aktīvs startēšanas dialoglodziņš.

  - **Data\_BootTime —** Project palaišanai nepieciešamais laiks

  - **Data\_CacheFileSize —** ja fails tika saglabāts kešatmiņā, faila lielums

  - **Data\_EntDocType —** atvērtā faila tips

  - **Data\_IsInCache —** vai atvērtais fails tika saglabāts kešatmiņā

  - **Data\_LoadSRAs —** vai lietotājs vēlas ielādēt SRA

  - **Data\_Outcome —** kopējais startēšanas un failu atvēršanas laiks

  - **Data\_OpenFromDocLib —** vai atvērtais Project fails ir no dokumentu bibliotēkas

  - **Data\_ProjectServerVersion —** pašreizējā Project versija un būvējums

#### <a name="officeprojectbootproject"></a>Office.Project.BootProject

Project tiek startēta bez faila atvēršanas. Šis notikums norāda, ka lietotājs ir atvēris Office Project bez saistītā faila. Tas satur kritiski svarīgus datus, lai varētu startēt Project.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_BootTime —** Project palaišanai nepieciešamais laiks

  - **Data\_FileLoaded —** aplams, ja, atverat no ārējas vietas vai jaunu, tukšu projektu

  - **Data\_IsEntOfflineWithProfile —** ja lietotāji ir profesionālā noliktavas vienībā un nav izveidots savienojums ar serveri

  - **Data\_IsEntOnline —** ja Project sesija ir savienota ar Project serveri ar uzņēmuma līdzekļiem

  - **Data\_IsLocalProfile —** ja Project sesija ir savienota ar Project serveri ar uzņēmuma līdzekļiem

  - **Data\_ProjectServerVersion —** pašreizējā Project versija un būvējums


#### <a name="officeprojectopenproject"></a>Office.Project.OpenProject

Project atver failu. Šis notikums norāda, ka lietotājs tieši atvēra Project failu. Tas satur kritiski svarīgus datus par sekmīgu failu atvēršanu programmā Project.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_AgileMode —** definē, vai atvērtais projekts ir ūdenskrituma vai spējas izstrādes projekts

  - **Data\_AlertTime —** laika periods, kad bija aktīvs startēšanas dialoglodziņš

  - **Data\_CacheFileSize —** ja fails tika saglabāts kešatmiņā, faila lielums

  - **Data\_EntDocType —** atvērtā faila tips

  - **Data\_IsInCache —** vai atvērtais fails tika saglabāts kešatmiņā

  - **Data\_LoadSRAs —** vai lietotājs vēlas ielādēt SRA

  - **Data\_OpenFromDocLib —** vai atvērtais Project fails ir no dokumentu bibliotēkas

  - **Data\_Outcome —** kopējais startēšanas un failu atvēršanas laiks

  - **Data\_Outcome —** kopējais startēšanas un failu atvēršanas laiks

  - **Data\_ProjectServerVersion —** pašreizējā Project versija un būvējums

#### <a name="officesessionidproviderofficeprocesssessionstart"></a>Office.SessionIdProvider.OfficeProcessSessionStart

Attiecas uz visām Office Windows lietojumprogrammām: win32 un UWP

Tiek apkopoti tālāk norādītie lauki.

- **OfficeProcessSessionStart** nosūta pamatinformāciju jaunas Office sesijas sākumā. To izmanto, lai saskaitītu unikālās sesijas, kas redzamas konkrētajā ierīcē. Tas tiek izmantots kā periodiska kontrolziņojuma notikums, lai pārliecinātos, vai lietojumprogramma darbojas ierīcē. Turklāt to var izmantot kā kritiski svarīgu signālu par kopējo lietojumprogrammu uzticamību

- **AppSessionGuid** — tās attiecīgās lietojumprogrammas sesijas identifikators, kuras sākums ir procesa izveides laiks un kas ilgst līdz procesa beigām. Tas ir formatēts kā standarta 128 bitu GUID, ko veido četras daļas. Šo četru daļu secība ir: (1) 32 bitu procesa ID (2) 16 bitu sesijas ID (3) 16 bitu palaišanas ID (4) 64 bitu procesa izveides laiks: UTC 100ns

- **processSessionId** — nejauši ģenerēts GUID, lai noteiktu programmas sesiju

- **UTCReplace_AppSessionGuid** — konstanta Būla vērtība. Vienmēr patiess.

#### <a name="officesystemsessionhandoff"></a>Office.System.SessionHandoff

Norāda, ka pašreizējā Office sesija ir nodošanas sesija. Tas nozīmē, ka darbs ar lietotāja pieprasījumu, lai atvērtu dokumentu, tiek pārsūtīts uz jau darbojošos instanci tajā pašā programmā.

Tiek apkopoti tālāk norādītie lauki.

- **ParentSessionId** — tās sesijas ID, kas veiks lietotāju pieprasījuma apstrādi.

#### <a name="officetelemetryengineisprelaunch"></a>Office.TelemetryEngine.IsPreLaunch

Attiecas uz Office UWP lietojumprogrammām.  Šis notikums tiek palaists, kad Office lietojumprogramma tiek inicializēta pirmo reizi pēc jaunināšanas/instalēšanas no veikala. Tā ir daļa no pamata diagnostikas datiem, kas tiek izmantoti, lai izsekotu, vai sesija ir palaišanas sesija.

Tiek apkopoti tālāk norādītie lauki.

- **appVersionBuild** — programmas būvējuma versijas numurs.

- **appVersionMajor** — programmas galvenās versijas numurs.

- **appVersionMinor** — programmas papildversijas numurs.

- **appVersionRev** — programmas pārskatītās versijas numurs.

- **SessionID** — nejauši ģenerēts GUID, lai noteiktu programmas sesiju

#### <a name="officetelemetryenginesessionhandoff"></a>Office.TelemetryEngine.SessionHandOff

Attiecas uz Win32 Office lietojumprogrammām.  Šis notikums palīdz saprast, vai tika izveidota jauna sesija, lai apstrādātu lietotāja iniciētu faila atvēršanas notikumu. Tā ir kritiski svarīga diagnostikas informācija, kas tiek izmantota, lai atvasinātu uzticamības signālu un pārliecinātos, vai lietojumprogramma darbojas, kā paredzēts.

Tiek apkopoti tālāk norādītie lauki.

- **appVersionBuild** — programmas būvējuma versijas numurs.

- **appVersionMajor** — programmas galvenās versijas numurs.

- **appVersionMinor** — programmas papildversijas numurs.

- **appVersionRev** — programmas pārskatītās versijas numurs.

- **childSessionID** — nejauši ģenerēts GUID, lai noteiktu programmas sesiju

- **parentSessionId** — nejauši ģenerēts GUID, lai noteiktu programmas sesiju

#### <a name="officevisiovisioiosappboottime"></a>Office.Visio.VisioIosAppBootTime

Tas tiek aktivizēts katru reizi, kad tiek sāknēta Visio iOS programma. Ir svarīgi saprast, kāda ir Visio iOS programmas sāknēšanas veiktspēja. Izmanto vājas veiktspējas problēmu novēršanai. 

Tiek apkopoti šādi lauki:

- **Data_AppBootTime** — programmas sāknēšanas ilgums milisekundēs.

#### <a name="officevisiovisioiosappresumetime"></a>Office.Visio.VisioIosAppResumeTime 

Tas tiek aktivizēts katru reizi, kad Visio iOS programma atsāk darboties. Ir svarīgi mērīt programmas atsākšanas veiktspēju un novērst Visio iOS programma veiktspējas problēmas.

Tiek apkopoti šādi lauki:

- **Data_AppResumeTime** — ilgums, līdz programma atsāk darboties milisekundēs.

#### <a name="officewordfileopenopencmdfilemrupriv"></a>Office.Word.FileOpen.OpenCmdFileMruPriv

Šis notikums norāda, ka Office Word atver dokumentu no pēdējo lietoto dokumentu saraksta. Tas satur arī kritiski svarīgus faila atvēršanas izpildes datus, un no lietotāja skatpunkta ir programmas startēšanas notikums. Notikums pārrauga, vai faila atvēršana no pēdējo lietoto dokumentu saraksta darbojas pareizi. To izmanto arī, lai aprēķinātu mēneša aktīvos lietotājus/ierīces un mākoņpakalpojumu uzticamības rādītājus.

Tiek apkopoti tālāk norādītie lauki.

- **Data_AddDocTelemRes** — norāda, vai mēs varam pareizi aizpildīt citas ar dokumentu telemetriju saistītās vērtības šajā notikumā. Izmanto datu kvalitātes diagnostikai.

- **Data_BytesAsynchronous** — baitu skaits (saspiests), bez kura uzskatām, ka varēsim atvērt failu, ja tos iegūstam pirms lietotājs vēlas sākt rediģēšanu vai saglabāšanu.

- **Data_BytesAsynchronousWithWork** — baitu skaits (saspiests), bez kura, iespējams, varēsim atvērt failu, taču tam būs nepieciešamas būtiskas koda izmaiņas.

- **Data_BytesSynchronous** — baitu skaits (saspiests), kuram jābūt mūsu rīcībā, pirms varam sākt faila atvēršanu.

- **Data_BytesUnknown**— baitu skaits dokumenta daļās, kuras neplānojam atrast. 

- **Data_detachedDuration** — cik ilgi darbība bija atdalīta no pavediena.

- **Data_Doc_AccessMode —** dokuments ir tikai lasāms/rediģējams.

- **Data_Doc_AssistedReadingReasons** — iepriekš definētu vērtību kopa, kas norāda, kāpēc dokuments ir atvērts pieejamā lasīšanas režīmā.

- **Data_Doc_AsyncOpenKind — ** norāda, vai tika atvērta mākoņa dokumenta kešotā versijā un kura asinhronā atsvaidzināšanas loģika tika izmantota.

- **Data_Doc_ChunkingType —** vienības, kas tiek izmantotas inkrementālā dokumenta atvēršanā.

- **Data_Doc_EdpState —** dokumenta elektronisko datu aizsardzības iestatījums.

- **Data_Doc_Ext —** dokumenta paplašinājums (docx/xlsb/pptx utt.).

- **Data_Doc_FileFormat —** faila formāta protokola versija.

- **Data_Doc_Fqdn —** OneDrive vai SharePoint Online domēna nosaukums.

- **Data_Doc_FqdnHash —** klientu identificējama domēna nosaukuma vienvirziena jaukšana.

- **Data_Doc_IdentityTelemetryId —** tādas lietotāja identitātes vienvirziena jaukšana, kas tiek izmantota atvēršanā.

- **Data_Doc_InitializationScenario —** dokumenta atvēršanas ieraksti.

- **Data_Doc_IOFlags —** atskaites par kešotajiem karodziņiem, kas tiek izmantoti atvēršanas pieprasījuma opciju iestatīšanai.

- **Data_Doc_IrmRights —** dokumentam/lietotājam piemērotās elektronisko datu politikas atļautās darbības.

- **Data_Doc_IsIncrementalOpen —** karodziņš, kas norāda, ka dokuments tika atvērts inkrementāli.

- **Data_Doc_IsOcsSupported —** karodziņš, kas norāda, ka dokuments tiek atbalstīts sadarbības pakalpojumā.

- **Data_Doc_IsOpeningOfflineCopy —** karodziņš, kas norāda, ka tika atvērta dokumenta bezsaistes kopija.

- **Data_Doc_IsSyncBacked —** karodziņš, kas norāda, ka datorā pastāv automātiski sinhronizēta dokumenta kopija.

- **Data_Doc_Location —** norāda pakalpojumu, kurā atrodas dokuments (OneDrive, File Server, SharePoint utt.).

- **Data_Doc_LocationDetails —** norāda, kurā zināmajā mapē atrodas lokāli saglabātais dokuments.

- **Data_Doc_NumberCoAuthors —** citu lietotāju skaits koprediģēšanas sesijā.

- **Data_Doc_PasswordFlags —** norāda lasīšanas/rakstīšanas paroles karodziņu kopu.

- **Data_Doc_ReadOnlyReasons —** iemesli, kāpēc dokuments ir atvērts tikai lasāmajā režīmā.

- **Data_Doc_ResourceIdHash —** anonimizēts dokumenta identifikators, ko izmanto problēmu noteikšanā.

- **Data_Doc_RtcType —** norāda, kā reāllaika kanāls (RTC) bija iestatīts pašreizējam failam (atspējots, neatbalstīts, pēc pieprasījuma, vienmēr ieslēgts utt.).

- **Data_Doc_ServerDocId —** nemainīgs anonimizēts dokumenta identifikators, ko izmanto problēmu noteikšanā. 

- **Data_Doc_ServerProtocol —** protokola versija, ko izmanto, lai sazinātos ar pakalpojumu.

- **Data_Doc_ServerType —** servera tips, kas nodrošina pakalpojumu (OneDrive, SharePoint, WOPI utt.).

- **Data_Doc_ServerVersion —** servera versija, kas nodrošina pakalpojumu.

- **Data_Doc_SessionId —** identificē konkrētu dokumenta rediģēšanas sesiju pilnā sesijā.

- **Data_Doc_SharePointServiceContext —** diagnostikas informācija no SharePoint Online pieprasījumiem.

- **Data_Doc_SizeInBytes —** dokumenta lieluma rādītājs.

- **Data_Doc_SpecialChars —** speciālo rakstzīmju rādītājs dokumenta vietrādī URL. 

- **Data_Doc_SyncBackedType —** norāda dokumenta veidu (lokālais vai servera).

- **Data_UrlHash —** vienvirziena jaukšana vienkāršota dokumenta identifikatora izveidei.

- **Data.Doc.WopiServiceId —** satur unikālu WOPI pakalpojumu sniedzēja identifikatoru.

- **Data_EditorDisablingRename** — pirmā redaktora identifikators, kas izraisīja pārdēvēšanas atspējošanu.

- **Data_EditorsCount** — redaktoru skaits dokumentā.

- **Data_ForceReadWriteReason** — vesela skaitļa vērtība, kas attēlo iemeslu, kāpēc fails tika atvērts lasīšanas/rakstīšanas režīmā.

- **Data_FSucceededAfterRecoverableFailure** — norāda, ka atvēršana izdevās pēc kļūmes izlabošanas, kas radās dokumenta atvēršanas laikā.

- **Data_LastLoggedTag** — unikāla atzīme koda izsaukuma vietā, ko izmanto, lai noteiktu, kad neizdodas atvērt divreiz (izmanto datu kvalitātes diagnostikai).

- **Data_LinkStyles** — norāda, vai ir saite ar veidņu stiliem.

- **Data_MainPdod** — dokumenta identifikators Office Word procesā.

- **Data_Measurements** — kodēta virkne, kas satur dažādu daļu atvēršanas laika sadalījumu. Izmanto, lai novērtētu izpildi.

- **Data_MoveDisabledReason** — kļūda, kas atspējo dokumenta pārvietošanu.

- **Data_MoveFlightEnabled** — vai lidojuma opcija pārvietošanas līdzeklī ir iespējota.

- **Data_PartsUnknown** — dokumenta daļu skaits, kurām mēs nevarējām iegūt datus.

- **Data_RecoverableFailureInitiationLocationTag** — unikāla atzīme koda izsaukumu vietā, lai identificētu vietu kodā, kur mēs mēģināsim izlabot failu pirms tā atvēršanas.

- **Data_RenameDisabledReason** — kļūda, kuras dēļ tiek atspējota dokumenta pārdēvēšana.

- **Data_RenameFlightEnabled** — vai testējamā varianta opcija pārdēvēšanas līdzeklī ir iespējota.

- **Data_SecondaryTag** — unikāla atzīme koda izsaukšanas vietai, kas tiek izmantota, lai pievienotu papildu kļūmes datus atvēršanai. 

- **Data_TemplateFormat** — tās veidnes faila formāts, kas ir dokumenta pamatā.

- **Data_UsesNormal** — norāda, vai atvērtā dokumenta pamatā ir parasta veidne.

- **PathData_Doc_StreamAvailability —** norāda, vai ir pieejama/atspējota dokumenta plūsma.


#### <a name="officewordfileopenopenffileopenxstzcore"></a>Office.Word.FileOpen.OpenFFileOpenXstzCore

Šis notikums norāda, ka Office Word atver dokumentu, uz kura lietotājs veic dubultklikšķi. Tas satur arī kritiski svarīgus faila atvēršanas izpildes datus, un no lietotāja skatpunkta ir programmas startēšanas notikums. Notikums pārrauga, vai faila atvēršana ar dubultklikšķi darbojas pareizi. To izmanto arī, lai aprēķinātu mēneša aktīvos lietotājus/ierīces un mākoņpakalpojumu uzticamības rādītājus.

Tiek apkopoti tālāk norādītie lauki.

- **Data_AddDocTelemRes** — norāda, vai mēs varam pareizi aizpildīt citas ar dokumentu telemetriju saistītās vērtības šajā notikumā. Izmanto datu kvalitātes diagnostikai
    
- **Data_BytesAsynchronous** — baitu skaits (saspiests), bez kura uzskatām, ka varēsim atvērt failu, ja tos iegūstam pirms lietotājs vēlas sākt rediģēšanu vai saglabāšanu.
    
- **Data_BytesAsynchronousWithWork** — baitu skaits (saspiests), bez kura, iespējams, varēsim atvērt failu, taču tam būs nepieciešamas būtiskas koda izmaiņas.

- **Data_BytesSynchronous** — baitu skaits (saspiests), kuram jābūt mūsu rīcībā, pirms varam sākt faila atvēršanu.
    
- **Data_BytesUnknown**— baitu skaits dokumenta daļās, kuras neplānojam atrast.

- **Data_detachedDuration** — cik ilgi darbība bija atdalīta no pavediena.

- **Data_Doc_AccessMode —** dokuments ir tikai lasāms/rediģējams.

- **Data_Doc_AssistedReadingReasons** — iepriekš definētu vērtību kopa, kas norāda, kāpēc dokuments ir atvērts pieejamā lasīšanas režīmā.

- **Data_Doc_AsyncOpenKind — ** norāda, vai tika atvērta mākoņa dokumenta kešotā versijā un kura asinhronā atsvaidzināšanas loģika tika izmantota.

- **Data_Doc_ChunkingType —** vienības, kas tiek izmantotas inkrementālā dokumenta atvēršanā.

- **Data_Doc_EdpState —** dokumenta elektronisko datu aizsardzības iestatījums.

- **Data_Doc_Ext —** dokumenta paplašinājums (docx/xlsb/pptx utt.).

- **Data_Doc_FileFormat —** faila formāta protokola versija.

- **Data_Doc_Fqdn —** OneDrive vai SharePoint Online domēna nosaukums.

- **Data_Doc_FqdnHash —** klientu identificējama domēna nosaukuma vienvirziena jaukšana.

- **Data_Doc_IOFlags —** atskaites par kešotajiem karodziņiem, kas tiek izmantoti atvēršanas pieprasījuma opciju iestatīšanai.

- **Data_Doc_IdentityTelemetryId —** tādas lietotāja identitātes vienvirziena jaukšana, kas tiek izmantota atvēršanā.

- **Data_Doc_InitializationScenario —** dokumenta atvēršanas ieraksti.

- **Data_Doc_IrmRights —** dokumentam/lietotājam piemērotās elektronisko datu politikas atļautās darbības.

- **Data_Doc_IsIncrementalOpen —** karodziņš, kas norāda, ka dokuments tika atvērts inkrementāli.

- **Data_Doc_IsOcsSupported —** karodziņš, kas norāda, ka dokuments tiek atbalstīts sadarbības pakalpojumā.
    
- **Data_Doc_IsOpeningOfflineCopy —** karodziņš, kas norāda, ka tika atvērta dokumenta bezsaistes kopija.

- **Data_Doc_IsSyncBacked —** karodziņš, kas norāda, ka datorā pastāv automātiski sinhronizēta dokumenta kopija.

- **Data_Doc_Location —** norāda pakalpojumu, kurā atrodas dokuments (OneDrive, File Server, SharePoint utt.).
    
- **Data_Doc_LocationDetails —** norāda, kurā zināmajā mapē atrodas lokāli saglabātais dokuments.

- **Data_Doc_NumberCoAuthors —** citu lietotāju skaits koprediģēšanas sesijā.

- **Data_Doc_PasswordFlags —** norāda lasīšanas/rakstīšanas paroles karodziņu kopu.

- **Data_Doc_ReadOnlyReasons —** iemesli, kāpēc dokuments ir atvērts tikai lasāmajā režīmā.

- **Data_Doc_ResourceIdHash —** anonimizēts dokumenta identifikators, ko izmanto problēmu noteikšanā.

- **Data_Doc_RtcType —** norāda, kā reāllaika kanāls (RTC) bija iestatīts pašreizējam failam (atspējots, neatbalstīts, pēc pieprasījuma, vienmēr ieslēgts utt.).

- **Data_Doc_ServerDocId —** nemainīgs anonimizēts dokumenta identifikators, ko izmanto problēmu noteikšanā.

- **Data_Doc_ServerProtocol —** protokola versija, ko izmanto, lai sazinātos ar pakalpojumu.

- **Data_Doc_ServerType —** servera tips, kas nodrošina pakalpojumu (OneDrive, SharePoint, WOPI utt.).
    
- **Data_Doc_ServerVersion —** servera versija, kas nodrošina pakalpojumu. 

- **Data_Doc_SessionId —** identificē konkrētu dokumenta rediģēšanas sesiju pilnā sesijā.

- **Data_Doc_SharePointServiceContext —** diagnostikas informācija no SharePoint Online pieprasījumiem.

- **Data_Doc_SizeInBytes —** dokumenta lieluma rādītājs.

- **Data_Doc_SpecialChars —** speciālo rakstzīmju rādītājs dokumenta vietrādī URL vai ceļā.

- **Data_Doc_StreamAvailability —** norāda, vai ir pieejama/atspējota dokumenta plūsma.

- **Data_Doc_SyncBackedType —** norāda dokumenta veidu (lokālais vai servera).

- **Data_UrlHash —** vienvirziena jaukšana vienkāršota dokumenta identifikatora izveidei.

- **Data.Doc.WopiServiceId —** satur unikālu WOPI pakalpojumu sniedzēja identifikatoru.

- **Data_EditorDisablingRename** — pirmā redaktora identifikators, kas izraisīja pārdēvēšanas atspējošanu.

- **Data_EditorsCount** — redaktoru skaits dokumentā.

- **Data_FSucceededAfterRecoverableFailure** — norāda, ka atvēršana izdevās pēc kļūmes izlabošanas, kas radās dokumenta atvēršanas laikā.

- **Data_ForceReadWriteReason** — vesela skaitļa vērtība, kas attēlo iemeslu, kāpēc fails tika atvērts lasīšanas/rakstīšanas režīmā.
    
- **Data_LastLoggedTag** — unikāla atzīme koda izsaukuma vietā, ko izmanto, lai noteiktu, kad neizdodas atvērt divreiz (izmanto datu kvalitātes diagnostikai).

- **Data_LinkStyles** — norāda, vai ir saite ar veidņu stiliem.

- **Data_MainPdod** — dokumenta identifikators Office Word procesā.

- **Data_Measurements** — kodēta virkne, kas satur dažādu daļu atvēršanas laika sadalījumu. Izmanto, lai novērtētu izpildi.
    
- **Data_MoveDisabledReason** — kļūda, kas atspējo dokumenta pārvietošanu.

- **Data_MoveFlightEnabled** — vai lidojuma opcija pārvietošanas līdzeklī ir iespējota.

- **Data_PartsUnknown** — dokumenta daļu skaits, kurām mēs nevarējām iegūt datus.

- **Data_RecoverableFailureInitiationLocationTag** — unikāla atzīme koda izsaukumu vietā, lai identificētu vietu kodā, kur mēs mēģināsim izlabot failu pirms tā atvēršanas.

- **Data_RenameDisabledReason** — kļūda, kuras dēļ tiek atspējota dokumenta pārdēvēšana.

- **Data_RenameFlightEnabled** — vai testējamā varianta opcija pārdēvēšanas līdzeklī ir iespējota.

- **Data_SecondaryTag** — unikāla atzīme koda izsaukšanas vietai, kas tiek izmantota, lai pievienotu papildu kļūmes datus atvēršanai.

- **Data_TemplateFormat** — tās veidnes faila formāts, kas ir dokumenta pamatā.

- **Data_UsesNormal** — norāda, vai atvērtā dokumenta pamatā ir parasta veidne.


#### <a name="officewordfileopenopenifrinitargs"></a>Office.Word.FileOpen.OpenIfrInitArgs

Šis notikums norāda, ka Office Word atver dokumentu, izmantojot COM aktivizēšanu vai komandrindu. Tas satur arī kritiski svarīgus faila atvēršanas izpildes datus, un no lietotāja skatpunkta ir programmas startēšanas notikums. Notikums pārrauga, vai faila atvēršana no komandrindas darbojas pareizi. To izmanto arī, lai aprēķinātu mēneša aktīvos lietotājus/ierīces un mākoņpakalpojumu uzticamības rādītājus.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_AddDocTelemRes —** norāda, vai mēs varam pareizi aizpildīt citas ar dokumentu telemetriju saistītās vērtības šajā notikumā. Izmanto datu kvalitātes diagnostikai.

  - **Data\_BytesAsynchronous —** baitu skaits (saspiests), bez kura uzskatām, ka varēsim atvērt failu, ja tos iegūstam pirms lietotājs vēlas sākt rediģēšanu vai saglabāšanu

  - **Data\_BytesAsynchronousWithWork —** baitu skaits (saspiests), bez kura, iespējams, varēsim atvērt failu, taču tam būs nepieciešamas būtiskas koda izmaiņas

  - **Data\_BytesSynchronous —** baitu skaits (saspiests), kuram jābūt mūsu rīcībā, pirms varam sākt faila atvēršanu

  - **Data\_BytesUnknown —** baitu skaits dokumenta daļās, kuras neplānojam atrast.

  - **Data\_Doc\_AccessMode —** dokuments ir tikai lasāms/rediģējams

  - **Data\_Doc\_AssistedReadingReasons —** iepriekš definētu vērtību kopa, kas norāda, kāpēc dokuments ir atvērts pieejamā lasīšanas režīmā

  - **Data_Doc_AsyncOpenKind — ** norāda, vai tika atvērta mākoņa dokumenta kešotā versijā un kura asinhronā atsvaidzināšanas loģika tika izmantota.

  - **Data\_Doc\_ChunkingType —** vienības, kas tiek izmantotas inkrementālā dokumenta atvēršanā

  - **Data\_Doc\_EdpState —** dokumenta elektronisko datu aizsardzības iestatījums

  - **Data\_Doc\_Ext —** dokumentu paplašinājums (docx/xlsb/pptx utt.)

  - **Data\_Doc\_FileFormat —** faila formāta protokola versija

  - **Data\_Doc\_Fqdn —** OneDrive vai SharePoint Online domēna nosaukums

  - **Data\_Doc\_FqdnHash —** klientu identificējama domēna nosaukuma vienvirziena jaukšana

  - **Data\_Doc\_IOFlags —** atskaites par kešotajiem karodziņiem, kas tiek izmantoti pieprasījuma opciju iestatīšanai

  - **Data\_Doc\_IdentityTelemetryId —** tādas lietotāja identitātes vienvirziena jaukšana, kas tiek izmantota atvēršanā

  - **Data\_Doc\_InitializationScenario —** dokumenta atvēršanas ieraksti

  - **Data\_Doc\_IrmRights —** dokumentam/lietotājam piemērotās elektronisko datu politikas atļautās darbības

  - **Data\_Doc\_IsIncrementalOpen —** karodziņš, kas norāda, ka dokuments ir atvērts inkrementāli

  - **Data\_Doc\_IsOcsSupported —** karodziņš, kas norāda, ka dokuments tiek atbalstīts sadarbības pakalpojumā

  - **Data\_Doc\_IsOpeningOfflineCopy —** atzīme, kas norāda, ka tika atvērta dokumenta bezsaistes kopija

  - **Data\_Doc\_IsSyncBacked —** atzīme, kas norāda, ka datorā pastāv automātiski sinhronizēta dokumenta kopija

  - **Data\_Doc\_Location —** norāda pakalpojumu, kurā atrodas dokuments (OneDrive, File Server, SharePoint)

  - **Data\_Doc\_LocationDetails —** norāda, kurā zināmajā mapē atrodas lokāli saglabātais dokuments

  - **Data\_Doc\_NumberCoAuthors —** citu lietotāju skaits koprediģēšanas sesijā

  - **Data\_Doc\_PasswordFlags —** norāda lasīšanas/rakstīšanas paroles karodziņu kopu

  - **Data\_Doc\_ReadOnlyReasons —** iemesli, kāpēc dokuments ir atvērts tikai lasāmajā režīmā

  - **Data\_Doc\_ResourceIdHash —** anonimizēts dokumenta identifikators, ko izmanto problēmu noteikšanā

  - **Data_Doc_RtcType —** norāda, kā reāllaika kanāls (RTC) bija iestatīts pašreizējam failam (atspējots, neatbalstīts, pēc pieprasījuma, vienmēr ieslēgts utt.).

  - **Data\_Doc\_ServerDocId —** nemainīgs anonimizēts dokumenta identifikators, ko izmanto problēmu noteikšanā

  - **Data\_Doc\_ServerProtocol —** tā protokola versija, ko izmanto, lai sazinātos ar pakalpojumu

  - **Data\_Doc\_ServerType —** tā servera tips, kas nodrošina pakalpojumu (OneDrive, SharePoint, WOPI utt.)

  - **Data\_Doc\_ServerVersion —** tā servera versija, kas nodrošina pakalpojumu

  - **Data\_Doc\_SessionId —** tā servera versija, kas nodrošina pakalpojumu

  - **Data\_Doc\_SharePointServiceContext —** diagnostikas informācija no SharePoint Online pieprasījumiem

  - **Data\_Doc\_SizeInBytes —** dokumenta lieluma rādītājs

  - **Data\_Doc\_SpecialChars —** speciālo rakstzīmju rādītājs dokumenta vietrādī URL vai ceļā

  - **Data\_Doc\_StreamAvailability —** norāda, vai ir pieejama/atspējota dokumenta plūsma

  - **Data\_Doc\_SyncBackedType —** norāda dokumenta veidu (lokālais vai servera)

  - **Data\_Doc\_UrlHash —** vienvirziena jaukšana vienkāršota dokumenta identifikatora izveidei

  - **Data\_Doc\_WopiServiceId —** satur unikālu WOPI pakalpojumu sniedzēja identifikatoru

  - **Data\_EditorDisablingRename —** tā pirmā redaktora identifikators, kas izraisīja pārdēvēšanas atspējošanu

  - **Data\_EditorsCount —** redaktoru skaits dokumentā

  - **Datu\_FSucceededAfterRecoverableFailure —** norāda, ka atvēršana izdevās pēc kļūmes izlabošanas, kas radās dokumenta atvēršanas laikā

  - **Data\_ForceReadWriteReason —** vesela skaitļa vērtība, kas attēlo iemeslu, kāpēc fails tika atvērts lasīšanas/rakstīšanas režīmā

  - **Data\_LastLoggedTag —** unikāla atzīme koda izsaukuma vietā, ko izmanto, lai noteiktu, kad neizdodas atvērt divreiz (izmanto datu kvalitātes diagnostikai)

  - **Data\_LinkStyles —** norāda, vai ir saite ar veidņu stiliem

  - **Data\_MainPdod —** dokumenta identifikators Office Word procesā

  - **Data\_Measurements —** kodēta virkne, kas satur dažādu daļu atvēršanas laika sadalījumu. Izmanto, lai diagnosticētu atvēršanas izpildi.

  - **Data\_MoveDisabledReason —** kļūda, kas atspējo dokumenta pārvietošanu

  - **Data\_MoveFlightEnabled —** vai lidojuma opcija pārvietošanas līdzeklī ir iespējota

  - **Data\_PartsUnknown —** dokumenta daļu skaits, kurām mēs nevarējām iegūt datus

  - **Data\_RecoverableFailureInitiationLocationTag —** unikāla atzīme koda izsaukumu vietā, lai identificētu vietu kodā, kur mēs mēģināsim izlabot failu pirms tā atvēršanas

  - **Data\_RenameDisabledReason —** kļūda, kuras dēļ tiek atspējota dokumenta pārdēvēšana

  - **Data\_RenameFlightEnabled —** vai testējamā varianta opcija pārdēvēšanas līdzeklī ir iespējota

  - **Data\_SecondaryTag —** unikāla atzīme koda izsaukšanas vietai, kas tiek izmantota, lai pievienotu papildu kļūmes datus atvēršanai

  - **Data\_TemplateFormat —** tās veidnes faila formāts, kas ir dokumenta pamatā.

  - **Data\_UsesNormal —** norāda, vai atvērtā dokumenta pamatā ir parasta veidne


#### <a name="officewordfileopenopenloadfile"></a>Office.Word.FileOpen.OpenLoadFile

Šis notikums norāda, ka Office Word atver dokumentu, izmantojot atvēršanas dialoglodziņu. Tas satur arī kritiski svarīgus faila atvēršanas izpildes datus, un no lietotāja skatpunkta ir programmas startēšanas notikums. Notikums pārrauga, vai faila atvēršana no atvēršanas dialoglodziņa darbojas pareizi. To izmanto arī, lai aprēķinātu mēneša aktīvos lietotājus/ierīces un mākoņpakalpojumu uzticamības rādītājus.

Tiek apkopoti tālāk norādītie lauki.

- **Data_AddDocTelemRes** — norāda, vai mēs varam pareizi aizpildīt citas ar dokumentu telemetriju saistītās vērtības šajā notikumā. Izmanto datu kvalitātes diagnostikai.

- **Data_BytesAsynchronous** — baitu skaits (saspiests), bez kura uzskatām, ka varēsim atvērt failu, ja tos iegūstam pirms lietotājs vēlas sākt rediģēšanu vai saglabāšanu.

- **Data_BytesAsynchronousWithWork** — baitu skaits (saspiests), bez kura, iespējams, varēsim atvērt failu, taču tam būs nepieciešamas būtiskas koda izmaiņas.
    
- **Data_BytesSynchronous** — baitu skaits (saspiests), kuram jābūt mūsu rīcībā, pirms varam sākt faila atvēršanu.

- **Data_BytesUnknown**— baitu skaits dokumenta daļās, kuras neplānojam atrast.

- **Data_detachedDuration** — cik ilgi darbība bija atdalīta no pavediena.

- **Data_Doc_AccessMode —** dokuments ir tikai lasāms/rediģējams.

- **Data_Doc_AssistedReadingReasons** — iepriekš definētu vērtību kopa, kas norāda, kāpēc dokuments ir atvērts pieejamā lasīšanas režīmā.

- **Data_Doc_AsyncOpenKind — ** norāda, vai tika atvērta mākoņa dokumenta kešotā versijā un kura asinhronā atsvaidzināšanas loģika tika izmantota.

- **Data_Doc_ChunkingType —** vienības, kas tiek izmantotas inkrementālā dokumenta atvēršanā.

- **Data_Doc_EdpState —** dokumenta elektronisko datu aizsardzības iestatījums.

- **Data_Doc_Ext —** dokumenta paplašinājums (docx/xlsb/pptx utt.).

- **Data_Doc_FileFormat —** faila formāta protokola versija.

- **Data_Doc_Fqdn —** OneDrive vai SharePoint Online domēna nosaukums.

- **Data_Doc_FqdnHash —** klientu identificējama domēna nosaukuma vienvirziena jaukšana.

- **Data_Doc_IdentityTelemetryId —** tādas lietotāja identitātes vienvirziena jaukšana, kas tiek izmantota atvēršanā.

- **Data_Doc_InitializationScenario —** dokumenta atvēršanas ieraksti.

- **Data_Doc_IOFlags —** atskaites par kešotajiem karodziņiem, kas tiek izmantoti atvēršanas pieprasījuma opciju iestatīšanai.

- **Data_Doc_IrmRights —** dokumentam/lietotājam piemērotās elektronisko datu politikas atļautās darbības.
    
- **Data_Doc_IsIncrementalOpen —** karodziņš, kas norāda, ka dokuments tika atvērts inkrementāli.

- **Data_Doc_IsOcsSupported —** karodziņš, kas norāda, ka dokuments tiek atbalstīts sadarbības pakalpojumā.

- **Data_Doc_IsOpeningOfflineCopy —** karodziņš, kas norāda, ka tika atvērta dokumenta bezsaistes kopija.

- **Data_Doc_IsSyncBacked —** karodziņš, kas norāda, ka datorā pastāv automātiski sinhronizēta dokumenta kopija.

- **Data_Doc_Location —** norāda pakalpojumu, kurā atrodas dokuments (OneDrive, File Server, SharePoint utt.).

- **Data_Doc_LocationDetails —** norāda, kurā zināmajā mapē atrodas lokāli saglabātais dokuments.

- **Data_Doc_NumberCoAuthors —** citu lietotāju skaits koprediģēšanas sesijā.

- **Data_Doc_PasswordFlags —** norāda lasīšanas/rakstīšanas paroles karodziņu kopu.

- **Data_Doc_ReadOnlyReasons —** iemesli, kāpēc dokuments ir atvērts tikai lasāmajā režīmā.

- **Data_Doc_ResourceIdHash —** anonimizēts dokumenta identifikators, ko izmanto problēmu noteikšanā.

- **Data_Doc_RtcType —** norāda, kā reāllaika kanāls (RTC) bija iestatīts pašreizējam failam (atspējots, neatbalstīts, pēc pieprasījuma, vienmēr ieslēgts utt.).

- **Data_Doc_ServerDocId —** nemainīgs anonimizēts dokumenta identifikators, ko izmanto problēmu noteikšanā. 

- **Data_Doc_ServerProtocol —** protokola versija, ko izmanto, lai sazinātos ar pakalpojumu.

- **Data_Doc_ServerType —** servera tips, kas nodrošina pakalpojumu (OneDrive, SharePoint, WOPI utt.).

- **Data_Doc_ServerVersion —** servera versija, kas nodrošina pakalpojumu.

- **Data_Doc_SessionId —** identificē konkrētu dokumenta rediģēšanas sesiju pilnā sesijā.

- **Data_Doc_SharePointServiceContext —** diagnostikas informācija no SharePoint Online pieprasījumiem.

- **Data_Doc_SizeInBytes —** dokumenta lieluma rādītājs.

- **Data_Doc_SpecialChars —** speciālo rakstzīmju rādītājs dokumenta vietrādī URL vai ceļā.

- **Data_Doc_StreamAvailability —** norāda, vai ir pieejama/atspējota dokumenta plūsma.

- **Data_Doc_SyncBackedType —** norāda dokumenta veidu (lokālais vai servera).

- **Data_UrlHash —** vienvirziena jaukšana vienkāršota dokumenta identifikatora izveidei.

- **Data_EditorDisablingRename** — pirmā redaktora identifikators, kas izraisīja pārdēvēšanas atspējošanu.

- **Data_EditorsCount** — redaktoru skaits dokumentā.

- **Data_ForceReadWriteReason** — vesela skaitļa vērtība, kas attēlo iemeslu, kāpēc fails tika atvērts lasīšanas/rakstīšanas režīmā.
    
- **Data_FSucceededAfterRecoverableFailure** — norāda, ka atvēršana izdevās pēc kļūmes izlabošanas, kas radās dokumenta atvēršanas laikā.

- **Data_LastLoggedTag** — unikāla atzīme koda izsaukuma vietā, ko izmanto, lai noteiktu, kad neizdodas saglabāt divreiz (izmanto datu kvalitātes diagnostikai).

- **Data_LinkStyles** — norāda, vai ir saite ar veidņu stiliem.

- **Data_MainPdod** — dokumenta identifikators Office Word procesā.

- **Data_Measurements** — kodēta virkne, kas satur dažādu daļu atvēršanas laika sadalījumu. Izmanto, lai novērtētu izpildi.

- **Data_MoveDisabledReason** — kļūda, kas atspējo dokumenta pārvietošanu.

- **Data_MoveFlightEnabled** — vai lidojuma opcija pārvietošanas līdzeklī ir iespējota.

- **Data_PartsUnknown** — dokumenta daļu skaits, kurām mēs nevarējām iegūt datus.

- **Data_RecoverableFailureInitiationLocationTag** — unikāla atzīme koda izsaukumu vietā, lai identificētu vietu kodā, kur mēs mēģināsim izlabot failu pirms tā atvēršanas.

- **Data_RenameDisabledReason** — kļūda, kuras dēļ tiek atspējota dokumenta pārdēvēšana.

- **Data_RenameFlightEnabled** — vai testējamā varianta opcija pārdēvēšanas līdzeklī ir iespējota.

- **Data_SecondaryTag** — unikāla atzīme koda izsaukšanas vietai, kas tiek izmantota, lai pievienotu papildu kļūmes datus atvēršanai.

- **Data_TemplateFormat** — tās veidnes faila formāts, kas ir dokumenta pamatā.

- **Data_UsesNormal** — norāda, vai atvērtā dokumenta pamatā ir parasta veidne.


#### <a name="renewuserop"></a>RenewUserOp

Tiek apkopots, kad lietotājs mēģina atvērt ar IRM aizsargātu dokumentu vai lietot IRM aizsardzību.  Tas satur informāciju, kas ir nepieciešama pareizai tādu problēmu izmeklēšanai un diagnosticēšanai, kas notiek lietotāja sertifikātu atjaunošanas darbības laikā. 

Tiek apkopoti tālāk norādītie lauki.

- **AppInfo.ClientHierarchy** — klienta hierarhija, kas norāda, ka lietojumprogramma darbojas ražošanas vidē vai izstrādātāja vidē

- **AppInfo.Name** — lietojumprogrammas nosaukums

- **AppInfo.Version** — lietojumprogrammas versija

- **iKey** — reģistrētāja servera ID

- **RMS.ApplicationScenarioId** — scenārija ID, ko nodrošina lietojumprogramma

- **RMS.Duration** — kopējais laiks darbības veikšanai

- **RMS.DurationWithoutExternalOps** — kopējais patērētais laiks mīnus ārējās operācijas, piemēram, tīkla latentums.

- **RMS.ErrorCode** — atgrieztais kļūdas kods, ja tāds ir, no darbības

- **RMS.HttpCall** — norāda, vai ir HTTP operācija

- **RMS.LicenseFormat** — licences formāts: XrML vai JSON

- **RMS.Result** — darbība sekmīga vai neizdevās

- **RMS.ScenarioId** — scenārija ID, ko definē tiesību pārvaldības pakalpojuma klients

- **RMS.SDKVersion** — tiesību pārvaldības pakalpojuma klienta versija

- **RMS.ServerType** — tiesību pārvaldības pakalpojuma servera tips 

- **RMS.StatusCode** — darbības rezultāta statusa kods

- **RMS.Type** — lietotāja informācijas tips

#### <a name="servicediscoveryop"></a>ServiceDiscoveryOp

Tiek apkopots, kad lietotājs mēģina atvērt ar IRM aizsargātu dokumentu vai lietot IRM aizsardzību.  Tas satur informāciju, kas ir nepieciešama pareizai tādu problēmu izmeklēšanai un diagnosticēšanai, kas notiek pakalpojuma atklāšanas darbības laikā. 

Tiek apkopoti tālāk norādītie lauki.

- **AppInfo.ClientHierarchy** — klienta hierarhija, kas norāda, ka lietojumprogramma darbojas ražošanas vidē vai izstrādātāja vidē

- **AppInfo.Name** — lietojumprogrammas nosaukums

- **AppInfo.Version** — lietojumprogrammas versija

- **iKey** — pieteikšanās pakalpojuma servera ID

- **RMS.ApplicationScenarioId** — scenārija ID, ko nodrošina lietojumprogramma

- **RMS.Duration** — kopējais laiks darbības veikšanai

- **RMS.DurationWithoutExternalOps** — kopējais patērētais laiks mīnus ārējās operācijas, piemēram, tīkla latentums.

- **RMS.ErrorCode** — atgrieztais kļūdas kods, ja tāds ir, no darbības

- **RMS.HttpCall** — norāda, vai pastāv HTTP operācija

- **RMS.LicenseFormat** — licences formāts: XrML vai JSON

- **RMS.OperationName** — darbības nosaukums

- **RMS.Result** — darbība sekmīga vai neizdevās

- **RMS.ScenarioId** — scenārija ID, ko definē tiesību pārvaldības pakalpojuma klients

- **RMS.SDKVersion** — tiesību pārvaldības pakalpojuma klienta versija

- **RMS.ServerType** — tiesību pārvaldības pakalpojuma servera tips 

- **RMS.StatusCode** — darbības rezultāta statusa kods


### <a name="office-accessibility-configuration-subtype"></a>*Office pieejamības konfigurācijas apakštips*

Office pieejamības līdzekļi

#### <a name="officeaccessibilityaccessibilitytoolsessionpresencewin32"></a>Office.Accessibility.AccessibilityToolSessionPresenceWin32

Ļauj mums noteikt, vai lietotājam ir palīgtehnoloģiju rīks, un tā nosaukumu. Tas ļauj saprast, vai Office lietotājam ir radušās problēmas ar konkrētu palīgtehnoloģiju rīku.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_Data\_Jaws —** norāda, vai Jaws darbojās sesijas laikā**Data\_Data\_Magic —** norāda, vai Magic darbojās sesijas laikā

  - **Data\_Data\_Magnify —** norāda, vai Magnify darbojās sesijas laikā

  - **Data\_Data\_Narrator —** norāda, vai Diktors darbojās sesijas laikā

  - **Data\_Data\_NVDA —** norāda, vai NVDA darbojās sesijas laikā

  - **Data\_Data\_SA —** norāda, vai SA darbojās sesijas laikā

  - **Data\_Data\_Supernova —** norāda, vai Supernova darbojās sesijas laikā

  - **Data\_Data\_SuperNovaessSuite —** norāda, vai SuperNovaessSuite darbojās sesijas laikā

  - **Data\_Data\_WinEyes —** norāda, vai WinEyes darbojās sesijas laikā

  - **Data\_Data\_ZoomText —** norāda, vai ZoomText darbojās sesijas laikā

#### <a name="office_apple_darkmode"></a>Office_Apple_DarkMode

Šo notikumu apkopo Office programmām, kas tiek lietotas Apple platformās. Šis notikums norāda, vai lietotājs darbina sistēmu DarkMode, un vai lietotājs ir pārrakstījis DarkMode sistēmas iestatījumu programmā Office.  Šis notikums tiek izmantots, lai nodrošinātu pieejamību un noteiktu prioritāti lietotāju ērtību optimizācijai.

Tiek apkopoti šādi lauki:

- **Data_DarkModeIsEnabled** — vai DarkMode sistēma ir iespējota.

- **Data_RequiresAquaSystemAppearanceEnabled** — vai DarkMode sistēma ir pārrakstīta programmā Office.

#### <a name="office_apple_hardwarekeyboardinuse_apple"></a>Office_Apple_HardwareKeyboardInUse_Apple

Šo notikumu apkopo Office programmām, kas tiek lietotas Apple platformās. Šis notikums norāda, ka lietotājs pievieno tastatūru savā mobilajā ierīcē. Šis pasākums palīdz mums uzlabot pieejamību un optimizēt mūsu lietotāja pieredzi.

Tiek apkopoti šādi lauki:

- **Data_CollectionTime** — laikspiedols, kas apzīmē notikumu vākšanas laiku.

#### <a name="office_apple_mbuinstrument_deviceaccessibilitysettings"></a>Office_Apple_MbuInstrument_DeviceAccessibilitySettings

Šo notikumu apkopo Office programmām, kas tiek lietotas Apple platformās. Pasākums apkopo dažādas pieejamības opcijas, kas pieejamas sesijas laikā. Šis notikums tiek izmantots, lai nodrošinātu pieejamību un noteiktu prioritāti lietotāju ērtību optimizācijai.

Tiek apkopoti šādi lauki:

- **Data_AccessibilityContentSize** — karodziņš, kas norāda, vai šis iestatījums ir iespējots

- **Data_AssistiveTouchRunning** — karodziņš, kas norāda, vai šis iestatījums ir iespējots

- **Data_BoldTextEnabled** — karodziņš, kas norāda, vai šis iestatījums ir iespējots

- **Data_CollectionTime** — karodziņš, kas norāda, vai šis iestatījums ir iespējots

- **Data_DarkerSystemColorsEnabled** — karodziņš, kas norāda, vai šis iestatījums ir iespējots

- **Data_DifferentiateWithoutColor** — karodziņš, kas norāda, vai šis iestatījums ir iespējots

- **Data_GrayscaleEnabled** — karodziņš, kas norāda, vai šis iestatījums ir iespējots

- **Data_GuidedAccessEnabled** — karodziņš, kas norāda, vai šis iestatījums ir iespējots

- **Data_IncreaseContrast** — karodziņš, kas norāda, vai šis iestatījums ir iespējots

- **Data_InvertColorsEnabled** — karodziņš, kas norāda, vai šis iestatījums ir iespējots

- **Data_PreferredContentSizeCategory** — karodziņš, kas norāda, vai šis iestatījums ir iespējots

- **Data_ReduceMotionEnabled** — karodziņš, kas norāda, vai šis iestatījums ir iespējots

- **Data_ReduceTransparency** — karodziņš, kas norāda, vai šis iestatījums ir iespējots

- **Data_ReduceTransparencyEnabled** — karodziņš, kas norāda, vai šis iestatījums ir iespējots

- **Data_ShakeToUndeEnabled** — karodziņš, kas norāda, vai šis iestatījums ir iespējots. (Novecojis — tiek izmantots tikai vecajos būvējumos.)

- **Data_ShakeToUndoEnabled** — karodziņš, kas norāda, vai šis iestatījums ir iespējots.

- **Data_SpeakScreenEnabled** — karodziņš, kas norāda, vai šis iestatījums ir iespējots

- **Data_SpeakSelectionEnabled** — karodziņš, kas norāda, vai šis iestatījums ir iespējots

- **Data_SwitchControlRunning** — karodziņš, kas norāda, vai šis iestatījums ir iespējots

- **Data_UAZoomEnabled** — karodziņš, kas norāda, vai šis iestatījums ir iespējots

- **Data_VoiceOverRunning** — karodziņš, kas norāda, vai šis iestatījums ir iespējots

#### <a name="officewordaccessibilitylearningtoolsreadaloudplayreadaloud"></a>Office.Word.Accessibility.LearningTools.ReadAloud.PlayReadAloud

Šis notikums norāda, vai Office Word lasa dokumenta tekstu. Šis notikums ir pieejamības līdzekļa periodiskais kontrolziņojums, kas ļauj Microsoft izvērtēt teksta lasīšanas līdzekļa darbspēju.

Tiek apkopoti šādi lauki:

  - **Data\_ParagraphCount —** rindkopu skaits dokumentā

  - **Data\_Play —** vai šī ir pirmā reize, kad programma Word lasa balsī

  - **Data\_ViewKind —** dokumenta skatīšanas tips

#### <a name="officewordaccessibilitylearningtoolsreadaloudstopreadaloud"></a>Office.Word.Accessibility.LearningTools.ReadAloud.StopReadAloud

Šis notikums norāda, vai Office Word pārtrauc lasīt dokumenta tekstu. Notikums ļauj Microsoft novērtēt līdzekli lasīšanas balsī līdzekļa darbspēju, nosakot darbības ilgumu.

Tiek apkopoti tālāk norādītie lauki.

  - Nav

### <a name="privacy-subtype"></a>*Konfidencialitātes apakštips*

Office konfidencialitātes iestatījumi 

#### <a name="officeintelligentserviceprivacyconsentprivacyevent"></a>Office.IntelligentService.PrivacyConsent.PrivacyEvent

Šis notikums apzīmē lietotāja vai sistēmas iniciētu darbību, kas ir daļa no Office lietotāju pieredzes ar konfidencialitāti. Tas tiek aktivizēts konfidencialitātes dialogos Pirmā palaišana, dialogā Konta konfidencialitāte un konfidencialitātes paziņojumos. Notikums tiek izmantots, lai izprastu šādus faktorus: lietotāju piekrišana Office konfidencialitātes iestatījumiem, lietotāju veiktas Office konfidencialitātes iestatījumu izmaiņas un Office konfidencialitātes iestatījumu atjaunināšana lietotāju sesijās.

Tiek apkopoti tālāk norādītie lauki:

  - **Data_ActionId —** lietotāja darbība konfidencialitātes dialogā

  - **Data_ControllerConnectedServicesState —** lietotāju politikas iestatījums papildu savienotajām pieredzēm pēc izvēles

  - **Data_DownloadedContentServiceGroupState —** lietotāja iestatījums lejupielādētajam saturam 
 
  - **Data_ForwardLinkId —** saite uz konfidencialitātes dokumentiem saistībā ar lietotāja scenāriju

  - **Data_HRESULT —** kļūdu ieraksts mijiedarbības laikā ar konfidencialitātes dialogu

  - **Data_IsEnterpriseUser —** lietotāja licences kategorija

  - **Data_OfficeServiceConnectionState —** lietotāja iestatījums savienotajiem pakalpojumiem

  - **Data_RecordRegistry —** uzņēmumu konfidencialitātes dialoga rādīšanas ieraksts

  - **Data_Scenario —** pirmās palaišanas scenārijs saistībā ar lietotāja licenci un kategoriju

  - **Data_SeenInsidersDialog —** Insider programmas dalībnieku dialoga rādīšanas ieraksts

  - **Data_SendTelemetryOption —** lietotāja iestatījums telemetrijai

  - **Data_SendTelemetryOptionPolicy —** lietotāja politikas iestatījums telemetrijai

  - **Data_UserCategory —** lietotāja konta veids  

  - **Data_UserCCSDisabled —** lietotāja iestatīta ignorēšana papildu savienotajām pieredzēm pēc izvēles

   - **Data_UserContentServiceGroupState —** lietotāja iestatījums satura analīzei

  - **Data_WillShowDialogs —** reižu skaits, kad lietotājam bijusi nepieciešamība skatīt konfidencialitātes dialogus Pirmā palaišana



## <a name="product-and-service-performance-data-events"></a>Produktu un pakalpojumu izpildes datu notikumi

Tālāk ir norādīti šīs kategorijas datu apakštipi.
- [Neparedzēts lietojumprogrammas darbības pārtraukums (avārijas)](#unexpected-application-exit-crash-subtype)
- [Lietojumprogrammas līdzekļu novērtējums](#application-feature-performance-subtype)
- [Lietojumprogrammas darbības kļūda](#application-activity-error-subtype)

### <a name="unexpected-application-exit-crash-subtype"></a>*Neparedzēts lietojumprogrammas darbības pārtraukums (avārijas) apakštips*

Neparedzēts lietojumprogrammas darbības pārtraukums un programmas statuss brīdī, kad tas notika.

#### <a name="app_startup_reason"></a>app_startup_reason

Šis notikums ļauj mums atklāt un novērst problēmas, kuru dēļ notika Outlook avārija sāknēšanas laikā.  Šis notikums iekļauj informāciju par avārijas iemeslu, lai mēs spētu novērst problēmu pēc iespējas ātrāk.

Tiek apkopoti šādi lauki: 

- **app_background_time** — laiks, ko pēdējās sesijas laikā lietojumprogramma pavadīja fonā

- **startup_reason_type** — norāda, kāpēc lietojumprogramma tiek sāknētā, kā arī norāda, vai iemesls ir piespiedu iziešana vai cits iemesls. 

- **watch_status_info** — uzskaita tālāk noradīto informāciju, ja attiecināms. 

  - **is_watch_app_installed** — nosaka, vai lietotājs ir instalējis pulksteņa lietojumprogrammu

  - **is_watch_paired** — nosaka, vai iOS ierīce ir savienota ar pulksteni

  - **is_watch_supported_and_active** — norāda, vai pulkstenis sesijas laikā nodrošina atbalstu un ir aktīvs

Tālāk norādītie lauki tiek apkopoti tikai Outlook Mobile darbam ar iOS:

- **clean_exit_reason** — vārdu virkne, kas norāda, vai ir iemesls lietojumprogrammas apturēšanai

- **is_agenda_user** — norāda, vai lietotājs ir nesen atvēris dienas kārtību, kas norāda, vai notiek ierakstīšana diskā sāknēšanas laikā 

- **is_watch_supported_and_active** — norāda, vai pulkstenis sesijas laikā nodrošina atbalstu un ir aktīvs


#### <a name="application_crash"></a>application_crash

Izmanto, lai uzraudzītu kritiskas lietojumprogrammu avārijas, un palīdz mums apkopot informāciju par to, kāpēc notika lietojumprogrammas avārija un kā to novērst.

Tiek apkopoti šādi lauki: 

- **android.hardware.** — (piem., android.hardware.bluetooth) Android platformas sniegtās aparatūras konfigurācijas vērtības

- **android.software.** — (e.g. android.software.device_admin) Android platformas sniegtās programmatūras konfigurācijas vērtības

- **android_version** — ierīces Android versijas nosaukums, kas norādīts android.os.Build.VERSION#RELEASE

- **application_package_name** — lietojumprogrammas pakotnes nosaukums, kas norādīts android.content.Context#getPackageName()

- **application_stack_trace** — avārijas izsekošanas steks

- **application_version_code** — Outlook lietojumprogrammas noteiktais lietojumprogrammas versijas kods

- **application_version_name** — Outlook lietojumprogrammas noteiktais lietojumprogrammas versijas nosaukums 

- **com.** (piem., com.google.android.feature.FASTPASS_BUILD, com.amazon.feature.PRELOAD, com.samsung.android.bio.face) Android platformas nodrošinātās ražotājam specifiskas konfigurācijas vērtības

- **device_brand** — ierīces zīmols (ražotājs vai operators), ko norāda android.os.Build#BRAND

- **device_ID** — ierīces unikālais ID (IMEI)

- **device_manufacturer** — ierīces ražotājs, ko norāda android.os.Build#MANUFACTURER

- **device_model** — ierīces modelis, ko norāda android.os.Build#MODEL

- **device_name** — ierīces nosaukums, ko norāda android.os.Build#DEVICE

- **device_total_memory** — kopējā ierīces atmiņas apjoma novērtējums, pamatojoties uz filesystem datiem.

- **glEsVersion** — OpenGL iegulto sistēmu versijas atslēga


#### <a name="crash_event"></a>crash_event

Palīdz mums atklāt un novērst situācijas, kurās notiek kritiskas lietojumprogrammas avārijas, un palīdz mums apkopot informāciju par lietojumprogrammas avārijas iemesliem un kā tos novērst.

Tiek apkopoti šādi lauki: 

- **crashTime** — avārijas datums un laiks, kas palīdz mūsu izmeklēšanai

- **exceptionName** — izņēmuma, kas izraisīja avāriju, nosaukums, lai palīdzētu mūsu izmeklēšanai

- **hasHx** — norāda, vai konts izmanto jauno sinhronizācijas pakalpojumu, lai palīdzētu noteikt mūsu sinhronizācijas pakalpojuma radītās problēmas

- **incidentIdentifier** — unikāls ID avārijas ziņojumam, kas palīdz mums atklāt atbilstošo problēmu

- **isAppKill** — palīdz mums noteikt, vai lietojumprogramma ierīcē tika apturēta vai aizvērta

- **reportKey** — unikāls lietojumprogrammas instalēšanas ID ierīcē problēmu izmeklēšanai

- **signal** — signāls, kas izraisīja avāriju, lai sniegtu mums papildu informāciju šīs avārijas izmeklēšanā


#### <a name="error"></a>Error

Ļauj mums noteikt problēmas, ar kurām saskaras mobilās lietojumprogrammas, kad tās mēģina izgūt konfidencialitātes iestatījumus no servera.

Tiek apkopoti šādi lauki:

- **correlationId** — unikāls identifikators pakalpojuma savienojumam, kas radīja kļūdu, ļauj mums diagnosticēt iespējamos kļūdas iemeslus

- **errorCode** — identificē atbilstošo kļūdas kodu, kas saņemts no pakalpojuma un kuru var izmantot problēmas diagnosticēšanai

- **exceptionType** — kļūdas tips, ar kuru saskārās bibliotēka iestatījuma ieneses laikā

- **message** — identificē no pakalpojuma saņemto kļūdas ziņojumu

- **roamingSettingType** — nosaka atrašanās vietu, no kuras tika veikts mēģinājums nolasīt iestatījumus

- **settingId** — iestatījums, kuru mēģināja ienest

#### <a name="officeappdomainunhandledexceptionhandlerfailed"></a>Office.AppDomain.UnhandledExceptionHandlerFailed

Apkopo informāciju par neapstrādātiem izņēmumiem, izmantojot programmu Data Streamer. Šie dati tiek izmantoti, lai pārraudzītu programmas darbspēju. Šo notikumu ģenerē Microsoft Data Streamer Excel pievienojumprogrammai.

Tiek apkopoti tālāk norādītie lauki.

- **Exception** — izņēmuma izsaukuma steks

- **Event Name** — notikuma nosaukums ir notikuma kategorija un notikuma etiķete.

#### <a name="office_apple_identitydomainname"></a>Office_Apple_IdentityDomainName

Šo notikumu apkopo Office programmām, kas tiek lietotas Apple platformās. Pasākums tiek lietots, lai pārraudzītu mūsu sistēmas darbspēju, kā arī noteiktu domēna lietotāju neveiksmes iemeslus. Mēs apkopojam domēnu, ko izmanto mūsu lietotāji autentificēšanas laikā.  Šie dati tiek izmantoti, lai palīdzētu noteikt un novērst problēmas, kas var neradīt pārāk lielu iespaidu plašākā līmenī, bet ir ļoti iespaidīgas noteiktiem lietotāju domēniem.

Tiek apkopoti šādi lauki:

- **Data_Domain** — autentifikācijai izmantotais domēns

- **Data_IdentityProvider** — autentifikācijas identitātes nodrošinātāja nosaukums. (piem., LiveId vai ADAL)

- **Data_IdentityProviderEnum** — autentifikācijas identitātes nodrošinātāja nosaukums. (Skaitlis)

#### <a name="office_apple_systemhealthappexitmacandios"></a>Office_Apple_SystemHealthAppExitMacAndiOS

Šo notikumu apkopo Office programmām, kas tiek lietotas Apple platformās. Pasākums tiek lietots, lai pārraudzītu mūsu Office programmu darbspēju, kā arī noteiktu kļūmju iemeslus. Mēs apkopojam datus katras programmas iziešanas laikā, lai noteiktu, vai no programmas ir iziets bez aizķeršanās.

Tiek apkopoti šādi lauki:

- **Data_AffectedProcessSessionID** — sesijas identifikators, kas veic programmas iziešanu.

- **Data_AffectedSessionBuildNumber** — tās programmas sekundārā versija, kurā tika novērota programmas iziešana.

- **Data_AffectedSessionDuration** — sesijas ilgums no sākuma līdz beigām

- **Data_AffectedSessionIDSMatch** — telemetrijas darbspējas rādītājs.

- **Data_AffectedSessionMERPSessionID** — telemetrijas darbspējas rādītājs.

- **Data_AffectedSessionOSLocale** — tās operētājsistēmas lokalizācija, ar kuru tika novērota programmas iziešana.

- **Data_AffectedSessionOSVersion** — tās operētājsistēmas lokalizācija, ar kuru tika novērota programmas iziešana.

- **Data_AffectedSessionResidentMemoryOnCrash** — rezidenta atmiņas apjoms, kas tika patērēts, kad tika veikta lietojumprogrammas iziešana

- **Data_AffectedSessionStackHash** — identifikators, kas aprakstīs konkrētās kļūdas trāpījums.

- **Data_AffectedSessionStartTime** — laiks, kad sesija sākās.

- **Data_AffectedSessionUAEType** — novērotais programmas iziešanas veids (ja tas bija ar aizķeršanos iziešanas gadījumā, šis kods apzīmēs novērotās kļūdas tipu)

- **Data_AffectedSessionBuildNumber** — programmas galvenā versija, kurā tika novērota programmas iziešana.

- **Data_AffectedSessionResidentMemoryOnCrash** — virtuālās atmiņas apjoms, kas tika patērēts, kad notika programmas iziešana.

- **Data_ExitWasGraceful** — vai programmas iziešana bija bez aizķeršanās vai ar aizķeršanos.

#### <a name="officeextensibilitycomaddinunhandledexception"></a>Office.Extensibility.COMAddinUnhandledException

Šis notikums tiek ģenerēts, kad Office lietotāju versijā notiek COM pievienojumprogrammas avārija. 

Izmantošana: izmanto, lai izskaitļotu globālu, ar konkrētu uzņēmumu nesaistītu Office 365 ProPlus pievienojumprogrammas ieviešanu, tālāk izmantojot ar tādiem rīkiem kā Readiness Toolkit. Ļauj biznesa versiju klientiem pārbaudīt, vai viņu organizācijā uzstādītās pievienojumprogrammas ir saderīgas ar jaunākajām Office 365 ProPlus versijām, ļaujot plānot tālākos atjauninājumus. 

Tiek apkopoti tālāk norādītie lauki.

- **ScopeId** — pašreizējā pavediena tvērums

- **Method** — Office metode, kurā radās izņēmums

- **Interface** — Office interfeiss, kurā radās izņēmums

- **AddinId** — pievienojumprogrammas klases ID

- **AddinProgId** — novecojis.

- **AddinFriendlyName** — novecojis.

- **AddinTimeDateStamp** — pievienojumprogrammas laikspiedols no DLL metadatiem.

- **AddinVersion** — novecojis.

- **AddinFileName** — novecojis.

- **VSTOAddIn** — vai pievienojumprogramma ir VSTO

- **AddinConnectFlag** — pašreizējās ielādes darbība

- **LoadAttempts** — pievienojumprogrammas ielādes mēģinājumu skaits

#### <a name="officeextensibilitycomaddinunhandledexceptionenterprise"></a>Office.Extensibility.COMAddinUnhandledExceptionEnterprise

Šis notikums tiek ģenerēts, kad Office biznesa versijā notiek COM pievienojumprogrammas avārija.

Izmantošana: izmanto, lai izskaitļotu globālu, ar konkrētu uzņēmumu nesaistītu Office 365 ProPlus pievienojumprogrammas ieviešanu, tālāk izmantojot ar tādiem rīkiem kā Readiness Toolkit. Ļauj biznesa versiju klientiem pārbaudīt, vai viņu organizācijā uzstādītās pievienojumprogrammas ir saderīgas ar jaunākajām Office 365 ProPlus versijām, ļaujot plānot tālākos atjauninājumus. 

- **ScopeId** — pašreizējā pavediena tvērums

- **Method** — Office metode, kurā radās izņēmums

- **Interface** — Office interfeiss, kurā radās izņēmums

- **AddinId** — pievienojumprogrammas klases ID

- **AddinProgId** — novecojis.

- **AddinFriendlyName** — novecojis.

- **AddinTimeDateStamp** — pievienojumprogrammas laikspiedols no DLL metadatiem.

- **AddinVersion** — novecojis.

- **AddinFileName** — novecojis.

- **VSTOAddIn** — vai pievienojumprogramma ir VSTO

- **AddinConnectFlag** — pašreizējās ielādes darbība

- **LoadAttempts** — pievienojumprogrammas ielādes mēģinājumu skaits

#### <a name="officeextensibilitysandboxodpactivationheartbeat"></a>Office.Extensibility.Sandbox.ODPActivationHeartbeat

Office pievienojumprogrammas darbojas smilškastē. Notikums periodiski apkopo informāciju par aktivācijām. Kad notiek pievienojumprogrammas avārija, notikums apkopo ar mūsu smilškasti saistītās avārijas iemeslu. Izmanto gadījumos, kad klienti aktualizē problēmas.
 
Tiek apkopoti tālāk norādītie lauki.

- **AppId** — lietojumprogrammas ID.

- **AppInfo** — dati par pievienojumprogrammas veidu (uzdevumrūts vai UILess, vai iegulšanas utt.) un nodrošinātāja veidu (omen, SharePoint, filesystem utt.).

- **AppInstanceId** — lietojumprogrammas instances ID. 

- **AssetId** — lietojumprogrammas līdzekļa ID.

- **ErrorCodeime** — iztērētais laiks kopā.

- **IsAugmentationScenario**— norāda uz to, vai pieauguma cilpa ir atbildīga par Office Solutions struktūras vadības inicializēšanu.

- **IsDebug** - norāda, vai sesija ir atkļūdošanas sesija

- **NumberOfAddinsActivated** — aktivēto pievienojumprogrammu skaitītājs.

- **RemoterType** — norāda pievienojumprogrammas aktivēšanai izmantotā attālinātāja veidu (uzticams, neuzticams, Win32webView, uzticams UDF utt.).

- **StoreType** — lietojumprogrammas izcelsme.

- **Atzīme**— norāda, kur tieši kodam radās kļūme, izmantojot ar to saistīto unikālo atzīmi.

- **UsesSharedRuntime** — norāda, ka programma izmanto sharedRuntime vai nē.


#### <a name="officeextensibilityvbatelemetrybreak"></a>Office.Extensibility.VbaTelemetryBreak

Notikums tiek ģenerēts, kad failam ar iespējotu makro rodas kompilēšanas vai izpildlaika kļūda

Datora analīze: to izmanto kā uzņēmuma darbspējas statusa izskaitļošanas skaitītāju tiem makro tipiem (piemēram, Word makro, Excel makro utt.), kas tiek izmantoti secinājumu veikšanai izmēģinājuma laikā, ja pievienojumprogramma ir gatava jaunināšanai ražošanas ciklā.

Tiek apkopoti tālāk norādītie lauki.

- **TagId** — telemetrijas atzīmes ID

- **BreakReason** — pārtraukuma iemesls (izpildlaiks, kompilēšana, cita kļūda)

- **SolutionType** — risinājuma tips (dokuments, veidne, pievienojumprogramma, COM pievienojumprogramma)

- **Data.ErrorCode** — VBA programmas norādītais kļūdas kods


#### <a name="officefindtimeappfailedtostart"></a>Office.FindTime.AppFailedToStart

Apkopo, ja programmu nevar palaist, jo startēšanas laikā radās neparedzēta kļūda. Izmantot, lai izsekotu izņēmumiem un avārijām.  Palīdz pārraudzīt un atkļūdot lietojumprogrammas darbspēju.

Tiek apkopoti tālāk norādītie lauki. 

- **DateTime** — notikuma reģistrēšanas laikspiedols.

- **EventName** — reģistrētā notikuma nosaukums.

#### <a name="officeoutlookdesktophangbucketmetrics"></a>Office.Outlook.Desktop.HangBucketMetrics

Apkopo Outlook reaģēšanas pārtraukuma laiku — unikāls identifikators katrā reaģēšanas pārtraukuma reizē, uzrāda pagājušo laiku un izsaukuma steka informāciju. Dati tiek izmantoti, lai noteiktu un identificētu programmas avārijas un novērstu problēmas turpmākajos atjauninājumos.

Tiek apkopoti tālāk norādītie lauki.

  - **BucketId** — izsaukuma steka jaukšana

  - **ElapsedTotal** — kopējais izsaukuma laiks

  - **ElapsedHanging** — izsaukumā pavadītais laiks bez reaģēšanas

#### <a name="officeoutlookdesktophangreportingscopeperfmetrics"></a>Office.Outlook.Desktop.HangReportingScopePerfMetrics

Apkopo laiku, kas nepieciešams Outlook pamata scenāriju izpildei — switchfolder, switchmodule, sendmailoutbox, openitemclassic, sendmailtransport. Dati tiek aktīvi pārraudzīti, lai noteiktu veiktspējas problēmas. Tie tiek izmantoti, lai noteiktu un diagnosticētu veiktspējas problēmas, kā arī uzlabotu veiktspēju katrā nākamajā atjauninājumā.

Tiek apkopoti tālāk norādītie lauki.

  - **ElapsedTotal** — kopējais šī izsaukuma laiks

  - **ScopeId** — tās funkcijas nosaukums, kas satur deklarāciju vai pielāgotu nosaukumu, kas piešķirts tvēruma definīcijas procesā

#### <a name="officeoutlookdesktopwatsonbuckets"></a>Office.Outlook.Desktop.WatsonBuckets

Šī kārtula apkopo informāciju par avāriju no notikumu žurnāliem, kad programma Outlook avarēja iepriekšējā sesijā.

Dati tiek aktīvi pārraudzīti, lai noteiktu anomālijas ar reaģēšanas pārstāšanu. Tie tiek izmantoti, lai noteiktu un identificētu situācijas, kad programma pārtrauc reaģēt, un novērstu problēmas turpmākajos atjauninājumos.

Tiek apkopoti tālāk norādītie lauki.

  - **BucketId** — izsaukuma steka jaukšana

  - **ElapsedTotal** — kopējais izsaukuma laiks

  - **ElapsedHanging** — izsaukumā pavadītais laiks bez reaģēšanas

#### <a name="officepowerpointsession"></a>Office.PowerPoint.Session

Apkopo informāciju par līdzekļu izmantošanu katrā PowerPoint sesijā. Šie dati tiek izmantoti, lai aprēķinātu PowerPoint neparedzētas aizvēršanas gadījumu proporciju, izmantojot līdzekli. PowerPoint neparedzētas aizvēršanas gadījumu proporcija ir būtisks signāls, lai nodrošinātu pareizu PowerPoint darbību.

Tiek apkopoti tālāk norādītie lauki.

  - **Flag** — sesijas karodziņi

  - **Usage** — līdzekļu lietojums

#### <a name="officepowerpointuaedialog"></a>Office.PowerPoint.UAE.Dialog

Tiek apkopots katru reizi, kad PowerPoint tika neparedzēti aizvērta, kad bija atvērts dialoglodziņš PowerPoint galvenā loga augšdaļā. Šī informācija ir kritiski svarīga, lai fiksētu PowerPoint neparedzētas aizvēršanas gadījumus, ko izraisa aktīvs dialoglodziņš, kas bloķē PowerPoint galveno logu. Microsoft izmanto šos datus, lai diagnosticētu problēmu un nodrošinātu, ka PowerPoint darbojas, kā paredzēts.

Tiek apkopoti tālāk norādītie lauki.

  - **DlgCnt** — kopējais atvērto dialoglodziņu skaits sesijas avārijas brīdī

  - **DlgId** — atvērto dialoglodziņu identifikators

  - **IdType** — atvērto dialoglodziņu identifikatora tips

  - **InitTime** — avarējušās sesijas inicializācijas laiks

  - **SessionID** — avarējušās sesijas identifikators

  - **TopId** — augšējā dialoglodziņa identifikators

  - **Version** — avarējušās sesijas versija

#### <a name="officepowerpointuaedocument"></a>Office.PowerPoint.UAE.Document

Apkopo, kāds līdzeklis tiek izmantots dokumentā, kad notiek neparedzēta PowerPoint aizvēršana. Šie līdzekļi ietver slaidrādi, dokumenta atvēršanu, saglabāšanu, rediģēšanu, koprediģēšanu, izslēgšanu. Šī informācija ir kritiski svarīga, lai fiksētu PowerPoint neparedzētas aizvēršanas gadījumus, izmantojot līdzekli. Microsoft izmanto šos datus, lai diagnosticētu problēmu un nodrošinātu, ka PowerPoint darbojas, kā paredzēts.

Tiek apkopoti tālāk norādītie lauki.

  - **CoauthFlag** — koprediģēšanas lietojuma karodziņi

  - **CommandFlag** — dokumenta modificēšanas karodziņi

  - **FileIOFlag** — failu ievadizvades lietojuma karodziņi

  - **InitTime** — avarējušās sesijas inicializācijas laiks

  - **Location** — dokumenta atrašanās vieta

  - **ServerDocId** — servera dokumenta identifikators

  - **SessionId** — avarējušās sesijas identifikators

  - **UrlHash** — dokumenta URL jaukšana

  - **Usage** — līdzekļu lietojums

  - **Version** — avarējušās sesijas versija

#### <a name="officepowerpointuaeopen"></a>Office.PowerPoint.UAE.Open

Apkopo katru reizi, kad PowerPoint tika neparedzēti aizvērta, atverot dokumentu. Šī informācija ir kritiski svarīga, lai fiksētu PowerPoint neparedzētas aizvēršanas gadījumus, atverot dokumentu. Microsoft izmanto šos datus, lai diagnosticētu problēmu un nodrošinātu, ka PowerPoint darbojas, kā paredzēts.

Tiek apkopoti tālāk norādītie lauki.

  - **FileUrlLocation** — dokumenta URL atrašanās vieta

  - **Flag** — atvēršanas karodziņi

  - **InitTime** — avarējušās sesijas inicializācijas laiks

  - **Location** — dokumenta atrašanās vieta

  - **OpenReason** — atvēršanas iemesls

  - **ServerDocId** — servera dokumenta identifikators

  - **SessionId** — avarējušās sesijas identifikators

  - **UrlHash** — dokumenta URL jaukšana

  - **Version** — avarējušās sesijas versija

#### <a name="officepowerpointuaesession"></a>Office.PowerPoint.UAE.Session

Apkopo, kāds līdzeklis tika izmantots, kad notika PowerPoint sesijas neparedzēta aizvēršana.Šī informācija ir kritiski svarīga, lai fiksētu PowerPoint neparedzētas aizvēršanas gadījumus, izmantojot līdzekli. Microsoft izmanto šos datus, lai diagnosticētu problēmu un nodrošinātu, ka PowerPoint darbojas, kā paredzēts.

Tiek apkopoti tālāk norādītie lauki.

  - **Flag** — sesijas karodziņi

  - **InitTime** — avarējušās sesijas inicializācijas laiks

  - **PreviousSessionId** — avarējušās sesijas identifikators

  - **Usage** — līdzekļu lietojums

  - **Version** — avarējušās sesijas versija

#### <a name="officepowerpointuaeshutdown"></a>Office.PowerPoint.UAE.Shutdown

Apkopo PowerPoint neparedzētu aizvēršanu izslēgšanas laikā. Šī informācija ir kritiski svarīga, lai fiksētu PowerPoint neparedzētas aizvēršanas gadījumus izslēgšanas laikā. Microsoft izmanto šos datus, lai diagnosticētu problēmu un nodrošinātu, ka PowerPoint darbojas, kā paredzēts.

Tiek apkopoti tālāk norādītie lauki.

  - **InitTime** — avarējušās sesijas inicializācijas laiks

  - **SessionId** — avarējušās sesijas identifikators

  - **Stage** — izslēgšanas posms

  - **Version** — avarējušās sesijas versija

#### <a name="officepowerpointuaeslideshow"></a>Office.PowerPoint.UAE.SlideShow

Apkopo PowerPoint neparedzētu aizvēršanu izslēgšanas laikā. Šī informācija ir kritiski svarīga, lai fiksētu PowerPoint neparedzētas aizvēršanas gadījumus izslēgšanas laikā. Microsoft izmanto šos datus, lai diagnosticētu problēmu un nodrošinātu, ka PowerPoint darbojas, kā paredzēts.

Tiek apkopoti tālāk norādītie lauki.

  - **InitTime** — avarējušās sesijas inicializācijas laiks

  - **Mode** — slaidrādes režīms

  - **SessionId** — avarējušās sesijas identifikators

  - **State** — slaidrādes stāvoklis

  - **Version** — avarējušās sesijas versija

#### <a name="officeprogrammabilitytelemetryaddincrash"></a>Office.Programmability.Telemetry.AddInCrash

Notikums, kas tiek ģenerēts, ja COM pievienojumprogramma tiek ielādēta. Šī informācija ir kritiski svarīga, lai noteiktu, vai pievienojumprogramma izraisīja Office programmas avāriju. To izmanto, lai novērtētu globālās pievienojumprogrammas saderību ar Office lietojumprogrammām.

Tiek apkopoti tālāk norādītie lauki.

  - **CLSID** — pievienojumprogrammas klases identifikators

  - **ConnectFlag** — pašreizējā pievienojumprogrammu ielādes darbība

  - **FileName** — pievienojumprogrammas faila nosaukums bez faila ceļa

  - **FriendlyName** — pievienojumprogrammas draudzīgais nosaukums

  - **Interface** — Office interfeiss, kurā radās izņēmums

  - **LoadAttempts** — pievienojumprogrammas ielādes mēģinājumu skaits

  - **Method** — Office metode, kurā radās izņēmums

  - **OfficeApplication** — Office lietojumprogramma, kurā radās izņēmums

  - **OfficeVersion** — Office versijas

  - **ProgID** — pievienojumprogrammas Prog identifikators

#### <a name="officeprogrammabilitytelemetrymacrofileopened"></a>Office.Programmability.Telemetry.MacroFileOpened 

Tiek izraisīts, atverot makro (VBA) saturošu failu ierīcē, kurā IT administrators ir iekļāvis Office lietojumprogrammas kā pakalpojumu (OAAS) un kurā ir aktivizēts Office 365 ProPlus ar Enterprise licenci. Notikums tiek izmantots, lai izprastu makro (VBA) saturošu failu darbspēju nomniekā, un tas tiek salīdzināts ar Office.Programmability.Telemetry.VbaTelemetryBreak, kas izseko kļūdas VBA saturošos failos. 

Netiek apkopoti nekādi lauki.

#### <a name="officesystemsystemhealthungracefulappexitmacandios"></a>Office.System.SystemHealthUngracefulAppExitMacAndiOS

Sāknēšanas notikums, kas tālākai izpētei uzskaita nelabvēlīgas iziešanas no lietojumprogrammas.

Tiek apkopoti tālāk norādītie lauki.

- **AffectedProcessAppBuild** — būvējuma numurs.

- **AffectedProcessAppBuildRevision** — būvējuma pārskatījuma numurs.

- **AffectedProcessAppMajorVer** — lietojumprogrammas galvenās versijas numurs.

- **AffectedProcessAppMinorVer** — lietojumprogrammas papildversijas numurs.

- **AffectedProcessAppName** — lietojumprogrammas nosaukums.

- **AffectedProcessResidentMemoryOnCrash** — avarējušās lietojumprogrammas iekšējā atmiņa.

- **AffectedProcessUnsymbolicatedChecksum** — tiek izmantots simbolizācijai kopā ar steka jaukšanu.

- **AffectedProcessVirtualMemoryOnCrash** — avarējušās lietojumprogrammas virtuālā atmiņa.

- **AffectedSessionDuration** — sesijas ilgums sekundēs pirms avārijas.

- **AffectedSessionLongBuildNumber** — garais būvējuma numurs.

- **CrashedProcessSessionID** — procesa sesijas ID lietojumprogrammas avārijā.

- **DetectionTime** — lietojumprogrammas avārijas datums/laiks.
    
- **DeviceModel** — aparatūras modelis.

- **MERPSessionID** — MERP sesijas ID.

- **ReportingOsLocaleTag** — OS lokalizācija.

- **ReportingOSVerStr** — OS versija.

- **SessionBuildNumber** — avarējušās lietojumprogrammas versija.

- **SessionIDSMatch** — Būla, lai pārliecinātos par to, ka atskaites sesijas ID ir tāds pats kā MERP fiksētais.

- **SessionVersion** — avarējušās lietojumprogrammas versija — **StackHash** — avarējušas lietojumprogrammas steka trasēšanas jaukšana.

- **UAEType** — uzskaitījums, kas sniedz mums informāciju par notikušās avārijas veidu.

#### <a name="officethisaddinstartupfailed"></a>Office.ThisAddIn.StartupFailed

Apkopo informāciju par izņēmumu, kas radās programmas Data Streamer startēšanas laikā. Šie dati tiek izmantoti, lai pārraudzītu programmas darbspēju. Šo notikumu ģenerē Microsoft Data Streamer Excel pievienojumprogrammai.

Tiek apkopoti tālāk norādītie lauki.

- **Exception** — izņēmuma izsaukuma steks

- **Event Name** — notikuma nosaukums ir notikuma kategorija un notikuma etiķete.

#### <a name="telemetry_error"></a>telemetry_error

Šis notikums ļauj mums noteikt un novērst problēmas, kas neļauj veikt nepieciešamo diagnostikas datu ģenerēšanu vai nosūtīšanu. Šie notikumi ļauj mums noteikt, vai mums pietrūkst kritiski svarīgi dati drošības problēmu vai būtisku lietojumprogrammas darbības problēmu noteikšanai. 

Tiek apkopoti šādi lauki: 

- **timer_name** — norāda, kur notiek telemetrijas problēma, piemēram, pastkastes komponentā vai kalendārā. Palīdz mums atklāt un novērst telemetrijas problēmas, kas notiek konkrētajā lietojumprogrammas daļā

- **type** — norāda taimera kļūdas tipu, lai palīdzētu mums noteikt, kad mūsu lietojumprogrammai ir problēmas ar diagnostikas telemetrijas datu sūtīšanu


#### <a name="watchdog_anr"></a>watchdog_anr

Nepieciešams lietojumprogrammas veiktspējas kļūdu uzraudzībai, lai novērstu gadījumus, kad lietojumprogramma pārtrauc reaģēt un jūsu ekrāns lietojumprogrammā sastingst (saīsina kā ANR - lietojumprogramma nereaģē)

Tiek apkopoti šādi lauki: 

- **callstack** — koda izsaukumsteks, kurā notika ANR
 
- **caused_restart** — norāda, vai ANR dēļ bija nepieciešama lietojumprogrammas restartēšana 
 
- **duration** — cik ilgi ierīce bija sastingusi
 
- **id** — unikāls ANR identifikators.
 
- **interval** — ANR nostrādāšanai konfigurētais slieksnis
 
- **is_application_object_initialized** — norāda, vai ANR notika pirms vai pēc pilnas lietojumprogrammas inicializācijas
 
- **last_known_is_in_foreground** — norāda, vai lietojumprogramma nesen atradās priekšplānā vai fonā


### <a name="application-feature-performance-subtype"></a>*Lietojumprogrammas līdzekļu izpildes apakštips*

Slikts atbildes laiks vai slikta veiktspēja tādos scenārijos kā programmas startēšana vai faila atvēršana.

#### <a name="android_frame_metrics"></a>android_frame_metrics

Ļauj mums noteikt un novērst situācijas, kad mūsu Android lietojumprogrammas komponenti izraisa veiktspējas problēmas, piemēram, ja jūsu iesūtnes ritināšana nenotiek vienmērīgi.

Tiek apkopoti šādi lauki: 

- **animation_duration** — animāciju renderēšanas ilgums milisekundēs

- **command_issue_duration** — komandu došanas platformai ilgums milisekundēs 

- **draw_duration** — UI zīmēšanas ilgums milisekundēs 

- **input_handling_duration** — ievades apstrādes ilgums milisekundēs 

- **layout_measure_duration** — izkārtojuma mērīšanas ilgums milisekundēs

- **origin** — mērāmais lietojumprogrammas komponents, piemēram, kalendārs vai pasts

- **sync_duration** — kadru sinhronizēšanas ilgums milisekundēs

- **swap_buffers_duration** — buferu maiņas ilgums milisekundēs

- **total_duration** — kopējais kadru renderēšanas laiks milisekundēs

- **unknown_delay** — nezināmu avotu izraisīta aizkave, izņemot precīzi izsekotos ilgumus

#### <a name="cal_component"></a>cal_component

Šis notikums ļauj mums noteikt un novērst problēmas, ja pastāv jūtama ietekme uz mūsu kalendāra UI komponentu veiktspēju, kas var izraisīt problēmas ar jūsu kalendāra ritināšanu.

Tiek apkopoti šādi lauki: 

- **account_counter** — izseko ar katru kalendāra tipu saistīto kontu skaitam, piemēram, 2 konti Gmail kalendāram, kā arī norāda, vai konts izmanto mūsu jauno sinhronizācijas pakalpojumu

- **component_name** — norāda kalendāra komponenta nosaukumu, piemēram, darba kārtības skats vai dienas skats, kas palīdz mums atklāt veiktspējas problēmas, kas ietekmē konkrētu kalendāra komponentu

- **display_frame_data** — izseko laikam, kas tika veltīts katru 60 kadru parādīšanai, lai noteiktu, vai pastāv veiktspējas problēmas. 

- **orientation** — norāda, vai ierīce ir portreta vai ainavas režīmā, lai palīdzētu mums atklāt veiktspējas problēmas, kas ietekmē konkrētu ierīces orientāciju

- **view_duration** — norāda laiku, kas bija nepieciešams, lai renderētu dažādus kalendāra UI komponentus, kas palīdz mums atklāt veiktspējas problēmas, kas ietekmē jūsu kalendāra izmantošanas pieredzi

#### <a name="conversation_load_time"></a>conversation_load_time

Šis notikums ļauj mums noteikt un novērst problēmas, kad ir jūtama veiktspējas ietekme uz e-pasta sarunu ielādi, lai nodrošinātu, ka e-pasta ziņojumi tiek ielādēti atbilstoši paredzētajam.

Tiek apkopoti šādi lauki: 

- **cid_type** — norāda, kāda tipa kontam pieder CID

- **time** — norāda laiku, kas bija nepieciešams e-pasta sarunas pilnai ielādei.

#### <a name="core_data_migration"></a>core_data_migration

Ļauj mums noteikt un novērst situācijas, kad jūsu ierīcē rodas kļūda, atjauninot e-pasta datus uz jaunāku versiju.

Tiek apkopoti šādi lauki:

- **db_size_megabytes** — izseko pamatdatu datubāzes izmēram, kas ir noapaļots līdz tuvākajiem 25 megabaitiem, ar maksimālo megabaitu 500

- **db_wal_size_megabytes** — izseko pamatdatu datubāzes izmēram, kad galvenās krātuves fails ir noapaļots līdz tuvākajam 1 megabaitam ar maksimālo megabaitu 10

- **free_space_megabytes** — izseko brīvo pieejamo vietu intervālos pa 10, 100, 1000, 10 000 un 100 000. 

- **migration_duration_seconds** — izseko migrācijas laikam, kas noapaļots līdz vienam no šiem laika periodiem - 0, 10, 20, 30, 40, 50, 60, 70, 80, 90, 100, 110, 120, 130, 140, 150, 160, 170, 180 (180 un vairāk tiks norādīts kā 180)

#### <a name="core_data_performance"></a>core_data_performance

Ļauj mums noteikt un novērst situācijas, kad e-pasta dati, kurus glabājam jūsu ierīcē, rada veiktspējas problēmas.

Tiek apkopoti šādi lauki:

- **Caller** — reģistrē elementa, kas izsauc saglabāšanas darbību, nosaukumu

- **db_size_megabytes** — izseko pamatdatu datubāzes izmēram, kas ir noapaļots līdz tuvākajiem 25 megabaitiem, ar maksimālo megabaitu 500

- **duration** — izseko laiku, kas ir nepieciešams darbības pabeigšanai

- **entity** — reģistrē elementa, kas izsauca ieneses darbību, nosaukumu

- **operation** — neapstrādāta darbības vērtība: saglabāt, ienest vai “lasīšanas/rakstīšansa rinda bloķēta”

#### <a name="inbox_component"></a>inbox_component

Šis notikums palīdz mums atklāt un novērst problēmas, ja pastāv redzama veiktspējas ietekme uz jūsu iesūtnes UI komponentiem, kas var traucēt atbilstošai e-pasta ziņojumu, avatāru, lasīts/nelasīts statusa ielādei vai parādīšanai.

Tiek apkopoti šādi lauki: 

- **above_40fps** — virs 40 kadriem sekundē renderēto kadru skaits

- **above_50fps** — virs 50 kadriem sekundē renderēto kadru skaits

- **above_55fps** — virs 55 kadriem sekundē renderēto kadru skaits

- **account_counter** — katra ierīcē esošā konta tipa uzskaitījums, piemēram Office 365 konti = 1 konts, Outlook.com konti = 1 konts.

- **ad_not_shown_reason** — iemesls, kāpēc reklāmas netiek parādītas

- **ad_shown** — norāda, vai reklāma tika parādīta (ja reklāma ir iespējota)

- **age** — cilvēka vecums (lai apstiprinātu atbilstību reklāmas vecuma ierobežojumam)

- **component_name** — tā komponenta/skata nosaukums, kas ir aktīvs filtrēšanas laikā

- **has_hx** — norāda, vai ierīcei ir vismaz viens Hx (mūsu jaunais e-pasta sinhronizēšanas pakalpojums) konts

- **has_subscription** — norāda, vai ierīcei ir reklāmas abonements

- **is_all_accounts_inbox** — norāda, vai pašreizējai iesūtnei ir mape “visi konti”

- **is_current_account** — norāda, vai pašreiz aktīvais konts ir reklāmas konts

- **load_error_code** — reklāmas ielādes kļūdas kods

- **network_error_code** — tīkla kļūdas kods, pieprasot reklāmas

- **orientation** — ekrāna orientācija (portrets vai ainava) notikuma laikā

- **sub_error_type** — detalizēts kļūdas tips

- **total_count** — kopējais komponenta attēloto kadru skaits

- **view_duration** — kopējais laiks, ko komponenta skatīšanai veltīja lietotājs

#### <a name="initial_page_landing"></a>Initial_page_landing 
 
Šis pasākums palīdz izsekot, kāda veida pieredze lietotājiem tiek rādīta, kad tie nonāk mūsu programmas lapā.  Šie dati tiek izmantoti, lai noteiktu lietotāju plūsmu katrā programmas lietošanas pieredzē, kā arī palīdz mums viegli konsolidēt eksperimentu rezultātus.
 
Tiek apkopoti šādi lauki: 

- **Lapa** — tā tiek lietota, lai izsekotu, kāda veida pieredzi lietotājs pirmo reizi redz, kad nonāk lapā. Iespējamās vērtības ir "Izmēģinājumversija", "Izlaist", "Salikts", "Abonements" utt.

- **storeExperience** — var izmantot, lai noteiktu, vai lietotājs ir tiesīgs skatīt veikala SDK pieredzi.

- **stringVariant** — var izmantot, lai noteiktu, kāda veida virknes lietotājs redz, kad nonāk lapā. Ņemiet vērā, ka jebkurai lapai, piemēram, "Izmēģinājumversija", lietotājs var būt tiesīgs skatīt dažādas virknes atkarībā no tā, vai viņiem ir instalēta mantota sistēma Office vai ja lietotājs iepriekš aktivizēja sistēmu Office. Iespējamie šī rekvizīta uzskaitījumi ir "LegacyUpsell", "OfficeOpened", "Noklusējums", "YesIntent", "NoIntent" utt.

- **windowsBuildType** — var izmantot, lai izsekotu WindowsBuildType, ko lietotājs ir ieplānojis. t.i., "RS4", "RS5", "RS19H1", "Vibranium" u.c. Tā kā mūsu pieredze parasti ir vērsta uz dažādiem WindowsBuildTypes, šis rekvizīts ir svarīgs, lai atšķirtu ieviešanu. 

#### <a name="ipcpbootstrapuser"></a>IpcpBootstrapUser

Tiek apkopots, kad lietotājs mēģina atvērt ar IRM aizsargātu dokumentu vai lietot IRM aizsardzību. Tas satur informāciju, kas ir nepieciešama pareizai tādu problēmu izmeklēšanai un diagnosticēšanai, kas notiek IpcpBootstrapUser API izsaukuma laikā.

Tiek apkopoti tālāk norādītie lauki.

- **AppInfo.ClientHierarchy** — klienta hierarhija, kas norāda, ka lietojumprogramma darbojas ražošanas vidē vai izstrādātāja vidē

- **AppInfo.Name** — lietojumprogrammas nosaukums

- **AppInfo.Version** — lietojumprogrammas versija

- **iKey** — pieteikšanās pakalpojuma servera ID

- **RMS.ApplicationScenarioId** — scenārija ID, ko nodrošina lietojumprogramma

- **RMS.AuthCallbackProvided** — norāda, vai autentificēšanas atzvanīšana tiek nodrošināta kā API izsaukuma ievade

- **RMS.ConnectionInfo.ExtranetUrl** — ārtīkla savienojuma informācijas vietrādis URL

- **RMS.ConnectionInfo.IntranetUrl** — iekštīkla savienojuma informācijas vietrādis URL

- **RMS.ConnectionMode** — savienojuma režīms starp tiesību pārvaldības pakalpojuma klientu un serveri: tiešsaistē vai bezsaistē

- **RMS.Duration** — kopējais laiks API izsaukuma veikšanai

- **RMS.DurationWithoutExternalOps** — kopējais patērētais laiks mīnus ārējās operācijas, piemēram, tīkla latentums.

- **RMS.ErrorCode** — atgrieztais kļūdas kods, ja tāds ir, no API izsaukuma

- **RMS.GuestTenant** — lietotāja viesa nomnieka ID

- **RMS.HomeTenant** — lietotāja vietējā nomnieka ID

- **RMS.HttpCall** — norāda, vai ir HTTP operācija

- **RMS.Identity.ExtranetUrl** — lietotāja tiesību pārvaldības pakalpojuma servera ārtīkla URL, kas tiek apkopots, iegūstot jaunu tiesību konta sertifikātu no servera

- **RMS.Identity.IntranetUrl** — lietotāja tiesību pārvaldības pakalpojuma servera iekštīkla URL, kas tiek apkopots, iegūstot jaunu tiesību konta sertifikātu no servera

- **RMS.Identity.Status** — pirmā reize, lai iegūtu tiesību konta sertifikātu no servera vai atjaunotu tiesību konta sertifikātu 

- **RMS.Identity.Type** — lietotāja konta tips, piemēram, Windows konts vai Live konts

- **RMS.Identity.UserProvided** — norāda, vai lietotāja e-pasta adrese ir nodrošināta, kad saņemat jaunu tiesību konta sertifikātu no servera

- **RMS.IssuerId** — tiesību pārvaldības pakalpojuma servera ID, kas izsniedz tiesību konta sertifikātu  

- **RMS.LicenseFormat** — licences formāts: XrML vai JSON

- **RMS.RACType** — tiesību konta sertifikāta tips

- **RMS.Result** — API izsaukums sekmīgs vai neizdevās

- **RMS.ScenarioId** — scenārija ID, ko definē API

- **RMS.SDKVersion** — tiesību pārvaldības pakalpojuma klienta versija

- **RMS.ServerType** — tiesību pārvaldības pakalpojuma servera tips 

- **RMS.StatusCode** — atgrieztā rezultāta statusa kods

- **RMS.TemplatesCount** — veidņu skaits

- **RMS.TokenProvided** — norāda, vai ir nodrošināts marķieris kā API izsaukuma ievade 

- **RMS.UserProvided** — norāda, vai ir nodrošināts klients kā API izsaukuma ievade 

- **UserInfo.UserObjectId** — lietotāja objekta ID

#### <a name="ipcpgetkey"></a>IpcpGetKey

Tiek apkopots, kad lietotājs mēģina atvērt ar informācijas piekļuves tiesību pārvaldības (IRM) aizsargātu dokumentu vai lietot IRM aizsardzību. Tas satur informāciju, kas ir nepieciešama pareizai tādu problēmu izmeklēšanai un diagnosticēšanai, kas notiek IpcpGetKey API izsaukuma laikā.

Tiek apkopoti šādi lauki:

- **AppInfo.ClientHierarchy** — klienta hierarhija, kas norāda, ka lietojumprogramma darbojas ražošanas vidē vai izstrādātāja vidē

- **AppInfo.Name** — lietojumprogrammas nosaukums

- **AppInfo.Version** — lietojumprogrammas versija

- **iKey** — pieteikšanās pakalpojuma servera ID

- **RMS.ApplicationScenarioId** — scenārija ID, ko nodrošina lietojumprogramma

- **RMS.AuthCallbackProvided** — norāda, vai autentificēšanas atzvanīšana tiek nodrošināta kā API izsaukuma ievade

- **RMS.ConnectionMode** — savienojuma režīms starp tiesību pārvaldības pakalpojuma klientu un serveri: tiešsaistē vai bezsaistē

- **RMS.ContentId** — dokumenta satura ID

- **RMS.Duration** — kopējais laiks API izsaukuma veikšanai

- **RMS.DurationWithoutExternalOps** — kopējais patērētais laiks mīnus ārējās operācijas, piemēram, tīkla latentums.

- **RMS.ErrorCode** — atgrieztais kļūdas kods, ja tāds ir, no API izsaukuma

- **RMS. EulId** — gala lietotāja licences ID

- **RMS.EulProvided** — norāda, vai gala lietotāja licence tiek nodrošināta kā API izsaukuma ievade

- **RMS.GuestTenant** — lietotāja viesa nomnieka ID 

- **RMS.HomeTenant** — lietotāja vietējā nomnieka ID

- **RMS.HttpCall** — norāda, vai pastāv HTTP operācija

- **RMS.Identity.ExtranetUrl** — lietotāja tiesību pārvaldības pakalpojuma servera ārtīkla URL, kas tiek apkopots, iegūstot jaunu tiesību konta sertifikātu no servera

- **RMS.Identity.IntranetUrl** — lietotāja tiesību pārvaldības pakalpojuma servera iekštīkla URL, kas tiek apkopots, iegūstot jaunu tiesību konta sertifikātu no servera

- **RMS.Identity.Status** — pirmā reize, lai iegūtu tiesību konta sertifikātu no servera vai atjaunotu tiesību konta sertifikātu 

- **RMS.Identity.Type** — lietotāja konta tips, piemēram, Windows konts vai Live konts

- **RMS.Identity.UserProvided** — norāda, vai lietotāja e-pasta adrese ir nodrošināta, kad saņemat jaunu tiesību konta sertifikātu no servera

- **RMS.IssuerId** — tiesību pārvaldības pakalpojuma servera ID, kas izsniedz tiesību konta sertifikātu 

- **RMS.KeyHandle** — atslēgas tura atmiņas adrese

- **RMS.LicenseFormat** — licences formāts: XrML vai JSON

- **RMS.PL.ExtranetUrl** — publicēšanas licences ārtīkla vietrādis URL

- **RMS.PL.IntranetUrl** — publicēšanas licences iekštīkla vietrādis URL

- **RMS.PL.KeyType** — norāda, vai PL bija aizsargāts ar vienkāršas atslēgas vai divkāršas atslēgas aizsardzību.

- **RMS.RACType** — tiesību konta sertifikāta tips

- **RMS.Result** — API izsaukums sekmīgs vai neizdevās

- **RMS.ScenarioId** — scenārija ID, ko definē API

- **RMS.SDKVersion** — tiesību pārvaldības pakalpojuma klienta versija

- **RMS.ServerType** — tiesību pārvaldības pakalpojuma servera tips

- **RMS.StatusCode** — atgrieztā rezultāta statusa kods

- **RMS.TemplatesCount** — veidņu skaits

- **RMS.TokenProvided** — norāda, vai ir nodrošināts marķieris kā API izsaukuma ievade 

- **RMS.UserProvided** — norāda, vai ir nodrošināts klients kā API izsaukuma ievade 

- **UserInfo.UserObjectId** — lietotāja objekta ID

#### <a name="json_parse_error"></a>json_parse_error 
 
Šis notikums norāda, ka JSON parsētājs rāda kļūdu.  Mēs nevarēsim atkļūdot to, kas tiek nosūtīts uz JSON parsētāju, lai nodrošinātu mūsu lietotājiem vienmērīgu lietošanu.
 
Tiek apkopoti šādi lauki: 

- **Kļūda** — tiek parādīts kļūdas ziņojums par to, ka kļūdu objekts atgriežas.

#### <a name="mail_filter_component"></a>mail_filter_component

Šis notikums ļauj mums noteikt un novērst problēmas, ja pastāv redzama ietekme uz jūsu e-pasta filtrēšanu, kuras rezultātā jūsu filtri netiks ielādēti vai parādīti pareizi.

Tiek apkopoti šādi lauki: 

- **above_40fps** — virs 40 kadriem sekundē renderēto kadru skaits
 
- **above_50fps** — virs 50 kadriem sekundē renderēto kadru skaits
 
- **above_55fps** — virs 55 kadriem sekundē renderēto kadru skaits
 
- **account_counter** — katra ierīcē esošā konta tipa uzskaitījums, piemēram Office 365 konti = 1 konts, Outlook.com konti = 1 konts.
 
- **ad_not_shown_reason** — iemesls, kāpēc reklāmas netiek parādītas
 
- **ad_shown** — norāda, vai reklāma tika parādīta (ja reklāma ir iespējota)
 
- **age** — cilvēka vecums (lai apstiprinātu atbilstību reklāmas vecuma ierobežojumam)
 
- **component_name** — tā komponenta/skata nosaukums, kas ir aktīvs filtrēšanas laikā
 
- **folder_type** — norāda filtrējamās mapes tipu (piemēram, iesūtne, atkritne vai NonSystem)
 
- **has_hx** — norāda, vai ierīcei ir vismaz viens Hx (jaunais e-pasta sinhronizēšanas pakalpojums) konts
 
- **has_subscription** — norāda, vai ierīcei ir reklāmas abonements
 
- **is_all_accounts_inbox** — norāda, vai pašreizējai iesūtnei ir mape “visi konti”
 
- **is_current_account** — norāda, vai pašreiz aktīvais konts ir reklāmas konts
 
- **load_error_code** — reklāmas ielādes kļūdas kods
 
- **network_error_code** — tīkla kļūdas kods, pieprasot reklāmas
 
- **orientation** — ekrāna orientācija (portrets vai ainava) notikuma laikā
 
- **sub_error_type** — detalizēts kļūdas tips
 
- **total_count** — kopējais komponenta attēloto kadru skaits
 
- **view_duration** — kopējais laiks, ko komponenta skatīšanai veltīja lietotājs

#### <a name="officeandroidandroidofficelaunchtolandingpagelatency"></a>Office.Android.AndroidOfficeLaunchToLandingPageLatency

Ir būtiski svarīgs, lai fiksētu lietojumprogrammas veiktspējas rādītāju attiecībā uz lietojumprogrammas atbildes laiku no sāknēšanas.  Microsoft to izmanto, lai apkopotu laiku, kas ir nepieciešams lietojumprogrammai, lai atbildētu, kā arī, lai noteiktu scenārijus, kas varat ietekmēt sāknēšanas laiku Word, Excel vai PowerPoint lietojumprogrammās.

Tiek apkopoti šādi lauki:
 
- **AnyCrashInteractionDuringBoot** — būla jebkurai avārijai, kas rodas sāknēšanas laikā

- **AppActivationTimeInMs** — lietojumprogrammas fāzes laiks

- **AppSuspendedDuringBoot** — būla lietojumprogrammas atlikšanai sāknēšanas laikā

- **AvailableMemoryInMB** — pieejamā atmiņa

- **CollectionTime** — notikuma laiks

- **DalvikHeapLimitInMB** — kaudzes informācija

- **DocumentRecoveryInvoked** — būla, kas norāda, vai dokuments ir atgūts

- **ExtractionDone** — vietējās bibliotēkas izvilkšanas laiks

- **FastBootGainTimeInMs** — ātrās sāknēšanas pabeigšanas laiks

- **FileActivationAttempted** — būla, kas norāda, vai lietojumprogramma tika palaista faila aktivācijas dēļ

- **HasLogcatLoggingImpactOnBoot** — būla, kas norāda, vai logcat rīks ietekmēja sāknēšanas laiku

- **IsThisFirstLaunch** — būla, kas norāda, vai tā ir pirmā lietojumprogrammas sāknēšanas reize

- **LatencyTimeInMilliSec** — latentums milisekundēs

- **LibrarySharingTimeInMs** — bibliotēku koplietošanas laiks

- **LoadMinLibsTimeInMs** — minimālās bibliotēku kopas ielādes laiks

- **MruListingTimeInMs** — MRU ielādes laiks

- **NativeLibrariesLoadTime** — CPP bibliotēkas ielādes laiks

- **NumberOfRunningProcesses** — darbībā esošu procesu skaits

- **NumberOfRunningProcesses** — darbībā esošu procesu skaits

- **NumberOfRunningServices** — darbībā esošo pakalpojumu skaits

- **OfficeActivityTimeInMs** — OfficeActivity inicializācijas laiks

- **PostAppInitTimeInMs**— lietojumprogrammas fāzes laiks

- **PreAppInitializationTime** — lietojumprogrammas fāzes inicializācijas laiks

- **PreAppInitTimeInMs** — lietojumprogrammas fāzes laiks

- **TotalMemoryInMB** — kopējā atmiņa

- **UIRaaSDownloadLanguagePackageBoot** — ar valodas pakotnes lejupielādi saistītā informācija

- **UserDialogInterruptionDuringBoot** — būla jebkuram bloķēšanas dialogam, kas tika parādīts sāknēšanas laikā


#### <a name="office_apple_apple_appboot_mac"></a>Office_Apple_Apple_AppBoot_Mac

Šo notikumu apkopo Office programmām, kas tiek lietotas Apple platformās. Pasākums tiek izmantots, lai apkopotu laiku, kas nepieciešams, lai sāknētu programmu, kā arī sniegtu detalizētu informāciju par to, kāda veida sāknēšana ir pabeigta. Šis notikums palīdz mums uzraudzīt mūsu sniegumu un nodrošināt veiktspējas uzlabojumus.

Tiek apkopoti šādi lauki:

- **Data_ Data_EvtBootTimerDocStageReady** — pagājušais laiks, līdz tiek sasniegts konkrēts punkts kodā.

- **Data_DocumentRecoveryInvoked** — vai sāknēšanas laikā tika izsaukta dokumentu atkopšana.

- **Data_EvtBootTimerBootIdle** — pagājušais laiks, līdz tiek sasniegts konkrēts punkts kodā.

- **Data_EvtBootTimerFinishLaunchEnd** — pagājušais laiks, līdz tiek sasniegts konkrēts punkts kodā.

- **Data_EvtBootTimerLaunchDidFinish** — pagājušais laiks, līdz tiek sasniegts konkrēts punkts kodā.

- **Data_EvtBootTimerLaunchStart** — pagājušais laiks, līdz tiek sasniegts konkrēts punkts kodā.

- **Data_EvtBootTimerMainStart** — pagājušais laiks, līdz tiek sasniegts konkrēts punkts kodā.

- **Data_EvtBootTimerMainStart** — pagājušais laiks, līdz tiek sasniegts konkrēts punkts kodā.

- **Data_EvtDockStageReady** — pagājušais laiks, līdz tiek sasniegts konkrēts punkts kodā.

- **Data_IsFileOpenAttempted** — vai ir mēģināts atvērt failu, veicot sāknēšanu.

- **Data_IsFirstRunAttempted** — vai programmas sāknēšana izzuda, izmantojot pirmo palaišanu.

- **Data_SentToBackground** — vai programma tika nosūtīta uz fonu sāknēšanas laikā.

#### <a name="office_apple_diskruleresultserializererroronstreamop"></a>Office_Apple_DiskRuleResultSerializerErrorOnStreamOp

Šo notikumu apkopo Office programmām, kas tiek lietotas Apple platformās. Pasākums tiek lietots, lai pārraudzītu mūsu telemetrijas infrastruktūras darbspēju. Šis notikums norāda, ka radās kļūda.

Tiek apkopoti šādi lauki:

- **Data_ActualBytesModified** — modificēto baitu skaits.

- **Data_BytesRequested** — baitu skaits, kas tiek apstrādāti.

- **Data_IsWriteOp** — vai mēs tūlīt veiksim ierakstīšanas darbību

#### <a name="office_apple_macbootresourceusage"></a>Office_Apple_MacBootResourceUsage

Šo notikumu apkopo Office programmām, kas tiek lietotas Apple platformās. Šo notikumu apkopo Office programmām, kas tiek lietotas Apple platformās. Pasākums tiek izmantots, lai apkopotu vairākus indikatorus ap resursiem, kas tiek patērēti sāknēšanas laikā, izmantojot Office programmas. Šis notikums palīdz mums uzraudzīt mūsu sniegumu un nodrošināt veiktspējas uzlabojumus.

Tiek apkopoti šādi lauki:

- **Data_BlockInputOperations** — bloka ievades darbību skaits

- **Data_BlockInputOperations** — bloka izvades darbību skaits

- **Data_InvoluntaryContextSwitches** — piespiedu konteksta pārslēgšanās skaits

- **Data_MainThreadCPUTime** — pagājušā laika mērījums

- **Data_MaxResidentSize** — atmiņas lieluma mērījums

- **Data_MessagesReceived** — saņemto ziņojumu skaits

- **Data_MessagesSent** — nosūtīto ziņojumu skaits

- **Data_PageFaults** — lapas atkārtotā pieprasīšana

- **Data_PageReclaims** — lapas atkārtotā pieprasīšana

- **Data_ProcessCPUTime** — pagājušā laika mērījums

- **Data_SharedTextMemorySize** — atmiņas lieluma mērījums

- **Data_SignalsReceived** — saņemto signālu skaits

- **Data_Swaps** — datu apmaiņas reižu skaits

- **Data_SystemCPUTime** — pagājušā laika mērījums

- **Data_SystemUpTime** — pagājušā laika mērījums

- **Data_UnsharedDataSize** — datu lieluma mērījums

- **Data_UnsharedStackSize** — steka lieluma mērījums

- **Data_UserCPUTime** — pagājušā laika mērījums

- **Data_VoluntaryContextSwitchesNvcsw** — piespiedu konteksta pārslēgšanās skaits

#### <a name="office_apple_mau_validation"></a>Office_Apple_MAU_Validation

Šo notikumu apkopo Office programmām, kas tiek lietotas Apple platformās. Pasākums tiek lietots, lai pārraudzītu Microsoft AutoUpdate komponenta darbspēju, kas tiek lietots, lai izplatītu un instalētu programmu atjauninājumus. Apkopotie dati tiek izmantoti kļūdu noteikšanai un neveiksmes cēloņu novēršanai.

Tiek apkopoti šādi lauki:

- **Data_EventID** — mēs apkopojam virkni, kas norāda kļūdas kodu

- **Data_Message** — mēs apkopojam virkni, kurā ir kļūdas apraksts.

#### <a name="office_apple_mbuinstrument_hang_detection_spin_control"></a>Office_Apple_MbuInstrument_Hang_Detection_Spin_Control

Šo notikumu apkopo Office programmām, kas tiek lietotas Apple platformās. Notikums tiek reģistrēts, kad programma izskatās nereaģējoša. Šis notikums palīdz mums uzraudzīt mūsu sniegumu un nodrošināt veiktspējas uzlabojumus.

Tiek apkopoti šādi lauki:

- **Data_CountSpinControlStart** — marķieris, kas norāda, ka programma izskatās nereaģējoša (vai reaģē lēni)

#### <a name="office_apple_mbuinstrument_vmondocumentclose"></a>Office_Apple_MbuInstrument_VMOnDocumentClose

Šo notikumu apkopo Office programmām, kas tiek lietotas Apple platformās. Pasākums tiek lietots, lai apkopotu atmiņas stāvokļa momentuzņēmumu dokumentu aizvēršanas laikā. Šis notikums palīdz mums uzraudzīt mūsu sniegumu un nodrošināt veiktspējas uzlabojumus.

Tiek apkopoti šādi lauki:

- **Data_CollectionTime** — laikspiedols no datu vākšanas brīža

- **Data_ResidentMemory** — novērotā rezidenta atmiņas apjoma vērtība

- **Data_VirtualMemory** — novērotā virtuālā atmiņa

#### <a name="office_apple_mbuinstrument_vmonshutdown"></a>Office_Apple_MbuInstrument_VMOnShutdown

Šo notikumu apkopo Office programmām, kas tiek lietotas Apple platformās. Pasākums tiek lietots, lai apkopotu atmiņas stāvokļa momentuzņēmumu dokumentu aizvēršanas laikā. Šis notikums palīdz mums uzraudzīt mūsu sniegumu un nodrošināt veiktspējas uzlabojumus.

Tiek apkopoti šādi lauki:

- **Data_CollectionTime** — laikspiedols no datu vākšanas brīža

- **Data_ResidentMemory** — novērotā rezidenta atmiņas apjoma vērtība

- **Data_VirtualMemory** — novērotā virtuālā atmiņa

#### <a name="office_apple_mbuinstrument_vmonstart"></a>Office_Apple_MbuInstrument_VMOnStart

Šo notikumu apkopo Office programmām, kas tiek lietotas Apple platformās. Pasākums tiek lietots, lai apkopotu atmiņas stāvokļa momentuzņēmumu dokumentu atvēršanas laikā. Šis notikums palīdz mums uzraudzīt mūsu sniegumu un nodrošināt veiktspējas uzlabojumus.

Tiek apkopoti šādi lauki:

- **Data_CollectionTime** — laikspiedols no datu vākšanas brīža

- **Data_ResidentMemory** — novērotā rezidenta atmiņas apjoma vērtība

- **Data_VirtualMemory** — novērotā virtuālā atmiņa

#### <a name="office_apple_msoappdelegate_bootperf"></a>Office_Apple_MsoAppDelegate_BootPerf

Šo notikumu apkopo Office programmām, kas tiek lietotas Apple platformās. Pasākums tiek izmantots, lai apkopotu laiku un patērēto atmiņu, izmantojot Office programmas, kā arī detalizētu informāciju par to, kāda veida sāknēšana ir pabeigta. Šis notikums palīdz mums uzraudzīt mūsu sniegumu un nodrošināt veiktspējas uzlabojumus.

Tiek apkopoti šādi lauki:

- **Data_AppLaunchDurationMicroSec** — sāknēšanas procesa ilgums

- **Data_AppLaunchFinishSystemTime** — laikspiedols konkrētajā sāknēšanas koda marķierī

- **Data_AppLaunchStartSystemTime** — laikspiedols konkrētajā sāknēšanas koda marķierī

- **Data_ResidentMemory** — pieejamās rezidenta atmiņas momentuzņēmums sāknēšanas laikā

- **Data_VirtualMemory** — pieejamās virtuālās atmiņas momentuzņēmums sāknēšanas laikā

#### <a name="office_apple_ungracefulappexithangsinprevioussession"></a>Office_Apple_UngracefulAppExitHangsInPreviousSession

Šo notikumu apkopo Office programmām, kas tiek lietotas Apple platformās. Pasākums tiek lietots, lai pārraudzītu mūsu Office programmu darbspēju, kā arī noteiktu kļūmju iemeslus. Mēs apkopojam, cik reizes programma izrādījās nereaģējoša pirms iziešanas no programmas ar aizķeršanos.

Tiek apkopoti šādi lauki:

- **Data_HangsDetected** — cik reizes programma izrādījās nereaģējoša pirms iziešanas no programmas ar aizķeršanos.

- **Data_LastSessionId** — tās sesijas identifikators, kurā tika novērota iziešana no programmas ar aizķeršanos.

- **Data_SessionBuildNumber** — tās programmas sekundārā versija, kurā tika novērota iziešana no programmas ar aizķeršanos.

- **Data_SessionVersion** — programmas galvenā versija, kurā tika novērota iziešana no programmas ar aizķeršanos.

#### <a name="office_apple_whatsnewerrorandwarning"></a>Office_Apple_WhatsNewErrorAndWarning

Šo notikumu vāc Office programmām, kas darbojas Apple platformās. Pasākums tiek lietots, lai pārraudzītu, kas ir jaunā līdzekļa darbspēju. Šis notikums norāda, ka, parsējot jaunumu saturu, radās kļūda/brīdinājums, norādot uz potenciālām satura autorēšanas problēmām.

Tiek apkopoti šādi lauki:

- **Data_ContentKey** — rādītājs uz satura sadaļu, kas visticamāk izraisīja kļūdu.

- **Data_ErrorCode** — novērotais kļūdas kods (ja pieejams)

- **Data_ErrorDescription** — kļūdas apraksts (ja pieejams)

- **Data_EventID** — mēs apkopojam virkni, kas norāda novērotās kļūdas tipu.

- **Data_IncludesHTMLTag** — vai saturā ir bagātināts html

- **Data_IncludesItemsTag** — vai saturā ir vienumu hierarhija

- **Data_LengthOfRawData** — satura lielums

- **Data_RequestURL** — vietrādis URL, no kura saturs tika lejupielādēts

- **Data_ServerLanguageTag** — valoda, kurā bija saturs.

- **Data_StatusCode** — kļūdas statuss (ja pieejams)

#### <a name="officeextensibilityrichapimethodinvocation"></a>Office.Extensibility.RichApiMethodInvocation

Šis notikums aktivizējas, kad klients izmanto Office pievienojumprogrammu un sazinās ar Rich API pakalpojuma sniegšanai. Izmanto, lai izmērītu pakalpojuma uzticamību, veiktspēju un lietojumu Rich API metodes izsaukšanai.
 
Tiek apkopoti tālāk norādītie lauki.

- **API** — pilns API nosaukums.

- **DispFlag** — bitu karodziņš, kas apraksta metodes izsaukuma tipu (piem., 0x1 = METHOD, 0x2 = PROPERTYGET, 0x4 = PROPERTYPUT, 0x8 = PROPERTYPUTREF).

- **DispId** — izsauktās metodes izsūtīšanas identifikators.

- **HResult** — metodes izsaukšanas HResult.

- **Latency** — izsaukuma latentums mikrosekundēs.

- **ReqId** — pakešu pieprasījuma GUID, pie kura pieder šī metode.

- **TypeId** — interfeisa GUID, uz kura šī metode tiek izsaukta.


#### <a name="officemanageabilityserviceapplypolicy"></a>Office.Manageability.Service.ApplyPolicy

Kritiski svarīgi telemetrijas dati, lai izsekotu kļūmi\\Sekmīgi lietoti mākoņa politikas iestatījumi reģistrā. LastError norāda, kāpēc un kur neizdevās politikas lietošana reģistrā.

Tiek apkopoti tālāk norādītie lauki.

  - **Data.ApplyLogMsg** — izņēmuma ziņojums politikas lietošanas laikā

  - **Data.Cid** — dinamiski ģenerēts korelācijas identifikators, kas nosūtīts uz pakalpojumu, kad tika veikts pakalpojuma izsaukums, lai ienestu mākoņa politiku. Tiek izmantots, lai korelētu, kurš izsaukums izraisīja problēmu, lietojot politikas mākonī.

  - **Data.Last Error** — viena no piecām virknes vērtībām (skaitītājiem), kas reģistrē, kurš politikas lietojums posms tika izpildīts, kad radās izņēmums 

#### <a name="officeoutlookdesktopbootperfmetrics"></a>Office.Outlook.Desktop.BootPerfMetrics

Apkopo Outlook palaišanas laiku. Outlook startēšanas laiks tiek aktīvi pārraudzīts, lai noteiktu un diagnosticētu regresiju. Tas tiek izmantots arī, lai diagnosticētu klienta eskalācijas, kā arī uzlabotu startēšanas izpildi laika gaitā.

Tiek apkopoti tālāk norādītie lauki.

  - **AddinElapsedTotal** — kopējais laiks, lai ielādētu pievienojumprogrammas

  - **CredPromptCount** — parādīto akreditācijas datu uzvedņu skaits

  - **ElapsedTotal** — kopējais startēšanas laiks

  - **IsLoggingEnabled** — vai ir iespējota reģistrēšana

  - **ShowChooseProfileDlg** — vai bija redzams dialoglodziņš Profila izvēle

  - **ShowFirstRunDlg** — vai Outlook tiek palaista pirmo reizi

  - **ShowIMAPSrchfldWarningDlg** — brīdinājumi, ja ir IMAP konts ar ANSI PST

  - **ShowNeedSupportDlg** — startēšanas kļūme aktivizēja atbalsta dialoglodziņu

  - **ShowSafeModeDlg** — vai sesija ir atvērta drošajā režīmā

  - **ShowScanPstDlg** — krātuves labošanas pārbaude parādīja kļūdas ziņojumu


#### <a name="officeoutlookmacbootperf"></a>Office.Outlook.Mac.BootPerf

Apkopo Outlook palaišanas laiku. Outlook startēšanas laiks tiek aktīvi pārraudzīts, lai noteiktu un diagnosticētu regresiju. Tas tiek izmantots arī, lai diagnosticētu klienta eskalācijas, kā arī uzlabotu startēšanas izpildi laika gaitā.

Tiek apkopoti tālāk norādītie lauki.

- **MacOLKBootPerfDuration** — kopējais sāknēšanas laiks.

- **MacOLKBootPerfID** — sāknēšanas laika identifikators.


#### <a name="officeoutlookmacperformanceunresponsive"></a>Office.Outlook.Mac.PerformanceUnresponsive

Izmanto, lai identificētu problēmas Outlook, kas ietekmē lietotāju un var izpausties kā pasliktināta veiktspēja. 

Tiek apkopoti tālāk norādītie lauki.

- **Duration** — pasliktinātās veiktspējas ilgums.

- **EventType** — notikuma ar pasliktināto veiktspēju veids.


#### <a name="officeperformanceboot"></a>Office.Performance.Boot

Tiek apkopots, palaižot Office programmu. Ietver informāciju par to, vai palaišana tika sākta, atverot failu vai palaižot no sākuma izvēlnes, vai tā bija pirmā programmas palaišana, cik daudz atmiņas programma izmanto un vai lietotājam tika rādīts bloķēšanas UI. Tiek izmantots, lai noteiktu, cik ātri Office programmas tiek palaistas un cik daudz atmiņas tās izmanto, kad tiek startētas, lai nodrošinātu pieņemamu lietotāja pieredzi.

Tiek apkopoti šādi lauki:

  - **ActivationKind** — vai programma tika startēta, palaižot no sākuma izvēlnes, atverot failu vai izmantojot OLE automatizāciju.
  
  - **BootToStart** — vai lietotājs ir izvēlējies sākuma ekrāna parādīšanu lietojumprogrammas startēšanas laikā.

  - **DocLocation** —  dokumenta atvēršanas brīdī norāda uz dokumenta izcelsmes pakalpojumu (OneDrive, File Server, SharePoint, u. tml.).

  - **FirstBoot** — vai šī bija pirmā programmas palaišana.

  - **InitializationDuration** — laiks milisekundēs, kas bija nepieciešams, lai vispirms inicializētu Office procesu.

  - **InterruptionMessageId** — vai palaišanu pārtrauca dialogs, pieprasot lietotāja ievadi, kā arī šī dialoga ID.

  - **TotalWorkingSetMB** — atmiņas apjoms megabaitos procesa darba kopā.

  - **VirtualSetMB** — atmiņas apjoms megabaitos procesa virtuālajā kopā. (Tikai MacOS/iOS)

  - **WorkingSetPeakMB** — vislielākais atmiņas apjoms megabaitos, kas līdz šim ir bijis procesa darba kopā.

#### <a name="officeuxofficeinsidercanshowofficeinsiderslab"></a>Office.UX.OfficeInsider.CanShowOfficeInsiderSlab

Darbība, kas izseko, vai Office Backstage UI cilnē Konts lietotājam var parādīt Office Insider bloku.

Tiek apkopoti šādi lauki:

  - **Data_CanShow** — norāda, vai Office Backstage UI cilnē Konts lietotājam var parādīt Office Insider bloku.
  
  - **Data_Event** — netiek izmantots

  - **Data_EventInfo** — netiek izmantots

  - **Data_Reason** — netiek izmantots.
 

#### <a name="officeuxofficeinsiderregistercurrentinsider"></a>Office.UX.OfficeInsider.RegisterCurrentInsider

Kritisks signāls, kas ļauj izsekot veiksmīgu vai neveiksmīgu iepriekš nereģistrētu Office Insider versiju lietotāju reģistrāciju. Tas ir paredzēts Office Insider lietotājiem, kas pievienojās Office Insider programmai pirms tika ieviesta Office Insider reģistrācija.

Tiek apkopoti tālāk norādītie lauki.

- **Data_RegisterInsider** — Office Insider reģistrācijas statuss.

- **Data_RegisterInsiderHr** — Office Insider reģistrācijas rezultāta kods.

- **Data_RegistrationStateCurrent** — pašreizējais reģistrācijas stāvoklis.

- **Data_RegistrationStateDesired** — pieprasītais reģistrācijas stāvoklis.


#### <a name="officeuxofficeinsidershowofficeinsiderdlg"></a>Office.UX.OfficeInsider.ShowOfficeInsiderDlg

Kritiskais signāls, kas izseko lietotāja mijiedarbību ar dialoglogu Pievienojies programmai Office Insider. Tiek izmantots, lai identificētu jebkāda veida problēmas lietotāja iniciēto izmaiņu īstenošanā, piemēram, pievienošanās vai izstāšanās no Office Insider programmas un Office Insider līmeņa izmaiņas.

Tiek apkopoti tālāk norādītie lauki.

- **Data_AcceptedContactMeNew** — norāda, vai lietotājs, pievienojoties Office Insider programmai, ir piekritis saziņai ar Microsoft.

- **Data_InsiderLevel** — Insider līmenis, atverot dialoglogu “Pievienojies Office Insider”.

- **Data_InsiderLevelNew** — Insider līmenis, aizverot dialoglogu “Pievienojies Office Insider”.

- **Data_IsInternalUser** — norāda, vai programma darbojas ar Microsoft korporatīvā konta akreditācijas datiem.

- **Data_IsInternalUserInit** — norāda, vai kods varēja noteikt to, vai programma darbojas ar Microsoft korporatīvā konta akreditācijas datiem.

- **Data_OpenNewsletterWebpage** — norāda, vai Office Insider biļetena abonēšanas saite tika aktivizēta pie nosacījuma, ka lietotājs pievienojās Office Insider programmai, biļetena abonementa funkcija ir iespējota un lietotājs nav atcēlis Office Insider biļetena abonementa tīmekļa vietnes atvēršanu.
    
- **Data_RegisterInsider** — Office Insider reģistrācijas statuss.

- **Data_RegisterInsiderHr** — Office Insider reģistrācijas rezultāta kods.

- **Data_RegistrationStateCurrent** — pašreizējais reģistrācijas stāvoklis.

- **Data_RegistrationStateDesired** — pieprasītais reģistrācijas stāvoklis.




#### <a name="officevisiosharedvisiofilerender"></a>Office.Visio.Shared.VisioFileRender

Šis notikums tver faila atveides laiku. Šis notikums palīdz veikt failu atveidošanas izpildes pārbaudi.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_AvgTime: integer** — vidējais laiks, lai atveidotu Visio zīmējumu sesijā

  - **Data\_CompositeSurfEnabled: bool** — ja patiess, kompozītās atveidošanas režīms ir iespējots

  - **Data\_Count: integer** — Visio zīmējuma atveidošanas gadījumu skaits sesijā

  - **Data\_FirstRenderTime: long** — laiks milisekundēs, lai atveidotu failu pirmajā palaišanas reizē

  - **Data\_MaxTime: integer** — maksimālais laiks, lai atveidotu Visio zīmējumu sesijā

#### <a name="officevisiovisiofileopenreliability"></a>Office.Visio.VisioFileOpenReliability

Šis notikums apkopo failu atvēršanas izpildes datus par Visio Dev16. Šis notikums tiek izmantots, lai pārraudzītu Visio Dev16 faila atvēršanas darbības izpildi, un saista to ar tādiem failu rekvizītiem kā faila lielums. Faila rekvizīti sniedz mums iespēju ātrāk atkļūdot problēmas un uzzināt to cēloņus.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_CorrelationId: string — **dokumentu korelācijas identifikators

  - **Data\_DocIsEnterpriseProtected: bool —** patiess, ja dokuments ir aizsargāts, izmantojot Windows informācijas aizsardzību

  - **Data\_DocumentId: string —** faila ceļa GUID

  - **Data\_DurationToCompleteInMilliseconds:double —** laiks milisekundēs, lai pabeigtu saglabāšanu

  - **Data\_DurationToCompleteInMillisecondsSquared: double —** argumenta DurationToCompleteInMilliseconds kvadrāta vērtība

  - **Data\_ErrorCode: integer —** faila atvēršanas kļūmes iekšējas kļūdas kods

  - **Data\_Extension\_Docs: string —** atvērtas shēmas faila paplašinājums

  - **Data\_FileIOBytesRead: int —** saglabāšanas laikā nolasīto baitu kopskaits

  - **Data\_FileIOBytesReadSquared: int —** Data\_FileIOBytesRead vērtība kvadrātā

  - **Data\_FileIOBytesWritten: int —** saglabāšanas laikā ierakstīto baitu kopskaits

  - **Data\_FileIOBytesWrittenSquared: int —** Data\_FileIOBytesWritten vērtība kvadrātā

  - **Data\_FileName: binary** — faila nosaukuma binārā jaukšana

  - **Data\_FileOpenDownloadDurationInMs: long —** faila lejupielādes laiks milisekundēs

  - **Data\_FileOpenEndDurationInMs: long —** faila atvēršanas laiks milisekundēs

  - **Data\_FileOpenTimeStamp: time: —** laikspiedols, kad tiek sākta faila atvēršana

  - **Data\_FilePathHash: binary** — faila ceļa GUID

  - **Data\_FileSize: long —** dokumenta lielums baitos

  - **Data\_FileType: string —** atvērtas shēmas faila paplašinājums

  - **Data\_IsInternalFile: bool —** patiess, ja fails ir iekšējais fails Piemēram, šablons

  - **Data\_IsIRM: bool —** patiess, ja failam ir informācijas tiesību piekļuves aizsardzība

  - **Data\_IsReadOnly: bool —** patiess, ja fails ir tikai lasāms

  - **Data\_IsSuccess: bool —** patiess, ja faila atvēršana bija sekmīga

  - **Data\_Location: string —** faila atrašanās vietas, piemēram, lokāla, SharePoint, OneDrive, WopiConsumer, WopiBusiness, GenericThirdPartyConsumer

  - **Data\_NetworkIOBytesRead: int —** saglabāšanas laikā nolasīto tīkla baitu kopskaits

  - **Data\_NetworkIOBytesReadSquared: int —** Data\_NetworkIOBytesRead vērtība kvadrātā

  - **Data\_NetworkIOBytesWritten: int —** saglabāšanas laikā ierakstīto tīkla baitu kopskaits

  - **Data\_NetworkIOBytesWrittenSquared: int —** NetworkIOBytesWritten vērtība kvadrātā

  - **Data\_OpenLocation: integer —** faila atrašanās vieta, no kuras tas tika atvērts 0, lokāla, 1, tīkls, 2, SharePoint, 3 – tīmeklis

  - **Data\_Size\_Docs: integer —** dokumenta lielums baitos

  - **Data\_Tag: string —** unikālais identifikators, lai identificētu notikumu Saglabāt kā

  - **Data\_WasSuccessful: bool —** patiess, ja notikusi veiksmīga atvēršana

#### <a name="onenotesyncprovisioningcompleted-previous-name-officeonenoteandroidsyncprovisioningcompleted"></a>OneNote.Sync.ProvisioningCompleted *(iepriekšējais nosaukums)*, Office.OneNote.Android.Sync.ProvisioningCompleted

Kritiskais signāls, kas tiek izmantots, ka pēc lietotāja pierakstīšanās OneNote Android lietojumprogrammā, tiek atbilstoši nodrošinātas piezīmju grāmatiņas, lai tām būtu vienkārši piekļūt. Tek izmantota kritiskas regresijas atklāšanai OneNote lietojumprogrammā un pakalpojuma darbspējā

Tiek apkopoti šādi lauki: 

- **AppSuspendedDuringEvent** — Būla izteiksme, kas norāda, vai lietojumprogramma tika aizturēta nodrošināšanas laikā

- **NetworkConnection** — izmantotās ierīces tīkla savienojamības tips

- **NetworkDataExchange** — reģistrē nodrošināšanas laikā apmainīto baitu skaitu.

- **ServerType** — atgriež tā servera tipu, kas piedāvā pakalpojumu

- **TimeTakenInMilliSeconds** — norāda nodrošināšanas pabeigšanai nepieciešamo laiku milisekundēs

#### <a name="onenotesyncprovisioningstarted-previous-name-officeonenoteandroidsyncprovisioningstarted"></a>OneNote.Sync.ProvisioningStarted *(iepriekšējais nosaukums)*, Office.OneNote.Android.Sync.ProvisioningStarted

Kritiskais signāls, kas tiek izmantots, ka pēc lietotāja pierakstīšanās OneNote Android lietojumprogrammā, tiek atbilstoši nodrošinātas piezīmju grāmatiņas, lai tām būtu vienkārši piekļūt.  Tek izmantota kritiskas regresijas atklāšanai OneNote lietojumprogrammā un pakalpojuma darbspējā

Tiek apkopoti šādi lauki: 

- **NetworkConnection** — izmantotās ierīces tīkla savienojamības tips

- **ServerType** — atgriež tā servera tipu, kas piedāvā pakalpojumu

#### <a name="perf_event"></a>perf_event

Izmanto, lai uzraudzītu iespējamo negatīvo ietekmi uz dažādu lietojumprogrammas daļu ielādes veiktspēju, piemēram, lai nodrošinātu to, ka pirmajā lietojumprogrammas atvēršanas reizē jūsu iesūtne tiktu ielādēta tik ātri, cik iespējams.

Tiek apkopoti šādi lauki: 

- **app_start_show_message_list** — nozīmē to, ka notika lietojumprogrammas sāknēšanas veiktspējas problēma, kuras rezultātā jūsu iesūtnes ziņojumu saraksta ielādei bija nepieciešams ilgs laiks

- **event_type** — norāda, kāda veida veiktspējas notikums izraisīja veiktspējas problēmu, lai palīdzētu mums atklāt problēmas, kas saistītas ar konkrētu tipu.   

- **extra_params** — izstrādātājs šeit var pievienot papildu parametrus, lai sniegtu mums vairāk informācijas par šīs veiktspējas problēmas iemesliem, piemēram, kad šī darbība sākās un beidzās utt. 

- **total_time_elapsed** — norāda veiktspējas notikuma ilgumu, lai palīdzētu mums noteikt veiktspējas problēmas nozīmīgumu

#### <a name="performance_record"></a>performance_record

Ļauj mums noteikt un novērst situācijas, kad lietojumprogrammas atmiņas izmantošana un procesora izmantošana kļūst kritiski augsta, kas var izraisīt jūsu ierīces darbības palēnināšanu

Tiek apkopoti šādi lauki: 

- **category** — norāda, vai lietojumprogramma konkrētajā laikā ir priekšplānā vai fonā. Iespējamās vērtības iekļauj priekšplānu un fonu.

- **cpu_usage** — norāda, kādu daļu procesora procentu izteiksmē izmantoja lietojumprogramma, lai mums būtu pieejama salīdzināma informācija negatīvās ietekmes uz veiktspēju noteikšanai

- **is_watch_app_installed** — norāda, vai lietotājs pašlaik izmanto Apple Watch un vai tas ir instalēts, lai palīdzētu mums izprast pulksteņa radīto negatīvo ietekmi uz veiktspēju

- **is_watch_paired** — norāda, vai lietotājs pašlaik izmanto Apple Watch un vai tas ir savienots ar ierīci, lai palīdzētu mums noteikt Apple Watch radīto negatīvo ietekmi uz veiktspēju

- **is_watch_supported_and_active** — norāda, vai lietotājs pašlaik izmanto Apple Watch un vai tas ir aktīvs, lai palīdzētu mums izprast pulksteņa radīto negatīvo ietekmi uz veiktspēju

- **memoAry_used_percentage** — norāda, kādu daļu atmiņas procentu izteiksmē izmantoja lietojumprogramma, lai mums būtu pieejama salīdzināma informācija negatīvās ietekmes uz veiktspēju noteikšanai

- **memory_used** — norāda, cik daudz atmiņas izmantoja lietojumprogramma, lai mums būtu pieejama salīdzināma informācija negatīvās ietekmes uz veiktspēju noteikšanai


### <a name="application-activity-error-subtype"></a>*Lietojumprogrammas darbības kļūdas apakštips*

Līdzekļa funkcionalitātes vai lietošanas iespēju kļūdas.

#### <a name="assertion"></a>assertion

Šis notikums ļauj mums noteikt, kad notiek kritiskas lietojumprogrammas kļūdas, kas izraisa jūsu lietojumprogrammas avāriju vai nopietnas problēmas, kuru rezultātā jūs redzat tukšas rindas jūsu iesūtnē.

Tiek apkopoti šādi lauki:

- **count** — kopējais ar kļūdu saistīto vienumu skaits, piemēram, kalendāru ar kļūdām skaits

- **has_hx** — norāda, vai konts izmanto jauno sinhronizācijas pakalpojumu, lai palīdzētu noteikt mūsu sinhronizācijas pakalpojuma radītās problēmas

- **host_name** — ar kļūdu saistītā pakalpojuma resursdatora nosaukums, kas ļauj mums noteikt ar konkrēto resursdatoru saistītās kļūdas.

- **host_name** — ar kļūdu saistītā resursdatora tips, lai palīdzētu mums atklāt ar konkrētu resursdatora tipu saistītās problēmas 

- **message** — pielāgots ziņojums novērtējumam, kas tiek izmantots problēmas diagnosticēšanai 

- **origin** — kļūdas izcelsme kodā, lai palīdzētu mums atklāt ar konkrēto koda daļu saistītās problēmas

- **stacktrace** — izsekošanas steks, kurā notika novērtējums, lai palīdzētu mums atklāt ar konkrētu koda daļu saistītās problēmas

- **type** — notikušās novērtējuma kļūdas tips, piemēram, null_folder_name, compose_selected_null_account, kas palīdz mums noteikt ar konkrētu koda daļu saistītās problēmas

#### <a name="edit_contact_error"></a>edit_contact_error

Ļauj mums noteikt un novērst situācijas, kad kļūdas notiek tad, kad mēģināt apskatīt vai rediģēt kontaktpersonas mūsu lietojumprogrammā.

Tiek apkopoti šādi lauki: 

- **errorType** — notikušās kļūdas tips, kas palīdz mums diagnosticēt problēmu

- **field** — kontaktpersonas lauks, ko lietotājs mēģināja rediģēt, kas palīdz mums diagnosticēt problēmu

- **version** — mūsu izmantotā kontaktpersonas kartītes pakalpojuma versija, kas palīdz mums diagnosticēt problēmu

#### <a name="error_report"></a>error_report

Šis notikums ļauj mums noteikt, kad notika kritiskās lietojumprogrammas kļūdas, lai mēs varētu novērst problēmas, kas izraisa jūsu lietojumprogrammas avārijas vai neļauj jums lasīt e-pasta ziņojumus. 

Tiek apkopoti šādi lauki: 

- **client-request-id** — klienta pieprasītais identifikators pieprasījumam, kas izraisīja kļūdu
 
- **date** — pieprasījuma, kas izraisīja kļūdu, laikspiedols

- **error** — kļūdas tips, piemēram, get_mailbox_location_failed
 
- **error_body** — kļūdas ziņojuma pamatteksts
 
- **is_x_mailbox_anchor_set** — norāda, vai pieprasījumā tika iestatīts rekvizīts X-AnchorMailbox
 
- **reason** — norāda kļūdas iemeslu, piemēram, kļūdas ziņojums
 
- **request-id** — servera pieprasījuma identifikators pieprasījumam, kas izraisīja kļūdu
 
- **source** — kļūdas avots OM infrastruktūrā, parasti viens no 'BE' vai 'FE'


#### <a name="officeairspacebackendwin32graphicsdriversofthang"></a>Office.AirSpace.Backend.Win32.GraphicsDriverSoftHang 

Palīdz Microsoft nošķirt videokartes draivera nereaģēšanas gadījumus no īsākiem gadījumiem, lai vieglāk pieņemtu lēmumus par to, kuriem videokartes draiveriem, iespējams, ir radušās problēmas. Lietotāja videokartes draiveris izraisīja situāciju, kurā Office pārtrauca reaģēt, taču šīs situācijas ietekme vēl nav zināma

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_InDeviceCall** — metode izsauca videokarti, kas izraisīja reaģēšanas pārtraukumu

  - **Data\_Timeout** — cik ilgi nereaģēja

  #### <a name="officeandroidadalsigninuiprompts"></a>Office.Android.ADALSignInUIPrompts

Šīs notikums norāda, ka lietotājs saņēma pierakstīšanās uzvedni skolas vai darba kontam.  Šis notikums palīdz saprast mūsu lietojumprogrammu pierakstīšanās stāvokļa darbspēju un atbilstoši rīkoties, kad pamanām neparedzētas pierakstīšanās uzvednes. 

Tiek apkopoti tālāk norādītie lauki:

- **LastLoginDelta** — laika delta no pēdējās sekmīgās pieteikšanās.

- **PreviousIdentityCredProviderState** — norāda konta stāvokli.

- **PreviousIdentityState** — norāda konta stāvokli, piemēram, sesijas laiks beidzies. 

- **SignInResultCode** — norāda pierakstīšanās uzvednes beigu rezultātā kodu.

- **UseCache**— norāda, vai mēs ar uzvednes palīdzību likām lietotājam ievadīt paroli atkārtoti.

- **UserType** — norāda, vai tas ir esošs konts vai jauns konts

#### <a name="officeandroidandroidappdocsfileoperationends"></a>Office.Android.AndroidAppDocsFileOperationEnds

Kritiskie dokumenti tikai Android (AppDocs) telemetrijas dati faila jauns/atvērt/saglabāt kā beigu darbībām. Uzskaita šo AppDocs neveiksmīgo darbību kļūdu kodus.  Microsoft to izmanto, lai noteiktu kļūmes dažādās failu darbībā un precīzo slāni, kurā radās Word, Excel vai PowerPoint lietojumprogrammu kļūme.

Tiek apkopoti šādi lauki:

- **AccessMode** — faila piekļuves režīma uzskaitījuma vērtība. Vērtības — nav, ReadOnly, ReadOnlyUpgradable, ReadWrite

- **BlockingUIShown** — būla, kas norāda, vai jebkurā vietā plūsmā tika parādīts bloķēšanas lietotāja interfeiss.

- **ContentUriAuthority** — satura URL no SAF iestādes

- **Correlation** — GUID ar darbību saistītajam sasaistes ID

- **DocId** — AppDocs ģenerētais dokumenta ID

- **DocInstanceId** — AppDocs ģenerētā dokumenta instances ID, kas ir ietverta darbības instancē dokumentā

- **DocIsEnterpriseProtected** — būla, kas norāda, vai dokuments ir aizsargāts.

- **DocUserId** — lietotāja ID no MS autentifikācijas slāņa

- **DocUserIdProvider** — uzskaitījums, kas apzīmē lietotāja ID nodrošinātāju, 0 = nezināms, 1 = LiveId, 2 = OrgId, 3 = SSPI, 4 = ADAL

- **DurationInMs** — faila darbības beigšanās laiks milisekundēs

- **EndReason** — uzskaitījuma vērtība, kas apzīmē beigu iemeslu.  Vērtības — nav, izdevās, neizdevās, atcelt

- **ErrorCode** — faila darbības kļūdas kods

- **Extension** — faila, kas tiek atvērts, paplašinājums.

- **FileSourceLocation** — faila atrašanās vietas uzskaitījuma vērtība. Iespējamās vērtības: nav, lokāls, UncOrMappedNetworkDrive, SkyDrive, lietojumprogramma, SharePoint, UnknownServer

- **FILETIME** — notikuma laiks

- **FirstBCSClientError_Info** — kļūdas koda informācija, kas saistīta ar failu konvertēšanu

- **HttpStatusCode** — http atbildes kods tīmekļa pakalpojuma pieprasījumam

- **InitalizationReason** — faila atvēršanas ieejas punkts

- **K2FileIOHresult** — Hresult kods faila atvēršanas darbības beigām

- **LastBCSClientError_TagId** — pēdējā BCS (binārā konvertēšanas pakalpojums) klienta kļūda

- **OfficeWebServiceApiStatusFlag** — statusa karodziņš tīmekļa pakalpojuma pieprasījumam

- **OpEndEventId** — atzīme, kas norāda, kur faktiski beidzās darbība

- **OpFlags** — dokumenta darbību param. karodziņi, ko izmanto AppDocs slānis.

- **OpSeqNum** — skaitlis, kas norāda ar failu darbību saistīto pieprasījumu secību AppDocs slānī

- **OpType** — darbības veida uzskaitījums. Vērtības: "nav", "CreateDocument", "OpenDocument", "CopyDocument", "CloseDocument", "SaveDocument", "OpenVersion", "CloseVersion"

- **PreFetchState** — uzskaitījums jaunu failu izveides darbību vedņu iepriekšējās ieneses stāvoklim.

- **ProviderApp** — tās lietojumprogrammas pakotnes nosaukums, no kuras tiek atvērts fails

- **ScopeInstanceId** — tvēruma instances ID, kas tiek lietots datu konteksta pievienošanai darbībām

- **Size** — faila lielums

- **State** — faila stāvokļa uzskaitījuma vērtība. Vērtības: nav, notiek izveide, izveidots, neizdevās izveidot, atvēršana, atvērts, atvēršana neizdevās, notiek kopēšana, kopēšana neizdevās, notiek aizvēršana, aizvērts, aizvēršana neizdevās

- **TemplateName** — binārais dokumenta veidnes no veidņu pakalpojuma nosaukums, piemēram, TF10002009.dotx

- **UriScheme** — URL shēma

#### <a name="officeandroidandroidautherror"></a>Office.Android.AndroidAuthError

Šis notikums apzīmē pamata autentifikācijas kļūmes klusās marķiera atsvaidzināšanas laikā, pakalpojuma pierakstīšanās lapas ielādes laikā un tā tālāk.  Šis notikums palīdz saprast mūsu lietojumprogrammu pierakstīšanās stāvokļa darbspēju, veiktos pierakstīšanās mēģinājumus, un atbilstoši rīkoties, kad pamanām neparedzētas kļūmes. 

Tiek apkopoti tālāk norādītie lauki:

- **ADALErrorCode** — norāda kļūdas kodu, vienlaikus parādot pierakstīšanās uzvedni vai kluso marķiera ieneses mēģinājumu darba kontam.

- **ADALErrorCode** — norāda neapstrādāto kļūdas kodu, vienlaikus parādot pierakstīšanās uzvedni vai kluso marķiera ieneses mēģinājumu darba kontam.

- **ErrorGroup** — norāda konta veidu, piemēram, personiskais vai darba konts vai lokālo darba kontu.

- **IDCRLErrorCode** — norāda kļūdas kodu, vienlaikus parādot pierakstīšanās uzvedni personiskajam kontam.

- **IDCRLRawErrorCode** — norāda neapstrādātu kļūdas kodu, vienlaikus parādot pierakstīšanās uzvedni personiskajam kontam.

- **LiveOAuthErrorCode** — norāda kļūdas kodu personiskā konta klusā marķiera atsvaidzināšanas mēģinājuma laikā.

- **LiveOAuthRawErrorCode** — norāda neapstrādātu kļūdas kodu personiskā konta klusā marķiera atsvaidzināšanas mēģinājuma laikā.

- **NTLMErrorCode** — norāda kļūdas kodu, vienlaikus parādot pierakstīšanās uzvedni lokālajam kontam.

#### <a name="officeandroidandroidfileasyncsavestatus"></a>Office.Android.AndroidFileAsyncSaveStatus

Tver faila asinhronizācijas saglabāšanas statusa datus un dažādus kļūdu kodus no dažādiem komponentiem.  Microsoft izmanto šos datus, lai analizētu, vai lietojumprogrammā pastāv lietotāju datu zudumi, saglabājot failus Word, Excel vai PowerPoint lietojumprogrammās.

Tiek apkopoti šādi lauki:

- **FileExtension** — faila paplašinājums

- **FileIOSaveHResult** — HResult faila saglabāšanas darbībai

- **FileIOSaveIsCopy**— būla, kas norāda, ja darbība saglabā kopiju.

- **FileSize** — faila lielums

- **FileSourceLocation** — faila atrašanās vietas uzskaitījums. Vērtības: nav, lokāls, UncOrMappedNetworkDrive, SkyDrive, lietojumprogramma, SharePoint, UnknownServer

#### <a name="officeandroidandroidfileopenreliability"></a>Office.Android.AndroidFileOpenReliability

Tver faila atvēršanas statusa datus un dažādu kļūdu kodus, lai identificētu, kādas ir faila atvēršanas paredzētās un neparedzētās kļūmes un kura koda daļa ziņo par to.  Microsoft izmanto šos datus, lai analizētu faila atvēršanas kļūmju iemeslus un aprēķinātu kritisko metriku, piemēram, faila atvēršanas izdošanās pakāpi Word, Excel vai PowerPoint lietojumprogrammās.

Tiek apkopoti šādi lauki:

- **AccessMode** — piekļuves režīma uzskaitījums

- **AppDocsFileOpenErrorCode** — AppDocs faila atvēršanas kļūdas kods

- **ContentUriAuthority** — satura URL no SAF iestādes

- **DownloadCsiError** — lejupielādē kļūdas ziņojumu no CSI

- **FileExtension** — faila paplašinājums

- **FileOpenEndErrorCode** — faila atvēršanas kļūdas kods

- **FileOpenStatus** — faila atvēršanas statusa uzskaitījums

- **FileSize** — faila lielums

- **FileSourceLocation** — faila atrašanās vietas uzskaitījums

- **FirstBCSClientError_Info** — pēdējā BCS (binārā konvertēšanas pakalpojums) klienta kļūda

- **IfWordFileOpencanceled** — ja lietotājs atcēla faila atvēršanu Word lietojumprogrammā

- **InitializationReason** — uzskaitījums, kas norāda faila atvēršanas ieejas punktu

- **IsAutoSaveDisabled** — vai automātiskā saglabāšana ir atspējota faila atvēršanas laikā

- **IsFileEmpty** — būla, kas norāda, vai fails ir tukšs

- **K2FileIOHresult** — Hresult faila darbības beigām

- **OpenCsiError** — faila atvēršanas kļūdas ziņojums CSI slānī

- **OpEndEventId** — atzīme, kas norāda, kur faktiski beidzās darbība

- **PPTHresult** — HRESULT programmā PPT

- **PPTIsExpectedError** — PPT kļūdas klasifikācija faila atvēršanas paredzētajai/neparedzētajai kļūmei 

- **PPTTag** — PPT kļūdas atzīme

- **ProviderApp** — tās lietojumprogrammas pakotnes nosaukums, no kuras tiek atvērts fails

- **ProviderFileSize** — faila lielums, kas notverts, atverot failu ar faila aktivāciju

- **State** — faila atvēršanas stāvokļa uzskaitījums.

- **UriScheme** — URL shēma

- **WordErrortag** — Word kļūdas atzīme

- **WordFileCorruptionReason** — bojājuma iemesls, kura dēļ var neizdoties atvērt Word failu

- **WordFileOpenErrorCode** — Word specifisks faila atvēršanas kļūdas kods.

- **WordFileTypeFromDod** — faila tips, kuru Word nosaka balstoties, uz faktisko faila formātu

- **WordFileTypeFromExtension** — faila veids, ko Word nosaka, balstoties uz faila paplašinājumu

#### <a name="officeandroidandroidfilesavestatus"></a>Office.Android.AndroidFileSaveStatus

Būtiski svarīgs, lai tvertu faila saglabāšanas statusa datus un dažādus kļūdu kodus no dažādiem komponentiem.  Microsoft izmanto šos datus, lai analizētu, vai lietojumprogrammā pastāv lietotāju datu zudumi, saglabājot failus Word, Excel vai PowerPoint lietojumprogrammās.

Tiek apkopoti šādi lauki:

- **AccessMode** — Vērtības** — nav, ReadOnly, ReadOnlyUpgradable, ReadWrite.

- **AppDocsEndReason** — uzskaitījums failu saglabāšanai Appdoc EndReason.  Vērtības: nav, izdevās, neizdevās, atcelt.

- **AppDocsErrorCode** — gala kļūdas kods faila saglabāšanas kļūmei.

- **AppDocsTriggeringSaveDetails** — lauks, lai norādītu, vai saglabāšanu izraisa AppDocs virkne

- **DocInstanceId** — AppDocs ģenerētā dokumenta instances ID, kas ir ietverta darbības instancē dokumentā

- **ExcelFileSaveResult** — Excel specifisks HResult

- **FileExtension** — faila paplašinājums.

- **FileIOSaveErrorCode** — FileIO kļūdas kods

- **FileIOSaveHResult** — FileIO Hresult

- **FileIOSaveIsCopy**— būla, kas norāda, vai šī ir kopēšanas darbība.

- **FileSize** — faila lielums

- **FileSourceLocation** — faila atrašanās vietas uzskaitījums.  Vērtības: nav, lokāls, UncOrMappedNetworkDrive, SkyDrive, lietojumprogramma, SharePoint, UnknownServer

- **OpFlags** — darbības karodziņi saglabāšanai

- **PPTFileSaveFailHresult** — PPT Hresult saglabāšanas kļūmei

- **PPTFileSaveFailTag** — PPT atzīme saglabāšanas kļūmei

- **State** — faila atvēršanas stāvokļa uzskaitījums. 

- **Values** — nav, notiek izveide, izveidots, neizdevās izveidot, atvēršana, atvērts, atvēršana neizdevās, notiek kopēšana, kopēšana neizdevās, notiek aizvēršana, aizvērts, aizvēršana neizdevās

- **WordFileCopyErrorTrackbackTag** — atsauces atzīme CopyDocument posma kļūmei Word lietojumprogrammā

- **WordFileSaveCancelReason** — atsauces atzīme atcelšanām Word lietojumprogrammā

- **WordFileSaveEid** — Word specifisks kļūdas kods

- **WordFileSaveErrorTrackbackTag** — atsauces atzīme saglabāšanas kļūmēm

- **WordFileSaveOpResult** — uzskaitījums rezultāta statusam 0, ja izdevās, 1, ja neizdevās, 2, ja atcelts

- **WordFileSaveSuccess** — uzskaitījums Word specifiskai detalizētajai informācijai veiksmīgas faila saglabāšanas darbībai.

#### <a name="officeandroidandroidofficeactivationlatency"></a>Office.Android.AndroidOfficeActivationLatency

Kritiski svarīgi dati, lai apkopotu pilnvērtīgu faila atvēršanas laiku visām faila atvēršanām Windows, Excel, PowerPoint lietojumprogrammās.  Microsoft to izmanto, lai noskaidrotu mūsu lietojumprogrammu failu atvēršanas metriku

Tiek apkopoti tālāk norādītie lauki:

- **AppBootingOccured** — būla, lai pārbaudītu, vai lietojumprogrammas sāknēšana ir pabeigta

- **ApplicationBootTime** — lietojumprogrammas sāknēšanas specifiskajai fāzei nepieciešamais laiks

- **AppSuspendedDuringBoot** — būla, lai pārbaudītu, vai lietojumprogramma tika aizturēta sāknēšanas laikā

- **BlockingUIShownDuringFileOpen** — būla, lai norādītu, vai faila atvēršanas darbības laikā bija bloķēšanas dialogs

- **CachedInfoAvailable** — būla, lai meklētu kešatmiņā saglabātu faila atvēršanai specifisku informāciju

- **DocumentRecoveryInvoked** — būla, kas norāda, vai bija atgūšanu gaidošs dokuments

- **EndToEndActivationTime** — laiks, kas veltīts faila renderēšanai failiem, kas atvērti ārpus lietojumprogrammas

- **EndToEndFileOpenTime** — laiks, kas veltīts faila renderēšanai failiem, kas atvērti lietojumprogrammā

- **FileOpenPhaseDurationInMs** — faila atvēršanas darbības laiks specifiskajā fāzē

- **FileSourceLocation** — uzskaites vērtība faila atrašanās vietai, piemēram, nav, lokāls, UncOrMappedNetworkDrive, SkyDrive, App, SharePoint, UnknownServer

- **InitalizationReason** — faila atvēršanas ieejas punkts

- **InitialBootPhaseTime** — lietojumprogrammas sāknēšanas specifiskajai fāzei nepieciešamais laiks

- **IsThisFirstLaunch** — būla, kas norāda, vai šī ir pirmā lietojumprogrammas sāknēšanas reize

- **MinimumLibraryLoadPhaseTime** — lietojumprogrammas sāknēšanas specifiskajai fāzei nepieciešamais laiks

- **MinimumLibraryLoadPhaseTime** — lietojumprogrammas sāknēšanas specifiskajai fāzei nepieciešamais laiks

- **MinimumLibraryLoadPhaseTime** — lietojumprogrammas sāknēšanas specifiskajai fāzei nepieciešamais laiks

- **PostAppInitTimeInMs** — lietojumprogrammas sāknēšanas specifiskajai fāzei nepieciešamais laiks

- **PPTRenderPhase** — ar PPT renderēšanas specifisku fāzi saistītais laiks

- **PreAppInitTimeInMs** — lietojumprogrammas sāknēšanai specifiskajai fāzei nepieciešamais laiks

- **ProviderApp** — tās lietojumprogrammas pakotnes nosaukums, no kuras tiek atvērts fails

- **TelemetryReason** — līdzīgs InitialisationReason, bet detalizētāka uzskaitījuma vērtība attiecībā uz faila atvēršanas ieejas punktu.

- **UserDialogInterruptionDuringBoot** — būla, kas norāda, vai sāknēšanas laikā bija kāds bloķēšanas dialogs

- **XLRenderPhase** — ar XL renderēšanai specifisku fāzi saistītais laiks

#### <a name="officeandroidappdocsfileoperationends"></a>Office.Android.AppDocsFileOperationEnds

Kritiskie dokumenti tikai Android (AppDocs) telemetrijas dati faila jauns/atvērt/saglabāt kā beigu darbībām. Uzskaita šo AppDocs neveiksmīgo darbību kļūdu kodus.  Microsoft to izmanto, lai noteiktu kļūmes dažādās failu darbībā un precīzo slāni, kurā radās Word, Excel vai PowerPoint lietojumprogrammu kļūme.

Tiek apkopoti šādi lauki:

- **AccessMode** — faila piekļuves režīma uzskaitījuma vērtība.  Vērtības: nav, ReadOnly, ReadOnlyUpgradable, ReadWrite

- **BlockingUIShown** — būla, kas norāda, vai jebkurā vietā plūsmā tika parādīts bloķēšanas lietotāja interfeiss.

- **ContentUriAuthority** — satura URL no SAF iestādes

- **Correlation** — GUID ar darbību saistītajam sasaistes ID

- **DocId** — AppDocs ģenerētais dokumenta ID

- **DocInstanceId** — AppDocs ģenerētā dokumenta instances ID, kas ir ietverta darbības instancē dokumentā

- **DocIsEnterpriseProtected** — būla, kas norāda, vai dokuments ir aizsargāts.

- **DocUserId** — lietotāja ID no MS autentifikācijas slāņa

- **DocUserIdProvider** — uzskaitījums, kas apzīmē lietotāja ID nodrošinātāju, 0 = nezināms, 1 = LiveId, 2 = OrgId, 3 = SSPI, 4 = ADAL

- **DurationInMs** — faila darbības pabeigšanas laiks milisekundēs

- **EndReason** — uzskaitījuma vērtība, kas apzīmē beigu iemeslu.  Vērtības: nav, izdevās, neizdevās, atcelt

- **ErrorCode** — faila darbības kļūdas kods

- **Paplašinājums** — pirmās četras paplašinājuma rakstzīmes failam, kas tiek atvērts.

- **FileSourceLocation** — faila atrašanās vietas uzskaitījuma vērtība. Iespējamās vērtības: nav, lokāls, UncOrMappedNetworkDrive, SkyDrive, lietojumprogramma, SharePoint, UnknownServer

- **FILETIME** — notikuma laiks

- **FirstBCSClientError_Info** — kļūdas koda informācija, kas saistīta ar failu konvertēšanu

- **HttpStatusCode** — HTTP atbildes kods tīmekļa pakalpojuma pieprasījumam

- **InitalizationReason** — faila atvēršanas ieejas punkts

- **K2FileIOHresult** — Hresult kods faila atvēršanas darbības beigām

- **LastBCSClientError_TagId** — pēdējā BCS (binārā konvertēšanas pakalpojums) klienta kļūda

- **OfficeWebServiceApiStatusFlag** — statusa karodziņš tīmekļa pakalpojuma pieprasījumam

- **OpEndEventId** — atzīme, kas norāda, kur faktiski beidzās darbība

- **OpFlags** — dokumenta darbību param. karodziņi, ko izmanto AppDocs slānis.

- **OpSeqNum** — skaitlis, kas norāda ar failu darbību saistīto pieprasījumu secību AppDocs slānī

- **OpType** — darbības veida uzskaitījums. Vērtības: "nav", "CreateDocument", "OpenDocument", "CopyDocument", "CloseDocument", "SaveDocument", "OpenVersion", "CloseVersion"

- **PreFetchState** — uzskaitījums jaunu failu izveides darbību vedņu iepriekšējās ieneses stāvoklim.

- **ProviderApp** — tās lietojumprogrammas pakotnes nosaukums, no kuras tiek atvērts fails

- **ScopeInstanceId** — tvēruma instances ID, kas tiek lietots datu konteksta pievienošanai darbībām

- **Size** — faila lielums

- **State** — faila stāvokļa uzskaitījuma vērtība. Vērtības: nav, notiek izveide, izveidots, neizdevās izveidot, atvēršana, atvērts, atvēršana neizdevās, notiek kopēšana, kopēšana neizdevās, notiek aizvēršana, aizvērts, aizvēršana neizdevās

- **TemplateName** — binārais dokumenta veidnes no veidņu pakalpojuma nosaukums, piemēram, TF10002009.dotx

- **UriScheme** — URL shēma

#### <a name="officeandroidbcserrors"></a>Office.Android.BCS.Errors

Binārās konversijas kļūdu telemetrija PDF drukāšanai un koplietošanai.  Microsoft to izmanto, lai identificētu kļūmes punktus BCS konversijas laikā Word, Excel vai PowerPoint lietojumprogrammās.

Tiek apkopoti šādi lauki:

- **DocumentFileSize** — faila lielums.

- **FileExtension** — faila paplašinājuma pirmās četras rakstzīmes.

- **IsFileDirty** — būla, kas norāda, vai failā ir nesaglabātas izmaiņas.

- **Location** — faila atrašanās vietas uzskaitījums.  Vērtības: OneDrive, SharePoint, Dropbox, citi

- **PDFConversionError** — atzīme, pie kuras rodas PDF konvertēšanas kļūda

- **PdfConversionErrorCode** — PDF konvertēšanas kļūdas kods

- **PdfConversionHRStatus** — PDF konvertēšanas statusa kods

- **PdfConversionResult** — PDF konvertēšanas rezultāta uzskaitījums.  Vērtības: "izdevās", "neizdevās" un "atcelts"

- **PdfFileSize** — PDF faila lielums

#### <a name="officeandroidclientsideiap"></a>Office.Android.ClientSideIAP

Kritisko kļūdu telemetrija datu bāzu kļūmei, pārlūkojot failus un pievienojot vietas.  Microsoft to izmanto, lai identificētu datu bāzu problēmas lietojumprogrammās, kas var traucēt lietotājam pievienot vietas vai pārlūkot tās lietojumprogrammās, izmantojot Word, Excel vai PowerPoint lietojumprogrammas. 

Tiek apkopoti šādi lauki:

- **ClientTransactionId** — GUID, kas tiek nodots DSC specifiskam izpirkšanas pieprasījumam.

- **CollectionTime** — abonementa iegādes pabeigšanas laiks

- **CountryCode** — klienta valsts kods, kas tiek nosūtīts DSC klienta izpirkšanas pieprasījumam

- **GoPremiumEntryPoint** — pirkuma aktivizēšanas ieejas punkts 

- **IsActivateExistingSubscription** — būla, kas norāda, vai bija iepriekš esošs abonements, kas tika aktivizēts

- **IsErrorRetriable** — būla, kas norāda, vai izpirkšanu var atkārtot

- **IsPreviousPurchase** — būla, kas norāda, vai aktivācija notika ar iepriekšējo abonementu iegādi

- **IsProvisioningTriggeredByRetry** — būla, kas norāda, vai tika iesaistīts atkārtots mēģinājums

- **LanguageCode** — klienta valodas kods, kas tiek nosūtīts DSC klienta izpirkšanas pieprasījumam

- **ProductIdentifier** — SKU, kuru klients mēģina iegādāties, nosaukums

- **ProvisioningHttpStatusCode** — nodrošināšanas http statusa kods

- **ProvisioningStatusCode** — nodrošināšanas statusa kods

- **PurchaseOrderId** — pirkšanas pasūtījuma identifikators no Google/Samsung veikala

- **RedemptionTaskHR** — HResult abonementa izpirkšanas uzdevumam

- **SubscriptionProvisioningSucceeded** — būla veiksmīgam abonementa nodrošināšanas rezultātam

- **SubscriptionPurchaseHR**— Hresult abonementa iegādes uzdevumam

- **SubscriptionType** — abonementa veida vai SKU uzskaitījums.

- **TCID** — noklikšķināšana uz ikonas uzsāk abonementa plūsmu

#### <a name="officeandroiddbfailurecause"></a>Office.Android.DBFailureCause

Kritisko kļūdu telemetrija datu bāzu kļūmei, pārlūkojot failus un pievienojot vietas.  Microsoft to izmanto, lai identificētu datu bāzu problēmas lietojumprogrammās, kas var traucēt lietotājam pievienot vietas vai pārlūkot tās lietojumprogrammās, izmantojot Word, Excel vai PowerPoint lietojumprogrammas. 

Tiek apkopoti šādi lauki:

- **ErrorAt** — atzīmes vērtība: informācija par vietu, kurā notika kļūme

- **ExceptionErrorMessage** — izvērsts kļūdas ziņojums

#### <a name="office_android_earlytelemetry_expansionfileserrors"></a>Office_Android_EarlyTelemetry_ExpansionFilesErrors

Android paplašināšanas failu komplekta (APK) paplašināšanas faili Office mobilajai lietojumprogrammai ir papildu resursu faili, kurus Android lietojumprogrammu izstrādātāji var publicēt kopā ar savu lietojumprogrammu. Lai padarītu mūsu paplašināšanas failu lejupielādes mehānismu par uzticamāku, mēs reģistrējam kļūdu iemeslus, kas rodas lejupielādējot paplašināšanas failus vai lasot lejupielādētos paplašināšanas failus.

Tiek apkopoti šādi lauki:

- **Data_ClassName** — teksts, kas norāda avota koda faila nosaukumu, kurā ir kļūda.

- **Data_ErrorMessage** — teksts, kas norāda neveiksmīgo darbību.

- **Data_ExceptionMessage** — neobligāts teksta lauks, kas norāda izņēmuma iemeslu.

- **Data_ExceptionType** — neobligāts teksta lauks, kas norāda izņēmumu, kas tiek izmests avota koda.

- **Data_MethodName** — teksts, kas norāda metodes nosaukumu avota kodā, kurā ir kļūda.

#### <a name="officeandroidearlytelemetrysharedlibraryloadersearchandloadlibraryerror"></a>Office.Android.EarlyTelemetry.SharedLibraryLoadersearchAndloadLibraryError 

Mēs reģistrējam šo notikumu gadījumā, ja ir rodas kļūdas, ielādējot koplietojamās bibliotēkas. Bibliotēkas ielādes kļūdas var notikt divu iemeslu dēļ: 1) instalētais APK nav saderīgs ar ierīci. 2) bibliotēka, ko mēģinām ielādēt var būt bojāta kļūdu, kas rodas izvēršanas kļūdu rezultātā, kuru iemesls ir vietas trūkums diskā vai atmiņas trūkums.

Tiek apkopoti tālāk norādītie lauki:

- **Data_ExceptionMessage** — izņēmuma ziņojums, kuru parāda Android API System.loadlibrary

- **Data_FreeSpaceInMB** — ierīcē pieejamā brīvā vieta

- **Data_nickName** — bibliotēkas, kuru neizdevās ielādēt, nosaukums.

#### <a name="officeandroidintuneintunejavacopyfailedattempts"></a>Office.Android.Intune.IntuneJavaCopyFailedAttempts

Kritisko kļūdu telemetriju, lai izsekotu neveiksmēm atsevišķiem Intune API; šī telemetrija tiek reģistrēta gadījumos, kad notiek kļūdas Intune aizsargāto mākoņa dokumentu lokālo kopiju saglabāšanā.  Microsoft izmanto šos datus, lai identificētu kļūdas, kas rodas Intune reģistrēšanas laikā lietojumprogrammā un pēc tās pēc pierakstīšanās lietojumprogrammā ar darba kontu

Tiek apkopoti šādi lauki:

- **Data_FileCreationFailedErrorCode** — ar plūsmu saistīts kļūdas kods

#### <a name="officeandroidintuneintunejavaexceptionadaltokenformam"></a>Office.Android.Intune.IntuneJavaExceptionADALTokenForMAM

Kritisko kļūdu telemetriju, lai izsekotu neveiksmēm atsevišķiem Intune API; šī telemetrija tiek reģistrēta gadījumos, kad notiek kļūdas mēģinot iegūt ADAL marķieri Intune resursiem.  Microsoft izmanto šos datus, lai identificētu kļūdas, kas rodas Intune reģistrēšanas laikā lietojumprogrammā pēc pierakstīšanās lietojumprogrammā ar darba kontu

Tiek apkopoti šādi lauki:

- **Data_ErrorCode** — ar plūsmu saistīts kļūdas kods

#### <a name="officeandroidintuneintunejavaexceptionapppolicy"></a>Office.Android.Intune.IntuneJavaExceptionAppPolicy

Kritisko kļūdu telemetriju, lai izsekotu neveiksmēm atsevišķiem Intune API; šī telemetrija tiek reģistrēta gadījumos, kad notiek kļūdas izsaucot Intune API, kas ir saistīti ar pašreizējā procesa identitātes ienešanas politikām.   Microsoft izmanto šos datus, lai identificētu kļūdas, kas rodas Intune reģistrēšanas laikā lietojumprogrammā un pēc tās pēc pierakstīšanās lietojumprogrammā ar darba kontu

Tiek apkopoti šādi lauki:
 
- Nav

#### <a name="officeandroidintuneintunejavaexceptionapppolicyforcontext"></a>Office.Android.Intune.IntuneJavaExceptionAppPolicyForContext

Kritisko kļūdu telemetriju, lai izsekotu neveiksmēm atsevišķiem Intune API; šī telemetrija tiek reģistrēta gadījumos, kad notiek kļūdas izsaucot Intune API, kas ir saistīti ar pašreizējās darbības identitātes ienešanas politikām.   Microsoft izmanto šos datus, lai identificētu kļūdas, kas rodas Intune reģistrēšanas laikā lietojumprogrammā un pēc tās pēc pierakstīšanās lietojumprogrammā ar darba kontu

Tiek apkopoti šādi lauki:
 
- Nav

#### <a name="officeandroidintuneintunejavaexceptionauthenticationcallback"></a>Office.Android.Intune.IntuneJavaExceptionAuthenticationCallback

Kritisko kļūdu telemetriju, lai izsekotu neveiksmēm atsevišķiem Intune API; šī telemetrija tiek reģistrēta gadījumos, kad notiek kļūdas izsaucot Intune API, kas ir saistīti ar reģistrāciju autentifikācijas atzvanīšanai pārvaldītajiem kontiem.  Microsoft izmanto šos datus, lai identificētu kļūdas, kas rodas Intune reģistrēšanas laikā lietojumprogrammā un pēc tās pēc pierakstīšanās lietojumprogrammā ar darba kontu

Tiek apkopoti šādi lauki:

- Nav

#### <a name="officeandroidintuneintunejavaexceptiongetaccountstatesync"></a>Office.Android.Intune.IntuneJavaExceptionGetAccountStateSync

Kritisko kļūdu telemetriju, lai izsekotu neveiksmēm atsevišķiem Intune API; šī telemetrija tiek reģistrēta gadījumos, kad notiek kļūdas izsaucot ar pārvaldīto kontu saistītajiem Intune API.  Microsoft izmanto šos datus, lai identificētu kļūdas, kas rodas Intune reģistrēšanas laikā lietojumprogrammā un pēc tās pēc pierakstīšanās lietojumprogrammā ar darba kontu

Tiek apkopoti šādi lauki:
 
- Nav

#### <a name="officeandroidintuneintunejavaexceptiongetissavetolocationallowed"></a>Office.Android.Intune.IntuneJavaExceptionGetIsSaveToLocationAllowed

Kritisko kļūdu telemetriju, lai izsekotu neveiksmēm atsevišķiem Intune API; šī telemetrija tiek reģistrēta gadījumos, kad notiek kļūdas ar saglabāšanu lokāli saistītajā ienešanas politikā.  Microsoft izmanto šos datus, lai identificētu kļūdas, kas rodas Intune reģistrēšanas laikā lietojumprogrammā un pēc tās pēc pierakstīšanās lietojumprogrammā ar darba kontu

Tiek apkopoti šādi lauki:

- Nav

#### <a name="officeandroidintuneintunejavaexceptiongetpolicyforidentity"></a>Office.Android.Intune.IntuneJavaExceptionGetPolicyForIdentity

Kritisko kļūdu telemetriju, lai izsekotu neveiksmēm atsevišķiem Intune API; šī telemetrija tiek reģistrēta gadījumos, kad notiek kļūdas izsaucot Intune API, kas ir saistīti ar identitātes ienešanas politikām.   Microsoft izmanto šos datus, lai identificētu kļūdas, kas rodas Intune reģistrēšanas laikā lietojumprogrammā un pēc tās pēc pierakstīšanās lietojumprogrammā ar darba kontu

Tiek apkopoti šādi lauki:

- Nav

#### <a name="officeandroidintuneintunejavaexceptiongetprotectioninfofromdescriptor"></a>Office.Android.Intune.IntuneJavaExceptionGetProtectionInfoFromDescriptor

Kritisko kļūdu telemetriju, lai izsekotu neveiksmēm atsevišķiem Intune API; šī telemetrija tiek reģistrēta gadījumos, kad notiek kļūdas izsaucot ar aizsardzības informāciju saistītajiem Intune API.  Microsoft izmanto šos datus, lai identificētu kļūdas, kas rodas Intune reģistrēšanas laikā lietojumprogrammā un pēc tās pēc pierakstīšanās lietojumprogrammā ar darba kontu

Tiek apkopoti šādi lauki:
  
- Nav

#### <a name="officeandroidintuneintunejavaexceptiongetprotectioninfofrompath"></a>Office.Android.Intune.IntuneJavaExceptionGetProtectionInfoFromPath

Kritisko kļūdu telemetriju, lai izsekotu neveiksmēm atsevišķiem Intune API; šī telemetrija tiek reģistrēta gadījumos, kad notiek kļūdas izsaucot ar aizsardzības informāciju saistītajiem Intune API.  Microsoft izmanto šos datus, lai identificētu kļūdas, kas rodas Intune reģistrēšanas laikā lietojumprogrammā un pēc tās pēc pierakstīšanās lietojumprogrammā ar darba kontu

Tiek apkopoti šādi lauki:

- Nav

#### <a name="officeandroidintuneintunejavaexceptiongetuipolicyidentity"></a>Office.Android.Intune.IntuneJavaExceptionGetUIPolicyIdentity

Kritisko kļūdu telemetriju, lai izsekotu neveiksmēm atsevišķiem Intune API; šī telemetrija tiek reģistrēta gadījumos, kad notiek kļūdas izsaucot Intune API, kas ir saistīti ar pārvaldītā konta lietotāja interfeisa politiku ienešanu.   Microsoft izmanto šos datus, lai identificētu kļūdas, kas rodas Intune reģistrēšanas laikā lietojumprogrammā un pēc tās pēc pierakstīšanās lietojumprogrammā ar darba kontu

Tiek apkopoti šādi lauki:

- Nav

#### <a name="officeandroidintuneintunejavaexceptionisidentitymanaged"></a>Office.Android.Intune.IntuneJavaExceptionIsIdentityManaged

Kritisko kļūdu telemetriju, lai izsekotu neveiksmēm atsevišķiem Intune API; šī telemetrija tiek reģistrēta gadījumos, kad notiek kļūdas izsaucot Intune API, kas ir saistīti ar konta pārvaldības identificēšanu.  Microsoft izmanto šos datus, lai identificētu kļūdas, kas rodas Intune reģistrēšanas laikā lietojumprogrammā un pēc tās pēc pierakstīšanās lietojumprogrammā ar darba kontu.

Tiek apkopoti šādi lauki:

- Nav

#### <a name="officeandroidintuneintunejavaexceptionnullenrollmentmanager"></a>Office.Android.Intune.IntuneJavaExceptionNullEnrollmentManager

Kritisko kļūdu telemetriju, lai izsekotu neveiksmēm atsevišķiem Intune API; šī telemetrija tiek reģistrēta gadījumos, kad notiek kļūdas izsaucot Intune API, kas ir saistīti ar komponentu reģistrāciju atzvanīšanai.  Microsoft izmanto šos datus, lai identificētu kļūdas, kas rodas Intune reģistrēšanas laikā lietojumprogrammā un pēc tās pēc pierakstīšanās lietojumprogrammā ar darba kontu

Tiek apkopoti šādi lauki:

- Nav

#### <a name="officeandroidintuneintunejavaexceptionprotect"></a>Office.Android.Intune.IntuneJavaExceptionProtect

Kritisko kļūdu telemetriju, lai izsekotu neveiksmēm atsevišķiem Intune API; šī telemetrija tiek reģistrēta gadījumos, kad notiek kļūdas izsaucot ar pārvaldītā dokumenta aizsardzību saistītajiem Intune API.  Microsoft izmanto šos datus, lai identificētu kļūdas, kas rodas Intune reģistrēšanas laikā lietojumprogrammā un pēc tās pēc pierakstīšanās lietojumprogrammā ar darba kontu.

Tiek apkopoti šādi lauki:

- Nav

#### <a name="officeandroidintuneintunejavaexceptionprotectfromdescriptorifrequired"></a>Office.Android.Intune.IntuneJavaExceptionProtectFromDescriptorIfRequired

Kritisko kļūdu telemetriju, lai izsekotu neveiksmēm atsevišķiem Intune API; šī telemetrija tiek reģistrēta gadījumos, kad notiek kļūdas izsaucot ar pārvaldītā dokumenta aizsardzību saistītajiem Intune API.  Microsoft izmanto šos datus, lai identificētu kļūdas, kas rodas Intune reģistrēšanas laikā lietojumprogrammā un pēc tās pēc pierakstīšanās lietojumprogrammā ar darba kontu

Tiek apkopoti šādi lauki:

- Nav

#### <a name="officeandroidintuneintunejavaexceptionregisteraccountsync"></a>Office.Android.Intune.IntuneJavaExceptionRegisterAccountSync

Kritisko kļūdu telemetriju, lai izsekotu neveiksmēm atsevišķiem Intune API; šī telemetrija tiek reģistrēta gadījumos, kad notiek kļūdas izsaucot Intune API, kas ir saistīti ar Intune Management konta reģistrāciju.  Microsoft izmanto šos datus, lai identificētu kļūdas, kas rodas Intune reģistrēšanas laikā lietojumprogrammā un pēc tās pēc pierakstīšanās lietojumprogrammā ar darba kontu

Tiek apkopoti šādi lauki:

- Nav

#### <a name="officeandroidintuneintunejavaexceptionsetuipolicyidentitysync"></a>Office.Android.Intune.IntuneJavaExceptionSetUIPolicyIdentitySync

Kritisko kļūdu telemetriju, lai izsekotu neveiksmēm atsevišķiem Intune API; šī telemetrija tiek reģistrēta gadījumos, kad notiek kļūdas izsaucot Intune API, kas ir saistīti ar iestatījumu politikām pārvaldītajam konta.  Microsoft izmanto šos datus, lai identificētu kļūdas, kas rodas Intune reģistrēšanas laikā lietojumprogrammā un pēc tās pēc pierakstīšanās lietojumprogrammā ar darba kontu

Tiek apkopoti šādi lauki:

- Nav

#### <a name="officeandroidintuneintunejavaexceptionunregisteraccountsync"></a>Office.Android.Intune.IntuneJavaExceptionUnregisterAccountSync

Kritisko kļūdu telemetriju, lai izsekotu neveiksmēm atsevišķiem Intune API; šī telemetrija tiek reģistrēta gadījumos, kad notiek kļūdas izsaucot Intune API, kas ir saistīti ar Intune Management attālinātās dzēšanas scenārijiem.  Microsoft izmanto šos datus, lai identificētu kļūdas, kas rodas Intune reģistrēšanas laikā lietojumprogrammā un pēc tās pēc pierakstīšanās lietojumprogrammā ar darba kontu

Tiek apkopoti šādi lauki:

- Nav

#### <a name="officeandroidintuneintunejavaexceptionupdatetoken"></a>Office.Android.Intune.IntuneJavaExceptionUpdateToken

Kritisko kļūdu telemetriju, lai izsekotu neveiksmēm atsevišķiem Intune API; šī telemetrija tiek reģistrēta gadījumos, kad notiek kļūdas izsaucot Intune API, kas ir saistīti ar pārvaldītā konta atjaunināšanas autorizācijas marķieri.  Microsoft izmanto šos datus, lai identificētu kļūdas, kas rodas Intune reģistrēšanas laikā lietojumprogrammā un pēc tās pēc pierakstīšanās lietojumprogrammā ar darba kontu

Tiek apkopoti šādi lauki:

- Nav

#### <a name="officeandroidlicenseactivationfailure"></a>Office.Android.LicenseActivationFailure

Kritisko kļūdu telemetrija, kas tiek izmantota Office 365 kontu Word, Excel vai PowerPoint lietojumprogrammās licencēšanas aktivizēšanas kļūmju izsekošanai.  Microsoft to izmanto, lai analizētu iegādāto Office 365 licenču aktivizēšanas kļūmes.

Tiek apkopoti šādi lauki:

- **EntryPoint** — ieejas punkta uzskaitījums licenču aktivizēšanas plūsmas aktivizēšanai

- **HResult** — kļūmes kļūdas kods

- **IsGallatin** — būla, kas tiek izmantota, lai pārbaudītu, vai tas ir Gallatin konts

- **MessageCode**— uzskaitījums, kas norāda aktivizēšanas kļūmes punktu

- **PreviousEntryPoint** — ieejas punkta uzskaitījums licenču aktivizēšanas plūsmas aktivizēšanai

- **StateAfterActivation** — uzskaitījums, kas norāda lietojumprogrammas licencēšanas stāvokli pirms aktivizēšanas plūsmas sākuma

- **StateBeforeActivation** — uzskaitījums, kas norāda lietojumprogrammas licencēšanas stāvokli pirms aktivizēšanas plūsmas sākuma

- **UserAccountType** — uzskaitījums, kas norāda, vai konts ir personiskais vai uzņēmuma konts.

#### <a name="officeandroidmsasigninuiprompts"></a>Office.Android.MSASignInUIPrompts

Šīs notikums norāda, ka lietotājs saņēma pierakstīšanās uzvedni personiskajam kontam.  Šis notikums palīdz saprast mūsu lietojumprogrammu pierakstīšanās stāvokļa darbspēju un atbilstoši rīkoties, kad pamanām neparedzētas pierakstīšanās uzvednes. 

Tiek apkopoti tālāk norādītie lauki:

- **ExternalCacheRefreshError** — marķiera atsvaidzināšanas mēģinājuma pirms pierakstīšanās uzvednes parādīšanas kļūdas kods.

- **LastLoginDelta** — laika delta no pēdējās sekmīgās pieteikšanās.

- **MSAserverUAID** — korelācijas ID ar pakalpojuma telemetrijas datiem.

- **PreviousIdentityState** — norāda konta stāvokli, piemēram, sesijas laiks beidzies. 

- **SignInResultCode** — norāda pierakstīšanās uzvednes beigu rezultātā kodu.

- **UseCache**— norāda, vai mēs ar uzvednes palīdzību likām lietotājam ievadīt paroli atkārtoti.

- **UserType** — norāda, vai tas ir esošs konts vai jauns konts

- **WasIdentitySignedOut** — norāda, vai konts bija izrakstīšanās stāvoklī.


#### <a name="office_apple_licensing_mac_dractivationfailures"></a>Office_Apple_Licensing_Mac_DRActivationFailures

Šo notikumu apkopo Office programmām, kas tiek lietotas Apple platformās. Pasākums tiek lietots Digital River aktivizēšanas kļūmju novēršanai (notikums reģistrē galveno un produktu, kas tika lietots aktivizācijai, kā arī saņemtās kļūdas kodu).  Šis notikums tiek lietots, lai noteiktu un palīdzētu novērst aktivizācijas kļūmes (Digital River problēmas).

Tiek apkopoti šādi lauki:

- **Data_DigitalRiverID** — Digital River produkta ID, kas kartē uz šo Office produkta SKY

- **Data_Error** — virkne, kas norāda aktivizācijas kļūdas kodu.

- **Data_ProductKey** — produkta atslēga, ko bija mēģināts aktivizēt

- **Data_ProductKeyHash** — aktivizēta kodētā produkta atslēga

#### <a name="office_apple_licensing_mac_getmachinestatuserrors"></a>Office_Apple_Licensing_Mac_GetMachineStatusErrors

Šo notikumu apkopo Office programmām, kas tiek lietotas Apple platformās. Pasākums apkopo kļūdas kodu, kas tiek atgriezts, periodiski pārbaudot abonementa licences derīgumu. Kļūdas kods var nozīmēt servera nepieejamību, kā arī licenču derīguma beigu datumu, datoru skaita ierobežojumu, uaparatūras ID utt.  Šis notikums tiek lietots, lai pārraudzītu Office licencēšanas pakalpojuma darbspēju, kā arī izmeklētu problēmas, kas saistītas ar abonementu datoru pārvaldību.

Tiek apkopoti šādi lauki:

- **Data_Error** — mēs apkopojam virkni, kas norāda kļūdas kodu.

#### <a name="officeextensibilitysandboxodperrornotification"></a>Office.Extensibility.Sandbox.ODPErrorNotification

Izseko dažādus no smilškastes saņemtos kļūdu paziņojumus. Izmanto, lai atklātu un labotu kļūdu scenārijus smilškastē, uzlabojot lietotāja produktivitāti. 
 
Tiek apkopoti tālāk norādītie lauki.

- **AppId** — lietojumprogrammas ID.

- **AppUrl** — notīrītais lietojumprogrammas URL. 

- **Result** — rezultāta kļūdas kods.

#### <a name="office_firstrun_apple_maconiolkfirstrunstarted"></a>Office_FirstRun_Apple_MacONIOLKFirstRunStarted

Šo notikumu apkopo Office programmām, kas tiek lietotas Apple platformās. Šis pasākums mūs informē, ka lietotājs ir veicis pirmo palaišanas pieredzi. Šis notikums tiek izmantots, lai noskaidrotu, vai pirmā palaišanas pieredze (PPP) tika sākta sekmīgi.

Tiek apkopoti šādi lauki:

- **Data_FirstRunCollectionTime** — laikspiedols, kas reģistrē laiku, kad plūsma tika sākta.

#### <a name="officegraphicsarcexceptions"></a>Office.Graphics.ARCExceptions 

Šī izņēmuma uzrādītā informācija ir svarīga, lai izvērtētu kopējo grafikas steka darbspēju, kā arī identificētu tās koda daļas, kur kļūmes radās ar lielu intensitāti, lai noteiktu izmeklēšanas prioritātes. Šī izņēmuma uzrādītā informācija ir svarīga, lai izvērtētu kopējo grafikas steka darbspēju, kā arī identificētu tās koda daļas, kur kļūmes radās ar lielu intensitāti. Tas palīdz inženierim noteikt, kuras atveidošanas kļūmes ietekmē lielāko daļu lietotāju, lai mēs varētu noteikt prioritātes mūsu ieguldījumiem, vēršot tos uz tādu problēmu novēršanu, kas lietotājiem sniegs vislielāko ieguvumu.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_HResult** — kļūmes atgrieztais kļūdas kods

  - **Data\_TagCount** — katras radušās kļūmes skaits

  - **Data\_TagID** — radušās kļūmes identifikators

#### <a name="officeoutlookdesktopcalendaracceptcalsharenavigatetosharedfolder_error"></a>Office.Outlook.Desktop.Calendar.AcceptCalShareNavigateToSharedFolder\_Error

Apkopo informāciju, kad rodas kļūme, veicot navigāciju uz koplietoto kalendāru. Šie dati tiek izmantoti, lai pārraudzītu kalendāra koplietošanas API darbspēju, kā arī Outlook mijiedarbību ar koplietojamajiem kalendāriem.

Tiek apkopoti tālāk norādītie lauki.

  - **FailedCaseHResult** — kļūmes atgrieztais kļūdas kods

#### <a name="officeoutlookdesktopedpedpopenstorefailure"></a>Office.Outlook.Desktop.EDP.EDPOpenStoreFailure

Sekmīga vai nesekmīga ar uzņēmuma datu aizsardzību aizsargātas pasta krātuves atvēršana, pamatojoties uz Windows API izsaukuma rezultātu, lai iegūtu atslēgu krātuves atšifrēšanai. Mēs to izmantojam, lai diagnosticētu vienu no biežāk sastopamajām uzņēmuma datu aizsardzības problēmām, kas var novērst Outlook startēšanu. Primārais kļūmes iemesls ir Outlook mijiedarbība ar Windows API, kas tiek izmantots, lai atšifrētu krātuves atslēgu.

Tiek apkopoti tālāk norādītie lauki.

  - **HVA Activity** **-** ar pielāgotiem datu laukiem

  - **IsFlightOn** — norāda, vai ir iespējots EDPDecryption izmēģinājums

#### <a name="officeoutlookdesktopndbcorruptionresult"></a>Office.Outlook.Desktop.NdbCorruptionResult

Office.Outlook.Desktop.NdbCorruptionResult un Office.Outlook.Desktop.NDBCorruptStore.Warning tiek apkopoti, kad mēs konstatējam bojājumu lietotāja PST/OST. Kad mēs konstatējam bojājumu, korporācija Microsoft apkopo informāciju par datu bāzes formātu, vietu, kur bojājums tika konstatēts, un nelielu kontekstinformāciju par bojājumu. OST/PST bojājums neļauj lietotājiem piekļūt saviem e-pasta ziņojumiem. Mēs aktīvi pārraugām šos datus, lai konstatētu nepareizu darbību. Mēs strādājam pie tā, lai izpētītu un diagnosticētu problēmas un ierobežotu klientu datu zudumu.

Tiek apkopoti tālāk norādītie lauki.

  - **0 —** procesa nosaukums, kas ziņoja par bojājumu

  - **1 —** Būla virkne, kas norāda, vai lietotājs izvēlas jaunu failu

  - **2 —** citu procesu skaits, kuros ir atvērta datu bāze

#### <a name="officeoutlookdesktopndbcorruptstorewarning"></a>Office.Outlook.Desktop.NDBCorruptStore.Warning

Office.Outlook.Desktop.NdbCorruptionResult un Office.Outlook.Desktop.NDBCorruptStore.Warning tiek apkopoti, kad mēs konstatējam bojājumu lietotāja PST/OST. Kad mēs konstatējam bojājumu, korporācija Microsoft apkopo informāciju par datu bāzes formātu, vietu, kur bojājums tika konstatēts, un nelielu kontekstinformāciju par bojājumu. OST/PST bojājums neļauj lietotājiem piekļūt saviem e-pasta ziņojumiem. Mēs aktīvi pārraugām šos datus, lai konstatētu nepareizu darbību. Mēs strādājam pie tā, lai izpētītu un diagnosticētu problēmas un ierobežotu klientu datu zudumu.

Tiek apkopoti tālāk norādītie lauki.

  - **CollectionTime** — apkopošanas laiks

  - **Context** — bojātas krātuves konteksts, kur tika konstatēts bojājums

  - **CreatedWithVersion** — (neobligāts) lauks ar krātuves versiju

  - **Details** — detalizēta informācija par avāriju

  - **NdbType** — krātuves tips, var būt 0 = NdbUndefined, 1 = NdbSmall, 2 = NdbLarge, 3 = NdbTardis

  - **ProcesaNosaukums** — darbības vārdu dēļ veikalā sabojātas

  - **PstVersion** — MSPST32.DLL versija

  - **Version** — krātuves faila formāta versija

#### <a name="officeoutlookdesktopoutlookcalendarusageerrmeetrcptforwardactionsruleo16"></a>Office.Outlook.Desktop.OutlookCalendarUsageErr.MeetRcpt.ForwardActions.Rule.O16

Apkopo sekmīgas un nesekmīgas darbību Pārsūtīt, Pārsūtīt kā pielikumu un Pārsūtīt kā iCalendar izpildes reizes atsevišķām, periodiskām un izņēmuma sapulces atbildēm pasta, kalendāra un kontroliera Outlook skatā. Darbību Pārsūtīt, Pārsūtīt kā pielikumu un Pārsūtīt kā iCalendar nesekmīgas izpildes biežums tiek aktīvi pārraudzīts, lai konstatētu anomālijas. Anomāla statistika norāda par kļūmi, kad Outlook nespēj veikt pamata kalendāra darbības. Šos datus izmanto arī, lai diagnosticētu citas ar kalendāru saistītas problēmas, kas var tikt konstatētas.

Tiek apkopoti tālāk norādītie lauki.

  - **CountExceptionForward** — pārsūtīto sapulces izņēmumu skaits.

  - **CountExceptionForwardAsiCal** — pārsūtīto sapulces izņēmumu kā iCal skaits.

  - **CountExceptionForwardInSplit** — pārsūtīto sapulces izņēmumu skaits no sadalīšanas izvēlnes lentē.

  - **CountExceptionForwardWithAttach** — pārsūtīto sapulces izņēmumu kā pielikumu skaits.

  - **CountRecurringForward** — pārsūtīto periodisko sapulču skaits.

  - **CountRecurringForwardAsiCal** — pārsūtīto periodisko sapulču kā iCal skaits.

  - **CountRecurringForwardInSplit** — pārsūtīto periodisko sapulču skaits no sadalīšanas izvēlnes lentē.

  - **CountRecurringForwardWithAttach** — pārsūtīto periodisko sapulču kā pielikumu skaits.

  - **CountSingleForward** — pārsūtīto atsevišķo sapulču skaits.

  - **CountSingleForwardAsiCal** — pārsūtīto atsevišķo sapulču kā iCal skaits.

  - **CountSingleForwardInSplit** — pārsūtīto atsevišķo sapulču skaits no sadalīšanas izvēlnes lentē.

  - **CountSingleForwardWithAttach** — pārsūtīto atsevišķo sapulču kā pielikumu skaits.

  - **HResult** — kļūdas kods.

  - **OlkViewName** — norāda pasta, kalendāra vai kontroliera skatu.

#### <a name="officeoutlookdesktopoutlookcalendarusageerrmeetrcptreplyactionsruleo16"></a>Office.Outlook.Desktop.OutlookCalendarUsageErr.MeetRcpt.ReplyActions.Rule.O16

Apkopo sekmīgas un nesekmīgas darbību Atbildēt, Atbildēt visiem, Atbildēt ar IM un Atbildēt visiem ar IM izpildes reizes atsevišķām, periodiskām un izņēmuma sapulces atbildēm pasta, kalendāra un kontroliera Outlook skatā. Darbību Atbildēt, Atbildēt visiem, Atbildēt ar IM un Atbildēt visiem ar IM tiek aktīvi pārraudzītas, lai konstatētu anomālijas. Anomāla statistika norāda par kļūmi, kad Outlook nespēj veikt pamata kalendāra darbības. Šos datus izmanto arī, lai diagnosticētu citas ar kalendāru saistītas problēmas, kas var tikt konstatētas.

Tiek apkopoti tālāk norādītie lauki.

  - **CountExceptionReply** — izņēmuma sapulces atbilžu skaits.

  - **CountExceptionReplyAll** — izņēmuma sapulces atbilžu visiem skaits.

  - **CountExceptionReplyAllWithIM** — izņēmuma sapulces atbilžu visiem ar IM skaits.

  - **CountExceptionReplyWithIM** — izņēmuma sapulces atbilžu ar IM skaits.

  - **CountRecurringReply** — periodiskas sapulces atbilžu skaits.

  - **CountRecurringReplyAll** — periodiskas sapulces atbilžu visiem skaits.

  - **CountRecurringReplyAllWithIM** — periodiskas sapulces atbilžu visiem ar IM skaits.

  - **CountRecurringReplyWithIM** — periodiskas sapulces atbilžu ar IM skaits.

  - **CountSingleReply** — atsevišķas sapulces atbilžu skaits.

  - **CountSingleReplyAll** — atsevišķas sapulces atbilžu visiem skaits.

  - **CountSingleReplyAllWithIM** — atsevišķas sapulces atbilžu visiem ar IM skaits.

  - **CountSingleReplyWithIM** — atsevišķas sapulces atbilžu ar IM skaits.

  - **HResult** — kļūdas kods.

  - **OlkViewName** — norāda pasta, kalendāra vai kontroliera skatu.

#### <a name="officeoutlookdesktopoutlookprivsdlgsingleuserloadfail"></a>Office.Outlook.Desktop.OutlookPrivsDlgSingleUser.LoadFail

Šī kārtula apkopo kalendāra koplietošanas kļūdas, pievienojot lietotāju (EX vai SMTP tips) no adrešu grāmatas. Šie dati tiek izmantoti, lai diagnosticētu un novērstu problēmas, kas konstatētas dialoglodziņā Kalendāra koplietošana

Tiek apkopoti tālāk norādītie lauki.

  - **CountAccountWizardEnd** — cik reizes tika izbeigts mantotā vedņa dialoglodziņš

  - **CountCreatePIMAccount** — cik reizes lietotājs ir izveidojis PIM profilu

#### <a name="officeoutlookmacmacolkasserts"></a>Office.Outlook.Mac.MacOLKAsserts

Izmanto, lai identificētu problēmas Outlook, kas ietekmē lietotāju un var izpausties kā avārijas vai pasliktināta veiktspēja. 

Tiek apkopoti tālāk norādītie lauki.

- **Category** — apliecinājuma veids.

- **CollectionTime** — apliecinājuma apkopošanas laiks.


#### <a name="officeoutlookmacmacolkerrors"></a>Office.Outlook.Mac.MacOLKErrors

Izmanto, lai identificētu problēmas Outlook, kas ietekmē lietotāju un var izpausties kā avārijas vai pasliktināta veiktspēja. 

Tiek apkopoti tālāk norādītie lauki.

- **Category** — kļūdas veids.

- **CollectionTime** — kļūdas apkopošanas laiks.

- **ThreadId** — pavediena identifikators.


#### <a name="officesystemsystemhealthasserts"></a>Office.System.SystemHealthAsserts

Šī notikuma konstatētās kļūdas palīdz mums izprast, kad ir pasliktināta klienta lietošanas pieredze. Daudzas no šīm ShipAsserts darbībām izraisa avārijas, un šī informācija ļauj izlabot daudzas no šīm problēmām. Apkopo ShipAsserts no produkta, kas palīdz konstatēt kļūdas.

Tiek apkopoti tālāk norādītie lauki.

 - **Count** – uzrādīto apliecinājumu skaits.

  - **EndTime** — laiks, kad radās pēdējais uzrādītais apliecinājums

  - **ErrorGroup** — katra apliecinājuma intervāla identifikators

  - **FirstTimeStamp** — pirmā reize, kad radās apliecinājums

  - **Trackback** — konkrēta apliecinājuma unikālais identifikators

#### <a name="officesystemsystemhealtherrorsetwshim"></a>Office.System.SystemHealthErrorsEtwShim

Izmanto, lai noteiktu klientu ietekmējošas problēmas darbībā esošajā programmā, kas var izpausties kā avārijas vai samazināta funkcionalitāte. Reģistrē kļūdas, kas rodas, procesa izpildlaikā.

Tiek apkopoti tālāk norādītie lauki.

  - **EndTime** — laiks, kad radās pēdējā uzrādītā kļūda

  - **Trackback** — konkrētas kļūdas unikālais identifikators

  - **ErrorGroup** — katras kļūdas intervāla identifikators

  - **Count** — kļūdu skaits

  - **FirstTimeStamp** — pirmā reize, kad radās kļūda

#### <a name="officesystemsystemhealtherrorsulsandasserts"></a>Office.System.SystemHealthErrorsUlsAndAsserts

Izmanto, lai noteiktu klientu ietekmējošas problēmas darbībā esošajā programmā, kas var izpausties kā avārijas vai samazināta funkcionalitāte. Reģistrē kļūdas, kas rodas, procesa izpildlaikā.

Tiek apkopoti tālāk norādītie lauki.

  - **EndTime** — laiks, kad radās pēdējā uzrādītā kļūda

  - **Trackback** — konkrētas kļūdas unikālais identifikators

  - **ErrorGroup** — katras kļūdas intervāla identifikators

  - **Count** — kļūdu skaits

  - **FirstTimeStamp** — pirmā reize, kad radās kļūda

#### <a name="officesystemsystemhealtherrorsulsworkaround"></a>Office.System.SystemHealthErrorsUlsWorkaround

Izmanto, lai noteiktu klientu ietekmējošas problēmas darbībā esošajā programmā, kas var izpausties kā avārijas vai samazināta funkcionalitāte. Reģistrē kļūdas, kas rodas, procesa izpildlaikā.

Tiek apkopoti tālāk norādītie lauki.

  - **EndTime** — laiks, kad radās pēdējā uzrādītā kļūda

  - **Trackback** — konkrētas kļūdas unikālais identifikators

  - **ErrorGroup** — katras kļūdas intervāla identifikators

  - **Count** — kļūdu skaits

#### <a name="officesystemsystemhealtherrorswithouttag"></a>Office.System.SystemHealthErrorsWithoutTag

Izmanto, lai noteiktu klientu ietekmējošas problēmas darbībā esošajā programmā, kas var izpausties kā avārijas vai samazināta funkcionalitāte. Reģistrē kļūdas, kas rodas, procesa izpildlaikā.

Tiek apkopoti tālāk norādītie lauki.

Count — kļūdu skaits

  - **EndTime** — laiks, kad radās pēdējā uzrādītā kļūda

  - **ErrorCode** — kļūdas identifikators

  - **ErrorGroup** — katras kļūdas intervāla identifikators

  - **ErrorId** — kļūdas identifikators

  - **FirstTimeStamp** — pirmā reize, kad radās kļūda

  - **Trackback** — konkrētas kļūdas unikālais identifikators

#### <a name="officesystemsystemhealtherrorswithtag"></a>Office.System.SystemHealthErrorsWithTag

Izmanto, lai noteiktu klientu ietekmējošas problēmas darbībā esošajā programmā, kas var izpausties kā avārijas vai samazināta funkcionalitāte. Reģistrē kļūdas, kas rodas, procesa izpildlaikā.

Tiek apkopoti tālāk norādītie lauki.

  - **Count** — kļūdu skaits

  - **EndTime** — laiks, kad radās pēdējā uzrādītā kļūda

  - **ErrorCode** — kļūdas identifikators

  - **ErrorGroup** — katras kļūdas intervāla identifikators

  - **ErrorId** — kļūdas identifikators

  - **FirstTimeStamp** — pirmā reize, kad radās kļūda

  - **Trackback** — konkrētas kļūdas unikālais identifikators

#### <a name="renewidentityfailure"></a>RenewIdentityFailure

Tiek apkopots, kad lietotājs mēģina atvērt ar IRM aizsargātu dokumentu vai lietot IRM aizsardzību. Tas satur informāciju, kas ir nepieciešama pareizai tādu problēmu izmeklēšanai un diagnosticēšanai, kas notiek, kad neizdodas lietotāja sertifikātu atjaunošana.

Tiek apkopoti tālāk norādītie lauki.

- **AppInfo.ClientHierarchy** — klienta hierarhija, kas norāda, ka lietojumprogramma darbojas ražošanas vidē vai izstrādātāja vidē

- **AppInfo.Name** — lietojumprogrammas nosaukums

- **AppInfo.Version** — lietojumprogrammas versija

- **Failure.Category** — kļūmes kategorija "UnhandledError"

- **Failure.Detail** — detalizēta informācija par kļūmi

- **Failure.Id** — kļūmes ID

- **Failure.Signature** — kļūmes paraksts, kas ir tāds pats kā notikuma nosaukums

- **iKey** — pieteikšanās pakalpojuma servera ID

- **RMS.HRESULT** — lietotāja sertifikāta atjaunošanas rezultāts

- **RMS.ScenarioId** — scenārija ID, ko definē tiesību pārvaldības pakalpojuma klients

- **RMS.SDKVersion** — tiesību pārvaldības pakalpojuma klienta versija

#### <a name="save_error"></a>save_error

Ļauj mums atklāt un novērst situācijas, kad kļūda notiek brīdī, kad mēģinājāt saglabāt failu.  Izseko kļūdām, kuru cēlonis ir failu saglabāšanas kļūmes, iekļaujot aprakstošos kļūdu ziņojumus, kas mums palīdz atrisināt problēmu.

Tiek apkopoti šādi lauki: 

- **error** — notikušās kļūdas tips, kas palīdz mums atklāt un atrisināt problēmas, kas ir saistītas ar konkrētu kļūdas tipu

- **file_type** — faila tips, ko lietotājs mēģināja saglabāt (piemēram,. doc)

- **origin** — norāda faila saglabāšanas mēģinājuma izcelsmi (piemēram, no e-pasta), ļaujot mums noteikt ar failu saglabāšanu konkrētajā vietā lietojumprogrammā saistītās problēmas

- **token_type** — faila saglabāšanai veiktās konta autentifikācijas marķiera veids, lai palīdzētu mums atklāt ar faila saglabāšanu saistītās autentifikācijas problēmas


## <a name="device-connectivity-and-configuration-data-events"></a>Ierīču savienojamības un konfigurācijas datu notikumi

Tālāk ir norādīti šīs kategorijas datu apakštipi.

- [Ierīču savienojamība un konfigurācija](#device-connectivity-and-configuration-subtype)


### <a name="device-connectivity-and-configuration-subtype"></a>*Ierīču savienojamības un konfigurācijas apakštips*

Tīkla savienojuma statuss un ierīces iestatījumi, piemēram, atmiņas iestatījumi.

#### <a name="application_did_receive_memory_warning"></a>application_did_receive_memory_warning

Šis notikums tiek sūtīts, kad Apple norāda uz to, ka lietojumprogrammā sāk pietrūkt atmiņas. Tas norāda mums uz to, ka mērs jūsu ierīcē radījām atmiņas pārvaldības problēmu.

Tiek apkopoti šādi lauki: 

- **current_memory_used** — norāda uz lietojumprogrammas izmantotās atmiņas apjomu brīdī, kad lietojumprogrammā beidzās atmiņa.

- **current_memory_used_percentage** — norāda uz lietojumprogrammas izmantotās atmiņas daudzumu procentu izteiksmē no kopējā pieejamā atmiņas apjoma brīdī, kad lietojumprogrammā beidzās atmiņa.

- **currentVC** — norāda, kurš skats tika rādīts brīdī, kad lietojumprogrammā beidzās atmiņa.

- **has_hx** — norāda, vai konts izmanto jauno sinhronizācijas pakalpojumu, lai palīdzētu noteikt mūsu sinhronizācijas pakalpojuma radītās problēmas

- **is_watch_app_installed** — norāda, vai lietotājs pašlaik izmanto Apple Watch un vai tas ir instalēts, lai palīdzētu mums izprast pulksteņa radīto negatīvo ietekmi uz veiktspēju

- **is_watch_paired** — norāda, vai lietotājs pašlaik izmanto Apple Watch un vai tas ir savienots ar ierīci, lai palīdzētu mums noteikt Apple Watch radīto negatīvo ietekmi uz veiktspēju

- **is_watch_supported_and_active** — norāda, vai lietotājs pašlaik izmanto Apple Watch un vai tas ir aktīvs, lai palīdzētu mums izprast pulksteņa radīto negatīvo ietekmi uz veiktspēju

- **rn_initialized** — norāda, vai brīdī, kad lietojumprogrammā beidzās atmiņa, tika inicializēts vietējais reaģēšanas modulis.

- **running_time** — norāda uz laiku, ko lietojumprogrammai pavadīja darbībā brīdī, kad lietojumprogrammā beidzās atmiņa.

#### <a name="conversation_memory_leak"></a>conversation_memory_leak

Ļauj mums noteikt situācijas, kurās mūsu e-pasta sarunas skata dēļ tiek izmantots lielāks jūsu ierīces atmiņas apjoms nekā paredzēts.

Tiek apkopoti šādi lauki:

- Lauki vai pievienotie dati netiek apkopoti. Ja atmiņas noplūde ir saistīta ar sarunas pavedienu, tiek apkopoti tikai žurnāli.

#### <a name="core_data_corruption"></a>core_data_corruption

Ļauj mums noteikt situācijas, kad mēs nevaram jums parādīt jūsu e-pastu vai kalendāru, jo krātuve jūsu ierīcē, kurā mēs glabājam jūsu e-pastu, ir bojāta.

Tiek apkopoti šādi lauki:

- **errorSource** — norāda, vai kļūdas izcēlās no saglabāšanas vai izveidošanas darbības

- **sqlError** — skaitlisks kļūdas kods, kas norādīts https://www.sqlite.org/c3ref/c_abort.html

#### <a name="core_data_corruption_user_reset"></a>core_data_corruption_user_reset

Ļauj mums noteikt situācijas, kad jūs dzēsāt vai atiestatījāt savu kontu mūsu lietotnē, kā iemesls bija e-pasta datu, kurus mēs saglabājām jūsu ierīcē, bojājumi.

Tiek apkopoti šādi lauki:

- **errorSource** — norāda, kur ir noticis bojājums, vai saglabāšanas vai izveidošanas laikā

#### <a name="core_data_diagnostics"></a>core_data_diagnostics 

Ļauj mums noteikt un novērst situācijas, kad mūsu e-pasta glabātuve izmanto pārāk lielu jūsu ierīces krātuves vietas apjomu

Tiek apkopoti šādi lauki:

- **db_size_megabytes** — izseko pamatdatu datubāzes izmēram, kas ir noapaļots līdz tuvākajiem 25 megabaitiem, ar maksimālo megabaitu 500

#### <a name="general_properties_log"></a>general_properties_log

Šis notikums apkopo informāciju, kas ļauj mums kategorizēt un klasificēt Outlook lietojumprogrammas problēmas, kas ir saistītas ar pieejamības un ierīces iestatījumiem.  Šī kategorizācija ir nepieciešama, lai noteiktu problēmu ietekmes uz klientiem līmeni.

Tālāk norādītie lauki tiek apkopoti tikai iOS:

- **bold_text** — norāda, vai ierīcei ir ieslēgts treknraksta teksts, lai palīdzētu mums atklāt treknraksta tekstu saistītās problēmas

- **closed_captioning** — norāda, vai lietotājs ir ieslēdzis slēptos titrus savā ierīcē, lai palīdzētu mums atklāt ar slēptajiem titriem saistītās problēmas

- **darker_system_colors** — norāda, vai lietotājs ir ieslēdzis tumšākas sistēmas krāsas savā ierīcē, lai palīdzētu mums noteikt ar šo iestatījumu saistītās problēmas

- **gray_scale** — norāda, vai lietotājs ir ieslēdzis pelēktoņu sistēmas krāsas savā ierīcē, lai palīdzētu mums noteikt ar šo iestatījumu saistītās problēmas

- **guided_access** — norāda, vai lietotājs ir ieslēdzis piekļuvi ar ceļvedi savā ierīcē, lai palīdzētu mums noteikt ar šo iestatījumu saistītās problēmas

- **invert_colors** — norāda, vai lietotājs ir ieslēdzis krāsu inversijas iestatījumu savā ierīcē, lai palīdzētu mums atklāt ar šo iestatījumu saistītās problēmas

- **mono_audio** — norāda, vai lietotājs ir ieslēdzis mono skaņas iestatījumu savā ierīcē, lai palīdzētu mums atklāt ar šo iestatījumu saistītās problēmas

- **reduce_motion** — norāda, vai lietotājs ir ieslēdzis kustības samazināšanas iestatījumu savā ierīcē, lai palīdzētu mums atklāt ar šo iestatījumu saistītās problēmas

- **reduce_transparency** — norāda, vai lietotājs ir ieslēdzis caurspīdības samazināšanas iestatījumu savā ierīcē, lai palīdzētu mums atklāt ar šo iestatījumu saistītās problēmas

- **speak_screen** — norāda, vai lietotājs ir ieslēdzis mono skaņas iestatījumu savā ierīcē, lai palīdzētu mums atklāt ar šo iestatījumu saistītās problēmas

- **speak_selection** — norāda, vai lietotājs ir ieslēdzis runas atlases iestatījumu savā ierīcē, lai palīdzētu mums atklāt ar šo iestatījumu saistītās problēmas

- **switch_control** — norāda, vai lietotājs ir ieslēdzis Switch Control iestatījumu savā ierīcē, lai palīdzētu mums atklāt ar šo iestatījumu saistītās problēmas

- **voice_over** — norāda, vai lietotājs ir ieslēdzis VoiceOver iestatījumu savā ierīcē, lai palīdzētu mums atklāt ar šo iestatījumu saistītās problēmas

Tālāk norādītie lauki tiek apkopoti tikai Android:

- **braille** — norāda, vai lietotājs ir ieslēdzis Braila raksta iestatījumu savā ierīcē, lai palīdzētu mums atklāt ar šo iestatījumu saistītās problēmas

- **caption** — norāda, vai lietotājs ir ieslēdzis slēptos titrus savā ierīcē, lai palīdzētu mums atklāt ar slēptajiem titriem saistītās problēmas

- **color_inversion** — norāda, vai lietotājs ir ieslēdzis krāsu inversijas iestatījumu savā ierīcē, lai palīdzētu mums atklāt ar šo iestatījumu saistītās problēmas

- **high_contrast** — norāda, vai lietotājs ir ieslēdzis augsta kontrasta iestatījumu savā ierīcē, lai palīdzētu mums atklāt ar šo iestatījumu saistītās problēmas

- **large_text** — norāda, vai ierīcē ir ieslēgts lielizmēra teksta iestatījums, lai palīdzētu mums atklāt ar šo iestatījumu saistītās problēmas

- **oem_preinstall** — norāda, vai mūsu lietojumprogramma bija iepriekš instalēta ierīcē (attiecas tikai uz Samsung ierīcēm)

- **supported_abis** — norāda, kāda veida lietojumprogrammu binārās saskarnes (ABI) tiek atbalstītas ierīces platformā, lai palīdzētu mums atklāt ar šo iestatījumu saistītās problēmas

- **switch_access** — norāda, vai lietotājs ir ieslēdzis Switch Access iestatījumu savā ierīcē, lai palīdzētu mums atklāt ar šo iestatījumu saistītās problēmas

- **talkback** — norāda, vai lietotājs ir ieslēdzis TalkBack iestatījumu savā ierīcē, lai palīdzētu mums atklāt ar šo iestatījumu saistītās problēmas

#### <a name="low_storage_warning"></a>low_storage_warning

Ir nepieciešams, lai uzraudzītu, vai mūsu lietojumprogramma pēkšņi neaizņem lielāko daļu jūsu ierīces krātuves palielināta atmiņas izmantošanas apjoma dēļ, norādot brīdi, kurā ierīcei trūkst krātuves apjoma.

Tiek apkopoti šādi lauki: 

- **free_bytes** — ierīcē pieejamās brīvās krātuves vietas apjoms

#### <a name="officeairspaceairspacelocalblocklistdriverupdated"></a>Office.AirSpace.AirSpaceLocalBlocklistDriverUpdated

Lietotājs atjaunināja videokartes draiveri, kas iepriekš izraisīja Office avārijas, un tas vairs netiek izmantots atveidošanai. Informē Microsoft, ka lietotājiem, kuriem bija pasliktināts atveidošanas stāvoklis, atkal ir ieteicamais atveidošanas stāvoklis.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_BlockedDriverVersion** — bloķētā draivera versija.

  - **Data\_DeviceId** — bloķētās videokartes ierīces identifikators.

  - **Data\_UpdatedDriverVersion** — atjauninātā draivera versija

#### <a name="officeairspaceairspacelocalblocklistinfo"></a>Office.AirSpace.AirSpaceLocalBlocklistInfo

Detalizēta informācija par lietotāja videokartes draiveri, kas izraisīja vairākas nesenas Office lietojumprogrammu avārijas. Office neizmantos šo videokarti šajā Office sesijā (tā vietā izmantojot programmatūras atveidošanu), līdz draiveris būs atjaunināts. Informē Microsoft par videokartes draiveri, kas rada problēmas sistēmā Office, lai identificētu tendences un analizētu šādu draiveru ietekmi uz lietotāju. Informējiet Microsoft, cik lietotāju ir šādā pasliktinātā stāvoklī.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_AllAppsBlocked** — vai visas Office lietojumprogrammas ir bloķētas

  - **Data\_BlockedDeviceId** — bloķētās videokartes ierīces identifikators

  - **Data\_BlockedDriverVersion** — bloķētā draivera versija

  - **Data\_CrashHistory** — virkne, kas attēlo videokartes draivera izraisītās avārijas, lai veiktu analīzi

  - **Data\_SecsBetweenCrashes** — cik bieži avarē draivera karte

#### <a name="officeairspaceairspacewincompisenabled"></a>Office.AirSpace.AirSpaceWinCompIsEnabled

Vai tiek izmantota jaunākā Office zema līmeņa atveidošanas platforma, kuras pamatā ir Windows salikums.

Norit jaunākās Office zema līmeņa atveidošanas platformas izstrāde un piegāde klientiem, kas ļauj Microsoft redzēt, cik daudz lietotāju ir katrā versijā, lai nodrošinātu, ka platforma darbojas bez kļūdām.

Tiek apkopoti šādi lauki:

  - **Data\_WinCompEnabled** — vai tiek izmantota Windows salikuma aizmugursistēma

#### <a name="officeairspacebackendwin32graphicsdriverhangdetectorblocklistapp"></a>Office.AirSpace.Backend.Win32.GraphicsDriverHangDetectorBlocklistApp

Lietotāja videokarte ir noteikta kā iemesls, kas izraisa ilgus vai neatkopjamus reaģēšanas pārtraukumus. Office neizmantos šo videokarti šajā Office sesijā (tā vietā izmantojot programmatūras atveidošanu), līdz draiveris būs atjaunināts. Informē Microsoft par videokartes draiveri, kas rada problēmas sistēmā Office, lai identificētu tendences un analizētu šādu draiveru ietekmi uz lietotāju. Palīdz arī informēt, cik lietotāju ir šādā pasliktinātā stāvoklī.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_AppName** — kurā programmā videokartes draiveris pārtrauca reaģēt

#### <a name="officeairspacebackendwin32graphicsdriverhangdetectorregistrywrite"></a>Office.AirSpace.Backend.Win32.GraphicsDriverHangDetectorRegistryWrite

Office konstatēja, ka lietotāja videokartes draiveris izraisīja reaģēšanas pārtraukumu, kas ir jāanalizē nākamajā Office lietojumprogrammas startēšanas reizē Izmanto, lai noteiktu, vai cits videokartes draiveris vai adapteris nodrošina labāku lietotāja pieredzi. Shēmu izpildes laikā Microsoft var veikt pielāgojumus, lai Office pieredzi saglabātu iespējami netraucētu.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_HangDetected** — vai tika konstatēts reaģēšanas pārtraukums

  - **Data\_InDeviceCall** — kādu videokartes atveidošanas izsaukumu veica Office, kad tā pārtrauca reaģēt

  - **Data\_Timeout** — cik ilgi nereaģēja, ja notika atkopšanās

  - **Data\_UnrecoverableCommand** — vai reaģēšanas pārtraukumu šajā videokartes atveidošanas komandā parasti iespējams atkopt.

#### <a name="officeairspacebackendwin32localblocklistactivity"></a>Office.AirSpace.Backend.Win32.LocalBlocklistActivity

Detalizēta informācija par lietotāja videokartes draiveri, kas izraisīja vairākas nesenas Office lietojumprogrammu avārijas. Office neizmantos šo videokarti šajā Office sesijā (tā vietā izmantojot programmatūras atveidošanu), līdz draiveris būs atjaunināts. Informē Microsoft par videokartes draiveri, kas rada problēmas sistēmā Office, lai identificētu tendences un analizētu šādu draiveru ietekmi uz lietotāju. Informējiet Microsoft, cik lietotāju ir šādā pasliktinātā stāvoklī.

Tiek apkopoti tālāk norādītie lauki.

  - **Data.AllAppsBlocked** — vai visas Office lietojumprogrammas ir bloķētas

  - **Data.BlockedDeviceId** — bloķētās videokartes ierīces identifikators

  - **Data.BlockedDriverVersion** — bloķētā draivera versija

  - **Data.CrashHistory System.String** — virkne, kas attēlo videokartes draivera izraisītās avārijas, lai veiktu analīzi

  - **Data.SecsBetweenCrashes** — cik bieži avarē draivera karte

#### <a name="officeairspacebackendwin32localblocklistdriverupdatedactivity"></a>Office.AirSpace.Backend.Win32.LocalBlocklistDriverUpdatedActivity

Lietotājs atjaunināja videokartes draiveri, kas iepriekš izraisīja Office avārijas, un tas vairs netiek izmantots atveidošanai. Informē Microsoft, ka lietotājiem, kuriem bija pasliktināts atveidošanas stāvoklis, atkal ir ieteicamais atveidošanas stāvoklis.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_BlockedDeviceId** — bloķētās videokartes ierīces identifikators

  - **Data\_BlockedDriverVersion** — bloķētā draivera versija

  - **Data\_UpdatedDriverVersion** — atjauninātā draivera versija

#### <a name="officegraphicsspritememcorrupt"></a>Office.Graphics.SpriteMemCorrupt

Uzrāda visas kļūdas, kas konstatētas Sprite atmiņas uzskaites telemetrijā. Kritiski svarīgi, lai novērtētu grafikas atmiņas lietojuma telemetrijas darbspēju. Šī informācija ir nepieciešama, lai validētu mūsu SpriteMem telemetrijas datu pareizību.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_CurrentSpriteMem** — kopējais atmiņas apjoms, kas tiek aktīvi piešķirta, lai noturētu Sprite objektus (attēlus), radot ekrāna saturu.

  - **Data\_Function** — funkcijas nosaukums, kas mēģina atbrīvot Sprite atmiņu.

  - **Data\_SpriteMemToRemove** — atmiņas apjoms, kas jānoņem no Sprite sadalījuma.

#### <a name="officepowerpointpptsharednointernetconnectivity"></a>Office.PowerPoint.PPT.Shared.NoInternetConnectivity

Apkopo katru reizi, kad PowerPoint konstatē, ka nav interneta savienojuma. Microsoft izmanto šos datus, lai iegūtu diagnostikas informāciju par lietotāja interneta savienojumu un izprastu, kā tas ietekmē savienojumu ar Office pakalpojumiem.

Tiek apkopoti tālāk norādītie lauki.

- **Data\_IsNexusDetected:bool** – redzams, vai ir interneta savienojuma statuss, izsaucot Nexus pakalpojumu (patiesa vērtība) vai izsaucot standarta tīmekļa pakalpojuma API (aplama vērtība)

#### <a name="officeserviceabilitymanagerofficesvcmgrprofile"></a>Office.ServiceabilityManager.OfficeSvcMgrProfile

Notikums sākas brīdi, kad tiek sāknēts Office Serviceability Manager, un ir kritiski svarīgs, lai sniegtu ieskatu saistībā ar izvietošanas statusu, lietojumprogrammu un pievienojumprogrammu avārijām klienta nomniekā, ļaujot mums ģenerēt ieskatus, lai IT administrators spētu pārliecināti veidot atjauninājumus sava uzņēmumam datoriem.  

Tiek apkopoti tālāk norādītie lauki:

- **DeviceIdJoinToken** — tiek izmantots, lai savienotu telemetrijas datus darbspējas un izvietošanas statusa ar citiem funkcionāliem datiem, kas tiek iegūti no pakalpojumu konveijera.

- **TenantAssociationKeyStamped** — būlas karodziņš, kas tiek izmantots, lai noteiktu Office ekosistēmā pārvaldīto ierīču skaitu.
