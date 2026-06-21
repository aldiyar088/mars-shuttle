# 🪐 Mars Shuttle 3D Prototype

A premium 3D web prototype of the Mars Shuttle landing, loading, and launch sequence, designed as a showcase and technical assessment. It adapts the classic "train loading" mechanic from *Township* to a sci-fi Martian setting.

## 🔗 Live Demo
👉 **[Launch Live Game on Mobile/Desktop](https://aldiyar088.github.io/mars-shuttle/)** (Open in Safari/Chrome on iOS/Android for full Gyroscope/Accelerometer experience!)

---

## 🎮 Game Features & Mechanics

1. **3D Interactive Orbit & Launchpad**: 
   - Powered by **Three.js** with high-fidelity custom lighting, Mars sky shader, stellar background, and responsive camera controls.
   - Interactive cargo crates that bob in 3D space.
   - Dynamic thruster, engine ignition, cargo loading, and storm discharge particle effects.
   - Procedural audio synthesizer using the **Web Audio API** (no external audio files needed).

2. **Cargo Loading System (Township Adaption)**:
   - 3 distinct cargo bays requiring specific Martian resources (Crystals, Helium-3, Phyto-concentrate, Deuterium, Superconductors).
   - Premium glassmorphic interface showing player stock, cost to instantly purchase lacking cargo, or a trigger to produce resources locally.

3. **Pre-Launch Obstacles**:
   - 📡 **Navigation Calibration**: Crosshair alignment puzzle. **Supports mobile gyroscope/accelerometer**—tilt your phone to align, or use touch control buttons.
   - ⚛️ **Reactor Core Stabilization**: Precision timing minigame where the player clicks/taps as the plasma needle sweeps through the stable green sector.
   - ⚡ **Geomagnetic Storm**: Rapid-tap anomaly game to discharge static buildup. Gives `-0.5s` time reduction per tap.

4. **Launch & Cargo Delivery Loop**:
   - Cinematic launching animation with engine rumble, smoke, camera shake, and flame expansion.
   - 8-second real-time shuttle transit to the orbital station *Hermes*.
   - Cargo claim screen with random rewards (Components, Armor, Batteries) returned from the station.

---

## 📂 Project Structure
- `index.html` / `mars_shuttle_3d (1).html` — Main source code (HTML, CSS, JS with Three.js).
- `Задание_3_Визуальные_референсы.docx` — Word document containing generated AI references for artists (Shuttle on runway, frozen methane crystal).
- `Задание_4_ТЗ_загрузка_шаттла.docx` — Senior Business Analyst style technical specification (ТЗ) for developers.

---

## 🛠️ Tech Stack
- **Core**: HTML5, Vanilla JavaScript (ES6)
- **3D Render Engine**: Three.js (WebGL)
- **Styling**: Vanilla CSS3 (Custom properties, keyframes, backdrop-filter, flexbox, grid)
- **Audio**: Web Audio API (Synthesized oscillators, filters, custom gain nodes)

---

## 📱 Running on Mobile (iOS / Android)
For the mobile gyroscope to function, **iOS requires an HTTPS connection**.
- Open the live link in Safari/Chrome.
- Tap **"Activate Gyroscope"** during the Navigation Calibration stage.
- Accept the motion sensor permissions when prompted.
