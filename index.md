# Skyris — Privacy Policy

**Effective date:** 16 November 2026
**Developer contact:** helloizzylogic@gmail.com

Skyris is a flight-progress tracker for smartwatches and phones. It is designed to work offline and to keep your data on your own devices. Skyris was previously called Windowseat; this policy covers both names.

## What the app collects and how it is used

- **Location (GPS).** Used only when you tap the GPS button, to compute your flight's progress and speed. Fixes are processed **on the device** and stored only in the app's local storage as part of the tracked flight. If you use Skyris on both a phone and a watch, the tracked flight (including its fixes) is shared **between your own paired devices** so both show the same flight. It is never sent to the developer.
- **Barometric pressure.** Read from the device's barometer to detect the flight phase (climb, cruise, descent, landed). Processed on the device only; never transmitted.
- **Camera and photos (phone app).** Used only when you scan a boarding pass, to read its barcode. The image is processed **on the device** and is not stored or sent. From the pass, the app keeps the flight number, route, date and seat; it does not keep the passenger name. A screenshot you choose from your photos is read the same way.
- **Flight number.** If you use flight-number lookup or live sync, the flight number and date are sent over HTTPS to Skyris's lookup service, which retrieves schedules, live status, terminals, gates and baggage belts from the AeroDataBox flight-data API. The request also carries a **random, anonymous per-install identifier** used solely for abuse prevention (rate limiting). This identifier is not linked to you, your location, or any account, and lookup responses may be briefly cached (about two minutes) to reduce upstream traffic. No other data accompanies these requests, and none of it is stored beyond the cache.
- **Flight logbook.** When a flight lands, the app saves a short record of it on the device: flight number, route, departure and arrival times, distance, how early or late it was, the aircraft model and the countries flown over. It never leaves your devices.

## Between your phone and your watch

Skyris on a phone and Skyris on a watch keep one flight in step using the operating system's own watch connection: Google's Wear OS Data Layer on Android, and Apple's WatchConnectivity on iPhone and Apple Watch. These carry the tracked flight between your own devices only. On Android, the Data Layer may relay through Google's servers when the phone and watch aren't connected directly; Skyris has no server of its own for this.

## Third-party components

The Android phone app reads barcodes with Google's ML Kit, which runs on the device. Google may collect limited performance and usage metrics about ML Kit itself, as described in Google's ML Kit documentation. These do not include your images, your flights or your location.

## What the app does not do

- No accounts, no sign-in.
- No advertising, and no analytics or tracking added by Skyris.
- No sale or sharing of personal data with third parties.
- Nothing leaves your devices except the flight-number lookup and the phone–watch sharing described above. Manual flight tracking works with no network use at all.

## Data retention and deletion

All data (the tracked flight, GPS fixes, pressure history and the flight logbook) lives in the app's local storage on your devices. Ending a flight deletes its GPS fixes and pressure history, on both devices if they're paired; the logbook keeps the summary described above. Uninstalling the app deletes everything on that device, including its logbook.

## Changes

Material changes to this policy will be reflected in an updated version at this URL with a new effective date.
