---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Welcome! I am an Alexander von Humboldt (AvH) Postdoctoral Fellow with Prof. Markus Klute at Karlsruhe Institute of Technology (KIT). My research aims at developing a new data analysis paradigm that is high-dimensional and unbinned using deep learning techniques.

Previously I was a graduate research & teaching assistant at Yale University and a research affiliate at Lawrence Berkeley National Laboratory, where I developed deep learning-based algorithms for detector deconvolution/unfolding and applied them to performing precision measurements with the ATLAS collaboration at the Large Hadron Collider, which is an experiment that probes the smallest scales at the highest energies to explore the most fundamental questions of nature, such as baryogenesis, dark matter, and the beginning stage of our universe.

<a href="mailto:jxp5547@gmail.com" title="If you are a student looking for thesis topics, please feel free to reach out!">
  <img src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/gmail.svg" 
       alt="Gmail" width="28" style="vertical-align:middle; margin-right:6px;">
  If you are a student looking for thesis topics, please feel free to reach out!
</a>


Recent Publications
======

<img style="float: right;padding: 10px 10px 10px 10px;" src="https://jp2555.github.io/images/tf.jpg" width=500>
[Measurement of jet track functions in pp collisions at $$\sqrt{s}=13$$ TeV with the ATLAS detector](https://arxiv.org/abs/2502.02062)
------
This paper presents the first measurement of jet track functions in $$pp$$ collisions at $$\sqrt{s}=13$$ TeV with the ATLAS detector. Jet track functions characterize the distribution of charged-particle momentum fractions within jets, providing a precision probe of jet substructure and perturbative QCD evolution. We use the OmniFold algorithm to perform an unbinned, high-dimensional unfolding, which enables direct measurement of the moments of the track function — observables inaccessible to traditional binned approaches — as well as the first measurement of their renormalization group flow.



<img style="float: left;padding: 10px 10px 10px 10px;" src="https://jp2555.github.io/images/npu.jpg" width=500>
[Neural Posterior Unfolding](https://arxiv.org/abs/2509.06370)
------
Standard detector unfolding methods produce point estimates of true-level observables and rely on covariance or bootstrap approximations for uncertainty quantification. In this work we introduce **Neural Posterior Unfolding (NPU)**, a method based on conditional normalizing flows that delivers fast, amortized access to the *full posterior distribution* over true-level observables given measured data. After a one-time training step, NPU yields per-event posteriors at negligible cost, enabling rigorous uncertainty quantification and Bayesian downstream inference for precision measurements at the LHC and beyond.



<img style="float: right;padding: 10px 10px 10px 10px;" src="https://jp2555.github.io/images/of.jpg" width=500>
[A Practical Guide to Unbinned Unfolding](https://arxiv.org/abs/2507.09582)
------
Unbinned, machine-learning-based unfolding has transformed how differential measurements at colliders can be performed, published, and reused. This community-authored guide surveys the modern estimator landscape — including OmniFold, density-ratio methods, simulation-based inference, and normalizing-flow approaches — and gives concrete recommendations on uncertainty quantification, validation, software choices, and analysis design. The aim is to lower the barrier for new analyses to adopt unbinned techniques and to encourage consistent practices across experiments.


<img style="float: left;padding: 10px 10px 10px 10px;" src="https://jp2555.github.io/images/h1.jpg" width=500>
[Towards Unfolding All Particles in High $$Q^2$$ DIS Events](https://www-h1.desy.de/h1/www/publications/htmlsplit/H1prelim-25-031.long.html)
------
This proceeding reports progress toward a fully differential measurement of the entire hadronic final state in high-$$Q^2$$ deep inelastic scattering events at the H1 experiment at HERA. Using OmniFold-style unbinned unfolding, all particles in each event are unfolded simultaneously to particle level, enabling new classes of observables — including the first measurement of energy correlators beyond the laboratory frame — and demonstrating the power of fully differential, all-particle unfolding for archival data at HERA and beyond.
