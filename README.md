<div align="center">
  
# 🌌 Aether :: Quantum Lab
### An Interactive, Visually Stunning Physics-Grade Web Simulator

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/)
[![JavaScript](https://img.shields.io/badge/Vanilla_JS-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/)
[![Three.js](https://img.shields.io/badge/Powered_by-Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white)](https://threejs.org/)
[![Chart.js](https://img.shields.io/badge/Data-Chart.js-FF6384?style=for-the-badge&logo=chart.js&logoColor=white)](https://www.chartjs.org/)

*Stripping away intimidating calculus, Aether translates the profound laws of quantum mechanics into pure, real-time interactivity designed to "wow".*

</div>

---

## ✨ Overview

**Aether Quantum Lab** is an interactive web-based visualization environment created to help users intuitively understand quantum mechanics. Through a modern, "glass-morphic" dark-mode interface, Aether provides real-time playgrounds for six major physical phenomena. 

Unlike standard textbook diagrams, Aether continuously computes live probabilities, vector interactions, and localized wave functions directly in your browser. Every module features an integrated **Concept Reference Guide** to help connect the stunning visual physics to their theoretical foundations.

---

## 🛠️ Simulation Modules

| Module | Description | Core Interactivity |
| :--- | :--- | :--- |
| **🛡️ Quantum Tunneling** | Watch wave-particle duality allow particles to pierce seemingly impenetrable solid matter thresholds over time. | Drag sliders for *Energy*, *Barrier Width*, and *Barrier Height* to manipulate exactly how much transmission probability leaks through. |
| **🔮 Bloch Sphere** | Explore true geometric representations of single unmeasured qubits in a mathematically faithful 3D subspace. | Apply **X, Y, Z, Hadamard (H), Phase (S), and T gates**. Freely drag the sphere to explore absolute state measurements ($|0\rangle, |1\rangle, \|+\rangle$) alongside dynamic phase sliders mapping $\theta$ and $\phi$. |
| **🌊 Double Slit** | Observe the quintessential experiment of the quantum measurement problem. | Adjust wavelength and slit distance metrics to construct interference fringes. Throw the **Detector Switch** to collapse the wave function and destroy the fringes! |
| **📦 Particle in a Box** | Dive into an infinite potential well and examine strict zero-point energies and probability graphs. | Expand the bounding walls (Box Width) and ratchet up the quantum number ($n$) to dynamically generate beautiful standing probability waves. |
| **⚛️ Hydrogen Orbitals**| Step out of the simplistic planetary Bohr model and explore cross-sections of real electron clouds. | View varying spherical-harmonic physical approximations for 1s, 2s, 2p, and 3d orbital energy levels. |
| **🔗 Entanglement** | Reproduce Einstein's "Spooky Action at a distance." | Establish paired systems between distant limits. Measuring Qubit A's superposition sends a shockwave that instantly forces an answer upon Qubit B without communication lag. |

---

## 💻 Tech Stack & Architecture

This application operates **entirely client-side**, requiring absolutely no backend processing capability to render high-level simulations.

- **🎨 UI / Aesthetics**: Fully custom CSS architecture implementing futuristic dark themes, neon highlighting, and elegant DOM transition animations.
- **📈 Data Computation**: Utilizes `Chart.js` for extremely high frame-rate rendering of the Schrodinger partial differential equations and wave bounds.
- **🌐 3D Rendering**: Engineered with `Three.js` (WebGL) to instantly construct and animate quaternion-based Qubit states mapped accurately through physical 3D space.

## 🚀 Getting Started

**Installation isn't necessary.** Because Aether runs completely within the browser engine, you can immediately begin experiencing the lab.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/sanjaykannan2007-max/Aether.git
   ```
2. **Access the Application:**
   Open `quantum_tunneling_simulator_fixed.html` in any modern web browser (Chrome, Edge, Firefox, Safari).

---

<div align="center">
  <i>Developed to make quantum physics beautiful.</i>
</div>
