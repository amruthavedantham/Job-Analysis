# 📊 Job Analysis – Data Analytics Project

This project presents an end-to-end analysis of job market data to uncover valuable insights about hiring trends, skill demands, job roles, and salary patterns. It was completed as part of the **"Building a Full Data Analytics Project" Summer Workshop** by **GeeksforGeeks**, under the mentorship of **Ashish Jangra**.

---

## 📌 Overview

The goal of this project is to perform exploratory data analysis on a dataset of job listings to identify patterns and support career-related decisions. The analysis focuses on job roles, company preferences, experience levels, skill requirements, and salary trends.

---

## 🎯 Objective

- Analyze hiring patterns across companies and locations.
- Identify in-demand job titles and required skills.
- Study salary trends by experience levels.
- Visualize insights for better interpretation.

---

## 📂 Dataset

- The dataset includes fields such as: `Title`, `Company`, `Location`, `Type`, `Level`, `Years of Experience`, `Country`, `Skills`, `Reviews`, `Salary`.
- Source: Scraped from job portals.

---

## 🔄 Data Processing

### 1. **Loading the Data**  
Imported the dataset using pandas and explored the structure using `.head()`, `.info()`, and `.describe()`.

### 2. **Data Exploration**  
Reviewed column types, distributions, and summary statistics.

### 3. **Handling Missing & Duplicate Data**  
- Removed null values (excluding `Reviews` and `Ratings`).
- Dropped duplicate rows.

### 4. **Data Cleaning**  
- Cleaned `Experience`, `Salary`, and `Review` columns for consistent formatting.
- Changed data types for proper analysis.
- Removed irrelevant columns like `Unnamed: 0`.

---

## 📈 Data Analysis & Visualization

Used `Matplotlib` and `Seaborn` to create meaningful visualizations:

- **Top Hiring Companies**: IBM, Dell, EY, etc.
- **Most In-Demand Job Titles**: Data Analyst, Software Engineer.
- **Skills Analysis**:
  - Common skills: Python, SQL, Communication
  - Company-specific (e.g., HDFC Bank): Sales, Excel
- **Experience vs. Job Count**: Entry-level roles are abundant.
- **Experience vs. Salary**: Salary increases steadily with experience.

---

## 🔧 Tools & Technologies

- **Language**: Python  
- **Environment**: Google Colab  
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn

---

## 📌 Key Insights

- Top recruiters include IBM, Dell, and multinational firms.
- Demand is highest for data and software-related roles.
- Core skills like Python and SQL are crucial across industries.
- Most job roles target candidates with 0–2 years of experience.
- Salary expectations align positively with experience level.

---

## 🚀 Future Enhancements

- Add job posting time-series trends.
- Perform NLP on job descriptions.
- Build an interactive dashboard using Streamlit or Plotly.
- Integrate ML models to predict demand by role.

---

⚠️ Note: Some visualizations in this notebook are interactive (Plotly/Altair) and may not render on GitHub or nbviewer. Please open this notebook in Google Colab or Jupyter for the full experience.

--- 

## 👤 Author

 V Amrutha Varshini

---

## 📄 License

This project is licensed under the **Creative Commons CC BY 4.0 License**. 
---


