
## Hospital Patient Readmission & Length-of-Stay Analytics

A complete Python analytics workflow analyzing hospital patient data to understand the factors associated with length of hospital stay and patient readmission. 

### Project Overview: 

Hospitals lose significant resources to preventable readmissions and extended stays. This project simulates a hospital dataset and applies a full analytics pipeline — from data cleaning through predictive modeling — to identify which patient characteristics and clinical factors are most associated with longer stays and higher readmission risk.

### Objectives:
Understand and clean a hospital patient dataset

Explore relationships between patient characteristics and outcomes

Visualize length-of-stay and readmission patterns

Test whether observed differences are statistically significant

Predict length of stay using linear regression

Predict readmission risk using logistic regression

Translate findings into hospital-relevant recommendations

### Step	Description: 
1. Data Understanding	Import data, check shape/types, identify numerical vs categorical variables
2. Data Cleaning	Handle missing values, remove duplicates, correct data types
3. Exploratory Data Analysis	Average length of stay, readmission rates by age group and diagnosis
4. Visualization	Histogram, count plot, scatter plot, boxplot, correlation heatmap, interactive chart
5. Statistical Testing	Independent t-test (length of stay vs readmission), Chi-Square test (gender vs readmission)
6. Regression	Linear Regression to predict length of stay
7. Classification	Logistic Regression to predict readmission (Yes/No)
8. Interpretation	Translating statistical results into healthcare recommendations
   
### Sample Visualizations
<img width="755" height="657" alt="corr" src="https://github.com/user-attachments/assets/b57d2575-19d1-4526-9654-ab9ee459e5a1" />
<img width="677" height="487" alt="r-plot" src="https://github.com/user-attachments/assets/9001f612-272e-4e9e-8958-d613bda32fd9" />


### Key Findings:
Length of stay is most strongly associated with number of procedures and prior admissions, rather than age alone.

The Linear Regression model predicting Length of Stay achieved an **R² of 0.946** and an
  **RMSE of 0.57 days**, meaning Age, Number of Procedures, and Prior Admissions together
  explain about 94.6% of the variation in how long a patient stays, with predictions typically
  off by only about half a day.

