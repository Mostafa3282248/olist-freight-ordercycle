<!-- اختياري: لو عملت CSS ضعه في docs/assets/style.css -->
<link rel="stylesheet" href="assets/style.css">

# Olist eCommerce — Freight & Lead-Time Analytics

> End-to-end analysis of Olist (Brazil) orders (2016–2018): data modeling, feature engineering, GLM (Quasi-Poisson) for interpretability, ensembles for accuracy, and cluster-based business summaries.

## 📊 Lead-time minis (Quarter × Order Status)

<p align="center"><b>Status: Delivered</b></p>
<p align="center">
  <img src="img/leadtime_minis_delivered.png" width="85%">
</p>

<p align="center"><b>Status: Canceled</b></p>
<p align="center">
  <img src="img/leadtime_minis_canceled.png" width="85%">
</p>

<p align="center"><b>Status: Invoiced</b></p>
<p align="center">
  <img src="img/leadtime_minis_invoiced.png" width="85%">
</p>

<p align="center"><b>Status: Processing</b></p>
<p align="center">
  <img src="img/leadtime_minis_processing.png" width="85%">
</p>

<p align="center"><b>Status: Approved</b> • <b>Status: Created</b></p>
<p align="center">
  <img src="img/leadtime_minis_approved.png" width="45%">
  <img src="img/leadtime_minis_created.png"  width="45%">
</p>

## Files
- `outputs/excel/Olist_Freight_OrderCycle_Report.xlsx`
- `outputs/tables/` (fast moving, cluster, glm)
