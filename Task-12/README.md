# Task 12 – Exploratory Data Analysis using Tableau Public

## 📊 Healthcare Diabetes Analysis

### Objective

The objective of this task is to explore the **Healthcare Diabetes dataset** using Tableau Public and identify meaningful patterns, trends, comparisons, and relationships without predefined questions or charts.

The analysis focuses on understanding how variables such as **Glucose, BMI, Age, and Diabetes Outcome** are related and presenting the findings through an interactive Tableau dashboard.

---

## 📁 Dataset

**Dataset:** `health care diabetes.csv`

The dataset contains **768 patient records** and the following 9 attributes:

| Field | Description |
|---|---|
| Pregnancies | Number of pregnancies |
| Glucose | Plasma glucose concentration |
| BloodPressure | Diastolic blood pressure |
| SkinThickness | Skin fold thickness |
| Insulin | 2-Hour serum insulin |
| BMI | Body Mass Index |
| DiabetesPedigreeFunction | Diabetes pedigree function |
| Age | Patient age |
| Outcome | Diabetes outcome |

### Outcome

- `0` → No Diabetes
- `1` → Diabetes

---

## 🛠️ Tools Used

- Tableau Public
- CSV Dataset
- Data Visualization
- Exploratory Data Analysis

---

## 📈 Visualizations Created

The dashboard contains four main visualizations.

### 1. Diabetes Outcome Distribution

A bar chart showing the number of patients in each diabetes outcome category.

- No Diabetes: **500 patients**
- Diabetes: **268 patients**

This provides an overview of the distribution of diabetes outcomes in the dataset.

---

### 2. Glucose by Diabetes Outcome

A visualization comparing glucose levels between patients with and without diabetes.

The average glucose values are:

| Outcome | Average Glucose |
|---|---:|
| No Diabetes | 109.98 |
| Diabetes | 141.26 |

This visualization shows that diabetes-positive patients generally have higher glucose measurements.

---

### 3. Age vs Glucose Scatter Plot

A scatter plot comparing:

- **X-axis:** Glucose
- **Y-axis:** Age
- **Color:** Diabetes Outcome

The visualization helps identify patterns between age, glucose levels, and diabetes outcome.

It also allows users to observe where diabetes-positive observations are concentrated.

---

### 4. BMI Category and Diabetes Outcome

BMI values were grouped into categories:

| BMI Range | Category |
|---|---|
| < 18.5 | Underweight |
| 18.5 – 24.9 | Normal |
| 25 – 29.9 | Overweight |
| 30 – 34.9 | Obese I |
| 35+ | Obese II+ |

The visualization compares diabetes outcomes across these BMI categories.

---

## 🎛️ Interactive Filters

Two interactive filters were added to the dashboard:

### 1. Age Filter

Allows users to select a specific age range and examine how the results change.

### 2. Diabetes Outcome Filter

Allows users to switch between:

- All
- No Diabetes
- Diabetes

The filters are applied across the dashboard to support interactive exploration.

---

## 📊 Dashboard

### Healthcare Diabetes Analysis Dashboard

The dashboard combines the four visualizations into a single interactive interface.

The dashboard allows users to:

- Explore diabetes outcome distribution
- Compare glucose levels
- Investigate age and glucose relationships
- Analyze BMI categories
- Filter results by age
- Filter results by diabetes outcome

---

## 🔍 Key Findings

### Finding 1 – Glucose shows a strong relationship with diabetes outcome

The average glucose level for diabetes-positive patients is approximately **141.26**, compared with **109.98** for patients without diabetes.

This indicates that glucose is one of the most important variables for distinguishing the two outcome groups in this dataset.

---

### Finding 2 – Higher BMI categories have higher diabetes prevalence

The proportion of diabetes-positive records increases substantially in the higher BMI categories.

The obese groups show considerably higher diabetes-positive proportions compared with the normal BMI group.

---

### Finding 3 – Diabetes outcomes vary across age groups

Older age groups show a higher proportion of diabetes-positive records compared with younger groups in this dataset.

This suggests that age can be useful when analyzing diabetes risk patterns together with other variables such as glucose and BMI.

---

## 💡 Suggestions

1. Healthcare organizations can prioritize glucose monitoring and diabetes screening for groups showing consistently elevated glucose measurements.

2. Weight-management and lifestyle programs can be targeted toward overweight and obese groups because these groups show higher diabetes-positive proportions.

---

## 🎯 Recommendations

- Use **Glucose, BMI, and Age together** when identifying higher-risk groups.
- Encourage regular diabetes screening for groups with elevated glucose measurements.
- Use interactive dashboards to investigate specific patient segments rather than relying only on overall averages.
- Future analysis can include additional clinical variables and larger datasets to validate these patterns.

---

## 📝 Overall Conclusion

The exploratory analysis of the Healthcare Diabetes dataset reveals meaningful differences between diabetes-positive and diabetes-negative patients.

**Glucose shows the strongest observable relationship with diabetes outcome**, while BMI and age also demonstrate important patterns.

The interactive Tableau dashboard provides an effective way to explore these relationships and identify higher-risk patient groups. The analysis can support data-driven approaches to diabetes screening, prevention, and healthcare decision-making.

> **Note:** The findings describe patterns and associations within this dataset and should not be interpreted as medical or causal conclusions.

---

## 📂 Project Structure

```text
Task-12/
│
├── README.md
│
└── health care diabetes.csv

## 🔗 Tableau Public Dashboard

[[View Healthcare Diabetes Analysis Dashboard](YOUR_TABLEAU_PUBLIC_LINK)] (https://public.tableau.com/views/task12_17914415915320/Dashboard1?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
