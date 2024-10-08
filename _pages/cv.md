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
* <b>Stanford University</b>, Stanford, CA, USA (2018 – present)
  * Ph.D. Candidate in Electrical Engineering
  * Advisor: Prof. Subhasish Mitra
  * Thesis Title (work in progress): _Illusion Scaeleup on 3D MOSAICs for Abundant Data Aplications_
    
* <b>Massachusetts Institute of Technology</b>, Cambridge, MA, USA (2016 – 2017)
  * M.Eng in Electrical Engineering & Computer Science
  * Advisor: Prof. Tomás Palacios, EECS
  * Thesis Title: <a href="https://dspace.mit.edu/handle/1721.1/113116" style="color:#0645AD;">_Near Junction Thermal Management of GaN HEMTs via Wafer Bonding_</a>
  
* <b>Massachusetts Institute of Technology</b>, Cambridge, MA, USA (2013 – 2016)
  * B.S. in Electrical Engineering & Computer Science

Research experience
======
**Robust Systems Group**, Stanford University, Stanford, CA, (Jun 2018 - Present)
* **3D MOSAIC (Monolithic, Stacked, Assembled IC) Systems that Scale via Multiple Multiplicative Improvements:**
  * Developed Illusion Systems that create the illusion of large on-chip memory (i.e., energy and exec. time within 5% of a dream single chip). Developed heuristic and binary integer linear program partitioning for ML applications on Illusion Systems. Developed hardware platform and simulations to demonstrate Illusion (**Nature Electronics ‘21, First Author**).
  * Developed Illusion Scaleup theory, finding linear improvement pathways in on-chip and inter-chip technology were sufficient to match exponential growth in ML application demands over a fixed horizon when combined with the Illusion Systems approach on a 3D MOSAIC (**IEDM ‘21, First Author**).
  * Developed parameterized application-to-emulation flow to demonstrate Illusion Scaleup via cycle-accurate system emulation using HLS and a power-aware Illusion compiler (leveraging fine-grained spatiotemporal power gating on chip) to generate parameterized Illusion Systems with variable per-chip capacities and chip-to-chip links (in preparation).
* **Technology-Optimized VLSI Systems:** Resistive RAM (RRAM) for edge AI/ML inference and training that scale.
  * Measured on-chip RRAM IoT microcontroller with >10x battery life and fine-grained temporal power gating (>5,000x faster) vs. comparable embedded flash microcontrollers (ISSCC ‘19).
  * Developed multi-chip system for CHIMERA, a RRAM-based edge AI/ML SoC with peak 2.2 TOPS/W energy efficiency, edge incremental training, 33us wakeup/shutdown, scaled to 6x larger models with <4% exec. time and <5% energy overheads (**Symp. VLSI Circuits ‘21 – Joint Focus Session, Best Student Paper Award, JSSC ‘22, Equal Contrib.**).
  * Physical design and custom 16-chip system integration of MINOTAUR, an RRAM-based, Transformer-optimized accelerator SoC for inference and training. Developed spatiotemporally fine-grained power gating for dynamically adjustable (< 1us), energy-proportional RRAM bandwidth (in preparation).
* **New Memories for Monolithic 3D:** Optimized ultra-dense (monolithic) 3D ICs integrating RRAM & CNFETs on silicon.
  * Iso-footprint and iso-capacity approach to 5-10x EDP benefits for monolithic 3D ICs (Carbon Nanotube FETs – CNFETs + RRAM + silicon CMOS) vs. 2D ICs (RRAM +silicon CMOS) (**DATE ‘23, Equal Contribution**).
  * First iso-footprint, iso-node, iso-performance, iso-reliability CNFET-RRAM cell vs. Si-RRAM cell, with apples-to-apples (same wafer) measurement (**Symp. VLSI Technology & Circuits ‘23, Technology Focus Session, Equal Contrib.**).
  * Transferred RRAM technology into SkyWater Foundry as part of the 3DSoC program, developed custom ATE programs to evaluate yield (ISQED ‘23).
  * Full-custom RRAM test arrays for 1T-1R and 1T-nR structures that demonstrated up 4-bits-per-cell storage (IEDM ‘19, EDL ‘21, IEEE TED ‘21).
  * Led design of mixed-technology memory cells and arrays, leveraging RRAM, Oxide Semiconducting FETs and Silicon CMOS (in fabrication).

  
**Meta Reality Labs, Silicon Research Intern**, Sunnyvale, CA, (Jun 2021 - Jan 2022)
  * Analyzed AR/VR applications via Illusion System approach for multi-chip scalability (**IEDM 2021, First Author**)
  * Developed performance models for AR/VR systems integrated in 3D using TSMC’s SoIC technology.
  * Analyzed design tradeoffs for 3D integrated SRAM memory in AR/VR systems (IEEE Micro 2022).
  * Developed initial exploratory physical design flow to analyze system design choices & performance.

**Palacios Group**, MIT Microsystems Technology Lab, Cambridge, MA, (Aug 2015 – Feb 2017)
  * Research Focus: GaN-to-SiC HEMTs via Wafer Bonding:
    * Led development and simulated a novel GaN-to-SiC HEMT structure fabricated using wafer bonding to improve thermal performance (IWN 2016).
    * Led development of a GaN-SiC wafer bonding process to fabricate this structure (patent application).
  * Contributed to thermal modeling of REO epitaxies, fabrication of optogenetic sensors, and thermal simulation of vertical GaN devices. 

**Multicore Algorithmics Group**, MIT CSAIL, Cambridge, MA, (June 2014 – June 2015)
  * Collaborated with the Harvard Visual Computing Group to develop a deep network method for fast detection of synapses in neuron electron microscopy imaging.
  * Explored algorithms to turn synapse pixel segmentations to identifications.
  * Method showed up to 4x speed up over state-of-the-art.

**Personal Robots Group**, MIT Media Lab, Cambridge, MA, (Feb 2013 – Jan 2014)
  * Researched reinforcement learning algorithms in the context of human-based reward functions.
  * Created new algorithms to transfer results of previous trainings and explored their convergence.
  * Tested different approaches using Amazon Mechanical Turk studies.

Work Experience
======
**D. E. Shaw & Co.**, Asset-Backed Securities Trader, New York, NY, (Jan 2017 – June 2018)
* Developed investment theses and risk management strategies for portfolio of structured products including RMBS, Consumer ABS, CMBS, CLOs and whole loan transactions.
* Executed trades and specialty transactions on above theses.
* Managed intern and rotational analyst projects to develop analytical infrastructure for team.

**D. E. Shaw & Co.**, Quantitative Trading Intern, New York, NY, (May 2015 – August 2015)
* Worked on ABS desk to develop statistical and machine learning models of credit risk transfer deals.
* Ran significance and dropout tests on multiple parameters to determine optimal model inputs.
* Built code framework to implement model for day-to-day trading use.

**Morgan Stanley**, Trading Intern, New York, NY, (January 2015)
* Shadowed several equity options trading desks, including Automated Market Making, Exotic Options, Single Name Options, and Index Options.
* Built several exotic options pricing models.

**Basis Technology, Inc.**, Software Engineering Intern, Cambridge, MA, (May 2014 – August 2014)
* Worked with R&D team to develop software library to detect language of query-like short strings. 
* Ran tests and error analyses on multiple methods to develop detection algorithm and feature functions. 
* Built multi-layered system for 25 languages that increased testing accuracy by 50%.

**Appian Corporation**, Software Engineering Intern, Reston, VA, (January 2014)
* Created type selector API for use in the Appian Interface Designer data pane.
* Integrate API into existing proprietary expression language. 

  
Service
======
<b>Reviewer:</b> 
  * Design Automation Conference (DAC ’23)
  * ACM Journal on Emerging Technologies in Computing Systems (JETC)
  * IEEE Journal on Solid-State Circuits (JSSC)
  * IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (TCAD)
  * IEEE Transactions on Circuits and Systems II: Express Briefs (TCAS-II)
  * IEEE Transactions on Very Large Scale Integration Systems (TVLSI)
    
Stanford Electronic Systems Technology Seminar: Member, Organizing Committee (Jan 2021 – June 2022)

IEEE & SSCS Graduate Student Member

Teaching & Outreach
======
**Stanford University**, Stanford, CA
* Guest Lecturer: EE 271 (Winter 2022, Winter 2023)
  * EE 271: Design Projects in VLSI Systems I is a graduate course covering EDA flows from RTL-to-GDS.
  * Developed and presented a lecture on IC packaging design, processes and advanced 2.5D/3D integration.
* Undergraduate and Master’s Student Research Mentor: Robust Systems Group (Sep 2018 – Present)
  * Throughout my time at Stanford, I am fortunate to have had the privilege of mentoring several undergraduate and master’s students (including several URM and FLI students) through various research projects here at Stanford, with several contributing to publications.
  * Stanford Research Experiences for Undergraduates: 3 Mentees	(Summers 2020, 2021, 2022)
  * Co-Term Thesis: 1 Mentee (June 2022)
  * Stanford PURE Program: 1 Mentee (Winter – Spring 2023)
    * Stanford PURE aims to support first-generation and/or low income (FLI) students to provide compensation for their work as research assistants in Stanford CS labs.
  * Master’s Research Assistants: 6 Mentees (Sep 2018 – Present)
	
**Massachusetts Institute of Technology**, Boston, MA
* Teaching Assistant:6.01 (Median Overall Rating: 7.0/7.0 - Fall 2013, Spring 2016)
  * 6.01: Introduction to Electrical Engineering and Computer Science I covered topics in electronics, programming, algorithms, and control theory.
  * Assisted with office hours, laboratory sessions, review sessions.
  * Developed and tested lab assignments, exam questions, and homework.

Honors & Awards
======
* Cadence Design Systems Fellow (Stanford Graduate Fellowship - SGF - Fall 2019 – Summer 2023)
* Stanford SystemX FMA Fellow (Fall 2019 – Present)
* Stanford Electrical Engineering Department Fellowship	(Fall 2018 – Summer 2019)
* SuperUROP: Certificate in Advanced Undergraduate Research in Computer Science (May 2015)
* MIT EECS – Mason Undergraduate Research and Innovation Scholar (Aug 2014 – May 2015)
* Intel Science Talent Search Semifinalist (Feb 2012)
* Siemens Competition Semifinalist (Oct 2011)
* National Merit Scholarship Finalist (Sep 2011)
* Omron Foundation National Merit Scholarship (Sep 2011)

