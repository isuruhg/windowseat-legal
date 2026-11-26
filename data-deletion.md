# Skyris — Data Deletion

Skyris stores your data (tracked flight, GPS fixes, pressure history, flight logbook,
settings) **only on your own devices**: your watch, and your phone if you use Skyris there.
Ending a flight deletes its GPS fixes and pressure history, on both devices if they're
paired; a short summary stays in each device's logbook. To delete everything, including the
logbook, uninstall the app from each device.

What leaves your devices is a lookup: a flight number and date, or, for the Android phone's
"in the air now" list, an airport code and a time window. Each lookup carries an
**anonymous, random per-install identifier** for rate limiting. For each identifier the
lookup service keeps only how many lookups it made in the current minute and day, and when
those periods began; nothing about you, and it isn't deleted automatically. Uninstalling the
app discards the identifier, so that record is never used again. (On Android phones,
Google's on-device barcode reader may send Google its own anonymous performance metrics;
these contain none of your data.)

For any data request, contact **helloizzylogic@gmail.com**.
