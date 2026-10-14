# Privacy Policy — Easy Piller (Таблетниця)

Last updated: 14 October 2026

## In short

The app collects nothing about you and sends nothing to us. It has no
networking code at all. Your data lives on your phone — and in your phone's own
backup, if you have that turned on.

## What the app stores

Your list of medications, the doses you mark as taken, how much of each you
have left, and your settings — theme, language and reminder times.

## Where it is stored

On your phone, in the app's own private storage. There is no account, no
sign-up and no sync, because there is no server for any of those to talk to.

On Android this is checkable rather than merely claimed: the release build
ships **without the `INTERNET` permission**, which Android shows in the app's
info screen. An app that cannot open a socket cannot send your medication list
anywhere.

The two permissions it does request are `POST_NOTIFICATIONS`, so reminders can
appear, and `RECEIVE_BOOT_COMPLETED`, so a queued reminder survives a restart.
A third, `VIBRATE`, is added by the notification library.

## Your phone's own backup

Your phone can keep a copy of the app's data in its own backup, and the app
deliberately lets it, so that your medications and their history can come with
you to a new phone:

- **iPhone and iPad:** iCloud Backup, or a backup to your computer, includes
  the app's data when it is turned on, and so does moving to a new device from
  one of those backups or directly from the old one.
- **Android:** the system backup to your Google account includes the app's
  data when it is turned on, and so does the system's transfer to a new phone.

That copy is made by the operating system, not by the app. It is held by Apple
or Google under your account and under their privacy policies
([Apple](https://www.apple.com/legal/privacy/),
[Google](https://policies.google.com/privacy)). The developer cannot see it and
receives nothing from it. If you would rather the app's data were not in that
backup, turn the backup off — or, where your phone lets you choose apps, leave
Easy Piller out of it.

## Who else sees it

Nobody through the app — not the developer, not any third party. There is no
analytics, no advertising, no crash reporting SDK and no tracker of any kind in
the app. The only copies outside the app are the ones described here: your
phone's own backup, and any file you export yourself.

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
file you export yourself, or in your phone's own backup and transfer described
above.

## Health data

The app records what you tell it about your own medication. That information is
sensitive, which is exactly why the app never collects it, never sends it
anywhere and never shares it. It is not written to any health platform — the app
does not integrate with Apple Health or Google Health Connect.

## Deleting your data

Deleting the app removes everything it stored on the phone. Individual
medications, along with their intake history, can be deleted inside the app.

A copy can remain in your phone's own backup until that backup is replaced or
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

## Contact

**kulagin.andrew38@gmail.com**
