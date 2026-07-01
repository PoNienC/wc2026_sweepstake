# World Cup 2026 · P+P Office Sweepstake

A single-file, static live bracket for the office World Cup 2026 sweepstake —
one colleague per nation. No backend, no build step: the page fetches FIFA's
public match feed (api.fifa.com) client-side every 60 seconds and derives the
knockout tree, live/next-match highlights, penalty shootouts and eliminations
from it.

- **Who's still in** — slide-in leaderboard (live matches pinned top, earliest
  knocked out at the bottom)
- **Knocked out** — strip under the bracket, grouped by exit stage
- Light / dark mode toggle; kick-off times shown in the viewer's local timezone

Unofficial fan page — not affiliated with FIFA. Match data © FIFA.
Names are shown as first name + initial only.
