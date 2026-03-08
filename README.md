# ⚗️ TitriLab — Advanced Chemistry Titration Simulator

**TitriLab** is a comprehensive, interactive browser-based chemistry laboratory simulator designed to help students, educators, and science enthusiasts visualize and calculate titration experiments. 

Built entirely with vanilla HTML, CSS, and JavaScript, it offers a beautifully animated virtual lab environment coupled with real-time data graphing, automatic equivalence point detection, and a built-in educational hub.

### ✨ Key Features

* **🧪 Multi-Mode Simulations**:
  * **Acid-Base**: Choose from 8 acids, 6 bases, and 6 indicators. Supports strong/weak and polyprotic combinations.
  * **Redox**: KMnO₄, K₂Cr₂O₇, and Cerimetry with dynamic potential (E in mV) tracking.
  * **Advanced & Instrumental**: Complexometry (EDTA/Water Hardness), Iodometry, Argentometry, and Conductometry.
* **📊 Real-Time Interactive Graphing**: Generates live titration curves (pH, E(mV), pMetal, or Conductance) on an HTML5 canvas as titrant is added. Graphs can be exported and downloaded as PNGs with a single click.
* **🥽 Immersive Virtual Lab**: Features animated burette drops, a rotating magnetic stirrer, dynamic liquid colors that react accurately to chemical indicators, and live digital meter readouts.
* **🧮 Smart Calculator**: Built-in calculation modules that automatically pull data from your current simulation to solve for Molarity, Equivalence Point, Henderson-Hasselbalch pH, Buffer Capacity, the Nernst Equation, and Ksp.
* **📚 Integrated Learning Hub**: Comprehensive built-in pages for **Theory** and step-by-step **Lab Procedures** for all supported reactions.
* **🌗 Modern UI/UX**: Fully responsive, accessible design featuring automatic Light/Dark mode switching and ambient background music for a relaxing study session.

### 🛠️ Tech Stack
* **Frontend**: HTML5, CSS3 (Custom Properties, CSS Grid/Flexbox, Keyframe Animations), Vanilla JavaScript (ES6+).
* **Graphics**: HTML5 `<canvas>` API for smooth mathematical curve rendering and inline SVG for crisp lab equipment visuals.
* **Zero Dependencies**: The entire application is completely self-contained in a single file without the need for external frameworks or libraries (no React, Vue, or npm required).

### 🚀 Who is this for?
* **Educators & Teachers**: Use it as a visual aid to demonstrate equivalence points, buffer regions, and indicator selection.
* **Students**: Perfect for pre-lab preparation, allowing you to practice finding endpoints and running calculations before handling hazardous chemicals.
