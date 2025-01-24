# FarmForesight: Crop Yield and Rainfall Prediction Model

FarmForesight is a machine learning-based solution designed to assist farmers, agricultural experts, and policymakers in making data-driven decisions. The project leverages historical data to predict crop yields and analyze rainfall patterns, providing insights that optimize agricultural practices and resource allocation.

## Features
- **Rainfall Analysis:** Predict and analyze seasonal rainfall trends across different states.
- **Crop Yield Prediction:** Leverage machine learning to predict crop yields based on inputs like area, rainfall, and season.
- **Data Visualization:** Visualize key patterns and relationships using heatmaps, line charts, and scatter plots.
- **User-Friendly Workflow:** Designed for seamless deployment and adaptation to new datasets.

---

## Dataset
The model utilizes a dataset containing:
- Yield
- Overall_Rainfall
- County_wise_Rain

Ensure your dataset is in .csv format and follows the expected schema.

---

## Usage
- **Load the Dataset**: Update the dataset path in the notebook or adapt it for your own dataset.
- **Run Preprocessing**: Clean and preprocess the data, ensuring missing values and incorrect formats are addressed.
- **Visualize Data**: Generate graphs to understand patterns, including:

  Rainfall ***trends*** across states.

  Crop yield variations by ***season***.

- **Train Models**: Run machine learning models such as Random Forest to predict production yield and analyze features.
- **Evaluate Results**: Use metrics like ***R²***, ***MAE***, and ***RMSE*** for performance evaluation.

---

## Visualizations
- **Heatmaps**: Analyze correlations between rainfall, crop yield, and area.
- **Seasonal Trends**: Rainfall distribution over the years.
- **Yield Distributions**: Understand production variability.

---

## Key Results
- **Rainfall Patterns**: Insights into regions with consistent or erratic rainfall trends.
- **Yield Predictions**: Accurate forecasts with a high ***R²*** score.

---

## Requirements
- Python 3.7+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Acknowledgments
Special thanks to the open datasets and tools that made this project possible.

