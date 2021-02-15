---
title: Office būtiskie pakalpojumi
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
description: Sniedz Office administratoriem informāciju par būtiskajiem pakalpojumiem sistēmā Office, piemēram, Click-to-Run un licencēšanu, kā arī nodrošina notikumu un datu lauku sarakstu šiem būtiskajiem pakalpojumiem.
hideEdit: true
ms.openlocfilehash: 7660e79628e31b17fb2b1c606378391419f15e8e
ms.sourcegitcommit: 163de1916420d26e4a0ef9de941fc4e86ade0412
ms.translationtype: HT
ms.contentlocale: lv-LV
ms.lasthandoff: 02/14/2021
ms.locfileid: "50242161"
---
# <a name="essential-services-for-office"></a>Office būtiskie pakalpojumi

> [!NOTE]
> Office produktu, uz kuriem attiecas šī konfidencialitātes informācija, saraksts ir pieejams [Konfidencialitātes kontroles līdzekļi Office produktiem](products-versions-privacy-controls.md).

Office sastāv no klienta programmām un saistītajiem līdzekļiem, kas paredzēti, lai jūs varētu efektīvāk veidot, sazināties un sadarboties. Lai gan varat kontrolēt daudzas savienotās iespējas, kas ir pieejamas jums vai jūsu lietotājiem, ja esat savas organizācijas administrators, pastāv pakalpojumu kopa, kas ir būtiski attiecībā uz to, kā Office darbojas, tāpēc tos nevar atspējot. Piemēram, licencēšanas pakalpojums, kas apstiprina, vai esat pareizi licencēts Office izmantošanai. Nepieciešamie pakalpojumu dati par šiem pakalpojumiem tiek apkopoti un nosūtīti korporācijai Microsoft neatkarīgi no citiem politikas iestatījumiem, kas saistīti ar konfidencialitāti un kurus esat konfigurējis.

Papildinformāciju skatiet šādos rakstos:

- [Office obligātais datu pakalpojums](required-service-data.md)
- [Office saistītie līdzekļi](connected-experiences.md)

Ja esat organizācijas administrators, iespējams, jūs interesēs arī šie raksti:

- [Microsoft 365 programmu lieluzņēmumiem konfidencialitātes vadīklu pārskats](overview-privacy-controls.md)
- [Politikas iestatījumu izmantošana, lai pārvaldītu Microsoft 365 programmu lieluzņēmumiem konfidencialitātes vadīklas](manage-privacy-controls.md)
- [Preferenču izmantošana Office darbam ar Mac konfidencialitātes kontroles līdzekļu pārvaldībai](mac-privacy-preferences.md)
- [Preferenču izmantošana Office darbam ar iOS ierīcēm konfidencialitātes kontroles līdzekļu pārvaldībai](ios-privacy-preferences.md)
- [Politikas iestatījumu izmantošana Office konfidencialitātes kontroles līdzekļu pārvaldībai Android ierīcēs](android-privacy-controls.md)
- [Politikas iestatījumu izmantošana konfidencialitātes kontroles līdzekļus Office programmās tīmeklim](office-web-privacy-controls.md)

## <a name="list-of-essential-services-for-office"></a>Office būtisko pakalpojumu saraksts 

Tālāk esošajā tabulā ir Office būtisko pakalpojumu saraksts, kā arī katra pakalpojuma apraksts.

| **Pakalpojums**  | **Apraksts**  |
| ------ | ---- |
| [Autentifikācija](#authentication-events) | Autentifikācija ir vairāku platformu pakalpojums, kas pārbauda jūsu Office lietotāja identitāti.   Tā ir nepieciešama, lai jums sniegtu iespēju pierakstīties sistēmā Office, aktivizēt jūsu Office licenci, piekļūtu jūsu mākonī saglabātajiem failiem, kā arī nodrošinātu konsekventu pieredzi vairākās Office sesijās un jūsu ierīcēs.    |
| [Click-to-Run](#click-to-run-events) | Click-to-Run ir instalēšanas tehnoloģija, kas tiek izmantota, lai instalētu un atjauninātu sistēmu Office operētājsistēmā Windows. Tā meklē jaunas Office versijas un, kad jauna versija ir pieejama, lejupielādē un instalē to.  Click-to-Run noteiks Office atjauninājumu (tostarp drošības atjauninājumu) nepieciešamību, veiks to lejupielādi un instalēšanu.     |
| [Uzlabotās konfigurācijas pakalpojums (ECS)](#enhanced-configuration-service-ecs-events) | ECS nodrošina korporācijai Microsoft iespēju atkārtoti konfigurēt Office instalācijas tā, lai jums nebūtu atkārtoti jāizvieto Office. Tā tiek izmantota, lai kontrolētu pakāpenisko līdzekļu vai atjauninājumu ieviešanu, kamēr ieviešanas ietekme tiek pārraudzīta no diagnostikas datiem, kas tiek apkopoti. Tā arī tiek izmantota, lai mazinātu drošības vai veiktspējas problēmas ar līdzekli vai atjauninājumu. Turklāt ECS atbalsta konfigurācijas izmaiņas, kas saistītas ar diagnostikas datiem, lai nodrošinātu, ka tiek apkopoti atbilstošie notikumi. |
| [Licencēšana](#licensing-events)     | Licencēšana ir mākoņpakalpojums, kas atbalsta jūsu Office aktivizāciju jaunām instalācijām, kā arī uztur licenci jūsu ierīcēs pēc Office aktivizēšanas. Tā reģistrē katru jūsu ierīci un aktivizē Office, pārbauda jūsu Office abonementa statusu un pārvalda jūsu produktu atslēgas.    |
|[Microsoft AutoUpdate (MAU)](#microsoft-autoupdate-mau-events)|Microsoft AutoUpdate (MAU) ir tehnoloģija, kas tiek lietota, lai atjauninātu Microsoft programmas, piemēram, Office, kuras tiek veidotas MacOS operētājsistēmām. MAU noteiks programmu atjauninājumu (tostarp drošības atjauninājumu) nepieciešamību, veiks to lejupielādi un instalēšanu.|
|[OneNote sinhronizācija](#onenote-sync-events)|Programma OneNote darbam ar Mac atbalsta tikai tādas piezīmju grāmatiņas, kas tiek glabātas internetā — OneDrive krātuvē vai SharePoint Online. Programma OneNote darbam ar Mac pastāvīgi sinhronizē visas lietotāja piezīmes ar OneDrive krātuvi vai SharePoint Online. Tādējādi lietotāji var atvērt, skatīt un rediģēt savas piezīmju grāmatiņas visās savās ierīcēs, un viņu piezīmju grāmatiņas vienmēr ir atjauninātas.
 [Pakalpojumu konfigurācija](#services-configuration-events)  | Pakalpojumu konfigurācija nodrošina iespēju veikt atjauninājumus Office konfigurācijas iestatījumos, lai iespējotu vai atspējotu klientu līdzekļus. Tā tiek izsaukta ikreiz, kad Office lietojumprogramma tiek startēta, un nodrošina detalizētu informāciju par citām Office konfigurācijām un pakalpojumiem. Pakalpojumu konfigurācija kontrolē arī to, kuri pakalpojumi ir paredzēti kā būtiskie pakalpojumi.  |
| [Telemetrijas dati ](#telemetry-events)  | Telemetrijas datu pakalpojums tiek izmantots, lai apkopotu diagnostikas datus no Office lietojumprogrammām. Tas nodrošina Office ģenerēto diagnostikas datu apkopošanu — gan obligāto, gan papildu diagnostikas datu. Atbild par atsevišķu obligāto Office pakalpojumu datu apkopošanu.  |

## <a name="events-and-data-fields-for-essential-services-for-office"></a>Office būtisko pakalpojumu notikumu un datu lauki

Nākamajās sadaļās ir sniegta tālāk norādītā informācija.

- Notikumu saraksts katram būtiskajam pakalpojumam
- Katra notikuma apraksts
- Datu lauku saraksts katrā notikumā
- Katra datu lauka apraksts


## <a name="authentication-events"></a>Autentifikācijas notikumi

Šie diagnostikas datu notikumi tiek apkopoti, kad Office mēģina iegūt autentifikācijas marķieri vai nu nemanāmi vai izmantojot uzvedni.

### <a name="officeandroidmsaguesttoaad"></a>Office.Android.MSAGuestToAAD

Šis notikums palīdz izprast, cik daudziem lietotajiem tiek lūgts norādīt personiskā konta paroli, piekļūstot darba resursiem, jo viņu personiskais konts var būt derīgs darbam ar konta nomnieku.

Šie dati palīdz mums saprast, cik daudziem lietotajiem ir jāsaskaras ar atkārtotām pieteikšanās uzvednēm, lai prioritizētu nemanāmu AAD marķieru iegūšanu balstoties uz Microsoft konta SAML (drošības novērtējuma iezīmēšanas valoda) vērtējumu.

Tiek apkopoti šādi lauki:

- **Tag** — norāda, ka lietotājs, piekļūstot darba resursam, saņēma pierakstīšanās uzvedni personiskajam kontam.


### <a name="officeidentityfbapromptwin32"></a>Office.Identity.FbaPromptWin32

Tiek apkopots, kad Office rāda lietotājam uz veidlapām balstītas pierakstīšanās uzvedni.

Kopā ar kluso pilnvaru iegūšanu autentifikācijas uzvednes tiek izmantotas, lai noteiktu, vai lietotājs ir bojātā autentifikācijas stāvoklī, kas lietotājam izraisa būtisku bezsaistes klienta stāvokli, vai sliktākajā gadījumā bojāta autentifikācija var traucēt licences iegūšanu, kā arī izraisīt pilnībā nelietojamu klientu.

Uz veidlapām balstītās autentifikācijas (FBA) pierakstīšanās uzvednes tiek izmantotas dažiem lokāliem autentifikācijas scenārijiem, un parasti mēs vēlamies nodrošināt, ka tā nenotiek, jo visiem vajadzētu lietot moderno autentifikāciju ar FBA saistīto drošības ievainojamību dēļ.

Tiek apkopoti šādi lauki:

  - **AuthScheme** — izmantotā autentifikācijas shēma

  - **DocumentUrlHash** — šifrēta URL pieprasīšana

  - **EndTag** — tags, kur FBA veidlapa tiek aizpildīta

  - **Flags** — novecojis

  - **FlowTag** — tags, kur FBA veidlapa tiek startēta

  - **LastError** — atgrieztais kļūdas kods

  - **PromptEndTime** — laiks, kad uzvedne tika beigta

  - **PromptStartTime** — laiks, kad uzvedne tiek sākta

  - **Result** — vai autentifikācija izdevās

  - **SessionEndTime** — laiks, kad notikuma sesija beidzās

  - **Timeout** — laiks, kad uzvednei iestājās taimauts

### <a name="officeidentitysignoutevent"></a>Office.Identity.SignOutEvent

Tiek apkopots, kad lietotājs izrakstās no Office.

Zinot, ka lietotājs ir izrakstījies, kļūst iespējams klasificēt citus notikumus, piemēram, uzvednes, kā paredzēts, lai šos notikumus varētu pareizi skaitļot uzticamības/gatavības nosūtīšanai metrikā, kā arī izvairīties no brīdinājumiem vai būvējumu atrites kļūdainā iekārtā, kur lietotājam rodas neparedzētas pierakstīšanās uzvednes.

Tiek apkopoti tālāk norādītie lauki.

  - **FlowEndTime** — laiks, kad izrakstīšanās darbība beidzās

  - **FlowStartTime** — laiks, kad izrakstīšanās darbība sākās

  - **IdentityErrorState** — jebkāds identitātes kļūdas stāvoklis izrakstīšanās laikā

  - **IdentityHashedUniqueId** — šifrētais identitātes ID, kam tiek veikta izrakstīšanās

  - **IdentityProviderType** — tās identitātes nodrošinātājs, kurai tiek veikta izrakstīšanās

  - **IdentityUniqueID** — identitātes ID, kam tiek veikta izrakstīšanās

  - **SessionEndTime** — laiks, kad notikuma sesija beidzās

  - **SignOutUserAction** — norāda, ka lietotājs sāk izrakstīšanās darbību

### <a name="officeidentitysspipromptwin32"></a>Office.Identity.SspiPromptWin32

Tiek apkopots, kad Office rāda lietotājam Windows SSPI pierakstīšanās uzvedni. Kopā ar kluso pilnvaru iegūšanu autentifikācijas uzvednes nosaka, vai lietotājs ir bojātā autentifikācijas stāvoklī, kas izraisa bezsaistes klienta stāvokli. Bojāta autentifikācija var traucēt licences iegūšanu, kā arī izraisīt pilnībā nelietojamu klientu.

Windows SSPI uzvednes tiek izmantotas autentifikācijai ar Exchange (pasta sinhronizēšanai), ja lietotāja Exchange resurss nav iestatīts daudzfaktoru autentifikācijai.

Šie notikumi kopā ar Office.MATS nosaukumvietas notikumiem tiek izmantoti tālāk norādītajiem mērķiem.

1.\) Identificēt, vai klienti var sekmīgi iegūt autentifikācijas marķieri vai ir pārgājuši bojātā autentifikācijas stāvoklī.

2.\) Novērtēt, vai izmaiņas, kas radušās klientā vai pakalpojumos, ir izraisījušas kritisku regresiju lietotāja autentifikācijas pieredzē un uzticamībā

3.\) Ja rodas kļūme, šie signāli raida svarīgus kļūmju kodus no atbildīgā komponenta (Office klienta kods, autentifikācijas bibliotēkas vai iestāžu pakalpojumi), ko var izmantot klasificēšanai, diagnostikai un mazināšanai

4.\) Šie signāli nodrošina dažādus nosūtīšanas gatavības un darbspējas pārraugus, kas aktivizē brīdinājumus, lai mūsu inženieri varētu ātri iesaistīties un samazināt laiku kritisko lietotāju bloķēšanas kļūmju mazināšanai.

Tiek apkopoti tālāk norādītie lauki.

  - **AllowSavedCreds** — vai jaunie akreditācijas dati ir pastāvīgi

  - **AuthScheme** — izmantotā autentifikācijas shēma

  - **CredsSaved** — vai jaunie akreditācijas dati ir saglabāti

  - **DocumentUrlHash** — šifrētā URL pieprasīšana

  - **EndTag** — tags, kur uzvedne beidzās

  - **NewIdentity**\_ErrorState — vai jaunā identitāte ir derīga

  - **NewIdentity\_HashedUniqueId** — šifrētais jaunais identitātes ID pēc uzvednes pabeigšanas

  - **NewIdentity\_ProviderType** — jaunais identitātes nodrošinātājs pēc uzvednes pabeigšanas

  - **NewIdentity\_UniqueID** — jaunais identitātes ID pēc uzvednes pabeigšanas

  - **OutStatus** — vai uzvednes izvade ir derīga

  - **PromptEndTime** — laiks, kad uzvedne tika beigta

  - **PromptFailedTag** — tags, kas norāda SSPI uzvednes kļūmi

  - **PromptFlow** — tags, kas izsauca SSPI uzvedni

  - **PromptStartTime** — laiks, kad uzvedne tiek sākta

  - **Proxy** — vai tiek izmantots starpniekserveris

  - **ServerHash** — šifrētā servera adrese

  - **SessionEndTime** — laiks, kad notikuma sesija beidzās

  - **Timeout** — laiks, kad uzvednei iestājas taimauts

  - **UiMessage** — UI ziņojums uzvednē

  - **UserNameHash** — šifrētais lietotājvārds

### <a name="officeidentitywin32prompt"></a>Office.Identity.Win32Prompt

Tiek apkopots, kad Office rāda lietotājam daudzfaktoru autentifikācijas pierakstīšanās uzvedni. Kopā ar kluso pilnvaru iegūšanu autentifikācijas uzvednes nosaka, vai lietotājs ir bojātā autentifikācijas stāvoklī, kas izraisa bezsaistes klienta stāvokli. Bojāta autentifikācija var traucēt licences iegūšanu, kā arī izraisīt pilnībā nelietojamu klientu.

Šie notikumi kopā ar Office.MATS nosaukumvietas notikumiem tiek izmantoti tālāk norādītajiem mērķiem.

1.\) Identificēt, vai klienti var sekmīgi iegūt autentifikācijas marķieri vai ir pārgājuši bojātā autentifikācijas stāvoklī.

2.\) Novērtēt, vai izmaiņas, kas radušās klientā vai pakalpojumos, ir izraisījušas kritisku regresiju lietotāja autentifikācijas pieredzē un uzticamībā

3.\) Ja rodas kļūme, šie signāli raida svarīgus kļūmju kodus no atbildīgā komponenta (Office klienta kods, autentifikācijas bibliotēkas vai iestāžu pakalpojumi), ko var izmantot klasificēšanai, diagnostikai un mazināšanai

4.\) Šie signāli nodrošina dažādus nosūtīšanas gatavības un darbspējas pārraugus, kas aktivizē brīdinājumus, lai mūsu inženieri varētu ātri iesaistīties un samazināt laiku kritisko lietotāju bloķēšanas kļūmju mazināšanai.

Tiek apkopoti tālāk norādītie lauki.

  - **AdalWAMUsed** — tags, kas norāda rezultātu, ja tiek izmantots ADAL-atop-WAM

  - **CallTag** — tags, kas norāda pierakstīšanās UI izsaucēju

  - **Context** — uzvednes pierakstīšanās konteksts

  - **EndTagIdentityProviderRequested** — tags, kur tiek pieprasīts identitātes nodrošinātājs

  - **HrdShownTag** — tags, kur tiek rādīts HRD pierakstīšanās dialogs

  - **IdentityProviderResulted** — identitātes nodrošinātāja tips, ko tas pieprasa

  - **IdPFlowTag** — tags, kas norāda identitātes pieprasījuma rezultātu

  - **LastLoginDelta** — laika delta no pēdējās sekmīgās pieteikšanās

  - **NewIdentity\_ErrorState** — vai identitāte ir derīga pēc uzvednes

  - **NewIdentity\_ProviderType** — jaunā identitātes nodrošinātāja tips pēc uzvednes

  - **NewIdentity\_UniqueID** — jaunais identitātes ID, kas tiek atgriezts pēc uzvednes

  - **PromptCorrelation** — uzvednes korelācijas ID diagnostikas mērķim

  - **PromptEndTime** — laiks, kad uzvedne tika beigta

  - **PromptStartTime** — laiks, kad uzvedne tiek sākta

  - **SessionEndTime** — laiks, kad notikuma sesija beidzās

  - **ShowUIResult** — rezultāta kods, kas atgriezts no uzvednes UI

  - **StartTag** — tags, kur Win32 uzvedne tika sākta

  - **Timeout** — laiks, kad uzvednei iestājas taimauts

  - **WasIdentitySignedOut** — vai lietotājs ir izrakstījies

### <a name="officematsactionofficewin32-officematsactionofficewinrt"></a>Office.MATS.actionofficewin32, Office.MATS.actionofficewinrt

Tālāk norādītais apraksts attiecas gan uz Win32, gan WinRT notikumiem (nosaukums ir atkarīgs no platformas).

Microsoft autentifikācijas telemetrijas sistēma (MATS) tiek apkopota, kad Office mēģina iegūt autentifikācijas marķieri vai nu nemanāmi vai izmantojot uzvedni. Ja iegūšanas mēģinājumi neizdodas, tiek iekļauta kļūdas informācija. Šie notikumi mūsu lietotājiem sniedz iespēju izvairīties no pāriešanas bojātos autentifikācijas stāvokļos.

1.\) Identificēšana, vai klienti var sekmīgi iegūt autentifikācijas marķieri vai ir pārgājuši bojātā autentifikācijas stāvoklī.

2.\) Novērtēt, kad izmaiņas rodas klientā vai pakalpojumos, vai tās izraisa kritisku regresiju lietotāja autentifikācijas pieredzē un uzticamībā

3.\) Ja rodas kļūme, šie signāli raida svarīgus kļūmju kodus no atbildīgā komponenta (Office klienta kods, autentifikācijas bibliotēkas vai iestāžu pakalpojumi), ko var izmantot klasificēšanai, diagnostikai un mazināšanai

4.\) Šie signāli nodrošina dažādus nosūtīšanas gatavības un darbspējas pārraugus, kas aktivizē brīdinājumus, lai mūsu inženieri varētu ātri iesaistīties un samazināt laiku kritisko kļūmju mazināšanai.

Tiek apkopoti tālāk norādītie lauki.

  - **Actiontype** — kura autentifikācijas bibliotēka tiek izmantota

  - **Appaudience** — vai lietojumprogrammas būvējums ir paredzēts iekšējai vai ārējai lietošanai

  - **Appforcedprompt** — vai lietojumprogramma ignorēja kešatmiņu un nodrošināja uzvednes rādīšanu piespiedu kārtā

  - **Appname** — tās lietojumprogrammas nosaukums, kas veic autentifikāciju

  - **Appver** — tās lietojumprogrammas versija, kas veic autentifikāciju

  - **Askedforcreds** — vai lietojumprogramma pieprasīja lietotājam ievadīt akreditācijas datus šai darbībai

  - **Authoutcome** — vai autentifikācijas mēģinājums izdevās, neizdevās vai tika atcelts

  - **Blockingprompt** — vai lietojumprogramma parādīja uzvedni, kur bija nepieciešama lietotāja mijiedarbība

  - **Correlationid** — GUID, kas tiek izmantots savienošanai ar pakalpojumu datiem

  - **Count** — notikumu skaits apkopojuma gadījumos

  - **Data\_accounttype** — patērētāja vai organizācijas konts

  - **Devicenetworkstate** — vai lietotājs bija tiešsaistē

  - **Deviceprofiletelemetryid** — anonīmais ierīces ID, kas tika izmantots, lai mērītu ierīces pieredzi

  - **Duration** — cik ilga bija autentifikācija

  - **Duration_Max** — ja šis signāls ir apkopots, tad tas ir jebkura apkopotā notikuma maksimālais ilgums.

  - **Duration_Min** — ja šis signāls ir apkopots, tad tas ir jebkura apkopotā notikuma minimālais ilgums.

  - **Duration_Sum** — ja šis signāls tiek apkopots, tad tas ir visu apkopoto notikumu ilgumu summa.

  - **Endtime** — kad autentifikācijas notikums beidzās

  - **Error** — kļūdas kods, ja autentifikācija neizdevās

  - **Errordescription** — īss kļūdas apraksts

  - **Errorsource** — vai kļūda radās pakalpojumā, autentifikācijas bibliotēkā vai lietojumprogrammā

  - **Identityservice** — vai tika izsaukts Microsoft pakalpojuma konts (MSA) vai Azure Active Directory (AAD) pakalpojums

  - **Interactiveauthcontainer** — kāda veida uzvedne tika rādīta

  - **Issilent** — vai uzvedne tika rādīta

  - **Microsoft**\_**ADAL**\_**adal**\_**version** — Azure Active Directory Authentication Library (ADAL) versija

  - **Microsoft\_ADAL\_api\_error\_code** — kļūdas kods, ko raidīja autentifikācijas bibliotēka šim autentifikācijas mēģinājumam

  - **Microsoft\_ADAL\_api\_id** — šim autentifikācijas mēģinājumam izsauktais API

  - **Microsoft\_ADAL\_authority** — Azure Active Directory tās iestādes URL, kas atbildīga par lietotāja autentifikāciju

  - **Microsoft\_ADAL\_authority\_type** — patērētāja/Microsoft pakalpojuma līgums (MSA) attiecībā pret organizāciju/Azure Active Directory (AAD); pašlaik vienmēr AAD

  - **Microsoft\_ADAL\_authority\_validation\_status** — norāda, vai autentifikācija tika pabeigta pakalpojuma pusē

  - **Microsoft\_ADAL\_broker\_app** — norāda, vai ADAL autentifikācijai izmantoja starpnieku

  - **Microsoft\_ADAL\_broker\_app\_used** — norāda starpnieka nosaukumu (piemēram, Windows kontu pārvaldība)

  - **Microsoft\_ADAL\_broker\_version** — norāda starpnieka versiju, ja tas tiek izmantots

  - **Microsoft\_ADAL\_cache\_event\_count** — kešatmiņas notikumu skaits, ko ADAL veica, izgūstot marķieri

  - **Microsoft\_ADAL\_cache\_event\_count\_max** — ja šis signāls tiek apkopots, maksimālais jebkura apkopotā notikuma kešatmiņas notikumu skaits.

  - **Microsoft\_ADAL\_cache\_event\_count\_min** — ja šis signāls tiek apkopots, minimālais jebkura apkopotā notikuma kešatmiņas notikumu skaits.

  - **Microsoft\_ADAL\_cache\_event\_count\_sum** — ja šis signāls tiek apkopots, visu apkopoto notikumu kešatmiņas notikumu summa.

  - **Microsoft\_ADAL\_cache\_read\_count** — cik reižu API lasīja no diska kešatmiņas. Spēkā, ja ir bijusi vismaz viena lasīšana.

  - **Microsoft\_ADAL\_cache\_read\_error\_count** — cik reižu diska kešatmiņas lasīšana neizdevās. Ir spēkā, ja ir bijusi vismaz viena kļūme.

  - **Microsoft\_ADAL\_cache\_read\_last\_error** — ADAL kļūdas kods. Spēkā, ja ir bijusi vismaz viena lasīšanas kļūme.

  - **Microsoft\_ADAL\_cache\_read\_last\_system\_error** — sistēmas kļūdas kods. Ir spēkā, ja ir bijusi vismaz viena lasīšanas kļūme.

  - **Microsoft\_ADAL\_cache\_write\_count** — cik reižu API rakstīja diska kešatmiņā. Spēkā, ja ir bijusi vismaz viena rakstīšana.

  - **Microsoft\_ADAL\_cache\_write\_error\_count** — cik reižu diska kešatmiņas rakstīšana neizdevās. Spēkā, ja ir bijusi vismaz viena kļūme.

  - **Microsoft\_ADAL\_cache\_write\_last\_error** — ADAL kļūdas kods. Spēkā, ja ir bijusi vismaz viena rakstīšanas kļūme.

  - **Microsoft\_ADAL\_cache\_write\_last\_system\_error** — sistēmas kļūdas kods. Spēkā, ja ir bijusi vismaz viena rakstīšanas kļūme.

  - **Microsoft\_ADAL\_client\_id** — jauktais AAD lietojumprogrammas ID

  - **Microsoft\_ADAL\_extended\_expires\_on\_setting** — patiess/aplams norāda, vai marķierim ir pagarināts kalpošanas laiks.

  - **Microsoft\_ADAL\_http\_event\_coun** t — HTTP izsaukumu skaits, ko veica ADAL.

  - **Microsoft\_ADAL\_http\_event\_count\_max** — ja šis signāls ir apkopots, maksimālais HTTP izsaukumu skaits, ko ADAL veic jebkuram apkopotajam notikumam.

  - **Microsoft\_ADAL\_http\_event\_count\_min** — ja šis signāls ir apkopots, minimālais HTTP izsaukumu skaits, ko ADAL veic jebkuram apkopotajam notikumam.

  - **Microsoft\_ADAL\_http\_event\_count\_sum** — ja šis signāls ir apkopots, HTTP izsaukumu summa, ko ADAL veic visiem apkopotajiem notikumiem.

  - **Microsoft\_ADAL\_is\_silent\_ui** — patiess/aplams norāda, vai UI ADAL rādīja UI (uzvedni).

  - **Microsoft\_ADAL\_is\_successful** — patiess/aplams norāda, vai ADAL API izdevās.

  - **Microsoft\_ADAL\_logging\_pii\_enabled** — patiess/aplams norāda, vai ADAL pilnās reģistrēšanas režīms ir iespējots. Šie dati tiek reģistrēti tikai lokāli, netiek raidīti telemetrijā.

  - **Microsoft\_ADAL\_oauth\_error\_code** — OAuth protokola kļūdas kods, ko atgrieza pakalpojums.

  - **Microsoft\_ADAL\_prompt\_behavior** — pieteikšanās vai nekāds HTTP parametrs tiek nodots pakalpojumam, lai norādītu, vai var rādīt lietotāja interfeisu.

  - **Microsoft\_ADAL\_request\_id** — transakcijas GUID pieprasījumam, ko ADAL raida pakalpojumam.

  - **Microsoft\_ADAL\_response\_code** — HTTP atbildes kods no pakalpojuma.

  - **Microsoft\_ADAL\_response\_time** — cik ilgi pakalpojums atgrieza ADAL.

  - **Microsoft\_ADAL\_response\_time\_max** — ja signāls ir apkopots, maksimālais laiks, cik ilgi ADAL atgriezās no API kādā no apkopotajiem notikumiem.

  - **Microsoft\_ADAL\_response\_time\_min** — ja signāls ir apkopots, minimālais laiks, cik ilgi pakalpojums atbildēja ADAL kādā no apkopotajiem notikumiem.

  - **Microsoft\_ADAL\_response\_time\_sum** — ja signāls ir apkopots, laika summa, cik ilgi ADAL atgriezās no API visos apkopotajos notikumos.

  - **Microsoft\_ADAL\_rt\_age** — atsvaidzināšanas marķiera vecums

  - **Microsoft\_ADAL\_server\_error\_code** — servera atgrieztais kļūdas kods

  - **Microsoft\_ADAL\_server\_sub\_error\_code** — servera atgrieztais pakārtotais kļūdas kods, lai norādītu, kāpēc pieprasījums neizdevās.

  - **Microsoft\_ADAL\_spe\_ring** — patiess/aplams norāda, vai lietotājs izmantoja Secure Production Enterprise iekšējo apli (tikai Microsoft darbinieki).

  - **Microsoft\_ADAL\_start\_time** — laiks, kad ADAL API izsaukums tika veikts

  - **Microsoft\_ADAL\_stop\_time** — laiks, kad ADAL API izsaukums tika atgriezts

  - **Microsoft\_ADAL\_telemetry\_pii\_enabled** — patiess/aplams norāda, vai ADAL pilnās telemetrijas režīms ir iespējots. Nosaukums ir misnomer, jo PII/EUII netiek raidīts.

  - **Microsoft\_ADAL\_tenant\_id** — GUID, kas identificē nomnieku, kam autentificētais lietotājs pieder.

  - **Microsoft\_ADAL\_token\_acquisition\_from\_context** — apraksta ADAL uzvedību, ņemot vērā marķierus autentifikācijas kontekstā.

  - **Microsoft\_ADAL\_token\_type** — atsvaidzināšanas marķieris (RT) vai vairāku resursu atsvaidzināšanas marķieris (MRRT).

  - **Microsoft\_ADAL\_ui\_event\_count** — uzvedņu skaits, kas tiek rādītas lietotājam. Var būt klusas.

  - **Microsoft\_ADAL\_user\_cancel** — patiess/aplams, ja lietotāja interfeisa logs tika atcelts.

  - **Microsoft_ADAL_was_request_throttled** — patiess/aplams, kas norāda, vai ADAL ierobežoja šo notikumu pārāk daudzu pieprasījumu dēļ.
 
  - **Microsoft\_ADAL\_x\_ms\_request\_id** — papildu pieprasījuma ID, ko HTTP galvenē pakalpojumam nodrošina ADAL.

  - **Platform** — Win32/WinRT/Android/iOS/Mac

  - **Promptreasoncorrelationid** — uzvednes gadījumā tas ir cita notikuma korelācijas ID, kas izskaidro, kāpēc lietotājam, iespējams, ir redzama autentifikācijas uzvedne.

  - **Resource** — resurss, kuram lietotājs pieprasa marķieri, piemēram, Exchange vai SharePoint.

  - **Scenarioid** — GUID. Vairāki notikumi var piederēt vienam scenārijam, piemēram, scenārijs var pievienot jaunu kontu, bet pastāv vairākas uzvednes, kas rodas kā daļa no šī scenārija. Šis ID nodrošina korelācijas iespējamību.

  - **Scenarioname** — scenārija nosaukums, kuram pieder šis autentifikācijas notikums.

  - **Sessionid** — GUID, kas identificē sāknēšanas sesiju

  - **Skdver** — MATS klienta SDK versija, kas tiek izmantota, lai radītu šos datus

  - **Starttime** — laiks, kad Start\*Action MATS API tika izsaukts

  - **Tenantid** — GUID, kas identificē nomnieku, kam autentificētais lietotājs pieder (ar ADAL nesaistītos gadījumos).

  - **Uploadid** — unikālais GUID šim notikumam, tiek izmantots dublikātu likvidēšanai

  - **Wamapi** — norāda, kurš WAM API ir izsaukts

  - **Wamtelemetrybatch** — pašlaik netiek izmantots. Nākotnē sniedz WAM komponentam iespēju izsūtīt papildinformāciju par autentifikācijas notikumu.


### <a name="officematsoneauthactionmicrosoftofficewin32"></a>Office.MATS.OneAuth.ActionMicrosoftOfficeWin32

Microsoft autentifikācijas telemetrijas sistēma (MATS) tiek apkopota, kad Office mēģina iegūt autentifikācijas marķieri vai nu nemanāmi vai izmantojot uzvedni. Ja iegūšanas mēģinājumi neizdodas, tiek iekļauta kļūdas informācija. Šie notikumi mūsu lietotājiem sniedz iespēju izvairīties no pāriešanas bojātos autentifikācijas stāvokļos.

1) Identificēšana, vai klienti var sekmīgi iegūt autentifikācijas marķieri no pakalpojuma vai ir pārgājuši bojātā autentifikācijas stāvoklī.

2) Novērtēt, kad izmaiņas rodas klientā vai pakalpojumos, vai tās izraisa kritisku regresiju lietotāja autentifikācijas pieredzē un uzticamībā

3) Ja rodas kļūme, šie signāli raida svarīgus kļūmju kodus no atbildīgā komponenta (Office klienta kods, autentifikācijas bibliotēkas vai iestāžu pakalpojumi), ko var izmantot klasificēšanai, diagnostikai un mazināšanai

4) Šie signāli nodrošina dažādus nosūtīšanas gatavības un darbspējas pārraugus, kas aktivizē brīdinājumus, lai mūsu inženieri varētu ātri iesaistīties un samazināt laiku kritisko kļūmju mazināšanai.

Tiek apkopoti šādi lauki:

- **Accounttype** — šim autentifikācijas notikumam izmantotais konta tips, piemēram, patērētājs vai organizācijas konts.

- **Actionname** — draudzīgs nosaukums šim notikumam, ja tāds tika norādīts.

- **Actiontype** — norāda, kāda veida autentifikācijas bibliotēku izmantojat.

- **Appaudience** — vai lietojumprogrammas būvējums ir paredzēts iekšējai vai ārējai lietošanai

- **Appforcedprompt** — vai lietojumprogramma ignorēja kešatmiņu un nodrošināja uzvednes rādīšanu piespiedu kārtā

- **Appname** — tās lietojumprogrammas nosaukums, kas veic autentifikāciju

- **Appver** — tās lietojumprogrammas versija, kas veic autentifikāciju

- **Askedforcreds** — vai lietojumprogramma pieprasīja lietotājam ievadīt akreditācijas datus šai darbībai

- **Authoutcome** — vai autentifikācijas mēģinājums izdevās, neizdevās vai tika atcelts

- **Blockingprompt** — vai lietojumprogramma parādīja uzvedni, kur bija nepieciešama lietotāja mijiedarbība

- **Correlationid** — identifikators, ko izmanto, lai saistītu informāciju par šo atsevišķo notikumu ar pakalpojumu datiem

- **Count** — kopējais apkopoto darbību skaits, kas ziņots šajā vienā datu notikumā.

- **Devicenetworkstate** — vai ierīce ir savienota ar internetu.

- **Deviceprofiletelemetryid** — anonīms ierīces ID, ko izmanto, lai mērītu visas ierīces autentifikācijas pieredzi un uzticamību.

- **Duration** — cik ilga bija autentifikācija

- **duration_max** — maksimālais jebkura no apkopotajiem notikumiem ilgums

- **duration_min** — minimālais jebkura no apkopotajiem notikumiem ilgums

- **duration_sum** — visu apkopoto notikumu ilguma summa

- **endtime** — kad autentifikācijas notikums beidzās

- **error** — kļūdas kods, ja autentifikācija neizdevās

- **errordescription** — īss kļūdas apraksts

- **errorsource** — vai kļūda radās pakalpojumā, autentifikācijas bibliotēkā vai lietojumprogrammā

- **eventtype** — vai šis notikums ziņo par autentifikācijas datu punktu vai datu kvalitātes kļūdas notikumu. Izmanto datu kvalitātes mērīšanai.

- **from_cache** — Būla vērtība, kas norāda, vai ieraksts ir no WAM kodola kešatmiņas vai spraudņa

- **hasadaltelemetry** — norāda, vai Azure Active Directory Authentication Library (ADAL) nodrošināja šim notikumam telemetriju.

- **Identityservice** — vai tika izsaukts Microsoft pakalpojuma konts (MSA) vai Azure Active Directory (AAD) pakalpojums

- **Interactiveauthcontainer** — kāda veida uzvedne tika rādīta

- **Issilent** — vai tika parādīta uzvedne vai arī šis bija kluss (fona) autentifikācijas notikums.

- **Microsoft_ADAL_adal_version** — Azure Active Directory Authentication Library (ADAL) versija

- **Microsoft_ADAL_api_error_code** — kļūdas kods, ko raidīja autentifikācijas bibliotēka šim autentifikācijas mēģinājumam

- **Microsoft_ADAL_api_id** — šim autentifikācijas mēģinājumam izsauktais API

- **Microsoft_ADAL_application_name** — lietojumprogrammas/procesa nosaukums, izmantojot ADAL.

- **Microsoft_ADAL_application_version** — lietojumprogrammas versija, izmantojot ADAL.

- **Microsoft_ADAL_authority** — Azure Active Directory tās iestādes URL, kas atbildīga par lietotāja autentifikāciju

- **Microsoft_ADAL_authority_type** — patērētāja/Microsoft pakalpojuma līgums (MSA) attiecībā pret organizāciju/Azure Active Directory (AAD); pašlaik vienmēr AAD

- **Microsoft_ADAL_authority_validation_status** — norāda, vai autentifikācija tika pabeigta pakalpojuma pusē

- **Microsoft_ADAL_broker_app** — norāda, vai ADAL autentifikācijai izmantoja starpnieku

- **Microsoft_ADAL_broker_app_used** — norāda starpnieka nosaukumu (piemēram, Windows kontu pārvaldība)

- **Microsoft_ADAL_broker_version** — norāda starpnieka versiju, ja tas tiek izmantots

- **Microsoft_ADAL_cache_event_count** — kešatmiņas notikumu skaits, ko ADAL veica, izgūstot marķieri

- **Microsoft_ADAL_cache_event_count_max** — ja šis signāls tiek apkopots, maksimālais jebkura apkopotā notikuma kešatmiņas notikumu skaits.

- **Microsoft_ADAL_cache_event_count_min** — ja šis signāls tiek apkopots, minimālais jebkura apkopotā notikuma kešatmiņas notikumu skaits.

- **Microsoft_ADAL_cache_event_count_sum** — ja šis signāls tiek apkopots, visu apkopoto notikumu kešatmiņas notikumu summa

- **Microsoft_ADAL_cache_read_count** — cik reižu API lasīja no diska kešatmiņas. Spēkā, ja ir bijusi vismaz viena lasīšana

- **Microsoft_ADAL_cache_read_error_count** — to, cik reizes neizdevās lasīt kešatmiņā. Ir spēkā, ja ir bijusi vismaz viena kļūme

- **Microsoft_ADAL_cache_read_last_error** — ADAL kļūdas kods. Spēkā, ja ir bijusi vismaz viena lasīšanas kļūme

- **Microsoft_ADAL_cache_read_last_system_error** — sistēmas kļūdas kods.  Ir spēkā, ja ir bijusi vismaz viena lasīšanas kļūme

- **Microsoft_ADAL_cache_write_count** — cik reizes API ir ierakstīts diska kešatmiņā. Spēkā, ja ir bijusi vismaz viena rakstīšana

- **Microsoft_ADAL_cache_write_error_count** — cik reizes diska kešatmiņas rakstīšana neizdevās. Spēkā, ja ir bijusi vismaz viena kļūme

- **Microsoft_ADAL_cache_write_last_error** — ADAL kļūdas kods. Spēkā, ja ir bijusi vismaz viena rakstīšanas kļūme

- **Microsoft_ADAL_cache_write_last_system_error** — sistēmas kļūdas kods. Spēkā, ja ir bijusi vismaz viena rakstīšanas kļūme

- **Microsoft_ADAL_client_id** — jauktais programmas Azure Active Directory ID

- **Microsoft_ADAL_device_id** — ADAL ģenerēts lokālās ierīces ID.

- **Microsoft_ADAL_error_domain** — domēns/komponents, kas ģenerēja kļūdas kodu.

- **Microsoft_ADAL_error_protocol_code** — OAuth protokola kļūdas kods, ko atgrieza pakalpojums, ADAL ierakstīts.

- **Microsoft_ADAL_extended_expires_on_setting** — patiess/aplams norāda, vai marķierim ir pagarināts kalpošanas laiks

- **Microsoft_ADAL_http_event_count** — HTTP pieprasījumus, ko ģenerē ADAL.

- **Microsoft_ADAL_idp** — identitātes nodrošinātājs (IDP), ko izmanto ADAL.

- **Microsoft_ADAL_network_event_count** — ADAL tīkla zvanu skaits

- **Microsoft_ADAL_http_event_count_max** — ja šis signāls ir apkopots, maksimālais http zvanu skaits, ko veic ADAL

- **Microsoft_ADAL_http_event_count_min** — ja šis signāls ir apkopots, minimālais http zvanu skaits, ko veic ADAL

- **Microsoft_ADAL_http_event_count_sum** — ja šis signāls ir apkopots, ADAL veikto http zvanu summa

- **Microsoft_ADAL_network_event_count_max** — ja šis signāls tiek apkopots, maksimālais tīkla zvanu skaits, ko veic ADAL par jebkuru apkopotu notikumu

- **Microsoft_ADAL_network_event_count_min** — ja šis signāls tiek apkopots, minimālais tīkla zvanu skaits, ko veic ADAL par jebkuru apkopotu notikumu

- **Microsoft_ADAL_network_event_count_sum** — ja šis signāls tiek apkopots, visu apvienoto notikumu ADAL veikto tīkla zvanu summa

- **Microsoft_ADAL_is_silent_ui** — patiess/aplams norāda, vai UI ADAL rādīja UI (uzvedni)

- **Microsoft_ADAL_is_successfull** — patiess/aplams norāda, vai ADAL API izdevās (macOS)

- **Microsoft_ADAL_is_successfull** — patiess/aplams norāda, vai ADAL API izdevās

- **Microsoft_ADAL_logging_pii_enabled** — patiess/aplams norāda, vai ADAL pilnās reģistrēšanas režīms ir iespējots. Šie dati tiek reģistrēti tikai lokāli, netiek raidīti telemetrijā

- **Microsoft_ADAL_ntlm** — patiess/aplams, norādot, vai ADAL izmanto pamata autentifikāciju (NTLM).

- **Microsoft_ADAL_oauth_error_code** — OAuth protokola kļūdas kods, ko atgrieza pakalpojums

- **Microsoft_ADAL_prompt_behavior** — pieteikšanās vai neviens tīkla parametrs nav nodots pakalpojumam, lai norādītu, vai var parādīt lietotāja interfeisu

- **Microsoft_ADAL_request_id** — transakcijas GUID pieprasījumam, ko ADAL raida pakalpojumam

- **Microsoft_ADAL_response_code** — tīkla atbildes kods no pakalpojuma

- **Microsoft_ADAL_response_time** — cik ilgi pakalpojums atgrieza ADAL

- **Microsoft_ADAL_response_time_max** — ja signāls ir apkopots, maksimālais laiks, cik ilgi ADAL atgriezās no API kādā no apkopotajiem notikumiem

- **Microsoft_ADAL_response_time_min** — ja signāls ir apkopots, minimālais laiks, cik ilgi pakalpojums atbildēja ADAL kādā no apkopotajiem notikumiem

- **Microsoft_ADAL_response_time_sum** — ja signāls ir apkopots, laika summa, cik ilgi ADAL atgriezās no API visos apkopotajos notikumos

- **Microsoft_ADAL_rt_age** — atsvaidzināšanas marķiera vecums

- **Microsoft_ADAL_server_error_code** — servera atgrieztais kļūdas kods

- **Microsoft_ADAL_server_sub_error_code** — servera atgrieztais pakārtotais kļūdas kods, lai norādītu, kāpēc pieprasījums neizdevās

- **Microsoft_ADAL_spe_info** — patiess/aplams norāda, vai lietotājs izmantoja Secure Production Enterprise iekšējo apli (tikai Microsoft darbinieki)

- **Microsoft_ADAL_spe_ring** — patiess/aplams norāda, vai lietotājs izmantoja Secure Production Enterprise iekšējo apli (tikai Microsoft darbinieki)

- **Microsoft_ADAL_start_time** — laiks, kad ADAL API izsaukums tika veikts

- **Microsoft_ADAL_status** — veiksmes/kļūmju statuss kopējā ADAL izsaukšanā

- **Microsoft_ADAL_stop_time** — laiks, kad tiek atgriezts ADAL API izsaukums

- **Microsoft_ADAL_telemetry_pii_enabled** — patiess/aplams norāda, vai ADAL pilnās telemetrijas režīms ir iespējots. Nosaukums ir misnomer, jo PII/EUII netiek raidīts

- **Microsoft_ADAL_tenant_id** — GUID, kas identificē nomnieku, kam autentificētais lietotājs pieder

- **Microsoft_ADAL_token_acquisition_from_context** — apraksta ADAL uzvedību, ņemot vērā marķierus autentifikācijas kontekstā

- **Microsoft_ADAL_token_frt_status** — atsvaidzināšanas marķiera statuss: vai tas ir izmēģināts, nav nepieciešams, nav atrasts vai izdzēsts.

- **Microsoft_ADAL_token_mrrt_status** — vairāku resursu atsvaidzināšanas marķiera (MRRT) statuss: vai tas ir izmēģināts, nav nepieciešams, nav atrasts vai izdzēsts.

- **Microsoft_ADAL_token_rt_status** — atsvaidzināšanas marķiera statuss: vai tas ir izmēģināts, nav nepieciešams, nav atrasts vai izdzēsts.

- **Microsoft_ADAL_token_type** — atsvaidzināšanas marķieris (RT) vai vairāku resursu atsvaidzināšanas marķieris (MRRT).

- **Microsoft_ADAL_ui_event_count** — uzvedņu skaits, kas tiek rādītas lietotājam. Var būt klusas

- **Microsoft_ADAL_user_cancel** — patiess/aplams, ja lietotāja interfeisa logs tika atcelts

- **Microsoft_ADAL_x_ms_request_id** — papildu pieprasījuma ID, kas tiek nodrošināts tīkla galvenē pakalpojumā, izmantojot ADAL

- **Microsoft_ADAL_x_client_cpu** — informācija, kas attiecas uz ierīces centrālā procesora arhitektūru

- **Microsoft_ADAL_x_client_os** — ierīces operētājsistēmas versija.

- **Microsoft_ADAL_x_client_sku** — ierīces operētājsistēmas SKU nosaukums.

- **Microsoft_ADAL_x_client_ver** — ADAL bibliotēkas versija.

- **MSAL_all_error_tags** — visas kļūdu atzīmes autentifikācijas plūsmā radās Microsoft autentifikācijas bibliotēka (MSAL).

- **MSAL_api_error_code** — ja MSAL sastopas ar kļūdu, kas rodas no operētājsistēmas, platformas kļūdu kodi tiek saglabāti šeit.

- **MSAL_api_error_context** — virkne, kas satur cilvēkiem lasāmu papildu informāciju par pēdējo MSAL radušos kļūdu. 

- **MSAL_api_error_tag** — unikālā virkne, kas paredzēta vietai kodā, kur radās šāda kļūda.

- **MSAL_api_name** — MSAL augšējā līmeņa API nosaukums, kas tiek izsaukts, lai sāktu šo autentifikācijas plūsmu.

- **MSAL_api_status_code** — statusa kods MSAL, kas tiek atgriezts šīs autentificēšanas plūsmas rezultātam.

- **MSAL_auth_flow** — darbības, ko MSAL mēģinājums šīs autentifikācijas plūsmas laikā (AT, PRT, LRT, FRT, māksla, IRT). Atdalīts ar caurules simbolu "|", lai atvieglotu parsēšanu.

- **MSAL_auth_flow_last_error** — kļūdas kods, ko saņēmāt no servera otrajā AuthFlow. (Piem.: ja AuthFlow = "PRT|LRT", PRT kļūda būs AuthFlowLastError).

- **MSAL_authority_type** — vai šis pieprasījums bija šādam lietotājam: AAD, federatīvam vai MSA.

- **MSAL_broker_app_used** — vai šajā starpniecības lietojumprogrammā tika izmantota autentifikācijas plūsma.

- **MSAL_client_id** — klienta ID izsaukšanas lietojumprogrammai

- **MSAL_correlation_id** — šī notikuma unikālais GUID, ko izmanto, lai savienotu darbības klienta, servera un programmu žurnālos.

- **MSAL_delete_token** — marķieru saraksts, kas šīs autentifikācijas plūsmas laikā tika izdzēsti no kešatmiņas.

- **MSAL_http_call_count** — autentifikācijas plūsmas laikā veikto MSAL HTTP zvanu skaits.

- **MSAL_is_successful** — vai autentifikācijas plūsma bija sekmīga.

- **MSAL_last_http_response_code** — ja MSAL veica vienu vai vairākus HTTP zvanus, tas ir pēdējais saņemtais HTTP atbildes kods.

- **MSAL_msal_version** — MSAL versijas virkne, formāts X.X.X+("OneAuth", "vietējais" vai saistību tēmturis).

- **MSAL_read_token** — marķieri, kas tika nolasīti no kešatmiņas (AT, ART, FRT, LRT, IRT, PRT, EAT [EAT = AT, kurai beidzies derīguma termiņš, tika nolasīta, bet izmesta]).

- **MSAL_read_token_last_error** — ja MSAL radās kļūda, lasot no kešatmiņas, šeit tiks saglabāta informācija. (Piem.: diska lasīšanas kļūda, kas radās no operētājsistēmas, atslēgu ķēdes kļūda macOS).

- **MSAL_request_duration** — cik ilgs laiks pagāja, kad tika izsaukta MSAL augstākā līmeņa API, līdz mēs atgriezām rezultātu.

- **MSAL_request_id** — pieprasījuma ID pēdējam zvanam, kuram mēs izmantojām Microsoft drošu marķieru pakalpojumu.

- **MSAL_server_error_code** — Microsoft īpašā, drošā marķiera pakalpojuma skaitliskās kļūdas kods, ja tādu saņēmām.

- **MSAL_server_spe_ring** -Microsoft Secure token Service Secure Production Enterprise zvana informācija, ja to saņēmāt.

- **MSAL_server_suberror_code** — Microsoft īpašā, drošā marķiera pakalpojuma apakškļūdas koda virkne, ja mēs to saņēmām.

- **MSAL_start_time** — laiks, kad MSAL pieprasījums tika sākts augstākā līmeņa publiskajā API.

- **MSAL_stop_time** — laiks, kad MSAL pabeidza pieprasījuma apstrādi un atgrieza rezultātu zvanītājam.

- **MSAL_tenant_id** — Microsoft GUID, kas identificē nomnieku, kuram lietotājs pastāv.

- **MSAL_ui_event_count** — UI uzvedņu skaits MSAL tiek parādīts ekrānā.

- **MSAL_wam_telemetry** — satur virkni WAM telemetrijas datu JSON virknē, kas tiks parsēti un pārveidoti par šī dokumenta laukiem, kas iegūti no WAM.

- **MSAL_was_request_throttled** — patiesi, ja MSAL ierobežotu šo pieprasījumu un neļautu tam nokļūt tīklā. Ja tas vispār ir patiess, visdrīzāk, ka zvana lietojumprogrammā ir cilpa.

- **MSAL_write_token** — marķieri, kas tika nolasīti no kešatmiņas (AT, ART, FRT, LRT, IRT, PRT, EAT [EAT = AT, kurai beidzies derīguma termiņš, tika nolasīta, bet izmesta]).

- **MSAL_write_token_last_error** — ja MSAL radās kļūda, rakstot kešatmiņā, mēs šeit saglabāsim informāciju. (Piem.: diska lasīšanas kļūda, kas radās no operētājsistēmas, atslēgu ķēdes kļūda macOS).

- **oneauth_api** — šim autentifikācijas mēģinājumam izsauktais OneAuth API.

- **oneauth_transactionuploadid** — GUID, kas norāda atsevišķu zvanu uz OneAuth API.

- **oneauth_version** — OneAuth SDK versija.

- **Platform** — operētājsistēmas platforma (0: Windows darbvirsma, 1: Android, 2: iOS, 3: macOS, 4: UWP)

- **Promptreasoncorrelationid** — korelācijas identifikatoru, ko var izmantot, lai uzmeklētu iepriekšējo autentifikācijas notikumu, kas tiek lietots, lai paskaidrotu, kāpēc lietotājam tika prasīts autentificēties.

- **Resource** — resurss, kuram tiek pieprasīts marķieris.

- **Scenarioid** — vairāki notikumi var piederēt vienam scenārijam, piemēram, scenārijs var pievienot jaunu kontu, bet pastāv vairākas uzvednes, kas rodas kā daļa no šī scenārija. Šis identifikators ļauj korelēt šos saistītos notikumus.

- **Scenarioname** — lietojumprogrammas scenārija nosaukums, kurā bija nepieciešama autentifikācija, piemēram, pirmā sāknēšana, licencēšana utt.

- **Scope** — tvērums, kuram tiek pieprasīts marķieris.

- **Sdkver** — Microsoft autentifikācijas telemetrijas sistēmas bibliotēkas versija, kas tiek lietota, lai izveidotu šos datus

- **Sessionid** — sāknēšanas sesijas identifikators

- **Starttime** — laiks, kad sākās autentifikācijas notikums.

- **Tenantid** — GUID, kas identificē nomnieku, kam autentificētais lietotājs pieder (ar ADAL nesaistītos gadījumos)

- **Uploadid** — unikālais GUID šim notikumam, tiek izmantots dublikātu likvidēšanai

- **wamapi** — nosaka, kurš Windows tīmekļa konta pārvaldības (WAM) API tiek izsaukts

- **wamtelemetrybatch** — pašlaik netiek izmantots. Nākotnē sniedz WAM komponentam iespēju izsūtīt papildinformāciju par autentifikācijas notikumu

- **WAM_account_join_on_end** — konta pievienošanās statuss WAM darbības beigās.  Iespējamās vērtības: "primārā", "sekundārā", "nav_pievienots"

- **WAM_account_join_on_start** — konta pievienošanās stāvoklis WAM darbības sākumā.  Iespējamās vērtības: "primārā", "sekundārā", "nav_pievienots"

- **WAM_api_error_code** — ja no AAD WAM spraudņa tika saņemta kļūdas atbilde, šis lauks pastāvēs un tajā būs šis kļūdas kods

- **WAM_authority** — virkne, kurā ietverts autorizācijas URL — tam vajadzētu būt izmantotajam login.windows.net galapunktam

- **WAM_broker_version** — spēkā, ja ir izmantota WAM, šī ir starpnieka versijas virkne

- **WAM_cache_event_count** — WAM kešatmiņas notikumu skaits operācijā

- **WAM_client_id** — identifikators savienošanai ar pakalpojumu datiem identificē klienta lietojumprogrammu.

- **WAM_correlation_id** — identifikators notikumu apvienošanai ar pakalpojumu datiem

- **WAM_device_join** — ierīces savienojuma statuss; iespējamās vērtības ir "aadj", "haadj"

- **WAM_network_event_count** — spēkā, ja noticis vismaz viens tīkla zvans; tīkla izsaukumu skaits uz pakalpojumu šai WAM operācijai

- **WAM_network_status** — spēkā, ja noticis vismaz viens tīkla zvans, kas satur HTTP kļūdas kodu, ja tīkla pieprasījums neizdevās.

- **WAM_idp** — norāda, vai ir izmantoti WAM patērētāja vai organizācijas autentifikācijas spraudnis.

- **WAM_is_cached** — norāda, vai WAM sniegtā atbilde ir izgūta no kešatmiņas.

- **WAM_oauth_error_code** — ietver pakalpojuma atgriezto kļūdas kodu, kas ir daļa no OAuth protokola.

- **WAM_prompt_behavior** — norāda, vai šī uzvedne ir spiesta programmā, vai arī šis pieprasījums var izlaist uzvedni, ja tas var nemanāmi autentificēties.

- **WAM_provider_id** — norāda Microsoft galapunktu, kas tiek izmantots autentifikācijas scenārijā.

- **WAM_redirect_uri** — pārvirzīt URI, kas ir reģistrēts lietojumprogrammai Azure Active Directory.

- **WAM_resource** — resurss, kuram tiek pieprasīts marķieris.

- **WAM_server_error_code** — kļūdas kods, kuru pakalpojums atgrieza WAM.

- **WAM_server_sub_code** — papildu kļūdas kods, ko izmanto, lai sīkāk sadalītu kļūmes cēloņus, ko atgriezis pakalpojums.

- **WAM_silent_code** — kļūdas kods, ar kuru saskaras iekšējais klusais mēģinājums, ko veic WAM, pirms aicināt lietotāju.

- **WAM_silent_mats** — neizmantots.

- **WAM_silent_message** — kļūdas ziņojums, kas saistīts ar iekšējo kluso mēģinājumu, ko veic WAM, pirms aicināt lietotāju.

- **WAM_silent_status** — veiksmīgs/neizdevies statuss iekšējam klusajam mēģinājumam, ko veic WAM, pirms aicināt lietotāju.

- **WAM_tenant_id** — nomnieka identifikators, kuram pieder autentificēts AAD lietotājs, ja pakalpojums to ir atgriezis

- **WAM_ui_visible** — spēkā, ja lietotājam tika parādīts vismaz viens lietotāja interfeisa logs “patiess” vai “aplams”

- **WAM_x_ms_clitelem** — spēkā, ja pakalpojums atgriež galveni “x-ms-clitelem”


### <a name="officematsoneauthtransactionmicrosoftofficewin32"></a>Office.MATS.OneAuth.TransactionMicrosoftOfficeWin32

Microsoft autentifikācijas telemetrijas sistēma (MATS) tiek apkopota, kad Office mēģina iegūt autentifikācijas marķieri vai nu nemanāmi vai izmantojot uzvedni. Šis notikums ir viena vai vairāku ActionMicrosoftOffice notikumu vecākobjekts, kas ļauj apvienot saistītus notikumus. Šie notikumi mūsu lietotājiem sniedz iespēju izvairīties no pāriešanas bojātos autentifikācijas stāvokļos.

1) Identificēšana, vai klienti var sekmīgi iegūt autentifikācijas marķieri no pakalpojuma vai ir pārgājuši bojātā autentifikācijas stāvoklī.

2) Novērtēt, kad izmaiņas rodas klientā vai pakalpojumos, vai tās izraisa kritisku regresiju lietotāja autentifikācijas pieredzē un uzticamībā

3) Ja rodas kļūme, šie signāli raida svarīgus kļūmju kodus no atbildīgā komponenta (Office klienta kods, autentifikācijas bibliotēkas vai iestāžu pakalpojumi), ko var izmantot klasificēšanai, diagnostikai un mazināšanai

4) Šie signāli nodrošina dažādus nosūtīšanas gatavības un darbspējas pārraugus, kas aktivizē brīdinājumus, lai mūsu inženieri varētu ātri iesaistīties un samazināt laiku kritisko kļūmju mazināšanai.

Tiek apkopoti šādi lauki:

- **Actiontype** — "oneauthtransaction" ir vienīgā vērtība.

- **Appaudience** — lietojumprogrammu auditorija (automatizācija, priekšražošana vai ražošana)

- **Appname** — lietojumprogrammas nosaukums

- **Appver** — lietojumprogrammas versija

- **Authoutcome** — vai autentifikācijas mēģinājums izdevās, neizdevās vai tika atcelts

- **Correlationid** — identifikators, ko izmanto, lai saistītu informāciju par šo atsevišķo notikumu ar pakalpojumu datiem

- **Count** — kļūdas rašanās reižu skaits

- **Devicenetworkstate** — ierīces tīkla stāvoklis

- **Deviceprofiletelemetryid** — ierīces profila telemetrijas ID (virkne, ko MATS izmanto, lai identificētu konkrētu ierīci)

- **duration_max** — šajā signālā apkopoto darījumu minimālais ilgums milisekundēs.

- **duration_min** — šajā signālā apkopoto darījumu maksimālais ilgums milisekundēs.

- **duration_sum** — šajā signālā apkopoto darījumu ilgumu summa milisekundēs.

- **Endtime** — laiks, kurā beidzās OneAuth transakcija.

- **Error** — OneAuth statusa kodu.

- **Eventtype** — notikuma tips

- **Issilent** — aplams, ja tika parādīts lietotāja interfeiss; tiesa, ja tas būtu fona notikums.

- **oneauth_api** — norāda publiski izmantoto OneAuth API.

- **oneauth_Domain** — ja API izsaukums izraisīja kļūdu, šis ir kļūdas sistēmas domēns.

- **oneauth_ErrorCode** — kļūdas kods, kas attēlo OneAuth iekšējo kļūdas stāvokli. Aizstāj veco lauku oneauth_errortag.

- **oneauth_errortag** — skaitliskais identifikators koda rindai, kas bija atbildīga par kļūdas radīšanu.

- **oneauth_ExecutionFlow** — atzīmju sērija, kas identificē kodēšanas ceļu, kuru šis API izsaukums izmantoja.

- **oneauth_internalerror** — kļūdas kods, kas attēlo OneAuth iekšējo kļūdas stāvokli.

- **oneauth_ServerErrorCode** — servera kļūda, kas tiek atgriezta OneAuth, šī API zvana noslēgumā, ja tāda tika konstatēta.

- **oneauth_SystemErrorCode** — sistēmas kļūda, kas tiek atgriezta OneAuth, šī API zvana noslēgumā, ja tāda tika konstatēta.

- **oneauth_Tag** — OneAuth marķieris, kas norāda galīgo vietu kodā, tika sasniegts šī API zvana beigās.

- **oneauth_transactionuploadid** — norāda nejauši ģenerētu iekšējo GUID, kas kartē konkrētu OneAuth API izsaukumu.

- **oneauth_version** — OneAuth SDK versija.

- **Platformu** — operētājsistēmas platforma (0: Win32, 1: Android, 2: iOS, 3: macOS, 4: WinRT

- **Scenarioname** — scenārija nosaukums, kuram nepieciešama autentifikācija, ko nosaka izsaucošā lietojumprogramma.

- **Schemaver** — shēmas versija

- **Sdkver** — MATS SDK versija

- **Sessionid** — sesijas ID

- **severityError** — smaguma pakāpe

- **starttime** — laiks, kurā sākas OneAuth transakcija.

- **Timestamp** — laikspiedols

- **Type** — kļūdas tips

- **Uploaded** — šī konkrētā notikuma unikālais identifikators dublikātu likvidēšanai.


### <a name="onenotesigninssoexternalappsaccountfound"></a>OneNote.SignIn.SSOExternalAppsAccountFound
 
Šis notikums tiek reģistrēts, ja tiek atrasts derīgs atsvaidzināšanas marķieris kontu sarakstā, ko nodrošina TokenSharingManager.  Šis scenārijs attiecas uz vienoto pierakstīšanos (SSO).
 
Tiek apkopoti tālāk norādītie lauki:
 
- **AccountType** — reģistrē konta tipu

- **ProviderPackageID** — reģistrē tās programmas pakotnes ID, kas nodrošināja šo kontu

### <a name="onenotesigninssoexternalappsinvalidaccount"></a>OneNote.SignIn.SSOExternalAppsInvalidAccount

Šis notikums tiek reģistrēts, ja radās kļūda, mēģinot iegūt konta atsvaidzināšanas marķieri kontu sarakstā, ko nodrošina TokenSharingManager. Šis scenārijs attiecas uz vienoto pierakstīšanos (SSO)
 
Tiek apkopoti tālāk norādītie lauki:
 
- **RawError** — reģistrē RAW kļūdu, kas rodas, mēģinot iegūt atsvaidzināšanas marķieri ar norādīto kontu

### <a name="onenotestickynotesfetchtokencompleted"></a>OneNote.StickyNotes.FetchTokenCompleted
 
Šis notikums ir pieteicies ziņas autentifikācijai, kad ir pabeigta atsvaidzināšanas marķiera iegūšana.
 
Tiek apkopoti tālāk norādītie lauki:
 
- **ErrorMessage** — ja neizdevās ielādēt marķieri, tiks parādīts kļūdas ziņojums 

- **Result** — reģistrē marķiera iegūšanas mēģinājuma rezultātu

- **StickyNoteAccountType** — reģistrē konta tipu, kuram programma mēģināja izgūt atsvaidzināšanas marķieri


## <a name="click-to-run-events"></a>Click-to-Run notikumi

### <a name="officeclicktorunbootstrapper"></a>Office.ClickToRun.Bootstrapper 

Office iestatīšanas un krājumu dati, kas tiek apkopoti, kad lietotājs palaiž failu Office setup.exe, lai modificētu savus instalētos Office produktus. Tiek izmantots, lai mērītu pilnas lietotāja uzsāktas Office instalēšanas sekmīgu izpildi/kļūmi, tostarp priekšnoteikumu pārbaudes.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_BootStrapperStateFailure\_ErrorCode** — kļūdas kods, ar kuru radās problēmas

  - **Data\_BootStrapperStateFailure\_ErrorSource** — funkcija, ar kuru radās problēmas

  - **Data\_BootStrapperStateFailure\_FailingState** — daļa, kas neizdevās boostrapperbootstrapper

  - **Data\_BootStrapperStateFailure\_OExceptionType** — izņēmuma veids, ar kuru radās problēmas

  - **Data\_Culture** — kultūra, ar kuru izmantojam šo exe failu, t.i., en-us

  - **Data\_HashedOLSToken** — marķiera sha-256 jaukšanas vērtība, ko OLS pakalpojums mums piešķir

  - **Data\_Platform** — x64 vai x86 instalācija

  - **Data\_PrereqFailure\_Type** — priekšnoteikumu kļūme, kāda rodas, t.i., operētājsistēma netiek atbalstīta

  - **Data\_ProductReleaseId** — produkts, ko instalējam, piemēram, Microsoft 365 programmas lieluzņēmumiem

### <a name="officeclicktoruncorruptioncheck"></a>Office.ClickToRun.CorruptionCheck

Office iestatīšanas un krājumu dati, kas tiek apkopoti, kad Click-to-Run klients veic bojājumu pārbaudi, lai nodrošinātu, ka Office binārie faili ir pareizi. Tiek izmantots, lai mērītu Office bināro failu bojājumu un to, kuri binārie faili ir bojāti.

Tiek apkopoti šādi lauki:

  - **Data\_Active —** pašreizējais straumes manifests, ko pārbaudām diskā

  - **Data\_ActivePackages —** kādas pakotnes manifests satur

  - **Data\_ActiveVersion —** manifesta versija

  - **Data\_AddFileCount —** cik failu pievienojam

  - **Data\_AddFileFiles —** failu, ko pievienojam, paraugs

  - **Data\_CompressionLevel —** kā faili tiek saspiesti

  - **Data\_CorruptionCheckLevel —** cik dziļi meklējam bojājumus, pakāpes

  - **Data\_CorruptSizeCount —** cik failiem ir bojāts lielums

  - **Data\_CorruptSizeFiles —** failu, kam ir bojāts lielums, paraugs

  - **Data\_CorruptVersionCount —** cik failiem ir bojāta versija

  - **Data\_CorruptVersionFiles —** failu, kam ir bojāta versija, paraugs

  - **Data\_FileBadDigestCount —** cik failus neizdevās atvērt

  - **Data\_FileBadDigestFiles —** failu, ko nevaram atvērt, paraugs

  - **Data\_FileNotSignedCount —** cik faili nav parakstīti

  - **Data\_FileNotSignedFiles —** failu, kas nav parakstīti, paraugs

  - **Data\_FileNotTrustedCount —** cik faili nav uzticami

  - **Data\_FileNotTrustedFiles —** failu, kam neuzticamies, paraugs

  - **Data\_IncompleteFileCount —** cik faili šķiet nepilnīgi

  - **Data\_IncompleteFileFiles —** nepilnīgo failu paraugs

  - **Data\_KeepFileCount —** ar cik failiem neko nedarām

  - **Data\_KeepFileFiles —** failu, ko paturam, paraugs

  - **Data\_KeepIncompleteFileCount —** cik failus nemainām, neskatoties uz to, ka tie ir nepilnīgi

  - **Data\_KeepIncompleteFileFiles —** failu, ko paturam un kuri ir nepilnīgi, paraugs

  - **Data\_MismatchSizeCount —** cik failu izmērs neatbilst mūsu manifestam

  - **Data\_MismatchSizeFiles —** failu, kam ir neatbilstošs lielums, paraugs

  - **Data\_MismatchVersionCount —** cik failiem versija atšķiras no mūsu manifesta

  - **Data\_MismatchVersionFiles —** failu, kam ir neatbilstošas versijas, paraugs

  - **Data\_MissingFileCount —** cik failu trūkst

  - **Data\_MissingFileFiles —** trūkstošo failu paraugs

  - **Data\_NotToBeStreamedFileCount —** cik failus nestraumējam

  - **Data\_RemoveFileCount —** cik failu noņemam

  - **Data\_RemoveFileFiles —** failu, ko noņemam, paraugs

  - **Data\_StreamUnitsMismatchCount —** cik failiem ir vienības, kas neatbilst manifestam

  - **Data\_StreamUnitsMismatchFiles —** failu, kam ir straume ar neatbilstošām vienībām, paraugs

  - **Data\_TimeElapsed —** cik ilga bija bojājumu meklēšana

  - **Data\_UpdateFileCount —** cik failu atjauninām

  - **Data\_UpdateFileFiles —** failu, ko pievienojam, paraugs

  - **Data\_Working —** jaunais manifests, ko pārbaudām

  - **Data\_WorkingVersion —** jaunā manifesta versija

### <a name="officeclicktorunmachinemetadata"></a>Office.ClickToRun.MachineMetadata

Office iestatīšanas un krājumu dati, kas nodrošina nepieciešamos metadatus iestatīšanai un krājumiem un kas tiek izmantoti, lai noteiktu precīzu instalēšanas bāzi.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_C2RClientVer** — OfficeClickToRun.exe versija datorā

  - **Data\_OfficeBitness** — bitu skaits, kādā sistēma Office ir instalēta, x86 vai x64

  - **Data\_OfficeVersion** — versija, kādā sistēma Office ir instalēta

  - **Data\_Sku** — instalētais SKU, piemēram,Microsoft 365 programmas lieluzņēmumiem

  - **Data\_SqmMachineID** — unikālais datora ID, ko izmanto Windows SQM Data\_SusClientID- datora Office atjaunināšanas identifikators

### <a name="officeclicktorunodt"></a>Office.ClickToRun.ODT

Office iestatīšanas un krājumu dati, kas tiek apkopoti, kad IT administrators palaiž Office izvietošanas rīka Click-to-Run failu setup.exe, lai modificētu savu lietotāju instalētos Office produktus. Tie tiek izmantoti, lai mērītu pilnas IT administratora uzsāktas Office instalēšanas sekmīgu izpildi/kļūmi, tostarp priekšnoteikumu pārbaudes.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_BootStrapperStateFailure\_ErrorCode —** kļūdas kods, ar kuru radās problēmas

  - **Data\_BootStrapperStateFailure\_ErrorSource —** funkcija, ar kuru radās problēmas

  - **Data\_BootStrapperStateFailure\_FailingState —** daļa, kas neizdevās boot-strapper

  - **Data\_BootStrapperStateFailure\_OExceptionType —** izņēmuma veids, ar kuru radās problēmas

  - **Data\_ConfigurationHost —** resursdators, no kura nācis fails configuration.xml

  - **Data\_ConfigurationId —** ID, ko iegūstam no faila configuration.xml

  - **Data\_ConfigurationSource —** no kurienes nācis fails configuration.xml

  - **Data\_Culture —** kultūra, ar kuru izmantojam šo exe failu, t.i., en-us

  - **Data\_HashedOLSToken —** marķiera sha-256 jaukšanas vērtība, ko OLS pakalpojums mums piešķir

  - **Data\_MigrateArchRequest —** vai migrējam lietotāju no x86 uz x64 vai pretēji

  - **Data\_MigrateArchRequestValid —** vai uzskatām, ka migrēšanas pieprasījums ir derīgs

  - **Data\_Platform —** x64 vai x86 instalācija

  - **Data\_PlatformMigratedFrom —** sākuma platforma, t.i., x86

  - **Data\_PlatformMigratedTo —** beigu platforma, t.i., x64

  - **Data\_PrereqFailure\_Type —** priekšnosacījumu kļūme, kas rodas

  - **Data\_ProductReleaseId** — produkts, ko instalējam, piemēram, Microsoft 365 programmas lieluzņēmumiem

### <a name="officeclicktorunrepomanlogger"></a>Office.ClickToRun.RepomanLogger

Ziņo par jaunā Click-to-Run atjauninājumu konveijera statusu (“Repoman”) un par to, vai tas veiksmīgi lejupielādē un instalē Office atjauninājumus.

Tiek apkopoti šādi lauki:

  - **ApplySucceeded —** patiess, ja konveijers veiksmīgi lietoja Office atjauninājumu, pretējā gadījumā — aplams.
  
  - **DownloadSucceeded —** patiess, ja konveijers veiksmīgi lietoja Office atjauninājumu, pretējā gadījumā — aplams.

  - **ErrorCode —** pēdējās kļūdas kods, kura radās Click-to-Run Repoman konveijerā.

  - **ErrorDetails —** papildu informācija par kļūdu, kura radās Click-to-Run Repoman konveijerā.
 
  - **ErrorMessage —** pēdējās kļūdas ziņa, kura radās Click-to-Run Repoman konveijerā.

  - **OpenStreamSessionSucceeded —** patiess, ja konveijerā veiksmīgi tiek radīta sesija Office atjauninājuma straumēšanai, pretējā gadījumā — aplams.

  - **RepomanErrorMessage —** kļūdas ziņojums, kurš saņemts no repoman.dll.
 

### <a name="officeclicktorunscenarioinstalltaskconfigure"></a>Office.ClickToRun.Scenario.InstallTaskConfigure

Office iestatīšanas un krājumu dati, kas tiek apkopoti, kad Office instalētājs izvieto no jauna lejupielādētos failus. Tiek izmantots, lai mērītu Office instalācijas sekmīgu/kļūdainu darbību.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_15\_SourceType —** kur Office 15 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_15\_UpdatesEnabled —** ja Office 15 atjauninājumi ir iespējoti 

  - **Data\_15\_UpdateVersion —** uz kādu Office 15 versiju veicam atjaunināšanu 

  - **Data\_15\_Version —** Office 15 versija 

  - **Data\_16\_SourceType —** kur Office 16 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_16\_UpdatesEnabled —** ja Office 16 atjauninājumi ir iespējoti 

  - **Data\_16\_UpdateVersion —** uz kādu Office 16 versiju veicam atjaunināšanu 

  - **Data\_16\_Version —** Office 16 versija 

  - **Data\_AddingFixedProducts —** produkti, ko pievienojam 

  - **Data\_AddingProducts —** kādus produktus mums tiek lūgts pievienot 

  - **Data\_CompletionState —** vai pabeidzām uzdevumu

  - **Data\_ErrorCode —** kļūdas kods, ar kuru radās problēmas 

  - **Data\_ErrorDetails —** papildu detalizēta informācija par kļūdu 

  - **Data\_ErrorMessage —** kļūdas ziņojums par to, kāda problēma radās 

  - **Data\_ErrorSource —** kur kļūda radās 

  - **Data\_ExceptionType —** izņēmums, ar kuru radās problēmas 

  - **Data\_IsErrorCodeIgnorable —** vai kļūdas kods, ar kuru radās problēmas, ir ignorējams 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth —** ja uzskatām, ka kļūdas kods ir ignorējams 

  - **Data\_NewestPackageVersion —** jaunākā Office versija datorā 

  - **Data\_OldestPackageVersion —** vecākā Office versija datorā 

  - **Data\_ProductsToAdd —** kādus Office produktus pievienojam 

  - **Data\_ProductsToRemove —** kādus Office produktus noņemam 

  - **Data\_RemovingFixedProducts —** produkti, ko noņemam 

  - **Data\_RemovingProducts —** produkti, kurus mums tiek lūgts noņemt 

  - **Data\_ScenarioInstanceID —** unikāls GUID darbības scenārijam 

  - **Data\_ScenarioName —** kāds scenārijs tiek izmantots. t.i., instalēšana 

  - **Data\_ScenarioSubType —** kāda veida scenāriju izmantojam, t.i., atinstalēšana, atkārtota instalēšana 

  - **Data\_SourceType —** kur ir mūsu avots, t.i., CDN 

  - **Data\_SqmMachineID —** unikālais datora ID, ko izmanto Windows SQM 

  - **Data\_SusClientID —** datora Office atjaunināšanas identifikators 

  - **Data\_TaskState —** kādā stāvoklī ir uzdevums, piemēram, darbojas vai atcelts 

  - **Data\_TotalClientCabSize —** mūsu klienta kabinetfaila lielums 

  - **Data\_TriggeringUI —** kas aktivizēja UI 

  - **Data\_UpdatesEnabled —** ja Office atjauninājumi ir iespējoti 

  - **Data\_Version —** Office versija 

### <a name="officeclicktorunscenarioinstalltaskconfigurelight"></a>Office.ClickToRun.Scenario.InstallTaskConfigurelight

Office iestatīšanas un krājumu dati, kas tiek apkopoti, kad Office instalētājs izlemj, kuri faili ir jālejupielādē. Tiek izmantots, lai mērītu Office instalācijas sekmīgu/kļūdainu darbību.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_15\_SourceType —** kur Office 15 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_15\_UpdatesEnabled —** ja Office 15 atjauninājumi ir iespējoti 

  - **Data\_15\_UpdateVersion —** uz kādu Office 15 versiju veicam atjaunināšanu 

  - **Data\_15\_Version —** Office 15 versija 

  - **Data\_16\_SourceType —** kur Office 16 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_16\_UpdatesEnabled —** ja Office 16 atjauninājumi ir iespējoti 

  - **Data\_16\_UpdateVersion —** uz kādu Office 16 versiju veicam atjaunināšanu 

  - **Data\_16\_Version —** Office 16 versija 

  - **Data\_AddingFixedProducts —** produkti, ko pievienojam 

  - **Data\_AddingProducts —** kādus produktus mums tiek lūgts pievienot 

  - **Data\_CompletionState —** vai pabeidzām uzdevumu

  - **Data\_ErrorCode —** kļūdas kods, ar kuru radās problēmas 

  - **Data\_ErrorDetails —** papildu detalizēta informācija par kļūdu 

  - **Data\_ErrorMessage —** kļūdas ziņojums par to, kāda problēma radās 

  - **Data\_ErrorSource —** kur kļūda radās 

  - **Data\_ExceptionType —** izņēmums, ar kuru radās problēmas 

  - **Data\_IsErrorCodeIgnorable —** vai kļūdas kods, ar kuru radās problēmas, ir ignorējams 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth —** ja uzskatām, ka kļūdas kods ir ignorējams 

  - **Data\_NewestPackageVersion —** jaunākā Office versija datorā 

  - **Data\_OldestPackageVersion —** vecākā Office versija datorā 

  - **Data\_ProductsToAdd —** kādus Office produktus pievienojam 

  - **Data\_ProductsToRemove —** kādus Office produktus noņemam 

  - **Data\_RemovingFixedProducts —** produkti, ko noņemam 

  - **Data\_RemovingProducts —** produkti, kurus mums tiek lūgts noņemt 

  - **Data\_ScenarioInstanceID —** unikāls GUID darbības scenārijam 

  - **Data\_ScenarioName —** kāds scenārijs tiek izmantots. t.i., instalēšana 

  - **Data\_ScenarioSubType —** kāda veida scenāriju izmantojam, t.i., atinstalēšana, atkārtota instalēšana 

  - **Data\_SourceType —** kur ir mūsu avots, t.i., CDN 

  - **Data\_SqmMachineID —** unikālais datora ID, ko izmanto Windows SQM 

  - **Data\_SusClientID —** datora Office atjaunināšanas identifikators 

  - **Data\_TaskState —** kādā stāvoklī ir uzdevums, piemēram, darbojas vai atcelts 

  - **Data\_TotalClientCabSize —** mūsu klienta kabinetfaila lielums 

  - **Data\_TriggeringUI —** kas aktivizēja UI 

  - **Data\_UpdatesEnabled —** ja Office atjauninājumi ir iespējoti 

  - **Data\_Version —** Office versija 

### <a name="officeclicktorunscenarioinstalltaskfinalintegrate"></a>Office.ClickToRun.Scenario.InstallTaskFinalintegrate

Office iestatīšanas un krājumu dati, kas tiek apkopoti, kad Office instalētājs instalē licences un reģistra iestatījumus. Tiek izmantots, lai mērītu Office instalācijas sekmīgu/kļūdainu darbību.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_15\_SourceType —** kur Office 15 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_15\_UpdatesEnabled —** ja Office 15 atjauninājumi ir iespējoti 

  - **Data\_15\_UpdateVersion —** uz kādu Office 15 versiju veicam atjaunināšanu

  - **Data\_15\_Version —** Office 15 versija 

  - **Data\_16\_SourceType —** kur Office 16 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_16\_UpdatesEnabled —** ja Office 16 atjauninājumi ir iespējoti 

  - **Data\_16\_UpdateVersion —** uz kādu Office 16 versiju veicam atjaunināšanu 

  - **Data\_16\_Version —** Office 16 versija 

  - **Data\_AddingFixedProducts —** produkti, ko pievienojam 

  - **Data\_AddingProducts —** kādus produktus mums tiek lūgts pievienot 

  - **Data\_CompletionState —** vai pabeidzām uzdevumu

  - **Data\_ErrorCode —** kļūdas kods, ar kuru radās problēmas 

  - **Data\_ErrorDetails —** papildu detalizēta informācija par kļūdu 

  - **Data\_ErrorMessage —** kļūdas ziņojums par to, kāda problēma radās 

  - **Data\_ErrorSource —** kur kļūda radās

  - **Data\_ExceptionType —** izņēmums, ar kuru radās problēmas 

  - **Data\_IsErrorCodeIgnorable —** vai kļūdas kods, ar kuru radās problēmas, ir ignorējams 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth —** ja uzskatām, ka kļūdas kods ir ignorējams 

  - **Data\_NewestPackageVersion —** jaunākā Office versija datorā 

  - **Data\_OldestPackageVersion —** vecākā Office versija datorā 

  - **Data\_ProductsToAdd —** kādus Office produktus pievienojam 

  - **Data\_ProductsToRemove —** kādus Office produktus noņemam 

  - **Data\_RemovingFixedProducts —** produkti, ko noņemam 

  - **Data\_RemovingProducts —** produkti, kurus mums tiek lūgts noņemt 

  - **Data\_ScenarioInstanceID —** unikāls GUID darbības scenārijam 

  - **Data\_ScenarioName —** kāds scenārijs tiek izmantots. t.i., instalēšana 

  - **Data\_ScenarioSubType —** kāda veida scenāriju izmantojam, t.i., atinstalēšana, atkārtota instalēšana 

  - **Data\_SourceType —** kur ir mūsu avots, t.i., CDN 

  - **Data\_SqmMachineID —** unikālais datora ID, ko izmanto Windows SQM 

  - **Data\_SusClientID —** datora Office atjaunināšanas identifikators 

  - **Data\_TaskState —** kādā stāvoklī ir uzdevums, piemēram, darbojas vai atcelts 

  - **Data\_TotalClientCabSize —** mūsu klienta kabinetfaila lielums 

  - **Data\_TriggeringUI —** kas aktivizēja UI 

  - **Data\_UpdatesEnabled —** ja Office atjauninājumi ir iespējoti 

  - **Data\_Version —** Office versija 

### <a name="officeclicktorunscenarioinstalltaskfonts"></a>Office.ClickToRun.Scenario.InstallTaskFonts

Office iestatīšanas un krājumu dati, kas tiek apkopoti, kad Office instalētājs instalē fontus. Tiek izmantots, lai mērītu Office instalācijas sekmīgu/kļūdainu darbību.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_15\_SourceType —** kur Office 15 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_15\_UpdatesEnabled —** ja Office 15 atjauninājumi ir iespējoti 

  - **Data\_15\_UpdateVersion —** uz kādu Office 15 versiju veicam atjaunināšanu 

  - **Data\_15\_Version —** Office 15 versija 

  - **Data\_16\_SourceType —** kur Office 16 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_16\_UpdatesEnabled —** ja Office 16 atjauninājumi ir iespējoti 

  - **Data\_16\_UpdateVersion —** uz kādu Office 16 versiju veicam atjaunināšanu 

  - **Data\_16\_Version —** Office 16 versija 

  - **Data\_AddingFixedProducts —** produkti, ko pievienojam 

  - **Data\_AddingProducts —** kādus produktus mums tiek lūgts pievienot 

  - **Data\_CompletionState —** vai pabeidzām uzdevumu

  - **Data\_ErrorCode —** kļūdas kods, ar kuru radās problēmas 

  - **Data\_ErrorDetails —** papildu detalizēta informācija par kļūdu 

  - **Data\_ErrorMessage —** kļūdas ziņojums par to, kāda problēma radās 

  - **Data\_ErrorSource —** kur kļūda radās 

  - **Data\_ExceptionType —** izņēmums, ar kuru radās problēmas 

  - **Data\_IsErrorCodeIgnorable —** vai kļūdas kods, ar kuru radās problēmas, ir ignorējams 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth —** ja uzskatām, ka kļūdas kods ir ignorējams 

  - **Data\_NewestPackageVersion —** jaunākā Office versija datorā 

  - **Data\_OldestPackageVersion —** vecākā Office versija datorā 

  - **Data\_ProductsToAdd —** kādus Office produktus pievienojam 

  - **Data\_ProductsToRemove —** kādus Office produktus noņemam 

  - **Data\_RemovingFixedProducts —** produkti, ko noņemam 

  - **Data\_RemovingProducts —** produkti, kurus mums tiek lūgts noņemt 

  - **Data\_ScenarioInstanceID —** unikāls GUID darbības scenārijam 

  - **Data\_ScenarioName —** kāds scenārijs tiek izmantots. t.i., instalēšana

  - **Data\_ScenarioSubType —** kāda veida scenāriju izmantojam, t.i., atinstalēšana, atkārtota instalēšana 

  - **Data\_SourceType —** kur ir mūsu avots, t.i., CDN 

  - **Data\_SqmMachineID —** unikālais datora ID, ko izmanto Windows SQM 

  - **Data\_SusClientID —** datora Office atjaunināšanas identifikators 

  - **Data\_TaskState —** kādā stāvoklī ir uzdevums, piemēram, darbojas vai atcelts 

  - **Data\_TotalClientCabSize —** mūsu klienta kabinetfaila lielums 

  - **Data\_TriggeringUI —** kas aktivizēja UI 

  - **Data\_UpdatesEnabled —** ja Office atjauninājumi ir iespējoti 

  - **Data\_Version —** Office versija 

### <a name="officeclicktorunscenarioinstalltaskinitupdates"></a>Office.ClickToRun.Scenario.InstallTaskInitupdates

Office iestatīšanas un krājumu dati, kas tiek apkopoti, kad Office instalētājs veidot iestatījumus, lai atjauninājumi darbotos pareizi. Tiek izmantots, lai mērītu Office instalācijas sekmīgu/kļūdainu darbību.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_15\_SourceType —** kur Office 15 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_15\_UpdatesEnabled —** ja Office 15 atjauninājumi ir iespējoti 

  - **Data\_15\_UpdateVersion —** uz kādu Office 15 versiju veicam atjaunināšanu 

  - **Data\_15\_Version —** Office 15 versija 

  - **Data\_16\_SourceType —** kur Office 16 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_16\_UpdatesEnabled —** ja Office 16 atjauninājumi ir iespējoti 

  - **Data\_16\_UpdateVersion —** uz kādu Office 16 versiju veicam atjaunināšanu 

  - **Data\_16\_Version —** Office 16 versija 

  - **Data\_AddingFixedProducts —** produkti, ko pievienojam 

  - **Data\_AddingProducts —** kādus produktus mums tiek lūgts pievienot 

  - **Data\_CompletionState —** vai pabeidzām uzdevumu

  - **Data\_ErrorCode —** kļūdas kods, ar kuru radās problēmas 

  - **Data\_ErrorDetails —** papildu detalizēta informācija par kļūdu 

  - **Data\_ErrorMessage —** kļūdas ziņojums par to, kāda problēma radās 

  - **Data\_ErrorSource —** kur kļūda radās 

  - **Data\_ExceptionType —** izņēmums, ar kuru radās problēmas 

  - **Data\_IsErrorCodeIgnorable —** vai kļūdas kods, ar kuru radās problēmas, ir ignorējams 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth —** ja uzskatām, ka kļūdas kods ir ignorējams 

  - **Data\_NewestPackageVersion —** jaunākā Office versija datorā 

  - **Data\_OldestPackageVersion —** vecākā Office versija datorā 

  - **Data\_ProductsToAdd —** kādus Office produktus pievienojam 

  - **Data\_ProductsToRemove —** kādus Office produktus noņemam 

  - **Data\_RemovingFixedProducts —** produkti, ko noņemam 

  - **Data\_RemovingProducts —** produkti, kurus mums tiek lūgts noņemt 

  - **Data\_ScenarioInstanceID —** unikāls GUID darbības scenārijam 

  - **Data\_ScenarioName —** kāds scenārijs tiek izmantots. t.i., instalēšana

  - **Data\_ScenarioSubType —** kāda veida scenāriju izmantojam, t.i., atinstalēšana, atkārtota instalēšana 

  - **Data\_SourceType —** kur ir mūsu avots, t.i., CDN 

  - **Data\_SqmMachineID —** unikālais datora ID, ko izmanto Windows SQM 

  - **Data\_SusClientID —** datora Office atjaunināšanas identifikators 

  - **Data\_TaskState —** kādā stāvoklī ir uzdevums, piemēram, darbojas vai atcelts 

  - **Data\_TotalClientCabSize —** mūsu klienta kabinetfaila lielums 

  - **Data\_TriggeringUI —** kas aktivizēja UI 

  - **Data\_UpdatesEnabled —** ja Office atjauninājumi ir iespējoti 

  - **Data\_Version —** Office versija 

### <a name="officeclicktorunscenarioinstalltaskintegrateinstall"></a>Office.ClickToRun.Scenario.InstallTaskIntegrateinstall

Office iestatīšanas un krājumu dati, kas tiek apkopoti, kad Office instalētājs veido reģistra ierakstus Office lietojumprogrammām. Tiek izmantots, lai mērītu Office instalācijas sekmīgu/kļūdainu darbību.

Tiek apkopoti šādi lauki:

  - **Data\_15\_SourceType —** kur Office 15 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_15\_UpdatesEnabled —** ja Office 15 atjauninājumi ir iespējoti 

  - **Data\_15\_UpdateVersion —** uz kādu Office 15 versiju veicam atjaunināšanu

  - **Data\_15\_Version —** Office 15 versija 

  - **Data\_16\_SourceType —** kur Office 16 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_16\_UpdatesEnabled —** ja Office 16 atjauninājumi ir iespējoti 

  - **Data\_16\_UpdateVersion —** uz kādu Office 16 versiju veicam atjaunināšanu 

  - **Data\_16\_Version —** Office 16 versija 

  - **Data\_AddingFixedProducts —** produkti, ko pievienojam 

  - **Data\_AddingProducts —** kādus produktus mums tiek lūgts pievienot 

  - **Data\_CompletionState —** vai pabeidzām uzdevumu

  - **Data\_ErrorCode —** kļūdas kods, ar kuru radās problēmas 

  - **Data\_ErrorDetails —** papildu detalizēta informācija par kļūdu 

  - **Data\_ErrorMessage —** kļūdas ziņojums par to, kāda problēma radās 

  - **Data\_ErrorSource —** kur kļūda radās 

  - **Data\_ExceptionType —** izņēmums, ar kuru radās problēmas 

  - **Data\_IsErrorCodeIgnorable —** vai kļūdas kods, ar kuru radās problēmas, ir ignorējams 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth —** ja uzskatām, ka kļūdas kods ir ignorējams 

  - **Data\_NewestPackageVersion —** jaunākā Office versija datorā 

  - **Data\_OldestPackageVersion —** vecākā Office versija datorā 

  - **Data\_ProductsToAdd —** kādus Office produktus pievienojam 

  - **Data\_ProductsToRemove —** kādus Office produktus noņemam 

  - **Data\_RemovingFixedProducts —** produkti, ko noņemam 

  - **Data\_RemovingProducts —** produkti, kurus mums tiek lūgts noņemt 

  - **Data\_ScenarioInstanceID —** unikāls GUID darbības scenārijam 

  - **Data\_ScenarioName —** kāds scenārijs tiek izmantots. t.i., instalēšana 

  - **Data\_ScenarioSubType —** kāda veida scenāriju izmantojam, t.i., atinstalēšana, atkārtota instalēšana 

  - **Data\_SourceType —** kur ir mūsu avots, t.i., CDN 

  - **Data\_SqmMachineID —** unikālais datora ID, ko izmanto Windows SQM

  - **Data\_SusClientID —** datora Office atjaunināšanas identifikators 

  - **Data\_TaskState —** kādā stāvoklī ir uzdevums, piemēram, darbojas vai atcelts 

  - **Data\_TotalClientCabSize —** mūsu klienta kabinetfaila lielums 

  - **Data\_TriggeringUI —** kas aktivizēja UI 

  - **Data\_UpdatesEnabled —** ja Office atjauninājumi ir iespējoti 

  - **Data\_Version —** Office versija 

### <a name="officeclicktorunscenarioinstalltasklastrun"></a>Office.ClickToRun.Scenario.InstallTaskLastrun

Office iestatīšanas un krājumu dati, kas tiek apkopoti, kad Office instalētājs pabeidz instalēšanu, piesprauž saīsnes un veido gala reģistra iestatījumus. Tiek izmantots, lai mērītu Office instalācijas sekmīgu/kļūdainu darbību.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_15\_SourceType —** kur Office 15 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_15\_UpdatesEnabled —** ja Office 15 atjauninājumi ir iespējoti 

  - **Data\_15\_UpdateVersion —** uz kādu Office 15 versiju veicam atjaunināšanu

  - **Data\_15\_Version —** Office 15 versija 

  - **Data\_16\_SourceType —** kur Office 16 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_16\_UpdatesEnabled —** ja Office 16 atjauninājumi ir iespējoti 

  - **Data\_16\_UpdateVersion —** uz kādu Office 16 versiju veicam atjaunināšanu 

  - **Data\_16\_Version —** Office 16 versija 

  - **Data\_AddingFixedProducts —** produkti, ko pievienojam 

  - **Data\_AddingProducts —** kādus produktus mums tiek lūgts pievienot 

  - **Data\_CompletionState —** vai pabeidzām uzdevumu

  - **Data\_ErrorCode —** kļūdas kods, ar kuru radās problēmas 

  - **Data\_ErrorDetails —** papildu detalizēta informācija par kļūdu 

  - **Data\_ErrorMessage —** kļūdas ziņojums par to, kāda problēma radās 

  - **Data\_ErrorSource —** kur kļūda radās 

  - **Data\_ExceptionType —** izņēmums, ar kuru radās problēmas 

  - **Data\_IsErrorCodeIgnorable —** vai kļūdas kods, ar kuru radās problēmas, ir ignorējams 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth —** ja uzskatām, ka kļūdas kods ir ignorējams 

  - **Data\_NewestPackageVersion —** jaunākā Office versija datorā 

  - **Data\_OldestPackageVersion —** vecākā Office versija datorā 

  - **Data\_ProductsToAdd —** kādus Office produktus pievienojam 

  - **Data\_ProductsToRemove —** kādus Office produktus noņemam 

  - **Data\_RemovingFixedProducts —** produkti, ko noņemam 

  - **Data\_RemovingProducts —** produkti, kurus mums tiek lūgts noņemt 

  - **Data\_ScenarioInstanceID —** unikāls GUID darbības scenārijam 

  - **Data\_ScenarioName —** kāds scenārijs tiek izmantots. t.i., instalēšana

  - **Data\_ScenarioSubType —** kāda veida scenāriju izmantojam, t.i., atinstalēšana, atkārtota instalēšana 

  - **Data\_SourceType —** kur ir mūsu avots, t.i., CDN 

  - **Data\_SqmMachineID —** unikālais datora ID, ko izmanto Windows SQM

  - **Data\_SusClientID —** datora Office atjaunināšanas identifikators 

  - **Data\_TaskState —** kādā stāvoklī ir uzdevums, piemēram, darbojas vai atcelts 

  - **Data\_TotalClientCabSize —** mūsu klienta kabinetfaila lielums 

  - **Data\_TriggeringUI —** kas aktivizēja UI 

  - **Data\_UpdatesEnabled —** ja Office atjauninājumi ir iespējoti 

  - **Data\_Version —** Office versija 

### <a name="officeclicktorunscenarioinstalltaskmigrate"></a>Office.ClickToRun.Scenario.InstallTaskMigrate

Office iestatīšanas un krājumu dati, kas tiek apkopoti, kad Office instalētājs migrē iestatījumus no vecākām Office versijām. Tiek izmantots, lai mērītu Office instalācijas sekmīgu/kļūdainu darbību.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_15\_SourceType —** kur Office 15 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_15\_UpdatesEnabled —** ja Office 15 atjauninājumi ir iespējoti 

  - **Data\_15\_UpdateVersion —** uz kādu Office 15 versiju veicam atjaunināšanu

  - **Data\_15\_Version —** Office 15 versija 

  - **Data\_16\_SourceType —** kur Office 16 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_16\_UpdatesEnabled —** ja Office 16 atjauninājumi ir iespējoti 

  - **Data\_16\_UpdateVersion —** uz kādu Office 16 versiju veicam atjaunināšanu 

  - **Data\_16\_Version —** Office 16 versija 

  - **Data\_AddingFixedProducts —** produkti, ko pievienojam 

  - **Data\_AddingProducts —** kādus produktus mums tiek lūgts pievienot 

  - **Data\_CompletionState —** vai pabeidzām uzdevumu

  - **Data\_ErrorCode —** kļūdas kods, ar kuru radās problēmas 

  - **Data\_ErrorDetails —** papildu detalizēta informācija par kļūdu 

  - **Data\_ErrorMessage —** kļūdas ziņojums par to, kāda problēma radās 

  - **Data\_ErrorSource —** kur kļūda radās

  - **Data\_ExceptionType —** izņēmums, ar kuru radās problēmas 

  - **Data\_IsErrorCodeIgnorable —** vai kļūdas kods, ar kuru radās problēmas, ir ignorējams 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth —** ja uzskatām, ka kļūdas kods ir ignorējams 

  - **Data\_NewestPackageVersion —** jaunākā Office versija datorā 

  - **Data\_OldestPackageVersion —** vecākā Office versija datorā 

  - **Data\_ProductsToAdd —** kādus Office produktus pievienojam 

  - **Data\_ProductsToRemove —** kādus Office produktus noņemam 

  - **Data\_RemovingFixedProducts —** produkti, ko noņemam 

  - **Data\_RemovingProducts —** produkti, kurus mums tiek lūgts noņemt 

  - **Data\_ScenarioInstanceID —** unikāls GUID darbības scenārijam 

  - **Data\_ScenarioName —** kāds scenārijs tiek izmantots. t.i., instalēšana

  - **Data\_ScenarioSubType —** kāda veida scenāriju izmantojam, t.i., atinstalēšana, atkārtota instalēšana 

  - **Data\_SourceType —** kur ir mūsu avots, t.i., CDN 

  - **Data\_SqmMachineID —** unikālais datora ID, ko izmanto Windows SQM

  - **Data\_SusClientID —** datora Office atjaunināšanas identifikators

  - **Data\_TaskState —** kādā stāvoklī ir uzdevums, piemēram, darbojas vai atcelts 

  - **Data\_TotalClientCabSize —** mūsu klienta kabinetfaila lielums 

  - **Data\_TriggeringUI —** kas aktivizēja UI 

  - **Data\_UpdatesEnabled —** ja Office atjauninājumi ir iespējoti 

  - **Data\_Version —** Office versija 

### <a name="officeclicktorunscenarioinstalltaskpublishrsod"></a>Office.ClickToRun.Scenario.InstallTaskPublishrsod

Office iestatīšanas un krājumu dati, kas tiek apkopoti, kad Office instalētājs publicē virtuālo reģistru AppV virtualizācijas slānim. Tiek izmantots, lai mērītu Office instalācijas sekmīgu/kļūdainu darbību.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_15\_SourceType —** kur Office 15 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_15\_UpdatesEnabled —** ja Office 15 atjauninājumi ir iespējoti 

  - **Data\_15\_UpdateVersion —** uz kādu Office 15 versiju veicam atjaunināšanu

  - **Data\_15\_Version —** Office 15 versija 

  - **Data\_16\_SourceType —** kur Office 16 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_16\_UpdatesEnabled —** ja Office 16 atjauninājumi ir iespējoti 

  - **Data\_16\_UpdateVersion —** uz kādu Office 16 versiju veicam atjaunināšanu 

  - **Data\_16\_Version —** Office 16 versija 

  - **Data\_AddingFixedProducts —** produkti, ko pievienojam 

  - **Data\_AddingProducts —** kādus produktus mums tiek lūgts pievienot 

  - **Data\_CompletionState —** vai pabeidzām uzdevumu

  - **Data\_ErrorCode —** kļūdas kods, ar kuru radās problēmas 

  - **Data\_ErrorDetails —** papildu detalizēta informācija par kļūdu 

  - **Data\_ErrorMessage —** kļūdas ziņojums par to, kāda problēma radās 

  - **Data\_ErrorSource —** kur kļūda radās

  - **Data\_ExceptionType —** izņēmums, ar kuru radās problēmas 

  - **Data\_IsErrorCodeIgnorable —** vai kļūdas kods, ar kuru radās problēmas, ir ignorējams 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth —** ja uzskatām, ka kļūdas kods ir ignorējams 

  - **Data\_NewestPackageVersion —** jaunākā Office versija datorā 

  - **Data\_OldestPackageVersion —** vecākā Office versija datorā 

  - **Data\_ProductsToAdd —** kādus Office produktus pievienojam 

  - **Data\_ProductsToRemove —** kādus Office produktus noņemam 

  - **Data\_RemovingFixedProducts —** produkti, ko noņemam 

  - **Data\_RemovingProducts —** produkti, kurus mums tiek lūgts noņemt 

  - **Data\_ScenarioInstanceID —** unikāls GUID darbības scenārijam 

  - **Data\_ScenarioName —** kāds scenārijs tiek izmantots, t.i., instalēšana 

  - **Data\_ScenarioSubType —** kāda veida scenāriju izmantojam, t.i., atinstalēšana, atkārtota instalēšana 

  - **Data\_SourceType —** kur ir mūsu avots, t.i., CDN 

  - **Data\_SqmMachineID —** unikālais datora ID, ko izmanto Windows SQM

  - **Data\_SusClientID —** datora Office atjaunināšanas identifikators 

  - **Data\_TaskState —** kādā stāvoklī ir uzdevums, piemēram, darbojas vai atcelts 

  - **Data\_TotalClientCabSize —** mūsu klienta kabinetfaila lielums 

  - **Data\_TriggeringUI —** kas aktivizēja UI 

  - **Data\_UpdatesEnabled —** ja Office atjauninājumi ir iespējoti 

  - **Data\_Version —** Office versija 

### <a name="officeclicktorunscenarioinstalltaskremoveinstallation"></a>Office.ClickToRun.Scenario.InstallTaskRemoveinstallation

Office iestatīšanas un krājumu dati, kas tiek apkopoti, kad Office atinstalētājs noņem Office daļas no ierīces. Tiek izmantots, lai mērītu Office instalācijas sekmīgu/kļūdainu darbību.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_15\_SourceType —** kur Office 15 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_15\_UpdatesEnabled —** ja Office 15 atjauninājumi ir iespējoti 

  - **Data\_15\_UpdateVersion —** uz kādu Office 15 versiju veicam atjaunināšanu 

  - **Data\_15\_Version —** Office 15 versija 

  - **Data\_16\_SourceType —** kur Office 16 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_16\_UpdatesEnabled —** ja Office 16 atjauninājumi ir iespējoti 

  - **Data\_16\_UpdateVersion —** uz kādu Office 16 versiju veicam atjaunināšanu 

  - **Data\_16\_Version —** Office 16 versija 

  - **Data\_AddingFixedProducts —** produkti, ko pievienojam 

  - **Data\_AddingProducts —** kādus produktus mums tiek lūgts pievienot 

  - **Data\_CompletionState —** vai pabeidzām uzdevumu

  - **Data\_ErrorCode —** kļūdas kods, ar kuru radās problēmas 

  - **Data\_ErrorDetails —** papildu detalizēta informācija par kļūdu 

  - **Data\_ErrorMessage —** kļūdas ziņojums par to, kāda problēma radās 

  - **Data\_ErrorSource —** kur kļūda radās 

  - **Data\_ExceptionType —** izņēmums, ar kuru radās problēmas 

  - **Data\_IsErrorCodeIgnorable —** vai kļūdas kods, ar kuru radās problēmas, ir ignorējams 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth —** ja uzskatām, ka kļūdas kods ir ignorējams 

  - **Data\_NewestPackageVersion —** jaunākā Office versija datorā 

  - **Data\_OldestPackageVersion —** vecākā Office versija datorā 

  - **Data\_ProductsToAdd —** kādus Office produktus pievienojam 

  - **Data\_ProductsToRemove —** kādus Office produktus noņemam 

  - **Data\_RemovingFixedProducts —** produkti, ko noņemam 

  - **Data\_RemovingProducts —** produkti, kurus mums tiek lūgts noņemt 

  - **Data\_ScenarioInstanceID —** unikāls GUID darbības scenārijam 

  - **Data\_ScenarioName —** kāds scenārijs tiek izmantots. t.i., instalēšana 

  - **Data\_ScenarioSubType —** kāda veida scenāriju izmantojam, t.i., atinstalēšana, atkārtota instalēšana 

  - **Data\_SourceType —** kur ir mūsu avots, t.i., CDN 

  - **Data\_SqmMachineID —** unikālais datora ID, ko izmanto Windows SQM

  - **Data\_SusClientID —** datora Office atjaunināšanas identifikators 

  - **Data\_TaskState —** kādā stāvoklī ir uzdevums, piemēram, darbojas vai atcelts 

  - **Data\_TotalClientCabSize —** mūsu klienta kabinetfaila lielums 

  - **Data\_TriggeringUI —** kas aktivizēja UI 

  - **Data\_UpdatesEnabled —** ja Office atjauninājumi ir iespējoti 

  - **Data\_Version —** Office versija 

### <a name="officeclicktorunscenarioinstalltaskstream"></a>Office.ClickToRun.Scenario.InstallTaskStream

Office iestatīšanas un krājumu dati, kas tiek apkopoti, kad Office instalētājs lejupielādē jaunus Office failus. Tiek izmantots, lai mērītu Office instalācijas sekmīgu/kļūdainu darbību.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_15\_SourceType —** kur Office 15 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_15\_UpdatesEnabled —** ja Office 15 atjauninājumi ir iespējoti 

  - **Data\_15\_UpdateVersion —** uz kādu Office 15 versiju veicam atjaunināšanu 

  - **Data\_15\_Version —** Office 15 versija 

  - **Data\_16\_SourceType —** kur Office 16 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_16\_UpdatesEnabled —** ja Office 16 atjauninājumi ir iespējoti 

  - **Data\_16\_UpdateVersion —** uz kādu Office 16 versiju veicam atjaunināšanu 

  - **Data\_16\_Version —** Office 16 versija 

  - **Data\_AddingFixedProducts —** produkti, ko pievienojam 

  - **Data\_AddingProducts —** kādus produktus mums tiek lūgts pievienot 

  - **Data\_CompletionState —** vai pabeidzām uzdevumu

  - **Data\_ErrorCode —** kļūdas kods, ar kuru radās problēmas 

  - **Data\_ErrorDetails —** papildu detalizēta informācija par kļūdu 

  - **Data\_ErrorMessage —** kļūdas ziņojums par to, kāda problēma radās 

  - **Data\_ErrorSource —** kur kļūda radās 

  - **Data\_ExceptionType —** izņēmums, ar kuru radās problēmas 

  - **Data\_IsErrorCodeIgnorable —** vai kļūdas kods, ar kuru radās problēmas, ir ignorējams 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth —** ja uzskatām, ka kļūdas kods ir ignorējams 

  - **Data\_NewestPackageVersion —** jaunākā Office versija datorā 

  - **Data\_OldestPackageVersion —** vecākā Office versija datorā 

  - **Data\_ProductsToAdd —** kādus Office produktus pievienojam 

  - **Data\_ProductsToRemove —** kādus Office produktus noņemam 

  - **Data\_RemovingFixedProducts —** produkti, ko noņemam 

  - **Data\_RemovingProducts —** produkti, kurus mums tiek lūgts noņemt 

  - **Data\_ScenarioInstanceID —** unikāls GUID darbības scenārijam 

  - **Data\_ScenarioName —** kāds scenārijs tiek izmantots. t.i., instalēšana 

  - **Data\_ScenarioSubType —** kāda veida scenāriju izmantojam, t.i., atinstalēšana, atkārtota instalēšana 

  - **Data\_SourceType —** kur ir mūsu avots, t.i., CDN 

  - **Data\_SqmMachineID —** unikālais datora ID, ko izmanto Windows SQM 

  - **Data\_SusClientID —** datora Office atjaunināšanas identifikators 

  - **Data\_TaskState —** kādā stāvoklī ir uzdevums, piemēram, darbojas vai atcelts 

  - **Data\_TotalClientCabSize —** mūsu klienta kabinetfaila lielums 

  - **Data\_TriggeringUI —** kas aktivizēja UI 

  - **Data\_UpdatesEnabled —** ja Office atjauninājumi ir iespējoti 

  - **Data\_Version —** Office versija 

### <a name="officeclicktorunscenarioinstalltaskuninstallcentennial"></a>Office.ClickToRun.Scenario.InstallTaskUninstallcentennial

Office iestatīšanas un krājumu dati, kas tiek apkopoti, kad Office instalētājs atinstalē iepriekšējo Office versiju, kas instalēta no Microsoft Store. Tiek izmantots, lai mērītu Office instalācijas sekmīgu/kļūdainu darbību.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_15\_SourceType —** kur Office 15 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_15\_UpdatesEnabled —** ja Office 15 atjauninājumi ir iespējoti 

  - **Data\_15\_UpdateVersion —** uz kādu Office 15 versiju veicam atjaunināšanu 

  - **Data\_15\_Version —** Office 15 versija 

  - **Data\_16\_SourceType —** kur Office 16 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_16\_UpdatesEnabled —** ja Office 16 atjauninājumi ir iespējoti 

  - **Data\_16\_UpdateVersion —** uz kādu Office 16 versiju veicam atjaunināšanu 

  - **Data\_16\_Version —** Office 16 versija 

  - **Data\_AddingFixedProducts —** produkti, ko pievienojam 

  - **Data\_AddingProducts —** kādus produktus mums tiek lūgts pievienot 

  - **Data\_CompletionState —** vai pabeidzām uzdevumu

  - **Data\_ErrorCode —** kļūdas kods, ar kuru radās problēmas 

  - **Data\_ErrorDetails —** papildu detalizēta informācija par kļūdu 

  - **Data\_ErrorMessage —** kļūdas ziņojums par to, kāda problēma radās 

  - **Data\_ErrorSource —** kur kļūda radās 

  - **Data\_ExceptionType —** izņēmums, ar kuru radās problēmas 

  - **Data\_IsErrorCodeIgnorable —** vai kļūdas kods, ar kuru radās problēmas, ir ignorējams 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth —** ja uzskatām, ka kļūdas kods ir ignorējams 

  - **Data\_NewestPackageVersion —** jaunākā Office versija datorā 

  - **Data\_OldestPackageVersion —** vecākā Office versija datorā 

  - **Data\_ProductsToAdd —** kādus Office produktus pievienojam 

  - **Data\_ProductsToRemove —** kādus Office produktus noņemam 

  - **Data\_RemovingFixedProducts —** produkti, ko noņemam 

  - **Data\_RemovingProducts —** produkti, kurus mums tiek lūgts noņemt 

  - **Data\_ScenarioInstanceID —** unikāls GUID darbības scenārijam 

  - **Data\_ScenarioName —** kāds scenārijs tiek izmantots. t.i., instalēšana 

  - **Data\_ScenarioSubType —** kāda veida scenāriju izmantojam, t.i., atinstalēšana, atkārtota instalēšana 

  - **Data\_SourceType —** kur ir mūsu avots, t.i., CDN 

  - **Data\_SqmMachineID —** unikālais datora ID, ko izmanto Windows SQM

  - **Data\_SusClientID —** datora Office atjaunināšanas identifikators 

  - **Data\_TaskState —** kādā stāvoklī ir uzdevums, piemēram, darbojas vai atcelts 

  - **Data\_TotalClientCabSize —** mūsu klienta kabinetfaila lielums 

  - **Data\_TriggeringUI —** kas aktivizēja UI 

  - **Data\_UpdatesEnabled —** ja Office atjauninājumi ir iespējoti 

  - **Data\_Version —** Office versija 

### <a name="officeclicktorunscenariorepairtaskfinalintegrate"></a>Office.ClickToRun.Scenario.RepairTaskFinalintegrate

Office iestatīšanas un krājumu dati, kas apkopoti, kad Office labošanas klients atkārtoti publicē .msi failus un Office paplašinājumus. Tiek izmantots, lai mērītu Office labošanas sekmīgu/kļūdainu darbību.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_15\_SourceType —** kur Office 15 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_15\_UpdatesEnabled —** ja Office 15 atjauninājumi ir iespējoti 

  - **Data\_15\_UpdateVersion —** uz kādu Office 15 versiju veicam atjaunināšanu 

  - **Data\_15\_Version —** Office 15 versija 

  - **Data\_16\_SourceType —** kur Office 16 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_16\_UpdatesEnabled —** ja Office 16 atjauninājumi ir iespējoti 

  - **Data\_16\_UpdateVersion —** uz kādu Office 16 versiju veicam atjaunināšanu 

  - **Data\_16\_Version —** Office 16 versija 

  - **Data\_AddingFixedProducts —** produkti, ko pievienojam 

  - **Data\_AddingProducts —** kādus produktus mums tiek lūgts pievienot 

  - **Data\_CompletionState —** vai pabeidzām uzdevumu

  - **Data\_ErrorCode —** kļūdas kods, ar kuru radās problēmas 

  - **Data\_ErrorDetails —** papildu detalizēta informācija par kļūdu 

  - **Data\_ErrorMessage —** kļūdas ziņojums par to, kāda problēma radās 

  - **Data\_ErrorSource —** kur kļūda radās 

  - **Data\_ExceptionType —** izņēmums, ar kuru radās problēmas 

  - **Data\_IsErrorCodeIgnorable —** vai kļūdas kods, ar kuru radās problēmas, ir ignorējams 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth —** ja uzskatām, ka kļūdas kodu var ignorēt 

  - **Data\_NewestPackageVersion —** jaunākā Office versija datorā 

  - **Data\_OldestPackageVersion —** vecākā Office versija datorā 

  - **Data\_ProductsToAdd —** kādus Office produktus pievienojam 

  - **Data\_ProductsToRemove —** kādus Office produktus noņemam 

  - **Data\_RemovingFixedProducts —** produkti, ko noņemam 

  - **Data\_RemovingProducts —** produkti, kurus mums tiek lūgts noņemt 

  - **Data\_ScenarioInstanceID —** unikāls GUID darbības scenārijam 

  - **Data\_ScenarioName —** kāds scenārijs tiek izmantots. t.i., instalēšana 

  - **Data\_ScenarioSubType —** kāda veida scenāriju izmantojam, t.i., atinstalēšana, atkārtota instalēšana 

  - **Data\_SourceType —** kur ir mūsu avots, t.i., CDN 

  - **Data\_SqmMachineID —** unikālais datora ID, ko izmanto Windows SQM 

  - **Data\_SusClientID —** datora Office atjaunināšanas identifikators 

  - **Data\_TaskState —** kādā stāvoklī ir uzdevums, piemēram, darbojas vai atcelts 

  - **Data\_TotalClientCabSize —** mūsu klienta kabinetfaila lielums 

  - **Data\_TriggeringUI —** kas aktivizēja UI 

  - **Data\_UpdatesEnabled —** ja Office atjauninājumi ir iespējoti 

  - **Data\_Version —** Office versija 

### <a name="officeclicktorunscenariorepairtaskfullrepair"></a>Office.ClickToRun.Scenario.RepairTaskFullrepair

Office iestatīšanas un krājumu dati, kas tiek apkopoti, kad Office labošanas klients lejupielādē visjaunāko Click-to-Run klienta versiju, lai sagatavotu datoru atinstalēšanai un atkārtotai instalēšanai. Tiek izmantots, lai mērītu Office labošanas sekmīgu/kļūdainu darbību.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_15\_SourceType —** kur Office 15 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_15\_UpdatesEnabled —** ja Office 15 atjauninājumi ir iespējoti 

  - **Data\_15\_UpdateVersion —** uz kādu Office 15 versiju veicam atjaunināšanu 

  - **Data\_15\_Version —** Office 15 versija 

  - **Data\_16\_SourceType —** kur Office 16 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_16\_UpdatesEnabled —** ja Office 16 atjauninājumi ir iespējoti 

  - **Data\_16\_UpdateVersion —** uz kādu Office 16 versiju veicam atjaunināšanu 

  - **Data\_16\_Version —** Office 16 versija 

  - **Data\_AddingFixedProducts —** produkti, ko pievienojam 

  - **Data\_AddingProducts —** kādus produktus mums tiek lūgts pievienot 

  - **Data\_CompletionState —** vai pabeidzām uzdevumu

  - **Data\_ErrorCode —** kļūdas kods, ar kuru radās problēmas 

  - **Data\_ErrorDetails —** papildu detalizēta informācija par kļūdu 

  - **Data\_ErrorMessage —** kļūdas ziņojums par to, kāda problēma radās 

  - **Data\_ErrorSource —** kur kļūda radās 

  - **Data\_ExceptionType —** izņēmums, ar kuru radās problēmas 

  - **Data\_IsErrorCodeIgnorable —** vai kļūdas kods, ar kuru radās problēmas, ir ignorējams 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth —** ja uzskatām, ka kļūdas kods ir ignorējams 

  - **Data\_NewestPackageVersion —** jaunākā Office versija datorā 

  - **Data\_OldestPackageVersion —** vecākā Office versija datorā 

  - **Data\_ProductsToAdd —** kādus Office produktus pievienojam 

  - **Data\_ProductsToRemove —** kādus Office produktus noņemam 

  - **Data\_RemovingFixedProducts —** produkti, ko noņemam 

  - **Data\_RemovingProducts —** produkti, kurus mums tiek lūgts noņemt 

  - **Data\_ScenarioInstanceID —** unikāls GUID darbības scenārijam 

  - **Data\_ScenarioName —** kāds scenārijs tiek izmantots. t.i., instalēšana 

  - **Data\_ScenarioSubType —** kāda veida scenāriju izmantojam, t.i., atinstalēšana, atkārtota instalēšana 

  - **Data\_SourceType —** kur ir mūsu avots, t.i., CDN 

  - **Data\_SqmMachineID —** unikālais datora ID, ko izmanto Windows SQM 

  - **Data\_SusClientID —** datora Office atjaunināšanas identifikators 

  - **Data\_TaskState —** kādā stāvoklī ir uzdevums, piemēram, darbojas vai atcelts 

  - **Data\_TotalClientCabSize —** mūsu klienta kabinetfaila lielums 

  - **Data\_TriggeringUI —** kas aktivizēja UI 

  - **Data\_UpdatesEnabled —** ja Office atjauninājumi ir iespējoti 

  - **Data\_Version —** Office versija 

### <a name="officeclicktorunscenariorepairtaskintegraterepair"></a>Office.ClickToRun.Scenario.RepairTaskIntegraterepair

Office iestatīšanas un krājumu dati, kas tiek apkopoti, kad Office labošanas klients mēģina labot dažus zināmus problemātiskos reģistra ierakstus. Tiek izmantots, lai mērītu Office labošanas sekmīgu/kļūdainu darbību.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_15\_SourceType —** kur Office 15 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_15\_UpdatesEnabled —** ja Office 15 atjauninājumi ir iespējoti 

  - **Data\_15\_UpdateVersion —** uz kādu Office 15 versiju veicam atjaunināšanu 

  - **Data\_15\_Version —** Office 15 versija 

  - **Data\_16\_SourceType —** kur Office 16 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_16\_UpdatesEnabled —** ja Office 16 atjauninājumi ir iespējoti 

  - **Data\_16\_UpdateVersion —** uz kādu Office 16 versiju veicam atjaunināšanu 

  - **Data\_16\_Version —** Office 16 versija 

  - **Data\_AddingFixedProducts —** produkti, ko pievienojam 

  - **Data\_AddingProducts —** kādus produktus mums tiek lūgts pievienot 

  - **Data\_CompletionState —** vai pabeidzām uzdevumu

  - **Data\_ErrorCode —** kļūdas kods, ar kuru radās problēmas 

  - **Data\_ErrorDetails —** papildu detalizēta informācija par kļūdu 

  - **Data\_ErrorMessage —** kļūdas ziņojums par to, kāda problēma radās 

  - **Data\_ErrorSource —** kur kļūda radās 

  - **Data\_ExceptionType —** izņēmums, ar kuru radās problēmas 

  - **Data\_IsErrorCodeIgnorable —** vai kļūdas kods, ar kuru radās problēmas, ir ignorējams 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth —** ja uzskatām, ka kļūdas kodu var ignorēt 

  - **Data\_NewestPackageVersion —** jaunākā Office versija datorā 

  - **Data\_OldestPackageVersion —** vecākā Office versija datorā 

  - **Data\_ProductsToAdd —** kādus Office produktus pievienojam 

  - **Data\_ProductsToRemove —** kādus Office produktus noņemam 

  - **Data\_RemovingFixedProducts —** produkti, ko noņemam 

  - **Data\_RemovingProducts —** produkti, kurus mums tiek lūgts noņemt 

  - **Data\_ScenarioInstanceID —** unikāls GUID darbības scenārijam 

  - **Data\_ScenarioName —** kāds scenārijs tiek izmantots. t.i., instalēšana 

  - **Data\_ScenarioSubType —** kāda veida scenāriju izmantojam, t.i., atinstalēšana, atkārtota instalēšana 

  - **Data\_SourceType —** kur ir mūsu avots, t.i., CDN 

  - **Data\_SqmMachineID —** unikālais datora ID, ko izmanto Windows SQM 

  - **Data\_SusClientID —** datora Office atjaunināšanas identifikators 

  - **Data\_TaskState —** kādā stāvoklī ir uzdevums, piemēram, darbojas vai atcelts 

  - **Data\_TotalClientCabSize —** mūsu klienta kabinetfaila lielums 

  - **Data\_TriggeringUI —** kas aktivizēja UI 

  - **Data\_UpdatesEnabled —** ja Office atjauninājumi ir iespējoti 

  - **Data\_Version —** Office versija 

### <a name="officeclicktorunscenariorepairtaskremoveinstallation"></a>Office.ClickToRun.Scenario.RepairTaskRemoveinstallation

Office iestatīšanas un krājumu dati, kas tiek apkopoti, kad Office labošanas klients noņem Office no ierīces, sagatavotos atkārtotai instalēšanai, veicot labošanu. Tiek izmantots, lai mērītu Office labošanas sekmīgu/kļūdainu darbību.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_15\_SourceType —** kur Office 15 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_15\_UpdatesEnabled —** ja Office 15 atjauninājumi ir iespējoti 

  - **Data\_15\_UpdateVersion —** uz kādu Office 15 versiju veicam atjaunināšanu 

  - **Data\_15\_Version —** Office 15 versija 

  - **Data\_16\_SourceType —** kur Office 16 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_16\_UpdatesEnabled —** ja Office 16 atjauninājumi ir iespējoti 

  - **Data\_16\_UpdateVersion —** uz kādu Office 16 versiju veicam atjaunināšanu 

  - **Data\_16\_Version —** Office 16 versija 

  - **Data\_AddingFixedProducts —** produkti, ko pievienojam 

  - **Data\_AddingProducts —** kādus produktus mums tiek lūgts pievienot 

  - **Data\_CompletionState —** vai pabeidzām uzdevumu

  - **Data\_ErrorCode —** kļūdas kods, ar kuru radās problēmas 

  - **Data\_ErrorDetails —** papildu detalizēta informācija par kļūdu 

  - **Data\_ErrorMessage —** kļūdas ziņojums par to, kāda problēma radās 

  - **Data\_ErrorSource —** kur kļūda radās 

  - **Data\_ExceptionType —** izņēmums, ar kuru radās problēmas 

  - **Data\_IsErrorCodeIgnorable —** vai kļūdas kods, ar kuru radās problēmas, ir ignorējams 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth —** ja uzskatām, ka kļūdas kods ir ignorējams 

  - **Data\_NewestPackageVersion —** jaunākā Office versija datorā 

  - **Data\_OldestPackageVersion —** vecākā Office versija datorā 

  - **Data\_ProductsToAdd —** kādus Office produktus pievienojam 

  - **Data\_ProductsToRemove —** kādus Office produktus noņemam 

  - **Data\_RemovingFixedProducts —** produkti, ko noņemam 

  - **Data\_RemovingProducts —** produkti, kurus mums tiek lūgts noņemt 

  - **Data\_ScenarioInstanceID —** unikāls GUID darbības scenārijam 

  - **Data\_ScenarioName —** kāds scenārijs tiek izmantots. t.i., instalēšana 

  - **Data\_ScenarioSubType —** kāda veida scenāriju izmantojam, t.i., atinstalēšana, atkārtota instalēšana 

  - **Data\_SourceType —** kur ir mūsu avots, t.i., CDN 

  - **Data\_SqmMachineID —** unikālais datora ID, ko izmanto Windows SQM 

  - **Data\_SusClientID —** datora Office atjaunināšanas identifikators 

  - **Data\_TaskState —** kādā stāvoklī ir uzdevums, piemēram, darbojas vai atcelts 

  - **Data\_TotalClientCabSize —** mūsu klienta kabinetfaila lielums 

  - **Data\_TriggeringUI —** kas aktivizēja UI 

  - **Data\_UpdatesEnabled —** ja Office atjauninājumi ir iespējoti 

  - **Data\_Version —** Office versija 

### <a name="officeclicktorunscenarioupdatetaskintegrateupdate"></a>Office.ClickToRun.Scenario.UpdateTaskIntegrateupdate 

Office iestatīšanas un krājumu dati, kas tiek apkopoti, kad Click-to-Run klients atjaunina licences, ja nepieciešams. Tiek izmantots, lai mērītu Office atjaunināšanas sekmīgu/kļūdainu darbību.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_15\_SourceType —** kur Office 15 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_15\_UpdatesEnabled —** ja Office 15 atjauninājumi ir iespējoti 

  - **Data\_15\_UpdateVersion —** uz kādu Office 15 versiju veicam atjaunināšanu 

  - **Data\_15\_Version —** Office 15 versija 

  - **Data\_16\_SourceType —** kur Office 16 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_16\_UpdatesEnabled —** ja Office 16 atjauninājumi ir iespējoti 

  - **Data\_16\_UpdateVersion —** uz kādu Office 16 versiju veicam atjaunināšanu 

  - **Data\_16\_Version —** Office 16 versija 

  - **Data\_AddingFixedProducts —** produkti, ko pievienojam 

  - **Data\_AddingProducts —** kādus produktus mums tiek lūgts pievienot 

  - **Data\_CompletionState —** vai pabeidzām uzdevumu

  - **Data\_ErrorCode —** kļūdas kods, ar kuru radās problēmas 

  - **Data\_ErrorDetails —** papildu detalizēta informācija par kļūdu 

  - **Data\_ErrorMessage —** kļūdas ziņojums par to, kāda problēma radās 

  - **Data\_ErrorSource —** kur kļūda radās 

  - **Data\_ExceptionType —** izņēmums, ar kuru radās problēmas 

  - **Data\_IsErrorCodeIgnorable —** vai kļūdas kods, ar kuru radās problēmas, ir ignorējams 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth —** ja uzskatām, ka kļūdas kods ir ignorējams 

  - **Data\_NewestPackageVersion —** jaunākā Office versija datorā 

  - **Data\_OldestPackageVersion —** vecākā Office versija datorā 

  - **Data\_ProductsToAdd —** kādus Office produktus pievienojam 

  - **Data\_ProductsToRemove —** kādus Office produktus noņemam 

  - **Data\_RemovingFixedProducts —** produkti, ko noņemam 

  - **Data\_RemovingProducts —** produkti, kurus mums tiek lūgts noņemt 

  - **Data\_ScenarioInstanceID —** unikāls GUID darbības scenārijam 

  - **Data\_ScenarioName —** kāds scenārijs tiek izmantots. t.i., instalēšana 

  - **Data\_ScenarioSubType —** kāda veida scenāriju izmantojam, t.i., atinstalēšana, atkārtota instalēšana 

  - **Data\_SourceType —** kur ir mūsu avots, t.i., CDN 

  - **Data\_SqmMachineID —** unikālais datora ID, ko izmanto Windows SQM 

  - **Data\_SusClientID —** datora Office atjaunināšanas identifikators 

  - **Data\_TaskState —** kādā stāvoklī ir uzdevums, piemēram, darbojas vai atcelts 

  - **Data\_TotalClientCabSize —** mūsu klienta kabinetfaila lielums 

  - **Data\_TriggeringUI —** kas aktivizēja UI 

  - **Data\_UpdatesEnabled —** ja Office atjauninājumi ir iespējoti 

  - **Data\_Version —** Office versija 

### <a name="officeclicktorunscenarioupdatetaskpublishrsod"></a>Office.ClickToRun.Scenario.UpdateTaskPublishrsod

Office iestatīšana un krājumi, kas tiek apkopoti, kad Click-to-Run klients atjaunina reģistra iestatījumus jaunajiem binārajiem failiem. Tiek izmantots, lai mērītu Office atjaunināšanas sekmīgu/kļūdainu darbību.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_15\_SourceType —** kur Office 15 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_15\_UpdatesEnabled —** ja Office 15 atjauninājumi ir iespējoti 

  - **Data\_15\_UpdateVersion —** uz kādu Office 15 versiju veicam atjaunināšanu 

  - **Data\_15\_Version —** Office 15 versija 

  - **Data\_16\_SourceType —** kur Office 16 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_16\_UpdatesEnabled —** ja Office 16 atjauninājumi ir iespējoti 

  - **Data\_16\_UpdateVersion —** uz kādu Office 16 versiju veicam atjaunināšanu 

  - **Data\_16\_Version —** Office 16 versija 

  - **Data\_AddingFixedProducts —** produkti, ko pievienojam 

  - **Data\_AddingProducts —** kādus produktus mums tiek lūgts pievienot 

  - **Data\_CompletionState —** vai pabeidzām uzdevumu

  - **Data\_ErrorCode —** kļūdas kods, ar kuru radās problēmas 

  - **Data\_ErrorDetails —** papildu detalizēta informācija par kļūdu 

  - **Data\_ErrorMessage —** kļūdas ziņojums par to, kāda problēma radās 

  - **Data\_ErrorSource —** kur kļūda radās 

  - **Data\_ExceptionType —** izņēmums, ar kuru radās problēmas 

  - **Data\_IsErrorCodeIgnorable —** vai kļūdas kods, ar kuru radās problēmas, ir ignorējams 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth —** ja uzskatām, ka kļūdas kods ir ignorējams 

  - **Data\_NewestPackageVersion —** jaunākā Office versija datorā 

  - **Data\_OldestPackageVersion —** vecākā Office versija datorā 

  - **Data\_ProductsToAdd —** kādus Office produktus pievienojam 

  - **Data\_ProductsToRemove —** kādus Office produktus noņemam 

  - **Data\_RemovingFixedProducts —** produkti, ko noņemam 

  - **Data\_RemovingProducts —** produkti, kurus mums tiek lūgts noņemt 

  - **Data\_ScenarioInstanceID —** unikāls GUID darbības scenārijam 

  - **Data\_ScenarioName —** kāds scenārijs tiek izmantots. t.i., instalēšana 

  - **Data\_ScenarioSubType —** kāda veida scenāriju izmantojam, t.i., atinstalēšana, atkārtota instalēšana 

  - **Data\_SourceType —** kur ir mūsu avots, t.i., CDN 

  - **Data\_SqmMachineID —** unikālais datora ID, ko izmanto Windows SQM 

  - **Data\_SusClientID —** datora Office atjaunināšanas identifikators 

  - **Data\_TaskState —** kādā stāvoklī ir uzdevums, piemēram, darbojas vai atcelts 

  - **Data\_TotalClientCabSize —** mūsu klienta kabinetfaila lielums 

  - **Data\_TriggeringUI —** kas aktivizēja UI 

  - **Data\_UpdatesEnabled —** ja Office atjauninājumi ir iespējoti 

  - **Data\_Version —** Office versija 

### <a name="officeclicktorunscenarioupdatetaskupdateapply"></a>Office.ClickToRun.Scenario.UpdateTaskUpdateapply

Office iestatīšanas un krājumu dati, kas tiek apkopoti, kad Click-to-Run klients izslēdz palaistās lietojumprogrammas, ja nepieciešams, un instalē jaunos failus, kas tika lejupielādēti. Tiek izmantots, lai mērītu Office atjaunināšanas sekmīgu/kļūdainu darbību.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_15\_SourceType —** kur Office 15 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_15\_UpdatesEnabled —** ja Office 15 atjauninājumi ir iespējoti 

  - **Data\_15\_UpdateVersion —** uz kādu Office 15 versiju veicam atjaunināšanu 

  - **Data\_15\_Version —** Office 15 versija 

  - **Data\_16\_SourceType —** kur Office 16 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_16\_UpdatesEnabled —** ja Office 16 atjauninājumi ir iespējoti 

  - **Data\_16\_UpdateVersion —** uz kādu Office 16 versiju veicam atjaunināšanu 

  - **Data\_16\_Version —** Office 16 versija 

  - **Data\_AddingFixedProducts —** produkti, ko pievienojam 

  - **Data\_AddingProducts —** kādus produktus mums tiek lūgts pievienot 

  - **Data\_AvailableVersion to —** kāda Office versija ir pieejama atjaunināšanai

  - **Data\_CompletedWithoutActionInfo —** kāpēc nepabeidzām scenāriju, piem., lietojumprogrammas bija atvērtas

  - **Data\_CompletionState —** vai pabeidzām uzdevumu

  - **Data\_CorruptionChecksOnly —** vai tikai meklējam bojājumus un neveicam atjaunināšanu

  - **Data\_ErrorCode —** kļūdas kods, ar kuru radās problēmas 

  - **Data\_ErrorDetails —** papildu detalizēta informācija par kļūdu 

  - **Data\_ErrorMessage —** kļūdas ziņojums par to, kāda problēma radās 

  - **Data\_ErrorSource —** kur kļūda radās

  - **Data\_ExceptionType —** izņēmums, ar kuru radās problēmas 

  - **Data\_HardlinkingException —** izņēmums, kas radās, mēģinot izveidot stingrās saites

  - **Data\_IsErrorCodeIgnorable —** vai kļūdas kods, ar kuru radās problēmas, ir ignorējams 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth —** ja uzskatām, ka kļūdas kods ir ignorējams 

  - **Data\_NewestPackageVersion —** jaunākā Office versija datorā 

  - **Data\_OldestPackageVersion —** vecākā Office versija datorā 

  - **Data\_PackageOperationSuccessful —** patiess, ja sekmīgi veicām savu uzdevumu ar Office pakotni

  - **Data\_ProductsToAdd —** kādus Office produktus pievienojam 

  - **Data\_ProductsToRemove —** kādus Office produktus noņemam 

  - **Data\_RemovingFixedProducts —** produkti, ko noņemam 

  - **Data\_RemovingProducts —** produkti, kurus mums tiek lūgts noņemt 

  - **Data\_ScenarioInstanceID —** unikāls GUID darbības scenārijam 

  - **Data\_ScenarioName —** kāds scenārijs tiek izmantots. t.i., instalēšana 

  - **Data\_ScenarioSubType —** kāda veida scenāriju izmantojam, t.i., atinstalēšana, atkārtota instalēšana 

  - **Data\_SourceType —** kur ir mūsu avots, t.i., CDN 

  - **Data\_SqmMachineID —** unikālais datora ID, ko izmanto Windows SQM

  - **Data\_SusClientID —** datora Office atjaunināšanas identifikators 

  - **Data\_TaskState —** kādā stāvoklī ir uzdevums, piemēram, darbojas vai atcelts 

  - **Data\_TotalClientCabSize —** mūsu klienta kabinetfaila lielums 

  - **Data\_TriggeringUI —** kas aktivizēja UI 

  - **Data\_UpdatesEnabled —** ja Office atjauninājumi ir iespējoti 

  - **Data\_Version —** Office versija 

  - **Data\_WorkstationLockState —** patiess, ja uzskatām, ka dators ir bloķēts

### <a name="officeclicktorunscenarioupdatetaskupdateclientdownload"></a>Office.ClickToRun.Scenario.UpdateTaskUpdateclientdownload

Office iestatīšanas un krājumu dati, kas tiek apkopoti, kad Click-to-Run klients lejupielādē jaunāku savu versiju. Tiek izmantots, lai mērītu Office atjaunināšanas sekmīgu/kļūdainu darbību.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_15\_SourceType —** kur Office 15 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_15\_UpdatesEnabled —** ja Office 15 atjauninājumi ir iespējoti 

  - **Data\_15\_UpdateVersion —** uz kādu Office 15 versiju veicam atjaunināšanu 

  - **Data\_15\_Version —** Office 15 versija 

  - **Data\_16\_SourceType —** kur Office 16 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_16\_UpdatesEnabled —** ja Office 16 atjauninājumi ir iespējoti 

  - **Data\_16\_UpdateVersion —** uz kādu Office 16 versiju veicam atjaunināšanu 

  - **Data\_16\_Version —** Office 16 versija 

  - **Data\_AddingFixedProducts —** produkti, ko pievienojam 

  - **Data\_AddingProducts —** kādus produktus mums tiek lūgts pievienot 

  - **Data\_CompletionState —** vai pabeidzām uzdevumu

  - **Data\_ErrorCode —** kļūdas kods, ar kuru radās problēmas 

  - **Data\_ErrorDetails —** papildu detalizēta informācija par kļūdu 

  - **Data\_ErrorMessage —** kļūdas ziņojums par to, kāda problēma radās 

  - **Data\_ErrorSource —** kur kļūda radās 

  - **Data\_ExceptionType —** izņēmums, ar kuru radās problēmas 

  - **Data\_IsErrorCodeIgnorable —** vai kļūdas kods, ar kuru radās problēmas, ir ignorējams 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth —** ja uzskatām, ka kļūdas kods ir ignorējams 

  - **Data\_NewestPackageVersion —** jaunākā Office versija datorā 

  - **Data\_OldestPackageVersion —** vecākā Office versija datorā 

  - **Data\_ProductsToAdd —** kādus Office produktus pievienojam 

  - **Data\_ProductsToRemove —** kādus Office produktus noņemam 

  - **Data\_RemovingFixedProducts —** produkti, ko noņemam 

  - **Data\_RemovingProducts —** produkti, kurus mums tiek lūgts noņemt 

  - **Data\_ScenarioInstanceID —** unikāls GUID darbības scenārijam 

  - **Data\_ScenarioName —** kāds scenārijs tiek izmantots. t.i., instalēšana 

  - **Data\_ScenarioSubType —** kāda veida scenāriju izmantojam, t.i., atinstalēšana, atkārtota instalēšana 

  - **Data\_SourceType —** kur ir mūsu avots, t.i., CDN 

  - **Data\_SqmMachineID —** unikālais datora ID, ko izmanto Windows SQM

  - **Data\_SusClientID —** datora Office atjaunināšanas identifikators 

  - **Data\_TaskState —** kādā stāvoklī ir uzdevums, piemēram, darbojas vai atcelts 

  - **Data\_TotalClientCabSize —** mūsu klienta kabinetfaila lielums 

  - **Data\_TriggeringUI —** kas aktivizēja UI 

  - **Data\_UpdatesEnabled —** ja Office atjauninājumi ir iespējoti 

  - **Data\_Version —** Office versija 

### <a name="officeclicktorunscenarioupdatetaskupdatedetection"></a>Office.ClickToRun.Scenario.UpdateTaskUpdatedetection

Office iestatīšanas un krājumu dati, kas tiek apkopoti, kad Click-to-Run klients pārbauda, vai ir pieejams jauns atjauninājums. Tiek izmantots, lai mērītu Office atjaunināšanas sekmīgu/kļūdainu darbību.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_15\_SourceType —** kur Office 15 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_15\_UpdatesEnabled —** ja Office 15 atjauninājumi ir iespējoti 

  - **Data\_15\_UpdateVersion —** uz kādu Office 15 versiju veicam atjaunināšanu 

  - **Data\_15\_Version —** Office 15 versija 

  - **Data\_16\_SourceType —** kur Office 16 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_16\_UpdatesEnabled —** ja Office 16 atjauninājumi ir iespējoti 

  - **Data\_16\_UpdateVersion —** uz kādu Office 16 versiju veicam atjaunināšanu 

  - **Data\_16\_Version —** Office 16 versija 

  - **Data\_AddingFixedProducts —** produkti, ko pievienojam 

  - **Data\_AddingProducts —** kādus produktus mums tiek lūgts pievienot 

  - **Data\_AvailableVersion —** uz kādu Office versiju ir pieejams atjauninājums

  - **Data\_ComAction —** int, kas atspoguļo com darbību, ko veicam

  - **Data\_CompletedWithoutActionInfo —** kāpēc nepabeidzām scenāriju, piem., lietojumprogrammas bija atvērtas

  - **Data\_CompletionState —** vai pabeidzām uzdevumu

  - **Data\_ErrorCode —** kļūdas kods, ar kuru radās problēmas 

  - **Data\_ErrorDetails —** papildu detalizēta informācija par kļūdu 

  - **Data\_ErrorMessage —** kļūdas ziņojums par to, kāda problēma radās 

  - **Data\_ErrorSource —** kur kļūda radās

  - **Data\_ExceptionType —** izņēmums, ar kuru radās problēmas 

  - **Data\_IsErrorCodeIgnorable —** vai kļūdas kods, ar kuru radās problēmas, ir ignorējams 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth —** ja uzskatām, ka kļūdas kods ir ignorējams 

  - **Data\_NewestPackageVersion —** jaunākā Office versija datorā 

  - **Data\_OldestPackageVersion —** vecākā Office versija datorā 

  - **Data\_PackageUpdateAvailable —** patiess, ja ir pieejama jauna Office versija

  - **Data\_ProductsToAdd —** kādus Office produktus pievienojam 

  - **Data\_ProductsToRemove —** kādus Office produktus noņemam 

  - **Data\_RemovingFixedProducts —** produkti, ko noņemam 

  - **Data\_RemovingProducts —** produkti, kurus mums tiek lūgts noņemt 

  - **Data\_ScenarioInstanceID —** unikāls GUID darbības scenārijam 

  - **Data\_ScenarioName —** kāds scenārijs tiek izmantots. t.i., instalēšana

  - **Data\_ScenarioSubType —** kāda veida scenāriju izmantojam, t.i., atinstalēšana, atkārtota instalēšana 

  - **Data\_SourceType —** kur ir mūsu avots, t.i., CDN 

  - **Data\_SqmMachineID —** unikālais datora ID, ko izmanto Windows SQM 

  - **Data\_SusClientID —** datora Office atjaunināšanas identifikators 

  - **Data\_TaskState —** kādā stāvoklī ir uzdevums, piemēram, darbojas vai atcelts 

  - **Data\_TotalClientCabSize —** mūsu klienta kabinetfaila lielums 

  - **Data\_TriggeringUI —** kas aktivizēja UI 

  - **Data\_UpdatesEnabled —** ja Office atjauninājumi ir iespējoti 

  - **Data\_Version —** Office versija 

### <a name="officeclicktorunscenarioupdatetaskupdatedownload"></a>Office.ClickToRun.Scenario.UpdateTaskUpdatedownload

Office iestatīšanas un krājumu dati, kas tiek apkopoti, kad Click-to-Run klients lejupielādē jaunu atjauninājumu. Tiek izmantots, lai mērītu Office atjaunināšanas sekmīgu/kļūdainu darbību.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_15\_SourceType —** kur Office 15 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_15\_UpdatesEnabled —** ja Office 15 atjauninājumi ir iespējoti 

  - **Data\_15\_UpdateVersion —** uz kādu Office 15 versiju veicam atjaunināšanu 

  - **Data\_15\_Version —** Office 15 versija 

  - **Data\_16\_SourceType —** kur Office 16 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_16\_UpdatesEnabled —** ja Office 16 atjauninājumi ir iespējoti 

  - **Data\_16\_UpdateVersion —** uz kādu Office 16 versiju veicam atjaunināšanu 

  - **Data\_16\_Version —** Office 16 versija 

  - **Data\_AddingFixedProducts —** produkti, ko pievienojam 

  - **Data\_AddingProducts —** kādus produktus mums tiek lūgts pievienot 

  - **Data\_AvailableVersion —** uz kādu Office versiju ir pieejams atjauninājums

  - **Data\_CompletedWithoutActionInfo —** kāpēc nepabeidzām scenāriju, piem., lietojumprogrammas bija atvērtas

  - **Data\_CompletionState —** vai pabeidzām uzdevumu

  - **Data\_CorruptionChecksOnly —** vai tikai meklējam bojājumus un neveicam atjaunināšanu

  - **Data\_ErrorCode —** kļūdas kods, ar kuru radās problēmas 

  - **Data\_ErrorDetails —** papildu detalizēta informācija par kļūdu 

  - **Data\_ErrorMessage —** kļūdas ziņojums par to, kāda problēma radās 

  - **Data\_ErrorSource —** kur kļūda radās

  - **Data\_ExceptionType —** izņēmums, ar kuru radās problēmas 

  - **Data\_FoundCorruptFiles —** patiess, ja esam atraduši bojātus failus

  - **Data\_IsErrorCodeIgnorable —** vai kļūdas kods, ar kuru radās problēmas, ir ignorējams 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth —** ja uzskatām, ka kļūdas kods ir ignorējams 

  - **Data\_NewestPackageVersion —** jaunākā Office versija datorā 

  - **Data\_OldestPackageVersion —** vecākā Office versija datorā 

  - **Data\_PackageOperationSuccessful —** patiess, ja sekmīgi veicām savu uzdevumu ar Office pakotni

  - **Data\_PipelineExitCode —** izejas kods, ko mūsu failu konveijers atgrieza

  - **Data\_ProductsToAdd —** kādus Office produktus pievienojam 

  - **Data\_ProductsToRemove —** kādus Office produktus noņemam 

  - **Data\_RemovingFixedProducts —** produkti, ko noņemam 

  - **Data\_RemovingProducts —** produkti, kurus mums tiek lūgts noņemt 

  - **Data\_ScenarioInstanceID —** unikāls GUID darbības scenārijam 

  - **Data\_ScenarioName —** kāds scenārijs tiek izmantots. t.i., instalēšana 

  - **Data\_ScenarioSubType —** kāda veida scenāriju izmantojam, t.i., atinstalēšana, atkārtota instalēšana 

  - **Data\_SourceType —** kur ir mūsu avots, t.i., CDN 

  - **Data\_SqmMachineID —** unikālais datora ID, ko izmanto Windows SQM 

  - **Data\_SusClientID —** datora Office atjaunināšanas identifikators 

  - **Data\_TaskState —** kādā stāvoklī ir uzdevums, piemēram, darbojas vai atcelts 

  - **Data\_TotalClientCabSize —** mūsu klienta kabinetfaila lielums 

  - **Data\_TriggeringUI —** kas aktivizēja UI 

  - **Data\_UpdatesEnabled —** ja Office atjauninājumi ir iespējoti 

  - **Data\_Version —** Office versija 

### <a name="officeclicktorunscenarioupdatetaskupdatefinalize"></a>Office.ClickToRun.Scenario.UpdateTaskUpdatefinalize

Office iestatīšanas un krājumu dati, kas tiek apkopoti, kad Click-to-Run klients veic tīrīšanu no atjaunināšanas un atjaunošanas lietojumprogrammām, kas iepriekš tika atvērtas. Tiek izmantots, lai mērītu Office atjaunināšanas sekmīgu vai kļūdainu darbību.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_15\_SourceType —** kur Office 15 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_15\_UpdatesEnabled —** ja Office 15 atjauninājumi ir iespējoti 

  - **Data\_15\_UpdateVersion —** uz kādu Office 15 versiju veicam atjaunināšanu 

  - **Data\_15\_Version —** Office 15 versija 

  - **Data\_16\_SourceType —** kur Office 16 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_16\_UpdatesEnabled —** ja Office 16 atjauninājumi ir iespējoti 

  - **Data\_16\_UpdateVersion —** uz kādu Office 16 versiju veicam atjaunināšanu 

  - **Data\_16\_Version —** Office 16 versija 

  - **Data\_AddingFixedProducts —** produkti, ko pievienojam 

  - **Data\_AddingProducts —** kādus produktus mums tiek lūgts pievienot 

  - **Data\_CompletionState —** vai pabeidzām uzdevumu

  - **Data\_ErrorCode —** kļūdas kods, ar kuru radās problēmas 

  - **Data\_ErrorDetails —** papildu detalizēta informācija par kļūdu 

  - **Data\_ErrorMessage —** kļūdas ziņojums par to, kāda problēma radās 

  - **Data\_ErrorSource —** kur kļūda radās 

  - **Data\_ExceptionType —** izņēmums, ar kuru radās problēmas 

  - **Data\_IsErrorCodeIgnorable —** vai kļūdas kods, ar kuru radās problēmas, ir ignorējams 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth —** ja uzskatām, ka kļūdas kods ir ignorējams 

  - **Data\_NewestPackageVersion —** jaunākā Office versija datorā 

  - **Data\_OldestPackageVersion —** vecākā Office versija datorā 

  - **Data\_ProductsToAdd —** kādus Office produktus pievienojam 

  - **Data\_ProductsToRemove —** kādus Office produktus noņemam 

  - **Data\_RemovingFixedProducts —** produkti, ko noņemam 

  - **Data\_RemovingProducts —** produkti, kurus mums tiek lūgts noņemt 

  - **Data\_ScenarioInstanceID —** unikāls GUID darbības scenārijam 

  - **Data\_ScenarioName —** kāds scenārijs tiek izmantots. t.i., instalēšana 

  - **Data\_ScenarioSubType —** kāda veida scenāriju izmantojam, t.i., atinstalēšana, atkārtota instalēšana 

  - **Data\_SourceType —** kur ir mūsu avots, t.i., CDN 

  - **Data\_SqmMachineID —** unikālais datora ID, ko izmanto Windows SQM 

  - **Data\_SusClientID —** datora Office atjaunināšanas identifikators 

  - **Data\_TaskState —** kādā stāvoklī ir uzdevums, piemēram, darbojas vai atcelts 

  - **Data\_TotalClientCabSize —** mūsu klienta kabinetfaila lielums 

  - **Data\_TriggeringUI —** kas aktivizēja UI 

  - **Data\_UpdatesEnabled —** ja Office atjauninājumi ir iespējoti 

  - **Data\_Version —** Office versija 

### <a name="officeclicktoruntransport"></a>Office.ClickToRun.Transport

Ziņo par failu lejupielādes darbībām, lai noteiktu operācijas sekmīgumu, veiktās lejupielādes tipu un diagnostikas informāciju.


- **BytesFromGroupPeers —** baiti no grupas vienranga dalībniekiem, tikai lejupielādēm, izmantojot piegādes optimizāciju

- **BytesFromHttp —** baiti no http, tikai lejupielādēm, izmantojot piegādes optimizāciju

- **ByteFromInternetPeers —** baiti no interneta vienranga dalībniekiem, tikai lejupielādēm, izmantojot piegādes optimizāciju 

- **BytesFromLanPeers —** baiti no LAN vienranga dalībniekiem, tikai lejupielādēm, izmantojot piegādes optimizāciju 

- **canceledJobs —** atcelto pieprasījumu skaits sesijā

- **Connected —** vai ir izveidots savienojums ar avotu

- **ErrorCode —** pēdējās kļūdas kods

- **ErrorDetails —** pēdējās kļūdas detalizētā informācija

- **ErrorMessage —** pēdējās kļūdas ziņojums 

- **ErrorSource —** pēdējās kļūdas cēlonis, piemēram, Connection, LoadFile vai LoadRange

- **FailedJob —** neizdevušos pieprasījumu skaits sesijā

- **FileSize —** resursa lielums

- **SourcePathNoFilePath —** resursa avota ceļš, tiek ziņots tikai par http avotu, lokālā faila ceļš un UNC ceļš tiek filtrēts

- **SucceededJobs —** sekmīgu pieprasījumu skaits sesijā

- **TotalJobs —** kopējais pieprasījumu skaits sesijā

- **TotalRequestedBytes —** kopējais pieprasīto baitu skaits sesijā

- **TotalTransferTime —** kopējais pārsūtīšanas laiks sesijā

- **TransferredBytes —** kopējais pārsūtīto baitu skaits sesijā

- **TransportType —** transporta veids, piemēram, piegādes optimizācija atmiņā, HTTP, fona režīma viedās pārsūtīšanas pakalpojums



### <a name="officeclicktoruntransportexperimentaltransportpipelinecreatetransport"></a>Office.ClickToRun.Transport.ExperimentalTransport.PipelineCreateTransport

Office iestatīšanas un krājumu dati, kas tiek apkopoti, kad Click-to-Run klients veido transportēšanas straumi, lai lejupielādētu Office failus. Tiek izmantoti, lai noteiktu dažādu transportēšanas tehnoloģiju (piemēram, HTTP, BITS, DO) darbspēju, kas ir kritiski svarīgi, lai pareizi lejupielādētu Office instalēšanai un atjauninājumiem.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_IsForeGroundStreaming** — vai straumējam priekšplānā vai fonā

  - **Data\_IsInstallMode** — 1 — ja instalējam un lejupielādējam failus, 0 — ja to nedarām

  - **Data\_SourceProtocol —** ja veicam lejupielādi no satura datu tīkla, CDN, datora, kurā veicam instalēšanu, lokāli vai resursa lokālajā tīklā,

  - **Data\_Status** — sekmīga izpilde vai kļūme 

### <a name="officeclicktorunupdatestatus"></a>Office.ClickToRun.UpdateStatus

Office iestatīšanas un krājumu dati, kas tiek apkopoti, kad Click-to-Run klients pabeidz atjaunināšanas statusu

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_build** — pašlaik instalētā Office versija

  - **Data\_channel** — kanāls, kurā lietotājs atrodas

  - **Data\_errorCode** — vesela skaitļa kods, kas norāda, kāda veida kļūda radās, ja tāda radās

  - **Data\_errorMessage** — virkne, kas nodrošina radušās kļūdas aprakstu, ja tāda radās

  - **Data\_status** — īss statuss par to, kas notika atjaunināšanas laikā, piemēram, Izdevās vai Lejupielādēts

  - **Data\_targetBuild —** Office versija, uz kuru mēģinām veikt atjaunināšanu


### <a name="officeclicktorununiversalbootstrapperapplication"></a>Office.ClickToRun.UniversalBootstrapper.Application

Ziņo par gala-gala instalācijas mēģinājuma rezultātu

 - **ErrorCode —** vesels skaitlis, kas saistīts ar neapstrādātu izņēmumu

 - **ErrorDetails —** virkne, kas apraksta atrašanās vietu, kur radās neapstrādāts izņēmums (funkcija, fails, rindiņas numurs, metēja iestatītie papildu parametri)

 - **ErrorMessage —** virkne, kas definēta punktā, kurā tika izmests neapstrādāts izņēmums, aprakstot kļūmes būtību

 - **ErrorType —** virkne, kas apraksta neapstrādāta izņēmuma kategoriju

 - **ExitCode —** vesela skaitļa vērtība, kas saistīta ar sāknēšanas programmas darbības rezultātu, norādot sekmes vai konkrētus kļūmju tipus

### <a name="officeclicktorununiversalbootstrappercalculateparameters"></a>Office.ClickToRun.UniversalBootstrapper.CalculateParameters

Atskaites par darbību, kas ir pamats apkopotajai ievadei, izmantojot CollectParameters

- **BitField  —**    argumenta BitField vesela skaitļa vērtība, kas norāda, vai ir pieprasīts konkrēts instalēšanas/atjaunināšanas kanāls. Piemēram, beta kanāls, pašreizējais kanāls (priekšskatījums), pašreizējais kanāls, ikmēneša uzņēmuma kanāls, pusgada uzņēmuma kanāls (priekšskatījums) vai pusgada uzņēmuma kanāls.

- **ChannelID —**    vesels skaitlis, kas norāda uzskaitītā atjauninājuma/instalācijas kanāla uzskaitījuma vērtību. Piemēram, beta kanāls, pašreizējais kanāls (priekšskatījums), pašreizējais kanāls, ikmēneša uzņēmuma kanāls, pusgada uzņēmuma kanāls (priekšskatījums), pusgada uzņēmuma kanāls vai nederīgs.

- **CMDMode —** draudzīgā virkne, kas atbilst tam, kāds vispārējā režīma pārslēgs tika noteikts .exe failam nodotajos cmd argumentos.

- **C2RClientUICulture —** instalējamā C2R klienta kultūra

- **ErrorCode —** vesels skaitlis, kas saistīts ar neapstrādātu izņēmumu

- **ErrorDetails —** virkne, kas apraksta atrašanās vietu, kur radās neapstrādāts izņēmums (funkcija, fails, rindiņas numurs, metēja iestatītie papildu parametri)

- **ErrorMessage —** virkne, kas definēta punktā, kurā tika izmests neapstrādāts izņēmums, aprakstot kļūmes būtību

- **ErrorType —** virkne, kas apraksta neapstrādāta izņēmuma kategoriju

- **ExcludedApps —** virkne, kurā uzskaitīti to atsevišķo Office programmu nosaukumi, kurām tika pieprasīta izslēgšana no instalētajiem Office komplektiem

- **InstalledCabVersion —** jau instalētā Office C2R klienta versija formātā “16.0.xxxxx.yyyyy”

- **InstalledProductVersion —** jau instalētā Office C2R produkta versija formātā “16.0.xxxxx.yyyyy”

- **IsC2RServiceRunning —** Būla karodziņš, kas norāda, vai modernā C2R klienta lokālā datora pakalpojums ierīcē ir ieslēgts un darbojas

- **IsElevatedFlagSet —** Būla karodziņš, kas norāda, vai sāknēšanas programma jau ir mēģinājusi iegūt administratora privilēģiju palielināšanu

- **IsFireFlyInstalled —** Būla karodziņš, kas norāda, vai šobrīd ir instalēts Office 2013 RTM C2R klients

- **IsFireflyServiceRunning —** Būla karodziņš, kas norāda, vai 2013 RTM C2R klienta lokālā datora pakalpojums ierīcē ir ieslēgts un darbojas

- **IsOfficeInstalled —** Būla karodziņš, kas norāda, vai modernais Office klients jau ir instalēts

- **OfficeCultures —** instalējamo Office kultūru sērijas saraksts

- **OfficeSourceType —** draudzīga virkne, kas saistīta ar instalēšanas avota uzskaitījuma vērtību (CDN, HTTP, UNC, CMBITS, DVD, LOCAL)

- **Origin —** virknes vērtība, kas norāda, kura no atbalstītajām izcelsmes vietām (Puertoriko [PR], Singapūra [SG], Dublina [DB]) ir jāizmanto sākotnējai instalācijas straumēšanai

- **PlatformFromLink —** virkne, kas norāda no C2R iestatīšanas pakalpojuma pieprasīto Office x86|x64|noklusējuma bitu daudzumu

- **PlatformOfExistingInstallation —** virkne, kas norāda, vai ierīcē bija jau instalēta x86 vai x64 sistēma Office

- **PlatformToInstall —** virkne, kas norāda galīgo lēmumu par to, vai ir jāinstalē x86 vai x64 Office Iespējas ir: automātiskā palaišana, konfigurēšana, patērētājs, lejupielāde, palīdzība, pakotājs

- **PRID —**    virknes vērtība, kas norāda pieprasītā produkta laidiena ID patērētāja instalēšanas gadījumā (piemēram, O365ProPlusRetail)

- **PridsToMigrateFromCentennial —** Office produktu virkne, lai migrētu no veikala instalācijām uz noklikšķināt, lai palaistu

- **ProductsToAdd —**   sērijas virkne, kas C2R klientam norāda, kurās produkta/kultūra kombinācijās tā ir jāinstalē

- **ProductsToMigrateFromO15C2R —**  Office produktu un kultūru virkne, lai migrētu no Office 2013 noklikšķināt, lai palaistu instalācijas

- **ProductsToRemove —** sērijas virkne, kas C2R klientam norāda, kurās produkta/kultūra kombinācijās tas ir jāatinstalē

- **SharedComputerLicensing —** Būla vērtība, kas norāda, vai IT administrators ir pieprasījis iestatīšanu, lai iespējotu līdzekli SharedComputerLicensing

- **ShouldActivate —** Būla vērtība, kas norāda, vai IT administrators ir pieprasījis automātisko licencēšanas aktivizācijas mēģinājumu savā konfigurācijas .xml failā

- **ShouldUninstallCentennial —** Būla karodziņš, kas norāda, vai Office produkti no veikala ir jāatinstalē

- **VersionToInstall —** instalējamās Office versijas virknes vērtība formātā “16.0.xxxxx.yyyyy”
 

### <a name="officeclicktorununiversalbootstrappercollectembeddedsignature"></a>Office.ClickToRun.UniversalBootstrapper.CollectEmbeddedSignature

Atskaites par darbībām, kas lasa atzīmēto ievadi no .exe faila iegultā paraksta.  Šī ir nepierādīta koncepcija, kuru iepriekšējā programmas setup.exe versija neimplementēja, un uz to mēs paļaujamies, lai pārnestu lietotāja produkta/valodas/bitu skaita izvēles no tīmekļa lapas uz iekšējo procesu programmā setup.exe.
 
- **ErrorCode —** vesels skaitlis, kas saistīts ar neapstrādātu izņēmumu

- **ErrorDetails —** virkne, kas apraksta atrašanās vietu, kur radās neapstrādāts izņēmums (funkcija, fails, rindiņas numurs, metēja iestatītie papildu parametri)

- **ErrorMessage —** virkne, kas definēta punktā, kurā tika izmests neapstrādāts izņēmums, aprakstot kļūmes būtību

- **ErrorType —** virkne, kas apraksta neapstrādāta izņēmuma kategoriju

### <a name="officeclicktorununiversalbootstrappercollectparameters"></a>Office.ClickToRun.UniversalBootstrapper.CollectParameters

Ziņo par Office instalēšanai izmantotajiem parametriem

- **BitField  —**    argumenta BitField vesela skaitļa vērtība, kas norāda, vai ir pieprasīts konkrēts instalēšanas/atjaunināšanas kanāls. Piemēram, beta kanāls, pašreizējais kanāls (priekšskatījums), pašreizējais kanāls, ikmēneša uzņēmuma kanāls, pusgada uzņēmuma kanāls (priekšskatījums) vai pusgada uzņēmuma kanāls.

- **ChannelID —**    vesels skaitlis, kas norāda uzskaitītā atjauninājuma/instalācijas kanāla uzskaitījuma vērtību. Piemēram, beta kanāls, pašreizējais kanāls (priekšskatījums), pašreizējais kanāls, ikmēneša uzņēmuma kanāls, pusgada uzņēmuma kanāls (priekšskatījums), pusgada uzņēmuma kanāls vai nederīgs.

- **CMDMode —** draudzīgā virkne, kas atbilst tam, kāds vispārējā režīma pārslēgs tika noteikts .exe failam nodotajos cmd argumentos. Iespējas ir: automātiskā palaišana, konfigurēšana, patērētājs, lejupielāde, palīdzība, pakotājs

- **C2RClientUICulture —** instalējamā C2R klienta kultūra

- **ErrorCode —** vesels skaitlis, kas saistīts ar neapstrādātu izņēmumu

- **ErrorDetails —** virkne, kas apraksta atrašanās vietu, kur radās neapstrādāts izņēmums (funkcija, fails, rindiņas numurs, metēja iestatītie papildu parametri)

- **ErrorMessage —** virkne, kas definēta punktā, kurā tika izmests neapstrādāts izņēmums, aprakstot kļūmes būtību

- **ErrorType —** virkne, kas apraksta neapstrādāta izņēmuma kategoriju

- **ExcludedApps —** virkne, kurā uzskaitīti to atsevišķo Office programmu nosaukumi, kurām tika pieprasīta izslēgšana no instalētajiem Office komplektiem

- **InstalledCabVersion —** jau instalētā Office C2R klienta versija formātā “16.0.xxxxx.yyyyy”

- **InstalledProductVersion —** jau instalētā Office C2R produkta versija formātā “16.0.xxxxx.yyyyy”

- **IsC2RServiceRunning —** Būla karodziņš, kas norāda, vai modernā C2R klienta lokālā datora pakalpojums ierīcē ir ieslēgts un darbojas

- **IsElevatedFlagSet —** Būla karodziņš, kas norāda, vai sāknēšanas programma jau ir mēģinājusi iegūt administratora privilēģiju palielināšanu

- **IsFireFlyInstalled —** Būla karodziņš, kas norāda, vai šobrīd ir instalēts Office 2013 RTM C2R klients

- **IsFireflyServiceRunning —** Būla karodziņš, kas norāda, vai 2013 RTM C2R klienta lokālā datora pakalpojums ierīcē ir ieslēgts un darbojas

- **IsOfficeInstalled —** Būla karodziņš, kas norāda, vai modernais Office klients jau ir instalēts

- **OfficeCultures —** instalējamo Office kultūru sērijas saraksts

- **OfficeSourceType —** draudzīga virkne, kas saistīta ar instalēšanas avota uzskaitījuma vērtību (CDN, HTTP, UNC, CMBITS, DVD, LOCAL)

- **Origin —** virknes vērtība, kas norāda, kura no atbalstītajām izcelsmes vietām (Puertoriko [PR], Singapūra [SG], Dublina [DB]) ir jāizmanto sākotnējai instalācijas straumēšanai

- **PlatformFromLink —** virkne, kas norāda no C2R iestatīšanas pakalpojuma pieprasīto Office x86|x64|noklusējuma bitu daudzumu

- **PlatformOfExistingInstallation —** virkne, kas norāda, vai ierīcē bija jau instalēta x86 vai x64 sistēma Office

- **PlatformToInstall —** virkne, kas norāda galīgo lēmumu par to, vai ir jāinstalē x86 vai x64 Office

- **PRID —**    virknes vērtība, kas norāda pieprasītā produkta laidiena ID patērētāja instalēšanas gadījumā (piemēram, O365ProPlusRetail)

- **PridsToMigrateFromCentennial —** Office produktu virkne, lai migrētu no veikala instalācijām uz noklikšķināt, lai palaistu

- **ProductsToAdd —**   sērijas virkne, kas C2R klientam norāda, kurās produkta/kultūra kombinācijās tā ir jāinstalē

- **ProductsToMigrateFromO15C2R —** Office produktu un kultūru virkne, lai migrētu no Office 2013 noklikšķināt, lai palaistu instalācijas

- **ProductsToRemove —** sērijas virkne, kas C2R klientam norāda, kurās produkta/kultūra kombinācijās tas ir jāatinstalē

- **SharedComputerLicensing —** Būla vērtība, kas norāda, vai IT administrators ir pieprasījis iestatīšanu, lai iespējotu līdzekli SharedComputerLicensing

- **ShouldActivate —** Būla vērtība, kas norāda, vai IT administrators ir pieprasījis automātisko licencēšanas aktivizācijas mēģinājumu savā konfigurācijas .xml failā

- **ShouldUninstallCentennial —** Būla karodziņš, kas norāda, vai Office produkti no veikala ir jāatinstalē

- **VersionToInstall —** instalējamās Office versijas virknes vērtība formātā “16.0.xxxxx.yyyyy”

### <a name="officeclicktorununiversalbootstrapperexecute"></a>Office.ClickToRun.UniversalBootstrapper.Execute

Ziņo par veiktajām darbībām, kas ietekmē datoru, kā to nosaka apspriestie dati no CalculateParameters

- **AvailableClientVersionText —** tās C2R klienta versijas formātā “16.0.xxxxx.yyyyy” virknes vērtība, kas atrasta versijas deskriptora XML failā, kurš tiek izmantots, lai noteiktu, vai šobrīd instalētais C2R klients ir jāatjaunina

- **CleanFireflyAction —** “patiess”, ja šīs instalēšanas laikā ir ieplānota uzdevuma CleanFireflyAction izpilde

- **CleanO15Action —** “patiess”, ja šīs instalēšanas laikā ir ieplānota uzdevuma CleanO15Action izpilde

- **CMDMode —** draudzīgā virkne, kas atbilst tam, kāds vispārējā režīma pārslēgs tika noteikts .exe failam nodotajos cmd argumentos. Iespējas ir: automātiskā palaišana, konfigurēšana, patērētājs, lejupielāde, palīdzība, pakotājs

- **DeliveryMechanism —** “FFNRoot” GUID, kas izvilkts no versijas deskriptora XML faila (apzīmogots ar RDX), kurš norāda, no kuras auditorijas/kanāla ir nācis būvējuma avots

- **DownloadC2RClientAction —** “patiess”, ja šīs instalēšanas laikā ir ieplānota uzdevuma DownloadC2RClientAction izpilde

- **ErrorCode —** vesels skaitlis, kas saistīts ar neapstrādātu izņēmumu

- **ErrorDetails —** virkne, kas apraksta atrašanās vietu, kur radās neapstrādāts izņēmums (funkcija, fails, rindiņas numurs, metēja iestatītie papildu parametri)

- **ErrorMessage —** virkne, kas definēta punktā, kurā tika izmests neapstrādāts izņēmums, aprakstot kļūmes būtību

- **ErrorType —** virkne, kas apraksta neapstrādāta izņēmuma kategoriju

- **ExitCode —** vesela skaitļa vērtība, kas saistīta ar sāknēšanas programmas izpildes fāzes darbības rezultātu, norādot sekmes vai konkrētus kļūmju tipus

- **LaunchAction —** “patiess”, ja šīs instalēšanas laikā ir ieplānota uzdevuma LaunchAction izpilde

- **LaunchUpdateAction —** “patiess”, ja šīs instalēšanas laikā ir ieplānota uzdevuma LaunchUpdateAction izpilde

- **PreReqResult —** rezultāta vesela skaitļa uzskaitījuma vērtība, ja tika veiktas PreReq pārbaudes (izturēja/neizturēja/atkārtota palaišana)

- **UnexpectedAction —**“patiess”, ja uzdevumam UnexpectedAction (kļūdas gadījums) ir ieplānota veikšana šīs instalēšanas laikā

- **VersionToInstall —** instalējamās Office versijas virknes vērtība formātā “16.0.xxxxx.yyyyy”

### <a name="officeserviceabilitymanagerinventoryaddonheartbeat"></a>Office.ServiceabilityManager.InventoryAddon.Heartbeat

*[Šis notikums ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

Šis notikums tiek izmantots, lai iegūtu standarta metadatus par katru inventāra pievienojumprogrammas darbību, kas ir daļa no tehniskās apkopes pārvaldnieka un tiek izmantota Office informācijas uzskaitei datoros un ierīcēs, kurām administrators to ir iespējojis. Šeit īpaši interesanti sesijas ID metadati, kas tiek izmantoti, lai izveidotu saiti uz citiem datiem, kas ir saglabāti katra nomnieka mākoņa pakalpojumā.

Šis notikums nesatur ekstra laukus, jo saistoši ir tikai metadati.

### <a name="officeserviceabilitymanagerinventoryaddonresults"></a>Office.ServiceabilityManager.InventoryAddon.Results

Šis notikums tiek reģistrēts, kad izsaukums uz tīmekļa pakalpojumu, kas veikts, izmantojot noklikšķināt, lai palaistu funkcionālo darbību pievienojumprogrammu, tiek pabeigts, neatkarīgi no tā, vai tas ir sekmīgs vai nē. Tā būtībā ir pēdējā operācija pievienojumprogrammā, lai izsekotu kopējo darbības statusu.

Tiek apkopoti šādi lauki:

- **ActionDetail** — papildu detalizēta informācija, kad rodas kļūme.
   - Ja HTTP pieprasījums izdodas, ActionDetail būs 0.
   - Ja rezultāta lauks nav labs (t.i., nav 0), tas nozīmē, ka pieprasījums netiek nosūtīts, šis lauks reģistrēs iekšējās kļūdas kodu, kas ir tāds pats kā Rezultāta lauks.
   - Ja rezultāts ir labs (t.i., 0), tas nozīmē, ka HTTP atbildes kods >= 300, tas reģistrēs HTTP atbildes kodu (piem., 404).

- **Result** — skaitlisks kļūdas kodu karodziņi, ko atgriezis Office tīmekļa pakalpojumu zvanu API. – piem., 3 nozīmētu, ka ir radusies problēma ar HTTP galveņu inicializēšanu.

- **Ierakstiet** — papildu informāciju par tipu. Krājuma gadījumā šī informācija norāda, kāda veida vērtumus tiek sūtīts, piem., pilns vai tikai izmaiņu delta. 

-  **WebCallSource** — uzskaitījuma vērtība (norādīta kā vesels skaitlis), kas norāda, kāda ir apkalpojamības pārvaldnieka pievienojumprogramma, kas bija zvana avots:
   - Krājumu saraksts: 0
   - Krājumu konfigurācija: 1
   - Krājumu politika: 2
   - Krājumu tīkla statuss: 3
   - Apkopes pārvaldnieks: 4
   - Pārvaldīšanas iespējas: 5

### <a name="officeserviceabilitymanagerwebservicefailure"></a>Office.ServiceabilityManager.WebserviceFailure

Šis paziņojums tiek reģistrēts, katru reizi, kad notiek kādas Office tehniskās apkopes pārvaldnieka pievienojumprogrammas kļūme. Kļūmju iemesls var būt iekšējās kļūmes vai nespēja izveidot savienojumu ar tīmekļa pakalpojumu.

Tiek apkopoti šādi lauki:

- **Pievienojumprogramma** — noklikšķināt, lai palaistu tehniskās apkopes pārvaldnieka pievienojumprogramma, no kuras tīmekļa pakalpojuma zvans tika veikts. Tam var būt vērtības, piemēram, krājums, pārvaldāmība utt., kas kodēta kā skaitliska vērtība.

- **Korelācijas ID** — nejauši ģenerētu GUID, kas raksturīgs pašreizējai instancei, kas tiek nosūtīta tīmekļa pakalpojumam, lai saistītu zvanus starp klientu un serveri.

- **Result** — skaitliska kļūdas kodu informācija, ko atgriezis Office tīmekļa pakalpojumu zvanu API.

- **ErrorMessage** — ziņojums, kas sniedz papildu ieskatu par kļūmi. Katrs kļūdas tips tiek kartēts pie stingri kodētas virknes, bet daži kļūdu tipi var būt potenciāli kartēti ar vairākām virknēm, atkarībā no kļūmes specifikas.

- **Funkcija** — funkcija kodā, no kura ir noticis pašreizējais zvans.

- **Statusa** — HTTP statusa kods, ko atgriezis zvans uz tīmekļa pakalpojumu, piemēram, 404, 500 utt.


## <a name="enhanced-configuration-service-ecs-events"></a>Uzlabotās konfigurācijas pakalpojuma (ECS) notikumi

### <a name="officeexperimentationfeaturequerybatched"></a>Office.Experimentation.FeatureQueryBatched

Apkopo informāciju par līdzekļu vārtejām/maiņas vārtejām, kam izpildītais kods ir veidojis vaicājumus.

Tiek apkopoti tālāk norādītie lauki.

  - **Count** — līdzekļu ar vaicājumiem vārteju skaits šajā partijā iekļautajā notikumā

  - **Features** — informācija par vārteju, kam izveidots vaicājums.

  - **Sequence** — secībā, kādā FeatureGate tika veidoti vaicājumi

### <a name="officeexperimentationflightnumberline"></a>Office.Experimentation.FlightNumberLine

Apkopo konfigurāciju sarakstu, ko klients saņēmis no ECS

Tiek apkopoti tālāk norādītie lauki.

  - **ECSConfigs** — komatatdalīts ECS konfigurāciju saraksts

  - **LockType** — FlightManager bloķēšanas veids.

  - **TasFlightingVersion** — versijas numurs

  - **TimeToLock** — laiks starp liblet uzsākšanu un FlightManager bloķēšanu

  - **UnmergedConfigs** — nesapludināto konfigurāciju saraksts

### <a name="officeexperimentationtriggeranalysis"></a>Office.Experimentation.TriggerAnalysis

Šis pasākums palīdz analizēt produktu lietojuma un veiktspējas rādītāju apjomu (piemēram, avārijas, uzkāršanos) lietotāju vai ierīču apakškopā, kura drīkst izmantot līdzekli, nodrošinot pareizu produkta darbību.

Tiek apkopoti šādi lauki.

  - **FeatureGate —** nosaka līdzekļu kopu, kura atbilst cēloņu analīzei.

### <a name="onenoteflightdefault"></a>OneNote.FlightDefault
 
Šis notikums tiek reģistrēts, kad OneNote pieprasa ECS serveri lidojuma vērtībām.  To var izmantot, lai nodrošinātu eksperimentālus līdzekļus tiem lietotājiem, kuri ir pieteikušies saņemt šādus lidojumus.
 
Tiek apkopoti tālāk norādītie lauki:
 
- **ConfigParam** — konfigurācija, kurai tiek lietota vērtība

## <a name="licensing-events"></a>Licencēšanas notikumi

### <a name="officeandroiddocsuipaywallcontrolautoredeempendingpurchaseresult"></a>Office.Android.DocsUI.PaywallControl.AutoRedeemPendingPurchaseResult

Kritisko tehnoloģiju telemetriju, reģistrējot automātiskās izpirkšanas mēģinājuma rezultātus, lai izpirktu gaidāmos lietotāja pirkumus. Produktu telemetriju, kas tiek izmantoti, lai saistītu pirkumu darbību informāciju ar Microsoft tirdzniecības sistēmu un iespējotu saistīto abonementu priekšrocības.

Tiek apkopoti šādi lauki:

- **EventDate** — notikuma laikspiedols 

- **Result** — Int apzīmē operācijas uzskaitījuma rezultātu. 

- **SessionID** — GUID, lai savienotu notikumus pēc sesijas

### <a name="officeandroiddocsuipaywallcontrolpaywalluishown"></a>Office.Android.DocsUI.PaywallControl.PaywallUIShown

Kritisko lietojumu telemetriju, kad lietotājam tiek rādīta Paywall vadīkla. Tiek izmantoti, lai saprastu lietojumprogrammas iegādes pieredzi lietotājam un optimizētu to pašu turpmākajām versijām.

Tiek apkopoti šādi lauki:

- **EventDate** — notikuma laikspiedols 

- **IsModeFRE** — Būla vērtība, lai norādītu pieredzes veidu, Upsell dialoglodziņu vai SKU Chooser

- **SessionID** — GUID, lai savienotu notikumus pēc sesijas

### <a name="officeandroiddocsuipaywallcontrolpurchasebuttonclicked"></a>Office.Android.DocsUI.PaywallControl.PurchaseButtonClicked

Kritiskā lietojuma telemetrija, lai uzzinātu, kad lietotājs noklikšķina uz pogas Pirkt. Izmanto, lai secinātu par izmantošanas modeli un reklāmguvumu metriku lietotājiem, kuri mēģina iegādāties abonementu lietojumprogrammā.

Tiek apkopoti šādi lauki:

- **EventDate** — notikuma laikspiedols

- **IsDefaultSku** — Būla vērtība, kas norāda, vai lietotājs mēģina iegādāties SKU, kas parādījās pirmā/noklusējums

- **ProductID** — virkne, kas nosaka, kurš abonementa lietotājs mēģina veikt pirkumu atbilstoši konfigurācijai veikalā

- **SessionID** — GUID, lai savienotu notikumus pēc sesijas

### <a name="officeandroiddocsuipaywallcontrolpurchaseresult"></a>Office.Android.DocsUI.PaywallControl.PurchaseResult

Kritiski tehniskās telemetrijas dati, lai reģistrētu pirkšanas mēģinājuma rezultātus, ko lietotājs aktivizējis manuāli. Produktu telemetriju, kas tiek izmantoti, lai saistītu pirkumu darbību informāciju ar Microsoft tirdzniecības sistēmu un iespējotu saistīto abonementu priekšrocības.

Tiek apkopoti šādi lauki:

- **EventDate** — notikuma laikspiedols 

- **IsModeFre** — Būla vērtība, norādot, vai pirkums ir izveidots no Upsell FRE ekrāna vai SKU Chooser

- **Result** — Int apzīmē operācijas uzskaitījuma rezultātu.

- **SessionID** — GUID, lai savienotu notikumus pēc sesijas

### <a name="officeandroiddocsuipaywallcontrolpurchasetokenredemptionresponse"></a>Office.Android.DocsUI.PaywallControl.PurchaseTokenRedemptionResponse

*[Šī notikuma iepriekšējais nosaukums bija Office.Android.DocsUI.Views.PurchaseTokenRedemptionResponse.]*

Šī produkta telemetrija tiek apkopota, lai izsekotu un uzskaitītu iekšējo transakciju statusu un saskaņošanas informāciju uzticamības un veiktspējas uzlabošanai. Microsoft izmanto šos datus, lai analizētu un uzlabotu iekšējo transakciju apstrādes un saskaņošanas mehānismu uzticamību un veiktspēju.

Tiek apkopoti šādi lauki:

- **MicrosoftPurchaseOrderId** — Microsoft pasūtījuma ID izsekošanas mērķiem tiek nosūtīts uz mazumtirdzniecības federācijas pakalpojumu (RFS).

- **ResponseCode** — HTTP atbildes kods (int)

- **StatusCode** — RFS atbildes statusa kods (RFS definēts uzskaitījums int-ierobežots)


### <a name="officeandroiddocsuipaywallcontrolseeallfeaturesanalytics"></a>Office.Android.DocsUI.PaywallControl.SeeAllFeaturesAnalytics

Mēs apkopojam šo lietošanas telemetriju, lai redzētu, cik daudz laika lietotājs pavada ekrānā “Skatīt citas priekšrocības”.  Šie dati tiek izmantoti, lai izprastu līdzekļa “Skatīt vairāk priekšrocības” lietojumu un optimizētu tā lietošanas pieredzi nākamajās versijās.

Tiek apkopoti šādi lauki:

- **Duration** — garš vesels skaitlis, kas norāda lietotāja pavadīto laiku ekrānā “Skatīt visas funkcijas” milisekundēs

- **EventDate** — notikuma laikspiedols 

- **MostExplored** — vesels skaitlis, kas apzīmē visvairāk pārslēdzamā vienuma indeksu Microsoft 365 programmu un to līdzekļu sarakstā

- **SessionID** — vispārēji unikāls identifikators (GUID), lai savienotu notikumus pēc sesijas

### <a name="officeandroiddocsuipaywallcontrolskuchooseranalytics"></a>Office.Android.DocsUI.PaywallControl.SkuChooserAnalytics

Lietojuma telemetrijas iespējas, lai uzzinātu, cik daudz laika lietotājs patērē SKU Chooser ekrānā. Lietojuma telemetrijas iespējas, lai uzzinātu, cik daudz laika lietotājs patērē SKU Chooser ekrānā.

Tiek apkopoti šādi lauki:

- **Duration** — Garš vesels skaitlis, kas norāda lietotāja pavadīto laiku SKU Chooser ekrānā milisekundēs

- **EventDate** — notikuma laikspiedols

- **SessionID** — GUID, lai savienotu notikumus pēc sesijas


### <a name="officeandroiddocsuiviewsdimeerror"></a>Office.Android.DocsUI.Views.DimeError

Šis notikums tiek apkopots Office lietojumprogrammai darbam ar Android (izlaista Huawei un Ķīnas veikalos). Šis notikums norāda, ka mēģinājums iegādāties Microsoft 365 abonementu, izmantojot Dime (klienta tīmekļa skatā ielādēts tīmekļa vietrādis URL), neizdevās. Tiek tverti tikai kļūdu scenāriji. Šī notikuma dati ir tikai kļūdas dati un tie tiek izmantoti, lai nodrošinātu Dime pirkumu plūsmas darbspēju klientā.

Tiek apkopoti šādi lauki:

- **CorrelationID** — ID, kas unikāli identificē Dime pirkuma sesiju.

- **ErrorReason** — norāda kļūdas rašanās iemeslu.
  - 0 — nezināma kļūda
  - 1 — internets nav pieejams
  - 2 — vispārēji unikālā identifikatora (UUID) validācija neizdevās
  - 3 — vispārēji unikāls identifikators (UUID) ir null vai tukšs
  - 4 — JavaScript injekcijas kļūda, kur Office lietojumprogramma darbam ar Android nevar padot authToken uz Dime
  - 5 — bāzes tīmekļa URL, kas ielādēts klientā, ir nederīgs


### <a name="officedimesdkhealth"></a>Office.Dime.Sdk.Health

Šis notikums tver datus, kas palīdz veikt Dime komponentu darbpsējas pārraudzību.  Piemēram, iegādes programmā plūsmai, kad lietotājs izvēlas iegādāties Microsoft 365 abonementu no Office lietojumprogrammas darbam ar Android vai ierīcēs, kurās darbojas operētājsistēma Windows.

Tiek apkopoti šādi lauki:

- **Data_ActivityErrorDescription** — darbības kļūdas apraksts

- **Data_ActivityErrorMessage** — darbības kļūdas ziņojums 

- **Data_CampaignId** — kampaņas ID attiecinājumam

- **Data_ContentId** — balstīts uz līdzekļa ID; tas tiek kartēts pie plūsmas ID vai satura ID

- **Data_CorrelationVector** — korelācijas vektors, lai korelētu Dime ar partneriem, kas izmanto korelācijas vektoru

- **Data_CustomerImpacted** — izmanto problēmu novēršanai, ja klients tiek ietekmēts plūsmas ielādes laikā

- **Data_DimeActivityDuration** — ilgums 

- **Data_DimeActivityMetadata** — darbības metadati

- **Data_DimeActivityName** — aktivitātes nosaukums darbspējas pārraudzībai

- **Data_DimeActivityResult** — darbības rezultāts, sekmīgi pabeigta / kļūda / paredzama kļūda

- **Data_DimeVersion** — būvējuma versija

- **Data_DurationLevel** — nozīmīguma pakāpe — 0/1/2

- **Data_EcsConfigIds** — eksperimentiem paredzētie ID

- **Data_EcsCountry** — noteiktā valsts

- **Data_EcsETag** — informācija par testējamiem variantiem

- **Data_Environment** — Dime vides izstrāde/priekšizstrāde

- **Data_ExperienceId** — ielādējamais līdzeklis 

- **Data_FlowId** — balstīts uz līdzekļa ID; tas tiek kartēts pie plūsmas ID vai satura ID

- **Data_Language** — kultūra

- **Data_Market** — noteiktais tirgus

- **Data_OTelJS_Version** — Office telemetrijas versija

- **Data_PageSessionId** — lapas sesijas ID

- **Data_PartnerId** — programma izsaucējs

- **Data_QosLevel** — nozīmīguma pakāpe 0/1/2

- **Data_SDX_AssetId** — pakalpojuma nodrošinātā līdzekļa (SDX), kurā ir izvietots saturs sistēmai Win32, līdzekļa ID

- **Data_SDX_BrowserToken** — pārlūkprogrammas sistēmai Win32 marķieris

- **Data_SDX_HostJsVersion** — JavaScript bibliotēkas versija sistēmai Win32

- **Data_SDX_Id** — pakalpojuma nodrošinātā līdzekļa ID sistēmai Win32

- **Data_SDX_InstanceId** — SDX sistēmai Win32 instances ID

- **Data_SDX_MarketplaceType** — SDX tirgus veids sistēmai Win32

- **Data_SDX_OfficeJsVersion** — Office JS versija sistēmai Win32

- **Data_SDX_SessionId** — SDX sistēmai Win32 sesijas ID

- **Data_SDX_Version** — SDX versija sistēmai Win32

- **CollectionTime** — notikuma laikspiedols

- **Data_TsgId** — katras darbības problēmu novēršanas vadlīniju ID

- **Data_UserAgent** — virsraksta atzīmes

### <a name="officeiospaywallskuchooserbuybuttontap"></a>Office.iOS.Paywall.SKUChooser.BuyButtonTap

Kritisko lietojumu telemetrijas tiek apkopots, lai norādītu, kad lietotājs pieskaras pogai Pirkums/Pirkt.  Datus izmanto, lai secinātu par izmantošanas modeli un reklāmguvumu metriku lietotājiem, kuri mēģina iegādāties abonementu lietojumprogrammā.

Tiek apkopoti šādi lauki:

- **entryPoint** — virkne — poga/plūsma, no kuras tika parādīts Paywall. Piemēram, “Premium jaunināšanas poga” vai “Pirmās palaišanas plūsma”.

- **isDefaultSKU** — Būla vērtība, ja lietotājs iegādājas produktu, iesakām to darīt, parādot to pēc noklusējuma.

- **productId** — virkne — lietojumprogrammu veikala produkta ID, kam nospiesta poga Pirkt

- **toggleCount** — Int — to reižu skaits, kad lietotājs pārslēdzās starp dažādu produktu skatīšanu, pirms viņš pieskārās pogai Pirkt, pašreizējā Paywall sesijā.

### <a name="officeiospaywallsuccessscreenseeallbenefitsbuttontap"></a>Office.iOS.Paywall.SuccessScreen.SeeAllBenefitsButtonTap

Izmantojiet telemetriju, lai uzzinātu, kad pēc veiksmīga pirkuma lietotājs pieskaras pogai “Skatīt visus ieguvumus”, lai skatītu tikko veiktajā pirkumā iekļautās programmas un līdzekļus. Dati tiek izmantoti, lai palīdzētu izstrādāt uzlabojumus nākotnē, kas samazinātu lietotāju traucēšanu programmu atjaunināšanas laikā.

Tiek apkopoti šādi lauki.

- **productId** — virkne — produkta, kuram lietotājs skata visas piedāvātās priekšrocības, App Store ID


### <a name="officelicensingaccepteulaforcurrentlicense"></a>Office.Licensing.AcceptEulaForCurrentLicense 

Tas tiek apkopots, kad lietotājs tiek licencēts un akceptē EULA pašreizējai licencei

Tas tiek izmantots, lai noteiktu, vai lietotājs ir piemērotā stāvoklī, kas tiek izmantota sistēmas darbspējai un diagnostikas mērķiem, ja lietotājs ziņo par problēmu savā datorā

Tiek apkopoti tālāk norādītie lauki.

  - **ACID** — GUID identifikators, kas norāda Office produktu, kuram lietotājam ir licence

  - **DwEulaId** — EULA tipa, ko akceptēja lietotājs, skaitliskais identifikators

### <a name="officelicensingactivation"></a>Office.Licensing.Activation 

Pēc licences iestatīšanas datorā mēs mēģinām aktivizēt licenci, izsaucot AVS pakalpojumu. Tādējādi tiek norādīts aktivizācijas izsaukuma rezultāts

Tas ir kritiski svarīgi, lai noteiktu, cik lietotājiem rodas aktivizācijas problēmas. Lai konstatētu regresiju, izmantojam anomāliju noteikšanu. Tas ir ārkārtīgi svarīgi, jo mums ir ārēja atkarība no AVS, un šis signāls norāda, vai mūsu ārējie partneri ir darbspējīgi. Tas tiek izmantots arī diagnostikas mērķiem un sistēmas darbspējai, ja lietotājs ziņo par problēmu ar savu datoru

Tiek apkopoti tālāk norādītie lauki.

  - **Acid** — GUID identifikators, kas norāda Office produktu, kuram lietotājam ir licence

  - **ReferralData** — OEM, kas datorā instalēja sistēmu Office, identifikators

### <a name="officelicensingactivationwizard"></a>Office.Licensing.ActivationWizard 

Ja kāda iemesla dēļ nevaram automātiski aktivizēt licenci, lietotājam tiek rādīts aktivizācijas vednis. Tas norāda, ka lietotājam tiek rādīts vednis. Tas ir kritiski svarīgs, lai noteiktu, vai lietotājs ir piemērotā stāvoklī un vai tam netrūkst funkcionalitātes, kas tiek izmantota sistēmas darbspējai un diagnostikas mērķiem, ja lietotājs ziņo par problēmu savā datorā

Šis notikums neapkopo laukus.

### <a name="officelicensingdialogswebviewdialogclose"></a>Office.Licensing.Dialogs.WebViewDialog.Close
 
Šis notikums tiek izmantots kā signāls, kas informē mūs par to, ka pirkumu veikšanas programmā līdzekli aizver lietotājs vai programma. Šie dati tiek izmantoti, lai pārraudzītu un brīdinātu par pirkumu programmā plūsmas darbspēju, lai nodrošinātu tās darbību atbilstoši paredzētajam.  
 
Tiek apkopoti šādi lauki:
 
- **Data_ClosedDialog** — karodziņš, kas norāda, ka lietotājs aizvēra dialogu

### <a name="officelicensingdialogswebviewdialoghandleerrornotification"></a>Office.Licensing.Dialogs.WebViewDialog.HandleErrorNotification
 
Šis notikums tiek izmantots kā signāls, lai informētu mūs par to, ka notika pirkuma programmā līdzekļa ielādes mēģinājums, taču notika kļūda, kuras rezultātā dialoglodziņš netiek parādīts. Šie dati tiek izmantoti, lai pārraudzītu un brīdinātu par pirkumu programmā plūsmas darbspēju, lai nodrošinātu tās darbību atbilstoši paredzētajam.  
 
Tiek apkopoti tālāk norādītie lauki.
  
- **Data_MoeErrorCode** — kļūdas kods, kas ir redzams tīmekļa dialoga struktūrā

### <a name="officelicensingdialogswebviewdialogpreload"></a>Office.Licensing.Dialogs.WebViewDialog.Preload
 
Šis notikums tiek izmantots kā signāls, kas informē mūs par to, ka fonā tiek ielādēts līdzeklis pirkumu veikšanai programmā. Šie dati tiek izmantoti, lai pārraudzītu un brīdinātu par pirkumu programmā plūsmas darbspēju, lai nodrošinātu tās darbību atbilstoši paredzētajam.  
 
Tiek apkopoti tālāk norādītie lauki.

 - Nav

### <a name="officelicensingdialogswebviewdialogshow"></a>Office.Licensing.Dialogs.WebViewDialog.Show
 
Šis notikums tiek izmantots kā signāls, kas informē mūs par to, ka lietotājam tiek parādīts līdzeklis pirkumu veikšanai programmā. Šie dati tiek izmantoti, lai pārraudzītu un brīdinātu par pirkumu programmā plūsmas darbspēju.  

Tiek apkopoti tālāk norādītie lauki.

 - Nav

### <a name="officelicensingdialogswebviewdialogtimeout"></a>Office.Licensing.Dialogs.WebViewDialog.Timeout

Šis notikums tiek izmantots kā signāls, lai informētu mūs par to, ka notika līdzekļa pirkumu veikšanai programmā ielādes mēģinājums, taču tam iestājās noildze. Šie dati tiek izmantoti, lai pārraudzītu un brīdinātu par pirkumu programmā plūsmas darbspēju un nodrošinātu tās paredzēto darbību. 

Tiek apkopoti tālāk norādītie lauki.

 - Nav


### <a name="officelicensingenforcesigninqualified"></a>Office.Licensing.EnforceSignInQualified 

Šis signāls norāda, vai eksperiments, ko veicam, lai uzspiestu lietotāja parakstu kā daļu no licencēšanas, ir sekmīgs. Tas ir kritiski svarīgi, lai noteiktu eksperimenta, kas liek lietotājiem pieteikties un kas ir obligāts solis modernajam licencēšanas stekam, izdošanos vai neizdošanos. Ja neizdodas pierakstīties, lietotāji nevar izmantot programmu.

Tiek apkopoti tālāk norādītie lauki.

  - **Qualified** — norāda, vai lietotājs kvalificējās pierakstīšanās uzspiešanai

### <a name="officelicensingexpirationdialogshown"></a>Office.Licensing.ExpirationDialogShown

Tas tiek apkopots, kad tiek parādīts dialoglodziņš derīguma beigu datums lietotājam, kurš norāda, ka viņu licences derīguma termiņš ir beidzies. Tas ir kritiski svarīgs, lai noteiktu, vai lietotājs ir piemērotā stāvoklī un vai tam netrūkst funkcionalitātes, kas tiek izmantota sistēmas darbspējai un diagnostikas mērķiem, ja lietotājs ziņo par problēmu savā datorā

Tiek apkopoti tālāk norādītie lauki.

  - **LicNotificationState** — skaitītājs, kas mums norāda, kāda veida paziņojums tiek rādīts lietotājam

### <a name="officelicensingfullvalidation"></a>Office.Licensing.FullValidation 

Tas tiek apkopots katrā sesijā, kas ziņo datora licencēšanas stāvokli un kļūdas, kas lietotājam rodas un kuru dēļ tas nevar izmantot lietojumprogrammu. Šis notikums norāda, vai lietotāja dators ir darbspējīgs. Esam iestatījuši anomāliju noteikšanu šim notikumam, lai norādītu, vai regresija vai aktivizācijas mehānisms izraisa neatbilstošo lietotāju uzvedību. Tas ir arī kritiski svarīgi, kad tiek diagnosticētas lietotāja problēmas, kā arī sistēmas darbspējas pārraudzībai.

Tiek apkopoti tālāk norādītie lauki.

  - **Acid** — GUID identifikators, kas norāda Office produktu, kuram lietotājam ir licence 
  
  - **ActivationAttributes** — lietotāja izmantotā aktivizācijas mehānisma veids.

  - **IsSessionLicensing** — vai pašlaik strādājam koplietojamā datora aktivizācijas režīmā 

  - **LicenseCategory** — lietotāja izmantotās Office licences kategorija 

  - **Licenses** — visu datorā esošo Office licenču nosaukumu saraksts 

  - **LicenseStatuses** — visu datorā esošo Office licenču statuss 

### <a name="officelicensinggetentitlement"></a>Office.Licensing.GetEntitlement 

Mēs to apkopojam, kad lietotājs iestata ierīci un mēs izsaucam mūsu licencēšanas pakalpojumu, lai noteiktu, vai lietotājam, kas ir pieteicies, ir Office tiesības. Tādējādi tiek norādīts attiecīgā izsaukuma rezultāts Tas ir kritiski svarīgs, lai noteiktu, vai lietotājs ir piemērotā stāvoklī un vai tam trūkst funkcionalitātes, kas tiek izmantota sistēmas darbspējai un diagnostikas mērķiem, ja lietotājs ziņo par problēmu savā datorā

Tiek apkopoti tālāk norādītie lauki:

- **EntitlementCount** — lietotājam piešķirto pilnvaru skaits


### <a name="officelicensingheartbeat"></a>Office.Licensing.Heartbeat 

Katrā sesijā pārbaudām, vai ir pagājušas 72 stundas kopš pēdējās licences atjaunošanas, un mēģinām pagarināt pašreizējās licences derīguma termiņu. Šis notikums ziņo par izsaukuma, ko veicam, lai nodrošinātu, ka varam pagarināt licences derīguma termiņu un uzturēt lietotāja Office instalācijas funkcionalitāti, sekmīgu izpildi vai kļūmi. Tas ir kritiski svarīgi, lai diagnosticētu ar abonementu saistītas problēmas un pakalpojumu problēmas lietotājam, kā arī ir kritiski svarīgi, lai noteiktu regresiju jau aktivizēto abonementu lietotājiem.

Tiek apkopoti tālāk norādītie lauki.

  - **Mode** — šajā datorā izmantotā Office licencēšanas steka skaitītāja attēlojums

### <a name="officelicensinginclientpinredemptioncallpinredemptionapi"></a>Office.Licensing.InClientPinRedemption.CallPinRedemptionAPI

Šī telemetrija izseko Office PIN izpirkšanas pakalpojuma zvana rezultātus.

Tiek apkopoti šādi lauki:

- **ClientTransactionId** — unikāls pakalpojuma zvana identifikators.

- **ErrorCategory** — katrs kļūdas tips var ietilpt vispārīgākā kategorijā, piemēram, "Atkārtojams".

- **ErrorType** — kļūmes iemesls, piemēram, "AlreadyRedeemedByOther".

- **InAFOFlow** — Būla izteiksme, kas norāda, vai mēs esam AFO izpirkšanas plūsmā.

- **StatusCode** — viena vārda pakalpojuma zvana rezultāts, piemēram, "Izveidots".

- **StatusMessage** — statusa koda detalizētā informācija, piemēram, "Veiksmīgi nodrošināta".

- **UsingNulApi** — Būla izteiksme, kas norāda, vai mēs izmantojam jauno licencēšanas steku.

### <a name="officelicensinginrfm"></a>Office.Licensing.InRFM 

Ja ierīce pāriet samazinātas funkcionalitātes režīmā, mēs izsūtām šo signālu, lai norādītu, ka iekārta nav darbspējīgā stāvoklī. Tas ir kritiski svarīgs, lai noteiktu, vai lietotājs ir piemērotā stāvoklī un vai tam trūkst funkcionalitātes, kas tiek izmantota sistēmas darbspējai un diagnostikas mērķiem, ja lietotājs ziņo par problēmu savā datorā

Tiek apkopoti tālāk norādītie lauki.

  - **ACID** — GUID identifikators, kas norāda Office produktu, kuram lietotājam ir licence

  - **DaysRemaining** — atlikušais dienu skaits pirms pašreizējās Office licences derīguma beigām

  - **Mode** — šajā datorā izmantotā Office licencēšanas steka skaitītāja attēlojums

  - **ProductName** — produkta, ko lietotājs pašlaik izmanto, nosaukums

  - **Reason** — kļūdas kods, kas norāda pašreizējā licences statusa iemeslu

### <a name="officelicensinginstallkey"></a>Office.Licensing.InstallKey

Tas tiek apkopots, kad mēģinām ierīcē instalēt atslēgu, lai datoru licencētu. Tas ziņo, vai instalēšana bija sekmīga un, ja tā nebija, norāda kļūdas kodu. Tas ir kritiski svarīgs, lai noteiktu, vai lietotājs ir piemērotā stāvoklī un vai tam netrūkst funkcionalitātes, kas tiek izmantota sistēmas darbspējai un diagnostikas mērķiem, ja lietotājs ziņo par problēmu savā datorā

Tiek apkopoti tālāk norādītie lauki.

  - **Prid** — produktu grupas, kurai tiek instalēta atslēga, nosaukums

  - **SkuId** — GUID identifikators, kas atspoguļo Office produktu, kuram tiek instalēta atslēga 

### <a name="officelicensinginvokelicensewizard"></a>Office.Licensing.InvokeLicenseWizard

Ja rodas problēmas ar aktivizācijas darbplūsmu, mēs aktivizējam licenču vedni un nosūtīsim šo signālu, lai norādītu vienu un to pašu. Tas ir kritiski svarīgs, lai noteiktu, vai lietotājs ir piemērotā stāvoklī un vai tam netrūkst funkcionalitātes, kas tiek izmantota sistēmas darbspējai un diagnostikas mērķiem, ja lietotājs ziņo par problēmu savā datorā

Tiek apkopoti tālāk norādītie lauki.

  - **Acid** — GUID identifikators, kas norāda Office produktu, kuram lietotājam ir licence

  - **LicenseStatus** — lietotāja izmantotās Office licences statuss

  - **MachineKey** — lietotājam izsniegtās licences atslēgas burtciparu identifikators

### <a name="officelicensinglicensingbar"></a>Office.Licensing.LicensingBar

Ja ierīcei rodas licencēšanas problēmas un lietotājam tiek rādīta kopnes josla, izsūtām šo signālu, kas arī ziņo par kopnes joslas veidu, kas tiek rādīta lietotājam. Tas ir kritiski svarīgs, lai noteiktu, vai lietotājs ir piemērotā stāvoklī un vai tam netrūkst funkcionalitātes, kas tiek izmantota sistēmas darbspējai un diagnostikas mērķiem, ja lietotājs ziņo par problēmu savā datorā.

Tiek apkopoti tālāk norādītie lauki.

  - **SuppressNotification** — norāda, vai apspiedām licencēšanas kopnes joslu

  - **Title** — licencēšanas kopnes joslas, kas tika rādīta lietotājam, nosaukums

  - **Type** — licencēšanas kopnes joslas, kas tiek rādīta lietotājam, veids

### <a name="officelicensinglicexitofficeprocess"></a>Office.Licensing.LicExitOfficeProcess 

Ja sistēmas Office darbība tiek beigta vai tā avarē licencēšanas kļūdas dēļ, mēs izsūtām šo signālu, lai norādītu to pašu. Tas ir kritiski svarīgs, lai noteiktu, vai lietotājs ir piemērotā stāvoklī un vai tam netrūkst funkcionalitātes, kas tiek izmantota sistēmas darbspējai un diagnostikas mērķiem, ja lietotājs ziņo par problēmu savā datorā.

Tiek apkopoti tālāk norādītie lauki.

  - **ExitCode** — iekšējais kods, kas izraisīja lietojumprogrammas izeju

### <a name="officelicensingloadidentityticket"></a>Office.Licensing.LoadIdentityTicket

Mēģinot ierīci licencēt, lietojumprogramma mēģina ielādēt lietotāja identitāti, lai noskaidrotu, vai lietotājam ir Office tiesības. Šis notikums ziņo par sekmīgu izpildi vai kļūmi kopā ar attiecīgā pakalpojuma izsaukuma kļūdas kodu. Tas ir kritiski svarīgs, lai noteiktu, vai lietotājs ir piemērotā stāvoklī un vai tam netrūkst funkcionalitātes, kas tiek izmantota sistēmas darbspējai un diagnostikas mērķiem, ja lietotājs ziņo par problēmu savā datorā.

Tiek apkopoti tālāk norādītie lauki.

  - **FederationProvider** — virkne, kas norāda federācijas nodrošinātāju lietotājam, kurš pašlaik ir pieteicies

  - **IdentityProvider** — virkne, kas norāda identitātes nodrošinātāju lietotājam, kurš pašlaik ir pieteicies

### <a name="officelicensinglvuxeulaexplicitcrash"></a>Office.Licensing.LVUX.EULAExplicitCrash 

Tas tiek apkopots, ja lietotājam tika rādīts EULA un lietotājs izvēlējās to neakceptēt, līdz ar to lietojumprogramma avarē/tiek aizvērta. Tas ir kritiski svarīgs, lai noteiktu, vai lietotājs ir piemērotā stāvoklī un vai tam netrūkst funkcionalitātes, kas tiek izmantota sistēmas darbspējai un diagnostikas mērķiem, ja lietotājs ziņo par problēmu savā datorā.

Tiek apkopoti tālāk norādītie lauki.

  - **Acid** — GUID identifikators, kas norāda Office produktu, kuram lietotājam ir licence

  - **OptInShown** — norāda, vai piekrišanas dialogs, kas tiek rādīts lietojumprogrammas pirmajā sāknēšanas reizē, jau ir rādīts

### <a name="officelicensingnextuserlicensingeligible"></a>Office.Licensing.NextUserLicensingEligible 

Šis signāls mums norāda, vai lietotājs ir kvalificēts pāriet uz mūsu jauno licencēšanas steku. Tas ir kritiski svarīgi, lai kvantificētu ietekmi uz esošajiem lietotājiem, kamēr ieviešam mūsu jauno licencēšanas steku un nodrošinām, ka lietotājiem nezūd funkcionalitāte.

Šis notikums neapkopo laukus.

### <a name="officelicensingnulfetcherfetchmodelfromols"></a>Office.Licensing.Nul.Fetcher.FetchModelFromOls

Ja ierīce izmanto moderno licencēšanas steku, mēģinām iegūt licences failu tieši no pakalpojuma. Šis notikums ziņo par sekmīgu izpildi vai kļūmi kopā ar attiecīgā pakalpojuma izsaukuma kļūdas kodu. Tas ir kritiski svarīgi, lai noteiktu, vai lietotājs ir piemērotā stāvoklī modernajā licencēšanas stekā, kas tiek izmantots sistēmas darbspējai un diagnostikas mērķiem, ja lietotājs ziņo par problēmu savā datorā.

Tiek apkopoti šādi lauki:

  - **MetadataValidationResult** — licences metadatu pārbaudes rezultāts, lai verificētu, ka tā nav ietekmēta

  - **SignatureValidationResult** — licences paraksta pārbaudes rezultāts, lai verificētu, ka tā nav ietekmēta

### <a name="officelicensingnulvalidationfullvalidation"></a>Office.Licensing.Nul.Validation.FullValidation 

Tas tiek apkopots katrā ierīces sesijā, kas darbojas modernajā licencēšanas stekā. Ziņo datora licencēšanas stāvokli un kļūdas, kas lietotājam rodas un kuru dēļ tas nevar izmantot programmu. Šis notikums norāda, vai lietotāja dators ir darbspējīgs. Esam iestatījuši anomāliju noteikšanu šim notikumam, lai norādītu, vai regresija izraisa neatbilstošo lietotāju uzvedību. Tas ir arī kritiski svarīgi, kad tiek diagnosticētas lietotāja problēmas, kā arī sistēmas darbspējas pārraudzībai.

Tiek apkopoti tālāk norādītie lauki.

  - **Acid** — GUID identifikators, kas norāda Office produktu, kuram lietotājam ir licence 

  - **AllAcids** — visu produkta GUID saraksts, kam lietotājam pašlaik ir licence 

  - **Category** — lietotāja izmantotās Office licences kategorija 

  - **DaysRemaining** — atlikušais dienu skaits pirms pašreizējās Office licences derīguma beigām 

  - **LicenseId** — lietotājam izsniegtās licences burtciparu identifikators 

  - **LicenseType** — lietotāja izmantotās Office licences veids 

### <a name="officelicensingofficeclientlicensingdolicensevalidation"></a>Office.Licensing.OfficeClientLicensing.DoLicenseValidation 

Tie ir licencēšanas metadati, kas tiek apkopoti no ierīces katrā sāknēšanas reizē, kas ziņo licences ACID, licences statusu, veidu un citus licences rekvizītus, kas ir kritiski svarīgi, lai identificētu līdzekļus, kas ir iestatīti kā pieejami lietotājam. Tas ir kritiski svarīgi, lai identificētu līdzekļu kopu, kas ir pieejama lietotājam, un vai lietotājam trūkst kāda funkcionalitāte. Tas tiek izmantots arī dienas aktīvo lietotāju/mēneša aktīvo lietotāju aprēķiniem un dažādām citām atskaitēm, ko izmanto dažādas grupas sistēmā Office, jo tas norāda tipa produktu, ko lietotājs izmanto, vai tas ir abonementa produkts un vai tam trūkst kāda kritiski svarīga funkcionalitāte.

Tiek apkopoti tālāk norādītie lauki.

  - **FullValidationMode** — režīms, kas norāda, ka veicam pilnīgu licences verifikācijas pārbaudi 

  - **IsRFM** — norāda, vai lietotājam ir samazinātas funkcionalitātes līmenis 

  - **IsSCA** — norāda, vai strādājam koplietojamā datora aktivizācijas režīmā 

  - **IsSubscription** — norāda, vai lietotājs izmanto abonementa licenci 

  - **IsvNext** — norāda, vai izmantojam jauno moderno licencēšanas steku 

  - **LicenseCategory** — lietotāja izmantotās Office licences kategorija 

  - **LicenseStatus** — lietotāja izmantotās Office licences statuss 

  - **LicenseType** — lietotāja izmantotās Office licences veids 

  - **LicensingACID** — GUID identifikators, kas norāda Office produktu, kuram lietotājam ir licence 

  - **OlsLicenseId** — lietotājam izsniegtās licences burtciparu identifikators 

  - **SkuIdIsNull** — norāda, vai radās kļūda un nezinām produktu, ko lietotājs izmanto 

  - **SlapiIsNull** — norāda, vai radās problēma, aizpildot kādu licencēšanas objektu 

### <a name="officelicensingonlinerepair"></a>Office.Licensing.OnlineRepair 

Ja kāda iemesla dēļ nevaram aktivizēt lietotāju un tam ir jārāda dialogs, kurā tiek lūgts pāriet tiešsaistē un mēģināt veikt labošanas darbības, tiek aktivizēts šis notikums. Tas ir kritiski svarīgs, lai noteiktu, vai lietotājs ir piemērotā stāvoklī un vai tam netrūkst funkcionalitātes, kas tiek izmantota sistēmas darbspējai un diagnostikas mērķiem, ja lietotājs ziņo par problēmu savā datorā

Šis notikums neapkopo laukus.

### <a name="officelicensingoobetrybuychoice"></a>Office.Licensing.OOBE.TryBuyChoice

Lietotāji, kuriem ir sākotnēji instalēta sistēma Office jaunos datoros, kuriem nav tiesību uz Office, tiek parādīts dialoglodziņš, ar ko viņi var izmēģināt, iegādāties vai ievadīt produkta kodu, lai saņemtu licenci. Šis notikums ietver lietotāja darbību dialoglodziņā. Šis notikums tiek lietots, lai izsekotu lietotāja darbību, kas tiek veikta, kad tiek parādīts dialoglodziņš lietotājiem, kuriem nav Office tiesību, kur sistēma Office tika sākotnēji instalēta datorā, un tas palīdz noteikt, vai lietotājs ir licencēts vai nelicencēts, izmantojot noformēšanu.

Tiek apkopoti tālāk norādītie lauki:

- **Buy** — norāda, vai lietotājs noklikšķināja uz pogas iegādāties vai nē

- **ForceAutoActivate** — norāda, vai ir jāveic vai nav jāveic programmas aktivizācija

- **GoBackToSignIn** — norāda, vai lietotājs vēlas pierakstīties vēlreiz (iespējams, ar citu kontu)

- **IsPin** — norāda, vai lietotājs ir ievadījis PIN

- **ProductKey** — norāda, vai lietotājs mēģināja ievadīt produkta kodu

- **Try** — norāda, vai lietotājs noklikšķināja uz pogas izmēģināt vai nē

- **UserDismissed** — norāda, vai lietotājs ir noraidīja dialogu, un tāpēc būtu pagarinātas vai samazinātas funkcionalitātes režīmā, jo viņi neizvēlas iegādāties Office vai saņemt izmēģinājumversiju

### <a name="officelicensingpurchase"></a>Office.Licensing.Purchase 

*[Šis notikums ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

Veicam eksperimentu, kas lietotājam sniedz iespēju izmēģināt un iestatīt automātisko maksāšanu par Office tieši no lietojumprogrammas, neizejot no lietojumprogrammas konteksta. Tas ziņo par šī eksperimenta sekmīgu izpildi vai kļūmi kopā ar kļūdas kodu. Tas ir kritiski svarīgi, lai noteiktu, vai lietotājs ir piemērotā stāvoklī un vai tam netrūkst funkcionalitātes, kas tiek izmantota sistēmas darbspējai un diagnostikas mērķiem, ja lietotājs ziņo par problēmu savā datorā.

Tiek apkopoti šādi lauki:

  - **StorePurchaseStatus** — atspoguļo pirkuma izsaukuma, kas tika veikts, izmantojot Windows Store, kļūdas kodu/sekmīgas izpildes kodu

### <a name="officelicensingsearchforsessiontoken"></a>Office.Licensing.SearchForSessionToken

Ja lietotājs strādā koplietojama datora aktivizācijas režīmā, mēs mēģinām meklēt sesijas marķieri datorā, kas lietotājam sniedz iespēju izmantot lietojumprogrammu. Šis notikums ziņo par scenārija sekmīgu izpildi vai kļūmi kopā ar kļūdas kodu. Tas ir kritiski svarīgs, lai noteiktu, vai lietotājs ir piemērotā stāvoklī un vai tam netrūkst funkcionalitātes, kas tiek izmantota sistēmas darbspējai un diagnostikas mērķiem, ja lietotājs ziņo par problēmu savā datorā.

Tiek apkopoti tālāk norādītie lauki.

  - **LoadLicenseResult** — atspoguļo kļūdas kodu/sekmīgas izpildes kodu attiecībā uz to, vai spējām ielādēt licences pašreizējam lietotājam

  - **OpportunisticTokenRenewalAttempted** — norāda, vai mēģinājām atjaunot lietotāja sesijas marķieri oportūnistiski

  - **SetAcidResult** — atspoguļo kļūdas kodu/sekmīgas izpildes kodu attiecībā uz to, vai spējām iestatīt ACID uz paredzēto vērtību

### <a name="officelicensingshownewdeviceactivationdialog"></a>Office.Licensing.ShowNewDeviceActivationDialog

Office lietojumprogrammas pirmajā sāknēšanas reizē mēs mēģināsim rādīt pierakstīšanās dialogu, kas iepriekš aizpildīts ar akreditācijas datiem, ko lietotājs izmantojat, lai lejupielādētu Office. Lietotājs pēc tam var turpināt pierakstīšanos ar šiem akreditācijas datiem, izmantot citus akreditācijas datus vai noraidīt dialogu. Šis notikums ziņo par lietotāja veikto darbību, kad tiek parādīts šis dialogs. Tas ir kritiski svarīgi, lai noteiktu, vai lietotājs ir piemērotā stāvoklī modernajā licencēšanas stekā, kas tiek izmantots sistēmas darbspējai un diagnostikas mērķiem, ja lietotājs ziņo par problēmu savā datorā

Tiek apkopoti tālāk norādītie lauki.

  - **UserAction** — lietotāja veiktās darbības, kad tiek parādīts šis dialogs, identifikators.

### <a name="officelicensingskutoskuconversion"></a>Office.Licensing.SkuToSkuConversion

Licencējot lietotāju, ja mums ir jāmaina lietotāja SKU uz citu, mēs izsūtām šo signālu kopā ar sekmīgas izpildes vai kļūmes kodu. Tas ir kritiski svarīgs, lai noteiktu, vai lietotājs ir piemērotā stāvoklī un vai tam trūkst funkcionalitātes, kas tiek izmantota sistēmas darbspējai un diagnostikas mērķiem, ja lietotājs ziņo par problēmu savā datorā.

Tiek apkopoti tālāk norādītie lauki.

  - **DestinationSku** — tās SKU nosaukums, uz kuru pašlaik instalētais produkts ir jākonvertē

  - **PendingAcid** — tā produkta ID, kam ir nepabeigta SKU konvertēšana

  - **SourceSku** — sākotnējās SKU, kas tika instalēta datorā, nosaukums

  - **UninstallProduct** — norāda, vai vecais produkts konvertēšanas ietvaros tiks atinstalēts

### <a name="officelicensingtelemetryflowolsresults"></a>Office.Licensing.TelemetryFlow.OLSResults

Kad lietotājs ir nelicencēts, mēs veicam vairākas pakalpojuma zvanus, lai lietotājam tiktu piešķirta licence, un lai aktivizētu savu Office produktu.  Šis notikums tiek izraisīts, zvanot Office licencēšanas pakalpojumam, lai pārbaudītu, vai lietotājam ir pilnvaras.  Šis pasākums tiks lietots, lai izsekotu lietotāja licencēšanas statusam pēc tam, kad tiek piezvanīts Office licencēšanas pakalpojumam un Office klienta statusam pēc mēģinājuma aktivizēt Office.

Tiek apkopoti tālāk norādītie lauki:

- **EntitlementPickerShown** — norāda, vai lietotājam ir vairākas pilnvaras, un vai lietotājam bija manuāli jāizvēlas no tām, lai saņemtu licenci

- **GetAuthResult** — norāda dažādus stāvokļus, kādos jūsu klients var būt, piemēram, ja iegādājās tukšu produkta kodu no Office licencēšanas pakalpojuma, vai ja bija tiesības izmantot citu produktu un Office ir jāpārvērš par jauno produktu

- **EntitlementCount** — norāda lietotājam piešķirto pilnvaru skaitu

- **GetEntitlementsSucceeded** — norāda, vai zvans uz Office licencēšanas pakalpojumu API, lai izgūtu lietotāja pilnvaras, ir sekmīgs vai nē

- **GetKeySucceeded** — norāda, vai zvans uz Office licencēšanas pakalpojumu API, lai izgūtu produkta kodu, ir sekmīgs vai nē

- **GetNextUserLicenseResult** — norāda, vai modernais licencēšanas steks varēja darboties, un vai lietotājam tika piešķirta licence vai nē

- **InstallKeyResult** — norāda dažādus iemeslus, kāpēc lietotājs var būt sliktā stāvoklī, piemēram, ja aktivizācija neizdevās vai produkta koda instalēšana neizdevās

- **NotInitializedBeforeWhileAdding** — šis ir tikai informatīvs, un norāda, vai notikums ir pievienots telemetrijas pārvaldnieka kartei tieši nereģistrējoties

- **NotInitializedBeforeWhileSending** — šis ir tikai informatīvs, un norāda, vai tika mēģināts nosūtīt notikumu, pirms tam neveicot tiešu reģistrēšanos telemetrijas pārvaldnieka kartē

- **SentOnDestruction** — šis ir tikai informatīvs, un norāda, vai notikums ir pievienots telemetrijas pārvaldnieka kartei tieši nereģistrējoties un netika nosūtīts tieši

- **Tag** — tiek lietota, lai iegūtu informāciju par to, kur kods ir nosūtīts no

- **VerifyEntitlementsResult** — norāda dažādus stāvokļus, kādos lietotājs var būt pēc tam, kad ir apstiprinātas pilnvaras, kas izgūtas no Office licencēšanas pakalpojuma

### <a name="officelicensingtelemetryflowsearchforbindingresult"></a>Office.Licensing.TelemetryFlow.SearchForBindingResult

OEM pārdod iekārtas, kurās ietilpst Office (viena gada abonementi vai mūžīgi).  Šie Office produkti tiek apmaksāti, kad klients iegādājas savu iekārtu. Iekārtās, kurās ir iestatīta īpaša reģistra atslēga (OOBEMode: OEMTA), iespējams, ir ar to saistīts Office.  Kad sāknējam Office šādās iekārtās, mēs veicam pakalpojumu pārbaudes, lai noskaidrotu, vai atrasta Office saistība, kas atbilst iekārtai.

Šīs telemetrijas darbības izseko veiksmes un neveiksmes punktus, meklējot sasaisti, lai mēs varētu nodrošināt, ka iekārtas, kurās ir sasaiste, var tos veiksmīgi ienest, un šie pakalpojumi ir darbspējīgi.  Šī darbība neizseko iekārtas, kuriem nav saistījumu ar tām pēc tam, kad esam pārbaudījuši ar saviem pakalpojumiem.

Tiek apkopoti šādi lauki:

- **DexShouldRetry** — signāls, ka esam saskārušies ar atkārtojuma problēmu (internets vai serveri nedarbojas)

- **GenuineTicketFailure** — norāda kļūmi HRESULT, kas rodas, mēģinot iegūt iekārtas Windows orģināla biļeti/produkta atslēgu (WPK).

- **PinValidationFailure** — norāda, kāpēc PIN validācijas process neizdevās. Iespējamās kļūdas:
    - GeoBlocked
    - InvalidFormat
    - InvalidPin
    - InvalidState
    - InvalidVersion
    - Unknown
    - Used

- **PinValidationResult** — norāda PIN validācijas rezultātu, ko neizdevās atkost.

- **Pkpn** — Pkpn diapazons, kuram pieder PIN.

- **Success** — norāda, ka mēs sekmīgi ienesām derīgu Office piesaisti (PIN) iekārtai.

- **Tag** — norāda, kurā solī apstājāmies meklēt sasaistīšanu. Iespējamie tagi:
  - 0x03113809  nav interneta savienojuma/pakalpojuma kļūdas, pārbaudot PIN
  - 0x0311380a PIN validācijas kļūme, nosūtīta ar PinValidationFailure lauku
  - 0x0310410f  izdevās, nosūtīts ar panākumu lauku
  - 0x0311380d  kļūdu novēršana (interneta problēmas, nezināmas kļūdas)
  - 0x0311380e  neiespējamu atkārtotu mēģinājumu kļūdas (saistošais piedāvājums beidzies)
  - 0x0311380f   citas kļūdas (nav iespējams licencēt)
  - 0x03104111  neizdevās atkost Office PIN, kas nosūtīts ar PinValidationResult lauku

- **WpkBindingFailure** — norāda kļūdas kodu, lai iegūtu Office PIN, kas saistīts ar ierīces WPK.

### <a name="officelicensingtelemetryflowshowafodialogs"></a>Office.Licensing.TelemetryFlow.ShowAFODialogs

Pēc sekmīgas Office PIN iegūšanas, kas ir saistīts ar iekārtu un iepriekš sasaistīts ar Office, mēs parādīsim lietotājam pierakstīšanās dialogu vai izpirkšanas dialogu.  Kad PIN kods ir izpirkts, tiek parādīts dialoglodziņš EULA.  Kā daļu no mūsu modernizācijas AFO līdzekļa mēs atsvaidzinājām abus dialogus, lai sniegtu papildinformāciju par Office produktu, kas ir komplektā ar iekārtu.  Šie telemetrijas dati seko, ja mūsu līdzeklis sekmīgi samazina lietotāju neērtības, izsekojot izpirkšanas procesa plūsmas un iziešanas punktus (kurš dialoglodziņš ir noraidīts).

Tiek apkopoti šādi lauki:

- **ActionActivate** — signāls, ko lietotājs ir noklikšķinājis uz pogas “Activate” (Aktivizēt).

- **ActionChangeAccount** — signāls, ka lietotājs ir noklikšķinājis uz hipersaites “Use a different account” (Izmantot citu kontu).

- **ActionCreateAccount** — signāls, ka lietotājs ir noklikšķinājis uz pogas “Create account” (Izveidot kontu).

- **ActionSignIn** — signāls, ka lietotājs ir noklikšķinājis uz pogas “Sign in” (Pierakstīties).

- **CurrentView** — tā dialoga tips, kuru lietotājs aizvēris.

- **DialogEULA** — signāls, kas parādīja dialogu ‘Accept EULA’ (Akceptēt EULA). 

- **DialogRedemption** — signāls, kas parādīja AFO izpirkšanas dialogu.

- **DialogSignIn** — signāls, kas parādīja AFO pierakstīšanās dialogu.

- **EmptyRedemptionDefaults** — signāls, ka nav izdevies saņemt noklusējuma izpirkšanas informāciju.
 
- **GetRedemptionInfo** — signāls, ka tiek iegūta demogrāfiskā informācija par PIN izpirkšanu.

- **MalformedCountryCode** — signāls, ka valsts kods, kas nepieciešams PIN izpirkšanai, ir nepareizs.

- **OExDetails** — detalizēta informācija par kļūdu, kas tiek atgriezta, kad tiek noraidīts identitātes pierakstīšanās dialogs.

- **OExType** — detalizēta informācija par kļūdu, kas tiek atgriezta, kad tiek noraidīts identitātes pierakstīšanās dialogs.

- **Tag** — norāda, kurā solī lietotājs iziet no AFO izpirkšanas procesa. Iespējamie tagi:
    - 0x0311380b    lietotājs noraidīja identitātes pierakstīšanās dialoglodziņu no izpirkšanas dialoglodziņa
    - 0x0311380c    neizdevās automātiski ielādēt identitāti pēc lietotāja pierakstīšanās no izpirkšanas dialoglodziņa
    - 0x03113810    neizdevās ielādēt konta demogrāfisko informāciju (valsts kodu, valodu, valūtu, izmēģinājuma piedāvājumu un mārketinga preferences)
    - 0x03113805    lietotājs noraidīja identitātes pierakstīšanās dialoglodziņu no pierakstīšanās dialoglodziņa
    - 0x03113806    neizdevās automātiski ielādēt identitāti pēc lietotāja pierakstīšanās no pierakstīšanās dialoglodziņa
    - 0x03113807    neizdevās automātiski ielādēt identitāti
    - 0x03113811    lietotājs aizvēra dialoglodziņu pierakstīšanās/izpirkšana
    - 0x03113812    lietotājs aizvēra akceptēt EULA dialoglodziņu
    - 0x03113808    lietotājs akceptēja EULA līgumu
    - 0x03113811      lietotājs aizvēra dialogu
    - 0x2370e3a0      lietotājs aizvēra dialogu
    - 0x2370e3c1      doties uz tīmekli, lai saņemtu PIN izpirkšanu
    - 0x2370e3a1      doties uz tīmekli, lai saņemtu PIN izpirkšanu
    - 0x2370e3c0      dialoga secība tika cikliski atkārtota, ko izraisa lietotājs, pārejot uz priekšu un atpakaļ dialogā plūsma
    - 0x2370e3a3      lietotājs noklikšķināja uz hipersaites “Not now” (Ne tagad), kas izlaiž AFO piedāvājumu tai sesijai
    - 0x2370e3a2      lietotājs noklikšķināja uz hipersaiti “Never show this to me” (Nekad nerādīt šo iespēju), kas atspējo AFO piedāvājumu


- **UseInAppRedemption** — norāda mums, vai mēs palīdzam lietotājiem programmā izpirkšanai vai nosūtīšanai uz tīmekļa vietni, lai izmantotu to ienesto PIN (iepriekš aizpildītu).

- **UseModernAFO** — norāda mums, vai izmantojat jauno vai veco AFO pieredzi.

### <a name="officelicensingtelemetryflowshowtrybuydialogforoobe"></a>Office.Licensing.TelemetryFlow.ShowTryBuyDialogForOOBE

Kad jaunās iekārtās ir instalēts Office, bet lietotājam nav pilnvaru, tiek parādīts dialoglodziņš, kurā lietotājam tiek piedāvāts izmēģināt, iegādāties vai ievadīt produkta kodu, lai lietotājs varētu saņemt licenci, un šis notikums seko, vai tiek parādīts dialoglodziņš. Šis pasākums palīdzēs saprast, vai dialoglodziņš bija redzams lietotājam, lai izmēģinātu, iegādātos vai ievadītu produkta kodu, un tādējādi palīdzēs mums noteikt, vai lietotājam bija iespēja saņemt licenci.

Tiek apkopoti šādi lauki: 

- **ActiveView** — norāda lietotājam redzamā dialoglodziņa ID

- **CurrentOOBEMode** — norāda pirmsinstalēšanas režīmu (OOBE režīmu, piemēram, AFO, OEM u.c.)

- **NotInitializedBeforeWhileAdding** — šis ir tikai informatīvs, un norāda, vai notikums ir pievienots telemetrijas pārvaldnieka kartei tieši nereģistrējoties

- **SentOnDestruction** — šis ir tikai informatīvs, un norāda, vai notikums ir pievienots telemetrijas pārvaldnieka kartei tieši nereģistrējoties un netika nosūtīts tieši

- **ShowTryButton** — norāda, vai izmēģināšanas poga bija redzama lietotājam dialoglodziņā vai nē

- **Tag** — tiek lietota, lai iegūtu informāciju par to, kur kods ir nosūtīts no

### <a name="officelicensingtelemetryflowtrialflow"></a>Office.Licensing.TelemetryFlow.TrialFlow

Ja lietotājs ar nelicencētu Office, kas iepriekš ir instalēts iekārtā, mēģina saņemt izmēģinājumversiju, tiek aktivizēts šis notikums.  Tas tiek izmantots, lai redzētu, kurš lietotājs sekos, lai saņemtu izmēģinājumversiju, un vai rodas kļūdas, mēģinot saņemt izmēģinājumversiju, izmantojot programmas pirkumus.  Atkarībā no lietotāja darbības un programmas iegādes rezultāta lietotājs var netikt licencēts.

Tiek apkopoti šādi lauki:

- **HasConnectivity** — norāda, vai lietotājam ir interneta savienojums, un gadījumā, ja lietotājam nav, iespējams, ir jāizmanto pagarinājuma licence piecu dienu laikā, vai, iespējams, darbojas samazinātas funkcionalitātes režīmā

- **InAppTrialPurchase** — norāda, vai ir iespējots lidojums veikala iegādes SDK palaišanai, lai tvertu PI un iegādātos izmēģinājumversiju programmā *[Šis lauks ir noņemts no pašreizējiem Office būvējumiem, bet, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

- **IsRS1OrGreater** — norāda, vai operētājsistēmas versija ir lielāka par RS1 vai nav, jo veikala iegādes SDK ir jāizmanto tikai tad, ja OS versija ir lielāka RS1

- **NotInitializedBeforeWhileAdding** — tikai informatīvs, un norāda, vai notikums ir pievienots telemetrijas pārvaldnieka kartei tieši nereģistrējoties

- **OEMSendToWebForTrial** — norāda, vai lidojums ir iespējots, lai nosūtītu lietotājus uz tīmekļa vietni un izpirktu izmēģinājumversiju

- **StoreErrorConditions** — norāda dažādus nosacījumus, saskaņā ar kuriem veikalu iegādes SDK varētu neizdoties *[Šis lauks ir noņemts no pašreizējiem Office būvējumiem, bet, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

- **StoreErrorHResult** — norāda kļūdas kodu no veikalu iegādes SDK *[Šis lauks ir noņemts no pašreizējiem Office būvējumiem, bet, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

- **StorePurchaseStatusResult** — norāda, kā tiek zvanīts veikala iegādei SDK, un, ja lietotājs ir veicis pirkumu vai nē, kas palīdzēs noteikt, vai lietotājam ir jābūt licencētam izmantot Office *[Šis lauks ir noņemts no pašreizējiem Office būvējumiem, bet, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

- **Tag** — tiek lietota, lai iegūtu informāciju par to, kur kods ir nosūtīts no

- **UserSignedInExplicitly** — norāda, vai lietotājs ir pierakstījies tieši. Šādā gadījumā mēs atkārtoti novirza lietotājus uz tīmekļa vietni izmēģinājumversijai *[Šis lauks ir noņemts no pašreizējiem Office būvējumiem, bet, iespējams, joprojām tiks rādīts vecākos būvējumos.]*

### <a name="officelicensingusegracekey"></a>Office.Licensing.UseGraceKey

Ja kāda iemesla dēļ nevaram lietotāju licencēt, instalējam pagarinājuma atslēgu un izsūtām signālu, kas to paziņo. Tas ir kritiski svarīgs, lai noteiktu, vai lietotājs ir piemērotā stāvoklī un vai tam trūkst funkcionalitātes, kas tiek izmantota sistēmas darbspējai un diagnostikas mērķiem, ja lietotājs ziņo par problēmu savā datorā

Tiek apkopoti tālāk norādītie lauki.

  - **OpportunisticTokenRenewalAttempted** — norāda, vai mēģinājām oportūnistisku atjaunošanu lietotājam koplietojamā datora aktivizācijas režīmā

  - **ReArmResult** — norāda instalētās atslēgas atkārtotu aktivizēšanu, kas var pagarināt pašreizējās licences derīgumu

### <a name="onenoteenrollmentresult"></a>OneNote.EnrollmentResult
 
Šis notikums reģistrē statusu pēc Intune reģistrēšanas.  Šis scenārijs ir raksturīgs tikai Intune iespējotiem kontiem.
 
Tiek apkopoti tālāk norādītie lauki:
 
- **EnrollmentResult** — Intune reģistrācijas rezultāts

## <a name="microsoft-autoupdate-mau-events"></a>Microsoft AutoUpdate (MAU) notikumi

### <a name="additionalappinfoinvalidpreference"></a>additionalappinfo.invalidpreference

Šis notikums ziņo par nederīgu preferences iestatījumu parādīt vairāk informācijas attiecībā uz produkta pakalpojuma beigām. Mēs izmantojam šo informāciju, lai informētu klientus par pareizu preferenču iestatīšanu, lai apskatītu papildinformāciju.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **Reason** — detalizēta informācija par nederīgu ievadi preferencēs

- **SessionId** — sesijas identifikators

### <a name="appdelegatelaunch"></a>appdelegate.launch

Šis notikums norāda, ka notika mēģinājums palaist programmu. Mēs reģistrējam tā rezultātu (kļūme vai sekmīgi). Šis notikums tiek izmantots, lai noteiktu gadījumus, kuros MAU neizdodas palaist

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu
    
- **AppInfo_Language** — valoda, kādā darbojas programma

- **AppversionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — statiska teksta kopa, kas norāda palaišanas statusu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="appdelegateterminate"></a>appdelegate.terminate

Šis notikums norāda, ka ir notikusi labvēlīga iziešana no programmas. Šis notikums tiek izmantots, lai atšķirtu labvēlīgu iziešanu no programmas no nelabvēlīgas.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference
    
- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators
    
- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — statisks teksts, kas norāda Microsoft AutoUpdate darbības pārtraukšanu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="appinstallconnecttoxpc"></a>appinstall.connecttoxpc

Šis notikums norāda, ka, veidojot savienojumu ar MAU palīgu (komponents, kas veic programmu instalēšanu), radās kļūdas.  Šis notikums norāda iespējamu MAU programmas bojājumu. Ierīce nevarēs instalēt atjauninājumus.

Tiek apkopoti šādi lauki:    

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — ietver kļūdas informāciju par savienojuma problēmu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

### <a name="appinstalllogscanned"></a>appinstall.logscanned

Šis notikums tiek izmantots, lai noteiktu, vai žurnālfails tika sekmīgi apstrādāts. Šis notikums tiek izmantots, lai atklātu un novērstu problēmas programmas instalēšanas laikā.  
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — ziņo par kļūdām, kas tiek atklātas programmas instalēšanas laikā un/vai parāda skenēšanas pabeigšanas statusu 

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

### <a name="appregistryconfig"></a>appregistry.config

Šis notikums ziņo par kļūdām, kas notika programmas reģistra informācijas ielādes laikā. Mēs izmantojam šo atskaiti, lai informētu IT administratorus par klientu programmu reģistrāciju iestatīšanas pareizo formātu.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — satur informāciju par programmas reģistrēšanas laikā notikušās kļūdas dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

### <a name="appregistryinfo"></a>appregistry.info

Šis notikums norāda, ka programma ir palaista. Šis notikums tiek izmantots, lai uzskaitītu programmas, kurām MAU var kontrolēt atjauninājumus, pieejamo kopiju skaitu, kā arī to versiju un instalācijas atrašanās vietu (noklusējuma vai cita).

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — ietver informāciju par identifikatoru sarakstu, ko programma izmanto, lai reģistrētos Microsoft AutoUpdate pakalpojumos, un programmai reģistrēto instalāciju skaitu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="appregistryremove"></a>appregistry.remove

Šis notikums norāda, ka notika mēģinājums noņemt programmu no MAU pārvaldīto programmu saraksta. Šis notikums tiek izmantots, lai apstiprinātu, ka ar MAU palīdzību tiek pārvaldītas tikai MAU izlaistas programmas (šeit nebūtu jābūt nevienai AppStore programmai).

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — noņemamās programmas nosaukums un identifikators neatkarīgi no tā, vai programma joprojām pastāv reģistrētajā atrašanās vietā un vai programma tika instalēta no AppStore.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="catalogerrorsignature"></a>catalog.errorsignature

Šis notikums ziņo par dažādām lejupielādēto failu problēmām, tostarp piegādātāja paraksta un jaukšanas vērtības neatbilstību lejupielādētā failā. Mēs izmantojam šo notikumu, lai atklātu problēmas lietojumprogrammu manifesta publicēšanā.

Tiek apkopoti šādi lauki.

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **FileHash** — lejupielādētā faila jaukšanas vērtība

- **FileName** — faila nosaukums, kurā redzama jaukšanas vērtības neatbilstība

- **HashInCatalog** — jaukšanas vērtības ieraksts atbilstošajā kataloga failā

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Lietderīgās** — iekļauta informācija par lietojumprogrammu, kas ziņo par problēmu

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

### <a name="cloningtaskbegin"></a>cloningtask.begin

Šis notikums norāda uz klonēšanas uzdevuma sākšanu pirms programmas atjaunināšanas. Šis notikums tiek izmantots kopā ar notikumu cloningtask.status, lai noteiktu klonēšanas kļūmju skaitu, lai noteiktu, vai klonēšanas līdzeklis ir jāierobežo citos auditorijas kanālos. 
 
Tiek apkopoti šādi lauki.

- **App** — programmas process, kas sūta notikumu

- **AppID** — programmas identifikators.

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

- **UpdateID** — atjauninājuma identifikators.


### <a name="cloningtaskhelpertoolconnection"></a>cloningtask.helpertoolconnection

Šis notikums reģistrē problēmas ar instalēšanu klonā (t.i., vai nu neizdodas izveidot savienojumu ar palīgu, lai lietotu atjauninājumu, vai savienojums ir izveidot, bet palīgs nevar lietot atjauninājumu). Ja tiek ziņots par kādu ierakstu, tas nozīmē, ka instalēšana klonā neizdevās un ka tagad ir jāveic atkāpšanās uz atjauninājumu atrašanās vietā.

Tiek apkopoti šādi lauki.

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — ietver ID, kas identificē vienu atjaunināšanas darbību, un klonēšanas procesa laikā ziņoto starpniekservera kļūdu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

### <a name="cloningtaskstatus"></a>cloningtask.status

Šis notikums norāda uz programmas, kas tiks atjaunināta, klonēšanas procesa statusu. Šis notikums tiek izmantots, lai noteiktu sekmīgas izpildes reižu skaitu un kļūdu, kas izraisa kļūmes, tipus. Šis notikums tiek izmantots, lai noteiktu, vai klonēšanas līdzeklis ir jāierobežo dažādos auditorijas kanālos.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppID** — programmas identifikators.

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Error** — virkne, kas satur kļūdas informāciju, ja kļūda notika klonēšanas uzdevuma laikā.

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

- **Success** — Būla mainīgā attēlojums virknē.

- **UpdateID** — atjauninājuma identifikators.

### <a name="cloningtaskstatusfinish"></a>cloningtask.status.finish

Šis notikums ziņo par klonēšanas uzdevuma pabeigšanu. Šis notikums veido daļu no atjauninājuma piltuves atskaites un mēs to izmantojam, lai noteiktu programmu atjauninājumu darbspēju.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppID** — programmas identifikators

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

- **Success** — norāda uz klonēšanas uzdevuma sekmīgu izpildi

- **UpdateID** — atjauninājuma identifikators.


### <a name="configurationchannel"></a>configuration.channel

Šis notikums reģistrē mēģinājumus rīkā MAU pārslēgt kanālus (auditorijas grupu).  Mēs to izmantojam, lai reģistrētu mēģinājumus un to rezultātus (sekmīgi vai kļūme).

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — ietver atlasītā kanāla nosaukumu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators


### <a name="configurationmetadata"></a>configuration.metadata

Šis notikums tiek reģistrēts ikreiz, kad notiek MAU inicializēšana. Tas ir MAU periodiskā kontrolziņojuma notikuma veids

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — statisks teksts, kurš norāda, ka tiek inicializēti atsevišķi metadati vai ka tiek inicializēta konfigurācija.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators.

### <a name="configurationsystemversion"></a>configuration.systemVersion

Šis notikums norāda uz neizdevušos mēģinājumu izgūt sistēmas versiju. Satur informāciju par informāciju, ko Microsoft Auto Update (MAU) izdevās iegūt no sistēmas. Šis notikums tiek izmantots, lai noteiktu vai MAU būtu jānovērš kļūmes. Ņemiet vērā, ka sistēmas versija tiek izmantota, lai noteiktu, vai klienta ierīcē ir iespējams instalēt atjauninājumu.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — satur informāciju par kļūdu, kas notika macOS sistēmas versijas virknes izgūšanas laikā.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

### <a name="controlleralertmanagerreinstallresponse"></a>controller.alertmanager.reinstallresponse

Šis notikums norāda, ka rīks MAU nonāca nelietojamā/neatkopjamā stāvoklī un ka ir nepieciešama atkārtota tā instalēšana. Šis notikums norāda neatkopjamu kļūdu, un ir nepieciešama lietotāja iejaukšanās.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — satur uzskaitīto lietotāju atlasi.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

    
### <a name="controlleralertmanagertmpdiskfull"></a>controller.alertmanager.tmpdiskfull

Šis notikums norāda, ka diskā nav pietiekami daudz vietas. Nevarēsim instalēt atjauninājumus, jo diskā trūkst vietas.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — statisks teksts. 

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="controlleralertmanagertmpdiskfullretry"></a>controller.alertmanager.tmpdiskfullretry

Šis notikums norāda, ka pēc nepietiekama brīvas vietas diskā apjoma noteikšanas tika sākts atkārtots mēģinājums instalēt atjauninājumu. Veicam atkārtotu instalēšanas mēģinājumu pēc tam, kad nespējām instalēt atjauninājumus, jo diskā nav pietiekami daudz brīvas vietas.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — statisks teksts. 

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators
    

### <a name="controlleralertmanagertmpdiskfullretrycancel"></a>controller.alertmanager.tmpdiskfullretrycancel

Šis notikums norāda, ka pēc nepietiekama brīvas vietas diskā apjoma noteikšanas notika atkārtota mēģinājuma instalēt atcelšana. Šis notikums tiek izmantots, lai noteiktu, vai ar mūsu atkāpšanās mehānismu pietika, lai lietotājam palīdzētu veikt atjaunināšanu gadījumā, kad diskā tika noteikts nepietiekams brīvās vietas apjoms.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)
    
- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference
    
- **Payload** — statisks teksts. 

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

    
### <a name="controllercheckwindownoupdatefoundok"></a>controller.checkwindow.noupdatefoundok

Šis notikums norāda, ka tika veikta pārbaude, kam netika atrasti atjauninājumi. Šis notikums tiek izmantots, lai nodrošinātu atjauninājumu piedāvāšanas pareizību, optimizētu pakalpojumu noslodzi un definētu, cik biežām ir jābūt pārbaudēm, vai nav atjauninājumu. Vēlamies arī optimizēt savu laidienu biežumu atbilstoši lietotāju gaidām saistībā ar atjauninājumiem.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — statisks teksts. 

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

    

### <a name="controllercheckwindowupdatecheck"></a>controller.checkwindow.updatecheck

Šis notikums norāda, ka tika veikta pārbaude, vai nav atjauninājumu. Šis notikums tiek izmantots, lai nodrošinātu atjauninājumu piedāvāšanas pareizību, optimizētu pakalpojumu noslodzi un definētu, cik biežām ir jābūt pārbaudēm, vai nav atjauninājumu. Vēlamies arī optimizēt savu laidienu biežumu atbilstoši lietotāju gaidām saistībā ar atjauninājumiem.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators
    
- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — statisks teksts. 

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="controllercheckwindowupdatecheckcancel"></a>controller.checkwindow.updatecheckcancel

Šis notikums norāda, ka pārbaudes, vai nav atjauninājumu, process tika atcelts (to izdarīja lietotājs vai sistēma). Šis notikums tiek izmantots, lai nodrošinātu atjauninājumu piedāvāšanas pareizību, optimizētu pakalpojumu noslodzi un definētu, cik biežām ir jābūt pārbaudēm, vai nav atjauninājumu. Vēlamies arī optimizēt savu laidienu biežumu atbilstoši lietotāju gaidām saistībā ar atjauninājumiem.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — statisks teksts. 

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

    
### <a name="controllercheckwindowupdatecheckcanceluser"></a>controller.checkwindow.updatecheckcanceluser

Šis notikums norāda, ka pārbaudes, vai nav atjauninājumu, procesu atcēla lietotājs.  Šis notikums tiek izmantots, lai nodrošinātu atjauninājumu piedāvāšanas pareizību, optimizētu pakalpojumu noslodzi un definētu, cik biežām ir jābūt pārbaudēm, vai nav atjauninājumu. Vēlamies arī optimizēt savu laidienu biežumu atbilstoši lietotāju gaidām saistībā ar atjauninājumiem.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija
    
- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — statisks teksts. 

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

    
### <a name="controllercheckwindowupdatesfound"></a>controller.checkwindow.updatesfound

Šis notikums norāda, ka pārbaudes, vai nav atjauninājumu, procesa rezultātā tika atrasti atjauninājumi.  Šis notikums tiek izmantots, lai nodrošinātu atjauninājumu piedāvāšanas pareizību.

Tiek apkopoti šādi lauki.

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — statisks teksts. 

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

    
### <a name="controllercheckwindowuptodate"></a>controller.checkwindow.uptodate

Šis notikums norāda, ka pārbaudes, vai nav atjauninājumu, veikšanas procesā netika atrasti atjauninājumi, jo ierīcē esošās programmas ir atjauninātas.  Šis notikums tiek izmantots, lai nodrošinātu atjauninājumu piedāvāšanas pareizību.

Tiek apkopoti šādi lauki.

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — statisks teksts. 

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="controllerdownloadwindowapplaunchwithpendingupdate"></a>controller.downloadwindow.applaunchwithpendingupdate

Šis notikums norāda, ka tika palaista programma, kurai notiek atjauninājumu iegūšanas process. Šis notikums tiek izmantots, lai nodrošinātu atjauninājumu piedāvāšanas pareizību. Nedrīkstam ļaut atjaunināt atvērtas programmas. Pirms atjaunināšanas programmas ir jāaizver.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — statisks teksts. 

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti
    
- **SessionId** — sesijas identifikators

    
### <a name="controllerdownloadwindowcloseapplicationdialog"></a>controller.downloadwindow.closeapplicationdialog

Šis notikums norāda, ka tika palaista programma, kurai notiek atjauninājumu iegūšanas process. Šis notikums tiek izmantots, lai nodrošinātu atjauninājumu piedāvāšanas pareizību. Nedrīkstam ļaut atjaunināt atvērtas programmas. Pirms atjaunināšanas programmas ir jāaizver.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — statisks teksts. 

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

    
### <a name="controllerdownloadwindowcurtasknull"></a>controller.downloadwindow.curtasknull

Šis notikums norāda, ka, mēģinot lietot atjauninājumu, radās neparedzēta kļūda. Šis notikums tiek izmantots, lai nodrošinātu atjauninājumu piedāvāšanas pareizību.

Tiek apkopoti šādi lauki.

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — statisks teksts. 

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

    
### <a name="controllerdownloadwindowdownloadcancel"></a>controller.downloadwindow.downloadcancel

Šis notikums norāda, ka lejupielādes procesu atcēla lietotājs.  Šis notikums tiek izmantots, lai nodrošinātu atjauninājumu piedāvāšanas pareizību.

Tiek apkopoti šādi lauki.

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — statisks teksts. 

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

    
### <a name="controllerdownloadwindowdownloadfailed"></a>controller.downloadwindow.downloadfailed

Šis notikums norāda, ka, lejupielādējot atjauninājumu, radās kļūda. Šis notikums tiek izmantots, lai nodrošinātu atjauninājumu piedāvāšanas un lejupielādes pareizību.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

    
### <a name="controllerdownloadwindowdownloadfailedok"></a>controller.downloadwindow.downloadfailedok

Šis notikums norāda, ka, lejupielādējot atjauninājumu, radās kļūda un lietotājs tika brīdināts. Šis notikums tiek izmantots, lai nodrošinātu atjauninājumu piedāvājuma un lejupielādes pareizību un lai kļūmes gadījumā lietotājam tiktu parādīts paziņojums.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="controllerdownloadwindowdownloadpathmissing"></a>controller.downloadwindow.downloadpathmissing

Šis notikums norāda, ka, lejupielādējot atjauninājumu, radās kļūda. Šis notikums tiek izmantots, lai nodrošinātu atjauninājumu piedāvāšanas un lejupielādes pareizību. Šis notikums norāda, ka trūkst lejupielādes vietrāža URL.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="controllerdownloadwindowdownloadtasknull"></a>controller.downloadwindow.downloadtasknull

Šis notikums norāda, ka, lejupielādējot atjauninājumu, radās kļūda. Šis notikums tiek izmantots, lai nodrošinātu atjauninājumu piedāvāšanas un lejupielādes pareizību. Šis notikums norāda, ka rīkam Microsoft AutoUpdate tika lūgts pauzēt/atsākt lejupielādi, bet nevarēja atrast atbilstošo lejupielādes pārvaldnieku.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="controllerdownloadwindowfilesignaturenotverified"></a>controller.downloadwindow.filesignaturenotverified

Šis notikums norāda, ka, lejupielādējot atjauninājumu, radās kļūda. Šis notikums norāda, ka Microsoft AutoUpdate nevarēja pārbaudīt, vai šo atjauninājumu publicēja Microsoft. Šis notikums tiek izmantots, lai nodrošinātu atjauninājumu piedāvāšanas un lejupielādes pareizību. 

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kurā ir iekļauts lejupielādes vietrādis URL. Šī ir Microsoft lejupielādes atrašanās vieta, izņemot, ja kanāls ir iestatīts kā pielāgots. Pielāgotajam kanālam šī vērtība ir iestatīta kā “Pielāgota atrašanās vieta”.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="controllerdownloadwindowinstallcomplete"></a>controller.downloadwindow.installcomplete

Šis notikums norāda, ka visu Microsoft AutoUpdate piedāvāto atjauninājumu instalēšana ir pabeigta. Šis notikums tiek izmantots, lai nodrošinātu atjauninājumu piedāvāšanas un lejupielādes pareizību. 

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma
    
- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="controllerdownloadwindownetworkunavailablealert"></a>controller.downloadwindow.networkunavailablealert

Šis notikums norāda, ka, lejupielādējot atjauninājumus, ir zudusi tīkla savienojamība.  Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

    
### <a name="controllerdownloadwindownetworkunavailablealertok"></a>controller.downloadwindow.networkunavailablealertok

Šis notikums norāda, ka, lejupielādējot atjauninājumus, ir zudusi tīkla savienojamība. Tas arī norāda, ka lietotājam tika paziņots par šo kļūdu. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

    
### <a name="controllerdownloadwindownoconnectionok"></a>controller.downloadwindow.noconnectionok

Šis notikums norāda, ka, lejupielādējot atjauninājumus, ir zudusi tīkla savienojamība. Tas arī norāda, ka lietotājam tika paziņots par šo kļūdu. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="controllerdownloadwindowrepairrequired"></a>controller.downloadwindow.repairrequired

Šis notikums norāda, ka atjaunināšanas process neizdevās. Tas arī norāda, ka atjauninājums tika pabeigts, bet Microsoft AutoUpdate atrada problēmu saistībā ar atjauninātu programmu, un ir nepieciešama labošana. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)
    
- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis
    
- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

### <a name="controllerdownloadwindowupdateaborted"></a>controller.downloadwindow.updateaborted

Šis notikums norāda, ka atjaunināšanas process tika priekšlaikus pārtraukts. Tas arī norāda to, ka dēmons jau veica atjaunināšanu, bet lietotājs noklikšķināja uz Labi, lai priekšlaikus pārtrauktu lejupielādi. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="controllerdownloadwindowupdatefailed"></a>controller.downloadwindow.updatefailed

Šis notikums norāda, ka viens vai vairāki pašreizējās paketes atjauninājumi neizdevās. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.
    
- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="controllerdownloadwindowupdatesuccessful"></a>controller.downloadwindow.updatesuccessful

Šis notikums norāda, ka visi pašreizējās paketes atjauninājumi bija sekmīgi. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="controllerdownloadwindowuserpaused"></a>controller.downloadwindow.userpaused

Šis notikums norāda, ka visi pašreizējās paketes atjauninājumi bija sekmīgi. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="controllerdownloadwindowuserresumed"></a>controller.downloadwindow.userresumed

Šis notikums norāda, ka atjauninājumu lejupielādes process tika sekmīgi atsākts pēc pauzes. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu
    
- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="controllermainwindowsetautomaticchecking"></a>controller.mainwindow.setautomaticchecking

Šis notikums norāda, ka ierīce tika reģistrēta automātiskās atjaunināšanas režīma izmantošanai. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.

Tiek apkopoti šādi lauki:

 - **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="controllermainwindowsetautomaticdownloadinstall"></a>controller.mainwindow.setautomaticdownloadinstall

Šis notikums norāda, ka ierīce tika reģistrēta automātiskās atjaunināšanas režīma izmantošanai. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

    
### <a name="controllermainwindowsetmanualchecking"></a>controller.mainwindow.setmanualchecking

Šis notikums norāda, ka ierīce tika reģistrēta manuālās atjaunināšanas režīma izmantošanai. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

    
### <a name="controllertemplateawindowcancel"></a>controller.templateawindow.cancel

Šis notikums norāda, ka lietotājs izvēlējās atcelt vai ignorēt norādīto brīdinājuma ziņojumu. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

    
### <a name="controllertemplateawindowenroll"></a>controller.templateawindow.enroll

Šis notikums norāda, ka lietotājs izvēlējās ievērot brīdinājumā norādīto ieteikumu. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference
    
- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators



### <a name="controllertemplateawindowinstall"></a>controller.templateawindow.install

Šis notikums norāda, ka lietotājs izvēlējās ievērot brīdinājumā norādīto ieteikumu saistībā ar programmatūras instalēšanas darbības uzsākšanu. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="controllerupdatewindowbegindownloadingapps"></a>controller.updatewindow.begindownloadingapps

Šis notikums norāda, ka atjauninājumu lejupielāde tika sākta, izmantojot atjaunināšanas logu. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — satur pieejamo atjauninājumu pakotņu vārdnīcu un norādi, vai lietotājs ir izvēlējās instalētu atbilstošo ierakstu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

    
### <a name="controllerupdatewindownetworkretry"></a>controller.updatewindow.networkretry

Šis notikums norāda, ka tīkla kļūmes dēļ atjaunināšanas lapā tika izraisīts atkārtots mēģinājums. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

    
### <a name="controllerupdatewindownetworkretrycancel"></a>controller.updatewindow.networkretrycancel

Šis notikums norāda, ka tīkla kļūmes dēļ atjaunināšanas lapā nevarēja izraisīt atkārtotu mēģinājumu. Šis notikums norāda, ka lietotājs izvēlējās atcelt atjauninājumus pēc brīdinājuma saņemšanas par to, ka tīkls kļūst nepieejams. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="controllerupdatewindownetworkunavailable"></a>controller.updatewindow.networkunavailable

Šis notikums norāda, ka pēkšņi zuda tīkla savienojamība. Šis notikums norāda, ka, mēģinot lejupielādēt atjauninājumu pakotni, serveris nav sasniedzams. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="controllerupdatewindownoupdateavailable"></a>controller.updatewindow.noupdateavailable

Šis notikums norāda, ka, meklējot atjauninājumus, neviens atjauninājums nebija pieejams. Šis notikums norāda, ka Microsoft AutoUpdate neatrada nevienu pieejamu atjauninājumu. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="controllerupdatewindownoupdatestoselect"></a>controller.updatewindow.noupdatestoselect

Šis notikums norāda, ka radās kļūda, izraisot tukšu atjauninājumu sarakstu. Šis notikums norāda, ka Microsoft AutoUpdate rāda tukšu atjauninājumu lapu. Tam nebūtu jānotiek. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="controllerupdatewindowupdateavailable"></a>Controller.UpdateWindow.UpdateAvailable

Šis notikums norāda, ka atjauninājumu meklēšanas rezultātā tika piedāvāti atjauninājumi. Šis notikums tiek izmantots, lai noteiktu, vai lietotājam skatīšanai tiek piedāvāti atjauninājumi, vai tiek rādīti atbilstoši atjauninājumi un vai atjauninājumu bloķēšana darbojas, kā paredzēts. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — satur pieejamo atjauninājumu pakotņu vārdnīcu un katras pakotnes lietotāja atlases statusu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

    
### <a name="controllerupdatewindowupdateavailablecancel"></a>controller.updatewindow.updateavailablecancel

Šis notikums norāda, ka lietotājs atcēla darbību pēc tam, kad parādījām atjauninājumu lapu, uzskaitot atjauninājumus. To izmantojam pat tam, lai izskaidrotu neatjaunināšanas iemeslus (piemēram, lietotājs labprāt atceļ darbību). Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="downloadactorpause"></a>downloadactor.pause

Šis notikums norāda, ka lietotājs izdeva pieprasījumu pauzēt lejupielādi. Mēs to izmantojam pat tam, lai izskaidrotu iemeslus, kāpēc atjaunināšana netiek pabeigta. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="downloadactorredirect"></a>downloadactor.redirect

Šis notikums norāda, ka lejupielādētāja aģents norādīja uz galapunktu, kas izdod URL novirzīšanu lejupielādes pieprasījumam. Šo notikumu izmantojam pat tam, lai izskaidrotu lejupielādes kļūmes un diagnosticētu starpniekservera problēmas. Tas var arī palīdzēt diagnosticēt iemeslus, kāpēc lietotāji instalē vecākus būvējumus. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — satur novirzītu vietrādi URL. Šī ir Microsoft lejupielādes atrašanās vieta, izņemot, ja kanāls ir iestatīts kā pielāgots. Pielāgotajam kanālam šī vērtība ir iestatīta kā “Pielāgota atrašanās vieta”.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

    
### <a name="downloadactorresume"></a>downloadactor.resume

Šis notikums norāda, ka lietotājs izdeva pieprasījumu atsākt pauzētu lejupielādi. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="downloadactorresumeerror"></a>downloadactor.resumeerror

Šis notikums norāda, ka lietotājs izdeva pieprasījumu atsākt pauzētu lejupielādi. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — satur lejupielādes vietrāža URL ceļu. Šī ir Microsoft lejupielādes atrašanās vieta, izņemot, ja kanāls ir iestatīts kā pielāgots. Pielāgotajam kanālam šī vērtība ir iestatīta kā “Pielāgota atrašanās vieta”.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

    
### <a name="downloadactorstatus"></a>downloadactor.status

Šis notikums reģistrē mēģinājumus ienest papildmateriālu failus un to rezultātus (sekmīgi vai kļūme). Vēlamies zināt, kādi papildmateriāli un paketes tiek ienesti. Nepareiza faila ienešana var norādīt uz būvējuma/papildmateriālu problēmu. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — ietver lejupielādes vietrādi URL un kļūdas kodu kļūmes gadījumā. Lejupielādes vietrādis URL ir Microsoft lejupielādes atrašanās vieta, izņemot, ja kanāls ir iestatīts kā pielāgots. Pielāgotajam kanālam šī vērtība ir iestatīta kā “Pielāgota atrašanās vieta”.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="downloadmanifestconfiguration"></a>downloadmanifest.configuration

Šis notikums ziņo par kļūdu Microsoft Auto Update (MAU) konfigurācijā, kas var būt gan pielāgotā servera iestatījumu preferencēs vai Update Assistant galapunktu definīcijās instalētajos MAU komponentos. Mēs izmantojam šo notikumu, lai informētu IT administratorus par pareiziem manifesta servera galapunktiem.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **Payload** — norāda, vai kļūda ir pielāgotā servera iestatījumos vai instalētajos MAU komponentos

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators


### <a name="downloadmanifestdownloadcatalogfail"></a>downloadmanifest.downloadcatalogfail

Šis notikums norāda uz lejupielādes kļūmi. Tiek reģistrēt fails, kuru neizdevās lejupielādēt. Vēlamies zināt, kādi papildmateriāli un paketes tiek ienesti. Manifesta lejupielādes kļūme var norādīt uz būvējuma papildmateriālu ģenerēšanas kļūmi, CDN konfigurācijas kļūdu, klienta konfigurācijas kļūdu vai tīkla kļūdu. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — ietver lejupielādes kļūdas kodu un lejupielādes faila vietrādi URL. Šī ir Microsoft lejupielādes atrašanās vieta, izņemot, ja kanāls ir iestatīts kā pielāgots. Pielāgotajam kanālam šī vērtība ir iestatīta kā “Pielāgota atrašanās vieta”.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

    
### <a name="downloadmanifestdownloadcatalogsuccess"></a>downloadmanifest.downloadcatalogsuccess

Šis notikums norāda, ka fails ir sekmīgi lejupielādēts. Manifesta lejupielādes kļūme var norādīt uz būvējuma papildmateriālu ģenerēšanas kļūmi, CDN konfigurācijas kļūdu, klienta konfigurācijas kļūdu vai tīkla kļūdu. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu
    
- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — ietver lejupielādes kļūdas kodu un lejupielādes faila vietrādi URL. Šī ir Microsoft lejupielādes atrašanās vieta, izņemot, ja kanāls ir iestatīts kā pielāgots. Pielāgotajam kanālam šī vērtība ir iestatīta kā “Pielāgota atrašanās vieta”.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="downloadmanifestdownloadfail"></a>downloadmanifest.downloadfail

Šis notikums norāda, ka radās lejupielādes kļūda. Tiek reģistrēts manifesta vai pakotnes fails, kuru neizdevās lejupielādēt, kā arī kļūdas detaļas. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — ietver lejupielādes kļūdas kodu un lejupielādes faila vietrādi URL. Šī ir Microsoft lejupielādes atrašanās vieta, izņemot, ja kanāls ir iestatīts kā pielāgots. Pielāgotajam kanālam šī vērtība ir iestatīta kā “Pielāgota atrašanās vieta”.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="downloadmanifestdownloadfromurl"></a>downloadmanifest.downloadfromurl

Šis notikums norāda, ka ir sākta kataloga faila lejupielāde. Mēs reģistrējam vietrādi URL, no kura tiek lejupielādēts kataloga fails. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — ietver lejupielādes kļūdas kodu un lejupielādes faila vietrādi URL. Šī ir Microsoft lejupielādes atrašanās vieta, izņemot, ja kanāls ir iestatīts kā pielāgots. Pielāgotajam kanālam šī vērtība ir iestatīta kā “Pielāgota atrašanās vieta”.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="downloadmanifestdownloading"></a>downloadmanifest.downloading

Šis notikums norāda, ka ir sākta kataloga faila lejupielāde. Mēs reģistrējam vietrādi URL, no kura tiek lejupielādēts kataloga fails. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — ietver lejupielādes kļūdas kodu un lejupielādes faila vietrādi URL. Šī ir Microsoft lejupielādes atrašanās vieta, izņemot, ja kanāls ir iestatīts kā pielāgots. Pielāgotajam kanālam šī vērtība ir iestatīta kā “Pielāgota atrašanās vieta”.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="downloadmanifestdownloadsuccess"></a>downloadmanifest.downloadsuccess

Šis notikums norāda, ka XML un pakotnes faila lejupielāde bija sekmīga. Mēs reģistrējam vietrādi URL, no kura tiek lejupielādēts fails. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — ietver lejupielādes kļūdas kodu un lejupielādes faila vietrādi URL. Šī ir Microsoft lejupielādes atrašanās vieta, izņemot, ja kanāls ir iestatīts kā pielāgots. Pielāgotajam kanālam šī vērtība ir iestatīta kā “Pielāgota atrašanās vieta”.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

    
### <a name="downloadmanifestdownloadurl"></a>downloadmanifest.downloadurl

Šis notikums norāda, ka radās pieprasījums lejupielādēt failu. Mēs reģistrējam vietrādi URL, no kura tiek lejupielādēts fails. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu
    
- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — ietver lejupielādes kļūdas kodu un lejupielādes faila vietrādi URL. Šī ir Microsoft lejupielādes atrašanās vieta, izņemot, ja kanāls ir iestatīts kā pielāgots. Pielāgotajam kanālam šī vērtība ir iestatīta kā “Pielāgota atrašanās vieta”.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="downloadmanifestfilenameerror"></a>downloadmanifest.filenameerror

Šis notikums norāda, ka radās neparedzēta kļūda. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="downloadmanifestinvalidhash"></a>downloadmanifest.invalidhash

Šis notikums norāda, ka failu drošības validācija neizdevās. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — satur tā lejupielādētā faila nosaukumu, kuram ir nederīga jaukšanas vērtība.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="downloadmanifestmissingdaemon"></a>downloadmanifest.missingdaemon

Šis notikums norāda, ka lietotājs mēģināja pārbaudīt, vai nav atjauninājumu, un mēs atklājām, ka rīkam MAU trūkst pamatkomponenta (dēmona). Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="downloadmanifestsignatureerror"></a>downloadmanifest.signatureerror

Šis notikums norāda, ka pakotnei neizdevās koda paraksta pārbaude. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — satur tā lejupielādētā faila nosaukumu, kuram ir nederīga jaukšanas vērtība.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="downloadmanifeststatus"></a>downloadmanifest.status

Šis notikums reģistrē tādu apkopotu mēģinājumu/kļūmju kopsavilkumu, kas notika manifesta un pakotnes failu lejupielādes procesā. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — satur informāciju, tostarp vietrādi URL (Microsoft adrese), lejupielādējamā faila prefiksu, visas radušās kļūdas utt.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="downloadmgrdownloadend"></a>downloadmgr.downloadend

Šis notikums reģistrē marķieri, kas norāda, ka lejupielādes process tika pabeigts patstāvīgi. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — satur informāciju, tostarp vietrādi URL (Microsoft adrese), lejupielādējamā faila prefiksu, visas radušās kļūdas utt.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="downloadmgrdownloadstart"></a>downloadmgr.downloadstart

Šis notikums reģistrē atjauninājumu, kas tūlīt tiks lejupielādēts. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — satur lejupielādējamā atjauninājuma nosaukumu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

### <a name="downloadtaskdownloadbegin"></a>downloadtask.downloadbegin

Šis notikums norāda uz programmas atjauninājuma lejupielādes darbības sākumu. Tas veido daļu no atjauninājuma piltuves un mēs to izmantojam, lai noteiktu programmu atjauninājumu darbspēju.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppID** — programmas, kas tiek atjaunināta, identifikators

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **BundleVersion** — programmas, kas tiek atjaunināta, versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **PreviousUpdateID** — programmas atjauninājuma identifikators

- **SessionId** — sesijas identifikators

- **UpdateID** — programmas atjauninājuma identifikators

- **UpdatePkg** — instalējamās atjauninājuma pakotnes nosaukums

- **UpdateVersion** — programmas versija pēc atjauninājuma


### <a name="downloadtaskdownloadfailure"></a>downloadtask.downloadfailure

Šis notikums reģistrē to, ka pakotnes faila lejupielādes laikā radās kļūda. Reģistrējam atjauninājuma ceļu un kļūdu. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppID** — programmas, kurai ir lejupielādes kļūme, identifikators.

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Error** — lejupielādes laikā novērotā kļūda.

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — satur lejupielādējamā atjauninājuma nosaukumu un novēroto kļūdu. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

- **UpdateID** — lejupielādējamā atjauninājuma identifikators.


### <a name="downloadtaskdownloadsuccess"></a>downloadtask.downloadsuccess

Sekmīga pakotnes faila lejupielāde. Reģistrējam izmantoto atjauninājuma ceļu. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppID** — programmas identifikators.

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — satur sekmīgas lejupielādes atjauninājuma ceļu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

- **UpdateID** — lejupielādētā atjauninājuma identifikators.

### <a name="downloadtaskupdatertypeerror"></a>downloadtask.updatertypeerror

Šis notikums ziņo par atjaunināšanas tipa kļūdu lejupielādētajā manifesta failā. Šis notikums tiek izmantots, lai informētu manifesta faila īpašnieku un labotu kļūdu.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppID** — programmas, kas tiek atjaunināta, identifikators

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

- **UpdateID** — programmas atjauninājuma identifikators

- **UpdaterType** — lejupielādētajā manifesta failā noradītā atjauninātāja tips

- **UpdateURL** — instalējamās pakotnes URL saite

### <a name="downloadtaskurlerror"></a>downloadtask.urlerror

Šis notikums ziņo par norādītā URL kļūdu lejupielādētajā manifesta failā. Šis notikums tiek izmantots, lai informētu manifesta faila īpašnieku un labotu kļūdu.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **Error** — norāda notikušās kļūdas būtību

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

- **UpdateID** — programmas atjauninājuma identifikators

- **UpdateURL** — instalējamās pakotnes URL saite

### <a name="fbachangelastupdate"></a>fba.changelastupdate

Šis notikums ziņo par to, vai Microsoft Auto Update (MAU) pārbaudīja atjauninājumu pieejamību. Šis notikums tiek izmantots, lai veiktu atkļūdošanu, ja konkrētā ierīce ilgstoši nav piedāvājusi veikt atjauninājumu.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **Payload** — satur laiku un datumu, kad MAU pārbaudīja atjauninājumu pieejamību

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators


### <a name="fbacheckforupdate"></a>fba.checkforupdate

Šis notikums norāda, ka fona process pārbauda, vai nav atjauninājumu. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="fbacheckforupdateskip"></a>fba.checkforupdateskip

Šis notikums norāda, ka fona process izlaida atjauninājumu, jo ir atvērts MAU GUI. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="fbaforceinstallmsgsent"></a>fba.forceinstallmsgsent

Šis notikums norāda, ka piespiedu atjauninājums tika iniciēts lietotāja interfeisā. Šis notikums veido daļu no piltuves un tiek izmantots, lai noteiktu piespiedu atjauninājuma līdzekļa darbspēju.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **Payload** — statisks teksts

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

### <a name="fbaforceupdatecheck"></a>fba.forceupdatecheck

Šis notikums norāda, ka atjauninājumu pieejamības pārbaude ir piespiedu. Šis notikums tiek izmantots, lai noteiktu skaitu piespiedu atjauninājumu pieejamības pārbaudēm, kas notiek ārpus normālā atjauninājumu pieejamības pārbaudes cikla.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **Payload** — statisks teksts

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

### <a name="fbaguiappopen"></a>fba.guiappopen

Šis notikums norāda, ka lietotāja interfeiss tiek palaists automātiskās pārbaudes režīmā, kamēr ir atvērta programma ar instalējamo atjauninājumu. Šis notikums tiek izmantots, lai noteiktu lietotāja interfeisa palaišanas reižu skaitu automātiskajā pārbaudes režīmā līdzekļa tālākai izstrādei.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **Payload** — statisks teksts

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

### <a name="fbainstallpending"></a>fba.installpending

Šis notikums norāda, ka Microsoft Auto Update (MAU) nosūtīja paziņojumu par gaidošajiem atjauninājumiem. Šis notikums tika izmantots, lai noteiktu atjauninājumu, kas tiek uzsākti no paziņojumiem lietotājam, skaitu un lai paaugstinātu lietotāju ērtību, samazinot traucējumus lietotājam nākotnes laidienos. 

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **Payload** — statisks teksts

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

### <a name="fbalaunch"></a>fba.launch

Šis notikums norāda Microsoft Update Assistant palaišanu un palaišanas metodi. Šis notikums tiek izmantots, lai noteiktu, vai Microsoft Update Assistant tiek palaists nepareizajā kontekstā.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **Payload** — statisks teksts

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

### <a name="fbalaunchbyagent"></a>fba.launchbyagent

Šis notikums norāda, ka Microsoft Update Assistant tika palaists ar palaišanas aģenta palīdzību. Šis notikums tiek izmantots, lai noteiktu Microsoft Update Assistant palaišanas no lietotāja interfeisa reižu skaitu turpmākai izstrādei.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **Payload** — statisks teksts

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

### <a name="fbalaunchfromprotocol"></a>fba.launchfromprotocol

Šis notikums norāda, ka Microsoft Update Assistant tika palaists ar URL protokola palīdzību. Šis notikums tiek izmantots, lai noteiktu Microsoft Update Assistant palaišanas no URL protokola reižu skaitu turpmākai izstrādei.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **Payload** — satur informāciju par URL shēmu un URL viesotāju

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

### <a name="fbalaunchgui"></a>fba.launchgui

Šis notikums norāda, ka Microsoft Update Assistant mēģina palaist grafisko lietotāja interfeisu (GUI). Šis notikums tiek izmantots, lai noteiktu lietotāja interfeisa no Microsoft Update Assistant iniciēto palaišanas reižu skaitu, lai palīdzētu turpmākai izstrādei, tai skaitā samazinot lietotāja traucēšanu ar biežo lietotāja interfeisa palaišanu.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **Payload** — statisks teksts

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators


### <a name="fbalaunchstatus"></a>fba.launchstatus

Šis notikums reģistrē MAU dēmona kļūmes, mēģinot veikt palaišanu. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Error** — satur OSStatus (Apple statusa kodu), kas atspoguļo palaišanas statusu.

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — satur OSStatus (Apple statusa kodu), kas atspoguļo palaišanas statusu. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

- **Success** — Būla virkne, kas norāda, vai MAU dēmona process tika palaists veiksmīgi.


### <a name="fbamausilentupdate"></a>fba.mausilentupdate

Šis notikums norāda, ka Microsoft Update Assistant iniciē klusos atjauninājumus. Šis notikums tiek izmantots, lai noteiktu atjauninājumu, kas tiek instalēti bez lietotāja dalības, skaitu, lai veicinātu paaugstinātu lietotāju ērtību.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija
 
- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **Payload** — statiskais teksts *[Šis lauks ir noņemts no pašreizējiem Office būvējumiem, bet, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **Reason** — statisks teksts, kas norāda, ka klusais atjauninājums nevar turpināties, kad lietotāja interfeiss ir atvērts

- **SessionId** — sesijas identifikators

### <a name="fbamoreinfofromappnotification"></a>fba.moreinfofromappnotification

Šis notikums ziņo par informāciju, kuru reģistrēta programma maršrutē caur Microsoft Auto Update (MAU). Piemēram, paziņojumi par pakalpojuma darbības beigām tiek piegādāti ar MAU paziņojuma palīdzību. Šis notikums tiek izmantots, lai noteiktu ierīču, kurās tiek parādīts konkrētais paziņojums, skaitu, lai noteiktu informācijas izplatīšanas sekmīgumu.

Tiek apkopoti šādi lauki:

- **AdditionalInfoID** — unikāli identificē gadījumus, ka Papildinformācija tiek piegādāta caru MAU.

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **NotificationEvent** — statisks teksts, kas norāda uz lietotā paziņojuma tipu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

### <a name="fbamultipledaemon"></a>fba.multipledaemon

Šis notikums norāda, ka tika atklāts cits Microsoft Update Assistant eksemplārs, bet pašreizējais eksemplāra darbība tiks pārtraukta. Šis notikums tiks izmantots, lai noteiktu ierīču skaitu, kurās tiek mēģināts palaist vairākus Update Assistant eksemplārus, un izstrādātu risinājumu, ja tas būs nepieciešams.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **Payload** — statisks teksts

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

### <a name="fbanofifyappclosed"></a>fba.nofifyappclosed

Šis notikums norāda, ka Microsoft Update Assistant nosūta paziņojumu gaidošiem atjauninājumiem, jo reģistrētas programmas nav atvērtas un atjauninājumu darbība var notikt netraucējot lietotājam. Šis notikums tiek izmantots, lai noteiktu atjauninājumu, kurus ir iespējams instalēt, bet tam nepieciešama lietotāja darbība, skaitu.  Šis notikums tiek izmantots, lai veicinātu lietotāja ērtības paaugstināšanu.

Tiek apkopoti šādi lauki: 
    
- **App** — programmas process, kas sūta notikumu
    
- **AppInfo_Language** — valoda, kurā darbojas programma
    
- **AppVersionLong** — programmas versija
    
- **Channel** — auditorijas preference
    
- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)
    
- **DeviceID** — ierīces identifikators
    
- **DeviceInfo_Model** — ierīces aparatūras modelis
    
- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)
    
- **DeviceInfo_OsBuild** — operētājsistēmas versija
    
- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija
    
- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums
    
- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 
    
- **HowToCheck** — kā pārbaudīt iestatījumu
    
- **Payload** — statisks teksts
    
- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)
    
- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti
    
- **SessionId** — sesijas identifikators

### <a name="fbanofifyappopen"></a>fba.nofifyappopen

Šis notikums norāda, ka Microsoft Update Assistant nosūta paziņojumu gaidošiem atjauninājumiem, jo ir atvērtas reģistrētas programmas un atjauninājumu darbībai būs nepieciešams šīs programmas aizvērt.  Šis notikums tiek izmantots, lai noteiktu atjauninājumu, kuriem nepieciešama lietotāja iejaukšanās, skaitu.  Šis notikums tiek izmantots, lai veicinātu lietotāja ērtības paaugstināšanu.

Tiek apkopoti šādi lauki:  

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma
    
- **AppVersionLong** — programmas versija
    
- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **Payload** — statisks teksts

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

### <a name="fbasettimerfail"></a>fba.settimerfail  

Šis notikums norāda, ka mēģinājums iestatīt taimeri nākotnes atjauninājumam neizdevās. Šis notikums ir kritisks un tiek izmantots, lai noteiktu kļūmju, kam varētu būt nepieciešama risinājuma izstrāde, skaitu.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **Payload** — satur informāciju par pēdējās atjaunināšanas laiku un izmantoto kalendāru

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators


### <a name="fbasilentupdateoptin"></a>fba.silentupdateoptin

Šis notikums norāda, ka lietotājs piekrīt klusajai atjaunināšanai. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

### <a name="fbaskipforcedupdate"></a>fba.skipforcedupdate

Šis notikums norāda piespiedu pārbaudes, vai nav atjauninājumu, izlaišanu atvērtu programmu dēļ. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="fbastartforcedupdate"></a>fba.startforcedupdate

Šis notikums norāda, ka ir noticis mēģinājums lietot piespiedu atjaunināšanu. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="fbaterminate"></a>fba.terminate

Šis notikums norāda, ka MAU dēmona darbība tika izbeigta normāli. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="fbaupdatefound"></a>fba.updatefound

Šis notikums norāda, ka MAU dēmons ir atradis pieejamus atjauninājumus, ko piedāvāt. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — satur atrasto pieejamo atjauninājumu skaitu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

    
### <a name="fbaupdatetimer"></a>fba.updatetimer

Šis notikums norāda, ka pēc iestatīta miega laika perioda Microsoft AutoUpdate dēmona process aktivizējās, lai pārbaudītu, vai nav atjauninājumu. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — satur pašreizējo datuma un laika informāciju.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="fbasilentupdateallappsclosed"></a>fbasilentupdate.allappsclosed

Šis notikums reģistrē, vai pirms instalēšanas bija aizvērtas visas programmas. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference
    
- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="fbasilentupdateapplaunchafterupdate"></a>fbasilentupdate.applaunchafterupdate

Šis notikums reģistrē mēģinājumu atkārtoti palaist programmu pēc klusās atjaunināšanas un atjaunināšanas režīmu (klons vai nav klons). Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppID** — programmas identifikators.

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Error** — detalizēta informācija par kļūdu, kas notika programmas palaišanas brīdī pēc atjaunināšanas.

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — ietver identifikatoru, kas tiek lietots, lai izsekotu atjaunināšanas darbību un palaižamās programmas nosaukumu. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*
    
- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)
    
- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="fbasilentupdateapplaunchwileinstalling"></a>fbasilentupdate.applaunchwileinstalling

Reģistrējam, ja atjauninājuma instalēšanas laikā tika veikta programmas palaišana. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — ietver identifikatoru, kas tiek lietots, lai izsekotu atjaunināšanas darbību.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="fbasilentupdateappneedtoclose"></a>fbasilentupdate.appneedtoclose

Reģistrējam, ja tika sākta atjaunināšana un ir atvērta atjaunināmā programma. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — ietver identifikatoru, kas tiek lietots, lai izsekotu atjaunināšanas darbību, atjauninājuma nosaukumu un programmu komplekta ID.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="fbasilentupdateappterminationeventreceived"></a>fbasilentupdate.appterminationeventreceived

Šis notikums norāda, ka Microsoft AutoUpdate saņēma Apple notikumu, informējot par programmas darbības pārtraukšanu. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppID** — programmas identifikators.

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Error** — detalizēta informācija par kļūdu, kas notika programmas izbeigšanas brīdī.

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — ietver identifikatoru, kas tiek lietots, lai izsekotu atjaunināšanas darbību un programmu komplekta ID. Var saturēt arī kļūdas virkni, ja Microsoft AutoUpdate nosaka, ka programma joprojām darbojas, lai gan tika saņemts darbības pārtraukšanas notikums. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

- **UpdateID** — programmas atjauninājuma identifikators.


### <a name="fbasilentupdateclientsession"></a>FBASilentUpdate.ClientSession

Šis notikums tiek izmantots, lai aprēķinātu Microsoft Auto Update (MAU) kritiskā atjauninājuma darbspējas rādītāju. Šis notikums ļauj mums norādīt, kuru atjaunināšanas sesiju (lejupielāde vai instalēšana) sistēma pašlaik apstrādā.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — norāda, kuru atjaunināšanas sesiju (lejupielāde vai instalēšana) sistēma pašlaik apstrādā.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators


### <a name="fbasilentupdatecodesignfailure"></a>fbasilentupdate.codesignfailure

Šis notikums reģistrē koda paraksta verifikācijas rezultātu pēc atjauninājuma lietošanas. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — satur koda paraksta verifikācijas darbības rezultātu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="fbasilentupdatedownload"></a>fbasilentupdate.download

Šis notikums norāda, ka atjauninājums tiek lejupielādēts. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — ietver identifikatoru, kas tiek lietots, lai izsekotu atjaunināšanas darbību un atjauninājuma nosaukumu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **ScreenLocked** — norāde, vai lejupielāde tiek sākta aiz bloķēta ekrāna

- **SessionId** — sesijas identifikators


### <a name="fbasilentupdatedownloadfailed"></a>fbasilentupdate.downloadfailed

Šis notikums norāda, ka, lejupielādējot atjauninājumu, radās kļūda. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppID** — programmas identifikators.

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Error** — detalizēta informācija par kļūdu, kas notika programmas atjauninājuma lejupielādes brīdī.

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — ietver identifikatoru, kas tiek lietots, lai izsekotu atjaunināšanas darbību un atjauninājuma nosaukumu. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

- **UpdateID** — programmas atjauninājuma identifikators.

- **UpdateName** — programmas atjauninājuma nosaukums.


### <a name="fbasilentupdatedownloadinbackground"></a>fbasilentupdate.downloadinbackground

Šis notikums norāda, ka sākam atjauninājumu kopas lejupielādi fona režīmā (reģistrējam vienlaikus lejupielādējamo atjauninājumu skaitu). Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — satur rindā iekļauto atjauninājumu skaitu.

    - **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="fbasilentupdatedownloadingrepairupdate"></a>fbasilentupdate.downloadingrepairupdate

Šis notikums norāda, ka esam uzsākuši mēģinājumu lejupielādēt labojumu nesekmīgam atjauninājumam. Reģistrējam versiju un atjauninājumu. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — ietver identifikatoru, kas tiek lietots, lai izsekotu atjaunināšanas darbību un atjauninājuma nosaukumu.
    
- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **ScreenLocked** — norāde, vai lejupielāde tiek sākta aiz bloķēta ekrāna

- **SessionId** — sesijas identifikators


### <a name="fbasilentupdateduplicatedownloadattempted"></a>fbasilentupdate.duplicatedownloadattempted

Šis notikums norāda, ka radās kļūda. Norādītajai programmai vienlaikus ir jāveic tikai viena atjauninājuma lejupielāde. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="fbasilentupdateinstallattemptfailed"></a>fbasilentupdate.installattemptfailed

Šis notikums norāda, ka atjauninājuma (versija) instalēšanas mēģinājums neizdevās. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="fbasilentupdateinstallcomplete"></a>fbasilentupdate.installcomplete

Šis notikums norāda, ka visu paketē iekļauto atjauninājumu instalēšana ir pabeigta. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="fbasilentupdateinstalled"></a>fbasilentupdate.installed

Šis notikums norāda, ka atsevišķs atjauninājums tika sekmīgi instalēts. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu. Ietver atjauninājuma identifikatoru.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

    
### <a name="fbasilentupdateinstalling"></a>fbasilentupdate.installing

Šis notikums norāda, ka tika uzsākts atsevišķs atjauninājums. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — ietver identifikatoru, kas tiek lietots, lai izsekotu atjaunināšanas darbību, atjauninājuma nosaukumu un atjauninājumu pakotnes nosaukumu.
    
- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

### <a name="fbasilentupdateinstallstatus"></a>fbasilentupdate.installstatus

Šis notikums ziņo par programmas atjaunināšanas uzdevuma statusu. Šis notikums veido daļu no programmas atjauninājuma piltuves un mēs to izmantojam, lai uzraudzītu programmu atjauninājumu darbspēju.

Tiek apkopoti šādi lauki: 

- **App** — programmas process, kas sūta notikumu

- **AppID** — programmas, kas tiek atjaunināta, identifikators

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **Payload** — satur informāciju par to, vai tiek parādīts izpildes skats

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

- **Success** — norāda, vai programmas atjaunināšana bija sekmīga

- **UpdateID** — programmas atjauninājuma identifikators

- **UpdateName** — atjauninājuma nosaukums, kā norādīts lejupielādētajā manifesta failā

- **UpdatePkg** — instalējamās atjauninājuma pakotnes nosaukums

### <a name="fbasilentupdatenotificationerror"></a>fbasilentupdate.notificationerror

Šis notikums ziņo par kļūdu, kas notika mēģinot nosūtīt paziņojumu lietotājam. Šis notikums tiks izmantots, lai atkļūdotu kļūdas iemeslu un veiktu labojumus.

Tiek apkopoti šādi lauki:  

- **App** — programmas process, kas sūta notikumu
 
- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **ErrType** — norāda notikušās kļūdas būtību

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **Message** — paziņojuma saturs

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

- **Title** — paziņojuma virsraksts

- **Type** — paziņojuma tips

### <a name="fbasilentupdatenotificationremoved"></a>fbasilentupdate.notificationremoved

Šis notikums norāda, ka bloķēts atjauninājums vairs nav bloķēts. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — ietver iepriekš bloķētas programmas ID (identifikators, ko programma izmanto, lai reģistrētos pakalpojumā Microsoft AutoUpdate)
    
- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="fbasilentupdatequeueinstall"></a>fbasilentupdate.queueinstall

Šis notikums norāda, ka atjauninājums tiks iekļauts klusās instalēšanas rindā. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — ietver identifikatoru, kas tiek lietots, lai izsekotu atjaunināšanas darbību un atjauninājuma nosaukumu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="fbasilentupdaterequiredappsclosed"></a>fbasilentupdate.requiredappsclosed

Reģistrējam, kad tiek aizvērta programma, kurai ir gaidošs atjauninājums. Tiek norādīts laiks, kad var turpināt ar faktisko instalēšanu. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — ietver identifikatoru, kas tiek lietots, lai izsekotu atjaunināšanas darbību un programmu komplekta ID.
    
- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

### <a name="fbasilentupdatetimerforapptermination"></a>FBASilentUpdate.TimerForAppTermination

Šis notikums tiek izmantots, lai aprēķinātu Microsoft Auto Update (MAU) kritiskā atjauninājuma darbspējas rādītāju. Šis notikums palīdz izsekot atvērtās programmas izbeigšanas notikumu un programmas atvērtā stāvokļa ilgumu.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** –— norāda, vai atvērtajai programmai bija iestatīts taimeris, kad tika sākta tās atjauninājuma instalēšana. 

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

### <a name="fbasilentupdateupdateavailablenotification"></a>fbasilentupdate.updateavailablenotification

Šis notikums norāda, ka tiek izraisīts paziņojums par pieejamu atjauninājumu. Ir jānodrošina plūsma uzvednes par atjauninājumu izraisīšanai, kad tiek atrasts atjauninājums. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **CustomNotification** — Būla vērtība, kas norāda, vai tika izmantots pielāgots paziņojums.

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="fbasilentupdateuserclicknotification"></a>fbasilentupdate.userclicknotification

Šis notikums norāda, ka lietotājs noklikšķināja paziņojuma par atjauninājuma pieejamību satura sadaļā un tiek palaists Microsoft AutoUpdate GUI. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="fbasilentupdateuserselectinstalllater"></a>fbasilentupdate.userselectinstalllater

Šis notikums norāda, ka lietotājs pēc paziņojuma par pieejamu atjauninājumu parādīšanas ir izvēlējies instalēt vēlāk. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="fbasilentupdateuserselectinstallnow"></a>fbasilentupdate.userselectinstallnow

Šis notikums norāda, ka lietotājs pēc paziņojuma par pieejamu atjauninājumu parādīšanas ir izvēlējies instalēt tūlīt. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

### <a name="guidashboardviewappisopendialogdisplay"></a>gui.dashboardview.appisopendialog.display 

Šis notikums norāda, ka lietotāja interfeiss parādīja dialoglodziņu par programmas aizvēršanu, lai turpinātu programmas atjaunināšanu. Šis notikums tiek izmantots, lai noteiktu aizkavēto atjauninājumu skaitu, lai nākotnē veiktu uzlabojumus un samazinātu lietotāju traucēšanu.

Tiek apkopoti šādi lauki: 

- **App** — programmas process, kas sūta notikumu

- **AppID** — programmas, kas tiek atjaunināta, identifikators

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

- **UpdateID** — programmas atjauninājuma identifikators

- **UpdateName** — atjauninājuma nosaukums, kā norādīts lejupielādētajā manifesta failā

### <a name="guidashboardviewappisopendialogbuttonclicked"></a>gui.dashboardview.appisopendialogbutton.clicked

Šis notikums norāda, vai programmas atjaunināšana tika izlaista, vai pēc atvērtajā programmā parādītā dialoglodziņa tiek veikts vēl viens mēģinājums. Šis notikums tiek izmantots, lai noteiktu izlaisto atjauninājumu skaitu un veiktu uzlabojumus, lai samazinātu lietotāju traucēšanu.

Tiek apkopoti šādi lauki:   

- **App** — programmas process, kas sūta notikumu

- **AppID** — programmas, kas tiek atjaunināta, identifikators

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **ButtonType** — izlaist vai mēģināt vēlreiz

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators 

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

- **UpdateID** — programmas atjauninājuma identifikators

- **UpdateName** — atjauninājuma nosaukums, kā norādīts lejupielādētajā manifesta failā

### <a name="guidashboardviewupdateinprogressdialogdisplay"></a>gui.dashboardview.updateinprogressdialog.display

Šis notikums reģistrē, vai lietotājiem tika parādīts dialoglodziņš ar informāciju par to, ka atjaunināšanas izpilde jau notiek.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

### <a name="guidashboardviewupdatemodebuttonclicked"></a>gui.dashboardview.updatemodebutton.clicked

Šis notikums norāda, ka atjaunināšanas režīms tika mainīts ar lietotāja interfeisa vadīklas palīdzību. Šis notikums tiek izmantots, lai noteiktu ierīču, kas pāriet no viena režīma citā, skaitu, un tiek izmantots, lai palīdzētu noteikt, kāpēc klienti atsakās no automātiskajiem atjauninājumiem.  

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu
 
- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **Payload** — norāda, vai automātiskā lejupielāde ir izslēgta

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

### <a name="guifeedbackwindowbuttonclicked"></a>gui.feedbackwindow.buttonclicked

Šis notikums ziņo par to, vai atsauksmes tika iesniegtas vai atceltas pirms iesniegšanas. Šis notikums palīdz noteikt par konkrētā laidiena versiju iesūtīto atsauksmju skaitu. Tas palīdz ātrāk izolēt potenciālās problēmas.

Tiek apkopoti šādi lauki: 

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **ButtonType** — norāda, vai atsauksmes tiek nosūtītas vai atceltas

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija
 
- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

### <a name="guipreferenceviewconsentsheetdisplay"></a>gui.preferenceview.consentsheet.display

Šis notikums norāda, vai konkrētajam kanālam tika parādīta piekrišanas lapa, ja tāda ir. Šis notikums tiek izmantots, lai noteiktu ierīču, kas tika no jauna reģistrētas atbilstošajā auditorijas kanālā (Insider Fast / Insider Slow), skaitu. Šis notikums tiek izmantots, lai nodrošinātu to, ka piekrišanas dialoglodziņš darbojas un lietotājiem parāda lietošanas noteikumus.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **ChannelName** — kanāls, kuram tiek parādīts piekrišanas dialoglodziņš

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

### <a name="guipreferenceviewconsentsheetlicenseerror"></a>gui.preferenceview.consentsheet.licenseerror

Šis notikums ziņo par kļūdu, kas piekrišanas dialoglodziņu parādīšanas mēģinājuma laikā. Šis notikums ir kritisks un tiek izmantots, lai labotu jebkādas problēmas, kuras izraisīja izmaiņas produktā, ja attiecināms.

Tiek apkopoti šādi lauki: 

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **ErrorCode** — notikušās kļūdas kods

- **ErrorDomain** — kļūdas domēns

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

### <a name="guipreferenceviewswitchchannel"></a>gui.preferenceview.switchchannel

Šis notikums ziņo par pārēju starp lietotāja atlasītajiem kanāliem. Šis notikums tiek izmantots, lai noteiktu, kāpēc klienti atsakās no Insider kanāliem.  

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **PickedFrom** — vecais kanāls

- **PickedTo** — jaunais kanāls

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

### <a name="guiupdatemanagerapplaunchduringupdate"></a>gui.updatemanager.applaunchduringupdate

Šis notikums ziņo par to, ka programma tika palaista, kad tā tika atjaunināta, un Microsoft AutoUpdate pārtrauc palaistās programmas darbību. Ņemiet vērā, ka programmas palaišana, kad tā tiek atjaunināta, var izraisīt programmas bojājumus. Šis notikums tiek izmantots, lai nodrošinātu to, ka atjaunināšanas procesu neietekmē palaistā programma pirms tā ir gatava lietošanai.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppID** — atjaunināšanas laikā palaistās programmas identifikators.

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

- **Success** — virknes Būla vērtība, kas norāda, vai programmas darbība tika sekmīgi izbeigta.

- **UpdateID** — programmas atjauninājuma identifikators.

### <a name="guiupdatemanagerdownloadupdateforapp"></a>gui.updatemanager.downloadupdateforapp

Šis notikums ziņo par atjauninājuma lejupielādes pabeigšanas statusu. Šis notikums tiek izmantots, lai nodrošinātu atjaunināšanas procesa darbspēju un izsekotu/novērstu kļūmes punktu.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppID** — programmas identifikators.

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **IsRepair** — virknes Būla, kas norāda, vai konkrētais atjauninājums ir labojuma lejupielāde.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

- **isRepair** — norāda, vai lejupielāde bija labojuma lejupielāde iepriekš neveiksmīgam atjauninājumam.

- **UpdateID** — atjauninājuma identifikators.

- **UpdateName** — atjauninājuma nosaukums.


### <a name="guiupdatemanagererror"></a>gui.updatemanager.error

Šis notikums ziņo par kļūdām, kas notika programmas atjaunināšanas laikā. Tas var norādīt uz kļūdu Microsoft Auto Update (MAU) izpildes secībā.  Mēs izmantojam šo atskaiti, lai instalētu MAU atjauninājumus, lai novērstu biežākos kļūdu scenārijus.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — satur informāciju par kļūdu, kas notikusi programmas atjaunināšanas laikā.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

- **Success** — virknes Būla vērtība, kas norāda, vai programmas darbība tika sekmīgi izbeigta.

### <a name="guiupdatemanagerinstallcleanupforapp"></a>gui.updatemanager.installcleanupforapp

Notikums norāda, ka pagaidu faili, kas tika izveidotie programmas instalēšanas laikā tika veiksmīgi notīrīti. Tas veido daļu no atjauninājuma piltuves, kas tiek izmantota programmu darbspēju noteikšanai.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppID** — programmas identifikators.

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppState** — vesels skaitlis, kas norāda programmas stāvokli pēc atjaunināšanas mēģinājuma.

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

- **UpdateID** — atjauninājuma identifikators.


### <a name="guiupdatemanagerinstallsuccessforapp"></a>gui.updatemanager.installsuccessforapp

Šis notikums norāda uz sekmīgu programmas atjaunināšanu. Šis notikums veido daļu no atjauninājuma piltuves, kuru mēs izmantojam, lai noteiktu atjauninājumu darbspēju.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppID** — programmas identifikators.

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

- **Success** — virknes Būla, kas norāda, vai atjauninājumi tika instalēti sekmīgi.

- **UpdateID** — atjauninājuma identifikators.

### <a name="guiupdatemanagerinstallupdateforapp"></a>gui.updatemanager.installupdateforapp

Šis notikums norāda uz programmas atjauninājuma faktisko instalēšanas procesa sākumu. Šis notikums veido daļu no programmas atjauninājuma piltuves, kuru mēs izmantojam, lai noteiktu atjauninājumu darbspēju.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppID** — programmas identifikators.

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

- **UpdateID** — atjauninājuma identifikators.

### <a name="guiupdatemanagerqueueinstallforapp"></a>gui.updatemanager.queueinstallforapp

Šis notikums norāda uz programmas atjauninājuma faktisko instalēšanas procesa sākumu. Šis notikums veido daļu no programmas atjauninājuma piltuves, kuru mēs izmantojam, lai noteiktu atjauninājumu darbspēju.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppID** — programmas identifikators.

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

- **UpdateID** — atjauninājuma identifikators.

### <a name="guiupdatemanagerrelaunchapp"></a>gui.updatemanager.relaunchapp

Šis notikums reģistrē, vai programmas tika sekmīgi palaistas pēc atjauninājumiem.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppID** — programmas identifikators.

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

- **Success** — virknes Būla vērtība, kas norāda, vai programmas darbība tika sekmīgi izbeigta.

- **UpdateID** — atjauninājuma identifikators.

- **UpdateName** — atjauninājuma nosaukums.

### <a name="installdatacheckrunning"></a>installdata.checkrunning

Šis notikums reģistrē instalējamo programmu un tā, vai notiks instalēšanas mēģinājums, pamatojoties uz to, vai programma ir atvērta, pārbaudes rezultātus. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

    
### <a name="installdatacleanup"></a>installdata.cleanup

Pakotnes faili pēc instalēšanas ir jānoņem. Šis notikums reģistrē gadījumus, kad tos neizdodas noņemt. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — satur lejupielādētā faila nosaukumu un detalizētu informāciju par kļūdu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="installedappinvalidbundle"></a>installedapp.invalidbundle

Šis notikums norāda, ka Microsoft AutoUpdate norādītajā ceļā nevarēja izgūt reģistrētās programmas komplekta informāciju. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — ietver programmas nosaukumu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

    
### <a name="installedappinvalidpreference"></a>installedapp.invalidpreference

Šis notikums reģistrē gadījumus, kad lietotāja preferencē ir iekļauts nederīgs programmas ieraksts. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

    
### <a name="installedappnilbundleid"></a>installedapp.nilbundleid

Šis notikums reģistrē gadījumus, kad programmai trūkst komplekta ID. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — ietver programmas nosaukumu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="installedappnilbundlename"></a>installedapp.nilbundlename

Šis notikums reģistrē gadījumus, kad programmai trūkst komplekta nosaukuma. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — ietver programmas nosaukumu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="installedappsendcoreappleevent"></a>installedapp.sendcoreappleevent

Šis notikums norāda, ka Microsoft Auto Update (MAU) nosūta Apple notikumu uz reģistrētu programmu, lai izbeigtu programmas darbību, lai turpinātu gaidošo programmas atjaunināšanu. Šis notikums pašlaik tiek izmantots, lai palīdzētu izstrādāt uzlabojumus nākotnē, kas samazinātu lietotāju traucēšanu programmu atjaunināšanas laikā. 

Tiek apkopoti šādi lauki:

- **Acknowledged** — norāda, vai attiecīgā programma apstiprināja notikuma saņemšanu

- **App** — programmas process, kas sūta notikumu

- **AppID** — programmas, kas tiek atjaunināta, identifikators

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppleEventClass** — norāda notikuma, kas tiek nosūtīts/apstiprināts, tipu

- **AppleEventID** — notikuma, kas tiek nosūtīts/apstiprināts, unikālais identifikators

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **Payload** — satur atkārtoto mēģinājumu skaitu

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

- **Success** — norāda, vai attiecīgā programma ziņoja par sekmīgu darbības izpildi

- **UpdateID** — atjauninājuma identifikators
    
### <a name="installstatuscodesign"></a>installstatus.codesign

Šis notikums reģistrē operētājsistēmas binārā koda paraksta statusu. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu
    
- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="installstatusdaemon"></a>installstatus.daemon

Šis notikums reģistrē Microsoft AutoUpdate dēmona statusu. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **BundleReachable** — Būla vērtība, kas norāda, vai pastāv problēma, piekļūstot Microsoft AutoUpdate lietojumprogrammu komplektam.

- **Channel** — auditorijas preference

- **Codesigned** — Būla vērtība, kas norāda, vai atjaunināšanas palīgs tika pareizi piešķirts kodā.

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **Exists** — Būla vērtība, kas norāda, vai diskā ir atjaunināšanas palīgs.

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — satur norādi, vai dēmona komponents pastāv paredzamajā atrašanās vietā un vai tā kods ir parakstīts. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="installstatushelper"></a>installstatus.helper

Šis notikums reģistrē Microsoft AutoUpdate palīdzības rīka statusu. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — satur norādi, vai komponents PrivilegedHelperTool pastāv paredzamajā atrašanās vietā un vai tā kods ir parakstīts.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

    
### <a name="installupdatestaskapplaunched"></a>installupdatestask.applaunched

Šis notikums norāda, ka Microsoft AutoUpdate noteica programmas palaišanu bloķētam atjauninājumam, bet nevarēja atrast atbilstošo instalēšanas programmu. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — satur palaistās programmas nosaukumu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

    
### <a name="installupdatestaskapplaunchwithpendingupdate"></a>installupdatestask.applaunchwithpendingupdate

Šis notikums norāda, ka Microsoft AutoUpdate noteica programmas palaišanu tādai programmai, kurai tiek gaidīts atjauninājums. Palaistās programmas darbība tiks priekšlaikus pārtraukta. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

    
### <a name="installupdatestaskcodesignverificationfail"></a>installupdatestask.codesignverificationfail

Šis notikums norāda, ka programmas atjauninājumam neizdevās koda paraksta verifikācija. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — ietver identifikatoru, kas tiek lietots, lai izsekotu atjaunināšanas darbību, atjauninātās programmas nosaukumu un kļūmes kodu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="installupdatestaskcodesignverificationstart"></a>installupdatestask.codesignverificationstart

Šis notikums norāda, ka programmas atjauninājumam tika sākta koda paraksta verifikācija. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — ietver identifikatoru, kas tiek lietots, lai izsekotu atjaunināšanas darbību un atjauninātās programmas nosaukumu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="installupdatestaskcodesignverificationsuccess"></a>installupdatestask.codesignverificationsuccess

Šis notikums norāda, ka programmas atjauninājuma koda paraksta verifikācija bija sekmīga. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — ietver identifikatoru, kas tiek lietots, lai izsekotu atjaunināšanas darbību un atjauninātās programmas nosaukumu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="installupdatestaskfailsilentinstall"></a>installupdatestask.failsilentinstall

Šis notikums reģistrē kļūmes, kas rodas, lietojot kluso atjaunināšanu, kā arī to, vai tā bija klonētā vai parastā instalēšana. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 
    
- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — ietver identifikatoru, kas tiek lietots, lai izsekotu atjaunināšanas darbību un atjauninājuma tipu.
    
- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

    
### <a name="installupdatestaskmultiplerelocatablepackage"></a>installupdatestask.multiplerelocatablepackage

Šis notikums norāda, ka Microsoft AutoUpdate lejupielādētajā manifestā norādītajai atjauninājumu pakotnei atrada vairākas programmas ieraksta instances. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — ietver identifikatoru, kas tiek lietots, lai izsekotu atjaunināšanas darbību un atjauninājuma nosaukumu

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

    
### <a name="installupdatestaskremoveclone"></a>installupdatestask.removeclone

Šis notikums norāda, ka klons ir noņemts. Klons tiek noņemts, ja instalēšanas klonā process ir pabeigts vai ja tiek sākts jauns process, un datorā ir atrasta vecāka klonēta versija. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — ietver identifikatoru, kas tiek lietots, lai izsekotu atjaunināšanas darbību, atjauninājuma nosaukumu, atjauninājumu pakotnes nosaukumu, klona noņemšanas statusu/detalizētu informāciju par kļūdu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="installupdatestaskretryfail"></a>installupdatestask.retryfail

Šis notikums norāda, ka atkārtota instalēšanas mēģinājuma laikā radās kļūdas. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — ietver identifikatoru, kas tiek lietots, lai izsekotu atjaunināšanas darbību, atjauninājuma nosaukumu un informāciju par to, vai instalēšana ir jāveic, izmantojot instalēšanu klonā

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

   
### <a name="installupdatestaskretryproxyerror"></a>installupdatestask.retryproxyerror

Šis notikums reģistrē iekšējā procesa saziņas kļūdas (saziņa ar MAU palīga rīku). Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — ietver identifikatoru, kas tiek lietots, lai izsekotu atjaunināšanas darbību, atjauninājuma nosaukumu un detalizētu informācija par ziņoto starpniekservera kļūdu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

    

### <a name="installupdatestaskretryresponse"></a>installupdatestask.retryresponse

Šis notikums reģistrē atkārtota mēģinājuma neizdošanos. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — ietver identifikatoru, kas tiek lietots, lai izsekotu atjaunināšanas darbību, atjauninājuma nosaukumu, programmas versijai, atjauninājumu pakotnes nosaukumu un norādi par to, vai bija ieslēgta instalēšana klonā, vai instalēšana notika sekmīgi, kā arī kļūmes gadījumā visas ziņotās kļūdas.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="installupdatestaskretrysuccess"></a>installupdatestask.retrysuccess

Šis notikums reģistrē sekmīgu atjauninājumu instalēšanu pēc atkārtota mēģinājuma. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — ietver identifikatoru, kas tiek lietots, lai izsekotu atjaunināšanas darbību, atjauninājuma nosaukumu, programmas versijai, atjauninājumu pakotnes nosaukumu un norādi par to, vai bija ieslēgta instalēšana klonā.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="installupdatestasksetreopengui"></a>installupdatestask.setreopengui

Šis notikums norāda, vai iestatījuma preference pēc instalēšanas atkārtoti atvērt GUI bija sekmīga. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda darbības sekmīgumu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="installupdatestaskupdatestatus"></a>installupdatestask.updatestatus

Šis notikums ziņo par instalēšanas uzdevuma statusu. Šis notikums veido daļu no atjauninājuma piltuves un tiek izmantots, lai noteiktu programmu atjauninājumu darbspēju.

Tiek apkopoti šādi lauki: 

- **App** — programmas process, kas sūta notikumu

- **AppID** — programmas, kas tiek atjaunināta, identifikators

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Error** — norāda kļūdas, kas notika atjaunināšanas procesa laikā, ja aizpildīts.

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **IOC** — norāda, vai tika izmantots līdzeklis Instalēt klonā

- **Payload** — statisks teksts, kas norāda uz instalēšanas procesa sākumu, ja ir

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

- **Success** — norāda, vai instalēšanas process tika sekmīgi pabeigts

- **UpdateID** — programmas atjauninājuma identifikators

- **UpdateName** — atjauninājuma nosaukums, kā norādīts lejupielādētajā manifesta failā

- **UpdatePkg** — instalējamās atjauninājuma pakotnes nosaukums

### <a name="lifecyclecomplimentproclaunch"></a>Lifecycle.complimentproclaunch

Šis notikums norāda uz mēģinājumu palaist Microsoft Update palīgu no Microsoft AutoUpdate vai no Microsoft AutoUpdate no Microsoft Update palīga. Šis notikums tiek izmantots, lai noteiktu un nodrošinātu Microsoft AutoUpdate un Microsoft Update palīga darbspēju.

Tiek apkopoti šādi lauki.

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Error** — jebkura kļūda, par kuru tiek ziņots palaišanas mēģinājuma laikā

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **Reason** — iemesls mēģinājumam palaist papildu procesu

- **SessionId** — sesijas identifikators

- **Success** — norāda, vai programmas atjaunināšana bija sekmīga

### <a name="lifecyclelaunch"></a>Lifecycle.launch

Šis notikums norāda uz Microsoft AutoUpdate vai Microsoft Update palīga palaišanu. Šis notikums tiek arī izmantots, lai ziņotu par jebkādām palaišanas procesa laikā atklātajām problēmām, kā arī ziņošanai par izmantoto Microsoft Update palīga palaišanas metodi.

*[Šis notikums aizstāj fba.launch un appdelegate.launch notikumus.]*

Tiek apkopoti šādi lauki.

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Error** — jebkura palaišanas laikā atklātā kļūda

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **LaunchedBy** — Microsoft Update palīga palaišanai izmantotā metode, ja attiecināms

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

### <a name="lifecycleperiodiccheck"></a>Lifecycle.periodiccheck

Šis notikums periodiski ziņo par MicrosoftAutoUpdate procesa statusu. Konkrēti, tas ziņo par to, kādi atlikušie uzdevumi gaida Update Assistant pabeigšanu, un lietotāja saskarnes gadījumā ziņo par to, vai process tiek pārtraukts lietotāja neaktivitātes dēļ.  Mēs izmantojam šo notikumu, lai noteiktu, kas traucē Update Assistant pabeigt atjauninājumus un pārtraukt darbību, un vai lietotāja interfeiss tiek pārtraukts lietotāja neaktivitātes dēļ.

Tiek apkopoti šādi lauki.

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **dataCollectionDialog** — Būla vērtība, norādot, vai process gaida lietotāja atbildi datu apkopošanas dialoglodziņā

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **forcedUpdateDialog** — Būla vērtība, norādot, vai process gaida, kad lietotājs reaģēs uz dialoglodziņu piespiedu atjaunināšana

- **HowToCheck** — kā pārbaudīt iestatījumu

- **isBusy** — Būla vērtība, norādot, vai process ir aizņemts, izmantojot aktīvo atjaunināšanu

- **isInactive** — Būla vērtība, norādot, vai process ilgāku laiku ir gaidījis lietotāja darbību

- **isWaiting** — Būla vērtība, norādot, vai process gaida lietotāja atbildi uz paziņojumu

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

- **SessionLength** — pašreizējās procesa sesijas ilgums sekundēs


### <a name="lifecycleterminate"></a>Lifecycle.terminate

Šis notikums norāda uz Microsoft AutoUpdate vai Microsoft Update palīga izbeigšanu. Šis notikums tiek izmantots, lai noteiktu Microsoft AutoUpdate un Microsoft Update palīga darbspēju.

*[Šis notikums aizstāj fba.terminate un appdelegate.terminate notikumus.]*

Tiek apkopoti šādi lauki.

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

- **SessionLength** — pašreizējās procesa sesijas ilgums sekundēs



### <a name="msupdateclieventhandler"></a>msupdate.cli.eventhandler

Šis notikums tiek izmantots, lai aprēķinātu dažādu Microsoft Auto Update (MAU) komandrindas interfeisa API.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppID** — programmas, kas nosūta komandrindas interfeisa API uz MAU, identifikators.

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **EventType** — notikuma, kuru programma sūta uz MAU komandrindas interfeisa API, tips.

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators


### <a name="msupdateclieventhandlerapplyupdatesappids"></a>msupdate.cli.eventhandler.applyupdates.appids

Šis notikums norāda, ka tika izdota CLI (klienta rindas interfeiss) komanda, lai lietotu atjauninājumu. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — satur atjaunināmo programmu ID sarakstu.
    
- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="msupdateclieventhandlerconfig"></a>msupdate.cli.eventhandler.config

Šis notikums norāda, ka Microsoft AutoUpdate komandrindas interfeisa modulis saņēma Apple notikumu, lai veiktu konfigurēšanu. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="msupdateclieventhandlerupdates"></a>msupdate.cli.eventhandler.updates

Šis notikums norāda, ka Microsoft AutoUpdate komandrindas interfeisa modulis saņēma Apple notikumu, lai uzskaitītu atjauninājumus. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

    
### <a name="msupdatemonitorprogressdownloaded"></a>msupdate.monitor.progress.downloaded

Šis notikums norāda, ka atjauninājumi ir lejupielādēti. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — satur lejupielādēto atjauninājumu sarakstus

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="msupdatemonitorprogressfailure"></a>msupdate.monitor.progress.failure

Šis notikums reģistrē sarakstu ar rindā iekļautajiem atjauninājumiem, kurus neizdevās lietot. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — satur atjauninājumu sarakstus.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

    
### <a name="msupdatemonitorprogressfinished"></a>msupdate.monitor.progress.finished

Šis notikums reģistrē sarakstu ar rindā iekļautajiem atjauninājumiem, kuru instalēšana ir pabeigta. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — satur atjauninājumu sarakstus.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="msupdatemonitorprogressqueued"></a>msupdate.monitor.progress.queued

Šis notikums reģistrē sarakstu ar rindā iekļautajiem atjauninājumiem. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — satur atjauninājumu sarakstus.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="optinnotificationaction"></a>Optinnotificationaction

Šis notikums reģistrē lietotāja atbildi uz piekrišanas dialogu, lai izmantotu kluso atjaunināšanu. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — satur statisku tekstu, kas norāda lietotāja atlasi piekrišanai automātiski lejupielādēt un instalēt.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="sauforcedupdateautodismiss"></a>sauforcedupdate.autodismiss

Šis notikums norāda, ka parādītais piespiedu atjaunināšanas dialoglodziņš tiek noraidīts lietotāja neaktivitātes dēļ. Šis notikums tiek izmantots, lai noteiktu piespiedu atjauninājumu, kas tiek izpildīti bez lietotāju reakcijas uz parādīto paziņojumu, skaitu. Šis notikums tiek izmantots, lai samazinātu traucējumus, uzlabojot lietotāja interfeisu.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis
  
- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **Payload** — statisks teksts

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

### <a name="sauforcedupdateclose"></a>sauforcedupdate.close

Šis notikums norāda, ka lietotājs izvēlējās aizvērt piespiedu atjaunināšanas dialoglodziņu. Šis notikums tiek izmantots, lai noteiktu piespiedu atjauninājumu, kas ir aizkavēti lietotāja darbību dēļ, skaitu. Šis notikums tiek izmantots, lai samazinātu traucējumus, uzlabojot lietotāja interfeisu. 

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **Payload** — statisks teksts

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

### <a name="sauforcedupdatecompleteautodismiss"></a>sauforcedupdate.completeautodismiss

Šis notikums norāda, ka parādītais piespiedu atjaunināšanas dialoglodziņš no izpildes termiņa līdzekļa tiek noraidīts lietotāja neaktivitātes dēļ. Šis notikums tiek izmantots, lai noteiktu piespiedu atjauninājumu, kas tiek izpildīti bez lietotāju reakcijas uz parādīto paziņojumu, skaitu. Šis notikums tiek izmantots, lai samazinātu izpildes termiņa līdzekļa traucējumus, uzlabojot lietotāja interfeisu.

Tiek apkopoti šādi lauki: 

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **Payload** — statisks teksts

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

### <a name="sauforcedupdatecompleteclose"></a>sauforcedupdate.completeclose

Šis notikums norāda uz piespiedu atjaunināšanas sekmīgu pabeigšanu. Šis notikums tiek izmantots, lai noteiktu piespiedu atjaunināšanas līdzekļa darbspēju. 

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **Payload** — statisks teksts

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

### <a name="sauforcedupdatedisplay"></a>sauforcedupdate.display

Šis notikums norāda, ka tika parādīts piespiedu atjaunināšanas dialoglodziņš.  Šis notikums veido daļu no piespiedu atjaunināšanas piltuves un tiek izmantots, lai noteiktu piespiedu atjaunināšanas līdzekļa darbspēju.

Tiek apkopoti šādi lauki: 

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **Payload** — statisks teksts

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

### <a name="sauforcedupdatedisplayfinalhour"></a>sauforcedupdate.displayfinalhour

Šis notikums norāda, ka tika parādīts piespiedu atjaunināšanas pēdējās stundas dialoglodziņš. Šis notikums veido daļu no piespiedu atjaunināšanas piltuves un tiek izmantots, lai noteiktu piespiedu atjaunināšanas līdzekļa darbspēju.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **Payload** — statisks teksts

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

### <a name="sauforcedupdatedone"></a>sauforcedupdate.done

Šis notikums norāda, ka piespiedu atjaunināšana tika sekmīgi pabeigta. Šis notikums veido daļu no piespiedu atjaunināšanas piltuves un tiek izmantots, lai noteiktu piespiedu atjaunināšanas līdzekļa darbspēju. 

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **Payload** — statisks teksts

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

### <a name="sauforcedupdateenabled"></a>sauforcedupdate.enabled

Šis notikums tiek izraisīts, kad Microsoft Auto Update (MAU) nosaka, ka ir piemērojama piespiedu atjaunināšana.  Šis notikums tiek izmantots, lai noteiktu piespiedu atjaunināšanas līdzekļa darbspēju. 

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Enabled** — norāda, vai ir iespējota piespiedu atjaunināšana

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **InvalidUpdates** — piespiedu atjauninājumu ar nederīgām atjauninājumu versijām skaits

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

### <a name="sauforcedupdateforcedupdatedismiss"></a>sauforcedupdate.forcedupdatedismiss

Šis notikums norāda, ka parādītais piespiedu atjaunināšanas pēdējās stundas dialoglodziņš tiek noraidīts lietotāja neaktivitātes dēļ. Šis notikums tiek izmantots, lai noteiktu piespiedu atjauninājumu, kas tiek izpildīti bez lietotāju reakcijas uz parādīto paziņojumu, skaitu. Šis notikums tiek izmantots, lai samazinātu traucējumus, uzlabojot lietotāja interfeisu. 

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **Payload** — statisks teksts

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

### <a name="sauforcedupdateforcequitandupdatenow"></a>sauforcedupdate.forcequitandupdatenow

Šis notikums norāda uz lietotāja sāktās piespiedu atjaunināšanas sākumu. Šis notikums veido daļu no piltuves un tiek izmantots, lai noteiktu piespiedu atjauninājuma līdzekļa darbspēju. 

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **Payload** — statisks teksts

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators 

### <a name="sauforcedupdateforceterminate"></a>sauforcedupdate.forceterminate

Šis notikums norāda uz piespiedu atjaunināšanas sākumu, izbeidzot programmas darbību piespiedu kārtā.  Šis notikums veido daļu no piltuves un tiek izmantots, lai noteiktu piespiedu atjauninājuma līdzekļa darbspēju.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **Payload** — satur programmu, kuru darbība ir jāizbeidz, skaitu

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

### <a name="sauforcedupdatequitandupdatenow"></a>sauforcedupdate.quitandupdatenow

Šis notikums norāda, ka lietotājs izvēlējās aizvērt programmu un instalēt atjauninājumu. Šis notikums veido daļu no piltuves un tiek izmantots, lai noteiktu piespiedu atjaunināšanas līdzekļa darbspēju. 

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **Payload** — statisks teksts

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

### <a name="sauforcedupdatesnooze"></a>sauforcedupdate.snooze

Šis notikums norāda, ka lietotājs izvēlējās atlikt piespiedu atjaunināšanu. Šis notikums veido daļu no piltuves un tiek izmantots, lai noteiktu piespiedu atjauninājuma līdzekļa darbspēju. 

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **Payload** — statisks teksts

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

### <a name="sauforcedupdateterminate"></a>sauforcedupdate.terminate

Šis notikums norāda uz piespiedu atjaunināšanas sākumu, izbeidzot programmas darbību. Šis notikums veido daļu no piltuves un tiek izmantots, lai noteiktu piespiedu atjauninājuma līdzekļa darbspēju.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **Payload** — satur programmu, kuru darbība ir jāizbeidz, skaitu

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

### <a name="sauforcedupdateupdatenow"></a>sauforcedupdate.updatenow

Šis notikums norāda, ka lietotājs izvēlējās atjaunināt programmu tagad.  Šis notikums veido daļu no piltuves un tiek izmantots, lai noteiktu piespiedu atjauninājuma līdzekļa darbspēju.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **Payload** — statisks teksts

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators


### <a name="sauupdateinfoprovider"></a>sauupdateinfoprovider

Šis notikums reģistrē manifesta atslēgas iztrūkumu papildmateriālos. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — satur virkni, kas izmantota, lai meklētu atjauninājuma atrašanās vietu vai lielumu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="updateapplaunchdetected"></a>update.applaunchdetected

Šis notikums norāda, ka programma tika palaista brīdī, kad notika atjaunināšana. Šis notikums tiek izmantots, lai noteiktu programmu, kas tiek palaistas atjaunināšanas laikā, skaitu un tiek izmantots, lai uzlabotu lietotāju ērtības nākotnes laidienos.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppID** — programmas, kas tiek atjaunināta, identifikators

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

- **Success** — norāda, vai palaistās programmas darbība tika sekmīgi izbeigta

- **UpdateID** — programmas atjauninājuma identifikators

### <a name="updateappterminationreceived"></a>update.appterminationreceived

Šis notikums norāda, ka programmas ar bloķētu atjauninājumu darbība tika izbeigta, un Microsoft Auto Update (MAU) var turpināt atjaunināšanu. Šis notikums veido daļu no piltuves un tiek izmantots, lai noteiktu programmu atjauninājumu darbspēju.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppID** — programmas, kas tiek atjaunināta, identifikators

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Error** — norāda, vai vēl ir programmas eksemplāri, kas joprojām darbojas un neļauj MAU turpināt darbību

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **Payload** — statisks teksts, kas norāda, ka MAU turpina atjaunināšanu

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

- **UpdateID** — programmas atjauninājuma identifikators

### <a name="updateblockedappclosed"></a>update.blockedappclosed

Šis notikums norāda, ka Microsoft Auto Update (MAU) atklātā programma ar bloķēto atjauninājumu tika aizvērta un MAU var turpināt atjaunināšanu. Šis notikums veido daļu no piltuves un tiek izmantots, lai noteiktu programmu atjauninājumu darbspēju. 

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppID** — programmas, kas tiek atjaunināta, identifikators

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija.

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums.

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums. 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **Payload** — statisks teksts

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

- **UpdateID** — programmas atjauninājuma identifikators

### <a name="updateblockedinstallskip"></a>update.blockedinstallskip

Šis notikums reģistrē kļūdas, kas notiek mēģinot izlaist programmas atjaunināšanu. Šis notikums ir kritisks un tiek izmantots, lai izpētītu ziņotās kļūdas.  

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppID** — programmas, kas tiek atjaunināta, identifikators

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **Payload** — satur informāciju par notikušo kļūdu

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

### <a name="updateclientsession"></a>update.clientsession

Par šo notikumu tiek ziņots, kad notiek klienta ierīces statusa izmaiņas, kuru rezultātā Microsoft Update Assistant pauzē vai turpina atjaunināšanas procesu. Šis notikums veido daļu no piltuves un tiek izmantots, lai noteiktu programmu atjauninājumu darbspēju. 

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **Payload** — norāda, vai Microsoft Auto Update (MAU) veic atsākšanu vai pauzēšanu

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

### <a name="updatedownloadbegin"></a>update.download.begin 

Šis notikums norāda uz programmas atjaunināšanas procesa sākumu. Šis notikums veido daļu no atjauninājuma piltuves un tiek izmantots, lai noteiktu programmu atjauninājumu darbspēju. 

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppID** — programmas, kas tiek atjaunināta, identifikators

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **IsRepair** — norāda, vai atjaunināšanas mērķis ir labot neizdevušos atjaunināšanu

- **Payload** — norāda, vai iepriekš tika mēģināts veikt lejupielādi

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

- **UpdateName** — atjauninājuma nosaukums, kā norādīts lejupielādētajā manifesta failā

### <a name="updatedownloadfinish"></a>update.download.finish

Šis notikums norāda programmas atjauninājuma lejupielādes posma beigas. Šis notikums veido daļu no atjauninājuma piltuves un tiek izmantots, lai noteiktu programmu atjauninājumu darbspēju.  

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppID** — programmas, kas tiek atjaunināta, identifikators

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **IsRepair** — norāda, vai atjaunināšanas mērķis ir labot neizdevušos atjaunināšanu

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

- **UpdateID** — programmas atjauninājuma identifikators

- **UpdateName** — atjauninājuma nosaukums, kā norādīts lejupielādētajā manifesta failā

### <a name="updatedownloadresume"></a>update.downloadresume

Šis notikums ziņo par kļūdu, kas notiek pauzēta lejupielādes uzdevuma atsākšanas mēģinājuma laikā. Šis notikums ir kritisks un tiek izmantots, lai izpētītu ziņotās kļūdas. 

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppID** — programmas, kas tiek atjaunināta, identifikators

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Error** — norāda notikušās kļūdas būtību

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

- **UpdateID** — programmas atjauninājuma identifikators

### <a name="updateerror"></a>update.error

Šis notikums ziņo par kļūdu, kas notiek reģistrētas programmas atjaunināšanas mēģinājuma laikā.  Šis notikums ir kritisks un tiek izmantots, lai izpētītu ziņotās kļūdas. 

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Payload** — satur informāciju par notikušās kļūdas būtību

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **Payload** — satur informāciju par notikušās kļūdas būtību

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

### <a name="updateinstallcleanupforapp"></a>update.installcleanupforapp

Šis notikums norāda, ka atjauninājuma instalēšana ir pabeigt un Microsoft Auto Update (MAU) veic tīrīšanu.  Šis notikums veido daļu no atjauninājuma piltuves un tiek izmantots, lai noteiktu programmu atjauninājumu darbspēju.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppID** — programmas, kas tiek atjaunināta, identifikators

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppState** — reģistrētas programmas statuss. Var norādīt kā kļūda, gaida labojumus utt.

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

- **UpdateID** — programmas atjauninājuma identifikators

### <a name="updateinstallupdateforapp"></a>update.installupdateforapp

Šis notikums tiek izmantots, lai ziņotu par programmas atjauninājuma instalēšanas sākšanu. Šis notikums veido daļu no atjauninājuma piltuves un tiek izmantots, lai noteiktu programmu atjauninājumu darbspēju. 

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppID** — programmas, kas tiek atjaunināta, identifikators

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Error** — notikušās kļūdas, ja ir

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

- **UpdateID** — programmas atjauninājuma identifikators

- **UpdateName** — atjauninājuma nosaukums, kā norādīts lejupielādētajā manifesta failā

### <a name="updateinstallupdateforappsuccess"></a>update.installupdateforapp.success

Šis notikums ziņo par instalēšanas uzdevuma statusu. Šis notikums veido daļu no atjauninājuma piltuves un tiek izmantots, lai noteiktu programmu atjauninājumu darbspēju. 

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppID** — programmas, kas tiek atjaunināta, identifikators

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **Payload** — norāda, vai instalēšanas procesa laikā tika parādīts procesa skats

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

- **Success** — instalēšanas uzdevums atgrieza norādi par sekmīgu izpildi

- **UpdateID** — programmas atjauninājuma identifikators

### <a name="updateinstallvariance"></a>Update.InstallVariance

Šis notikums tiek izmantots, lai aprēķinātu MAU kritiskā atjauninājuma darbspējas rādītāju. Šis notikums ļauj mums noteikt instalēšanas prioritātes līdzekļa sekmīguma metriku un pārbaudīt līdzekļa integritāti.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — satur programmu ID sarakstu un tām atbilstošo instalēšanas prioritāti, kas ir norādīta skaitļos.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

### <a name="updatemultipleappupdates"></a>update.multipleappupdates 

Šis notikums norāda uz vairākām izpildes procesā esošām programmu atjaunināšanām, kas notiek fonā. Šis notikums veido daļu no atjauninājuma piltuves un tiek izmantots, lai noteiktu programmu atjauninājumu darbspēju.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators 

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **Payload** — satur informāciju par atjaunināmo programmu skaitu

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

### <a name="updatepreviousidnil"></a>update.previousidnil

Šis notikums norāda, ka tiek lejupielādēta labojumu pakotne, bet nav iepriekšējās lejupielādes informācijas. Šis notikums ir kritisks un tiek izmantots, lai izpētītu ziņotās kļūdas. 

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppID** — programmas, kas tiek atjaunināta, identifikators

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Error** — norāda notikušās kļūdas būtību

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

### <a name="updatequeueinstallforapp"></a>update.queueinstallforapp 

Šis notikums norāda, ka lejupielādētā atjauninājuma pakotne ir ievietota instalēšanas rindā.  Šis notikums veido daļu no atjauninājuma piltuves un tiek izmantots, lai noteiktu programmu atjauninājumu darbspēju.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppID** — programmas, kas tiek atjaunināta, identifikators

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **Payload** — statisks teksts, kas norāda, ka programmu ir jāaizver, ja ir

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

- **UpdateID** — programmas atjauninājuma identifikators

- **UpdateName** — atjauninājuma nosaukums, kā norādīts lejupielādētajā manifesta failā

### <a name="updaterelaunchafterupdate"></a>update.relaunchafterupdate 

Šis notikums norāda, ka programmas atjaunināšana tika pabeigta un programma tiek palaista atkārtoti. Šis notikums veido daļu no atjauninājuma piltuves un tiek izmantots, lai noteiktu programmu atjauninājumu darbspēju. 

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppID** — programmas, kas tiek atjaunināta, identifikators

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Error** — satur informāciju par kļūdām, kas ir notikušas, mēģinot atkārtoti palaist programmu

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

- **UpdateID** — programmas atjauninājuma identifikators

### <a name="updatetimerforapptermination"></a>update.timerforapptermination 

Šis notikums norāda uz programmas statusa pārbaudes taimera sākumu/beigām. Šis notikums ir sapārots un tiek izmantots, lai noteiktu, vai ir noņemti visi taimera objekti, kad notiek programmas atjaunināšana.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **Payload** — norāda, vai taimeris tika pievienots vai noņemts

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators


### <a name="updatecoreappregistration"></a>updatecore.appregistration

Šis notikums reģistrē mēģinājumus reģistrēt programmu un rezultātu/iemeslu. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — ietver identifikatoru, kas tiek lietots, lai izsekotu atjaunināšanas darbību, norādi par to, vai ir pieejama preference, norādi par to, vai tā ir atkārtota reģistrācija, un norādi par to, vai ir nepieciešama reģistrācija.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="updatecoreloadinglaunchagent"></a>updatecore.loadinglaunchagent

Šis notikums norāda palaišanas aģenta ielādi. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

### <a name="updatecorerunnstaskcommand"></a>updatecore.runnstaskcommand

Šis notikums ziņo par kļūdām uzdevuma palaišanas laikā. Šis notikums ir kritisks un tiek izmantots, lai izpētītu ziņotās kļūdas.  

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **Payload** — satur ceļu uz komandu, kas tiek izpildīta

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

### <a name="updatecoreserverconnectionfail"></a>updatecore.server.connectionfail

Šis notikums reģistrē kļūdas, kas rodas, sazinoties ar CDN. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — ietver informāciju par servera nosaukumu, vai serveris ir derīgs un vai serveris ir sasniedzams.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

### <a name="updatecoreservernullurl"></a>updatecore.server.nullurl

Šis notikums ziņo par kļūdu, kas norāda, ka konkrēto serveri nav iespējams sasniegt. Šis notikums tiek izmantots, lai noteiktu atjaunināšanas neizdošanās tīkla problēmu dēļ gadījumu skaitu. 

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **Payload** — statisks teksts

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

### <a name="updatefilterhelpercannotretrievebuilddate"></a>updatefilterhelper.cannotretrievebuilddate

Izmantojot MAU pakalpojumu, varam filtrēt atjauninājumus tikai tad, ja piedāvātais atjauninājums nav vecāks par noteiktu dienu skaitu. Šeit reģistrējam, ka no programmas metadatiem nevarējām izgūt datumu. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — satur programmas ID.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="updatefilterhelperinvalidappid"></a>updatefilterhelper.invalidappid

Šis notikums ziņo par kļūdu, norādot, ka nevar atrast no tīmekļa atbildes izgūtajam programmas ID atbilstošus manifesta failus. Šis notikums tiek izmantots, lai izpētītu ziņoto kļūdu.

Tiek apkopoti šādi lauki: 

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **Payload** — satur tīmekļa atbildē norādīto programmas ID

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

### <a name="updatefilterhelperinvalidappidfromwebservices"></a>updatefilterhelper.invalidappidfromwebservices

Šis notikums ziņo par kļūdu, kas norāda, ka no tīmekļa atbildes izgūtais programmas ID nav paredzētajā formātā. Šis notikums tiek izmantots, lai izpētītu ziņoto kļūdu.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **Payload** — statisks teksts

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

### <a name="updatefilterhelperinvalidresponsefromupdatefiltering"></a>updatefilterhelper.invalidresponsefromupdatefiltering

Izmantojot MAU pakalpojumu, varam filtrēt atjauninājumus tikai tad, ja piedāvātais atjauninājums nav vecāks par noteiktu dienu skaitu. Šeit reģistrējam, ka programmas metadatos trūkst datuma. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 
    
- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — satur programmas ID.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="updatefilterhelpermissingbuilddate"></a>updatefilterhelper.missingbuilddate

Izmantojot MAU pakalpojumu, varam filtrēt atjauninājumus tikai tad, ja piedāvātais atjauninājums nav vecāks par noteiktu dienu skaitu. Šeit reģistrējam, ka programmas metadatos trūkst datuma. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — satur programmas ID.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="updatefilterhelperupdatebypassedoldage"></a>updatefilterhelper.updatebypassedoldage

Izmantojot MAU pakalpojumu, varam filtrēt atjauninājumus tikai tad, ja piedāvātais atjauninājums nav vecāks par noteiktu dienu skaitu. Šeit reģistrējam pakalpojuma apiešanu sena atjauninājuma datuma dēļ. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — satur programmas ID.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="updatefindercheckerror"></a>updatefinder.check.error

Šis notikums ziņo par kļūdu, kas notiek pieejamo atjauninājumu pārbaudes laikā. Šis notikums ir kritisks un tiek izmantots, lai izpētītu ziņoto kļūdu. 

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Code** — kļūdas kods 

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Domain** — kļūdas domēns

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

 
### <a name="updatefindercheckstart"></a>updatefinder.check.start

Šis notikums reģistrē gadījumus, kad tiek sākta pārbaude, vai nav atjauninājumu. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu
    
- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — satur informāciju par piedāvājamajiem atjauninājumiem, reģistrētajām programmām un pagaidu atrašanās vietu, kur tiks saglabāti lejupielādētie faili.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="updatefindercheckstatus"></a>updatefinder.check.status

Šis notikums apkopo pārbaužu, vai nav atjauninājumu, statusu (piltuve no meklēšanas līdz lejupielādei). Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — satur informāciju par piedāvājamajiem atjauninājumiem, reģistrētajām programmām un pagaidu atrašanās vietu, kur tiks saglabāti lejupielādētie faili.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="updatefindercheckupdatefound"></a>updatefinder.check.updatefound

Reģistrējam ikreiz, kad pārbaudes, vai nav atjauninājumu, rezultātā tiek atrasti atjauninājumi. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="updatefindercheckupdatenotfound"></a>updatefinder.check.updatenotfound

Reģistrējam ikreiz, kad pārbaudes, vai nav atjauninājumu, rezultātā netiek piedāvāti atjauninājumi, jo neviens atjauninājums nav atrasts. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="updatefindercheckuptodate"></a>updatefinder.check.uptodate

Reģistrējam ikreiz, kad pārbaudes, vai nav atjauninājumu, rezultātā netiek piedāvāti atjauninājumi, jo visas programmas jau ir atjauninātas. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="updatefinderofferupdatesinvalidappid"></a>updatefinder.offerupdates.invalidappid

Šis notikums ziņo par kļūdu, mēģinot novērtēt, vai atjauninājums ir piemērojams. Šis notikums ir kritisks un tiek izmantots, lai izpētītu ziņoto kļūdu.  

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **CatalogID** — kataloga, kuram piekļūts, identifikators

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **IsNullID** — norāda, vai ID ir null

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

### <a name="updatefinderofferupdatesminoscheckfail"></a>updatefinder.offerupdates.minoscheckfail

Reģistrējam ikreiz, kad bloķējam kādu atjauninājumu, jo nav atbilstības operētājsistēmas prasībām. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — ietver minimālo nepieciešamo operētājsistēmas versiju, kā tas ir norādīts lejupielādētā manifesta failā.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

### <a name="updatefinderofferupdatesmissingtrigger"></a>updatefinder.offerupdates.missingtrigger

Šis notikums ziņo par kļūdu, kas notiek mēģinot novērtēt trigerus lejupielādētajā programmas atjauninājuma manifestā. Tas ir kritisks un tiek izmantots, lai izpētītu ziņoto kļūdu.  

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

- **TriggerKey** — manifestā norādītā trigera atslēga

- **Triggers** — manifestā norādītā trigeru vārdnīca

### <a name="updatefinderofferupdatesnullbundleforappid"></a>updatefinder.offerupdates.nullbundleforappid

Šis notikums norāda, ka Microsoft AutoUpdate lejupielādētajā manifestā norādītajam programmas ID nevarēja ielādēt komplekta informāciju. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — satur programmas ID.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="updatefinderofferupdatesupdaterulematched"></a>updatefinder.offerupdates.updaterulematched

Šis notikums norāda, ka programmai un bāzlīnijai tika atrasts atjauninājums. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — ietver programmas ID un komplekta versijas informāciju.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

    
### <a name="updatefinderregisteredapps"></a>updatefinder.registeredapps

Reģistrējam programmas, kas tiek instalētas/reģistrētas/MAU kontrolētas. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — ietver programmas ID un komplekta versijas informāciju.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

### <a name="updatefindersuiteinvalidsuiteversion"></a>updatefinder.suite.invalidsuiteversion

Šis notikums ziņo par komplekta versijas kļūdu, kas notiek mēģinot novērtēt, vai atjauninājums ir piemērojams. Šis notikums ir kritisks un tiek izmantots, lai izpētītu ziņoto kļūdu.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

- **Suite** — konkrētā komplekta nosaukums

### <a name="updatefindersuitekeyvaluemissing"></a>updatefinder.suite.keyvaluemissing

Šis notikums ziņo par kļūdu, kas notiek, mēģinot pievienot programmu komplektam. Šis notikums ir kritisks un tiek izmantots, lai izpētītu ziņoto kļūdu.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppID** — programmas, kas tiek atjaunināta, identifikators

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators 

- **Suite** — komplekta, kuram tiks pievienota programma, nosaukums

    
### <a name="updatefindersuitemissingcollateral"></a>updatefinder.suite.missingcollateral

Komplekta atjaunināšana — reģistrējam gadījumus, kad komplekta atjaunināšana nav lietojama, jo trūkst papildmateriālu. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — teksts, kas norāda notikuma dabu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="updatefindersuitestaleversion"></a>updatefinder.suite.staleversion

Komplekta atjaunināšana — reģistrējam gadījumus, kad komplekta atjaunināšana nav lietojama, jo bāzes versija ir pārāk veca. Reģistrējam bāzlīnijas versiju un komplekta AppId. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — ietver komplekta nosaukumu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="updatefindersuiteupdateapplicable"></a>updatefinder.suite.updateapplicable

Komplekta atjaunināšana — reģistrējam gadījumus, kad komplekta atjaunināšana ir lietojama. Reģistrējam bāzlīnijas versiju un komplekta AppId. Reģistrējam bāzlīnijas versiju un komplekta AppId. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — ietver komplekta nosaukumu, bāzlīniju un atjauninājuma versiju.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="updatefindersuiteupdatenotapplicabledefaultpath"></a>updatefinder.suite.updatenotapplicabledefaultpath

Komplekta atjaunināšana — reģistrējam gadījumus, kad komplekta atjaunināšana netiek piedāvāta, jo ne visas komplekta programmas tiek instalētas, izmantojot noklusējuma ceļu. Reģistrējam bāzlīnijas versiju un komplekta AppId. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — ietver komplekta nosaukumu, bāzlīniju un atjauninājuma versiju.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

    
### <a name="updatefindersuiteupdatenotapplicableversion"></a>updatefinder.suite.updatenotapplicableversion

Komplekta atjaunināšana — reģistrējam gadījumus, kad komplekta atjaunināšana netiek piedāvāta, jo ne visas komplekta programmas ir vienā bāzes versijā. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — ietver komplekta nosaukumu, bāzlīniju un atjauninājuma versiju.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="updatefindersuiteupdatenotoffered"></a>updatefinder.suite.updatenotoffered

Komplekta atjaunināšana — reģistrējam gadījumus, kad komplekta atjaunināšana netiek piedāvāta, jo komplekta lielums pārsniedz atsevišķo atjauninājumu lielumu. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — ietver komplekta nosaukumu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="updatefindersuiteupdateoffered"></a>updatefinder.suite.updateoffered

Komplekta atjaunināšana — reģistrējam gadījumus, kad komplekta atjaunināšana tiek piedāvāta. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — ietver komplekta nosaukumu, bāzlīniju un atjauninājuma versiju.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="updatemanagercheckupdate"></a>updatemanager.checkupdate

Šis notikums reģistrē vairākus atjauninājumus, kurus Microsoft AutoUpdate atrada pārbaudot, vai nav atjauninājumu. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — satur atrasto pieejamo atjauninājumu skaitu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

    
### <a name="updatemanagerupdatespending"></a>updatemanager.updatespending

Šis notikums norāda, ka atjauninājumi ir atrasti un gaida instalēšanu. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — satur norādi, vai uzdevums tiek izpildīts galvenajā pavedienā, un gaidāmo atjauninājumu skaitu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

### <a name="updatestatuscodesign"></a>UpdateStatus.Codesign

Šis notikums ziņo par koda paraksta verifikācijas, kuru Microsoft Update Assistant palaiž pēc klienta programmu atjauninājumu instalēšanas, statusu. Šis notikums tiek izmantots, lai nodrošinātu to, ka nodrošinātās pakotnes ir derīgas un atjauninās instalēto programmu līdz jaunākajai versijai.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppID** — programmas, kas tiek atjaunināta, identifikators

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Error** — kļūdas, kas tika pamanītas koda paraksta verifikācijas procesa laikā

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

- **Success** — norāda, vai koda paraksta verifikācija bija sekmīga

- **UpdateID** — instalētā atjauninājuma unikālais identifikators 

- **UpdateName** — atjauninājuma manifestā norādītais atjauninājuma nosaukums

- **UpdatePkg** — instalētās atjauninājuma pakotnes nosaukums

### <a name="urlutilitiesgetmauinfo"></a>urlutilities.getmauinfo

Šis notikums ziņo par kļūdu, kas notiek, piekļūstot Microsoft Auto Update (MAU) programmas komplektam. Šis notikums ir kritisks un tiek izmantots, lai izpētītu ziņoto kļūdu.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **Payload** — satur informāciju par notikušo kļūdu

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators
   
### <a name="webservicescheckforsilentupdates"></a>webservices.checkforsilentupdates

Šis notikums norāda, ka ir atrasti klusās atjaunināšanas kandidāti. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — ietver atrasto atjauninājumu skaitu un programmas ID.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="webservicesdeltaupdater"></a>webservices.deltaupdater

Šis notikums reģistrē mijiedarbību starp klienta kodu un līdzekļu vārteju, kas kontrolē, vai klientam ir jāatļauj delta atjauninājumi. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — satur atbildi no tīmekļa pakalpojumiem un lietojamā atjauninātāja tipu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="webservicesserviceaction"></a>webservices.serviceaction

Reģistrējam visas kļūdas, kas rodas neparedzētas tīmekļa pakalpojuma atbildes dēļ. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — satur detalizētu informāciju par darbībām, kas tiek stumtas no tīmekļa pakalpojumiem.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="webservicesserviceresponse"></a>webservices.serviceresponse

Šis notikums reģistrē pieprasījumus MAU pakalpojumam, atbilžu laikus un kļūdas. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — satur pieprasījuma ID, programmas nosaukumu, atbildes laiku un/vai statusa kodu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

    
### <a name="webservicessilentupdate"></a>webservices.silentupdate

Reģistrējam pieprasījumus, lai pārbaudītu, vai nav piespiedu atjauninājumu lietošanas kārtulu, t.i., vai lietotājam no būvējuma N nav jāpāriet uz būvējumu N+1, jo pastāv kāda liela problēma. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — satur pieprasījuma ID, programmas nosaukumu, atbildes laiku un/vai statusa kodu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

### <a name="webservicesupdatefiltering"></a>webservices.updatefiltering

Šis notikums norāda uz filtrēšanu, kas veikta tīmekļa pakalpojumos pieejamajam piemērojamo atjauninājumu sarakstam. Šis notikums tiek izmantots, lai nodrošinātu pareizu programmu bloķēšanas darbību, ja ir jābloķē atjauninājums.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **Payload** — satur informāciju par ar tīmekļa pakalpojumu palīdzību bloķēto atjauninājumu skaitu

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

### <a name="webserviceswebcontent"></a>webservices.webcontent

Reģistrējam tīmekļa pakalpojumā saņemtos pieprasījumus un atbildes. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — satur tīmekļa pakalpojuma izsaucēja ID

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators

### <a name="webserviceswhatsnew"></a>webservices.whatsnew

Šis notikums tiek izraisīts, kad Microsoft Auto Update (MAU) “kas jauns” līdzeklī nosūta ar reģistrētajām programmās saistītus vaicājumus tīmekļa pakalpojumiem. Šis notikums tiek izmantots, lai noteiktu līdzekļa “kas jauns” darbspēju. 

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kurā darbojas programma

- **AppVersionLong** — programmas versija

- **Channel** — auditorijas preference

- **Device_NetworkCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **DeviceID** — ierīces identifikators

- **DeviceInfo_Model** — ierīces aparatūras modelis

- **DeviceInfo_NetworkType** — tīkla tips (Wi-Fi, vadu, nezināms)

- **DeviceInfo_OsBuild** — operētājsistēmas versija

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowToCheck** — kā pārbaudīt iestatījumu

- **Payload** — satur informāciju par programmu skaitu ar “kas jauns” informāciju

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators

## <a name="onenote-sync-events"></a>OneNote sinhronizācijas notikumi

### <a name="officeonenotestoragenotebooksyncresult"></a>Office.OneNote.Storage.NotebookSyncResult
 
Šis notikums reģistrē piezīmju grāmatiņas sinhronizācijas rezultātu. Tas tiek lietots, lai, aprēķinot OneNote sinhronizācijas vērtējumu, noteiktu, cik daudz ir unikālu sinhronizācijas mērķu.
 
Tiek apkopoti tālāk norādītie lauki

- **CachedError_Code** A— numurēts vai burtciparu kods, kas tiek lietots, lai noteiktu kešatmiņā saglabātās kļūdas raksturu un/vai to, kāpēc tā radās

- **CachedError_Description** — kešatmiņā saglabātās kļūdas apraksts

- **CachedError_Tag** — norāda, kur kodā rodas kešatmiņā saglabātā kļūda

- **CachedError_Type** — kešatmiņā saglabātās kļūdas tips, piemēram, Win32Error u.tml.

- **ExecutionTime** — laiks milisekundēs, kas bija nepieciešams, lai replicētu piezīmju grāmatiņu

- **Gosid** — globālais objektu telpas ID

- **IdentityType** — identitātes tips, piemēram, Windows Live, organizācijas ID utt.

- **InitialReplicationInSession** — norāda, vai šī replicēšana ir pirmā piezīmju grāmatiņas replicēšana pēc atvēršanas

- **IsBackgroundSync** — norāda, vai tā ir fona sinhronizācija

- **IsCachedErrorSuppressed** — norāda, vai kešatmiņā saglabātā kļūda tiek apspiesta

- **IsCachedErrorUnexpected** — norāda, vai kešatmiņā saglabātā kļūda ir neparedzēta

- **IsNotebookErrorSuppressed** — norāda, vai piezīmju grāmatiņas līmeņa sinhronizācijas kļūda tiek apspiesta

- **IsNotebookErrorUnexpected** — norāda, vai piezīmju grāmatiņas līmeņa sinhronizācijas kļūda ir neparedzēta

- **IsSectionErrorSuppressed** — norāda, vai sadaļu sinhronizācijas kļūdas tiek apspiestas

- **IsSectionErrorUnexpected** — norāda, vai sadaļas sinhronizācijas kļūda bija paredzēta

- **IsUsingRealtimeSync** — norāda, vai piezīmju grāmatiņas sinhronizēšana notiek, izmantojot moderno lapas satura sinhronizāciju

- **LastAttemptedSync** — laikspiedols, kad piezīmju grāmatiņu tika mēģināts sinhronizēt iepriekšējo reizi

- **LastBackgroundSync** — laikspiedols, kad notika pēdējais mēģinājums veikt sinhronizāciju fona režīmā

- **LastNotebookViewedDate** — datums, kad piezīmju grāmatiņa pēdējoreiz tika skatīta

- **LastSuccessfulSync** — laikspiedols, kad piezīmju grāmatiņa iepriekš sekmīgi sinhronizēta

- **NeedToRestartBecauseOfInconsistencies** — norāda, vai sinhronizācija ir jārestartē, jo pastāv nekonsekvences

- **NotebookErrorCode** — piezīmju grāmatiņas līmeņa sinhronizācijas kļūdas kods, kas saglabāts piezīmju grāmatiņas diagrammas apgabalā

- **NotebookId** — piezīmju grāmatiņas ID

- **NotebookType** — piezīmju grāmatiņas tips

- **ReplicatingAgainBecauseOfInconsistencies** — norāda, vai sinhronizācija tiek restartēta nekonsekvenču dēļ

- **SectionError_Code** — numurēts vai burtciparu kods, kas tiek lietots, lai noteiktu sadaļas sinhronizācijas kļūdas raksturu un/vai to, kāpēc tā radās

- **SectionError_Description** — sadaļas sinhronizācijas kļūdas apraksts

- **SectionError_Tag** — norāda, kur kodā rodas sadaļas sinhronizācijas kļūda

- **SectionError_Type** — sadaļas sinhronizācijas kļūdas tips, piemēram, Win32Error u.tml.

- **Success** — norāda, vai piezīmju grāmatiņas sinhronizācija izdevās

- **SyncDestinationType** — sinhronizācijas galamērķa tips, t.i., OneDrive vai SharePoint Online

- **SyncId** — katrai piezīmju grāmatiņas sinhronizācijai unikāls numurs

- **SyncWasFirstInSession** — norāda, vai šī ir pirmo sinhronizācija pašreizējā sesijā

- **SyncWasUserInitiated** — norāda, vai šo sinhronizāciju uzsāka lietotājs

- **TenantId** — SharePoint nomnieka ID

- **TimeSinceLastAttemptedSync** — laiks, kas pagājis kopš pēdējā piezīmju grāmatiņas sinhronizācijas mēģinājuma

- **TimeSinceLastSuccessfulSync** — laiks, kas pagājis kopš pēdējās sekmīgās piezīmju grāmatiņas sinhronizēšanas

### <a name="officeonenotestoragerealtimewebsocketsessioninfo"></a>Office.OneNote.Storage.RealTime.WebSocketSessionInfo
 
Šis notikums reģistrē WebSocket sinhronizācijas rezultātu gan OneNote modernā lapas satura sinhronizācijai, gan modernās hierarhijas sinhronizācijai. Tas tiek lietots, lai, aprēķinot OneNote sinhronizācijas vērtējumu, noteiktu, cik daudz ir unikālu sinhronizācijas mērķu. Tas tiek izmantots arī OneNote modernās sinhronizācijas veiktspējas informācijas paneļa vajadzībām.
 
Tiek apkopoti šādi lauki:
 
- **CloseReason** — WebSocket aizvēršanas iemesls, piemēram, anormāla aizvēršana utt.

- **DataIsFreshCount** — sekmīgo atgādāšanas pieprasījumu skaits WebSocket sesijā

- **DeviceSessionId** — ierīces sesijas ID

- **DownloadCount** — lejupielāžu skaits WebSocket sesijā

- **Error** — tas pamatā ir Exception_Type+Exception_Description+Exception_Code+Exception_Tag

- **Exception_Code** — numurēts vai burtciparu kods, kas tiek lietots, lai noteiktu kļūdas raksturu un/vai to, kāpēc tā radās

- **Exception_Description** — kļūdas apraksts

- **Exception_Tag** — norāda, kur kodā rodas kļūda

- **Exception_Type** — kļūdas tips, piemēram, Win32Error u.tml.

- **FirstUpdateSize** — pirmā atjaunināšanas ziņojuma garums

- **HasError** — norāda, vai WebSocket sesijas laikā radās kļūda 

- **IsEducationNotebook** — norāda, vai pašreizējā piezīmju grāmatiņa ir piezīmju grāmatiņa izglītības iestādēm

- **IsHierarchyResource** — norāda, vai pašreizējais resurss ir lapa vai sadaļa

- **NotebookId** — OneNote piezīmju grāmatiņas ID

- **OperationWithError** — kuras operācijas laikā notika kļūda, piemēram, WebSocket.Close, WebSocket.Open u.tml.

- **ResourceId** — OneNote lapas vai sadaļas resursa ID

- **SectionId** — OneNote sadaļas ID

- **ServerSessionId** — sesijas ID, kas tiek izmantota savstarpējai WebSocket pieprasījuma un onenote.com saistīšanai

- **SessionDurationInMs** — WebSocket sesijas ilgums milisekundēs

- **TenantId** — SharePoint nomnieka ID

- **TimeToFirstUpdateInMs** — laiks milisekundēs, kas bija nepieciešams, lai saņemtu pirmo atjauninājumu no servera puses pēc tam, kad tika izveidota WebSocket sesija

- **UploadAckCount** — augšupielādes apstiprinājumu skaits WebSocket sesijā

- **Web URL** — PII notīrītais tīmekļa vietrādis URL 

### <a name="officeonenotestoragesectionsyncresult"></a>Office.OneNote.Storage.SectionSyncResult
 
Šis notikums reģistrē sadaļas sinhronizācijas rezultātu. Tas tiek lietots, lai, aprēķinot OneNote sinhronizācijas vērtējumu, noteiktu, cik daudz ir unikālu sinhronizācijas mērķu. Tas tiek izmantots arī OneNote modernās sinhronizācijas veiktspējas informācijas paneļa vajadzībām.
 
Tiek apkopoti tālāk norādītie lauki

- **Error_Code** — numurēts vai burtciparu kods, kas tiek lietots, lai noteiktu kļūdas raksturu un/vai to, kāpēc tā radās

- **Error_Description** — kļūdas apraksts

- **Error_Tag** — norāda, kur kodā rodas kļūda

- **Error_Type** — kļūdas tips, piemēram, Win32Error u.tml.

- **ErrorLast** — pēdējās radušās kļūdas kods 

- **ExecutionTime** — laiks milisekundēs, kas bija nepieciešams, lai replicētu sadaļu

- **InitialReplicationInSession** — norāda, vai šī replicēšana ir pirmā piezīmju grāmatiņas replicēšana pēc atvēršanas

- **IsAttachedViaShortcut** — norāda, vai sadaļa tika pievienota, izmantojot saīsni

- **IsBackgroundSync** — norāda, vai tā ir fona sinhronizācija

- **IsEncrypted** — norāda, vai sadaļa ir šifrēta

- **IsErrorSuppressed** — norāda, vai šī kļūda tika apspiesta 

- **IsErrorTransient** — norāda, vai šī kļūda ir pārejoša

- **IsErrorUnexpected** — norāda, vai šī kļūda ir neparedzēta

- **IsUsingRealtimeSync** — norāda, vai sadaļas sinhronizēšana notiek, izmantojot moderno lapas satura sinhronizāciju

- **NotebookId** — piezīmju grāmatiņas ID

- **NotebookPath** — PII notīrītais piezīmju grāmatiņas vietrādis URL

- **SectionPath** — PII notīrītais sadaļas vietrādis URL

- **SectionReplicatingIsOutbound** — norāda, vai šī ir izejošā replicēšana

- **SectionReplicatingIsSameIdentity** — norāda, vai šīs replicēšanas pamatā ir tā paša pašu faila identitāte

- **SectionResourceId** — OneNote sadaļas resursa ID

- **Success** — norāda, vai sadaļas sinhronizācija izdevās

- **SyncDestinationType** — sinhronizācijas galamērķa tips, t.i., OneDrive vai SharePoint Online

- **SyncId** — katrai sadaļas sinhronizācijai unikāls numurs

- **SyncWasFirstInSession** — norāda, vai šī ir pirmo sinhronizācija pašreizējā sesijā

- **SyncWasUserInitiated** — norāda, vai šo sinhronizāciju uzsāka lietotājs

- **TenantId** — SharePoint nomnieka ID

- **UnmappedGosid** — sadaļas ID pirms kartēšanas GUID lietošanas


### <a name="officeonenotestoragesyncscore"></a>Office.OneNote.Storage.SyncScore
 
Šis notikums reģistrē visus lietotājiem redzamos negatīvos sinhronizācijas iespēju apstākļus. Tas tiek lietots, lai aprēķinātu OneNote sinhronizācijas vērtējumu, kas ir kritisks rādītājs, novērtējot OneNote lietotāju sinhronizācijas iespējas.
 
Tiek apkopoti tālāk norādītie lauki

- **AutoShowSyncStatus** — norāda, vai sinhronizācijas statuss tiek rādīts automātiski

- **Cause** — kas izraisīja OneNote lapu/sadaļu pārvietošanu uz nesakārtotām sadaļām

- **Context** — uzskaitījums kategorizē, ko lietotājs cenšas veikt, piemēram, sadaļas pārdēvēšana, piezīmju grāmatiņas atkārtota atvēršana utt.

- **Error_Code** — numurēts vai burtciparu kods, kas tiek lietots, lai noteiktu kļūdas raksturu un/vai to, kāpēc tā radās

- **Error_Description** — kļūdas apraksts

- **Error_Tag** — norāda, kur kodā rodas kļūda

- **Error_Type** — kļūdas tips, piemēram, Win32Error u.tml.

- **ErrorText** — kļūdas teksts, kas redzams lietotāja interfeisā

- **Explanation** — paskaidro, kāda veida ir gaidošas izejošās izmaiņas, kas ir jāpārvieto uz nesakārtotām sadaļām

- **fishbowlType** — akvārija tips, piemēram, lapas akvārijs, sadaļas akvārijs utt.

- **IDS** — lietotāja interfeisā redzamā teksta vesela skaitļa identifikators

- **idsFishbowl** — lietotāja interfeisā redzamās akvārija kļūdas vesela skaitļa identifikators

- **IsUsingRealtimeHierarchySync** — norāda, vai tiek izmantota modernās hierarhijas sinhronizācija

- **NotebookId** — piezīmju grāmatiņas ID

- **PageSyncUIState** — lapas sinhronizācijas statusa virkne, piemēram, UpToDate, Syncing, SaveOffline, SyncError utt. 

- **ServerGosid** — jaunizveidotās konflikta lapas resursa ID

- **Source** — uzskaitījums, kas norāda, kurš notikums izraisīja UI, t.i., izveidoja jaunu redx attēlu, sinhronizācijas kļūda sinhronizācijas lietotāja interfeisā, parādīja kļūdas dialogu utt.

### <a name="onenoteappprovisioningmovelocalnotebooktoonlinenotebookfailed"></a>OneNote.App.Provisioning.MoveLocalNotebookToOnlineNotebookFailed
 
Šis notikums tiek reģistrēts, ja lokālās piezīmju grāmatiņas pārnešana uz disku neizdodas.  Šis scenārijs attiecas uz novēlotas pierakstīšanās lietotāju. Kad lietotājs pierakstās, lokālā piezīmju grāmatiņa tiek pārnesta uz viņu OneDrive krātuvi. 
 
Tiek apkopoti šādi lauki:
 
- **ErrorMsg** — kļūdas ziņojums, kas atbilst kļūmei.

### <a name="onenotestorageconnectivitychanged"></a>OneNote.Storage.ConnectivityChanged

Notikumu žurnāli, ja lietotājam ir vai nav savienojums ar internetu. Tas tiek lietots, lai saistītu citus sinhronizācijas darbspējas standartus, ļaujot mums ignorēt notikumus, kas notiek, kamēr lietotājam nav interneta savienojuma, jo nesagaidām, ka mūsu pakalpojuma latentums būs pieņemams bez interneta savienojuma. Tas ļauj mums aprēķināt precīzu sesiju skaitu mūsu metrikai starp klientu sektoriem (par katru nomnieku, par katru sektoru). Mēs to izmantojam arī, lai filtrētu kļūdu ziņojumus, jo ir daudz sinhronizācijas kļūdu, kuras, iespējams, tiks rādītas bez tīkla savienojama, bet pretējā gadījumā jāveic izmeklēšana.

Ja nesaņemsim šos datus, mēs nevarēsim precīzi pārraudzīt mūsu produktu veiktspēju vai noteikt, vai ir paredzams, ka lietotājam radušās kļūdas, vai arī jums būs jāveic papildu izmeklēšana.

Tiek apkopoti šādi lauki:

- **InternetConnectivityNowAvailable** — ja savienojuma stāvoklis ir mainīts, lai tagad tas būtu internets

### <a name="onenotestoragelegacyinboundlatency"></a>OneNote.Storage.LegacyInboundLatency

Svarīgo signālu izmanto, lai izsekotu ienākošo sinhronizācijas darbību veiktspēju, kuras tieši mijiedarbojas ar SharePoint, ieskaitot sasaistīto informāciju, kas ļauj mums pārraudzīt un izmeklēt datu augšupielādes veiktspēju mūsu pakalpojumā. Šis signāls apkopo tikai sliktākās veiktspējas lejupielādes pēdējās 300 sekundēs (sekunžu skaitu Microsoft var konfigurēt atkarībā no pakalpojuma veiktspējas un nosacījuma).

Tas tiek izmantots, lai nodrošinātu pakalpojumu darbspēju, ļaujot mums redzēt, kuri nomnieki saskaras ar nepieņemami lēnu datu saņemšanu mūsu pakalpojumā, informāciju par datiem, ko tie augšupielādē, kad tieši rodas palēnināta saņemšana, un to, cik izplatīta ir latentuma problēma nomnieku vidū. Tas tiek izmantots, lai ziņotu par pakalpojumu darbspēju un veiktspēju mūsu klientiem, lai novērtētu tendences laika gaitā un brīdinātu par problēmām, kas automātiski attiecas uz inženiertehnisko mazināšanu. Ja mums nav šo datu, tas neļaus mums nodrošināt atbilstošu lejupielādes veiktspēju, kad lietotājs sinhronizēs izmaiņas no SharePoint savā datorā.

Tiek apkopoti šādi lauki: 

- **IsEducationNotebook** — Būls, kas norāda, vai piezīmju grāmatiņa ir piezīmju grāmatiņa izglītības iestādēm

- **NotebookId** — piezīmju grāmatiņas ID, kas ir daļa no šīs augšupielādes

- **TimeToConfirmSyncedWithServerInMs** — laiks milisekundēs, kas bija nepieciešams augšupielādes veikšanai

### <a name="onenotestoragelegacyoutboundlatency"></a>OneNote.Storage.LegacyOutboundLatency

Svarīgo signālu izmanto, lai izsekotu izejošo sinhronizācijas darbību veiktspēju, kuras tieši mijiedarbojas ar SharePoint, ieskaitot sasaistīto informāciju, kas ļauj mums pārraudzīt un izmeklēt datu augšupielādes veiktspēju mūsu pakalpojumā. Šis signāls apkopo tikai sliktākās veiktspējas lejupielādes pēdējās 300 sekundēs (sekunžu skaitu Microsoft var konfigurēt atkarībā no pakalpojuma veiktspējas un nosacījuma).

Tas tiek izmantots, lai nodrošinātu pakalpojumu darbspēju, ļaujot mums redzēt, kuri nomnieki saskaras ar nepieņemami lēnu datu nosūtīšana mūsu pakalpojumā, informāciju par datiem, ko tie augšupielādēja, kad tieši rodas palēnināta nosūtīšana, un to, cik izplatīta ir latentuma problēma nomnieku vidū. Tas tiek izmantots, lai ziņotu par pakalpojumu darbspēju un veiktspēju mūsu klientiem, lai novērtētu tendences laika gaitā un brīdinātu par problēmām, kas automātiski attiecas uz inženiertehnisko mazināšanu. Ja mums nav šo datu, tas neļaus mums nodrošināt atbilstošu veiktspēju, sinhronizējot lietotāju izmaiņas no SharePoint. 

Tiek apkopoti šādi lauki: 

- **IsEducationNotebook** — Būls, kas norāda, vai piezīmju grāmatiņa ir piezīmju grāmatiņa izglītības iestādēm

- **NotebookId** — piezīmju grāmatiņas ID, kas ir daļa no šīs augšupielādes

- **TimeToConfirmSyncedWithServerInMs** — laiks milisekundēs, kas bija nepieciešams augšupielādes veikšanai

### <a name="onenotestoragerealtimefiledataobjectdownload"></a>OneNote.Storage.RealTime.FileDataObjectDownload 

Svarīgo signālu izmanto, lai izsekotu veiktspēju, ja lietotājs saņem faila datu objektu (piemēram, iegultu failu vai attēlu), kas ir lejupielādēts tieši no mūsu pakalpojuma, nevis kā daļa no sinhronizācijas operācijas lapā, sadaļā vai piezīmju grāmatiņā. Šis signāls apkopo tikai sliktākās veiktspējas lejupielādes pēdējās 300 sekundēs (sekunžu skaitu Microsoft var konfigurēt atkarībā no pakalpojuma veiktspējas un nosacījuma).

Tas tiek izmantots, lai nodrošinātu pakalpojumu darbspēju un veiktspēju, ļaujot mums redzēt, kuri nomnieki saskaras ar nepieņemami lēnu lejupielādi no mūsu pakalpojuma, un cik izplatīta ir latentuma problēma nomnieku vidū, un ziņo par mūsu uzvedību laika gaitā, ļaujot mums izmērīt pakalpojumu veiktspējas tendences. Ja ir novērojams nepieļaujams latentums faila objektam, tiks izmantoti arī šie dati, lai savstarpēji saistītu ar citiem signāliem no klienta un pakalpojuma, kas attiecas uz šo objektu, lai uzlabotu mūsu lejupielādes procesu. Mēs arī sadalījām datus, pamatojoties uz lejupielādētā failu objekta paplašinājumu, jo mums ir dažādas gaidas, pamatojoties uz to, vai fails tiek prezentēts mūsu kanvā (piem., attēls), vai arī tas ir fails, kas nav ievietots (piemēram, teksta dokuments). Ja nesaņemsim šos datus, mēs nevarēsim pārraudzīt šo lejupielāžu veiktspēju.

Tiek apkopoti šādi lauki: 

- **FileSizeInBytes** — lejupielādētā faila lielums baitos 

- **IsImage** — Būla noteikšana, ja lejupielādējamajam failam ir paplašinājums, kas atbilst iepriekš noteiktam bieži lietotā attēla formātu (.bmp, .emf, .gif, .jpe, .jpeg, .jpg, .png) sarakstam, kas tiek rādīts iekļautajā kanvā

- **TimeToDownload** — laiks, kas bija nepieciešams, lai veiksmīgi lejupielādētu FDO no mūsu BLOB krātuves ierīcē 

### <a name="onenotestoragerealtimewebsocketdownload"></a>OneNote.Storage.RealTime.WebSocketDownload

Svarīgo signālu izmanto, lai izsekotu ienākošo sinhronizācijas darbību veiktspēju, ieskaitot sasaistīto informāciju, kas ļauj mums pārraudzīt un izmeklēt datu lejupielādes no mūsu pakalpojuma (onenote.com) veiktspēju. Šis signāls apkopo tikai sliktākās veiktspējas lejupielādes pēdējās 300 sekundēs (sekunžu skaitu Microsoft var konfigurēt atkarībā no pakalpojuma veiktspējas un nosacījuma).

Tas tiek izmantots, lai nodrošinātu pakalpojumu darbspēju, ļaujot mums redzēt, kuri nomnieki saskaras ar nepieņemami lēnu datu saņemšanu no mūsu pakalpojuma, informāciju par datiem, ko tie lejupielādēja, kad tieši rodas palēnināta saņemšana, un to, cik izplatīta ir latentuma problēma nomnieku vidū. Tas tiek izmantots, lai ziņotu par pakalpojumu darbspēju un veiktspēju mūsu klientiem, lai novērtētu tendences laika gaitā un brīdinātu par problēmām, kas automātiski attiecas uz inženiertehnisko mazināšanu. 

Ja sadaļai vai piezīmju grāmatiņai tiek novērots nepieņemams latentums, mēs izmantosim arī šos datus, lai saistītu ar citiem signāliem no klienta un pakalpojuma, kas attiecas uz to pašu dokumentu, lai identificētu klienta puses veiktspējas regresijas, kas ļauj mums nodrošināt labākas veiktspējas pakalpojumus.

Ja nesaņemsim šos datus, mēs nevarēsim pārraudzīt šī mūsu pakalpojuma darbības rezultātu vai servera puses izmaiņu ietekmi, kas, iespējams, ir nepieciešama lietošanas vai citu faktoru dēļ.

Tiek apkopoti šādi lauki:

- **DeviceSessionId** — ierīces sesijas ID

- **IsEducationNotebook** — Būls, kas norāda, vai piezīmju grāmatiņa ir piezīmju grāmatiņa izglītības iestādēm

- **IsHierarchyResource** — Būls, kas norāda, vai resurss ir hierarhijas resurss

- **NotebookId** — piezīmju grāmatiņas ID, kas ir daļa no šīs augšupielādes

- **ResourceId** — resursa ID, kuru augšupielādējam

- **SectionId** — sadaļas ID, kas ir daļa no šīs augšupielādes

- **ServerSessionId** — servera ID, kas ir daļa no šīs augšupielādes

- **TimeToConfirmSyncedWithServerInMs** — laiks milisekundēs starp lietotāju, kurš pārvietojas uz lapu, un replicēšanas steku, kas apstiprina, ka šī lapa ir sinhronizēta ar serveri.

- **TimeToFirstUpdateInMs** — laiks milisekundēs starp sinhronizācijas programmu, kas sākas ar lapas ienākošo replicēšanu, un replicēšanas darbību, kura sasniegusi sinhronizāciju ar servera stāvokli.

### <a name="onenotestoragerealtimewebsocketupload"></a>OneNote.Storage.RealTime.WebSocketUpload

Svarīgo signālu izmanto, lai izsekotu izejošo sinhronizācijas darbību veiktspēju, ieskaitot sasaistīto informāciju, kas ļauj mums pārraudzīt un izmeklēt datu augšupielādes mūsu pakalpojumā (onenote.com) veiktspēju.

Tas tiek izmantots, lai nodrošinātu pakalpojumu darbspēju, ļaujot mums redzēt, kuri nomnieki saskaras ar nepieņemami lēnu datu nosūtīšana mūsu pakalpojumā, informāciju par datiem, ko tie augšupielādēja, kad tieši rodas palēnināta nosūtīšana, un to, cik izplatīta ir latentuma problēma nomnieku vidū. Tas tiek izmantots, lai ziņotu par pakalpojumu darbspēju un veiktspēju mūsu klientiem, lai novērtētu tendences laika gaitā un brīdinātu par problēmām, kas automātiski attiecas uz inženiertehnisko mazināšanu. Mēs arī izmantosim šos datus, lai izsekotu mūsu klientu un pakalpojumu uzlabojumu ietekmi un efektivitāti. 

Ja sadaļai vai piezīmju grāmatiņai tiek novērots nepieņemams latentums, mēs izmantosim arī šos datus, lai saistītu ar citiem signāliem no klienta un pakalpojuma, kas attiecas uz to pašu dokumentu, lai identificētu veiktspējas regresijas, kas ļauj mums nodrošināt labākas veiktspējas pieredzi.

Ja nesaņemsim šos datus, mēs nevarēsim pārraudzīt šī mūsu pakalpojuma darbības rezultātu vai servera puses izmaiņu ietekmi, kas, iespējams, ir nepieciešama lietošanas vai citu faktoru dēļ.

Tiek apkopoti šādi lauki: 

- **DeviceSessionId** — ierīces sesijas ID

- **IsEducationNotebook** — Būls, kas norāda, vai piezīmju grāmatiņa ir piezīmju grāmatiņa izglītības iestādēm

- **IsHierarchyResource** — Būls, kas norāda, vai resurss ir hierarhijas resurss

- **IsWorstTime** — Būls, kas norāda, vai laiks ir regulārs augšupielādes notikums, vai vissliktākais laiks, ko novērojām šim klientam pēdējās 300 sekundēs (sekunžu skaitu var konfigurēt Microsoft atkarībā no pakalpojuma veiktspējas un nosacījuma).

- **NotebookId** — piezīmju grāmatiņas ID, kas ir daļa no šīs augšupielādes

- **RecommendedPutIntervalInMs** — laiks, kad pakalpojums ir pateicis klientam par ieteicamo iestatīto intervālu

- **ResourceId** — resursa ID, kuru augšupielādējam

- **SectionId** — sadaļas ID, kas ir daļa no šīs augšupielādes

- **SenderRequestId** — sūtītāja ID, kas veic augšupielādi

- **ServerSessionId** — servera ID, kas ir daļa no šīs augšupielādes

- **UploadNonSuspendedTimeInMs** — laiks milisekundēs, kas bija nepieciešams augšupielādes veikšanai, izņemot laiku, kad lietojumprogramma tika apturēta

- **UploadTimeInMs** — laiks milisekundēs, kas bija nepieciešams augšupielādes reālai veikšanai

- **WaitTimeInMs** — laiks milisekundēs starp augšupielādes pieprasīšanu un augšupielādes sākšanu

- **WebURL** — augšupielādes tīkls URL (Pieteicies kā PiiWz)

### <a name="onenotestoragesynchealth"></a>OneNote.Storage.SyncHealth

Svarīgo signālu izmanto, lai izsekotu kļūdas un izņēmumus, kas ir radušies sinhronizācijas stekā OneNote klientā, kas ļauj mums pārraudzīt un mazināt šādus neparedzētus nosacījumus.

Tas tiek lietots, lai nodrošinātu pakalpojuma darbspēju, ļaujot mums skatīt klientu kļūdu ziņojumus reāllaikā, un ļauj mums reaģēt uz sinhronizācijas problēmām tiklīdz tās rodas. To izmanto arī, lai noteiktu, cik izplatīta ir problēma, un cik nopietna ir, savstarpēji norādot kļūdas atzīmi ar klienta kodu, lai identificētu kļūmes avotu. Mēs apkopojām arī šos datus, lai iegūtu informāciju par mūsu veiktspēju laika gaitā un to uzlabojumu ietekmi un efektivitāti, ko veicam saviem klientiem un pakalpojumiem. Ja mums nav šo datu, mēs nevarēsim proaktīvi reaģēt uz kļūdu nosacījumiem mūsu sinhronizācijas pakalpojumā, bez klienta eskalācijas.

Tiek apkopoti šādi lauki: 

- **Service** — sinhronizācijas pakalpojums, ko klients izmantoja, kad radās kļūda (mantotā vai modernā sinhronizācija)

- **Tag** — atzīme (identifikācijas vērtība), kura norāda kļūdu, kas radās sinhronizācijas darbības laikā klientam

### <a name="onenotesynccreatenotebookfailed"></a>OneNote.Sync.CreateNotebookFailed
 
Šis notikums tiek reģistrēts, ja neizdodas izveidot piezīmju grāmatiņu.  
 
Tiek apkopoti tālāk norādītie lauki:
 
- **NetworkConnection** — reģistrē savienojuma tipu, kurā ierīce pašlaik ir ieslēgta, piemēram, Wi-Fi, bezsaistē, 3G 

- **ServerType** — reģistrē servera tipu, kur tiks izveidota piezīmju grāmatiņa.

### <a name="onenotesyncfirstrunerror"></a>OneNote.Sync.FirstRunError
 
Šis notikums tiek reģistrēts, ja lietotājam, veicot pirmās palaišanas darbības ierīcē, neizdevās sinhronizēt ātrās piezīmes.  Šis ir raksturīgs pirmās palaišanas scenārijam.
 
Tiek apkopoti tālāk norādītie lauki.
 
- **NetworkConnection** — reģistrē savienojuma tipu, kurā ierīce pašlaik ir ieslēgta, piemēram, Wi-Fi, bezsaistē, 3G

- **ServerType** — reģistrē servera tipu, kur tiks izveidota ātro piezīmju grāmatiņa.

## <a name="services-configuration-events"></a>Pakalpojumu konfigurācijas notikumi

Pakalpojumu konfigurācija neapkopo nepieciešamos pakalpojumu datu notikumus.

## <a name="telemetry-events"></a>Telemetrijas notikumi

### <a name="officeandroiddocsuipaywallcontrolpaywalloperationmetrics"></a>Office.Android.DocsUI.PaywallControl.PaywallOperationMetrics

*[Šī notikuma iepriekšējais nosaukums bija Office.Android.DocsUI.Views.PaywallOperationMetrics.]*

Microsoft izmanto šo opciju, lai uzlabotu lietotāja funkciju, panākumu vai kļūdu īpatsvaru pirkumos, lai nodrošinātu atbilstošus ieguldījumus, lai uzlabotu klientu pirkumu pieredzi mobilajās platformās.

Tiek apkopoti šādi lauki.

- **OperationTimeInMs** — laiks, kas nepieciešams pirkuma operācijas pabeigšanai (ilgs - milisekundes)

- **PaywallOperationResult** — veiksmes/ kļūdas kods/ lietotājs atcelts (uzskaitījums/ Int — ierobežots)

- **PaywallOperationType** — Paywall operācijas veids (uzskaitījums/Int — ierobežotie)

### <a name="officeandroiddocsuipaywallcontrolpaywallsessiondata"></a>Office.Android.DocsUI.PaywallControl.PaywallSessionData

*[Šī notikuma iepriekšējais nosaukums bija Office.Android.DocsUI.Views.PaywallSessionData.]*

Sesijas metadati, kad lietotājam tiek parādīts Paywall lietotāja interfeiss. Microsoft izmanto šo opciju, lai iegūtu lietotāja pieredzi un saprastu ierīces un operētājsistēmas versijas, ko lietotājs izmanto, lai palīdzētu pieņemt lēmumus par investīcijām, lai uzlabotu pieredzi šajos apgabalos.

Tiek apkopoti tālāk norādītie lauki.

- **App Version** — patērējošās lietojumprogrammas versijas kods

- **ClientId** — anonīms identifikators, kas nav PII unikāls ierīces identifikators (GUID/virkne)

- **Entry Point** — unikāls kontekstuālo vai nemainīgo ievadīšanas punktu identifikators no patērējošās lietojumprogrammas

- **isTablet** — vai ierīcē tiek rādīts planšetdators UX

- **OSVersion** — ierīces Android OS versija

- **SessionId** — GUID: unikāls Paywall sesijas identifikators


### <a name="officefirstrunappletelemetryoptin"></a>Office.FirstRun.Apple.TelemetryOptIn

Šo notikumu apkopo Office programmām, kas darbojas Apple platformās. Šo notikumu lieto, lai pārraudzītu mūsu telemetrijas piedalīšanās plūsmas darbspēju pirmās palaišanas programmā. Mēs vācam koda datus, kas norāda, kāda veida diagnostikas datu vākšanas opciju lietotājs ir atlasījis.

Tiek apkopoti šādi lauki:

- **Data_EventId** – kods, kas norāda lietotāja atlasītu diagnostikas datu vākšanas preferenci.

### <a name="officeiospaywallprovisioningresponse"></a>Office.iOS.Paywall.Provisioning.Response

Produktu telemetriju, kas tiek izmantoti, lai saistītu pirkumu darbību informāciju ar Microsoft tirdzniecības sistēmu un iespējotu saistīto abonementu priekšrocības. Izmanto, lai atvieglotu darījumu reģistrēšanu un abonēšanas nodrošināšanu turpmākai uzziņai un iekšējai saskaņošanai.

Tiek apkopoti šādi lauki.

- **entryPoint** — virkne — poga/plūsma, no kuras tika parādīts Paywall. Piemēram, “Premium jaunināšanas poga” vai “Pirmās palaišanas plūsma”.

- **failureReason** — virkne — tiek pievienota tikai tad, ja statuss ir "kļūme". Norāda kļūdas reakciju, ko sniedz RFS nodrošināšanas atbilde.

- **productId** — virkne — lietojumprogrammas veikala pieprasītā produkta ID

- **status** — virkne — veiksme vai kļūme, norādot, vai pieprasījums ir izdevies vai nav izdevies


### <a name="officeiospaywallstorekitresponse"></a>Office.iOS.Paywall.StoreKit.Response

Dati tiek apkopoti kā kritiski tehniskās telemetrijas dati, lai reģistrētu pirkšanas mēģinājuma rezultātus, ko lietotājs aktivizējis manuāli. Produktu telemetrija tiek izmantota, lai saistītu pirkumu darbību informāciju ar Microsoft tirdzniecības sistēmu un iespējotu saistīto abonementu priekšrocības.

Tiek apkopoti šādi lauki.

- **entryPoint** — virkne — poga/plūsma, no kuras tika parādīts Paywall. Piemēram, “Premium jaunināšanas poga” vai “Pirmās palaišanas plūsma”.

- **failureReason** — virkne — tiek pievienota tikai tad, ja statuss ir "kļūme". Norāda kļūdas reakciju, ko sniedz lietojumprogrammu veikala atbilde.

- **productId** — virkne — tikai "MakePurchase", "PendingPurchase", tā produkta ID lietojumprogrammu veikalā, par kuru tiek iesniegts pieprasījums.

- **productsCount** — Int — tikai "ProductsFetch" — veikalā atgriezto produktu skaits.

- **requestType** — virkne — StoreKit pieprasījuma tips. Piemēram, "ProductsFetch", "PendingPurchase"

- **status** — virkne — sekmīga izpilde vai kļūme, norādot pieprasījuma veiksmīgumu vai kļūmi

### <a name="officeonenotegetsharepointidsfordocument"></a>Office.OneNote.GetSharePointIdsForDocument

Apkopotie dati reģistrē SharePoint (SPO) ID sekmīgu vai nesekmīgu iegūšanu dokumenta vietrādim URL. Izsaukuma sekmīga vai nesekmīga izpilde (tai skaitā nesekmīgas izpildes iemesls) tiek reģistrēta visām platformām. Šis marķieris ir nepieciešams, lai sekotu un diagnosticētu ID saņemšanai veiktā izsaukuma darbspēju. ID ir nepieciešami, lai OneNote lapas (daļa no SharePoint saglabātajām piezīmju grāmatām) dati tiktu rādīti plūsmā.   

Tiek apkopoti šādi lauki:

- **ErrorCode** — kļūdas int vērtība

- **ErrorMessage** — kļūdu aprakstošā virkne

- **FailureType** — kļūdas tipa noteikšanai paredzētā virkne

- **HttpStatusCode** — tīkla izsaukuma HTTP kļūdas kods

- **InnerErrorCode** — int kods

- **InnerErrorMesage** — kļūdas ziņojums

- **IsSuccess** — Būla vērtība, ja signāls ir sekmīgs

### <a name="officeonenotegetsharepointidsfordocumentw32old"></a>Office.OneNote.GetSharePointIdsForDocumentW32Old

Šī telemetrija reģistrē SharePoint (SPO) ID dokumentu vietrādim URL iegūšanas sekmīgos un nesekmīgos scenārijus. Tiek reģistrēta izsaukuma sekmīga vai nesekmīga izpilde (tai skaitā nesekmīgas izpildes iemesls). Šis tiek reģistrēts tikai vecajā win32 platformā. Šis marķieris ir nepieciešams, lai sekotu un diagnosticētu ID saņemšanai veiktā izsaukuma darbspēju. ID ir nepieciešami, lai OneNote lapas (daļa no SharePoint saglabātajām piezīmju grāmatām) dati tiktu rādīti plūsmā.   

Tiek apkopoti šādi lauki:

- **ErrorCode** — kļūdas int vērtība

- **ErrorMessage** — kļūdu aprakstošā virkne

- **FailureType** — kļūdas tipa noteikšanai paredzētā virkne

- **HttpStatusCode** — tīkla izsaukuma HTTP kļūdas kods

- **InnerErrorCode** — int kods

- **InnerErrorMesage** — kļūdas ziņojums

- **IsSuccess** — Būla vērtība, ja signāls ir sekmīgs


### <a name="officesystemgracefulexitgracefulappexitdesktop"></a>Office.System.GracefulExit.GracefulAppExitDesktop

Notikumu izraisa atbilstoša Office klienta programmu izbeigšana, piemēram, Word, Excel, PowerPoint, Outlook un citas programmas. Mēs izmantojam rādītāju Atbilstoša izbeigšana, lai novērtētu Office klienta produktu darbspēju. Tas ir paredzēts kā uzņēmējdarbībai svarīgs signāls, kuru izmanto Office inženieri, lai noteiktu produktu stabilitāti.

Tiek apkopoti šādi lauki:

- **AppBuild** — būvējuma versijas identifikators ietekmētajam procesam.
- **AppMajor** — galvenās versijas identifikators ietekmētajam procesam.
- **AppMinor** — papildversijas identifikators ietekmētajam procesam.
- **AppRevision** —būvējuma versijas identifikators ietekmētajam procesam.
- **BootCompleted** — norāda, vai Office process pabeidza sāknēšanu.
- **DetectionTime** — laiks, kad tika konstatēta neparedzētā izeja.
- **EcsETag** — procesa eksperimenta identifikators.
- **HasEdit** — norāda, vai dokumenta rediģēšana notika Office procesa laikā.
- **HasOpen** — norāda, vai dokuments tika atvērts Office procesa laikā.
- **InstallMethod** — vai pašreizējais Office būvējums tika jaunināts, atritināts vai svaigi instalēts.
- **OfficeUILang** — Office procesa valoda.
- **PreviousBuild** — iepriekš instalētā būvējuma versija.
- **SafeMode** — norāda, vai Office process bija drošajā režīmā.
- **SessionId** — procesa unikālais identifikators.
- **SessionInitTime** — ietekmētā procesa sākuma laiks.

### <a name="officesystemidentitychanged"></a>Office.System.IdentityChanged

Lietotāja identitātes informācija, kas nepieciešama, lai izpildītu datu subjektu pieprasījumus.

Tiek apkopoti tālāk norādītie lauki.

  - **IdentityChanged** — vienmēr patiess. Identitāte ir mainīta.

  - **TimerDetectedChange** — vai izmaiņas konstatēja regulāra laika programma Ping.

### <a name="officesystemprivacyfallbacktosettingsstore"></a>Office.System.PrivacyFallbackToSettingsStore

Tiek izmantots, lai noteiktu, vai radušās kļūmes, lasot lietotāja konfidencialitātes iestatījumus Viesabonēšanas krātuvē.

Tiek apkopoti tālāk norādītie lauki.

  - **Tags —** koda atzīme, kas norāda, kurš iestatījums ir atgriezies atpakaļ iestatījumu krātuvē.

### <a name="officesystemsessiondatao365"></a>Office.System.SessionDataO365

Metadati, kas nepieciešami, lai izolētu kļūmes atkārtošanu.

Tiek apkopoti tālāk norādītie lauki.

  - **AppId —** identifikators, uz kādu Office lietojumprogrammu šie dati attiecas.

  - **ApplicationArchitecture —** kādai procesora arhitektūrai sistēma Office ir paredzēta.

  - **AppVersionBuild —** Office lietojumprogrammas būvējuma versija.

  - **AppVersionMajor —** Office lietojumprogrammas galvenā versija.

  - **AppVersionMinor —** Office lietojumprogrammas papildversija.

  - **AppVersionUpdate —** Office lietojumprogrammas būvējuma pārskatījums.

  - **CollectorVersion —** klienta apkopošanas loģikas versijas identifikators.

  - **DeviceHash —** operētājsistēmas ierīces identifikatora vienvirziena jaukšanas vērtība.

  - **DeviceName —** ierīces, kurā Office darbojas, nosaukums.

  - **Domain —** ierīces, kurā Office darbojas, domēns.

  - **IsCeip —** vai Office instalācija tika reģistrēta novecojušā klientu pieredzes uzlabošanas programmā.

  - **IsDebug —** vai šis ir Office atkļūdošanas būvējums.

  - **IsImmersive —** vai Office lietojumprogramma ir universāla Windows vai tīrskata lietojumprogramma.

  - **IsLaptop —** vai ierīce, kurā Office darbojas, ir klēpjdators.

  - **IsMicrosoftInternal —** vai Windows lietotājs, kurš izmanto Office, ir Microsoft darbinieks.

  - **IsO365 —** vai Office instalēšana ir daļa no novecojušas Outlook 365 programmas.

  - **IsTablet —** vai ierīce, kurā Office darbojas, ir planšetdators.

  - **IsTerminalServer —** aplams/patiess ir termināļa servera klients

  - **MaxMemory —** maksimālais brīvpiekļuves atmiņas apjoms, kas ir pieejams ierīcei, kurā darbojas Office.

  - **OsArchitecture —** centrālā procesora arhitektūra, kam operētājsistēma, kurā darbojas Office, ir paredzēta,

  - **OsVersionBuild —** operētājsistēmas būvējuma versija.

  - **OsVersionMajor —** operētājsistēmas galvenā versija.

  - **OsVersionMinor —** operētājsistēmas papildversija.

  - **OsVersionUpdate —** OS būvējuma pārskatījums

  - **ProcessFileName —** darbojošās lietojumprogrammas izpildāmais nosaukums.

  - **ProcessorArchitecture —** kādā procesora arhitektūrā Office darbojas.

  - **ProcessorFrequency —** procesora ātrums megahercos ierīcēs, kur Office darbojas.

  - **SessionStart —** laiks, kad aktīvais Office process tika startēts.

  - **UserName —** konta, kas izmanto Office, nosaukums.

### <a name="officesystemsystemhealthcoremetadata"></a>Office.System.SystemHealthCoreMetadata

Metadati, kas nepieciešami, lai izolētu kļūmes atkārtošanu.

Tiek apkopoti tālāk norādītie lauki.

  - **AppBuild —** Office lietojumprogrammas būvējuma versija.

  - **AppBuildRevision —** Office lietojumprogrammas būvējuma pārskatījums.

  - **AppMajorVer —** Office lietojumprogrammas galvenā versija.

  - **AppMinorVer —** Office lietojumprogrammas papildversija.

  - **CID —** pseidonimizēta lietotāja identitāte

  - **CollectibleClassifications —** datu klasifikāciju kopa, ko var apkopot.

  - **CollectionTime —** laiks, kad metadati tika apkopoti.

  - **DeviceManufacturer —** ierīces, kurā Office darbojas, ražotājs.

  - **DeviceModel —** ierīces, kurā Office darbojas, modelis.

  - **FirstRunTime —** pirmā reize, kad Office lietojumprogramma tika palaista.

  - **IsClickToRunInstall —** vai Office lietojumprogramma tika instalēta, izmantojot Click -To-Run

  - **IsDebug —** vai šis ir Office atkļūdošanas būvējums.

  - **IsLabMachine —** vai sistēma Office tiek izmantota Microsoft laboratorijā.

  - **IsLaptop —** vai ierīce, kurā Office darbojas, ir klēpjdators.

  - **IsMsftInternal —** vai Windows lietotājs, kurš izmanto Office, ir Microsoft darbinieks.

  - **IsSubscription —** vai Office lietojumprogramma ir instalēta atbilstoši abonementa licencei.

  - **IsTablet —** vai ierīce, kurā Office darbojas, ir planšetdators.

  - **IsTerminalServer —** vai sistēma Office tiek izmantota termināļa serverī.

  - **MsoAppId —** identifikators, uz kādu Office lietojumprogrammu šie dati attiecas.

  - **OfficeArchitectureText —** kādai procesora arhitektūrai sistēma Office ir paredzēta.

  - **OsBuild —** operētājsistēmas būvējuma versija.

  - **OsBuildRevision —** OS būvējuma pārskatījums

  - **OSEnvironment —** identifikators, kādā vidē Office darbojas.

  - **OsMajorVer —** operētājsistēmas galvenā versija.

  - **OsMinorVer —** operētājsistēmas papildversija.

  - **OSVersionString —** operētājsistēmas versija kā virkne.

  - **ProcessorArchitecture —** kādā procesora arhitektūrā Office darbojas.

  - **ProcessorCount —** procesoru skaits ierīcē, kurā Office darbojas.

  - **ProcSpeedMHz —** procesora ātrums megahercos ierīcēs, kur Office darbojas.

  - **RamMB —** RAM apjoms, kas pieejams ierīcē, kur Office darbojas.

  - **SqmUserId —** Office instalēšanas nejaušs identifikators.

### <a name="officesystemsystemhealthdesktopsessionlifecycleandheartbeat"></a>Office.System.SystemHealthDesktopSessionLifecycleAndHeartbeat

Nodrošina informāciju par sistēmas darbspējas datiem.

Tiek apkopoti tālāk norādītie lauki.

  - **InstallMethod** — vai pašreizējais Office būvējums tika jaunināts, atritināts vai svaigi instalēts.

  - **OfficeArchitectureText** — Office produkta arhitektūra kā virkne (piem., x86, arm).

  - **PreviousBuild** — Office versija, uz kuru šis būvējums tika jaunināts vai no kura tas tika atritināts.

  - **State** — stāvoklis, uz kuru sesija veica maiņu.

  - **Time** — sesijas stāvokļa maiņas laiks.

### <a name="officesystemsystemhealthessentialidentitycount"></a>Office.System.SystemHealthEssentialIdentityCount

Apkopo parakstīto lietotāja identitāšu skaitu

Tiek apkopoti tālāk norādītie lauki.

  - **AllIdentityCount** — visu identitāšu skaits

  - **ValidIdentityCount** — pārbaudīto identitāšu skaits

### <a name="officesystemsystemhealthessentialmetadataallidentities"></a>Office.System.SystemHealthEssentialMetadataAllIdentities

Pārrauga to kontu stāvokli, ko sistēma Office atpazina šajā sesijā. Tiek izmantots, lai izolētu kļūmi konta pieteikšanās veidā, ja kļūme ir specifiska veidam.

Tiek apkopoti tālāk norādītie lauki.

  - **CollectionTime** — laiks, kad identitātes informācija tika apkopota.

  - **IdentityType** — autentifikācijas vai konta veids

  - **IdentityUniqueId** — pseidonimizētās identitātes nodrošinātājs

  - **IdentityUniqueIdHashed** — identitātes unikālā ID vienvirziena jaukšanas vērtība

### <a name="officesystemsystemhealthmetadataapplicationadditional"></a>Office.System.SystemHealthMetadataApplicationAdditional

Metadati, kas nepieciešami, lai izolētu kļūmes atkārtošanu.

Tiek apkopoti tālāk norādītie lauki.

  - **Alias —** ja lietotājs, kurš izmanto Office, ir Microsoft darbinieks, viņa uzņēmuma iekšējais aizstājvārds.

  - **AppBuild —** Office lietojumprogrammas būvējuma versija.

  - **AppBuildRevision —** Office lietojumprogrammas būvējuma pārskatījums.

  - **AppMajorVer —** Office lietojumprogrammas galvenā versija.

  - **AppMinorVer —** Office lietojumprogrammas papildversija.

  - **CID —** pseidonimizēta lietotāja identitāte

  - **CollectibleClassifications —** datu klasifikāciju kopa, ko var apkopot.

  - **DeviceManufacturer —** ierīces, kurā Office darbojas, ražotājs.

  - **DeviceModel —** ierīces, kurā Office darbojas, modelis.

  - **DeviceProcessorModel —** ierīces, kurā Office darbojas, procesora modelis.

  - **DigitizerInfo —** informācija par ciparotāju, kas pievienots ierīcei, kurā Office darbojas.

  - **DomainName —** domēna, ar kuru ir savienots dators, kurā darbojas Office (ja tāds ir), nosaukums.

  - **FirstRunTime —** pirmā reize, kad Office lietojumprogramma tika palaista.

  - **HorizontalResolution —** horizontālā ekrāna izšķirtspēja

  - **IsDebug —** vai šis ir Office atkļūdošanas būvējums.

  - **IsImmersive —** vai Office lietojumprogramma ir universāla Windows vai tīrskata lietojumprogramma.

  - **IsJoinedToDomain —** vai ierīce, kurā darbojas Office, ir pievienota domēnam.

  - **IsLabMachine —** vai sistēma Office tiek izmantota Microsoft laboratorijā.

  - **IsLaptop —** vai ierīce, kurā Office darbojas, ir klēpjdators.

  - **IsMsftInternal —** vai Windows lietotājs, kurš izmanto Office, ir Microsoft darbinieks.

  - **IsOEMInstalled —** vai palaisto Office lietojumprogrammu instalēja OEM.

  - **IsRunAsAdmin —** vai Office lietojumprogramma darbojas kā administratora.

  - **IsSubscription —** vai Office lietojumprogramma ir instalēta atbilstoši abonementa licencei.

  - **MsoAppId —** identifikators, uz kādu Office lietojumprogrammu šie dati attiecas.

  - **NumProcPhysCores —** fizisko kodolu skaits procesorā.

  - **OfficeBuild —** Office koplietojamo bibliotēku būvējuma versija.

  - **OfficeBuildRevision —** Office koplietojamo bibliotēku būvējuma pārskatījuma versija.

  - **OfficeMajorVer —** Office koplietojamo bibliotēku galvenā versija.

  - **OfficeMinorVer —** Office koplietojamo bibliotēku papildversija.

  - **OsBuild —** operētājsistēmas būvējuma versija.

  - **OsBuildRevision —** OS būvējuma pārskatījums

  - **OsMajorVer —** operētājsistēmas galvenā versija.

  - **OsMinorVer —** operētājsistēmas papildversija.

  - **PowerPlatformRole —** ierīces, kurā Office darbojas, OEM vēlamās datora lomas identifikators.

  - **ProcessFileName —** darbojošās lietojumprogrammas izpildāmais nosaukums.

  - **ProcessorCount —** procesoru skaits ierīcē, kurā Office darbojas.

  - **RamMB —** RAM apjoms, kas pieejams ierīcē, kur Office darbojas.

  - **SqmUserId —** Office instalēšanas nejaušs identifikators.

  - **StudyId —** programmatūras kvalitātes metrikas pētījuma identifikators.

  - **VerticalResolution —** vertikālā ekrāna izšķirtspēja

  - **WinUserActType —** vai Windows lietotājs, kas izmanto Office, ir lokālais administrators, prasmīgs lietotājs vai parasts lietotājs.

### <a name="officesystemsystemhealthmetadataapplicationandlanguage"></a>Office.System.SystemHealthMetadataApplicationAndLanguage

Metadati ir nepieciešami, lai izolētu kļūmes atkārtošanu.

Tiek apkopoti tālāk norādītie lauki.

  - **AppBuild —** Office lietojumprogrammas būvējuma versija.

  - **AppBuildRevision —** Office lietojumprogrammas būvējuma pārskatījums.

  - **AppMajorVer —** Office lietojumprogrammas galvenā versija.

  - **AppMinorVer —** Office lietojumprogrammas papildversija.

  - **AppState —** Office lietojumprogrammas stāvokļa identifikators.

  - **Click2RunPackageVersionBuild —** Click-to-Run instalētāja pakotnes būvējuma versija.

  - **Click2RunPackageVersionMajor —** Click-to-Run instalētāja pakotnes galvenā versija.

  - **Click2RunPackageVersionMinor —** Click-to-Run instalētāja pakotnes papildversija.

  - **Click2RunPackageVersionRevision —** Click-to-Run instalētāja pakotnes būvējuma pārskatījums.

  - **DistributionChannel —** Office izplatīšanas kanāls.

  - **InstallType —** Office instalēšanas metodes identifikators.

  - **IsClickToRunInstall —** vai Office lietojumprogramma tika instalēta, izmantojot Click-to-Run

  - **IsDebug —** vai šis ir Office atkļūdošanas būvējums.

  - **IsImmersive —** vai Office lietojumprogramma ir universāla Windows vai tīrskata lietojumprogramma.

  - **IsMsftInternal —** vai Windows lietotājs, kurš izmanto Office, ir Microsoft darbinieks.

  - **IsOEMInstalled —** vai palaisto Office lietojumprogrammu instalēja OEM.

  - **IsRunAsAdmin —** vai Office lietojumprogramma darbojas kā administratora.

  - **IsSubscription —** vai Office lietojumprogramma ir instalēta atbilstoši abonementa licencei.

  - **MsoAppId —** identifikators, uz kādu Office lietojumprogrammu šie dati attiecas.

  - **OfficeArchitectureText —** kādai procesora arhitektūrai sistēma Office ir paredzēta.

  - **OfficeBuild —** Office koplietojamo bibliotēku būvējuma versija.

  - **OfficeBuildRevision —** Office koplietojamo bibliotēku būvējuma pārskatījuma versija.

  - **OfficeMajorVer —** Office koplietojamo bibliotēku galvenā versija.

  - **OfficeMinorVer —** Office koplietojamo bibliotēku papildversija.

  - **OfficeMuiCount —** instalēto Office valodu pakotņu skaits.

  - **OfficeSkuLanguage —** instalētā SKU valoda.

  - **OfficeSkuLanguageTag —** instalētā SKU valoda.

  - **OfficeUiLang —** Office lietojumprogrammas lietotāja interfeisa valoda.

  - **OfficeUiLangTag —** Office lietojumprogrammas lietotāja interfeisa valoda.

  - **ProcessFileName —** darbojošās lietojumprogrammas izpildāmais nosaukums.

  - **SqmAppId —** identifikators, uz kādu Office lietojumprogrammu šie dati attiecas.

### <a name="officesystemsystemhealthmetadatadelayedlogin"></a>Office.System.SystemHealthMetadataDelayedLogin

Lietotāja identitātes informācija, kas nepieciešama, lai izpildītu datu subjektu pieprasījumus.

Tiek apkopoti tālāk norādītie lauki.

  - **CID** — pseidonimizēta lietotāja identitāte

### <a name="officesystemsystemhealthmetadatadevice"></a>Office.System.SystemHealthMetadataDevice

Metadati, kas nepieciešami, lai izolētu kļūmes atkārtošanu.

Tiek apkopoti tālāk norādītie lauki.

  - **CollectionTime —** laiks, kad metadati tika apkopoti.

  - **ComputerSystemProductUuidHash —** mātesplates UUID vienvirziena jaukšanas vērtība.

  - **DeviceClass —** ierīces, kurā Office darbojas, tipa identifikators.

  - **DeviceMake —** ierīces, kurā Office darbojas, aparatūras sistēmas saimes identifikators.

  - **DeviceManufacturer —** ierīces, kurā Office darbojas, ražotājs.

  - **DeviceModel —** ierīces, kurā Office darbojas, modelis.

  - **DigitizerInfo —** informācija par ciparotāju, kas pievienots ierīcei, kurā Office darbojas.

  - **IsLaptop —** vai ierīce, kurā Office darbojas, ir klēpjdators.

  - **IsTablet —** vai ierīce, kurā Office darbojas, ir planšetdators.

  - **LicensingACID —** Office instalācijas licencēšanas identifikators.

  - **MachineName —** ierīces, kurā Office darbojas, nosaukums.

  - **NumProcPhysCores —** fizisko kodolu skaits procesorā.

  - **NumProcShareSingleCache —** procesoru skaits, kas koplieto vienu kešatmiņu ierīcē, kurā Office darbojas.

  - **NumProcShareSingleCore —** procesoru skaits katrā fiziskajā kodolā ierīcē, kurā Office darbojas.

  - **OlsLicenseId —** Office instalācijas licencēšanas pakalpojuma identifikators.

  - **Platform —** identifikators, kādā vidē Office darbojas.

  - **PowerPlatformRole —** ierīces, kurā Office darbojas, OEM vēlamās datora lomas identifikators.

  - **ProcessorCount —** procesoru skaits ierīcē, kurā Office darbojas.

  - **ProcSpeedMHz —** procesora ātrums megahercos ierīcē, kur Office darbojas.

  - **ProcType —** procesora arhitektūra.

  - **ProcTypeText —** procesora veids ierīcē, kurā darbojas Office.

  - **RamMB —** RAM apjoms, kas pieejams ierīcē, kur Office darbojas.

  - **SusClientId —** tās ierīces Windows Update ID, kurā Office darbojas.

  - **SystemFamily —** ierīces, kurā Office darbojas, aparatūras sistēmas saimes identifikators.

  - **SystemSKU —** ierīces, kurā Office darbojas, aparatūras sistēmas SKU identifikators.

  - **SysVolFreeSpaceMB —** sistēmas sējumā pieejamās brīvās vietas apjoms megabaitos.

  - **SysVolSizeMB —** sistēmas sējumā pieejamās vietas apjoms megabaitos.

  - **WindowsErrorReportingMachineId —** ierīces, kurā Office darbojas, Windows kļūdu uzrādīšanas piešķirtais datora identifikators.

  - **WindowsSqmMachineId —** ierīces, kurā Office darbojas, Windows piešķirtais datora identifikators.

### <a name="officesystemsystemhealthmetadatadeviceconsolidated"></a>Office.System.SystemHealthMetadataDeviceConsolidated

Metadati, kas nepieciešami, lai izolētu kļūmes atkārtošanu.

Tiek apkopoti tālāk norādītie lauki.

  - **BootDiskType —** disks vai cietvielu disks

  - **ComputerSystemProductUuidHash —** mātesplates UUID vienvirziena jaukšanas vērtība.

  - **DeviceClass —** ierīces, kurā Office darbojas, tipa identifikators.

  - **DeviceManufacturer —** ierīces, kurā Office darbojas, ražotājs.

  - **DeviceModel —** ierīces, kurā Office darbojas, modelis.

  - **DeviceProcessorModel —** ierīces, kurā Office darbojas, procesora modelis.

  - **DigitizerInfo —** informācija par ciparotāju, kas pievienots ierīcei, kurā Office darbojas.

  - **HasSpectreFix —** vai ierīces, kurā Office darbojas, procesoram ir Spectre labojums.

  - **IsLaptop —** vai ierīce, kurā Office darbojas, ir klēpjdators.

  - **IsTablet —** vai ierīce, kurā Office darbojas, ir planšetdators.

  - **MachineName —** ierīces, kurā Office darbojas, nosaukums.

  - **NumProcPhysCores —** fizisko kodolu skaits procesorā.

  - **NumProcShareSingleCache —** procesoru skaits, kas koplieto vienu kešatmiņu ierīcē, kurā Office darbojas.

  - **NumProcShareSingleCore —** procesoru skaits katrā fiziskajā kodolā ierīcē, kurā Office darbojas.

  - **Platform —** identifikators, kādā vidē Office darbojas.

  - **PowerPlatformRole —** ierīces, kurā Office darbojas, OEM vēlamās datora lomas identifikators.

  - **powerPlatformRole —** ierīces, kurā Office darbojas, OEM vēlamās datora lomas identifikators.

  - **ProcessorCount —** procesoru skaits ierīcē, kurā Office darbojas.

  - **ProcSpeedMHz —** procesora ātrums megahercos ierīcē, kur Office darbojas.

  - **ProcType —** procesora arhitektūra.

  - **ProcTypeText —** procesora veids ierīcē, kurā darbojas Office.

  - **RamMB —** RAM apjoms, kas pieejams ierīcē, kur Office darbojas.

  - **SusClientId —** tās ierīces Windows Update ID, kurā Office darbojas.

  - **SysVolFreeSpaceMB —** sistēmas sējumā pieejamās brīvās vietas apjoms megabaitos.

  - **SysVolSizeMB —** sistēmas sējumā pieejamās vietas apjoms megabaitos.

  - **sysVolSizeMB —** sistēmas sējumā pieejamās vietas apjoms megabaitos.

  - **WindowsErrorReportingMachineId** — ierīces, kurā Office darbojas, Windows kļūdu uzrādīšanas piešķirtais datora identifikators.

  - **WindowsSqmMachineId** — ierīces, kurā Office darbojas, Windows piešķirtais datora identifikators.

### <a name="officesystemsystemhealthmetadataoperatingsystem"></a>Office.System.SystemHealthMetadataOperatingSystem

Metadati, kas nepieciešami, lai izolētu kļūmes atkārtošanu.

Tiek apkopoti tālāk norādītie lauki.

  - **CollectionTime** — laiks, kad šis notikums tika ierindots augšupielādei

  - **IsTerminalServer** — aplams/patiess ir termināļa servera klients

  - **OsBuild** — operētājsistēmas būvējuma versija.

  - **OsBuildRevision** — OS būvējuma pārskatījums

  - **OSEnvironment —** Windows, iOS, Mac, Android utt.

  - **OsMajorVer** — operētājsistēmas galvenā versija.

  - **OsMinorVer** — operētājsistēmas papildversija.

  - **OSSDKVersionCode** — operētājsistēmas SDK versijas identifikators.

  - **OsSku** — OS SKU

  - **OsSuite2** — operētājsistēmas komplekta identifikators.

  - **OSVersionString** — operētājsistēmas versijas identifikators.

  - **ServicePackMajorVer** — OS servisa pakotnes galvenā versija

  - **ServicePackMinorVer** — OS servisa pakotnes papildversija

### <a name="officesystemsystemhealthmetadataoperatingsystemdevice"></a>Office.System.SystemHealthMetadataOperatingSystemDevice

Metadati, kas nepieciešami, lai izolētu kļūmes atkārtošanu.

Tiek apkopoti tālāk norādītie lauki.

  - **CollectionTime —** laiks, kad šis notikums tika ierindots augšupielādei

  - **DeviceClass —** ierīces, kurā Office darbojas, tipa identifikators.

  - **DeviceManufacturer —** ierīces, kurā Office darbojas, ražotājs.

  - **DeviceModel —** ierīces, kurā Office darbojas, modelis.

  - **DigitizerInfo —** informācija par ciparotāju, kas pievienots ierīcei, kurā Office darbojas.

  - **IsLaptop —** vai ierīce, kurā Office darbojas, ir klēpjdators.

  - **IsTablet —** vai ierīce, kurā Office darbojas, ir planšetdators.

  - **IsTerminalServer —** aplams/patiess ir termināļa servera klients

  - **MachineName —** ierīces, kurā Office darbojas, nosaukums.

  - **NumProcPhysCores —** fizisko kodolu skaits procesorā.

  - **NumProcShareSingleCache —** procesoru skaits, kas koplieto vienu kešatmiņu ierīcē, kurā Office darbojas.

  - **NumProcShareSingleCore —** procesoru skaits katrā fiziskajā kodolā ierīcē, kurā Office darbojas.

  - **OsBuild —** operētājsistēmas būvējuma versija.

  - **OsBuildRevision —** OS būvējuma pārskatījums

  - **OSEnvironment —** Windows, iOS, Mac, Android utt.

  - **OsMajorVer —** operētājsistēmas galvenā versija.

  - **OsMinorVer —** operētājsistēmas papildversija.

  - **OSSDKVersionCode —** operētājsistēmas SDK versijas identifikators.

  - **OsSku —** OS SKU

  - **OsSuite2 —** operētājsistēmas komplekta identifikators.

  - **OSVersionString —** operētājsistēmas versijas identifikators.

  - **Platform —** identifikators, kādā vidē Office darbojas.

  - **PowerPlatformRole —** ierīces, kurā Office darbojas, OEM vēlamās datora lomas identifikators.

  - **ProcessorCount —** procesoru skaits ierīcē, kurā Office darbojas.

  - **ProcSpeedMHz —** procesora ātrums megahercos ierīcē, kur Office darbojas.

  - **ProcTypeText —** procesora veids

  - **RamMB —** RAM apjoms, kas pieejams ierīcē, kur Office darbojas.

  - **ServicePackMajorVer —** OS servisa pakotnes galvenā versija

  - **ServicePackMinorVer —** OS servisa pakotnes papildversija

  - **SysVolFreeSpaceMB —** sistēmas sējumā pieejamās brīvās vietas apjoms megabaitos.

  - **SysVolSizeMB —** sistēmas sējumā pieejamās vietas apjoms megabaitos.

### <a name="officesystemsystemhealthmetadataos"></a>Office.System.SystemHealthMetadataOS

Metadati, kas nepieciešami, lai izolētu kļūmes atkārtošanu.

Tiek apkopoti tālāk norādītie lauki.

  - **CountryRegion —** valsts/reģiona identifikatora operētājsistēmas iestatījums.

  - **HorizontalResolution —** horizontālā ekrāna izšķirtspēja

  - **IsTerminalServer —** aplams/patiess ir termināļa servera klients

  - **KeyboardLanguage —** ierīces tastatūras valodas identifikators

  - **KeyboardLanguageTag —** ierīces tastatūras valodas identifikators

  - **OfficeWvd —** norāda, kādā stāvoklī ir Windows virtuālais dators.

  - **OsBuild —** operētājsistēmas būvējuma versija.

  - **OsBuildRevision —** OS būvējuma pārskatījums

  - **OSEnvironment —** Windows, iOS, Mac, Android utt.

  - **OsLocale —** operētājsistēmas lokalizācijas identifikators.

  - **OsLocaleTag —** operētājsistēmas lokalizācijas identifikators.

  - **OsMajorVer —** operētājsistēmas galvenā versija.

  - **OsMinorVer —** operētājsistēmas papildversija.

  - **OSSDKVersionCode —** operētājsistēmas SDK versijas identifikators.

  - **OsSku —** operētājsistēmas SKU identifikators.

  - **OsSuite2 —** operētājsistēmas komplekta identifikators.

  - **OsUiLang —** operētājsistēmas lietotāja interfeisa valoda.

  - **OSVersionString —** operētājsistēmas versijas identifikators.

  - **ScreenDepth —** ekrāna dziļums

  - **ScreenDpi —** ekrāna DPI

  - **ServicePackMajorVer —** OS servisa pakotnes galvenā versija

  - **ServicePackMinorVer —** OS servisa pakotnes papildversija

  - **SystemLocale —** operētājsistēmas noklusējuma lokalizācija

  - **SystemLocaleTag —** operētājsistēmas noklusējuma lokalizācija

  - **TimeZoneBiasInMinutes —** starpība minūtēs starp vietējo laiku un UTC.

  - **VerticalResolution —** vertikālā ekrāna izšķirtspēja

### <a name="officesystemsystemhealthmetadatascreencultureusersqmid"></a>Office.System.SystemHealthMetadataScreenCultureUserSqmId

Metadati, kas nepieciešami, lai izolētu kļūmes atkārtošanu.

Tiek apkopoti tālāk norādītie lauki.

  - **Alias —** Microsoft darbinieka vai automatizētā lietotāja aizstājvārds

  - **CID —** pseidonimizēta lietotāja identitāte

  - **CollectibleClassifications —** datu klasifikācijas, ko var apkopot atbilstoši klienta konfidencialitātes iestatījumiem

  - **CollectionTime —** laiks, kad šis notikums tika ierindots augšupielādei

  - **CountryRegion —** valsts/reģiona identifikatora operētājsistēmas iestatījums.

  - **DomainName —** Microsoft domēna nosaukums

  - **HorizontalResolution —** horizontālā ekrāna izšķirtspēja

  - **IntegratedScreenSize —** integrētā ekrāna lielums.

  - **IsJoinedToDomain —** patiess/aplams, vai klienta domēns ir savienots

  - **IsLabMachine —** ir Microsoft testēšanas laboratorijas dators

  - **IsMsftInternal —** patiess/aplams, vai dators ir Microsoft uzņēmuma domēnā

  - **IsSubscription —** vai Office lietojumprogramma ir instalēta atbilstoši abonementa licencei.

  - **KeyboardLanguage —** ierīces tastatūras valodas identifikators

  - **KeyboardLanguageTag —** ierīces tastatūras valodas identifikators

  - **OsLocale —** operētājsistēmas lokalizācijas identifikators.

  - **OsLocaleTag —** operētājsistēmas lokalizācijas identifikators.

  - **OsUiLang —** operētājsistēmas lietotāja interfeisa valoda.

  - **ScreenDepth —** ekrāna dziļums

  - **ScreenDpi —** ekrāna DPI

  - **ScreenXDpi —** ekrāna X DPI

  - **ScreenYDpi —** ekrāna Y DPI

  - **SqmUserId —** Office instalēšanas nejaušs identifikators.

  - **StudyId —** programmatūras kvalitātes metrikas pētījuma identifikators.

  - **SystemLocale —** operētājsistēmas noklusējuma lokalizācija

  - **SystemLocaleTag —** operētājsistēmas noklusējuma lokalizācija

  - **TimeZoneBiasInMinutes —** starpība minūtēs starp vietējo laiku un UTC.

  - **VerticalResolution —** vertikālā ekrāna izšķirtspēja

  - **WinUserActType —** vai Windows lietotājs, kas izmanto Office, ir lokālais administrators, prasmīgs lietotājs vai parasts lietotājs.

### <a name="officesystemsystemhealthofficelensidentity"></a>Office.System.SystemHealthOfficeLensIdentity

Lietotāja identitātes informācija, kas nepieciešama, lai izpildītu datu subjektu pieprasījumus.

Tiek apkopoti tālāk norādītie lauki.

  - **CID** — pseidonimizēta lietotāja identitāte

### <a name="officesystemsystemhealthrollbacksessionmetadata"></a>Office.System.SystemHealthRollbackSessionMetadata

Metadati, kas nepieciešami, lai izolētu kļūmes atkārtošanu.

Tiek apkopoti tālāk norādītie lauki.

  - **InstallMethod** — jauna instalēšana, atjaunināšana vai atrite

  - **IsSubscription** — vai Office lietojumprogramma ir instalēta atbilstoši abonementa licencei.

  - **PreviousBuild** — iepriekš instalētā būvējuma versija

### <a name="officesystemsystemhealthsessionlifecycleandheartbeat"></a>Office.System.SystemHealthSessionLifecycleAndHeartbeat

Nodrošina informāciju par sistēmas darbspējas datiem.

Tiek apkopoti tālāk norādītie lauki.

  - **InstallMethod** — vai pašreizējā Office instalācija tika jaunināta, atritināta vai svaigi instalēta.

  - **InteractionSessionID** — sesijas identifikators.

  - **PreviousBuild** — Office versija, uz kuru šis būvējums tika jaunināts vai no kura tas tika atritināts.

  - **State** — stāvoklis, uz kuru sesija veica maiņu.

  - **Time** — brīdis, kad sesijas stāvoklis tika mainīts.

### <a name="officesystemsystemhealthsessionstarttime"></a>Office.System.SystemHealthSessionStartTime

Tiek izmantots kopā ar avārijas datiem, lai atdalītu agrīnās avārijas no vēlīnajām (t.i., noteiktu, vai lietotājs izmantoja lietojumprogrammu kādu laiku pirms avārijas)

Tiek apkopoti tālāk norādītie lauki.

  - **SessionStart** — laiks, kad telemetrija sāk datu apstrādi.

### <a name="officesystemsystemhealthungracefulappexitdesktop"></a>Office.System.SystemHealthUngracefulAppExitDesktop

Notikumu izraisa abnormāla lietojumprogrammas apture (piemēram, likvidēts uzdevumu pārvaldnieks, uzkaras programma utt.) Office klienta programmām, ieskaitot, bet ne tikai, Word, Excel, PowerPoint un Outlook. Mēs izmantojam rādītājus par nelabvēlīgu iziešanu no programmas, lai mērītu Office klienta produktu darbspēju. Tas ir uzņēmējdarbībā svarīgs signāls, kuru izmanto Office inženieri, lai noteiktu produktu stabilitāti.

Tiek apkopoti tālāk norādītie lauki.

  - **AffectedProcessAppBuild —** būvējuma versijas identifikators ietekmētajam procesam.

  - **AffectedProcessAppBuildRevision —** būvējuma pārskatījuma identifikators ietekmētajam procesam.

  - **AffectedProcessAppMajorVer —** būvējuma galvenās versijas identifikators ietekmētajam procesam.

  - **AffectedProcessAppMinorVer —** būvējuma papildversijas identifikators ietekmētajam procesam.

  - **AffectedProcessAppName —** ietekmētā procesa nosaukums. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **AffectedProcessExeBuildVersion —** ietekmētā procesa būvējuma versijas numurs. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **AffectedProcessExeMajorVersion —** ietekmētā procesa galvenās versijas numurs. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **AffectedProcessExeMinorVersion —** ietekmētā procesa papildversijas numurs. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **AffectedProcessExeRevisionVersion —** ietekmētā procesa būvējuma pārskatījuma versijas numurs. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **AffectedProcessIsDebug —** vai ietekmētais process ir atkļūdošanas būvējums. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **AffectedProcessIsLabMachine —** vai ietekmētais process ir Microsoft laboratorijā. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **AffectedProcessOsEnvironment —** ietekmētā procesa operētājsistēmas identifikators. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **AppName —** ietekmētās lietojumprogrammas nosaukums. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **CrashedAssignedFlights —** avarējušajam procesam piešķirtie lidojumi. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **CrashedConfigIds —** avarējušajam procesam piešķirtā konfigurācija. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **CrashedEcsETag —** avarējušā procesa eksperimenta identifikators.

  - **CrashedImpressionId —** avarējušā procesa seansa identifikators. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **CrashedModuleName —** kļūdainā moduļa nosaukums.

  - **CrashedProcessSessionID —** avarējušā procesa unikāls identifikators. 

  - **CrashedProcessSessionInitTime —** laiks, kad ietekmētais process tika sākts. 

  - **CrashedSessionInitTime —** laiks, kad ietekmētais process tika sākts.

  - **HexCrashTag —** unikālais avārijas koda identifikators.

  - **CrashType —** avārijas veida intervāla identifikators.

  - **DetectionTime —** laiks, kad tika konstatēta neparedzētā izeja. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **ErrorString —** kļūdas apraksts. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **ExceptionAddress —** adrese programmā, kur kļūme radās. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **ExceptionCode —** izņēmuma intervāla identifikators.

  - **FaultAppName —** kļūdainās lietojumprogrammas nosaukums. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **InstallMethod —** vai pašreizējais Office būvējums tika jaunināts, atritināts vai svaigi instalēts.

  - **InstallType —** Office instalēšanas metodes identifikators. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **InstallTypeName —** Office instalēšanas metodes identifikators. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **IsLabMachine —** vai sistēma Office tiek izmantota Microsoft laboratorijā. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **IsMsftInternal —** vai Windows lietotājs, kurš izmanto Office, ir Microsoft darbinieks. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **ModuleBaseAddress —** kļūdainā moduļa bāzes adrese. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **ModuleBuildVersion —** kļūdainā moduļa būvējuma versijas numurs. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **ModuleMajorVersion —** kļūdainā moduļa galvenās versijas numurs. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **ModuleMinorVersion —** kļūdainā moduļa papildversijas numurs. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **ModuleName —** kļūdainā moduļa nosaukums. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **HexModuleOffset —** nobīde baitos (heksadecimālajā formātā) no bāzes adreses, kur kļūme radās.

  - **ModuleRevisionVersion —** kļūdainā moduļa būvējuma pārskatījuma versijas numurs. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **ModuleSize —** kļūdainā moduļa izmērs baitos. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **ModuleVersion** — par avāriju atbildīgā kļūmes moduļa versija.

  - **OfficeArchitectureText** — instalācijas arhitektūra: x64, x86 utt.

  - **OfficeUiLang —** Office lietojumprogrammas lietotāja saskarnes valoda.

  - **OSEnvironment —** identifikators, kādā vidē Office darbojas.

  - **PreviousBuild —** iepriekš instalētā būvējuma versija

  - **ProcessorArchitecture** — apstrādātāja arhitektūra videi: x64, x86, utt.

  - **SessionFlags** — nosaka sesijas nosacījumus, piemēram: vai fails tika atvērts vai rediģēts, vai mākoņa dokuments tika atvērts, vai palaišanas sekvence tika pabeigta utt. 

  - **UAETypeName —** intervāla identifikators par to, kā izeja no lietojumprogrammas notika negraciozi. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **UninitLibletId –** kļūdainā avārijas komponenta unikālais identifikators.

  - **VerifyElseCrashTag —** unikālais identifikators par to, kur lietojumprogramma avarēja. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

### <a name="officesystemsystemhealthungracefulappexitimmersive"></a>Office.System.SystemHealthUngracefulAppExitImmersive

Tiek izmantots, lai tvertu avāriju metriku.

Tiek apkopoti tālāk norādītie lauki.

  - **AffectedProcessAppBuild —** būvējuma versijas identifikators ietekmētajam procesam.

  - **AffectedProcessAppBuildRevision —** būvējuma pārskatījuma identifikators ietekmētajam procesam.

  - **AffectedProcessAppMajorVer —** būvējuma galvenās versijas identifikators ietekmētajam procesam.

  - **AffectedProcessAppMinorVer —** būvējuma papildversijas identifikators ietekmētajam procesam.

  - **AffectedProcessAppName —** ietekmētā procesa nosaukums.

  - **AffectedProcessExeBuildVersion —** ietekmētā procesa būvējuma versijas numurs.

  - **AffectedProcessExeMajorVersion —** ietekmētā procesa galvenās versijas numurs.

  - **AffectedProcessExeMinorVersion —** ietekmētā procesa papildversijas numurs.

  - **AffectedProcessExeRevisionVersion —** ietekmētā procesa būvējuma pārskatījuma versijas numurs.

  - **AffectedProcessIsDebug —** vai ietekmētais process ir atkļūdošanas būvējums.

  - **AffectedProcessIsLabMachine —** vai ietekmētais process ir Microsoft laboratorijā.

  - **AffectedProcessOsEnvironment —** ietekmētā procesa operētājsistēmas identifikators.

  - **AppName —** ietekmētās lietojumprogrammas nosaukums.

  - **CrashedAssignedFlights —** avarējušajam procesam piešķirtie lidojumi.

  - **CrashedConfigIds —** avarējušajam procesam piešķirtā konfigurācija.

  - **CrashedImpressionId —** avarējušā procesa seansa identifikators.

  - **CrashedInteractionSessionID —** mijiedarbības sesijas identifikators ietekmētajam procesam.

  - **CrashedInteractionSessionTime —** laiks, kad ar ietekmēto procesu var mijiedarboties.

  - **CrashedProcessSessionID —** avarējušā procesa unikāls identifikators.

  - **CrashedProcessSessionInitTime —** laiks, kad ietekmētais process tika sākts.

  - **DetectionTime —** laiks, kad tika konstatēta neparedzētā izeja.

  - **IsLabMachine —** vai sistēma Office tiek izmantota Microsoft laboratorijā.

  - **IsMsftInternal —** vai Windows lietotājs, kurš izmanto Office, ir Microsoft darbinieks.

  - **OSEnvironment —** identifikators, kādā vidē Office darbojas.

  - **PreviousLifecycleState —** ietekmētā procesa stāvoklis, kad tas avarēja.

  - **UAETypeName —** intervāla identifikators par to, kā izeja no lietojumprogrammas notika negraciozi.

### <a name="officesystemsystemhealthungracefulapplicationexitwin32"></a>Office.System.SystemHealthUngracefulApplicationExitWin32

Notikumu izraisa abnormāla lietojumprogrammas apture (piemēram, likvidēts uzdevumu pārvaldnieks, uzkaras programma utt.) Office klienta programmām, ieskaitot, bet ne tikai, Word, Excel, PowerPoint un Outlook. Mēs izmantojam rādītājus par nelabvēlīgu iziešanu no programmas, lai mērītu Office klienta produktu darbspēju. Tas ir uzņēmējdarbībā svarīgs signāls, kuru izmanto Office inženieri, lai noteiktu produktu stabilitāti.

Tiek apkopoti tālāk norādītie lauki.

  - **AddinExecution —** karodziņš, kas informē, ja pievienojumprogramma izpildīja un nepabeidza izpildi nelabvēlīgas iziešanas no programmas laikā. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **AppUsedVirtualMemory** — Office programmas izmantota virtuālā atmiņa

  - **BootCompleted —** vai Office sāknēšana tika pabeigta avārijas brīdī. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **BucketId** — Watson avārijas intervāla identifikators
 
  - **CabGuid** — Watson .cab faila unikālais identifikators (GUID).

  - **CrashedAppBuild —** būvējuma versijas identifikators ietekmētajam procesam. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **CrashedAppMajor —** galvenās versijas identifikators ietekmētajam procesam. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*
 
  - **CrashedAppMinor —** papildversijas identifikators ietekmētajam procesam. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **CrashedAppVersion** — avarējuša procesa programmas versijas identifikators.

  - **CrashedEcsETag —** avarējušā procesa eksperimenta identifikators.

  - **CrashedModuleName —** kļūdainā moduļa nosaukums.

  - **CrashedProcessSessionId —** avarējušā procesa unikāls identifikators.

  - **CrashedProcessSessionInitTime —** laiks, kad ietekmētais process tika sākts.

  - **CrashedSessionInitTime —** laiks, kad ietekmētais process tika sākts.

  - **HexCrashTag —** unikālais avārijas koda identifikators.

  - **CrashTime —** laiks, kad klienta darbība tika pārtraukta neatbilstošā veidā. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **CrashType —** avārijas veida intervāla identifikators.

  - **DetectionTime** — laiks, kad tika konstatēta neparedzētā izeja. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **ExceptionAddress —** adrese programmā, kur kļūme radās. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **ExceptionCode —** izņēmuma intervāla identifikators.

  - **ExceptionInfo** — izņēmuma sistēmas informācija.

  - **HandOff —** vai lietotājs izveidoja un nodeva Office procesu jaunajai sesijai. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **HangTypeCode** — atspoguļo reaģēšana pārtraukšanas klasi, ja process pārstāja reaģēt izpildes laikā.

  - **HasEdit —** vai lietotājs rediģēja dokumentu avarējušajā klientā. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **HasOpen —** vai avarējušajā klientā bija atvērts dokuments. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **HexCrashTag —** unikālais avārijas koda identifikators. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **HexExceptionAddress —** adrese heksadecimālā formātā programmā, kur kļūme radās. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **HexExceptionCode —** izņēmuma intervāla identifikators heksadecimālajā formātā. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **HexModuleBaseAddress —** kļūdainā moduļa bāzes adrese heksadecimālā formātā. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **HexModuleOffset —** nobīde baitos (heksadecimālajā formātā) no bāzes adreses, kur kļūme radās. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **HexModuleSize —** kļūdainā moduļa izmērs baitos heksadecimālā formātā. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **HexVerifyElseCrashTag —** unikālais identifikators heksadecimālajā formātā par to, kur lietojumprogramma avarēja. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **InstallMethod** — vai pašreizējais Office būvējums tika jaunināts, atritināts vai svaigi instalēts.

  - **IsLabMachine —** vai sistēma Office tiek izmantota Microsoft laboratorijā. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **ModuleBaseAddress —** kļūdainā moduļa bāzes adrese. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **HexModuleOffset —** nobīde baitos (heksadecimālajā formātā) no bāzes adreses, kur kļūme radās.

  - **ModuleSize —** kļūdainā moduļa izmērs baitos. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **ModuleStamp** — kļūmes moduļa spiedogs.

  - **ModuleVersion** — par avāriju atbildīgā kļūmes moduļa versija.

  - **OfficeArchitectureText** — Office produkta arhitektūra kā virkne (piem., x86, arm).

  - **OfficeUiLang —** Office lietojumprogrammas lietotāja saskarnes valoda.

  - **PreviousBuild** — iepriekš instalētā būvējuma versija

  - **ProcessorArchitecture** — apstrādātāja arhitektūra videi: x64, x86, utt.

  - **SafeMode —** norāda, vai sesija tika sākta drošajā režīmā. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **SessionFlags** — nosaka sesijas nosacījumus, piemēram: vai fails tika atvērts vai rediģēts, vai mākoņa dokuments tika atvērts, vai palaišanas sekvence tika pabeigta utt. 

  - **StackHash** — pakalpojumā Office nodrošinu kešotu kļūmes steka ID.

  - **SystemAvailableMemory** — operētājsistēmā pieejamā atmiņā

  - **UAEOSEnvironment —** operētājsistēmas vides identifikators. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **UninitLibletId –** kļūdainā avārijas komponenta unikālais identifikators.

  - **VerifyElseCrashTag —** unikālais identifikators par to, kur lietojumprogramma avarēja. *[Šis lauks ir dzēsts jaunākajos Office būvējumos, taču, iespējams, joprojām tiek rādīts vecākos būvējumos.]*

  - **WatsonReportId** — Windows pakalpojumam Watson nosūtītā ziņojuma identifikators.

  - **WerEventCreatedTime** — Windows kļūdu ziņošanas notikuma laikspiedols.


### <a name="officesystemungracefulapplicationexitdesktopappexit"></a>Office.System.UngracefulApplicationExit.DesktopAppExit

Tiek izmantots, lai tvertu avāriju metriku.

Tiek apkopoti tālāk norādītie lauki.

  - **AppBuildVersion —** būvējuma versijas identifikators ietekmētajam procesam.

  - **AppMajorVersion —** ietekmētā procesa galvenās versijas numurs.

  - **AppMinorVersion —** papildversijas identifikators ietekmētajam procesam.

  - **AppName —** ietekmētās lietojumprogrammas nosaukums.

  - **AppRevisionVersion —** būvējuma pārskatījuma identifikators ietekmētajam procesam.

  - **CrashedAssignedFlights —** avarējušajam procesam piešķirtie lidojumi.

  - **CrashedConfigIds —** avarējušajam procesam piešķirtā konfigurācija.

  - **CrashedImpressionId —** avarējušā procesa seansa identifikators.

  - **CrashedInteractionSessionId —** avarējušā procesa mijiedarbības sesijas identifikators.

  - **CrashedProcessSessionId —** avarējušā procesa unikāls identifikators.

  - **CrashType —** avārijas veida intervāla identifikators.

  - **ErrorString —** kļūdas apraksts.

  - **ExceptionAddress —** adrese programmā, kur kļūme radās.

  - **ExceptionCode —** izņēmuma intervāla identifikators.

  - **FaultAppName —** kļūdainās lietojumprogrammas nosaukums.

  - **InstallMethod —** vai pašreizējais Office būvējums tika jaunināts, atritināts vai svaigi instalēts.

  - **InstallType —** Office instalēšanas metodes identifikators.

  - **IsDebug —** vai šis ir Office atkļūdošanas būvējums.

  - **IsHandledCrash —** vai avāriju apstrādātājs tika izsaukts avārijas sesijā.

  - **IsLabMachine —** vai sistēma Office tiek izmantota Microsoft laboratorijā.

  - **ModuleBaseAddress —** kļūdainā moduļa bāzes adrese.

  - **ModuleName —** kļūdainā moduļa nosaukums.

  - **ModuleOffset —** nobīde baitos no bāzes adreses, kur kļūme radās.

  - **ModuleSize —** kļūdainā moduļa izmērs baitos.

  - **OSEnvironment —** identifikators, kādā vidē Office darbojas.

  - **PreviousBuild —** iepriekš instalētā būvējuma versija

  - **PreviousInteractionSessionTime —** laiks, kad iepriekšējā mijiedarbības sesija tika sākta.

  - **PreviousLifecycleState —** iepriekšējās sesijas dzīves cikla stāvokļa identifikators.

  - **PreviousSessionInitTime —** laiks, kad iepriekšējā sesija tika sākta.

  - **StackHash —** identifikators, kas norāda, kur kodā ietekmētais process avarēja.

  - **VerifyElseCrashTag —** unikālais identifikators par to, kur lietojumprogramma avarēja.

### <a name="officesystemuserchangeddiagnosticlevel"></a>Office.System.UserChangedDiagnosticLevel

Informācija, kas nepieciešama, lai nodrošinātu, ka tiek īstenota lietotāja konfidencialitātes politikas izvēle.

Tiek apkopoti tālāk norādītie lauki.

  - **DiagnosticLevelChanged**: norāda, ka lietotājs mainīja savu diagnostikas līmeni.

  - **NewDiagnosticLevel**: līmenis pēc lietotāja maiņas.

  - **OldDiagnosticLevel**: līmenis, ko lietotājs izmantoja pirms savām izmaiņām.

### <a name="officetelemetryariaeventsinkhandlemsadevicetokenresponse"></a>Office.Telemetry.AriaEventSink.HandleMsaDeviceTokenResponse

Microsoft konta pakalpojuma nepieejamības signāls.

Tiek apkopoti tālāk norādītie lauki.

  - **RetryCount** — atkārtotu savienojumu mēģinājumu skaits ar MSA pakalpojumu.

### <a name="officetelemetryariaeventsinkrequestmsadevicetoken"></a>Office.Telemetry.AriaEventSink.RequestMsaDeviceToken

Microsoft konta pakalpojuma nepieejamības signāls.

Tiek apkopoti tālāk norādītie lauki.

  - **RetryCount** — atkārtotu savienojumu mēģinājumu skaits ar Microsoft konta pakalpojumu.

### <a name="officetelemetryclientsamplingoverridden"></a>Office.Telemetry.ClientSamplingOverridden

Nepieciešams, lai nodrošinātu precīzu atveidošanas ātrumu. Parasti neattiecas uz ražošanas mērķauditorijas grupu.

Tiek apkopoti tālāk norādītie lauki.

  - **OverriddenMeasureEnabled** — vai klients ir iestatīts nosūtīt vairāk nekā nesavākto paraugu notikumus

  - **OverriddenNumberlinePosition** — jaunā numura rindas pozīcija paraugu ņemšanai

  - **OverriddenReportedSampleRate** — jaunais norādītais parauga ātrums

  - **OverriddenSampleRate** — jaunais parauga ātrums

  - **PreviousNumberlinePosition** — paraugu ņemšanas pozīcija numura rindā.

  - **PreviousSampleRate** — parauga ātrums pirms ignorēšanas.

  - **WasMeasureEnabled** — vai klients tika iestatīts nosūtīt vairāk nekā nesavākto paraugu notikumus

### <a name="officetelemetrycomplianceeventnotinbasicallowlist"></a>Office.Telemetry.Compliance.EventNotInBasicAllowList

Atskaišu nederīgā telemetrijas ieviešana vai izvietošana

Tiek apkopoti tālāk norādītie lauki.

  - **EventName** — notikuma nosaukums, kas nav sarakstā

### <a name="officetelemetrycompliancemissingdatacategory"></a>Office.Telemetry.Compliance.MissingDataCategory

Atskaišu nederīgā telemetrijas ieviešana vai izvietošana

Tiek apkopoti tālāk norādītie lauki.

  - **EventName** — notikuma nosaukums, kam trūkst kategorijas

  - **IsFromRule** — vai notikums bija no telemetrijas kārtulas

### <a name="officetelemetrycompliancemissingdatacategoryinrule"></a>Office.Telemetry.Compliance.MissingDataCategoryInRule

Atskaišu nederīgā telemetrijas ieviešana vai izvietošana

Tiek apkopoti tālāk norādītie lauki.

  - **RuleId** — kārtulas ID, kam trūkst datu kategorijas

  - **RuleVersion** — kārtulas versija, kam trūkst datu kategorijas

### <a name="officetelemetrydiagnosticdataviewerstatechanged"></a>Office.Telemetry.DiagnosticDataViewerStateChanged

Pārbauda, vai patērētāji var skatīt datus, kad tie tiek izvadīti no datora, izmantojot diagnostikas datu skatītāju.

Tiek apkopoti šādi lauki:

  - **Dialogcanceled** — vai diagnostikas datu skatītāja dialogs tika atcelts

  - **NewState** — jaunais diagnostikas datu skatītāja stāvoklis

  - **WasDialogUsed** — vai diagnostikas datu skatītāja dialogs tika izmantots

### <a name="officetelemetrydynamicconfigfetchconfigs"></a>Office.Telemetry.DynamicConfig.FetchConfigs

Dati, kas nepieciešami, lai izmērītu telemetrijas konfigurācijas pakalpojuma darbspēju.

Tiek apkopoti tālāk norādītie lauki.

  - **ParsedConfigCount** — parsēto dinamisko konfigurāciju skaits

  - **ParsedConfigs** — parsēto dinamisko konfigurāciju skaits

  - **RejectedConfigCount** — noraidīto konfigurāciju skaits

  - **RejectedConfigs** — noraidīto konfigurāciju skaits

  - **RejectedConfigsList** — komatatdalīts noraidīto konfigurāciju saraksts.

### <a name="officetelemetrydynamicconfigparsejsonconfig"></a>Office.Telemetry.DynamicConfig.ParseJsonConfig

Dati, kas nepieciešami, lai izmērītu telemetrijas konfigurācijas pakalpojuma darbspēju

Tiek apkopoti tālāk norādītie lauki.

  - **ErrorMessage** — parsēšanas kļūdas ziņojums

  - **NodeName** — mezgls, kuru neizdevās parsēt

### <a name="officetelemetrydynamicconfigpopulatedrequestignored"></a>Office.Telemetry.DynamicConfig.PopulatedRequestIgnored

Šis notikums tiek ģenerēts, kad mums neizdodas izveidot telemetrijas konfigurācijas konveijeru.

Šis notikums neapkopo laukus.

### <a name="officetelemetrydynamicconfigpopulatetreecalledagain"></a>Office.Telemetry.DynamicConfig.PopulateTreeCalledAgain

Dati, kas nepieciešami, lai izmērītu telemetrijas konfigurācijas pakalpojuma darbspēju.

Šis notikums neapkopo laukus.

### <a name="officetelemetryeventquarantined"></a>Office.Telemetry.EventQuarantined

Tiek izmantots, lai verificētu, vai citi NSD notikumi darbojas pareizi.

Tiek apkopoti tālāk norādītie lauki.

  - **EventName** — karantīnā ievietotā notikuma nosaukums

  - **Reason** — karantīnas iemesls

### <a name="officetelemetryflusheventbuffer"></a>Office.Telemetry.FlushEventBuffer 

Norāda notikuma bufera lielumu un var norādīt telemetrijas kļūmes, kas saistītas ar lielu bufera lietojumu.

Tiek apkopoti tālāk norādītie lauki.

  - **EventCount** — notikumu skaits buferī

  - **FirstPassCount** — pirmās nodošanas notikumu skaits

  - **SecondPassCount** — otrās nodošanas notikumu skaits

### <a name="officetelemetrygetfilteredpayloadsfromdisk"></a>Office.Telemetry.GetFilteredPayloadsFromDisk

Verificē, vai noteiktas mantotā telemetrijas konveijera daļas darbojas platformās, kas to joprojām izmanto.

Šis notikums neapkopo laukus.

### <a name="officetelemetryinvaliddatacontractname"></a>Office.Telemetry.InvalidDataContractName

Atskaišu nederīgā telemetrijas ieviešana vai izvietošana

Tiek apkopoti tālāk norādītie lauki.

  - **DataContractName** — telemetrijas datu līguma nosaukums

  - **EventName** — notikuma ar nederīgo datu līgumu nosaukums

  - **IsRuleEvent** — patiess/aplams, vai šo notikumu ieviesa telemetrijas kārtula

### <a name="officetelemetryinvaliddatafieldname"></a>Office.Telemetry.InvalidDataFieldName 

Atskaišu nederīgā telemetrijas ieviešana vai izvietošana

Tiek apkopoti tālāk norādītie lauki.

  - **DataFieldName** — telemetrijas datu lauka nosaukums

  - **EventName** — notikuma ar nederīgo lauku nosaukums

  - **IsRuleEvent** — patiess/aplams, vai šo notikumu ieviesa telemetrijas kārtula.

### <a name="officetelemetryinvalideventcontractname"></a>Office.Telemetry.InvalidEventContractName 

Atskaišu nederīgā telemetrijas ieviešana vai izvietošana

Tiek apkopoti tālāk norādītie lauki.

  - **EventContractName** — nederīgā telemetrijas līguma nosaukums

  - **EventName** — notikuma ar nederīgo līguma nosaukumu nosaukums

  - **IsRuleEvent** — patiess/aplams, vai šo notikumu ieviesa telemetrijas kārtula

### <a name="officetelemetryloadxmlrules"></a>Office.Telemetry.LoadXmlRules

Norāda, vai parsēšanas telemetrijas kārtulu izpilde izdevās

Tiek apkopoti tālāk norādītie lauki.

  - **DetachedDuration** — atvienošanas ilgums mikrosekundēs

### <a name="officetelemetrymissingfielddetails"></a>Office.Telemetry.MissingFieldDetails

Atskaitēm trūkst lauku informācijas, lai diagnosticētu drukas kļūdas telemetrijas konfigurācijā.

Tiek apkopoti tālāk norādītie lauki.

  - **ErrorRuleId** — telemetrijas kārtulas ID, kas pieprasīja trūkstošo lauku

  - **ErrorRuleVersion** — telemetrijas kārtulas versija, kas pieprasīja trūkstošo lauku

  - **EtwEventGuid** — pieprasītā lauka ETW GUID

  - **EtwEventId** — pieprasītā lauka ETW notikuma ID

  - **MissingFieldName** — pieprasītais lauka nosaukums

  - **UlsTagId** — trūkstošā lauka koda tags

### <a name="officetelemetryprocessidlequeuejob"></a>Office.Telemetry.ProcessIdleQueueJob

Norāda, ka telemetrijas dīkstāves apstrāde tika sākta, kā paredzēts.

Tiek apkopoti tālāk norādītie lauki.

  - **DetachedDuration** — atvienošanas ilgums mikrosekundēs

  - **FailureDiagnostic** — kļūdainā darbība

### <a name="officetelemetryredstoneinboxsampling"></a>Office.Telemetry.RedstoneInboxSampling

Klienta paraugu ņemšanas stāvoklis, kas nepieciešams, lai precīzi interpretētu citu metriku.

Tiek apkopoti tālāk norādītie lauki.

  - **MeasuresEnabled** — vai šajā sesijā ir iespējoti mērījumi?

  - **SamplingClientIdValue** — paraugu ņemšanas vērtība šim klientam

  - **SamplingKey** — paraugu ņemšanas atslēga šim klientam

  - **SamplingMethod** — paraugu ņemšanas metode šim klientam

### <a name="officetelemetryredstoneinboxsamplingcritical"></a>Office.Telemetry.RedstoneInboxSamplingCritical

Klienta paraugu ņemšanas stāvoklis var būt nepieciešams, lai precīzi interpretētu citu metriku.

Tiek apkopoti tālāk norādītie lauki.

  - **MeasuresEnabled** — vai šajā sesijā ir iespējoti mērījumi?

  - **SamplingClientIdValue** — paraugu ņemšanas vērtība šim klientam

  - **SamplingKey** — paraugu ņemšanas atslēga šim klientam

  - **SamplingMethod** — paraugu ņemšanas metode šim klientam

### <a name="officetelemetryruleerrorsaggregated"></a>Office.Telemetry.RuleErrorsAggregated

Telemetrijas darbspējas kļūdu uzrādīšana. Nepieciešama, lai pārbaudītu citus datus (tostarp NSD).

Tiek apkopoti tālāk norādītie lauki.

  - **ErrorCount** — šīs kļūdas skaits apkopošanas laika periodā

  - **ErrorInfo** — kļūdas diagnostikas informācijas numurs

  - **ErrorRuleId** — telemetrijas kārtulas ID, kas izraisīja kļūdu

  - **ErrorRuleVersion** — telemetrijas kārtulas versija, kas izraisīja kļūdu

  - **WarningInfo** — brīdinājuma diagnostikas informācijas numurs

  - **QueueFlushCount** — ierindoto pludināšanas gadījumu skaits

  - **QueueFlushDueToSizeLimit** — lielums, kura gadījumā telemetrija pludina rindu

  - **QueueFlushesDueToSize** — rindas pludināšanas gadījumu skaits, ko izraisīja bufera lielums

  - **QueueHardLimit** — telemetrijas izslēgšanas ierobežojums

  - **QueueLimitHitTime** — kad izslēgšanas ierobežojums tika sasniegts

  - **ResultTime** — šī notikuma laiks

### <a name="officetelemetryrulesenginediskthrottled"></a>Office.Telemetry.RulesEngineDiskThrottled

Ierobežošanas DQ metrika. Nepieciešama, lai nodrošinātu uzticamību visiem pārējiem datiem.

Tiek apkopoti tālāk norādītie lauki.

  - **DiskWriteLimit** — telemetrijas datu diska lieluma ierobežojums

  - **DiskWriteTotal** — telemetrijas datu diska rakstīšanas kopsumma

  - **SessionDiskWriteTotal** — telemetrijas datu sesijas diska rakstīšanas kopsumma

  - **ThrottlingTimestamp** — laiks, kad sesija tika ierobežota

### <a name="officetelemetryrulesenginemediumcostthrottled"></a>Office.Telemetry.RulesEngineMediumCostThrottled

Ierobežošanas DQ metrika. Nepieciešama, lai nodrošinātu uzticamību visiem pārējiem datiem.

Šis notikums neapkopo laukus.

### <a name="officetelemetryrulesenginespikethrottled"></a>Office.Telemetry.RulesEngineSpikeThrottled

Ierobežošanas DQ metrika. Nepieciešama, lai nodrošinātu uzticamību visiem pārējiem datiem.

Tiek apkopoti tālāk norādītie lauki.

  - **CurrentLimit** — pašreizējais smaiļu ierobežojums

  - **Duration** — smailes ilgums

  - **Factor** — smailes faktors

  - **HighestImpactingRuleBytes** — baitu maksimums, ko reģistrēja telemetrijas kārtula

  - **HighestImpactingRuleId** — kārtulas ID, kas reģistrēja visvairāk baitu

  - **HighestImpactingRuleVersion** — kārtulas versija, kas reģistrēja visvairāk baitu

  - **MaxLimit** — maksimālais ierobežojums

  - **ThrottlingTimestamp** — kad telemetrija tika ierobežota

### <a name="officetelemetryrulesenginethrottled"></a>Office.Telemetry.RulesEngineThrottled

Ierobežošanas DQ metrika. Nepieciešama, lai nodrošinātu uzticamību visiem pārējiem datiem.

Tiek apkopoti tālāk norādītie lauki.

  - **ThrottlingTimestamp** — kad telemetrija tika ierobežota

### <a name="officetelemetryrulesengineulsqueuesizebackgroundprocessinglevelreached"></a>Office.Telemetry.RulesEngineUlsQueueSizeBackgroundProcessingLevelReached

Norāda, ka ir pārāk daudz notikumu rindā, ko apstrādāt lietojumprogrammas dīkstāves laikā.

Tiek apkopoti tālāk norādītie lauki.

  - **BackgroundProcessingLevelInBytes** — rindas lielums, lai sāktu apstrādi fonā.

  - **CurrentQueueSize** — notikumu skaits nULS rindā.

  - **CurrentQueueSizeInBytes** — nULS rindas lielums baitos.

  - **ReachedTimestamp** — laiks, kad tika sākta apstrāde fonā.

### <a name="officetelemetryrulesresultuploadlatencyrule"></a>Office.Telemetry.RulesResultUploadLatencyRule

Katras stundas kārtulu rezultātu lietderīgo datu augšupielādes vidējais, minimālais un maksimālais augšupielādes latentums

Tiek apkopoti tālāk norādītie lauki.

  - **AverageLatency** — vidējais augšupielādes latentums.

  - **CollectionTime** — laiks, kad dati par kārtulu augšupielādi tika apkopoti.

  - **LatencyGE201LE400** — augšupielādes gadījumu skaits ar latentumu, kas ir lielāks vai vienāds ar 201 ms un mazāks vai vienāds ar 400 ms

  - **LatencyGE3001** — augšupielādes gadījumu skaits ar latentumu, kas ir lielāks vai vienāds ar 3001 ms.

  - **LatencyGE401LE600** — augšupielādes gadījumu skaits ar latentumu, kas ir lielāks vai vienāds ar 401 ms un mazāks vai vienāds ar 600 ms

  - **LatencyGE601LE800** — augšupielādes gadījumu skaits ar latentumu, kas ir lielāks vai vienāds ar 601 ms un mazāks vai vienāds ar 800 ms

  - **LatencyLE200** — augšupielādes gadījumu skaits ar latentumu, kas ir mazāks par 200 milisekundēm.

  - **MaxLatency** — lielākais novērotais latentums.

  - **MinLatency** — mazākais novērotais latentums.

### <a name="officetelemetrysamplingpolicy"></a>Office.Telemetry.SamplingPolicy

Klienta paraugu ņemšanas stāvoklis, kas nepieciešams, lai precīzi interpretētu citu metriku.

Tiek apkopoti tālāk norādītie lauki.

  - **MeasuresEnabled** — vai šajā sesijā ir iespējoti mērījumi?

  - **SamplingClientIdValue** — paraugu ņemšanas vērtība šim klientam

  - **SamplingKey** — paraugu ņemšanas atslēga šim klientam

  - **SamplingMethod** — paraugu ņemšanas metode šim klientam

### <a name="officetelemetrysamplingpolicyeventtrigger"></a>Office.Telemetry.SamplingPolicyEventTrigger

Klienta paraugu ņemšanas stāvoklis, kas nepieciešams, lai precīzi interpretētu citu metriku.

Tiek apkopoti tālāk norādītie lauki.

  - **MeasuresEnabled** — vai šajā sesijā ir iespējoti mērījumi?

  - **SamplingKey** — paraugu ņemšanas atslēga šim klientam

  - **SamplingMethod** — paraugu ņemšanas metode šim klientam

### <a name="officetelemetrysessiontelemetryruleschanged"></a>Office.Telemetry.SessionTelemetryRulesChanged

Norāda, ka telemetrijas kārtulu kopa ir mainīta

Tiek apkopoti tālāk norādītie lauki.

  - **ChangedRuleId** — telemetrijas kārtulas ID, kas mainījās pašreizējā atjauninājumā

  - **ChangedRuleVersion** — telemetrijas kārtulas versija, kas mainījās pašreizējā atjauninājumā

  - **OperationType** — pievienot vai noņemt darbības tagu

### <a name="officetelemetrysessiontelemetryrulescount"></a>Office.Telemetry.SessionTelemetryRulesCount

Norāda ielādēto telemetrijas kārtulu skaitu

Tiek apkopoti tālāk norādītie lauki.

  - **CountOfLoadedRules** — cik telemetrijas kārtulas ir ielādētas

  - **HadRuleFileAtBoot** — vai sāknējot lietojumprogrammu bija pieejams telemetrijas kārtulu fails

### <a name="officetelemetrysessiontelemetryrulesinitialstate"></a>Office.Telemetry.SessionTelemetryRulesInitialState

Norāda telemetrijas kārtulas, kas tika ielādētas sesijas sākumā

Tiek apkopoti tālāk norādītie lauki.

  - **HadRuleFileAtBoot** — vai sāknējot lietojumprogrammu bija pieejams telemetrijas kārtulu fails

  - **LoadedRulesCount** — cik telemetrijas kārtulas ir ielādētas

  - **LoadedRulesList** — ielādēto telemetrijas kārtulu skaits

### <a name="officetelemetrysystemhealthmetadatanetworkcost"></a>Office.Telemetry.SystemHealthMetadataNetworkCost

Tīkla maksa norāda mūsu spēju iegūt datus.

Tiek apkopoti tālāk norādītie lauki.

  - **NetworkCost** — jaunā tīkla izmērītā vai neizmērītā maksa

  - **OldNetworkCost** — iepriekšējā tīkla izmērītā vai neizmērītā maksa

  - **Tag** — avota koda tags, kas konstatēja izmaiņas

### <a name="officetelemetrysystemhealthmetadatanetworkcostchange"></a>Office.Telemetry.SystemHealthMetadataNetworkCostChange

Tīkla maksa norāda mūsu spēju iegūt datus.

Tiek apkopoti tālāk norādītie lauki.

  - **NewNetworkCost** — jaunā tīkla izmērītā vai neizmērītā maksa

  - **OldNetworkCost** — iepriekšējā tīkla izmērītā vai neizmērītā maksa

  - **Tag** — avota koda tags, kas konstatēja izmaiņas

### <a name="officetelemetrytelemetryactivityaggregationwindowstatistics"></a>Office.Telemetry.TelemetryActivityAggregationWindowStatistics

Norāda apkopoto darbību grupu un instanču skaitu katrā darbībā, kas tiek augšupielādēta.

Tiek apkopoti tālāk norādītie lauki.

  - **GroupCount** — apkopoto darbību, kas sūta datus, skaits.

  - **InstancesToSend** — apkopoto darbību, kas sūta datus, instanču skaits.

### <a name="officetelemetrytelemetryulsqueueusage"></a>Office.Telemetry.TelemetryUlsQueueUsage

Telemetrijas darbspējas kļūdu uzrādīšana. Nepieciešama, lai pārbaudītu citus datus (tostarp NSD).

Tiek apkopoti tālāk norādītie lauki.

  - **AverageEventCount** — vidējais notikumu skaits rindā

  - **AverageQueueCB** — vidējais rindas atmiņas lielums

  - **PeakEventCount** — maksimālais rindas notikumu skaits

  - **PeakQueueCB** — maksimālais rindas atmiņas lielums

  - **QueueDisableRuleLimit** — ierobežojums, kura gadījumā telemetrijas kārtulas tiek atspējotas

### <a name="officetelemetryulsqueuetopthrottlingtags"></a>Office.Telemetry.UlsQueueTopThrottlingTags

Norāda galvenos tagus, kas veicināja ULS rindas izslēgšanu.

Tiek apkopoti tālāk norādītie lauki.

  - **Tag0 —** tags, kas patērēja lielāko rindas daļu

  - **Tag0Percent —** tag0 izmantotā procentuālā rindas daļa

  - **Tag1 —** tags, kas patērēja 2. lielāko rindas apjomu

  - **Tag10 —** tags, kas patērēja 11. lielāko rindas apjomu

  - **Tag10Percent —** tag10 izmantotā procentuālā rindas daļa

  - **Tag11 —** tags, kas patērēja 12. lielāko rindas apjomu

  - **Tag11Percent —** tag11 izmantotā procentuālā rindas daļa

  - **Tag12 —** tags, kas patērēja 13. lielāko rindas apjomu

  - **Tag12Percent —** tag12 izmantotā procentuālā rindas daļa

  - **Tag13 —** tags, kas patērēja 14. lielāko rindas apjomu

  - **Tag13Percent —** tag13 izmantotā procentuālā rindas daļa

  - **Tag14 —** tags, kas patērēja 15. lielāko rindas apjomu

  - **Tag14Percent —** tag14 izmantotā procentuālā rindas daļa

  - **Tag1Percent —** tag1 izmantotā procentuālā rindas daļa

  - **Tag2 —** tags, kas patērēja trešo lielāko rindas apjomu

  - **Tag2Percent —** tag2 izmantotā procentuālā rindas daļa

  - **Tag3 —** tags, kas patērēja ceturto lielāko rindas apjomu

  - **Tag3Percent —** tag3 izmantotā procentuālā rindas daļa

  - **Tag4 —** tags, kas patērēja piekto lielāko rindas apjomu

  - **Tag4Percent —** tag4 izmantotā procentuālā rindas daļa

  - **Tag5 —** tags, kas patērēja sesto lielāko rindas apjomu

  - **Tag5Percent —** tag5 izmantotā procentuālā rindas daļa

  - **Tag6 —** tags, kas patērēja septīto lielāko rindas apjomu

  - **Tag6Percent —** tag6 izmantotā procentuālā rindas daļa

  - **Tag7 —** tags, kas patērēja astoto lielāko rindas apjomu

  - **Tag7Percent —** tag7 izmantotā procentuālā rindas daļa

  - **Tag8 —** tags, kas patērēja devīto lielāko rindas apjomu

  - **Tag8Percent —** tag8 izmantotā procentuālā rindas daļa

  - **Tag9 —** tags, kas patērēja desmito lielāko rindas apjomu

  - **Tag9Percent —** tag9 izmantotā procentuālā rindas daļa

### <a name="officetelemetryvolumetrackingdata"></a>Office.Telemetry.VolumeTrackingData

Notikumu apjoma izsekošanas metrika telemetrijas notikumiem

Tiek apkopoti tālāk norādītie lauki.

  - **EventThreshold** — maksimālais viena notikuma instanču skaits, ko var nosūtīt laika periodā.

  - **HighestEventCount** — lielākais viena notikuma instanču skaits, kas nosūtīts šajā periodā.

  - **HighestEventName** — notikuma ar vislielāko instanču skaitu šajā periodā nosaukums.

  - **TimeWindowInSeconds** — perioda ilgums sekundēs.

  - **TotalEvents** — kopējais periodā nosūtītais notikumu skaits.

  - **UniqueEvents** — periodā nosūtīto unikālo notikumu skaits.

### <a name="officetelemetrywritepayloadstodisk"></a>Office.Telemetry.WritePayloadsToDisk

Verificē, vai noteiktas mantotā konveijera daļas darbojas platformās, kas to joprojām izmanto.

Tiek apkopoti tālāk norādītie lauki.

  - **DetachedDuration** — atvienošanas ilgums mikrosekundēs
