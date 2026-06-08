# DCF Valuation Model — Apple Inc. (AAPL)

## Objective
To build a Discounted Cash Flow (DCF) valuation model for Apple (AAPL) using
2024 Free Cash Flow data, projecting intrinsic enterprise value using Python-based
financial modelling.

## What This Project Covers
- Base FCF input from Apple's 2024 financials ($93,736M)
- 10-year FCF projection with two-stage growth rates (8% years 1-5, 4% years 6-10)
- Present Value calculation for each projected year using a 9% discount rate (WACC)
- Terminal Value computation using the Gordon Growth Model
- Enterprise Value = Sum of PVs + PV of Terminal Value
- Sensitivity analysis across discount rates (7% to 11%) showing EV impact

## Key Findings
- Base case Enterprise Value (9% WACC): ~$2.06 trillion
- Terminal Value accounts for ~59% of total Enterprise Value
- EV ranges from $1.61T (11% WACC) to $3.04T (7% WACC) — 
  highlighting the sensitivity of DCF models to discount rate assumptions

## Future Work
- Build DCF models for 3 additional companies across different sectors 
  (energy, pharma, consumer goods)
- Add a two-dimensional sensitivity heatmap varying both growth rate 
  and discount rate simultaneously
- Explore LBO (Leveraged Buyout) modelling as an extension to 
  existing valuation work

## Tools & Libraries
- Python, Jupyter Notebook
- pandas, numpy

## How to Run
1. Clone the repo
2. Install dependencies: `pip install pandas numpy`
3. Open `DCF_Valuation_Model.ipynb` in Jupyter Notebook

## Author
Snehil Kejriwal — Economics + B.Tech, BITS Pilani Hyderabad
