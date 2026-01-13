# Prairies-Crop-Land-Mask
A workflow to refine crop mask for the Prairies cropland using-AAFC-and-AlphaEartth-data

📄 Overview

This project produces a crop vs non-crop land mask for the Canadian Prairies (2017–2024) using sample data from Agriculture and Agri-Food Canada (AAFC) and inputs from AlphaEarth. It leverages machine-learning classification (Random Forest) to generate annual masks, and computes crop frequency maps over the 8-year period.

📊 Data & Methods
✅ Training & Reference Data

AAFC crop vs non-crop samples — used as reference data for classification
Data covers the entire Prairie Provinces region

🛰️ Input Data
AlphaEarth data — used as predictors for land cover classification

🔄 Workflow

Collect and preprocess AAFC reference samples and AlphaEarth predictors.
Train a Random Forest classifier for each year.
Predict crop vs non-crop for the full study area.
Generate annual crop masks (2017–2024).
Aggregate annual masks to compute crop frequency map (how often each pixel was classified as crop over the period).


<img width="1754" height="815" alt="image" src="https://github.com/user-attachments/assets/0002f9c3-a64b-4148-b34e-b6267b7ab786" />


🎯 Purpose & Applications

Provide a reliable crop vs non-crop mask over time for the Prairies
Enable crop frequency analysis, useful for:
Land use change studies
Agricultural monitoring
Crop rotation / cropping intensity research
Environmental and soil-health assessments
Serve as baseline data for further modeling (soil, yield, hydrology, climate impacts)

📬 Contact & Citation
Thuan Ha
thua.ha@usask.ca
Research Officer, University of Saskatchewan
GitHub: https://github.com/thuanhavan
