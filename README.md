
# Task 5: Exploratory Data Analysis (EDA) - Titanic Dataset

## 🎯 Objective
Extract insights using visual and statistical exploration of the Titanic dataset.

## 🛠️ Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📁 Dataset Used
- **Source**: [Kaggle Titanic Dataset](https://www.kaggle.com/competitions/titanic/data)
- **File**: `train.csv`

## 📌 Steps Performed

### 1. Data Loading
- Loaded `train.csv` using Pandas.

### 2. Data Inspection
- `.info()` to check structure and data types.
- `.describe()` for statistical summary.
- `.value_counts()` for categorical features.

### 3. Data Cleaning (Optional)
- Checked for missing values.
- Handled nulls in `Age`, `Cabin`, and `Embarked`.

### 4. Visual Exploration
- **Histograms** for age, fare.
- **Boxplots** to spot outliers in fare and age.
- **Scatterplots** (e.g., Age vs Fare, Fare vs Survival).
- **Pairplot** to see multi-variable relationships.
- **Heatmap** for correlation between numerical variables.

### 5. Observations
- Written for each plot directly in the notebook using markdown cells.

### 6. Summary of Findings
- Gender had a significant impact on survival.
- Passengers in higher classes had a better survival rate.
- Younger passengers had a higher chance of survival.

## 📄 Deliverables
- `Titanic_EDA.ipynb` (Jupyter Notebook)
- `Titanic_EDA.pdf` (PDF Export of notebook)
- `README.md` (this file)

## 💡 Outcome
Gained hands-on experience in:
- Performing EDA using Python
- Detecting patterns, trends, and anomalies
- Drawing insights using visualizations

## 🎤 Interview Prep Questions (Examples)
1. What types of visualizations are most effective for identifying outliers?
2. How do you interpret a correlation heatmap?
3. What steps would you take to clean data with missing values?

