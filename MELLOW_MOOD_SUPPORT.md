# Support — Mellow Mood Tracker

A quiet place to notice how you feel, one day at a time.

Most questions about this app have the same answer, so they are written out
below rather than left for an email.

## Where is my data?

On your phone, in the app's own private storage, and nowhere else. There is no
account and no server. Nothing is uploaded, so there is nothing to log into and
nothing to recover from a support desk.

The full detail is in the [privacy policy](MELLOW_MOOD_PRIVACY_POLICY.md).

## I deleted the app. Can I get my history back?

Only from a file you exported yourself. Because your entries never leave the
device, uninstalling takes them with it — nobody holds a copy that could be
restored for you.

Since version 1.2.0, **Settings → Export** writes your whole history to a
single file and hands it to the share sheet. A file you have sent somewhere —
your email, your files, anywhere — survives the app. If you never exported,
the history is gone, and that is worth knowing before it happens.

## I am moving to a new phone. How do I bring my history?

**Settings → Export** on the old phone, send the file to yourself, then
**Settings → Import** on the new one and pick that file. Import replaces what
is in the app with the contents of the file — it says so before it does it —
so do it before you start logging days on the new phone, not after.

## How do I erase everything?

**Settings → Start fresh — erase everything.** It asks once, then does it
immediately. Every saved day and every habit goes; nothing else on the phone is
touched.

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

The widget refreshes when the app saves a day. If it is showing yesterday, open
the app once — that pushes the current day to it.

Tapping a dot logs a mood without opening the app. On iOS this needs iOS 17 or
later; on older versions the tap opens the app instead.

## Something else

Write to **kulagin.andrew38@gmail.com**, or open an issue in
[this repository](https://github.com/AndrewKuliahin96/privacy-policies/issues)
if you would rather it were public.

Please say which phone and which OS version. For anything that looks like a
crash, the store consoles already collect the report automatically, so the
version number is usually enough to find it.
