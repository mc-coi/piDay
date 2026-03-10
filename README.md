# MORTAL KOMBAKE

> *"Its a good day to pi"*

A pie-themed 2-player fighting game built for **Pi Day (March 14th)** — inspired by Mortal Kombat, built in a few hours.

![Game Screenshot](https://img.shields.io/badge/Pi%20Day-March%2014-gold?style=for-the-badge) ![Platform](https://img.shields.io/badge/Platform-Browser-blue?style=for-the-badge) ![Players](https://img.shields.io/badge/Players-2%20Local-red?style=for-the-badge)

---

## How to Play

Open `mortal-kombake.html` in any modern browser. No install, no server — just double-click and fight.

1. Click **⚔ BEGIN KOMBAKE** on the title screen
2. Each player selects their fighter on the character select screen
3. First to win **2 rounds** takes the Kombake crown

---

## The Roster

| Fighter | Emoji | Style |
|---|---|---|
| Cherry Bomb | 🥧 | Balanced speed/power |
| Lord Meringue | 🍋 | Heavy hitter |
| The Pecan | 🤎 | Slow but devastating |
| Pumpkin Reaper | 🎃 | Fast slasher |
| Shepherd's Bane | 🛡️ | All-rounder |
| Π Destroyer | 🔢 | Glass cannon speedster |

---

## Controls

### Player 1 — Left Side
| Key | Action |
|---|---|
| `A` / `D` | Move left / right |
| `W` | Jump |
| `F` | Punch |
| `G` | Kick |
| `R` + `F` | **Special** (throws pie) |

### Player 2 — Right Side
| Key | Action |
|---|---|
| `←` / `→` | Move left / right |
| `↑` | Jump |
| `K` | Punch |
| `L` | Kick |
| `P` + `K` | **Special** (throws pie) |

---

## Combat

| Move | Damage | Notes |
|---|---|---|
| Punch | 8 HP | Fast, short range |
| Kick | 12 HP | Extended reach, launches opponent |
| Special | 22 HP | Fires a spinning 🥧 pie projectile — can be dodged! |

- **Health bars** deplete in real time — watch the color shift to red when low
- **Timer** counts down from 99; if time runs out the player with more HP wins
- **Screen shake** on special hits and KOs
- **Dizzy stars** appear above a fighter hit by a special move
- **Win dots** track rounds won (best of 2)

---

## Screens

- **Title Screen** — atmospheric torchlit intro with flickering logo
- **Character Select** — click to pick P1's fighter; Shift+click for P2. Stats and special move preview shown for each fighter
- **Fight Arena** — stone floor, torch flames, ominous pie moon in the sky
- **Victory Screen** — winner announced with a random Pastry-ality message

---

## Technical Details

- Pure **vanilla HTML5 / JavaScript / Canvas** — single `.html` file, zero dependencies
- Rendering via `Canvas 2D API` with per-frame game loop (`requestAnimationFrame`)
- Fighter art drawn entirely in code (no image assets)
- Pie projectiles use basic parabolic physics
- Particle system for hit effects, explosions, and victory celebrations

---

## About

Made for **Pi Day — March 14th** 🥧 a ThinkSpace project at STEM School Chattanooga.

*π ≈ 3.14159265358979...*
