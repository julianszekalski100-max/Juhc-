# Notes for Claude

- The user is in Poland. When reporting times to them, use 24-hour format in Polish time
  (Europe/Warsaw, CET/CEST). The trader-* tools print New York time; convert it, e.g.
  "16:25 (10:25 ET)". The offset is usually 6 hours, but 5 hours for a few weeks in
  March and late October/early November, when the US and Europe switch clocks on different dates.
  Compute it with `TZ=Europe/Warsaw date` rather than assuming.
