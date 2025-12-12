# Street Fighter–Style Fighting Game (CMU Graphics) — Python

## Project Summary

This project is a **Street Fighter–inspired 2D fighting game** developed in **Python** using **CMU Graphics**. The game demonstrates real-time gameplay systems including character movement, attacks, projectile mechanics, collision detection, health tracking, and match flow, all implemented from scratch without a game engine.

The project focuses on **game systems design, animation handling, user input processing, and UI feedback**, delivering a playable and polished fighting game experience suitable for academic and portfolio presentation.

---

## Key Highlights

- Fully playable **2D fighting game**
- Custom **menu system** with Play and Controls screens
- Real-time combat with **melee and projectile attacks**
- **Health bars, round indicators, and UI feedback**
- Frame-based animation and hit detection
- Clean, modular Python game architecture

---

## Gameplay Features

### Characters
- **Ryu (Character One)**
- **Sagat (Opponent Character)**

Each character features:
- Idle and movement animations
- Attack animations
- Hit reactions and knockback

---

### Combat Mechanics
- **Melee attacks (Punch)**
- **Projectile attack (Hadouken)**
- Damage values assigned per attack
- Projectile collision detection
- Health reduction and win conditions

---

### Game Flow & UI
- Start menu with:
  - **Play Game**
  - **Controls**
- Controls screen displaying:
  - Character images
  - Movement and attack mappings
  - Damage values per move
- In-game UI:
  - Health bars for both players
  - Round indicators
  - Visual hit feedback during combat

---

## Controls (As Implemented)

### **Ryu (Character One)**

**Movement**
- Move Left: `Left Arrow`
- Move Right: `Right Arrow`
- Jump: `W`

**Attacks**
- Punch (10 damage): `M`
- Hadouken (15 damage): `L`

---

## Technical Stack

- **Language:** Python  
- **Framework / Library:** CMU Graphics  
- **Programming Concepts:**
  - Game loops
  - State-based animation
  - Collision detection
  - Input handling
  - UI rendering

---

## Engineering & Design Focus

- Designed a real-time **update–render loop**
- Implemented projectile physics and collision logic
- Structured character logic for extensibility
- Balanced visual clarity and gameplay responsiveness
- Managed multiple game states (menu, controls, gameplay)

---

## Testing & Debugging

- Manual gameplay testing for:
  - Collision accuracy
  - Damage consistency
  - Input responsiveness
- Iterative tuning of animations and hit timing

---

## How to Run

1. Open the project in a **CMU Graphics–supported Python environment**.
2. Run the main Python file.
3. Use the menu to start the game or view controls.

---

## Academic Context

This project was developed for **CMU Graphics** as part of coursework emphasizing:
- Interactive graphics
- Game mechanics implementation
- Real-time user interaction
- Visual feedback and UI design

---

## Notes

This project is intended for **educational and portfolio demonstration purposes** and showcases hands-on experience in building a complete interactive game system in Python.
