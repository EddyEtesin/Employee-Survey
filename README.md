# Employee-Survey

## Employee Survey Data Analysis

### Overview

This project performs an in-depth analysis of employee survey data to uncover patterns and relationships between key workplace factors such as job satisfaction, stress levels, work-life balance, sleep, physical activity, job level, and commuting distance. The goal is to provide insights that can inform organizational decisions around employee well-being, productivity, and HR policy development.

---

### Dataset Description

The dataset used in this analysis contains information from employee surveys, covering the following key attributes:

- **Demographics**: Age, Gender, Experience Level
- **Job-Related**: Job Level, Department, Commute Distance, Workload
- **Health & Lifestyle**: Stress Level, Sleep Hours, Physical Activity Hours
- **Satisfaction Metrics**: Job Satisfaction, Work-Life Balance

---

### Key Objectives

The project addresses multiple analytical questions, including:

1. What is the distribution of job satisfaction scores?
2. Are employees with higher stress levels more likely to report lower job satisfaction?
3. Does work-life balance vary significantly across age groups?
4. How does commute distance relate to work-life balance?
5. Is there any correlation between job level and workload?
6. Are physically active employees experiencing lower stress levels?
7. Is there a relationship between sleep and productivity or satisfaction?

---

### Techniques Used

- **Data Cleaning**: Handling missing values, correcting data types
- **Feature Engineering**: Categorization of continuous variables (e.g., sleep, activity hours)
- **Data Mapping**: Mapping qualitative levels to numeric scores for analysis
- **Exploratory Data Analysis (EDA)**: Distribution plots, group comparisons
- **Statistical Analysis**: Correlation analysis to assess relationships
- **Visualization**: Scatter plots, box plots, and bar charts using `matplotlib` and `seaborn`

---

### Example Feature Engineering

#### Physical Activity Mapping

Physical activity (in hours per week) was grouped as:

| Hours per Week | Category        |
|----------------|-----------------|
| 0–0.5          | Inactive        |
| 0.5–1.5        | Very Light      |
| 1.5–3          | Light           |
| 3–4.5          | Moderate        |
| 4.5–5          | Active          |

#### Sleep Hours Mapping

Sleep hours were classified as:

| Sleep Hours | Category                  |
|-------------|---------------------------|
| 1–3         | Severely Sleep Deprived   |
| 3–5         | Sleep Deprived            |
| 5–6.5       | Insufficient              |
| 6.5–8       | Normal                    |
| 8–10        | Well Rested               |

---

### Key Findings

- **Stress vs Job Satisfaction**: Weak negative correlation (r ≈ -0.21) suggests that higher stress levels are modestly associated with lower job satisfaction.
- **Age vs Work-Life Balance**: No significant correlation (r ≈ -0.015), indicating age does not strongly influence perceived work-life balance.
- **Commute vs Work-Life Balance**: Analysis shows very weak relationship, suggesting other factors may be more influential.
- **Physical Activity vs Stress**: Correlation near zero (r ≈ -0.0009), suggesting no linear relationship, though grouping may reveal patterns.
- **Job Level vs Workload**: No correlation (r ≈ -0.00087), suggesting that workload is evenly distributed across levels.

---

### How to Run

1. Clone this repository or download the `.ipynb` notebook.
2. Ensure you have the necessary Python environment. Recommended libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```
3. Run the notebook using:
   ```bash
   jupyter notebook Employee_survey\ Queried.ipynb
   ```

---

### File Structure

```
.
├── Employee_survey Queried.ipynb   # Jupyter notebook with code and analysis
├── employee_survey.csv             # Source dataset
├── README.md                       # Project documentation
```

---

### Author

This analysis was developed as part of a broader exploration into workplace wellness and data-driven HR insights. For more details or custom analytics, please reach out.
ediomoetesin40@gmail.com
ed_etesin on x.com
Ediomo Etesin on linkedn
