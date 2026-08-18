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
  <p>I am a PhD researcher in machine learning at the Gatsby Unit, UCL, working primarily on causal and probabilistic machine learning. My research develops representations and algorithms that exploit invariance, compositional structure and the geometry of transformations to make causal inference and generative modelling more robust, interpretable and computationally efficient. Recent work includes counterfactual transports and cocycles, generative modelling of interventional distributions using flow matching, causal uncertainty quantification, and accelerator-efficient Monte Carlo methods. More broadly, I am interested in how causal and statistical structure can help us understand, manipulate and reason about complex learned systems, including questions around representation, identifiability, abstraction and reliable intervention.</p>
</div>

<div class="home-links" aria-label="Research profile links">
  <a class="btn btn--primary" href="/cv/">CV</a>
  <a class="btn" href="https://scholar.google.co.uk/citations?user=h4Q6RJEAAAAJ&amp;hl=en&amp;oi=ao">Google Scholar</a>
  <a class="btn" href="https://github.com/HWDance">GitHub</a>
</div>

## Selected Research

<div class="home-project-grid">
  <article class="home-project-card">
    <div class="home-project-figure" aria-hidden="true">
      <svg viewBox="0 0 360 160" role="img">
        <defs>
          <marker id="arrow-flow" markerWidth="8" markerHeight="8" refX="7" refY="4" orient="auto"><path d="M0,0 L8,4 L0,8 z" /></marker>
        </defs>
        <g class="svg-muted">
          <circle cx="40" cy="48" r="7"/><circle cx="64" cy="73" r="7"/><circle cx="36" cy="96" r="7"/><circle cx="83" cy="41" r="7"/><circle cx="86" cy="102" r="7"/>
          <circle cx="275" cy="43" r="7"/><circle cx="309" cy="63" r="7"/><circle cx="274" cy="90" r="7"/><circle cx="312" cy="104" r="7"/><circle cx="292" cy="121" r="7"/>
        </g>
        <path class="svg-accent-line" d="M114 76 C150 34, 205 116, 252 72" marker-end="url(#arrow-flow)"/>
        <text class="svg-caption" x="24" y="149">observational</text>
        <text class="svg-caption" x="244" y="149">interventional</text>
      </svg>
    </div>
    <div class="home-project-body">
      <div class="home-project-meta">Generative modelling · causal inference</div>
      <h3>Debiased Counterfactual Generation via Flow Matching from Observations</h3>
      <p>Rather than learning an interventional distribution from scratch, we learn a <em>deconfounding flow</em> from the observed conditional distribution to its counterfactual target. The method combines flow matching with semiparametric debiasing and minimal-energy transports for high-dimensional outcomes.</p>
      <p class="home-project-links"><a href="https://arxiv.org/abs/2605.07665">Paper</a></p>
    </div>
  </article>

  <article class="home-project-card">
    <div class="home-project-figure" aria-hidden="true">
      <svg viewBox="0 0 360 150" role="img">
        <defs>
          <marker id="arrow-cocycle" markerWidth="8" markerHeight="8" refX="7" refY="4" orient="auto"><path d="M0,0 L8,4 L0,8 z" /></marker>
        </defs>
        <circle class="svg-node" cx="72" cy="103" r="22"/>
        <circle class="svg-node" cx="180" cy="43" r="22"/>
        <circle class="svg-node" cx="288" cy="103" r="22"/>
        <path class="svg-accent-line" d="M92 92 L158 55" marker-end="url(#arrow-cocycle)"/>
        <path class="svg-accent-line" d="M202 55 L268 92" marker-end="url(#arrow-cocycle)"/>
        <path class="svg-accent-line" d="M96 103 L264 103" marker-end="url(#arrow-cocycle)"/>
        <text class="svg-node-label" x="72" y="108" text-anchor="middle">Y(x)</text>
        <text class="svg-node-label" x="180" y="48" text-anchor="middle">Y(x′)</text>
        <text class="svg-node-label" x="288" y="108" text-anchor="middle">Y(x″)</text>
      </svg>
    </div>
    <div class="home-project-body">
      <div class="home-project-meta">Counterfactuals · invariance · transport</div>
      <h3>Counterfactual Cocycles: A Framework for Robust and Coherent Counterfactual Transports</h3>
      <p>We represent intervention-induced transformations through cocycles: maps with algebraic composition structure that identify coherent systems of interventional and counterfactual distributions. This yields estimators that can avoid unnecessary latent-noise modelling while retaining robustness and efficiency.</p>
      <p class="home-project-links"><a href="https://arxiv.org/abs/2405.13844">Paper</a> <span>·</span> <a href="https://github.com/HWDance/Cocycles">Code</a></p>
    </div>
  </article>

  <article class="home-project-card">
    <div class="home-project-figure" aria-hidden="true">
      <svg viewBox="0 0 360 150" role="img">
        <path class="svg-band" d="M24 109 C64 86, 92 60, 130 63 C170 66, 184 83, 218 76 C250 70, 277 44, 336 46 L336 78 C278 78, 251 101, 218 104 C182 108, 167 92, 130 91 C90 90, 62 112, 24 131 Z"/>
        <path class="svg-accent-line" d="M24 120 C63 98, 92 75, 130 77 C168 78, 184 92, 218 90 C250 88, 278 62, 336 61"/>
        <line class="svg-axis" x1="22" y1="136" x2="340" y2="136"/>
        <line class="svg-axis" x1="22" y1="136" x2="22" y2="20"/>
        <circle class="svg-point" cx="48" cy="113" r="3.4"/><circle class="svg-point" cx="68" cy="98" r="3.4"/><circle class="svg-point" cx="90" cy="91" r="3.4"/><circle class="svg-point" cx="112" cy="75" r="3.4"/><circle class="svg-point" cx="134" cy="87" r="3.4"/><circle class="svg-point" cx="158" cy="70" r="3.4"/><circle class="svg-point" cx="183" cy="97" r="3.4"/><circle class="svg-point" cx="207" cy="82" r="3.4"/><circle class="svg-point" cx="232" cy="99" r="3.4"/><circle class="svg-point" cx="256" cy="78" r="3.4"/><circle class="svg-point" cx="283" cy="70" r="3.4"/><circle class="svg-point" cx="312" cy="51" r="3.4"/>
        <text class="svg-caption" x="281" y="126">intervention</text>
      </svg>
    </div>
    <div class="home-project-body">
      <div class="home-project-meta">Uncertainty quantification · Gaussian processes</div>
      <h3>Interventional Processes for Causal Uncertainty Quantification</h3>
      <p>We develop spectral Gaussian-process representations for causal effects that support flexible nonparametric estimation together with calibrated epistemic uncertainty. The resulting framework provides reliable uncertainty quantification for intervention functions and causal decision-making.</p>
      <p class="home-project-links"><a href="https://arxiv.org/abs/2410.14483">Paper</a> <span>·</span> <strong>ICML 2026</strong></p>
    </div>
  </article>

  <article class="home-project-card">
    <div class="home-project-figure" aria-hidden="true">
      <svg viewBox="0 0 360 150" role="img">
        <defs>
          <marker id="arrow-fsm" markerWidth="8" markerHeight="8" refX="7" refY="4" orient="auto"><path d="M0,0 L8,4 L0,8 z" /></marker>
        </defs>
        <rect class="svg-state" x="40" y="49" width="63" height="38" rx="8"/>
        <rect class="svg-state" x="148" y="49" width="63" height="38" rx="8"/>
        <rect class="svg-state" x="256" y="49" width="63" height="38" rx="8"/>
        <path class="svg-accent-line" d="M103 68 L145 68" marker-end="url(#arrow-fsm)"/>
        <path class="svg-accent-line" d="M211 68 L253 68" marker-end="url(#arrow-fsm)"/>
        <path class="svg-muted-line" d="M163 49 C143 18, 216 18, 197 49" marker-end="url(#arrow-fsm)"/>
        <text class="svg-node-label" x="71" y="72" text-anchor="middle">INIT</text>
        <text class="svg-node-label" x="180" y="72" text-anchor="middle">STEP</text>
        <text class="svg-node-label" x="287" y="72" text-anchor="middle">DONE</text>
        <text class="svg-caption" x="87" y="119">finite-state-machine control flow</text>
      </svg>
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
    <p>I develop methods for interventions and counterfactuals from observational data, including counterfactual transports, causal uncertainty quantification, causal discovery and interventional generation. Current work studies partial identification, using dependence between potential outcomes to sharpen counterfactual bounds.</p>
  </section>

  <section class="home-theme-card">
    <h3>Generative models and structured dynamical systems</h3>
    <p>I use transport, flow matching and dynamical-systems perspectives to learn transformations between distributions. Recent work includes debiased flow matching for interventional generation and velocity-based causal discovery; current work develops multi-parameter flows with path independence, composition and low-energy dynamics.</p>
  </section>

  <section class="home-theme-card">
    <h3>Latent structure, invariance and identifiability</h3>
    <p>I exploit invariance and compositional structure to remove unnecessary parameterisation while preserving what is needed for inference. Building on counterfactual cocycles, current work studies latent-indexed transformations for dimension reduction, latent identification and extrapolation, with broader links to causal abstraction and learned representations.</p>
  </section>

  <section class="home-theme-card">
    <h3>Probabilistic machine learning, uncertainty and computation</h3>
    <p>I develop probabilistic methods for scalable inference and calibrated uncertainty, including Gaussian processes for high-dimensional variable selection and causal uncertainty quantification, and finite-state-machine representations of adaptive MCMC for efficient execution on modern accelerators.</p>
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

I am completing my PhD in Machine Learning at the [Gatsby Computational Neuroscience Unit](https://www.ucl.ac.uk/gatsby/), UCL, supervised by Professor Peter Orbanz. Before starting the PhD, I spent around five years as an econometrician in PwC's Economic Consulting team in London, working on causal estimation, high-dimensional forecasting, Bayesian modelling and applied policy research. Earlier training includes an MSc in Computational Statistics and Machine Learning and an MSc in Economics, both from UCL. Selected applied work is available in my [industry experience](/portfolio/).
