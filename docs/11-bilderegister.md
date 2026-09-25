# Bilderegister

[Forside](../README.md)

Her finner du alle 166 skjermbilder fra labben, sortert etter kapitlene i guiden. Åpne steget du vil se nærmere på.

## 1. Labmiljø og nettverk

<details>
<summary>Installer VirtualBox og opprett serveren – vis figur 1–6</summary>

### Figur 1

![VirtualBox lastes ned fra den offisielle nettsiden](../images/screenshots/001.png)

*VirtualBox lastes ned fra den offisielle nettsiden.*

### Figur 2

![VirtualBox Manager: opprett en ny virtuell maskin med New](../images/screenshots/002.png)

*VirtualBox Manager: opprett en ny virtuell maskin med New.*

### Figur 3

![Den virtuelle serveren får navn og installasjonsmedium](../images/screenshots/003.png)

*Den virtuelle serveren får navn og installasjonsmedium.*

### Figur 4

![Serveren får 16 GB arbeidsminne og fire virtuelle prosessorer](../images/screenshots/004.png)

*Serveren får 16 GB arbeidsminne og fire virtuelle prosessorer.*

### Figur 5

![Serverens virtuelle disk settes til 50 GB](../images/screenshots/005.png)

*Serverens virtuelle disk settes til 50 GB.*

### Figur 6

![DC01 er opprettet i VirtualBox og klar til å starte](../images/screenshots/006.png)

*DC01 er opprettet i VirtualBox og klar til å starte.*

</details>

<details>
<summary>Installer Windows Server – vis figur 7–11</summary>

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

![Passordet til Administrator-kontoen opprettes](../images/screenshots/010.png)

*Passordet til Administrator-kontoen opprettes.*

### Figur 11

![Ctrl+Alt+Delete sendes til den virtuelle serveren fra VirtualBox-menyen](../images/screenshots/011.png)

*Ctrl+Alt+Delete sendes til den virtuelle serveren fra VirtualBox-menyen.*

</details>

<details>
<summary>Gi serveren navnet DC01 – vis figur 12–14</summary>

### Figur 12

![Server Manager viser datamaskinnavnet før navneendringen](../images/screenshots/012.png)

*Server Manager viser datamaskinnavnet før navneendringen.*

### Figur 13

![System Properties åpnes for å endre servernavnet](../images/screenshots/013.png)

*System Properties åpnes for å endre servernavnet.*

### Figur 14

![Servernavnet endres til DC01](../images/screenshots/014.png)

*Servernavnet endres til DC01.*

</details>

<details>
<summary>Sett opp nettverkskortene – vis figur 15–19</summary>

### Figur 15

![Avslutningsmenyen åpnes i VirtualBox](../images/screenshots/015.png)

*Avslutningsmenyen åpnes i VirtualBox.*

### Figur 16

![VirtualBox ber om bekreftelse før maskinen slås av med Power Off](../images/screenshots/016.png)

*VirtualBox ber om bekreftelse før maskinen slås av med Power Off.*

### Figur 17

![Innstillingene åpnes for den avslåtte serveren](../images/screenshots/017.png)

*Innstillingene åpnes for den avslåtte serveren.*

### Figur 18

![Adapter 1 på DC01 kobles til Host-only-nettverket](../images/screenshots/018.png)

*Adapter 1 på DC01 kobles til Host-only-nettverket.*

### Figur 19

![Adapter 2 bruker NAT for utgående forbindelser fra DC01](../images/screenshots/019.png)

*Adapter 2 bruker NAT for utgående forbindelser fra DC01.*

</details>

<details>
<summary>Finn DHCP-området i VirtualBox – vis figur 20–21</summary>

### Figur 20

![Nettverksinnstillingene i VirtualBox åpnes via File → Tools → Network](../images/screenshots/020.png)

*Nettverksinnstillingene i VirtualBox åpnes via File → Tools → Network.*

### Figur 21

![DHCP-området kontrolleres før vi velger en fast IP-adresse til serveren](../images/screenshots/021.png)

*DHCP-området kontrolleres før vi velger en fast IP-adresse til serveren.*

</details>

<details>
<summary>Gi serveren en fast IP-adresse – vis figur 22–25</summary>

### Figur 22

![Nettverkstilkoblinger åpnes på serveren](../images/screenshots/022.png)

*Nettverkstilkoblinger åpnes på serveren.*

### Figur 23

![Egenskapene åpnes for serverens nettverkskort på labnettverket](../images/screenshots/023.png)

*Egenskapene åpnes for serverens nettverkskort på labnettverket.*

### Figur 24

![IPv4-innstillingene åpnes for nettverkskortet](../images/screenshots/024.png)

*IPv4-innstillingene åpnes for nettverkskortet.*

### Figur 25

![DC01 får IP-adressen 192.168.56.55, masken 255.255.255.0 og samme adresse som DNS-server](../images/screenshots/025.png)

*DC01 får IP-adressen 192.168.56.55, masken 255.255.255.0 og samme adresse som DNS-server.*

</details>

<details>
<summary>Installer Guest Additions – vis figur 47–54</summary>

### Figur 47

![Guest Additions-CD-en monteres fra VirtualBox Devices-menyen](../images/screenshots/047.png)

*Guest Additions-CD-en monteres fra VirtualBox Devices-menyen.*

### Figur 48

![Filutforskeren åpnes inne i den virtuelle maskinen](../images/screenshots/048.png)

*Filutforskeren åpnes inne i den virtuelle maskinen.*

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

![Den virtuelle maskinen startes på nytt etter installasjonen](../images/screenshots/054.png)

*Den virtuelle maskinen startes på nytt etter installasjonen.*

</details>

<details>
<summary>Juster skjerm og skalering – vis figur 55–58</summary>

### Figur 55

![VirtualBox viser skjerm- og skaleringsvalg etter installasjonen](../images/screenshots/055.png)

*VirtualBox viser skjerm- og skaleringsvalg etter installasjonen.*

### Figur 56

![Den virtuelle maskinen vises med større skjermflate](../images/screenshots/056.png)

*Den virtuelle maskinen vises med større skjermflate.*

### Figur 57

![Display settings åpnes i Windows](../images/screenshots/057.png)

*Display settings åpnes i Windows.*

### Figur 58

![Skalering endres for å gjøre tekst og ikoner større](../images/screenshots/058.png)

*Skalering endres for å gjøre tekst og ikoner større.*

</details>

## 2. Active Directory

<details>
<summary>Installer AD DS – vis figur 26–37</summary>

### Figur 26

![Server Manager åpnes for å installere AD DS-rollen](../images/screenshots/026.png)

*Server Manager åpnes for å installere AD DS-rollen.*

### Figur 27

![Add roles and features starter rolleinstallasjonen](../images/screenshots/027.png)

*Add roles and features starter rolleinstallasjonen.*

### Figur 28

![Veiviseren viser hva som bør være klart før rolleinstallasjonen](../images/screenshots/028.png)

*Veiviseren viser hva som bør være klart før rolleinstallasjonen.*

### Figur 29

![Role-based or feature-based installation velges](../images/screenshots/029.png)

*Role-based or feature-based installation velges.*

### Figur 30

![DC01 velges som serveren rollen skal installeres på](../images/screenshots/030.png)

*DC01 velges som serveren rollen skal installeres på.*

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

![AD DS er installert. Serveren skal nå settes opp som domenekontroller](../images/screenshots/037.png)

*AD DS er installert. Serveren skal nå settes opp som domenekontroller.*

</details>

<details>
<summary>Opprett domenet og gjør DC01 til domenekontroller – vis figur 38–46</summary>

### Figur 38

![Varselikonet åpner neste steg i oppsettet av domenekontrolleren](../images/screenshots/038.png)

*Varselikonet åpner neste steg i oppsettet av domenekontrolleren.*

### Figur 39

![Promote this server to a domain controller velges](../images/screenshots/039.png)

*Promote this server to a domain controller velges.*

### Figur 40

![En ny skog opprettes med domenenavnet LAB.local](../images/screenshots/040.png)

*En ny skog opprettes med domenenavnet LAB.local.*

### Figur 41

![Innstillingene for domenekontrolleren velges, og passord for gjenoppretting angis](../images/screenshots/041.png)

*Innstillingene for domenekontrolleren velges, og passord for gjenoppretting angis.*

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

![Innstillingene for domenekontrolleren oppsummeres før installasjon](../images/screenshots/045.png)

*Innstillingene for domenekontrolleren oppsummeres før installasjon.*

### Figur 46

![Veiviseren kontrollerer at serveren er klar for installasjon](../images/screenshots/046.png)

*Veiviseren kontrollerer at serveren er klar for installasjon.*

</details>

## 3. Windows-klienten

<details>
<summary>Opprett klienten i VirtualBox – vis figur 59–63</summary>

### Figur 59

![En ny virtuell maskin opprettes for Windows-klienten](../images/screenshots/059.png)

*En ny virtuell maskin opprettes for Windows-klienten.*

### Figur 60

![Windows 11 velges som installasjonsmedium](../images/screenshots/060.png)

*Windows 11 velges som installasjonsmedium.*

### Figur 61

![Klienten får 8 GB arbeidsminne og tre virtuelle prosessorer](../images/screenshots/061.png)

*Klienten får 8 GB arbeidsminne og tre virtuelle prosessorer.*

### Figur 62

![Klientens virtuelle disk settes til 80 GB](../images/screenshots/062.png)

*Klientens virtuelle disk settes til 80 GB.*

### Figur 63

![Den virtuelle klienten er klar til å starte](../images/screenshots/063.png)

*Den virtuelle klienten er klar til å starte.*

</details>

<details>
<summary>Installer Windows 11 Pro – vis figur 64–74</summary>

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

![Installasjonen fortsetter uten produktnøkkel](../images/screenshots/068.png)

*Installasjonen fortsetter uten produktnøkkel.*

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

![Installasjonsvalgene oppsummeres før Windows installeres](../images/screenshots/072.png)

*Installasjonsvalgene oppsummeres før Windows installeres.*

### Figur 73

![Windows 11 installeres](../images/screenshots/073.png)

*Windows 11 installeres.*

### Figur 74

![Windows fortsetter installasjonen etter omstart](../images/screenshots/074.png)

*Windows fortsetter installasjonen etter omstart.*

</details>

<details>
<summary>Velg region, tastatur og maskinnavn – vis figur 75–78</summary>

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

</details>

<details>
<summary>Opprett en lokal konto – vis figur 79–85</summary>

### Figur 79

![Sign-in options åpnes i jobb- eller skoleoppsettet](../images/screenshots/079.png)

*Sign-in options åpnes i jobb- eller skoleoppsettet.*

### Figur 80

![Domain join instead velges for å opprette en lokal konto før klienten meldes inn i domenet](../images/screenshots/080.png)

*Domain join instead velges for å opprette en lokal konto før klienten meldes inn i domenet.*

### Figur 81

![Set up for work or school velges i førstegangsoppsettet](../images/screenshots/081.png)

*Set up for work or school velges i førstegangsoppsettet.*

### Figur 82

![Den lokale klientkontoen får navnet Ola Nordmann](../images/screenshots/082.png)

*Den lokale klientkontoen får navnet Ola Nordmann.*

### Figur 83

![Passordet til den lokale kontoen opprettes](../images/screenshots/083.png)

*Passordet til den lokale kontoen opprettes.*

### Figur 84

![Passordet til den lokale kontoen bekreftes](../images/screenshots/084.png)

*Passordet til den lokale kontoen bekreftes.*

### Figur 85

![Sikkerhetsspørsmål settes opp for den lokale kontoen](../images/screenshots/085.png)

*Sikkerhetsspørsmål settes opp for den lokale kontoen.*

</details>

<details>
<summary>Velg personverninnstillinger og fullfør oppsettet – vis figur 86–92</summary>

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

</details>

<details>
<summary>Koble klienten til labnettverket – vis figur 93</summary>

### Figur 93

![Klienten kobles til samme Host-only-nettverk som serveren](../images/screenshots/093.png)

*Klienten kobles til samme Host-only-nettverk som serveren.*

</details>

<details>
<summary>Sett klientens DNS-server – vis figur 112–115</summary>

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

![Klienten får IP-adresse automatisk og bruker 192.168.56.55 som DNS-server](../images/screenshots/115.png)

*Klienten får IP-adresse automatisk og bruker 192.168.56.55 som DNS-server.*

</details>

<details>
<summary>Meld klienten inn i domenet – vis figur 116–122</summary>

### Figur 116

![Kommandolinjen åpnes fra Start-menyen](../images/screenshots/116.png)

*Kommandolinjen åpnes fra Start-menyen.*

### Figur 117

![sysdm.cpl åpner systemegenskapene på klienten](../images/screenshots/117.png)

*sysdm.cpl åpner systemegenskapene på klienten.*

### Figur 118

![Klientens System Properties viser CLT-001 i en arbeidsgruppe](../images/screenshots/118.png)

*Klientens System Properties viser CLT-001 i en arbeidsgruppe.*

### Figur 119

![LAB.local angis som domene for CLT-001](../images/screenshots/119.png)

*LAB.local angis som domene for CLT-001.*

### Figur 120

![En konto med rettighet til å melde klienten inn i domenet oppgis](../images/screenshots/120.png)

*En konto med rettighet til å melde klienten inn i domenet oppgis.*

### Figur 121

![Velkomstmeldingen bekrefter vellykket tilknytning til LAB.local](../images/screenshots/121.png)

*Velkomstmeldingen bekrefter vellykket tilknytning til LAB.local.*

### Figur 122

![Klienten må startes på nytt etter domenetilknytningen](../images/screenshots/122.png)

*Klienten må startes på nytt etter domenetilknytningen.*

</details>

## 4. Brukere, grupper og OU-er

<details>
<summary>Opprett OU-ene Accounts og Groups – vis figur 94–97</summary>

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

</details>

<details>
<summary>Opprett brukerkontoene – vis figur 98–102</summary>

### Figur 98

![En ny bruker opprettes i Accounts](../images/screenshots/098.png)

*En ny bruker opprettes i Accounts.*

### Figur 99

![Eirik Solbergs navn og påloggingsnavn eirsol fylles inn](../images/screenshots/099.png)

*Eirik Solbergs navn og påloggingsnavn eirsol fylles inn.*

### Figur 100

![Brukeren får et midlertidig passord som må endres ved neste pålogging](../images/screenshots/100.png)

*Brukeren får et midlertidig passord som må endres ved neste pålogging.*

### Figur 101

![Oppsummering før Eiriks konto opprettes](../images/screenshots/101.png)

*Oppsummering før Eiriks konto opprettes.*

### Figur 102

![Alle ti labkontoene vises i Accounts](../images/screenshots/102.png)

*Alle ti labkontoene vises i Accounts.*

</details>

<details>
<summary>Opprett avdelingsgruppene – vis figur 103–105</summary>

### Figur 103

![En ny gruppe opprettes i Groups](../images/screenshots/103.png)

*En ny gruppe opprettes i Groups.*

### Figur 104

![HR opprettes som global sikkerhetsgruppe](../images/screenshots/104.png)

*HR opprettes som global sikkerhetsgruppe.*

### Figur 105

![De fem avdelingsgruppene vises i katalogen](../images/screenshots/105.png)

*De fem avdelingsgruppene vises i katalogen.*

</details>

<details>
<summary>Legg brukerne i riktig gruppe – vis figur 106–111</summary>

### Figur 106

![Eiriks brukeregenskaper åpnes for å endre medlemskap](../images/screenshots/106.png)

*Eiriks brukeregenskaper åpnes for å endre medlemskap.*

### Figur 107

![Egenskapene for Eiriks brukerkonto vises](../images/screenshots/107.png)

*Egenskapene for Eiriks brukerkonto vises.*

### Figur 108

![Member Of viser Domain Users før avdelingsgruppen legges til](../images/screenshots/108.png)

*Member Of viser Domain Users før avdelingsgruppen legges til.*

### Figur 109

![IT søkes opp som gruppenavn i LAB.local](../images/screenshots/109.png)

*IT søkes opp som gruppenavn i LAB.local.*

### Figur 110

![Check Names bekrefter at IT-gruppen finnes](../images/screenshots/110.png)

*Check Names bekrefter at IT-gruppen finnes.*

### Figur 111

![Eirik er nå medlem av IT og Domain Users](../images/screenshots/111.png)

*Eirik er nå medlem av IT og Domain Users.*

</details>

## 5. Delte mapper og rettigheter

<details>
<summary>Opprett mappene – vis figur 123–128</summary>

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

</details>

<details>
<summary>Del HR-mappen og sett delingsrettigheter – vis figur 129–133</summary>

### Figur 129

![HR-mappens egenskaper åpnes](../images/screenshots/129.png)

*HR-mappens egenskaper åpnes.*

### Figur 130

![Sharing-fanen åpnes for å dele HR-mappen](../images/screenshots/130.png)

*Sharing-fanen åpnes for å dele HR-mappen.*

### Figur 131

![HR aktiveres som deling i Advanced Sharing](../images/screenshots/131.png)

*HR aktiveres som deling i Advanced Sharing.*

### Figur 132

![Everyone får Full Control under delingsrettighetene](../images/screenshots/132.png)

*Everyone får Full Control under delingsrettighetene.*

### Figur 133

![Delingsinnstillingene bekreftes i Advanced Sharing](../images/screenshots/133.png)

*Delingsinnstillingene bekreftes i Advanced Sharing.*

</details>

<details>
<summary>Gi HR-gruppen Modify-tilgang med NTFS – vis figur 134–138</summary>

### Figur 134

![Security-fanen åpnes for å endre NTFS-rettighetene](../images/screenshots/134.png)

*Security-fanen åpnes for å endre NTFS-rettighetene.*

### Figur 135

![Edit åpner redigering av NTFS-rettighetene](../images/screenshots/135.png)

*Edit åpner redigering av NTFS-rettighetene.*

### Figur 136

![HR-gruppen søkes opp og bekreftes med Check Names](../images/screenshots/136.png)

*HR-gruppen søkes opp og bekreftes med Check Names.*

### Figur 137

![HR-gruppen får Modify-tilgang til HR-mappen](../images/screenshots/137.png)

*HR-gruppen får Modify-tilgang til HR-mappen.*

### Figur 138

![Security-fanen viser de valgte tillatelsene for HR](../images/screenshots/138.png)

*Security-fanen viser de valgte tillatelsene for HR.*

</details>

## 6. Test av tilgang

<details>
<summary>Logg på med en domenekonto – vis figur 139</summary>

### Figur 139

![Maja logger på klienten med domenekontoen sin](../images/screenshots/139.png)

*Maja logger på klienten med domenekontoen sin.*

</details>

<details>
<summary>Koble til HR-mappen som nettverksstasjon – vis figur 140–142</summary>

### Figur 140

![Map network drive åpnes fra klientens File Explorer](../images/screenshots/140.png)

*Map network drive åpnes fra klientens File Explorer.*

### Figur 141

![Nettverksstasjonen Z: kobles til \\LAB.LOCAL\HR](../images/screenshots/141.png)

*Nettverksstasjonen Z: kobles til \\LAB.LOCAL\HR.*

### Figur 142

![HR-delingen åpnes fra klienten og viser undermappene](../images/screenshots/142.png)

*HR-delingen åpnes fra klienten og viser undermappene.*

</details>

<details>
<summary>Test at brukeren kan opprette en mappe – vis figur 143</summary>

### Figur 143

![Maja oppretter en mappe i HR-delingen for å teste skrivetilgangen](../images/screenshots/143.png)

*Maja oppretter en mappe i HR-delingen for å teste skrivetilgangen.*

</details>

## 7. Vanlige supportsaker

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

![Et midlertidig passord settes med krav om passordbytte ved neste pålogging](../images/screenshots/147.png)

*Et midlertidig passord settes med krav om passordbytte ved neste pålogging.*

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

![Kontoen låses i 30 minutter etter tre mislykkede påloggingsforsøk](../images/screenshots/159.png)

*Kontoen låses i 30 minutter etter tre mislykkede påloggingsforsøk.*

### Figur 160

![Klienten viser en feilmelding ved feil passord](../images/screenshots/160.png)

*Klienten viser en feilmelding ved feil passord.*

### Figur 161

![Klienten viser at kontoen er låst](../images/screenshots/161.png)

*Klienten viser at kontoen er låst.*

### Figur 162

![Unlock account låser opp Noras konto](../images/screenshots/162.png)

*Unlock account låser opp Noras konto.*

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
