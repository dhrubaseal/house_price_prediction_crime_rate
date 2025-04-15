# House Price Prediction with Crime Rate Analysis

This project analyzes the relationship between crime rates and house prices using data analysis and statistical modeling techniques.

## Project Overview

This analysis explores how crime rates affect median home values in neighborhoods, providing insights into:
- The correlation between crime rates and house prices
- Statistical modeling of the relationship
- Visualization of trends and patterns

## Dataset

The dataset (`data/houseprice.csv`) includes the following key variables:
- Crime rate
- Median home value
- Other housing market factors:
  - Residential land zone information
  - Business acres
  - Charles River proximity
  - Nitric oxides concentration
  - Number of rooms
  - Age of property
  - Distances to employment centers
  - Highway accessibility
  - Property tax rates
  - Pupil-teacher ratio

## Requirements

The project requires the following Python packages:
```bash
pandas
numpy
matplotlib
seaborn
statsmodels
jupyter
```

You can install all required packages using:
```bash
pip install -r requirements.txt
```

## Analysis Features

1. **Data Exploration**
   - Loading and inspection of housing dataset
   - Missing value analysis
   - Basic statistical summaries

2. **Visualization**
   - Scatter plots of crime rate vs. home values
   - Regression plots showing trend lines
   - Statistical distribution visualizations

3. **Statistical Analysis**
   - Correlation analysis
   - Simple linear regression
   - Multiple regression with control variables
   - Statistical significance testing

## Key Findings

Based on the analysis:
- There is a negative correlation (-0.388) between crime rates and median home values
- For every 0.01 increase in crime rate, median home prices decrease by approximately $1.20

## Usage

1. Clone the repository:
```bash
git clone https://github.com/dhrubaseal/house_price_prediction_crime_rate.git
```

2. Create and activate a virtual environment (recommended):
```bash
python -m venv .hp_env
source .hp_env/bin/activate  # On Windows use: .hp_env\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Open and run the Jupyter notebook:
```bash
jupyter notebook house_price_prediction_crime_rate.ipynb
```

## Project Structure

```
house_price_prediction_crime_rate/
├── data/
│   └── houseprice.csv
├── house_price_prediction_crime_rate.ipynb
├── requirements.txt
└── README.md
```

## Contributing

Feel free to fork this repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License - see the LICENSE file for details.