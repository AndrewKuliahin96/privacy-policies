# Privacy Policy — Easy Piller (Таблетниця)

Last updated: 12 August 2026

## In short

The app collects nothing about you. It has no networking code at all.

## What the app stores

Your list of medications, the doses you mark as taken, how much of each you
have left, and your settings — theme, language and reminder times.

## Where it is stored

On your phone, in the app's own private storage, and nowhere else. There is no
account, no sign-up and no sync, because there is no server for any of those to
talk to.

On Android this is checkable rather than merely claimed: the release build
ships **without the `INTERNET` permission**, which Android shows in the app's
info screen. An app that cannot open a socket cannot send your medication list
anywhere.

The two permissions it does request are `POST_NOTIFICATIONS`, so reminders can
appear, and `RECEIVE_BOOT_COMPLETED`, so a queued reminder survives a restart.
A third, `VIBRATE`, is added by the notification library.

## Who else sees it

Nobody. Not the developer, not any third party. There is no analytics, no
advertising, no crash reporting SDK and no tracker of any kind in the app.

## Reminders

Reminders are created and displayed by your device's own operating system. Their
text is composed on the device from your medication names and is not
transmitted anywhere.

## Export and import

**Ліки → Дані → Експортувати** writes everything to a single JSON file and hands
it to the system share sheet. Where that file goes next is entirely your choice
— a messaging app, a cloud drive, your own computer — and from that moment it is
governed by whatever service you picked, not by this app.

**Імпортувати** reads such a file back through the system's file picker. Neither
feature needs a storage permission: both go through the system's own pickers,
which hand the app one file rather than access to your device.

Nothing leaves the device unless you export it yourself.

## Health data

The app records what you tell it about your own medication. That information is
sensitive, which is exactly why it stays where it is: it is never collected,
never transmitted and never shared. It is not written to any health platform —
the app does not integrate with Apple Health or Google Health Connect.

## Deleting your data

Deleting the app removes everything it stored, permanently. Individual
medications, along with their intake history, can be deleted inside the app.
There is no copy anywhere else for anyone to restore, which is the other half of
the same promise.

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

## Contact

**kulagin.andrew38@gmail.com**
