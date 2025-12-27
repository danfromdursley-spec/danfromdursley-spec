# Dan Williams — Quantum Design Systems (QDS)

I build **offline-first decision tools** (mostly on an Android phone) that turn messy real-world signals into **board-safe outputs**.

Think: *scientific calculator for noisy systems* — batteries, markets, cosmology — wrapped in phone-safe web apps.

---

## Snapshot

- 🔋 Battery analytics • 📊 Revenue modelling • 🧠 Signal compression  
- 📱 Built & demoed **entirely from a phone** (Termux + local web stack)  
- 🌐 Open demos + reproducible runs + public datasets (Zenodo, GitHub)  
- 🎯 Goal: give people **one-click, auditable experiments** instead of hand-wavy slides

---

## Current focus (3 pillars)

- 📱 **Battery Whisperer**  
  - Battery stress / ageing insights for real duty-cycles  
  - Simple, explainable metrics you can screenshot into a slide  
  - Built on public NASA datasets + synthetic stress scenarios

- 📊 **Revenue Floor**  
  - Realistic revenue plans: **capacity-capped, assumption-audited**  
  - “What does this actually look like in cash & risk?” rather than hockey-sticks  
  - Exportable evidence pack for boards, investors, and grant panels

- 🧠 **Signal Compression / Stress-Testing**  
  - Tools for noisy time-series (markets, sensors, operational data)  
  - Physics-inspired “noise as a resource” view — test what survives turbulence  
  - Focus on explainable knobs: correlation length, variance, duty-cycle

---

## Why offline-first

- Works in **low-connectivity environments** (site visits, workshops, council rooms)  
- Fast demos: **click → run → export** (no login, no setup)  
- “Show your working” by default — inputs, assumptions, and outputs all visible  
- No back-end, no external API calls — everything runs **client-side** for easy auditing, pen-testing, and air-gapped use

---

## Live demos

These all run client-side in the browser – safe to try, fork, or take into a room.

- 🔋 **Battery Whisperer (public demo)**  
  Battery stress & ageing sandbox for real-world duty cycles.  
  https://danfromdursley-spec.github.io/QDS-Battery-Whisperer-Demo/

- 🌌 **QDS Physics Labs (public pack)**  
  Front door into multiple physics / cosmology tools (rotation curves, variance labs, etc.).  
  https://danfromdursley-spec.github.io/QDS-Physics-Labs-Demo/www/qds_physics_omega_frontdoor_v3.html  

- 🎮 **Qutrit Competition Lab · Ultra (neon fairness sandbox)**  
  Tweak qutrit transition rules, run tournaments, and see which strategies survive noisy play.  
  https://danfromdursley-spec.github.io/qds-qutrit-competition-lab-ultra/qutrit_competition_lab_ultra.html  

  _Example path:_ DDO154 → compute χ² → scan QDS distance factor → log result in the Evidence Log.

- 🌠 **QDS Binary Pulsar Constraint Lab · One-Button NEON**  
  One-click Yukawa-style envelope sanity sweep for binary pulsars.  
  Given orbital separation and an allowed timing residual band, it computes the tightest allowed QDS amplitude α(λ).  
  https://danfromdursley-spec.github.io/QDS-Physics-Labs-Demo/www/qds_pulsar_onebutton_neon.html

---

## Who this is for

- 🧪 **Scientists & engineers**  
  - Want to test “what if?” constraints quickly on real or public data  
  - Need transparent, modifiable models rather than opaque services  

- 🧾 **Founders, operators, and boards**  
  - Need **sanity-checked numbers** for batteries, hardware rollouts, or noisy operations  
  - Prefer tools that log assumptions and can be dropped straight into a diligence pack  

- 🎓 **Students & curious hackers**  
  - Looking for real examples of doing non-trivial science & engineering **without a big lab**  
  - Interested in Termux / phone-first dev, reproducible experiments, and physics-flavoured simulations

---

## Under the hood (tech & stack)

- **Platform:** Android + Termux + `python -m http.server` + static HTML/JS  
- **Languages:** TypeScript/JavaScript, Python, Bash, HTML5 Canvas / SVG  
- **Data:** public datasets (NASA battery RW series, open astronomy catalogues, Zenodo releases, etc.)  
- **Design goals:**
  - Offline-capable, single-file or small-bundle tools  
  - Zero external JS dependencies where possible  
  - Clear separation of **model**, **UI**, and **evidence export**

---

## Data & publications

- **QDS variance & cosmology stack** — Zenodo datasets & software  

  - 10.5281/zenodo.17769921 — *QDS: GR-Compatible Stochastic Kernel Cosmology*  
  - 10.5281/zenodo.18056074 — *Stochastic Vacuum Kernel Cosmology: A QDS Variance Model*  
  - 10.5281/zenodo.17451092 — QDS data release (with software and supporting material)

- **ORCID**: [0009-0009-5888-5140](https://orcid.org/0009-0009-5888-5140)

---

## How I work

- **Build fast. Ship clean. Prove value.**  
- Phone-first dev (Termux + local web tools) → exportable evidence packs.  
- Bias toward transparent assumptions, reproducible runs, and offline demos you can take into the room.  
- Preference for **small, inspectable tools** over monoliths — easier to fork, test, and throw away if the idea fails.

---

## How to engage

If you:

- have **data** you’d like stress-tested (batteries, markets, sensors, astronomy),  
- want a **phone-safe demo** built around your system, or  
- are looking for a collaborator who’s comfortable living at the physics ↔ software ↔ business boundary,

then feel free to reach out.

---

## Contact

📍 Dursley, UK  
📧 danfromdursley@gmail.com  
🌐 danfromdursley-spec on GitHub
