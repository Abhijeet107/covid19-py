# covid19-py
Navigating COVID-19 Data with Python

# 🧪 Navigating COVID-19 Data with Python

A hands-on data analysis project using Python and Pandas to explore and extract insights from a COVID-19 dataset.

## 📌 Project Overview

This project is a practical walkthrough of analyzing real-world COVID-19 data. It covers data cleaning, exploratory analysis, and basic visualization using popular Python libraries.

**Key Objectives:**
- Understand the structure of the dataset.
- Identify and visualize missing values.
- Filter and sort records for meaningful insights.
- Highlight regional patterns in confirmed and recovered cases.

## 🗂️ Dataset

The dataset used in this project is a subset of a larger COVID-19 dataset from [Kaggle](https://www.kaggle.com/). It contains data up to **April 29, 2020**.

Columns include:
- `Date`
- `State`
- `Region`
- `Confirmed`
- `Deaths`
- `Recovered`

## 🛠️ Tools & Libraries

- Python 3.x
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

## 📊 Key Analysis Techniques

- `data.count()`: Check non-null entries
- `data.isnull().sum()`: Identify missing values
- `sns.heatmap(data.isnull())`: Visualize missing data
- Boolean indexing for filtering (`data[~(data.Confirmed < 10)]`)
- Grouping and aggregation (`data.groupby('Region').sum()`)
- Sorting for trends (ascending confirmed, descending recovered)

## 📈 Insights

- The United States had the highest confirmed cases.
- Spain showed strong recovery numbers despite high case counts.
- Filtering out entries with <10 confirmed cases helped streamline the analysis.
- Sorting and grouping revealed regional trends and healthcare response effectiveness.

## 🚀 Next Steps

The current dataset contains 321 entries, but the original Kaggle dataset has **19,000+ rows**. Scaling this analysis to the full dataset will provide even deeper insights and more robust data handling experience.

## 📁 Folder Structure
 Navigating-COVID-19-Data/
├── covid_analysis.ipynb
├── dataset.csv
├── README.md
└── images/
├── heatmap_missing_data.png
├── confirmed_cases_sorted.png
└── recovered_cases_sorted.png


## 🙌 Acknowledgments

- Data Source: [Kaggle COVID-19 Dataset](https://www.kaggle.com/)
- Developed by: Abhijeet Kuanr

## 📬 Let's Connect

Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/abhijeet-kuanr-6a2672160) or explore more of my projects [here](https://github.com/Abhijeet107).

---


