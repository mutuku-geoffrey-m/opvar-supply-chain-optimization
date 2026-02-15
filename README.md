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

#### **2. LinkedIn Post Description**
When posting, focus on the *story* (the conflict) rather than just the code.

**Draft Post:**
> **Headline:** Excel averages lie. Distributions tell the truth. 📉
>
> I recently deployed a Monte Carlo simulation to resolve a standoff between a CFO and Supply Chain Director.
>
> **The Problem:** High interest rates were eating margins. The CFO wanted to slash inventory by $2M. The SC Director refused, citing volatile lead times at the Port of Mombasa. Neither was wrong, but their static Excel models couldn't quantify the trade-off.
>
> **The Fix:** I built a Python model to simulate 10,000 future scenarios, capturing the "long tail" risks of port delays that averages miss.
>
> **The Result:** We found the "Efficient Frontier"—we could safely release **$1.5M** in cash (a 15% cut) while maintaining a 98.5% service level. Beyond that point, the risk curve went vertical.
>
> It wasn't just about coding; it was about using data to find the safe zone between liquidity and risk.
>
> Check out the code and the "Risk Curve" visualization on GitHub: [Link to Repo]
>
> #SupplyChain #Python #DataScience #Logistics #FinOps #Nairobi
