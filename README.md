# NEXUS//OPS — NetForge Edition

Offline network engineering operations and study console — one self-contained HTML file.

The app combines NEXUS//OPS recurring checklists, CCNP tools, change notes, and offline data controls with NetForge's multi-vendor command learning tools.

## Open offline

### Desktop
1. Download or clone this repo.
2. Open [`index.html`](index.html) in Chrome, Firefox, Edge, or Safari (double-click, or File → Open).
3. No server and no internet required after the file is on disk.

### iPhone / iPad
1. Save `index.html` to the **Files** app (AirDrop, iCloud Drive, or download).
2. In **Files**, tap the file → **Share** → **Open in Safari** (or long-press → Open With → Safari).
3. Optional: in Safari, tap Share → **Add to Home Screen** for an app-like icon.
4. Progress (bookmarks, streaks, quiz marks, journal) stays in that browser’s local storage.

## What’s inside

| Module | Purpose |
|---|---|
| Operations queue | Recurring operations checklists with completion evidence and safety classifications |
| CCNP tools | ENCOR blueprint, Study Hub, flashcards, labs, and timed 80-question practice exams |
| Command Forge | 116 annotated Cisco, Juniper, Palo Alto, Linux, and PowerShell commands |
| Vendor compare | Same networking task across five CLIs |
| CLI sandbox | Safe fake per-vendor terminal with canned realistic output |
| Automation labs | Netmiko, GuestShell, Lua NSE mindset, C/Rust/Java socket notes |
| Change records | Offline change notes with locally stored screenshot evidence |
| Console controls | Dark/light theme, data import/export, localStorage and IndexedDB persistence |

## Daily / weekly study (built into the app)

**Daily:** Work the Operations Queue, then use Command Forge for five command deep-dives and one sandbox scenario.

**Weekly:** Mon Cisco L2/L3 · Tue Junos commit · Wed Palo Alto zones · Thu Linux/PowerShell · Fri automation · Sat incident scenario · Sun weak-card review + toolkit.

## Notes

- The Command Forge sandbox does **not** SSH to real devices — it is a safe offline trainer.
- Python labs are meant to be copied onto your lab PC or GuestShell.
- Everything ships in one file: HTML + CSS + JS + embedded task, command, study, and exam data.
- The previous standalone [`netforge.html`](netforge.html) remains available as a reference.
