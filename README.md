# Fight record

A personal decision record styled as a fighter's record: past bets as wins and losses,
scheduled fights at two a year, a fight camp with next actions, and a five-voice corner
(Thinking in Bets, the Stoics, Duckworth, Goggins on taking souls, Jocko).

`index.html` at the top of the repo is the whole page, so it loads at the site's home address. No build step.

## Where the data lives

- Opened from this repo or any normal web host, the record is saved in the browser
  (localStorage). It stays on that browser and device. Use Export record and Import record
  at the bottom of the page to back it up or move it.
- Opened as a Claude artifact, it uses the artifact's own store.

`sample-record.json` is Liam's own record, kept here on purpose as the starting data. On a
first visit the page loads it into the browser, and "Load sample record" at the bottom of
the page reloads it. This repo is public, so that file is public too.

Other export files (`fight-record*.json`) are ignored by git so one is not committed by
accident.

## Driver OT sign-off tracker

`driving/index.html` is a separate page at `/driving/`: the Rule of 100 plan for the Driver OT
sign-off. It tracks reps for 12 off-road drills (100 each, last 10 clean in a row), full mocks,
the fix-now and assessment-day checklists, and pace against the timeline to the 27 Feb 2027
report. Reps save in the browser (localStorage); use Export log to back them up.
No names or client details are on the page, because this repo is public.
