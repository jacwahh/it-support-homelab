# IT-support-homelab

I denne Windows-labben med Active Directory (AD) setter vi opp brukere, grupper og delte mapper, og løser vanlige supportsaker. Målet er å lære mer om profesjonelle IT-miljøer gjennom praktisk arbeid i et simulert miljø.

Den detaljerte fremgangsmåten er dokumentert med skjermbilder i [bilderegisteret](docs/11-bilderegister.md). Se der hvis du lurer på et konkret steg eller en innstilling.

## Følg guiden

1. [Labmiljø og nettverk](docs/01-labmiljo.md)
2. [Active Directory](docs/02-active-directory.md)
3. [Windows-klienten](docs/03-klient.md)
4. [Brukere, grupper og organisatoriske enheter](docs/04-brukere-grupper-ou.md)
5. [Delte mapper og rettigheter](docs/05-delte-mapper.md)
6. [Test av tilgang](docs/06-test-av-tilgang.md)
7. [Vanlige supportsaker](docs/07-supportsaker.md)

## Dette bruker vi

| Del | Oppsett i labben |
| --- | --- |
| Vertsmaskin | Windows 11 med VirtualBox 7.2.8 |
| Server | `DC01` — Windows Server 2022 Standard Evaluation, Desktop Experience |
| Klient | `CLT-001` — Windows 11 Pro |

Serveren fungerer både som domenekontroller, navnetjener og filserver. Navnetjenesten **Domain Name System (DNS)** hjelper klienten med å finne domenet og serverens tjenester. Det holder labben enkel. I et produksjonsmiljø ville man normalt brukt en dedikert filserver.

Alle personnavn i labben er fiktive.

[Kilder](docs/kilder.md)

## Les guiden lokalt

Last ned via **Code → Download ZIP**, pakk ut hele ZIP-filen og åpne `index.html` i nettleseren. Behold `images`-mappen sammen med filen, slik at bildene vises.
