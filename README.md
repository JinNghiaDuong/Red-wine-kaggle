# Red Wine Quality Analysis

## Project overview

This project explores the **Red Wine Quality** dataset and uses Python to analyse the relationship between physicochemical wine properties and wine quality scores.

The aim of the project is to demonstrate an end-to-end data science workflow, including:

- loading and inspecting data
- exploratory data analysis
- data visualisation
- feature analysis
- basic machine learning modelling
- model evaluation
- reflection on limitations and possible improvements

This project was completed as part of my learning and portfolio development in data science.

## Repository contents

| File | Description |
|---|---|
| `Red Wine Quality.ipynb` | Main Jupyter Notebook containing the analysis, visualisations and modelling workflow. |

## Tools and libraries used

The project uses Python and common data science libraries, including:

- `pandas` for data manipulation
- `numpy` for numerical operations
- `matplotlib` and/or `seaborn` for data visualisation
- `scikit-learn` for machine learning and model evaluation

## Dataset

The dataset contains red wine samples with several physicochemical features, such as acidity, sugar, pH, alcohol and sulphates, alongside a wine quality score.

The target variable is `quality`.

The main analytical question is:

> Can we use the measurable chemical properties of red wine to understand and predict wine quality?

## Methodology

The analysis follows these main stages:

### 1. Data inspection

I first explored the structure of the dataset, including:

- number of rows and columns
- data types
- missing values
- duplicate values
- summary statistics

This helped me understand the quality and shape of the data before modelling.

### 2. Exploratory data analysis

I used visualisations and summary statistics to investigate patterns in the data, including:

- distribution of wine quality scores
- relationships between individual features and quality
- correlation between variables
- possible signs of skewness or imbalance

This stage helped identify which variables appeared most strongly related to wine quality.

### 3. Data preparation

Before modelling, I prepared the data by separating features from the target variable and creating suitable training and testing sets.

Where appropriate, I considered the need for preprocessing steps such as scaling, depending on the model used.

### 4. Modelling

I applied machine learning techniques to test whether wine quality could be predicted from the available features.

The modelling process was used not only to generate predictions, but also to understand which variables may contribute more strongly to wine quality.

### 5. Evaluation

Model performance was assessed using appropriate evaluation metrics.

I compared model outputs with the actual wine quality scores to understand how well the model performed and where it may have struggled.

## Key findings

The analysis suggested that some features, such as alcohol level, acidity-related variables and sulphates, may have a meaningful relationship with wine quality.

However, wine quality is subjective and may not be fully explained by chemical measurements alone. The model should therefore be understood as an analytical tool rather than a perfect predictor.

## Limitations

This project has several limitations:

- The dataset is relatively small and may not represent all red wines.
- Wine quality scores are subjective and may depend on human judgement.
- Some quality categories may be underrepresented, which can affect model performance.
- The analysis is based only on the variables available in the dataset.
- More advanced validation would be needed before using the model in a real-world setting.

## Possible future improvements

If I were to continue improving this project, I would:

- add clearer comparison between multiple models
- use cross-validation for more robust performance estimates
- tune model hyperparameters
- explore classification approaches by grouping quality scores
- improve feature engineering
- add clearer business or research interpretation of the results
- refactor parts of the notebook into reusable Python scripts

## What this project demonstrates

This project demonstrates my ability to:

- work with structured data in Python
- inspect and clean data
- use visualisation to explore patterns
- apply basic machine learning methods
- evaluate model performance
- explain assumptions, limitations and next steps
- document a data science workflow clearly

## Author

**Trong-Nghia (Jin) Duong**

- GitHub: [JinNghiaDuong](https://github.com/JinNghiaDuong)
- LinkedIn: [linkedin.com/in/jin-duong](https://linkedin.com/in/jin-duong/)
