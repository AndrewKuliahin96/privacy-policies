# Support — Habit Garden

A habit tracker that does not push. Plant a habit, tend it on the days you can,
and watch it grow.

Most questions about this app have the same answer, so they are written out
below rather than left for an email.

## Where is my data?

On your phone, in the app's own private storage, and nowhere else. There is no
account and no server. Nothing is uploaded, so there is nothing to log into and
nothing to recover from a support desk.

The full detail is in the [privacy policy](HABIT_GARDEN_PRIVACY_POLICY.md).

## I am moving to a new phone. How do I bring my garden?

**Settings → Export** writes everything to a single file and hands it to the
share sheet. Send it to yourself however you like, then on the new phone use
**Settings → Import** and pick that file.

Import **replaces** the current garden rather than merging with it. Two gardens
with the same habit names and overlapping days have no honest way to be
reconciled, and a silent merge would leave you unsure what you now have.

## I deleted the app. Can I get my garden back?

Only from a file you exported yourself. Because your habits never leave the
device, uninstalling takes them with it — there is no copy anywhere for anyone
to restore. Export before you delete.

## Why did my streak not break when I took a rest day?

Because that is the point of the app. A day has three answers, not two: done,
rest, or not yet.

Rest freezes a streak instead of breaking it — and it does not extend it
either. The tag shows both numbers, "9-day streak · 2 rest days", so the streak
stays honest and the rest stays free.

## Why can I not tick a day from three weeks ago?

Adding a mark is limited to the last seven days. Removing one never is.

The asymmetry is deliberate: it stops a streak being drawn in after the fact,
without getting in the way of fixing a tap you made by mistake.

## The daily reminder is not appearing

Three things to check, in this order:

1. **Settings** in the app — the reminder toggle, and the time next to it.
2. Whether a **quiet week** is running. It turns the reminder off for seven
   days and back on by itself.
3. Your phone's own notification settings for Habit Garden. If notifications
   are switched off there, nothing the app does can override it.

There is also a case where it is silent on purpose: the reminder is skipped on
days when everything is already done. A nudge about a finished garden is noise.

## A habit disappeared

Two possibilities. If you put it in the **greenhouse** it is paused, not gone —
open any habit's page to find the greenhouse and bring it back. If you **dug it
up**, it is recoverable for thirty days, after which it is removed for good.

## Why is there no sync between my devices?

Because syncing needs a network, and this app has none. On Android you can
confirm that yourself: it ships with no `INTERNET` permission at all, which is
visible in Android's app info screen. That is the trade, made deliberately.
Export and import move a garden between devices instead.

## The flowers moving bothers me

**Settings → Flowers sway** turns it off. The system's own "Reduce Motion"
setting stops it too, if you would rather set it once for every app.

## Something else

Write to **kulagin.andrew38@gmail.com**, or open an issue in
[this repository](https://github.com/AndrewKuliahin96/privacy-policies/issues)
if you would rather it were public.

Please say which phone and which OS version. For anything that looks like a
crash, the store consoles already collect the report automatically, so the
version number is usually enough to find it.
