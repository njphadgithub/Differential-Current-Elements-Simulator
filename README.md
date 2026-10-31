# Force Between Differential Current Elements - 3D Interactive Simulation

A self-contained, browser-based 3D educational simulation designed for undergraduate engineering electromagnetics instruction. Built with **Three.js** and **Tailwind CSS**, this interactive application visualizes the mutual magnetic forces between two differential current elements using the Biot-Savart Law and Ampère's Force Law in real time.

Developed for academic use at the **Government College of Engineering, Chh. Sambhajinagar**.

## Creator
* **Dr. Nitin Phadkule**
* **Department:** Electronics and Telecommunication Engineering
* **Institution:** Government College of Engineering, Chh. Sambhajinagar
* **Email:** phadkule@geca.ac.in

---

## Key Features

1. **Mutual Differential Electromagnetic Calculations:** Computes the differential magnetic field and force interactions between two current-carrying elements:
   * **Element 1 & Element 2:** Configurable currents ($I_1, I_2$) and differential lengths ($dL_1, dL_2$).
   * **Spatial Positions:** Independent 3D position coordinates $[x, y, z]$ for both elements.
   * **Governing Equations:** 
     * $d\mathbf{B}_1 = \frac{\mu_0 I_1 \, d\mathbf{L}_1 \times \mathbf{\hat{R}}}{4\pi R^2}$
     * $d\mathbf{F}_2 = I_2 \, d\mathbf{L}_2 \times d\mathbf{B}_1$
2. **Configuration Presets:** Instant quick-toggle presets for:
   * **Parallel (Same Direction):** Side-by-side conductors with currents flowing in the same direction, demonstrating mutual attractive differential forces.
   * **Parallel (Opposite Direction):** Side-by-side conductors with currents flowing in opposite directions, demonstrating mutual repulsive differential forces.
   * **Custom Manual Setup:** Full user control over positions, lengths, and current magnitudes.
3. **Interactive 3D Viewport (WebGL):** 
   * Fully rotatable, zoomable, and pannable 3D coordinate frame.
   * Color-coded vector annotations:
     * 🔴 **Element 1** ($I_1 d\mathbf{L}_1$) (Red)
     * 🔵 **Element 2** ($I_2 d\mathbf{L}_2$) (Blue)
     * 🔵 **Force on Element 2** ($d\mathbf{F}_2$) (Cyan)
     * 🟣 **Force on Element 1** ($d\mathbf{F}_1$) (Purple)
     * 🟡 **Separation Vector** ($\mathbf{R}$) (Amber)
   * High-visibility bottom legend and independent checkboxes to toggle force display options.

---

## Technical Stack

* **HTML5 / CSS3** (Single-file self-contained architecture)
* **Tailwind CSS** (Modern styling and responsive layout)
* **Three.js (r128)** (High-performance 3D WebGL rendering engine)

---

## How to Run Locally

1. Clone or download this repository.
2. Save the application code as `index.html`.
3. Double-click `index.html` to open it directly in any modern web browser (Chrome, Edge, Firefox, Safari)—no local server installation required!

---

## License

This educational tool is open-source and intended for academic instruction, laboratory demonstrations, and student self-study in engineering electromagnetics.