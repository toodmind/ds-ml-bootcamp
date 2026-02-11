# Car Price Data Preprocessing Pipeline

## Project Overview
This project demonstrates a complete data preprocessing pipeline for a messy tabular dataset containing car sales information. The goal was to transform raw, inconsistent data into a clean, scaled, and feature-engineered format ready for machine learning models.

## Dataset Description
The dataset includes the following features:
- **Price:** Mixed numeric and currency strings (Target).
- **Odometer_km:** Vehicle mileage.
- **Doors/Accidents:** Vehicle specifications and history.
- **Location:** Categorical geographic data with typos and missing values.
- **Year:** Manufacture year.

## Preprocessing Steps
1. **Target Cleaning:** Converted currency strings to numeric floats and handled skewness.
2. **Category Correction:** Fixed typos (e.g., "Subrb" to "Suburb") and standardized text.
3. **Imputation:** Filled missing values using Median (continuous) and Mode (categorical) strategies.
4. **Outlier Management:** Used IQR capping to clip extreme values in Price and Odometer.
5. **Feature Engineering:** Created `CarAge`, `Km_per_year`, `Is_Urban`, and `LogPrice`.
6. **Feature Scaling:** Standardized continuous variables using `StandardScaler`.

## Files in this Repository
- `l3_preprocess.py`: The main Python execution script.
- `car_l3_clean_ready.csv`: The final processed dataset.
- `reflection.md`: Detailed reasoning for technical decisions.
- `requirements.txt`: Python dependencies.

## How to Run
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
