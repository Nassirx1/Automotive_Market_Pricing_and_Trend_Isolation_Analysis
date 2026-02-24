# 🚗 Automotive Market Pricing & Trend Isolation Analysis

> A data-driven valuation framework for used vehicle markets isolating model price performance from macroeconomic noise and quantifying key depreciation drivers.

---

## Overview

Used vehicle pricing is  sensitive to external shocks supply chain disruptions, fuel price swings, and demand anomalies like the COVID-19 pandemic can distort market signals and make it difficult to evaluate how a specific vehicle model is truly performing. This project builds a granular pricing analysis pipeline that separates model-level trends from macroeconomic noise, producing clean, actionable insights for inventory pricing and procurement decisions.

---

## Key Features

### 📊 Granular Valuation Model — Pivot Table Cohort Segmentation
Vehicle records are segmented into cohorts by make, model, year, and fuel type using multi-dimensional pivot tables. This cohort-based structure allows the analysis to isolate how a specific model performs independently of market-wide events. For example, the 2020 COVID-19 demand spike — which inflated prices across the entire used car market — is flagged and isolated so that its distortion doesn't contaminate long-term model valuation trends.

### 🧹 Time-Series Cleaning Pipeline — Rolling Window Imputation
Historical pricing data is rarely complete. Auction gaps, discontinued trims, and sparse regional records leave holes in time-series that can mislead trend analysis. A **5-year rolling window imputation strategy** is applied to fill missing values by referencing local price behavior within a contextually relevant time horizon — long enough to capture trend patterns, short enough to remain sensitive to local economic conditions rather than blending across structurally different market periods.

### 📉 Correlation Analysis — Depreciation Driver Quantification
Pearson and Spearman correlation analyses are conducted between vehicle pricing and two primary depreciation drivers: **mileage** and **engine size**. Results are used to calibrate the valuation model and provide inventory managers with quantified, interpretable decision support — e.g., the expected price impact per 10,000 km of additional mileage for a given vehicle cohort.

## Participants in the project: 
Nassir Almotairi ,Abdullah Alqurashi, Rayan Majed and Mohammad Saad



