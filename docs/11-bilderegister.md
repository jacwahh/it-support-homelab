# Bilderegister

[Forside](../README.md)

Her finner du alle 166 skjermbilder fra labben, steg for steg. Åpne en seksjon for å se fremgangsmåten.

## Serverinstallasjon og nettverk

<details>
<summary>Vis figur 1–25</summary>

### Figur 1

![VirtualBox: offisiell nedlastingsside og versjonen brukt i labben](../images/screenshots/001.png)

*VirtualBox: offisiell nedlastingsside og versjonen brukt i labben.*

### Figur 2

![VirtualBox Manager: opprett en ny virtuell maskin med New](../images/screenshots/002.png)

*VirtualBox Manager: opprett en ny virtuell maskin med New.*

### Figur 3

![Serverens VM-navn og installasjonsmedium; profilnavnet i filstiene er sladdet](../images/screenshots/003.png)

*Serverens VM-navn og installasjonsmedium; profilnavnet i filstiene er sladdet.*

### Figur 4

![Serverens ressurser: 16 GB arbeidsminne og fire virtuelle prosessorer i denne labben](../images/screenshots/004.png)

*Serverens ressurser: 16 GB arbeidsminne og fire virtuelle prosessorer i denne labben.*

### Figur 5

![Serverens virtuelle disk på 50 GB; profilnavnet i lagringsstien er sladdet](../images/screenshots/005.png)

*Serverens virtuelle disk på 50 GB; profilnavnet i lagringsstien er sladdet.*

### Figur 6

![DC01 er opprettet i VirtualBox og klar til å starte](../images/screenshots/006.png)

*DC01 er opprettet i VirtualBox og klar til å starte.*

### Figur 7

![Windows Server 2022 Standard Evaluation med Desktop Experience velges](../images/screenshots/007.png)

*Windows Server 2022 Standard Evaluation med Desktop Experience velges.*

### Figur 8

![Custom velges for en ny installasjon på den virtuelle disken](../images/screenshots/008.png)

*Custom velges for en ny installasjon på den virtuelle disken.*

### Figur 9

![Serverens tomme virtuelle disk velges som installasjonsmål](../images/screenshots/009.png)

*Serverens tomme virtuelle disk velges som installasjonsmål.*

### Figur 10

![Administratorpassord settes; feltene i bildet er tomme](../images/screenshots/010.png)

*Administratorpassord settes; feltene i bildet er tomme.*

### Figur 11

![VirtualBox-menyen brukes til å sende Ctrl+Alt+Delete til gjesten](../images/screenshots/011.png)

*VirtualBox-menyen brukes til å sende Ctrl+Alt+Delete til gjesten.*

### Figur 12

![Server Manager viser datamaskinnavnet før navneendringen](../images/screenshots/012.png)

*Server Manager viser datamaskinnavnet før navneendringen.*

### Figur 13

![System Properties åpnes for å endre servernavnet](../images/screenshots/013.png)

*System Properties åpnes for å endre servernavnet.*

### Figur 14

![Windows-navnet settes til DC01 før domenekontrolleroppsettet](../images/screenshots/014.png)

*Windows-navnet settes til DC01 før domenekontrolleroppsettet.*

### Figur 15

![Avslutning via VirtualBox; bruk normalt Shut down i Windows](../images/screenshots/015.png)

*Avslutning via VirtualBox; bruk normalt Shut down i Windows.*

### Figur 16

![Power Off-advarsel: dette kutter strømmen og er ikke anbefalt normal avslutning](../images/screenshots/016.png)

*Power Off-advarsel: dette kutter strømmen og er ikke anbefalt normal avslutning.*

### Figur 17

![Innstillinger åpnes for den avslåtte server-VM-en](../images/screenshots/017.png)

*Innstillinger åpnes for den avslåtte server-VM-en.*

### Figur 18

![Adapter 1 på DC01 kobles til Host-only-nettverket](../images/screenshots/018.png)

*Adapter 1 på DC01 kobles til Host-only-nettverket.*

### Figur 19

![Adapter 2 bruker NAT for utgående forbindelser fra DC01](../images/screenshots/019.png)

*Adapter 2 bruker NAT for utgående forbindelser fra DC01.*

### Figur 20

![VirtualBox Network-verktøyet åpnes fra File og Tools](../images/screenshots/020.png)

*VirtualBox Network-verktøyet åpnes fra File og Tools.*

### Figur 21

![VirtualBox DHCP-område kontrolleres før valg av fast serveradresse](../images/screenshots/021.png)

*VirtualBox DHCP-område kontrolleres før valg av fast serveradresse.*

### Figur 22

![Nettverkstilkoblinger åpnes på serveren](../images/screenshots/022.png)

*Nettverkstilkoblinger åpnes på serveren.*

### Figur 23

![Egenskaper åpnes for det aktuelle nettverkskortet](../images/screenshots/023.png)

*Egenskaper åpnes for det aktuelle nettverkskortet.*

### Figur 24

![IPv4-egenskaper velges for labkortet](../images/screenshots/024.png)

*IPv4-egenskaper velges for labkortet.*

### Figur 25

![DC01 får 192.168.56.55 med nettverksmasken 255.255.255.0 og peker til seg selv som DNS-server](../images/screenshots/025.png)

*DC01 får 192.168.56.55 med nettverksmasken 255.255.255.0 og peker til seg selv som DNS-server.*

</details>

## Active Directory

<details>
<summary>Vis figur 26–46</summary>

### Figur 26

![Server Manager åpnes for å installere AD DS-rollen](../images/screenshots/026.png)

*Server Manager åpnes for å installere AD DS-rollen.*

### Figur 27

![Add roles and features starter rolleinstallasjonen](../images/screenshots/027.png)

*Add roles and features starter rolleinstallasjonen.*

### Figur 28

![Veiviserens innledende kontrollpunkter](../images/screenshots/028.png)

*Veiviserens innledende kontrollpunkter.*

### Figur 29

![Role-based or feature-based installation velges](../images/screenshots/029.png)

*Role-based or feature-based installation velges.*

### Figur 30

![DC01 velges som målserver; serveren har flere nettverksadresser](../images/screenshots/030.png)

*DC01 velges som målserver; serveren har flere nettverksadresser.*

### Figur 31

![Active Directory Domain Services markeres i rollelisten](../images/screenshots/031.png)

*Active Directory Domain Services markeres i rollelisten.*

### Figur 32

![Nødvendige administrasjonsverktøy legges til med Add Features](../images/screenshots/032.png)

*Nødvendige administrasjonsverktøy legges til med Add Features.*

### Figur 33

![AD DS er valgt i rollelisten](../images/screenshots/033.png)

*AD DS er valgt i rollelisten.*

### Figur 34

![Tilleggsfunksjoner vises før installasjonen fortsetter](../images/screenshots/034.png)

*Tilleggsfunksjoner vises før installasjonen fortsetter.*

### Figur 35

![Informasjon om AD DS og behovet for DNS](../images/screenshots/035.png)

*Informasjon om AD DS og behovet for DNS.*

### Figur 36

![Rolleinstallasjonen bekreftes med Install](../images/screenshots/036.png)

*Rolleinstallasjonen bekreftes med Install.*

### Figur 37

![AD DS-rollen er installert; promotering gjenstår](../images/screenshots/037.png)

*AD DS-rollen er installert; promotering gjenstår.*

### Figur 38

![Varselikonet viser at etterkonfigurering er nødvendig](../images/screenshots/038.png)

*Varselikonet viser at etterkonfigurering er nødvendig.*

### Figur 39

![Promote this server to a domain controller velges](../images/screenshots/039.png)

*Promote this server to a domain controller velges.*

### Figur 40

![En ny skog opprettes med domenenavnet LAB.local](../images/screenshots/040.png)

*En ny skog opprettes med domenenavnet LAB.local.*

### Figur 41

![DNS, Global Catalog og funksjonsnivå vises; DSRM-passordet er maskert](../images/screenshots/041.png)

*DNS, Global Catalog og funksjonsnivå vises; DSRM-passordet er maskert.*

### Figur 42

![Advarsel om manglende DNS-delegering i laboppsettet](../images/screenshots/042.png)

*Advarsel om manglende DNS-delegering i laboppsettet.*

### Figur 43

![Plassering av AD-databasen, loggene og den delte systemmappen SYSVOL](../images/screenshots/043.png)

*Plassering av AD-databasen, loggene og den delte systemmappen SYSVOL.*

### Figur 44

![NetBIOS-navnet settes til LAB](../images/screenshots/044.png)

*NetBIOS-navnet settes til LAB.*

### Figur 45

![Oppsummering av domenekontrollerkonfigurasjonen](../images/screenshots/045.png)

*Oppsummering av domenekontrollerkonfigurasjonen.*

### Figur 46

![Forutsetningskontroll med advarsler som må vurderes før installasjon](../images/screenshots/046.png)

*Forutsetningskontroll med advarsler som må vurderes før installasjon.*

</details>

## Guest Additions og skjerm

<details>
<summary>Vis figur 47–58</summary>

### Figur 47

![Guest Additions-CD-en monteres fra VirtualBox Devices-menyen](../images/screenshots/047.png)

*Guest Additions-CD-en monteres fra VirtualBox Devices-menyen.*

### Figur 48

![File Explorer åpnes i gjesteoperativsystemet](../images/screenshots/048.png)

*File Explorer åpnes i gjesteoperativsystemet.*

### Figur 49

![Guest Additions-CD-stasjonen finnes under This PC](../images/screenshots/049.png)

*Guest Additions-CD-stasjonen finnes under This PC.*

### Figur 50

![Windows-installasjonsprogrammet for Guest Additions velges](../images/screenshots/050.png)

*Windows-installasjonsprogrammet for Guest Additions velges.*

### Figur 51

![Guest Additions-installasjonen starter](../images/screenshots/051.png)

*Guest Additions-installasjonen starter.*

### Figur 52

![Installasjonsplassering for Guest Additions](../images/screenshots/052.png)

*Installasjonsplassering for Guest Additions.*

### Figur 53

![Komponentvalg for Guest Additions](../images/screenshots/053.png)

*Komponentvalg for Guest Additions.*

### Figur 54

![Gjesten må startes på nytt etter Guest Additions](../images/screenshots/054.png)

*Gjesten må startes på nytt etter Guest Additions.*

### Figur 55

![VirtualBox viser skjerm- og skaleringsvalg etter installasjonen](../images/screenshots/055.png)

*VirtualBox viser skjerm- og skaleringsvalg etter installasjonen.*

### Figur 56

![Gjesten vises med større tilgjengelig skjermflate](../images/screenshots/056.png)

*Gjesten vises med større tilgjengelig skjermflate.*

### Figur 57

![Display settings åpnes i Windows](../images/screenshots/057.png)

*Display settings åpnes i Windows.*

### Figur 58

![Skalering endres for å gjøre tekst og ikoner større](../images/screenshots/058.png)

*Skalering endres for å gjøre tekst og ikoner større.*

</details>

## Klientinstallasjon

<details>
<summary>Vis figur 59–93</summary>

### Figur 59

![En ny VM opprettes for Windows-klienten](../images/screenshots/059.png)

*En ny VM opprettes for Windows-klienten.*

### Figur 60

![Windows 11-ISO velges; profilnavnet i filstiene er sladdet](../images/screenshots/060.png)

*Windows 11-ISO velges; profilnavnet i filstiene er sladdet.*

### Figur 61

![Klienten får 8 GB arbeidsminne og tre virtuelle prosessorer i labben](../images/screenshots/061.png)

*Klienten får 8 GB arbeidsminne og tre virtuelle prosessorer i labben.*

### Figur 62

![Klientens virtuelle disk settes til 80 GB; profilnavnet i lagringsstien er sladdet](../images/screenshots/062.png)

*Klientens virtuelle disk settes til 80 GB; profilnavnet i lagringsstien er sladdet.*

### Figur 63

![Windows-klientens VM er klar til å starte](../images/screenshots/063.png)

*Windows-klientens VM er klar til å starte.*

### Figur 64

![En tast trykkes for å starte installasjonen fra ISO-en](../images/screenshots/064.png)

*En tast trykkes for å starte installasjonen fra ISO-en.*

### Figur 65

![Språk og region velges i Windows 11-installasjonen](../images/screenshots/065.png)

*Språk og region velges i Windows 11-installasjonen.*

### Figur 66

![Norsk tastaturoppsett velges](../images/screenshots/066.png)

*Norsk tastaturoppsett velges.*

### Figur 67

![Ren Windows-installasjon velges på den virtuelle maskinen](../images/screenshots/067.png)

*Ren Windows-installasjon velges på den virtuelle maskinen.*

### Figur 68

![Ingen produktnøkkel er skrevet inn i dette installasjonstrinnet](../images/screenshots/068.png)

*Ingen produktnøkkel er skrevet inn i dette installasjonstrinnet.*

### Figur 69

![Windows 11 Pro velges for domenetilknytning](../images/screenshots/069.png)

*Windows 11 Pro velges for domenetilknytning.*

### Figur 70

![Lisensvilkårene vises før installasjonen](../images/screenshots/070.png)

*Lisensvilkårene vises før installasjonen.*

### Figur 71

![Den tomme virtuelle disken på 80 GB velges](../images/screenshots/071.png)

*Den tomme virtuelle disken på 80 GB velges.*

### Figur 72

![Installasjonsoppsummering; bildet viser også en merknad om systemkrav](../images/screenshots/072.png)

*Installasjonsoppsummering; bildet viser også en merknad om systemkrav.*

### Figur 73

![Windows 11 installeres](../images/screenshots/073.png)

*Windows 11 installeres.*

### Figur 74

![Installasjonsfremdrift under omstart](../images/screenshots/074.png)

*Installasjonsfremdrift under omstart.*

### Figur 75

![Norge velges som region i førstegangsoppsettet](../images/screenshots/075.png)

*Norge velges som region i førstegangsoppsettet.*

### Figur 76

![Norsk tastatur velges i førstegangsoppsettet](../images/screenshots/076.png)

*Norsk tastatur velges i førstegangsoppsettet.*

### Figur 77

![Et ekstra tastaturoppsett hoppes over](../images/screenshots/077.png)

*Et ekstra tastaturoppsett hoppes over.*

### Figur 78

![Windows-maskinnavnet settes til CLT-001](../images/screenshots/078.png)

*Windows-maskinnavnet settes til CLT-001.*

### Figur 79

![Sign-in options åpnes i jobb- eller skoleoppsettet](../images/screenshots/079.png)

*Sign-in options åpnes i jobb- eller skoleoppsettet.*

### Figur 80

![Domain join instead gir lokal oppretting før senere domenetilknytning](../images/screenshots/080.png)

*Domain join instead gir lokal oppretting før senere domenetilknytning.*

### Figur 81

![Set up for work or school; dette valget kommer før de to foregående dialogene i arbeidsflyten](../images/screenshots/081.png)

*Set up for work or school; dette valget kommer før de to foregående dialogene i arbeidsflyten.*

### Figur 82

![Den lokale klientkontoen får navnet Ola Nordmann](../images/screenshots/082.png)

*Den lokale klientkontoen får navnet Ola Nordmann.*

### Figur 83

![Passord til lokal konto oppgis; innholdet er maskert](../images/screenshots/083.png)

*Passord til lokal konto oppgis; innholdet er maskert.*

### Figur 84

![Passordet til lokal konto bekreftes; innholdet er maskert](../images/screenshots/084.png)

*Passordet til lokal konto bekreftes; innholdet er maskert.*

### Figur 85

![Sikkerhetsspørsmål vises, men svarfeltet er tomt](../images/screenshots/085.png)

*Sikkerhetsspørsmål vises, men svarfeltet er tomt.*

### Figur 86

![Posisjonstilgang avslås i personverninnstillingene](../images/screenshots/086.png)

*Posisjonstilgang avslås i personverninnstillingene.*

### Figur 87

![Find my device avslås i personverninnstillingene](../images/screenshots/087.png)

*Find my device avslås i personverninnstillingene.*

### Figur 88

![Bare nødvendige diagnosedata velges](../images/screenshots/088.png)

*Bare nødvendige diagnosedata velges.*

### Figur 89

![Valgfri forbedring av håndskrift og inntasting avslås](../images/screenshots/089.png)

*Valgfri forbedring av håndskrift og inntasting avslås.*

### Figur 90

![Personlige tilbud avslås](../images/screenshots/090.png)

*Personlige tilbud avslås.*

### Figur 91

![Windows fullfører oppdateringer i førstegangsoppsettet](../images/screenshots/091.png)

*Windows fullfører oppdateringer i førstegangsoppsettet.*

### Figur 92

![Påloggingsskjerm for den lokale kontoen Ola Nordmann](../images/screenshots/092.png)

*Påloggingsskjerm for den lokale kontoen Ola Nordmann.*

### Figur 93

![Klienten kobles til samme Host-only-nettverk som serveren](../images/screenshots/093.png)

*Klienten kobles til samme Host-only-nettverk som serveren.*

</details>

## OU-er, brukere og grupper

<details>
<summary>Vis figur 94–111</summary>

### Figur 94

![Active Directory Users and Computers åpnes på DC01](../images/screenshots/094.png)

*Active Directory Users and Computers åpnes på DC01.*

### Figur 95

![New Organizational Unit velges under LAB.local](../images/screenshots/095.png)

*New Organizational Unit velges under LAB.local.*

### Figur 96

![OU-en Accounts opprettes med beskyttelse mot utilsiktet sletting](../images/screenshots/096.png)

*OU-en Accounts opprettes med beskyttelse mot utilsiktet sletting.*

### Figur 97

![OU-en Groups opprettes med beskyttelse mot utilsiktet sletting](../images/screenshots/097.png)

*OU-en Groups opprettes med beskyttelse mot utilsiktet sletting.*

### Figur 98

![En ny bruker opprettes i Accounts](../images/screenshots/098.png)

*En ny bruker opprettes i Accounts.*

### Figur 99

![Eirik Solbergs navn og påloggingsnavn eirsol fylles inn](../images/screenshots/099.png)

*Eirik Solbergs navn og påloggingsnavn eirsol fylles inn.*

### Figur 100

![Midlertidig passord er maskert og må endres ved neste pålogging](../images/screenshots/100.png)

*Midlertidig passord er maskert og må endres ved neste pålogging.*

### Figur 101

![Oppsummering før Eiriks konto opprettes](../images/screenshots/101.png)

*Oppsummering før Eiriks konto opprettes.*

### Figur 102

![Alle ti labkontoene vises i Accounts](../images/screenshots/102.png)

*Alle ti labkontoene vises i Accounts.*

### Figur 103

![En ny gruppe opprettes i Groups](../images/screenshots/103.png)

*En ny gruppe opprettes i Groups.*

### Figur 104

![HR opprettes som global sikkerhetsgruppe](../images/screenshots/104.png)

*HR opprettes som global sikkerhetsgruppe.*

### Figur 105

![De fem avdelingsgruppene vises i katalogen](../images/screenshots/105.png)

*De fem avdelingsgruppene vises i katalogen.*

### Figur 106

![Eiriks brukeregenskaper åpnes for å endre medlemskap](../images/screenshots/106.png)

*Eiriks brukeregenskaper åpnes for å endre medlemskap.*

### Figur 107

![Brukerens egenskaper; kontaktfeltene i bildet er tomme](../images/screenshots/107.png)

*Brukerens egenskaper; kontaktfeltene i bildet er tomme.*

### Figur 108

![Member Of viser Domain Users før avdelingsgruppen legges til](../images/screenshots/108.png)

*Member Of viser Domain Users før avdelingsgruppen legges til.*

### Figur 109

![IT søkes opp som gruppenavn i LAB.local](../images/screenshots/109.png)

*IT søkes opp som gruppenavn i LAB.local.*

### Figur 110

![Check Names har løst IT til et gruppeobjekt](../images/screenshots/110.png)

*Check Names har løst IT til et gruppeobjekt.*

### Figur 111

![Eirik er nå medlem av IT og Domain Users](../images/screenshots/111.png)

*Eirik er nå medlem av IT og Domain Users.*

</details>

## Domenetilknytning

<details>
<summary>Vis figur 112–122</summary>

### Figur 112

![Nettverkstilkoblinger åpnes på klienten](../images/screenshots/112.png)

*Nettverkstilkoblinger åpnes på klienten.*

### Figur 113

![Klientens Ethernet-egenskaper åpnes](../images/screenshots/113.png)

*Klientens Ethernet-egenskaper åpnes.*

### Figur 114

![Klientens IPv4-egenskaper velges](../images/screenshots/114.png)

*Klientens IPv4-egenskaper velges.*

### Figur 115

![Klienten beholder DHCP for IP og får 192.168.56.55 som DNS](../images/screenshots/115.png)

*Klienten beholder DHCP for IP og får 192.168.56.55 som DNS.*

### Figur 116

![En kommandolinje åpnes; bildet viser serverens skrivebord som illustrasjon](../images/screenshots/116.png)

*En kommandolinje åpnes; bildet viser serverens skrivebord som illustrasjon.*

### Figur 117

![sysdm.cpl kjøres på klienten fra den lokale kontoen](../images/screenshots/117.png)

*sysdm.cpl kjøres på klienten fra den lokale kontoen.*

### Figur 118

![Klientens System Properties viser CLT-001 i en arbeidsgruppe](../images/screenshots/118.png)

*Klientens System Properties viser CLT-001 i en arbeidsgruppe.*

### Figur 119

![LAB.local angis som domene for CLT-001](../images/screenshots/119.png)

*LAB.local angis som domene for CLT-001.*

### Figur 120

![En konto med innmeldingsrettighet oppgis; administratorpassordet er maskert](../images/screenshots/120.png)

*En konto med innmeldingsrettighet oppgis; administratorpassordet er maskert.*

### Figur 121

![Velkomstmeldingen bekrefter vellykket tilknytning til LAB.local](../images/screenshots/121.png)

*Velkomstmeldingen bekrefter vellykket tilknytning til LAB.local.*

### Figur 122

![Klienten må startes på nytt etter domenetilknytningen](../images/screenshots/122.png)

*Klienten må startes på nytt etter domenetilknytningen.*

</details>

## Delte mapper og rettigheter

<details>
<summary>Vis figur 123–138</summary>

### Figur 123

![File Explorer åpnes på serveren](../images/screenshots/123.png)

*File Explorer åpnes på serveren.*

### Figur 124

![Serverens C-disk åpnes](../images/screenshots/124.png)

*Serverens C-disk åpnes.*

### Figur 125

![En ny mappe opprettes på serveren](../images/screenshots/125.png)

*En ny mappe opprettes på serveren.*

### Figur 126

![Hovedmappen C:\Shares er opprettet](../images/screenshots/126.png)

*Hovedmappen C:\Shares er opprettet.*

### Figur 127

![Avdelingsmappene Finance, HR, IT, Marketing og Sales er opprettet](../images/screenshots/127.png)

*Avdelingsmappene Finance, HR, IT, Marketing og Sales er opprettet.*

### Figur 128

![HR Forms og Resumes er opprettet under HR](../images/screenshots/128.png)

*HR Forms og Resumes er opprettet under HR.*

### Figur 129

![HR-mappens egenskaper åpnes](../images/screenshots/129.png)

*HR-mappens egenskaper åpnes.*

### Figur 130

![Sharing-fanen åpnes; mappen er ennå ikke delt i dette bildet](../images/screenshots/130.png)

*Sharing-fanen åpnes; mappen er ennå ikke delt i dette bildet.*

### Figur 131

![HR aktiveres som deling i Advanced Sharing](../images/screenshots/131.png)

*HR aktiveres som deling i Advanced Sharing.*

### Figur 132

![Everyone får Full Control på delingsnivå i labmodellen](../images/screenshots/132.png)

*Everyone får Full Control på delingsnivå i labmodellen.*

### Figur 133

![Delingsinnstillingene bekreftes i Advanced Sharing](../images/screenshots/133.png)

*Delingsinnstillingene bekreftes i Advanced Sharing.*

### Figur 134

![Security-fanen før HR-gruppen legges til](../images/screenshots/134.png)

*Security-fanen før HR-gruppen legges til.*

### Figur 135

![NTFS-redigering åpnes med eksisterende identiteter i listen](../images/screenshots/135.png)

*NTFS-redigering åpnes med eksisterende identiteter i listen.*

### Figur 136

![HR-gruppen søkes opp og bekreftes med Check Names](../images/screenshots/136.png)

*HR-gruppen søkes opp og bekreftes med Check Names.*

### Figur 137

![HR-gruppen får Modify på HR-mappen](../images/screenshots/137.png)

*HR-gruppen får Modify på HR-mappen.*

### Figur 138

![Security-fanen viser de valgte tillatelsene for HR](../images/screenshots/138.png)

*Security-fanen viser de valgte tillatelsene for HR.*

</details>

## Tilgangstest fra klienten

<details>
<summary>Vis figur 139–143</summary>

### Figur 139

![Maja logger på LAB; passordfeltet er maskert](../images/screenshots/139.png)

*Maja logger på LAB; passordfeltet er maskert.*

### Figur 140

![Map network drive åpnes fra klientens File Explorer](../images/screenshots/140.png)

*Map network drive åpnes fra klientens File Explorer.*

### Figur 141

![Z: kobles til HR via LAB.LOCAL, den dokumenterte fungerende domenebaserte stien](../images/screenshots/141.png)

*Z: kobles til HR via LAB.LOCAL, den dokumenterte fungerende domenebaserte stien.*

### Figur 142

![HR-delingen åpnes fra klienten og viser undermappene](../images/screenshots/142.png)

*HR-delingen åpnes fra klienten og viser undermappene.*

### Figur 143

![Maja oppretter en mappe i HR-delingen som positiv tilgangstest](../images/screenshots/143.png)

*Maja oppretter en mappe i HR-delingen som positiv tilgangstest.*

</details>


## Supportsaker

<details>
<summary>Glemt passord – vis figur 144–151</summary>

### Figur 144

![Søk etter brukere i Active Directory Users and Computers](../images/screenshots/144.png)

*Søk etter brukere i Active Directory Users and Computers.*

### Figur 145

![Nora Eidem finnes med Find Now](../images/screenshots/145.png)

*Nora Eidem finnes med Find Now.*

### Figur 146

![Reset Password velges for Noras konto](../images/screenshots/146.png)

*Reset Password velges for Noras konto.*

### Figur 147

![Midlertidig passord settes med krav om passordbytte](../images/screenshots/147.png)

*Midlertidig passord settes med krav om passordbytte.*

### Figur 148

![Active Directory bekrefter at passordet er tilbakestilt](../images/screenshots/148.png)

*Active Directory bekrefter at passordet er tilbakestilt.*

### Figur 149

![Klienten krever passordbytte før pålogging](../images/screenshots/149.png)

*Klienten krever passordbytte før pålogging.*

### Figur 150

![Nora fyller inn et nytt passord](../images/screenshots/150.png)

*Nora fyller inn et nytt passord.*

### Figur 151

![Windows bekrefter at passordet er endret](../images/screenshots/151.png)

*Windows bekrefter at passordet er endret.*

</details>

<details>
<summary>Låst konto – vis figur 152–162</summary>

### Figur 152

![Group Policy Management åpnes med gpmc.msc](../images/screenshots/152.png)

*Group Policy Management åpnes med gpmc.msc.*

### Figur 153

![Domenet vises i Group Policy Management](../images/screenshots/153.png)

*Domenet vises i Group Policy Management.*

### Figur 154

![Default Domain Policy åpnes for redigering](../images/screenshots/154.png)

*Default Domain Policy åpnes for redigering.*

### Figur 155

![Account Lockout Policy viser innstillingene for kontolåsing](../images/screenshots/155.png)

*Account Lockout Policy viser innstillingene for kontolåsing.*

### Figur 156

![Account lockout threshold åpnes for endring](../images/screenshots/156.png)

*Account lockout threshold åpnes for endring.*

### Figur 157

![Windows foreslår følgeendringer til kontolåsingen](../images/screenshots/157.png)

*Windows foreslår følgeendringer til kontolåsingen.*

### Figur 158

![Terskelen settes til tre mislykkede påloggingsforsøk](../images/screenshots/158.png)

*Terskelen settes til tre mislykkede påloggingsforsøk.*

### Figur 159

![Ferdige innstillinger: tre forsøk og 30 minutter](../images/screenshots/159.png)

*Ferdige innstillinger: tre forsøk og 30 minutter.*

### Figur 160

![Klienten viser feil passord](../images/screenshots/160.png)

*Klienten viser feil passord.*

### Figur 161

![Klienten viser at kontoen er låst](../images/screenshots/161.png)

*Klienten viser at kontoen er låst.*

### Figur 162

![Unlock account brukes på Noras konto](../images/screenshots/162.png)

*Unlock account brukes på Noras konto.*

</details>

<details>
<summary>Deaktivere og aktivere konto – vis figur 163–166</summary>

### Figur 163

![Disable Account velges for Nora](../images/screenshots/163.png)

*Disable Account velges for Nora.*

### Figur 164

![Active Directory bekrefter at kontoen er deaktivert](../images/screenshots/164.png)

*Active Directory bekrefter at kontoen er deaktivert.*

### Figur 165

![Enable Account velges for Nora](../images/screenshots/165.png)

*Enable Account velges for Nora.*

### Figur 166

![Active Directory bekrefter at kontoen er aktivert](../images/screenshots/166.png)

*Active Directory bekrefter at kontoen er aktivert.*

</details>
