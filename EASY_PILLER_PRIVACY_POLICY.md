# Privacy Policy — Easy Piller (Таблетниця)

Last updated: 16 October 2026

## In short

The app collects nothing about you and sends nothing to us. It has no
networking code at all. Your data lives on your device — and in the device's
own backup, if you have that turned on.

## What the app stores

Your list of medications, the doses you mark as taken, how much of each you
have left, and your settings — theme, language and reminder times. For the
one-time rating request described below, it also keeps up to seven dates on
which the app was opened, and whether the request was made.

## Where it is stored

On your device — phone or tablet — in the app's own private storage. There is
no account, no sign-up and no sync, because there is no server for any of
those to talk to.

On Android this is checkable rather than merely claimed: the release build
ships **without the `INTERNET` permission**, which Android shows in the app's
info screen. An app that cannot open a socket cannot send your medication list
anywhere.

The two permissions it does request are `POST_NOTIFICATIONS`, so reminders can
appear, and `RECEIVE_BOOT_COMPLETED`, so a queued reminder survives a restart.
A third, `VIBRATE`, is added by the notification library.

## Your device's own backup

Your device can keep a copy of the app's data in its own backup, and the app
deliberately lets it, so that your medications and their history can come with
you to a new device:

- **iPhone and iPad:** iCloud Backup, or a backup to your computer, includes
  the app's data when it is turned on, and so does moving to a new device from
  one of those backups or directly from the old one.
- **Android:** the system backup to your Google account includes the app's
  data when it is turned on, and so does the system's transfer to a new device.

That copy is made by the operating system, not by the app. It is held by Apple
or Google under your account and under their privacy policies
([Apple](https://www.apple.com/legal/privacy/),
[Google](https://policies.google.com/privacy)). The developer cannot see it and
receives nothing from it. If you would rather the app's data were not in that
backup, turn the backup off — or, where your device lets you choose apps,
leave Easy Piller out of it.

## Who else sees it

Nobody through the app — not the developer, not any third party. There is no
analytics, no advertising, no crash reporting SDK and no tracker of any kind in
the app. The only copies outside the app are the ones described here: your
device's own backup and its transfer to a new device, and any file you export
yourself.

## Reminders

Reminders are created and displayed by your device's own operating system. Their
text is composed on the device from your medication names and is not sent
anywhere by the app.

## Export and import

**Ліки → Дані → Експортувати** writes everything to a single JSON file and hands
it to the system share sheet. Where that file goes next is entirely your choice
— a messaging app, a cloud drive, your own computer — and from that moment it is
governed by whatever service you picked, not by this app.

**Імпортувати** reads such a file back through the system's file picker. Neither
feature needs a storage permission: both go through the system's own pickers,
which hand the app one file rather than access to your device.

The app itself sends nothing anywhere. Your data leaves the device only in a
file you export yourself, or in your device's own backup and transfer described
above.

## Buttons that open other apps

A few buttons at the bottom of **Meds** open another app, and none of your
medications or history goes with them:

- **Rate the app** and **Our other apps** open this app's page, or our other
  apps' pages, in the App Store or Google Play. Once the app has been opened on
  seven different days, it may also ask the store, once, to show its own
  rating dialog; whether it appears is up to Apple or Google, and a rating you
  give goes to the store under its policy, as any store rating does.
- **Feedback** opens your mail app with our address and a subject line naming
  the app's version, your platform and your language. Nothing is sent unless
  you send the email yourself; if you do, we receive what you wrote and your
  email address, and use them only to answer you.
- **Privacy policy** (from version 1.6.0) opens this page in your browser.

## Health data

The app records what you tell it about your own medication. That information is
sensitive, which is exactly why the app never collects it, never sends it
anywhere and never shares it. It is not written to any health platform — the app
does not integrate with Apple Health or Google Health Connect.

## Deleting your data

Deleting the app removes everything it stored on the device. Individual
medications, along with their intake history, can be deleted inside the app.

A copy can remain in your device's own backup until that backup is replaced or
you delete it there, and restoring it can bring the data back — on Android,
reinstalling the app can restore it too. That is what the backup is for. The
developer holds no copy, so there is nothing we could restore or delete for
you.

## Children

The app is not directed at children and collects nothing from anyone, of any
age.

## Not medical advice

Easy Piller is a diary. It gives no medical advice, makes no diagnosis, suggests
no dose, and is not a substitute for a doctor or a pharmacist.

## App stores

If you installed the app from Google Play or the App Store, that store collects
its own data about the installation under
[Google's Privacy Policy](https://policies.google.com/privacy) or
[Apple's Privacy Policy](https://www.apple.com/legal/privacy/). That is between
you and them; the app itself neither sees nor receives any of it.

## Changes

If this policy changes, the date at the top changes with it, and the previous
wording stays in this file's history.

On 14 October 2026 this policy stopped saying that nothing leaves the device
unless you export it, and that no copy exists anywhere else. The phone's own
backup had always been able to carry the app's data; the app now says so, here
and on its Meds screen, instead of promising otherwise.

On 16 October 2026 it began to name the buttons that open another app — Rate
the app, Our other apps, Feedback and Privacy policy — and the one-time
rating request, which it had left out; and to say «device» where it said
«phone», because the app runs on iPad and Android tablets too.

## Contact

**kulagin.andrew38@gmail.com**
