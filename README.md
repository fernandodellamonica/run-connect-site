# Run Connect — Project Website

This repository contains the public website, branding asset, and privacy notices for Run Connect.

Run Connect is an independent, non-commercial learning and development project created by Fernando Della Monica Pereira in Brazil. It is currently intended for personal and family use.

## Site files

- `index.html` — project overview
- `privacy.html` — privacy policy (English)
- `privacy.pt-BR.html` — privacy policy (Brazilian Portuguese)
- `assets/style.css` — site styles
- `assets/run-connect-brand.svg` — 300 × 300 branding image for developer portal registration

## Garmin Connect status

Run Connect is exploring an official Garmin Connect integration. No Garmin integration is currently active. The intended initial scope is Activity API (receive authorized user activities) and Training API (send user-created structured workouts to Garmin Connect).

Official program information:
- https://developer.garmin.com/gc-developer-program/overview/
- https://developer.garmin.com/gc-developer-program/enterprise/program-faq/

## Publishing

GitHub Pages publishes the `main` branch from the repository root.

The privacy-policy URL should remain available while the app handles account, activity, or location information. If the site is ever moved, configure a redirect from the existing policy URL rather than simply removing it.

This repository is separate from the private Run Connect application repository. Never add application source code, credentials, API secrets, database passwords, or private user data here.

Contact: runconnect@proton.me
