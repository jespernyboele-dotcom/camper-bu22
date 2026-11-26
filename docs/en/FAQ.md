# Frequently asked questions · Camper BU22

*[Dansk version](../da/FAQ.md)*

### What does the app actually do?
It restarts the VW climate for you every 28 minutes at night, so it does not stop on its own after 30 minutes. You sleep, the van stays warm.

### How does it work? Does it have access to VW's systems?
No. There is no API, no agreement with VW and no login. The app taps the VW app on your phone for you through Android Accessibility, exactly like a finger. So it can only do what you can do yourself in the VW app.

### Is it from Volkswagen?
No. An unofficial hobby project, not affiliated with VW.

### Why isn't it on Google Play?
Camper BU22 is a free hobby project and is published directly on nyboledigital.dk. Apps on Google Play that use Accessibility to control another app need separate approval from Google, and Camper BU22 hasn't been through that process.

### Why does Play Protect block the app?
Google blocks every app from outside the Play Store that uses Accessibility, because fraud apps can misuse that access. The block says nothing about Camper BU22 itself. The app needs Accessibility to tap the VW app. Switch off Play Protect scanning while you install, and back on afterwards. See the [installation guide, section 2](INSTALLATION.md#2-install-getting-past-play-protect).

### Does it send my data anywhere?
No data about you. The app fetches the weather forecast (from your approximate location) for the battery forecast and checks GitHub for new versions and messages from the developer.

If a new VW app makes Camper BU22 fail, the app sends one anonymous message to the developer: VW version, app version, error code, phone model and the app's event log (all text from the VW screen removed). No name, no location, no ID. You can switch it off under Settings → Phone.

Logs only leave the phone if you send them yourself.

### How much of the car's battery does the climate use?
Typically 1–2 % per hour, more in the cold. The battery forecast on the home screen gives an estimate based on the weather forecast and your earlier nights.

VW switches the climate off itself at about 20 %. With the battery guard you can stop earlier, e.g. at 30 %.

### Does it use a lot of power on the phone?
Yes, noticeably more than normal, because the phone stays awake all night. Keep it on the charger. Switch on "Dim automatically at night" so the screen goes dark.

### Why did the climate stop?
See Settings → Help → Troubleshooting → Last session. It shows what happened.

The most common reasons: VW stops by itself at about 20 % battery, the battery guard stopped it, VW's servers or the car didn't respond (the app retries within a minute and then every 5 minutes), or Android closed the app.

### Can I use the phone during a session?
Yes. Press the home button and use the phone as normal. The night screen comes back by itself at the next restart.

Don't press the power button, and don't touch the screen during the roughly 5 seconds the VW app is showing. If it happens anyway, the app restarts the climate as soon as you unlock the phone.

### Pets in the car — can I use it for that?
Yes. Turn on animal mode. The screen keeps normal brightness in daylight, and the app alerts you if something goes wrong — low battery, climate stops, a restart fails, or VW is down — so you can react in time.

⚠️ But the app is a help, not a guarantee. Never let an animal depend on it alone. Keep watch, have a plan B, and never leave an animal where it can get too hot or too cold.

### Which cars and phones does it work on?
Buzz model year 2026 and older, which lack the built-in camper mode (that arrived in MY27). Tested on selected Android phones. The VW app must be version 4.8.1 or newer.

### Does it work abroad or in other languages?
Yes — it is the same VW app. The app is available in several languages.

### What happens when VW updates its app?
Usually nothing. If VW changes something that stops Camper BU22, the developer is told automatically and an update follows.

Tip: switch off auto-update for the VW app in the Play Store, and only update once Camper BU22 is ready.

### How do I get new versions?
The app checks by itself and notifies you once when there's a new version. The notification and the card on the home screen open the download page on nyboledigital.dk. Install it over the old one when no session is running. Calibration and settings are kept. If Play Protect blocks it, do the same as for the first install.

### It is free — how do I support it?
Through MobilePay or Ko-fi at the bottom of the Statistics tab. No subscription, no obligation.

### Where do I get help if something doesn't work?
Settings → Help → Troubleshooting. There you can check your setup and tap whatever the problem is.

If that doesn't help, send a log (Statistics → Send log to the developer) or write to camperbu22@nyboledigital.dk.

---

Can't find the answer? See the [installation guide](INSTALLATION.md), use **Settings → Help → Troubleshooting** in the app, or write to camperbu22@nyboledigital.dk.

Made by [NyboleDigital](https://nyboledigital.dk/?utm_source=github&utm_medium=faq).
