[Forside](../README.md) · [Forrige](02-active-directory.md) · [Neste](04-brukere-grupper-ou.md)

# 3. Windows-klienten

Klienten er PC-en labbrukerne skal logge på. Vi bruker **Windows 11 Pro**, som støtter tilknytning til et lokalt AD-domene.

## Installer klienten

1. Opprett en ny VM i VirtualBox og velg Windows 11-ISO-en.
2. Labben bruker **8 GB arbeidsminne, 3 virtuelle prosessorer og 80 GB disk**.
3. Start installasjonen, velg språk og tastatur, og installer **Windows 11 Pro** på den tomme virtuelle disken.
4. Sett Windows-maskinnavnet til `CLT-001`.
5. I førstegangsoppsettet velger vi **Set up for work or school → Sign-in options → Domain join instead** for å opprette den lokale kontoen **Ola Nordmann**.
6. Sett passord, fullfør sikkerhetsspørsmålene og velg personverninnstillinger. Installer gjerne Guest Additions som beskrevet i kapittel 1.

Valgene i førstegangsoppsettet kan variere mellom Windows-versjoner. **Domain join instead** oppretter her en lokal konto; selve tilknytningen til LAB.local gjør vi nedenfor.

I denne labben ga to virtuelle prosessorer svart skjerm, mens tre fungerte. Bruk en VM-konfigurasjon som oppfyller systemkravene til din Windows-utgave.

<br>

![Windows 11 Pro velges under installasjonen.](../images/screenshots/069.png)

*Windows 11 Pro velges under installasjonen.*

## Koble klienten til labnettverket

Koble klienten til det samme virtuelle nettverket som serveren:

1. Slå av Windows 11 inne i den virtuelle klientmaskinen.
2. Marker klientmaskinen i VirtualBox, og åpne **Settings → Network → Adapter 1**.
3. Kontroller at **Enable Network Adapter** er merket av, og sett **Attached to** til **Host-only Adapter**.
4. Under **Name** velger du det samme nettverksnavnet som er valgt for **Adapter 1** på DC01. I denne labben er det **VirtualBox Host-Only Ethernet Adapter**.
5. Klikk på **OK**, og start klientmaskinen igjen.

Serveren og klienten er nå koblet til samme labnettverk, slik at de kan kommunisere med hverandre.

Åpne **View network connections**, høyreklikk **Ethernet** og velg **Properties**. Marker **Internet Protocol Version 4** og klikk på **Properties**. Behold automatisk IP-adresse og sett **Preferred DNS server** til `192.168.56.55`.

<br>

![Klienten får IP-adresse automatisk, men bruker DC01 som DNS-server.](../images/screenshots/115.png)

*Klienten får IP-adresse automatisk, men bruker DC01 som DNS-server.*

## Meld klienten inn i domenet

1. Åpne **Run** eller en terminal og skriv `sysdm.cpl`.
2. Velg **Computer Name → Change**.
3. Merk **Domain**, skriv `LAB.local` og velg **OK**.
4. Oppgi en domenekonto som har rettighet til å melde inn maskinen. I labben brukes Administrator.
5. Bekreft velkomstmeldingen og start klienten på nytt.

<br>

![Velkomstmeldingen bekrefter at klienten er meldt inn i LAB.local.](../images/screenshots/121.png)

*Velkomstmeldingen bekrefter at klienten er meldt inn i LAB.local.*

<br>

Etter omstart kan domenebrukerne logge på. Vi oppretter dem i neste kapittel. Den lokale kontoen Ola Nordmann og kontoene i LAB er separate kontoer.

---

[Forside](../README.md) · [Forrige](02-active-directory.md) · [Neste](04-brukere-grupper-ou.md)
