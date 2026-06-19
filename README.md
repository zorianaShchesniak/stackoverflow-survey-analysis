# stackoverflow-survey-analysis
Exploratory Data Analysis (EDA) of the global Stack Overflow Developer Survey dataset using Python and Pandas to extract demographic, salary, and technology insights.


Markdown
# Stack Overflow Developer Survey Analysis (Python & Pandas)

## 📌 Project Overview
In this project, I performed an Exploratory Data Analysis (EDA) on the global Stack Overflow Developer Survey dataset. Using Python and the **Pandas** library, I analyzed survey responses to uncover patterns in developer demographics, remote work trends, education paths, and global compensation models. 

This analysis highlights my ability to manipulate large datasets, clean missing data, handle multi-valued categorical features, and extract data-driven conclusions.

---

## 🛠️ Tools & Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy (for data manipulation and descriptive statistics)
* **Environment:** Jupyter Notebook / Google Colab

---

## 💾 Core Metrics & Tasks Solved

Here is what I accomplished step-by-step in my Jupyter Notebook:

1. **Dataset Volume:** Loaded and parsed the main public survey file (`survey_results_public.csv`) alongside the metadata schema to determine the total number of respondents.
2. **Data Completeness Analysis:** Extracted questions from the schema file using the `qname` field and performed a set intersection to count how many respondents filled out the survey completely without missing values.
3. **Descriptive Statistics:** Analyzed the `WorkExp` column, calculating measures of central tendency (**Mean, Median, and Mode**) to understand developer experience levels while correctly handling `NaN` values.
4. **Remote Work Trends:** Filtered categorical work-format fields to isolate and count the total number of specialists fully working remotely.
5. **Python Popularity:** Calculated the overall percentage of respondents using Python. Since the programming languages column allows multiple values per row, I implemented string matching logic to ensure accurate counts.
6. **Education Patterns:** Investigated the educational landscape to find exactly how many developers used online courses as a primary or supplementary learning resource.
7. **Geographic Salary Breakdown:** Grouped data by country specifically for Python developers to compute and compare both **mean and median annual compensation** (`ConvertedCompYearly`) in a clean tabular format.
8. **Top Earners Education:** Sorted global income data in descending order to isolate the Top 5 highest-paid respondents and analyzed their corresponding formal education levels.

---

## 📊 Repository Contents
* `stackoverflow_analysis.ipynb` – The complete Jupyter Notebook with clean code, execution outputs, and descriptive comments for each task.
* `survey_results_schema.csv` – The metadata schema file containing question mappings used during the analysis.

---

## 💡 Key Learnings
Working on this project helped me master advanced Pandas methods like `.str.contains()
