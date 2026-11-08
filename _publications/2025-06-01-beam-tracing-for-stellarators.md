---
title: "Beam Tracing for Stellarators"
collection: publications
category: theses
permalink: /publication/2025-06-01-beam-tracing-for-stellarators
excerpt: 'Final-year BSc thesis: Cartesian Scotty, a beam-tracing library for Doppler backscattering in non-axisymmetric geometries such as stellarators.'
date: 2025-06-01
venue: 'BSc thesis, Nanyang Technological University'
citation: 'E. Wikarta (2025). &quot;Beam Tracing for Stellarators.&quot; BSc thesis, Nanyang Technological University, Singapore.'
---

<!-- TODO: add paperurl in the front matter if the thesis is online (e.g. on DR-NTU), and check the date. -->

This thesis develops *Cartesian Scotty*, a Python library that extends the Scotty beam-tracing code
to model Doppler backscattering (DBS) with the beam model in complex, non-axisymmetric magnetic
geometries.

* **Validation** in three cases: vacuum and the 2D linear layer (both against analytic solutions),
  and a DIII-D tokamak equilibrium (against Scotty). All three agree well.
* **Stellarator simulations:** preliminary DBS simulations in a W7-X-like equilibrium generated
  with DESC, using two simple scaling laws for the turbulence spectrum. The backscattered power
  does not follow these scaling laws globally, which points to signal localisation rather than the
  turbulence spectrum itself. This needs care when inverting measured backscattered spectra to
  infer the turbulence spectrum.
* **Mismatch angle:** a short discussion of why optimising the mismatch angle matters in real DBS
  systems.

Work done as an A\*STAR Research Internship Award (ARIA) intern at the Institute of High
Performance Computing (IHPC).
