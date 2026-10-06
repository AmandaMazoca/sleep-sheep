# 🐑 Sheep Counter - Relaxing Night Game

A calm, cozy, and relaxing HTML5 Canvas mini-game designed to help users unwind before bed. Tap or click to help sheep jump smoothly over the fence under a starry night sky.

> 🚀 **Live Demo:** [Click here to play](https://AmandaMazoca.github.io/Sleep-sheep/) 

---

## 🌟 Features

- **Cozy & Minimalist Aesthetics:** Dynamically generated twinkling starry sky, illuminated moon, and gentle night pasture.
- **Smooth Physics Engine:** Float-like parabolic jumps crafted for a stress-free and easy gameplay experience.
- **Synthesized Audio:** Built-in ambient sound effects using the Web Audio API (jump sounds, sheep bleats, and success chimes) without external audio file dependencies.
- **Relaxation First:** Welcome screen prompting users to lower screen brightness before starting.
- **Fully Responsive & Standalone:** Works seamlessly on mobile devices and desktop browsers without installation or external frameworks.

---

## 🛠️ Tech Stack

- **HTML5 Canvas:** Custom 2D rendering loop (`requestAnimationFrame`) for smooth 60fps physics and animations.
- **JavaScript (ES6+):** Pure vanilla JavaScript for state management, physics calculations, and dynamic audio synthesis.
- **Tailwind CSS:** Modern styling for responsive UI overlays, typography, and modal dialogs.
- **Web Audio API:** Real-time audio generation for crisp, lightweight sound effects.

---

## 🤖 AI-Assisted Development Process

This project served as my first hands-on experience with **AI-Assisted Development (Vibe Coding)** and prompt engineering.

### Key Learnings & Iterations:
1. **Conceptualization to Execution:** Translated a high-level creative idea (a dark starry sheep-counting game) into a functional web application in minutes.
2. **UX & Physics Refinement:** Identified friction points during testing—such as strict jump hitboxes—and instructed the AI to adjust gravity (`0.32`) and jump impulse (`-10.5`) to make the game exceptionally easy and relaxing.
3. **Localization & Onboarding:** Added a dim-brightness welcome overlay and translated the full interface into English for international reach.

---

## 🚀 How to Run Locally

Since this project relies entirely on browser-native technologies, no complex build process is required!

1. **Clone the repository:**
   ```bash
   git clone [https://AmandaMazoca.github.io/Sleep-sheep/.git](https://AmandaMazoca.github.io/Sleep-sheep/.git)
