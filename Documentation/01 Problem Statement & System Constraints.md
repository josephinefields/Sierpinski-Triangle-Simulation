## 1. Context & Domain Background

* **Target Audience:** Portfolio visitors and anyone interested in interactive Sierpinski Triangle visualizations.
* **Legacy System / Baseline:** A Java 17 compiled script originally written during my freshman year at the University of South Carolina for an Algorithmic Design II class. The math worked, but running it required an IDE like Eclipse.

## 2. Core Functional Requirements

* **REQ-1 (Fractal Generation):** The application must compute and draw a Sierpinski Triangle based on midpoint subdivision.
* **REQ-2 (Variable State):** The user must be able to change the recursion depth levels dynamically using a frontend slider.
* **REQ-3 (Visual Configuration):** The system must support real-time color scheme changes without breaking the shape's coordinate layouts.

## 3. Non-Functional Constraints (System Boundaries)

* **Portability & Access:** The application must run entirely in a standard mobile or desktop web browser. Visitors must not be forced to download executables, run an IDE, or configure a local runtime.
* **Performance Limits:** Dynamic adjustments must render instantly on an HTML5 Canvas.
* **Cost & Maintenance:** The software configuration must rely strictly on vanilla client-side files (HTML/CSS/JS) to allow permanent, zero-cost hosting via GitHub Pages.

## 4. Definition of Success

* The system is complete when the repository hosts an interactive web application where users can adjust fractal depth levels smoothly in real time.
