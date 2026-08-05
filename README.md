# Driver Time Sheet Log — Version 1.0

A mobile-first Progressive Web App for recording a driver's workday.

## Main workflow

1. Select driver and vehicle.
2. Start the shift. No activity starts automatically.
3. Tap **Start Activity** and choose the actual task.
4. Finish the activity or finish it and immediately start another.
5. End the shift, review the report, print/save PDF, or export CSV/JSON.

## Included

- Modern app-style mobile interface
- Driving, loading, unloading, waiting, fueling, lunch, vehicle issue, other
- Drop-and-hook tools for the semi-truck
- Vendor and postal location list with addresses
- Local device backup and resume
- Completed shift history
- CSV and JSON exports
- Printable daily time sheet
- Offline support after first load

## GitHub Pages

Upload all files to the repository root. GitHub Pages should deploy from the `main` branch and `/ (root)` folder.


## Version 1.0.1 fix

- Fixed page jumping to the top while scrolling.
- Fixed notes fields losing focus while typing.
- Fixed dropdown menus closing or resetting while scrolling.
- Live timers now update without rebuilding the active screen every second.
