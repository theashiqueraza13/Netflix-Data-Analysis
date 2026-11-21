# Netflix Data Analysis Project

## 1. Project Overview

This project focuses on analyzing Netflix Movies and TV Shows using Python and Data Analytics libraries.

The main objective is to explore the Netflix dataset, clean the data, identify useful patterns, and visualize insights through different charts and graphs.

This project is created as a beginner-level Data Analytics project for B.Tech 1st Year students.

## 2. Objectives

- Analyze Netflix Movies and TV Shows.
- Understand the dataset using Python.
- Identify and handle missing values.
- Remove duplicate records.
- Perform Exploratory Data Analysis (EDA).
- Create meaningful charts and visualizations.
- Discover useful insights from the dataset.

## 3. Technologies Used

- Python3
- Pandas
- Numpy
- VS Code
- Git and GitHub

## 4. Dataset Information

The dataset contains information about Netflix Movies and TV Shows.

**Dataset Details:**

- Total Records: 8,807
- Total Columns: 12

### Dataset Columns

| Column       | Description                  |
| ------------ | ---------------------------- |
| show_id      | Unique ID of each show       |
| type         | Movie or TV Show             |
| title        | Name of the content          |
| director     | Director's name              |
| cast         | Actors and actresses         |
| country      | Country of production        |
| date_added   | Date added to Netflix        |
| release_year | Release year                 |
| rating       | Content rating               |
| duration     | Movie duration or TV seasons |
| listed_in    | Genre or category            |
| description  | Short description of content |

## 5. Project Workflow

### Step 1: Data Collection

Collected the Netflix dataset in CSV format.

### Step 2: Data Understanding

- Loaded the dataset using Pandas.
- Used head(), info(), describe() and shape().
- Checked columns and data types.

### Step 3: Data Cleaning

Performed the following cleaning operations:

- Checked missing values.
- Removed duplicate records.
- Removed unnecessary spaces.
- Standardized text formatting.
- Handled missing values using "Not Available".
- Converted date_added into a consistent date format.
- Converted release_year into a numeric data type.

### Step 4: Exploratory Data Analysis (EDA)

Planned analysis:

- Total number of Movies and TV Shows.
- Country-wise content distribution.
- Most common genres on Netflix.
- Year-wise content releases.
- Distribution of content ratings.

### Step 5: Data Visualization

Created visualizations using Matplotlib and Seaborn to understand patterns and trends in the dataset.

### Step 6: Insights and Conclusion

The findings will be documented after completing the exploratory data analysis.

## 6. Data Cleaning Results

| Details                   | Result |
| ------------------------- | -----: |
| Original Records          |  8,807 |
| Cleaned Records           |  8,807 |
| Duplicate Records Removed |      0 |
| Total Columns             |     12 |
| Missing Values Remaining  |      0 |

## 7. Project Structure

```text
Netflix-Data-Analysis/
│
├── data/
│   ├── netflix_titles.csv
│   └── netflix_titles_cleaned.csv
│
├── notebooks/
│   └── netflix_analysis.ipynb
│
├── images/
│
├── README.md
│
└── requirements.txt
```


```bash
pip install pandas numpy matplotlib seaborn jupyter
```

4. VS Code

```bash
VS Code
```

5. Open the Netflix analysis notebook.
6. Run all the cells to perform the analysis.



## 10. Conclusion

This project provides practical experience in data cleaning, data analysis, and data visualization using Python.

It helps beginners understand how real-world datasets can be processed and analyzed to extract meaningful information.

## 11. Author

**Name:** Ashraf Raza

**Course:** B.Tech (1st Year)

**Project:** Netflix Data Analysis

**Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn
