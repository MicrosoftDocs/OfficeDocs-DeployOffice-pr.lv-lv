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
ms.openlocfilehash: 25f594865089d35cb46ebfcc9b97d6b048f6298d
ms.sourcegitcommit: ad2bb6e42b2432a2cb9370594cd50f3a14f2fbe3
ms.translationtype: HT
ms.contentlocale: lv-LV
ms.lasthandoff: 11/13/2019
ms.locfileid: "38310687"
---
# <a name="essential-services-for-office"></a>Office būtiskie pakalpojumi

> [!IMPORTANT]
> Informācija šajā rakstā attiecas uz tālāk minētās Office klienta programmatūras versiju 1904 vai jaunāku versiju, kas instalēta datorā, kurā darbojas sistēma Windows:
> - Office 365 ProPlus un Office 365 Business
> - Office 365 individuālai lietošanai, Office 365 mājas lietošanai vai citas Office versijas, kas ir daļa no Office 365 abonementa.
> - Project un Visio, kas ir iekļautas dažos abonēšanas plānos, piemēram, Project Online Professional plānā vai Visio Online 2. plānā.
>
> Šī informācija attiecas arī uz tālāk norādīto sistēmas Office darbam ar Mac lietojumprogrammu versiju 16.28 vai jaunākām versijām: Excel, Outlook, OneNote, PowerPoint un Word.

Office sastāv no klienta programmām un saistītajiem līdzekļiem, kas paredzēti, lai jūs varētu efektīvāk veidot, sazināties un sadarboties. Lai gan varat kontrolēt daudzas savienotās iespējas, kas ir pieejamas jums vai jūsu lietotājiem, ja esat savas organizācijas administrators, pastāv pakalpojumu kopa, kas ir būtiski attiecībā uz to, kā Office darbojas, tāpēc tos nevar atspējot. Piemēram, licencēšanas pakalpojums, kas apstiprina, vai esat pareizi licencēts Office izmantošanai. Nepieciešamie pakalpojumu dati par šiem pakalpojumiem tiek apkopoti un nosūtīti korporācijai Microsoft neatkarīgi no citiem politikas iestatījumiem, kas saistīti ar konfidencialitāti un kurus esat konfigurējis. Šos datus varat skatīt, izmantojot diagnostikas datu skatītāju.

Papildinformāciju skatiet šeit:

- [Office nepieciešamais datu pakalpojums](required-service-data.md)
- [Diagnostikas datu skatītāja izmantošana ar Office](https://support.office.com/article/cf761ce9-d805-4c60-a339-4e07f3182855)
- [Office saistītie līdzekļi](connected-experiences.md)

Ja esat organizācijas administrators, iespējams, jūs interesēs arī šie raksti:

- [Pārskats par konfidencialitātes kontroles līdzekļiem pakalpojumā Office 365 ProPlus](overview-privacy-controls.md)
- [Politikas iestatījumu izmantošana Office 365 ProPlus konfidencialitātes kontroles pārvaldībai](manage-privacy-controls.md)
- [Preferenču izmantošana Office darbam ar Mac konfidencialitātes kontroles līdzekļu pārvaldībai](mac-privacy-preferences.md)
- [Preferenču izmantošana Office darbam ar iOS ierīcēm konfidencialitātes kontroles līdzekļu pārvaldībai](ios-privacy-preferences.md)
- [Politikas iestatījumu izmantošana Office konfidencialitātes kontroles līdzekļu pārvaldībai Android ierīcēs](android-privacy-controls.md)

## <a name="list-of-essential-services-for-office"></a>Office būtisko pakalpojumu saraksts 

Tālāk esošajā tabulā ir Office būtisko pakalpojumu saraksts, kā arī katra pakalpojuma apraksts.

| **Pakalpojums**  | **Apraksts**  |
| ------ | ---- |
| [Autentifikācija](#authentication-events) | Autentifikācija ir vairāku platformu pakalpojums, kas pārbauda jūsu Office lietotāja identitāti.  Tā ir nepieciešama, lai jums sniegtu iespēju pierakstīties sistēmā Office, aktivizēt jūsu Office licenci, piekļūtu jūsu mākonī saglabātajiem failiem, kā arī nodrošinātu konsekventu pieredzi vairākās Office sesijās un jūsu ierīcēs.    |
| [Click-to-Run](#click-to-run-events) | Click-to-Run ir instalēšanas tehnoloģija, kas tiek izmantota, lai instalētu un atjauninātu sistēmu Office operētājsistēmā Windows. Tā meklē jaunas Office versijas un, kad jauna versija ir pieejama, lejupielādē un instalē to. Click-to-Run noteiks Office atjauninājumu (tostarp drošības atjauninājumu) nepieciešamību, veiks to lejupielādi un instalēšanu.     |
| [Uzlabotās konfigurācijas pakalpojums (ECS)](#enhanced-configuration-service-ecs-events) | ECS nodrošina korporācijai Microsoft iespēju atkārtoti konfigurēt Office instalācijas tā, lai jums nebūtu atkārtoti jāizvieto Office. Tā tiek izmantota, lai kontrolētu pakāpenisko līdzekļu vai atjauninājumu ieviešanu, kamēr ieviešanas ietekme tiek pārraudzīta no diagnostikas datiem, kas tiek apkopoti. Tā arī tiek izmantota, lai mazinātu drošības vai veiktspējas problēmas ar līdzekli vai atjauninājumu. Turklāt ECS atbalsta konfigurācijas izmaiņas, kas saistītas ar diagnostikas datiem, lai nodrošinātu, ka tiek apkopoti atbilstošie notikumi. |
| [Licencēšana](#licensing-events)     | Licencēšana ir mākoņpakalpojums, kas atbalsta jūsu Office aktivizāciju jaunām instalācijām, kā arī uztur licenci jūsu ierīcēs pēc Office aktivizēšanas. Tā reģistrē katru jūsu ierīci un aktivizē Office, pārbauda jūsu Office abonementa statusu un pārvalda jūsu produktu atslēgas.    |
|[Microsoft AutoUpdate (MAU)](#microsoft-autoupdate-mau-events)|Microsoft AutoUpdate (MAU) ir tehnoloģija, kas tiek lietota, lai atjauninātu Microsoft programmas, piemēram, Office, kuras tiek veidotas MacOS vajadzībām. MAU noteiks programmu atjauninājumu (tostarp drošības atjauninājumu) nepieciešamību, veiks to lejupielādi un instalēšanu.|
|[OneNote sinhronizācija](#onenote-sync-events)|Programma OneNote darbam ar Mac atbalsta tikai tādas piezīmju grāmatiņas, kas tiek glabātas internetā — OneDrive krātuvē vai SharePoint Online. Programma OneNote darbam ar Mac pastāvīgi sinhronizē visas lietotāja piezīmes ar OneDrive krātuvi vai SharePoint Online. Tādējādi lietotāji var atvērt, skatīt un rediģēt savas piezīmju grāmatiņas visās savās ierīcēs, un viņu piezīmju grāmatiņas vienmēr ir atjauninātas.
 [Pakalpojumu konfigurācija](#services-configuration-events)  | Pakalpojumu konfigurācija nodrošina iespēju veikt atjauninājumus Office konfigurācijas iestatījumos, lai iespējotu vai atspējotu klientu līdzekļus. Tā tiek izsaukta ikreiz, kad Office lietojumprogramma tiek startēta, un nodrošina detalizētu informāciju par citām Office konfigurācijām un pakalpojumiem. Pakalpojumu konfigurācija kontrolē arī to, kuri pakalpojumi ir paredzēti kā būtiskie pakalpojumi.  |
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

### <a name="officeclicktorunrepomanlogger"></a>Office.ClickToRun.RepomanLogger

Ziņo par jaunā Click-to-Run atjauninājumu konveijera statusu (“Repoman”) un par to, vai tas veiksmīgi lejupielādē un instalē Office atjauninājumus.

Tiek apkopoti šādi lauki.

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

### <a name="officeclicktoruntransport"></a>Office.ClickToRun.Transport

Ziņo par failu lejupielādes darbībām, lai noteiktu operācijas sekmīgumu, veiktās lejupielādes tipu un diagnostikas informāciju.


- **BytesFromGroupPeers —** baiti no grupas vienranga dalībniekiem, tikai lejupielādēm, izmantojot piegādes optimizāciju

- **BytesFromHttp —** baiti no http, tikai lejupielādēm, izmantojot piegādes optimizāciju

- **ByteFromInternetPeers —** baiti no interneta vienranga dalībniekiem, tikai lejupielādēm, izmantojot piegādes optimizāciju 

- **BytesFromLanPeers —** baiti no LAN vienranga dalībniekiem, tikai lejupielādēm, izmantojot piegādes optimizāciju 

- **CancelledJobs —** atcelto pieprasījumu skaits sesijā

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

- **TransferredBytes —** kopējais pārnesto baitu skaits sesijā

- **TransportType —** transporta veids, piemēram, piegādes optimizācija atmiņā, HTTP, fona režīma intelektiskās pārsūtīšanas pakalpojums



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


### <a name="officeclicktorununiversalbootstrapperapplication"></a>Office.ClickToRun.UniversalBootstrapper.Application

Ziņo par gala-gala instalācijas mēģinājuma rezultātu

 - **ErrorCode —** vesels skaitlis, kas saistīts ar neapstrādātu izņēmumu

 - **ErrorDetails —** virkne, kas apraksta atrašanās vietu, kur radās neapstrādāts izņēmums (funkcija, fails, rindiņas numurs, metēja iestatītie papildu parametri)

 - **ErrorMessage —** virkne, kas definēta punktā, kurā tika izmests neapstrādāts izņēmums, aprakstot kļūmes būtību

 - **ErrorType —** virkne, kas apraksta neapstrādāta izņēmuma kategoriju

 - **ExitCode —** vesela skaitļa vērtība, kas saistīta ar sāknēšanas programmas darbības rezultātu, norādot sekmes vai konkrētus kļūmju tipus

### <a name="officeclicktorununiversalbootstrappercalculateparameters"></a>Office.ClickToRun.UniversalBootstrapper.CalculateParameters

Atskaites par darbību, kas ir pamats apkopotajai ievadei, izmantojot CollectParameters

- **BitField** — argumenta BitField vesela skaitļa vērtība, kas norāda, vai ir pieprasīts konkrēts instalēšanas/atjaunināšanas kanāls (Monthly, Insiders Slow, Insiders Fast, Semi-Annual, Semi-Annual Targeted)

- **ChannelID —** vesels skaitlis, kas norāda atlasītā atjaunināšanas/instalēšanas kanāla uzskaitījuma vērtību (Monthly, Insiders Slow, Insiders Fast, Semi-Annual, Semi-Annual Targeted, Invalid)

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

- **PlatformToInstall —** virkne, kas norāda galīgo lēmumu par to, vai ir jāinstalē x86 vai x64 Office. Iespējas ir: automātiskā palaišana, konfigurēšana, patērētājs, lejupielāde, palīdzība, pakotājs

- **PRID —** virknes vērtība, kas norāda pieprasītā produkta laidiena ID patērētāja instalēšanas scenārijā (piemēram, O365ProPlusRetail)

- **ProductsToAdd —** sērijas virkne, kas C2R klientam norāda, kurās produkta/kultūra kombinācijās tas ir jāinstalē

- **ProductsToRemove —** sērijas virkne, kas C2R klientam norāda, kurās produkta/kultūra kombinācijās tas ir jāatinstalē

- **SharedComputerLicensing —** Būla vērtība, kas norāda, vai IT administrators ir pieprasījis iestatīšanu, lai iespējotu līdzekli SharedComputerLicensing

- **ShouldActivate —** Būla vērtība, kas norāda, vai IT administrators ir pieprasījis automātisko licencēšanas aktivizācijas mēģinājumu savā konfigurācijas .xml failā

- **VersionToInstall —** instalējamās Office versijas virknes vērtība formātā “16.0.xxxxx.yyyyy”
 

### <a name="officeclicktorununiversalbootstrappercollectembeddedsignature"></a>Office.ClickToRun.UniversalBootstrapper.CollectEmbeddedSignature

Atskaites par darbībām, kas lasa atzīmēto ievadi no .exe faila iegultā paraksta.  Šī ir nepierādīta koncepcija, kuru iepriekšējā programmas setup.exe versija neimplementēja, un uz to mēs paļaujamies, lai pārnestu lietotāja produkta/valodas/bitu skaita izvēles no tīmekļa lapas uz iekšējo procesu programmā setup.exe.
 
- **ErrorCode —** vesels skaitlis, kas saistīts ar neapstrādātu izņēmumu

- **ErrorDetails —** virkne, kas apraksta atrašanās vietu, kur radās neapstrādāts izņēmums (funkcija, fails, rindiņas numurs, metēja iestatītie papildu parametri)

- **ErrorMessage —** virkne, kas definēta punktā, kurā tika izmests neapstrādāts izņēmums, aprakstot kļūmes būtību

- **ErrorType —** virkne, kas apraksta neapstrādāta izņēmuma kategoriju

### <a name="officeclicktorununiversalbootstrappercollectparameters"></a>Office.ClickToRun.UniversalBootstrapper.CollectParameters

Ziņo par Office instalēšanai izmantotajiem parametriem

- **BitField** — argumenta BitField vesela skaitļa vērtība, kas norāda, vai ir pieprasīts konkrēts instalēšanas/atjaunināšanas kanāls (Monthly, Insiders Slow, Insiders Fast, Semi-Annual, Semi-Annual Targeted)

- **ChannelID —** vesels skaitlis, kas norāda atlasītā atjaunināšanas/instalēšanas kanāla uzskaitījuma vērtību (Monthly, Insiders Slow, Insiders Fast, Semi-Annual, Semi-Annual Targeted, Invalid)

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

- **ProductsToRemove —** sērijas virkne, kas C2R klientam norāda, kurās produkta/kultūra kombinācijās tas ir jāatinstalē

- **PRID —** virknes vērtība, kas norāda pieprasītā produkta laidiena ID patērētāja instalēšanas scenārijā (piemēram, O365ProPlusRetail)

- **ProductsToAdd —** sērijas virkne, kas C2R klientam norāda, kurās produkta/kultūra kombinācijās tas ir jāinstalē

- **SharedComputerLicensing —** Būla vērtība, kas norāda, vai IT administrators ir pieprasījis iestatīšanu, lai iespējotu līdzekli SharedComputerLicensing

- **ShouldActivate —** Būla vērtība, kas norāda, vai IT administrators ir pieprasījis automātisko licencēšanas aktivizācijas mēģinājumu savā konfigurācijas .xml failā

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

Ja sistēmas Office darbība tiek beigta vai tā avarē licencēšanas kļūdas dēļ, mēs izsūtām šo signālu, lai norādītu to pašu. Tas ir kritiski svarīgs, lai noteiktu, vai lietotājs ir piemērotā stāvoklī un vai tam netrūkst funkcionalitātes, kas tiek izmantota sistēmas darbspējai un diagnostikas mērķiem, ja lietotājs ziņo par problēmu savā datorā.

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

### <a name="officelicensingnextuserlicensingeligible"></a>Office.Licensing.NextUserLicensingEligible 

Šis signāls mums norāda, vai lietotājs ir kvalificēts pāriet uz mūsu jauno licencēšanas steku. Tas ir kritiski svarīgi, lai kvantificētu ietekmi uz esošajiem lietotājiem, kamēr ieviešam mūsu jauno licencēšanas steku un nodrošinām, ka lietotājiem nezūd funkcionalitāte.

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

## <a name="microsoft-autoupdate-mau-events"></a>Microsoft AutoUpdate (MAU) notikumi

### <a name="appdelegate_launch"></a>appdelegate_launch

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


### <a name="appdelegate_terminate"></a>appdelegate_terminate

Šis notikums norāda, ka ir notikusi labvēlīga iziešana no programmas. Šis notikums tiek izmantots, lai atšķirtu labvēlīgu iziešanu no programmas no nelabvēlīgas.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kādā darbojas programma

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


### <a name="appinstall_connecttoxpc"></a>appinstall_connecttoxpc

Šis notikums norāda, ka, veidojot savienojumu ar MAU palīgu (komponents, kas veic programmu instalēšanu), radās kļūdas.  Šis notikums norāda iespējamu MAU programmas bojājumu. Ierīce nevarēs instalēt atjauninājumus.

Tiek apkopoti šādi lauki: 

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kādā darbojas programma

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


### <a name="appregistry_info"></a>appregistry_info

Šis notikums norāda, ka programma ir palaista. Šis notikums tiek izmantots, lai uzskaitītu programmas, kurām MAU var kontrolēt atjauninājumus, pieejamo kopiju skaitu, kā arī to versiju un instalācijas atrašanās vietu (noklusējuma vai cita).

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kādā darbojas programma

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


### <a name="appregistry_remove"></a>appregistry_remove

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


### <a name="catalog_errorsignature"></a>catalog_errorsignature

Šis notikums norāda, ka, atjauninājuma papildmateriālu failam veicot koda parakstīšanas validāciju, radās kļūme.  Visi papildmateriāli, kuriem radušās koda parakstīšanas verifikācijas kļūmes, ir jāuzskata par nederīgiem.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kādā darbojas programma

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

- **Payload** — ietver tā kataloga faila nosaukumu, kuram ir nederīgs paraksts. Cits statisks teksts apraksta atšķirīgus kļūdas nosacījumus.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie trīs okteti

- **SessionId** — sesijas identifikators


### <a name="cloningtask_helpertoolconnection"></a>cloningtask_helpertoolconnection

Šis notikums reģistrē problēmas ar instalēšanu klonā (t.i., vai nu neizdodas izveidot savienojumu ar palīgu, lai lietotu atjauninājumu, vai savienojums ir izveidot, bet palīgs nevar lietot atjauninājumu). Ja tiek ziņots par kādu ierakstu, tas nozīmē, ka instalēšana klonā neizdevās un ka tagad ir jāveic atkāpšanās uz atjauninājumu atrašanās vietā.

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kādā darbojas programma

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


### <a name="configuration_channel"></a>configuration_channel

Šis notikums reģistrē mēģinājumus rīkā MAU pārslēgt kanālus (auditorijas grupu).  Mēs to izmantojam, lai reģistrētu mēģinājumus un to rezultātus (sekmīgi vai kļūme).

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kādā darbojas programma

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


### <a name="configuration_metadata"></a>configuration_metadata

Šis notikums tiek reģistrēts ikreiz, kad notiek MAU inicializēšana. Tas ir MAU periodiskā kontrolziņojuma notikuma veids

Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kādā darbojas programma

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


### <a name="controller_alertmanager_reinstallresponse"></a>controller_alertmanager_reinstallresponse

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

    
### <a name="controller_alertmanager_tmpdiskfull"></a>controller_alertmanager_tmpdiskfull

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


### <a name="controller_alertmanager_tmpdiskfullretry"></a>controller_alertmanager_tmpdiskfullretry

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
    

### <a name="controller_alertmanager_tmpdiskfullretrycancel"></a>controller_alertmanager_tmpdiskfullretrycancel

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

    
### <a name="controller_checkwindow_noupdatefoundok"></a>controller_checkwindow_noupdatefoundok

Šis notikums norāda, ka, veicot pārbaudi, vai nav atjauninājumu, neviens atjauninājums netika atrasts. Šis notikums tiek izmantots, lai nodrošinātu atjauninājumu piedāvāšanas pareizību, optimizētu pakalpojumu noslodzi un definētu, cik biežām ir jābūt pārbaudēm, vai nav atjauninājumu. Vēlamies arī optimizēt savu laidienu biežumu atbilstoši lietotāju gaidām saistībā ar atjauninājumiem.

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

    

### <a name="controller_checkwindow_updatecheck"></a>controller_checkwindow_updatecheck

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


### <a name="controller_checkwindow_updatecheckcancel"></a>controller_checkwindow_updatecheckcancel

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

    
### <a name="controller_checkwindow_updatecheckcanceluser"></a>controller_checkwindow_updatecheckcanceluser

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

    
### <a name="controller_checkwindow_updatesfound"></a>controller_checkwindow_updatesfound

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

    
### <a name="controller_checkwindow_uptodate"></a>controller_checkwindow_uptodate

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


### <a name="controller_downloadwindow_applaunchwithpendingupdate"></a>controller_downloadwindow_applaunchwithpendingupdate

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

    
### <a name="controller_downloadwindow_closeapplicationdialog"></a>controller_downloadwindow_closeapplicationdialog

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

    
### <a name="controller_downloadwindow_curtasknull"></a>controller_downloadwindow_curtasknull

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

    
### <a name="controller_downloadwindow_downloadcancel"></a>controller_downloadwindow_downloadcancel

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

    
### <a name="controller_downloadwindow_downloadfailed"></a>controller_downloadwindow_downloadfailed

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

    
### <a name="controller_downloadwindow_downloadfailedok"></a>controller_downloadwindow_downloadfailedok

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


### <a name="controller_downloadwindow_downloadpathmissing"></a>controller_downloadwindow_downloadpathmissing

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


### <a name="controller_downloadwindow_downloadtasknull"></a>controller_downloadwindow_downloadtasknull

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


### <a name="controller_downloadwindow_filesignaturenotverified"></a>controller_downloadwindow_filesignaturenotverified

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


### <a name="controller_downloadwindow_installcomplete"></a>controller_downloadwindow_installcomplete

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


### <a name="controller_downloadwindow_networkunavailablealert"></a>controller_downloadwindow_networkunavailablealert

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

    
### <a name="controller_downloadwindow_networkunavailablealertok"></a>controller_downloadwindow_networkunavailablealertok

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

    
### <a name="controller_downloadwindow_noconnectionok"></a>controller_downloadwindow_noconnectionok

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


### <a name="controller_downloadwindow_repairrequired"></a>controller_downloadwindow_repairrequired

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

### <a name="controller_downloadwindow_updateaborted"></a>controller_downloadwindow_updateaborted

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


### <a name="controller_downloadwindow_updatefailed"></a>controller_downloadwindow_updatefailed

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


### <a name="controller_downloadwindow_updatesuccessful"></a>controller_downloadwindow_updatesuccessful

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


### <a name="controller_downloadwindow_userpaused"></a>controller_downloadwindow_userpaused

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


### <a name="controller_downloadwindow_userresumed"></a>controller_downloadwindow_userresumed

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


### <a name="controller_mainwindow_setautomaticdownloadinstall"></a>controller_mainwindow_setautomaticdownloadinstall

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

    
### <a name="controller_mainwindow_setmanualchecking"></a>controller_mainwindow_setmanualchecking

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

    
### <a name="controller_templateawindow_cancel"></a>controller_templateawindow_cancel

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

    
### <a name="controller_templateawindow_enroll"></a>controller_templateawindow_enroll

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



### <a name="controller_templateawindow_install"></a>controller_templateawindow_install

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


### <a name="controller_updatewindow_begindownloadingapps"></a>controller_updatewindow_begindownloadingapps

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

    
### <a name="controller_updatewindow_networkretry"></a>controller_updatewindow_networkretry

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

    
### <a name="controller_updatewindow_networkretrycancel"></a>controller_updatewindow_networkretrycancel

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


### <a name="controller_updatewindow_networkunavailable"></a>controller_updatewindow_networkunavailable

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


### <a name="controller_updatewindow_noupdateavailable"></a>controller_updatewindow_noupdateavailable

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


### <a name="controller_updatewindow_noupdatestoselect"></a>controller_updatewindow_noupdatestoselect

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


### <a name="controller_updatewindow_updateavailable"></a>Controller_UpdateWindow_UpdateAvailable

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

    
### <a name="controller_updatewindow_updateavailablecancel"></a>controller_updatewindow_updateavailablecancel

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


### <a name="downloadactor_pause"></a>downloadactor_pause

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


### <a name="downloadactor_redirect"></a>downloadactor_redirect

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

    
### <a name="downloadactor_resume"></a>downloadactor_resume

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


### <a name="downloadactor_resumeerror"></a>downloadactor_resumeerror

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

    
### <a name="downloadactor_status"></a>downloadactor_status

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


### <a name="downloadmanifest_downloadcatalogfail"></a>downloadmanifest_downloadcatalogfail

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

    
### <a name="downloadmanifest_downloadcatalogsuccess"></a>downloadmanifest_downloadcatalogsuccess

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


### <a name="downloadmanifest_downloadfail"></a>downloadmanifest_downloadfail

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


### <a name="downloadmanifest_downloadfromurl"></a>downloadmanifest_downloadfromurl

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


### <a name="downloadmanifest_downloading"></a>downloadmanifest_downloading

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


### <a name="downloadmanifest_downloadsuccess"></a>downloadmanifest_downloadsuccess

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

    
### <a name="downloadmanifest_downloadurl"></a>downloadmanifest_downloadurl

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


### <a name="downloadmanifest_filenameerror"></a>downloadmanifest_filenameerror

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


### <a name="downloadmanifest_invalidhash"></a>downloadmanifest_invalidhash

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


### <a name="downloadmanifest_missingdaemon"></a>downloadmanifest_missingdaemon

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


### <a name="downloadmanifest_signatureerror"></a>downloadmanifest_signatureerror

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


### <a name="downloadmanifest_status"></a>downloadmanifest_status

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


### <a name="downloadmgr_downloadend"></a>downloadmgr_downloadend

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


### <a name="downloadmgr_downloadstart"></a>downloadmgr_downloadstart

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


### <a name="downloadtask_downloadfailure"></a>downloadtask_downloadfailure

Šis notikums reģistrē to, ka pakotnes faila lejupielādes laikā radās kļūda. Reģistrējam atjauninājuma ceļu un kļūdu. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
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

- **Payload** — satur lejupielādējamā atjauninājuma nosaukumu un novēroto kļūdu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="downloadtask_downloadsuccess"></a>downloadtask_downloadsuccess

Sekmīga pakotnes faila lejupielāde. Reģistrējam izmantoto atjauninājuma ceļu. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
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

- **Payload** — satur sekmīgas lejupielādes atjauninājuma ceļu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="fba_checkforupdate"></a>fba_checkforupdate

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


### <a name="fba_checkforupdateskip"></a>fba_checkforupdateskip

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


### <a name="fba_launchstatus"></a>fba_launchstatus

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

- **Event_ReceivedTime** — laiks, kad tika saņemta telemetrija

- **EventInfo_Name** — reģistrējamā telemetrijas notikuma nosaukums

- **EventInfo_Time** — laiks, kad notika reģistrētais notikums 

- **HowTocheck** — pārbaudes, vai nav atjauninājumu, preference

- **Payload** — satur OSStatus (Apple statusa kodu), kas atspoguļo palaišanas statusu.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="fba_silentupdateoptin"></a>fba_silentupdateoptin

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


### <a name="fba_skipforcedupdate"></a>fba_skipforcedupdate

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


### <a name="fba_startforcedupdate"></a>fba_startforcedupdate

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


### <a name="fba_terminate"></a>fba_terminate

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


### <a name="fba_updatefound"></a>fba_updatefound

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

    
### <a name="fba_updatetimer"></a>fba_updatetimer

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


### <a name="fbasilentupdate_allappsclosed"></a>fbasilentupdate_allappsclosed

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


### <a name="fbasilentupdate_applaunchafterupdate"></a>fbasilentupdate_applaunchafterupdate

Šis notikums reģistrē mēģinājumu atkārtoti palaist programmu pēc klusās atjaunināšanas un atjaunināšanas režīmu (klons vai nav klons). Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
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

- **Payload** — ietver identifikatoru, kas tiek lietots, lai izsekotu atjaunināšanas darbību un palaižamās programmas nosaukumu.
    
- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)
    
- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="fbasilentupdate_applaunchwileinstalling"></a>fbasilentupdate_applaunchwileinstalling

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


### <a name="fbasilentupdate_appneedtoclose"></a>fbasilentupdate_appneedtoclose

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


### <a name="fbasilentupdate_appterminationeventreceived"></a>fbasilentupdate_appterminationeventreceived

Šis notikums norāda, ka Microsoft AutoUpdate saņēma Apple notikumu, informējot par programmas darbības pārtraukšanu. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
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

- **Payload** — ietver identifikatoru, kas tiek lietots, lai izsekotu atjaunināšanas darbību un programmu komplekta ID. Var saturēt arī kļūdas virkni, ja Microsoft AutoUpdate nosaka, ka programma joprojām darbojas, lai gan tika saņemts darbības pārtraukšanas notikums.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="fbasilentupdate_codesignfailure"></a>fbasilentupdate_codesignfailure

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


### <a name="fbasilentupdate_download"></a>fbasilentupdate_download

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

- **SessionId** — sesijas identifikators


### <a name="fbasilentupdate_downloadfailed"></a>fbasilentupdate_downloadfailed

Šis notikums norāda, ka, lejupielādējot atjauninājumu, radās kļūda. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
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


### <a name="fbasilentupdate_downloadinbackground"></a>fbasilentupdate_downloadinbackground

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


### <a name="fbasilentupdate_downloadingrepairupdate"></a>fbasilentupdate_downloadingrepairupdate

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

- **SessionId** — sesijas identifikators


### <a name="fbasilentupdate_duplicatedownloadattempted"></a>fbasilentupdate_duplicatedownloadattempted

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


### <a name="fbasilentupdate_installattemptfailed"></a>fbasilentupdate_installattemptfailed

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


### <a name="fbasilentupdate_installcomplete"></a>fbasilentupdate_installcomplete

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


### <a name="fbasilentupdate_installed"></a>fbasilentupdate_installed

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

    
### <a name="fbasilentupdate_installing"></a>fbasilentupdate_installing

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


### <a name="fbasilentupdate_notificationremoved"></a>fbasilentupdate_notificationremoved

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


### <a name="fbasilentupdate_queueinstall"></a>fbasilentupdate_queueinstall

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


### <a name="fbasilentupdate_requiredappsclosed"></a>fbasilentupdate_requiredappsclosed

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


### <a name="fbasilentupdate_updateavailablenotification"></a>fbasilentupdate_updateavailablenotification

Šis notikums norāda, ka tiek izraisīts paziņojums par pieejamu atjauninājumu. Ir jānodrošina plūsma uzvednes par atjauninājumu izraisīšanai, kad tiek atrasts atjauninājums. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
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


### <a name="fbasilentupdate_userclicknotification"></a>fbasilentupdate_userclicknotification

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


### <a name="fbasilentupdate_userselectinstalllater"></a>fbasilentupdate_userselectinstalllater

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


### <a name="fbasilentupdate_userselectinstallnow"></a>fbasilentupdate_userselectinstallnow

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


### <a name="installdata_checkrunning"></a>installdata_checkrunning

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

    
### <a name="installdata_cleanup"></a>installdata_cleanup

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


### <a name="installedapp_invalidbundle"></a>installedapp_invalidbundle

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

    
### <a name="installedapp_invalidpreference"></a>installedapp_invalidpreference

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

    
### <a name="installedapp_nilbundleid"></a>installedapp_nilbundleid

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


### <a name="installedapp_nilbundlename"></a>installedapp_nilbundlename

Šis notikums reģistrē gadījumus, kad programmai trūkst komplekta nosaukuma. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
Tiek apkopoti šādi lauki:

- **App** — programmas process, kas sūta notikumu

- **AppInfo_Language** — valoda, kādā darbojas programma

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

    
### <a name="installstatus_codesign"></a>installstatus_codesign

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


### <a name="installstatus_daemon"></a>installstatus_daemon

Šis notikums reģistrē Microsoft AutoUpdate dēmona statusa statusu. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
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

- **Payload** — satur norādi, vai dēmona komponents pastāv paredzamajā atrašanās vietā un vai tā kods ir parakstīts.

- **PipelineInfo_ClientCountry** — ierīces valsts/reģions (atbilstoši IP adresei)

- **PipelineInfo_ClientIp** — IP adreses pirmie 3 okteti

- **SessionId** — sesijas identifikators


### <a name="installstatus_helper"></a>installstatus_helper

Šis notikums reģistrē Microsoft AutoUpdate palīga rīka statusa statusu. Šis notikums tiek izmantots, lai nodrošinātu paredzēto atjaunināšanas procesa darbību un lai palīdzētu novērst kļūdas.
 
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

    
### <a name="installupdatestask_applaunched"></a>installupdatestask_applaunched

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

    
### <a name="installupdatestask_applaunchwithpendingupdate"></a>installupdatestask_applaunchwithpendingupdate

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

    
### <a name="installupdatestask_codesignverificationfail"></a>installupdatestask_codesignverificationfail

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


### <a name="installupdatestask_codesignverificationstart"></a>installupdatestask_codesignverificationstart

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


### <a name="installupdatestask_codesignverificationsuccess"></a>installupdatestask_codesignverificationsuccess

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


### <a name="installupdatestask_failsilentinstall"></a>installupdatestask_failsilentinstall

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

    
### <a name="installupdatestask_multiplerelocatablepackage"></a>installupdatestask_multiplerelocatablepackage

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

    
### <a name="installupdatestask_removeclone"></a>installupdatestask_removeclone

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


### <a name="installupdatestask_retryfail"></a>installupdatestask_retryfail

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


### <a name="installupdatestask_retryproxyerror"></a>installupdatestask_retryproxyerror

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

    
### <a name="installupdatestask_retryproxyerror"></a>installupdatestask_retryproxyerror

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

    

### <a name="installupdatestask_retryresponse"></a>installupdatestask_retryresponse

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


### <a name="installupdatestask_retrysuccess"></a>installupdatestask_retrysuccess

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


### <a name="installupdatestask_setreopengui"></a>installupdatestask_setreopengui

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


### <a name="msupdate_cli_eventhandler_applyupdates_appids"></a>msupdate_cli_eventhandler_applyupdates_appids

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


### <a name="msupdate_cli_eventhandler_config"></a>msupdate_cli_eventhandler_config

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


### <a name="msupdate_cli_eventhandler_updates"></a>msupdate_cli_eventhandler_updates

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

    
### <a name="msupdate_monitor_progress_downloaded"></a>msupdate_monitor_progress_downloaded

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


### <a name="msupdate_monitor_progress_failure"></a>msupdate_monitor_progress_failure

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

    
### <a name="msupdate_monitor_progress_finished"></a>msupdate_monitor_progress_finished

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


### <a name="msupdate_monitor_progress_queued"></a>msupdate_monitor_progress_queued

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


### <a name="updatecore_appregistration"></a>updatecore_appregistration

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


### <a name="updatecore_loadinglaunchagent"></a>updatecore_loadinglaunchagent

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


### <a name="updatecore_server_connectionfail"></a>updatecore_server_connectionfail

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


### <a name="updatefilterhelper_cannotretrievebuilddate"></a>updatefilterhelper_cannotretrievebuilddate

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


### <a name="updatefilterhelper_invalidresponsefromupdatefiltering"></a>updatefilterhelper_invalidresponsefromupdatefiltering

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


### <a name="updatefilterhelper_missingbuilddate"></a>updatefilterhelper_missingbuilddate

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


### <a name="updatefilterhelper_updatebypassedoldage"></a>updatefilterhelper_updatebypassedoldage

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


### <a name="updatefinder_check_start"></a>updatefinder_check_start

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


### <a name="updatefinder_check_status"></a>updatefinder_check_status

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


### <a name="updatefinder_check_updatefound"></a>updatefinder_check_updatefound

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


### <a name="updatefinder_check_updatenotfound"></a>updatefinder_check_updatenotfound

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


### <a name="updatefinder_check_uptodate"></a>updatefinder_check_uptodate

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


### <a name="updatefinder_offerupdates_minoscheckfail"></a>updatefinder_offerupdates_minoscheckfail

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


### <a name="updatefinder_offerupdates_nullbundleforappid"></a>updatefinder_offerupdates_nullbundleforappid

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


### <a name="updatefinder_offerupdates_updaterulematched"></a>updatefinder_offerupdates_updaterulematched

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

    
### <a name="updatefinder_registeredapps"></a>updatefinder_registeredapps

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

    
### <a name="updatefinder_suite_missingcollateral"></a>updatefinder_suite_missingcollateral

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


### <a name="updatefinder_suite_staleversion"></a>updatefinder_suite_staleversion

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


### <a name="updatefinder_suite_updateapplicable"></a>updatefinder_suite_updateapplicable

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


### <a name="updatefinder_suite_updatenotapplicabledefaultpath"></a>updatefinder_suite_updatenotapplicabledefaultpath

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

    
### <a name="updatefinder_suite_updatenotapplicableversion"></a>updatefinder_suite_updatenotapplicableversion

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


### <a name="updatefinder_suite_updatenotoffered"></a>updatefinder_suite_updatenotoffered

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


### <a name="updatefinder_suite_updateoffered"></a>updatefinder_suite_updateoffered

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


### <a name="updatemanager_checkupdate"></a>updatemanager_checkupdate

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

    
### <a name="updatemanager_updatespending"></a>updatemanager_updatespending

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

    
### <a name="webservices_checkforsilentupdates"></a>webservices_checkforsilentupdates

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


### <a name="webservices_deltaupdater"></a>webservices_deltaupdater

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


### <a name="webservices_serviceaction"></a>webservices_serviceaction

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


### <a name="webservices_serviceaction"></a>webservices_serviceaction

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


### <a name="webservices_serviceresponse"></a>webservices_serviceresponse

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

    
### <a name="webservices_silentupdate"></a>webservices_silentupdate

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



### <a name="webservices_webcontent"></a>webservices_webcontent

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

## <a name="onenote-sync-events"></a>OneNote sinhronizācijas notikumi

### <a name="officeonenotestoragenotebooksyncresult"></a>Office.OneNote.Storage.NotebookSyncResult
 
Šis notikums reģistrē piezīmju grāmatiņas sinhronizācijas rezultātu. Tas tiek lietots, lai, aprēķinot OneNote sinhronizācijas vērtējumu, noteiktu, cik daudz ir unikālu sinhronizācijas mērķu.
 
Tiek apkopoti tālāk norādītie lauki

- **CachedError_Code**A— numurēts vai burtciparu kods, kas tiek lietots, lai noteiktu kešatmiņā saglabātās kļūdas raksturu un/vai to, kāpēc tā radās

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


## <a name="services-configuration-events"></a>Pakalpojumu konfigurācijas notikumi

Pakalpojumu konfigurācija neapkopo nepieciešamos pakalpojumu diagnostikas datu notikumus.

## <a name="telemetry-events"></a>Telemetrijas notikumi

### <a name="office_firstrun_apple_telemetryoptin"></a>Office_FirstRun_Apple_TelemetryOptIn

Šo notikumu apkopo Office programmām, kas tiek darbinātas Apple platformās. Pasākumu lieto, lai pārraudzītu mūsu telemetrijas piedalīšanās plūsmas darbspēju pirmajā palaišanas pieredzē. Mēs apkopojam kodu, kas norāda, kāda veida diagnostikas datu vākšanas opciju lietotājs ir atlasījis.

Tiek apkopoti šādi lauki:

 - **Data_EventId** – kods, kas norāda lietotāja atlasītu diagnostikas datu kolekcijas preferenci.


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

Notikumu izraisa abnormāla lietojumprogrammas apture (piemēram, likvidēts uzdevumu pārvaldnieks, uzkaras programma utt.) Office klienta programmām, ieskaitot, bet ne tikai, Word, Excel, PowerPoint un Outlook. Mēs izmantojam rādītājus par nelabvēlīgu iziešanu no programmas, lai mērītu Office klienta produktu darbspēju. Tas ir uzņēmējdarbībā svarīgs signāls, kuru izmanto Office inženieri, lai noteiktu produktu stabilitāti.

Tiek apkopoti tālāk norādītie lauki.

  - **CrashedAppBuild —** būvējuma versijas identifikators ietekmētajam procesam.

  - **CrashedAppMajor —** galvenās versijas identifikators ietekmētajam procesam.

  - **CrashedAppMinor —** papildversijas identifikators ietekmētajam procesam.

  - **CrashedAppRevision —** būvējuma versijas identifikators ietekmētajam procesam.

  - **CrashedEcsETag —** avarējušā procesa eksperimenta identifikators.

  - **CrashedModuleName —** kļūdainā moduļa nosaukums.

  - **CrashedSessionId —** avarējušā procesa unikāls identifikators.

  - **CrashedSessionInitTime —** laiks, kad ietekmētais process tika sākts.

  - **CrashType —** avārijas veida intervāla identifikators.

  - **DetectionTime —** laiks, kad tika konstatēta neparedzētā izeja.

  - **ExceptionAddress —** adrese programmā, kur kļūme radās.

  - **ExceptionCode —** izņēmuma intervāla identifikators.

  - **HexCrashTag —** unikālais avārijas koda identifikators.

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

  - **UninitLibletId –** kļūdainā avārijas komponenta unikālais identifikators.

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

Tiek apkopoti šādi lauki:

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
