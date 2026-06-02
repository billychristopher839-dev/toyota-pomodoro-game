# Toyota Pomodoro Drive

A gamified Pomodoro study timer. Every focused hour unlocks a real Toyota model
(1936 → 2024) and grows your sales, revenue, and global rank. Reach 50 hours to
become #1 worldwide. Defaults: 60 min Focus / 10 min Pit Stop / 40 min Long Break.


## Notes

- Progress (hours, unlocked cars, tasks, settings) saves automatically in your
  browser via `localStorage`. It's per-browser and per-device, not synced.
- Serving over HTTPS (which Pages does) is the best environment for the timer
  sound and saved progress.
- The timer is wall-clock based, so it stays accurate even if you minimize the
  tab or switch away during a session.
