---
permalink: /
title: "Hugh Dance"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<p class="home-kicker">PhD researcher in causal machine learning at the Gatsby Unit, University College London.</p>

<div class="home-intro">
  <p>I am a PhD researcher in machine learning at the Gatsby Unit, UCL, working primarily on causal and probabilistic machine learning. My research develops representations and algorithms that exploit structure&mdash;such as invariance, composition and transport&mdash;to make causal inference and generative modelling more robust, interpretable and computationally efficient. Recent work includes counterfactual transports and cocycles, generative modelling of interventional distributions using flow matching, causal uncertainty quantification, and accelerator-efficient Monte Carlo methods. More broadly, I am interested in how causal and statistical structure can help us understand, manipulate and reason about complex learned systems, including questions around representation, identifiability, abstraction and reliable intervention.</p>
</div>

<div class="home-links" aria-label="Research profile links">
  <a class="btn btn--primary" href="/cv/">CV</a>
  <a class="btn" href="https://scholar.google.co.uk/citations?user=h4Q6RJEAAAAJ&hl=en&oi=ao">Google Scholar</a>
  <a class="btn" href="https://github.com/HWDance">GitHub</a>
</div>

## Selected Research

<div class="home-project-grid">
  <article class="home-project-card">
    <div class="home-project-figure">
      <img src="{{ '/images/home/debiased_flow_matching.png' | relative_url }}" alt="Debiased flow-matching schematic and CelebA counterfactual generation examples">
    </div>
    <div class="home-project-body">
      <div class="home-project-meta">Generative modelling · causal inference</div>
      <h3>Debiased Counterfactual Generation via Flow Matching</h3>
      <p>Rather than learning an interventional distribution from scratch, we learn a <em>deconfounding flow</em> from the observed conditional distribution to its counterfactual target. The method combines flow matching with semiparametric debiasing and minimal-energy transports for high-dimensional outcomes.</p>
      <p class="home-project-links"><a href="https://arxiv.org/abs/2605.07665">Paper</a></p>
    </div>
  </article>

  <article class="home-project-card">
    <div class="home-project-figure">
      <img src="{{ '/images/home/cocycles.png' | relative_url }}" alt="Cocycle transports connecting intervention-indexed outcome distributions">
    </div>
    <div class="home-project-body">
      <div class="home-project-meta">Counterfactuals · invariance · transport</div>
      <h3>Counterfactual Cocycles</h3>
      <p>We represent intervention-induced transformations through cocycles: maps with algebraic composition structure that identify coherent systems of interventional and counterfactual distributions. This yields estimators that can avoid unnecessary latent-noise modelling while retaining robustness and efficiency.</p>
      <p class="home-project-links"><a href="https://arxiv.org/abs/2405.13844">Paper</a> <span>·</span> <a href="https://github.com/HWDance/Cocycles">Code</a></p>
    </div>
  </article>

  <article class="home-project-card">
    <div class="home-project-figure">
      <img src="{{ '/images/home/interventional_processes.png' | relative_url }}" alt="Interventional-process uncertainty quantification with calibrated posterior bands and intervention samples">
    </div>
    <div class="home-project-body">
      <div class="home-project-meta">Uncertainty quantification · Gaussian processes</div>
      <h3>Interventional Processes for Causal Uncertainty Quantification</h3>
      <p>We develop spectral Gaussian-process representations for causal effects that support flexible nonparametric estimation together with calibrated epistemic uncertainty. The resulting framework provides reliable uncertainty quantification for intervention functions and causal decision-making.</p>
      <p class="home-project-links"><a href="https://arxiv.org/abs/2410.14483">Paper</a> <span>·</span> <strong>ICML 2026</strong></p>
    </div>
  </article>

  <article class="home-project-card">
    <div class="home-project-figure">
      <img src="{{ '/images/home/fsm_mcmc.png' | relative_url }}" alt="Finite-state-machine representation of iterative MCMC control flow">
    </div>
    <div class="home-project-body">
      <div class="home-project-meta">Probabilistic ML · JAX · accelerators</div>
      <h3>Efficiently Vectorized MCMC on Modern Accelerators</h3>
      <p>We recast adaptive MCMC algorithms as finite-state machines so vectorized chains can progress through control flow independently, avoiding synchronization bottlenecks on GPUs and other accelerators. The resulting JAX implementations achieve speed-ups of up to an order of magnitude.</p>
      <p class="home-project-links"><a href="https://arxiv.org/abs/2503.17405">Paper</a> <span>·</span> <a href="https://github.com/HWDance/jax-fsm-mcmc">Code</a> <span>·</span> <strong>ICML 2025 Spotlight</strong></p>
    </div>
  </article>
</div>

## Research Themes

<div class="home-theme-grid">
  <section class="home-theme-card">
    <h3>Causal and counterfactual machine learning</h3>
    <p>My work develops methods for reasoning about interventions and counterfactuals from observational data, including counterfactual transports, causal uncertainty quantification, causal discovery, and generative modelling of interventional distributions. Current work extends these ideas to partial identification, asking how dependence between potential outcomes can sharpen otherwise weak counterfactual bounds.</p>
  </section>

  <section class="home-theme-card">
    <h3>Generative models and structured dynamical systems</h3>
    <p>I use transport, flow matching and dynamical-systems perspectives to represent and learn transformations between distributions. Recent work includes debiased flow matching for interventional generation and velocity-based representations for causal discovery. I am now studying multi-parameter generative systems whose transformations satisfy stronger global properties such as path independence, composition and low-energy dynamics.</p>
  </section>

  <section class="home-theme-card">
    <h3>Latent structure, identifiability and abstraction</h3>
    <p>A recurring theme in my work is exploiting invariance and compositional structure to remove unnecessary parameterisation while preserving the information required for inference. Building on counterfactual cocycles, I am studying latent-indexed families of transformations for dimension reduction, latent identification and extrapolation. More broadly, I am interested in how these ideas can inform causal abstraction and the understanding of complex learned systems.</p>
  </section>
</div>

## Software

<div class="home-software-grid">
  <article class="home-software-card">
    <h3><a href="https://github.com/HWDance/jax-fsm-mcmc">jax-fsm-mcmc</a></h3>
    <p>JAX implementations of finite-state-machine MCMC methods designed for efficient vectorized execution on modern accelerators.</p>
    <div class="home-software-tags"><span>JAX</span><span>MCMC</span><span>GPU</span></div>
  </article>

  <article class="home-software-card">
    <h3><a href="https://github.com/HWDance/Cocycles">Cocycles</a></h3>
    <p>Research code for learning and evaluating cocycle-based counterfactual transports across simulations and applied causal-inference problems.</p>
    <div class="home-software-tags"><span>Causal ML</span><span>Transport</span><span>Research code</span></div>
  </article>

  <article class="home-software-card">
    <h3><a href="https://github.com/HWDance/SSVGP">SSVGP</a></h3>
    <p>Scalable spike-and-slab variable selection for high-dimensional Gaussian-process models, accompanying the AISTATS 2022 oral paper.</p>
    <div class="home-software-tags"><span>Gaussian processes</span><span>Bayesian ML</span><span>Inference</span></div>
  </article>
</div>

## Background

I am completing my PhD in Machine Learning at the [Gatsby Computational Neuroscience Unit](https://www.ucl.ac.uk/gatsby/), UCL, supervised by Professor Peter Orbanz. Before starting the PhD, I spent around five years as an econometrician in PwC's Economic Consulting team in London, working on causal estimation, high-dimensional forecasting, Bayesian modelling and applied policy research. Earlier training includes an MSc in Computational Statistics and Machine Learning and an MSc in Economics, both from UCL. Selected applied work is available in my [industry portfolio](/portfolio/).
