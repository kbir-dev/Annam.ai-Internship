# Crop Monitoring – AI Tools for Growth Analysis and Yield Prediction

## 🧠 Project Overview

Agriculture is the backbone of the Indian economy, yet farmers face major challenges due to unpredictable weather, market fluctuations, and a lack of real-time crop health insights. This project aims to build an AI-based system that:
- Predicts **crop yield** accurately using **machine learning** and **multi-modal datasets**.
- Ensures **transparency** and **trust** through **Explainable AI (XAI)**.
- Enables **real-time crop monitoring** using **NDVI** and satellite imagery.

We are among the first to operationalize the **CY-Bench dataset** in an India-focused application for field-level yield prediction, integrating it with NDVI, weather, and soil data.

---

## ✅ Week 1 Progress

### 🔄 Updated Problem Statement
With our mentor's guidance, we refined the project scope from multiple AgriTech tracks to a focused domain: **Crop Monitoring and Yield Prediction**. This makes the solution more targeted, feasible, and impactful.

### 📚 Literature Review
We reviewed 8 recent research papers (2020–2025) to understand:
- Common ML/DL techniques used in crop yield prediction.
- Gaps in multimodal data usage, explainability, and model generalization.
- Key limitations like black-box modeling, overfitting, and lack of Indian regional datasets.

### 🔍 Key Gaps Identified
- **Lack of multimodal data fusion** (NDVI + weather + soil).
- **Absence of Explainable AI** to interpret model decisions.
- **Minimal focus on feature engineering** and **hyperparameter tuning**.
- **Limited use of standardized datasets** in Indian context.

### 💡 Our Proposed Solutions
1. **Crop Yield Prediction using CY-Bench Dataset**
   - Dataset includes NDVI, FPAR, temperature, rainfall, soil data, crop calendars.
   - Perform **feature engineering** and **hyperparameter tuning**.
   - Use ML models with metrics like R², MAE, RMSE.
   - Apply **XAI** for model interpretability.

2. **NDVI-Based Crop Monitoring Tool**
   - Real-time region selection (max 5 km²) via lat/long or Google Maps.
   - Use **Bhuvan NRSC**, **Sentinel**, or **Landsat** imagery via Google Earth Engine.
   - Visualize crop health and detect anomalies.

3. **Weather & Soil Data Integration**
   - Use **Open Meteo API** for real-time and historical weather/soil info.
   - Augment yield prediction with environmental variables.

---

## 👥 Team Contributions

| Member         | Contribution                                                                 |
|----------------|------------------------------------------------------------------------------|
| Neeraj Jaiswal | Dataset feasibility study, validated Open Meteo, CY-Bench, and satellite data |
| Karanbir Singh | Conducted real-world farmer interview to understand practical problems        |
| Komal, Sonu, Jatin | Performed in-depth literature study of recent crop yield prediction research papers |

---

## 📁 Files
- `Problem Statement Week 1 Report Updated.pdf` – Full report of Week 1 research and project scope

---

## 🚀 Next Steps (Week 2 Preview)
- Begin preprocessing CY-Bench data
- Start building feature extraction scripts
- Set up NDVI visualization using Google Earth Engine

---

## 📌 References
Detailed references and paper summaries are available in the attached Week 1 report.

