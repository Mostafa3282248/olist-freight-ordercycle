# Olist Freight & Order Cycle — Analytics (Explainable & Actionable)

**Objective (Challenge Brief):** Explain what drives **Freight Value (shipping cost) per order**, how the **order cycle** changes over time, and how **customers vs. sellers** are distributed geographically—while accounting for different **order types**.

## What’s inside
- **Polished report (Excel):** `outputs/excel/Olist_Freight_OrderCycle_Report.xlsx`  
  - Top drivers per cluster (Quasi-Poisson GLM → clear “% per unit” multipliers)  
  - Simple items-per-order effect per cluster  
  - Top positive/negative drivers (ready to present)
- **Tables:** `outputs/tables/`  
  - `glm_per_cluster_interpretation.csv`, `glm_simple_items_per_cluster.csv`  
  - `cluster_top_positive_drivers.csv`, `cluster_top_negative_drivers.csv`  
  - (Optional) Fast-Moving categories (§4.2) buckets: `fast_moving_*.csv`
- **Figures (optional):** `outputs/figures/` (screenshots/charts for README or slides)

## How to view
Download and open the Excel report above (no setup needed). For reproducibility, source scripts live in `src/` (optional), and raw Olist data should be downloaded from Kaggle (see `data/README.md`); data files are not committed.

---
*This repo focuses on explainability for decision-makers: cluster-wise drivers turned into intuitive multipliers (e.g., “+5.3% per kg”, “+4.2% per +100 km”, “−2.0% per extra item”).*

