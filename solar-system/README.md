# Procedural 3D Solar System

This is a self-contained 3D Solar System simulation built with Three.js.

## Features
- **Procedural Textures**: Planets and the Sun have textures generated on the fly using HTML5 Canvas, ensuring no missing asset errors.
- **Accurate-ish Orbits**: Relative speeds and distances are scaled for visualization.
- **Interactive**: Use your mouse to rotate, zoom, and pan around the solar system.
- **Saturn's Rings**: Visualized with a custom gradient texture.
- **Starfield**: A randomly generated background of stars.

## How to Run

Because this project uses ES Modules (`import ... from ...`), modern browsers require it to be served over HTTP/HTTPS, not the `file://` protocol.

### Option 1: VS Code Live Server (Recommended)
1.  Install the **Live Server** extension in VS Code.
2.  Right-click on `index.html`.
3.  Select **Open with Live Server**.

### Option 2: Python Simple HTTP Server
If you have Python installed, you can run a simple server from this directory:

```bash
# Run this in the terminal inside the 'solar-system' folder
python -m http.server
```

Then open `http://localhost:8000` in your browser.

### Option 3: Node.js http-server
If you have Node.js installed:

```bash
npx http-server .
```
