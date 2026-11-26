# Installation guide · Camper BU22

Read this guide once from start to finish before your first night. Reading takes about 5 minutes, and the setup itself about 10.

*[Dansk version](../da/INSTALLATION.md)*

---

## Before you start

You need:
- **An Android phone or tablet** with Android 11 or newer. The app does not work on iPhone.
- **The VW app (Volkswagen) version 4.8.1 or newer**, signed in, where you can start the climate yourself.
- **Internet and power all night.** Keep the phone on a charger.
- **2 extra minutes for Play Protect.** Google blocks the install until you briefly switch off Play Protect scanning. See section 2.

It's a good idea to:
- **Open the VW app first** and start and stop the climate once yourself. Then you know the car responds and the VW app has finished its welcome screens.
- **Switch off auto-update for the VW app** in the Play Store: open the VW app's page → **⋮** → untick **Enable auto update**. That way the VW app doesn't change in the middle of a trip. Camper BU22 tells you itself if a new VW version causes problems.

---

## 1. Download the app
On your phone, open **[Camper BU22 on nyboledigital.dk](https://nyboledigital.dk/en/projects/camper-bu22/#download)** and tap **Download Camper BU22**. The file is called `CamperBU22.apk`.

Only download the app from there. Every official release is signed with the same key, and Android refuses to install an update signed with a different key.

## 2. Install: getting past Play Protect
If you open the file straight away, Google Play Protect shows **"App blocked to protect your device"** with only an OK button. Google blocks every app from outside the Play Store that uses Accessibility, because fraud apps can misuse that access. Camper BU22 needs Accessibility to tap the VW app, so you switch off Play Protect scanning while you install, and back on afterwards:

1. Tap **OK** on the Play Protect message.
2. Open the **Play Store**, tap your **profile picture** in the top right, and choose **Play Protect**.
3. Tap the **gear** in the top right and switch off **Scan apps with Play Protect**.
4. Open the downloaded file `CamperBU22.apk`, e.g. from **Files → Downloads**.
5. **"Install unknown apps":** tap **Settings → Allow from this source**, then go back.
6. Tap **Install**, then **Open**.
7. **Switch "Scan apps with Play Protect" back on** in the same place as steps 1–2. It takes 10 seconds and matters for your phone's security.

**Tapped OK on the block?** No problem. Switch off scanning and open the file again.

**Updating from an earlier version?** Just install over the old one. Don't uninstall first. That way you keep calibration, settings and statistics. If Play Protect blocks the update too, do the same as above.

## 3. The setup guide and Accessibility
The first time you open Camper BU22, the app shows a **setup guide**. It checks the phone one step at a time and briefly explains why each step is needed. Tap **Fix it** on every step that isn't OK.

The most important step is **Accessibility**. Camper BU22 taps in the VW app for you – only climate, temperature, Start and Stop. You switch it on once:

1. Tap **Fix it**.
2. Tap **Camper BU22** under **Downloaded apps** (Samsung: **Installed apps**).
3. Switch it on and tap **Allow**.

### Is Camper BU22 grey, or does it say "Restricted setting"?
That's normal the first time. It's Android's protection against apps from outside the Play Store.

1. Tap the grey **Camper BU22**. A message about **Restricted setting** appears. Tap **OK**.
2. Go to the phone's **Settings → Apps → Camper BU22** (or tap **Open app info** in the guide).
3. Tap **⋮** at the top right → **Allow restricted settings**. Confirm with your PIN or fingerprint.
4. Go back to **Accessibility → Camper BU22**. It is no longer grey. Switch it on.
5. Can't see **⋮** in step 3? Then you haven't tried to switch it on yet. Start again from step 1.

## 4. The other steps in the guide
- **Battery: Unrestricted:** tap **Fix it → Allow**. Then Android won't close the app at night.
- **Modify system settings:** tap **Fix it** → switch on **Allow modifying system settings** → go back. The app only raises the screen timeout during a session and puts your own setting back afterwards.
- **Notifications:** tap **Fix it → Allow**. Used for warnings such as a locked phone or lost access.
- **Alarm:** choose yourself whether you want to be woken. The default is no alarm.
- **Approximate location:** only used for the weather forecast for the battery forecast. The app works without it.

The guide runs a quick check every time you tap Start. You can also check yourself: **Settings → Help → Troubleshooting → Check my setup**. Everything should be green.

## 5. Settings for your phone brand
Many phones close background apps to save power. Then the restart doesn't happen, and the climate stops after about 30 minutes. Do this once:

- **All phones:** Settings → Apps → Camper BU22 → **App battery usage** (Samsung: **Battery**) → **Unrestricted**.
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
- **New versions:** the app checks for a new version by itself. You get one notification and a card on the home screen that opens the download page. Install it when no session is running.
- **VW updates:** if a new VW app makes Camper BU22 fail, the app tells the developer anonymously (VW version, app version, error code, phone model and the app's event log without any screen text). You can switch this off under **Settings → Phone**.
- **Never tap "Force stop"** on Camper BU22. Android then switches the service off, and nothing happens at night.

## 9. If something goes wrong
1. **Open Troubleshooting:** **Settings → Help → Troubleshooting**. Check your setup, see what happened in the last session, and tap whatever the problem is.
2. **Send a log:** **Statistics → Send log to the developer**. Your mail app opens with the log attached. Write a line about what happened. The log contains no login, passwords or location, only times, steps, temperatures and battery levels.
3. **Contact:** camperbu22@nyboledigital.dk

---

*Camper BU22 is an unofficial hobby project. It is not made by, endorsed by or affiliated with Volkswagen. The app may stop working if VW changes its app. Use at your own risk.*

Made by [NyboleDigital](https://nyboledigital.dk/?utm_source=github&utm_medium=install).
