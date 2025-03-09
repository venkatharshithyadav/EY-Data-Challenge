EY Open Science AI & Data Challenge 2025

Urban Heat Island (UHI) Hotspot Prediction

Introduction:
This repository contains the implementation for the EY Open Science AI & Data Challenge 2025. The challenge focuses on predicting urban heat island (UHI) hotspots using machine learning. The goal is to develop a regression model that predicts UHI Index values for urban locations and identifies key factors contributing to heat intensity.

Problem Statement:
Urban heat islands (UHI) occur due to high building density and limited green spaces in cities, leading to temperature differences between urban and rural areas. This phenomenon impacts public health, energy consumption, and urban planning. The challenge involves predicting UHI hotspots based on provided dataset features.

Dataset:
Participants are provided with near-surface air temperature data in an index format, collected on 24 July 2021 in the Bronx and Manhattan regions of New York City. The dataset includes:
- Latitude & Longitude: Spatial coordinates of measurement points
- UHI Index: Temperature variation at a given point compared to the city's average

Approach:
1. Data Preprocessing: Cleaning and normalizing data, handling missing values
2. Exploratory Data Analysis (EDA): Understanding data distributions and key patterns
3. Feature Engineering: Creating additional relevant features
4. Model Selection & Training: Experimenting with regression models (e.g., Linear Regression, Random Forest, Gradient Boosting, Neural Networks)
5. Evaluation & Optimization**: Assessing performance using RMSE, R², and feature importance
6. Visualization**: Mapping hotspots and analyzing influential factors

Requirements:
To run the project, install dependencies using:
```bash
pip install -r requirements.txt
```

How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ey-uhi-challenge.git
   cd ey-uhi-challenge
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the data preprocessing script:
   ```bash
   python preprocess.py
   ```
4. Train the model:
   ```bash
   python train.py
   ```
5. Make predictions:
   ```bash
   python predict.py
   ```

Results:
- Model evaluation metrics
- Heatmaps & visualizations
- Insights on key contributing factors

Contributors:
- Venkat Harshith Yadav Govindappa (GitHub: https://github.com/venkatharshithyadav)
- Open for collaboration!
