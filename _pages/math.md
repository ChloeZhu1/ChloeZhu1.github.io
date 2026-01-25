---
layout: archive
title: ""
permalink: /math/
author_profile: true
redirect_from:
  - /resume
--- 

{% include base_path %}
<!-- <a href="#section-title1">Skyrmions</a> -->
## [Skyrmions](https://chloezhu1.github.io/research-experience/#section-title1)
![Skyrmions](/images/skyrmions.jpg)
* Imagine a field of arrows all pointing upward. Now take one small spot and gently twist the arrows so that:
  * At the center, the arrow points down
  * Moving outward, the arrows rotate smoothly
  * Far away, everything points up again
    
  The small knot formed by this twist is known as a skyrmion. It's chiral because the arrows always twist left-handed or right-handed, which one can't easily "untwist" without tearing the pattern apart. This makes skyrmions very stable.      
* Because skyrmions are stable, tiny (nanometers across), and easy to move, they're promising candidates for next-generation low-power magnetic memory.

<!-- <h2 id="section2">## proj2</h2> -->
<h2 id="section-title">Ginzburg-Laudau</h2>
One Studies a complex field

$u:\ \Omega \subset \mathbb{R}^n \rightarrow \mathbb{C}$

and the Ginzburg-Landau energy

$E_{\epsilon}(u) = \int_\Omega \frac{1}{2}\|\nabla u\|^2+\frac{1}{4{\epsilon}^2}(1-\|u\|^2)^2\ dx$

<!-- <p style="text-align: left;"> -->
* In superconductivity, Ginzburg–Landau is a phenomenological theory describing a material near its critical temperature. If $u$ takes values in the complex plane $\mathbb{C}$, then $u$ can describe the wavefunction for a “fluid” of Cooper pairs in a superconductor. $\|u\|^2$ is the superconducting density.
* This research sits at the interface of harmonic analysis and nonlinear PDE, and it’s motivated by a very concrete failure of compactness. In many geometric and physical PDEs — like Ginzburg-Landau — we only have weak $L^2$ control on gradients, while the quantities of interest are nonlinear and should not converge under weak limits.
* From the Ginzburg-Landau equations, when separating their amplitude and phase, one encounters the term

  $\rho^2\|\nabla \phi\|^2 = \nabla \phi \cdot Im(\bar{u}\nabla u)$

where the equations imply div(Im($\bar{u}\nabla u$)) $= 0$
* div(Im($\bar{u}\nabla u$)) $= 0$ $\Rightarrow$ $\rho^2\|\nabla \phi\|^2 \in \mathit{H}^1$
  * oscillation $\neq$ noise
  * oscillation = noise + conservation
* This beautifully unifies the Hardy/BMO section with GL.
  
[Harmonic Analysis in PDE](https://chloezhu1.github.io/research-experience/#PDE)
