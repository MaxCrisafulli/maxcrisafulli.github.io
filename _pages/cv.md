---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

EDUCATION
======
* **MS/PhD** (Control Theory), UC Santa Barbara, 2028 (Expected)
* **B.S.** (Electrical Engineering), UC Santa Barbara, 2023
  * Coursework: Continuous & Digital Control Systems, Kalman-Filtering & Optimal Estimation, RF Electronics, Circuit Design/Analysis, Digital Signal Processing, IC Fabrication, Electromagnetic/TL Theory, Machine Learning
  * Overall GPA: 3.96/4.00

WORK EXPERIENCE
======
* **Summer 2023: *SpaceX - Starlink* (Associate Engineer - Postgrad)**
  * Designed, laid out, released, and programmed a daughter-board PCBA for a Raspberry Pi 4 to act as a connectivity tester for Ethernet links between boards in the Starlink satellite, functioning up to datarates of 25Gb/s. Developed for integration teams at Starlink manufacturing and launch facilities to reduce time spent debugging connectivity issues.
  * Aided in debugging of on-orbit hardware failures and bring up of in-development PCBAs for next-gen satellites
  * Wrote Python code to interface with the SpaceX telemetry API and diagnose on-orbit satellite hardware failures.

* **Summer 2022: *ASML* (FPGA Engineering Intern)**
  * Developed hardware/firmware testbench plans for an FPGA-based DAQ module. Produced documentation, block diagrams, and proposals for test procedures of the testbench.
  * Worked on a VHDL & SIMULINK HDL Coder based filter in parallel with main task. Developed from ground up through to implementation on an FPGA dev-board ([Repo](https://github.com/MaxCrisafulli/Basys3-Simulink-Audio-Filter)). 
  * Gained experience in programming VHDL, writing test-benches, Xilinx Vivado synthesis tools and IP cores, Modelsim, Makefiles/Buildfile automation, and FPGA verification.

* **Summer 2021: *ASML* (Analog Electrical Engineering Intern)**
  * Worked to develop a differential block pulse amplifier for use as a laboratory prototype. Constructed a differential combiner assembly to combine block pulse and sinusoidal signals for use in driving a piezo-electric transducer. Produced documentation, startup and use procedures, daily reports/presentations, and wiring schematics for all components in the system.

PROJECTS
======
* **Energy Control for EUV Photolithography**
  * Developed a novel control scheme to mitigate sensor feedback delay issues using a model of the ASML EUV Source in SIMULINK. Designed a feedback predictor algorithm using system identification methods and Kalman filtering. Developed metrics to characterize and verify system performance.
  * Project won the ”Distinguished Technical Achievement in EE” Award at End-of-Year Senior Project Expo

* **Rotational Inverted Pendulum Control ([Repo](https://github.com/MaxCrisafulli/furuta_pendulum))**
  * Derived nonlinear equations of motion and linearized to produce a state-space model of a rotational inverted (Furuta) pendulum. Designed a non-linear swing up and LQR balancing controller, as well as the switching logic to allow the pendulum to swing up and balance itself. Performed state estimation with a Kalman Filter. Implemented and tuned on hardware using SIMULINK autocoder.
  
SKILLS
======
* **Programming Languages:** Python, MATLAB, C, VHDL, Latex
* **Programs & CAD Tools:** MATLAB, SIMULINK, Linux, Xilinx Vivado, LTSpice, Keysight ADS, Siemens Xpedition Designer & Layout, Microsoft Office Programs, Atlassian Tools
* **Electronics Development:** PCB Schematic Capture & Layout, Use of Electronics Development Equipment



<!-- Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams -->
