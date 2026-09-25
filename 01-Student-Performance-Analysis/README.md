# Student Performance Analysis

## 📌 Project Overview

This project focuses on Exploratory Data Analysis (EDA) of student performance data using Python. The analysis explores student scores, compares performance across different categories, examines relationships between assessments, and identifies important patterns within the dataset.

## 🎯 Objectives

- Understand and explore the dataset
- Check data quality and structure
- Identify missing values and duplicate records
- Analyze descriptive statistics
- Compare student performance across subjects, genders, and classes
- Analyze relationships between Test 1, Test 2, and Final Exam scores
- Perform correlation analysis
- Analyze Pass/Fail performance
- Study the distribution of final exam scores
- Identify potential outliers

## 📊 Dataset

The dataset contains **1,000 records** and **10 columns** related to student performance.

### Dataset Features

| Column | Description |
|---|---|
| `student_id` | Unique student identifier |
| `name` | Student name |
| `gender` | Student gender |
| `age` | Student age |
| `class` | Student class |
| `teacher_id` | Teacher identifier |
| `subject` | Subject |
| `test1_score` | Test 1 score |
| `test2_score` | Test 2 score |
| `final_exam_score` | Final exam score |

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## 🔍 Data Exploration & Cleaning

The dataset was first examined to understand its structure and quality.

### Data Quality Checks

- **Total records:** 1,000
- **Total columns:** 10
- **Missing values:** 0
- **Duplicate rows:** 0

Descriptive statistics were also calculated for age, Test 1, Test 2, and Final Exam scores.

## 📈 Exploratory Data Analysis

The following analyses and visualizations were performed:

### 1. Overall Score Analysis

The average scores were:

| Assessment | Average Score |
|---|---:|
| Test 1 | 63.94% |
| Test 2 | 66.13% |
| Final Exam | 68.41% |

### 2. Subject-wise Performance

Average Final Exam scores by subject:

| Subject | Average Final Score |
|---|---:|
| Computer | 70.64% |
| Art | 70.59% |
| English | 70.50% |
| History | 68.00% |
| Science | 66.64% |
| Math | 65.98% |

### 3. Gender-wise Performance

| Gender | Average Final Score |
|---|---:|
| Female | 68.82% |
| Male | 68.04% |

These results are descriptive and do not establish a causal relationship.

### 4. Class-wise Performance

| Class | Average Final Score |
|---|---:|
| 9th | 67.33% |
| 10th | 67.92% |
| 11th | 69.95% |
| 12th | 68.54% |

## 🔗 Correlation Analysis

Correlation analysis was performed to examine linear relationships between numerical variables.

| Variables | Correlation |
|---|---:|
| Test 1 vs Test 2 | 0.831 |
| Test 1 vs Final Exam | 0.792 |
| Test 2 vs Final Exam | 0.783 |
| Age vs Final Exam | 0.034 |

The results show relatively strong positive linear relationships between Test 1/Test 2 scores and Final Exam scores in this dataset.

Correlation indicates association and does not by itself establish causation.

## 📊 Visualizations

The project includes several visualizations:

- Average Final Exam Score by Subject
- Average Final Exam Score by Gender
- Average Final Exam Score by Class
- Test 1 vs Final Exam scatter plot
- Test 2 vs Final Exam scatter plot
- Test 1 vs Test 2 scatter plot
- Correlation Heatmap
- Pass vs Fail percentage chart
- Final Exam Score Distribution
- Final Exam Score Box Plot

## ✅ Pass/Fail Analysis

A score of **50% or above** was considered a passing result.

| Result | Percentage |
|---|---:|
| Pass | 88.4% |
| Fail | 11.6% |

## 📦 Outlier Analysis

A box plot was used to examine the spread of Final Exam scores and identify potential outliers.

| Statistic | Score |
|---|---:|
| Minimum | 25% |
| Q1 | 57.4% |
| Median | 68.0% |
| Q3 | 79.33% |
| Maximum | 100% |

No obvious outlier points were observed in the box plot.

## 🔎 Key Findings

- The average Final Exam score was **68.41%**.
- **88.4%** of records achieved a passing Final Exam score.
- Computer had the highest average Final Exam score at **70.64%** among the listed subjects.
- Test 1 and Test 2 showed a strong positive correlation of **0.831**.
- Test 1 and Final Exam scores showed a correlation of **0.792**.
- Test 2 and Final Exam scores showed a correlation of **0.783**.
- Age and Final Exam score showed almost no linear relationship in this dataset, with a correlation of **0.034**.
- The box plot did not show obvious outlier points.

## 📓 Project Notebook

The complete analysis, Python code, calculations, and visualizations are available in:

**`Student Performance Analysis.ipynb`**

## 📝 Conclusion

This project provided practical experience in Python-based Exploratory Data Analysis. It covered data inspection, data quality checks, descriptive statistics, grouping and aggregation, correlation analysis, data visualization, Pass/Fail analysis, and outlier analysis.

The analysis demonstrates how Python libraries such as Pandas, NumPy, and Matplotlib can be used to transform raw student performance data into meaningful statistical insights and visualizations.
