---
permalink: /code/
title: "Code"
author_profile: true
---

Scotty
======
**[beam-tracing/Scotty](https://github.com/beam-tracing/Scotty)**: a beam-tracing code for
Doppler backscattering synthetic diagnostics, written in Python.

* Traces the microwave beam through the plasma and computes the backscattered signal, so that DBS
  measurements can be interpreted quantitatively.
* Version 4 is a major rewrite, of which I am one of the main developers. It supports Cartesian or
  cylindrical geometry, has a modular beam solver, and stores its results as an `xarray.DataTree`.
* Reference: V. H. Hall-Chen, F. I. Parra and J. C. Hillesheim,
  [*Plasma Phys. Control. Fusion* **64**, 095002 (2022)](https://doi.org/10.1088/1361-6587/ac57a1).

Current work on Scotty
------
* **Analytic benchmark:** Cartesian-geometry beams compared with the exact O-mode solution for a
  2D linear density layer ([pull request](https://github.com/beam-tracing/Scotty/pull/173)).
* **Cyclotron resonance:** robust handling of beams that approach the electron cyclotron resonance.

Cartesian Scotty (2024–2025)
======
For my final-year thesis I wrote *Cartesian Scotty*, a Python library that extends Scotty's beam
model of DBS to non-axisymmetric magnetic geometries. It was validated in vacuum, against the
analytic 2D linear-layer solution, and against Scotty on tokamak data. I then used it for
preliminary DBS simulations in a W7-X-like stellarator equilibrium generated with
[DESC](https://github.com/PlasmaControl/DESC).

Other projects
======
My other public code is on [GitHub](https://github.com/eduardwikarta).
