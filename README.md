# Healthcare Prioritization Survey Analysis

**Project Focus:** Understanding public perspectives on ethical decision-making in healthcare resource allocation through survey analysis and data visualization.

---

## Project Summary

This project explores public opinion on healthcare prioritization using survey data. By analyzing responses, this study identifies how factors like age, condition severity, and socioeconomic status influence views on equitable healthcare distribution. The results can inform future policies aimed at creating a more transparent and fair system for resource allocation.

| Business Problem | Technical Approach | Outcome |
| :--- | :--- | :--- |
| Lack of quantitative data on public opinion regarding healthcare ethics. | **Survey data analysis using Python and visualization with Tableau.** | Generated key insights into public priorities, values, and trust in the healthcare system. |

---

## Technologies & Tools

| Category | Technologies Used |
| :--- | :--- |
| **Programming Language** | Python |
| **Libraries** | Pandas, NumPy, Matplotlib, Seaborn |
| **Data Visualization** | Tableau, Matplotlib |

---

## Methodology Summary

The project involved a comprehensive analysis of survey data, beginning with a thorough data cleaning process. This included removing timestamps and duplicates, structuring multi-choice responses into linked tables for clarity, and standardizing column names for seamless integration with Tableau. The final, clean dataset was then used for statistical analysis and the creation of an interactive dashboard to visualize the findings.

---

## Key Findings from the Survey

#### 1. Crisis Prioritization Preferences
- **44%** of respondents believe **everyone should be treated equally**.
- **22%** prioritize elderly patients, while **17%** prioritize children.

#### 2. Age Group Distribution
- The majority (56%) of respondents fall within the **25-34 age group**, followed by **18-24 (28%)**.

#### 3. Gender-Based Prioritization Factors
- Males prioritize **Age (9 votes)** and **Severity of Condition (8 votes)**.
- Females prioritize **Severity of Condition (5 votes)** and **Socioeconomic Status (2 votes)**.

#### 4. Valued Ethical Principles
- The most valued ethical principles are **Equity and Individual Rights**, while **Maximization of Benefits** ranks lowest.

#### 5. Trust in the Healthcare System
- **57%** of respondents report encountering **barriers when accessing healthcare**.
- **Trust in the system is notably lower** among individuals who have faced these barriers.

---

## Tableau Dashboard

The interactive Tableau dashboard centralizes key survey insights, featuring visualizations such as bar charts comparing gender-based priorities, stacked charts for crisis preferences, and a bubble chart illustrating the relationship between trust levels and barriers to access.

![Healthcare Prioritization Survey Dashboard](https://github.com/user-attachments/assets/644239c8-31f7-439f-bc11-59a8b6246ac6)

---

## Project Files & Execution

- **`Survey_Analysis.ipynb`**: Jupyter Notebook containing all data processing, EDA, and statistical analysis steps.
- **`Survey1.xlsx`**: The raw survey dataset.

### How to Run the Analysis

The notebook is accessible and can be run directly in Google Colab, with no local setup required.

- **[Open Survey Analysis Notebook in Google Colab](https://colab.research.google.com/github/harrisd97/Health-Care-Prioritization-Survey/blob/main/Survey_Analysis.ipynb)**
