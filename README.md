

---

````markdown
# Commodity Futures Modeling Using Two-Factor Stochastic Models

This repository contains the implementation of commodity futures modeling and pricing using the **Gibson–Schwartz (1990)** and **Schwartz–Smith (2000)** two-factor models. The project includes calibration to historical futures data, Monte Carlo simulation, and pricing of futures and European options.

---

## Overview

The notebook **finance.ipynb** performs the following:

- Downloads and processes historical futures prices (Oil `CL=F`, Natural Gas `NG=F`, Copper `HG=F`, Gold `GC=F`)
- Calibrates both two-factor models to real market data
- Simulates joint factor dynamics under the risk-neutral measure
- Computes model-implied futures curves and prices European options
- Visualises historical prices, simulated paths, and model comparisons

---

## Key Features

- **Gibson–Schwartz Model:** Spot price + mean-reverting convenience yield  
- **Schwartz–Smith Model:** Long-term equilibrium + short-term deviation  
- **Monte Carlo Pricing:** Futures and options valuation using simulated paths  
- **Model Comparison:** Behaviour across different commodities and factors  

---

## Requirements

```bash
pip install numpy pandas matplotlib scipy yfinance jupyter
````

Run:

```bash
jupyter notebook
```

---

## Files

```
finance.ipynb              # Full implementation

```

---

## References

Gibson & Schwartz (1990), Schwartz & Smith (2000), Geman (2005), Eydeland & Wolyniec (2003)

---

## Author

Safura Palekar — Khalifa University


