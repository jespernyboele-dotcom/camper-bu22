# Changelog · Camper BU22

*English below.*

## 1.0.1 – 26. november 2026

Rettelser fra den første uge med 1.0. Installér oven på 1.0.0. Du skal ikke kalibrere igen.

**Fejl, der er rettet**
- **Kalibrering fejlede på nogle Samsung-telefoner med stor skrift.** VW-appens klimakort lå uden for skærmen, mens VW-appen åbnede, og trykket ramte ved siden af. Appen venter nu, til kortet står stille på skærmen, beder Android om at vise det, og klikker til sidst uden koordinater.
- **Klimaet kunne stoppe uden besked**, hvis Android lukkede appens adgang om aftenen. Nu får du besked med det samme (alarm, hvis du har valgt det), og appen fortsætter selv, når du slår den til igen.
- **"Ingen forbindelse" blev vist, selv om forbindelsen var fin.** Beskeden bruges nu kun, når forbindelsen faktisk mangler.
- **Startede du Camper BU22, mens klimaet allerede kørte, kunne VW slukke det før næste genstart.** Appen aflæser nu VW's "Aktiv • N min" og genstarter 2 minutter før, VW slukker.
- **Bankapps og MitID kunne blokere lige efter installation.** Bankvenlig tilstand slår nu også Camper BU22 fra, når den ikke har været brugt i 2 minutter, ikke kun efter en session.

**Nyt**
- **Opsætningsguide trin for trin** ved første installation: batteri, præcise alarmer, systemindstillinger, notifikationer og Hjælpefunktioner, med en kort forklaring på hvert trin. Ved hver Start tjekkes det samme, og kun det, der mangler, vises. Vækkealarmen er slået fra, med mindre du selv vælger den.
- **Uafhængig vagt:** Er klimaet ikke bekræftet i 45 minutter (32 i dyretilstand), får du besked, også selv om Android har lukket appen.
- **Appen kører som forgrundstjeneste** under en session (en stille notifikation, "Camper BU22 kører"), så Android ikke lukker den. Du kan bruge andre apps som normalt.
- **Dyretilstand:** egen alarmlydstyrke (50–100 %), knappen **Test alarmen** og tjek af Forstyr ikke før start.
- **Natskærmen** viser "Klima bekræftet 02:14 · for 6 min siden".
- **VW-appen skal være version 4.8.1 eller nyere.** Er den ældre, beder Camper BU22 dig opdatere den i Google Play.
- **Hjælp skrevet om trin for trin** med de ord, telefonen viser (Hjælpefunktioner, Samsung: Tilgængelighed). Nye emner: "Camper BU22 er grå og kan ikke slås til" og "Play Protect blokerer installationen".
- **Beskeder fra udvikleren:** Appen kan vise en kort besked på forsiden, fx når der søges testere. Tryk ✕, så vises den ikke igen.

**Privatliv**
- Når en ny VW-app får Camper BU22 til at fejle, følger appens hændelseslog med beskeden til udvikleren. Al tekst fra VW-skærmen (fx bilens navn) fjernes i appen, før den sendes. Det kan stadig slås fra under Indstillinger → Meld VW-opdateringer automatisk.

## 1.0.0 – 23. november 2026

Første officielle udgave. Erstatter 0.4.7-beta, som holder op med at virke 28. november 2026. Installér 1.0.0 oven på den gamle version. Så beholder du kalibrering, indstillinger og statistik.

**Genstart og timing**
- Klimaet genstartes altid 28 minutter efter den sidste bekræftede start og aldrig før 25 minutter. Det fjerner de for tidlige genstarter, hvor VW viste "kører", uden at klimaet kørte.

**Nattemperatur**
- Vælg en nattemperatur 1–3° under din normale. Den gælder fra kl. 01:00 og slutter 1 time før sluttidspunktet, så bilen er varm, når I står op.
- Skiftet sker ved en almindelig genstart og giver ingen ekstra genstarter.

**Låst telefon**
- Appen venter, når telefonen er låst, og genstarter klimaet med det samme, når du låser op.
- Natskærmen viser tydeligt, at telefonen er låst, og har en **Fortsæt**-knap.
- Du får en advarsel, hvis telefonen har været låst i 5 minutter.

**Dyretilstand**
- Alarmen er nu høj og bruger alarmlyden. Den stopper, når du trykker Stop alarm, låser op eller åbner appen, og ellers efter 5 minutter.

**VW-appen og forbindelsen**
- Appen opdager, hvis VW-appen er logget ud, eller hvis der ikke er internet, og fortæller dig det.
- Skærmen dæmpes, mens VW-appen er fremme. Så er der intet lysglimt ved genstart.
- Stopper en ny VW-app Camper BU22, får udvikleren automatisk en anonym besked (VW-version, appversion, fejlkode og telefonmodel). Det kan slås fra under Indstillinger → Meld VW-opdateringer automatisk.

**Kalibrering**
- Er nu kortere: én start og ét stop, og derefter temperaturskalaen.
- Mangler der internet, eller er VW-appen logget ud, stopper kalibreringen med det samme og viser en tjekliste. Den starter ikke selv forfra igen.

**Ny natskærm**
- Nyt mørkt design med ur, status, temperatur og tidslinje.
- Hold Stop-knappen inde i 1 sekund for at stoppe.
- Indholdet flytter sig lidt hvert minut for at skåne skærmen.

**Fejlsøgning**
- Indstillinger → Hjælp tjekker din opsætning og forklarer, hvad der skete i sidste session.

**Godmorgen-besked**
- En stille besked med nattens resultat, når sessionen slutter af sig selv.

**Statistik**
- Viser minutter uden klima.
- Nætter, hvor batteriet ikke faldt (fx fordi bilen lå til opladning), tæller ikke med i batteriprognosen.

**Opdateringer**
- Appen tjekker én gang om dagen, om der er en ny version, og giver én besked pr. version. Beskeden kommer kun mellem kl. 8 og 20 og aldrig under en session.

**Øvrigt**
- Beta-udløbsdatoen er fjernet.

---

# Changelog (English)

## 1.0.1 – 26 November 2026

Fixes from the first week of 1.0. Install over 1.0.0. No new calibration needed.

**Fixed**
- **Calibration failed on some Samsung phones with large text.** The VW app's climate tile was off screen while the VW app was opening, so the tap missed. The app now waits until the tile is at rest on screen, asks Android to show it, and as a last resort clicks it without coordinates.
- **The climate could stop without any message** if Android closed the app's access in the evening. You are now told at once (an alarm if you chose one), and the app carries on by itself when you switch it on again.
- **"No connection" was shown although the connection was fine.** It is now only shown when the connection really is missing.
- **If you started Camper BU22 while the climate was already running, VW could switch it off before the next restart.** The app now reads VW's "Active • N min" and restarts 2 minutes before VW switches off.
- **Banking apps and MitID could block right after installing.** Bank-friendly mode now also switches Camper BU22 off when it has been unused for 2 minutes, not only after a session.

**New**
- **Step-by-step setup guide** on first install: battery, exact alarms, system settings, notifications and Accessibility, each with a short explanation. Every Start checks the same and shows only what is missing. The wake-up alarm stays off unless you choose it.
- **Independent watchdog:** if the climate isn't confirmed for 45 minutes (32 in animal mode), you are told, even if Android has closed the app.
- **The app runs as a foreground service** during a session (a quiet notification, "Camper BU22 is running"), so Android doesn't close it. You can use other apps as normal.
- **Animal mode:** its own alarm volume (50–100 %), a **Test the alarm** button and a Do-not-disturb check before start.
- **Night screen** shows "Climate confirmed 02:14 · 6 min ago".
- **The VW app must be version 4.8.1 or newer.** If it is older, Camper BU22 asks you to update it in Google Play.
- **Help rewritten step by step** with the words the phone shows. New topics: "Camper BU22 is grey and can't be switched on" and "Play Protect blocks the install".
- **Messages from the developer:** the app can show a short message on the home screen, e.g. when testers are wanted. Tap ✕ and it won't show again.

**Privacy**
- When a new VW app makes Camper BU22 fail, the app's event log is sent with the message to the developer. All text from the VW screen (e.g. the car's name) is removed in the app before sending. You can still switch it off under Settings → Report VW updates automatically.

## 1.0.0 – 23 November 2026

First official release. Replaces 0.4.7-beta, which stops working on 28 November 2026. Install 1.0.0 over the old version to keep calibration, settings and statistics.

**Restarts and timing**
- The climate is always restarted 28 minutes after the last verified start, and never sooner than 25 minutes. This removes early restarts where VW showed "running" but the climate wasn't.

**Night temperature**
- Choose a night temperature 1–3° below your normal one. It applies from 01:00 and ends 1 hour before the end time, so the car is warm when you get up.
- The switch happens at a regular restart and adds no extra restarts.

**Locked phone**
- When the phone is locked, the app waits and restarts the climate as soon as you unlock.
- The night screen clearly shows that the phone is locked and has a **Continue** button.
- You get a warning if the phone has been locked for 5 minutes.

**Animal mode**
- The alarm is now loud and uses the alarm sound. It stops when you tap Stop alarm, unlock the phone or open the app, and otherwise after 5 minutes.

**VW app and connection**
- The app detects when the VW app is signed out or there is no internet, and tells you.
- The screen is dimmed while the VW app is showing, so there is no flash of light at restarts.
- If a new VW app stops Camper BU22, the developer is told automatically and anonymously (VW version, app version, error code and phone model). You can switch this off under Settings → Report VW updates automatically.

**Calibration**
- Now shorter: one start and one stop, then the temperature scale.
- With no internet or a signed-out VW app, calibration stops at once and shows a checklist. It does not keep retrying by itself.

**New night screen**
- New dark design with clock, status, temperature and timeline.
- Hold the Stop button for 1 second to stop.
- The content shifts slightly every minute to protect the screen.

**Troubleshooting**
- Settings → Help checks your setup and explains what happened in the last session.

**Good-morning message**
- A quiet notification with the night's result when the session ends by itself.

**Statistics**
- Shows minutes without climate.
- Nights where the battery didn't drop (e.g. because the car was charging) are left out of the battery forecast.

**Updates**
- The app checks for a new version once a day and notifies you once per version. The message only comes between 08:00 and 20:00, and never during a session.

**Other**
- The beta expiry date has been removed.
