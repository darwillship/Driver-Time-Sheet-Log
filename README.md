# Driver Time Sheet Log — Version 0.1

A simple mobile-first web application for a four-week driver time study.

## Included files

- `index.html` — complete application
- `manifest.webmanifest` — installable mobile web app settings
- `sw.js` — offline cache/service worker
- `icon.svg` — app icon
- `README.md` — setup and testing instructions

## Version 0.1 features

- Start a driver shift with driver, date, start time, and vehicle number
- Add, edit, and delete stops or activities
- Automatic stop numbering and time calculations
- Activity categories for driving, loading, unloading, waiting, fueling, breaks, lunch, warehouse work, vehicle issues, and other activity
- Overlap, duplicate, missing-time, and invalid-time validation
- Productive and nonproductive time totals
- Productivity percentage
- End-of-day time sheet
- Print or save as PDF using the phone or browser print menu
- Local device history
- Resume an unfinished day after closing the browser
- CSV and JSON export
- Offline support after the first successful load
- Remembers the last driver name and vehicle number on the same device

## Important Version 0.1 limits

- Data is stored only in the browser on the device being used.
- Clearing browser data, using private browsing, or changing devices can remove or hide saved records.
- Export CSV or JSON regularly during the four-week test.
- No cloud database, login, automatic email, GPS, or supervisor dashboard is included yet.

## Upload to GitHub Pages

1. Sign in to GitHub.
2. Create a new public repository, for example `driver-timesheet-log`.
3. Upload all five files from this folder to the top level of the repository. Do not upload only the ZIP.
4. Open the repository **Settings**.
5. Open **Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**.
7. Select the `main` branch and `/ (root)` folder.
8. Click **Save**.
9. Wait for GitHub to display the website address.
10. Open that address on a phone and complete the test checklist below.

## Phone test checklist

1. Open the GitHub Pages address in Safari or Chrome.
2. Enter a driver name, date, start time, and vehicle number.
3. Tap **Start Day**.
4. Add at least three activities, including one productive and one nonproductive activity.
5. Close the browser tab.
6. Reopen the website and confirm **Resume Active Day** appears.
7. Resume and add another activity.
8. Tap **End Day**, enter the shift end time, and save.
9. Confirm the final time sheet shows all stops and totals.
10. Tap **Print / Save PDF** and use the phone print menu to save or share a PDF.
11. Export the day as CSV and JSON.
12. Reopen the site and confirm the completed record remains in **Saved History**.
13. Turn on airplane mode after the site has loaded once, reopen it, and confirm it still opens.

## Installing on a phone home screen

### iPhone / Safari

1. Open the GitHub Pages website in Safari.
2. Tap the Share button.
3. Tap **Add to Home Screen**.
4. Open the new Driver Log icon.

### Android / Chrome

1. Open the GitHub Pages website in Chrome.
2. Open the browser menu.
3. Tap **Add to Home screen** or **Install app**.

## Productivity rules used in Version 0.1

Productive:

- Driving
- Loading
- Unloading
- Fueling
- Warehouse work

Nonproductive:

- Waiting
- Break
- Lunch
- Vehicle issue
- Other
- Any unlogged time between the shift start and shift end

Unlogged time is treated as nonproductive to avoid overstating productivity.
