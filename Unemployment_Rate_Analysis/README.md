# Unemployment Analysis in India

## Project Overview

This project analyzes unemployment trends in India using Python and data visualization techniques. The main goal is to explore unemployment rates over time, compare different regions and areas, and understand how the COVID-19 pandemic affected unemployment.

The project uses the **Unemployment in India** dataset and applies data cleaning, exploratory data analysis (EDA), statistical analysis, and visualization to identify important patterns and insights.

## Objectives

- Analyze unemployment rates in India over time.
- Compare average unemployment rates before and during the COVID-19 period.
- Identify the regions with the highest average unemployment rates.
- Compare unemployment rates between rural and urban areas.
- Explore the distribution of unemployment rates and detect outliers.
- Study the relationships between unemployment, employment, and labour force participation.

## Technologies Used

- **Python** – Main programming language.
- **Pandas** – Data loading, cleaning, and analysis.
- **NumPy** – Numerical operations and data processing.
- **Matplotlib** – Data visualization.
- **Seaborn** – Statistical charts and visualizations.
- **Google Colab** – Development and execution environment.

## Dataset

The project uses the `Unemployment in India.csv` dataset, which contains information about unemployment across different regions of India.

The dataset includes the following columns:

- `Region` – The region or state.
- `Date` – The date of the observation.
- `Frequency` – The frequency of data collection.
- `Estimated Unemployment Rate (%)` – The estimated unemployment rate.
- `Estimated Employed` – The estimated number of employed people.
- `Estimated Labour Participation Rate (%)` – The estimated labour force participation rate.
- `Area` – Whether the area is rural or urban.

The original dataset contains 768 rows. After removing 28 completely empty rows, 740 rows remain for analysis.

## Project Workflow

### 1. Data Loading

- Import the required Python libraries.
- Upload the CSV dataset to Google Colab.
- Load the dataset using Pandas.

### 2. Data Exploration

- Display the first five rows.
- Check the dataset's dimensions and data types.
- Generate descriptive statistics to understand the data.

### 3. Data Cleaning and Preparation

- Identify missing values and completely empty rows.
- Remove rows containing missing values.
- Check for duplicate records.
- Convert the `Date` column to datetime format.
- Extract the year and month.
- Create a `Covid_Period` column to distinguish between the periods before and during COVID-19.

For this analysis, dates before March 2020 are classified as **Before Covid**, while dates from March 2020 onward are classified as **During Covid**.

### 4. Exploratory Data Analysis (EDA)

The project includes the following analyses and visualizations:

- **COVID-19 Comparison:** Compare the average unemployment rate before and during the pandemic.
- **Unemployment Over Time:** Examine changes in unemployment rates across the observation period.
- **Monthly Analysis:** Compare average unemployment rates across calendar months.
- **Regional Analysis:** Identify the ten regions with the highest average unemployment rates.
- **Rural vs. Urban Comparison:** Compare unemployment rates by area.
- **Distribution Analysis:** Use a histogram to understand the distribution of unemployment rates.
- **Outlier Detection:** Use a box plot to identify unusually high or low values.
- **Correlation Analysis:** Explore relationships between unemployment rates, estimated employment, and labour force participation.

## Key Findings

The analysis produced the following results:

1. **Higher unemployment during COVID-19:** The average unemployment rate increased from approximately 9.51% before COVID-19 to 17.77% during the defined pandemic period.
2. **Significant increase in early 2020:** The unemployment rate showed a sharp rise around April and May 2020.
3. **Regional differences:** Tripura had the highest average unemployment rate among the regions in the dataset, at approximately 28.35%.
4. **Rural vs. urban areas:** Urban areas had a higher average unemployment rate (13.17%) than rural areas (10.32%).
5. **Outliers:** The box plot revealed unusually high unemployment observations in some regions and periods.
6. **Correlation results:** Unemployment had a weak negative correlation with estimated employment (-0.223) and an almost zero correlation with labour force participation (0.003).

These findings describe patterns in the dataset and do not, by themselves, establish that COVID-19 caused every observed change.

## How to Run the Project

1. Open [Google Colab](https://colab.research.google.com/).
2. Create a new notebook.
3. Upload `Unemployment in India.csv`.
4. Install any required libraries if they are not already available.
5. Copy the project code into the notebook.
6. Run the cells in order to generate the analysis and visualizations.

## Conclusion

This project explores unemployment trends in India and highlights differences across time, regions, and rural and urban areas. The results show a substantial increase in the average unemployment rate during the period classified as COVID-19, along with clear regional differences.

The project provided practical experience in data cleaning, exploratory data analysis, statistical summaries, correlation analysis, and data visualization using Python.

## Future Improvements

- Add interactive visualizations using Plotly.
- Create a dashboard to explore regional unemployment trends.
- Analyze individual states over time.
- Investigate additional economic indicators to better understand unemployment patterns.

## Author

Mayada Abou Hamdan
CodeAlpha Machine Learning Intern
