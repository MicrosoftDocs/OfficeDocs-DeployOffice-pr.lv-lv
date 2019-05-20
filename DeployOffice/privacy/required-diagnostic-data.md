---
title: Nepieciešamie Office diagnostikas dati
ms.author: danbrown
author: DHB-MSFT
manager: laurawi
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection: Ent_O365
ms.custom:
- Ent_Office_ProPlus
- Ent_Office_Privacy
description: Sniedz informāciju Office administratoriem par nepieciešamajiem Office diagnostikas datiem un nodrošina notikumu un datu lauku sarakstu.
hideEdit: true
ms.openlocfilehash: 9b22b428999c51b46e6f6ce662fad99f5a727b4c
ms.sourcegitcommit: 6145cfe372725bedab7bc6a80adab100561f74fd
ms.translationtype: HT
ms.contentlocale: lv-LV
ms.lasthandoff: 05/17/2019
ms.locfileid: "34106931"
---
# <a name="required-diagnostic-data-for-office"></a>Nepieciešamie Office diagnostikas dati

> [!IMPORTANT]
> Informācija šajā rakstā attiecas uz tālāk minētās Office klienta programmatūras versiju 1904 vai jaunāku versiju, kas instalēta datorā, kurā darbojas sistēma Windows:
> - Office 365 ProPlus un Office 365 Business
> - Office 365 individuālai lietošanai, Office 365 mājas lietošanai vai citas Office versijas, kas ir daļa no Office 365 abonementa.
> - Project un Visio, kas ir iekļautas dažos abonēšanas plānos, piemēram, Project Online Professional plānā vai Visio Online 2. plānā.

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

  - **DiagnosticConsentConsentTime** — norāda, kad lietotājs ir iesniedzis atļauju diagnostikas datiem

  - **ServiceConnectionState** — norāda, vai lietotājs ir izvēlējies lietot vai nelietot visus saistītos līdzekļus

  - **ServiceConnectionStateSourceLocation** — norāda, kā lietotājs ir izvēlējies lietot vai nelietot visus saistītos līdzekļus

  - **ServiceConnectionStateConsentTime** — norāda, kad lietotājs ir izvēlējies lietot vai nelietot visus saistītos līdzekļus

  - **ControllerConnectedServicesState** — norāda, vai lietotājam ir piekļuve neobligātajiem saistītajiem līdzekļiem

  - **ControllerConnectedServicesStateSourceLocation** — norāda, kā tika veikta lietotāja izvēle lietot neobligātos saistītos līdzekļus

  - **ControllerConnectedServicesStateConsentTime** — norāda, kad lietotājs izvēlējās neobligāto saistīto līdzekļu statusu

  - **UserContentDependentState** — norāda, vai lietotājs ir izvēlējies iespējot vai atspējot saistītos līdzekļus, kas analizē saturu

  - **UserContentDependentStateSourceLocation** — norāda, kā tika veikta lietotāja izvēle iespējot vai atspējot saistītos līdzekļus, kas analizē saturu

  - **UserContentDependentStateConsentTime** — norāda, kad lietotājs izvēlējās iespējot vai atspējot saistītos līdzekļus, kas analizē saturu

  - **DownloadContentState** — norāda, vai lietotājs ir izvēlējies iespējot vai atspējot saistītos līdzekļus, kas lejupielādē tiešsaistes saturu

  - **DownloadContentStateSourceLocation** — norāda, kā lietotājs izvēlējās iespējot vai atspējot saistītos līdzekļus, kas lejupielādē tiešsaistes saturu

  - **DownloadContentStateConsentTime** — norāda, kad lietotājs izvēlējās iespējot vai atspējot saistītos līdzekļus, kas lejupielādē tiešsaistes saturu.

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

## <a name="software-setup-and-inventory-data-events"></a>Programmatūras iestatīšanas un inventāra datu notikumi

Tālāk ir norādīti šīs kategorijas datu apakštipi.
- [Office iestatīšana un inventārs](#office-setup-and-inventory-subtype)
- [Office pievienojumprogrammu konfigurācija](#office-add-in-configuration-subtype)
- [Drošība](#security-subtype)  

### <a name="office-setup-and-inventory-subtype"></a>*Office iestatīšana un inventāra apakštips*

Instalētais produkts, versija un instalēšanas statuss.

#### <a name="officeclicktorunupdatestatus"></a>Office.ClickToRun.UpdateStatus

Attiecas uz visām win32 lietojumprogrammām. Palīdz mums noteikt Office komplekta atjaunināšanas procesa statusu (izdošanās vai neizdošanās ar detalizētu informāciju par kļūdām)

Tiek apkopoti tālāk norādītie lauki.

- **build** — pašreiz instalētā Office versija

- **channel** — Office izplatīšanas kanāls

- **errorCode** — kļūdas kods, kas norāda uz kļūmi

- **errorMessage** — papildu informācija par kļūdu

- **status** — pašreizējais atjauninājuma statuss

- **targetBuild** — versija, uz kuru tiek atjaunināta sistēma Office

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

- **UTCReplace_AppSessionGuid** — konstanta Būla vērtība. Vienmēr True.

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

### <a name="office-add-in-configuration-subtype"></a>*Office pievienojumprogrammu konfigurācijas apakštips*

Programmatūras pievienojumprogrammas un to iestatījumi.

#### <a name="officeextensibilityappcommandsappcmdprojectionstatus"></a>Office.Extensibility.AppCommands.AppCmdProjectionStatus

Apkopo informāciju, lai izsekotu, kuras Office pievienojumprogrammu instalācijas sekmīgi atjaunināja lenti un kurām tas neizdevās.

Izmanto bieži sastopamu ar reģistrāciju saistītu problēmu novēršanai, ja pievienojumprogrammas tiek nepareizi instalētas un nekad neparādās, kā rezultātā kļūst nelietojamas.

Tiek apkopoti tālāk norādītie lauki.

  - Nav

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

Dati par sekmīgu vai nesekmīgu atjaunināto datu vajadzības izgūšanu attiecībā uz Office 365 nomnieka administratora piešķirtajām pievienojumprogrammām. Izmanto darbspējas rādītājiem, diagrammām un klientu problēmu analīzei. ExchangeGetLastUpdate vienmēr tiek izpildīts palaišanas laikā kā daļa no resursa koda un nosaka, vai ir mainījušās pievienojumprogrammu piešķires lietotājam.  Ja tā ir, tad tiek ielādēts osf.DLL, lai mēs varētu izsaukt ExchangeGetEntitlements ar mērķi iegūt konkrētas piešķires (tiek izsaukts arī ExchangeGetManifests, lai izgūtu jebkuru jaunu nepieciešamo manifestu).  ExchangeGetEntitlements (un ExchangeGetManifests) var izsaukt arī pēc pieprasījuma pēc tam, kad ir darbojusies viesošanas lietojumprogramma.  Mērķis ir neielādēt lielu DLL, ja tas nav nepieciešams.  Ja šis notikums nebūtu nepieciešams, mēs nevarētu noteikt, vai lietotājiem izdodas iegūt viņiem piešķirtās pievienojumprogrammas, ja neizdodas pirmais pakalpojuma izsaukums.  Tas ir arī galvenais veids, kā mēs uzzinām, vai pastāv kādas autorizācijas problēmas saistībā ar mūsu pakalpojumu izsaukšanu.

Tiek apkopoti tālāk norādītie lauki.

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

  - **Standarta HVA darbība ar lietderīgajiem datiem, kas nav pielāgoti**

#### <a name="officeprogrammabilityadd-insinternalsetconnectenterprise"></a>Office.Programmability.Add-ins.InternalSetConnectEnterprise

Notikums, kas tiek ģenerēts, ja COM pievienojumprogramma tiek ielādēta uzņēmuma ierīcē. Desktop Analytics: ielāžu skaits tiek izmantots kā darbspējas aprēķina daļskaitļa saucējs (avāriju skaits/ielāžu skaits ) darbspējas rādītāju aprēķinam izmēģinājuma un ražošanas lokiem uzņēmuma scenārijos. Datiem ir jābūt precīziem un neiztvertiem, jo ierīču skaits ir mazāks (100–1 tūkst.).

Tiek apkopoti tālāk norādītie lauki.

  - **Add-inconnectFlag** — pašreizējās ielādes darbība

  - **Add-inDescription** — pievienojumprogrammas apraksts

  - **Add-inFileName** — pievienojumprogrammas faila nosaukums bez faila ceļa

  - **Add-inFriendlyName** — pievienojumprogrammas draudzīgais nosaukums

  - **Add-inId** — pievienojumprogrammas klases ID

  - **Add-inProgId** — pievienojumprogrammas Prog ID

  - **Add-inProvider** — pievienojumprogrammas nodrošinātājs

  - **Add-inTimeDateStamp** — pievienojumprogrammas laikspiedols no DLL metadatiem

  - **Add-inVersion** — pievienojumprogrammas versija

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


### <a name="application-feature-success-subtype"></a>*Lietojumprogrammas līdzekļu sekmju apakštips*

Informācija par sekmīgu lietojumprogrammas funkcionalitāti. Attiecas tikai uz programmas un dokumentu atvēršanu un aizvēršanu, failu rediģēšana un failu koplietošanu (sadarbību).

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

#### <a name="officeextensibilitycatalogexchangeprocessentitlement"></a>Office.Extensibility.Catalog.ExchangeProcessEntitlement

Dati par Office 365 nomnieka administratora piešķirtas pievienojumprogrammas atsevišķas pilnvaras apstrādi.

Izmanto tādu diagrammu izveidē (pieprasa grupas pārvaldība), kurā tiek analizēti klientu panākumi un problēmas.

Tiek apkopoti tālāk norādītie lauki.

  - **AppVersion** — pievienojumprogrammas viesošanas programmas versija.

  - **SolutionId** — GUID, kas apzīmē unikālu pievienojumprogrammu

  - **TelemetryId —** GUID, kas apzīmē unikālu lietotāju

#### <a name="officefileiocsiccachedfilecsiloadfilebasic"></a>Office.FileIO.CSI.CCachedFileCsiLoadFileBasic

Ļauj uzzināt, vai fails ir veiksmīgi atvērts no FIO līmeņa. Izmanto līdzekļu darbspējas veicināšanai un pārraudzībai.

Tiek apkopoti tālāk norādītie lauki.

  - **Activity.Group —** tags, kas ļauj grupēt pārraudzības notikumu kopu, lai pārvaldītu kopējos panākumus

  - **Activity.IsHVA —** karodziņš, kas norāda, ka šis notikums ir svarīgs lietotāja panākumiem

  - **Data.AsyncOpen —** karodziņš, kas norāda atvērto saturu, kas ir pieejams pēc galvenā satura atvēršanas

  - **Data.CacheFileId —** izveido savienojumu ar Office dokumentu kešatmiņas telemetriju, lai iespējotu analīzi saistībā ar kešatmiņas problēmu ietekmi uz lietotāju pieredzi

  - **Data.CoauthStatus —** reģistrē atvērta dokumenta sadarbības statusu

  - **Data.CountOfMultiRoundTripsDownload —** to servera apmeklējumu skaits, kas tiek izmantoti veiktspējas un tīkla problēmu novēršanai

  - **Data.CountOfMultiRoundTripsUpload —** to servera apmeklējumu skaits, kas tiek izmantoti veiktspējas un tīkla problēmu novēršanai

  - **Data.DialogId —** tiek iestatīts, ja atvēršanas laikā tiek parādīts lietotāja interfeisa dialoglodziņš, norādot, ka lietotājs saņēma brīdinājuma ziņojumu

  - **Data.DidFallbackToDAV —** tiek iestatīts, ja dokuments tika atvērts, izmantojot vecāku failu pārsūtīšanas protokolu

  - **Data.Doc.AccessMode —** dokuments ir tikai lasāms/rediģējams

  - **Data.Doc.AssistedReadingReasons —** tiek iestatīts, ja dokumentā ir iespējota elektronisko datu aizsardzība

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

  - **Data.Input.FileOpenState —** statuss, ko pieprasa programma (lasīšana/lasīšana un rakstīšana utt.) **-**

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

  - **Data.DialogChoice —** ierakstu izvēle kļūdu dialoglodziņos

  - **Data.DialogId —** reģistrē jebkuru saglabāšanas laikā parādīto kļūdu dialoglodziņu identifikatoru

  - **Data.Dmc.IsOcsSupported —** novecojis

  - **Data.Doc.AccessMode —** dokuments ir tikai lasāms

  - **Data.Doc.AssistedReadingReasons —** tiek iestatīts, ja dokumentā ir iespējota elektronisko datu aizsardzība

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

#### <a name="officeoutlookdesktopprovidersloadproviderlibrary"></a>Office.Outlook.Desktop.Providers.LoadProviderLibrary

Šis notikums reģistrē MAPI panākumus ielādēt pakalpojumu sniedzēja DLL (piemēram, contab32.dll, emsmdb32.dll vai pievienojumprogrammas izmantotu DLL). MAPI darbība, kas atbild par pakalpojuma sniedzēja DLL ielādi, ir būtiski svarīga Outlook nepieciešamajām darbībām, kā arī paplašināšanai (izmantojot pievienojumprogrammas vai pielāgotus krātuves/transportēšanas/adrešu grāmatas nodrošinātājus). Mēs aktīvi pārraugām šīs darbības panākumus, lai nodrošinātu, ka pamata MAPI funkcionalitāte turpina pareizi darboties.

Tiek apkopoti tālāk norādītie lauki.

  - **Standarta HVA darbība** ar lietderīgajiem datiem, kas nav pielāgoti

#### <a name="officeoutlookdesktopstorescreatenewstore"></a>Office.Outlook.Desktop.Stores.CreateNewStore

Apkopo rezultātus šim: jaunas krātuves izveide (ar tipu un versiju), kā arī rezultātu kodu. Mēs aktīvi pārraugām šo notikumu, lai izsekotu darbspējai, lietotāja spējai lokāli sinhronizēt pastu, arhivēt pastu (PST) vai izmantot grupas.

Tiek apkopoti tālāk norādītie lauki.

  - **Standarta HVA darbība** ar lietderīgajiem datiem, kas ir pielāgoti

  - **StoreType** — izveidotās krātuves tips (OST/PST/NST)

  - **StoreVersion** — izveidotās krātuves versija (Small/Large/Tardis)

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

  - **Data_Doc_IsRtcAlwaysOn —** patiess, ja reāllaika kanāls (RTC) šim failam vienmēr ir ieslēgts.

  - **Data\_Doc\_IsSyncBacked:bool —** pārbauda, vai ja dokuments tiek atvērts no mapes, kas izmanto OneDrive sinhronizācijas programmu

  - **Data\_Doc\_Location:long —** iepriekš definētu vērtību kopa, kas norāda dokumenta glabāšanas vietu (lokālā, SharePoint, WOPI, tīkls utt.)

  - **Data\_Doc\_LocationDetails:long —** iepriekš definētu detalizētākas atrašanās vietas vērtību kopa (mape Temp, lejupielāžu mape, OneDrive dokumenti, OneDrive attēli utt.)

  - **Data\_Doc\_NumberCoAuthors:long —** līdzautoru skaits dokumenta atvēršanas brīdī

  - **Data\_Doc\_PasswordFlags:long —** iepriekš definētu vērtību kopa, kas norāda veidu, kā dokuments ir šifrēts ar paroli (nav, parole lasīšanai, parole rediģēšanai)

  - **Data\_Doc\_ReadOnlyReasons:long —** iepriekš definētu vērtību kopa, kas norāda, kāpēc šis dokuments ir atzīmēts kā tikai lasāms (bloķēts serverī, pabeigts dokuments, aizsargāts ar paroli rediģēšanai utt.)

  - **Data\_Doc\_ResourceIdHash:string —** resursu identifikatora jaukšana mākonī saglabātajiem dokumentiem

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

  - **Data_Doc_IsRtcAlwaysOn —** patiess, ja reāllaika kanāls (RTC) šim failam vienmēr ir ieslēgts.

  - **Data\_Doc\_IsSyncBacked:bool —** vai dokuments tiek atvērts no mapes, kas izmanto OneDrive sinhronizācijas programmu

  - **Data\_Doc\_Location:long —** iepriekš definētu vērtību kopa, kas norāda dokumenta glabāšanas vietu (lokālā, SharePoint, WOPI, tīkls utt.)

  - **Data\_Doc\_LocationDetails:long —** iepriekš definētu detalizētākas atrašanās vietas vērtību kopa (mape Temp, lejupielāžu mape, OneDrive dokumenti, OneDrive attēli utt.)

  - **Data\_Doc\_NumberCoAuthors:long —** līdzautoru skaits dokumenta atvēršanas brīdī

  - **Data\_Doc\_PasswordFlags:long —** iepriekš definētu vērtību kopa, kas norāda veidu, kā dokuments ir šifrēts ar paroli (nav, parole lasīšanai, parole rediģēšanai)

  - **Data\_Doc\_ReadOnlyReasons:long —** iepriekš definētu vērtību kopa, kas norāda, kāpēc šis dokuments ir atzīmēts kā tikai lasāms (bloķēts serverī, pabeigts dokuments, aizsargāts ar paroli rediģēšanai utt.)

  - **Data\_Doc\_ResourceIdHash:string —** resursu identifikatora jaukšana mākonī saglabātajiem dokumentiem

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

  - **Data_Doc_IsRtcAlwaysOn —** patiess, ja reāllaika kanāls (RTC) šim failam vienmēr ir ieslēgts.

  - **Data\_Doc\_IsSyncBacked:bool —** vai dokuments tiek atvērts no mapes, kas izmanto OneDrive sinhronizācijas programmu

  - **Data\_Doc\_Location:long —** iepriekš definētu vērtību kopa, kas norāda dokumenta glabāšanas vietu (lokālā, SharePoint, WOPI, tīkls utt.)

  - **Data\_Doc\_LocationDetails:long —** iepriekš definētu detalizētākas atrašanās vietas vērtību kopa (mape Temp, lejupielāžu mape, OneDrive dokumenti, OneDrive attēli utt.)

  - **Data\_Doc\_NumberCoAuthors:long —** līdzautoru skaits dokumenta atvēršanas brīdī

  - **Data\_Doc\_PasswordFlags:long —** iepriekš definētu vērtību kopa, kas norāda veidu, kā dokuments ir šifrēts ar paroli (nav, parole lasīšanai, parole rediģēšanai)

  - **Data\_Doc\_ReadOnlyReasons:long —** iepriekš definētu vērtību kopa, kas norāda, kāpēc šis dokuments ir atzīmēts kā tikai lasāms (bloķēts serverī, pabeigts dokuments, aizsargāts ar paroli rediģēšanai utt.)

  - **Data\_Doc\_ResourceIdHash:string —** resursu identifikatora jaukšana mākonī saglabātajiem dokumentiem

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

Apkopots ikreiz, kad PowerPoint veic darbību Saglabāt kā. Ietver saglabāšanas veiktspējas rādītāju rezultātu tipa panākumus un saistītos dokumenta metadatus. Saglabāšanas kļūmes var izraisīt datu zudumu.

Microsoft izmanto šos datus, lai nodrošinātu, ka līdzeklis darbojas, kā paredzēts, un lietotāju saturs tiek sekmīgi turpināts.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_AddDocTelemetryResult:long —** vai šim žurnāla ierakstam ir visa nepieciešamā dokumenta telemetrija (Data\_Doc\_\* lauki)? Ja tā nav, kāpēc?

  - **Data\_CppUncaughtExceptionCount:long —** nenotverti vietējie izņēmumi darbības izpildes laikā

  - **Data\_DetachedDuration:long —** darbības atvienošanas/nedarbošanās ilgums

  - **Data\_DstDoc\_AccessMode:long —** kā šis dokuments ir atvērts (tikai lasāms | lasīšana un rakstīšana)

  - **Data\_DstDoc\_AssistedReadingReasons:long —** iepriekš definētu vērtību kopa, kas norāda, kāpēc dokuments ir atvērts pieejamā lasīšanas režīmā

  - **Data\_DstDoc\_ChunkingType:long —** kā dokuments ir saglabāts pakalpojumā SharePoint

  - **Data\_DstDoc\_EdpState:long —** dokumenta uzņēmuma datu aizsardzība statuss

  - **Data\_DstDoc\_Ext:string —** dokumenta paplašinājums

  - **Data\_DstDoc\_Extension:string —** dokumenta paplašinājums

  - **Data\_DstDoc\_FileFormat:long —** iepriekš definētu faila formāta vērtību kopa (detalizētāka par paplašinājumu).

  - **Data\_DstDoc\_Fqdn:string —** dokumentu glabāšanas vieta (SharePoint.com, live.net), pieejama tikai Office 365 domēniem

  - **Data\_DstDoc\_FqdnHash:string —** dokumenta glabāšanas vietas jaukšana

  - **Data\_DstDoc\_IdentityTelemetryId:string —** unikāls lietotāja GUID

  - **Data\_DstDoc\_IdentityUniqueId:string —** tās identitātes unikālais identifikators, kas tika izmantota koplietojamo dokumentu darbībai

  - **Data\_DstDoc\_IOFlags:long —** bitmaska dažādiem ar IO saistītiem karodziņiem, kas attiecas uz dokumentu

  - **Data\_DstDoc\_IrmRights:long —** iepriekš definētu vērtību kopa, kas attiecas uz informācijas piekļuves tiesību pārvaldības tipu, kas tiek lietots šim dokumentam (pārsūtīšana, atbildēšana, SecureReader, rediģēšana u.c.)

  - **Data\_DstDoc\_IsCloudCollabEnabled:bool —** patiess, ja "IsCloudCollabEnabled" HTTP galvene jau ir saņemta no pieprasījuma OPTIONS.

  - **Data\_DstDoc\_IsIncrementalOpen:bool —** vai dokuments tika atvērts inkrementāli (jauns līdzeklis, kas atver dokumentu bez vajadzības lejupielādēt visu dokumentu)

  - **Data\_DstDoc\_IsOcsSupported:bool —** vai ir dokuments atbalsta koprediģēšanu, izmantojot jauno OCS pakalpojumu

  - **Data\_DstDoc\_IsOpeningOfflineCopy:bool —** pārbauda, vai dokuments tiek atvērts no lokālās kešatmiņas

  - **Data\_DstDoc\_IsSyncBacked:bool —** vai dokuments tiek atvērts no mapes, kas izmanto OneDrive sinhronizācijas programmu

  - **Data\_DstDoc\_Location:long —** iepriekš definētu vērtību kopa, kas norāda dokumenta glabāšanas vietu (lokālā, SharePoint, WOPI, tīkls utt.)

  - **Data\_DstDoc\_LocationDetails:long —** iepriekš definētu detalizētākas atrašanās vietas vērtību kopa (mape Temp, lejupielāžu mape, OneDrive dokumenti, OneDrive attēli utt.)

  - **Data\_DstDoc\_NumberCoAuthors:long —** līdzautoru skaits dokumenta atvēršanas brīdī

  - **Data\_DstDoc\_PasswordFlags:long —** iepriekš definētu vērtību kopa, kas norāda veidu, kā dokuments ir šifrēts ar paroli (nav, parole lasīšanai, parole rediģēšanai)

  - **Data\_DstDoc\_ReadOnlyReasons:long —** iepriekš definētu vērtību kopa, kas norāda, kāpēc šis dokuments ir atzīmēts kā tikai lasāms (bloķēts serverī, pabeigts dokuments, aizsargāts ar paroli rediģēšanai utt.)

  - **Data\_DstDoc\_ResourceIdHash:string —** resursu identifikatora jaukšana mākonī saglabātajiem dokumentiem

  - **Data\_DstDoc\_ServerDocId:string —** nemainīgs identifikators mākonī saglabātajiem dokumentiem

  - **Data\_DstDoc\_ServerProtocol:long —** iepriekš definētu vērtību kopa, kas norāda, kurš protokols tiek izmantots, lai sazinātos ar serveri (HTTP, Cobalt, WOPI utt.)

  - **Data\_DstDoc\_ServerType:long —** iepriekš definētu vērtību kopas servera tipam (SharePoint, DropBox, WOPI)

  - **Data\_DstDoc\_ServerVersion:long —** pārbauda, vai servera pamatā ir Office14, Office15 vai Office 16

  - **Data\_DstDoc\_SessionId:long —** ģenerēts GUID, kas norāda dokumenta instanci tajā pašā procesa sesijā

  - **Data\_DstDoc\_SharePointServiceContext:string —** necaurspīdīga virkne, parasti GridManagerID.FarmID. Noder, lai saistītu klienta un servera žurnālu

  - **Data\_DstDoc\_SizeInBytes:long —** dokumenta lielums baitos

  - **Data\_DstDoc\_SpecialChars:long —** bitmaska, kas norāda speciālās rakstzīmes dokumenta vietrādī URL vai ceļā

  - **Data\_DstDoc\_StorageProviderId:string —** virkne, kas norāda dokumenta krātuves nodrošinātāju, piemēram, "DropBox"

  - **Data\_DstDoc\_StreamAvailability:long —** iepriekš definētu dokumenta straumēšanas vērtību kopas statuss (pieejams, neatgriezeniski atspējots, nav pieejams)

  - **Data\_DstDoc\_UrlHash:string —** pilna vietrāža URL jaukšana mākonī saglabātiem dokumentiem

  - **Data\_DstDoc\_UsedWrsDataOnOpen:bool —** patiess, ja fails tika atvērts inkrementāli, izmantojot iepriekš kešotus WRS datus resursdatorā

  - **Data\_DstDoc\_WopiServiceId:string —** WOPI pakalpojuma identifikators, piemēram, "Dropbox"

  - **Data\_FileType:long —** iepriekš definētu iekšējā faila tipa vērtību kopa

  - **Data\_fLifeguarded:bool —** vai dokuments kādreiz ir bijis aizsargāts (līdzeklis, lai izlabotu dokumenta kļūdas, neziņojot par to lietotājam)?

  - **Data\_FWebCreated:bool —** vai dokumentam ir WebCreator karodziņš?

  - **Data\_SaveReason:long —** iepriekš definētu vērtību kopa, kas norāda, kāpēc tika veikta saglabāšana (Automātiskā saglabāšana, ToOCSTransitionSave, ToCSITransitionSave utt.)

  - **Data\_SaveType:long —** iepriekš definētu vērtību kopa saglabāšanas tipam (SaveAs, Publish, Manual, OMSave utt.)

  - **Data\_SrcDoc\_AccessMode:long —** kā šis dokuments ir atvērts (tikai lasāms | lasīšana un rakstīšana)

  - **Data\_SrcDoc\_AssistedReadingReasons:long —** iepriekš definētu vērtību kopa, kas norāda, kāpēc dokuments ir atvērts pieejamā lasīšanas režīmā

  - **Data\_SrcDoc\_ChunkingType:long —** kā dokuments ir saglabāts pakalpojumā SharePoint

  - **Data\_SrcDoc\_EdpState:long —** dokumenta uzņēmuma datu aizsardzība statuss

  - **Data\_SrcDoc\_Ext:string —** dokumenta paplašinājums

  - **Data\_SrcDoc\_Extension:string —** dokumenta paplašinājums

  - **Data\_SrcDoc\_FileFormat:long —** iepriekš definētu faila formāta vērtību kopa (detalizētāka par paplašinājumu).

  - **Data\_SrcDoc\_Fqdn:string —** dokumentu glabāšanas vieta (SharePoint.com, live.net), pieejama tikai Office 365 domēniem

  - **Data\_SrcDoc\_FqdnHash:string —** dokumenta glabāšanas vietas jaukšana

  - **Data\_SrcDoc\_IdentityTelemetryId:string —** unikāls lietotāja GUID

  - **Data\_SrcDoc\_IdentityUniqueId:string —** tās identitātes unikālais identifikators, kas tika izmantota koplietojamo dokumentu darbībai

  - **Data\_SrcDoc\_IOFlags:long —** bitmaska dažādiem ar IO saistītiem karodziņiem, kas attiecas uz dokumentu

  - **Data\_SrcDoc\_IrmRights:long —** iepriekš definētu vērtību kopa, kas attiecas uz informācijas piekļuves tiesību pārvaldības tipu, kas tiek lietots šim dokumentam (pārsūtīšana, atbildēšana, SecureReader, rediģēšana u.c.)

  - **Data\_SrcDoc\_IsCloudCollabEnabled:bool —** patiess, ja "IsCloudCollabEnabled" HTTP galvene jau ir saņemta no pieprasījuma OPTIONS.

  - **Data\_SrcDoc\_IsIncrementalOpen:bool —** vai dokuments tika atvērts inkrementāli (jauns līdzeklis, kas atver dokumentu bez vajadzības lejupielādēt visu dokumentu)

  - **Data\_SrcDoc\_IsOcsSupported:bool —** vai ir dokuments atbalsta koprediģēšanu, izmantojot jauno OCS pakalpojumu

  - **Data\_SrcDoc\_IsOpeningOfflineCopy:bool —** pārbauda, vai dokuments tiek atvērts no lokālās kešatmiņas

  - **Data\_SrcDoc\_IsSyncBacked:bool —** vai dokuments tiek atvērts no mapes, kas izmanto OneDrive sinhronizācijas programmu

  - **Data\_SrcDoc\_Location:long —** iepriekš definētu vērtību kopa, kas norāda dokumenta glabāšanas vietu (lokālā, SharePoint, WOPI, tīkls utt.)

  - **Data\_SrcDoc\_LocationDetails:long —** iepriekš definētu detalizētākas atrašanās vietas vērtību kopa (mape Temp, lejupielāžu mape, OneDrive dokumenti, OneDrive attēli utt.)

  - **Data\_SrcDoc\_NumberCoAuthors:long —** līdzautoru skaits dokumenta atvēršanas brīdī

  - **Data\_SrcDoc\_PasswordFlags:long —** iepriekš definētu vērtību kopa, kas norāda veidu, kā dokuments ir šifrēts ar paroli (nav, parole lasīšanai, parole rediģēšanai)

  - **Data\_SrcDoc\_ReadOnlyReasons:long —** iepriekš definētu vērtību kopa, kas norāda, kāpēc šis dokuments ir atzīmēts kā tikai lasāms (bloķēts serverī, pabeigts dokuments, aizsargāts ar paroli rediģēšanai utt.)

  - **Data\_SrcDoc\_ResourceIdHash:string —** resursu identifikatora jaukšana mākonī saglabātajiem dokumentiem

  - **Data\_SrcDoc\_ServerDocId:string —** nemainīgs identifikators mākonī saglabātajiem dokumentiem

  - **Data\_SrcDoc\_ServerProtocol:long —** iepriekš definētu vērtību kopa, kas norāda, kurš protokols tiek izmantots, lai sazinātos ar serveri (HTTP, Cobalt, WOPI utt.)

  - **Data\_SrcDoc\_ServerType:long —** iepriekš definētu vērtību kopas servera tipam (SharePoint, DropBox, WOPI)

  - **Data\_SrcDoc\_ServerVersion:long —** pārbauda, vai servera pamatā ir Office14, Office15 vai Office 16Data\_SrcDoc\_SessionId:long ģenerēts GUID, kas norāda dokumenta instanci tajā pašā procesa sesijā

  - **Data\_SrcDoc\_SharePointServiceContext:string —** necaurspīdīga virkne, parasti GridManagerID.FarmID. Noder, lai saistītu klienta un servera žurnālu

  - **Data\_SrcDoc\_SizeInBytes:long —** dokumenta lielums baitos

  - **Data\_SrcDoc\_SpecialChars:long —** bitmaska, kas norāda speciālās rakstzīmes dokumenta vietrādī URL vai ceļā

  - **Data\_SrcDoc\_StorageProviderId:string —** virkne, kas norāda dokumenta krātuves nodrošinātāju, piemēram, "DropBox"

  - **Data\_SrcDoc\_StreamAvailability:long —** iepriekš definētu dokumenta straumēšanas vērtību kopas statuss (pieejams, neatgriezeniski atspējots, nav pieejams)

  - **Data\_SrcDoc\_UrlHash:string —** pilna vietrāža URL jaukšana mākonī saglabātiem dokumentiem

  - **Data\_SrcDoc\_UsedWrsDataOnOpen:bool —** patiess, ja fails tika atvērts inkrementāli, izmantojot iepriekš kešotus WRS datus resursdatorā

  - **Data\_SrcDoc\_WopiServiceId:string —** WOPI pakalpojuma identifikators, piemēram, "Dropbox"

  - **Data\_StopwatchDuration:long —** kopējais darbības ilgums

  - **Data\_TypeOfSaveDialog:long —** iepriekš definētu vērtību kopa dialoglodziņam (RUN\_SAVEAS\_DLG, RUN\_SAVEMEDIA\_DLG, RUN\_SAVEAS\_VIDEO\_DLG utt.)

  - **DstDoc —** jaunā dokumenta atrašanās vieta

  - **SrcDoc —** sākotnējā dokumenta atrašanās vieta

#### <a name="officepowerpointdocoperationsavelegacy"></a>Office.PowerPoint.DocOperation.SaveLegacy

Apkopots ikreiz, kad PowerPoint veic saglabāšanu, izmantojot mantotā koda ceļu. Ietver saglabāšanas veiktspējas rādītāju rezultātu tipa panākumus un saistītos dokumenta metadatus. Saglabāšanas kļūmes var izraisīt datu zudumu. Microsoft izmanto šos datus, lai nodrošinātu, ka līdzeklis darbojas, kā paredzēts, un lietotāju saturs tiek sekmīgi turpināts.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_AddDocTelemetryResult:long —** vai šim žurnāla ierakstam ir visa nepieciešamā dokumenta telemetrija (Data\_Doc\_\* lauki)? Ja tā nav, kāpēc?

  - **Data\_CppUncaughtExceptionCount:long —** nenotverti vietējie izņēmumi darbības izpildes laikā

  - **Data\_DetachedDuration:long —** darbības atvienošanas/nedarbošanās ilgums

  - **Data\_Doc\_AccessMode:long —** kā šis dokuments ir atvērts (tikai lasāms | lasīšana un rakstīšana)

  - **Data\_Doc\_AssistedReadingReasons:long —** iepriekš definētu vērtību kopa, kas norāda, kāpēc dokuments ir atvērts pieejamā lasīšanas režīmā

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

  - **Data_Doc_IsRtcAlwaysOn —** patiess, ja reāllaika kanāls (RTC) šim failam vienmēr ir ieslēgts.

  - **Data\_Doc\_IsSyncBacked:bool —** vai dokuments tiek atvērts no mapes, kas izmanto OneDrive sinhronizācijas programmu

  - **Data\_Doc\_Location:long —** iepriekš definētu vērtību kopa, kas norāda dokumenta glabāšanas vietu (lokālā, SharePoint, WOPI, tīkls utt.)

  - **Data\_Doc\_LocationDetails:long —** iepriekš definētu detalizētākas atrašanās vietas vērtību kopa (mape Temp, lejupielāžu mape, OneDrive dokumenti, OneDrive attēli utt.)

  - **Data\_Doc\_NumberCoAuthors:long —** līdzautoru skaits dokumenta atvēršanas brīdī

  - **Data\_Doc\_PasswordFlags:long —** iepriekš definētu vērtību kopa, kas norāda veidu, kā dokuments ir šifrēts ar paroli (nav, parole lasīšanai, parole rediģēšanai)

  - **Data\_Doc\_ReadOnlyReasons:long —** iepriekš definētu vērtību kopa, kas norāda, kāpēc šis dokuments ir atzīmēts kā tikai lasāms (bloķēts serverī, pabeigts dokuments, aizsargāts ar paroli rediģēšanai utt.)

  - **Data\_Doc\_ResourceIdHash:string —** resursu identifikatora jaukšana mākonī saglabātajiem dokumentiem

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

  - **Data\_DstDoc\_AccessMode:long —** kā šis dokuments ir atvērts (tikai lasāms | lasīšana un rakstīšana)

  - **Data\_DstDoc\_AssistedReadingReasons:long —** iepriekš definētu vērtību kopa, kas norāda, kāpēc dokuments ir atvērts pieejamā lasīšanas režīmā

  - **Data\_DstDoc\_ChunkingType:long —** kā dokuments ir saglabāts pakalpojumā SharePoint

  - **Data\_DstDoc\_EdpState:long —** dokumenta uzņēmuma datu aizsardzība statuss

  - **Data\_DstDoc\_Ext:string —** dokumenta paplašinājums

  - **Data\_DstDoc\_Extension:string —** dokumenta paplašinājums

  - **Data\_DstDoc\_FileFormat:long —** iepriekš definētu faila formāta vērtību kopa (detalizētāka par paplašinājumu).

  - **Data\_DstDoc\_Fqdn:string —** dokumentu glabāšanas vieta (SharePoint.com, live.net), pieejama tikai Office 365 domēniem

  - **Data\_DstDoc\_FqdnHash:string —** dokumenta glabāšanas vietas jaukšana

  - **Data\_DstDoc\_IdentityTelemetryId:string —** unikāls lietotāja GUID

  - **Data\_DstDoc\_IdentityUniqueId:string —** tās identitātes unikālais identifikators, kas tika izmantota koplietojamo dokumentu darbībai

  - **Data\_DstDoc\_IOFlags:long —** bitmaska dažādiem ar IO saistītiem karodziņiem, kas attiecas uz dokumentu

  - **Data\_DstDoc\_IrmRights:long —** iepriekš definētu vērtību kopa, kas attiecas uz informācijas piekļuves tiesību pārvaldības tipu, kas tiek lietots šim dokumentam (pārsūtīšana, atbildēšana, SecureReader, rediģēšana u.c.)

  - **Data\_DstDoc\_IsCloudCollabEnabled:bool —** patiess, ja "IsCloudCollabEnabled" HTTP galvene jau ir saņemta no pieprasījuma OPTIONS.

  - **Data\_DstDoc\_IsIncrementalOpen:bool —** vai dokuments tika atvērts inkrementāli (jauns līdzeklis, kas atver dokumentu bez vajadzības lejupielādēt visu dokumentu)

  - **Data\_DstDoc\_IsOcsSupported:bool —** vai ir dokuments atbalsta koprediģēšanu, izmantojot jauno OCS pakalpojumu

  - **Data\_DstDoc\_IsOpeningOfflineCopy:bool —** pārbauda, vai dokuments tiek atvērts no lokālās kešatmiņas

  - **Data\_DstDoc\_IsSyncBacked:bool —** vai dokuments tiek atvērts no mapes, kas izmanto OneDrive sinhronizācijas programmu

  - **Data\_DstDoc\_Location:long —** iepriekš definētu vērtību kopa, kas norāda dokumenta glabāšanas vietu (lokālā, SharePoint, WOPI, tīkls utt.)

  - **Data\_DstDoc\_LocationDetails:long —** iepriekš definētu detalizētākas atrašanās vietas vērtību kopa (mape Temp, lejupielāžu mape, OneDrive dokumenti, OneDrive attēli utt.)

  - **Data\_DstDoc\_NumberCoAuthors:long —** līdzautoru skaits dokumenta atvēršanas brīdī

  - **Data\_DstDoc\_PasswordFlags:long —** iepriekš definētu vērtību kopa, kas norāda veidu, kā dokuments ir šifrēts ar paroli (nav, parole lasīšanai, parole rediģēšanai)

  - **Data\_DstDoc\_ReadOnlyReasons:long —** iepriekš definētu vērtību kopa, kas norāda, kāpēc šis dokuments ir atzīmēts kā tikai lasāms (bloķēts serverī, pabeigts dokuments, aizsargāts ar paroli rediģēšanai utt.)

  - **Data\_DstDoc\_ResourceIdHash:string —** resursu identifikatora jaukšana mākonī saglabātajiem dokumentiem

  - **Data\_DstDoc\_ServerDocId:string —** nemainīgs identifikators mākonī saglabātajiem dokumentiem

  - **Data\_DstDoc\_ServerProtocol:long —** iepriekš definētu vērtību kopa, kas norāda, kurš protokols tiek izmantots, lai sazinātos ar serveri (HTTP, Cobalt, WOPI utt.)

  - **Data\_DstDoc\_ServerType:long —** iepriekš definētu vērtību kopas servera tipam (SharePoint, DropBox, WOPI)

  - **Data\_DstDoc\_ServerVersion:long —** pārbauda, vai servera pamatā ir Office14, Office15 vai Office 16

  - **Data\_DstDoc\_SessionId:long —** ģenerēts GUID, kas norāda dokumenta instanci tajā pašā procesa sesijā

  - **Data\_DstDoc\_SharePointServiceContext:string —** necaurspīdīga virkne, parasti GridManagerID.FarmID. Noder, lai saistītu klienta un servera žurnālu

  - **Data\_DstDoc\_SizeInBytes:long —** dokumenta lielums baitos

  - **Data\_DstDoc\_SpecialChars:long —** bitmaska, kas norāda speciālās rakstzīmes dokumenta vietrādī URL vai ceļā

  - **Data\_DstDoc\_StorageProviderId:string —** virkne, kas norāda dokumenta krātuves nodrošinātāju, piemēram, "DropBox"

  - **Data\_DstDoc\_StreamAvailability:long —** iepriekš definētu dokumenta straumēšanas vērtību kopas statuss (pieejams, neatgriezeniski atspējots, nav pieejams)

  - **Data\_DstDoc\_UrlHash:string —** pilna vietrāža URL jaukšana mākonī saglabātiem dokumentiem

  - **Data\_DstDoc\_UsedWrsDataOnOpen:bool —** patiess, ja fails tika atvērts inkrementāli, izmantojot iepriekš kešotus WRS datus resursdatorā

  - **Data\_DstDoc\_WopiServiceId:string —** WOPI pakalpojuma identifikators, piemēram, "Dropbox"

  - **Data\_FileType:long —** iepriekš definētu iekšējā faila tipa vērtību kopa

  - **Data\_fLifeguarded:bool —** vai dokuments kādreiz ir bijis aizsargāts (līdzeklis, lai izlabotu dokumenta kļūdas, neziņojot par to lietotājam)?

  - **Data\_SaveReason:long —** iepriekš definētu vērtību kopa, kas norāda, kāpēc tika veikta saglabāšana (Automātiskā saglabāšana, ToOCSTransitionSave, ToCSITransitionSave utt.)

  - **Data\_SaveType:long —** iepriekš definētu vērtību kopa saglabāšanas tipam (SaveAs, Publish, Manual, OMSave utt.)

  - **Data\_SrcDoc\_AccessMode:long —** kā šis dokuments ir atvērts (tikai lasāms | lasīšana un rakstīšana)

  - **Data\_SrcDoc\_AssistedReadingReasons:long —** iepriekš definētu vērtību kopa, kas norāda, kāpēc dokuments ir atvērts pieejamā lasīšanas režīmā

  - **Data\_SrcDoc\_ChunkingType:long —** kā dokuments ir saglabāts pakalpojumā SharePoint

  - **Data\_SrcDoc\_EdpState:long —** dokumenta uzņēmuma datu aizsardzība statuss

  - **Data\_SrcDoc\_Ext:string —** dokumenta paplašinājums

  - **Data\_SrcDoc\_Extension:string —** dokumenta paplašinājums

  - **Data\_SrcDoc\_FileFormat:long —** iepriekš definētu faila formāta vērtību kopa (detalizētāka par paplašinājumu).

  - **Data\_SrcDoc\_Fqdn:string —** dokumentu glabāšanas vieta (SharePoint.com, live.net), pieejama tikai Office 365 domēniem

  - **Data\_SrcDoc\_FqdnHash:string —** dokumenta glabāšanas vietas jaukšana

  - **Data\_SrcDoc\_IdentityTelemetryId:string —** unikāls lietotāja GUID

  - **Data\_SrcDoc\_IdentityUniqueId:string —** tās identitātes unikālais identifikators, kas tika izmantota koplietojamo dokumentu darbībai

  - **Data\_SrcDoc\_IOFlags:long —** bitmaska dažādiem ar IO saistītiem karodziņiem, kas attiecas uz dokumentu

  - **Data\_SrcDoc\_IrmRights:long —** iepriekš definētu vērtību kopa, kas attiecas uz informācijas piekļuves tiesību pārvaldības tipu, kas tiek lietots šim dokumentam (pārsūtīšana, atbildēšana, SecureReader, rediģēšana u.c.)

  - **Data\_SrcDoc\_IsCloudCollabEnabled:bool —** patiess, ja "IsCloudCollabEnabled" HTTP galvene jau ir saņemta no pieprasījuma OPTIONS.

  - **Data\_SrcDoc\_IsIncrementalOpen:bool —** vai dokuments tika atvērts inkrementāli (jauns līdzeklis, kas atver dokumentu bez vajadzības lejupielādēt visu dokumentu)

  - **Data\_SrcDoc\_IsOcsSupported:bool —** vai ir dokuments atbalsta koprediģēšanu, izmantojot jauno OCS pakalpojumu

  - **Data\_SrcDoc\_IsOpeningOfflineCopy:bool —** pārbauda, vai dokuments tiek atvērts no lokālās kešatmiņas

  - **Data\_SrcDoc\_IsSyncBacked:bool —** vai dokuments tiek atvērts no mapes, kas izmanto OneDrive sinhronizācijas programmu

  - **Data\_SrcDoc\_Location:long —** iepriekš definētu vērtību kopa, kas norāda dokumenta glabāšanas vietu (lokālā, SharePoint, WOPI, tīkls utt.)

  - **Data\_SrcDoc\_LocationDetails:long —** iepriekš definētu detalizētākas atrašanās vietas vērtību kopa (mape Temp, lejupielāžu mape, OneDrive dokumenti, OneDrive attēli utt.)

  - **Data\_SrcDoc\_NumberCoAuthors:long —** līdzautoru skaits dokumenta atvēršanas brīdī

  - **Data\_SrcDoc\_PasswordFlags:long —** iepriekš definētu vērtību kopa, kas norāda veidu, kā dokuments ir šifrēts ar paroli (nav, parole lasīšanai, parole rediģēšanai)

  - **Data\_SrcDoc\_ReadOnlyReasons:long —** iepriekš definētu vērtību kopa, kas norāda, kāpēc šis dokuments ir atzīmēts kā tikai lasāms (bloķēts serverī, pabeigts dokuments, aizsargāts ar paroli rediģēšanai utt.)

  - **Data\_SrcDoc\_ResourceIdHash:string —** resursu identifikatora jaukšana mākonī saglabātajiem dokumentiem

  - **Data\_SrcDoc\_ServerDocId:string —** nemainīgs identifikators mākonī saglabātajiem dokumentiem

  - **Data\_SrcDoc\_ServerProtocol:long —** iepriekš definētu vērtību kopa, kas norāda, kurš protokols tiek izmantots, lai sazinātos ar serveri (HTTP, Cobalt, WOPI utt.)

  - **Data\_SrcDoc\_ServerType:long —** iepriekš definētu vērtību kopas servera tipam (SharePoint, DropBox, WOPI)

  - **Data\_SrcDoc\_ServerVersion:long —** pārbauda, vai servera pamatā ir Office14, Office15 vai Office 16

  - **Data\_SrcDoc\_SessionId:long —** ģenerēts GUID, kas norāda dokumenta instanci tajā pašā procesa sesijā

  - **Data\_SrcDoc\_SharePointServiceContext:string —** necaurspīdīga virkne, parasti GridManagerID.FarmID. Noder, lai saistītu klienta un servera žurnālu

  - **Data\_SrcDoc\_SizeInBytes:long —** dokumenta lielums baitos

  - **Data\_SrcDoc\_SpecialChars:long —** bitmaska, kas norāda speciālās rakstzīmes dokumenta vietrādī URL vai ceļā

  - **Data\_SrcDoc\_StorageProviderId:string —** virkne, kas norāda dokumenta krātuves nodrošinātāju, piemēram, "DropBox"

  - **Data\_SrcDoc\_StreamAvailability:long —** iepriekš definētu dokumenta straumēšanas vērtību kopas statuss (pieejams, neatgriezeniski atspējots, nav pieejams)

  - **Data\_SrcDoc\_UrlHash:string —** pilna vietrāža URL jaukšana mākonī saglabātiem dokumentiem

  - **Data\_SrcDoc\_UsedWrsDataOnOpen:bool —** patiess, ja fails tika atvērts inkrementāli, izmantojot iepriekš kešotus WRS datus resursdatorā

  - **Data\_SrcDoc\_WopiServiceId:string —** WOPI pakalpojuma identifikators, piemēram, "Dropbox"

  - **Data\_StopwatchDuration:long —** kopējais darbības ilgums

  - **Data\_TypeOfSaveDialog:long —** iepriekš definētu vērtību kopa dialoglodziņam (RUN\_SAVEAS\_DLG, RUN\_SAVEMEDIA\_DLG, RUN\_SAVEAS\_VIDEO\_DLG utt.)

  - **Doc —** pašreizējais dokuments saglabāšanai

  - **DstDoc —** jaunā dokumenta atrašanās vieta (darbībai Saglabāt kā)

  - **SrcDoc —** sākotnējā dokumenta atrašanās vieta (darbībai Saglabāt kā)

#### <a name="officepowerpointpptsharedslideshowfailure"></a>Office.PowerPoint.PPT.Shared.SlideShow.Failure

Apkopo slaidrādes laikā radušās kļūmes. Slaidrāde ir būtisks PowerPoint līdzeklis. Microsoft apkopo datus par kļūdām slaidrādes laikā, lai palīdzētu uzlabot slaidrādes lietošanas iespējas. Microsoft izmanto šos datus, lai iegūtu diagnostikas informāciju par vietu, kur notika kļūda, kamēr lietotājs izmantoja slaidrādi

Tiek apkopoti tālāk norādītie lauki.

  - **CountSlideShowErrors** — kopējais slaidrādes kļūdu skaits

  - **CountPPTErrors** — kopējais PPT kļūdu skaits

  - **CountOArtErrors** — kopējais OArt kļūdu skaits

  - **CountOtherErrors** — kopējais pārējo kļūdu skaits

  - **FirstSlideShowError** — pirmā kļūda slaidrādē

  - **FirstOArtError** — pirmā OArt kļūda

  - **FirstPPTError** — pirmā PPT kļūda

  - **FirstOtherError** — pirmā kļūda citā apgabalā

#### <a name="officeprojectprojectfilesave"></a>Office.Project.ProjectFileSave

Project saglabā failu. Šis notikums norāda Project saglabāto failu. Tas ļauj korporācijai Microsoft novērtēt Project faila saglabāšanas panākumus, kas ir svarīgi, lai novērstu datu zudumu.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_TriggerTime** — saglabāšanas laiks

  - **Data\_FileType** — saglabātā projekta faila tips
 
#### <a name="officesessionactivitystart"></a>Office.Session.Activity.Start

Ļauj uzzināt, kad tiek sākta datu straumēšanas sesija.  Izmanto līdzekļu darbspējas veicināšanai un pārraudzībai. Šo notikumu ģenerē Microsoft Data Streamer Excel pievienojumprogrammai.

Tiek apkopoti tālāk norādītie lauki.

- **Activity_Name** — darbības "Session" nosaukums

- **Activity_CV** — ID, kas saista savienojuma sesijas notikumus

- **Activity_StartStopType** — sākums

- **Activity_DateTimeTicks** — darbības datums un laiks

#### <a name="officesessionactivitystop"></a>Office.Session.Activity.Stop

Ļauj uzzināt, kad tiek pārtraukta datu straumēšanas sesija. Izmanto līdzekļa veiktspējas uzlabošanai un pārraudzībai. Šo notikumu ģenerē Microsoft Data Streamer Excel pievienojumprogrammai.

Tiek apkopoti tālāk norādītie lauki.

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

  - **Data.actionSource —** kā tika izraisīta tulkošanas atlase

  - **Data.bodyBackgroundColor —** Office dizaina konteinera fona krāsa

  - **Data.bodyForegroundColor —** Office dizaina konteinera priekšplāna krāsa

  - **Data.browserLang —** pašreizējā pārlūkprogrammas interfeisa valoda

  - **Data.browserOnline —** novecojis

  - **Data.browserPlatform —** pārlūkprogrammas platforma

  - **Data.browserUserAgent —** pārlūkprogrammas lietotāja aģents

  - **Data.colorDepth —** sistēmas krāsu dziļums

  - **Data.contentLanguage —** noteiktā tulkojamā satura valoda

  - **Data.controlBackgroundColor —** Office dizaina kontroles fona krāsa

  - **Data.controlForegroundColor —** Office dizaina kontroles priekšplāna krāsa

  - **Data.correlationId —** uz pakalpojumu nosūtītā pieprasījuma unikālais identifikators

  - **Data.crossSessionId —** — lietotāja unikālais identifikators

  - **Data.crossSessionStartTime —** tulkošanas sesijas sākuma UTC laikspiedols

  - **Data.currentTime —** UTC laikspiedols, kas norāda, kad tika nosūtīts šis telemetrijas ziņojums

  - **Data.displayLanguage —** Office interfeisa valoda

  - **Data.documentSourceLang —** dokumenta satura valoda

  - **Data.documentTargetLang —** valoda, uz kuru ir jātulko dokuments

  - **Data.environment —** tā pakalpojuma vide, uz kuru tiek nosūtīts pieprasījums

  - **Data.errorMessage —** pakalpojuma reģistrētais kļūdas ziņojums

  - **Data.eventActionType —** telemetrijas notikuma tips

  - **Data.eventTagId —** tās kodu rindas unikālais identifikators, kas izraisīja šo telemetrijas ziņojumu

  - **Data.flights —** iespējotie testējamie varianti

  - **Data.fileSize —** tulkojamā Word faila lielums

  - **Data.fileSource —** vieta, kur tiek viesots Word fails (tiešsaistē, bezsaistē)

  - **Data.fileType —** Word faila paplašinājums

  - **Data.innerHeight" —** sānu rūts konteinera augstums

  - **Data.innerWidth" —** sānu rūts konteinera platums

  - **Data.lookupSourceLang —** netiek izmantots dokumenta tulkošanai

  - **Data.lookupTargetLang —** netiek izmantots dokumenta tulkošanai

  - **Data.officeHost —** Office lietojumprogramma, kas vieso sānu rūti

  - **Data.officeLocale —** Office lietotāja valoda

  - **Data.officeMachineId —** ierīces unikālais identifikators

  - **Data.officePlatform —** ierīces platforma

  - **Data.officeSessionId —** Office sesijas identifikators

  - **Data.officeUserId —** Office lietotāja unikālais identifikators

  - **Data.officeVersion —** Office versija

  - **Data.pageXOffset —** rūts horizontālās ritjoslas pozīcija no rūts kreisās puses

  - **Data.pageYOffset —** rūts vertikālās ritjoslas pozīcija no rūts augšpuses

  - **Data.pixelDepth —** ekrāna krāsas izšķirtspēja

  - **Data.responseCode —** pieprasījuma atbildes kods no pakalpojuma

  - **Data.responseTime —** pieprasījuma pagājušais laiks

  - **Data.resultType —** pieprasījuma rezultāts

  - **Data.screenHeight —** ekrāna augstums pikseļos

  - **Data.screenLeft —** loga horizontālā koordināta attiecībā pret ekrānu

  - **Data.screenTop —** loga vertikālā koordināta attiecībā pret ekrānu

  - **Data.screenWidth —** ekrāna platums pikseļos

  - **Data.selectedTab —** kura ir atlasītā cilne: atlase vai dokuments

  - **Data.serverUrl —** tulkošanas pakalpojuma URL

  - **Data.sessionId —** sānu rūts sesijas identifikators

  - **Data.SessionStartTime —** tulkošanas sesijas sākuma UTC laikspiedols

  - **Data.sourceTextHash —** tulkojamā teksta jaukšana

  - **Data.sourceTextLength —** tulkojamā teksta garums

  - **Data.sourceTextWords —** tulkojamā teksta vārdu skaits

  - **Data.warningMessage —** pakalpojuma reģistrētais brīdinājuma ziņojums

#### <a name="officetranslatortexttranslated"></a>Office.Translator.TextTranslated

Apkopo tās atlases tulkojuma panākumus, kuru izraisīja lietotāja darbība, izmantojot tulkošanas SDX. Tas ir svarīgi, lai novērtētu tulkošanas līdzekļa darbspēju un reaģētu uz iespējamiem darbības pārtraukumiem. Izmanto, lai pārraudzītu atlases tulkošanas scenārija darbspēju programmā Excel, PowerPoint un Word.

Tiek apkopoti tālāk norādītie lauki.

  - **Data.actionSource —** kā tika izraisīta tulkošanas atlase

  - **Data.bodyBackgroundColor —** Office dizaina konteinera fona krāsa

  - **Data.bodyForegroundColor —** Office dizaina konteinera priekšplāna krāsa

  - **Data.browserLang —** pašreizējā pārlūkprogrammas interfeisa valoda

  - **Data.browserOnline —** novecojis

  - **Data.browserPlatform —** pārlūkprogrammas platforma

  - **Data.browserUserAgent —** pārlūkprogrammas lietotāja aģents

  - **Data.colorDepth —** sistēmas krāsu dziļums

  - **Data.contentLanguage —** noteiktā tulkojamā satura valoda

  - **Data.controlBackgroundColor —** Office dizaina kontroles fona krāsa

  - **Data.controlForegroundColor —** Office dizaina kontroles priekšplāna krāsa

  - **Data.correlationId —** uz pakalpojumu nosūtītā pieprasījuma unikālais identifikators

  - **Data.crossSessionId —** — lietotāja unikālais identifikators

  - **Data.crossSessionStartTime —** tulkošanas sesijas sākuma UTC laikspiedols

  - **Data.currentTime —** UTC laikspiedols, kas norāda, kad tika nosūtīts šis telemetrijas ziņojums

  - **Data.displayLanguage —** Office interfeisa valoda

  - **Data.documentSourceLang —** netiek izmantots atlasei

  - **Data.documentTargetLang —** netiek izmantots tulkojuma atlasei

  - **Data.environment —** tā pakalpojuma vide, uz kuru tiek nosūtīts pieprasījums

  - **Data.errorMessage —** pakalpojuma reģistrētais kļūdas ziņojums

  - **Data.eventActionType —** telemetrijas notikuma tips

  - **Data.eventTagId —** tās kodu rindas unikālais identifikators, kas izraisīja šo telemetrijas ziņojumu

  - **Data.flights —** iespējotie testējamie varianti

  - **Data.innerHeight —** sānu rūts konteinera augstums

  - **Data.innerWidth —** sānu rūts konteinera platums

  - **Data.lookupSourceLang —** pašreiz atlasītā teksta valoda

  - **Data.lookupTargetLang —** pašlaik atlasītā teksta valoda, kurā tiks veikts tulkojums

  - **Data.officeHost —** Office lietojumprogramma, kas vieso sānu rūti

  - **Data.officeLocale —** Office lietotāja valoda

  - **Data.officeMachineId —** ierīces unikālais identifikators

  - **Data.officePlatform —** ierīces platforma

  - **Data.officeSessionId —** Office sesijas identifikators

  - **Data.officeUserId —** Office lietotāja unikālais identifikators

  - **Data.officeVersion —** Office versija

  - **Data.pageXOffset —** rūts horizontālās ritjoslas pozīcija no rūts kreisās puses

  - **Data.pageYOffset —** rūts vertikālās ritjoslas pozīcija no rūts augšpuses

  - **Data.pixelDepth —** ekrāna krāsas izšķirtspēja

  - **Data.responseCode —** pieprasījuma atbildes kods no pakalpojuma

  - **Data.responseTime —** pieprasījuma pagājušais laiks

  - **Data.resultType —** pieprasījuma rezultāts

  - **Data.screenHeight —** ekrāna augstums pikseļos

  - **Data.screenLeft —** loga horizontālā koordināta attiecībā pret ekrānu

  - **Data.screenTop —** loga vertikālā koordināta attiecībā pret ekrānu

  - **Data.screenWidth —** ekrāna platums pikseļos

  - **Data.selectedTab —** kura ir atlasītā cilne: atlase vai dokuments

  - **Data.serverUrl —** tulkošanas pakalpojuma URL

  - **Data.sessionId —** sānu rūts sesijas identifikators

  - **Data.SessionStartTime —** tulkošanas sesijas sākuma UTC laikspiedols

  - **Data.sourceTextHash —** tulkojamā teksta jaukšana

  - **Data.sourceTextLength —** tulkojamā teksta garums

  - **Data.sourceTextWords —** tulkojamā teksta vārdu skaits

  - **Data.warningMessage —** pakalpojuma reģistrētais brīdinājuma ziņojums

#### <a name="officewordexperimentationdocumentstatsoncloseandsuspend"></a>Office.Word.Experimentation.DocumentStatsOnCloseAndSuspend

Šis notikums reģistrē katra dokumenta statistiku, kad Office Word ir aizvērts vai aizturēts.

Notikumu izmanto, lai saistītu dokumenta rediģēšanu, lielumu utt. ar dokumenta saglabāšanas, dokumenta kopīgošanas un dokumenta tiešsaistes koprediģēšanas kļūdām.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_BkmkRefCount —** grāmatzīmju atsauču skaits dokumentā

  - **Data\_CharacterCount —** rakstzīmju skaits dokumentā

  - **Data\_CharactersWithSpaceCount —** rakstzīmju un atstarpju skaits dokumentā

  - **Data\_ChartCount —** diagrammu skaits dokumentā

  - **Data\_CitationCount —** citātu skaits dokumentā

  - **Data\_DocumentLocation —** norāda pakalpojumu, kurā atrodas dokuments (OneDrive, File Server, SharePoint utt.)

  - **Data\_ETW\_TrackbackTag —** norāda vietu kodā, kur šis notikums ir aktivizēts (aizvēršana vai aizturēšana)

  - **Data\_EndnoteDocCount —** beigu vēru skaits dokumentā

  - **Data\_FootnoteDocCount —** vēru skaits dokumentā

  - **Data\_HasBibliography —** norāda, vai dokumentā ir bibliogrāfija

  - **Data\_HasHeader —** norāda, vai dokumentā ir galvene

  - **Data\_IsImeUsed —** norāda, vai dokumentā tiek izmantots ievades metodes redaktors

  - **Data\_IsPageCountInProgress —** norāda, vai pašlaik dokumentā notiek lappušu skaitīšana.

  - **Data\_IsTouchUsed —** norāda, vai dokumentā tika izmantota skārienievade

  - **Data\_IsTrackChangesOn —** norāda, vai dokumentā tiek reģistrētas izmaiņas

  - **Data\_LineCount —** rindiņu skaits dokumentā

  - **Data\_MainPdod —** dokumenta identifikators Office Word procesā.

  - **Data\_PageCount —** lapu skaits dokumentā

  - **Data\_PageNumberFieldCount —** lappušu numuru lauku skaits dokumentā

  - **Data\_ParagraphCount —** rindkopu skaits dokumentā

  - **Data\_PicCount —** attēlu skaits dokumentā

  - **Data\_RsidCount —** labojumu saglabāšanas identifikatoru skaits dokumentā

  - **Data\_TocCount —** satura rādītāju skaits dokumentā

  - **Data\_UrlHash —** vienvirziena jaukšana vienkāršota dokumenta identifikatora izveidei

  - **Data\_UserActionID —** šis datu lauks netiek lietots (vērtība vienmēr ir 0).

  - **Data\_UserActionName —** vienmēr "DocumentStatsOnCloseAndSuspend"

  - **Data\_UserInteractionTimeMsec —** cik milisekunžu lietotājs aktīvi mijiedarbojās ar dokumentu

  - **Data\_WordCount —** vārdu skaits dokumentā

#### <a name="officewordfilenewcreatenewfile"></a>Office.Word.FileNew.CreateNewFile

Šis notikums norāda, ka ir izveidots jauns Office Word dokuments un seko šīs darbības panākumu statusam. Notikums tiek izmantots, lai pārraudzītu jaunā dokumenta izveides pareizu darbību. To izmanto arī, lai aprēķinātu mēneša aktīvos lietotājus/ierīces un mākoņpakalpojumu uzticamības rādītājus.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_DirtyState** — vai dokuments tika izveidots mainītā statusā (ar nesaglabātām izmaiņām)

  - **Data\_ErrorID** — identifikators darbības kļūmes gadījumā

  - **Data\_MainPdod —** dokumenta identifikators šī procesa laikā.

  - **Data\_UsesCustomTemplate** — norāda, vai dokuments ir izveidots, izmantojot pielāgotu veidni

#### <a name="officewordfilesaveactcmdgosubsaveas"></a>Office.Word.FileSave.ActCmdGosubSaveAs

Šis notikums norāda, ka lietotājs saglabā izmaiņas jaunā dokumentā. Notikums pārrauga jauna dokumenta saglabāšanas pareizu darbību. To izmanto arī, lai aprēķinātu mēneša aktīvos lietotājus/ierīces un mākoņpakalpojumu uzticamības rādītājus.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_AddDocTelemRes —** norāda, vai mēs varam pareizi aizpildīt citas ar dokumentu telemetriju saistītās vērtības šajā notikumā. Izmanto datu kvalitātes diagnostikai.

  - **Data\_DetachedDuration —** cik ilgi darbība bija atdalīta no pavediena

  - **Data\_Doc\_AccessMode —** dokuments ir tikai lasāms/rediģējams

  - **Data\_Doc\_AssistedReadingReasons —** iepriekš definētu vērtību kopa, kas norāda, kāpēc dokuments ir atvērts pieejamā lasīšanas režīmā

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

  - **Data_Doc_IsRtcAlwaysOn —** patiess, ja reāllaika kanāls (RTC) šim failam vienmēr ir ieslēgts.

  - **Data\_Doc\_IsSyncBacked —** karodziņš, kas norāda, ka datorā pastāv automātiski sinhronizēta dokumenta kopija

  - **Data\_Doc\_Location —** norāda pakalpojumu, kurā atrodas dokuments (OneDrive, File Server, SharePoint utt.)

  - **Data\_Doc\_LocationDetails —** norāda, kurā zināmajā mapē atrodas lokāli saglabātais dokuments

  - **Data\_Doc\_NumberCoAuthors —** citu lietotāju skaits koprediģēšanas sesijā

  - **Data\_Doc\_PasswordFlags —** norāda lasīšanas/rakstīšanas paroles karodziņu kopu

  - **Data\_Doc\_ReadOnlyReasons —** iemesli, kāpēc dokuments ir atvērts tikai lasāmajā režīmā

  - **Data\_Doc\_ResourceIdHash —** anonimizēts dokumenta identifikators, ko izmanto problēmu noteikšanā

  - **Data\_Doc\_ServerDocId —** nemainīgs anonimizēts dokumenta identifikators, ko izmanto problēmu noteikšanā

  - **Data\_Doc\_ServerProtocol —** tā protokola versija, ko izmanto, lai sazinātos ar pakalpojumu

  - **Data\_Doc\_ServerType —** tā servera tips, kas nodrošina pakalpojumu (OneDrive, SharePoint, WOPI utt.)

  - **Data\_Doc\_ServerVersion —** tā servera versija, kas nodrošina pakalpojumu

  - **Data\_Doc\_SessionId —** identificē konkrētu dokumenta rediģēšanas sesiju pilnā sesijā

  - **Data\_Doc\_SharePointServiceContext —** diagnostikas informācija no SharePoint Online pieprasījumiem

  - **Data\_Doc\_SizeInBytes —** dokumenta lieluma rādītājs

  - **Data\_Doc\_SpecialChars —** speciālo rakstzīmju rādītājs dokumenta vietrādī URL vai ceļā

  - **Data\_Doc\_StreamAvailability —** norāda, vai ir pieejama/atspējota dokumenta plūsma

  - **Data\_Doc\_SyncBackedType —** norāda dokumenta veidu (lokālais vai servera)

  - **Data\_Doc\_UrlHash —** vienvirziena jaukšana vienkāršota dokumenta identifikatora izveidei

  - **Data\_EditorDisablingRename —** tā pirmā redaktora identifikators, kas izraisīja pārdēvēšanas atspējošanu

  - **Data\_EditorsCount —** redaktoru skaits dokumentā

  - **Data\_LastLoggedTag —** unikāla atzīme koda izsaukuma vietā, ko izmanto, lai noteiktu, kad neizdodas saglabāt divreiz (izmanto datu kvalitātes diagnostikai)

  - **Data\_MoveDisabledReason —** kļūda, kas atspējo dokumenta pārvietošanu

  - **Data\_MoveFlightEnabled —** vai testējamā varianta opcija pārvietošanas līdzeklī ir iespējota

  - **Data\_RenameDisabledReason —** kļūda, kuras dēļ tiek atspējota dokumenta pārdēvēšana

  - **Data\_RenameFlightEnabled —** vai testējamā varianta opcija pārdēvēšanas līdzeklī ir iespējota

#### <a name="officewordfilesaveactfconfirmsavedoccoreautorecoverysave"></a>Office.Word.FileSave.ActFConfirmSaveDocCoreAutoRecoverySave

Šis notikums norāda, ka Office Word saglabā automātiski atkoptu dokumentu, kas nav bijis saglabāts iepriekš. Tādējādi Microsoft var noteikt automātiskās atkopšanas kļūdas, kam ir būtiska nozīme dokumenta datu aizsardzībā.

Notikums pārrauga automātiski atkopta dokumenta saglabāšanas pareizu darbību. To izmanto arī, lai aprēķinātu mēneša aktīvos lietotājus/ierīces un mākoņpakalpojumu uzticamības rādītājus.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_DetachedDuration —** cik ilgi darbība bija atdalīta no pavediena

  - **Data\_Doc\_AccessMode —** dokuments ir tikai lasāms/rediģējams

  - **Data\_Doc\_AssistedReadingReasons —** iepriekš definētu vērtību kopa, kas norāda, kāpēc dokuments ir atvērts pieejamā lasīšanas režīmā

  - **Data\_Doc\_ChunkingType —** vienības, kas tiek izmantotas inkrementālā dokumenta atvēršanā

  - **Data\_Doc\_EdpState —** dokumenta elektronisko datu aizsardzības iestatījums

  - **Data\_Doc\_Ext —** dokumentu paplašinājums (docx/xlsb/pptx utt.)

  - **Data\_Doc\_FileFormat —** faila formāta protokola versija

  - **Data\_Doc\_Fqdn —** OneDrive vai SharePoint Online domēna nosaukums

  - **Data\_Doc\_FqdnHash —** klientu identificējama domēna nosaukuma vienvirziena jaukšana

  - **Data\_Doc\_IdentityTelemetryId —** tādas lietotāja identitātes vienvirziena jaukšana, kas tiek izmantota atvēršanā

  - **Data\_Doc\_InitializationScenario —** dokumenta atvēršanas ieraksti

  - **Data\_Doc\_IOFlags —** atskaites par kešotajiem karodziņiem, kas tiek izmantoti pieprasījuma opciju iestatīšanai

  - **Data\_Doc\_IrmRights —** dokumentam/lietotājam piemērotās elektronisko datu politikas atļautās darbības

  - **Data\_Doc\_IsIncrementalOpen —** karodziņš, kas norāda, ka dokuments ir atvērts inkrementāli

  - **Data\_Doc\_IsOcsSupported —** karodziņš, kas norāda, ka dokuments tiek atbalstīts sadarbības pakalpojumā

  - **Data\_Doc\_IsOpeningOfflineCopy —** atzīme, kas norāda, ka tika atvērta dokumenta bezsaistes kopija

  - **Data_Doc_IsRtcAlwaysOn —** patiess, ja reāllaika kanāls (RTC) šim failam vienmēr ir ieslēgts.

  - **Data\_Doc\_IsSyncBacked —** karodziņš, kas norāda, ka datorā pastāv automātiski sinhronizēta dokumenta kopija

  - **Data\_Doc\_Location —** norāda pakalpojumu, kurā atrodas dokuments (OneDrive, File Server, SharePoint utt.)

  - **Data\_Doc\_LocationDetails —** norāda, kurā zināmajā mapē atrodas lokāli saglabātais dokuments

  - **Data\_Doc\_NumberCoAuthors —** citu lietotāju skaits koprediģēšanas sesijā

  - **Data\_Doc\_PasswordFlags —** norāda lasīšanas/rakstīšanas paroles karodziņu kopu

  - **Data\_Doc\_ReadOnlyReasons —** iemesli, kāpēc dokuments ir atvērts tikai lasāmajā režīmā

  - **Data\_Doc\_ResourceIdHash —** anonimizēts dokumenta identifikators, ko izmanto problēmu noteikšanā

  - **Data\_Doc\_ServerDocId —** nemainīgs anonimizēts dokumenta identifikators, ko izmanto problēmu noteikšanā

  - **Data\_Doc\_ServerProtocol —** tā protokola versija, ko izmanto, lai sazinātos ar pakalpojumu

  - **Data\_Doc\_ServerType —** tā servera tips, kas nodrošina pakalpojumu (OneDrive, SharePoint, WOPI utt.)

  - **Data\_Doc\_ServerVersion —** tā servera versija, kas nodrošina pakalpojumu

  - **Data\_Doc\_SessionId —** identificē konkrētu dokumenta rediģēšanas sesiju pilnā sesijā

  - **Data\_Doc\_SharePointServiceContext —** diagnostikas informācija no SharePoint Online pieprasījumiem

  - **Data\_Doc\_SizeInBytes —** dokumenta lieluma rādītājs

  - **Data\_Doc\_SpecialChars —** speciālo rakstzīmju rādītājs dokumenta vietrādī URL vai ceļā

  - **Data\_Doc\_StreamAvailability —** norāda, vai ir pieejama/atspējota dokumenta plūsma

  - **Data\_Doc\_SyncBackedType —** norāda dokumenta veidu (lokālais vai servera)

  - **Data\_Doc\_UrlHash —** vienvirziena jaukšana vienkāršota dokumenta identifikatora izveidei

  - **Data\_Doc\_WopiServiceId —** satur unikālu WOPI pakalpojumu sniedzēja identifikatoru

  - **Data\_FailureClass —** skaitlis, kas atspoguļo Office sadarbības pakalpojumu (Office Collaboration Services — OCS) pārejas kļūmju kļūmes klasi

  - **Data\_MainPdod —** dokumenta identifikators Office Word procesā.

  - **Data\_MoveFlightEnabled —** vai testējamā varianta opcija pārvietošanas līdzeklī ir iespējota

  - **Data\_OCSSyncbackSaveStarted —** karodziņš, kas norāda, ka saglabātais dokuments ir saistīts ar sinhronizēto saglabāšanu

  - **Data\_RenameDisabledReason —** kļūda, kuras dēļ tiek atspējota dokumenta pārdēvēšana

  - **Data\_RenameFlightEnabled —** vai testējamā varianta opcija pārdēvēšanas līdzeklī ir iespējota

  - **Data\_SaveInitiateKind —** vesels skaitlis, kas norāda, kā tika sākta saglabāšana

  - **Data\_SrcDocIsUnnamedOrNew —** norāda, vai saglabājamais dokuments ir jauns

#### <a name="officewordfilesaveactfconfirmsavedoccorequerysave"></a>Office.Word.FileSave.ActFConfirmSaveDocCoreQuerySave

Šis notikums norāda, ka Office Word aicina lietotāju saglabāt izmaiņas, kad tiek mēģināts aizvērt dokumentu. Tas ļauj korporācijai Microsoft pārraudzīt, vai saglabāšana pēc programmas aizvēršanas darbojas pareizi un netiek zaudēti dati. Notikums pārrauga, vai dokumenta saglabāšana pēc programmas aizvēršanas darbojas pareizi. To izmanto arī, lai aprēķinātu mēneša aktīvos lietotājus/ierīces un mākoņpakalpojumu uzticamības rādītājus.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_AddDocTelemRes —** norāda, vai mēs varam pareizi aizpildīt citas ar dokumentu telemetriju saistītās vērtības šajā notikumā. Izmanto datu kvalitātes diagnostikai.

  - **Data\_DetachedDuration —** cik ilgi darbība bija atdalīta no pavediena

  - **Data\_Doc\_AccessMode —** dokuments ir tikai lasāms/rediģējams

  - **Data\_Doc\_AssistedReadingReasons —** iepriekš definētu vērtību kopa, kas norāda, kāpēc dokuments ir atvērts pieejamā lasīšanas režīmā

  - **Data\_Doc\_ChunkingType —** vienības, kas tiek izmantotas inkrementālā dokumenta atvēršanā

  - **Data\_Doc\_EdpState —** dokumenta elektronisko datu aizsardzības iestatījums

  - **Data\_Doc\_Ext —** dokumentu paplašinājums (docx/xlsb/pptx utt.)

  - **Data\_Doc\_FileFormat —** faila formāta protokola versija

  - **Data\_Doc\_Fqdn —** OneDrive vai SharePoint Online domēna nosaukums

  - **Data\_Doc\_FqdnHash —** klientu identificējama domēna nosaukuma vienvirziena jaukšana

  - **Data\_Doc\_IdentityTelemetryId —** tādas lietotāja identitātes vienvirziena jaukšana, kas tiek izmantota atvēršanā

  - **Data\_Doc\_InitializationScenario —** dokumenta atvēršanas ieraksti

  - **Data\_Doc\_IOFlags —** atskaites par kešotajiem karodziņiem, kas tiek izmantoti pieprasījuma opciju iestatīšanai

  - **Data\_Doc\_IrmRights —** dokumentam/lietotājam piemērotās elektronisko datu politikas atļautās darbības

  - **Data\_Doc\_IsIncrementalOpen —** karodziņš, kas norāda, ka dokuments ir atvērts inkrementāli

  - **Data\_Doc\_IsOcsSupported —** karodziņš, kas norāda, ka dokuments tiek atbalstīts sadarbības pakalpojumā

  - **Data\_Doc\_IsOpeningOfflineCopy —** atzīme, kas norāda, ka tika atvērta dokumenta bezsaistes kopija

  - **Data_Doc_IsRtcAlwaysOn —** patiess, ja reāllaika kanāls (RTC) šim failam vienmēr ir ieslēgts.

  - **Data\_Doc\_IsSyncBacked —** karodziņš, kas norāda, ka datorā pastāv automātiski sinhronizēta dokumenta kopija

  - **Data\_Doc\_Location —** norāda pakalpojumu, kurā atrodas dokuments (OneDrive, File Server, SharePoint utt.)

  - **Data\_Doc\_LocationDetails —** norāda, kurā zināmajā mapē atrodas lokāli saglabātais dokuments

  - **Data\_Doc\_NumberCoAuthors —** citu lietotāju skaits koprediģēšanas sesijā

  - **Data\_Doc\_PasswordFlags —** norāda lasīšanas/rakstīšanas paroles karodziņu kopu

  - **Data\_Doc\_ReadOnlyReasons —** iemesli, kāpēc dokuments ir atvērts tikai lasāmajā režīmā

  - **Data\_Doc\_ResourceIdHash —** anonimizēts dokumenta identifikators, ko izmanto problēmu noteikšanā

  - **Data\_Doc\_ServerDocId —** nemainīgs anonimizēts dokumenta identifikators, ko izmanto problēmu noteikšanā

  - **Data\_Doc\_ServerProtocol —** tā protokola versija, ko izmanto, lai sazinātos ar pakalpojumu

  - **Data\_Doc\_ServerType —** tā servera tips, kas nodrošina pakalpojumu (OneDrive, SharePoint, WOPI utt.)

  - **Data\_Doc\_ServerVersion —** tā servera versija, kas nodrošina pakalpojumu

  - **Data\_Doc\_SessionId —** identificē konkrētu dokumenta rediģēšanas sesiju pilnā sesijā

  - **Data\_Doc\_SharePointServiceContext —** diagnostikas informācija no SharePoint Online pieprasījumiem

  - **Data\_Doc\_SizeInBytes —** dokumenta lieluma rādītājs

  - **Data\_Doc\_SpecialChars —** speciālo rakstzīmju rādītājs dokumenta vietrādī URL vai ceļā

  - **Data\_Doc\_StreamAvailability —** norāda, vai ir pieejama/atspējota dokumenta plūsma

  - **Data\_Doc\_SyncBackedType —** norāda dokumenta veidu (lokālais vai servera)

  - **Data\_Doc\_UrlHash —** vienvirziena jaukšana vienkāršota dokumenta identifikatora izveidei

  - **Data\_Doc\_WopiServiceId —** satur unikālu WOPI pakalpojumu sniedzēja identifikatoru

  - **Data\_DstDoc\_AccessMode —** mērķa dokuments ir tikai lasāms/ rediģējams

  - **Data\_DstDoc\_EdpState — mērķa dokumenta elektronisko datu aizsardzības iestatījums**

  - **Datu\_DstDoc\_Ext —** mērķa dokumenta paplašinājums (docx/xlsb/pptx utt.)

  - **Data\_DstDoc\_FileFormat —** mērķa dokumenta faila formāta protokola versija

  - **Data\_DstDoc\_Location —** norāda pakalpojumu, kurā atrodas mērķa dokuments (OneDrive, File Server, SharePoint utt.)

  - **Datu\_DstDoc\_LocationDetails —** norāda, kura lokālajā zināmajā mapē tiek glabāts mērķa dokuments

  - **Data\_DstDoc\_SessionId —** identificē konkrētu dokumenta rediģēšanas sesiju pilnā sesijā

  - **Data\_DstDoc\_UrlHash —** vienvirziena jaukšana vienkāršota mērķa dokumenta identifikatora izveidei

  - **Data\_FailureClass —** skaitlis, kas atspoguļo OCS pārejas kļūmju kļūmes klasi

  - **Data\_LocationPickerSaveStatus —** skaitliska vērtība, kas norāda darbību, kas aktivizēja saglabāšanu izejas dialoglodziņā

  - **Data\_MainPdod —** dokumenta identifikators Office Word procesā

  - **Data\_MoveFlightEnabled —** vai testējamā varianta opcija pārvietošanas līdzeklī ir iespējota

  - **Data\_OCSSyncbackSaveStarted —** karodziņš, kas norāda, ka saglabātais dokuments ir saistīts ar sinhronizēto saglabāšanu

  - **Data\_RenameDisabledReason —** kļūda, kuras dēļ tiek atspējota dokumenta pārdēvēšana

  - **Data\_RenameFlightEnabled —** vai testējamā varianta opcija pārdēvēšanas līdzeklī ir iespējota

  - **Data\_SaveInitiateKind —** vesels skaitlis, kas norāda, kā tika sākta saglabāšana

  - **Data\_SrcDocIsUnnamedOrNew —** norāda, vai saglabājamais dokuments ir jauns

#### <a name="officewordfilesavesaveassavefile"></a>Office.Word.FileSave.SaveAsSaveFile

Šis notikums norāda, ka Office Word saglabā dokumentu jaunā dokumentā. Tādējādi Microsoft var noteikt darbības “saglabāt kā” kļūdas, kam ir būtiska nozīme, lai novērstu dokumenta datu zudumu. Notikums pārrauga, vai dokumenta saglabāšana darbojas pareizi. To izmanto arī, lai aprēķinātu mēneša aktīvos lietotājus/ierīces un mākoņpakalpojumu uzticamības rādītājus.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_AddDocTelemRes —** norāda, vai mēs varam pareizi aizpildīt citas ar dokumentu telemetriju saistītās vērtības šajā notikumā. Izmanto datu kvalitātes diagnostikai.

  - **Data\_AddDocTelemResDst —** norāda, vai mēs varam pareizi aizpildīt citas ar dokumentu telemetriju saistītās vērtības šajā notikumā mērķa dokumentam. Izmanto datu kvalitātes diagnostikai.

  - **Data\_AddDocTelemResSrc —** norāda, vai mēs varam pareizi aizpildīt citas ar dokumentu telemetriju saistītās vērtības šajā notikumā avota dokumentam. Izmanto datu kvalitātes diagnostikai.

  - **Data\_DetachedDuration —** cik ilgi darbība bija atdalīta no pavediena

  - **Data\_Doc\_AccessMode —** dokuments ir tikai lasāms/rediģējams

  - **Data\_Doc\_AssistedReadingReasons —** iepriekš definētu vērtību kopa, kas norāda, kāpēc dokuments ir atvērts pieejamā lasīšanas režīmā

  - **Data\_Doc\_ChunkingType —** vienības, kas tiek izmantotas inkrementālā dokumenta atvēršanā

  - **Data\_Doc\_EdpState —** dokumenta elektronisko datu aizsardzības iestatījums

  - **Data\_Doc\_Ext —** dokumentu paplašinājums (docx/xlsb/pptx utt.)

  - **Data\_Doc\_FileFormat —** faila formāta protokola versija

  - **Data\_Doc\_Fqdn —** OneDrive vai SharePoint Online domēna nosaukums

  - **Data\_Doc\_FqdnHash —** klientu identificējama domēna nosaukuma vienvirziena jaukšana

  - **Data\_Doc\_IdentityTelemetryId —** tādas lietotāja identitātes vienvirziena jaukšana, kas tiek izmantota atvēršanā

  - **Data\_Doc\_IOFlags —** atskaites par kešotajiem karodziņiem, kas tiek izmantoti pieprasījuma opciju iestatīšanai

  - **Data\_Doc\_IrmRights —** dokumentam/lietotājam piemērotās elektronisko datu politikas atļautās darbības

  - **Data\_Doc\_IsIncrementalOpen —** karodziņš, kas norāda, ka dokuments ir atvērts inkrementāli

  - **Data\_Doc\_IsOcsSupported —** karodziņš, kas norāda, ka dokuments tiek atbalstīts sadarbības pakalpojumā

  - **Data\_Doc\_IsOpeningOfflineCopy —** atzīme, kas norāda, ka tika atvērta dokumenta bezsaistes kopija

  - **Data_Doc_IsRtcAlwaysOn —** patiess, ja reāllaika kanāls (RTC) šim failam vienmēr ir ieslēgts.

  - **Data\_Doc\_IsSyncBacked —** karodziņš, kas norāda, ka datorā pastāv automātiski sinhronizēta dokumenta kopija

  - **Data\_Doc\_Location —** norāda pakalpojumu, kurā atrodas dokuments (OneDrive, File Server, SharePoint utt.)

  - **Data\_Doc\_LocationDetails —** norāda, kurā zināmajā mapē atrodas lokāli saglabātais dokuments

  - **Data\_Doc\_NumberCoAuthors —** citu lietotāju skaits koprediģēšanas sesijā

  - **Data\_Doc\_ReadOnlyReasons —** iemesli, kāpēc dokuments ir atvērts tikai lasāmajā režīmā

  - **Data\_Doc\_ResourceIdHash —** anonimizēts dokumenta identifikators, ko izmanto problēmu noteikšanā

  - **Data\_Doc\_ServerDocId —** nemainīgs anonimizēts dokumenta identifikators, ko izmanto problēmu noteikšanā

  - **Data\_Doc\_ServerProtocol —** tā protokola versija, ko izmanto, lai sazinātos ar pakalpojumu

  - **Data\_Doc\_ServerType —** tā servera tips, kas nodrošina pakalpojumu (OneDrive, SharePoint, WOPI utt.)

  - **Data\_Doc\_ServerVersion —** tā servera versija, kas nodrošina pakalpojumu

  - **Data\_Doc\_SessionId —** identificē konkrētu dokumenta rediģēšanas sesiju pilnā sesijā

  - **Data\_Doc\_SharePointServiceContext —** diagnostikas informācija no SharePoint Online pieprasījumiem

  - **Data\_Doc\_SizeInBytes —** dokumenta lieluma rādītājs

  - **Data\_Doc\_SpecialChars —** speciālo rakstzīmju rādītājs dokumenta vietrādī URL vai ceļā

  - **Data\_Doc\_StreamAvailability —** norāda, vai ir pieejama/atspējota dokumenta plūsma

  - **Data\_Doc\_UrlHash —** vienvirziena jaukšana vienkāršota dokumenta identifikatora izveidei

  - **Data\_DstDoc\_AccessMode —** mērķa dokuments ir tikai lasāms/ rediģējams

  - **Data\_DstDoc\_AssistedReadingReasons —** iepriekš definētu vērtību kopa, kas norāda, kāpēc mērķa dokuments ir atvērts pieejamā lasīšanas režīmā

  - **Data\_DstDoc\_ChunkingType —** vienības, kas tiek izmantotas inkrementālā dokumenta atvēršanā

  - **Data\_DstDoc\_EdpState —** mērķa dokumenta elektronisko datu aizsardzības iestatījums

  - **Data\_DstDoc\_Ext —** dokumentu paplašinājums (docx/xlsb/pptx utt.)

  - **Data\_DstDoc\_FileFormat —** faila formāta protokola versija

  - **Datu\_DstDoc\_Fqdn —** OneDrive vai SharePoint Online domēna nosaukums mērķa dokumentam

  - **Data\_DstDoc\_FqdnHash —** klientu identificējama domēna nosaukuma vienvirziena jaukšana mērķa dokumentam

  - **Data\_DstDoc\_IdentityTelemetryId —** tādas lietotāja identitātes vienvirziena jaukšana, kas tiek izmantota atvēršanā

  - **Data\_DstDoc\_InitializationScenario —** mērķa dokumenta atvēršanas ieraksti

  - **Data\_DstDoc\_IOFlags —** atskaites par kešotajiem karodziņiem, kas tiek izmantoti pieprasījuma opciju iestatīšanai mērķa dokumentam

  - **Data\_DstDoc\_IrmRights —** mērķa dokumentam/lietotājam piemērotās elektronisko datu politikas atļautās darbības

  - **Data\_DstDoc\_IsIncrementalOpen —** karodziņš, kas norāda, ka dokuments ir atvērts inkrementāli

  - **Data\_DstDoc\_IsOcsSupported —** karodziņš, kas norāda, ka dokuments tiek atbalstīts sadarbības pakalpojumā

  - **Data\_DstDoc\_IsOpeningOfflineCopy —** atzīme, kas norāda, ka tika atvērta dokumenta bezsaistes kopija

  - **Data\_DstDoc\_IsSyncBacked —** karodziņš, kas norāda, ka datorā pastāv automātiski sinhronizēta dokumenta kopija

  - **Data\_DstDoc\_Location —** norāda pakalpojumu, kurā atrodas mērķa dokuments (OneDrive, File Server, SharePoint utt.)

  - **Data\_DstDoc\_LocationDetails —** norāda, kurā zināmajā mapē atrodas lokāli saglabātais dokuments

  - **Data\_DstDoc\_NumberCoAuthors —** citu lietotāju skaits koprediģēšanas sesijā

  - **Data\_DstDoc\_PasswordFlags —** norāda lasīšanas/rakstīšanas paroles karodziņu kopu mērķa dokumentam

  - **Data\_DstDoc\_ReadOnlyReasons —** iemesli, kāpēc mērķa dokuments ir atvērts tikai lasāmajā režīmā

  - **Data\_DstDoc\_ResourceIdHash —** anonimizēts dokumenta identifikators, ko izmanto problēmu noteikšanā

  - **Data\_DstDoc\_ServerDocId —** nemainīgs anonimizēts dokumenta identifikators, ko izmanto problēmu noteikšanā

  - **Data\_DstDoc\_ServerProtocol —** tā protokola versija, ko izmanto, lai sazinātos ar pakalpojumu

  - **Data\_DstDoc\_ServerType —** tā servera tips, kas nodrošina pakalpojumu (OneDrive, SharePoint, WOPI utt.)

  - **Data\_DstDoc\_ServerVersion —** tā servera versija, kas nodrošina pakalpojumu

  - **Data\_DstDoc\_SessionId —** identificē konkrētu dokumenta rediģēšanas sesiju pilnā sesijā

  - **Data\_DstDoc\_SharePointServiceContext —** diagnostikas informācija no SharePoint Online pieprasījumiem

  - **Data\_DstDoc\_SizeInBytes —** dokumenta lieluma rādītājs

  - **Data\_DstDoc\_SpecialChars —** speciālo rakstzīmju rādītājs dokumenta vietrādī URL vai ceļā

  - **Data\_DstDoc\_StreamAvailability —** norāda, vai ir pieejama/atspējota dokumenta plūsma

  - **Data\_DstDoc\_SyncBackedType —** norāda dokumenta veidu (lokālais vai servera)

  - **Data\_DstDoc\_UrlHash —** vienvirziena jaukšana vienkāršota mērķa dokumenta identifikatora izveidei

  - **Data\_DstDoc\_WopiServiceId —** satur unikālu WOPI pakalpojumu sniedzēja identifikatoru

  - **Data\_FailureClass —** skaitlis, kas atspoguļo OCS pārejas kļūmju kļūmes klasi

  - **Data\_LocationPickerPropagateToSaveTime,spLapsedMsec —** izmēra laiku milisekundēs, kas nepieciešams, līdz saglabāšanas aktivizēšanai pēc rezultāta iegūšanas no atrašanās vietas meklētāja

  - **Data\_LocationPickerSaveStatus —** atrašanās vietas meklētāja atgrieztais statuss

  - **Data\_MainPdod —** dokumenta identifikators Office Word procesā

  - **Data\_MoveDisabledReason —** kļūda, kas atspējo dokumenta pārvietošanu

  - **Data\_MoveFlightEnabled —** vai lidojuma opcija pārvietošanas līdzeklī ir iespējota

  - **Data\_RenameDisabledReason —** kļūda, kuras dēļ tiek atspējota dokumenta pārdēvēšana

  - **Data\_RenameFlightEnabled —** vai testējamā varianta opcija pārdēvēšanas līdzeklī ir iespējota

  - **Data\_SaveInitiateKind —** vesels skaitlis, kas norāda, kā tika sākta saglabāšana

  - **Data\_SrcDoc\_AccessMode —** avota dokuments ir tikai lasāms/rediģējams

  - **Data\_SrcDoc\_AssistedReadingReasons —** iepriekš definētu vērtību kopa, kas norāda, kāpēc dokuments ir atvērts pieejamā lasīšanas režīmā

  - **Data\_SrcDoc\_ChunkingType —** vienības, kas tiek izmantotas inkrementālā dokumenta atvēršanā

  - **Data\_SrcDoc\_EdpState —** avota dokumenta elektronisko datu aizsardzības iestatījums

  - **Data\_SrcDoc\_Ext —** avota dokumenta paplašinājums (docx/xlsb/pptx utt.)

  - **Data\_SrcDoc\_FileFormat —** avota dokumenta faila formāta protokola versija

  - **Datu\_SrcDoc\_Fqdn —** OneDrive vai SharePoint Online domēna nosaukums avota dokumentam

  - **Data\_SrcDoc\_FqdnHash —** klientu identificējama domēna nosaukuma vienvirziena jaukšana avota dokumentam

  - **Data\_SrcDoc\_IdentityTelemetryId —** tādas lietotāja identitātes vienvirziena jaukšana, kas tiek izmantota atvēršanā

  - **Data\_SrcDoc\_InitializationScenario —** dokumenta atvēršanas ieraksti

  - **Data\_SrcDoc\_IOFlags —** atskaites par kešotajiem karodziņiem, kas tiek izmantoti pieprasījuma opciju iestatīšanai

  - **Data\_SrcDoc\_IrmRights —** dokumentam/lietotājam piemērotās elektronisko datu politikas atļautās darbības

  - **Data\_SrcDoc\_IsIncrementalOpen —** karodziņš, kas norāda, ka dokuments ir atvērts inkrementāli

  - **Data\_SrcDoc\_IsOcsSupported —** karodziņš, kas norāda, ka dokuments tiek atbalstīts sadarbības pakalpojumā

  - **Data\_SrcDoc\_IsOpeningOfflineCopy —** atzīme, kas norāda, ka tika atvērta dokumenta bezsaistes kopija

  - **Data\_SrcDoc\_IsSyncBacked —** karodziņš, kas norāda, ka datorā pastāv automātiski sinhronizēta dokumenta kopija

  - **Data\_SrcDoc\_Location —** norāda pakalpojumu, kurā atrodas avota dokuments (OneDrive, File Server, SharePoint utt.)

  - **Data\_SrcDoc\_LocationDetails —** norāda, kurā zināmajā mapē atrodas lokāli saglabātais dokuments

  - **Data\_SrcDoc\_NumberCoAuthors —** citu lietotāju skaits koprediģēšanas sesijā

  - **Data\_SrcDoc\_PasswordFlags —** norāda lasīšanas/rakstīšanas paroles karodziņu kopu

  - **Data\_SrcDoc\_ReadOnlyReasons —** iemesli, kāpēc dokuments ir atvērts tikai lasāmajā režīmā

  - **Data\_SrcDoc\_ResourceIdHash —** anonimizēts dokumenta identifikators, ko izmanto problēmu noteikšanā

  - **Data\_SrcDoc\_ServerDocId —** nemainīgs anonimizēts dokumenta identifikators, ko izmanto problēmu noteikšanā

  - **Data\_SrcDoc\_ServerProtocol —** tā protokola versija, ko izmanto, lai sazinātos ar pakalpojumu

  - **Data\_SrcDoc\_ServerType —** tā servera tips, kas nodrošina pakalpojumu (OneDrive, SharePoint, WOPI utt.)

  - **Data\_SrcDoc\_ServerVersion —** tā servera versija, kas nodrošina pakalpojumu

  - **Data\_SrcDoc\_SessionId —** identificē konkrētu dokumenta rediģēšanas sesiju pilnā sesijā

  - **Data\_SrcDoc\_SharePointServiceContext —** diagnostikas informācija no SharePoint Online pieprasījumiem

  - **Data\_SrcDoc\_SizeInBytes —** dokumenta lieluma rādītājs

  - **Data\_SrcDoc\_SpecialChars —** speciālo rakstzīmju rādītājs dokumenta vietrādī URL vai ceļā

  - **Data\_SrcDoc\_StreamAvailability —** norāda, vai ir pieejama/atspējota dokumenta plūsma

  - **Data\_SrcDoc\_SyncBackedType —** norāda dokumenta veidu (lokālais vai servera)

  - **Data\_SrcDoc\_UrlHash —** vienvirziena jaukšana vienkāršota dokumenta identifikatora izveidei

  - **Data\_SrcDoc\_WopiServiceId —** satur unikālu WOPI pakalpojumu sniedzēja identifikatoru

  - **Data\_SrcDocIsUnnamedOrNew —** norāda, vai saglabājamais dokuments ir jauns

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

### <a name="application-status-and-boot-subtype"></a>*Lietojumprogrammas statuss un palaišanas apakštips*

Nosaka, vai ir notikuši konkrēti līdzekļu notikumi, piemēram, startēšana vai apturēšana, un vai līdzeklis darbojas.

#### <a name="officeextensibilityofficejsappactivated"></a>Office.Extensibility.OfficeJS.Appactivated

Ieraksta informāciju par neparedzētu Office izslēgšanu. Tas ļauj mums noteikt produkta avārijas vai, ja tas pārstāj reaģēt, un atrisināt šīs problēmas.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_AirspaceInitTime:integer — ** laiks, lai inicializētu Airspace Office komponentu

  - **Data\_AllShapes:integer —** formu skaits dokumentā

  - **Data\_APIInitTime:integer —** laiks, lai inicializētu Visio API moduli

  - **Data\_AppSizeHeight —** pievienojumprogrammas**-** loga augstums

  - **Data\_AppSizeWidth —** pievienojumprogrammas**-** loga platums

  - **Data\_AppURL —** pievienojumprogrammas URL; reģistrē pilnu URL krātuves pievienojumprogrammām un URL domēnu pievienojumprogrammām, kas nav krātuves pievienojumprogrammas

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

  - **Data_Doc_IsRtcAlwaysOn —** patiess, ja reāllaika kanāls (RTC) šim failam vienmēr ir ieslēgts.

  - **Data\_Doc\_IsSyncBacked:bool —** patiess, ja šis ir servera dokuments, kas pastāv lokāli, un ir sinhronizēta ar serveri (piemēram, izmantojot OneDrive vai ODB klienta programmām)

  - **Data\_Doc\_Location:long —** iepriekš definētu vērtību kopa, kas norāda dokumenta glabāšanas vietu (lokālā, SharePoint, WOPI, tīkls utt.)

  - **Data\_Doc\_LocationDetails:long —** iepriekš definētu detalizētākas atrašanās vietas vērtību kopa (mape Temp, lejupielāžu mape, OneDrive dokumenti, OneDrive attēli)

  - **Data\_Doc\_ResourceIdHash:string —** resursu identifikatora jaukšana mākonī saglabātajiem dokumentiem

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

  - **Data\_InitPerfTime:integer —** izpildes Office komponenta inicializācijas laiks

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

#### <a name="officeoutlookdesktopexchangepuidandtenantcorrelation"></a>Office.Outlook.Desktop.ExchangePuidAndTenantCorrelation

Reizi sesijā apkopo PUID un nomnieka identifikatoru. PUID un nomnieka korelācija ir nepieciešama, lai izprastu un diagnosticētu Outlook problēmas katram nomniekam.

Tiek apkopoti tālāk norādītie lauki.

  - **CollectionTime** — notikuma laikspiedols

  - **ConnId** — savienojuma identifikators: identifikators savienojuma parsēšanai starp PUID un OMS nomnieka identifikatoru

  - **OMSTenantId** — Microsoft ģenerētais nomnieka unikālais identifikators

  - **PUID** — Exchange PUID unikālai lietotāju identificēšanai

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

  - **Data\_ContentTransaction —** iepriekš definētu vērtību kopa, kad iespējams izveidot transakciju (AllowedOnLoadDocument AllowedOnOpenComplete utt.)

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

  - **Data_Doc_IsRtcAlwaysOn —** patiess, ja reāllaika kanāls (RTC) šim failam vienmēr ir ieslēgts.

  - **Data\_Doc\_IsSyncBacked:bool —** vai dokuments tiek atvērts no mapes, kas izmanto OneDrive sinhronizācijas programmu

  - **Data\_Doc\_Location:long —** iepriekš definētu vērtību kopa, kas norāda dokumenta glabāšanas vietu (lokālā, SharePoint, WOPI, tīkls utt.)

  - **Data\_Doc\_LocationDetails:long —** iepriekš definētu detalizētākas atrašanās vietas vērtību kopa (mape Temp, lejupielāžu mape, OneDrive dokumenti, OneDrive attēli utt.)

  - **Data\_Doc\_NumberCoAuthors:long —** līdzautoru skaits dokumenta atvēršanas brīdī

  - **Data\_Doc\_PasswordFlags:long —** iepriekš definētu vērtību kopa, kas norāda veidu, kā dokuments ir šifrēts ar paroli (nav, parole lasīšanai, parole rediģēšanai)

  - **Data\_Doc\_ReadOnlyReasons:long —** iepriekš definētu vērtību kopa, kas norāda, kāpēc šis dokuments ir atzīmēts kā tikai lasāms (bloķēts serverī, pabeigts dokuments, aizsargāts ar paroli rediģēšanai utt.)

  - **Data\_Doc\_ResourceIdHash:string —** resursu identifikatora jaukšana mākonī saglabātajiem dokumentiem

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

#### <a name="officewordfileopenopencmdfilemrupriv"></a>Office.Word.FileOpen.OpenCmdFileMruPriv

Šis notikums norāda, ka Office Word atver dokumentu no pēdējo lietoto dokumentu saraksta. Tas satur arī kritiski svarīgus faila atvēršanas izpildes datus, un no lietotāja skatpunkta ir programmas startēšanas notikums. Notikums pārrauga, vai faila atvēršana no pēdējo lietoto dokumentu saraksta darbojas pareizi. To izmanto arī, lai aprēķinātu mēneša aktīvos lietotājus/ierīces un mākoņpakalpojumu uzticamības rādītājus.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_AddDocTelemRes —** norāda, vai mēs varam pareizi aizpildīt citas ar dokumentu telemetriju saistītās vērtības šajā notikumā. Izmanto datu kvalitātes diagnostikai.

  - **Data\_BytesAsynchronous —** baitu skaits (saspiests), bez kura uzskatām, ka varēsim atvērt failu, ja tos iegūstam pirms lietotājs vēlas sākt rediģēšanu vai saglabāšanu

  - **Data\_BytesAsynchronousWithWork —** baitu skaits (saspiests), bez kura, iespējams, varēsim atvērt failu, taču tam būs nepieciešamas būtiskas koda izmaiņas

  - **Data\_BytesSynchronous —** baitu skaits (saspiests), kuram jābūt mūsu rīcībā, pirms varam sākt faila atvēršanu

  - **Data\_BytesUnknown —** baitu skaits dokumenta daļās, kuras neplānojam atrast

  - **Data\_DetachedDuration —** cik ilgi darbība bija atdalīta no pavediena

  - **Data\_Doc\_AccessMode —** dokuments ir tikai lasāms/rediģējams

  - **Data\_Doc\_AssistedReadingReasons —** iepriekš definētu vērtību kopa, kas norāda, kāpēc dokuments ir atvērts pieejamā lasīšanas režīmā

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

  - **Data_Doc_IsRtcAlwaysOn —** patiess, ja reāllaika kanāls (RTC) šim failam vienmēr ir ieslēgts.

  - **Data\_Doc\_IsSyncBacked —** karodziņš, kas norāda, ka datorā pastāv automātiski sinhronizēta dokumenta kopija

  - **Data\_Doc\_Location —** norāda pakalpojumu, kurā atrodas dokuments (OneDrive, File Server, SharePoint utt.)

  - **Data\_Doc\_LocationDetails —** norāda, kurā zināmajā mapē atrodas lokāli saglabātais dokuments

  - **Data\_Doc\_NumberCoAuthors —** citu lietotāju skaits koprediģēšanas sesijā

  - **Data\_Doc\_PasswordFlags —** norāda lasīšanas/rakstīšanas paroles karodziņu kopu

  - **Data\_Doc\_ReadOnlyReasons —** iemesli, kāpēc dokuments ir atvērts tikai lasāmajā režīmā

  - **Data\_Doc\_ResourceIdHash —** anonimizēts dokumenta identifikators, ko izmanto problēmu noteikšanā

  - **Data\_Doc\_ServerDocId —** nemainīgs anonimizēts dokumenta identifikators, ko izmanto problēmu noteikšanā

  - **Data\_Doc\_ServerProtocol —** tā protokola versija, ko izmanto, lai sazinātos ar pakalpojumu

  - **Data\_Doc\_ServerType —** tā servera tips, kas nodrošina pakalpojumu (OneDrive, SharePoint, WOPI utt.)

  - **Data\_Doc\_ServerVersion —** tā servera versija, kas nodrošina pakalpojumu

  - **Data\_Doc\_SessionId —** identificē konkrētu dokumenta rediģēšanas sesiju pilnā sesijā

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

  - **Data\_Measurements —** kodēta virkne, kas satur dažādu daļu atvēršanas laika sadalījumu. Izmanto, lai novērtētu izpildi.

  - **Data\_MoveDisabledReason —** kļūda, kas atspējo dokumenta pārvietošanu

  - **Data\_MoveFlightEnabled —** vai lidojuma opcija pārvietošanas līdzeklī ir iespējota

  - **Data\_PartsUnknown —** dokumenta daļu skaits, kurām mēs nevarējām iegūt datus

  - **Data\_RecoverableFailureInitiationLocationTag —** unikāla atzīme koda izsaukumu vietā, lai identificētu vietu kodā, kur mēs mēģināsim izlabot failu pirms tā atvēršanas

  - **Data\_RenameDisabledReason —** kļūda, kuras dēļ tiek atspējota dokumenta pārdēvēšana

  - **Data\_RenameFlightEnabled —** vai testējamā varianta opcija pārdēvēšanas līdzeklī ir iespējota

  - **Data\_SecondaryTag —** unikāla atzīme koda izsaukšanas vietai, kas tiek izmantota, lai pievienotu papildu kļūmes datus atvēršanai

  - **Data\_TemplateFormat —** tās veidnes faila formāts, kas ir dokumenta pamatā.

  - **Data\_UsesNormal —** norāda, vai atvērtā dokumenta pamatā ir parasta veidne

#### <a name="officewordfileopenopenffileopenxstzcore"></a>Office.Word.FileOpen.OpenFFileOpenXstzCore

Šis notikums norāda, ka Office Word atver dokumentu, uz kura lietotājs veic dubultklikšķi. Tas satur arī kritiski svarīgus faila atvēršanas izpildes datus, un no lietotāja skatpunkta ir programmas startēšanas notikums. Notikums pārrauga, vai faila atvēršana ar dubultklikšķi darbojas pareizi. To izmanto arī, lai aprēķinātu mēneša aktīvos lietotājus/ierīces un mākoņpakalpojumu uzticamības rādītājus.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_AddDocTelemRes —** norāda, vai mēs varam pareizi aizpildīt citas ar dokumentu telemetriju saistītās vērtības šajā notikumā. Izmanto datu kvalitātes diagnostikai

  - **Data\_BytesAsynchronous —** baitu skaits (saspiests), bez kura uzskatām, ka varēsim atvērt failu, ja tos iegūstam pirms lietotājs vēlas sākt rediģēšanu vai saglabāšanu

  - **Data\_BytesAsynchronousWithWork —** baitu skaits (saspiests), bez kura, iespējams, varēsim atvērt failu, taču tam būs nepieciešamas būtiskas koda izmaiņas

  - **Data\_BytesSynchronous —** baitu skaits (saspiests), kuram jābūt mūsu rīcībā, pirms varam sākt faila atvēršanu

  - **Data\_BytesUnknown —** baitu skaits dokumenta daļās, kuras neplānojam atrast

  - **Data\_DetachedDuration —** cik ilgi darbība bija atdalīta no pavediena

  - **Data\_Doc\_AccessMode —** dokuments ir tikai lasāms/rediģējams

  - **Data\_Doc\_AssistedReadingReasons —** iepriekš definētu vērtību kopa, kas norāda, kāpēc dokuments ir atvērts pieejamā lasīšanas režīmā

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

  - **Data_Doc_IsRtcAlwaysOn —** patiess, ja reāllaika kanāls (RTC) šim failam vienmēr ir ieslēgts.

  - **Data\_Doc\_IsSyncBacked —** karodziņš, kas norāda, ka datorā pastāv automātiski sinhronizēta dokumenta kopija

  - **Data\_Doc\_Location —** norāda pakalpojumu, kurā atrodas dokuments (OneDrive, File Server, SharePoint utt.)

  - **Data\_Doc\_LocationDetails —** norāda, kurā zināmajā mapē atrodas lokāli saglabātais dokuments

  - **Data\_Doc\_NumberCoAuthors —** citu lietotāju skaits koprediģēšanas sesijā

  - **Data\_Doc\_PasswordFlags —** norāda lasīšanas/rakstīšanas paroles karodziņu kopu

  - **Data\_Doc\_ReadOnlyReasons —** iemesli, kāpēc dokuments ir atvērts tikai lasāmajā režīmā

  - **Data\_Doc\_ResourceIdHash —** anonimizēts dokumenta identifikators, ko izmanto problēmu noteikšanā

  - **Data\_Doc\_ServerDocId —** nemainīgs anonimizēts dokumenta identifikators, ko izmanto problēmu noteikšanā

  - **Data\_Doc\_ServerProtocol —** tā protokola versija, ko izmanto, lai sazinātos ar pakalpojumu

  - **Data\_Doc\_ServerType —** tā servera tips, kas nodrošina pakalpojumu (OneDrive, SharePoint, WOPI utt.)

  - **Data\_Doc\_ServerVersion —** tā servera versija, kas nodrošina pakalpojumu

  - **Data\_Doc\_SessionId —** tā servera versija, kas nodrošina pakalpojumu

  - **Data\_Doc\_SharePointServiceContext —**

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

  - **Data\_Measurements —** kodēta virkne, kas satur dažādu daļu atvēršanas laika sadalījumu. Izmanto, lai novērtētu izpildi.

  - **Data\_MoveDisabledReason —** kļūda, kas atspējo dokumenta pārvietošanu

  - **Data\_MoveFlightEnabled —** vai lidojuma opcija pārvietošanas līdzeklī ir iespējota

  - **Data\_PartsUnknown —** dokumenta daļu skaits, kurām mēs nevarējām iegūt datus

  - **Data\_RecoverableFailureInitiationLocationTag —** unikāla atzīme koda izsaukumu vietā, lai identificētu vietu kodā, kur mēs mēģināsim izlabot failu pirms tā atvēršanas

  - **Data\_RenameDisabledReason —** kļūda, kuras dēļ tiek atspējota dokumenta pārdēvēšana

  - **Data\_RenameFlightEnabled —** vai testējamā varianta opcija pārdēvēšanas līdzeklī ir iespējota

  - **Data\_SecondaryTag —** unikāla atzīme koda izsaukšanas vietai, kas tiek izmantota, lai pievienotu papildu kļūmes datus atvēršanai

  - **Data\_TemplateFormat —** tās veidnes faila formāts, kas ir dokumenta pamatā.

  - **Data\_UsesNormal —** norāda, vai atvērtā dokumenta pamatā ir parasta veidne


#### <a name="officewordfileopenopenifrinitargs"></a>Office.Word.FileOpen.OpenIfrInitArgs

Šis notikums norāda, ka Office Word atver dokumentu, izmantojot COM aktivizēšanu vai komandrindu. Tas satur arī kritiski svarīgus faila atvēršanas izpildes datus, un no lietotāja skatpunkta ir programmas startēšanas notikums. Notikums pārrauga, vai faila atvēršana no komandrindas darbojas pareizi. To izmanto arī, lai aprēķinātu mēneša aktīvos lietotājus/ierīces un mākoņpakalpojumu uzticamības rādītājus.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_AddDocTelemRes —** norāda, vai mēs varam pareizi aizpildīt citas ar dokumentu telemetriju saistītās vērtības šajā notikumā. Izmanto datu kvalitātes diagnostikai.

  - **Data\_BytesAsynchronous —** baitu skaits (saspiests), bez kura uzskatām, ka varēsim atvērt failu, ja tos iegūstam pirms lietotājs vēlas sākt rediģēšanu vai saglabāšanu

  - **Data\_BytesAsynchronousWithWork —** baitu skaits (saspiests), bez kura, iespējams, varēsim atvērt failu, taču tam būs nepieciešamas būtiskas koda izmaiņas

  - **Data\_BytesSynchronous —** baitu skaits (saspiests), kuram jābūt mūsu rīcībā, pirms varam sākt faila atvēršanu

  - **Data\_BytesUnknown —** baitu skaits dokumenta daļās, kuras neplānojam atrast

  - **Data\_Doc\_AccessMode —** dokuments ir tikai lasāms/rediģējams

  - **Data\_Doc\_AssistedReadingReasons —** iepriekš definētu vērtību kopa, kas norāda, kāpēc dokuments ir atvērts pieejamā lasīšanas režīmā

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

  - **Data_Doc_IsRtcAlwaysOn —** patiess, ja reāllaika kanāls (RTC) šim failam vienmēr ir ieslēgts.

  - **Data\_Doc\_IsSyncBacked —** karodziņš, kas norāda, ka datorā pastāv automātiski sinhronizēta dokumenta kopija

  - **Data\_Doc\_Location —** norāda pakalpojumu, kurā atrodas dokuments (OneDrive, File Server, SharePoint)

  - **Data\_Doc\_LocationDetails —** norāda, kurā zināmajā mapē atrodas lokāli saglabātais dokuments

  - **Data\_Doc\_NumberCoAuthors —** citu lietotāju skaits koprediģēšanas sesijā

  - **Data\_Doc\_PasswordFlags —** norāda lasīšanas/rakstīšanas paroles karodziņu kopu

  - **Data\_Doc\_ReadOnlyReasons —** iemesli, kāpēc dokuments ir atvērts tikai lasāmajā režīmā

  - **Data\_Doc\_ResourceIdHash —** anonimizēts dokumenta identifikators, ko izmanto problēmu noteikšanā

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

  - **Data\_AddDocTelemRes —** norāda, vai mēs varam pareizi aizpildīt citas ar dokumentu telemetriju saistītās vērtības šajā notikumā. Izmanto datu kvalitātes diagnostikai.

  - **Data\_BytesAsynchronous —** baitu skaits (saspiests), bez kura uzskatām, ka varēsim atvērt failu, ja tos iegūstam pirms lietotājs vēlas sākt rediģēšanu vai saglabāšanu

  - **Data\_BytesAsynchronousWithWork —** baitu skaits (saspiests), bez kura, iespējams, varēsim atvērt failu, taču tam būs nepieciešamas būtiskas koda izmaiņas

  - **Data\_BytesSynchronous —** baitu skaits (saspiests), kuram jābūt mūsu rīcībā, pirms varam sākt faila atvēršanu

  - **Data\_BytesUnknown —** baitu skaits dokumenta daļās, kuras neplānojam atrast

  - **Data\_DetachedDuration —** cik ilgi darbība bija atdalīta no pavediena

  - **Data\_Doc\_AccessMode —** dokuments ir tikai lasāms/rediģējams

  - **Data\_Doc\_AssistedReadingReasons —** iepriekš definētu vērtību kopa, kas norāda, kāpēc dokuments ir atvērts pieejamā lasīšanas režīmā

  - **Data\_Doc\_ChunkingType —** vienības, kas tiek izmantotas inkrementālā dokumenta atvēršanā

  - **Data\_Doc\_EdpState —** dokumenta elektronisko datu aizsardzības iestatījums

  - **Data\_Doc\_Ext —** dokumentu paplašinājums (docx/xlsb/pptx utt.)

  - **Data\_Doc\_FileFormat —** faila formāta protokola versija

  - **Data\_Doc\_Fqdn —** OneDrive vai SharePoint Online domēna nosaukums

  - **Data\_Doc\_FqdnHash —** klientu identificējama domēna nosaukuma vienvirziena jaukšana

  - **Data\_Doc\_IdentityTelemetryId —** tādas lietotāja identitātes vienvirziena jaukšana, kas tiek izmantota atvēršanā

  - **Data\_Doc\_InitializationScenario —** dokumenta atvēršanas ieraksti

  - **Data\_Doc\_IOFlags —** atskaites par kešotajiem karodziņiem, kas tiek izmantoti pieprasījuma opciju iestatīšanai

  - **Data\_Doc\_IrmRights —** dokumentam/lietotājam piemērotās elektronisko datu politikas atļautās darbības

  - **Data\_Doc\_IsIncrementalOpen —** karodziņš, kas norāda, ka dokuments ir atvērts inkrementāli

  - **Data\_Doc\_IsOcsSupported —** karodziņš, kas norāda, ka dokuments tiek atbalstīts sadarbības pakalpojumā

  - **Data\_Doc\_IsOpeningOfflineCopy —** atzīme, kas norāda, ka tika atvērta dokumenta bezsaistes kopija

  - **Data_Doc_IsRtcAlwaysOn —** patiess, ja reāllaika kanāls (RTC) šim failam vienmēr ir ieslēgts.

  - **Data\_Doc\_IsSyncBacked —** karodziņš, kas norāda, ka datorā pastāv automātiski sinhronizēta dokumenta kopija

  - **Data\_Doc\_Location —** norāda pakalpojumu, kurā atrodas dokuments (OneDrive, File Server, SharePoint utt.)

  - **Data\_Doc\_LocationDetails —** norāda, kurā zināmajā mapē atrodas lokāli saglabātais dokuments

  - **Data\_Doc\_NumberCoAuthors —** citu lietotāju skaits koprediģēšanas sesijā

  - **Data\_Doc\_PasswordFlags —** norāda lasīšanas/rakstīšanas paroles karodziņu kopu

  - **Data\_Doc\_ReadOnlyReasons —** iemesli, kāpēc dokuments ir atvērts tikai lasāmajā režīmā

  - **Data\_Doc\_ResourceIdHash —** anonimizēts dokumenta identifikators, ko izmanto problēmu noteikšanā

  - **Data\_Doc\_ServerDocId —** nemainīgs anonimizēts dokumenta identifikators, ko izmanto problēmu noteikšanā

  - **Data\_Doc\_ServerProtocol —** tā protokola versija, ko izmanto, lai sazinātos ar pakalpojumu

  - **Data\_Doc\_ServerType —** tā servera tips, kas nodrošina pakalpojumu (OneDrive, SharePoint, WOPI utt.)

  - **Data\_Doc\_ServerVersion —** tā servera versija, kas nodrošina pakalpojumu

  - **Data\_Doc\_SessionId —** identificē konkrētu dokumenta rediģēšanas sesiju pilnā sesijā

  - **Data\_Doc\_SharePointServiceContext —** diagnostikas informācija no SharePoint Online pieprasījumiem

  - **Data\_Doc\_SizeInBytes —** dokumenta lieluma rādītājs

  - **Data\_Doc\_SpecialChars —** speciālo rakstzīmju rādītājs dokumenta vietrādī URL vai ceļā

  - **Data\_Doc\_StreamAvailability —** norāda, vai ir pieejama/atspējota dokumenta plūsma

  - **Data\_Doc\_SyncBackedType —** norāda dokumenta veidu (lokālais vai servera)

  - **Data\_Doc\_UrlHash —** vienvirziena jaukšana vienkāršota dokumenta identifikatora izveidei

  - **Data\_EditorDisablingRename —** tā pirmā redaktora identifikators, kas izraisīja pārdēvēšanas atspējošanu

  - **Data\_EditorsCount —** redaktoru skaits dokumentā

  - **Data\_ForceReadWriteReason —** vesela skaitļa vērtība, kas attēlo iemeslu, kāpēc fails tika atvērts lasīšanas/rakstīšanas režīmā

  - **Datu\_FSucceededAfterRecoverableFailure —** norāda, ka atvēršana izdevās pēc kļūmes izlabošanas, kas radās dokumenta atvēršanas laikā

  - **Data\_LastLoggedTag —** unikāla atzīme koda izsaukuma vietā, ko izmanto, lai noteiktu, kad neizdodas saglabāt divreiz (izmanto datu kvalitātes diagnostikai)

  - **Data\_LinkStyles —** norāda, vai ir saite ar veidņu stiliem

  - **Data\_MainPdod —** dokumenta identifikators Office Word procesā

  - **Data\_Measurements —** kodēta virkne, kas satur dažādu daļu atvēršanas laika sadalījumu. Izmanto, lai novērtētu izpildi.

  - **Data\_MoveDisabledReason —** kļūda, kas atspējo dokumenta pārvietošanu

  - **Data\_MoveFlightEnabled —** vai lidojuma opcija pārvietošanas līdzeklī ir iespējota

  - **Data\_PartsUnknown —** dokumenta daļu skaits, kurām mēs nevarējām iegūt datus

  - **Data\_RecoverableFailureInitiationLocationTag —** unikāla atzīme koda izsaukumu vietā, lai identificētu vietu kodā, kur mēs mēģināsim izlabot failu pirms tā atvēršanas

  - **Data\_RenameDisabledReason —** kļūda, kuras dēļ tiek atspējota dokumenta pārdēvēšana

  - **Data\_RenameFlightEnabled —** vai testējamā varianta opcija pārdēvēšanas līdzeklī ir iespējota

  - **Data\_SecondaryTag —** unikāla atzīme koda izsaukšanas vietai, kas tiek izmantota, lai pievienotu papildu kļūmes datus atvēršanai

  - **Data\_TemplateFormat —** tās veidnes faila formāts, kas ir dokumenta pamatā

  - **Data\_UsesNormal —** norāda, vai atvērtā dokumenta pamatā ir parasta veidne


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

#### <a name="officewordaccessibilitylearningtoolsreadaloudplayreadaloud"></a>Office.Word.Accessibility.LearningTools.ReadAloud.PlayReadAloud

Šis notikums norāda, vai Office Word lasa dokumenta tekstu. Šis notikums ir pieejamības līdzekļa periodiskais kontrolziņojums, kas ļauj Microsoft izvērtēt teksta lasīšanas līdzekļa darbspēju.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_CharacterCount —** rakstzīmju skaits dokumentā

  - **Data\_CharactersWithSpaceCount —** dokumenta rakstzīmju un atstarpju skaits

  - **Data\_IsPageCountInProgress —** vai notiek lappušu skaitīšana

  - **Data\_LineCount —** rindiņu skaits dokumentā

  - **Data\_PageCount —** lappušu skaits dokumentā

  - **Data\_ParagraphCount —** rindkopu skaits dokumentā

  - **Data\_Play —** vai šī ir pirmā reize, kad programma Word lasa balsī

  - **Data\_ViewKind —** dokumenta skatīšanas tips

  - **Data\_WordCount —** vārdu skaits dokumentā

#### <a name="officewordaccessibilitylearningtoolsreadaloudstopreadaloud"></a>Office.Word.Accessibility.LearningTools.ReadAloud.StopReadAloud

Šis notikums norāda, vai Office Word pārtrauc lasīt dokumenta tekstu. Notikums ļauj Microsoft novērtēt līdzekli lasīšanas balsī līdzekļa darbspēju, nosakot darbības ilgumu.

Tiek apkopoti tālāk norādītie lauki.

  - Nav

## <a name="product-and-service-performance-data-events"></a>Produktu un pakalpojumu izpildes datu notikumi

Tālāk ir norādīti šīs kategorijas datu apakštipi.
- [Neparedzēts lietojumprogrammas darbības pārtraukums (avārijas)](#unexpected-application-exit-crash-subtype)
- [Lietojumprogrammas līdzekļu novērtējums](#application-feature-performance-subtype)
- [Lietojumprogrammas darbības kļūda](#application-activity-error-subtype)

### <a name="unexpected-application-exit-crash-subtype"></a>*Neparedzēts lietojumprogrammas darbības pārtraukums (avārijas) apakštips*

Neparedzēts lietojumprogrammas darbības pārtraukums un programmas statuss brīdī, kad tas notika.

#### <a name="officeappdomainunhandledexceptionhandlerfailed"></a>Office.AppDomain.UnhandledExceptionHandlerFailed

Apkopo informāciju par neapstrādātiem izņēmumiem, izmantojot programmu Data Streamer. Šie dati tiek izmantoti, lai pārraudzītu programmas darbspēju. Šo notikumu ģenerē Microsoft Data Streamer Excel pievienojumprogrammai.

Tiek apkopoti tālāk norādītie lauki.

- **Exception** — izņēmuma izsaukuma steks

- **Event Name** — notikuma nosaukums ir notikuma kategorija un notikuma etiķete.

#### <a name="officeextensibilitycomaddinunhandledexception"></a>Office.Extensibility.COMAddinUnhandledException

Notikums, kas tiek ģenerēts, ja COM pievienojumprogramma avarē

Datora analīze: to izmanto kā uzņēmuma darbspējas statusa izskaitļošanas skaitītāju tām pievienojumprogrammām, kas tiek izmantotas secinājumu veikšanai izmēģinājuma laikā, ja pievienojumprogrammas ir gatavas jaunināšanai ražošanas ciklā.  
Globālie ieskati: tos izmanto, lai izskaitļotu globālu, ar konkrētu uzņēmumu nesaistītu pievienojumprogrammu gatavību, kas tiek publicēta vietnē readyforwindows.com, un citiem rīkiem, piemēram, Readiness Toolkit

Tiek apkopoti tālāk norādītie lauki.

**ScopeId** — pašreizējā pavediena tvērums

**Method** — Office metode, kurā radās izņēmums

**Interface** — Office interfeiss, kurā radās izņēmums

**AddinId** — pievienojumprogrammas klases ID

**AddinProgId** — pievienojumprogrammas Prog ID

**AddinFriendlyName** — pievienojumprogrammas draudzīgais nosaukums

**AddinTimeDateStamp** — pievienojumprogrammas laikspiedols no DLL metadatiem

**AddinVersion** — pievienojumprogrammas versija

**AddinFileName** — pievienojumprogrammas faila nosaukums bez faila ceļa

**VSTOAddIn** — vai pievienojumprogramma ir VSTO

**AddinConnectFlag** — pašreizējās ielādes darbība

**LoadAttempts** — pievienojumprogrammas ielādes mēģinājumu skaits

#### <a name="officeextensibilityvbatelemetrybreak"></a>Office.Extensibility.VbaTelemetryBreak

Notikums tiek ģenerēts, kad failam ar iespējotu makro rodas kompilēšanas vai izpildlaika kļūda

Datora analīze: to izmanto kā uzņēmuma darbspējas statusa izskaitļošanas skaitītāju tiem makro tipiem (piemēram, Word makro, Excel makro utt.), kas tiek izmantoti secinājumu veikšanai izmēģinājuma laikā, ja pievienojumprogramma ir gatava jaunināšanai ražošanas ciklā.

Tiek apkopoti tālāk norādītie lauki.

**TagId** — telemetrijas atzīmes ID

**BreakReason** — pārtraukuma iemesls (izpildlaiks, kompilēšana, cita kļūda)

**SolutionType** — risinājuma tips (dokuments, veidne, pievienojumprogramma, COM pievienojumprogramma)

**Data.ErrorCode** — VBA programmas norādītais kļūdas kods

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

#### <a name="officepowerpointsession"></a>**Office.PowerPoint.Session**

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

#### <a name="officethisaddinstartupfailed"></a>Office.ThisAddIn.StartupFailed

Apkopo informāciju par izņēmumu, kas radās programmas Data Streamer startēšanas laikā. Šie dati tiek izmantoti, lai pārraudzītu programmas darbspēju. Šo notikumu ģenerē Microsoft Data Streamer Excel pievienojumprogrammai.

Tiek apkopoti tālāk norādītie lauki.

- **Exception** — izņēmuma izsaukuma steks

- **Event Name** — notikuma nosaukums ir notikuma kategorija un notikuma etiķete.


### <a name="application-feature-performance-subtype"></a>*Lietojumprogrammas līdzekļu izpildes apakštips*

Slikts atbildes laiks vai slikta izpilde tādos scenārijos kā programmas startēšana vai faila atvēršana.

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

#### <a name="officeperformanceboot"></a>Office.Performance.Boot

Tiek apkopots, palaižot Office programmu. Ietver informāciju par to, vai palaišana tika sākta, atverot failu vai palaižot no sākuma izvēlnes, vai tā bija pirmā programmas palaišana, cik daudz atmiņas programma izmanto un vai lietotājam tika rādīts bloķēšanas UI. Izmanto, lai noteiktu, cik ātri Office programmas tiek palaistas un cik daudz atmiņas tās izmanto, kad tiek startētas, lai nodrošinātu pieņemamas lietošanas iespējas.

Tiek apkopoti šādi lauki:

  - **ActivationKind** — vai programma tika startēta, palaižot no sākuma izvēlnes, atverot failu vai izmantojot OLE automatizāciju.

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

  - **Data_Reason** — netiek izmantots

#### <a name="officeuxofficeinsidershowofficeinsiderdlg"></a>Office.UX.OfficeInsider.ShowOfficeInsiderDlg

Darbība, kas izseko Office Insider dialoga lietojumu un veiktspēju.

Tiek apkopoti šādi lauki:

  - **Data_AcceptedContactMeNew** — izlemjot piedalīties Insider līmenī un ja lietotāja izvēle tika sekmīgi reģistrēta, norāda, vai lietotājs akceptēja saziņu ar to no Microsoft puses.

  - **Data_DialogChoice** — netiek izmantots
  
  - **Data_DialogId** — netiek izmantots
  
  - **Data_Event** — netiek izmantots
  
  - **Data_EventInfo** — netiek izmantots
  
  - **Data_InsiderLevel** — Insider līmenis, kad dialogs pirmo reizi tiek parādīts lietotājam.
  
  - **Data_InsiderLevelNew** — jaunais Insider līmenis, ko atlasīja lietotājs.
  
  - **Data_IsInternalUser** — norāda, vai programma darbojas ar @microsoft.com konta akreditācijas datiem.
  
  - **Data_IsInternalUserInit** — norāda, vai kods varēja noteikt to, vai programma darbojas ar @microsoft.com konta akreditācijas datiem.
  
  - **Data_OpenNewsletterWebpage** — kad ir iespējots Office Insider biļetena abonēšanas līdzeklis un lietotājs pārslēdzas uz Insider līmeni no ražošanas līmeņa, norāda, vai tika izraisīta pārlūka navigācija uz Office Insider biļetena abonēšanas saiti.

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

### <a name="application-activity-error-subtype"></a>*Lietojumprogrammas darbības kļūdas apakštips*

Līdzekļa funkcionalitātes vai lietošanas iespēju kļūdas.

#### <a name="officeairspacebackendwin32graphicsdriversofthang"></a>Office.AirSpace.Backend.Win32.GraphicsDriverSoftHang 

Palīdz Microsoft nošķirt videokartes draivera nereaģēšanas gadījumus no īsākiem gadījumiem, lai vieglāk pieņemtu lēmumus par to, kuriem videokartes draiveriem, iespējams, ir radušās problēmas. Lietotāja videokartes draiveris izraisīja situāciju, kurā Office pārtrauca reaģēt, taču šīs situācijas ietekme vēl nav zināma

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_InDeviceCall** — metode izsauca videokarti, kas izraisīja reaģēšanas pārtraukumu

  - **Data\_Timeout** — cik ilgi nereaģēja

#### <a name="officegraphicsarcexceptions"></a>Office.Graphics.ARCExceptions 

Šī izņēmuma uzrādītā informācija ir svarīga, lai izvērtētu kopējo grafikas steka darbspēju, kā arī identificētu tās koda daļas, kur kļūmes radās ar lielu intensitāti, lai noteiktu izmeklēšanas prioritātes. Šī izņēmuma uzrādītā informācija ir svarīga, lai izvērtētu kopējo grafikas steka darbspēju, kā arī identificētu tās koda daļas, kur kļūmes radās ar lielu intensitāti. Tas palīdz inženierim noteikt, kuras atveidošanas kļūmes ietekmē lielāko daļu lietotāju, lai mēs varētu noteikt prioritātes mūsu ieguldījumiem, vēršot tos uz tādu problēmu novēršanu, kas lietotājiem sniegs vislielāko ieguvumu.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_HResult** — kļūmes atgrieztais kļūdas kods

  - **Data\_TagCount** — katras radušās kļūmes skaits

  - **Data\_TagID** — radušās kļūmes identifikators

#### <a name="officeoutlookdesktopcalendaracceptcalsharenavigatetosharedfoldererror"></a>Office.Outlook.Desktop.Calendar.AcceptCalShareNavigateToSharedFolder\_Error

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

  - **CountExceptionForward — pārsūtīto sapulces izņēmumu skaits**

  - **CountExceptionForwardAsiCal — pārsūtīto sapulces izņēmumu kā iCal skaits**

  - **CountExceptionForwardInSplit — pārsūtīto sapulces izņēmumu skaits no sadalīšanas izvēlnes lentē**

  - **CountExceptionForwardWithAttach — pārsūtīto sapulces izņēmumu kā pielikumu skaits**

  - **CountRecurringForward — pārsūtīto periodisko sapulču skaits**

  - **CountRecurringForwardAsiCal — pārsūtīto periodisko sapulču kā iCal skaits**

  - **CountRecurringForwardInSplit — pārsūtīto periodisko sapulču skaits no sadalīšanas izvēlnes lentē**

  - **CountRecurringForwardWithAttach — pārsūtīto periodisko sapulču kā pielikumu skaits**

  - **CountSingleForward — pārsūtīto atsevišķo sapulču skaits**

  - **CountSingleForwardAsiCal — pārsūtīto atsevišķo sapulču kā iCal skaits**

  - **CountSingleForwardInSplit — pārsūtīto atsevišķo sapulču skaits no sadalīšanas izvēlnes lentē**

  - **CountSingleForwardWithAttach — pārsūtīto atsevišķo sapulču kā pielikumu skaits**

  - **HResult — kļūdas kods**

  - **OlkViewName — norāda pasta, kalendāra vai kontroliera skatu**

#### <a name="officeoutlookdesktopoutlookcalendarusageerrmeetrcptreplyactionsruleo16"></a>Office.Outlook.Desktop.OutlookCalendarUsageErr.MeetRcpt.ReplyActions.Rule.O16

Apkopo sekmīgas un nesekmīgas darbību Atbildēt, Atbildēt visiem, Atbildēt ar IM un Atbildēt visiem ar IM izpildes reizes atsevišķām, periodiskām un izņēmuma sapulces atbildēm pasta, kalendāra un kontroliera Outlook skatā. Darbību Atbildēt, Atbildēt visiem, Atbildēt ar IM un Atbildēt visiem ar IM tiek aktīvi pārraudzītas, lai konstatētu anomālijas. Anomāla statistika norāda par kļūmi, kad Outlook nespēj veikt pamata kalendāra darbības. Šos datus izmanto arī, lai diagnosticētu citas ar kalendāru saistītas problēmas, kas var tikt konstatētas.

Tiek apkopoti tālāk norādītie lauki.

  - **CountExceptionReply — izņēmuma sapulces atbilžu skaits**

  - **CountExceptionReplyAll — izņēmuma sapulces atbilžu visiem skaits**

  - **CountExceptionReplyAllWithIM — izņēmuma sapulces atbilžu visiem ar IM skaits**

  - **CountExceptionReplyWithIM — izņēmuma sapulces atbilžu ar IM skaits**

  - **CountRecurringReply — periodiskas sapulces atbilžu skaits**

  - **CountRecurringReplyAll — periodiskas sapulces atbilžu visiem skaits**

  - **CountRecurringReplyAllWithIM — periodiskas sapulces atbilžu visiem ar IM skaits**

  - **CountRecurringReplyWithIM — periodiskas sapulces atbilžu ar IM skaits**

  - **CountSingleReply — atsevišķas sapulces atbilžu skaits**

  - **CountSingleReplyAll — atsevišķas sapulces atbilžu visiem skaits**

  - **CountSingleReplyAllWithIM — atsevišķas sapulces atbilžu visiem ar IM skaits**

  - **CountSingleReplyWithIM — atsevišķas sapulces atbilžu ar IM skaits**

  - **HResult — kļūdas kods**

  - **OlkViewName — norāda pasta, kalendāra vai kontroliera skatu**

#### <a name="officeoutlookdesktopoutlookprivsdlgsingleuserloadfail"></a>Office.Outlook.Desktop.OutlookPrivsDlgSingleUser.LoadFail

Šī kārtula apkopo kalendāra koplietošanas kļūdas, pievienojot lietotāju (EX vai SMTP tips) no adrešu grāmatas. Šie dati tiek izmantoti, lai diagnosticētu un novērstu problēmas, kas konstatētas dialoglodziņā Kalendāra koplietošana

Tiek apkopoti tālāk norādītie lauki.

  - **CountAccountWizardEnd** — cik reizes tika izbeigts mantotā vedņa dialoglodziņš

  - **CountCreatePIMAccount** — cik reizes lietotājs ir izveidojis PIM profilu

#### <a name="officesystemsystemhealthasserts"></a>Office.System.SystemHealthAsserts

Šī notikuma konstatētās kļūdas palīdz mums izprast, kad ir pasliktināta klienta lietošanas pieredze. Daudzas no šīm ShipAsserts darbībām izraisa avārijas, un šī informācija ļauj izlabot daudzas no šīm problēmām. Apkopo ShipAsserts no produkta, kas palīdz konstatēt kļūdas.

Tiek apkopoti tālāk norādītie lauki.

Count — uzrādīto apliecinājumu skaits

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

## <a name="device-connectivity-and-configuration-data-events"></a>Ierīču savienojamības un konfigurācijas datu notikumi

Tālāk ir norādīti šīs kategorijas datu apakštipi.

- [Ierīču savienojamība un konfigurācija](#device-connectivity-and-configuration-subtype)


### <a name="device-connectivity-and-configuration-subtype"></a>*Ierīču savienojamības un konfigurācijas apakštips*

Tīkla savienojuma statuss un ierīces iestatījumi, piemēram, atmiņas iestatījumi.

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

Tiek apkopoti tālāk norādītie lauki.

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
