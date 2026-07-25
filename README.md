# NetForge

Offline multi-vendor network engineering study tool — one self-contained HTML file.

**NetForge** helps you learn what each command does across Cisco IOS/XE, Juniper Junos, Palo Alto PAN-OS, Linux Bash, Windows PowerShell, and VMware vSphere (esxcli + PowerCLI), plus Netmiko / GuestShell / PAN-OS API automation labs, CLI sandbox drills, and a daily/weekly study planner.

Coverage spans the full CCNP/CCIE ENCOR (350-401) blueprint plus multi-vendor operations.

**Routing & switching**

- **EIGRP** — classic and named mode, feasibility condition, variance/unequal-cost, authentication, SIA troubleshooting, metric math
- **STP / RSTP / MSTP + EtherChannel** — port roles and states, root election, PortFast/BPDU Guard/Root Guard/Loop Guard, MST regions, the PAgP vs LACP vs static-`on` negotiation truth table, VTP, 802.1Q trunking and DTP
- **FHRP** — HSRP, VRRP and GLBP side by side: priorities, timers, preemption, object tracking, AVG/AVF roles, and each protocol's virtual MAC format
- **IP multicast** — IGMPv2/v3, PIM dense/sparse, static RP vs Auto-RP vs BSR, `show ip mroute` anatomy, and the RPF check
- **IP services** — NTP (incl. authentication), GRE and GRE-over-IPsec tunnels, VRF-lite and route leaking, PBR, plus DHCP snooping → Dynamic ARP Inspection → IP Source Guard

**Security, assurance & automation**

- **Enterprise security** — AAA with TACACS+ vs RADIUS, 802.1X/MAB, port-security and err-disable recovery, device hardening, WPA2/WPA3
- **Network assurance** — classic and Flexible NetFlow, SPAN/RSPAN/ERSPAN, SNMPv3, syslog severities, NETCONF/RESTCONF, EEM
- **Programmability** — JSON/YAML/XML literacy, REST verbs and status codes, Python `requests`, YANG, agent-based vs agentless orchestration

**Architecture & platforms**

- **SD-WAN & SD-Access** — vManage/vSmart/vBond/vEdge planes, OMP, LISP EID/RLOC, Map Server/Resolver, fabric node roles, VXLAN VNI/VTEP
- **Wireless** — RF fundamentals (dBm/RSSI/SNR), AP modes, the CAPWAP join sequence, L2 vs L3 roaming, location services
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
| Encyclopedia | 462 annotated commands: purpose, tokens, sample output, pitfalls, equivalents |
| Vendor compare | Same networking task across six platforms (forwarding-decision lookups, static-route failover, traffic mirroring, teaming vs EtherChannel) |
| CLI sandbox | Fake per-vendor terminal with canned output + “Explain last” — Cisco, Junos, PAN-OS, Linux, PowerShell, ESXi/PowerCLI |
| Automation labs | 16 labs: Netmiko + TextFSM EIGRP audit, EIGRP metric math, PAN-OS XML API, PowerCLI VLAN audit, jumbo-frame proofs, EEM, NETCONF/RESTCONF in Python, PBR + IP SLA failover, Ansible config backup, GuestShell, sockets |
| Drills | Flashcards (auto-built from every command), 40+ scenario quizzes, 36 incident playbooks |
| Planner | Daily 20–40 min loop + weekly focus rotation across L2, L3, QoS/assurance, PAN-OS, VMware and automation |
| Toolkit | ENCOR cert guide, 101 Labs, Wireshark, GNS3/EVE-NG, CML, VM-Series labs, nested ESXi, Postman, ntopng, iperf3, NAPALM, and more |

## Daily / weekly study (built into the app)

**Daily:** 10 flashcards → 5 command deep-dives → 1 sandbox scenario → 1 host-side (Linux/PowerShell) drill → journal one troubleshooting thought.

**Weekly:** Mon Cisco L2 (STP/EtherChannel/VLANs) · Tue Cisco L3 (EIGRP/OSPF/multicast/FHRP) · Wed QoS + network assurance · Thu Palo Alto routing & security policy · Fri VMware vSphere networking · Sat automation lab day · Sun incident scenarios + weak-card review.

## Notes

- The sandbox does **not** SSH to real devices — it is a safe offline trainer.
- Python labs are meant to be copied onto your lab PC or GuestShell.
- Everything ships in a single file: HTML + CSS + JS + embedded study data.
