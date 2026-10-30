Environmental Monitoring and Air Quality Intelligence

Project Overview
This project analyzes air quality across Indian cities by combining air pollution data, weather conditions, and city-level geographical information. It uses data visualization and machine learning to identify pollution patterns, estimate AQI, and generate air-quality alerts.

Objectives
- Analyze air pollution levels across Indian cities and regions.
- Identify highly polluted cities using the Air Quality Index (AQI).
- Study relationships between pollutants and weather conditions.
- Visualize seasonal and regional pollution trends.
- Develop machine learning models for AQI estimation and forecasting.
- Generate rule-based air-quality alerts and advisories.
- Create an interactive geographical air-quality heatmap.

Datasets
The project uses three CSV files:

- `cities.csv` — City metadata, geographical coordinates, state, region, and elevation.
- `air_quality_daily.csv` — Daily air-quality measurements and pollutant levels.
- `weather_daily.csv` — Daily weather measurements.

Place all three datasets in the same directory as the Jupyter Notebook before running it.

Technologies Used
- Python
- Jupyter Notebook / JupyterLab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Folium

Project Workflow

1. Data Loading:Import the air-quality, weather, and city datasets.
2. Data Cleaning and Integration:Convert date columns, merge datasets, and create time-based features.
3. Exploratory Data Analysis:Examine regional pollution levels and identify the ten cities with the highest average AQI.
4. Data Visualization: Generate pollution trend charts and a correlation heatmap.
5. AQI Estimation:Train a Random Forest Regressor and evaluate its performance using R² and Mean Absolute Error (MAE).
6. Time-Series Feature Engineering:Create AQI lag features and seven-day rolling averages.
7. AQI Forecasting: Train a Random Forest model and evaluate it using RMSE and R².
8. Geospatial Visualization:Generate an interactive AQI heatmap of Indian cities using Folium.
9. Air-Quality Alerts:Generate alerts based on AQI, wind speed, and precipitation thresholds.
10.Data Export:Save the integrated dataset as `environmental_intelligence_processed.csv`.

Installation

Install the required Python libraries:

pip install pandas numpy matplotlib seaborn scikit-learn folium jupyter


Expected Outputs
- Regional pollution summaries.
- Top ten most polluted cities by average AQI.
- Air-quality and weather correlation heatmap.
- Monthly AQI trend visualization.
- Random Forest feature-importance chart.
- Interactive geographical AQI heatmap.
- City-level air-quality alerts.
- Model evaluation metrics.
- Processed CSV dataset.

Limitations
- Results depend on the quality and availability of the input datasets.
- AQI alerts use simplified rule-based thresholds and are not official public-health advisories.
- Model predictions are estimates and require appropriate validation before real-world deployment.

Future Enhancements
- Develop an interactive dashboard using Streamlit or Power BI.
- Integrate regularly updated air-quality data.
- Compare additional machine learning and forecasting models.
- Improve time-series validation and model evaluation.
- Add advanced alerting and reporting features.

Author
Tanvi Ghatul
Pradnya Handrale
Aliya Shaikh
Gaurav Pandey
