# Hi, I'm Nathan

Physicist. I build simulations of physical systems that interest me—compressible flow, orbital mechanics, relativistic dynamics, thermal convection, multi-body problems. Aerospace keeps pulling me in.

Most of these projects started as research work or academic curiosity where version control wasn't a priority. I've since cleaned them up and posted them here to track progress and share the work.

---

## Projects

**Rayleigh-Bénard Convection Simulator** — Lattice Boltzmann solver for turbulent thermal convection up to Reynolds numbers of up to 10^4. Smagorinsky LES for subgrid turbulence. Real-time browser visualization with live Nusselt and Reynolds tracking.
`C++` `React`

**Shock Tube Compressible Flow Simulator** — 1D Euler solver with HLLC and exact Riemann solvers, MUSCL-Hancock reconstruction. Also utilized entropy-stable flux methods from Ismael and Roe's research in 2009. Validated against Toro test suite (<3% error). Monte Carlo uncertainty propagation for sensor noise effects.
`C++` `React`

**Orbital Dynamics & Bifurcation Analysis Simulator** — Schwarzschild geodesic integrator with Keplerian comparison mode for weak-field validation. Stability basin mapping, perihelion precession analysis. Added classical propagator with J2 perturbation for cross-referencing curved vs flat spacetime. Utilizes a non-moving black hole.
`Python` `React`

**Orbital Dynamics & Bifurcation Analysis (Rotating) Simulator** — All the same features as "Orbital Dynamics & Bifurcation Analysis" project but written with a C++ backend to compute 3D orbits using a rotating black hole. All equations of motion for the 3D model are derived from the Kerr spacetime metric, and currently brainstorming how to perform nonlinear analysis on the now 3D system. 
`C++` `React`

**RelNav-MC** — Spacecraft proximity operations simulator using Clohessy-Wiltshire relative motion. Monte Carlo dispersion analysis for approach corridor compliance. Glideslope guidance and LQR optimal control for rendezvous trajectory tracking.
`C++` `React`

**Orbital Maneuver Calculator** — Computes Hohmann, bi-elliptic, and phasing transfer trajectories with ΔV budgeting. Lambert solver for two-impulse targeting. Visualization tool for transfer geometry and ΔV vs time-of-flight tradeoffs.
`Python`

**Fragment Cloud Dispersion Simulator** — Trajectory propagation for debris and dispersion analysis with atmospheric drag modeling. Computes expanding lethality envelopes and Monte Carlo analysis to comptue hit probability contours against target planes.
`Python` `React`

**Propellant Tank Blowdown Model** — Lumped-parameter transient model for pressurized gas systems. Isentropic expansion with choked-flow discharge dynamics. Monte Carlo sensitivity analysis on discharge coefficient and initial conditions.
`Python`

---

## Currently Building

**Solar System Music Box** — An orrery that plays music. Each planet triggers a note when it crosses a certain point in its orbit. Exploring the tension between astronomical accuracy and musical coherence—real orbital periods create generative ambient polyrhythms, while tuned resonances (like the Galilean moons' 4:2:1 Laplace resonance) allow actual melodies. My goal is to have it play the Interstellar theme.

---

## Tech Stack

```
Languages      C/C++, Python, MATLAB, JavaScript, Mathematica
Libraries      NumPy, SciPy, Eigen, Cantera
Tools          Git, CMake, Linux, Bash
```

---

## Interests

- Compressible flow and gas dynamics
- Spacecraft trajectory design and GNC
- Nonlinear dynamics and chaos
- Numerical methods for PDEs

---

## Contact

[njwleeph@gmail.com](mailto:njwleeph@gmail.com) · [LinkedIn](https://linkedin.com/in/nathanjwlee)

---

*Open to any engineering roles with interest towards simulation, propulsion, GNC, and systems engineering roles.*
