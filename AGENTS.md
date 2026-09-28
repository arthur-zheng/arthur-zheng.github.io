# Public app website

This repository is the public support and privacy website for Arthur Zheng's apps.

## App paths

- Meadows: `/meadows/`
- Meadows support: `/meadows/support/`
- Meadows privacy: `/meadows/privacy/`
- PianoKid (小琴童): `/pianokid/`, support `/pianokid/support/`, privacy `/pianokid/privacy/` (bilingual, EN/中文 toggle)

When adding a new app, give it its own top-level path and add it to the root `index.html`. Keep each app's support and privacy pages under that app's path. Do not put source code, journal data, secrets, certificates, or signing files in this repository.

## Meadows source

The iOS source repository is `/Users/arthur/code/iOS/Meadows` and its private GitHub repository is `arthur-zheng/meadows`. Changes to product behavior belong there; this repository only contains the public web pages linked from App Store Connect.

## PianoKid source

The iOS source is `/Users/arthur/code/iOS/PianoKid`. The privacy page states that the app has no network access, collects no data, never stores microphone audio, and keeps local practice logs; change the page if any of that changes.
