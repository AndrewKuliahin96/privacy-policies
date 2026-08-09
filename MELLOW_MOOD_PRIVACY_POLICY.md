# Privacy Policy — Mellow Mood Tracker

**Last updated: 8 August 2026**

Mellow Mood Tracker does not collect any personal data.

There is no account to create, no server to sync with, and nothing is sent
anywhere. This is not a promise about what we choose to do with your data — it
is a property of how the app is built.

## What the app stores, and where

Everything you enter stays in the app's own private storage on your device:

- the mood, energy, sleep and tags you record for a day
- anything you write in the note field
- your habits and which days you ticked them
- the name you type in Settings, if you type one
- your settings: reminder time, week start, appearance

On Android this is the app's private `SharedPreferences`, shared with the
home-screen widget through the app's own storage. On iOS it is the app's
`UserDefaults`, shared with the widget through a private App Group. Both are
sandboxed by the operating system: no other app can read them.

Uninstalling the app deletes all of it. So does **Settings → Start fresh —
erase everything**, which is immediate and cannot be undone.

## What the app does not do

- No analytics, no crash reporting, no advertising, no tracking of any kind.
- No third-party SDK that transmits anything.
- No access to contacts, photos, location, health data, or the microphone.
- No backup to any cloud service run by us.

**The Android build has no `INTERNET` permission at all.** You can confirm this
yourself in Android's app info screen. Without that permission the operating
system will not let the app open a network connection, so there is no way for
your entries to leave the device — not by design decision, not by accident, and
not by a future bug.

The iOS build contains no networking code for the same reason, though iOS has no
equivalent permission to point at as proof.

## Notifications

If you turn on the daily reminder, the app schedules a local notification on
your device at the time you choose. It is generated on the phone. No push
service is involved and no reminder passes through any server.

## Data you export yourself

The app has no export or sharing feature. Nothing leaves the device unless you
copy it out by hand.

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

Questions about this policy: **kulagin.andrew38@gmail.com**

The same address is shown on the app's store listings, under **Contact the
developer** on Google Play and **App Support** on the App Store.
