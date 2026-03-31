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
