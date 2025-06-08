# 📘 Project 2: Option Pricing Models

This repository explores classical option pricing models widely used in financial engineering.  
Specifically, we implement and analyze two key methodologies: the Black-Scholes-Merton model and the Binomial Tree method. These tools are fundamental for valuing European options and understanding dynamic hedging strategies.

---

## 📂 Notebook Overview

### 📄 `Proj2_BlackScholesMerton.ipynb` – Black-Scholes-Merton (BSM) Model

This notebook implements the closed-form Black-Scholes-Merton model for pricing European call and put options.  
Key components include:

- Derivation of BSM formula using standard mathematical functions
- Application to real-world option parameters (e.g., volatility, interest rate, maturity)
- Calculation of option Greeks (Delta, Gamma, Vega, Theta, Rho)
- Sensitivity analysis of option prices to underlying parameters

This model assumes continuous trading, log-normal price distribution, and no arbitrage.

---

### 📄 `Proj2_BTREE.ipynb` – Binomial Tree Option Pricing

This notebook implements a discrete-time binomial tree model for European and American options.  
Key components include:

- Construction of an up/down binomial lattice
- Recursive backward valuation of call/put options
- Visualization of convergence to BSM price as steps increase
- Comparison between European and American style pricing

The binomial method is especially useful for American-style options that cannot be priced with BSM's closed-form solution.

---

## 🔍 Concepts Covered

- 📈 European Option Valuation
- 🧮 Risk-Neutral Pricing and Arbitrage-Free Framework
- 🏗 Binomial Tree Lattice Construction
- 🎯 Sensitivity (Greeks) of Option Pricing Models
- 🔁 Convergence of Discrete Models to Continuous Models

---

## 🛠 Libraries Used

- Python Standard Math Library
- NumPy
- Matplotlib (for plotting, optional)

---

## 📁 Folder Structure

```
financial-engineering2/
└── project2_option_pricing/
├── Proj2_BlackScholesMerton.ipynb # Closed-form BSM pricing model
├── Proj2_BTREE.ipynb # Binomial tree implementation
└── README.md
```

---

## ✅ Notes

These notebooks are developed for educational purposes as part of a university course on Financial Engineering.  
They serve as a practical introduction to quantitative option pricing.
