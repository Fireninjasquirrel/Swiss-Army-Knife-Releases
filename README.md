# Jack Of All Widgets

A small floating widget for Windows that stays on top of your other windows. It has a media player
(it controls whatever's already playing: Spotify, YouTube in a browser, and so on), plus a clock,
weather, stopwatch, timers, and a view-only Google Calendar.

This repository only holds the installers.

## Download
Go to **[Releases](../../releases/latest)** and download `SwissArmyKnife-Setup-<version>.exe`.

Windows will probably say **"Windows protected your PC"**, because the app isn't code-signed yet.
Click **More info → Run anyway**. You don't need admin rights.

## Updates
The app checks for new versions once a day. When one is out, a dot appears on the ⚙ gear.
Open **Settings → Updates** and click **Update**. Your settings are kept.

## Uninstalling
**Settings → Apps → Installed apps → Jack Of All Widgets → Uninstall.** The uninstaller asks whether
to also delete your settings and Google sign-in.

## Privacy
- Weather: your chosen city's location is sent to Open-Meteo.com.
- Calendar (only if you sign in): read-only access to your Google Calendar. The sign-in is stored
  encrypted on your PC.
- Update checks: the app asks GitHub for the latest release. Nothing about you is sent.
- Nothing else is collected.
