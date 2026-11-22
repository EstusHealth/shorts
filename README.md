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

No record data is kept in this repo. Export files are ignored by git so one is not
committed by accident.
