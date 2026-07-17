# Fatherhood Program

## Tools Used
- Python (pandas, numpy)
- Tableau

## Key Features
- Python cleaning script for coded survey responses
- Parameter-driven filtering across 5 data fields
- Interactive map to view regional and location-based data/trends

## Overview
This project is a retrospective exploratory data analysis of a Fatherhood Program that was implemented in a non-profit organization from 2021-2025. 
This program served fathers and father figures in predominantly rural and suburban areas and aimed to improve parenting skills through evidence-based curricula in group sessions.
Key performance indicators include enrollments, completions, completion rates, and the number of children served over the duration of the program.

Data exported from the database contained coded survey responses, which were mapped and cleaned using a Python script in conjunction with a data dictionary.

The dashboard, built in Tableau, includes 3 visualizations:
- Running totals of enrollments and completions over time
- Completion rates based on various characteristics of program participants, which can be toggled with a parameter
- Interactive map of all areas served, allowing for drill-down of specific regional data points and trends

## Dashboard
[View Interactive Dashboard on Tableau Public](https://public.tableau.com/views/Fatherhood/EnrollmentandCompletion?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Data Notice
All personally-identifiable information (PII) was removed from this dataset prior to upload into Tableau, including name, address, email, and phone. Each individual is represented by a unique code number. 
