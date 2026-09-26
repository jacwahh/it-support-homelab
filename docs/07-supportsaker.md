[Forside](../README.md) · [Forrige](06-test-av-tilgang.md)

# 7. Vanlige supportsaker

Vi bruker Nora Eidem fra markedsføring til å øve på tre vanlige supportsaker: glemt passord, låst konto og deaktivert konto. Endringene gjøres på DC01, og pålogging testes fra klienten.

## Sak 1: Glemt passord

Nora har glemt passordet og trenger hjelp til å logge på. Før et passord tilbakestilles, må vi bekrefte brukerens identitet etter virksomhetens rutiner.

1. Åpne **Active Directory Users and Computers** på DC01, marker **Accounts** og velg **Find objects in Active Directory Domain Services** på verktøylinjen.
2. Skriv `Nora` i **Name** og velg **Find Now**. Søk gjør det enklere å finne riktig konto når det er mange brukere.
3. Kontroller at du har funnet **Nora Eidem**, høyreklikk på kontoen og velg **Reset Password**.
4. Fyll inn et midlertidig passord i **New password** og **Confirm password**. Merk **User must change password at next logon**, og velg **OK**.

<br>

![Et midlertidig passord settes for Nora, med krav om passordbytte ved neste pålogging.](../images/screenshots/147.png)

*Nora må velge sitt eget passord ved neste pålogging.*

<br>

Formidle det midlertidige passordet til Nora gjennom virksomhetens godkjente kanal. På klienten logger hun på med domenekontoen sin og det midlertidige passordet, og blir bedt om å velge et nytt.

<br>

![Klienten ber Nora endre passordet før hun kan logge på.](../images/screenshots/149.png)

*Klienten krever passordbytte før påloggingen fullføres.*

<br>

![Windows bekrefter at Noras passord er endret.](../images/screenshots/151.png)

*Passordet er endret. Kontroller at Nora får logget på før saken avsluttes.*

## Sak 2: Låst konto

Nora får ikke logget på etter flere forsøk med feil passord. Vi setter først opp kontolåsing, slik at vi kan gjenskape problemet i labben.

### Klargjør kontolåsing

**Gruppepolicy (Group Policy)** brukes til å styre innstillinger sentralt i domenet. Her setter vi en grense på tre mislykkede påloggingsforsøk for å gjøre låsingen enkel å teste.

1. Åpne **Group Policy Management** på DC01 ved å søke etter `gpmc.msc`.
2. Utvid **Forest: LAB.local → Domains → LAB.local**. Høyreklikk **Default Domain Policy** og velg **Edit**.
3. Gå til **Computer Configuration → Policies → Windows Settings → Security Settings → Account Policies → Account Lockout Policy**.
4. Åpne **Account lockout threshold**, angi **3 invalid logon attempts**, og velg **Apply**. Bekreft de foreslåtte følgeendringene med **OK**.
5. Sett de øvrige verdiene som vist i tabellen, og lagre endringene.

| Innstilling | Verdi i labben | Betydning |
| --- | --- | --- |
| Account lockout threshold | 3 forsøk | Antall feilforsøk før kontoen låses |
| Account lockout duration | 30 minutter | Hvor lenge kontoen forblir låst uten manuell opplåsing |
| Reset account lockout counter after | 30 minutter | Telleren nullstilles etter denne tiden uten nye feilforsøk |
| Allow Administrator account lockout | Disabled | Kontolåsing for den innebygde Administrator-kontoen er deaktivert i øvelsen |

Dette er labbens testinnstillinger; i et arbeidsmiljø følger vi virksomhetens sikkerhetsrutiner.

<br>

![Kontolåsingsreglene er satt til tre feilforsøk og 30 minutter.](../images/screenshots/159.png)

*De ferdige innstillingene for kontolåsing i labben.*

### Gjenskap problemet og lås opp kontoen

Når policyen har trådt i kraft, prøver vi å logge på klienten med Noras konto og feil passord til meldingen om låst konto vises.

<br>

![Klienten viser at Noras konto er låst.](../images/screenshots/161.png)

*En låst konto må låses opp, eller vente til låsetiden utløper.*

<br>

1. Finn Nora i **Active Directory Users and Computers** på DC01.
2. Dobbeltklikk på kontoen og åpne fanen **Account**.
3. Merk **Unlock account**, og velg **Apply → OK**.

<br>

![Unlock account er tilgjengelig på fanen Account for Noras låste konto.](../images/screenshots/162.png)

*Unlock account låser opp kontoen uten å endre passordet.*

<br>

Spør Nora om hun husker passordet. Hvis ikke, tilbakestiller vi det som i sak 1. Test deretter pålogging fra klienten. Med innstillingene våre oppheves låsingen også automatisk etter 30 minutter.

## Sak 3: Deaktivert konto

I denne øvelsen er Noras konto deaktivert mens hun er borte. Når hun kommer tilbake fra ferie, ber hun om tilgang igjen. Vi avklarer med HR eller ansvarlig leder at kontoen skal aktiveres før vi gjør endringen.

En **låst konto** skyldes feilforsøk og kan låses opp. En **deaktivert konto** er slått av administrativt og må aktiveres igjen.

1. For å gjenskape situasjonen finner vi Nora i **Active Directory Users and Computers**, høyreklikker på kontoen og velger **Disable Account**.
2. Bekreft meldingen om at kontoen er deaktivert.

<br>

![Active Directory bekrefter at Noras konto er deaktivert.](../images/screenshots/164.png)

*Vi deaktiverer kontoen uten å slette den, slik at den kan aktiveres igjen.*

<br>

3. Når aktivering er godkjent, høyreklikker vi på kontoen og velger **Enable Account**.
4. Bekreft meldingen og be Nora prøve å logge på fra klienten.

<br>

![Active Directory bekrefter at Noras konto er aktivert igjen.](../images/screenshots/166.png)

*Kontoen er aktivert igjen. Kontroller påloggingen før saken avsluttes.*

<br>

Alle stegene og skjermbildene finnes i [bilderegisteret](11-bilderegister.md).

---

[Forside](../README.md) · [Forrige](06-test-av-tilgang.md)
