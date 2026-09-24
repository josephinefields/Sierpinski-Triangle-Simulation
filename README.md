# Sierpinski Triangle Web Migration Project

An interactive web application that visualizes the recursive geometry of the Sierpinski Triangle. This repository modernizes an academic project originally built during my freshman year at the University of South Carolina.

##  Live Resources

* **Live Site:** [N/A]
* **[Repository URL:](https://github.com/josephinefields/Sierpinski-Triangle-Simulation/tree/main)**

---

##  The Tech Stack

* **Frontend:** JavaScript (ES6+), HTML5, CSS
* **Backend:** None
* **DevOps / Hosting:** GitHub Pages

---

## Engineering Architecture & Documentation

This project follows professional software engineering documentation standards. Technical trade-offs, system constraints, and major pivots are chronologically tracked below:

1. **[01 Problem Statement & System Constraints](https://github.com/josephinefields/Sierpinski-Triangle-Simulation/blob/main/Documentation/01%20Problem%20Statement%20%26%20System%20Constraints.md)**: Defining system boundaries, business rules, and user requirements.
2. **[02 Architecture Decisions Log](https://github.com/josephinefields/Sierpinski-Triangle-Simulation/blob/main/Documentation/02%20Architecture%20Decisions%20Log.md)**: The master log indexing technical choices and rejected options.
3. **[03 Implementation Log](https://github.com/josephinefields/Sierpinski-Triangle-Simulation/blob/main/Documentation/03%20Implementation%20Log.md)**: Chronological engineering diary tracking development phases and bugs.
4. **[04 Project Retrospective & Technical Debt Review](https://github.com/josephinefields/Sierpinski-Triangle-Simulation/blob/main/Documentation/04%20Project%20Retrospective%20%26%20Technical%20Review.md)**: A transparent post-mortem analyzing system performance and technical debt.

---

## Key Features & Engineering Deliverables

* **Browser-Based Math Rendering:** Uses a JavaScript recursion loop to draw triangles onto an HTML5 Canvas.
* **Separation of Architecture:** Keeps the fractal math logic independent from the UI layout.
* **No Local Setup Required:** Moves the logic from a local Eclipse Java script to a public link, so anyone can run the app without needing an IDE.

---

## Core System Logic / Algorithm Overview

The visual layout runs on a straightforward divide-and-conquer recursion loop:

1. **Gather Inputs:** The program reads user preferences (like mac recursion depth and custom colors) from the sidebar controls.
2. **Calculate Points:** Starting with a single large triangle, the code calculates the midpoints of the sides to break it down into smaller sub-triangles.
3. **Draw to Screen:** The script wipes the canvas and draws the newly calculated lines to update the frame.

---

##  Local Setup & Execution

1. Copy the **[Repository URL](https://github.com/josephinefields/Sierpinski-Triangle-Simulation)**.

2. Run the clone command in your terminal:
   ```bash
   git clone (Repository URL)
   ``` 
   
3. Move into the project directory:
   ```bash
   cd Sierpinski-Triangle Simulation
   ```
   
4. Double-click `index.html` to run the app in your browser.
