# Students Exam Scores Analysis

## 📌 Overview  
This project analyzes the **Students Exam Scores** dataset from Kaggle by:  

- Loading and exploring the dataset.  
- Cleaning and standardizing columns.  
- Performing descriptive and comparative analysis.  
- Generating visualizations to understand patterns in scores.  

**📥 Dataset Link:** [Students Exam Scores – Kaggle](https://www.kaggle.com/datasets/desalegngeb/students-exam-scores)  

---

## 🗂 Project Workflow  

### **Data Loading**  
- Reads the dataset file (`Expanded_data_with_more_features.csv`).  
- Displays dataset shape, column names, and sample rows.  

### **Data Cleaning**  
- Standardizes column names.  
- Ensures numerical score columns are in the correct format.  
- Handles missing values if present.  
- Removes duplicate rows.  

### **Analysis & Visualization**  
- Distribution of scores for **Math**, **Reading**, and **Writing**.  
- Comparisons based on **gender**, **race/ethnicity**, and **parental education**.  
- Effect of **lunch type** and **test preparation course** on scores.  
- Correlation analysis between subject scores.  
- Visualizations using **Matplotlib** & **Seaborn**.  

---

## **Outputs**  
- Cleaned dataset ready for analysis.  
- Charts and plots showing score trends and comparisons.  

---

## ⚙️ Requirements  
```bash
pip install pandas numpy matplotlib seaborn
