# Privacy policies

Published policies for Kuliahin apps. Each app has one file, linkable on its
own — app stores want a direct URL, not a page you have to navigate from.

| App | Policy | Support |
| --- | --- | --- |
| Mellow Mood Tracker (Android, iOS) | [MELLOW_MOOD_PRIVACY_POLICY.md](MELLOW_MOOD_PRIVACY_POLICY.md) | [MELLOW_MOOD_SUPPORT.md](MELLOW_MOOD_SUPPORT.md) |
| Habits Garden (Android, iOS) | [HABIT_GARDEN_PRIVACY_POLICY.md](HABIT_GARDEN_PRIVACY_POLICY.md) | [HABIT_GARDEN_SUPPORT.md](HABIT_GARDEN_SUPPORT.md) |
| Easy Piller · Таблетниця (Android, iOS) | [EASY_PILLER_PRIVACY_POLICY.md](EASY_PILLER_PRIVACY_POLICY.md) | [EASY_PILLER_SUPPORT.md](EASY_PILLER_SUPPORT.md) |
| Luma: Light Puzzle (iOS) | [LUMA_PRIVACY_POLICY.md](LUMA_PRIVACY_POLICY.md) | [LUMA_SUPPORT.md](LUMA_SUPPORT.md) |

## Adding another app

Copy the pattern: one `<APP>_PRIVACY_POLICY.md` at the root, one row in the
table. Keep the filenames stable — a store listing points at the URL, and
renaming the file breaks a link that is hard to notice is broken.

## Support pages

The App Store will not accept a submission without a support URL, and it has to
be a page rather than an email address. `<APP>_SUPPORT.md` covers that, and is
worth writing properly rather than as a placeholder: for an app with no account
and no server, most support questions have a fixed answer, and a page that
answers them is faster for everyone than a mailbox that repeats them.

## Keeping them true

A privacy policy is the one document that becomes a lie by standing still. When
an app gains a permission, an SDK, or anything that leaves the device, the
policy changes in the same week — not at the next release.

For all three apps, the claim to watch is that the Android build ships without
the `INTERNET` permission. It is checkable, which is what makes it
worth saying; it is also the first thing that would quietly stop being true if
either app ever took a dependency that wants the network. Flutter adds
`INTERNET` to debug and profile builds on its own, so the check has to be run
against a release artifact:

```bash
aapt2 dump permissions build/app/outputs/flutter-apk/app-release.apk
```

All three store apps have an export feature (Mellow's since version 1.3.0),
so none of their policies may say that nothing leaves the device: a file the
user exports goes wherever the user sends it, which is the user's choice, not
the app's.

And the phone's own backup and transfer carry each of the three apps' data on
purpose, held by Apple or Google under the user's account. Easy Piller's
policy names that since 14 October 2026, Mellow's and Habits Garden's since
15 October 2026; each used to say nothing else existed, which had never been
true. The promise all three make now is narrower and true: no account, nothing
is sent to us, the data is on the device and in its own backup if that is on —
the sentence each app shows from its next version on. If an app ever excludes
its data from the backup, its policy changes the same week.

Easy Piller records medication, so its policy carries one extra sentence the
other two do not need: the data is sensitive, which is the reason the app never
collects or sends it rather than a reason to handle it carefully somewhere else.
