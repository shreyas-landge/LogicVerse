# LogicVerse
### Interactive Digital Electronics Simulator

<p align="center">
  <strong>Explore. Design. Simulate. Understand Digital Logic.</strong>
</p>

<p align="center">
  A web-based platform for learning and visualizing digital electronics through Boolean algebra, logic gates, circuit design, and interactive simulations.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="MIT License"/>
</p>

---

## Overview

**LogicVerse** is an interactive digital electronics simulator designed to make digital logic concepts easier to understand through visualization and experimentation.

It provides tools to analyze Boolean expressions, generate truth tables, simplify logic functions using Karnaugh maps, and construct digital circuits using interactive logic gates.

The platform also introduces the internal working of digital systems through a layered simulation, progressing from semiconductor physics to logic gates, combinational circuits, and CPU operations.

## Features

### Boolean Expression Analyzer
- Analyze Boolean expressions.
- Generate truth tables.
- Identify minterms and maxterms.
- Generate minimized SOP and POS expressions.

### Karnaugh Map Solver
- Visualize Karnaugh maps for 2, 3, and 4 variables.
- Simplify Boolean functions.
- Understand grouping and logic minimization.

### Interactive Circuit Builder
- Build circuits using drag-and-drop components.
- Use AND, OR, NOT, XOR, NAND, NOR, and XNOR gates.
- Connect inputs and outputs.
- Observe circuit behavior through simulation.

### From Silicon to Code

Explore digital systems through six interactive layers:

| Layer | Topic |
|---|---|
| 01 | Semiconductor Physics |
| 02 | MOSFET Transistor |
| 03 | Logic Gates |
| 04 | Combinational Circuits |
| 05 | CPU Components |
| 06 | Instruction Execution |

## Learning Objectives

- Understand number systems and Boolean algebra.
- Analyze Boolean functions using truth tables.
- Learn SOP, POS, minterms, and maxterms.
- Simplify Boolean expressions using Karnaugh maps.
- Explore combinational circuit concepts.
- Understand the relationship between transistors, logic gates, and digital systems.

## Technology Stack

| Technology | Purpose |
|---|---|
| HTML5 | Structure |
| CSS3 | Styling and layout |
| JavaScript | Logic and simulation |
| Git | Version control |
| GitHub | Source code hosting |

## Getting Started

### Prerequisites

- Modern web browser
- Visual Studio Code
- Live Server extension (recommended)

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/YOUR_USERNAME/LogicVerse.git
```

**2. Navigate to the project directory**

```bash
cd LogicVerse
```

**3. Run the application**

Open `index.html` in your browser or use the Live Server extension in Visual Studio Code.

To access the extended simulator, open:

```text
full-simulator/index.html
```

## Project Structure

```text
LogicVerse/
├── index.html
├── style.css
├── app.js
├── logic.js
├── circuit.js
├── kmap.js
├── full-simulator/
│   ├── index.html
│   ├── style.css
│   ├── main.js
│   ├── simulator.js
│   ├── utils.js
│   └── js/
└── README.md
```

*The structure is illustrative. Update it to match the actual files in your repository.*

## Future Enhancements

- Number system conversion tools.
- Interactive flip-flop simulations.
- Counter and shift-register demonstrations.
- Additional combinational circuit modules.
- Guided digital electronics experiments.

## Academic Information

| Detail | Information |
|---|---|
| Project | LogicVerse – Interactive Digital Electronics Simulator |
| Subject | Foundations of Intelligent Digital Systems (FOIDS) |
| Program | B.Tech – Artificial Intelligence and Data Science |
| Institution | Vishwakarma Institute of Technology, Pune |

## Credits and License

This project is based on the open-source [Logic Simulator](https://github.com/christianad11/logic-simulator) by Christian Abou Daher.

The original MIT License and attribution must be retained. LogicVerse includes project-level customization and presentation changes.

---

<p align="center">
  <strong>LOGICVERSE</strong><br/>
  Making Digital Electronics Interactive.
</p>