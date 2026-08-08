# Privacy Policy — Habit Garden

**Last updated: 9 August 2026**

Habit Garden does not collect any personal data.

There is no account to create, no server to sync with, and nothing is sent
anywhere. This is not a promise about what we choose to do with your data — it
is a property of how the app is built.

## What the app stores, and where

Everything you enter stays in the app's own private storage on your device:

- the habits you plant: their names, icons, colours and how often you mean to
  do them
- which days you marked done, which you took as rest, and which you left
- your settings: theme, garden palette, flower shape, calendar style, week
  start, language, reminder time

Your habits and their days live in a SQLite database file inside the app's
private support directory. Settings live in Android's `SharedPreferences` or
iOS's `UserDefaults`. Both locations are sandboxed by the operating system: no
other app can read them, and neither is visible in the Files app or through a
USB connection.

Uninstalling the app deletes all of it.

Habits you dig up are kept for 30 days so they can be restored, then removed
permanently. Until then they are still in the database, hidden from the garden.

## What the app does not do

- No analytics, no crash reporting, no advertising, no tracking of any kind.
- No third-party SDK that transmits anything.
- No access to contacts, photos, location, health data, the camera, or the
  microphone.
- No backup to any cloud service run by us.

**The Android build has no `INTERNET` permission at all.** You can confirm this
yourself in Android's app info screen. Without that permission the operating
system will not let the app open a network connection, so there is no way for
your garden to leave the device — not by design decision, not by accident, and
not by a future bug.

The Android build requests exactly three permissions, all of them for the daily
reminder: `POST_NOTIFICATIONS` to show it, `RECEIVE_BOOT_COMPLETED` to put the
reminder back after the phone restarts, and `VIBRATE`.

The iOS build contains no networking code for the same reason, though iOS has no
equivalent permission to point at as proof.

## Notifications

If you turn on the daily reminder, the app schedules a local notification on
your device at the time you choose. It is generated on the phone. No push
service is involved and no reminder passes through any server.

The reminder is skipped on days when everything is already done, which the app
works out on the device from data that never leaves it.

## Data you export yourself

**Settings → Export** writes your whole garden to a JSON file and hands it to
the system share sheet. From that point the file goes wherever you send it —
a messaging app, a cloud drive, your own computer — and this policy no longer
covers it, because it is no longer in the app's hands. The app has no
destination of its own and no default: it cannot send the file anywhere you did
not choose.

**Settings → Import** reads a file you pick through the system file picker and
replaces the current garden with it. The app sees only the file you select.

Neither feature needs a storage permission on Android: both go through the
system's own pickers, which hand the app a single file rather than access to
your device.

## Children

The app is not directed at children and collects nothing from anyone, of any
age.

## Google Play

If you installed the app from Google Play, Google collects its own data about
the installation under
[Google's Privacy Policy](https://policies.google.com/privacy). That is between
you and Google; the app itself neither sees nor receives any of it.

## Changes

If this policy changes, the date at the top changes with it, and the previous
wording stays in this file's history.

## Contact

Questions about this policy can go to the developer contact address shown on
the app's Google Play listing, under **Contact the developer**.

One address, kept in one place, so it cannot fall out of step with the one the
store shows. To publish a direct address here as well, replace this paragraph
with it.
