# Statistical Analysis of Insurance Claims

## Overview
This project aims to analyze a dataset of insurance claims to uncover relationships and correlations between various attributes. Leveraging this information can help insurance companies make better business decisions.

## Dataset
The dataset used in this analysis is available on Kaggle: [Insurance Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance).

### Dataset Information
The dataset includes the following features:
- **age**: Age of the primary beneficiary.
- **sex**: Gender of the insurance contractor (female, male).
- **bmi**: Body mass index, an index of body weight relative to height.
- **children**: Number of children covered by health insurance.
- **smoker**: Indicates whether the person is a smoker.
- **region**: Residential area in the US (northeast, southeast, southwest, northwest).
- **charges**: Individual medical costs billed by health insurance.

### Variable Types
- **Categorical Variables**: `sex`, `smoker`, `region`, `children`
- **Quantitative Variables**: `age`, `bmi`, `charges`
  - `children` is a discrete variable.
  - `age`, `bmi`, and `charges` are continuous variables.

## Descriptive Statistics
Summary statistics provide an overview of the dataset's central tendencies, variability, and distribution.

## Exploratory Data Analysis (EDA)
### Univariate Analysis
- **Box Plot**: Provides insights into the distribution and outliers in individual variables.
- **Histogram and Rug Plot**: Visualizes the distribution of continuous variables.

### Bivariate Analysis
- **Scatter Plots**: Explore relationships between two continuous variables.
- **Categorical Comparisons**: Compare categorical variables against continuous variables (e.g., charges by region, BMI by age group).

### Multivariate Analysis
- **Heatmaps**: Examine correlations between multiple variables.
- **Pair Plots**: Visualize relationships between pairs of variables in a multi-dimensional space.

## Statistical Analysis
This section involves hypothesis testing and other statistical methods to determine the significance of observed relationships.

## Project Files
- `insurance.csv`: The dataset file.
- `stat-analysis-insurance.ipynb`: Jupyter notebook containing the full analysis, including data loading, cleaning, EDA, and statistical testing.

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/vinayvaida27/Insurance-Claims-Statistical-Analysis.git
