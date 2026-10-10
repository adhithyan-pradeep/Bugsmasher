# 👾 3AM Bugsmasher — Arcade Hotfix Mayhem

[![Antigravity](https://img.shields.io/badge/Built%20With-Google%20DeepMind%20Antigravity-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://deepmind.google)
[![Wispr Flow](https://img.shields.io/badge/Powered%20By-Wispr%20Flow-7C3AED?style=for-the-badge&logo=soundcharts&logoColor=white)](https://wisprflow.ai)
[![Tailwind CSS](https://img.shields.io/badge/Styling-Tailwind%20CSS%20v3-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://tailwindcss.com)
[![Web Audio API](https://img.shields.io/badge/Audio-Pure%20Web%20Audio%20API-10B981?style=for-the-badge&logo=webrtc&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)
[![Zero Dependencies](https://img.shields.io/badge/Architecture-Single--File%20%2F%20Zero%20Build-F59E0B?style=for-the-badge)](index.html)

> *"It's 3:00 AM. Production is ablaze. PagerDuty won't stop screaming. NullPointer bugs and Memory Leaks are breaking containment across the server rack. Grab your mechanical keyboard, activate Wispr Flow, and let's hotfix this outage before morning standup!"*

---

## 🚀 Co-Created with Antigravity × Wispr Flow

This project was built from concept to production through the combined superpowers of **Antigravity** and **Wispr Flow** — in a fully **voice-driven development session**:

- **🎙️ Wispr Flow (Voice-Driven Prompting)**: Every single prompt, design direction, feature request, and iteration in this project was **spoken aloud and dictated via Wispr Flow**. There was no keyboard typing of instructions — Wispr Flow transcribed the developer's voice in real-time into precise, structured prompts that were sent directly to Antigravity. This is voice-driven development at its most literal: describing a game concept, a new UI feature, or a specific sound effect out loud, and watching Antigravity build it immediately.
- **🤖 Google DeepMind Antigravity**: Served as the agentic AI pairing partner receiving those voice-dictated prompts — architecting the single-file modular codebase, implementing real-time Web Audio API signal synthesis (oscillators, biquad filters, procedural noise buffers), constructing dynamic canvas particle physics, configuring cyberpunk Tailwind styling, and tuning the game balance mechanics, all from spoken natural language alone.

### 🗣️ The Voice-Driven Development Workflow

```
Developer speaks  ──►  Wispr Flow transcribes  ──►  Antigravity receives prompt  ──►  Code ships
  (no keyboard)          in real-time                 & builds the feature           immediately
```

This project is a living proof-of-concept for **fully hands-free software creation**: an idea spoken into the air becomes a production-ready, playable arcade game — without the developer writing a single line of code or a single typed word. The game's own **Wispr Flow™ Voice Overdrive** mechanic is a direct homage to this workflow: one voice command to clear the entire server rack of bugs, just as one spoken sentence to Antigravity delivers an entire feature.

---

## 🎮 Game Backstory & Overview

You are the lone on-call software engineer guarding `us-east-1` at 3:00 AM. A rogue pull request bypassed CI/CD, unleashing an army of bugs directly into the server sockets.

You have a strict **30.0-second incident response window** to smash bugs, maintain high combo streaks, gulp espresso for emergency clock extensions, avoid disastrous `--force` pushes, charge your **Wispr Flow™ Voice Overdrive**, and earn your ticket to **Hacker House Goa**!

---

## ✨ Features & Gameplay Mechanics

### 1. 🎛️ Cyberpunk Header & SEV-1 Incident Banner
- **SEV-1 Critical Outage Status**: Flashing telemetry alert with a live incident ticker (`#war-room-3am`).
- **All-Time High Score**: Automatically persisted across game sessions via browser `localStorage`.
- **Sound Toggle**: Instant audio muting/unmuting with HUD status.

### 2. 📊 High-Precision Top Stats HUD
- **5-Digit LED Score Display**: Retro arcade counter that tallies points with dynamic scaling and bounce effects.
- **Combo Counter & Dynamic Multipliers**:
  - `5+ Combo`: **1.5x Multiplier** (On Fire)
  - `10+ Combo`: **2.0x Multiplier** (Supercharged)
  - `15+ Combo`: **3.0x Multiplier** (MAX HYPER STREAK with neon magenta pulse)
- **30.0-Second Precision Countdown Timer**:
  - Live millimeter progress bar showing time left in the shift.
  - Urgent critical heartbeat pulse alert when time drops below 8.0 seconds.

### 3. 🕹️ 3×3 Server Rack Hotspots
- Nine interactive server socket ports (`PORT:0` to `PORT:8`) with a central highlighted core (`CORE:4`).
- CRT scanline overlay, ambient matrix grid, and responsive hover/glow animations.
- Custom cursor smasher hammer animation on clicks and whacks.

### 4. 👾 Dynamic Entity Roster

| Entity | Emoji | Points | Effect | Behavior |
| :--- | :---: | :---: | :--- | :--- |
| **NullPointer Bug** | 🐛 | `+100 PTS` | Standard bug squash | Normal spawn duration, base combo booster |
| **Memory Leak (Crit)** | 🕷️ | `+250 PTS` | Critical bug squash | High-speed despawn, critical hit sound & particles |
| **Espresso Shot (Bonus)** | ☕ | `+300 PTS` | **+2.0s Time Extension** | Keeps the server alive longer; golden glow |
| **Force Push Trap** | 💣 | `-200 PTS` | **Combo Wiped to 0** | Explodes on click, triggers screen shake & Slack alarm |

---

## ⚡ Wispr Flow™ Voice Overdrive & Lightning Wipe

The marquee mechanic of 3AM Bugsmasher is the **Wispr Flow™ Voice Power**:

```
[ Whack Bugs / Sip Coffee ] ──► [ Voice Meter Charges ] ──► [ 100% OVERDRIVE READY ] ──► [ Press 'V' or Click ]
                                                                                                  │
                                  ┌───────────────────────────────────────────────────────────────┘
                                  ▼
      ⚡ FULL-SCREEN PROCEDURAL LIGHTNING WIPE
      💥 Vaporizes all active bugs on the grid simultaneously
      🛡️ Automatically defuses all active Force Push bombs safely
      ☕ Automatically cashes in all active espressos (+300 PTS & +2s each)
      🔊 Voice laser frequency sweep + thunderous electrical shockwave
      📳 Dramatic screen shake & canvas particle lightning branches
```

- **Charging**: Whacking bugs grants `+14%` to `+22%` charge; drinking espresso grants `+25%`; passive charge trickles in continuously.
- **Trigger**: Hit the glowing neon Wispr Flow button or press the <kbd>V</kbd> / <kbd>F</kbd> key.

---

## 🔊 100% Synthesized Web Audio API Sound Engine

**No MP3s. No WAV files. Zero network audio requests.** Every single sound in the game is synthesized mathematically in real-time using the native HTML5 Web Audio API:

- 🐛 **Bug Splat**: Descending triangle-wave pitch squelch (440Hz ➔ 55Hz) blended with an organic low-pass filtered white noise burst.
- ☕ **Espresso Chime**: Crystalline 4-note bell triad (C6, E6, G6, C7; 1046Hz – 2093Hz) with exponential decays.
- 🚨 **Slack Buzzer / Bomb Trap**: Two-tone woodblock knock-brush (440Hz ➔ 660Hz) followed by a harsh 165Hz sawtooth SEV-1 workspace buzzer.
- 🎙️ **Wispr Voice Laser**: Futuristic sci-fi bandpass-filtered frequency sweep (180Hz ➔ 2600Hz ➔ 220Hz) with high Q resonance.
- ⚡ **Lightning Screen Wipe**: High-voltage sawtooth zap (880Hz ➔ 75Hz), sub-bass thunder rumble (140Hz ➔ 32Hz sine wave), and bandpass-filtered electrical static crackle.
- 🎺 **Start Fanfare & Game Over**: Arpeggiated major chords and mournful descending minor transitions.

---

## 🏆 End-Game Developer Rank Calculations

When the 30-second maintenance shift ends, your performance is evaluated via a composite engineering score:

$$\text{Performance Score} = \text{Final Score} + (\text{Max Combo} \times 60) + (\text{Wispr Wipes} \times 400) + (\text{Accuracy \%} \times 25)$$

### Rank Tiers:

1. **🐐👑 S+ Tier — 10x Mythical Goat of Goa** (Score ≥ 5,800 or Perf ≥ 7,200)
   > *"Dictated 5,000 lines of Rust via Wispr Flow with a coconut in hand. Outage resolved before morning standup!"* — **Top 0.1% Mythical Engineer**
2. **🚒⚡ S Tier — Principal 3AM Firefighter** (Score ≥ 4,000 or Perf ≥ 5,000)
   > *"Averted us-east-1 cataclysm in the dead of night. The incident commander wept tears of pure relief."* — **Top 3% Emergency Responder**
3. **⚔️🔥 A Tier — Senior Staff Hotfix Exterminator** (Score ≥ 2,600 or Perf ≥ 3,200)
   > *"Smashed memory leaks with laser precision strikes. Never broke a sweat or missed a single espresso sip."* — **Top 15% Veteran Fixer**
4. **📜☕ B Tier — Mid-Level YAML Whisperer** (Score ≥ 1,400 or Perf ≥ 1,800)
   > *"Guessed the Kubernetes port on the second try. Kept the system latency within acceptable limits."* — **Top 45% Stable Contributor**
5. **🍼💻 C Tier — Junior Bootcamper (Spilled Chai)** (Baseline)
   > *"Survived the 3AM outage! A bit shaky on the git cherry-picks, but the prod server is still breathing."* — **Top 70% of On-Call Responders**

---

## 🌴 VIP Golden Ticket: Hacker House Goa

Survive the shift and unlock your golden pass to **Hacker House Goa**:
- **Golden Foil Button**: Shimmering animated gold button with ambient particle bursts.
- **Pass Details Modal**:
  - Official VIP Invitation with individual Boarding Pass Serial (`GOA-WISPR-XXXX`).
  - Awarded Developer Rank & Handle.
  - Retreat Perks: Private Beachfront Villa & Infinity Pool Co-working, 10 Gbps Starlink Fiber + Wispr AI Voice Lab, unlimited single-origin espresso & fresh tender coconuts.
- **Copyable Ticket & Share Stats**: One-click clipboard copy feature to flex your ticket and stats to your team or social media.

---

## ⌨️ Controls & Keyboard Shortcuts

| Key | Action |
| :---: | :--- |
| <kbd>Left Click</kbd> / <kbd>Tap</kbd> | Squash bug / Drink espresso / Defuse socket |
| <kbd>Space</kbd> | Start Game / Replay Hotfix Shift |
| <kbd>V</kbd> or <kbd>F</kbd> | Activate Wispr Flow™ Lightning Screen Wipe |
| <kbd>R</kbd> | Quick Reset Shift |
| <kbd>M</kbd> | Toggle Sound On / Off |

---

## 📁 Project Structure & Quickstart

The entire game is self-contained in a single, zero-dependency file:

```
wisprtask/
├── index.html        # Complete standalone application (HTML, CSS, JS, Audio, Canvas)
└── README.md         # Full project documentation & attribution
```

### Running Locally

No `npm`, `pnpm`, or build step required! You can open it directly:

#### Option 1: Direct File Open
Double-click `index.html` in your file explorer, or open it in any modern browser:
```bash
# Windows
start index.html

# macOS
open index.html

# Linux
xdg-open index.html
```

#### Option 2: Local HTTP Server
```bash
# Using Python
python -m http.server 8080

# Using Node.js
npx serve .
```
Then navigate to `http://localhost:8080` in Chrome, Edge, Safari, or Firefox.

---

## 🛠️ Technical Stack & Implementation Highlights

- **HTML5 Canvas 2D Engine**: High-performance particle physics simulating sparks, directional splats, multi-point recursive fractal lightning bolts, and tumbling multi-colored confetti ribbons.
- **Tailwind CSS (CDN)**: Modern utility-first cyberpunk palette (`#00f2ff` cyan, `#ff007f` magenta, `#39ff14` lime, `#ffb703` amber, `#b026ff` purple) with glowing neon drop shadows and CRT scanline aesthetics.
- **Web Audio API**: Real-time signal generation with zero external asset latency, complete with user gesture auto-resume.
- **Responsive & Mobile Ready**: Full touch event handling, responsive grid scaling for desktop, tablet, and mobile screens.

---

## 🤝 Acknowledgements

- **Google DeepMind Antigravity**: For state-of-the-art agentic pair programming, codebase generation, sound synthesis design, and game design execution.
- **Wispr Flow**: For powering next-generation voice-first developer productivity and inspiring the game's core lightning wipe superpower.
