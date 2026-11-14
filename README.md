# Sick Log

Installable web app (Android and iPhone) to keep a private diary of your sick days: each sickness with first and last sick day, type, symptoms, severity, days off work, doctor visit, medication and notes, plus statistics over the years.

**Privacy:** everything stays in the browser storage of your own device. There is no server and no tracking. The only online request is the app checking its own address for a newer version.

## Features (1.00)
- **Log:** "I'm sick" opens a sickness from today, "I'm well again" closes it; earlier sicknesses can be added with their dates.
- **History:** all episodes by year, with search and type filter.
- **Statistics:** episodes and sick days per year, per month (seasonality), by type, symptom and severity, days off work, doctor visits, healthy stretches.
- **Calendar:** one year at a glance, coloured by severity.
- **Settings:** your own lists of types and symptoms, colour themes, light / dark mode, backup file (replace or merge), CSV export, update notice.

## Install on your phone
Open https://dusiaclaw.github.io/SickLog/ in Chrome (Android) and use **Settings → Install app**, or the ⋮ menu → *Install app*.

## Updating
Edit `APP_VERSION` and `CHANGELOG` in `index.html`, bump the cache name in `sw.js`, then run `python3 make-version.py` (writes `version.json`, which tells installed apps that an update exists).

## License
GPL-3.0, see [LICENSE](LICENSE). App shell derived from Receipt Archive (GPL-3.0). Includes [Tabler Icons](https://github.com/tabler/tabler-icons) (MIT).
