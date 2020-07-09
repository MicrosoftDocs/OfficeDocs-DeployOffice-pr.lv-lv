---
title: Politikas iestatījumu izmantošana, lai pārvaldītu Microsoft 365 programmu lieluzņēmumiem konfidencialitātes vadīklas
ms.author: danbrown
author: DHB-MSFT
manager: laurawi
audience: ITPro
ms.topic: article
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection:
- Ent_O365
- M365-modern-desktop
ms.custom:
- Ent_Office_ProPlus
- Ent_Office_Privacy
description: Nodrošina Office administratoriem informāciju par to, kā pārvaldīt konfidencialitātes kontroles līdzekļus Microsoft 365 programmās lieluzņēmumiem (iepriekš Office 365 ProPlus), izmantojot politikas iestatījumus.
hideEdit: true
ms.openlocfilehash: 5f9cafff0f7baf12ed8f0f57d7561bc356fbb98b
ms.sourcegitcommit: f441b1a5f8853c0941b3e23c7781c89abf0be641
ms.translationtype: HT
ms.contentlocale: lv-LV
ms.lasthandoff: 07/09/2020
ms.locfileid: "45087212"
---
# <a name="use-policy-settings-to-manage-privacy-controls-for-microsoft-365-apps-for-enterprise"></a>Politikas iestatījumu izmantošana, lai pārvaldītu Microsoft 365 programmu lieluzņēmumiem konfidencialitātes vadīklas

Korporācija Microsoft ir apņēmusies nodrošināt jūs ar informāciju un kontroles līdzekļiem, kas ir nepieciešami, lai pieņemtu lēmumus par to, kā jūsu dati tiek apkopoti un izmantoti, kad lietojat Microsoft 365 programmas lieluzņēmumiem (iepriekš Office 365 ProPlus).

Sākot ar Microsoft 365 programmu lieluzņēmumiem versiju 1904, ir jauni politikas iestatījumi, kuri nodrošina iespēju kontrolēt ar šādām iespējām saistītus iestatījumus:

- ***Diagnostikas dati***, kas tiek apkopoti un nosūtīti korporācijai Microsoft par izmantoto Office klienta programmatūru.

- ***Saistītie līdzekļi***, kas izmanto mākoņa funkcionalitāti, lai nodrošinātu uzlabotus Office līdzekļus jums un jūsu lietotājiem.

Tālāk ir nosaukti pieci jaunie politikas iestatījumi:

- Konfigurēt to klienta programmatūras diagnostikas datu līmeni, kurus Office nosūta korporācijai Microsoft
- Atļaut Office izmantot saistītos līdzekļus, kuri analizē saturu
- Atļaut Office izmantot saistītos līdzekļus, kuri lejupielādē tiešsaistes saturu
- Atļaut Office izmantot papildu neobligātos saistītos līdzekļus
- Atļaut Office izmantot saistītos līdzekļus

Šos politikas iestatījums var ieviest, izmantojot grupas politiku vai [Office mākoņa politikas pakalpojumu](../overview-office-client-policy-service.md). Ja izmantojot grupas politiku, ir nepieciešams [Microsoft lejupielādes centrā](https://www.microsoft.com/download/details.aspx?id=49030) lejupielādēt visjaunāko administratīvo veidņu failu (ADMX/ADML) versiju.

> [!NOTE]
> - Informāciju par to, kā pārvaldīt Office darbam ar Mac konfidencialitātes kontroles līdzekļus, skatiet rakstā [Preferenču izmantošana Office darbam ar Mac konfidencialitātes kontroles līdzekļu pārvaldībai](mac-privacy-preferences.md).
> - Papildinformāciju par līdzīgu Office iestatījumu izmantošanu iOS ierīcēs, skatiet rakstā [Preferenču izmantošana iOS ierīcēs konfidencialitātes kontroles līdzekļu pārvaldībai](ios-privacy-preferences.md).
> - Papildinformāciju par līdzīgu Office iestatījumu izmantošanu Android ierīcēs skatiet rakstā [Politikas iestatījumu izmantošana Office konfidencialitātes kontroles līdzekļu pārvaldībai Android ierīcēs](android-privacy-controls.md).


Ja izmantojat grupas politikas pārvaldības rīku, visi šie politikas iestatījumi atrodas sadaļā Lietotāja konfigurācija\\Politikas\\Administratīvās veidnes\\Microsoft Office 2016\\Konfidencialitāte\\Drošības kontroles centrs.

Šie jaunie politiku iestatījumi tiek piemēroti arī datoriem paredzētajām programmām Project un Visio, kurām tiek piedāvāti abonēšanas plāni, piemēram, Project 5. plāns vai Visio 2. plāns Tie tiek piemēroti arī Microsoft 365 programmām darbam (iepriekš Office 365 darbam).

Daži no esošajiem politikas iestatījumiem vairs netiks lietoti Microsoft 365 programmās lieluzņēmumiem, un ir veiktas arī dažas ar konfidencialitātes iestatījumiem saistītas izmaiņas lietotāja interfeisā, par kurām jums jābūt informētam, jo lietotāji tās, iespējams, pamanīs un par tām vaicās.

Tāpat kā ar visiem jaunajiem politikas iestatījumiem jums tie ir uzmanīgi jāizmēģina ierobežotā, kontrolētā vidē, lai pārliecinātos, vai konfigurētie iestatījumi sniedz nepieciešamo efektu; tikai pēc tam ieviesiet politikas iestatījumus savā organizācijā plašākā mērogā.

## <a name="policy-setting-for-diagnostic-data"></a>Diagnostikas datu politikas iestatījums

Diagnostikas dati tiek izmantoti, lai uzturētu Office drošu un atjauninātu, noteiktu, diagnosticētu un novērstu problēmas, kā arī uzlabotu produktu.

Politikas iestatījumu *Konfigurēt to klienta programmatūras diagnostikas datu līmeni, kurus Office nosūta korporācijai Microsoft* var izmantot, lai izvēlētos, kāda līmeņa diagnostikas dati tiek nosūtīti korporācijai Microsoft.

Ja šis politikas iestatījums ir iespējots, jums ir jāizvēlas, kāda līmeņa diagnostikas dati tiek nosūtīti korporācijai Microsoft. Pieejamās vērtības ir Nepieciešamie, Neobligātie un Neviens no šiem.

- Ja izvēlaties ***Nepieciešamie***, tad korporācijai Microsoft tiek nosūtīti minimālie dati, kas nepieciešami, lai Office uzturētu drošu, atjauninātu un ar paredzēto veiktspēju atbilstošajā ierīcē.

- Ja izvēlaties ***Neobligātie***, korporācijai Microsoft tiek nosūtīti papildu dati, kas palīdz uzlabot produktu un nodrošina papildu informāciju, kura palīdz noteikt, diagnosticēt un novērst problēmas. Ja izvēlaties nosūtīt neobligātos diagnostikas datus, tiek iekļauti arī nepieciešamie diagnostikas dati.

- Ja izvēlaties ***Neviens no šiem***, korporācijai Microsoft netiek nosūtīti nekādi diagnostikas dati par Office klienta programmatūru, kas darbojas lietotāja ierīcē. Tomēr šī opcija būtiski ierobežo Microsoft iespējas noteikt, diagnosticēt un novērst problēmas, kas jūsu lietotājiem var rasties, izmantojot Office.

Ja šis politikas iestatījums tiek atspējots vai netiek konfigurēts, korporācijai Microsoft tiek nosūtīti gan neobligātie, gan obligātie diagnostikas dati.

Papildinformāciju par diagnostikas datiem lasiet šajos rakstos:

- [Microsoft 365 programmu lieluzņēmumiem konfidencialitātes vadīklu pārskats](overview-privacy-controls.md)
- [Nepieciešamie Office diagnostikas dati](required-diagnostic-data.md)
- [Neobligātie Office diagnostikas dati](optional-diagnostic-data.md)
- [Diagnostikas datu skatītāja izmantošana ar Office](https://support.office.com/article/cf761ce9-d805-4c60-a339-4e07f3182855)

## <a name="policy-settings-for-connected-experiences"></a>Saistīto līdzekļu politikas iestatījumi

Microsoft 365 programmas lieluzņēmumiem sastāv no klienta programmām un saistītajiem līdzekļiem, kas paredzēti, lai jūs varētu efektīvāk radīt, sazināties un sadarboties. Darbs kopā ar citiem lietotājiem, strādājot pie dokumenta, kas glabājas OneDrive darbam krātuvē, vai Word dokumenta satura tulkošana citā valodā ir saistīto līdzekļu piemēri.

Mēs saprotam, ka varat vēlēties noteikt, kādu veidu saistītie līdzekļi ir pieejami lietotājiem, strādājot Office programmās. Tāpēc piedāvājam četrus jaunus politikas iestatījumus:

- Atļaut Office izmantot saistītos līdzekļus, kuri analizē saturu
- Atļaut Office izmantot saistītos līdzekļus, kuri lejupielādē tiešsaistes saturu
- Atļaut Office izmantot papildu neobligātos saistītos līdzekļus
- Atļaut Office izmantot saistītos līdzekļus

Ja nekonfigurēsit šos politikas iestatījumus, būs pieejami visi saistītie līdzekļi. Tādējādi lietotājiem būs pieejami visi Microsoft 365 programmu lieluzņēmumiem līdzekļi un funkcijas. Tomēr mēs saprotam, ka jums var būt nepieciešams izslēgt dažus vai visus saistītos līdzekļus, lai ievērotu organizācijā noteiktās prasības.

Ja izvēlaties lietotājiem nenodrošināt noteiktu veidu saistītos līdzekļus, to komandas lentē vai izvēlnē būs pelēkotas vai arī lietotāji saņems kļūdas ziņojumu, kad mēģinās lietot šos saistītos līdzekļus. Šādos gadījumos korporācijai Microsoft netiks nosūtīti [nepieciešamie pakalpojuma dati](required-service-data.md) par šiem saistītajiem līdzekļiem.

Jūsu lietotāji nevarēs izvēlēties ieslēgt vai izslēgt šos Microsoft 365 programmās lieluzņēmumiem iekļautos saistītos līdzekļus, ja tie būs pierakstījušies pakalpojumā Office ar savas organizācijas akreditācijas datiem, kas dažkārt tiek dēvēti par darba vai mācību kontu.

### <a name="policy-setting-for-connected-experiences-that-analyze-your-content"></a>Politikas iestatījums saistītajiem līdzekļiem, kuri analizē jūsu saturu

Šie ir līdzekļi, kas izmanto jūsu Office saturu, lai sniegtu noformējuma ieteikumus, rediģēšanas ieteikumus, datu ieskatus un līdzīgas iespējas. Piemēram, PowerPoint noformētājs vai tulkotājs programmā Word. Pilnīgāku saistīto līdzekļu sarakstu skatiet rakstā [Office saistītie līdzekļi](connected-experiences.md).

Politikas iestatījumu *Atļaut Office izmantot saistītos līdzekļus, kuri analizē saturu* var izmantot, lai kontrolētu, vai lietotājiem ir pieejami šāda veida saistītie līdzekļi. Ja nekonfigurēsit šo politikas iestatījumu, lietotājiem būs pieejami visi šie saistītie līdzekļi.

Ņemiet vērā: ja atspējojat politikas iestatījumu *Atļaut Office izmantot saistītos līdzekļus*, lietotājiem nav pieejami saistītie līdzekļi, kuri analizē saturu.

### <a name="policy-setting-for-connected-experiences-that-download-online-content"></a>Politikas iestatījums saistītajiem līdzekļiem, kuri lejupielādē tiešsaistes saturu

Šīs ir lietošanas iespējas, kas ļauj meklēt un lejupielādēt tiešsaistes saturu, tostarp veidnes, attēlus, 3D modeļus, video un atsauces materiālus, lai uzlabotu jūsu dokumentus. Piemēram, Office veidnes vai PowerPoint ātrais sākums. Pilnīgāku saistīto līdzekļu sarakstu skatiet rakstā [Office saistītie līdzekļi](connected-experiences.md).

Politikas iestatījumu *Atļaut Office izmantot saistītos līdzekļus, kuri lejupielādē tiešsaistes saturu* var izmantot, lai kontrolētu, vai lietotājiem ir pieejami šāda veida saistītie līdzekļi. Ja nekonfigurēsit šo politikas iestatījumu, lietotājiem būs pieejami visi šie saistītie līdzekļi.

Ņemiet vērā: ja atspējojat politikas iestatījumu *Atļaut Office izmantot saistītos līdzekļus*, lietotājiem nav pieejami saistītie līdzekļi, kuri lejupielādē tiešsaistes saturu.

### <a name="policy-setting-for-optional-connected-experiences"></a>Politikas iestatījums neobligātajiem saistītajiem līdzekļiem

Papildus iepriekš minētajiem saistītajiem līdzekļiem, kas ir iekļauti pakalpojumā Microsoft 365 programmas lieluzņēmumiem, pastāv papildu saistītie līdzekļi, kurus varat atļaut lietotājiem izmantot, lietojot organizācijas kontu. Piemēram, CV palīga LinkedIn līdzekļi programmā Word vai 3D karšu līdzeklis programmā Excel, kas izmanto Bing. Citus piemērus skatiet rakstā [Pārskats par Office neobligātajiem saistītajiem līdzekļiem](optional-connected-experiences.md).

Šie saistītie līdzekļi var atšķirties, jo uz tiem neattiecas jūsu organizācijas komerclīgums ar korporāciju Microsoft. Neobligātos saistītos līdzekļus Microsoft piedāvā tieši lietotājiem, un to darbību regulē [Microsoft pakalpojumu līgums](https://www.microsoft.com/servicesagreement), nevis [tiešsaistes pakalpojumu nosacījumi](https://www.microsoft.com/licensing/product-licensing/products). Dažos gadījumos šo neobligāto saistīto līdzekļu ietvaros tiek nodrošināts trešo pušu saturs vai funkcijas un ir spēkā citi nosacījumi. Papildinformāciju skatiet rakstā [Pārskats par Office neobligātajiem saistītajiem līdzekļiem](optional-connected-experiences.md).

Politikas iestatījumu *Atļaut Office izmantot papildu neobligātos saistītos līdzekļus* var izmantot, lai kontrolētu, vai lietotājiem ir pieejami šāda veida saistītie līdzekļi. Ja nekonfigurēsit šo politikas iestatījumu, jūsu lietotājiem būs pieejami šie papildu saistītie līdzekļi.

> [!NOTE]
> Politikas iestatījumu *Atļaut Office izmantot papildu neobligātos saistītos līdzekļus* iespējams konfigurēt lietošanai arī šādās Office darbam tīmeklī lietojumprogrammām:
> - Excel darbam tīmeklī
> - OneNote darbam tīmeklī
> - PowerPoint darbam tīmeklī
> - Visio darbam tīmeklī
> - Word darbam tīmeklī
>
> Lai konfigurētu šo politikas iestatījumu šīm Office darbam tīmeklī lietojumprogrammām, ir jāizmanto [Office mākoņa politikas pakalpojums](../overview-office-cloud-policy-service.md).

Pat tad, ja izvēlaties šos neobligātos saistītos līdzekļus padarīt pieejamus saviem lietotājiem, tiem būs iespēja izslēgt šos līdzekļus kā grupu, dodoties uz [konfidencialitātes iestatījumu dialoglodziņu](https://support.office.com/article/3e7bc183-bf52-4fd0-8e6b-78978f7f121b). Lietotājiem šī izvēle būs tikai tad, ja tie būs pierakstījušies pakalpojumā Office ar organizācijas akreditācijas datiem (dažkārt tos sauc par darba vai mācību kontu), bet ne ar personisko e-pasta adresi.

Turklāt daži no šiem neobligātajiem saistītajiem līdzekļiem tiek uzskatīti arī par saistītajiem līdzekļiem, kuri analizē saturu vai lejupielādē tiešsaistes saturu. Piemēram, Tiešsaistes attēlu ievietošana ir neobligāts saistītais līdzeklis, kura darbību nodrošina Microsoft Bing, bet tas tiek uzskatīts arī par saistīto līdzekli, kurš lejupielādē tiešsaistes saturu. Tāpēc ņemiet vērā: ja atspējojat politikas iestatījumu *Atļaut Office izmantot saistītos līdzekļus, kuri lejupielādē tiešsaistes saturu*, lietotājiem nav pieejams līdzeklis Tiešsaistes attēlu ievietošana. Tas nav pieejams pat tad, ja esat iespējojis politikas iestatījumu *Atļaut Office izmantot papildu neobligātos saistītos līdzekļus*. Papildinformāciju par to, kuri saistītie līdzekļi analizē saturu vai lejupielādē tiešsaistes saturu, skatiet rakstā [Office saistītie līdzekļi](connected-experiences.md).

Pastāv viens izņēmums, kas jāņem vērā. Politikas iestatījums *Atļaut Office izmantot papildu neobligātos saistītos līdzekļus* nekontrolē saistītos līdzekļus, kuri pieprasa savienot jūsu LinkedIn kontu ar Microsoft darba vai mācību kontu. Lai kontrolētu šāda veida līdzekļus (piemēram, LinkedIn informāciju [profila kartītē](https://support.office.com/article/365-e80f931f-5fc4-4a59-ba6e-c1e35a85b501) programmā Outlook), skatiet rakstu [LinkedIn un Microsoft kontu saistīšana](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381) un [Piekrišana LinkedIn kontu savienošanai Azure Active Directory organizācijā](https://docs.microsoft.com/azure/active-directory/users-groups-roles/linkedin-integration).

### <a name="policy-setting-for-most-connected-experiences"></a>Politikas iestatījums lielākajai daļai saistīto līdzekļu

Politikas iestatījumu *Atļaut Office izmantot saistītos līdzekļus* var izmantot, lai kontrolētu, vai lietotājiem ir pieejama lielākā daļa saistīto līdzekļu, kas tiek piedāvāti Microsoft 365 programmās lieluzņēmumiem. Ja šis politikas iestatījums ir atspējots, lietotājiem nav pieejami tālāk nosaukto veidu saistītie līdzekļi.

- Lietošanas iespējas, kas analizē jūsu saturu
- Lietošanas iespējas, kas lejupielādē tiešsaistes saturu
- Neobligātie saistītie līdzekļi

Turklāt, ja šis politikas iestatījums ir atspējots, tiek izslēgta arī lielākā daļa pārējo saistīto līdzekļu, piemēram, koprediģēšana un failu tiešsaistes krātuve. Pilnīgāku šo pārējo saistīto līdzekļu sarakstu skatiet rakstā [Office saistītie līdzekļi](connected-experiences.md).

Tomēr pat tad, ja atspējosit šo politikas iestatījumu, dažas Office funkcijas joprojām būs pieejamas, piemēram, programmā Outlook tiks sinhronizēta pastkaste un joprojām darbosies Teams un Skype darbam. Joprojām būs pieejami arī [būtiskie pakalpojumi](essential-services.md), piemēram, licencēšanas pakalpojums, kurš apstiprina, ka pakalpojums Office ir atbilstoši licencēts.

## <a name="existing-policy-settings-that-are-replaced-by-new-policy-settings"></a>Esošie politikas iestatījumi, kurus aizstāj jauni politikas iestatījumi

Ir divi esošie politikas iestatījumi, kuri vairs nav spēkā, sākot ar Microsoft 365 programmām lieluzņēmumiem versiju 1904. Šie politikas iestatījumi ir:

- **Nosūtīt personas informāciju**, kas atrodas sadaļā Lietotāja konfigurācija\\Politikas\\Administratīvās veidnes\\Microsoft Office 2016\\Konfidencialitāte\\Drošības kontroles centrs.

- **Tiešsaistes satura opcijas**, kas atrodas sadaļā Lietotāja konfigurācija\\Politikas\\Administratīvās veidnes\\Microsoft Office 2016\\Rīki | Opcijas | Vispārīgi | Pakalpojuma opcijas...\\Tiešsaistes saturs.

Sākot ar versiju 1904, šo divu esošo politikas iestatījumu konfigurācija neietekmē Microsoft 365 programmas lieluzņēmumiem. Tie vairs nav spēkā, jo to funkcijas veic šie jaunie politikas iestatījumi:

- Atļaut Office izmantot saistītos līdzekļus, kuri analizē saturu
- Atļaut Office izmantot saistītos līdzekļus, kuri lejupielādē tiešsaistes saturu
- Atļaut Office izmantot papildu neobligātos saistītos līdzekļus
- Atļaut Office izmantot saistītos līdzekļus

Šie jaunie politikas iestatījumi nodrošina precīzāku kontroli nekā divi esošie politikas iestatījumi. Piemēram, ja iepriekš izmantojāt politikas iestatījumu *Nosūtīt personas informāciju*, tika izslēgts gan PowerPoint ātrais sākums, gan viedā uzmeklēšana. Toties tagad, ja izmantojat jauno politikas iestatījumu *Atļaut Office izmantot saistītos līdzekļus, kuri analizē saturu*, lai izslēgtu šāda veida saistītos līdzekļus, tiek izslēgta tikai viedā uzmeklēšana. PowerPoint ātrais sākums lietotājiem joprojām ir pieejams.

Politikas iestatījumi joprojām tiek rādīti grupas politikas pārvaldības rīkā, jo tie joprojām ir spēkā Office 2016 un Office 2019 lielapjoma licencēšanas versijām, piemēram, Office Professional Plus 2019.

## <a name="what-about-existing-policy-settings-that-control-connected-experiences"></a>Kas notiek ar esošajiem politikas iestatījumiem, kuri kontrolē saistītos līdzekļus?

Kā jūs, iespējams, jau zināt, daži esošie politikas iestatījumi ļauj kontrolēt saistītos līdzekļus. Tālāk ir aprakstīti daži esošo politikas iestatījumu piemēri.

- *PowerPoint noformētāja opcijas* sadaļā Lietotāja konfigurācija\\Politikas\\Administratīvās veidnes\\Microsoft Office 2016\\Rīki | Opcijas | Vispārīgi | Pakalpojuma opcijas...\\PowerPoint noformētājs

- *Izslēgt ātro sākumu* sadaļā Lietotāja konfigurācija\\Politikas\\Administratīvās veidnes\\Microsoft PowerPoint 2016\\PowerPoint opcijas\\Vispārīgi

- *Atļaut LinkedIn CV palīga līdzekli* sadaļā Lietotāja konfigurācija\\Politikas\\Administratīvās veidnes\\Microsoft Word 2016\\Word opcijas\\Vispārīgi

 Šos esošos politikas iestatījumus joprojām varat izmantot, ja vēlaties izslēgt atsevišķus saistītos līdzekļus. Tomēr ņemiet vērā: izmantojot kādu no jaunajiem politikas iestatījumiem, tas var izslēgt saistīto līdzekli, ko esat ieslēdzis, izmantojot citu politikas iestatījumu. Piemēram, ja iespējojat politikas iestatījumu *Atļaut LinkedIn CV palīga līdzekli*, bet atspējojat politikas iestatījumu *Atļaut Office izmantot saistītos līdzekļus*, LinkedIn CV palīgs lietotājiem nebūs pieejams.

Parasti gadījumos, kad viens politikas iestatījums ir konfigurēts, lai ieslēgtu noteiktu saistīto līdzekli, bet vienlaikus cits politikas iestatījums ir konfigurēts izslēgt šāda veida saistītos līdzekļus, konkrētais saistītais līdzeklis lietotājiem tiek izslēgts.

## <a name="privacy-related-changes-to-the-office-ui"></a>Ar konfidencialitāti saistītas izmaiņas Office lietotāja interfeisā

Microsoft 365 programmu lieluzņēmumiem lietotāja interfeisā ir ieviestas dažas ar konfidencialitāti saistītas izmaiņas, kuras lietotāji, iespējams, pamanīs un par tām vaicās. Šīs izmaiņas ir tieši saistītas ar jaunajiem konfidencialitātes kontroles līdzekļiem un politikas iestatījumiem, kuri ir pieejami, sākot no versijas 1904.

### <a name="dialog-about-optional-connected-experiences"></a>Dialoglodziņš par neobligātajiem saistītajiem līdzekļiem

Ja esat izvēlējies nodrošināt lietotājiem [neobligātos saistītos līdzekļus](optional-connected-experiences.md), tad, lietotājiem pēc atjaunināšanas uz versiju 1904 vai jaunāku versiju pirmo reizi atverot Office programmu, tiks parādīts informatīvs dialoglodziņš. Šis dialoglodziņš informē lietotājus par to, ka viņiem ir piešķirta iespēja izmantot šos neobligātos saistītos līdzekļus, kā arī norāda, ka šo iestatījumu var mainīt sadaļā **Fails** > **Konts** > **Konta konfidencialitāte**.

### <a name="privacy-settings-removed-from-the-office-ui"></a>No Office lietotāja interfeisa noņemtie konfidencialitātes iestatījumi

Tālāk norādītie iestatījumi ir noņemti sadaļā **Fails** > **Opcijas** > **Drošības kontroles centrs** > **Drošības kontroles centra iestatījumi…** > **Privātuma opcijas**:

- Iegūstiet noformējumus, informāciju, ieteikumus un pakalpojumus, ļaujot Office piekļūt un uzlabot produktus atbilstoši ierīcē esošajam Office saturam.

- Atļaut sistēmai Office izveidot savienojumu ar Microsoft tiešsaistes pakalpojumiem, lai nodrošinātu jūsu lietojumam un preferencēm atbilstošas funkcijas.

Sadaļā **Fails** > **Opcijas** > **Vispārīgi** ir noņemta arī opcija iespējot Office intelektiskos pakalpojumus.

Kā savas organizācijas administrators jūs tagad kontrolējat šiem iestatījumiem ekvivalentus iestatījumus, ko nodrošina iepriekš aprakstītie jaunie politikas iestatījumi.

### <a name="privacy-settings-added-to-the-office-ui"></a>Office lietotāja interfeisam pievienotie konfidencialitātes iestatījumi

Office lietotāja interfeisam ir pievienoti tālāk nosauktie jaunie elementi.

- Sadaļā **Fails** > **Konts** lietotājiem tiek rādīta jauna izvēles iespēja **Konta konfidencialitāte** > **Pārvaldīt iestatījumus**. Tā atrodas sadaļā **Pārvaldīt iestatījumus**, kur lietotāji var izslēgt papildu saistītos līdzekļus, ja esat viņiem sniedzis šādu iespēju.

- Sadaļā **Fails** > **Opcijas** > **Drošības kontroles centrs** > **Drošības kontroles centra iestatījumi…** > **Privātuma opcijas** ir opcija ierīcē iespējot rīka [Diagnostikas datu skatītājs](https://support.office.com/article/cf761ce9-d805-4c60-a339-4e07f3182855) lietošanu.

 
## <a name="control-privacy-settings-by-editing-the-registry"></a>Konfidencialitātes iestatījumu kontrole, rediģējot reģistru

Daži administratori izvēlas mainīt iestatījumus tieši reģistrā, piemēram, izmantojot skriptu, nevis izmantojot grupas politiku vai Office mākoņa politikas pakalpojumu. Varat izmantot tālāk norādīto informāciju, lai konfidencialitātes iestatījumus konfigurētu tieši reģistrā.


|**Politikas iestatījums** |**Reģistra iestatījums**  |**Vērtības**  |
|---------|---------|---------|---------|
|Konfigurēt to klienta programmatūras diagnostikas datu līmeni, kurus Office nosūta korporācijai Microsoft  | SendTelemetry |1=nepieciešams <br/> 2=neobligāts <br/> 3=Ne viens, ne otrs|
|Atļaut Office izmantot saistītos līdzekļus, kuri analizē saturu  | UserContentDisabled | 1=iespējots <br/> 2=atspējots|
|Atļaut Office izmantot saistītos līdzekļus, kuri lejupielādē tiešsaistes saturu  | DownloadContentDisabled | 1=iespējots <br/> 2=atspējots|
|Atļaut Office izmantot papildu neobligātos saistītos līdzekļus   | ControllerConnectedServicesEnabled  |1=iespējots <br/> 2=atspējots|
|Atļaut Office izmantot saistītos līdzekļus | DisconnectedState  | 1=iespējots <br/> 2=atspējots|

Lai izveidotu .reg failu konfidencialitātes iestatījumiem, atveriet programmu Piezīmjbloks un kopējiet tālāk norādītās rindiņas. Pielāgojiet vērtības atbilstoši savām vajadzībām un pēc tam saglabājiet failu. Pārliecinieties, vai faila nosaukuma paplašinājums ir .reg

```console
Windows Registry Editor Version 5.00

[HKEY_CURRENT_USER\Software\Policies\Microsoft\office\16.0\common\privacy]
"disconnectedstate"=dword:00000001
"usercontentdisabled"=dword:00000001
"downloadcontentdisabled"=dword:00000001
"controllerconnectedservicesenabled"=dword:00000001

[HKEY_CURRENT_USER\Software\Policies\Microsoft\office\common\clienttelemetry]
"sendtelemetry"=dword:00000002
```

Piemēram, varat izmantot šo .reg failu, skriptā lietojot komandu regedit.exe, lai konfigurētu lietotāja konfidencialitātes iestatījumus.