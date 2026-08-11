# Driver Time Sheet Log — Version 1.1

GitHub Pages-compatible mobile PWA.

## Highlights
- Dynamic greeting
- Live shift progress ring
- Optional local weather
- Driver photo stored on device
- Automatic light/dark mode
- Recent-location shortcuts and destination suggestion
- Bottom navigation: Home, Timeline, Summary, Settings
- Animated activity feedback and haptics
- End-of-shift completion screen
- Local device history, CSV/JSON export, print/PDF, offline support

## Install
Upload all five files to the root of the existing GitHub repository and allow GitHub Pages to redeploy.


## Version 1.1.3

Built directly from the original Version 1.1 interface.

Changes:
- Required digital pre-trip inspection before Start Shift.
- Full checklist based on the existing paper form.
- Odometer, condition, comments, and driver acknowledgment.
- Mark All OK shortcut; defects require comments.
- Pre-trip saved with the completed daily record and included in JSON/CSV/report data.
- Removed all quick/recent location suggestion chips and suggested destinations.
- Location dropdowns remain, with the saved address shown after selection.
- After End Shift, the active dashboard/navigation are hidden and only Shift Complete + the final report are shown.
- Original Version 1.1 design and activity workflow otherwise remain unchanged.


## Version 1.1.4

- Pre-Trip Inspection is now a completely separate screen.
- Start Shift is hidden until the pre-trip is successfully completed.
- Complete Pre-Trip now validates the form, saves it, returns to the shift setup screen, and displays Pre-Trip Complete.
- Back buttons return to shift setup without starting the shift.
- The Version 1.1 interface and all previously approved fixes remain unchanged.


## Version 1.2.1 — Guided Driver Workflow

- Keeps the Version 1.1 visual design and the separate pre-trip screen.
- Driving now uses an Arrived button instead of a generic Finish Driving button.
- Arrival automatically carries the destination into the next step.
- Darwill McCook/Hillside prioritize Loading, Unloading, Waiting, then Driving.
- Vendors prioritize Pickup, Delivery, Waiting, then Driving.
- Post offices prioritize Delivery, Unloading, Waiting, then Driving.
- Added productive Pickup and Delivery activities.
- Finishing an activity shows the most likely next actions at the same location instead of returning to the full activity menu.
- Fuel Stop is available while driving. Done Fueling automatically resumes the same route.
- Lunch uses a 30-minute countdown. It does not falsify the record by auto-ending; the driver taps End Lunch when actually finished.
- Location and route context carry forward so drivers do not repeatedly select the same information.
