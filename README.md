# SwaraGee — legal pages

The public legal documents for the [SwaraGee](https://swaragee.com) mobile app,
served by GitHub Pages.

| Page | URL |
|---|---|
| Privacy Policy | `/privacy.html` (also the site root) |

## How this is maintained

**Do not edit the HTML here by hand.** The source of truth is
`docs/legal/PRIVACY-POLICY.md` in the main SwaraGee repository; these pages are
generated from it. Editing the output means the next regeneration silently
discards your change, and the version a regulator reads stops matching the
version the team reviewed.

## Why a separate repository

The main repository is private, and serving Pages from its `docs/` folder would
publish the backlog, the bug list and every architecture document along with
the policy. This repository contains the legal pages and nothing else.

## Moving to swaragee.com

When the apex resolves, add a `CNAME` file and set the custom domain in the
repository's Pages settings. The URL in AdMob, in both store listings and in the
app's Settings screen should be updated at the same time — a privacy policy URL
that 404s is worse than one on a github.io domain.
