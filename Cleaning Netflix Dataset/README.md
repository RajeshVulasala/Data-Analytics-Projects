# Netflix Data Cleaning & Preparation Project

An end-to-end data cleaning and exploratory preparation project using Python and Pandas to transform a raw Netflix movies and TV shows dataset into a clean, analysis-ready format.

---

## 📋 Project Overview
Raw datasets frequently contain structural anomalies, missing values, and formatting inconsistencies. This project processes the raw Netflix dataset to ensure absolute data integrity, appropriately handle missing information, and convert columns into the correct data types for downstream analysis and machine learning.

---

## 🛠️ Tech Stack & Libraries
* **Python**
* **Pandas** (Data manipulation, cleaning, and transformation)
* **NumPy** (Numerical operations)
* **Jupyter Notebook** (Development environment)

---

## 🔍 Data Cleaning Workflow
1. **Handling Missing Values:**
   * Computed null counts across all columns via `.isnull().sum()`.
   * Replaced missing categorical text values (`director`, `cast`, `country`, and `rating`) with appropriate placeholder labels (`"Unknown"`).
2. **Data Type Standardization:**
   * Converted date entries (such as `date_added`) from string/object representations into robust **datetime** objects using `pd.to_datetime()`.
3. **Duplicate Verification:**
   * Evaluated row-level duplication (`df.duplicated().sum()`), confirming zero duplicate rows exist in the final dataset.
4. **Exporting Cleaned Data:**
   * Exported the fully processed and validated DataFrame to a clean CSV file (`cleaned_netflix_dataset.csv`).

---

## 📂 Project Structure
```text
├── Cleaning Netflix Dataset.ipynb    # Jupyter Notebook detailing step-by-step code
├── cleaned_netflix_dataset.csv       # Final processed dataset output
└── README.md                         # Project documentation
```
🌐 Live Project URL
https://drive.google.com/file/d/1g8TbWz_nJoNqGW2-lR9oFSJjntjRkpbH/view?usp=sharing

🚀 How to Run Locally
Clone this repository or download the source files.

Launch Jupyter Notebook or Jupyter Lab:

```
jupyter notebook
```
Open Cleaning Netflix Dataset.ipynb to inspect and execute the complete data cleaning pipeline.

👤 Author
Rajesh Vulasala
