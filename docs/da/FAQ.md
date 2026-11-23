# Ofte stillede spørgsmål · Camper BU22

*[English version](../en/FAQ.md)*

### Hvad gør appen egentlig?
Den genstarter VW's klima for dig hver 28. minut om natten, så det ikke stopper af sig selv efter 30 minutter. Du sover, bilen holder varmen.

### Hvordan virker den? Har den adgang til VW's systemer?
Nej. Der er ingen API, ingen aftale med VW og intet login. Appen trykker i VW-appen på telefonen for dig via Androids tilgængelighedsfunktion (Accessibility), præcis som en finger. Derfor kan den kun det, du selv kan i VW-appen.

### Er den fra Volkswagen?
Nej. Et uofficielt hobbyprojekt, ikke tilknyttet VW.

### Hvorfor ligger den ikke i Google Play?
Camper BU22 er et gratis hobbyprojekt og udgives direkte på nyboledigital.dk. Apps i Google Play, der bruger tilgængelighed til at styre en anden app, skal godkendes særskilt af Google, og den proces har Camper BU22 ikke været igennem.

### Hvorfor blokerer Play Protect appen?
Google blokerer alle apps uden for Play Butik, der bruger Accessibility, fordi svindelapps kan misbruge den adgang. Blokeringen siger ikke noget om Camper BU22 i sig selv. Appen skal bruge Accessibility for at trykke i VW-appen. Slå Play Protects scanning fra, mens du installerer, og til igen bagefter. Se [installationsguiden, afsnit 2](INSTALLATION.md#2-installér-kom-forbi-play-protect).

### Sender den mine data nogen steder hen?
Ikke data om dig. Appen henter vejrudsigten (ud fra omtrentlig placering) til batteriprognosen og tjekker GitHub for nye versioner.

Får en ny VW-app Camper BU22 til at fejle, sender appen én anonym besked til udvikleren: VW-version, appversion, fejlkode og telefonmodel. Intet navn, ingen placering, intet ID. Det kan slås fra under Indstillinger → Telefon.

Logs forlader kun telefonen, hvis du selv sender dem.

### Hvor meget af bilens batteri bruger klimaet?
Typisk 1–2 % i timen, mere i kulde. Batteriprognosen på forsiden giver et skøn ud fra vejrudsigten og dine tidligere nætter.

VW slukker selv klimaet ved ca. 20 %. Med batterivagten kan du stoppe tidligere, fx ved 30 %.

### Bruger den meget strøm på telefonen?
Ja, mærkbart mere end normalt, fordi telefonen er vågen hele natten. Hav den i opladeren. Slå "Dæmp automatisk om natten" til, så skærmen bliver mørk.

### Hvorfor stoppede klimaet?
Se Indstillinger → Hjælp → Fejlsøgning → Sidste session. Den viser, hvad der skete.

De almindeligste årsager: VW stopper selv ved ca. 20 % batteri, batterivagten stoppede, VW's servere eller bilen svarede ikke (appen prøver igen inden for et minut og derefter hvert 5. minut), eller Android lukkede appen.

### Kan jeg bruge telefonen under en session?
Ja. Tryk på hjem-knappen, og brug telefonen som normalt. Natskærmen kommer selv tilbage ved næste genstart.

Tryk ikke på tænd/sluk-knappen, og rør ikke skærmen i de ca. 5 sekunder, hvor VW-appen er fremme. Sker det alligevel, genstarter appen klimaet, så snart du låser telefonen op.

### Dyr i bilen — kan jeg bruge appen til det?
Ja. Slå dyretilstand til. Så holder skærmen normal lysstyrke i dagslys, og appen alarmerer dig hvis noget går galt — lavt batteri, klimaet stopper, en genstart fejler, eller VW er nede — så du kan nå at reagere i tide.

⚠️ Men appen er en hjælp, ikke en garanti. Lad aldrig et dyr være afhængig af den alene. Hold øje, hav en plan B, og efterlad aldrig et dyr et sted hvor det kan blive for varmt eller for koldt.

### Hvilke biler og telefoner virker den på?
Buzz årgang 2026 og ældre, som mangler den indbyggede camper-mode (den kom i MY27). Testet på udvalgte Android-telefoner.

### Virker den i udlandet eller på andre sprog?
Ja — det er den samme VW-app. Appen findes på flere sprog.

### Hvad sker der, når VW opdaterer deres app?
Som regel ingenting. Ændrer VW noget, der stopper Camper BU22, får udvikleren automatisk besked, og der kommer en opdatering.

Tip: Slå automatisk opdatering af VW-appen fra i Play Butik, og opdater først, når Camper BU22 er klar.

### Hvordan får jeg nye versioner?
Appen tjekker selv og giver dig én besked, når der er en ny version. Beskeden og kortet på forsiden åbner download-siden på nyboledigital.dk. Installér den oven på den gamle, når der ikke kører en session. Kalibrering og indstillinger bliver liggende. Blokerer Play Protect, så gør som ved første installation.

### Den er gratis — hvordan støtter jeg?
Via MobilePay eller Ko-fi nederst på Statistik. Intet abonnement, ingen forpligtelse.

### Hvor får jeg hjælp, hvis noget ikke virker?
Indstillinger → Hjælp → Fejlsøgning. Der kan du tjekke din opsætning og trykke på det, der er problemet.

Hjælper det ikke, så send en log (Statistik → Send log til udvikleren), eller skriv til camperbu22@nyboledigital.dk.

---

Kan du ikke finde svaret? Se [installationsguiden](INSTALLATION.md), brug **Indstillinger → Hjælp → Fejlsøgning** i appen, eller skriv til camperbu22@nyboledigital.dk.

Lavet af [NyboleDigital](https://nyboledigital.dk/?utm_source=github&utm_medium=faq).
