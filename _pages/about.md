---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Brief Bio
------------
Robert M. Radway is an Assistant Professor of Electrical & Systems Engineering at the University of Pennsylvania. His Ph.D. in Electrical Engineering at Stanford University is supervised by Prof. Subhasish Mitra. He received his M.Eng. and B.S. in Electrical Engineering and Computer Science from MIT. His research focuses on building hardware systems leveraging heterogeneous memory, logic, and 3D integration for large benefits. His research contributions include the first published non-volatile Resistive RAM (RRAM) systems, the first edge AI/ML chips using foundry RRAM for full on-chip inference and training, multi-chip systems to efficiently scaleup to larger models, and the first foundry monolithic 3D hardware delivering large benefits. His honors include the Stanford Graduate Fellowship, the Symposium on VLSI Circuits Best Student Paper Award, and the Symposium on VLSI Technology Best Student Paper Award.


Actively Recruiting Ph.D. Students - University of Pennsylvania Electrical & Systems Engineering
-------------
I am actively recruiting Ph.D. students to join my lab at UPenn for the 2025-2026 academic year. Please submit a [formal application](https://gradadm.seas.upenn.edu/how-to-apply/) to the [doctoral program](https://www.ese.upenn.edu/doctoral/), listing me as a potential supervisor. In additon, feel free to contact me via email with your CV, transcript, and a brief description of your research background and interests, emphasizing how they align with our work.

Research Interests
--------------
My research interests are in scaling system architectures via multiple multiplicative improvements:
  * Technology-optimized architectures for artificial inteligence / machine learning, augmented & virtual reality, and the internet of things
  * Heterogeneous 2.5D, 3D, and monolithic 3D integration
  * Heterogenous-technology systems electronic design automation & compilation

Projects
--------
* **3D MOSAIC (Monolithic, Stacked, Assembled IC) Systems that Scale via Multiple Multiplicative Improvements:**
  * Developed Illusion Systems that create the illusion of large on-chip memory (i.e., energy and exec. time within 5% of a dream single chip). Developed heuristic and binary integer linear program partitioning for ML applications on Illusion Systems. Developed hardware platform and simulations to demonstrate Illusion (**Nature Electronics ‘21, First Author**).
  * Developed Illusion Scaleup theory, finding linear improvement pathways in on-chip and inter-chip technology were sufficient to match exponential growth in ML application demands over a fixed horizon when combined with the Illusion Systems approach on a 3D MOSAIC (**IEDM ‘21, First Author**).
  * Developed parameterized application-to-emulation flow to demonstrate Illusion Scaleup via cycle-accurate system emulation using HLS and a power-aware Illusion compiler (leveraging fine-grained spatiotemporal power gating on chip) to generate parameterized Illusion Systems with variable per-chip capacities and chip-to-chip links (in preparation).
* **Technology-Optimized VLSI Systems:** Resistive RAM (RRAM) for edge AI/ML inference and training that scale.
  * Developed multi-chip system for CHIMERA, a RRAM-based edge AI/ML SoC with peak 2.2 TOPS/W energy efficiency, edge incremental training, 33us wakeup/shutdown, scaled to 6x larger models with <4% exec. time and <5% energy overheads (**Symp. VLSI Circuits ‘21 – Joint Focus Session, Best Student Paper Award, JSSC ‘22, Equal Contrib.**).
  * Physical design and custom 16-chip system integration of MINOTAUR, an RRAM-based, Transformer-optimized accelerator SoC for inference and training. Developed spatiotemporally fine-grained power gating for dynamically adjustable (< 1us), energy-proportional RRAM bandwidth (in preparation).
* **New Memories for Monolithic 3D:** Optimized ultra-dense (monolithic) 3D ICs integrating RRAM & CNFETs on silicon.
  * Iso-footprint and iso-capacity approach to 5-10x EDP benefits for monolithic 3D ICs (Carbon Nanotube FETs – CNFETs + RRAM + silicon CMOS) vs. 2D ICs (RRAM +silicon CMOS) (**DATE ‘23, Equal Contribution**).
  * First iso-footprint, iso-node, iso-performance, iso-reliability CNFET-RRAM cell vs. Si-RRAM cell, with apples-to-apples (same wafer) measurement (**Symp. VLSI Technology & Circuits ‘23, Technology Focus Session, Equal Contrib.**).
 
