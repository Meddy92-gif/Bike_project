# Bike Share Data Analysis

## Overview
This repository contains Python scripts for analyzing bike share data, exploring patterns related to weather conditions, user behavior, and seasonal variations. The dataset used includes daily weather information and ride statistics for casual and member users between 2021 and 2023.

## Features
- **Data Cleaning & Preparation:**
  - Handles missing values and duplicate records
  - Converts date column to datetime format and sets it as index
  - Adds new categorical features such as seasons, holidays, and weekends
- **Exploratory Data Analysis (EDA):**
  - Scatter plots to visualize ride distribution based on temperature and wind speed
  - Pie and bar charts for user type comparisons (casual vs. member)
  - Seasonal trends and holiday effects on ride counts
- **Weather Impact Analysis:**
  - Categorization of weather conditions (clear sky, rain, drizzle, snowflakes)
  - Investigation of temperature and wind speed correlations with ride volume
- **Predictive Modeling:**
  - Polynomial regression to analyze ride demand based on temperature
  - Linear regression to estimate total rides based on multiple factors
- **Geospatial Analysis:**
  - Integration of Folium for mapping bike stations with geolocation data
  - Overlaying GeoJSON data for visual representation

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/bikeshare-analysis.git
   cd bikeshare-analysis
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Dataset
The dataset used in this project consists of:
- **Bike share data (CSV format):** Contains ride details including user type, date, and weather-related attributes.
- **GeoJSON file:** Used for mapping bike station locations.

## Usage
### Running the Script
To perform the analysis and generate visualizations, run the main script:
```bash
python analysis.py
```

### Notebooks
For interactive analysis and visualization, open the Jupyter Notebook:
```bash
jupyter notebook analysis.ipynb
```

## Results
- Identification of seasonal patterns and peak usage periods
- Insights into the impact of temperature and weather conditions on bike usage
- Prediction models for estimating ride demand

## Dependencies
The following Python libraries are used in this project:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `folium`

## Contributions
Contributions are welcome! Feel free to fork this repository, submit pull requests, or raise issues.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact
For any inquiries, please contact:
- **Name:** Media Haji Younis
- **Email:** mediahajo@gmail.com
- **LinkedIn:** [Media Haji Younis](https://www.linkedin.com/in/media-h-younis)
- **GitHub:** [Meddy92](https://github.com/Meddy92)

