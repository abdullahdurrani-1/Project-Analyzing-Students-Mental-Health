# Project-Analyzing-Students-Mental-Health
Here's a professional and engaging **GitHub README description** for your project. It highlights the research question, tools used (PostgreSQL), and the key findings you're analyzing:

---

## 🌍 International Students' Mental Health Analysis with PostgreSQL

### 🧠 Project Overview

This project explores whether studying abroad impacts the mental health of international students, inspired by a 2019 study conducted at a Japanese international university. The original study revealed that international students are more vulnerable to mental health difficulties, and identified **social connectedness** and **acculturative stress** as key predictors of **depression**.

Using a student dataset and PostgreSQL for data analysis, this project investigates:

* 📊 **Is there a correlation between depression and social connectedness or acculturative stress?**
* 📈 **Does the length of stay influence mental health metrics for international students?**
* 🧮 **How do international students compare in terms of average scores across mental health indicators?**

---

### 🔍 Key Analyses

* Filtered and grouped international students (`inter_dom = 'Inter'`)
* Calculated average scores for:

  * **Depression** (`todep`)
  * **Social Connectedness** (`tosc`)
  * **Acculturative Stress** (`toas`)
* Aggregated results by **length of stay**
* Sorted data to find meaningful trends using `GROUP BY` and `ORDER BY`

---

### 🛠️ Tools Used

* **SQL Language**: PostgreSQL
* **Concepts Applied**: Aggregation, Filtering, Grouping, Conditional Analysis
* **Environment**: Google Colab

---

### 📌 Key Findings

* Longer stays tend to correlate with slightly improved social connectedness but may also increase stress or depression in certain cases.
* Depression scores tend to be influenced by both **social integration** and **stress adapting to the new culture**.

---

### 📚 Learning Highlights

* Practical experience using **PostgreSQL** for real-world data analysis
* Interpreting psychological survey data through **SQL queries**
* Understanding how structured data can support social research


