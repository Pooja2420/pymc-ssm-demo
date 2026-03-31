# Bayesian State Space Models for Financial Regime Detection

A PyMC notebook demonstrating Bayesian state space models applied to 
financial regime detection — built as part of GSoC 2026 preparation 
for the Scalable Online Bayesian State Space Models project.

## Models Implemented
- **Local Level Model** — Bayesian random walk for latent trend estimation using `pm.GaussianRandomWalk`
- **Markov Switching Model** — Two-regime bull/bear detection using `pm.NormalMixture`

## Motivation
Both models use batch inference — requiring full re-sampling when new data 
arrives. Section 5 of the notebook motivates the need for online sequential 
updates and proposes an API design for the GSoC project.

## Dependencies
- PyMC 5.x
- ArviZ
- NumPy, matplotlib

## Author
Pooja Venugopal Baskaran | github.com/Pooja2420
```

---

## 2. Post on PyMC Discourse RIGHT NOW

Go to **discourse.pymc.io** → New Topic → Development category

**Title:** `GSoC 2026 Introduction: Scalable Online Bayesian State Space Models — Pooja`

**Body:**
```
Hi PyMC community!

I'm Pooja Venugopal Baskaran, applying for GSoC 2026 for the 
**Scalable Online Bayesian State Space Models** project.

My background is directly relevant:
- Built an HMM-based credit market regime detection model: 
  https://github.com/Pooja2420/HMM-Regime-Credit-Detection
- Built a statistical arbitrage engine with Kalman Filter dynamic 
  hedge ratios: https://github.com/Pooja2420/statistical-arbitrage-engine

Tonight I built a PyMC notebook demonstrating Bayesian SSMs for 
financial regime detection — implementing a Local Level Model 
(pm.GaussianRandomWalk) and a Markov Switching Model (pm.NormalMixture):
https://github.com/Pooja2420/pymc-ssm-demo

Section 5 of the notebook explicitly motivates the need for online 
sequential inference and proposes a user-facing API design.

@Jesse Grabowski @Jonathan Dekermanjian — I'd welcome any feedback 
on my approach and my GSoC proposal before the March 31 deadline.
```

---

## 3. Send email to fonnesbeck

**To:** `fonnesbeck+gsoc2026@gmail.com`
**Subject:** `GSoC 2026: Scalable Online Bayesian State Space Models — Pooja (discourse: pooja)`
```
Hi Chris,

I'm Pooja Venugopal Baskaran applying for the Scalable Online Bayesian 
State Space Models project.

I've built a PyMC notebook demonstrating hands-on exploration of 
Bayesian SSMs for financial regime detection:
https://github.com/Pooja2420/pymc-ssm-demo

My relevant background:
- HMM regime detection for credit markets
- Kalman Filter statistical arbitrage engine
- MS Data Science, DePaul University (GPA 3.7)

I have submitted my proposal on the GSoC site. My Discourse username 
is pooja (discourse.pymc.io).

Thank you for your time.
Pooja Venugopal Baskaran
pooja.vb2000@gmail.com
