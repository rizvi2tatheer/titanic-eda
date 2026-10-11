# TITANIC-EDA
Exploratory Data Analysis of the Titanic passenger dataset using Python

# Titanic Exploratory Data Analysis (EDA)-Project Overview
This project explores the Titanic passenger dataset to understand the data, identify patterns, and investigate which passenger characteristics were associated with survival. The analysis was completed in Python using a Jupyter notebook.
This is an exploratory data analysis project. It focuses on understanding and visualizing the data rather than building a predictive machine-learning model.
# Objectives
- Inspect the dataset structure and data types.
- Identify missing values and review summary statistics.
- Explore survival, age, fare, sex, passenger class, embarkation port, and family size.
- Use charts to identify patterns and relationships.
- Summarize findings and note areas for further analysis.
# Tools and Libraries
- Python
- Pandas — data loading and analysis
- NumPy — numerical operations
- Matplotlib — plotting
- Seaborn — statistical visualizations
- Jupyter Notebook in VS Code — analysis environment
# Key Findings
- The training dataset contains 891 passengers.
- 342 passengers survived and 549 did not survive, giving an overall survival rate of approximately 38.4%.
- The Age column has 177 missing values.
- The Cabin column has 687 missing values.
- The Embarked column has 2 missing values.
- Survival rates were substantially higher among female passengers than male passengers.
- First-class passengers had a higher survival rate than second- and third-class passengers.
- Fare values are strongly right-skewed: most passengers paid lower fares, while a small number paid much higher fares.
- Survival rates varied across age groups and family sizes.
- Survival rates also differed by embarkation port. This pattern may be related to other passenger characteristics and should not be interpreted as evidence that the port itself caused the difference.
- Scatterplots and the correlation heatmap helped explore relationships, but no single variable fully explains survival.
  
Data Quality Notes
Missing values were identified during inspection. 
In this EDA, missing age values are naturally excluded from age-based plots, and missing embarkation values are not represented in the embarkation-port comparison. 
The large number of missing cabin values is an important limitation.
Potential fare outliers were observed. 
They should be investigated in context rather than removed automatically. Correlations involving PassengerId should not be treated as meaningful relationships because it is an identifier, not a measured passenger characteristic.
Limitations
- This analysis identifies associations; it does not establish causation.
- Some groups, such as very large families or the oldest age group, may contain relatively few passengers.
- Missing values may affect comparisons.
- The analysis does not train or evaluate a machine-learning model.

Kaggle — Titanic: Machine Learning from Disaster
