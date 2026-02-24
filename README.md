# Hi, I'm Nathan

Physicist. I build simulations of physical systems that interest me—compressible flow, orbital mechanics, relativistic dynamics, thermal convection, multi-body problems. Aerospace keeps pulling me in.

Most of these projects started as research work or academic curiosity where version control wasn't a priority. I've since cleaned them up and posted them here to track progress and share the work.

---

## Projects

**Rayleigh-Bénard Convection Simulator** — Lattice Boltzmann solver for turbulent thermal convection cells.
`C++` `React`

**Shock Tube Compressible Flow Simulator** — 1D Euler solver with HLLC and exact Riemann solvers, MUSCL-Hancock reconstruction. Used entropy-stable flux methods from Ismael and Roe's research in 2009. Validated against Toro test suite (<3% error). Monte Carlo uncertainty propagation for sensor noise effects.
`C++` `React`

**Orbital Dynamics & Bifurcation Analysis Simulator** — Schwarzschild geodesic integrator with Keplerian comparison mode for weak-field validation. Stability basin mapping, perihelion precession analysis. Added classical propagator with J2 perturbation for cross-referencing curved vs flat spacetime.
`Python` `React`

**Orbital Dynamics & Bifurcation Analysis (Rotating Black Hole) Simulator** — All the same features as "Orbital Dynamics & Bifurcation Analysis" project but written with a C++ backend to compute 3D orbits using a rotating black hole. All equations of motion for the 3D model are derived from the Kerr spacetime metric. 
`C++` `React`

**RelNav-MC** — RPO simulator using Clohessy Wiltshire equations with circular ref. orbits. Trajectories controlled with glideslope velocity limiting, waypoint generation, EKF measuring, and LQR optimal control. Monte Carlo uncertainty dispersion amongst initial states along with thrust magnitude and orientation. Performance envelope showcasing success/failure trials, optimal total dv, and dominant failure modes.
`C++` `React`

**Orbital Maneuver Calculator** — Computes Hohmann, bi-elliptic, and phasing transfer trajectories with ΔV budgeting. Lambert solver for two-impulse targeting. Visualization tool for transfer geometry and ΔV vs time-of-flight tradeoffs.
`Python`

**Fragment Cloud Dispersion Simulator** — Trajectory propagation for debris and dispersion analysis with atmospheric drag modeling. Computes expanding lethality envelopes and Monte Carlo analysis to comptue hit probability contours against target planes.
`Python` `React`

**Propellant Tank Blowdown Model** — Lumped-parameter transient model for pressurized gas systems. Isentropic expansion with choked-flow discharge dynamics. Monte Carlo sensitivity analysis on discharge coefficient and initial conditions.
`Python`

---

## Tech Stack

```
Languages      C/C++, Python, MATLAB, React.js, Mathematica
Libraries      NumPy, SciPy, Eigen, Cantera
Tools          Git, CMake, Linux, Bash
```

---

## Interests

- Compressible fluid dynamics
- GNC
- Nonlinear dynamics and chaos

---

## Contact

[njwleeph@gmail.com](mailto:njwleeph@gmail.com) · [LinkedIn](https://linkedin.com/in/nathanjwlee)

---

*Open to any engineering roles with interest towards simulation, propulsion, GNC, and systems engineering roles.*
