# ABC Company – Employee Data Analysis

This project is part of the Module 4 assignment in my Data Science course. The dataset contains information about 458 employees from ABC Company, structured using NBA-style teams and positions.

## 📁 Project Structure

- `ABC_Employee_Analysis.ipynb`: Main Jupyter Notebook with all code, visualizations, and explanations
- `employee_data.csv`: Cleaned dataset used for analysis
- `README.md`: Overview and explanation of the project

## 🔍 Objective

- Clean the dataset and handle missing or incorrect values
- Analyze employee distribution by team, position, and age
- Study salary distribution across teams and roles
- Find correlation between age and salary
- Visualize all insights using graphs

## ⚙️ Preprocessing Steps

- Removed duplicate entries
- Replaced missing or unrealistic `Height` values
- Filled missing `College` entries with "Unknown"
- Converted `Salary` from string to numeric format
- Checked and handled null values

## 📊 Analysis Performed

- Most employees work for New Orleans Pelicans and Memphis Grizzlies
- Most common positions are SG, PF, and PG
- Most employees are between 20–24 years old
- Cleveland Cavaliers have the highest total salary
- Centers (C) earn the most overall
- Weak positive correlation (0.21) between age and salary

## 📈 Visualizations

The notebook includes bar charts, count plots, and correlation heatmaps using Matplotlib and Seaborn.

## 💡 Key Insights

- The workforce is mostly young and early in their careers
- Some roles are overrepresented, while others are rare
- Age has only a small effect on salary
- Top teams and positions have high salary variations

## 🧠 Learnings

I learned how to:
- Clean and prepare a dataset for analysis
- Perform EDA using Pandas and visualization libraries
- Tell a data story using Markdown and charts
- Organize and present a data science project

## ✅ How to Run

1. Clone the repository
2. Open the Jupyter Notebook (`.ipynb`)
3. Run all cells step-by-step

## 📌 Notes

- Dataset is static and doesn’t include performance or time-based data
- Team names are symbolic and represent departments

---

**Submitted by:** Salman  
**Course:** Data Science & Machine Learning – 2025  
