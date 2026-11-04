# Run Connect public website

Static landing page and bilingual privacy-policy drafts for the Run Connect project.

## Files

- `index.html` — project landing page
- `privacy.html` — English privacy-policy draft
- `privacy.pt-BR.html` — Brazilian Portuguese privacy-policy draft
- `assets/style.css` — responsive styling (system fonts; no external font request)
- `.nojekyll` — static publishing marker

## Important: do not enable GitHub Pages until the review is complete

Both privacy pages are explicitly marked as drafts. Before publication, complete and verify all of the following:

1. Replace the developer-identity placeholder with the responsible individual's correct legal name and confirm the public contact channel.
2. Confirm the actual Supabase project hosting region and update the international-processing section.
3. Audit the released Android build and repository for all data collected or transmitted, including device diagnostics, crash reporting, analytics, advertising, maps, and third-party SDKs. Add every relevant provider and purpose to the policy.
4. Verify the exact cloud data fields transmitted, including activity summaries, splits, workout plans, route geometry, sync metadata, and any authentication data.
5. Verify that the GPS privacy-zone behaviour in the released build matches the description in both policy pages.
6. Define and test the account-deletion and data-rights request procedure, including Supabase Auth, related database records, local device copies, sync tombstones, and provider backups.
7. Confirm applicable retention periods, including any backup or operational-log retention. Do not promise a deletion deadline until it is known and operationally supported.
8. Confirm the legal basis for each processing purpose and the intended age range / rules for family use.
9. Review the notices for applicable Brazilian privacy requirements (including LGPD). Obtain qualified legal advice where appropriate.

## Garmin status

Garmin Connect integration is described as **planned and not currently available**. Keep this wording accurate unless/until Garmin approves the project and the integration is implemented.

## Publishing

The intended GitHub Pages source is the `main` branch, repository root. The app source repository is separate and must remain private.

A GitHub Pages site is publicly accessible. Do not publish application source code, credentials, API secrets, database passwords, private user data, or any other confidential material here.

Contact: runconnect@proton.me
