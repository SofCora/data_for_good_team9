# data_for_good_team9
## Objective
Help us identify the top 3 ohio cities primed for Move to Prosper to expand to (besides Columbus where they currently operate)

These cities should have the following properties:
- it's more of community or collection of towns (can be a metro area not rigid city lines)
- large number of families that are economically in need of our assistance(30-55 ami)
- also has a population of richer/better condition area for better education and philanthropy
- donors that can continuously support the program
- racially diverse so it'll be easier for families to transition.
# Data for Good: Identifying Ideal Cities for Family Prosperity

## Dataset
The dataset is sourced from:
- **U.S. Census Bureau** for demographic and income statistics
- **National Center for Education Statistics (NCES)** for school data
- **Crime Reports** for safety metrics

## Features Considered
- **Performance Index Score** (school effectiveness)
- **Student-Teacher Ratio** (quality of education)
- **Free and Reduced Lunch Ratio** (indicator of socioeconomic status)
- **Crime Rate** (safety factor)
- **Median Income & Income Inequality** (financial stability)
- **Housing Costs & Population Metrics** (cost of living and city size)

## Technical Approach
### Data Preprocessing
- Data cleaning and handling missing values
- Standardization and normalization of numerical features
- Removing outliers and ensuring consistency across datasets

### Machine Learning Techniques
- **K-Means Clustering** for city categorization
  - **Elbow Method & Silhouette Score** metric for optimal K selection
- **Principal Component Analysis (PCA)** for dimensionality reduction and feature correlation analysis

## Model Evaluation
- Clusters are analyzed based on key indicators such as crime rates, school performance, and median income.
- The most favorable clusters are identified based on their potential to uplift families through education and financial security.

## Results & Key Findings
- The analysis identified three optimal cities: **North Royalton, Loveland, and Centerville**.
- These cities exhibit low crime rates, high-performing schools, and balanced income equality, making them ideal for families looking for better opportunities.

## Future Improvements
- Incorporate additional factors such as healthcare access and employment opportunities.
- Enhance clustering accuracy using hierarchical clustering or deep learning approaches.
- Develop a web-based tool for real-time city recommendations.

## Requirements
- Python
- Pandas, NumPy, Scikit-learn
- Matplotlib & Seaborn (for visualizations)
- Jupyter Notebook

