---
layout: archive
title: ""
permalink: /research-experience/
author_profile: true
redirect_from:
  - /resume
---
{% include base_path %}
# Math Research
<h2 id="section-title1">Chiral skyrmions in the plane</h2>
* Mathematically, chiral skyrmions arise as minimizers of a critical harmonic-map energy perturbed by a symmetry-breaking linear term.
* I studied and presented the non-trivial minimizers to the chiral skyrmions energy functional, using concentration-compactness (the Zeeman term $\frac{\mathcal{h}}{2} \int \|m-e_3\|^2$) to restore compactness (preventing energy from drifting to infinity).
* By studying skyrmions, we can transfer the same technique to machine learning optimization problems. For example, applying the "mountain
pass" saddle point method to optimize functionals’ critical values.
<br>
[Skyrmion Paper](/files/Chiral Skyrmions Research Summary_Chloe.pdf)
<br>
[Skyrmions Image & Description](/math/)

<h2 id="PDE">Harmonic Analysis in Partial Differential Equations</h2>
* I used a div-curl structure from [Ginzburg-Landau](https://chloezhu1.github.io/math/#section-title) to restore compactness, which allows products of weakly convergent quantities to land in Hardy space.
* By showing that certain nonlinear quantities actually lie in Hardy space $\mathit{H}^1$, I can pass to limits in a function space dual to VMO, rather than collapsing to measures.
<br>
[Presentation](/files/Fangjun_Bonn_Presentation.pdf) (Please see the first half "Harmonic Analysis in PDE")

<h2 id="topoi">Indepedent Study on Topology</h2>
* I studied the [invariants of the complements of complex hypersurfaces](https://chloezhu1.github.io/math/#topdetails) by analyzing the topology of $\mathbb{C}^2\setminus\mathit{C}$ through localized homology and linking number constructions.
* By isolating a canonical linking direction and localizing the associated group ring, I defined an invariant $\delta_0(\mathit{C})$ that measures the size of first homology in a way that is stable under deformation. 
* I showed that, when finite, this invariant coincides with the degree of the Alexander polynomial, providing a conceptual and computable bridge between homological and classical polynomial invariants.
<br>
[Presentation](/files/Fangjun_Bonn_Presentation.pdf) (Please see the second half "Invariants of Hypersurface Complements")

<h2 id="gaus">Quasi-Invariance and Harmonic Analysis for Gaussian Measures in Infinite Dimensions</h2>
* I gave a detailed, functional-analytic treatment of the Cameron–Martin theorem, showing that [Gaussian measures](https://chloezhu1.github.io/math/#gdet) are quasi-invariant precisely along a distinguished Hilbert subspace — the Cameron–Martin space — and that translations in these directions admit an explicit Radon–Nikodym derivative.
* In infinite dimensions, Gaussian measures replace Lebesgue measures in finite dimensions, but Gaussian measures are not invariant under translation. My research answered the question of along which direction translation remains meaningful, and how the measure transforms.
<br>
[Paper](/files/Translations of Gaussian Measures for the Infinite Dimensional Segal-Bargmann Representation .pdf)

<h2 id="writ">Heat Equations and Harmonic Analysis on Manifolds</h2>
* I studied the Laplace equation ($\Delta u =  f$) and the heat equation ($\partial_t u - \Delta u = f$), on Riemannian manifolds.
* I constructed Green's functions on both compact manifolds with boundary and complete non-compact manifolds, developed the theory using level sets of Green's functions as substitutes for Euclidean balls, and accounted for geometric effects like Ricci curvature in gradient estimates.
<br>
[Paper](/files/Heat_eqns Inves.pdf)
<br>
[Details](https://chloezhu1.github.io/math/#rie)

# Physics and Engineering Research
<h2 id="mer">Computational Physics</h2>
[General Relativity and Mercury’s Precession](https://chloezhu1.github.io/physics-and-engineering-research/#gr)
* In Newtonian gravity, planetary orbits are closed ellipses, so any perihelion precession must come from perturbations. General relativity introduces a small correction to the equations of motion, reflecting the curvature of spacetime around the Sun. Though tiny, this relativistic term accumulates over many orbits, producing the observed perihelion precession of Mercury.
* My work provided a numerical simulation, translated differential equations into efficient algorithms, analyzed qualitative behavior, and visualized dynamics.

Methods & Tools

* Numerical integration of ODEs
* Stability and error analysis
* Visualization of trajectories and phase space
* Python, NumPy, Matplotlib, Jupyter notebooks
<br>
[GitHub](https://github.com/ChloeZhu1/computational-physics)

<h2 id="dp">Double Pendulum Dynamics</h2>
* The [double pendulum](https://chloezhu1.github.io/physics-and-engineering-research/#dpa) is a simple mechanical system whose equations of motion are nonlinear and highly sensitive to initial conditions. Despite being governed by deterministic ODEs, its dynamics exhibit chaotic behavior, making it a canonical example for studying instability, energy conservation, and long-time numerical integration.
<br>
[GitHub](https://github.com/ChloeZhu1/computational-physics)

<h2 id="mr">Machine Learning: Movie Recommendation System</h2>
* This project implements a [collaborative filtering–based movie recommendation system](https://chloezhu1.github.io/physics-and-engineering-research/#mra) using real user–rating data from the MovieLens dataset. By analyzing patterns in user–movie interactions, the model predicts personalized movie recommendations based on similarity between users and items.
<br>
[GitHub](https://github.com/ChloeZhu1/Machine-Learning-Movie-Recommendation-System.git)
<br>
[YouTube Demo Link](https://www.youtube.com/watch?v=anGgSRu01nY&feature=youtu.be)

<h2 id="gt">Gauge Transformations in Electrodynamics</h2>
A theoretical note analyzing [gauge redundancy in classical electrodynamics](https://chloezhu1.github.io/physics-and-engineering-research/#gta), clarifying the relationship between Maxwell’s equations, electromagnetic potentials, and well-posedness of the initial value problem. The work emphasizes gauge invariance, Utiyama’s theorem, and the role of temporal gauge in restoring deterministic evolution.
<br>
[Paper](/files/Gauge_Transformations.pdf)
<br>
[YouTube Link](https://youtu.be/l8rPY8Bcc0A)

<h2 id="hr">🤖 Vision-Driven NAO Robot Navigation & Control</h2>
* Engineered a C++ autonomous behavior system for the [NAO humanoid robot](https://chloezhu1.github.io/physics-and-engineering-research/#naoa) that fuses _real-time vision detection_ with _motion planning_ and _closed-loop control_. 
* Implemented a perception-to-action pipeline using NAOqi and OpenCV to detect targets, estimate relative pose, and drive head movement, walking, and task actions through a finite-state controller. Designed the system for robust target search, alignment, and approach under real hardware constraints.
<br>

Stack: C++, OpenCV, NAOqi SDK, robot motion control, state machines, real-time perception.
<br>
Focus: Vision-guided navigation, pose estimation, behavior control, hardware integration.
<br>
[GitHub](https://github.com/ChloeZhu1/naoqi-robot-vision-motion.git)
<br>
[YouTube Link](https://www.youtube.com/watch?v=r45bdkmdulo) 

<h2 id="db">From Graphics to Motion: A Vision-Driven Robot Pipeline</h2>
I designed and implemented a full SVG-to-robot calligraphy pipeline that converts vector character geometry into precise, physically executed pen strokes using a [Dobot robotic arm](https://youtu.be/dUUH_BGZyok). 

The system bridges computer graphics, geometric path planning, and real-world robot control, human-robot interaction, transforming SVG-based stroke data into executable robot trajectories with accurate pen-up / pen-down control.

The system successfully:
* Writes individual characters with multiple strokes
* Produces structured multi-line poems
* Demonstrates smooth, continuous stroke execution
* Preserves the visual structure of vector-based glyphs in physical form

[Details](https://chloezhu1.github.io/physics-and-engineering-research/#dba)<br>
[GitHub](https://github.com/ChloeZhu1/Image-to-Trajectory-Robot-Controller.git)

<h2 id="st">STM32 Internal Temperature Sensor & LCD Display</h2>
* I developed a bare-metal STM32F10x embedded systems project that measures temperature using the on-chip internal temperature sensor and displays the result in real time on an LCD screen.
* Implemented in C using the STM32 Standard Peripheral Library (StdPeriph) and targets an STM32F103 (ARM Cortex-M3) microcontroller. 
* Demonstrated core embedded concepts, including ADC configuration, sensor calibration, LCD interfacing, and real-time data display. 

[Details](https://chloezhu1.github.io/physics-and-engineering-research/#sta)<br>
[GitHub](https://github.com/ChloeZhu1/STM32-Internal-Temperature-Sensor-LCD-Display.git)

<h2 id="sy">Precise Synchronous Frequency Offset Apparatus for Multi-Robot RF Communication</h2>
This project develops a digitally controlled synchronous frequency calibration and offset generation system for dense multi-robot RF communication environments. The apparatus is designed for robotics competitions and coordinated robot fleets where dozens of transmitters operate simultaneously and require stable, interference-resistant, frequency-separated channels.

The core contribution is a microcontroller-based real-time frequency measurement and control architecture that replaces traditional analog PLL synchronization loops with a software-assisted calibration pipeline driven by an external standard frequency reference. The system extracts a national standard frequency (SF) signal embedded in broadcast video synchronization pulses and uses it to continuously discipline a VCXO reference, which is then used to drive a multi-channel RF frequency synthesis chain.

```html
<svg width="900" height="520" viewBox="0 0 900 520" xmlns="http://www.w3.org/2000/svg">
  <style>
    .box { fill:#111827; stroke:#60a5fa; stroke-width:2; rx:10 }
    .txt { fill:#e5e7eb; font-size:14px; font-family:monospace }
    .arrow { stroke:#9ca3af; stroke-width:2; marker-end:url(#arrow) }
  </style>

  <defs>
    <marker id="arrow" markerWidth="10" markerHeight="10" refX="9" refY="5" orient="auto">
      <polygon points="0,0 10,5 0,10" fill="#9ca3af"/>
    </marker>
  </defs>

  <!-- Input -->
  <rect class="box" x="40" y="60" width="200" height="60"/>
  <text class="txt" x="60" y="95">Broadcast Video Input</text>

  <rect class="box" x="40" y="150" width="200" height="60"/>
  <text class="txt" x="55" y="185">Sync Separator (H/V)</text>

  <rect class="box" x="40" y="240" width="200" height="60"/>
  <text class="txt" x="65" y="275">Line Gate + Counter</text>

  <!-- IPU -->
  <rect class="box" x="300" y="120" width="260" height="140"/>
  <text class="txt" x="320" y="150">IPU (Microcontroller)</text>
  <text class="txt" x="320" y="175">• Phase Detector</text>
  <text class="txt" x="320" y="195">• ADC Sampling</text>
  <text class="txt" x="320" y="215">• Digital Control Loop</text>
  <text class="txt" x="320" y="235">• DAC Feedback</text>

  <!-- VCXO -->
  <rect class="box" x="300" y="300" width="260" height="70"/>
  <text class="txt" x="320" y="340">VCXO (Disciplined)</text>

  <!-- Converter -->
  <rect class="box" x="300" y="400" width="260" height="60"/>
  <text class="txt" x="320" y="435">Freq Convert → 9 kHz Ref</text>

  <!-- FSU -->
  <rect class="box" x="620" y="160" width="220" height="120"/>
  <text class="txt" x="640" y="190">FSU (PLL Bank)</text>
  <text class="txt" x="640" y="215">• Dual Ref Inputs</text>
  <text class="txt" x="640" y="235">• Auto Switch</text>
  <text class="txt" x="640" y="255">• Multi-PLL Synth</text>

  <!-- RF Out -->
  <rect class="box" x="620" y="320" width="220" height="70"/>
  <text class="txt" x="645" y="360">Multi-Channel RF Out</text>

  <!-- Arrows -->
  <line class="arrow" x1="240" y1="90" x2="300" y2="150"/>
  <line class="arrow" x1="240" y1="180" x2="300" y2="180"/>
  <line class="arrow" x1="240" y1="270" x2="300" y2="210"/>

  <line class="arrow" x1="430" y1="260" x2="430" y2="300"/>
  <line class="arrow" x1="430" y1="370" x2="430" y2="400"/>
  <line class="arrow" x1="560" y1="430" x2="620" y2="340"/>
</svg>
```

[Slides](/files/PSFA.pptx)
