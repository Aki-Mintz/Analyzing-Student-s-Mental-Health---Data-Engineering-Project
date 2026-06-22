# Analyzing-Student-s-Mental-Health--Data-Engineering-Project

# Analyzing Students' Mental Health

## Overview

This project explores the mental health of international students using SQL. The analysis is based on survey data collected from a Japanese international university to investigate whether the length of stay influences depression levels, social connectedness, and acculturative stress.

Using SQL queries, the project summarizes key mental health indicators and identifies trends among international students.

---

## Objectives

- Analyze the relationship between the length of stay and students' mental health.
- Calculate average depression, social connectedness, and acculturative stress scores.
- Practice SQL aggregation and filtering techniques.
- Generate insights from a real-world dataset.

---

## Dataset

The dataset contains survey responses from students enrolled at a Japanese international university.

### Key Columns

| Column | Description |
|--------|-------------|
| `inter_dom` | Student type (International or Domestic) |
| `stay` | Length of stay in Japan |
| `todep` | Depression score (PHQ-9) |
| `tosc` | Social connectedness score (SCS) |
| `toas` | Acculturative stress score (ASISS) |

---

## Tools Used

- SQL
- PostgreSQL
- DataCamp Workspace

---

## SQL Concepts Demonstrated

- SELECT
- WHERE
- GROUP BY
- COUNT()
- AVG()
- ROUND()
- ORDER BY

---

## Analysis Performed

The project focuses on international students by:

- Filtering the dataset to include only international students.
- Grouping students according to their length of stay.
- Counting the number of students in each group.
- Calculating the average depression score.
- Calculating the average social connectedness score.
- Calculating the average acculturative stress score.
- Comparing mental health indicators across different lengths of stay.

---

## Key Insight

The analysis provides an overview of how mental health indicators vary among international students with different lengths of stay. These findings can help better understand the challenges faced by students adapting to a new country and environment.

---

## Repository Structure

```
├── notebook.ipynb
├── README.md
└── mentalhealth.jpg
```

---

## Learning Outcomes

Through this project, I strengthened my skills in:

- Writing analytical SQL queries
- Aggregating and summarizing data
- Working with real-world datasets
- Extracting insights from relational databases
- Presenting data-driven findings

---

## Acknowledgment

This project was completed as part of the DataCamp Associate Data Engineer in SQL learning track using a guided real-world dataset.
