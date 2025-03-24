# Delhi Precipitation Analysis (1997-2022)

## Project Overview

This project analyzes precipitation data in Delhi from 1997 to 2022. The dataset was cleaned, missing values were handled, and various statistical and visual analyses were performed to understand trends, extreme rainfall events, and seasonal variations.

## Dataset

- **Source**: Delhi NCR Safdarjung weather station  https://www.kaggle.com/datasets/vanvalkenberg/historicalweatherdataforindiancities/data
- **Time Period**: 1997-2022
- **Attributes**: Date, Precipitation (mm), and other meteorological parameters
- **Total Records**: 9337 (post-filtering for 1997-2022)

## Data Preprocessing

- Filtered data to include only 1997-2022.
- Handled missing values using different methods:
  - **Zero Imputation**: Replaced missing values with 0.
  - **Linear Interpolation**: Estimated missing values based on adjacent data points.
  - **Monthly Average Imputation**: Filled missing values with the average precipitation for that specific month across all years.

## Visualizations

The following visualizations were created to depict precipitation trends and insights:

1. **Precipitation Trends Over Time**

   - Line plot showing daily precipitation from 1997 to 2022.

2. **Average Monthly Precipitation**

   - Bar chart showing the mean precipitation for each month over 25 years.

3. **Total Yearly Precipitation**

   - Line plot with markers showing total annual precipitation.

4. **Extreme Rainfall Events**

   - Scatter plot highlighting extreme rainfall occurrences over time.

5. **Smoothed Precipitation Trends**

   - Rolling average plot (30-day window) for better trend visualization.

## Data Summary

A summary table was generated containing yearly and monthly precipitation values in a structured format, saved as an Excel file for documentation.

## How to Run

1. Clone this repository:
   ```sh
   git clone https://github.com/yourusername/Delhi-Precipitation-Analysis.git
   ```
2. Install dependencies:
   ```sh
   pip install pandas numpy matplotlib seaborn
   ```
3. Open `analysis.ipynb` in Jupyter Notebook and execute the cells.

## Insights

- **Seasonal Trends**: Monsoon months (July, August) experience peak rainfall.
- **Extreme Events**: Notable spikes in certain years due to heavy storms.
- **Long-term Variability**: Fluctuations in annual precipitation over the years.

## Future Improvements

- Incorporating additional weather parameters.
- Using ML models to predict future precipitation trends.
- Comparing precipitation trends with temperature variations.

## Author

Aabhas Sharma

## License

This project is licensed under the MIT License.

