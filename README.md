# Sweden–Finland Overlanding — traveller roadbook

**Live:** https://emag165.github.io/sweden-finland-roadbook/

29-day self-driven 4x4 trip, 26 Sep – 26 Oct 2026. Four travellers, two vehicles.
Vehicles collected at the Stockholm hotel on 27 Sep (moved from Arlanda on 21 Sep);
the 25 Oct return point is to confirm with the operator.

Six tabs: **Legs** (day by day — a driving card for every move, a base card the day after arrival at each multi-night base with the things-to-do shortlist and its booking state) ·
**Distance** · **Lodging** · **Things to do** · **Weather** · **Contingency**.
Day/night toggle at the right of the tab bar.

## Contents

- `index.html` — the whole roadbook in one self-contained file, no external assets or scripts
  (v1.22, 24 Sep 2026 midday: Bonnstan, Skellefteå's church town, an optional half hour on the 30 Sep drive, leaving Granö 09:30; `analysis/Plan_30Sep_1Oct_3Oct_v1.2.md`; v1.21, 24 Sep 2026 morning: 30 Sep back on the E4 with an hour at Gammelstad church town, 351 km, no alternative — Storforsen is ~30 min on the 1 Oct line; `analysis/Plan_30Sep_1Oct_3Oct_v1.1.md`; v1.20, 24 Sep: 30 Sep by the inland roads with an hour at Storforsen (Gammelstad the alternative), 416 km; 1 Oct the saved S-06 line km 452 → 228 from Arvidsjaur, 377 km with ~260 km of gravel; 3 Oct a hike day from the ICEHOTEL, Gohpasvággi or Trollsjön decided at breakfast; `analysis/Plan_30Sep_1Oct_3Oct_v1.0.md`; v1.19, 23 Sep night: a live FORECAST line on every card and a forecast table on the Weather tab, one Open-Meteo request kept on the device, `analysis/Weather_Live_Forecast_v1.0.md`; v1.18, 23 Sep late night: the 1 Oct loop lengthened — the S-06 line from the gate to Vidsel and Storforsen, two hours at the rapids, road to S-16 km 750, the S-16 line to km 790, BD 682 home; 220 km, ~155 km of it gravel, 7.4 h, chosen by Adam from seven surface-sampled shapes; `analysis/Base_Loop_1Oct_v1.1.md`; v1.17: 30 Sep is a road day by the E4 with an hour at Gammelstad church town, 351 km; the S-06 gravel became the 1 Oct loop from Treehotel; `analysis/Base_Loop_1Oct_v1.0.md`; v1.16, 23 Sep night: Codex's map, distance and travel-time audit applied — cut clocks derived from the cut, one surface vocabulary, K1's Lentiira connector on the map, the H6/K1 bars from the manifest, Koli → Rantasalmi 220 km on the drawn corridor, road hours labelled driving time, `analysis/Map_Audit_Disposition_v1.0.md`; v1.15, 23 Sep evening: Codex's audit of v1.14 applied — H6's connector gravel and the Kivikiekintie conditions clause restored, the Ruka card's activities re-paired with the operators' pages (HoNS Thursday 40 € by 12 Oct, Friday rafting, pedestrian gondola 15 €, Kiutaköngäs 2 km), the Bear Centre line on the current site, the north loop on its own samples, the map note "approximate", the phone-width and anchor-offset fixes; `analysis/Card_Rebuild_Review_v1.1.md`; v1.14: Kuusamo — the Oulanka eagle hides, the border gravel loop from the lodge, Kuusamo town — on the Ruka card; v1.13: every card rebuilt to one grammar — SLEEP · ROUTE · DRIVE bar · compact trail box · read cells — eight base cards for the free days, the Things-to-do tab from the 23 Sep operator-page research with its book-by table, `analysis/Card_Rebuild_Review_v1.0.md`; v1.12: check-in / check-out / nights line on every accommodation card; driving hours by recorded road surface — Trafikverket NVDB and Digiroad, `analysis/Surface_Verification_v1.2.md` — and the map drawn by surface: the road plan solid on tarmac and dashed on gravel, the alternatives amber where gravel and cyan-dotted where tarmac, `analysis/Map_Verification_v1.5.md` and `_v1.6.md`)
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

- **Sealed legs** carry the Google Maps road distance and a plain drive bar.
- **Trail alternatives** carry a dashed bar and an hours figure computed
  at **35 km/h on gravel, 65 on tarmac, plus an hour of stops**, from first light. That
  speed is a planning assumption, not a measurement — the GPX files carry no surface data.
  Trail kilometres are summed point to point from the 2026 `Sweden TET.gpx` and
  `Finland TET.gpx`. **Road kilometres — sealed legs and every connector — are Google Maps
  driving distances (fastest route, looked up 10–11 Sep 2026)**; sealed hours are km ÷ 65.
  Parts of the Finnish file are drawn coarsely (chords of 3–10 km), so those trail kilometres
  are floors and the surface there may be an ordinary road.

Every long day carries a **cut rule** — the point in the day at which you leave the trail
for the road — and the full bar on a drive strip is 400 km, the six-hour ceiling on sealed
road at 65 km/h.

## Route shape

- **28 Sep – 2 Oct, Sweden:** the **paved route is the plan** — E4 to Docksta, E4 · 353 · E12 to
  Granö, the inland roads by Storforsen to Treehotel, 97 · E10 to the ICEHOTEL on 2 Oct (116 · 191 · 416 · 279 km;
  1 Oct is a second night at Treehotel, added 21 Sep) —
  and the eastern TET corridor is the **alternative, chosen at breakfast**: S-07 from the Sundsvall
  hotel door, S-07 + S-06 to Granö, S-16 to Hakkas, **882 km of trail** in three options plus the
  **1 Oct gravel day on the saved S-06 line from Arvidsjaur** (decided 24 Sep: 30 Sep stays on the road with an
  hour at Gammelstad; Storforsen is ~30 min on the line; the line is 225 km, ~260 km of gravel with the road out).
- **4 – 18 Oct, Finland:** the same rule — paved plan on every card, a TET line beside it as
  an **alternative, chosen on the departure morning**. Six of them,
  up to **1,325 km** of optional gravel. The stay days at Levi, Ivalo and Rovaniemi carry
  gravel loops on the sections the transfers do not use.
- **17 Oct:** a transit night at Lentiira, added so that Ruka → Koli becomes two gravel
  days (or two gravel options) instead of one 439-km road day.
- **25 Oct:** the ferry docks at 06:10, the vehicles go back to the operator (return point to
  confirm — the pickup moved to the Stockholm hotel on 21 Sep), and the party flies Stockholm →
  Frankfurt the same evening.

## Notes

- **All 30 nights are booked.** The 1 Oct Treehotel night was added 21 Sep; Treehotel updates
  the booking 22 Sep and the confirmation is still to be filed. The one travel booking still
  open is the ARN → FRA flight on 25 Oct. Road km are Google Maps throughout (27 Sep re-routed
  from the Stockholm hotel on 21 Sep, 375 km).
- Activity opening hours were checked against operators' own pages and booking systems
  on 7 Sep 2026, and each item is marked confirmed / previous-season / no-source / closed.
  Seasons slip — re-check the week before travelling.
- Weather figures are station records (SMHI and FMI, mostly 1996–2025) for each base's own
  dates, with ERA5 wind — **not a forecast**. Method and every table:
  `analysis/Weather_Climate_Normals_v3.1.md`.
- The map draws the trail days and alternatives from the GPX geometry and every road along
  the OpenStreetMap network (OSRM routing), simplified to about 2 km. **Tap or hover any
  leg** for its distance, hours and arrival (the alternative's figures on the sealed legs
  that have one); tap again, tap empty map or press Escape to clear. Where an alternative's
  road link runs on the same road as the sealed leg, the tap goes to the sealed leg. On a phone
  (under 640 px) every table shows as stacked cards instead of scrolling sideways. The coastline is
  simplified for web delivery; the full-detail version lives in the
  project folder at `design/Traveller_Roadbook_v1.12.html`, which also retains all booking
  references for the four travellers.
- Sources behind the activity claims: `analysis/Base_Activities_Verified_v1.1.md`.
  Trail working: `analysis/TET_Eastern_Corridor_v1.6.md` (Sweden) and
  `analysis/TET_Finland_Legs_v2.2.md` (Finland); the road-distance correction of 11 Sep and
  the map verification: `analysis/Map_Verification_v1.6.md`. Navigation files (GPX per day for
  Gaia, KML for Google My Maps) are in `Navigation/`.

Built 7 Sep 2026 · last updated 21 Sep 2026 (roadbook v1.4: 26 Sep night moved to Ett Hem, Stockholm; pickup at the hotel; ICEHOTEL 2–4 Oct; Treehotel 1 Oct added; Navigation files v6). Previous: 17 Sep 2026 (Sweden paved-first; Codex review corrections; Navigation files v5).
