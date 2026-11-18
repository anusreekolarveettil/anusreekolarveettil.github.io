---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **PhD, Civil Engineering**, Indian Institute of Science, Bangalore, 2021 – present (thesis submitted November 2026)
  * CGPA 8.8 / 10
  * Supervisor: Prof. G. Madhavi Latha
* **MTech, Civil Engineering**, Indian Institute of Technology Madras, 2018 – 2020
  * CGPA 8.88 / 10
  * Supervisor: Prof. Subhadeep Banerjee
* **BTech, Civil Engineering**, College of Engineering Trivandrum, 2013 – 2017
  * CGPA 8.52 / 10

Research projects
======
* **PhD: Multi-level particle morphology effects on granular soil behaviour** (IISc, 2021 – present)
  * Studied how particle shape affects the packing, permeability and pore-scale flow of granular soils, using 3D-printed grains with controlled shapes, X-ray micro-CT, particle image velocimetry (PIV) and DEM simulations.

* **MTech: Seismic response analysis of mechanically stabilised earth (MSE) walls** (IIT Madras, 2018 – 2020)
  * Developed a finite-difference model of MSE walls under earthquake loading in FLAC2D, validated it against published shaking-table tests, and used it in parametric studies of wall design and ground-motion effects.

Teaching experience
======
* **Teaching Assistant**, Indian Institute of Science, Bangalore, Aug – Dec 2023
  * CE201 Basic Geomechanics: conducted tutorials and held office hours
* **Teaching Assistant**, Indian Institute of Technology Madras, 2019 – 2020
  * CE5310 Advanced Soil Mechanics: graded assignments

Skills
======
* **Software:** PFC3D, FLAC2D, Blender, MeshLab, PIVlab
* **Programming:** MATLAB (micro-CT image processing, 3D shape characterisation, PIV post-processing), FISH (PFC3D scripting)
* **Numerical modelling:** DEM simulation of irregular particles, spherical harmonic-based particle reconstruction
* **Imaging and characterisation:** X-ray micro-CT, 3D particle morphology analysis, laser-sheet PIV
* **Additive manufacturing:** PolyJet, DLP and SLA printing of particle analogues
* **Experimental:** index void ratio and permeability tests, transparent soil testing

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
