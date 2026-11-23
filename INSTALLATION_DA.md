# Installationsguide · Camper BU22

Læs guiden én gang fra start til slut, før den første nat. Det tager cirka 5 minutter, og selve opsætningen tager cirka 10.

*[English version](INSTALLATION_EN.md)*

---

## Før du starter

Du skal bruge:
- **En Android-telefon eller -tablet** med Android 11 eller nyere. Appen virker ikke på iPhone.
- **VW-appen (Volkswagen)**, hvor du er logget ind, og hvor du selv kan starte klimaet.
- **Internet og strøm hele natten.** Telefonen skal ligge i en oplader.

Det er en god idé at:
- **Åbne VW-appen først** og starte og stoppe klimaet én gang selv. Så ved du, at bilen svarer, og at VW-appen er færdig med sine velkomstvinduer.
- **Slå automatisk opdatering fra for VW-appen** i Play Butik: åbn VW-appens side → **⋮** → fjern fluebenet ved **Aktivér automatisk opdatering**. Så ændrer VW-appen sig ikke midt på en tur. Camper BU22 siger selv til, hvis en ny VW-version giver problemer.

---

## 1. Hent appen
Gå til **[Releases](https://github.com/jespernyboele-dotcom/camper-bu22/releases/latest)** på telefonen, og tryk på filen, der ender på **`.apk`**.

Hent kun appen herfra. Alle officielle udgaver er signeret med samme nøgle, og Android nægter at installere en opdatering med en anden nøgle.

## 2. Installér
Android viser nogle advarsler, fordi appen ikke kommer fra Google Play. De er normale.

1. **"Installer ukendte apps":** Tryk **Indstillinger → Tillad fra denne kilde**, og gå tilbage.
2. **Play Protect** ("Usikker app" eller "Appen er ikke scannet"): Tryk **Flere oplysninger → Installer alligevel**. Spørger den, om appen må sendes til scanning, vælger du selv. Det ændrer ikke på appen.
3. Tryk **Installer** og derefter **Åbn**.

**Opdaterer du fra en tidligere version?** Installér bare oven på den gamle. Afinstallér ikke først. Så beholder du kalibrering, indstillinger og statistik.

## 3. Giv appen lov til at styre VW-appen
Camper BU22 trykker i VW-appen for dig via Androids tilgængelighedsfunktion (Accessibility). Den skal slås til én gang.

1. Åbn Camper BU22, læs ansvarsfraskrivelsen, og tryk **Jeg forstår** og derefter **Åbn Accessibility**.
2. Tryk på **Camper BU22**, slå den **til**, og tryk **Tillad**.
3. **Er den grå, eller står der "Begrænset indstilling"?** Det er Androids beskyttelse mod apps uden for Play Butik:
   - Gå til **Indstillinger → Apps → Camper BU22**.
   - Tryk **⋮** øverst til højre → **Tillad begrænsede indstillinger**, og bekræft med din pinkode.
   - Gå tilbage til **Accessibility → Camper BU22**, og slå den til.

## 4. Giv de sidste tilladelser
Står der gule bokse øverst på forsiden, så tryk på dem én ad gangen:
- **Hold skærmen tændt:** Slå **Tillad ændring af systemindstillinger** til. Appen hæver kun skærmens slukketid under en session og sætter din egen indstilling tilbage bagefter.
- **Kørsel i baggrunden:** Tillad, at appen ikke bliver batterioptimeret. Ellers kan Android lukke den om natten.
- **Notifikationer:** Kun nødvendigt, hvis du vil have alarmer.
- **Omtrentlig placering:** Bruges kun til at hente vejrudsigten til batteriprognosen. Appen virker også uden.

**Tjek, at alt er i orden:** **Indstillinger → Hjælp → Fejlsøgning → Tjek min opsætning**. Alt skal være grønt.

## 5. Indstillinger for dit telefonmærke
Mange telefoner lukker apps i baggrunden for at spare strøm. Så kommer genstarten ikke, og klimaet stopper efter cirka 30 minutter. Gør dette én gang:

- **Alle telefoner:** Indstillinger → Apps → Camper BU22 → Batteri → **Ubegrænset**.
- **Samsung:** Indstillinger → Batteri → Grænser for baggrundsbrug → tilføj Camper BU22 til **Apps, der aldrig sover**. Slå også **Automatisk genstart** fra under Enhedspleje, så telefonen ikke genstarter om natten.
- **Xiaomi, Redmi og POCO:** Indstillinger → Apps → Camper BU22 → slå **Autostart** til, og sæt batterisparer til **Ingen begrænsninger**.
- **OnePlus, OPPO og Realme:** Indstillinger → Apps → Camper BU22 → Batteriforbrug → slå **Tillad baggrundsaktivitet** og **Tillad automatisk start** til.

Menuernes navne kan variere lidt fra model til model.

## 6. Kalibrering (kun første gang)
Appen tjekker én gang, at den kan styre din VW-app: den starter og stopper klimaet én gang og lærer temperaturskalaen.

- **Vær logget ind i VW-appen, og hav internet på telefonen.** Mangler en af delene, stopper kalibreringen med det samme og fortæller, hvad du skal gøre.
- **Bilen skal have forbindelse.** Viser VW-appen ingen Start-knap inden for 30 sekunder, stopper kalibreringen og beder dig tjekke forbindelsen.
- **Du skal ikke gøre noget imens.** Appen styrer selv VW-appen. Lad den køre færdig. Det tager et par minutter.
- **Fejler den,** så følg tjeklisten i beskeden, og start kalibreringen igen fra forsiden, når du er klar. Fejler den igen, så send en log (se afsnit 9).

## 7. Din første nat
1. **Vælg temperatur** på forsiden med − og +.
2. **Vælg start:** **Nu** eller **Senere**, fx kl. 00:30, hvis bilen er varm nok til at begynde med.
3. **Vælg slut:** det klokkeslæt, klimaet skal stoppe.
4. **Batteriprognosen** viser, hvor mange procent klimaet cirka bruger i løbet af natten, ud fra vejrudsigten og dine tidligere nætter. Ender bilen under 20 %, får du en advarsel.
5. Tryk **START CAMPER MODE**, og læg telefonen i opladeren.

**Hvad sker der så?**
- **Natskærmen** kommer frem. Den er mørk med vilje, så den ikke lyser bilen op. Tryk på den for at se den tydeligt i 15 sekunder.
- **Hvert 28. minut** åbner appen VW-appen i cirka 5 sekunder, genstarter klimaet og går tilbage til natskærmen. Det er meningen. VW slukker selv klimaet efter cirka 30 minutter, og appen kommer før.
- **Klimaet stopper af sig selv** på sluttidspunktet. Du kan også stoppe det med **STOP CAMPER MODE**.

**Under sessionen:**
- **Tryk ikke på tænd/sluk-knappen.** Så låser telefonen sig, og appen kan ikke genstarte klimaet, før du låser op igen. Så genstarter den med det samme.
- **Skal du bruge telefonen,** så tryk på hjem-knappen og brug den som normalt. Natskærmen kommer selv tilbage ved næste genstart. Rør ikke skærmen i de 5 sekunder, hvor VW-appen er fremme.
- **Sover I i bilen?** Slå **kabineovervågning** fra på bilens skærm, før I låser. Ellers kan bevægelser i bilen udløse tyverialarmen.

## 8. Godt at vide
- **Telefonen bruger ekstra strøm.** Den er vågen hele natten, så hold den i opladeren. Under **Indstillinger → Natskærm** kan du slå **Dæmp automatisk om natten** til.
- **Bilens batteri:** VW slukker selv klimaet ved cirka **20 %**. Med **batterivagten** kan du vælge at stoppe tidligere, fx ved 30 %.
- **Bankapps og MitID:** Nogle bankapps vil ikke åbne, mens en app har Accessibility slået til. **Bankvenlig tilstand** er slået til fra start og slår adgangen fra efter hver session. Næste gang du trykker Start, beder appen dig slå den til igen med ét tryk.
- **Dyretilstand** er et ekstra sikkerhedsnet med alarm, ikke en garanti. Tjek altid selv dine dyr.
- **Nye versioner:** Appen tjekker selv, om der er en ny version, og viser et kort på forsiden. Installér den, når der ikke kører en session.
- **VW-opdateringer:** Hvis en ny VW-app får Camper BU22 til at fejle, giver appen selv udvikleren anonym besked (VW-version, appversion, fejlkode og telefonmodel). Det kan slås fra under **Indstillinger → Telefon**.
- **Tryk aldrig "Tving til at stoppe"** på Camper BU22. Så slår Android tjenesten fra, og der sker ingenting om natten.

## 9. Hvis noget driller
1. **Åbn Fejlsøgning:** **Indstillinger → Hjælp → Fejlsøgning**. Tjek din opsætning, se hvad der skete i den sidste session, og tryk på det, der er problemet.
2. **Send en log:** **Statistik → Send log til udvikleren**. Din mail-app åbner med loggen vedhæftet. Skriv en linje om, hvad der skete. Loggen indeholder ikke login, adgangskoder eller position, kun tidspunkter, trin, temperaturer og batteriniveauer.
3. **Kontakt:** camperbu22@nyboledigital.dk

---

*Camper BU22 er et uofficielt hobbyprojekt. Det er ikke lavet af, godkendt af eller tilknyttet Volkswagen. Appen kan holde op med at virke, hvis VW ændrer deres app. Du bruger appen på eget ansvar.*

Lavet af [NyboleDigital](https://nyboledigital.dk/?utm_source=github&utm_medium=install).
