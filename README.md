Students Exam Scores Analysis
📌 Overview

This project analyzes the Students Exam Scores dataset from Kaggle by:

Loading and exploring the dataset.

Cleaning and standardizing columns.

Performing descriptive and comparative analysis.

Generating visualizations to understand patterns in scores.

🗂 Project Workflow
Data Loading

Reads the dataset file (Expanded_data_with_more_features.csv).

Displays dataset shape, column names, and sample rows.

Data Cleaning

Standardizes column names.

Ensures numerical score columns are in the correct format.

Handles missing values if present.

Removes duplicate rows.

Analysis & Visualization

Distribution of scores for Math, Reading, and Writing.

Comparisons based on gender, race/ethnicity, and parental education.

Effect of lunch type and test preparation course on scores.

Correlation analysis between subject scores.

Visualizations using Matplotlib & Seaborn.

Outputs

Cleaned dataset ready for analysis.

Charts and plots showing score trends and comparisons.

⚙️ Requirements

Install the dependencies with:

pip install pandas numpy matplotlib seaborn

▶️ Usage

Download the dataset from Kaggle and place it in the project directory.

Open and run the Jupyter Notebook:

jupyter notebook "Project - 1.ipynb"


View generated charts directly in the notebook.

📁 Example Output Files

outputs/score_distribution.png – Histograms of scores for each subject.

outputs/score_comparison.png – Boxplots comparing scores by demographic attributes.

outputs/score_correlation.png – Heatmap showing correlation between subjects.

📌 Notes

Dataset includes demographic and academic performance data for students.

CSV should match the original Kaggle column names for smooth execution.
