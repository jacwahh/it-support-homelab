[Forside](../README.md) · [Forrige](05-delte-mapper.md) · [Neste](07-supportsaker.md)


# 6. Test av tilgang

Vi tester fra klienten som **Maja Hovland**, som er medlem av HR-gruppen.

1. Logg på CLT-001 med Majas domenekonto. Bruk hennes påloggingsnavn, og kontroller at du logger på `LAB`.
2. Endre passordet dersom dette kreves ved første pålogging.
3. Åpne **File Explorer → This PC → Map network drive**.
4. Velg en ledig stasjonsbokstav, for eksempel `Z:`.
5. Skriv `\\LAB.LOCAL\HR` under **Folder**, og velg **Finish**.


![HR-delingen kobles til Z: via LAB.LOCAL, slik den ble brukt i labben.](../images/screenshots/141.png)

*HR-delingen kobles til Z: via LAB.LOCAL, slik den ble brukt i labben.*


Stasjonsbokstaven er bare en praktisk snarvei på klienten. Det er gruppemedlemskapet og rettighetene på serveren som bestemmer tilgangen.

Når delingen åpnes, ser vi **HR Forms** og **Resumes**. Opprett en ny mappe for å kontrollere at Maja også kan skrive til delingen.


![Maja oppretter en ny mappe i HR-delingen.](../images/screenshots/143.png)

*Maja oppretter en ny mappe i HR-delingen.*


## Resultat

Den dokumenterte testen viser at Maja kan åpne HR-delingen og opprette en mappe. Det bekrefter at denne delen av oppsettet fungerer fra klienten.

Labben har nå en domenekontroller, en tilknyttet klient, ti brukere, fem avdelingsgrupper og delte mapper med gruppetildelte rettigheter.


---

[Forside](../README.md) · [Forrige](05-delte-mapper.md) · [Neste](07-supportsaker.md)
