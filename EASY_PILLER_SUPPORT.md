# Support — Easy Piller (Таблетниця)

A medication tracker that does not ask for a time. Mark a dose in its part of
the day — morning, daytime or evening — and that is the whole interaction.

Most questions about this app have the same answer, so they are written out
below rather than left for an email.

## Where is my data?

On your phone, in the app's own private storage, and nowhere else. There is no
account and no server. Nothing is uploaded, so there is nothing to log into and
nothing for a support desk to recover.

The full detail is in the [privacy policy](EASY_PILLER_PRIVACY_POLICY.md).

## Why can I not set a time like 08:00?

Because a dose belongs to a part of the day, not to a minute on the clock.
Somebody who takes a tablet with breakfast does not take it at 08:00 sharp, and
an app that insists otherwise builds a wall of misses that never happened.

If the time genuinely matters for one medication — melatonin before bed, say —
open that medication and switch on **Нагадування на точний час**. It is
per-medication and entirely optional.

## My reminder arrived a few minutes late

That is intended, and the app says so under the exact-time switch: *"Приблизно
у цей час"*. Reminders are scheduled inexactly.

Android grants exact alarms only to apps built around them, and asking for that
privilege would contradict the one idea this app is built on. A nudge near a
time is what it promises and what it delivers. It is not an alarm clock.

## A reminder did not arrive at all

Three things to check, in order:

1. **Is the toggle on?** Reminders start switched off. A switch that looked
   armed before you had granted notification permission would be a promise the
   app cannot keep, so it stays off until you turn it on.
2. **Was permission granted?** The app asks the moment you switch a reminder on.
   If you declined, Android and iOS both stop asking, and the only way back is
   the system Settings app for Easy Piller.
3. **Was everything already marked?** A reminder for a part of the day is
   skipped once every dose in it is ticked. That is deliberate — being nudged
   about something you have already done is how people learn to ignore an app.

Battery optimisation on some Android phones (Xiaomi, Huawei, Samsung in
aggressive modes) will also delay or drop scheduled notifications. If reminders
are consistently missing, allow the app to run in the background in your
phone's battery settings.

## I am moving to a new phone. How do I bring my history?

**Ліки → Дані → Експортувати** writes everything to a single file and hands it
to the share sheet. Send it to yourself however you like, then on the new phone
use **Імпортувати** and pick that file.

Import **replaces** what is on the device rather than merging with it. Two
phones with the same medication names and overlapping days have no honest way
to be reconciled, and a silent merge would leave you unsure what you now have —
about medication, which is the worst subject to be unsure about.

## I deleted the app. Can I get my history back?

Only from a file you exported yourself. Because your record never leaves the
device, uninstalling takes it with it. Export before you delete.

## I finished a course. How do I get it off the Today screen?

Open the medication and choose **Більше не приймаю**. It leaves Today and the
active list, and its entire intake history stays. If you change your mind, the
snackbar has an undo, and the medication itself has **Приймаю знову**.

**Видалити назавжди** is the other option, and it is deliberately one step
further in — only reachable from a medication you have already stopped. That one
takes the history with it and cannot be undone.

## Why did a day I archived on stop counting?

A medication stops being due from the day you archive it, that day included. If
it counted through the archive day, stopping something in the evening would
leave the rest of that day looking like a run of missed doses that never
happened.

## Why can I not edit yesterday?

History is read-only on purpose. Being able to fill in a week after the fact is
the one feature that would let this app tell you a comfortable lie about your
own medication, and the honest version is the only useful one.

## What does "Залишилось" count, and why did it change?

It is how much of that medication you have left, in the unit its form implies —
pieces, millilitres or doses. It goes down by one every time you mark a dose,
and back up if you un-mark it, so correcting a mis-tap costs nothing.

If you never enter a supply it simply sits at zero, which is the honest reading
of "I do not know how many are left".

## Does it work on a tablet?

Yes. From about 840 dp of width — an iPad in portrait, any tablet in landscape —
the navigation moves to a rail down the side and the content splits into two
columns. Smaller tablets stay in the single-column phone layout, because two
cramped columns are worse than one comfortable one.

## Does it sync between my devices?

No, and it cannot: syncing needs a network, and this app has none. On Android
you can confirm that yourself — the release build ships with no `INTERNET`
permission, visible in Android's app info screen. That is the trade, made
deliberately. Export and import move a record between devices instead.

## Something else

Write to **kulagin.andrew38@gmail.com**, or open an issue in
[this repository](https://github.com/AndrewKuliahin96/privacy-policies/issues)
if you would rather it were public.

Please say which phone and which OS version. For anything that looks like a
crash, the store consoles already collect the report automatically, so the
version number is usually enough to find it.
