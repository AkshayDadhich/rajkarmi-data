# RajKarmi data

Public data files read by the RajKarmi app (Rajasthan government employees' app):

- `manifest.json` — which data is published, and its version
- `holidays_<year>.json` — the holiday list for a year (Rajasthan Government, High Court, stock market)

The app checks `manifest.json` and downloads a year's list again whenever `holidays.version` goes up.
Each year file is the complete list for that year; bump the version after changing any file.

Holiday dates are taken from the calendars published by the respective authorities. Please confirm
against the official notification before relying on them.
