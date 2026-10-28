# Student Grade Data Processing and Statistical Analysis Using Python

## 📌 Project Overview

This project focuses on processing and analyzing student grade records using Python and Pandas. It transforms raw CSV data into a structured format, calculates statistical summaries, analyzes grade distributions, and identifies top-performing students.

This project was developed as part of **Task 9 of the AI & ML Internship at Veda Technology**.

## 🎯 Objectives

- Load and process student grade records from a CSV file.
- Clean column names and prepare data for analysis.
- Calculate average, highest, and lowest student marks.
- Analyze assessment performance.
- Examine grade distribution.
- Identify the top 10 students based on their average marks.
- Export the processed data into a new CSV file.

## 📂 Dataset Information

**Dataset:** `grade-records.csv`

The dataset contains student grade records with fields related to:

- First Name
- Last Name
- Mid-term Exams
- Final Exam
- Coursework 1 (CW 1)
- Coursework 2 (CW 2)
- Total Points
- Student Average
- Grade

The dataset is used to explore student performance and generate statistical summaries.

## 🛠️ Technologies Used

- **Python** — Programming language
- **Pandas** — Data manipulation and analysis
- **Google Colab / Jupyter Notebook** — Development environment
- **CSV** — Data storage format
- **GitHub** — Version control and project hosting

## ✨ Features

### 1. Data Loading
Reads student records from a CSV file using Pandas.

### 2. Data Cleaning
Standardizes column names and converts percentage values into numeric data for calculations.

### 3. Statistical Analysis
Calculates:
- Number of student records
- Average student marks
- Highest student average
- Lowest student average

### 4. Assessment Analysis
Calculates average, maximum, and minimum marks for the available assessments.

### 5. Grade Distribution
Counts students in each grade category and calculates the percentage distribution.

### 6. Top Student Identification
Identifies the top 10 students according to their recorded student averages.

### 7. Report Generation
Generates a summary report containing student statistics, assessment averages, and grade distribution.

### 8. Data Export
Saves the processed dataset as `processed_grade_records.csv`.

## 🚀 How to Run the Project

### Step 1: Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Replace `YOUR_GITHUB_REPOSITORY_URL` with your actual GitHub repository URL.

### Step 2: Install the Required Library

```bash
pip install pandas
```

### Step 3: Prepare the Dataset

Place `grade-records.csv` in the same directory as your Python notebook or script.

### Step 4: Run the Notebook

Open the notebook in Google Colab or Jupyter Notebook and execute the cells in order.

### Step 5: View the Results

Review the processed records, statistical summaries, grade distribution, and top 10 students.

The program also exports the processed records to a new CSV file.

## 📊 Expected Results

After successful execution, the project produces:

- A cleaned student dataset
- Summary statistics for student averages
- Assessment performance statistics
- Grade distribution analysis
- A table of the top 10 students
- A final student data processing report
- An exported CSV file containing processed records

**Note:** The actual results depend on the contents of the input dataset.

## 📁 Project Structure

```text
Student-Grade-Data-Processing/
│
├── grade-records.csv
├── Task9.ipynb
├── processed_grade_records.csv
└── README.md
```

*The processed CSV file is generated after running the notebook. Include it in the repository only if you want to publish the output.*

## 🎓 Learning Outcomes

Through this project, I gained practical experience in:

- Python programming and reusable functions
- Working with lists and dictionaries
- Data cleaning and preprocessing
- Using Pandas for data analysis
- Calculating statistical measures
- Analyzing student performance
- Reading and writing CSV files
- Organizing and documenting a Python project

## 👨‍💻 Internship Details

- **Organization:** Veda Technology
- **Track:** AI & ML
- **Task:** Task 9 — Python Data Processing

