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

Stack: C++, OpenCV, NAOqi SDK, robot motion control, state machines, real-time perception
<br>

Focus: Vision-guided navigation · pose estimation · behavior control · hardware integration
<br>
[GitHub](https://github.com/ChloeZhu1/naoqi-robot-vision-motion.git)
<br>
[YouTube Link](https://www.youtube.com/watch?v=r45bdkmdulo) 

<h2 id="hr">From Graphics to Motion: A Vision-Driven Robot Pipeline</h2>
I designed and implemented a full SVG-to-robot handwriting pipeline that converts vector character geometry into precise, physically executed pen strokes using a [Dobot robotic arm](https://youtu.be/dUUH_BGZyok).

The system successfully:
* Writes individual characters with multiple strokes
* Produces structured multi-line poems
* Demonstrates smooth, continuous stroke execution
* Preserves the visual structure of vector-based glyphs in physical form

[Details](https://chloezhu1.github.io/physics-and-engineering-research/#dba)<br>
[GitHub](https://github.com/ChloeZhu1/Image-to-Trajectory-Robot-Controller.git)
