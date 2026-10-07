Driver Time Sheet v1.7.0 (2026-10-07)
- Pre-trip inspections are now stored centrally in Supabase (driver_pretrips) the moment the driver taps
  Complete Pre-Trip. Records are insert-only: they cannot be edited or deleted from the apps (DOT retention).
- Start Shift / End Shift create and close a shift record (driver_shifts) with totals; every finished activity
  is saved to driver_activities. The dispatch dashboard shows "On since …" and a Time Sheets view.
- Everything is still saved on the phone first. An offline outbox sends records in order and retries
  automatically (on app open, when signal returns, and every minute). Settings → Cloud Sync shows status.
- Live activity now reaches the dispatch dashboard (driver_live_status); the "Dashboard sync failed"
  pop-up was removed (quiet retry instead).
- Drivers are matched by their Supabase driver id (name only as a fallback for shifts started before v1.7.0).
- Default date uses the phone's local date (no more "tomorrow" after 7 PM).
- My Routes uses the dispatch work date (falls back to scheduled time), the same rule as the dashboard.
- Driver list is cached for offline use; the last selected driver is restored.
- Fix: End Shift is always reachable (it was hidden once no route was active, e.g. after the last route).
- Service worker cache bumped to driver-timesheet-v1.7.0 so installed phones pick up the update.

Driver Time Sheet v1.6.0
- My Routes is now the first/primary section on Home after a shift starts.
- Separate Routes bottom-navigation tab removed.
- Route Start/Complete controls remain connected to Dispatch.
- Activity timer and manual driver activities remain directly below routes.
- Added a route refresh button on Home.
