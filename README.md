
# 🧪 EDA Task - Titanic Dataset

## 🎯 Objective

The goal of this task is to perform **Exploratory Data Analysis (EDA)** on the Titanic dataset to uncover insights about passenger demographics, survival rates, and relationships between features. This includes both statistical and visual analysis.

---

## 🛠️ Tasks Performed

### 1. Generate Summary Statistics
- Used `df.describe()` to get mean, median, standard deviation, min, max, etc., for numeric features.

### 2. Create Histograms and Boxplots
- Histograms visualized the distribution of features like Age and Fare.
- Boxplots helped identify outliers and spread of values.

### 3. Use Pairplot/Correlation Matrix
- Pairplot displayed relationships between multiple features based on survival status.
- Correlation heatmap helped understand how strongly numerical features are related.

### 4. Identify Patterns, Trends, or Anomalies
- Observed trends such as:
  - First-class passengers had higher survival rates.
  - Younger passengers were more likely to survive.
  - Fare and survival had a positive relationship.

### 5. Make Basic Feature-Level Inferences
- Grouped data by class and calculated survival rates.
- Created bar plots to visualize and confirm inferences.

---

## 📦 Libraries Used

```python
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
```

---

## 📁 Dataset Info
- Filename: `cleaned_titanic.csv`
- Must include columns like: `age`, `fare`, `pclass`, `survived`

---

## ✅ Outcome

- Developed understanding of the dataset using statistical and visual techniques.
- Gained insight into how various features influenced passenger survival.

---

> Prepared by Bharat 💪
