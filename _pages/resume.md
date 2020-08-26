---
layout: archive
title: "Industry Resume"
permalink: /resume/
author_profile: true
---

{% include base_path %}

Significant experience in developing **numerical codes for a broad array of
physics/engineering problems** and **machine learning (ML) / uncertainty quantification (UQ) tools**

* Development of **neural network-based surrogate models** and **physics-informed ML** approaches for accelerating materials discovery and design of energy storage devices such as Li-Ion batteries and supercapacitors.
* Design and implementation of **novel Monte Carlo-based solvers** to accelerate predictive modeling/UQ for multiphase flows in reactive granular media and subsurface phenomena.
* Development of numerical solvers for a broad range of **nonlinear systems with inherent uncertainty or random forcing**.
* Construction of **innovative models for shocked particle-laden flows** that enable process-scale, predictive simulations of high-speed applications ranging from dust explosions to engines for hypersonic propulsion systems.

## Professional experience

### [DEPARTMENT OF ENERGY RESOURCES ENGINEERING](https://earth.stanford.edu/ere), [STANFORD UNIVERSITY](https://www.stanford.edu) - Stanford, CA, USA

* Position: **Postdoctoral Scholar**, September 2018-Present
* Duties: 
  * Development of **enhanced multilevel Monte Carlo** methods for estimating the 
    cumulative distribution function of quantities of interest in **multiphase flows** e.g. in stochastic reservoir simulation: 
    * Fusion of standard Monte Carlo with **variance reduction** techniques to 
      **speed up UQ** simulations.
    * Sponsored by Air Force Office of Scientific Research (AFOSR) and Total
      S.A. and aimed at **inventing, testing and deploying new UQ techniques** that are more computationally efficient and yet as accurate as current exhaustive system realizations.
  * Design of a **neural network** with **TensorFlow 2** to accelerate **sensitivity analysis** and **UQ** studies of **energy storage systems** to aid in the **design** and testing of these devices.
     
### [SAN DIEGO STATE UNIVERSITY RESEARCH FOUNDATION](https://www.foundation.sdsu.edu/) - San Diego, CA, USA

* Position: **Research Specialist I**, October 2016-July 2018
* Duties: 
  * Development of transformative **Eulerian-Lagrangian** methods for simulation 
    of **particle-laden flows** in high-speed engineering applications:
    * Design and validation of **Cloud-In-Cell** models with enhanced accuracy and efficiency compared to the current state of the art for simulation of a particle cloud interacting with a shocked carrier flow.
    * Multi-institution collaborative effort aimed at designing a general **multiscale framework** for modeling **multimaterial dynamics**.
    * Sponsored by Air Force Office of Scientific Research (AFOSR) and aimed 
      at designing and implementing computational models capable of **predicting** the dynamics of **process-scale, compressible particle-laden flow** problems with **uncertain parameters**. 

### THEORETICAL DIVISION, [LOS ALAMOS NATIONAL LABORATORY (LANL)](https://www.lanl.gov/) - Los Alamos, NM, USA

* Position: **Graduate Research Assistant**, August 2014 to June 2015
* Duties: 
  * Development of an **information-directed** approach for materials discovery 
    and design:
    * Lab-Directed Research and Development (LDRD) effort (>$1M) aimed at 
      demonstrating the capability to **accelerate materials discovery**. 
    * Design of a **physics-informed ML** technique for **model selection** in 
      materials science and beyond.

## Education

* Ph.D in **Engineering Physics**, [University of California San Diego (UCSD)](https://ucsd.edu/), USA, 2016 (*GPA: 4.0/4.0*)
* M.S. in **Engineering Physics**, [University of California San Diego (UCSD)](https://ucsd.edu/), USA, 2012
* M.S. in **Physics**, [Katholieke Universiteit Leuven](https://www.kuleuven.be/english/), Belgium, 2006 (*Cum Laude*)

## Selected Honors and Awards

* Nomination for Chancellor’s Dissertation Medal by MAE Department, 2017  
  <br>[University of California San Diego](https://ucsd.edu/)

* College of Engineering Dean's Fellowship, 2009-2010  
  <br>[University of Michigan Ann Arbor](https://umich.edu/)

## Publications

  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

## Skills

* **Computing**: Finite difference/volume, particle-in-cell, Eulerian-Lagrangian, Monte Carlo simulation  
  * Programming languages: C++, Python, Fortran, MATLAB
  * Software packages: COMSOL, Tensorflow 2
  * Other: Unix/Linux, basic HPC
* **Numerical**:
  * Finite difference/volume
  * Particle-in-cell, Eulerian-Lagrangian
  * Monte Carlo simulation  
* **Written/oral/communication**:
  * Paper/funding proposal writing and peer review of articles
  * Interdisciplinary teamwork, student supervision
  * Project presentations at international scientific conferences
