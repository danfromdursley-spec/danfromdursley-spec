# Dan Williams — Quantum Dynamic Systems (QDS)
*Reducing noise from information.*

I build **offline-first decision tools** (mostly on an Android phone) that turn messy real-world signals into **board-safe outputs**.
Think: a **scientific calculator for noisy systems** — batteries, markets, cosmology — wrapped in phone-safe web apps you can walk into a meeting.

---

## 💷 Pricing (offline-first tools)
**Offline Installer Tools · Pricing Menu**
- Client view: https://danfromdursley-spec.github.io/phone-chatgpt-dev-lab/qds_pricing_menu_v4.html?mode=client
- Full view:   https://danfromdursley-spec.github.io/phone-chatgpt-dev-lab/qds_pricing_menu_v4.html

---

## Snapshot
- 🔋 **Battery analytics** • 📊 **Revenue modelling** • 🧠 **Signal compression**
- 📱 Built & demoed **entirely from a phone** (Termux + static HTML/JS)
- 🧪 Open demos + reproducible runs + public datasets (Zenodo, GitHub)
- 🎯 Goal: give people **one-click, auditable experiments** instead of hand-wavy slides — especially in board and council rooms

---

## Outcomes / proof (at a glance)
- **Battery Whisperer** → flags high-stress / ageing patterns on NASA RW battery datasets in minutes, with screenshots you can drop straight into a slide.
- **Revenue Floor** → turns rough assumptions into exportable, capacity-capped revenue scenarios for grant, finance, and council packs.
- **Signal Compression / Stress-Testing** → stress-tests noisy, correlated time-series (markets, sensors, ops) to see what structure actually survives turbulence.

---

## Core tools (3 pillars)

### 1) Battery Whisperer — stress & ageing clarity
Tools for teams deploying or funding battery assets (home storage, fleets, off-grid, etc.).
- Stress / ageing insights for **real duty-cycles**, not lab fairy-tales
- Explainable metrics you can screenshot straight into a slide
- Built on public **NASA battery RW series** + synthetic stress scenarios

Designed for:
- **Installers & OEMs** wanting evidence for customers and insurers  
- **Councils & funders** wanting **risk-aware deployment plans**

### 2) Revenue Floor — reality-checked plans
Evidence packs for grant, finance, and board conversations.
- **Capacity-capped** revenue scenarios (no hockey-stick hallucinations)
- Assumptions are visible and defensible (audit-friendly)
- Exports for briefings: copy board, print layout, JSON/CSV packs

Tuned for:
- Grant applications (clear linkage from assumptions → outputs)
- Explorer decks & council briefings (stress-tested scenarios, not one-liners)

### 3) Signal Compression / Stress-Testing — noisy data as an asset
For any time-series where noise is part of the story (markets, sensors, operations).
- Works on **noisy, correlated time-series**
- Physics-inspired “**noise as a resource**” view — test what survives turbulence
- Explainable knobs:
  - correlation length
  - variance / volatility
  - duty-cycle / stress history

---

## Why offline-first
Most of the rooms that matter don’t live in perfect cloud-SaaS land.
- Works in **low-connectivity environments** (site visits, workshops, council rooms)
- Fast demos: **click → run → export** (no login, no setup)
- “Show your working” by default — inputs, assumptions, outputs visible
- No back-end, no external calls — everything runs **client-side** for:
  - easy auditing & pen-testing
  - air-gapped use on sensitive networks
  - long-term reproducibility (HTML files keep working)

---

## Live demos (safe to click, fork, and test)
All of these run purely in the browser. No tracking, no back-end.

### 🔋 Battery & operations
- **Battery Whisperer (public demo)** — Battery stress & ageing sandbox for real-world duty cycles  
  https://danfromdursley-spec.github.io/QDS-Battery-Whisperer-Demo/

### 🌌 Physics & constraint labs
- **QDS Physics Labs (public pack)** — Front door into multiple physics / cosmology tools  
  https://danfromdursley-spec.github.io/QDS-Physics-Labs-Demo/www/qds_physics_omega_frontdoor_v3.html

- **QDS Binary Pulsar Constraint Lab · One-Button NEON** — One-click Yukawa-style envelope sanity sweep  
  https://danfromdursley-spec.github.io/QDS-Physics-Labs-Demo/www/qds_pulsar_onebutton_neon.html

### 🎮 Fairness & algorithm labs
- **Qutrit Competition Lab · Ultra** — Tweak rules, run tournaments, see what survives noisy play  
  https://danfromdursley-spec.github.io/qds-qutrit-competition-lab-ultra/qutrit_competition_lab_ultra.html

---

## Who this is for

### 🔬 Scientists & engineers
- Want to test “what if?” constraints quickly on real or public data
- Need transparent, modifiable models rather than opaque services

### 💼 Founders, operators, and boards
- Need sanity-checked numbers for batteries, rollouts, or noisy operations
- Prefer tools that log assumptions and drop straight into a diligence pack

### 🧱 Councils, funders, and public bodies
- Need offline-capable demos that work in meeting rooms and site cabins
- Want evidence that connects **data → risk → decision**, and can be re-run later

### 🧪 Students & curious hackers
- Want real examples of doing non-trivial science & engineering **without a big lab**
- Interested in Termux / phone-first development, reproducible experiments, and physics-flavoured sims

---

## Under the hood (tech & stack)
- **Platform:** Android + Termux + `python -m http.server` + static HTML/JS
- **Languages:** JavaScript/TypeScript, Python, Bash, HTML5 Canvas / SVG
- **Data:** public datasets (NASA battery RW series, open astronomy catalogues, Zenodo releases, etc.)
- **Design goals:**
  - Offline-capable, single-file or small-bundle tools
  - Zero external JS dependencies where possible
  - Clear separation of **model, UI, and evidence export**

---

## Data & publications
If you only click one thing: **Preprint (variance model)** → then **data release** → then **MIT tools**.

### Preprint / papers
- 10.5281/zenodo.18056074 — *Stochastic Vacuum Kernel Cosmology: A QDS Variance Model*
- 10.5281/zenodo.17769921 — *QDS: GR-Compatible Stochastic Kernel Cosmology*

### Data / reproducibility
- 10.5281/zenodo.17451092 — Data release (supporting material + reproducibility bundle)
- 10.5281/zenodo.17448726 — Data release v1 (concept DOI: 10.5281/zenodo.17448725)

### Software (MIT)
- 10.5281/zenodo.17771649 — MIT-licensed tools (offline-first demos / analysis helpers)

**ORCID:** 0009-0009-5888-5140

---

## How I work
- Build fast. Ship clean. Prove value.
- Phone-first dev (Termux + local web tools) → exportable evidence packs
- Bias toward transparent assumptions, reproducible runs, and offline demos you can take into the room
- Preference for small, inspectable tools over monoliths — easier to fork, test, and kill if the idea fails

---

## How to engage
If you:
- have data you’d like stress-tested (batteries, markets, sensors, astronomy),
- want a **phone-safe demo** built around your system, or
- are looking for a collaborator who’s comfortable living at the **physics ⇄ software ⇄ business** boundary,

reach out:
- 📧 Email: danfromdursley@gmail.com
- 🔗 ORCID: https://orcid.org/0009-0009-5888-5140
