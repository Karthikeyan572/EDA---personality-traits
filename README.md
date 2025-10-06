# 🧠 Personality Traits Analysis

## Project Overview

This project conducts **Exploratory Data Analysis EDA** and initial modeling preparation on a dataset focused on **personality traits** specifically distinguishing between **Extroverts and Introverts**

The goal is to analyze behavioral metrics like social activity and solitary time to understand how they correlate with an individuals personality type

The core analysis is performed and documented in the **personality_traitsipynb** Jupyter Notebook

---

## Technical Stack

* **Primary Language** Python
* **Key Libraries**
    * **pandas** and **numpy** for data manipulation
    * **matplotlibpyplot** and **seaborn** for data visualization
* **Environment** Jupyter Notebook or JupyterLab

---

## Dataset and Data Dictionary

The analysis uses a dataset loaded from **personality_datasetcsv** It contains 2900 rows and 8 columns of behavioral data

| Column Name | Description | Example Values |
| :--- | :--- | :--- |
| **Time_spent_Alone** | The amount of time spent in solitary activities | 00 to 110 |
| **Stage_fear** | Indicates presence of stage or public speaking anxiety | Yes No |
| **Social_event_attendance** | Frequency or measure of attending social gatherings | 00 to 100 |
| **Drained_after_socializing** | Whether socializing results in mental fatigue | Yes No |
| **Friends_circle_size** | The number of people in the individuals close friend group | 00 to 150 |
| **Personality** | The target variable classifying the individual | Extrovert Introvert |

---

## Analysis Highlights from Notebook

The notebook **personality_traitsipynb** performs these essential data science steps

* **Data Loading** The dataset of 2900 samples was loaded
* **Missing Value Check** The statistical summary shows columns like **Friends_circle_size** have missing values that need handling before modeling
* **Initial Exploration** The analysis includes basic descriptive statistics to understand the central tendency and spread of numerical features

---

## Contribution and Git Push Workflow

To contribute new code or analysis to this repository follow these steps

1.  **Stage your changes**
    ```bash
    git add .
    ```
2.  **Commit the changes**
    ```bash
    git commit -m "feat Added new correlation matrix visualization"
    ```
3.  **Push the commit to the remote repository**
    ```bash
    git push origin [your-branch-name]
    ```