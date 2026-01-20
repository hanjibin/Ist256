Python individual project P3.py
# IST256 Python Project — Korea Income & Welfare Data Story

This project builds a small “data story” using a Korea income & welfare dataset.  
Goal: explore how income patterns differ by **gender, occupation, education, age, non-working reasons, and region**.

## What I did
- Cleaned messy columns (occupation / company size / non-working reasons) by stripping blank strings and labeling missing info.
- Converted coded variables into readable labels (gender, education, age groups, and region).
- Created a new metric **income_per_person = income / family_member** to compare living standard more fairly.
- Merged an occupation translation table (**job_code_translated.xlsx**) so job codes become readable job titles.
- Built comparisons and visualizations (Seaborn/Matplotlib):  
  - gender income gap  
  - top 10 vs bottom 10 occupations by income + gender composition  
  - education and age patterns  
  - non-working reason groups and income_per_person  
  - regional comparisons + interactive Folium map (switchable metric)

## Outputs / Highlights
- Bar charts for group comparisons (gender, education, age, occupation, region)
- Income per person distribution by gender
- Interactive regional map (Folium) showing income patterns by location

## Data source
Dataset was downloaded from Kaggle (public dataset).  
**Raw CSV is not included in this repo** (file size / licensing).  
To run this project, download the dataset and place it in the project folder as:
- `Korea_income_and_Welfare.csv`

## How to run
Open `P3.ipynb` and run cells from top to bottom.
