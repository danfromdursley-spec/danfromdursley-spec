# Dan Williams — Quantum Design Systems (QDS)

*Reducing noise from information.*

I build **offline-first decision tools** (mostly on an Android phone) that turn messy real-world signals into **board-safe outputs**.

Think: a **scientific calculator for noisy systems** — batteries, markets, cosmology — wrapped in phone-safe web apps you can walk into a meeting.

---

## Snapshot

- 🔋 **Battery analytics** • 📊 **Revenue modelling** • 🧠 **Signal compression**
- 📱 Built & demoed **entirely from a phone** (Termux + static HTML/JS)
- 🧪 Open demos + reproducible runs + public datasets (Zenodo, GitHub)
- 🎯 Goal: give people **one-click, auditable experiments** instead of hand-wavy slides — especially in board and council rooms

---

## Core tools (3 pillars)

### 1) Battery Whisperer — stress & ageing clarity

Tools for teams deploying or funding battery assets (home storage, fleets, off-grid, etc.).

- Battery stress / ageing insights for **real duty-cycles**, not lab fairy-tales  
- Simple, explainable metrics you can screenshot straight into a slide  
- Built on public **NASA battery RW series** + synthetic stress scenarios  

Designed for:

- **Installers & OEMs** wanting evidence for customers and insurers  
- **Councils & funders** wanting **risk-aware deployment plans**

---

### 2) Revenue Floor — reality-checked plans

Evidence packs for grant, finance, and board conversations.

- Realistic revenue plans: **capacity-capped, assumption-audited**  
- Answers “**What does this actually look like in cash & risk?**” rather than hockey-sticks  
- Tuned for  
  - grant applications (clear linkage from assumptions → outputs)  
  - explorer decks & council briefings (stress-test scenarios, not just one line)

---

### 3) Signal Compression / Stress-Testing — noisy data as an asset

For any time-series where noise is part of the story (markets, sensors, operations).

- Tools for **noisy, correlated time-series** (markets, sensors, operational data)  
- Physics-inspired **“noise as a resource”** view — test what survives turbulence  
- Focus on explainable knobs:
  - correlation / length  
  - variance / volatility  
  - duty-cycle / stress history  

---

## Why offline-first

Most of the rooms that matter don’t live in perfect cloud-SaaS land.

- Works in **low-connectivity environments** (site visits, workshops, council rooms)  
- Fast demos: **click → run → export** (no login, no setup)  
- “Show your working” by default — inputs, assumptions, and outputs all visible  
- No back-end, no external API calls — everything runs **client-side** for:
  - easy auditing & pen-testing  
  - air-gapped use on sensitive networks  
  - long-term reproducibility (HTML files keep working)

---

## Live demos (safe to click, fork, and test)

All of these run purely in the browser. No tracking, no back-end, just static pages + JS.

### 🔋 Battery & operations

- **Battery Whisperer (public demo)**  
  Battery stress & ageing sandbox for real-world duty cycles.  
  https://danfromdursley-spec.github.io/QDS-Battery-Whisperer-Demo/

### 🌌 Physics & constraint labs

- **QDS Physics Labs (public pack)**  
  Front door into multiple physics / cosmology tools (rotation curves, variance labs, etc.).  
  https://danfromdursley-spec.github.io/QDS-Physics-Labs-Demo/www/qds_physics_omega_frontdoor_v3.html  

- **QDS Binary Pulsar Constraint Lab · One-Button NEON**  
  One-click Yukawa-style envelope sanity sweep for binary pulsars.  
  Given orbital separation and an allowed timing residual band, it computes the tightest allowed QDS amplitude α(λ).  
  https://danfromdursley-spec.github.io/QDS-Physics-Labs-Demo/www/qds_pulsar_onebutton_neon.html

### 🎮 Fairness & algorithm labs

- **Qutrit Competition Lab · Ultra (neon fairness sandbox)**  
  Tweak qutrit transition rules, run tournaments, and see which strategies survive noisy play.  
  https://danfromdursley-spec.github.io/qds-qutrit-competition-lab-ultra/qutrit_competition_lab_ultra.html  

_Example path:_ DDO154 → compute χ² → scan QDS distance factor → log result in the Evidence Log.

---

## Who this is for

### 🔬 Scientists & engineers

- Want to test **“what if?”** constraints quickly on real or public data  
- Need transparent, modifiable models rather than opaque services  

### 💼 Founders, operators, and boards

- Need **sanity-checked numbers** for batteries, hardware rollouts, or noisy operations  
- Prefer tools that log assumptions and can be dropped straight into a diligence pack  

### 🧱 Councils, funders, and public bodies

- Need **offline-capable demos** that work in meeting rooms and site cabins  
- Want evidence that:
  - connects **data → risk → decision**, and  
  - can be re-run later without a platform subscription  

### 🧪 Students & curious hackers

- Looking for real examples of doing non-trivial science & engineering **without a big lab**  
- Interested in Termux / phone-first development, reproducible experiments, and physics-flavoured simulations  

---

## Under the hood (tech & stack)

- **Platform:** Android + Termux + `python -m http.server` + static HTML/JS  
- **Languages:** TypeScript / JavaScript, Python, Bash, HTML5 Canvas / SVG  
- **Data:** public datasets (NASA battery RW series, open astronomy catalogues, Zenodo releases, etc.)  
- **Design goals:**
  - Offline-capable, single-file or small-bundle tools  
  - Zero external JS dependencies where possible  
  - Clear separation of **model, UI, and evidence export**

---

## Data & publications (start here)
If you only click one thing: **Preprint (variance model)** → then **data release** → then **MIT tools**.

**Preprint / papers**
- 10.5281/zenodo.18056074 — *Stochastic Vacuum Kernel Cosmology: A QDS Variance Model* (core idea + predictions/falsifiers)
- 
- 10.5281/zenodo.17769921 — *QDS: GR-Compatible Stochastic Kernel Cosmology* (framework + formalism)

**Data / reproducibility**
- 10.5281/zenodo.17451092 — Data release (supporting material + reproducibility bundle)
- 
- 10.5281/zenodo.17448726 — Data release v1 (concept DOI: 10.5281/zenodo.17448725)

**Software (MIT)**
- 10.5281/zenodo.17771649 — MIT-licensed tools (offline-first demos / analysis helpers)

ORCID: 0009-0009-5888-5140predictionsow I work

- **Build fast. Ship clean. Prove value.**  
- Phone-first dev (Termux + local web tools) → exportable evidence packs.  
- Bias toward **transparent assumptions**, reproducible runs, and offline demos you can take into the room.  
- Preference for **small, inspectable tools** over monoliths — easier to fork, test, and throw away if the idea fails.

---

## How to engage

If you:

- have data you’d like stress-tested (batteries, markets, sensors, astronomy),  
- want a **phone-safe demo** built around your system, or  
- are looking for a collaborator who’s comfortable living at the **physics ⇄ software ⇄ business** boundary,

then feel free to reach out.

---

## Contact

📍 Dursley, UK  
📧 danfromdursley@gmail.com  
🌐 https://github.com/danfromdursley-spec
