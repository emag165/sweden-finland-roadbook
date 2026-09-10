# Sweden–Finland Overlanding — traveller roadbook

**Live:** https://emag165.github.io/sweden-finland-roadbook/

29-day self-driven 4x4 trip, 26 Sep – 26 Oct 2026. Four travellers, two vehicles,
Stockholm Arlanda round trip.

Six tabs: **Legs** (day by day, each base carrying a "while here" shortlist) ·
**Distance** · **Lodging** · **Things to do** · **Weather** · **Contingency**.
Day/night toggle at the right of the tab bar.

## Contents

- `index.html` — the whole roadbook in one self-contained file, no external assets or scripts
- `robots.txt` and a `noindex` meta tag — ask search engines not to index the page
- `.nojekyll` — serve files verbatim

## What is deliberately not on this page

The page is public: anyone with the URL can read it. So it does **not** carry —

- booking **PINs**
- **airline references** (Lufthansa, SAS) or e-ticket numbers
- the ferry **boarding code**
- the traveller name list

Hotel booking numbers are present, but a booking number without its PIN cannot be
used to view or change a reservation. Adam holds the PINs and airline references
separately.

`noindex` keeps it out of search results; it is not access control. Share the link
directly rather than posting it anywhere public.

## How to read the driving figures

Two kinds of day, marked differently:

- **Sealed legs** carry a measured road distance and a plain drive bar.
- **Trail days and trail alternatives** carry a dashed bar and an hours figure computed
  at **35 km/h on gravel, 65 on tarmac, plus an hour of stops**, from first light. That
  speed is a planning assumption, not a measurement — the GPX files carry no surface data.
  Trail kilometres are summed point to point from the 2026 `Sweden TET.gpx` and
  `Finland TET.gpx`; road connectors are straight line × 1.25 and are **floors**. Parts of
  the Finnish file are drawn coarsely (chords of 3–10 km), so those kilometres are floors
  too and the surface there may be an ordinary road.

Every long day carries a **cut rule** — the point in the day at which you leave the trail
for the road — and the full bar on a drive strip is 400 km, the six-hour ceiling on sealed
road at 65 km/h.

## Route shape

- **28 Sep – 1 Oct, Sweden:** four trail days on the eastern TET corridor — S-07 from the
  Sundsvall hotel door, S-06 driven against its numbering, S-16 to Hakkas — via Ullånger,
  Granö Beckasin and Treehotel to the ICEHOTEL. **882 km of trail.**
- **4 – 18 Oct, Finland:** the **paved route is the plan on every card**; a TET line is
  offered beside it as an **alternative, chosen on the departure morning**. Six of them,
  up to **1,328 km** of optional gravel. The stay days at Levi, Ivalo and Rovaniemi carry
  gravel loops on the sections the transfers do not use.
- **17 Oct:** a transit night at Lentiira, added so that Ruka → Koli becomes two gravel
  days instead of one 429-km road day.
- **25 Oct:** the ferry docks at 06:10, the vehicles go back to the operator at Arlanda,
  and the party flies Stockholm → Frankfurt the same evening.

## Notes

- **All 30 nights are booked.** The one travel booking still open is the ARN → FRA flight
  on 25 Oct.
- Activity opening hours were checked against operators' own pages and booking systems
  on 7 Sep 2026, and each item is marked confirmed / previous-season / no-source / closed.
  Seasons slip — re-check the week before travelling.
- Weather figures are station records (SMHI and FMI, mostly 1996–2025) for each base's own
  dates, with ERA5 wind — **not a forecast**. Method and every table:
  `analysis/Weather_Climate_Normals_v3.1.md`.
- The map coastline is simplified for web delivery; the full-detail version lives in the
  project folder at `design/Traveller_Roadbook_v1.2.html`, which also retains all booking
  references for the four travellers.
- Sources behind the activity claims: `analysis/Base_Activities_Verified_v1.1.md`.
  Trail working: `analysis/TET_Eastern_Corridor_v1.6.md` (Sweden) and
  `analysis/TET_Finland_Legs_v2.2.md` (Finland).

Built 7 Sep 2026 · last updated 10 Sep 2026.
