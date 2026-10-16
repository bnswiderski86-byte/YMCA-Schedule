# Longview YMCA Schedule

A one-page weekly calendar that combines the group exercise, main pool and activity pool schedules (Aug 31 to Dec 31, 2026).

## Files

- `index.html` is the whole app (page, styles and schedule data).
- `manifest.webmanifest` tells your phone this is an installable app.
- `sw.js` lets the app open without internet.
- `icons/` holds the app icons.
- `.nojekyll` tells GitHub to serve the files as they are.

## Changing the schedule later

1. Open `index.html` and find the schedule data (lines that look like `[0,'g','class','Zumba','17:30',null,'Jennifer · Back Gym']`).
2. Edit or add a line. Day 0 is Monday and 6 is Sunday. Times use 24 hour format (17:30 is 5:30pm).
3. Open `sw.js` and change the number in `var VERSION = 'v2';` to the next one (`'v3'`) so installed copies update.
4. Commit the changes on GitHub.
