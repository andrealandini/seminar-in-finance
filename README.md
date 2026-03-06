# Noise vs Signal in Decentralized Prediction Markets

Seminar in Finance - SS 2026, Universitat Liechtenstein

Analyzing whether Polymarket-implied probabilities during the 2025 papal conclave reflect pure noise (speculation, herding, liquidity shocks) or rational updating based on publicly observable signals. We use realized variance, realized kernel estimators, and state-space models to decompose price variation into permanent (signal) and transitory (noise) components across conclave vs. non-conclave windows.

**Authors:** Andrea Landini, Simone Fruner, Emre Dalmizrak, Jan Mokrosinski
**Supervisor:** Nicola Benigni, MSc

## Repository Structure

```
.
├── README.md
├── assignmnets
│   ├── assignment.pdf            # Seminar assignment brief
│   ├── final-presentation.pptx   # Final presentation slides
│   ├── interim-presentation.pptx # Interim presentation slides
│   ├── main.pdf                  # Compiled paper
│   └── main.tex                  # LaTeX source for the paper
├── data
│   ├── All_Data.xlsx
│   └── polymarket-nicola-scraped-by-hand.csv
└── notebooks
    └── nb01-data-analysis.ipynb  # Data collection & exploration via Polymarket API
```

## Data

High-frequency trade data from the Polymarket event "Who will be the next Pope?", sourced via the Gamma and CLOB APIs.

## Key References

- Barndorff-Nielsen, O. E., Hansen, P. R., Lunde, A., & Shephard, N. (2008). *Econometrica*, 76(6), 1481--1536.
- Harvey, A. (2010). State space models. In *Macroeconometrics and Time Series Analysis*, Palgrave Macmillan.
