# EDA_Titanic_Python

## Overview
This project explores the Titanic dataset using Python and various data analysis libraries to uncover insights into passenger survival rates based on socio-demographic factors. The dataset provides a glimpse into one of the most infamous maritime disasters in history.

## Project Goals
- Perform comprehensive EDA to understand the dataset's structure and contents.
- Visualize distributions and relationships between variables.
- Handle missing data appropriately.
- Extract meaningful insights into the factors influencing survival.

## Tools and Technologies Used
- Python
- Jupyter Notebook
- Libraries:
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Scikit-learn

## Project Steps
1. **Data Loading and Initial Exploration**
   - Loaded the dataset using Seaborn.
   - Examined the structure and summary statistics of the data.

2. **Handling Missing Data**
   - Addressed missing values in 'age', 'embarked', and 'embark_town'.
   - Employed median and mode imputation strategies.

3. **Univariate Analysis**
   - Visualized distributions of 'age', 'fare', and other variables using histograms and box plots.
   - Calculated summary statistics and assessed skewness and kurtosis.

4. **Bivariate Analysis**
   - Explored correlations between variables such as 'age', 'class', and 'survived'.
   - Visualized relationships using scatter plots and heatmaps.

5. **Multivariate Analysis**
   - Investigated interactions between multiple variables to uncover deeper insights.
   - Built a correlation matrix and heatmap to visualize relationships.

## Future Improvements
- Experiment with additional machine learning algorithms for comparative analysis.
- Enhance feature engineering to potentially uncover more predictive features.
- Perform deeper statistical testing and validation.

## Repository Structure
- `README.md`: Project overview and documentation.
- `titanic.ipynb`: Jupyter Notebook containing the complete EDA process.
- `titanic_dataset.csv`: Dataset used for analysis.

## Getting Started
To replicate this project locally:
1. Clone this repository.
2. Open and run `titanic.ipynb` in Jupyter Notebook.

## Contributors
- [Maryam Tariq](https://www.linkedin.com/in/maryamtariq1/)

## Acknowledgments
- This project was completed as part of an internship at CodexCue.
- Special thanks to mentors and colleagues for guidance and support.
