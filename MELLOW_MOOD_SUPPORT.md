# Support — Mellow Mood Tracker

A quiet place to notice how you feel, one day at a time.

Most questions about this app have the same answer, so they are written out
below rather than left for an email.

## Where is my data?

On your phone, in the app's own private storage. There is no account and no
server. Nothing is uploaded to us, so there is nothing to log into and nothing
for a support desk to recover.

If your phone's own backup is turned on — iCloud or a computer backup on iPhone
and iPad, the Google backup on Android — it includes the app's data too. That
copy is made and held by Apple or Google under your account, not by us.

The full detail is in the [privacy policy](MELLOW_MOOD_PRIVACY_POLICY.md).

## I deleted the app. Can I get my history back?

From a file you exported yourself, or from your phone's own backup if it was
turned on: on Android, reinstalling the app can restore it; on iPhone, only
restoring the whole phone from a backup made before the app was deleted brings
it back. We hold no copy, so there is nothing we can send you.

Since version 1.3.0, **Settings → Export** writes your whole history to a
single file and hands it to the share sheet. A file you have sent somewhere —
your email, your files, anywhere — survives the app and any backup. Export
before you delete.

## I am moving to a new phone. How do I bring my history?

**Settings → Export** on the old phone, send the file to yourself, then
**Settings → Import** on the new one and pick that file. This is the way that
always works, including from Android to iPhone and back.

If you move with your phone's own transfer, or set the new phone up from a
backup of the old one, your entries may already be there when you open the
app. That is the system's doing and has not been checked on every phone, so
look before you rely on it — and keep the exported file until you have.

Import replaces what is in the app with the contents of the file — it says so
before it does it — so do it before you start logging days on the new phone,
not after.

## How do I erase everything?

**Settings → Start fresh — erase everything.** It asks once, then does it
immediately. Every saved day and every habit goes; nothing else on the phone is
touched. A copy made earlier by your phone's own backup stays there until the
backup is replaced or you delete it.

## The daily reminder is not appearing

Two things to check, in this order:

1. **Settings** in the app — the reminder toggle, and the time next to it.
2. Your phone's own notification settings for Mellow. If notifications are
   switched off there, the app says so when you turn the reminder on, and
   nothing it does can override that.

## Why is there no sync between my devices?

Because syncing needs a network, and this app has none. On Android you can
confirm that yourself: it ships with no `INTERNET` permission at all, which is
visible in Android's app info screen. That is the trade, made deliberately.
Export and import move a history between devices instead.

## The home-screen widget is not updating

The widget is on Android only for now. It refreshes when the app saves a day,
and turns to the new day by itself at midnight. If it is showing yesterday,
open the app once — that pushes the current day to it.

Tapping a dot logs a mood without opening the app.

## Something else

Write to **kulagin.andrew38@gmail.com** — **Settings → Feedback** opens your
mail app with the address and the app's version already filled in — or open
an issue in
[this repository](https://github.com/AndrewKuliahin96/privacy-policies/issues)
if you would rather it were public.

Please say which phone and which OS version. For anything that looks like a
crash, the store consoles already collect the report automatically, so the
version number is usually enough to find it.
