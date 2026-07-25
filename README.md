# NetForge

Offline multi-vendor network engineering study tool — one self-contained HTML file.

**NetForge** helps you learn what each command does across Cisco IOS/XE, Juniper Junos, Palo Alto PAN-OS, Linux Bash, Windows PowerShell, and VMware vSphere (esxcli + PowerCLI), plus Netmiko / GuestShell / PAN-OS API automation labs, CLI sandbox drills, and a daily/weekly study planner.

Deep-dive tracks included:

- **EIGRP on Cisco** — classic and named mode, feasibility condition, variance/unequal-cost, authentication, SIA troubleshooting, metric math
- **Palo Alto routing** — virtual routers, named static routes, metric vs admin-dist, **path monitoring** (the PAN-OS answer to IP SLA + track), `test routing fib-lookup`, PBF, ECMP
- **VMware virtual networking** — vSwitch/vDS, portgroups & VLAN tagging modes (EST/VST/VGT), NIC teaming vs physical EtherChannel, VMkernel interfaces, jumbo-frame proofs with `vmkping -d -s 8972`, and the switchport template for ESXi uplinks

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
| Encyclopedia | 240 annotated commands: purpose, tokens, sample output, pitfalls, equivalents |
| Vendor compare | Same networking task across six platforms (incl. forwarding-decision lookups and static-route failover) |
| CLI sandbox | Fake per-vendor terminal with canned output + “Explain last” — now with ESXi/PowerCLI |
| Automation labs | Netmiko + TextFSM EIGRP audit, EIGRP metric math, PAN-OS XML API, PowerCLI VLAN audit, jumbo-frame proofs, GuestShell, sockets |
| Drills | Flashcards, scenario quizzes (EIGRP / PAN-OS routing / VMware), incident playbooks |
| Planner | Daily 20–40 min loop + weekly focus rotation (Sunday = VMware networking) |
| Toolkit | Wireshark, GNS3/EVE-NG, CML, VM-Series labs, nested ESXi, iperf3, NAPALM, and more |

## Daily / weekly study (built into the app)

**Daily:** 10 flashcards → 5 command deep-dives → 1 sandbox scenario → 1 host-side (Linux/PowerShell) drill → journal one troubleshooting thought.

**Weekly:** Mon Cisco L2/L3 + EIGRP · Tue Junos commit · Wed Palo Alto routing & path monitoring · Thu Linux/PowerShell · Fri automation · Sat incident scenario · Sun VMware networking + weak-card review.

## Notes

- The sandbox does **not** SSH to real devices — it is a safe offline trainer.
- Python labs are meant to be copied onto your lab PC or GuestShell.
- Everything ships in a single file: HTML + CSS + JS + embedded study data.
