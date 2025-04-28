# Elevatelabs-DA-Task5
 
Objective: Extract insights using visual and statistical exploration.

# Exploratory Data Analysis (EDA) on Titanic Dataset  

## Overview  
This project conducts an Exploratory Data Analysis (EDA) on the Titanic dataset to analyze the factors contributing to the survival of passengers. The analysis leverages statistical and visual tools provided by Python libraries.  

## Objectives  
- Extract insights through visual and statistical exploration.  
- Identify relationships and trends among various factors affecting survival rates.  

## Tools Used  
- **Python 3.x**  
- **Pandas** for data manipulation  
- **Matplotlib** and **Seaborn** for data visualization  
- **Scikit-learn** for machine learning (model building)  

## Dataset  
- The Titanic dataset, sourced from Kaggle, contains diverse information about the passengers, including demographics and survival status.  

## Steps Taken  
1. **Data Loading**: Imported the Titanic dataset using Pandas.  
2. **Initial Data Exploration**:   
   - Used `.describe()`, `.info()`, and `.value_counts()` to gain insights into the dataset.  
   - Detected and handled missing values appropriately.  
3. **Data Visualization**:  
   - Created count plots for categorical variables (e.g., `Survived`, `Pclass`, `Sex`).  
   - Constructed histograms and heatmaps to examine the distribution and correlation of numerical features.  
   - Developed box plots to analyze the impact of specific factors (e.g., `Age`, `Fare`) on survival.  
   - Used subplots to organize multiple visualizations in a coherent layout.  
4. **Insights**:   
   - Observed that gender and passenger class significantly influenced survival rates.  
   - Analyzed the relationship between age, family size, and survival outcomes.  
5. **Machine Learning Model**:   
   - Built a Logistic Regression model to predict survival based on selected features.  
   - Evaluated model accuracy, emphasizing the importance of preprocessing steps.  

## Visual Insights  
The project includes various visual outputs to illustrate findings from the analysis, showcasing the relationships between features and survival rates.  

## Challenges and Resolutions  
- **Handling Missing Data**: Implemented strategies to fill missing values and drop non-essential columns to optimize analysis.  
- **Visualization Updates**: Adapted to library changes by switching from deprecated functions (like `sns.distplot`) to updated alternatives (`sns.histplot`).  

## Conclusion  
This EDA provided valuable insights into the factors influencing survival on the Titanic. These findings can serve as a basis for further predictive modeling or in-depth analysis.  

## Submission  
This repository contains:  
- Jupyter Notebook (`ELEVATELABS_Task5.ipynb`)  
- This README file  
- Visualizations and outputs from the analysis  
- The Titanic dataset files (`train.csv`, `test.csv`) 

## Acknowledgments  
Thanks to Elevate Labs for the opportunity to perform this project.   
