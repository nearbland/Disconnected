# DISCONNECTED (alpha 0.1.0)

> A modern, standalone, single-file falling-block web game featuring a time-stop "Focus" mechanic. Built with zero dependencies.
> Disconnected has no affiliation with Tetris.

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Zero Dependencies](https://img.shields.io/badge/dependencies-none-brightgreen.svg)]()
[![Single File](https://img.shields.io/badge/built%20with-Vanilla%20JS%20%7C%20HTML5%20Canvas-orange.svg)]()

---

## ⚡ Overview

**DISCONNECTED** is fully self-contained inside a single file: `Disconnected_game.html`. It uses raw HTML5 Canvas (2D context), vanilla ES6+ JavaScript, Web Audio API, and the standard Gamepad API—with zero frameworks, build steps, or external libraries.

---

## ✨ Key Features

- **Core Falling-Block Mechanics**:
  - Full Super Rotation System (SRS) kick tables for standard tetrominoes (`JLSTZ`, `I`).
  - 7-Bag randomizer, 4-row hidden spawn buffer, sub-row falling interpolation, and grounded lock delay (0.5s with a 15-move reset limit).
  - Accurate Mini/Full T-Spins (including the 5th-kick exception), Back-to-Back (B2B ×1.5), combo multipliers, and Perfect Clear scoring .

- **"FOCUS" Mechanics**:
  - Charged through line clears (8 lines per 25% quadrant; up to 100% / 20 seconds) .
  - Freezes gravity and pushes cleared rows to the base, unlocking massive multi-line clears (Octoris, Dodecatris, up to *Infinitris*) .
  - Built-in safe exit prevents top-out game overs while in an active Focus window .

- **Game Modes**:
  - **Lines (Focus Marathon)**: Selectable line threshold from 40 to 400 lines (default 120) with SS–D rank grading .
  - **Endless**: Classic endurance and gravity scaling .
  - **Zen Mode**: Unranked, timer-free sandbox with a peaceful exit screen .

- **Controls & Cross-Platform Support**:
  - Adaptive HUD indicators for Keyboard vs. Gamepad .
  - Full Gamepad API support with D-Pad/Left Stick navigation and Right Stick menu scrolling .
  - Mobile touch HUD with an in-game **Free-Form Touch Layout Editor** (`MOVE PAD`) that saves separate layouts for Portrait and Landscape .
  - Mobile browser back-guard and escape key interception to avoid accidental tab exits .

- **Visuals & Customization**:
  - Themes: *Cyber Neon*, *Synthwave*, *Solar Flare*, *Emerald Matrix*, *Pastel Pop*, *Mono Retro*, *Black & White*, and customizable 8-accent *Monochrome*.
  - Pure `#000000` OLED dark mode .
  - Dynamic 50%–500% UI and matrix scaling.

- **Built-in Easter Eggs**: Matrix terminal sequence, an 8-bit chiptune performance, and a high-gravity "NOZEN" speed challenge.

---

## 🕹️ Default Controls

| Action | Keyboard | Gamepad | Mobile Touch |
| :--- | :--- | :--- | :--- |
| **Move Left / Right** | `←` / `→` or `A` / `D` | D-Pad / Left Stick | On-screen Left / Right |
| **Soft Drop** | `↓` or `S` | D-Pad Down / Left Stick Down | Down |
| **Hard Drop** | `Space` | D-Pad Up / `Y` / `△` | Hard Drop |
| **Rotate CW** | `↑` / `X` / `W` | `A` / `✕` | Rotate CW |
| **Rotate CCW** | `Z` / `Control` | `B` / `○` | Rotate CCW |
| **Hold Piece** | `C` / `Shift` | `LB` / `L1` | Left Hold button |
| **Activate Focus** | `V` / `Enter` | `RB` / `R1` / Triggers | Right Focus button |
| **Pause / Back** | `Esc` | `Start` / `Back` / `B` | Pause button |

---

## 🚀 Quick Start

No local servers, build tools, or dependencies required

1. Clone the repository:
   ```bash
   git clone [https://github.com/nearbland/Disconnected.git](https://github.com/nearbland/Disconnected.git)
