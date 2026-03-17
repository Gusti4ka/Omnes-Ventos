# Omnes Ventos ⚓
### A Stochastic Monte Carlo Analysis and Probabilistic Race Strategy for the IMOCA 60 Class

> *"In tranquillo esse quisque gubernator potest."*
> *"Anyone can hold the helm when the sea is calm."*
> — Publilius Syrus, 1st century BC

---

## Overview

The Vendée Globe is the dream of the seasoned sailor — a real-world echo
of Jules Verne's *Around the World in 80 Days*, except the ocean fights back.
Solo, non-stop, unassisted: 24,000 nautical miles through the roaring forties,
the furious fifties, and the screaming sixties.

This project applies **Monte Carlo simulation** and **stochastic modelling**
to analyse probabilistic race strategy for the IMOCA 60 class.
Given that wind is uncertain, which route should a skipper choose?

---

## Contents

| File | Description |
|------|-------------|
| `Omnes_Ventos.ipynb` | Main analysis notebook |
| `README.md` | This file |

---

## Methods

- **Ornstein-Uhlenbeck process** for wind speed simulation
- **IMOCA 60 polar diagram** as the boat physics engine
- **Monte Carlo simulation** — 500 scenarios × 3 candidate routes
- **Statistical analysis** — distributions, box plots, CDF curves

---

## Key Results

| Route | Mean Finish | Std | Median | Best Case | Worst Case |
|-------|-------------|-----|--------|-----------|------------|
| Conservative | 109.6 days | 4.5 days | 109.2 days | 99.8 days | 125.4 days |
| Nominal | 108.6 days | 4.4 days | 108.3 days | 98.2 days | 124.2 days |
| **Aggressive** | **105.5 days** | **4.3 days** | **105.3 days** | **95.0 days** | **120.5 days** |

The model confirms what real skippers know: going south is faster.
Charlie Dalin won the 2024-2025 Vendée Globe in 64 days, 19 hours,
22 minutes, and 49 seconds — the gap between simulation and reality
points to exciting next steps.

---

## Requirements

- Python 3 (Anaconda Distribution)
- `numpy`, `matplotlib`, `scipy`, `pandas`

---

## Author

**Avgustina Daskalova**
Math for Developers — Final Exam Project, March 2026

---

## References

See Section 8 of the notebook for full references.