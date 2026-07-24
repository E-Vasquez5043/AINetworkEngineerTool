# NetForge

Offline multi-vendor network engineering study tool — one self-contained HTML file.

**NetForge** helps you learn what each command does across Cisco IOS/XE, Juniper Junos, Palo Alto PAN-OS, Linux Bash, and Windows PowerShell, plus Netmiko / GuestShell automation labs, CLI sandbox drills, and a daily/weekly study planner.

## Open offline

### Desktop
1. Download or clone this repo.
2. Open [`netforge.html`](netforge.html) in Chrome, Firefox, Edge, or Safari (double-click, or File → Open).
3. No server and no internet required after the file is on disk.

### iPhone / iPad
1. Save `netforge.html` to the **Files** app (AirDrop, iCloud Drive, or download).
2. In **Files**, tap the file → **Share** → **Open in Safari** (or long-press → Open With → Safari).
3. Optional: in Safari, tap Share → **Add to Home Screen** for an app-like icon.
4. Progress (bookmarks, streaks, quiz marks, journal) stays in that browser’s local storage.

## What’s inside

| Module | Purpose |
|---|---|
| Encyclopedia | Annotated commands: purpose, tokens, sample output, pitfalls, equivalents |
| Vendor compare | Same networking task across five CLIs |
| CLI sandbox | Fake per-vendor terminal with canned output + “Explain last” |
| Automation labs | Netmiko, GuestShell, Lua NSE mindset, C/Rust/Java socket notes |
| Drills | Flashcards, scenario quizzes, incident playbooks |
| Planner | Daily 20–40 min loop + weekly focus rotation |
| Toolkit | Wireshark, GNS3/EVE-NG, iperf3, NAPALM, runbooks, and more |

## Daily / weekly study (built into the app)

**Daily:** 10 flashcards → 5 command deep-dives → 1 sandbox scenario → 1 host-side (Linux/PowerShell) drill → journal one troubleshooting thought.

**Weekly:** Mon Cisco L2/L3 · Tue Junos commit · Wed Palo Alto zones · Thu Linux/PowerShell · Fri automation · Sat incident scenario · Sun weak-card review + toolkit.

## Notes

- The sandbox does **not** SSH to real devices — it is a safe offline trainer.
- Python labs are meant to be copied onto your lab PC or GuestShell.
- Everything ships in a single file: HTML + CSS + JS + embedded study data.
