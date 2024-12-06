# Analyzing the Impact of College Distance on Educational Attainment  

This project examines how the distance to the nearest college influences the educational attainment of students, measured in years of completed education. Using a dataset with various socioeconomic and demographic factors, the analysis employs regression models to assess the impact of distance while controlling for additional variables.

## Overview  

The dataset, `CollegeDistance.csv`, includes data on:
- **Distance to College (Dist)**: Measured in tens of miles.
- **Educational Attainment (ED)**: Years of completed education.
- Student and family characteristics like gender, race, family income, and parental education levels.
- Local economic factors such as county unemployment rates and state manufacturing wages.

Key questions explored in this project:  
1. How does increasing the distance to the nearest college impact educational attainment?  
2. Does controlling for additional variables alter the estimated impact of distance on education?  
3. How do socioeconomic and demographic factors influence educational outcomes?  

## Methods  

Two Ordinary Least Squares (OLS) regression models were implemented:  
- **Model 1**: Simple regression of educational attainment on college distance.  
- **Model 2**: Extended regression including additional control variables such as test scores, race, family income, and local economic conditions.  

### Key Findings  
- A 10-mile increase in distance to the nearest college reduces the average years of completed education by **0.073 years** in Model 1.  
- In Model 2, this effect reduces to **0.0315 years**, indicating omitted variable bias in the simpler model.  
- Socioeconomic factors like parental education and family income significantly contribute to explaining educational outcomes.  

## Data and Code  

- **Data**: [CollegeDistance.csv](CollegeDistance.csv)  
- **Notebook**: [Krish_Patel_Project.ipynb](Krish_Patel_Project.ipynb)  

The analysis was conducted in Python using pandas for data manipulation and statsmodels for regression analysis.  

## How to Use  

1. Clone this repository:
   ```bash
   git clone https://github.com/username/repository-name.git
