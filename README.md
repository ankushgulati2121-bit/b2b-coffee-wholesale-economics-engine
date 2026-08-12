# B2B Specialty Coffee Wholesale Pricing & Account Economics Engine
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ankushgulati2121-bit/b2b-coffee-wholesale-economics-engine/blob/main/B2B_Wholesale_Pricing_Engine.ipynb)
A commercial decision engine built in Python to evaluate B2B wholesale account profitability, equipment CAPEX payback timelines, and logistics cost-to-serve across regional hospitality accounts in New Zealand.

---

## Business Problem & Context
In specialty coffee wholesale, sales managers frequently structure commercial contracts involving equipment subsidization (e.g., high-spec commercial espresso machine packages) in exchange for multi-year bean supply commitments.

Evaluating account profitability solely on gross bean margin often obscures the true net contribution once equipment payback schedules and ongoing delivery logistics are accounted for. This tool simulates complete account economics to help commercial teams evaluate deal viability and optimize contract terms.

---

## Key Features & Analytics

- **Dynamic Wholesale Price Tiers:** Automatically assigns volume-based wholesale pricing ($/kg) based on weekly account consumption thresholds.
- **Equipment CAPEX Amortization:** Calculates monthly payback schedules for subsidized hardware packages relative to contract lengths.
- **Logistics Cost-to-Serve Modeling:** Integrates weekly freight logistics and field support costs to calculate true Net Contribution Margin.
- **Deal Viability Categorization:** Automatically flags accounts as *Target Deal (High Yield)*, *Approved (Low Margin)*, or *Unviable (Restructure Needed)*.
- **Margin Sensitivity Analysis:** Generates sensitivity matrices evaluating how volume shifts and price-per-kg changes impact net margin percentage.

---

## Visualizations

### Account Viability & Equipment Payback Analysis
<img width="1118" height="369" alt="account_viability_scatter png" src="https://github.com/user-attachments/assets/75acf48f-f8d1-4cf4-aea9-5d1ebf689ba4" />


### Commercial Margin Sensitivity Heatmap
<img width="725" height="453" alt="margin_sensitivity_heatmap png" src="https://github.com/user-attachments/assets/2017afa3-f0d3-4a67-a482-ba6d6a2d5402" />


---

## Tech Stack
- **Language:** Python
- **Data Manipulation:** Pandas, NumPy
- **Data Visualization:** Seaborn, Matplotlib, Plotly Express

---

## How to Run

1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/b2b-coffee-wholesale-economics-engine.git](https://github.com/YOUR_USERNAME/b2b-coffee-wholesale-economics-engine.git)
