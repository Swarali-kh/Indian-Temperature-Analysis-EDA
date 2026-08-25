# Indian-Temperature-Analysis-EDA
Exploratory Data Analysis of Indian climate data — temperature, AQI, rainfall &amp; humidity trends across Indian cities using Python

Exploratory Data Analysis (EDA) on Indian climate data covering **temperature, Air Quality Index (AQI), rainfall, and humidity** across 10 major Indian cities, using Python.

## Dataset
- 7,310+ records
- Time period: 2024–2025
- Features: City, Date, Temperature (max/min/avg), AQI, AQI Category, Rainfall, Humidity

## Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Workflow
- Data cleaning: standardized column names, handled missing values (median for numeric, mode for categorical)
- Feature engineering: extracted Month, Year, and Season from date column
- Univariate & bivariate analysis with 8+ visualizations
- Correlation analysis using a heatmap
- City-wise and season-wise temperature comparison

## Key Insights
- Temperature shows a clear seasonal pattern  rises in summer, dips in winter, aligning with expected seasonal climate variation
- Rainfall distribution is heavily right-skewed most days show low/zero rainfall, with a smaller number of days showing high monsoon spikes
- Max, min, and average temperature are strongly correlated with each other, but AQI, humidity, and rainfall show almost no correlation suggesting these variables are largely independent
- Most AQI readings fall in a moderate range  not consistently "good" but also not consistently "severe"
- All 10 cities show a fairly similar average temperature range (29.5–30°C); Kolkata has the highest average, followed by Ahmedabad, while Jaipur has the lowest
- Summer has the highest median temperature and widest spread; winter has the lowest, with monsoon and post-monsoon falling in between
- The Temperature vs AQI relationship isn't very strong  suggesting AQI is influenced by factors beyond just temperature
- Humidity tends to increase alongside rainfall, showing a positive relationship



## Author
Swarali Khandagale
