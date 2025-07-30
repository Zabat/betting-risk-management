# 📊 Sports Betting Portfolio Simulations

This repository contains Python simulation code accompanying the paper:

**“Towards Sports Betting as a Financial Asset: An Investigative Analysis of Risk, Investment Potential, and Future Perspectives”**  
by René Manassé Galekwa, Jean Marie Tshimula, Etienne Gael Tajeuna, and Kyandoghere Kyamakya.

---

## 🚀 Overview

This project models key financial risk and optimization concepts in the context of sports betting:

- ✅ Leverage cycle dynamics
- ✅ Kelly criterion under uncertainty
- ✅ Correlated stress test simulations
- ✅ Tail risk and CVaR management
- ✅ Multi-panel visual analytics

---

## 📂 Structure

| File | Description |
|------|-------------|
| `simulation.py` | Main simulation script |
| `sports_betting_simulations.png` | Multi-panel figure output |
| `README.md` | This file |

---

## 📈 Key Simulations

### 1. Leverage Cycles  
Modeling capital amplification and collapse using recursive leverage functions with/without VaR caps.

### 2. Kelly Criterion under Uncertainty  
Adjusting optimal bet sizing when win probabilities are misestimated (via KL divergence penalty).

### 3. Stress Test Scenario  
Simulating simultaneous underdog wins and measuring impact on various bet types and risk controls.

### 4. CVaR Protection  
Estimating Conditional Value at Risk (CVaR) over 500 portfolio simulations and analyzing safe vs. danger zones.

---

## 🖼️ Sample Output

![Simulation Results](sports_betting_simulations.png)

---

## 📦 Dependencies

This project uses:

```bash
numpy
matplotlib
seaborn
scipy
