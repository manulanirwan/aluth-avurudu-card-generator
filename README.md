# 🌞 Sinhala & Tamil New Year (Aluth Avurudu) Card Generator

A beautiful, light-weight, single-page web application built to help users create and download high-quality personalized greeting cards for the Sinhala and Tamil New Year. Developed entirely with pure vanilla frontend technologies, this tool integrates serverless client-side photo processing, custom multi-layered border structures, and a mathematically drawn traditional sun motif.

---

## 🚀 Features

* **Procedural Sun Motif Generator:** Renders an accurate, scalable traditional sun icon using a custom Canvas loop that programmatically builds a central solar core and twelve evenly distributed geometric ray paths.
* **Circular Portrait Clipping:** Securely handles device photo updates, center-crops the input to maintain aspect stability, and processes it into a sleek 170px radius circular display framework.
* **4 Culturally Rooted Preset Themes:** Swap out visual themes dynamically with pre-configured color matrices celebrating traditional Avurudu palettes:
  * **Suryan Gold:** Radiant gold trim accented by vibrant celebration orange tones.
  * **Erabadu Red:** Deep crimson red background rules paired with premium gold accents.
  * **Royal Teal:** Modern high-contrast deep teal borders highlighted by warm amber rays.
  * **Traditional Terracotta:** Earthy rustic clay tones matched with gold secondary lines.
* **Intricate Corner Border Elements:** Combines structural double-frame vector paths with loop-generated interlocking circular nodes at each perimeter junction for an authentic stationary aesthetic.
* **Smart Native Word Wrapping:** Monitors character updates via a continuous state tracker, instantly calculating substring lengths against width thresholds to position sentences across multiple canvas lines without clipping edges.
* **Instant PNG Exports:** Packages active canvas configurations instantly into a transparent browser-triggered download queue as a high-resolution `Sinhala_Tamil_NewYear_Card.png` file.
* **Blogger-Ready Sandboxed Layout:** Out-of-the-box CSS scoping shields the generator module from layout leakage, facilitating seamless integration inside external host structures like Blogger templates.

---

## 🛠️ Tech Stack

* **HTML5:** Semantic workspace layout, text forms, and the core pixel drawing wrapper (`<canvas>`).
* **CSS3:** Flexible template selection grids, device responsive media breakpoints, and smooth interface transition timers.
* **JavaScript (ES6+):**
  * `FileReader API` for isolated local asset reading without triggering data uploads or backend processes.
  * `HTML5 Canvas API` for dynamic pixel compilation sequences (`arc`, `lineTo`, `strokeRect`, `clip`, and text-wrap calculation blocks).

---

## 📦 Getting Started

This workspace requires no local compiler stacks, build routines, or development servers.

1. Clone this repository onto your workstation:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/aluth-avurudu-card-generator.git](https://github.com/YOUR_USERNAME/aluth-avurudu-card-generator.git)
