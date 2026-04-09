# Titanic Data Analysis & Custom Dataset Creation
**Data Science Bootcamp - Task 3**

## 📌 Project Overview
This project consists of two main parts designed to demonstrate proficiency in Python's `pandas` library:
1.  **Custom Dataset Creation:** Building a structured DataFrame from a Python dictionary with custom indexing.
2.  **Titanic Dataset Analysis:** Cleaning, filtering, and analyzing the classic Titanic passenger manifest to uncover survival trends.

## 🛠️ Technologies Used
* **Python 3**
* **Pandas:** For data manipulation and analysis.
* **Google Colab:** As the development environment.

## 📂 Dataset Description
* **Custom Dataset:** A 15-row dataset representing a fictional Tech Startup, including columns for Department, Salary, Remote status, and Experience.
* **Titanic Dataset:** The standard `train.csv` file containing passenger demographics and survival outcomes.

## 🧹 Data Cleaning Steps
To ensure analysis accuracy, the following steps were taken:
* Filled missing **Age** values using the **median**.
* Filled missing **Embarked** values using the **mode**.
* Dropped the **Cabin** column due to excessive missing data.
* Verified and removed any duplicate rows.

## 📊 Key Insights
* **Gender:** Females had a significantly higher survival rate (~74%) than males (~19%).
* **Class:** Survival was strongly correlated with passenger class; 1st Class passengers were prioritized and had the highest survival probability.
* **Age:** Children (0-12) were prioritized for lifeboats, showing a higher survival rate than the adult average.
* **Top Survival Group:** The demographic with the highest survival rate was **Females in 1st Class**.

## 🚀 How to Run
1.  Clone this repository.
2.  Upload the `train.csv` file to your environment.
3.  Run the `.ipynb` notebook cells sequentially.
