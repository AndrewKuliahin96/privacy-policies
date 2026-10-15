# Privacy Policy — Mellow Mood Tracker

**Last updated: 15 October 2026**

## In short

Mellow Mood Tracker collects nothing about you and sends nothing to us. There
is no account to create and no server to sync with, and the app contains no
networking code at all. Your entries live on your device — and in your
device's own backup, if you have that turned on.

## What the app stores

- the mood, energy, sleep and tags you record for a day, including the names
  of any check-in options you add yourself
- anything you write in the note field
- your habits and which days you ticked them
- the name you type in Settings, if you type one
- your settings: the daily reminder and its time, week start, appearance
- up to seven dates on which the app was opened, and whether it has already
  asked once for a rating — kept apart from your entries and used for nothing
  else

## Where it is stored

On your device, in the app's own private storage: Android's
`SharedPreferences`, which the home-screen widget reads from the same place,
or iOS's `UserDefaults`. Both are sandboxed by the operating system: no other
app can read them. There is no account, no sign-up and no sync, because there
is no server for any of those to talk to.

On Android this is checkable rather than merely claimed: the build has **no
`INTERNET` permission at all**, which Android shows in the app's info screen.
Without that permission the operating system will not let the app open a
network connection, so the app cannot send your entries anywhere — not by our
decision, and not by our mistake. The iOS build contains no networking code
for the same reason, though iOS has no equivalent permission to point at as
proof.

## Your device's own backup

Your device can keep a copy of the app's data in its own backup, and the app
lets it, so that your entries can come with you to a new phone:

- **iPhone and iPad:** iCloud Backup, or a backup to your computer, includes
  the app's data when it is turned on, and so does moving to a new device from
  one of those backups or directly from the old one.
- **Android:** the system backup to your Google account includes the app's
  data when it is turned on, and so does the system's transfer to a new phone.

That copy is made by the operating system, not by the app. It is held by
Apple or Google under your account and under their privacy policies
([Apple](https://www.apple.com/legal/privacy/),
[Google](https://policies.google.com/privacy)), or on your own computer. The
developer cannot see it and receives nothing from it. If you would rather the
app's data were not in that backup, turn the backup off — or, where your phone
lets you choose apps, leave Mellow out of it.

## What the app does not do

- No analytics, no crash reporting, no advertising, no tracking of any kind.
- No third-party SDK that transmits anything.
- No access to contacts, photos, location, health data, the camera or the
  microphone.
- No backup or sync to any service run by us.

## Notifications

If you turn on the daily reminder, the app schedules a local notification on
your device at the time you choose. It is generated on the device. No push
service is involved and no reminder passes through any server.

## Export and import

**Settings → Export** writes your whole history to a single file and hands it
to the system share sheet. Where that file goes next is entirely your choice —
a messaging app, a cloud drive, your own computer — and from that moment it is
governed by whatever service you picked, not by this app.

**Settings → Import** reads such a file back through the system's file picker
and replaces what is in the app with it. Neither feature needs a storage
permission: both go through the system's own pickers, which hand the app one
file rather than access to your device.

## Buttons that open other apps

A few buttons in Settings open another app, and none of your entries goes
with them:

- **Privacy policy** opens this page in your browser.
- **Rate the app** and **Our other apps** open this app's page, or our other
  apps' pages, in the App Store or Google Play. The app may also, once, ask the
  store to show its own rating dialog; whether it appears is up to Apple or
  Google, and a rating you give goes to the store under its policy, as any
  store rating does.
- **Feedback** opens your mail app with our address and a subject line naming
  the app's version, your platform and your language. Nothing is sent unless
  you send the email yourself; if you do, we receive what you wrote and your
  email address, and use them only to answer you.

## Who else sees your entries

Nobody through the app — not the developer, not any third party. The only
copies outside the app are the ones described here: your device's own backup,
and any file you export yourself.

## Deleting your data

**Settings → Start fresh — erase everything** removes every saved day and
habit from the device at once, and cannot be undone. Deleting the app removes
everything it stored on the device.

A copy can remain in your device's own backup until that backup is replaced
or you delete it there, and restoring it can bring the data back — on Android,
reinstalling the app can restore it too. That is what the backup is for. The
developer holds no copy, so there is nothing we could restore or delete for
you.

## Children

The app is not directed at children and collects nothing from anyone, of any
age.

## App stores

If you installed the app from Google Play or the App Store, that store
collects its own data about the installation under
[Google's Privacy Policy](https://policies.google.com/privacy) or
[Apple's Privacy Policy](https://www.apple.com/legal/privacy/). That is
between you and them; the app itself neither sees nor receives any of it.

## Changes

If this policy changes, the date at the top changes with it, and the previous
wording stays in this file's history.

On 15 October 2026 this policy stopped saying that there is no way for your
entries to leave the device and that uninstalling deletes all of it: the
device's own backup had always been able to carry the app's data, and the app
now says so, here and in its Settings, instead of promising otherwise. The
same day it stopped saying the app has no export (export arrived in version
1.3.0) and that an iOS widget shares the data through an App Group (there is
no iOS widget), and it started naming the buttons that open other apps.

## Contact

Questions about this policy: **kulagin.andrew38@gmail.com**

The same address is shown on the app's store listings, under **Contact the
developer** on Google Play and **App Support** on the App Store.
