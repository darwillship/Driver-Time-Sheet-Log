# Driver Time Sheet Log — Version 0.3

Mobile-first GitHub Pages application for a four-week driver time study.

## Version 0.3 additions

- Vehicle dropdown for the Darwill fleet
- Vendor/location dropdown with saved addresses
- Other-location option
- Optional **Stamp Current Address** button using the phone location
- Only the readable address and timestamp are shown/saved; latitude and longitude are not displayed
- Address is included in the timeline, printed time sheet, CSV, and JSON exports
- Existing Version 0.2 device history remains available

## Upload

Upload all five files to the root of the existing GitHub repository and commit the changes. GitHub Pages will redeploy automatically. Refresh the phone page after deployment.

## Location permission

The browser asks for location permission only when the driver taps **Stamp Current Address**. A saved vendor can also be selected without using phone location. Address results can be corrected manually.
