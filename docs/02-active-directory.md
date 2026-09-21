[Forside](../README.md) · [Forrige](01-labmiljo.md) · [Neste](03-klient.md)


# 2. Active Directory

**Active Directory Domain Services (AD DS)** samler brukere, grupper og datamaskiner i en felles katalog. Det gjør at vi kan administrere kontoer sentralt i stedet for å opprette dem på hver enkelt PC.

Et **domene** er området disse kontoene og maskinene tilhører. Vårt domene heter `LAB.local`. Serveren som kjører AD DS, kalles en **domenekontroller** — her er det DC01.

## Slik henger labben sammen

En **organisatorisk enhet (Organizational Unit, OU)** er en administrativ mappe i AD. Vi bruker Accounts til brukerkontoer og Groups til sikkerhetsgrupper.

![Skogen LAB.local inneholder domenet LAB.local. DC01 er domenekontroller og CLT-001 er klient. Accounts er OU-en for brukere, mens Groups er OU-en for sikkerhetsgrupper.](../images/diagrams/skog-domene-lab.png)

**Skogen** er den ytterste rammen. Den kan inneholde flere domener, men i labben har vi bare ett. Skogen får navn etter det første domenet, så begge heter `LAB.local`.

**DC01 er maskinen som kjører AD DS**, mens `LAB.local` er domenet den betjener. Klienten `CLT-001` kobles til dette domenet. Inne i AD bruker vi OU-ene **Accounts** og **Groups** til å organisere brukerkontoer og sikkerhetsgrupper; disse oppretter vi i kapittel 4.

## Installer AD DS

1. Åpne **Server Manager → Add roles and features**.
2. Velg **Role-based or feature-based installation** og DC01 som målserver.
3. Merk **Active Directory Domain Services** og godta **Add Features**.
4. Fortsett gjennom veiviseren og velg **Install**.

Rollen er nå installert. Neste steg er å gjøre serveren til domenekontroller.


![AD DS-rollen er valgt med de nødvendige administrasjonsverktøyene.](../images/screenshots/033.png)

*AD DS-rollen er valgt med de nødvendige administrasjonsverktøyene.*


## Opprett domenet

1. Åpne varselflagget i Server Manager og velg **Promote this server to a domain controller**.
2. Velg **Add a new forest** og skriv `LAB.local`. En skog er den overordnede AD-strukturen; her oppretter vi en skog med ett domene.
3. Behold **DNS server** og **Global Catalog** valgt, slik bildene viser.
4. Sett et passord for **Directory Services Restore Mode (DSRM)**, gjenopprettingsmodusen for AD.
5. Kontroller at domenets kortnavn blir `LAB` i feltet **NetBIOS domain name**, og fortsett med katalogplasseringene som vises i veiviseren.
6. Les oppsummeringen og eventuelle advarsler i forutsetningskontrollen. Velg deretter **Install**.
7. Serveren starter på nytt når oppsettet er ferdig.


![LAB.local opprettes som labbens første domene.](../images/screenshots/040.png)

*LAB.local opprettes som labbens første domene.*


## Hvorfor trenger vi DNS?

Klienten bruker DC01 (`192.168.56.55`) som **DNS-server** for å finne domenet `LAB.local` og domenekontrolleren. Dette gjør at klienten kan kobles til domenet og brukerne kan logge på med domenekontoene sine.


---

[Forside](../README.md) · [Forrige](01-labmiljo.md) · [Neste](03-klient.md)
