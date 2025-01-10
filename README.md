# Tokyo Rental Rate Forecasting

## Project Overview
This project, developed in Summer 2024, predicts rental rates for residential properties along Tokyo’s Odakyu Line using machine learning. The model analyzes property features like proximity to train stations, building age, and square footage to provide actionable insights for renters, investors, and property managers.

---

## Key Features
- **Data Collection**: Scraped data from 776 rental properties across 52 pages using `BeautifulSoup`.
- **Data Preprocessing**:
  - Removed irrelevant features and handled missing values.
  - Created new variables, including building age and dummy variables for room types.
- **Visualization**:
  - Rental trends and correlations visualized using bar graphs, box plots, and heatmaps.
- **Model Development**:
  - A linear regression model achieved an R² of 0.85.
- **Web Deployment**:
  - User-friendly prediction app deployed via Flask on PythonAnywhere.

---

## Data and Methods

### Data Source
- Data scraped from [Real Estate Japan](https://realestate.co.jp/en/rent).

### Preprocessing
- Filtered properties along the Odakyu Line.
- Added dummy variables for categorical data and standardized numerical features.

### Visualization
- **Trends**:
  - Rental properties distribution by station.
- **Relationships**:
  - Rent vs. distance to the nearest station.

---

## Model Performance
| Metric       | Value (JPY) |
|--------------|-------------|
| **R²**       | 0.85        |
| **MAE**      | 18,123.36   |
| **RMSE**     | 23,705.81   |

---

## Web Application
The project includes a deployed web interface that enables users to:
- Input property features like building age, square footage, and proximity to stations.
- Obtain instant rental rate predictions.

🔗 **Try it out here**: [Tokyo Rental Predictor](https://coco2525.pythonanywhere.com/regression)

---

## Applications
- **First-time Renters**: Estimate rental costs for planning purposes.
- **Investors and Agents**: Strategically evaluate rental properties.
- **Current Tenants**: Compare rents with market rates.

---

## Future Enhancements
1. Expand the dataset to include seasonal and economic trends.
2. Explore alternative machine learning models for improved accuracy.
3. Extend the model to other regions in Tokyo or Japan.

---

## Author
- **Momo Ogawa**  
