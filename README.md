# 📊 Job Market Analysis

This project analyzes job listings and salary data to understand trends in job roles, required experience levels, and salary expectations. It involves cleaning and merging datasets, classifying experience levels, and preparing the data for further analysis or modeling.

## 🚀 Project Goals

- Understand which roles are in demand and where.
- Categorize job listings based on required experience level.
- Merge job role information with salary data to explore compensation expectations.
- Create a clean, structured dataset ready for further analysis or visualization.

---

## 📁 Datasets

### `job_postings.csv`
- `job_title`
- `company_name`
- `location`
- `post_Date`
- `Qualifications`
- `post_days_ago`

### `sal.csv`
- `job_title`
- `experience_level`
- `salary_ex_level`

---

## 🧹 Data Preparation

We began by selecting only the relevant columns from a raw job postings dataset. This helped reduce noise and focus only on useful attributes like job title, company, location, posting date, and qualification requirements.

---
## 🧠 Experience Level Classification

A custom rule-based method was used to classify job listings into entry-level, mid-level, and senior-level categories. This was based on keywords found in the job qualification text, allowing us to tag each listing with a standardized experience label for comparison and filtering.

---

## 🔗 Dataset Merging

After classifying experience levels, we merged the job postings dataset with a salary dataset based on matching job titles and experience categories. This enabled a consolidated view combining role requirements with expected salary bands.

---

## 🎯 Outcome

The final output is a well-structured dataset that can answer questions such as:
- What are the most common roles at each experience level?
- Which locations offer higher-paying jobs for a given title?
- How does experience requirement correlate with salary expectations?

---
