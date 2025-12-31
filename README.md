# Solar Energy Production Prediction (Aswan, Egypt)

##  Project Overview
This project applies Machine Learning to predict solar energy output based on meteorological data collected from **Aswan, Egypt** (Benban Solar Park region). The goal is to classify daily solar production into **Low, Medium, or High** categories to assist in grid stability and energy management.

##  Dataset
The dataset includes daily weather observations:
- **Features:** Average Temperature, Humidity, Wind Speed, Pressure, Dew Point.
- **Target:** Solar PV Output (Classified into Low, Medium, High).
- **Source:** [Mention source if you have it, e.g., NASA Power or Local Station].

## Technologies Used
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **Scikit-Learn** (Decision Tree, KNN, LDA, Logistic Regression)
- **Data Viz:** Heatmaps, 3D Scatter Plots, ROC Curves.

##  Key Results
- **Best Model:** Decision Tree Classifier (**65% Accuracy**).
- **Key Insight:** The relationship between Temperature and Solar Output is **non-linear**. Simple linear models (Logistic Regression) failed (~30% acc), while rule-based models (Trees) succeeded.
- **Top Features:** Temperature and Humidity were the strongest predictors of solar output.

##  How to Run
1. Clone the repo:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/solar-energy-prediction-aswan.git](https://github.com/YOUR_USERNAME/solar-energy-prediction-aswan.git)
