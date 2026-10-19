# System Cockpit — Features & Key Selling Points

> **Logline:** Your Mac, explained. A futuristic system cockpit that watches every core, gigabyte, and packet — then tells you in plain language what matters and what to do about it.

**Tagline options**

- SYSTEM·COCKPIT — Your Mac, explained.
- Stop guessing. Start knowing.
- A mission control for your Mac — with a local AI that speaks human.

**Positioning (the pitch in one paragraph)**
Activity Monitor tells you *numbers*. System Cockpit tells you *what they mean*. It watches your Mac in real time, flags what's abnormal, explains it in plain English, and even maps every gigabyte on your disk — all powered by a local AI that never sends your data anywhere. It's the dashboard Apple never shipped.

---

## The features

### 1. Live cockpit — your whole Mac on one screen
CPU, memory, disk pressure, swap, network, load average, and every process — updating every second. Four gauges, four live charts, hottest processes, and per-disk read/write throughput at a glance. One look and you know if the machine is healthy.

*On screen: sweep across the gauges and charts; numbers ticking in real time.*

### 2. Intelligence briefing — the AI that reads your Mac for you
One tap, four reports in parallel: **System health**, **Network & firewall**, **Notable processes**, and **Storage**. Written in plain language, not jargon — every finding carries a severity tag ([HIGH] / [MEDIUM] / [LOW]) with a concrete next step. A "Needs attention" filter shows only what matters. It streams in as the model thinks, and reuses recent results so it's instant when you come back.

*On screen: tap "Intelligence briefing"; sections fill in live; highlight a [HIGH] bullet and the "Needs attention" filter.*

### 3. Copilot — ask your Mac anything
A chat that sees live telemetry, your network history, and your disk map. "What's eating my disk?" gets an answer grounded in your actual scan, not generic advice. It remembers the conversation and pulls in past learnings from your own machine.

*On screen: type "what's eating my disk?"; answer appears citing the real numbers.*

### 4. Alerts that explain themselves
A rule engine watches for CPU hogs, disks filling fast, memory pressure, and suspicious network behavior. Each alert arrives with a severity, a count of repeat occurrences — and a plain-English explanation written by the AI, so you know whether to act or relax.

*On screen: an alert slides in; its explanation streams beneath it.*

### 5. Disk map — see every gigabyte, reclaim the wasted ones
A read-only scan walks your entire home folder (millions of files in minutes) and draws it as an interactive treemap. Stat cards show free space, safely reclaimable space, and what needs review. Smart recommendations — Xcode DerivedData, node_modules, iOS simulators, Docker data, caches, old AI models — come with one-line commands. Check what you want, copy the script, run it when you're ready.

**The safety promise: System Cockpit never deletes anything.** Cleanup happens only through a script *you* copy and review. Your files are always yours.

*On screen: treemap zooming from home folder into Library/Caches; stat cards; checkbox recommendations; "Copy script".*

### 6. Network X-ray + built-in speed test
See which apps move your bytes — in and out, first and last seen — with live connection endpoints and states, persisting across restarts. Filter by app, IP, or port to hunt down a talkative process. And a built-in **speed test** measures real download, upload, and ping to the nearest edge — with a live meter, results in ~15 seconds.

*On screen: per-app traffic rows; endpoint chips; speed test meter climbing to the result.*

### 7. It learns what you find useful
Every 👍/👎 on a briefing section or alert explanation is remembered. A daily reflection distills that feedback into learnings, and future analyses use them — the cockpit gets better attuned to *your* Mac the more you use it. Add your own notes to the knowledge base anytime.

*On screen: vote buttons; a learning note appearing in Knowledge.*

### 8. Process explorer with full detail
Every process with CPU, memory, threads, network I/O, disk I/O, and path — sortable and searchable. When something's hot, you see exactly what and where it is.

*On screen: sort by CPU; reveal a process path.*

### 9. Private by design
All analysis runs on your machine against a local model (Ollama, LM Studio, or your own endpoint). Telemetry, scans, chats, and learnings never leave your Mac. No account, no cloud, no tracking. Speed tests touch only Cloudflare's measurement endpoint.

*On screen: settings showing the local model endpoint; "local LLM" chip.*

### 10. Native, fast, and beautiful
Built in Rust with a React cockpit UI — tiny footprint, buttery 1-second refresh. Four themes: Light, Dark, **Monochrome**, and **Matrix terminal**. Universally signed and notarized for macOS.

*On screen: theme switcher cycling through all four themes.*

---

## Suggested 60-second ad script

| Beat | Time | On screen | Voice-over |
|---|---|---|---|
| Cold open | 0:00–0:05 | Activity Monitor wall of numbers, confusing | "Your Mac produces a thousand numbers a second. None of them talk." |
| Reveal | 0:05–0:10 | System Cockpit fades in, gauges ticking | "This is System Cockpit. Your whole machine, on one screen — alive." |
| Briefing | 0:10–0:22 | Tap briefing; four sections stream; [HIGH] tag; Needs-attention filter | "One tap and its local AI briefs you: health, network, processes, storage — in plain language, with exactly what to do next." |
| Disk map | 0:22–0:35 | Treemap zoom, stat cards, check recommendations, copy script | "Wondering where 400 gigabytes went? The disk map draws every one of them — and hands you a script to reclaim the waste. It never deletes a thing without your say-so." |
| Network + speed test | 0:35–0:45 | Per-app traffic, endpoints, speed test meter | "See which apps move your bytes, what they connect to — and how fast your internet really is." |
| Alerts + learning | 0:45–0:52 | Alert explanation streams; 👍 tap | "When something's wrong, it tells you why. And the more you use it, the better it knows your Mac." |
| Close | 0:52–0:60 | Theme cycle to Matrix; wordmark | "Private. Local. Yours. SYSTEM·COCKPIT — your Mac, explained." |

---

## Claims guardrails (keep the ad honest)

- ✅ Safe to say: read-only disk analysis, never auto-deletes; local AI; plain-English briefings; built-in speed test; learns from your feedback; signed & notarized.
- ⚠️ Don't say: "antivirus", "removes malware", "makes your Mac faster" — it *diagnoses and explains*; cleanup is user-run. Don't claim specific speed-test numbers, only the mechanism (~15 s, down/up/ping).
