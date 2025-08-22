# 🏎️ F1 NextGP Predictor

An AI-powered project that predicts **Formula 1 Grand Prix results instantly** using machine learning models and interactive controls.  
Built and tested in **Google Colab**, with support for all 2025 season tracks.

---

## 🚀 Features
- Predicts **Top 10 race results** for any F1 2025 track.
- Interactive **Colab UI** with dropdowns for:
  - Track selection (all 2025 GP circuits included)
  - Weather conditions (Dry, Rain, Mixed)
  - Track temperature (Cool, Normal, Hot)
  - Tyre strategy (1-stop, 2-stop, Aggressive)
  - Safety car probability (Low, Medium, High)
- Instant result generation with:
  - **Predicted Podium Finishers**
  - **Fastest Lap Probability**
  - **Driver DNF (Did Not Finish) Predictions**

---

## ⚙️ How It Works
1. **Data Collection** – Uses historical F1 race data, driver statistics, and environmental conditions.  
2. **Feature Engineering** – Combines track info, weather, tyre strategy, and driver/team performance metrics into structured datasets.  
3. **Model Training** – ML models (Random Forest, XGBoost, Logistic Regression) trained & validated with cross-validation.  
4. **Prediction Interface** – Built with `ipywidgets` in Google Colab, allowing dropdown-based controls for instant GP predictions.  

---

## 📊 Example Output
**Predicted Top 10 finishers for the selected race.**  
**Probability breakdown** for Podium, Fastest Lap, and DNFs.  

Visualizations of:
- Driver performance trends  
- Track-specific results  
- Impact of weather/tyre strategy  

---

## 🛠️ Tech Stack
- **Python** – Data Processing & ML  
- **Pandas, NumPy, Matplotlib** – Data Handling & Visualization  
- **Scikit-learn, XGBoost** – Prediction Models  
- **Google Colab** – Development Environment  
- **ipywidgets** – Interactive UI  

---

## ▶️ Getting Started
1. Open the Google Colab Notebook.  
2. Run all cells to set up the environment.  
3. Use the dropdown menus to configure:
   - Track, Weather, Temperature, Tyre Strategy, Safety Car Probability  
4. Click **Predict Next GP** to generate race predictions instantly.  

---

## 📈 Results & Accuracy
- Achieved **~75% accuracy** in predicting **race winners**.  
- Achieved **~55–60% accuracy** in predicting **podium finishers (any order)**.  
- Achieved **~70% accuracy** in predicting the **set of Top 10 finishers**.  
- Models validated across multiple seasons for robustness.  

---
