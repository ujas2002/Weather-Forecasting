
This project analyzes the climate data in Delhi using the Daily Delhi Climate dataset. The dataset contains information about daily mean temperature, humidity, wind speed, and mean pressure in Delhi over several years.

## Requirements
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- plotly
- prophet

## Usage
1. Clone the repository or download the files.
2. Make sure you have all the required packages installed. You can install them using pip:
   ```
   pip install pandas numpy matplotlib seaborn plotly prophet
   ```
3. Run the code in a Python environment such as Jupyter Notebook or any IDE.

## Files
- `DailyDelhiClimateTrain.csv`: The dataset file containing daily climate data.

## Data Analysis
The code performs the following analysis and visualization tasks:

1. Data loading and initial exploration:
   - Loads the dataset using pandas.
   - Displays the first few rows of the dataset.
   - Computes basic statistics of the dataset.

2. Visualization of climate trends:
   - Plots the mean temperature in Delhi over the years.
   - Plots the humidity in Delhi over the years.
   - Plots the wind speed in Delhi over the years.
   - Creates a scatter plot to visualize the relationship between temperature and humidity.

3. Time-based analysis:
   - Converts the "date" column to the datetime format.
   - Extracts the year and month from the date.
   - Plots the mean temperature change in Delhi over the years, grouped by month.

4. Forecasting using Prophet:
   - Renames the columns required by the Prophet library.
   - Initializes a Prophet model.
   - Fits the model to the data.
   - Makes future predictions for the next 365 days.
   - Plots the forecasted data.

## Limitations
- The dataset used in this analysis may not represent the most recent climate data in Delhi.
- The forecasted data should be interpreted with caution as they are based on historical trends and may not accurately predict future climate patterns.
