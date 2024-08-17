# Diabetes Prediction Using Pima Indian Heritage Dataset

## About the Dataset

This dataset is sourced from the National Institute of Diabetes and Digestive and Kidney Diseases. The primary objective is to predict whether a patient has diabetes based on diagnostic measurements provided in the dataset. The dataset specifically includes instances of female patients who are at least 21 years old and of Pima Indian heritage.

### Dataset Details

- **Source**: National Institute of Diabetes and Digestive and Kidney Diseases.
- **Format**: The dataset is provided as a `.csv` file.
- **Variables**:
  - **Independent Variables**: Several medical predictor variables.
  - **Dependent Variable**: `Outcome` (indicates whether the patient has diabetes).

## Work Done

### Data Exploration and Preparation

1. **Initial Exploration**:
   - **Shape of Dataset**: Checked the number of rows and columns.
   - **Data Information**: Used `.info()` to get a summary of the dataset, including data types and non-null counts.
   - **Descriptive Statistics**: Generated summary statistics using `.describe()` to understand the distribution of variables.
   - **Missing Values**: Checked for null values and handled them accordingly.

2. **Exploratory Data Analysis (EDA)**:
   - **Correlation Matrix & Heatmap**: Analyzed the relationships between variables using a correlation matrix and visualized it with a heatmap.
   - **Histograms**: Plotted histograms to examine the distribution of each variable.
   - **Violin Plot**: Used violin plots to visualize the distribution and density of variables.
   - **Boxplot**: Created boxplots to visualize the spread and identify outliers in the data.
   - **Barplot**: Used bar plots for categorical variables to explore their distributions.

### Data Preparation for Modeling

- **Feature Selection**: Assigned independent variables to `X` and the target variable to `Y`.
- **Data Standardization**: Standardized the data to ensure all features contribute equally to the model.
- **Train-Test Split**: Split the dataset into training and testing sets to evaluate model performance.

### Machine Learning Model

- **Support Vector Machine (SVM)**:
  - Trained an SVM model on the standardized data.
  - Evaluated accuracy on both training and testing sets to assess model performance.
  - Tested the model by inputting new data to predict whether a person is diabetic.

