# Project Overview
This project involves comprehensive data exploration (EDA), visualization, and preparation/processing of popular Kaggle datasets, followed by the creation of predictive models using AutoML tools. The main objectives are:

1. **Tabular Data Analysis** (e.g., NYC Taxi or Airbnb dataset)
2. **Time Series Data Analysis** (e.g., Store Sales dataset)

Each dataset has undergone the following steps:

## Tasks Completed
### 1. Detailed Exploratory Data Analysis (EDA)
- Performed detailed manual EDA including descriptive statistics, data distribution analysis, and feature correlations.
- Utilized Auto EDA tools for deeper insights, ensuring cross-validation with manual observations.
- Created a variety of visualizations to represent trends, distributions, and correlations.

### 2. Data Preprocessing and Cleaning
- Handled missing values using techniques like forward/backward fill and interpolation.
- Capped and floored outliers based on the 1st and 99th percentiles to ensure robust modeling.
- Normalized and transformed features as needed.

### 3. Data Imputation and Anomaly Detection
- Conducted anomaly detection and eliminated outliers that could skew model performance.
- Applied clustering techniques (e.g., K-Means) to detect natural groupings and anomalies.
- Imputed missing values with appropriate methods to maintain dataset integrity.

### 4. Feature Engineering
- Created new features from existing data to enhance model predictive power.
- Selected relevant features using feature importance ranking and selection algorithms.

### 5. Model Building
- Used AutoML tools, including AutoViML, to build and compare a range of models.
- Experimented with various ML algorithms, including ensemble models, to find the best fit.
- Documented model performance metrics and selected the best-performing model based on cross-validation results.

## Tools and Libraries Used
- **Pandas**, **NumPy** for data manipulation
- **Matplotlib**, **Seaborn**, **Plotly** for data visualization
- **Scikit-learn** for preprocessing and manual feature selection
- **AutoViz**, **Sweetviz** for automated EDA
- **AutoViML** for AutoML model building
- **SciPy**, **Statsmodels** for statistical analysis
- **Jupyter Notebook** for development

## Notebooks and Results
### Tabular Data Analysis
- **Notebook**: `Auto_EDA_for_Airbnb_dataset_and_regression_using_AutoVIML.ipynb`
- **Description**: Comprehensive EDA, data preprocessing, and regression modeling on the Airbnb dataset.

### Time Series Data Analysis
- **Notebook**: `Store_Sales_Time_Series_Forecasting.ipynb`
- **Description**: Full EDA, data cleaning, feature engineering, and time series forecasting with AutoML.

## How to Use This Repository
1. **Clone the repository**:
   ```bash
   git clone <your-repo-url>
   ```
2. **Navigate to the project directory**:
   ```bash
   cd your-repo-name
   ```
3. **Run the notebooks**:
   Open the Jupyter Notebooks in your local environment or a cloud-based platform like Google Colab.

## Results and Findings
- **Tabular Analysis**: Identified key features contributing to pricing dynamics and built regression models with significant accuracy.
- **Time Series Analysis**: Successfully forecasted future sales using ensemble methods and achieved robust performance metrics.

## Directory Structure
```
project-directory/
|-- Auto_EDA_for_Airbnb_dataset_and_regression_using_AutoVIML.ipynb
|-- Store_Sales_Time_Series_Forecasting.ipynb
|-- README.md
```

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
- Kaggle for providing rich datasets for analysis.
- OpenAI's ChatGPT for insightful assistance during project development.
- Authors of AutoViML and Auto EDA tools for simplifying the modeling process.
