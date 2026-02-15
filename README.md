# OpVaR: Optimizing Liquidity vs. Supply Chain Risk 📉📦

## 🚀 Project Overview
A stochastic modeling tool built to resolve a conflict between Finance (Liquidity) and Operations (Service Levels). Used Monte Carlo simulations to calculate the Operational Value-at-Risk (OpVaR) for a Nairobi-based distributor.

## 💼 The Challenge
*   **Goal:** Reduce inventory holding by $2M to mitigate high interest rate costs.
*   **Constraint:** Highly volatile lead times from the Port of Mombasa.
*   **Conflict:** CFO wanted cuts; Supply Chain Director feared stockouts.

## 🛠️ Methodology
Moved beyond Excel "averages" to model the full distribution of risk:
*   **Engine:** Python (NumPy/Pandas)
*   **Technique:** Monte Carlo Simulation (10,000 scenarios)
*   **Variables:** Demand Volatility (Normal) & Lead Time Variance (Log-Normal)

## 📊 Key Results
*   Identified an **Efficient Frontier** where $1.5M could be released with negligible risk (<1.5%).
*   Showed that cuts beyond $1.5M caused exponential risk spikes.
*   **Outcome:** $1.5M Cash Unlocked | 98.5% Service Level Maintained.

## 💻 How to Run
1. Install dependencies: `pip install -r requirements.txt`
2. Run the simulation: `python simulation.py`
