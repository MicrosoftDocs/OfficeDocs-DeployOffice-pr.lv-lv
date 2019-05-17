---
title: Office būtiskie pakalpojumi
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
description: Sniedz Office administratoriem informāciju par būtiskajiem pakalpojumiem sistēmā Office, piemēram, Click-to-Run un licencēšanu, kā arī nodrošina notikumu un datu lauku sarakstu šiem būtiskajiem pakalpojumiem.
hideEdit: true
ms.openlocfilehash: 31a0eb94d96e43eddb400670437b0d618eb5f30e
ms.sourcegitcommit: 9956e9e774e334a1894f1bb95e628eb71e0b5b2d
ms.translationtype: HT
ms.contentlocale: lv-LV
ms.lasthandoff: 05/02/2019
ms.locfileid: "33559222"
---
# <a name="essential-services-for-office"></a>Office būtiskie pakalpojumi

> [!IMPORTANT]
> Informācija šajā rakstā attiecas uz tālāk minētās Office klienta programmatūras versiju 1904 vai jaunāku versiju, kas instalēta datorā, kurā darbojas sistēma Windows:
> - Office 365 ProPlus un Office 365 Business
> - Office 365 individuālai lietošanai, Office 365 mājas lietošanai vai citas Office versijas, kas ir daļa no Office 365 abonementa.
> - Project un Visio, kas ir iekļautas dažos abonēšanas plānos, piemēram, Project Online Professional plānā vai Visio Online 2. plānā.


Office sastāv no klienta programmām un saistītajiem līdzekļiem, kas paredzēti, lai jūs varētu efektīvāk veidot, sazināties un sadarboties. Lai gan varat kontrolēt daudzas savienotās iespējas, kas ir pieejamas jums vai jūsu lietotājiem, ja esat savas organizācijas administrators, pastāv pakalpojumu kopa, kas ir būtiski attiecībā uz to, kā Office darbojas, tāpēc tos nevar atspējot. Piemēram, licencēšanas pakalpojums, kas apstiprina, vai esat pareizi licencēts Office izmantošanai. Nepieciešamie pakalpojumu dati par šiem pakalpojumiem tiek apkopoti un nosūtīti korporācijai Microsoft neatkarīgi no citiem politikas iestatījumiem, kas saistīti ar konfidencialitāti un kurus esat konfigurējis. Šos datus varat skatīt, izmantojot diagnostikas datu skatītāju.

Papildinformāciju skatiet šeit:

- [Office nepieciešamais datu pakalpojums](required-service-data.md)
- [Diagnostikas datu skatītāja izmantošana ar Office](https://support.office.com/article/cf761ce9-d805-4c60-a339-4e07f3182855)
- [Office saistītie līdzekļi](connected-experiences.md)

Ja esat organizācijas administrators, iespējams, jūs interesēs arī šie raksti:

- [Pārskats par konfidencialitātes kontroles līdzekļiem pakalpojumā Office 365 ProPlus](overview-privacy-controls.md)
- [Politikas iestatījumu izmantošana Office 365 ProPlus konfidencialitātes kontroles pārvaldībai](manage-privacy-controls.md)

## <a name="list-of-essential-services-for-office"></a>Office būtisko pakalpojumu saraksts 

Tālāk esošajā tabulā ir Office būtisko pakalpojumu saraksts, kā arī katra pakalpojuma apraksts.

| **Pakalpojums**  | **Apraksts**  |
| ------ | ---- |
| [Autentifikācija](#authentication-events) | Autentifikācija ir vairāku platformu pakalpojums, kas pārbauda jūsu Office lietotāja identitāti.  Tā ir nepieciešama, lai jums sniegtu iespēju pierakstīties sistēmā Office, aktivizēt jūsu Office licenci, piekļūtu jūsu mākonī saglabātajiem failiem, kā arī nodrošinātu konsekventu pieredzi vairākās Office sesijās un jūsu ierīcēs.    |
| [Click-to-Run](#click-to-run-events) | Click-to-Run ir instalēšanas tehnoloģija, kas tiek izmantota, lai instalētu un atjauninātu sistēmu Office operētājsistēmā Windows. Tā meklē jaunas Office versijas un, kad jauna versija ir pieejama, lejupielādē un instalē to. Click-to-Run noteiks Office atjauninājumu (tostarp drošības atjauninājumu) nepieciešamību, veiks to lejupielādi un instalēšanu.     |
| [Uzlabotās konfigurācijas pakalpojums (ECS)](#experimentation-and-configuration-service-ecs-events) | ECS nodrošina korporācijai Microsoft iespēju atkārtoti konfigurēt Office instalācijas tā, lai jums nebūtu atkārtoti jāizvieto Office. Tā tiek izmantota, lai kontrolētu pakāpenisko līdzekļu vai atjauninājumu ieviešanu, kamēr ieviešanas ietekme tiek pārraudzīta no diagnostikas datiem, kas tiek apkopoti. Tā arī tiek izmantota, lai mazinātu drošības vai veiktspējas problēmas ar līdzekli vai atjauninājumu. Turklāt ECS atbalsta konfigurācijas izmaiņas, kas saistītas ar diagnostikas datiem, lai nodrošinātu, ka tiek apkopoti atbilstošie notikumi. |
| [Licencēšana](#licensing-events)     | Licencēšana ir mākoņpakalpojums, kas atbalsta jūsu Office aktivizāciju jaunām instalācijām, kā arī uztur licenci jūsu ierīcēs pēc Office aktivizēšanas. Tā reģistrē katru jūsu ierīci un aktivizē Office, pārbauda jūsu Office abonementa statusu un pārvalda jūsu produktu atslēgas.    |
| [Pakalpojumu konfigurācija](#services-configuration-events)  | Pakalpojumu konfigurācija nodrošina iespēju veikt atjauninājumus Office konfigurācijas iestatījumos, lai iespējotu vai atspējotu klientu līdzekļus. Tā tiek izsaukta ikreiz, kad Office lietojumprogramma tiek startēta, un nodrošina detalizētu informāciju par citām Office konfigurācijām un pakalpojumiem. Pakalpojumu konfigurācija kontrolē arī to, kuri pakalpojumi ir paredzēti kā būtiskie pakalpojumi.  |
| [Telemetrijas dati ](#telemetry-events)  | Telemetrijas datu pakalpojums tiek izmantots, lai apkopotu diagnostikas datus no Office lietojumprogrammām. Tas nodrošina Office ģenerēto diagnostikas datu apkopošanu — gan obligāto, gan papildu diagnostikas datu. Tas ir arī atbildīgs par Office nepieciešamo pakalpojuma datu pakalpojuma diagnostikas datu daļas apkopošanu.  |

## <a name="events-and-data-fields-for-essential-services-for-office"></a>Office būtisko pakalpojumu notikumu un datu lauki

Nākamajās sadaļās ir sniegta tālāk norādītā informācija.

- Notikumu saraksts katram būtiskajam pakalpojumam
- Katra notikuma apraksts
- Datu lauku saraksts katrā notikumā
- Katra datu lauka apraksts

Šos notikumus varat skatīt, izmantojot diagnostikas datu skatītāju.



## <a name="authentication-events"></a>Autentifikācijas notikumi

Šie diagnostikas datu notikumi tiek apkopoti, kad Office mēģina iegūt autentifikācijas marķieri vai nu nemanāmi vai izmantojot uzvedni.

### <a name="officeidentityfbapromptwin32"></a>Office.Identity.FbaPromptWin32

Tiek apkopots, kad Office rāda lietotājam uz veidlapām balstītas pierakstīšanās uzvedni.

Kopā ar kluso pilnvaru iegūšanu autentifikācijas uzvednes tiek izmantotas, lai noteiktu, vai lietotājs ir bojātā autentifikācijas stāvoklī, kas lietotājam izraisa būtībā bezsaistes klienta stāvokli, vai sliktākajā gadījumā bojāta autentifikācija var traucēt licences iegūšanu, kā arī izraisīt pilnībā nelietojamu klientu.

Uz veidlapām balstītās autentifikācijas (FBA) pierakstīšanās uzvednes tiek izmantotas dažiem lokāliem autentifikācijas scenārijiem, un parasti mēs vēlamies nodrošināt, ka tā nenotiek, jo visiem vajadzētu lietot moderno autentifikāciju ar FBA saistīto drošības ievainojamību dēļ.

**Tiek apkopoti tālāk norādītie lauki.**

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

4.\) Šie signāli nodrošina dažādus nosūtīšanas gatavības un darbspējas pārraugus, kas aktivizē brīdinājumus,lai mūsu inženieri varētu ātri iesaistīties un samazināt laiku kritisko lietotāju bloķēšanas kļūmju mazināšanai

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

4.\) Šie signāli nodrošina dažādus nosūtīšanas gatavības un darbspējas pārraugus, kas aktivizē brīdinājumus,lai mūsu inženieri varētu ātri iesaistīties un samazināt laiku kritisko lietotāju bloķēšanas kļūmju mazināšanai.

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

4.\) Šie signāli nodrošina dažādus nosūtīšanas gatavības un darbspējas pārraugus, kas aktivizē brīdinājumus,lai mūsu inženieri varētu ātri iesaistīties un samazināt laiku kritisko kļūmju mazināšanai.

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

  - **Microsoft\_ADAL\_http\_event\_coun**t — HTTP izsaukumu skaits, ko veica ADAL.

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

  - **Microsoft\_ADAL\_x\_ms\_request\_id** — papildu pieprasījuma ID, ko HTTP galvenē pakalpojumam nodrošina ADAL.

  - **Platform** — Win32/WinRT/Android/iOS/Mac

  - **Scenarioid** — GUID. Vairāki notikumi var piederēt vienam scenārijam, piemēram, scenārijs var pievienot jaunu kontu, bet pastāv vairākas uzvednes, kas rodas kā daļa no šī scenārija. Šis ID nodrošina korelācijas iespējamību.

  - **Sessionid** — GUID, kas identificē sāknēšanas sesiju

  - **Skdver** — MATS klienta SDK versija, kas tiek izmantota, lai radītu šos datus

  - **Starttime** — laiks, kad Start\*Action MATS API tika izsaukts

  - **Tenantid** — GUID, kas identificē nomnieku, kam autentificētais lietotājs pieder (ar ADAL nesaistītos gadījumos).

  - **Uploadid** — unikālais GUID šim notikumam, tiek izmantots dublikātu likvidēšanai

  - **Wamapi** — norāda, kurš WAM API ir izsaukts

  - **Wamtelemetrybatch** — pašlaik netiek izmantots. Nākotnē sniedz WAM komponentam iespēju izsūtīt papildinformāciju par autentifikācijas notikumu.

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

  - **Data\_ProductReleaseId** — produkts, ko instalējam, t.i., Office 365 ProPlus

### <a name="officeclicktoruncorruptioncheck"></a>Office.ClickToRun.CorruptionCheck

Office iestatīšanas un krājumu dati, kas tiek apkopoti, kad Click-to-Run klients veic bojājumu pārbaudi, lai nodrošinātu, ka Office binārie faili ir pareizi. Tiek izmantots, lai mērītu Office bināro failu bojājumu un to, kuri binārie faili ir bojāti.

Tiek apkopoti tālāk norādītie lauki.

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

  - **Data\_FileBadDigestCount — **cik failus neizdevās atvērt

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

  - **Data\_MismatchSizeCount —** cik failu lielums neatbilst mūsu manifestam

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

  - **Data\_Sku** — instalētā SKU, t.i., Office 365 ProPlus.en-us

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

  - **Data\_ProductReleaseId —** produkts, ko instalējam, t.i., Office 365 ProPlus

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

  - **Data\_AddingProducts —** kādus produktus mums ir lūgts pievienot 

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

  - **Data\_AddingProducts —** kādus produktus mums ir lūgts pievienot 

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

  - **Data\_ProductsToRemove —** kādus Office produktus noņemam 

  - **Data\_RemovingFixedProducts —** produkti, ko noņemam 

  - **Data\_RemovingProducts —** produkti, kurus mums tiek lūgts noņemt 

  - **Data\_ScenarioInstanceID —** unikāls GUID darbības scenārijam 

  - **Data\_ScenarioName —** kāds scenārijs tiek izmantots. t.i., instalēšana 

  - **Data\_ScenarioSubType —** kāda veida scenāriju izmantojam, t.i., atinstalēšana, atkārtota instalēšana 

  - **Data\_SourceType —** kur ir mūsu avots, t.i., CDN 

  - **Data\_SqmMachineID —**  unikālais datora ID, ko izmanto Windows SQM 

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

  - **Data\_AddingProducts —** kādus produktus mums ir lūgts pievienot 

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

  - **Data\_ProductsToRemove —**  kādus Office produktus noņemam 

  - **Data\_RemovingFixedProducts —** produkti, ko noņemam 

  - **Data\_RemovingProducts —** produkti, kurus mums tiek lūgts noņemt 

  - **Data\_ScenarioInstanceID —** unikāls GUID darbības scenārijam 

  - **Data\_ScenarioName —** kāds scenārijs tiek izmantots. t.i., instalēšana 

  - **Data\_ScenarioSubType —** kāda veida scenāriju izmantojam, t.i., atinstalēšana, atkārtota instalēšana 

  - **Data\_SourceType —** kur ir mūsu avots, t.i., CDN 

  - **Data\_SqmMachineID —** unikālais datora ID, ko izmanto Windows SQM 

  - **Data\_SusClientID —** datora Office atjaunināšanas identifikators 

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

  - **Data\_AddingProducts —** kādus produktus mums ir lūgts pievienot 

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

  - **Data\_ProductsToRemove —** kādus Office produktus noņemam 

  - **Data\_RemovingFixedProducts —** produkti, ko noņemam 

  - **Data\_RemovingProducts —** produkti, kurus mums tiek lūgts noņemt 

  - **Data\_ScenarioInstanceID —** unikāls GUID darbības scenārijam 

  - **Data\_ScenarioName —** kāds scenārijs tiek izmantots. t.i., instalēšana

  - **Data\_ScenarioSubType —** kāda veida scenāriju izmantojam, t.i., atinstalēšana, atkārtota instalēšana 

  - **Data\_SourceType —** kur ir mūsu avots, t.i., CDN 

  - **Data\_SqmMachineID —**  unikālais datora ID, ko izmanto Windows SQM 

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

  - **Data\_AddingProducts —** kādus produktus mums ir lūgts pievienot 

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

  - **Data\_ProductsToRemove —** kādus Office produktus noņemam 

  - **Data\_RemovingFixedProducts —** produkti, ko noņemam 

  - **Data\_RemovingProducts —** produkti, kurus mums tiek lūgts noņemt 

  - **Data\_ScenarioInstanceID —** unikāls GUID darbības scenārijam 

  - **Data\_ScenarioName —** kāds scenārijs tiek izmantots. t.i., instalēšana

  - **Data\_ScenarioSubType —** kāda veida scenāriju izmantojam, t.i., atinstalēšana, atkārtota instalēšana 

  - **Data\_SourceType —** kur ir mūsu avots, t.i., CDN 

  - **Data\_SqmMachineID —**  unikālais datora ID, ko izmanto Windows SQM 

  - **Data\_SusClientID —** datora Office atjaunināšanas identifikators 

  - **Data\_TaskState —** kādā stāvoklī ir uzdevums, piemēram, darbojas vai atcelts 

  - **Data\_TotalClientCabSize —** mūsu klienta kabinetfaila lielums 

  - **Data\_TriggeringUI —** kas aktivizēja UI 

  - **Data\_UpdatesEnabled —** ja Office atjauninājumi ir iespējoti 

  - **Data\_Version —** Office versija 

### <a name="officeclicktorunscenarioinstalltaskintegrateinstall"></a>Office.ClickToRun.Scenario.InstallTaskIntegrateinstall

Office iestatīšanas un krājumu dati, kas tiek apkopoti, kad Office instalētājs veido reģistra ierakstus Office lietojumprogrammām. Tiek izmantots, lai mērītu Office instalācijas sekmīgu/kļūdainu darbību.

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

  - **Data\_AddingProducts —** kādus produktus mums ir lūgts pievienot 

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

  - **Data\_ProductsToRemove —** kādus Office produktus noņemam 

  - **Data\_RemovingFixedProducts —** produkti, ko noņemam 

  - **Data\_RemovingProducts —** produkti, kurus mums tiek lūgts noņemt 

  - **Data\_ScenarioInstanceID —** unikāls GUID darbības scenārijam 

  - **Data\_ScenarioName —** kāds scenārijs tiek izmantots. t.i., instalēšana 

  - **Data\_ScenarioSubType —** kāda veida scenāriju izmantojam, t.i., atinstalēšana, atkārtota instalēšana 

  - **Data\_SourceType —** kur ir mūsu avots, t.i., CDN 

  - **Data\_SqmMachineID —** unikālais datora ID, ko izmanto Windows SQM

  - **Data\_SusClientID —** datora Office atjaunināšanas identifikators 

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

  - **Data\_AddingProducts —** kādus produktus mums ir lūgts pievienot 

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

  - **Data\_ProductsToRemove —**  kādus Office produktus noņemam 

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

  - **Data\_AddingProducts —** kādus produktus mums ir lūgts pievienot 

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

  - **Data\_ProductsToRemove —** kādus Office produktus noņemam 

  - **Data\_RemovingFixedProducts —** produkti, ko noņemam 

  - **Data\_RemovingProducts —** produkti, kurus mums tiek lūgts noņemt 

  - **Data\_ScenarioInstanceID —** unikāls GUID darbības scenārijam 

  - **Data\_ScenarioName —** kāds scenārijs tiek izmantots. t.i., instalēšana

  - **Data\_ScenarioSubType —** kāda veida scenāriju izmantojam, t.i., atinstalēšana, atkārtota instalēšana 

  - **Data\_SourceType —** kur ir mūsu avots, t.i., CDN 

  - **Data\_SqmMachineID —** unikālais datora ID, ko izmanto Windows SQM

  - **Data\_SusClientID —**  datora Office atjaunināšanas identifikators

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

  - **Data\_AddingProducts —** kādus produktus mums ir lūgts pievienot 

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

  - **Data\_ProductsToRemove —** kādus Office produktus noņemam 

  - **Data\_RemovingFixedProducts —** produkti, ko noņemam 

  - **Data\_RemovingProducts —** produkti, kurus mums tiek lūgts noņemt 

  - **Data\_ScenarioInstanceID —** unikāls GUID darbības scenārijam 

  - **Data\_ScenarioName —** kāds scenārijs tiek izmantots, t.i., instalēšana 

  - **Data\_ScenarioSubType —** kāda veida scenāriju izmantojam, t.i., atinstalēšana, atkārtota instalēšana 

  - **Data\_SourceType —** kur ir mūsu avots, t.i., CDN 

  - **Data\_SqmMachineID —** unikālais datora ID, ko izmanto Windows SQM

  - **Data\_SusClientID —** datora Office atjaunināšanas identifikators 

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

  - **Data\_15\_UpdateVersion —**  uz kādu Office 15 versiju veicam atjaunināšanu 

  - **Data\_15\_Version —** Office 15 versija 

  - **Data\_16\_SourceType —** kur Office 16 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_16\_UpdatesEnabled —** ja Office 16 atjauninājumi ir iespējoti 

  - **Data\_16\_UpdateVersion —** uz kādu Office 16 versiju veicam atjaunināšanu 

  - **Data\_16\_Version —** Office 16 versija 

  - **Data\_AddingFixedProducts —** produkti, ko pievienojam 

  - **Data\_AddingProducts —** kādus produktus mums ir lūgts pievienot 

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

  - **Data\_ProductsToRemove —** kādus Office produktus noņemam 

  - **Data\_RemovingFixedProducts —** produkti, ko noņemam 

  - **Data\_RemovingProducts —** produkti, kurus mums tiek lūgts noņemt 

  - **Data\_ScenarioInstanceID —** unikāls GUID darbības scenārijam 

  - **Data\_ScenarioName —** kāds scenārijs tiek izmantots. t.i., instalēšana 

  - **Data\_ScenarioSubType —** kāda veida scenāriju izmantojam, t.i., atinstalēšana, atkārtota instalēšana 

  - **Data\_SourceType —** kur ir mūsu avots, t.i., CDN 

  - **Data\_SqmMachineID —** unikālais datora ID, ko izmanto Windows SQM

  - **Data\_SusClientID —** datora Office atjaunināšanas identifikators 

  - **Data\_TaskState —** kādā stāvoklī ir uzdevums, piemēram, darbojas vai atcelts 

  - **Data\_TotalClientCabSize —** mūsu klienta kabinetfaila lielums 

  - **Data\_TriggeringUI —** kas aktivizēja UI 

  - **Data\_UpdatesEnabled —** ja Office atjauninājumi ir iespējoti 

  - **Data\_Version —** Office versija 

### <a name="officeclicktorunscenarioinstalltaskstream"></a>Office.ClickToRun.Scenario.InstallTaskStream

Office iestatīšanas un krājumu dati, kas tiek apkopoti, kad Office instalētājs lejupielādē jaunus Office failus. Tiek izmantots, lai mērītu Office instalācijas sekmīgu/kļūdainu darbību.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_15\_SourceType —** kur Office 15 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_15\_UpdatesEnabled —** ja Office 15 atjauninājumi ir iespējoti 

  - **Data\_15\_UpdateVersion —**  uz kādu Office 15 versiju veicam atjaunināšanu 

  - **Data\_15\_Version —** Office 15 versija 

  - **Data\_16\_SourceType —** kur Office 16 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_16\_UpdatesEnabled —** ja Office 16 atjauninājumi ir iespējoti 

  - **Data\_16\_UpdateVersion —** uz kādu Office 16 versiju veicam atjaunināšanu 

  - **Data\_16\_Version —** Office 16 versija 

  - **Data\_AddingFixedProducts —** produkti, ko pievienojam 

  - **Data\_AddingProducts —** kādus produktus mums ir lūgts pievienot 

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

  - **Data\_ProductsToRemove —**  kādus Office produktus noņemam 

  - **Data\_RemovingFixedProducts —** produkti, ko noņemam 

  - **Data\_RemovingProducts —** produkti, kurus mums tiek lūgts noņemt 

  - **Data\_ScenarioInstanceID —** unikāls GUID darbības scenārijam 

  - **Data\_ScenarioName —** kāds scenārijs tiek izmantots. t.i., instalēšana 

  - **Data\_ScenarioSubType —** kāda veida scenāriju izmantojam, t.i., atinstalēšana, atkārtota instalēšana 

  - **Data\_SourceType —** kur ir mūsu avots, t.i., CDN 

  - **Data\_SqmMachineID —**  unikālais datora ID, ko izmanto Windows SQM 

  - **Data\_SusClientID —**  datora Office atjaunināšanas identifikators 

  - **Data\_TaskState —** kādā stāvoklī ir uzdevums, piemēram, darbojas vai atcelts 

  - **Data\_TotalClientCabSize —** mūsu klienta kabinetfaila lielums 

  - **Data\_TriggeringUI —** kas aktivizēja UI 

  - **Data\_UpdatesEnabled —** ja Office atjauninājumi ir iespējoti 

  - **Data\_Version —** Office versija 

### <a name="officeclicktorunscenarioinstalltaskuninstallcentennial"></a>Office.ClickToRun.Scenario.InstallTaskUninstallcentennial

Office iestatīšanas un krājumu dati, kas tiek apkopoti, kad Office instalētājs atinstalē iepriekšēju Office versiju, kas instalēta no Store. Tiek izmantots, lai mērītu Office instalācijas sekmīgu/kļūdainu darbību.

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

  - **Data\_AddingProducts —** kādus produktus mums ir lūgts pievienot 

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

  - **Data\_ProductsToRemove —** kādus Office produktus noņemam 

  - **Data\_RemovingFixedProducts —** produkti, ko noņemam 

  - **Data\_RemovingProducts —** produkti, kurus mums tiek lūgts noņemt 

  - **Data\_ScenarioInstanceID —** unikāls GUID darbības scenārijam 

  - **Data\_ScenarioName —** kāds scenārijs tiek izmantots. t.i., instalēšana 

  - **Data\_ScenarioSubType —** kāda veida scenāriju izmantojam, t.i., atinstalēšana, atkārtota instalēšana 

  - **Data\_SourceType —** kur ir mūsu avots, t.i., CDN 

  - **Data\_SqmMachineID —**  unikālais datora ID, ko izmanto Windows SQM

  - **Data\_SusClientID —** datora Office atjaunināšanas identifikators 

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

  - **Data\_15\_UpdateVersion —**  uz kādu Office 15 versiju veicam atjaunināšanu 

  - **Data\_15\_Version —** Office 15 versija 

  - **Data\_16\_SourceType —** kur Office 16 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_16\_UpdatesEnabled —** ja Office 16 atjauninājumi ir iespējoti 

  - **Data\_16\_UpdateVersion —** uz kādu Office 16 versiju veicam atjaunināšanu 

  - **Data\_16\_Version —** Office 16 versija 

  - **Data\_AddingFixedProducts —** produkti, ko pievienojam 

  - **Data\_AddingProducts —** kādus produktus mums ir lūgts pievienot 

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

  - **Data\_ProductsToRemove —** kādus Office produktus noņemam 

  - **Data\_RemovingFixedProducts —** produkti, ko noņemam 

  - **Data\_RemovingProducts —** produkti, kurus mums tiek lūgts noņemt 

  - **Data\_ScenarioInstanceID —** unikāls GUID darbības scenārijam 

  - **Data\_ScenarioName —** kāds scenārijs tiek izmantots. t.i., instalēšana 

  - **Data\_ScenarioSubType —** kāda veida scenāriju izmantojam, t.i., atinstalēšana, atkārtota instalēšana 

  - **Data\_SourceType —** kur ir mūsu avots, t.i., CDN 

  - **Data\_SqmMachineID —**  unikālais datora ID, ko izmanto Windows SQM 

  - **Data\_SusClientID —** datora Office atjaunināšanas identifikators 

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

  - **Data\_AddingProducts —** kādus produktus mums ir lūgts pievienot 

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

  - **Data\_ProductsToRemove —** kādus Office produktus noņemam 

  - **Data\_RemovingFixedProducts —** produkti, ko noņemam 

  - **Data\_RemovingProducts —** produkti, kurus mums tiek lūgts noņemt 

  - **Data\_ScenarioInstanceID —** unikāls GUID darbības scenārijam 

  - **Data\_ScenarioName —** kāds scenārijs tiek izmantots. t.i., instalēšana 

  - **Data\_ScenarioSubType —** kāda veida scenāriju izmantojam, t.i., atinstalēšana, atkārtota instalēšana 

  - **Data\_SourceType —** kur ir mūsu avots, t.i., CDN 

  - **Data\_SqmMachineID —**  unikālais datora ID, ko izmanto Windows SQM 

  - **Data\_SusClientID —** datora Office atjaunināšanas identifikators 

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

  - **Data\_AddingProducts —** kādus produktus mums ir lūgts pievienot 

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

  - **Data\_ProductsToRemove —** kādus Office produktus noņemam 

  - **Data\_RemovingFixedProducts —** produkti, ko noņemam 

  - **Data\_RemovingProducts —** produkti, kurus mums tiek lūgts noņemt 

  - **Data\_ScenarioInstanceID —** unikāls GUID darbības scenārijam 

  - **Data\_ScenarioName —** kāds scenārijs tiek izmantots. t.i., instalēšana 

  - **Data\_ScenarioSubType —** kāda veida scenāriju izmantojam, t.i., atinstalēšana, atkārtota instalēšana 

  - **Data\_SourceType —** kur ir mūsu avots, t.i., CDN 

  - **Data\_SqmMachineID —**  unikālais datora ID, ko izmanto Windows SQM 

  - **Data\_SusClientID —** datora Office atjaunināšanas identifikators 

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

  - **Data\_AddingProducts —** kādus produktus mums ir lūgts pievienot 

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

  - **Data\_ProductsToRemove —**  kādus Office produktus noņemam 

  - **Data\_RemovingFixedProducts —** produkti, ko noņemam 

  - **Data\_RemovingProducts —** produkti, kurus mums tiek lūgts noņemt 

  - **Data\_ScenarioInstanceID —** unikāls GUID darbības scenārijam 

  - **Data\_ScenarioName —** kāds scenārijs tiek izmantots. t.i., instalēšana 

  - **Data\_ScenarioSubType —** kāda veida scenāriju izmantojam, t.i., atinstalēšana, atkārtota instalēšana 

  - **Data\_SourceType —** kur ir mūsu avots, t.i., CDN 

  - **Data\_SqmMachineID —**  unikālais datora ID, ko izmanto Windows SQM 

  - **Data\_SusClientID —** datora Office atjaunināšanas identifikators 

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

  - **Data\_AddingProducts —** kādus produktus mums ir lūgts pievienot 

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

  - **Data\_ProductsToRemove —** kādus Office produktus noņemam 

  - **Data\_RemovingFixedProducts —** produkti, ko noņemam 

  - **Data\_RemovingProducts —** produkti, kurus mums tiek lūgts noņemt 

  - **Data\_ScenarioInstanceID —** unikāls GUID darbības scenārijam 

  - **Data\_ScenarioName —** kāds scenārijs tiek izmantots. t.i., instalēšana 

  - **Data\_ScenarioSubType —** kāda veida scenāriju izmantojam, t.i., atinstalēšana, atkārtota instalēšana 

  - **Data\_SourceType —** kur ir mūsu avots, t.i., CDN 

  - **Data\_SqmMachineID —**  unikālais datora ID, ko izmanto Windows SQM 

  - **Data\_SusClientID —** datora Office atjaunināšanas identifikators 

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

  - **Data\_AddingProducts —** kādus produktus mums ir lūgts pievienot 

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

  - **Data\_ProductsToRemove —** kādus Office produktus noņemam 

  - **Data\_RemovingFixedProducts —** produkti, ko noņemam 

  - **Data\_RemovingProducts —** produkti, kurus mums tiek lūgts noņemt 

  - **Data\_ScenarioInstanceID —** unikāls GUID darbības scenārijam 

  - **Data\_ScenarioName —** kāds scenārijs tiek izmantots. t.i., instalēšana 

  - **Data\_ScenarioSubType —** kāda veida scenāriju izmantojam, t.i., atinstalēšana, atkārtota instalēšana 

  - **Data\_SourceType —** kur ir mūsu avots, t.i., CDN 

  - **Data\_SqmMachineID —**  unikālais datora ID, ko izmanto Windows SQM 

  - **Data\_SusClientID —** datora Office atjaunināšanas identifikators 

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

  - **Data\_AddingProducts —** kādus produktus mums ir lūgts pievienot 

  - **Data\_AvailableVersion to —** kāda Office versija ir pieejama atjaunināšanai

  - **Data\_CompletedWithoutActionInfo —** kāpēc nepabeidzām scenāriju, t.i., lietojumprogrammas bija atvērtas

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

  - **Data\_ProductsToRemove —** kādus Office produktus noņemam 

  - **Data\_RemovingFixedProducts —** produkti, ko noņemam 

  - **Data\_RemovingProducts —** produkti, kurus mums tiek lūgts noņemt 

  - **Data\_ScenarioInstanceID —** unikāls GUID darbības scenārijam 

  - **Data\_ScenarioName —** kāds scenārijs tiek izmantots. t.i., instalēšana 

  - **Data\_ScenarioSubType —** kāda veida scenāriju izmantojam, t.i., atinstalēšana, atkārtota instalēšana 

  - **Data\_SourceType —** kur ir mūsu avots, t.i., CDN 

  - **Data\_SqmMachineID —**  unikālais datora ID, ko izmanto Windows SQM

  - **Data\_SusClientID —**  datora Office atjaunināšanas identifikators 

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

  - **Data\_AddingProducts —** kādus produktus mums ir lūgts pievienot 

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

  - **Data\_ProductsToRemove —** kādus Office produktus noņemam 

  - **Data\_RemovingFixedProducts —** produkti, ko noņemam 

  - **Data\_RemovingProducts —** produkti, kurus mums tiek lūgts noņemt 

  - **Data\_ScenarioInstanceID —** unikāls GUID darbības scenārijam 

  - **Data\_ScenarioName —** kāds scenārijs tiek izmantots. t.i., instalēšana 

  - **Data\_ScenarioSubType —** kāda veida scenāriju izmantojam, t.i., atinstalēšana, atkārtota instalēšana 

  - **Data\_SourceType —** kur ir mūsu avots, t.i., CDN 

  - **Data\_SqmMachineID —** unikālais datora ID, ko izmanto Windows SQM

  - **Data\_SusClientID —** datora Office atjaunināšanas identifikators 

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

  - **Data\_AddingProducts —** kādus produktus mums ir lūgts pievienot 

  - **Data\_AvailableVersion —** uz kādu Office versiju ir pieejams atjauninājums

  - **Data\_ComAction —** int, kas atspoguļo com darbību, ko veicam

  - **Data\_CompletedWithoutActionInfo —** kāpēc nepabeidzām scenāriju, t.i., lietojumprogrammas bija atvērtas

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

  - **Data\_ProductsToRemove —**  kādus Office produktus noņemam 

  - **Data\_RemovingFixedProducts —** produkti, ko noņemam 

  - **Data\_RemovingProducts —** produkti, kurus mums tiek lūgts noņemt 

  - **Data\_ScenarioInstanceID —** unikāls GUID darbības scenārijam 

  - **Data\_ScenarioName —** kāds scenārijs tiek izmantots. t.i., instalēšana

  - **Data\_ScenarioSubType —** kāda veida scenāriju izmantojam, t.i., atinstalēšana, atkārtota instalēšana 

  - **Data\_SourceType —** kur ir mūsu avots, t.i., CDN 

  - **Data\_SqmMachineID —**  unikālais datora ID, ko izmanto Windows SQM 

  - **Data\_SusClientID —**  datora Office atjaunināšanas identifikators 

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

  - **Data\_15\_UpdateVersion —**  uz kādu Office 15 versiju veicam atjaunināšanu 

  - **Data\_15\_Version —** Office 15 versija 

  - **Data\_16\_SourceType —** kur Office 16 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_16\_UpdatesEnabled —** ja Office 16 atjauninājumi ir iespējoti 

  - **Data\_16\_UpdateVersion —** uz kādu Office 16 versiju veicam atjaunināšanu 

  - **Data\_16\_Version —** Office 16 versija 

  - **Data\_AddingFixedProducts —** produkti, ko pievienojam 

  - **Data\_AddingProducts —** kādus produktus mums ir lūgts pievienot 

  - **Data\_AvailableVersion —** uz kādu Office versiju ir pieejams atjauninājums

  - **Data\_CompletedWithoutActionInfo —** kāpēc nepabeidzām scenāriju, t.i., lietojumprogrammas bija atvērtas

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

  - **Data\_ProductsToRemove —** kādus Office produktus noņemam 

  - **Data\_RemovingFixedProducts —** produkti, ko noņemam 

  - **Data\_RemovingProducts —** produkti, kurus mums tiek lūgts noņemt 

  - **Data\_ScenarioInstanceID —** unikāls GUID darbības scenārijam 

  - **Data\_ScenarioName —** kāds scenārijs tiek izmantots. t.i., instalēšana 

  - **Data\_ScenarioSubType —** kāda veida scenāriju izmantojam, t.i., atinstalēšana, atkārtota instalēšana 

  - **Data\_SourceType —** kur ir mūsu avots, t.i., CDN 

  - **Data\_SqmMachineID —** unikālais datora ID, ko izmanto Windows SQM 

  - **Data\_SusClientID —** datora Office atjaunināšanas identifikators 

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

  - **Data\_15\_UpdateVersion —**  uz kādu Office 15 versiju veicam atjaunināšanu 

  - **Data\_15\_Version —** Office 15 versija 

  - **Data\_16\_SourceType —** kur Office 16 avots atrodas, t.i., CDN vai lokāls 

  - **Data\_16\_UpdatesEnabled —** ja Office 16 atjauninājumi ir iespējoti 

  - **Data\_16\_UpdateVersion —** uz kādu Office 16 versiju veicam atjaunināšanu 

  - **Data\_16\_Version —** Office 16 versija 

  - **Data\_AddingFixedProducts —** produkti, ko pievienojam 

  - **Data\_AddingProducts —** kādus produktus mums ir lūgts pievienot 

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

  - **Data\_ProductsToRemove —** kādus Office produktus noņemam 

  - **Data\_RemovingFixedProducts —** produkti, ko noņemam 

  - **Data\_RemovingProducts —** produkti, kurus mums tiek lūgts noņemt 

  - **Data\_ScenarioInstanceID —** unikāls GUID darbības scenārijam 

  - **Data\_ScenarioName —** kāds scenārijs tiek izmantots. t.i., instalēšana 

  - **Data\_ScenarioSubType —** kāda veida scenāriju izmantojam, t.i., atinstalēšana, atkārtota instalēšana 

  - **Data\_SourceType —** kur ir mūsu avots, t.i., CDN 

  - **Data\_SqmMachineID —**  unikālais datora ID, ko izmanto Windows SQM 

  - **Data\_SusClientID —**  datora Office atjaunināšanas identifikators 

  - **Data\_TaskState —** kādā stāvoklī ir uzdevums, piemēram, darbojas vai atcelts 

  - **Data\_TotalClientCabSize —** mūsu klienta kabinetfaila lielums 

  - **Data\_TriggeringUI —** kas aktivizēja UI 

  - **Data\_UpdatesEnabled —** ja Office atjauninājumi ir iespējoti 

  - **Data\_Version —** Office versija 

### <a name="officeclicktoruntransportexperimentaltransportpipelinecreatetransport"></a>Office.ClickToRun.Transport.ExperimentalTransport.PipelineCreateTransport

Office iestatīšanas un krājumu dati, kas tiek apkopoti, kad Click-to-Run klients veido transportēšanas straumi, lai lejupielādētu Office failus. Tiek izmantoti, lai noteiktu dažādu transportēšanas tehnoloģiju (piemēram, HTTP, BITS, DO) darbspēju, kas ir kritiski svarīgi, lai pareizi lejupielādētu Office instalēšanai un atjauninājumiem.

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_IsForeGroundStreaming**  — vai straumējam priekšplānā vai fonā

  - **Data\_IsInstallMode** — 1 — ja instalējam un lejupielādējam failus, 0 — ja to nedarām

  - **Data\_SourceProtocol —** ja veicam lejupielādi no satura datu tīkla, CDN, datora, kurā veicam instalēšanu, lokāli vai resursa lokālajā tīklā,

  - **Data\_Status**  — sekmīga izpilde vai kļūme 

### <a name="officeclicktorunupdatestatus"></a>Office.ClickToRun.UpdateStatus

Office iestatīšanas un krājumu dati, kas tiek apkopoti, kad Click-to-Run klients pabeidz atjaunināšanas statusu

Tiek apkopoti tālāk norādītie lauki.

  - **Data\_build** — pašlaik instalētā Office versija

  - **Data\_channel** — kanāls, kurā lietotājs atrodas

  - **Data\_errorCode** — vesela skaitļa kods, kas norāda, kāda veida kļūda radās, ja tāda radās

  - **Data\_errorMessage** — virkne, kas nodrošina radušās kļūdas aprakstu, ja tāda radās

  - **Data\_status** — īss statuss par to, kas notika atjaunināšanas laikā, piemēram, Izdevās vai Lejupielādēts

  - **Data\_targetBuild —** Office versija, uz kuru mēģinām veikt atjaunināšanu


## <a name="experimentation-and-configuration-service-ecs-events"></a>Eksperimentēšanas un konfigurēšanas pakalpojuma (ECS) notikumi

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


## <a name="licensing-events"></a>Licencēšanas notikumi

### <a name="officelicensingaccepteulaforcurrentlicense"></a>Office.Licensing.AcceptEulaForCurrentLicense 

Tas tiek apkopots, kad lietotājs tiek licencēts un akceptē EULA pašreizējai licencei

Tas tiek izmantots, lai noteiktu, vai lietotājs ir piemērotā stāvoklī, kas tiek izmantota sistēmas darbspējai un diagnostikas mērķiem, ja lietotājs ziņo par problēmu savā datorā

Tiek apkopoti tālāk norādītie lauki.

  - **ACID** — GUID identifikators, kas norāda Office produktu, kuram lietotājam ir licence

  - **DwEulaId** — EULA tipa, ko tikko akceptēja lietotājs, skaitliskais identifikators

### <a name="officelicensingactivation"></a>Office.Licensing.Activation 

Pēc licences iestatīšanas datorā mēs mēģinām aktivizēt licenci, izsaucot AVS pakalpojumu. Tādējādi tiek norādīts aktivizācijas izsaukuma rezultāts

Tas ir kritiski svarīgi, lai noteiktu, cik lietotājiem rodas aktivizācijas problēmas. Lai konstatētu regresiju, izmantojam anomāliju noteikšanu. Tas ir ārkārtīgi svarīgi, jo mums ir ārēja atkarība no AVS, un šis signāls norāda, vai mūsu ārējie partneri ir darbspējīgi. Tas tiek izmantots arī diagnostikas mērķiem un sistēmas darbspējai, ja lietotājs ziņo par problēmu ar savu datoru

Tiek apkopoti tālāk norādītie lauki.

  - **Acid** — GUID identifikators, kas norāda Office produktu, kuram lietotājam ir licence

  - **ReferralData** — OEM, kas datorā instalēja sistēmu Office, identifikators

### <a name="officelicensingactivationwizard"></a>Office.Licensing.ActivationWizard 

Ja kāda iemesla dēļ nevaram automātiski aktivizēt licenci, lietotājam tiek rādīts aktivizācijas vednis. Tas norāda, ka lietotājam tiek rādīts vednis. Tas ir kritiski svarīgs, lai noteiktu, vai lietotājs ir piemērotā stāvoklī un vai tam netrūkst funkcionalitātes, kas tiek izmantota sistēmas darbspējai un diagnostikas mērķiem, ja lietotājs ziņo par problēmu savā datorā

Šis notikums neapkopo laukus.

### <a name="officelicensingenforcesigninqualified"></a>Office.Licensing.EnforceSignInQualified 

Šis signāls norāda, vai eksperiments, ko veicam, lai uzspiestu lietotāja parakstu kā daļu no licencēšanas, ir sekmīgs. Tas ir kritiski svarīgi, lai noteiktu eksperimenta, kas liek lietotājiem pieteikties un kas ir obligāts solis modernajam licencēšanas stekam, izdošanos vai neizdošanos. Ja neizdodas pierakstīties, lietotāji nevar izmantot programmu.

Tiek apkopoti tālāk norādītie lauki.

  - **Qualified** — norāda, vai lietotājs kvalificējās pierakstīšanās uzspiešanai

### <a name="officelicensingexpirationdialogshown"></a>Office.Licensing.ExpirationDialogShown

Tas tiek apkopots, kad lietotājam rādām derīguma beigu dialogu, kurā norādīts, ka lietotāja licencei ir beidzies derīgums. Tas ir kritiski svarīgs, lai noteiktu, vai lietotājs ir piemērotā stāvoklī un vai tam netrūkst funkcionalitātes, kas tiek izmantota sistēmas darbspējai un diagnostikas mērķiem, ja lietotājs ziņo par problēmu savā datorā.

Tiek apkopoti tālāk norādītie lauki.

  - **LicNotificationState** — skaitītājs, kas mums norāda, kāda veida paziņojums tiek rādīts lietotājam

### <a name="officelicensingfullvalidation"></a>Office.Licensing.FullValidation 

Tas tiek apkopots katrā sesijā, kas ziņo datora licencēšanas stāvokli un kļūdas, kas lietotājam rodas un kuru dēļ tas nevar izmantot lietojumprogrammu. Šis notikums norāda, vai lietotāja dators ir darbspējīgs. Esam iestatījuši anomāliju noteikšanu šim notikumam, lai norādītu, vai regresija izraisa neatbilstošo lietotāju uzvedību. Tas ir arī kritiski svarīgi, kad tiek diagnosticētas lietotāja problēmas, kā arī sistēmas darbspējas pārraudzībai

Tiek apkopoti tālāk norādītie lauki.

  - **Acid** — GUID identifikators, kas norāda Office produktu, kuram lietotājam ir licence 

  - **IsSessionLicensing** — vai pašlaik strādājam koplietojamā datora aktivizācijas režīmā 

  - **LicenseCategory** — lietotāja izmantotās Office licences kategorija 

  - **Licenses** — visu datorā esošo Office licenču nosaukumu saraksts 

  - **LicenseStatuses** — visu datorā esošo Office licenču statuss 

### <a name="officelicensinggetentitlement"></a>Office.Licensing.GetEntitlement 

Mēs to apkopojam, kad lietotājs iestata ierīci un mēs izsaucam mūsu licencēšanas pakalpojumu, lai noteiktu, vai lietotājam, kas ir pieteicies, ir Office tiesības. Tādējādi tiek norādīts attiecīgā izsaukuma rezultāts Tas ir kritiski svarīgs, lai noteiktu, vai lietotājs ir piemērotā stāvoklī un vai tam trūkst funkcionalitātes, kas tiek izmantota sistēmas darbspējai un diagnostikas mērķiem, ja lietotājs ziņo par problēmu savā datorā

Šis notikums neapkopo laukus.

### <a name="officelicensingheartbeat"></a>Office.Licensing.Heartbeat 

Katrā sesijā pārbaudām, vai ir pagājušas 72 stundas kopš pēdējās licences atjaunošanas, un mēģinām pagarināt pašreizējās licences derīguma termiņu. Šis notikums ziņo par izsaukuma, ko veicam, lai nodrošinātu, ka varam pagarināt licences derīguma termiņu un uzturēt lietotāja Office instalācijas funkcionalitāti, sekmīgu izpildi vai kļūmi. Tas ir kritiski svarīgi, lai diagnosticētu ar abonementu saistītas problēmas un pakalpojumu problēmas lietotājam, kā arī ir kritiski svarīgi, lai noteiktu regresiju jau aktivizēto abonementu lietotājiem.

Tiek apkopoti tālāk norādītie lauki.

  - **Mode** — šajā datorā izmantotā Office licencēšanas steka skaitītāja attēlojums

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

Ja rodas problēmas ar aktivizācijas darbplūsmu, mēs aktivizējam licences vedni un izsūtām šo signālu, lai norādītu to pašu. Tas ir kritiski svarīgi, lai noteiktu, vai lietotājs ir piemērotā stāvoklī un vai tam netrūkst funkcionalitātes, kas tiek izmantota sistēmas darbspējai un diagnostikas mērķiem, ja lietotājs ziņo par problēmu savā datorā.

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

Ja sistēmas Office darbība tiek beigta/tā avarē licencēšanas kļūdas dēļ, mēs izsūtām šo signālu, lai norādītu to pašu. Tas ir kritiski svarīgs, lai noteiktu, vai lietotājs ir piemērotā stāvoklī un vai tam netrūkst funkcionalitātes, kas tiek izmantota sistēmas darbspējai un diagnostikas mērķiem, ja lietotājs ziņo par problēmu savā datorā.

Tiek apkopoti tālāk norādītie lauki.

  - **ExitCode** — iekšējais kods, kas izraisīja lietojumprogrammas izeju

### <a name="officelicensingloadidentityticket"></a>Office.Licensing.LoadIdentityTicket

Mēģinot ierīci licencēt, lietojumprogramma mēģina ielādēt lietotāja identitāti, lai noskaidrotu, vai lietotājam ir Office tiesības. Šis notikums ziņo par tā paša procesa sekmīgu izpildi vai kļūmi kopā ar kļūdas kodu. Tas ir kritiski svarīgi, lai noteiktu, vai lietotājs ir piemērotā stāvoklī un vai tam netrūkst funkcionalitātes, kas tiek izmantota sistēmas darbspējai un diagnostikas mērķiem, ja lietotājs ziņo par problēmu savā datorā.

Tiek apkopoti tālāk norādītie lauki.

  - **FederationProvider** — virkne, kas norāda federācijas nodrošinātāju lietotājam, kurš pašlaik ir pieteicies

  - **IdentityProvider** — virkne, kas norāda identitātes nodrošinātāju lietotājam, kurš pašlaik ir pieteicies

### <a name="officelicensinglvuxeulaexplicitcrash"></a>Office.Licensing.LVUX.EULAExplicitCrash 

Tas tiek apkopots, ja lietotājam tika rādīts EULA un lietotājs izvēlējās to neakceptēt, līdz ar to lietojumprogramma avarē/tiek aizvērta. Tas ir kritiski svarīgs, lai noteiktu, vai lietotājs ir piemērotā stāvoklī un vai tam netrūkst funkcionalitātes, kas tiek izmantota sistēmas darbspējai un diagnostikas mērķiem, ja lietotājs ziņo par problēmu savā datorā.

Tiek apkopoti tālāk norādītie lauki.

  - **Acid** — GUID identifikators, kas norāda Office produktu, kuram lietotājam ir licence

  - **OptInShown** — norāda, vai piekrišanas dialogs, kas tiek rādīts lietojumprogrammas pirmajā sāknēšanas reizē, jau ir rādīts

  - **Office.Licensing.NextUserLicensingEligible —** šis signāls mums norāda, vai lietotājs ir kvalificēts pāriet uz mūsu jauno licencēšanas steku. Tas ir kritiski svarīgi, lai kvantificētu ietekmi uz esošajiem lietotājiem, kamēr ieviešam mūsu jauno licencēšanas steku un nodrošinām, ka lietotājiem nezūd funkcionalitāte

Šis notikums neapkopo laukus.

### <a name="officelicensingnulfetcherfetchmodelfromols"></a>Office.Licensing.Nul.Fetcher.FetchModelFromOls

Ja ierīce izmanto moderno licencēšanas steku, mēģinām iegūt licences failu tieši no pakalpojuma. Šis notikums ziņo par sekmīgu izpildi vai kļūmi kopā ar attiecīgā pakalpojuma izsaukuma kļūdas kodu. Tas ir kritiski svarīgi, lai noteiktu, vai lietotājs ir piemērotā stāvoklī modernajā licencēšanas stekā, kas tiek izmantots sistēmas darbspējai un diagnostikas mērķiem, ja lietotājs ziņo par problēmu savā datorā.

Tiek apkopoti tālāk norādītie lauki.

  - **MetadataValidationResult** — licences metadatu pārbaudes rezultāts, lai verificētu, ka tā nav ietekmēta

  - **SignatureValidationResult** — licences paraksta pārbaudes rezultāts, lai verificētu, ka tā nav ietekmēta

### <a name="officelicensingnulvalidationfullvalidation"></a>Office.Licensing.Nul.Validation.FullValidation 

Tas tiek apkopots katrā ierīces sesijā, kas darbojas modernajā licencēšanas stekā. Tas ziņo datora licencēšanas stāvokli un kļūdas, kas lietotājam rodas un kuru dēļ tas nevar izmantot lietojumprogrammu. Šis notikums norāda, vai lietotāja dators ir darbspējīgs modernajā licencēšanas stekā. Esam iestatījuši anomāliju noteikšanu šim notikumam, lai norādītu, vai regresija izraisa neatbilstošo lietotāju uzvedību. Tas ir arī kritiski svarīgi, kad tiek diagnosticētas lietotāja problēmas, kā arī sistēmas darbspējas pārraudzībai.

Tiek apkopoti tālāk norādītie lauki.

  - **Acid** — GUID identifikators, kas norāda Office produktu, kuram lietotājam ir licence 

  - **AllAcids** — visu produkta GUID saraksts, kam lietotājam pašlaik ir licence 

  - **Category** — lietotāja izmantotās Office licences kategorija 

  - **DaysRemaining** — atlikušais dienu skaits pirms pašreizējās Office licences derīguma beigām 

  - **LicenseId** — lietotājam izsniegtās licences burtciparu identifikators 

  - **LicenseType** — lietotāja izmantotās Office licences veids 

### <a name="officelicensingofficeclientlicensingdolicensevalidation"></a>Office.Licensing.OfficeClientLicensing.DoLicenseValidation 

Tie ir licencēšanas metadati, kas tiek apkopoti no ierīces katrā sāknēšanas reizē, kas ziņo licences ACID, licences statusu, veidu un citus licences rekvizītus, kas ir kritiski svarīgi, lai identificētu līdzekļus, kas ir iestatīti kā pieejami lietotājam. Tas ir kritiski svarīgi, lai identificētu līdzekļu kopu, kas ir pieejama lietotājam, un vai lietotājam trūkst kāda funkcionalitāte. Tas tiek izmantots arī dienas aktīvo lietotāju/mēneša aktīvo lietotāju aprēķiniem un dažādām citām atskaitēm, ko izmanto dažādas grupas sistēmā Office (mārketings/DIG/licencēšana), jo tas norāda tipa produktu, ko lietotājs izmanto, vai tas ir abonementa produkts un vai tam trūkst kāda kritiski svarīga funkcionalitāte.

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

### <a name="officelicensingpurchase"></a>Office.Licensing.Purchase 

Veicam eksperimentu, kas lietotājam sniedz iespēju izmēģināt un iestatīt automātisko maksāšanu par Office tieši no lietojumprogrammas, neizejot no lietojumprogrammas konteksta. Tas ziņo par šī eksperimenta sekmīgu izpildi vai kļūmi kopā ar kļūdas kodu. Tas ir kritiski svarīgi, lai noteiktu, vai lietotājs ir piemērotā stāvoklī un vai tam netrūkst funkcionalitātes, kas tiek izmantota sistēmas darbspējai un diagnostikas mērķiem, ja lietotājs ziņo par problēmu savā datorā.

Tiek apkopoti tālāk norādītie lauki.

  - **StorePurchaseStatus** — atspoguļo pirkuma izsaukuma, kas tika veikts, izmantojot Windows Store, kļūdas kodu/sekmīgas izpildes kodu

### <a name="officelicensingsearchforsessiontoken"></a>Office.Licensing.SearchForSessionToken

Ja lietotājs strādā koplietojama datora aktivizācijas režīmā, mēs mēģinām meklēt sesijas marķieri datorā, kas lietotājam sniedz iespēju izmantot lietojumprogrammu. Šis notikums ziņo par scenārija sekmīgu izpildi vai kļūmi kopā ar kļūdas kodu. Tas ir kritiski svarīgi, lai noteiktu, vai lietotājs ir piemērotā stāvoklī un vai tam netrūkst funkcionalitātes, kas tiek izmantota sistēmas darbspējai un diagnostikas mērķiem, ja lietotājs ziņo par problēmu savā datorā.

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

### <a name="officelicensingusegracekey"></a>Office.Licensing.UseGraceKey

Ja kāda iemesla dēļ nevaram lietotāju licencēt, instalējam pagarinājuma atslēgu un izsūtām signālu, kas to paziņo. Tas ir kritiski svarīgs, lai noteiktu, vai lietotājs ir piemērotā stāvoklī un vai tam trūkst funkcionalitātes, kas tiek izmantota sistēmas darbspējai un diagnostikas mērķiem, ja lietotājs ziņo par problēmu savā datorā

Tiek apkopoti tālāk norādītie lauki.

  - **OpportunisticTokenRenewalAttempted** — norāda, vai mēģinājām oportūnistisku atjaunošanu lietotājam koplietojamā datora aktivizācijas režīmā

  - **ReArmResult** — norāda instalētās atslēgas atkārtotu aktivizēšanu, kas var pagarināt pašreizējās licences derīgumu

## <a name="services-configuration-events"></a>Pakalpojumu konfigurācijas notikumi

Pakalpojumu konfigurācija neapkopo nepieciešamos pakalpojumu diagnostikas datu notikumus.

## <a name="telemetry-events"></a>Telemetrijas notikumi

### <a name="officesystemidentitychanged"></a>Office.System.IdentityChanged

Lietotāja identitātes informācija, kas nepieciešama, lai izpildītu datu subjektu pieprasījumus.

Tiek apkopoti tālāk norādītie lauki.

  - **IdentityChanged** — vienmēr patiess. Identitāte ir mainīta.

  - **TimerDetectedChange** — vai izmaiņas konstatēja regulāra laika programma Ping.

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

<!-- end list -->

  - **WindowsErrorReportingMachineId** — ierīces, kurā Office darbojas, Windows kļūdu uzrādīšanas piešķirtais datora identifikators.

  - **WindowsSqmMachineId** — ierīces, kurā Office darbojas, Windows piešķirtais datora identifikators.

### <a name="officesystemsystemhealthmetadataoperatingsystem"></a>Office.System.SystemHealthMetadataOperatingSystem

Metadati, kas nepieciešami, lai izolētu kļūmes atkārtošanu.

Tiek apkopoti tālāk norādītie lauki.

  - **CollectionTime** — laiks, kad šis notikums tika ierindots augšupielādei

  - **IsTerminalServer** — aplams/patiess ir termināļa servera klients

  - **OsBuild** — operētājsistēmas būvējuma versija.

  - **OsBuildRevision** — OS būvējuma pārskatījums

  - **OSEnvironment** — Windows, iOS, Mac, Android utt.

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

Tiek izmantots, lai tvertu avāriju metriku.

Tiek apkopoti tālāk norādītie lauki.

  - **AffectedProcessAppBuild —** būvējuma versijas identifikators ietekmētajam procesam.

  - **AffectedProcessAppBuildRevision —** būvējuma pārskatījuma identifikators ietekmētajam procesam.

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

  - **CrashedEcsETag —** avarējušā procesa eksperimenta identifikators.

  - **CrashedImpressionId —** avarējušā procesa seansa identifikators.

  - **CrashedProcessSessionID —** avarējušā procesa unikāls identifikators.

  - **CrashedProcessSessionInitTime —** laiks, kad ietekmētais process tika sākts.

  - **CrashType —** avārijas veida intervāla identifikators.

  - **DetectionTime —** laiks, kad tika konstatēta neparedzētā izeja.

  - **ErrorString —** kļūdas apraksts.

  - **ExceptionAddress —** adrese programmā, kur kļūme radās.

  - **ExceptionCode —** izņēmuma intervāla identifikators.

  - **FaultAppName —** kļūdainās lietojumprogrammas nosaukums.

  - **InstallMethod —** vai pašreizējais Office būvējums tika jaunināts, atritināts vai svaigi instalēts.

  - **InstallType —** Office instalēšanas metodes identifikators.

  - **InstallTypeName —** Office instalēšanas metodes identifikators.

  - **IsLabMachine —** vai sistēma Office tiek izmantota Microsoft laboratorijā.

  - **IsMsftInternal —** vai Windows lietotājs, kurš izmanto Office, ir Microsoft darbinieks.

  - **ModuleBaseAddress —** kļūdainā moduļa bāzes adrese.

  - **ModuleBuildVersion —** kļūdainā moduļa būvējuma versijas numurs.

  - **ModuleMajorVersion —** kļūdainā moduļa galvenās versijas numurs.

  - **ModuleMinorVersion —** kļūdainā moduļa papildversijas numurs.

  - **ModuleName —** kļūdainā moduļa nosaukums.

  - **ModuleOffset —** nobīde baitos no bāzes adreses, kur kļūme radās.

  - **ModuleRevisionVersion —** kļūdainā moduļa būvējuma pārskatījuma versijas numurs.

  - **ModuleSize —** kļūdainā moduļa izmērs baitos.

  - **OSEnvironment —** identifikators, kādā vidē Office darbojas.

  - **PreviousBuild —** iepriekš instalētā būvējuma versija

  - **UAETypeName —** intervāla identifikators par to, kā izeja no lietojumprogrammas notika negraciozi.

  - **VerifyElseCrashTag —** unikālais identifikators par to, kur lietojumprogramma avarēja.

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

Tiek izmantots, lai tvertu avāriju metriku.

Tiek apkopoti tālāk norādītie lauki.

  - **CrashedAppBuild —** būvējuma versijas identifikators ietekmētajam procesam.

  - **CrashedAppMajor —** galvenās versijas identifikators ietekmētajam procesam.

  - **CrashedAppMinor —** papildversijas identifikators ietekmētajam procesam.

  - **CrashedAppRevision —** būvējuma versijas identifikators ietekmētajam procesam.

  - **CrashedConfigIds —** avarējušajam procesam piešķirtā konfigurācija.

  - **CrashedEcsETag —** avarējušā procesa eksperimenta identifikators.

  - **CrashedImpressionId —** avarējušā procesa seansa identifikators.

  - **CrashedModuleName —** kļūdainā moduļa nosaukums.

  - **CrashedSessionId —** avarējušā procesa unikāls identifikators.

  - **CrashedSessionInitTime —** laiks, kad ietekmētais process tika sākts.

  - **CrashType —** avārijas veida intervāla identifikators.

  - **DetectionTime —** laiks, kad tika konstatēta neparedzētā izeja.

  - **ExceptionAddress —** adrese programmā, kur kļūme radās.

  - **ExceptionCode —** izņēmuma intervāla identifikators.

  - **HexExceptionAddress —** adrese heksadecimālā formātā programmā, kur kļūme radās.

  - **HexExceptionCode —** izņēmuma intervāla identifikators heksadecimālajā formātā.

  - **HexModuleBaseAddress —** kļūdainā moduļa bāzes adrese heksadecimālā formātā.

  - **HexModuleOffset —** nobīde baitos (heksadecimālajā formātā) no bāzes adreses, kur kļūme radās.

  - **HexModuleSize —** kļūdainā moduļa izmērs baitos heksadecimālā formātā.

  - **HexVerifyElseCrashTag —** unikālais identifikators heksadecimālajā formātā par to, kur lietojumprogramma avarēja.

  - **InstallMethod —** vai pašreizējais Office būvējums tika jaunināts, atritināts vai svaigi instalēts.

  - **IsLabMachine —** vai sistēma Office tiek izmantota Microsoft laboratorijā.

  - **ModuleBaseAddress —** kļūdainā moduļa bāzes adrese.

  - **ModuleOffset —** nobīde baitos no bāzes adreses, kur kļūme radās.

  - **ModuleSize —** kļūdainā moduļa izmērs baitos.

  - **PreviousBuild —** iepriekš instalētā būvējuma versija

  - **UAEOSEnvironment —** operētājsistēmas vides identifikators.

  - **VerifyElseCrashTag —** unikālais identifikators par to, kur lietojumprogramma avarēja.

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

Tiek apkopoti tālāk norādītie lauki.

  - **DialogCancelled** — vai diagnostikas datu skatītāja dialogs tika atcelts

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

<!-- end list -->

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
