# Pomodoro Timer
A clean, minimal Pomodoro timer with daily session history.
## How to Run
This is a **single HTML file** — no build step, no npm install needed.

# Option 1 — just open it
open index.html     # macOS
start index.html    # Windows

# Option 2 — serve locally (avoids any browser quirks)
npx serve .
# then visit http://localhost:3000

That's it. No dependencies to install.
## Features

- 25-min focus / 5-min break (both configurable)
- Start, pause, resume, reset controls
- Skip phase button
- Audible 3-note chime when phase ends
- Auto-transitions between focus and break
- Daily session history (persists on reload, resets at midnight)
- Keyboard shortcut: `Space` = play/pause, `R` = reset
## Keyboard Shortcuts
- `Space` — play / pause
- `R` — reset timer
- Works on mobile (360px) and desktop (1440px+)
