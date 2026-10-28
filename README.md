# 1.Clean the Netflix Dataset

This project is part of the [Clean the Netflix Dataset](https://roadmap.sh/projects/cleaning-netflix-dataset) challenge on roadmap.sh. 

## Project Overview
The goal of this project is to load the Netflix Movies and TV Shows dataset from Kaggle and perform a thorough data cleaning process using Python and Pandas. Rather than simply dropping missing values, this project focuses on analyzing missingness, standardizing column types, handling mixed-format data, and properly parsing timestamps.

## Technologies Used
- Python
- Pandas
- Jupyter Notebook / Kaggle Notebook

## Project Steps & Implementation
1. **Inspection**: Inspected the raw dataset using `.info()`, `.describe()`, and `.head()` to understand data shapes, types, and missing values.
2. **Missing Value Handling**: Replaced missing categorical values in `director`, `cast`, `country`, and `rating` with `"Unknown"` to preserve dataset rows and prevent bias against older or international titles.
3. **Datetime Parsing**: Cleaned trailing whitespace in `date_added`, parsed it into proper datetime objects using `pd.to_datetime()`, and handled remaining nulls cleanly.
4. **Export**: Exported the final polished data into a clean CSV file (`cleaned_netflix_dataset.csv`).

---
*Cleaned dataset and notebook developed as part of data analytics practice.*
