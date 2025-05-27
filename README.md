# Insurance Data Analysis Project
Student ID: P146737
Course: STQD6324 Data Management (Semester 2, 2024/2025)
University: University Kebangsaan Malaysia (UKM)

## Project Overview
This project is a part of the Data Management course for the Masters of Data Science and Analytics at UKM. 
The objective is to demonstrate skills in data cleaning, exploration, visualization, and interpretation using a real-world dataset. I'm currently in the Insurance industry and I aspire to continue working in this domain upon completing my Masters program.
The analysis here is to identify the relationship between demographic and lifestyle factors (such as age, sex, BMI, smoking status) and medical insurance premium charged.

## Dataset Source
The chosen dataset is accessible at GitHub at https://github.com/stedy/Machine-Learning-with-R-datasets/blob/master/insurance.csv from the Machine Learning with R dataset repository.

### Features
- 'age' represents the age of the insured 
- 'sex' represents the gender of the insured 
- 'bmi' represents the Body Mass Index of the insured 
- 'children' represents the number of dependents of the insured
- 'smoker' represents the smoking status of the insured
- 'region' represents the residential area of the insured in United States
- 'charges' is the premium charged by life insurance company towards the insured

## Tools and Technologies
**Python(Jupyter Notebook via Google Colab)**
**Pandas** - for data manipulation
**Matplotlib and Seaborn** - for data visualization
**Apache Hive** - for data querying and processing
**GitHub** - for version control and publishing

## Repository contents
## Project Sections
### 1. Data Cleaning
- Verified dataset for missing values (none found)
- Converted categorical data to numerical format using label encoding
- Ensured data types and structure were suitable for analysis

### 2. Data Visualization
- Created histograms for age, bmi and charges to understand distributions
- Generated a correlation heatmap to identify feature relationships
- Developed boxplots to compare charges across smoker status and region
- Pair plots for multivariate visual analysis

### 3. Insights and Explanations
- Smoking status has a significant impact on insurance charges, with smokers incurring higher costs
- Higher BMI is associated with increased medical expenses
- Age shows positive correlation with insurance charges, indicating higher costs for older individuals

### 4. Recommendations
- Encourage wellness programs targeting smokers and high-BMI individuals to promote healthier lifestyles
- Consider age-based risk adjustment in premium calculation to account for increased costs with age
- Explore region specific insurance pricing strategies to reflect variations in healthcare usage

### 5. Conclusion
- This analysis provides key insights into factors affecting insurance charges. These insights can help life insurance companies to optimize pricing strategies and refine risk models, leading to more accurate and fair premium calculations.
