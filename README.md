# **Repository Overview**

This repository contains all files and models used for predicting **Email Open Rates (OR%)** using multiple modeling approaches.  
All data cleaning, validation, and feature extraction were performed directly in **Excel**, to keep the modeling notebooks clean and focused.

---

## **Repository Contents**

### **1. Data Files**
- **All Data (Excel file):**  
  The master dataset containing all raw and processed campaign records.

- **Model Data (CSV file):**  
  Cleaned, filtered, and ready-to-use dataset for modeling.  
  This file serves as the main input for all machine learning notebooks.

- **Subject Features Data:**  
  Includes extracted features for each subject line (e.g., tone, personalization, emoji, urgency, etc.).

- **Meta Data:**  
  Provides category definitions and descriptions for each subject-line feature used in modeling.

---

### **2. Model Files**
- **Binomial GLM Model:**  
  Predicts **Email Open Rate (OR%)** using a logistic regression approach suitable for proportion data.  
  Provides interpretable insights into key feature effects.

- **LightGBM Model:**  
  Predicts **Email Open Rate (OR%)** using a gradient boosting approach that captures nonlinear relationships and interactions.

- **Linear Mixed  Model:**  
  Predicts **Email Open Rate (OR%)** captures variability across campaign groups while modeling open rate as a continuous outcome.

---

### **3. Notes**
- All **data preprocessing (cleaning, validation, feature extraction)** was completed in Excel before modeling.  
- The notebooks focus solely on **model training, evaluation, and prediction**, ensuring cleaner and more modular code.
