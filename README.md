# VB WebGPU Early Torus Prototype

<h2>Description</h2>
<p>Interactive WebGPU prototype that ray-marches nested tori and an optional spherical projection to demonstrate a “recursive toroidal hologram”: an energy-field of ~8k advected particles and a mock JWST early-galaxy sky are encoded to a torus-UV boundary texture each frame and then sampled back onto the toroidal shell.</p>

<h2>User Interface and Controls</h2>
<p>UI sliders expose R/r, tilt, child shift, smooth-union k, exposure, and recursion depth; toggles switch Sphere projection, Hologram mode (interior/throat view), JWST overlay, and energy field. HUD shows GPU + FPS; controls: WASD/mouse, Q/E (down/up), Shift (faster), O (auto-orbit), plus a simple audio heartbeat. Includes ten inline JWST mock points (z≈10.38–12.93) colored by redshift for illustrative seeding.</p> 

<h2>Run Instructions</h2>

### Run locally

This demo is a single HTML file, but the safest way to run it is from a local web server
(some browsers restrict `file://` access).

1. **Download the source** (Code ▸ Download ZIP) or `git clone` the repo.
2. **Start a local server** from the repo root:

   **Python 3 (any OS)**
   ```bash
   # from the repo folder
   python -m http.server 8080

Open the sim in your browser:

http://localhost:8080/[FILENAME].html

Example: VB_WebGPU_Early_Torus_Prototype.html

Tip: Double-clicking the HTML may work on some setups, but a local server avoids CORS/security issues.

### Browser support

Requires a modern browser with WebGPU (Chrome/Edge latest recommended with hardware acceleration on).
If you see “WebGPU not available,” try updating your browser or switching to Chrome/Edge.


## Safety Notice

⚠️ **Visual Patterns Disclaimer**  
This simulation generates dynamic interference and holographic patterns.  
While safe under normal use, some individuals may experience mild visual discomfort if viewed for extended periods.  
It is recommended to take breaks and avoid prolonged continuous viewing.

---

### VB Early Toroidal Prototype Simulation

This project is licensed under the Apache 2.0 License – see the [![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](LICENSE) file for details.


