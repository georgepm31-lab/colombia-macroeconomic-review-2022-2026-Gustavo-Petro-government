# Colombian Macroeconomic Review (2022–2026): Structural Shifts, Policy Trade-Offs, and Key Indicators

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue.svg)](https://www.python.org/)
[![Libraries](https://img.shields.io/badge/Libraries-Pandas%20%7C%20Matplotlib%20%7C%20Seaborn-orange.svg)]()
[![Data Sources](https://img.shields.io/badge/Data-DANE%20%7C%20BanRep%20%7C%20CARF-green.svg)]()
[![Status](https://img.shields.io/badge/Status-Completed-success.svg)]()

## Executive Overview
This project presents an empirical macroeconomic assessment of Colombia during the presidential administration of Gustavo Petro (August 2022 – August 2026). 

The central thesis of the evaluation demonstrates that Colombia's macroeconomic path did not experience an outright collapse or an industrial leap; rather, it navigated an intense structural tension between **accelerated social redistribution** and **depressed private capital formation**.

Utilizing official time series from primary statistical authorities—the **National Administrative Department of Statistics (DANE)**, the **Central Bank (Banco de la República)**, and the **Autonomous Fiscal Rule Committee (CARF)**—this repository tracks real output, monetary transmission, sovereign debt dynamics, and household welfare indicators.

The empirical findings highlight a defining structural tension: **accelerated social redistribution and poverty reduction** accompanied by **depressed private capital formation and severe fiscal rigidity**.

---

## Macroeconomic Balance Sheet: In-Depth Pros & Cons Matrix

| Dimension | Policy Interventions & Positive Outturns (Pros) | Structural Costs & Lingering Vulnerabilities (Cons) |
| :--- | :--- | :--- |
| **Monetary & Prices** | • **FEPC Unwinding:** Elimination of the regressive ~COP 36T fuel subsidy deficit.<br>• **Disinflation:** Convergence of headline CPI from 13.34% to the ~3.6% target range.<br>• **Institutional Autonomy:** Respected Central Bank independence throughout the tightening cycle. | • **Prolonged Restrictiveness:** Fuel price adjustments kept regulated CPI high, forcing the Central Bank to maintain peak rates (13.25%) longer than regional peers, curbing domestic credit. |
| **Growth & Production** | • **Averted Technical Recession:** Countercyclical public administration spending (+3.8%) and agricultural recovery buffered output during the 2023–2024 slowdown. | • **Investment Slump:** Gross Fixed Capital Formation dropped to ~15% of GDP (vs. historical 21%).<br>• **Contraction in Core Sectors:** Severe multi-quarter slowdown in manufacturing (-1.8%) and housing construction (-3.9%). |
| **Labor & Living Standards** | • **Purchasing Power Expansion:** Consecutive real minimum wage increases (+2.8% to +6.8% in real terms).<br>• **Poverty Compression:** Monetary poverty declined from 36.6% to under 30%.<br>• **Unemployment Containment:** Headline joblessness maintained in single digits (~9.1%–9.7%). | • **The Informality Ceiling:** Informality remained stubbornly entrenched above 54% of the workforce, showing that statutory wage hikes primarily benefited formal payrolls without integrating the informal base. |
| **External & FX Accounts** | • **External Balance Correction:** Current Account deficit narrowed from -6.2% of GDP in 2022 to -2.4%.<br>• **Currency Normalization:** COP/USD recovered from late-2022 overshooting (~COP 5,000) back to the COP 3,900–4,150 corridor.<br>• **Tourism Expansion:** Non-extractive service exports reached record highs. | • **De-investment Compression:** The external balance adjustment was largely driven by compressed imports of capital goods rather than a non-traditional export boom.<br>• **Extractive FDI Decline:** Moratoriums on new exploration contracts cut oil & mining foreign investment by >50%. |
| **Fiscal Accounts & Debt** | • **Tax Reform (Law 2277):** Initial revenue boost and progressive taxation framework introduced in 2022–2023. | • **Fiscal Squeeze & Debt Rigidity:** Central government deficit widened back to -5.6% of GDP in 2024, requiring mandatory spending freezes.<br>• **Capital Crowding Out:** Public debt interest payments (4.6% of GDP) surpassed productive public investment (3.3% of GDP). |

---

## Project Structure

```text
├── notebooks/
│   └── colombia_macroeconomic_review_2022_2026.ipynb   # Complete executable analysis
├── README.md                                           # Project documentation & scorecard
└── requirements.txt                                    # Python environment dependencies
