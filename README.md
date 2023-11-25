# Data
- New York City and Jersey City Bike Share data from Kaggle (https://www.kaggle.com/datasets/akkithetechie/new-york-city-bike-share-dataset/)
- New York City weather data from (https://www.wunderground.com/history/daily/us/ny/new-york-city)

# Task
- Forecast the daily revenue for next 30 days
- Complete the forecast for only 7 selected stations of choosing
- Assume the cost of bike rental is $1.00 + $0.10 per minute until the ride lasts

### Task breakdown
- **Step 1: Data Cleaning, Feature Engineering**
  - Clean the bike trip dataset, handling missing data, and dropping unnecessary columns
  - Create additional features like day of the week, hour of the day, public holidays, user age, revenue calculation
- **Step 2: Exploratory Data Analysis (EDA)**
  - Perform EDA to understand variable distributions, identify outliers, and visualize trends in trip durations
  - Explore the distribution of trip durations and assess their impact on revenue calculations
- **Step 3: Data Merging**
  - Develop a robust merging strategy, ensuring proper alignment of time periods and handling missing data appropriately
- **Step 4: Correlation Analysis**
  - Conduct a thorough correlation analysis within both weather and bike trip datasets, identifying features strongly correlated with revenue
- **Step 6: Visualizing Full Data**
  - Visualize the data
- **Step 5: Station-Specific Visualization**
  - Select 7 stations
  - Explore dynamic and scalable solutions for station-specific analysis, possibly through functions or loops
- **Step 8: Feature Selections**
  - Finding the most important features responsible for revenue
- **Step 9: FB Prophet Model**
  - Implement the FB Prophet model for forecasting daily revenue for January, March, July, and October 2016
  - Focus on the 7 selected stations
  - Assume a cost of bike rental as $1.00 + $0.10 per minute
