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

## Driver OT tab

The same `index.html` has a second tab, Driver OT (open it directly with `#driving`): the Rule
of 100 plan for the Driver OT sign-off. It tracks reps for 12 off-road drills (100 each, last 10
clean in a row), full mocks, the fix-now and assessment-day checklists, and pace against the
timeline to the 27 Feb 2027 report. It runs in its own shadow root so its light styles and the
fight record's dark styles stay apart. Reps save in the browser (localStorage); use Export log to
back them up. No names or client details are on it, because this repo is public.

## OT Driver Assessment Day Pack

`day-pack.html` is the assessment-day web app (linked as Day pack in the tab bar). It has the day run sheet,
a run sheet, record form and notes for each of the 8 sections, timers for the timed tests, scores that flag
against the cut-offs, a pre-drive summary that pulls the flags together, an on-road stage log with verbal and
physical intervention counts, and a print kit (client sheets, a blank pack, or the filled-in assessment).

- Road law uses an Estus WA Road Law and Road Craft Screen (15 questions, 8 intersection diagrams) written
  against WA rules as at November 2026. Check transport.wa.gov.au when rules change.
- Client sheets drawn by the app: Estus consent form, Trail Making A and B with samples, clock sheet, WA screen.
- Copyright tests (Bells, OT Drive Home Maze, Snellgrove Maze, ADSES, DriveSafe and DriveAware) are not in this
  public repo. Print them from the licensed copies in Drive; the app only records their scores.
- Entries save in the browser (localStorage) on that device only. Nothing about a client is in the repo.
  Use Export in Print kit to save a copy to the client file before starting a new assessment.
