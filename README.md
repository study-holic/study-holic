# William Odumosu

Second-year BSc Mathematics at the University of Manchester. I build market-microstructure research tools, trading competition entries, and simulated markets, mostly in Python.

## Experience

**Founder and President, Algorithmic Trading Society, University of Manchester (Jun 2026 – present)**
I founded the society and grew it to 200 members in its founding term, with Jane Street and TPP as sponsors. I wrote the 2026/27 curriculum, 17 taught weeks running from Python strategy foundations to C++ in two ability tracks. I also design the market models for the UoM Algothon and the semester competitions, which cover a drifting peg, regime-switching trends, options on a stochastic-volatility underlying, and lag-linked baskets, each graded from easy to impossible.

**Decoded: Data at Bloomberg (Apr – Jun 2026)**
I spent three days at Bloomberg's European headquarters in London with the first London cohort. I won two EDA flash rounds profiling a client-complaint file, and I diagnosed a trade feed dropping to zero and proposed a 20-tick moving-average check to classify each drop as a data error or a genuine price move. My team, Encoded, won BPuzzled, Bloomberg's problem-solving competition, and I went on to complete Decoded's mentoring track with a Bloomberg mentor.

**Stephen Lawrence Scholar, Freshfields Bruckhaus Deringer (Jun 2026 – present)**
I hold a multi-year scholarship carrying a £5,000 award and assigned mentors at the Bank of England and Freshfields. During the August 2026 work experience week, I built the evidence base for a 12-person cohort's Bribery Act 2010 case study as document manager, and I led a five-area Responsible Business presentation to a guest panel.

**FOCUS Programme, Jane Street (Jan 2026)**
I quoted two-sided markets in chip-based market-making simulations and worked through Jane Street's puzzle set. In a live incident simulation, my five-person team traced failing trades to a software update that had broken trade entry. On my lead rotation, I mapped which department owned each stage of the pipeline and proposed the revert the team adopted, and trading resumed about 24 minutes after the open.

**Mathletes Captain, Maths Society, University of Manchester (Jun 2026 – present)**
I write all 20 weekly sessions for the year, write and mark the Manchester Maths League papers, and help host the Imperial-Cambridge Maths Competition and MIMUC.

## Featured Project

### [LOB Alpha: Limit Order Book Signal Research](https://github.com/study-holic/q1-lob-alpha)
Python · 80 tests · MIT licence · [SSRN preprint](http://dx.doi.org/10.2139/ssrn.7342098)

- Tests order flow imbalance, queue imbalance, micro-price deviation, and spread against forward mid returns on five NASDAQ instruments, at six horizons from 1 to 100 events
- Cleans 2,110,860 raw LOBSTER events to 953,829 under ten audited rules, grouping every shift, roll, and diff by instrument and session
- Finds that order flow imbalance predicts returns on all five instruments (rank IC 0.10 to 0.19, cross-sectional t = 18.0) and loses money after costs, breaking even at 4.8% of the assumed half-spread
- Corrects for multiple testing across all 1,080 hypotheses with an exact circular cross-correlation over 950,000 shifts
- Documents four defects found in its own audit, including walk-forward folds split by row position on an instrument-major panel
- The data covers one trading session, 21 June 2012, so I haven't tested whether the signals persist from day to day

## More Projects

- **[IMC Prosperity 4](https://github.com/study-holic/imc-p4)** (Python). A round-by-round writeup of a solo entry. My Round 5 algorithm placed 69th of 18,803 teams with one uniform market-making template across 50 products.
- **[Monte Carlo Option Pricing Engine](https://github.com/study-holic/monte-carlo-option-pricing-engine)** (Python). It prices European calls under Black-Scholes. At 50,000 paths, the optimal control variate cuts standard error by 62% and antithetic variates cut it by 29%.
- **[Tuning as Optimisation](https://github.com/study-holic/tuning-optimisation)** (Python). It compares 12-, 19-, and 31-TET under L1, L2, and L∞ loss, with weights induced from a MIDI score. It's published as a [Zenodo preprint](https://doi.org/10.5281/zenodo.19026923).
- **[Poker Bot](https://github.com/study-holic/poker_bot)** (Python). A heads-up no-limit hold'em bot that models each opponent across seven betting situations and narrows their range over 1,326 combinations on every action. It placed 4th of 68 teams.
- **[Pact](https://github.com/tylerw-11/NatWest-Challenge)** (TypeScript, Python). A cash-flow forecast app for gig workers that my team of four built at GreatUniHack 2026. I designed all ten screens, wrote the team's data-contract decision, and wrote the contract-snapshot and speed-budget tests in its 126-test suite.

## Achievements

- IMC Prosperity 4: 69th of 18,803 teams on the Round 5 algorithm and 318th algorithmic overall, entering solo
- Manchester AI Society Poker Bot Tournament: 4th of 68 teams, entering solo, after placing 2nd of 68 in round 1
- Kaggle March Machine Learning Mania 2026: 562nd of 3,462
- MIMUC 2026: Best First-Year Talk (Jane Street and LMS)
- Bloomberg BPuzzled: winner, team Encoded
- MUFG strategy pitch: 1st of 8 teams

## Technical Skills

**Quant and data:** Python, NumPy, pandas, Optuna, XGBoost, SQL
**Backend and web:** TypeScript, React, Next.js, FastAPI
**Exposure:** C++, OCaml, R

## Current Focus

- Building the Algothon market models for the Algorithmic Trading Society
- Second-year modules in Stochastic Processes, Introduction to Financial Mathematics, and Numerical Analysis 1

## Publications

- [LOB Alpha: Microstructure Signals Under Exact Permutation Testing](http://dx.doi.org/10.2139/ssrn.7342098), SSRN preprint, 2026
- [Tuning as Optimisation: A Quantitative Analysis of Equal and Non-Equal Temperaments](https://doi.org/10.5281/zenodo.19026923), Zenodo preprint, 2026

## Connect

[LinkedIn](https://www.linkedin.com/in/williamodu) · [Email](mailto:williamodumosuu@gmail.com) · [ORCID](https://orcid.org/0009-0004-0273-8073)
