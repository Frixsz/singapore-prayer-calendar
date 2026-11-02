# Singapore Prayer Times Calendar (2026–2027)

Apple Calendar-compatible subscription calendar generated from the supplied Singapore prayer timetable PDFs.

## Contents

- `singapore-prayer-times-2026-2027.ics` — subscription calendar
- `data/prayer-times.json` — structured source data
- `data/prayer-times.csv` — audit-friendly source data
- `index.html` — simple GitHub Pages landing page

## Publish with GitHub Pages

1. Upload all files to the root of your GitHub repository.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select your default branch (usually `main`) and `/ (root)`, then save.
5. Your direct subscription URL will be:

   `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/singapore-prayer-times-2026-2027.ics`

Keep the filename and URL unchanged when updating future years so subscribers do not need to subscribe again.

## iPhone subscription

Open **Calendar → Calendars → Add Calendar → Add Subscription Calendar**, paste the direct `.ics` URL, and subscribe. Ensure **Event Alerts** is enabled for this calendar.

## Calendar behaviour

- Time zone: `Asia/Singapore`
- Event duration: 5 minutes
- Alerts: at prayer time for Subuh, Zohor, Asar, Maghrib and Isyak
- Syuruk is included without an alert
- Events are transparent, so they do not mark you as busy

## Validation

The dataset contains 730 consecutive dates from 1 January 2026 through 31 December 2027, with six entries per day (4,380 events). Times are ordered Subuh → Syuruk → Zohor → Asar → Maghrib → Isyak.

## Important

Please compare several dates against the original PDFs before publishing. Calendar clients control subscription refresh timing and may not apply embedded alerts consistently to subscribed calendars.
