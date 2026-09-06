# Meridian

A minimal world clock — tell the time across zones at a glance.

- **Your local time** up top, with the day/date and UTC offset.
- **Add any city or IANA time zone** (typeahead over every zone the browser knows), **remove** with ×.
- **Scrub the slider** to pin a reference hour: every zone updates to show what time it is everywhere when *your* clock reads that — then **Now** snaps back to live.
- **Day-difference badges** ("next day" / "prev day") so a late night at home reading tomorrow abroad is obvious.
- Handles half-hour zones (e.g. UTC+5:30) and DST correctly, via the browser's `Intl` APIs.

Static, offline-friendly, no accounts, no tracking. Your zone list is saved in this browser's local storage. HUD look; single-file `index.html`.

Live: https://offport.github.io/meridian/
