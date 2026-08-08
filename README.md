# Privacy policies

Published policies for Kuliahin apps. Each app has one file, linkable on its
own — app stores want a direct URL, not a page you have to navigate from.

| App | Policy |
| --- | --- |
| Mellow Mood Tracker (Android, iOS) | [MELLOW_MOOD_PRIVACY_POLICY.md](MELLOW_MOOD_PRIVACY_POLICY.md) |

## Adding another app

Copy the pattern: one `<APP>_PRIVACY_POLICY.md` at the root, one row in the
table. Keep the filenames stable — a store listing points at the URL, and
renaming the file breaks a link that is hard to notice is broken.

## Keeping them true

A privacy policy is the one document that becomes a lie by standing still. When
an app gains a permission, an SDK, or anything that leaves the device, the
policy changes in the same week — not at the next release.

For Mellow specifically, the claim to watch is that the Android build ships
without the `INTERNET` permission. It is checkable, which is what makes it worth
saying; it is also the first thing that would quietly stop being true if the app
ever took a dependency that wants the network.
