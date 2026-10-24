# CLAUDE.md

The home of AllSense by OtterBridge: the README people land on (what it is, download, the map of the other repos), the app's issue tracker (`.github/ISSUE_TEMPLATE/`), the app's CHANGELOG, and the app's releases (APKs). No code: the app's code is in a private repository. Public.

## Working here

- **The user makes every commit and push.** Edit files, then hand over: what changed and a one-line commit message suggestion. Never run `git commit`, `git push`, tags or releases; add no Co-Authored-By line unless asked.
- **Public repository:** never write the user's serials, IPs, Wi-Fi details, home location, tokens or file paths into it. Screenshots: never of a connect guide or Settings → Server (they show the pairing token); Location only with coordinates hidden. Machine facts go in `CLAUDE.local.md` (git-ignored).
- **Not open source:** the README, images and releases are © wen-da-ng; there is deliberately no LICENSE file. The libraries, protocol, starters and docs are MIT in their own repos.

## How it fits

- Releases: each APK is built and signed from the private app repo and published here with its SHA-256 and the signing certificate's SHA-256; add a CHANGELOG entry for each.
- Screenshots in `images/{light,dark}/` are copies of the docs site's (`otterbridge-allsense-docs/docs/images/app/`).
- Library and protocol issues belong in their own repos; the issue chooser (`config.yml`) points there.
