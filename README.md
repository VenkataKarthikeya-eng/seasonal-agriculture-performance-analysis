Seasonal Agriculture Performance Analysis

A Python-based data analytics project focused on understanding how agricultural performance changes across different seasons.

Project Overview

Agricultural performance can vary with seasonal conditions, crop selection, environmental factors, resource usage, farming practices, and economic conditions. This project analyzes an agricultural dataset to identify these patterns and compare performance across seasons.

The analysis is performed using exploratory data analysis, descriptive statistics, and data visualization.

Objectives
Understand the structure and quality of the agricultural dataset.
Clean and prepare the data for analysis.
Compare agricultural performance across seasons.
Analyze crop performance across different seasons.
Study relationships between environmental conditions and yield.
Examine irrigation and resource usage.
Analyze production, revenue, cost, and profit.
Identify potential outliers and unusual observations.
Use statistical analysis and visualization to support findings.
Develop meaningful insights and data-based recommendations.
Dataset

Dataset: seasonal_agriculture_performance_dataset.csv

The dataset contains 4,000 records and 28 columns covering agricultural activities across different seasons and locations.

Main Categories
Farm and geographical information
Crop and seasonal information
Environmental conditions
Soil and nutrient information
Irrigation and farming resources
Yield and production
Water usage and efficiency
Market price, revenue, cost, and profit
Disease and pest risk
Important Variables
Farm_ID
State
District
Crop
Season
Farm_Area_Hectares
Rainfall_mm
Avg_Temperature_C
Humidity_pct
Soil_pH
Irrigation_Method
Yield_Tonnes_Ha
Production_Tonnes
Revenue_INR
Total_Cost_INR
Profit_INR
Water_Used_m3
Water_Efficiency_t_per_1000m3
Disease_Pest_Risk_pct
Tools and Technologies
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
Analysis Performed
1. Data Understanding
Dataset shape
Column names
Data types
First and last records
Statistical summaries
Unique-value analysis
2. Data Quality Analysis
Missing-value checking
Duplicate checking
Missing-value treatment
Variable classification
3. Statistical Analysis
Mean
Median
Standard deviation
Minimum and maximum
Range
Interquartile range
Season-wise statistical summaries
4. Univariate Analysis
Season distribution
Crop distribution
Yield distribution
Profit distribution
Rainfall distribution
Boxplot analysis
5. Outlier Analysis

Potential outliers are identified using the IQR method. Extreme observations are investigated rather than being removed automatically.

6. Bivariate Analysis

Relationships and comparisons are studied using:

Season vs Yield
Season vs Profit
Season vs Water Usage
Rainfall vs Yield
Farm Area vs Production
Irrigation Method vs Yield
7. Multivariate Analysis
Crop and Season vs Yield
Irrigation Method, Season and Yield
Rainfall, Farm Area, Season and Yield
Yield, Farm Area, Season and Profit
Pair plots
Correlation heatmap
8. Seasonal Comparison

The project compares important measures such as:

Average yield
Total production
Average profit
Total profit
Water usage
Water efficiency
Key Findings

Based on the current analysis:

The dataset contains 4,000 records and 28 variables.
Kharif has the highest average yield at approximately 5.63 tonnes/ha.
Rabi has an average yield of approximately 5.04 tonnes/ha.
Zaid has the lowest average yield at approximately 4.64 tonnes/ha.
Kharif has the highest average profit in the current dataset.
Zaid shows a negative average profit.
Zaid also has the highest average water usage.
Sugarcane shows the highest average yield across the analyzed seasons.
Potential outliers are present in variables such as profit, production, water efficiency, and yield.
Correlation and visualization analysis are used to identify relationships between important variables.

These findings describe patterns in the available dataset and should not be interpreted as proof of cause-and-effect relationships.

Project Structure
seasonal-agriculture-performance-analysis/
│
├── seasonal_agriculture_performance_dataset.csv
├── Seasonal_Agriculture_Performance_Analysis.ipynb
├── README.md
└── Seasonal_Agriculture_Performance_Analysis_Presentation.pptx
How to Run
Clone this repository.
git clone https://github.com/your-username/seasonal-agriculture-performance-analysis.git
Open the project folder.
cd seasonal-agriculture-performance-analysis
Install the required Python libraries.
pip install pandas numpy matplotlib seaborn jupyter
Start Jupyter Notebook.
jupyter notebook
Open:
Seasonal_Agriculture_Performance_Analysis.ipynb
Make sure the dataset file is available in the same project directory.
Project Output

The project produces:

Data-quality summaries
Statistical summaries
Seasonal comparisons
Crop performance comparisons
Distribution plots
Boxplots
Bar charts
Scatter plots
Pair plots
Correlation heatmaps
Outlier analysis
Data-based insights and recommendations
Future Scope

The analysis can be extended by:

Adding data from multiple years.
Performing deeper state and district-level comparisons.
Conducting crop-specific seasonal studies.
Performing statistical hypothesis testing.
Building an interactive dashboard.
Developing predictive models for future yield or profit estimation.
Author

Cherukuri Venkata Karthikeya
Vellore Institute of Technology – Amaravati (VIT-AP University)

License

This project is created for academic and educational purposes.
