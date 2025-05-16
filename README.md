
# Assignment 2 – Sampling and Credit Card Fraud Detection 

**Course:** UCS654 – Data Analytics  
**Author:** Sanyam Sharma  
**Roll Number:** 102203823  

---

## Objective

The objective of this assignment is to explore and analyze a credit card dataset using various sampling techniques and exploratory data analysis (EDA). The focus is on understanding fraud detection by examining data distributions and identifying patterns in imbalanced datasets.

---

## Dataset

**File Used:** `Creditcard_data.csv`  
**Rows:** 772  
**Columns:** 31  
**Target Variable:** `Class`  
- `0`: Legitimate transaction  
- `1`: Fraudulent transaction

**Features:**
- `Time`, `Amount`, and 28 anonymized PCA components (`V1` to `V28`)

Key Points:
- No missing values
- Clean and numeric data

---

## Sampling Techniques Implemented

- Simple Random Sampling  
- Systematic Sampling  
- Stratified Sampling  

Each method is used to analyze:
- Class distribution  
- Sampling bias  
- Variation in fraud detection based on sample strategy  

---

## Exploratory Data Analysis (EDA)

- Class balance analysis  
- Distribution plots of features  
- Correlation heatmap  
- Boxplots comparing fraudulent vs non-fraudulent transactions  
- Statistical summaries including mean and variance  

---

## Key Learnings

- Handling class imbalance using stratified sampling  
- Understanding how sampling methods impact data representation  
- Importance of visual EDA in revealing financial fraud patterns  

---

## How to Run

1. Open the notebook `Sampling Assignment.ipynb` using Jupyter Notebook or VS Code.  
2. Make sure `Creditcard_data.csv` is in the same directory.  
3. Run all code cells to view sampling results and visual analysis.

---

## Libraries Used

- pandas  
- numpy  
- matplotlib  
- seaborn  
- sklearn.model_selection  

---

## Sample Output (Preview)

```
Shape: (772, 31)
No missing values found.
Class Distribution:
  Legitimate (0): 697
  Fraud (1): 75
```

---

## Future Scope

- Apply oversampling and undersampling techniques (e.g., SMOTE, Tomek Links)  
- Train machine learning models such as Random Forest on balanced samples  
- Package the analysis into a modular PyPI-ready EDA toolkit  
