# MEDICAL INSURANCE COST PREDICTION USING MULTIPLE LINEAR REGRESSION

## OBJECTIVE

The objective of this project is to develop a Multiple Linear Regression model to predict medical insurance charges based on customer demographic and health-related information. The project includes data understanding, exploratory data analysis (EDA), data preprocessing, model development, and performance evaluation.

---

## DATASET LINK

**Medical Cost Personal Insurance Dataset**

Kaggle Dataset:
https://www.kaggle.com/datasets/mirichoi0218/insurance

> **Note:** The dataset is not included in this repository. Please download it directly from the Kaggle link above.

---

## LIBRARIES USED

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## METHODOLOGY

1. Loaded the dataset using Pandas.
2. Performed data understanding by examining the dataset structure, feature types, missing values, duplicate records, and summary statistics.
3. Conducted Exploratory Data Analysis (EDA) using histograms, count plots, scatter plots, box plots, and a correlation heatmap.
4. Removed duplicate records (if any).
5. Encoded categorical variables (`sex`, `smoker`, and `region`) using One-Hot Encoding.
6. Split the dataset into 80% training and 20% testing sets.
7. Built a Multiple Linear Regression model.
8. Predicted insurance charges for the test dataset.
9. Evaluated the model using Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² Score.
10. Visualized the model performance using an Actual vs Predicted scatter plot.

---

## RESULTS

| Evaluation Metric | Value |
|-------------------|-------|
| Mean Absolute Error (MAE) | **4177.05** |
| Mean Squared Error (MSE) | **35478020.68** |
| R² Score | **0.8069** |

### Key Findings

- The model explains approximately **80.69%** of the variation in medical insurance charges.
- Smoking status is the most influential factor affecting insurance costs.
- Age and BMI also have a positive impact on insurance charges.
- The model performs well overall but has larger prediction errors for customers with very high medical expenses.

---

## CONCLUSION

This project successfully developed a Multiple Linear Regression model to predict medical insurance charges using customer information such as age, sex, BMI, number of children, smoking status, and region. The model achieved an **R² score of 0.8069**, indicating good predictive performance. The analysis revealed that smoking status is the most significant factor affecting insurance charges, followed by age and BMI, while gender, region, and the number of children have comparatively smaller effects. Although the model produced reasonably accurate predictions, it showed larger errors for customers with very high insurance charges. A limitation of Multiple Linear Regression is that it assumes a linear relationship between the features and the target variable, making it less effective at capturing complex or non-linear patterns.

---

## PROJECT STRUCTURE

```text
Medical-Insurance-Cost-Prediction/
│
├── Assignment-1.ipynb
└── README.md
```

---

## AUTHOR

**Name:** Megha Rajeev

**Course:** Integrated M.Tech in Artificial Intelligence

**Assignment:** Assignment-1 – Medical Insurance Cost Prediction using Multiple Linear Regression
