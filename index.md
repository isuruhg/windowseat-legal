# Skyris — Privacy Policy

**Effective date:** 26 November 2026
**Developer contact:** helloizzylogic@gmail.com

Skyris is a flight-progress tracker for smartwatches and phones. It is designed to work offline and to keep your data on your own devices. Skyris was previously called Windowseat; this policy covers both names.

## What the app collects and how it is used

- **Location (GPS).** Used only when you tap the GPS button, to compute your flight's progress and speed. Fixes are processed **on the device** and stored only in the app's local storage as part of the tracked flight. If you use Skyris on both a phone and a watch, the tracked flight (including its fixes) is shared **between your own paired devices** so both show the same flight. It is never sent to the developer.
- **Barometric pressure.** Read from the device's barometer to detect the flight phase (climb, cruise, descent, landed). Processed on the device only; never transmitted.
- **Camera and photos (phone app).** Used only when you scan a boarding pass, to read its barcode. The image is processed **on the device** and is not stored or sent. From the pass, the app keeps the flight number, route, date and seat; it does not keep the passenger name. A screenshot you choose from your photos is read the same way.
- **Flight lookups.** If you look up a flight number or use live sync, the flight number and date are sent over HTTPS to Skyris's lookup service, which gets schedules, live status, terminals, gates and baggage belts from the AeroDataBox flight-data API.
- **Flights in the air now (Android phone).** When you first open it, the phone app offers to show a few flights that are in the air right now. If you open that list, it asks the lookup service for one busy airport's recent departures, sending the airport's code and a time window. The airport is chosen from your phone's time-zone setting, not from your location.
- **Anonymous install ID.** Every request to the lookup service also carries a **random, anonymous identifier** that the app creates on first use, used only to limit how many lookups one install can make. It is not linked to you, your device, your location or any account. No other data goes with lookup requests. For each identifier the service keeps only a rate-limit record: how many lookups it made in the current minute and day, and when those periods began. The record holds nothing else and is not deleted automatically. If you enter your own AeroDataBox key in the watch app's settings, lookups go straight to AeroDataBox under your key instead, without the identifier.
- **Caching.** The lookup service caches answers so that people asking for the same thing share one request to AeroDataBox: a flight for about two minutes, an airport's departures for about 30 minutes. Cached answers hold flight data only, never your identifier.
- **Flight logbook.** When a flight lands, the app saves a short record of it on the device: flight number, route, departure and arrival times, distance, how early or late it was, the aircraft model and the countries flown over. It never leaves your devices.

## Between your phone and your watch

Skyris on a phone and Skyris on a watch keep one flight in step using the operating system's own watch connection: Google's Wear OS Data Layer on Android, and Apple's WatchConnectivity on iPhone and Apple Watch. These carry the tracked flight between your own devices only. On Android, the Data Layer may relay through Google's servers when the phone and watch aren't connected directly; Skyris has no server of its own for this.

## Third-party components

The Android phone app reads barcodes with Google's ML Kit, which runs on the device. Google may collect limited performance and usage metrics about ML Kit itself, as described in Google's ML Kit documentation. These do not include your images, your flights or your location.

## What the app does not do

- No accounts, no sign-in.
- No advertising, and no analytics or tracking added by Skyris.
- No sale or sharing of personal data with third parties.
- Nothing leaves your devices except the lookups and the phone–watch sharing described above. Manual flight tracking works with no network use at all.

## Data retention and deletion

All data (the tracked flight, GPS fixes, pressure history and the flight logbook) lives in the app's local storage on your devices. Ending a flight deletes its GPS fixes and pressure history, on both devices if they're paired; the logbook keeps the summary described above. Uninstalling the app deletes everything on that device, including its logbook and its install ID. The lookup service keeps only the rate-limit record described above, which can't be tied to you.

## Changes

Material changes to this policy will be reflected in an updated version at this URL with a new effective date.
