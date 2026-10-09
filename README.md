# WITHIN — An Atom Explorer

**WITHIN** is a single-file, interactive 3D web application that takes users on a visual journey through the architecture of matter across three distinct scales: atomic, nuclear, and subatomic (nucleon).

---

## Key Features

* **Multi-Scale Exploration:** Seamlessly transition across three chapters:
  1. **Atomic Scale ($\sim 10^{-10}\text{ m}$):** Explore neutral ground-state atoms (Hydrogen-1, Helium-4, Neon-20, Argon-40) with interactive electron shells and probabilistic clouds.
  2. **Nuclear Scale ($\sim 10^{-15}\text{ m}$):** Examine the dense atomic nucleus, packed with discrete protons and neutrons. Click or tap any nucleon to dive inside.
  3. **Nucleon Scale ($\sim 10^{-15}\text{ m}$):** Look inside individual protons ($uud$) and neutrons ($udd$) to visualize valence quarks and toggle dynamic gluon field interactions.
* **Interactive Controls:** 
  * Orbit freely by dragging/swiping.
  * Zoom via mouse wheel, pinch gestures, or on-screen buttons.
  * Isolate individual quantum shells or toggle 90% boundary layers.
  * Pause or resume cinematic motion and inspect performance telemetry in real time.
* **Zero Dependencies:** Built entirely with vanilla JavaScript and HTML5 Canvas 2D using depth-sorted perspective projection, requiring no external build tools or asset files.

---

## How to Run

Because `index.html` is completely self-contained with embedded styling and script logic, you do not need to install packages or configure a bundler.

1. Download or copy the `index.html` file.
2. Open the file directly in any modern web browser (Chrome, Safari, Firefox, Edge).

---

## Controls Reference

* **Orbit:** Click and drag (or touch and drag) anywhere on the canvas.
* **Zoom:** Scroll wheel, pinch gesture, or use the `+` / `−` buttons.
* **Stage Navigation:** Press keys `1`, `2`, or `3` (or click the bottom chapter buttons).
* **Pause / Play:** Press the `Spacebar` or click the pause button.
* **Reset Camera:** Press `R` or click the reset target button.
