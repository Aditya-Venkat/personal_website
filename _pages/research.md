---

permalink: /research/

title: "Research and projects"

author_profile: true

---

## Publications & Posters

**Benchmarking of Spatial Transcriptomics Methodologies**  

Ajita Shree, *\*Aditya V\**, Tanush Kumar, Hamim Zafar  

[**bioRxiv preprint**](https://www.biorxiv.org/content/10.64898/2026.05.11.724248v1.full)

Comprehensive benchmarking of 20+ spatial transcriptomics methods across simulated and real datasets, introducing new evaluation metrics and simulation techniques.  

Poster accepted at **RECOMB 2025, Seoul** and **ECCB 2026, Geneva** 



## Overview

My research explores the intersection of **Bayesian statistics**, **probabilistic machine learning** and **computational genomics** — focusing on developing interpretable statistical models to understand genetic mechanisms, disease progression, and survival data.

I have worked across several domains, ranging from **spatial transcriptomics** and **Bayesian survival modeling** to **machine unlearning** . Below are highlights of my recent and ongoing research projects.

---

<style>

/* Theme-aware research cards */

.research-card {

  background-color: var(--card-bg);

  border: 1px solid var(--card-border);

  border-radius: 1rem;

  padding: 1.2rem 1.5rem;

  margin-bottom: 1.5rem;

  box-shadow: 0 2px 6px var(--card-shadow);

  transition: transform 0.2s ease, box-shadow 0.2s ease;

  color: var(--card-text);

}

.research-card:hover {

  transform: translateY(-4px);

  box-shadow: 0 6px 12px var(--card-hover-shadow);

}

.research-card h3 {

  margin-top: 0;

  color: var(--card-heading);

}

/* LIGHT MODE COLORS */

:root {

  --card-bg: #f9fafb;

  --card-border: #e5e7eb;

  --card-shadow: rgba(0, 0, 0, 0.05);

  --card-hover-shadow: rgba(0, 0, 0, 0.08);

  --card-text: #1f2937;      /* dark grey */

  --card-heading: #111827;  /* near-black */

}

/* DARK MODE COLORS (Minimal Mistakes toggles html.dark) */

html.dark {

  --card-bg: #1f1f1f;

  --card-border: #3a3a3a;

  --card-shadow: rgba(255,255,255,0.05);

  --card-hover-shadow: rgba(255,255,255,0.08);

  --card-text: #e5e5e5;      /* light grey */

  --card-heading: #ffffff;   /* white */

}

</style>

---

---

<div class="research-card">

<h3>Benchmarking of Spatial Transcriptomics Methodologies</h3>

<strong>Supervisor:</strong> Prof. Hamim Zafar, IIT Kanpur<br>

<em>Sep 2023 – Nov 2025</em><br><br>

<ul>

<li>Built large-scale benchmarking pipelines for <strong>spatial deconvolution</strong> and <strong>spatial domain detection</strong> across 30+ datasets and 20+ methods.</li>

<li>Proposed a novel statistic, <em>Spatial Geary’s C</em>, improving performance evaluation of spatial methods.</li>

<li>Co-authored posters presented at <strong>RECOMB 2025 (Seoul)</strong> and <strong>ECCB 2026 (Geneva)</strong>; manuscript published on <strong>bioRxiv</strong>.</li>

</ul>

<a href="https://github.com/Zafar-Lab/spDDB" target="_blank">🔗 View Code</a>

</div>

---

<div class="research-card">

<h3>Bayesian Load-Sharing Models for Survival Analysis</h3>

<strong>Supervisor:</strong> Prof. Debasis Kundu, IIT Kanpur<br>

<em>Jan 2025 – Present</em><br><br>

<ul>

<li>Extended traditional load-sharing models to a <strong>Bayesian hierarchical framework</strong>, enabling prior-informed estimation and uncertainty quantification.</li>

<li>Developed MCMC samplers for exponential, Weibull, and piecewise-continuous hazard priors.</li>

<li>Preparing manuscript for submission.</li>

</ul>

<a href="https://github.com/Aditya-Venkat/Bayesian_bivariate_load_sharing_model" target="_blank">🔗 View Code</a>

</div>

---

<div class="research-card">

<h3>Bayesian Inference Unlearning</h3>

<em>Course Project — MTH707: Intro to ML (Spring 2025)</em><br><br>

<ul>

<li>Investigated MCMC-based algorithms for <strong>machine unlearning</strong> using Stochastic Gradient Riemannian Langevin Dynamics (SGRLD).</li>

<li>Developed a novel <strong>KL– and JSD–based unlearning criterion</strong> for efficient data removal.</li>

<li>Validated via simulation studies on posterior recovery and unlearning efficiency.</li>

</ul>

<a href="https://github.com/Aditya-Venkat/Bayesian_inference_unlearning" target="_blank">🔗 View Code</a>

</div>

---

<div class="research-card">

<h3>Multimodal Cell Type Imputation</h3>

<strong>Supervisor:</strong> Prof. Hamim Zafar, IIT Kanpur <br>

<em>Sep 2025 – Present</em><br><br>

<ul>

  <li>Built spatial joint embeddings using <strong>GAN-based models</strong> conditioned on niche-informed inference parameters.</li>

  <li>Applied <strong>non-parametric classifiers</strong> including Spearman correlation and multi-class p-tests for cell type prediction across spatial xenium samples.</li>

  <li>Developing a <strong>graph-based dual-autoencoder architecture</strong> with adversarial training for improved multimodal spatial representations.</li>

</ul>

<a href="https://github.com/Zehaan22/Xenium_Annotation_CS690" target="_blank">🔗 View Code</a>

</div>

---

<div class="research-card">

<h3>Antibody Expression Analysis for Cancer Therapeutics</h3>

<em>Intern, TenSixty Bio (Stanford-founded Biotech) — Jun–Jul 2024</em><br><br>

<ul>

<li>Developed <strong>AWS-based computer vision pipelines</strong> to analyze histological samples for antibody expression in small-cell lung cancer.</li>

<li>Parsed genomic data from <strong>UniProtKB (80,000+ genes)</strong>, identifying ~800 candidate proteins for therapeutic design.</li>

<li>Contributed to TenSixty Bio’s ongoing therapeutic screening framework.</li>

</ul>

</div>

---

<div class="research-card">

<h3>Genomic Variant Analysis for Drug Resistance</h3>

<strong>Ongoing Research Project</strong>, IIT Kanpur<br>

<em>2025 – Present</em><br><br>

<ul>

<li>Developed variant-level representations integrating <strong>functional annotations, allele frequencies, zygosity, and gene-level information</strong> across 4M+ genomic variants.</li>

<li>Applied <strong>UMAP, decision trees, random forests, and logistic regression</strong> to investigate patterns associated with drug resistance.</li>

<li>Implemented a <strong>weighted set-cover optimization</strong> framework for multi-hit variant detection and evaluated its predictive performance using cross-validation.</li>

</ul>

</div>

---

<div class="research-card">

<h3>Projects mentored</h3>

<ul>

<li><strong>Landing on the Moon (DQN Reinforcement Learning):</strong> Mentored students to train Deep Q-Networks for rover landing on simulated terrain.</li>

<li><strong>Sound Refine (Audio ML):</strong> Guided students to build a robust CNN-based denoising and transcription pipeline for audio restoration and classification.</li>

</ul>

<a href="https://github.com/Aditya-Venkat/Sound-Refine" target="_blank">🔗 View Code</a>

</div>

---

<div class="research-card">

<h3>Bayesian Modeling of Networks in Complex Business Intelligence Problems</h3>

<em>Course Project — MTH422: Introduction to Bayesian Analysis, IIT Kanpur (2024)</em><br><br>

<ul>

  <li>Reimplemented the Bayesian hierarchical model by <em>Durante et al.</em> for analysing cross-selling behaviour across agencies.</li>

  <li>Simulated customer product choices and co-subscription networks to validate model behaviour under controlled settings.</li>

  <li>Reconstructed the full MCMC pipeline, including latent eigenmodel mixtures and cluster inference.</li>

  <li>Evaluated posterior recovery, clustering accuracy, and practical strengths/limitations of the approach</li>

</ul>

<a href="https://github.com/Aditya-Venkat/Bayesian_modelling_business_intelligence" target="_blank">

🔗 View Code

</a>

</div>

---

<div class="research-card">

<h3>Credit Card Fraud Detection</h3>

<em>Course Project — MTH443: Statistical & AI Techniques in Data Mining</em><br><br>

<ul>

  <li>Analyzed the Kaggle credit card transaction dataset to detect fraudulent activity in an unsupervised setting.</li>

  <li>Implemented multiple anomaly detection frameworks, including <strong>Isolation Forest</strong>, <strong>One-Class SVM</strong>, and <strong>DBSCAN</strong>.</li>

  <li>Modeled temporal transactional behavior using <strong>Hidden Markov Models (HMMs)</strong> for sequence-level fraud detection.</li>

  <li>Built relational fraud scores through <strong>graph-based analysis</strong> using NetworkX to capture coordination patterns across entities.</li>

  <li>Demonstrated the benefits of integrating statistical, ML, and network-analytic methods for robust fraud detection in terms of key insights offered by each modality.</li>

</ul>

<a href="https://github.com/Aditya-Venkat/Credit_card_fraud_detection" target="_blank">

🔗 View Code

</a>

</div>