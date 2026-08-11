# Driver Time Sheet Log — Version 1.2

GitHub Pages-compatible mobile Progressive Web App.

## Version 1.2 workflow
- Start Shift starts only the shift clock.
- Start a location visit by selecting the location and the work being done there.
- Finish Visit stamps departure time.
- Start Travel records driving between locations.
- Arrive ends the travel block and immediately opens the next-location visit form.
- Timeline entries can be edited before or after shift completion.
- Add Missed Entry can insert forgotten visits or travel blocks.
- Validation blocks overlapping times and invalid time ranges.

All records remain on the device in localStorage. CSV/JSON exports and printable daily reports remain available.

## Deploy
Upload these files to the root of the GitHub Pages repository:
- index.html
- manifest.webmanifest
- sw.js
- icon.svg
- README.md

After deployment, fully close and reopen the installed web app so the v1.2 service worker replaces the older cache.
