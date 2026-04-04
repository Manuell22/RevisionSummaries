# Revision Summaries

Exam revision notebooks for each module, generated from lecture notes. Each module has three notebooks:

| # | Notebook | Purpose |
|---|----------|---------|
| 1 | `1_HighLevel_Summary.ipynb` | Bird's-eye overview: course structure, key equations, core theorems, method toolkit, exam notes |
| 2 | `2_Detailed_Summary.ipynb` | Chapter-by-chapter detail: every definition, theorem, proposition, and proof sketch |
| 3 | `3_Exercises_Methods.ipynb` | Problem-type recipes, worked-example strategies, formulae cheat sheet, exam strategy |

## Modules

| Module | Chapters | Notebooks |
|--------|----------|-----------|
| **GameTheory** | Strategic-form games, Nash equilibrium, mixed strategies, extensive-form, repeated games, evolutionary GT | 3 |
| **OptionsPricing** | Binomial model, Black-Scholes, Greeks, American options, exotic options | 3 |
| **QuantumMechanics1** | Classical mechanics, Schrödinger dynamics, Hilbert spaces, 5 Principles, harmonic oscillator, representations, spectral properties, quantum dynamics (Lie groups), angular momentum & spin | 3 |
| **SDEsFinance** | Brownian motion, Itô calculus, SDEs, Fokker-Planck, financial applications | 3 |
| **StochasticSimulation** | Bayesian inference, pseudo-random number generation, inverse transform, transformation method, Box-Müller, composition, rejection sampling, curse of dimensionality | 3 |
| **FiniteElements** | Poisson/Helmholtz, Ciarlet FE spaces, Lagrange/Hermite/Argyris elements, interpolation error, Hilbert spaces, Lax-Milgram, Céa's lemma, Aubin-Nitsche, Stokes & Brezzi | 3 |

## Progress Tracking

| Module | Lecture Notes Read | Summaries Created | Past Papers Reviewed | Status |
|--------|--------------------|-------------------|----------------------|--------|
| **SDEsFinance** | ✅ Done | ✅ 3 notebooks | ✅ 2024 & 2025 | 🟢 Revision phase |
| **QuantumMechanics1** | ❌ Not started | ✅ 3 notebooks | ❌ | 🔴 Notes unread |
| **StochasticSimulation** | ❌ Not started | ✅ 3 notebooks | ❌ | 🔴 Notes unread |
| **FiniteElements** | ❌ Not started | ✅ 3 notebooks | ❌ | 🔴 Notes unread |
| **OptionsPricing** | ❌ Not started | ✅ 3 notebooks | ❌ | 🔴 Notes unread |
| **GameTheory** | ❌ Not started | ✅ 3 notebooks | ❌ | 🔴 Notes unread |

## Exam Schedule

| Date | Day | Module |
|------|-----|--------|
| **Mon 27 Apr** | Week 1 | SDEs in Finance |
| **Tue 28 Apr** | Week 1 | Quantum Mechanics 1 |
| **Mon 18 May** | Week 4 | Stochastic Simulation |
| **Thu 21 May** | Week 4 | Finite Elements |
| **Fri 22 May** | Week 4 | Options Pricing |
| **Mon 25 May** | Week 5 | Game Theory |

## Usage

Use the **RevisionAgent** (`@RevisionAgent` in VS Code chat) to ask revision questions. It searches the notebooks and returns exam-focused answers with definitions, theorems, and method recipes.

## Structure

```
├── GameTheory/
│   ├── LecNotes/
│   ├── 1_HighLevel_Summary.ipynb
│   ├── 2_Detailed_Summary.ipynb
│   └── 3_Exercises_Methods.ipynb
├── OptionsPricing/
│   ├── LecNotes/
│   ├── 1_HighLevel_Summary.ipynb
│   ├── 2_Detailed_Summary.ipynb
│   └── 3_Exercises_Methods.ipynb
├── QuantumMechanics1/
│   ├── LecNotes/
│   ├── 1_HighLevel_Summary.ipynb
│   ├── 2_Detailed_Summary.ipynb
│   └── 3_Exercises_Methods.ipynb
├── SDEsFinance/
│   ├── LecNotes/
│   ├── 1_HighLevel_Summary.ipynb
│   ├── 2_Detailed_Summary.ipynb
│   └── 3_Exercises_Methods.ipynb
├── StochasticSimulation/
│   ├── LecNotes/
│   ├── 1_HighLevel_Summary.ipynb
│   ├── 2_Detailed_Summary.ipynb
│   └── 3_Exercises_Methods.ipynb
└── FiniteElements/
    ├── LecNotes/
    ├── 1_HighLevel_Summary.ipynb
    ├── 2_Detailed_Summary.ipynb
    └── 3_Exercises_Methods.ipynb
```
