# Installation guide · Camper BU22

Read this guide once from start to finish before your first night. Reading takes about 5 minutes, and the setup itself about 10.

*[Dansk version](INSTALLATION_DA.md)*

---

## Before you start

You need:
- **An Android phone or tablet** with Android 11 or newer. The app does not work on iPhone.
- **The VW app (Volkswagen)**, signed in, where you can start the climate yourself.
- **Internet and power all night.** Keep the phone on a charger.

It's a good idea to:
- **Open the VW app first** and start and stop the climate once yourself. Then you know the car responds and the VW app has finished its welcome screens.
- **Switch off auto-update for the VW app** in the Play Store: open the VW app's page → **⋮** → untick **Enable auto update**. That way the VW app doesn't change in the middle of a trip. Camper BU22 tells you itself if a new VW version causes problems.

---

## 1. Download the app
On your phone, go to **[Releases](https://github.com/jespernyboele-dotcom/camper-bu22/releases/latest)** and tap the file ending in **`.apk`**.

Only download the app from here. Every official release is signed with the same key, and Android refuses to install an update signed with a different key.

## 2. Install
Android shows some warnings because the app doesn't come from Google Play. They are normal.

1. **"Install unknown apps":** tap **Settings → Allow from this source**, then go back.
2. **Play Protect** ("Unsafe app" or "App not scanned"): tap **More details → Install anyway**. If it asks to send the app for scanning, that's up to you. It doesn't change the app.
3. Tap **Install**, then **Open**.

**Updating from an earlier version?** Just install over the old one. Don't uninstall first. That way you keep calibration, settings and statistics.

## 3. Let the app control the VW app
Camper BU22 taps the VW app for you through Android Accessibility. It has to be switched on once.

1. Open Camper BU22, read the disclaimer, tap **I understand**, then **Open Accessibility**.
2. Tap **Camper BU22**, switch it **on**, and tap **Allow**.
3. **Greyed out, or it says "Restricted setting"?** That's Android's protection against apps from outside the Play Store:
   - Go to **Settings → Apps → Camper BU22**.
   - Tap **⋮** in the top right → **Allow restricted settings**, and confirm with your PIN.
   - Go back to **Accessibility → Camper BU22** and switch it on.

## 4. Give the last permissions
If there are yellow boxes at the top of the home screen, tap them one at a time:
- **Keep screen on:** switch on **Allow modifying system settings**. The app only raises the screen timeout during a session and puts your own setting back afterwards.
- **Background running:** allow the app not to be battery-optimised. Otherwise Android may close it at night.
- **Notifications:** only needed if you want alarms.
- **Approximate location:** only used to fetch the weather forecast for the battery forecast. The app works without it.

**Check that everything is fine:** **Settings → Help → Troubleshooting → Check my setup**. Everything should be green.

## 5. Settings for your phone brand
Many phones close background apps to save power. Then the restart doesn't happen, and the climate stops after about 30 minutes. Do this once:

- **All phones:** Settings → Apps → Camper BU22 → Battery → **Unrestricted**.
- **Samsung:** Settings → Battery → Background usage limits → add Camper BU22 to **Never sleeping apps**. Also switch off **Auto restart** under Device care, so the phone doesn't restart at night.
- **Xiaomi, Redmi and POCO:** Settings → Apps → Camper BU22 → switch on **Autostart**, and set battery saver to **No restrictions**.
- **OnePlus, OPPO and Realme:** Settings → Apps → Camper BU22 → Battery usage → switch on **Allow background activity** and **Allow auto launch**.

Menu names can vary slightly between models.

## 6. Calibration (first time only)
The app checks once that it can control your VW app: it starts and stops the climate once and learns the temperature scale.

- **Be signed in to the VW app, and have internet on the phone.** If either is missing, calibration stops at once and tells you what to do.
- **The car must be connected.** If the VW app shows no Start button within 30 seconds, calibration stops and asks you to check the connection.
- **You don't need to do anything.** The app controls the VW app by itself. Let it finish. It takes a few minutes.
- **If it fails,** follow the checklist in the message, and start the calibration again from the home screen when you're ready. If it fails again, send a log (see section 9).

## 7. Your first night
1. **Choose the temperature** on the home screen with − and +.
2. **Choose the start:** **Now** or **Later**, e.g. 00:30 if the car is warm enough to begin with.
3. **Choose the end:** the time the climate should stop.
4. **The battery forecast** shows roughly how many percent the climate will use overnight, based on the weather forecast and your earlier nights. If the car would end below 20 %, you get a warning.
5. Tap **START CAMPER MODE** and put the phone on the charger.

**What happens then?**
- **The night screen** appears. It's dark on purpose so it doesn't light up the car. Tap it to see it clearly for 15 seconds.
- **Every 28 minutes** the app opens the VW app for about 5 seconds, restarts the climate and goes back to the night screen. That's intended. VW switches the climate off itself after about 30 minutes, and the app gets there first.
- **The climate stops by itself** at the end time. You can also stop it with **STOP CAMPER MODE**.

**During the session:**
- **Don't press the power button.** The phone then locks, and the app can't restart the climate until you unlock it. Then it restarts right away.
- **Need the phone?** Press the home button and use it as normal. The night screen comes back by itself at the next restart. Don't touch the screen during the 5 seconds the VW app is showing.
- **Sleeping in the car?** Switch off **interior monitoring** on the car's screen before you lock up. Otherwise movement inside the car can set off the alarm.

## 8. Good to know
- **The phone uses extra power.** It stays awake all night, so keep it on the charger. Under **Settings → Night screen** you can switch on **Dim automatically at night**.
- **The car's battery:** VW switches the climate off itself at about **20 %**. With the **battery guard** you can choose to stop earlier, e.g. at 30 %.
- **Banking apps:** some banking apps refuse to open while an app has Accessibility switched on. **Bank-friendly mode** is on by default and switches access off after each session. Next time you tap Start, the app asks you to switch it on again with one tap.
- **Animal mode** is an extra safety net with alarms, not a guarantee. Always check on your animals yourself.
- **New versions:** the app checks for a new version by itself and shows a card on the home screen. Install it when no session is running.
- **VW updates:** if a new VW app makes Camper BU22 fail, the app tells the developer anonymously (VW version, app version, error code and phone model). You can switch this off under **Settings → Phone**.
- **Never tap "Force stop"** on Camper BU22. Android then switches the service off, and nothing happens at night.

## 9. If something goes wrong
1. **Open Troubleshooting:** **Settings → Help → Troubleshooting**. Check your setup, see what happened in the last session, and tap whatever the problem is.
2. **Send a log:** **Statistics → Send log to the developer**. Your mail app opens with the log attached. Write a line about what happened. The log contains no login, passwords or location, only times, steps, temperatures and battery levels.
3. **Contact:** camperbu22@nyboledigital.dk

---

*Camper BU22 is an unofficial hobby project. It is not made by, endorsed by or affiliated with Volkswagen. The app may stop working if VW changes its app. Use at your own risk.*

Made by [NyboleDigital](https://nyboledigital.dk/?utm_source=github&utm_medium=install).
