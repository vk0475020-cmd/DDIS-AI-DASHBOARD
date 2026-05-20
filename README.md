# Deepfake & Misinformation Detection Intelligence System (DDIS)

A highly interactive, single-page web application designed to simulate AI-driven detection of deepfakes and misinformation. Built with a premium "cyberpunk/glassmorphism" user interface, this dashboard provides a visually engaging experience for analyzing images and text.

## Features

*   **Deepfake Image Analysis Simulation:** Interactive UI with drag-and-drop support, animated progress indicators, and visual overlays.
*   **NLP Misinformation Engine:** A client-side heuristic engine that analyzes text for manipulation signals (e.g., emotional loading, capitalization abuse, sourcing credibility) and generates contextual explanations based on a composite risk score.
*   **Dynamic Data Visualizations:** Utilizes the HTML5 Canvas API for interactive radial charts, confidence rings, and animated background elements (neural networks, holographic spheres).
*   **Fully Responsive UI:** A seamless experience across desktop and mobile devices, built entirely with vanilla web technologies.

## Tech Stack

*   HTML5
*   CSS3 (Glassmorphism, Cyberpunk Aesthetics, Animations)
*   Vanilla JavaScript (ES6+)
*   HTML5 Canvas API
*   Vite (for local development server)

## Getting Started

To run this project locally:

1.  Ensure you have Node.js installed.
2.  Clone this repository.
3.  Install dependencies:
    ```bash
    npm install
    ```
4.  Start the development server:
    ```bash
    npm run dev
    ```
    (Note: If port 8080 is blocked, Vite will typically try the next available port, or you can run `npm run dev -- --port 3000` to specify a port).

## Project Structure

The entire application logic, styles, and markup are self-contained within `neuro.html`, making it a pure, lightweight front-end demonstration.
