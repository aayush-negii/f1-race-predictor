🏎️ F1 NextGP Predictor

An AI-powered project that predicts Formula 1 Grand Prix results instantly using machine learning models and interactive controls.
Built and tested in Google Colab, with support for all 2025 season tracks.

🚀 Features

Predicts Top 10 race results for any Formula 1 2025 track.

Interactive Colab UI with dropdowns for:

Track selection (all 2025 GP circuits included)

Weather conditions (Dry, Rain, Mixed)

Track temperature (Cool, Normal, Hot)

Tyre strategy (1-stop, 2-stop, Aggressive)

Safety car probability (Low, Medium, High)

Instant result generation with:

Predicted Podium Finishers

Fastest Lap Probability

Driver DNF (Did Not Finish) Predictions

⚙️ How It Works

Data Collection – Uses historical F1 race data, driver statistics, and environmental conditions.

Feature Engineering – Merges track info, weather, tyre strategy, and driver/team performance metrics into structured datasets.

Model Training – ML models (Random Forest, XGBoost, Logistic Regression) trained & validated with cross-validation.

Prediction Interface – Built with ipywidgets in Google Colab, allowing dropdown-based controls for instant GP predictions.

📊 Example Output

Predicted Top 10 finishers for the selected race.

Probability breakdown for Podium, Fastest Lap, and DNFs.

Visualizations of:

Driver performance trends

Track-specific results

Impact of weather/tyre strategy

🛠️ Tech Stack

Python – Data Processing & ML

Pandas, NumPy, Matplotlib – Data Handling & Visualization

Scikit-learn, XGBoost – Prediction Models

Google Colab – Development Environment

ipywidgets – Interactive UI

▶️ Getting Started

Open the Google Colab Notebook [🔗 Link Here].

Run all cells to set up the environment.

Use the dropdown menus to configure:

Track, Weather, Temperature, Tyre Strategy, Safety Car Probability

Click Predict Next GP to generate race predictions instantly.

📈 Results & Accuracy

Achieved ~X% accuracy in predicting Top 10 positions (validated using cross-validation).

Models tested across multiple race seasons to ensure robustness.
