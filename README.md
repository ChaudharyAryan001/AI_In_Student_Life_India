# AI in Student Life (India) – Data Analysis Project

Project Overview

This project analyzes how Artificial Intelligence (AI) tools are impacting student life in India. It focuses on usage patterns, academic impact, and trends across different streams and states using data analysis and visualization techniques.

---

Dataset

The dataset used in this project:

- File Name: "AI_in_Student_Life_India.csv"
- Contains information such as:
  - Student Stream (Engineering, Commerce, etc.)
  - State
  - Daily Usage Time of AI tools
  - Main AI Tool used (e.g., ChatGPT)
  - Impact on Grades

---

Technologies Used

- Python
- Pandas (Data Analysis)
- NumPy (Numerical Operations)
- Matplotlib (Visualization)
- Seaborn (Advanced Visualization)

---

Features & Analysis

Data Exploration

- Display first 10 rows of dataset
- Check dataset shape
- View dataset information
- Identify missing values

Statistical Analysis

- Descriptive statistics of daily usage time
- Average usage time for Engineering students
- Top 5 states with highest AI usage

Data Insights

- Number of students per stream
- Number of students per state
- Unique AI tools used

Filtering

- Extract students who use ChatGPT

---

Visualizations

The project includes multiple visualizations:

- Scatter Plot
  Relationship between daily usage time and grades

- Bar Chart
  Number of students in each stream

- Pie Chart
  Distribution of AI tools used

- Histogram
  Distribution of daily usage time

- Scatter Plot (Index vs Time)
  Individual student usage trends

---

How to Run

1. Install required libraries:

pip install pandas numpy matplotlib seaborn

2. Place dataset file in the same directory:

AI_in_Student_Life_India.csv

3. Run the script:

python final.py

---

Key Insights

- AI usage varies significantly across different streams and states.
- Engineering students tend to use AI tools more frequently.
- ChatGPT is one of the most commonly used AI tools.
- Higher usage may influence academic performance.

---

Notes

- Ensure dataset file path is correct.
- Some plots may overlap if "plt.show()" is not used properly.
- Code is generated from Google Colab notebook.

---

Author

Aryan Chaudhary

---

Future Improvements

- Add more advanced visualizations (heatmaps, boxplots)
- Perform correlation analysis
- Build predictive models (Machine Learning)
- Create dashboard using Streamlit or Power BI

---
