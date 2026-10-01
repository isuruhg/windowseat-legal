# Windowseat — Privacy Policy

**Effective date:** 1 October 2026
**Developer contact:** helloizzylogic@gmail.com

Windowseat is a flight-progress tracker for smartwatches. It is designed to work offline
and to keep your data on your device.

## What the app collects and how it is used

- **Location (GPS).** Used only when you tap the GPS button, to compute your flight's
  progress and speed. Fixes are processed **on the device**, stored only in the app's
  local storage as part of the tracked flight, and are **never transmitted anywhere**.
- **Barometric pressure.** Read from the watch's barometer to detect the flight phase
  (climb, cruise, descent, landed). Processed on the device only; never transmitted.
- **Flight number.** If you use flight-number lookup or live sync, the flight number and
  date are sent over HTTPS to Windowseat's lookup service, which retrieves schedules and
  live status from the AeroDataBox flight-data API. The request also carries a **random,
  anonymous per-install identifier** used solely for abuse prevention (rate limiting).
  This identifier is not linked to you, your location, or any account, and lookup
  responses may be briefly cached (about two minutes) to reduce upstream traffic.
  No other data accompanies these requests, and none of it is stored beyond the cache.

- **Flight logbook.** When a flight lands, the app saves a short record of it on the watch:
  flight number, route, departure and arrival times, distance, how early or late it was,
  the aircraft model and the countries flown over. It never leaves the watch.

## What the app does not do

- No accounts, no sign-in.
- No advertising, no analytics, no tracking SDKs.
- No sale or sharing of personal data with third parties.
- No data leaves the device except the flight-number lookup described above, which is
  optional — manual flight tracking works with no network use at all.

## Data retention and deletion

All data (the tracked flight, GPS fixes, pressure history, API key and the flight logbook)
lives in the app's local storage on the watch. Ending a flight deletes its GPS fixes and
pressure history; the logbook keeps the summary described above. Uninstalling the app
deletes everything, including the logbook.

## Changes

Material changes to this policy will be reflected in an updated version at this URL with
a new effective date.
