![Index](https://user-images.githubusercontent.com/98583912/210836880-a20c3d74-edbb-420f-8481-a590d94ad2ed.gif)

[![Telegram](https://img.shields.io/badge/Telegram-CScorza%20%22Indagini%20Telematiche%22-informational)](https://t.me/+kP_uYlc6-345Njc8)
[![**Manuali CScorza**](https://img.shields.io/badge/CScorza-Manuali-green)](https://drive.google.com/drive/folders/14jbOwS4GBSJhXP2BJk-TFCSMIzbZLBlj?usp=share_link)

**INDICE**
||
| :--- |
|[**1 - Elenchi Telefonici - Ricerca Numero**/*Phone Directories - Number Search*](https://github.com/CScorza/OSINT-FORENSICS-MOBILE#elenchi-telefonici---ricerca-numero)|
|[**2 - Analisi Celle Telefoniche**/*Mobile Cell Analysis*](https://github.com/CScorza/OSINT-FORENSICS-MOBILE#analisi-celle-telefoniche)|
|[**3 - Ricerca Operatori Telefonici**/*Mobile Network Operator Search*](https://github.com/CScorza/OSINT-FORENSICS-MOBILE#ricerca-operatori-telefonici)|
|[**4 - Codice IMEI**/*IMEI Cod*](https://github.com/CScorza/OSINT-FORENSICS-MOBILE#codice-imei)|
|[**5 - Applicazioni Android**/*Android Applications*](https://github.com/CScorza/OSINT-FORENSICS-MOBILE#applicazioni-android)|
|[**6 - Messaggistica**/*Messaging*](https://github.com/CScorza/OSINT-FORENSICS-MOBILE#messaggistica)|
|[**7 - Android/iOS Forense**](https://github.com/CScorza/OSINT-FORENSICS-MOBILE#androidios-forense)|
|[**8 - Immagini ed Emulatori Android**/*Android Emulators and Images*](https://github.com/CScorza/OSINT-FORENSICS-MOBILE#emulatori-android)|
|[**9 - LE BEST PRACTICES DELLA MOBILE FORENSICS**/*Best Practices in Mobile Forensics*](https://github.com/CScorza/OSINT-FORENSICS-MOBILE#le-best-practices-della-mobile-forensics)|

![smartphonemagnify-300x240](https://user-images.githubusercontent.com/98583912/190924812-fd8c70f6-8223-47d3-bf8e-b37bec16f2b4.png)

## Elenchi Telefonici - Ricerca Numero/*Phone Directories - Number Search*

|**Italia**||
| :--- | :--- |
|[**Elenchi Telefonici**](http://www.elenchitelefonici.it/home/)||
|[**Agcom**](https://www.agcom.it/numerazionicallcenter)|*Registry of the company/companies operating call center activities**|
|[**Pagine Bianche**](https://www.paginebianche.it/)||

|**Stranieri**/*Foreigners*|
| :--- |
|[**Truecaller**](https://www.truecaller.com/auth/sign-in)|
|[**Sync.me**](https://sync.me/it/)|
|[**Infobel**](https://www.infobel.com/fr/world)|
|[**Webmii**](https://webmii.com/)|
|[**National Cellular Directory**](https://www.nationalcellulardirectory.com/)|
|[**Annuario 118712 Francia**](https://www.118712.fr/) |
|[**Spokeo**](https://www.spokeo.com/)|
|[**Phone Books**](https://www.phonebooks.com/)|
|[**This Number**](https://www.thisnumber.com/)|
|[**Phoneinfoga**](https://demo.phoneinfoga.crvx.fr/#/)|

## Analisi Celle Telefoniche/*Mobile Cell Analysis*
### Sim MOBILE
![2022-09-19 15_59_59-Carta SIM - Wikipedia](https://user-images.githubusercontent.com/98583912/191035415-86079c40-ab6d-4057-a9cc-42de86c0de17.png)
![2022-09-19 16_06_05-Come vengono tracciati i telefoni cellulari - il Valore Italiano](https://user-images.githubusercontent.com/98583912/191036569-2bf6617f-8c62-4aa4-bca5-30cdef2afe0a.png)

**Copertura Rete**/*Network Coverage*

|**ITALIA**|**USA**|**UK**|
| :--- | :--- | :--- |
|[**LTE ITALY - Mappa Antenne 4G**](https://lteitaly.it/it/)|[**Antenna Search**](https://www.antennasearch.com/)|[**MASTDATA**](https://mastdata.com/)|
|[**OpenCelliD**](https://opencellid.org/#zoom=16&lat=37.77888&lon=-122.41941)||
|[**MLS - Overview**](https://location.services.mozilla.com/)||
|[**Unwired Labs Location API**](https://unwiredlabs.com/)||
|[**CellMapper**](https://www.cellmapper.net)||
|[**Infrapedia - Global Internet Infrastructure Map**](https://www.infrapedia.com)||
|[**NPERF**](https://www.nperf.com/it/map/IT/-/-/signal/)||

## Ricerca Operatori Telefonici/ *Mobile Network Operator Search*

|**Generic**|**USA**|
| :--- | :--- |
|[**Twilio - Ricerca per API**](https://www.twilio.com/lookup)|[**Ricerca Numero**](https://www.thisnumber.com/)|
|[**Reverse Phone Lookup - Ricerca per Numero telefonico**](http://www.reversephonelookup.com/)|[**HLRLookup**](https://www.hlrlookup.com/)|
|[**Spy Dialer - Ricerca per Numero Telefonico**](http://spydialer.com/)||
|[**Phone Validator - Ricerca e Convalida numero telefonico**](https://www.phonevalidator.com/index.aspx)||
|[**Free Carrier Lookup - Ricerca Operatore Telefonico**](http://freecarrierlookup.com/)||
|[**SMSC**](https://smsc.ru/testhlr/)||


## Codice IMEI/ *IMEI CODE*
![COdice Imei](https://spyproject.com/img/landing/b/imei1.jpg)
![Imei](https://it.tab-tv.com/wp-content/uploads/2019/11/IMEI-codice-che-significa-spiegazione-it.jpg)
```
International Mobile Equipment Identity

L'IMEI si può visualizzare digitando *#06#, ovvero il comando AT + CGSN.
"Oppure nel retro nella scatola del telefono oppure dietro la batteria dello stesso"
È composto da 15 cifre, suddiviso in 4 parti:

AAAAAA BB CCCCCC D

dove:
- AAAAAA rappresenta il TAC (Type Approval Code) che identifica la casa costruttrice e il modello del telefonino;
- BB rappresenta il FAC (Final Assembly Code) che identifica il luogo di costruzione o di assemblaggio del prodotto;
- CCCCCC indica il numero di serie del cellulare;
- D viene definita SP (Spare) o CD (Check digit) ed è una cifra riservata di controllo che verifica la correttezza del codice IMEI, calcolato con la formula di Luhn.
La sigla TAC, inoltre, ha cambiato significato ed è divenuto acronimo di Type Allocation Code.
Alcuni numeri IMEI hanno 16 cifre; l'ultima parte di due cifre, detta SV (Software Version), indica la versione del firmware dell'apparecchio, mentre la cifra spare è rimossa.

Fonte: 
https://it.wikipedia.org/wiki/International_Mobile_Equipment_Identity
```
```
The IMEI can be viewed by dialing *#06#, or using the AT command + CGSN.
"Alternatively, it can be found on the back of the phone, on the box, or behind the battery."
It consists of 15 digits, divided into 4 parts:

AAAAAA BB CCCCCC D

where:

AAAAAA represents the TAC (Type Approval Code), which identifies the manufacturer and the model of the phone;
BB represents the FAC (Final Assembly Code), which identifies the location where the product was manufactured or assembled;
CCCCCC indicates the serial number of the phone;
D is the SP (Spare) or CD (Check digit), a reserved control digit that verifies the correctness of the IMEI, calculated using the Luhn formula.
Additionally, the acronym TAC has changed its meaning and is now referred to as the Type Allocation Code.
Some IMEI numbers have 16 digits; the last two digits, called SV (Software Version), indicate the firmware version of the device, while the spare digit is removed.
```
|[**SNDeepInfo**](https://sndeep.info/en)|[**IMEI tools**](http://imei-number.com/imei-number-lookup/)|[**Nobbi**](http://www.nobbi.com/tacquery.php)|[**IMEI.info**](https://www.imei.info/)
| :--- | :--- | :--- | :--- |
|[**CONTROLLO IMEI/IMEI Check**](https://www.imei.info/)|[**Telefono sotto controllo**](https://www.telefonosottocontrollo.com/imei-marca-modello-cellulare/)|[**Analisi dei numeri IMEI**](https://www.numberingplans.com/?page=analysis&sub=imeinr)|

## Applicazioni Android

|**BTS**|**WIFI**|**APP**|
| :--- | :--- | :--- |
|[**Securcube BTS Tracker**](https://play.google.com/store/apps/details?id=net.securcube.btstracker&hl=en_US&gl=US)|[**WIGLE - Wifi**](https://play.google.com/store/apps/details?id=net.wigle.wigleandroid&hl=en_US&gl=US)|[**FAKE GPS**](https://play.google.com/store/apps/details?id=com.gsmartstudio.fakegps&hl=it&gl=US)|
|[**Cell Tower Locator**](https://play.google.com/store/apps/details?id=ru.v_a_v.celltowerlocator&hl=en&gl=US)|[**Fing - Network Tools**](https://play.google.com/store/apps/details?id=com.overlook.android.fing&hl=it&gl=US)|
|[**Opensignal - 5G, 4G Speed Test**](https://play.google.com/store/apps/details?id=com.staircase3.opensignal&hl=en&gl=US)|[**WifiAnalyzer**](https://play.google.com/store/apps/details?id=cz.webprovider.wifianalyzer&hl=it&gl=US)|
|[**NetMonitor Cell Signal Logging**](https://play.google.com/store/apps/details?id%3Dru.v_a_v.netmonitor)|[**SignalMonitoring**](https://play.google.com/store/apps/details?id=com.signalmonitoring.gsmsignalmonitoring&hl=it&gl=US)|
|[**CellMapper**](https://play.google.com/store/apps/details?id=cellmapper.net.cellmapper&hl=it&gl=US)|[**SpeedTest**](https://play.google.com/store/apps/details?id=org.zwanoo.android.speedtest&hl=it&gl=US)|


# MESSANGERS App
## WHATSAPP

![Whatsapp_37229**](https://user-images.githubusercontent.com/98583912/190934139-b3b41790-aecd-4a9d-9b00-59249a70d0eb.png)

**Esportazione Chat**/ *Export a Chat*

![esportazione-chat-whatsapp**](https://user-images.githubusercontent.com/98583912/190933662-164db90f-eda8-42da-9bd7-d21034feb6d5.jpg)

|**Analisi**|**Ricerca Gruppi**|**Altri Strumenti**|
| :--- | :--- | :--- |
|[**Chat Visualizer**](https://chatvisualizer.com/)|[**Whatsgrouplink**](https://whatsgrouplink.com/#0-pubg-whatsapp-group)|[**Watools**](https://watools.io/download-profile-picture)|
[**WhatsAnalyze**](https://whatsanalyze-80665.web.app/)|||



## Telegram

![telegram_icon-icons com_72055](https://user-images.githubusercontent.com/98583912/190934092-0fb3047e-697f-4d75-946b-a94dde6870d4.png)

- [**Telegram Web**](https://web.telegram.org/k/)

**Esportazione Chat Telegram** /*Export a Chat*

![esportare-chat-telegram](https://user-images.githubusercontent.com/98583912/190934176-ba345478-258a-44ab-b8e4-73789135c84a.jpg)

|**Ricerca Gruppi**/ *Group Search*||||
| :--- | :--- | :--- | :--- |
|[**telegramdb**](https://telegramdb.org/)|[**Telegram Search Engine**](https://xtea.io/ts_en.html)|[**Global Telegram Database**](https://t.me/s/privatelinks)|[**TGStat - Catalogo canali e gruppi Telegram**](https://tgstat.com/)|
|[**Telegago**](https://cse.google.com/cse?&cx=006368593537057042503:efxu7xprihg#gsc.tab=0)|[**SocialFinder**](https://socialfinder.app/list/Telegram)|[**lyzem.com**](https://lyzem.com/)|[**Telegram Channels**](https://telegramchannels.me/)|


# Android/iOS Forense

![Senzanome](https://user-images.githubusercontent.com/98583912/190924780-e187ac6b-4512-454e-8ff0-fcc62a16f75c.png)


|[**Gsmarena**](https://www.gsmarena.com/)|**Catalogo e specifiche dei smartphone**|*Catalog and specifications of smartphones*|
| :--- | :--- | :--- |
|[**Mobile Phone Museum**](https://www.mobilephonemuseum.com/catalogue/)|**Collezione storica dei telefoni cellulari e Smartphone**|*Historical collection of mobile phones and smartphones*|
|[**Cruscotto**](https://wiki.sei.cmu.edu/confluence/display/android)|**Android Secure Coding Standard*||
|[**HardReset**](https://www.hardreset.info/)|**Cancellare tutti i dati sul tuo dispositivo**|*Erase all data on your device*|
|[**DoubleBlak Digital Forensics**](https://www.doubleblak.com/index.php)||
|[**3uTools - IOS**](http://www.3u.com/)|**Recupero delle informazioni sul disposiitvo e dei contenuti**|*Recovery of information and content on the device*|
|[**ADBGui - Android ADB**](https://github.com/hexadezi/adbGUI)|**Sideload, netstats e info utili**||

## Smontaggio Smartphone
*🇬🇧- Smartphone Disassembly*

![image](https://user-images.githubusercontent.com/98583912/231369444-292715d1-82f2-4d87-9815-d45c4fa69e00.png)

|![Android](https://user-images.githubusercontent.com/98583912/231368017-e05e5429-bdc4-4e9e-bacf-772a4f282764.gif)|![Apple](https://user-images.githubusercontent.com/98583912/231368043-40229ce9-68b5-435b-910f-44ffb7fb504d.gif)|![Windows Phone jpg](https://user-images.githubusercontent.com/98583912/231368105-dc26c445-5dfb-4d5e-892a-10d35cc6d171.gif)|![Linux Phone](https://user-images.githubusercontent.com/98583912/231368209-c8261462-363c-498c-bdb9-8ecd473aa681.gif)|![Altri](https://user-images.githubusercontent.com/98583912/231368408-df40d903-c65d-4ba8-9478-0bd806005dec.gif)
| :---: | :---: | :---: | :---: | :---: | 
|[**Anroid**](https://it.ifixit.com/Device/Other_OS_Phone)|[**Apple Iphone**](https://it.ifixit.com/Device/iPhone)|[**Windows**](https://it.ifixit.com/Device/Windows_Phone)|[**Linux Phone**](https://it.ifixit.com/Device/Linux_Phone)|[**Altri Device**](https://it.ifixit.com/Device/Other_OS_Phone)|

**Attrezzatura Utile**
*🇬🇧- Useful Equipment*
|[**Tappettino**](https://www.amazon.it/isolamento-riparazione-smontaggio-Workstation-manutenzione/dp/B07ZQKLGQ6)|[**Set Cacciaviti**](https://www.amazon.it/Housolution-Cacciavite-Ricaricabile-Magnetiche-Illuminazione/dp/B09Q5W5P53/ref=sr_1_38?__mk_it_IT=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=GY52RARAR8AJ&keywords=set%2Bcacciaviti%2Briparazione%2Btelefono%2Belettrico%2Briparazione%2Btelefoni&qid=1681280943&s=industrial&sprefix=set%2Bcacciaviti%2Briparazione%2Btelefono%2Belettrico%2Briparazione%2Btelefon%2Cindustrial%2C215&sr=1-38&th=1)
| :---: | :---: |

**Il tutto è puramente indicativo**
*🇬🇧- Everything is purely indicative*


## Tools Github

![icon](https://user-images.githubusercontent.com/98583912/231379177-72ede23c-cf91-4c4b-9089-2fec3e350ad9.svg)

|[**GitHub - Scrcpy**](https://github.com/Genymobile/scrcpy/releases)|**Questa applicazione fornisce la visualizzazione e il controllo dei dispositivi Android collegati tramite USB o tramite TCP/IP. Non richiede alcun accesso come root. Funziona su GNU/Linux, Windows e macOS**|*🇬🇧- This application provides the visualization and control of Android devices connected via USB or TCP/IP. It does not require root access. It works on GNU/Linux, Windows, and macOS.*|
| :--- | :--- | :--- |
|[**GitHub - Andriller CE**](https://github.com/den4uk/andriller)|**Software con una raccolta di strumenti forensi per smartphone**|🇬🇧- Software with a collection of forensic tools for smartphones*|
|[**GitHub - ALEAPP**](https://github.com/abrignoni/ALEAPP)|**Android registra eventi e protobuf parser**|🇬🇧- *Android logs events and protobuf parser*|
|[**GitHub - MEAT**](https://github.com/jfarley248/MEAT)|**MEAT - Mobile Evidence Acquisition Toolkit**||
|[**GitHub - AvillaForensics**](https://github.com/AvillaDaniel/AvillaForensics)|**Free Tools Mobile Forensics Avilla Forensics**|
|[**GitHub - Mobile Verification Toolkit**](https://github.com/mvt-project/mvt)||
|[**GitHub - ashishb / Android-Security-Awesome**](https://github.com/ashishb/android-security-awesome)|**Una raccolta di risorse relative alla sicurezza Android**|*🇬🇧- A collection of resources related to Android security*|

# Android Emulator
- [**Emulatori Android**](https://github.com/CScorza/DistroForensics#emulaotri-android)
- [**Android Studio**](https://developer.android.com/studio)

# BEST PRACTICES FORENSICS MOBILE

|[**CScorza - Best Practices di Digital Forensics.pdf**](https://github.com/CScorza/OSINT-FORENSICS-MOBILE/files/11068492/CScorza.-.Best.Practices.di.Digital.Forensics.pdf)|||
| :--- | :--- | :--- |
|[**SWGDE Best Practices for Mobile Phone Forensics.pdf**](https://github.com/CScorza/OSINT-FORENSICS-MOBILE/files/9600300/SWGDE.Best.Practices.for.Mobile.Phone.Forensics.pdf)|[**TipiLoschi.net - Best Practices per iPhone e iDevice**](https://www.tipiloschi.net/drupal/best-practice-iphone-ios)|[**Mobile Devices**](https://www.nist.gov/itl/ssd/software-quality-group/computer-forensics-tool-testing-program-cftt/cftt-technical/mobile)|
|[**Guidelines on Mobile DeviceForensics**](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-101r1.pdf)|[**ACPO Good Practice Guide for Digital Evidence v5**](https://www.digital-detective.net/digital-forensics-documents/ACPO_Good_Practice_Guide_for_Digital_Evidence_v5.pdf)|

# N.B.
![Attensione](https://user-images.githubusercontent.com/98583912/200124134-52263b4c-0332-4218-80d3-b5f7b0cfd97d.gif)

🇮🇹- Qualsiasi strumento inserito, può essere usato sia per fini professionali che per fini didattici.
Ai fini professionali si consiglia l'uso di strumenti idonei per evitare qualisasi forma di tracciamento (Ambiente virtualizzato etc) e di seguire le varie Best pratics. Per realizzare un ambiente virtuale seguire questi repository:

*🇬🇧 -Any tool included can be used for both professional and educational purposes.
For professional purposes, it is recommended to use appropriate tools to avoid any form of tracking (Virtualized environment, etc.) and to follow the various Best Practices. To create a virtual environment, refer to the following repositories:*

|[**DataProtection - Rendersi Anonimi nel Web**](https://github.com/CScorza/Data-Protection#rendersi-anonimi-nel-web)|[**DistroForensics**](https://github.com/CScorza/DistroForensics)|
| :--- | :--- |
