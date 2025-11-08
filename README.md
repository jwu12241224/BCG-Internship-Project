# BCG X — Global Supply Chain Optimization

This project is a hands-on demo of how a data scientist at **BCG X** might approach a real business problem.  
It combines machine learning, optimization, and clear storytelling to show how analytics can drive smarter supply chain decisions.

---

## 🌍 Problem Overview

A global manufacturer needs to ship products from multiple suppliers to several regions around the world.  
The challenge is balancing **cost, delivery time, emissions,** and **supply risk** — all while meeting demand and respecting supplier capacity.

The goal:  
> Find the most efficient shipment plan that minimizes overall cost and risk, while keeping emissions and delivery times under control.

---

## 🧠 What the Project Does

1. **Simulates realistic supply chain data**  
   Creates suppliers, regions, and transport modes (air, sea, rail) with unique costs, speeds, and emission factors.

2. **Predicts supplier disruption risk**  
   Trains a small Random Forest model to estimate the probability that each supplier might experience a delay or disruption.

3. **Optimizes shipment routes**  
   Uses linear programming to decide how much to ship from each supplier to each region using each transport mode — minimizing a blended objective (cost + CO₂ + time + risk).

4. **Visualizes key results**  
   - Cost and emission breakdowns by region  
   - Sensitivity analysis showing how results change when you care more about emissions vs. cost  
   - A short executive-style summary at the end  

---

## ⚙️ Tech Stack

- **Python**: pandas, numpy, scikit-learn, scipy, matplotlib  
- **No external data or dependencies** — the notebook generates its own dataset  
- **Runs fully offline** in under a minute  

---

## 🚀 How to Run It

1. Open `bcgx_supply_chain_optimization.ipynb`  
2. Run all cells (top to bottom)  
3. Read the “Executive Summary” section at the end for insights and recommendations  

---

## 📊 Why It’s a Good Fit for BCG X

- **End-to-end workflow**: from data generation to modeling to optimization and communication  
- **Business-first mindset**: clear trade-offs between profit, risk, and sustainability  
- **Explainable results**: simple visuals and an executive summary instead of black-box outputs  
- **Scalable logic**: could easily extend to real supplier datasets or integrate into dashboards  

---

## 🗂 Files Included

- `bcgx_supply_chain_optimization.ipynb` — the full analysis notebook  
- `README.md` — this overview and documentation  
- `Executive_Brief.pdf` — one-page summary for quick context  
