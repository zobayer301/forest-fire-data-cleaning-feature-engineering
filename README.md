# Forest Fire Data Cleaning & Feature Engineering

A complete data preprocessing project using the **Algerian Forest Fires Dataset**. This repository demonstrates practical data cleaning, feature engineering, exploratory data analysis (EDA), and dataset preparation techniques commonly used before building machine learning models.

The project follows a structured preprocessing workflow that transforms raw data into a clean, analysis-ready dataset.

---

## Project Overview

Raw datasets often contain missing values, inconsistent formatting, duplicate records, and incorrect data types. These issues reduce model performance and lead to unreliable analysis.

In this project, I perform an end-to-end preprocessing pipeline that includes:

* Data inspection
* Data cleaning
* Handling missing values
* Data type conversion
* Feature engineering
* Exploratory Data Analysis (EDA)
* Preparing the dataset for machine learning

---

## Dataset Description

**Dataset:** Algerian Forest Fires Dataset

The dataset contains daily weather observations collected from two regions of Algeria during the forest fire season.

### Features

| Feature     | Description             |
| ----------- | ----------------------- |
| day         | Day of month            |
| month       | Month                   |
| year        | Year                    |
| Temperature | Temperature (°C)        |
| RH          | Relative Humidity (%)   |
| Ws          | Wind Speed (km/h)       |
| Rain        | Rainfall (mm)           |
| FFMC        | Fine Fuel Moisture Code |
| DMC         | Duff Moisture Code      |
| DC          | Drought Code            |
| ISI         | Initial Spread Index    |
| BUI         | Build Up Index          |
| FWI         | Fire Weather Index      |
| Classes     | Fire / Not Fire         |

---

## Data Cleaning Steps

The following preprocessing tasks were performed:

* Removed unnecessary spaces from column names
* Cleaned inconsistent class labels
* Removed invalid and missing records
* Converted numerical columns to appropriate data types
* Created a new **Region** feature
* Removed duplicate rows
* Verified missing values
* Prepared the dataset for analysis

---

## Feature Engineering Techniques

Several new features were created to improve the dataset for future machine learning models.

Examples include:

* Region Encoding
* Rain Indicator (`Rain_Flag`)
* Weather Index
* High Fire Weather Indicator
* Temperature Categories
* Humidity Categories
* Temperature × Wind interaction feature
* Log Transformation of Fire Weather Index
* Standardization of numerical features
* One-Hot Encoding of categorical features

---

## Exploratory Data Analysis (EDA)

The project includes visual analysis such as:

* Missing value analysis
* Class distribution
* Correlation heatmap
* Histograms
* Boxplots
* Outlier detection
* Feature distribution analysis

These visualizations help understand the dataset before model development.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Repository Structure

```text

forest-fire-data-cleaning-feature-engineering/

│

├── Algerian_forest_fires_dataset.csv   # Original dataset

├── data_cleaning.ipynb                 # Data cleaning and feature engineering notebook

├── README.md                           # Project documentation

├── LICENSE                             # MIT License



```

---

## Results

After preprocessing:

* Dataset cleaned and standardized
* Missing values removed
* Incorrect formatting fixed
* Duplicate records removed
* New informative features created
* Dataset prepared for machine learning workflows

---

## Future Improvements

* Build classification models
* Perform feature selection
* Hyperparameter tuning
* Cross-validation
* Model comparison
* Deploy the model using Streamlit

---

## Author

**Md. Zobayer Chowdhury**
- Computer Science and Engineering
- Interested in Data Science, Machine Learning, and Artificial Intelligence.

Feel free to explore the project and provide feedback or suggestions.
