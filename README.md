# Camper BU22

**Klima hele natten i din VW ID.** – en gratis Android-app, der holder klimaet kørende, mens du sover i bilen.

*English below.*

VW slukker selv klimaet efter ca. 30 minutter. Camper BU22 genstarter det automatisk hvert 28. minut, hele natten, ved at trykke i VW-appen for dig.

> Uofficielt hobbyprojekt. Ikke lavet af, godkendt af eller tilknyttet Volkswagen. Brug på eget ansvar.

---

## Hent appen

Gå til **[Releases](../../releases/latest)** og hent filen, der ender på **`.apk`**. Åbn den på telefonen for at installere.

👉 **Læs [installationsguiden](INSTALLATION_DA.md) før første nat.** Den tager dig fra download til første nat på cirka 10 minutter.
Spørgsmål? Se [ofte stillede spørgsmål](FAQ_DA.md).

Kræver Android 11 eller nyere og VW-appen (We Connect / Volkswagen) logget ind på samme telefon.

---

## "Er det her sikkert?" – advarslerne forklaret

Camper BU22 ligger **ikke** i Google Play Butik. Derfor viser Android nogle advarsler, som er helt normale for apps, der installeres direkte. De betyder ikke, at der er noget galt med appen. De betyder kun, at Google ikke har gennemgået den.

**1. "Installer ukendte apps"**
Første gang beder telefonen dig give din browser eller Filer-app lov til at installere apps. Tryk **Indstillinger → Tillad fra denne kilde**, og gå tilbage.

**2. Play Protect: "Appen er ikke scannet" / "Usikker app"**
Tryk **Flere oplysninger → Installer alligevel**. Spørger den, om appen skal sendes til scanning, må du selv vælge. Det ændrer ikke på appen.

**3. "Begrænset indstilling" ved Accessibility**
Appen bruger Android Accessibility til at trykke i VW-appen. På nyere Android er den grå første gang. Gå til **Indstillinger → Apps → Camper BU22 → ⋮ (øverst til højre) → Tillad begrænsede indstillinger**, og slå den så til.

### Hvorfor ikke Google Play?
Camper BU22 er et gratis hobbyprojekt og udgives direkte her. Apps i Google Play, der bruger Accessibility til at styre en anden app, skal godkendes særskilt af Google, og den proces har Camper BU22 ikke været igennem.

### Hvad appen gør – og ikke gør
- ✅ Den trykker kun i **VW-appen**: åbner klima, sætter temperatur, trykker Start/Stop.
- ✅ Den rører **ikke** opladning, vinduesvarme, døre eller andet i bilen.
- ✅ **Ingen login, ingen konto, ingen server.** Den kender ikke din VW-adgangskode.
- ✅ Den sender **ingen data** om dig nogen steder hen. Den henter kun vejrudsigt (Open-Meteo, ud fra omtrentlig placering til batteriprognosen) og tjekker her på GitHub, om der er en ny version.
- ✅ **Én undtagelse, anonym:** Hvis en opdatering af VW-appen får Camper BU22 til at fejle, sender appen én gang et lille signal til udvikleren med VW-version, appversion, fejlkode og telefonmodel. Intet navn, ingen placering, intet ID. Så ved udvikleren det med det samme og kan rette det. Kan slås fra under **Indstillinger → Meld VW-opdateringer automatisk**.
- ✅ Logs forlader kun telefonen, hvis **du selv** trykker "Send log til udvikleren".
- ✅ **Bankvenlig tilstand:** Accessibility slås fra efter hver session, så bankapps og MitID virker mellem turene.

### Tjek at filen er ægte
Alle officielle udgaver er signeret med samme nøgle. Certifikatets SHA-256:

```
6d:ca:0f:4b:fa:35:1b:08:d5:c3:44:81:fd:92:29:87:ea:00:13:f9:94:b6:18:2c:00:6b:ac:33:aa:41:4d:0b
```

Hent kun appen herfra. Android nægter at installere en opdatering, der er signeret med en anden nøgle.

---

## Godt at vide
- Appen afhænger af VW-appen og VW's servere. Er de nede, eller mister bilen forbindelsen, kan klimaet ikke genstartes. Det er uden for appens kontrol.
- VW slukker selv klimaet ved ca. **20 % batteri**. Batterivagten kan stoppe før.
- Lad telefonen ligge i bilen med strøm og skærmen på natskærmen.
- **Slå kabineovervågning fra** på bilens skærm, før I lægger jer til at sove. Ellers kan bevægelser i bilen udløse tyverialarmen.
- **Kalibrering:** Første gang kalibrerer appen sig selv til din telefon. Du skal ikke gøre noget imens. Sørg for, at bilen og VW-appen har forbindelse, før du starter.
- **Dyretilstand** er et ekstra sikkerhedsnet med alarm, ikke en garanti. Tjek altid selv dine dyr.

Fejl eller spørgsmål? Brug **Indstillinger → Fejlsøgning** i appen, eller send en log (Statistik → Send log til udvikleren). Kontakt: camperbu22@nyboledigital.dk

Lavet af [NyboleDigital](https://nyboledigital.dk/?utm_source=github&utm_medium=readme).

---
---

# Camper BU22 (English)

**Climate all night in your VW ID.** – a free Android app that keeps the climate running while you sleep in the car.

VW switches the climate off after about 30 minutes. Camper BU22 restarts it automatically every 28 minutes, all night, by tapping the VW app for you.

> Unofficial hobby project. Not made by, endorsed by or affiliated with Volkswagen. Use at your own risk.

## Download
Go to **[Releases](../../releases/latest)** and download the file ending in **`.apk`**. Open it on your phone to install. Requires Android 11+ and the VW app (We Connect / Volkswagen) signed in on the same phone.

👉 **Read the [installation guide](INSTALLATION_EN.md) before your first night.** It takes you from download to first night in about 10 minutes.
Questions? See the [FAQ](FAQ_EN.md).

## "Is this safe?" – the warnings explained
Camper BU22 is **not** on Google Play, so Android shows warnings that are normal for directly installed apps. They don't mean anything is wrong. They only mean Google hasn't reviewed it.

1. **"Install unknown apps"** – tap **Settings → Allow from this source**, then go back.
2. **Play Protect: "App not scanned" / "Unsafe app"** – tap **More details → Install anyway**.
3. **"Restricted setting" for Accessibility** – go to **Settings → Apps → Camper BU22 → ⋮ → Allow restricted settings**, then switch it on.

**Why not Google Play?** Camper BU22 is a free hobby project and is published directly here. Apps on Google Play that use Accessibility to control another app need separate approval from Google, and Camper BU22 hasn't been through that process.

**What it does and doesn't do:** it only taps the **VW app** (open climate, set temperature, Start/Stop). It never touches charging, window heating, doors or anything else. No login, no account, no server, and it never sees your VW password. It sends **no data about you** anywhere; it only fetches a weather forecast (Open-Meteo, approximate location, for the battery forecast) and checks GitHub for a new version. One anonymous exception: if a VW app update makes Camper BU22 fail, the app sends one small signal to the developer (VW version, app version, error code, phone model; no name, location or ID) so it can be fixed fast. You can switch it off under **Settings → Report VW updates automatically**. Logs only leave the phone if **you** tap "Send log". Bank-friendly mode switches Accessibility off after each session so banking apps work between trips.

**Verify the file:** every official release is signed with the same key. Certificate SHA-256:
`6d:ca:0f:4b:fa:35:1b:08:d5:c3:44:81:fd:92:29:87:ea:00:13:f9:94:b6:18:2c:00:6b:ac:33:aa:41:4d:0b`

## Good to know
- The app depends on the VW app and VW's servers. If they're down or the car loses its connection, the climate can't be restarted.
- VW switches the climate off by itself at about **20 % battery**. The battery guard can stop earlier.
- **Switch off interior monitoring** on the car's screen before you go to sleep, or movement inside the car can set off the alarm.
- **Calibration:** the first time, the app calibrates itself to your phone. You don't need to do anything. Make sure the car and the VW app are connected before you start.
- **Animal mode** is an extra safety net with alarms, not a guarantee. Always check on your animals yourself.

Problems? Use **Settings → Troubleshooting** in the app, or send a log. Contact: camperbu22@nyboledigital.dk

Made by [NyboleDigital](https://nyboledigital.dk/?utm_source=github&utm_medium=readme).
