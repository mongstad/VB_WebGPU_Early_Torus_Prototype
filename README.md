# VB WebGPU Early Torus Prototype

<h2>Description</h2>
<p>Interactive WebGPU prototype that ray-marches nested tori and an optional spherical projection to demonstrate a “recursive toroidal hologram”: an energy-field of ~8k advected particles and a mock JWST early-galaxy sky are encoded to a torus-UV boundary texture each frame and then sampled back onto the toroidal shell.</p>

<h2>User Interface and Controls</h2>
<p>UI sliders expose R/r, tilt, child shift, smooth-union k, exposure, and recursion depth; toggles switch Sphere projection, Hologram mode (interior/throat view), JWST overlay, and energy field. HUD shows GPU + FPS; controls: WASD/mouse, Q/E (down/up), Shift (faster), O (auto-orbit), plus a simple audio heartbeat. Includes ten inline JWST mock points (z≈10.38–12.93) colored by redshift for illustrative seeding.</p> 

<h2>Run Instructions</h2>
<p>Run locally in Chrome/Edge 113+ with WebGPU; no server required</p>

## License
This project is licensed under the Apache 2.0 License – see the [![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](LICENSE) file for details.

<footer style="margin:20px; font-size:12px; color:#94a3b8; text-align:center; opacity:0.8;">
  <h3>Safety Notice ⚠️</h3>
  <p><strong>Visual Patterns Disclaimer</strong><br>
  This simulation generates dynamic interference and holographic patterns.
  While safe under normal use, some individuals may experience mild visual discomfort if viewed for extended periods.<br>
  It is recommended to take breaks and avoid prolonged continuous viewing.</p>

  <p class="small">VB Early Toroidal Prototype Simulation<br>
  This project is licensed under the Apache 2.0 License – see the [![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](LICENSE) file for details.
</footer>

