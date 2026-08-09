# Privacy policies

Published policies for Kuliahin apps. Each app has one file, linkable on its
own — app stores want a direct URL, not a page you have to navigate from.

| App | Policy | Support |
| --- | --- | --- |
| Mellow Mood Tracker (Android, iOS) | [MELLOW_MOOD_PRIVACY_POLICY.md](MELLOW_MOOD_PRIVACY_POLICY.md) | [MELLOW_MOOD_SUPPORT.md](MELLOW_MOOD_SUPPORT.md) |
| Habit Garden (Android, iOS) | [HABIT_GARDEN_PRIVACY_POLICY.md](HABIT_GARDEN_PRIVACY_POLICY.md) | — |

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

For Mellow and Habit Garden both, the claim to watch is that the Android build
ships without the `INTERNET` permission. It is checkable, which is what makes it
worth saying; it is also the first thing that would quietly stop being true if
either app ever took a dependency that wants the network. Flutter adds
`INTERNET` to debug and profile builds on its own, so the check has to be run
against a release artifact:

```bash
aapt2 dump permissions build/app/outputs/flutter-apk/app-release.apk
```

Habit Garden additionally has an export feature, which Mellow does not. That
makes its policy's claim narrower and worth reading carefully: nothing leaves
the device *unless the user exports it themselves*, and where it goes after that
is the user's choice, not the app's.
