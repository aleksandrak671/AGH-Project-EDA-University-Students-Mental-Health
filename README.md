# EDA - University Students' Mental Health

## Project Description

Exploratory Data Analysis (EDA) of mental health among university students, based on survey data collected from students at a university in Malaysia. The goal is to better understand factors related to students' mental well-being, examine their distribution in the sample, and answer a set of research questions.

The analysis includes:
- Loading, cleaning, and initial preparation of the data
- Describing the variables and their distributions
- Answering ten research questions, supported by statistical tests (chi-square, Pearson correlation, linear regression)
- Visualization and interpretation of the results

## Dataset

The data was collected through an online survey (Google Forms) and contains **1000 responses described by 16 variables**, grouped into:
- **Demographics and academics:** gender, age, field of study (course), year of study, CGPA (grade average)
- **Mental health indicators:** depression, anxiety, panic attacks, specialist treatment, symptom frequency (last 7 days), access to mental health support
- **Study and lifestyle:** sleep quality, study stress level, study hours per week, academic engagement

## Technologies

The project was developed in **R Markdown** using packages such as:
- dplyr, tidyr, readr, stringr, forcats (data manipulation)
- ggplot2, scales, RColorBrewer, corrplot (visualization)
- knitr, kableExtra, DT (tables and report output)

## Data Source and Context

The data comes from a publicly available dataset on Kaggle:
[University Students' Mental Health Dataset on Kaggle](https://www.kaggle.com/datasets/junnn0126/university-students-mental-health/data)

This project was prepared as part of the **Introduction to Data Analysis 2024/25** university course, as a practical example of applying exploratory data analysis (EDA) methods.
