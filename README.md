# Aura Engine 2.2

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Version](https://img.shields.io/badge/version-2.2-blue.svg)](https://github.com/pgspears/aura)
[![Status](https://img.shields.io/badge/status-active-brightgreen.svg)](https://github.com/pgspears/aura)
[![Tech](https://img.shields.io/badge/tech-HTML%20%7C%20CSS%20%7C%20JS-orange.svg)](https://github.com/pgspears/aura)

A browser-based generative art studio for creating beautiful, dynamic motion art. Paint with living particles, sculpt with physics, and record your creations, all within a single HTML file.

---

<p align="center">
  <img src="https://raw.githubusercontent.com/pgspears/aura/main/aura_demo.gif" alt="Aura Engine in action" width="800"/>
</p>

## ✨ Live Demo

Experience Aura Engine directly in your browser. No installation required.

**[➡️ Launch Aura Studio](https://pgspears.github.io/aura/)**

## 🚀 Introduction

Aura is a digital art tool that transforms your mouse strokes into dynamic, physics-based animations. It's not a traditional frame-by-frame animation app; instead, it's a creative instrument where you set systems in motion. The goal is to make creating complex, beautiful motion art feel as intuitive and playful as painting on a canvas.

This entire application—including the physics engine, GUI, and rendering logic—is self-contained in a single HTML file, demonstrating the power of modern web technologies with zero external dependencies.

## 🌟 Features

-   **GPU-Accelerated Canvas:** Smooth, high-performance rendering using the HTML5 Canvas API.
-   **Multiple Brush Engines:**
    -   **Swarm:** A classic particle burst for nebulas and energy effects.
    -   **Flow:** Simulates thick, smoke-like or ink-in-water effects.
    -   **Growth:** Generatively creates branching, vine-like structures.
    -   **Sparks:** A crackling, physics-based brush perfect for fireworks and impacts.
-   **Interactive Physics:**
    -   **Mouse Force Field:** Attract or repel particles with your mouse.
    -   **Global Gravity:** Apply a constant downward force to all particles.
-   **Live GUI Controls:** A clean, responsive panel to tweak every parameter in real-time.
-   **Built-in Demos:** Launch one of several pre-scripted animations to showcase the physics engine.
-   **In-Browser Video Recording:** Record your creations as high-quality `.webm` video files directly in the browser, with the option to include the GUI.
-   **Screenshot Export:** Instantly save a high-resolution `.png` of your art.

## 🛠️ Usage

Simply open the [Live Demo](https://pgspears.github.io/aura/) link in a modern web browser (Chrome, Firefox, Edge, Safari are recommended).

Alternatively, you can run it locally by downloading the `index.html` file and opening it in your browser.

## 💻 Technology Stack

This project is a demonstration of what can be achieved with a minimal stack, using only the core technologies of the web:

-   **HTML5:** For the structure and GUI elements.
-   **CSS3:** For all styling, layout (Flexbox), and the dark theme.
-   **JavaScript (ES6+):** For the entire application logic, including the physics engine, particle system, and rendering loop.
-   **Web APIs:**
    -   **Canvas API:** For 2D rendering.
    -   **MediaRecorder API & getDisplayMedia API:** For native, in-browser screen and tab recording.

**No external libraries or frameworks are used.**

## 🎨 GUI Controls Guide

| Control              | Type      | Function                                                              |
| -------------------- | --------- | --------------------------------------------------------------------- |
| **Record Video**     | Button    | Starts/stops recording. Prompts for screen/tab permission.            |
| **Record Full UI**   | Checkbox  | If checked, records the entire window, including the GUI.               |
| **Screenshot/Clear** | Buttons   | Saves a PNG of the canvas or clears all particles.                      |
| **Load Demo**        | Dropdown  | Loads a pre-scripted physics and particle demonstration.                |
| **Brush Select**     | Dropdown  | Switches between different brush engines (Swarm, Flow, etc.).           |
| **Count**            | Slider    | The number of particles spawned per frame while painting.               |
| **Lifespan**         | Slider    | How long particles live before fading away.                           |
| **Speed**            | Slider    | The initial velocity of spawned particles.                            |
| **Radius**           | Slider    | The size of the particles.                                            |
| **Mouse Force Field**| Checkbox  | Activates a physics effector that follows the mouse.                  |
| **Mouse Strength**   | Slider    | The power of the mouse effector. Positive is attraction, negative is repulsion. |
| **Global Gravity**   | Checkbox  | Applies a constant downward pull on all particles.                      |
| **Gravity Strength** | Slider    | The strength of the global downward gravity.                          |
| **Color Select**     | Dropdown  | Switches between different color harmonies for the particles.           |
| **Bloom/Vignette**   | Checkboxes| Toggles post-processing visual effects.                               |
| **Trail Length**     | Slider    | Controls how quickly the canvas fades, creating longer or shorter trails. |

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/pgspears/aura/issues).

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## 📜 License

Distributed under the MIT License. See `LICENSE.md` for more information.

---

**© 2025 Accelerate Solutions, LLC**

*Conceptualized and developed in collaboration with Google's Gemini.*
