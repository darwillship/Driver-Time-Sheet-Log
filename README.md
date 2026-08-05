# Driver Time Sheet Log — Version 0.2

Mobile-first GitHub Pages web application for a four-week driver time study.

## Main changes from Version 0.1

- One-tap activity timestamps
- Start and end current activity using the phone's current time
- Full activity timeline instead of only customer stops
- Live productivity dashboard
- Saved driver name and vehicle profile
- Manual correction option
- Overlap and missing-time validation
- Resume unfinished day
- Local device history
- CSV and JSON exports
- Print or save daily sheet as PDF
- Offline use after the first successful load

## Productive activities

- Driving
- Loading
- Unloading
- Fueling
- Warehouse work

Waiting, Break, Lunch, Vehicle issue, Other, and unlogged shift time are counted as nonproductive.

## Updating the GitHub Pages site

1. Open the existing GitHub repository.
2. Upload the five Version 0.2 files.
3. Allow GitHub to replace files with the same names.
4. Commit the changes.
5. Wait about one minute for GitHub Pages to redeploy.
6. Refresh the website. On phones, fully close and reopen the page if the old version remains cached.

## Test workflow

1. Start a shift.
2. Tap Driving and start it.
3. End the current activity.
4. Start Loading or Waiting.
5. Close the browser and verify Resume Active Day works.
6. End the day.
7. Review totals.
8. Print or save PDF.
9. Export CSV and JSON.
