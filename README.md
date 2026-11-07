# 📊 Learn Data Science

![Level: Beginner](https://img.shields.io/badge/Level-Beginner-2ea44f)
![Path: Python, SQL, Statistics, ML](https://img.shields.io/badge/Path-Python%20%7C%20SQL%20%7C%20Statistics%20%7C%20ML-3776AB?logo=python&logoColor=white)
![Tools: NumPy, pandas, Jupyter, matplotlib](https://img.shields.io/badge/Tools-NumPy%20%7C%20pandas%20%7C%20Jupyter%20%7C%20matplotlib-F37626?logo=jupyter&logoColor=white)
![Free options first](https://img.shields.io/badge/Resources-Free%20options%20first-6f42c1)
[![Last updated](https://img.shields.io/github/last-commit/ImmuneMoon/Learn-Data-Science?label=updated)](https://github.com/ImmuneMoon/Learn-Data-Science/commits/main)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey)](LICENSE)

**📄 [Download the PDF](Learn-Data-Science.pdf)**

## 📖 Overview
**Learn Data Science** is a plain-language route into working with data: asking a question, finding and cleaning the data, analyzing it, and showing what you found. It covers:
- what data science is, and how data analysts, data scientists and machine learning engineers differ;
- the order to learn things in: Python, then SQL, then statistics, then the Python data stack (NumPy, pandas, Jupyter and matplotlib), then machine learning basics;
- a first notebook and a first machine learning model, with code you can run;
- a set of edX courses, whether you can audit them for free, and what the certificate costs;
- more free courses (Kaggle Learn, freeCodeCamp, Harvard's CS50 courses and others), free datasets, and projects to build.

## ⚠️ Important Notes
* **Course prices change, and sales are frequent.** The edX prices here are from November 2026, during a sale period. Always check the course page before you pay.
* **"Free to audit" on edX is limited.** Auditing gives you the course materials for a set time, but not the graded assignments or a certificate. See Section 9.
* **None of these course providers or creators are affiliated with this guide.** Videos are credited to their channels; watch them there.
* **Check a dataset's license before you publish work based on it,** and never put personal data you collected about real people into a public project.

## 🚀 How to Use
Download the PDF above, or read on below. If you're brand new, read Sections 1 to 3, then work through Sections 4 to 8 in order, one step at a time. Section 9 onward is a menu of courses, datasets and projects to pick from.

This guide works alongside these others:
* [Python and Node Tool Environments](https://github.com/ImmuneMoon/Python-and-Node-Tool-Environments) - Installing Python and keeping each project in its own virtual environment.
* [Learn Back-End Web Development](https://github.com/ImmuneMoon/Learn-Back-End-Web-Development) - Its SQL section is a good first look at databases.
* [Computer Science Fundamentals](https://github.com/ImmuneMoon/Computer-Science-Fundamentals) - Data structures, algorithms, and the math different fields need.
* [Safer Package Installs with npm and pip](https://github.com/ImmuneMoon/Safer-Package-Installs-npm-and-pip) - Installing Python packages without picking up malicious ones.
* [Learning How to Learn Programming](https://github.com/ImmuneMoon/Learning-How-to-Learn-Programming) - Study habits, avoiding tutorial hell, and staying well.
* [Coding Practice and Interview Prep](https://github.com/ImmuneMoon/Coding-Practice-and-Interview-Prep) - Practice sites and technical interviews, including SQL and Python problems.
* [Publishing to GitHub with gh](https://github.com/ImmuneMoon/Publishing-to-GitHub-with-gh) - Putting your notebooks and projects on GitHub.

---

<!-- guide:start -->

## Contents

1. [What Data Science Is](#1-what-data-science-is)
2. [The Roles: Analyst, Data Scientist and ML Engineer](#2-the-roles-analyst-data-scientist-and-ml-engineer)
3. [The Path at a Glance](#3-the-path-at-a-glance)
4. [Step 1: Python](#4-step-1-python)
5. [Step 2: SQL](#5-step-2-sql)
6. [Step 3: Statistics and the Math Behind It](#6-step-3-statistics-and-the-math-behind-it)
7. [Step 4: The Data Stack](#7-step-4-the-data-stack)
8. [Step 5: Machine Learning Basics](#8-step-5-machine-learning-basics)
9. [The edX Courses](#9-the-edx-courses)
10. [More Free Courses and References](#10-more-free-courses-and-references)
11. [Practice: Where to Find Datasets](#11-practice-where-to-find-datasets)
12. [Projects to Build](#12-projects-to-build)
13. [Common Mistakes](#13-common-mistakes)
14. [Sources](#14-sources)

---

## 1. What Data Science Is
Data science is using data to answer questions and make decisions. Most projects follow the same loop:

1. **Ask a question.** "Which products sell best in winter?" or "Can we tell which emails are spam?"
2. **Get the data.** From a spreadsheet, a database (using SQL), a website's API, or a public dataset.
3. **Clean it.** Fix missing values, duplicates, typos and wrong types. This is often most of the work.
4. **Explore and analyze it.** Summaries, charts and statistics, to see what's really there.
5. **Model it, if needed.** Use statistics or machine learning to explain or predict something.
6. **Communicate it.** Charts, a short report or a dashboard that someone else can act on.

You'll use a programming language (usually **Python**, sometimes R), **SQL** for databases, **statistics** to know whether a pattern is real, and **visualization** to show it.

## 2. The Roles: Analyst, Data Scientist and ML Engineer
Job titles overlap, and every company uses them a little differently. Read the job posting, not just the title.

| Role | What the work looks like | Core skills |
|---|---|---|
| **Data analyst** | Answers business questions with existing data: reports, dashboards, "what happened and why?" | SQL, spreadsheets, a dashboard tool (such as Power BI or Tableau), basic statistics, often Python |
| **Data scientist** | Deeper analysis, experiments (such as A/B tests), and predictive models | Python, SQL, statistics, machine learning, communicating results |
| **Machine learning engineer** | Builds, deploys and maintains models in real products, so they run reliably at scale | Strong software engineering, Python, ML frameworks, cloud and DevOps basics |
| **Data engineer** (related) | Builds the pipelines and databases that everyone else's data comes from | SQL, Python, databases, cloud data tools |

**A realistic note on getting in:** analyst roles are the most common way in. Many data scientist roles ask for a degree in math, statistics or computer science, and some ask for a master's. The US Bureau of Labor Statistics (BLS) says data scientists typically need at least a bachelor's degree, reports a median pay of $120,230 in May 2025, and projects 35% employment growth from 2025 to 2035. Those are US figures; check your own country's sources.

If you like the engineering side more than the analysis side, [Getting Started with DevOps](https://github.com/ImmuneMoon/Getting-Started-with-DevOps) covers the deployment and cloud skills ML engineers lean on.

## 3. The Path at a Glance
Learn these in order, and don't take on more than one new thing at a time. Build something small at each step before moving on.

| Step | Learn | You're ready to move on when you can... |
|---|---|---|
| 1 | **Python** | Write a script with variables, loops, functions, lists and dictionaries, and read a file |
| 2 | **SQL** | Filter, sort, group and join tables to answer a question |
| 3 | **Statistics** | Explain mean, median, spread, distributions, correlation, and why a sample can mislead |
| 4 | **The data stack** | Load a CSV into pandas in Jupyter, clean it, summarize it, and chart it with matplotlib |
| 5 | **Machine learning basics** | Split data into training and test sets, train a simple model, and judge it honestly |

roadmap.sh has visual roadmaps for the [Data Analyst](https://roadmap.sh/data-analyst), [AI and Data Scientist](https://roadmap.sh/ai-data-scientist), [Machine Learning](https://roadmap.sh/machine-learning), [Python](https://roadmap.sh/python) and [SQL](https://roadmap.sh/sql) paths, if you like to see the whole map.

## 4. Step 1: Python
Python is the main language of data science, because of its libraries: NumPy, pandas, matplotlib, scikit-learn and many more.

1. **Install Python and set up a virtual environment.** The [Python and Node Tool Environments](https://github.com/ImmuneMoon/Python-and-Node-Tool-Environments) guide walks through installing Python on Windows and [creating a virtual environment](https://github.com/ImmuneMoon/Python-and-Node-Tool-Environments#5-create-a-virtual-environment) for each project.
2. **Learn the basics** with one course, not five. Good free choices:
   * **[CS50's Introduction to Programming with Python](https://cs50.harvard.edu/python/)** (CS50P, Harvard, free). Ten weeks: functions, conditionals, loops, exceptions, libraries, unit tests, file input and output, regular expressions and object-oriented programming, plus a final project. Score at least 70% on every problem and the final project to earn a free CS50 certificate; a paid edX certificate is optional.
   * **[Kaggle Learn: Intro to Programming](https://www.kaggle.com/learn) and Python** (free, short, in the browser). Good if you want to get to data quickly.
   * **[freeCodeCamp Python Certification](https://www.freecodecamp.org/learn/python-v9/)** (free). Theory, workshops and labs, five required projects, then a certification exam.
3. **Build a tiny project** before moving on, such as a script that reads a CSV file of your expenses and prints the total per category.

## 5. Step 2: SQL
Most company data lives in databases, so SQL is a must for every data role, and it's often tested in analyst interviews.

Learn to:
* select columns and filter rows (`SELECT`, `WHERE`);
* sort and limit (`ORDER BY`, `LIMIT`);
* summarize (`COUNT`, `SUM`, `AVG`, `GROUP BY`, `HAVING`);
* combine tables (`JOIN`).

```sql
-- Total sales per category, biggest first
SELECT category, SUM(amount) AS total_sales
FROM orders
WHERE order_date >= '2026-01-01'
GROUP BY category
ORDER BY total_sales DESC;
```

**Where to learn it:**
* **[CS50's Introduction to Databases with SQL](https://cs50.harvard.edu/sql/)** (CS50 SQL, Harvard, free). Seven weeks, using SQLite, with an introduction to PostgreSQL and MySQL at the end.
* **[Kaggle Learn](https://www.kaggle.com/learn): Intro to SQL and Advanced SQL** (free). Uses Google BigQuery in the browser.
* **[SQLBolt](https://sqlbolt.com/):** short interactive lessons with an exercise at the end of each one.
* **[IBM SQL for Data Science on edX](https://www.edx.org/learn/data-science/ibm-sql-for-data-science)** (Section 9).
* The [Learn Back-End Web Development guide's SQL section](https://github.com/ImmuneMoon/Learn-Back-End-Web-Development#8-databases-sql-first-nosql-when-it-fits) explains tables, SQLite and PostgreSQL, and how to pass values to a database safely from Python.

**Tip:** SQLite is built into Python (`import sqlite3`), so you can practice SQL on your own PC without installing a database server.

## 6. Step 3: Statistics and the Math Behind It
Statistics is what turns "the numbers went up" into "the numbers went up, and it probably isn't chance". You don't need a math degree to start, but you do need these ideas:

* **Describing data:** mean, median, mode, range, variance and standard deviation.
* **Distributions:** the normal distribution, skew, and outliers.
* **Probability:** the basics, and conditional probability.
* **Sampling:** why a sample can mislead, and what bias is.
* **Relationships:** correlation, and why correlation isn't causation.
* **Inference:** confidence intervals, hypothesis tests and p-values, and what they do and don't tell you.

Machine learning later adds **linear algebra** (vectors and matrices), a little **calculus** (how models improve step by step) and more probability. The [Computer Science Fundamentals guide's math section](https://github.com/ImmuneMoon/Computer-Science-Fundamentals#7-math-for-programmers) shows which math each field needs.

**Free ways to learn it:**
* **[Khan Academy: Statistics and probability](https://www.khanacademy.org/math/statistics-probability)** (free). Short videos and practice, from reading graphs up to inference.
* **[OpenIntro Statistics](https://www.openintro.org/book/os/)** (free PDF, or a paid printed copy). A complete, widely used introductory textbook.
* **[StatQuest with Josh Starmer](https://www.youtube.com/@statquest)** (YouTube). Clear, friendly explanations of statistics and machine learning ideas.
* **3Blue1Brown, [Essence of linear algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) and [Essence of calculus](https://www.youtube.com/playlist?list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr)** (YouTube playlists). Visual introductions for when you reach machine learning.

## 7. Step 4: The Data Stack
### 7.1 What each tool does

| Tool | What it's for |
|---|---|
| **NumPy** | Fast arrays of numbers and the math on them. Most other data libraries are built on it. |
| **pandas** | Tables of data (called **DataFrames**): loading CSV and Excel files, cleaning, filtering, grouping and joining. The tool you'll use most. |
| **Jupyter** | Notebooks: code, results, charts and notes together in one document, run one cell at a time. **JupyterLab** is the full editor; **Jupyter Notebook** is the simpler classic one. |
| **matplotlib** | Charts: line, bar, scatter, histograms and more. pandas uses it for its own `.plot()` charts. |
| **seaborn** (optional) | Nicer statistical charts with less code, built on matplotlib. |
| **scikit-learn** | Machine learning (Section 8). |

You don't need to pin exact versions to learn. Install the current releases into a virtual environment, and check each project's site for what's new.

### 7.2 Set up a project with Jupyter
These steps use Windows PowerShell. Use your own folder name.

1. Make a folder for the project and open it:
   ```powershell
   mkdir C:\Projects\first-analysis
   cd C:\Projects\first-analysis
   ```
2. Create and activate a virtual environment:
   ```powershell
   py -m venv .venv
   .\.venv\Scripts\Activate.ps1
   ```
   If PowerShell says **running scripts is disabled on this system**, see [Section 7 of the Python and Node Tool Environments guide](https://github.com/ImmuneMoon/Python-and-Node-Tool-Environments#7-activate-a-venv-and-the-powershell-script-error).
3. Install the data stack. pandas installs NumPy for you:
   ```powershell
   python -m pip install jupyterlab pandas matplotlib scikit-learn
   ```
4. Start JupyterLab. It opens in your browser:
   ```powershell
   jupyter lab
   ```
5. Click **Python 3** under **Notebook** to create a new notebook. To stop JupyterLab later, close the tab and press **Ctrl+C** in the terminal.

On macOS and Linux, use `python3 -m venv .venv` and `source .venv/bin/activate` instead. For the classic interface, install `notebook` and run `jupyter notebook`.

**Prefer not to install anything yet?** [Try Jupyter](https://jupyter.org/try) runs JupyterLab in your browser through JupyterLite (download anything you want to keep), and [Google Colab](https://colab.research.google.com/) gives you hosted notebooks with a Google account. Kaggle's own notebooks also run in the browser.

### 7.3 A first analysis
Put any CSV file in your project folder (Section 11 lists free datasets) and change `data.csv` and the column name to match yours. Run each block in its own notebook cell.

```python
import pandas as pd
import matplotlib.pyplot as plt

df = pd.read_csv("data.csv")

df.head()          # the first five rows
df.info()          # column names, types and missing values
df.describe()      # count, mean, spread, min and max of number columns
```

```python
# Clean: drop exact duplicate rows, and count what's still missing
df = df.drop_duplicates()
df.isna().sum()
```

```python
# Summarize one column, then chart it
df["price"].describe()

df["price"].plot(kind="hist", bins=30, title="Price distribution")
plt.xlabel("Price")
plt.show()
```

The pandas [Getting started tutorials](https://pandas.pydata.org/docs/getting_started/index.html) go further, one question at a time: reading and writing tables, selecting data, plotting, new columns, summary statistics, reshaping, combining tables, time series and text.

## 8. Step 5: Machine Learning Basics
Machine learning means letting a program find patterns in examples instead of writing every rule by hand. The two main kinds to start with:

* **Supervised learning:** you have examples with the right answer, such as house details with their sale price. **Regression** predicts a number; **classification** predicts a category, such as spam or not spam.
* **Unsupervised learning:** no answers, just finding structure, such as grouping similar customers (**clustering**).

The key habit: **always test a model on data it hasn't seen.** A model that scores well on its own training data may just have memorized it (this is called **overfitting**).

This example uses scikit-learn's built-in iris flower dataset, so there's nothing to download:

```python
from sklearn.datasets import load_iris
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LogisticRegression
from sklearn.metrics import accuracy_score

X, y = load_iris(return_X_y=True)

# Keep 25% of the rows aside to test on
X_train, X_test, y_train, y_test = train_test_split(X, y, random_state=0)

model = LogisticRegression(max_iter=1000)
model.fit(X_train, y_train)              # learn from the training rows

predictions = model.predict(X_test)      # predict the unseen rows
print(accuracy_score(y_test, predictions))
```

Every scikit-learn model works the same way: create it, call `fit()` on training data, then `predict()`. Its [Getting Started page](https://scikit-learn.org/stable/getting_started.html) adds pipelines, cross-validation and parameter search.

**Free ways to go further:**
* **[Kaggle Learn](https://www.kaggle.com/learn): Intro to Machine Learning, then Intermediate Machine Learning** (free, with certificates).
* **[Google's Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course)**. Self-contained modules: linear and logistic regression, classification, working with data, overfitting, neural networks, embeddings, large language models, production systems and fairness.
* **[CS50's Introduction to Artificial Intelligence with Python](https://cs50.harvard.edu/ai/)** (CS50 AI, Harvard, free). Seven weeks: search, knowledge, uncertainty, optimization, learning, neural networks and language. It expects CS50x or about a year of Python first.

## 9. The edX Courses
These edX courses fit the path above. You can also [search all edX data science courses](https://www.edx.org/search?q=data+science&tab=course).

| Course | Provider | Length | Free to audit? | Certificate (Nov 2026) | Notes |
|---|---|---|---|---|---|
| **[Introduction to Data Science](https://www.edx.org/learn/data-science/ibm-introduction-to-data-science)** | IBM | 6 weeks, self-paced | Yes | $99 | An overview of the field from working data scientists. Also offers an IBM skill badge. |
| **[Programming for Data Science](https://www.edx.org/learn/data-science/university-of-adelaide-programming-for-data-science)** | University of Adelaide (AdelaideX) | About 10 weeks at 8 to 10 hours a week, self-paced | Yes | $199 | Teaches programming and simple data visualization using **Processing**, not Python. |
| **[Python Data Science Professional Certificate](https://www.edx.org/professional-certificate/ibm-python-data-science)** | IBM | 6 courses, about 6 months | Yes, course by course | $574 for the program, or $516.60 when bought together | Python basics, a Python project, analyzing and visualizing data, machine learning, and a capstone. Uses pandas, NumPy, matplotlib, seaborn and scikit-learn. |
| **[SQL for Data Science](https://www.edx.org/learn/data-science/ibm-sql-for-data-science)** | IBM | 4 weeks, self-paced | Yes | $99 | SQL for getting data out of databases. Also offers an IBM skill badge. |

**What auditing gets you.** On edX, choosing **Audit course** is free. According to edX's help pages, audit access ends after the course's expected length, graded assignments are for paid learners only, and you don't get a certificate. You can still upgrade later. If you need more time or the certificate, pay; if you just want to learn, audit.

**Want college credit?** edX lists [MicroBachelors programs](https://www.edx.org/bachelors/microbachelors), which give transferable college credit for around $166 per credit, according to edX. In November 2026, they included the London School of Economics' **Statistics Fundamentals** and **Mathematics and Statistics Fundamentals**. Whether a college accepts the credit is up to that college, so check before you pay.

**Another option:** HarvardX's **[Learning Python for Data Science Professional Certificate](https://www.edx.org/professional-certificate/harvardx-learning-python-for-data-science)** bundles CS50P, *Data Analysis: Basic Probability and Statistics*, and *Introduction to Data Science with Python* ($747, or $672.30 bought together, in November 2026). CS50P itself is also free on Harvard's own site (Section 4).

## 10. More Free Courses and References
**Interactive courses**
* **[Kaggle Learn](https://www.kaggle.com/learn)** (free, with certificates). Short courses that take hours, not weeks: Intro to Programming, Python, Pandas, Data Visualization, Data Cleaning, Intro to SQL, Advanced SQL, Intro to Machine Learning, Intermediate Machine Learning, Feature Engineering, Time Series, Intro to Deep Learning, Computer Vision, Machine Learning Explainability, Intro to AI Ethics, Geospatial Analysis and more. Start with Python, Pandas and Data Visualization.
* **freeCodeCamp's [Data Analysis with Python](https://www.freecodecamp.org/learn/data-analysis-with-python/)** (free). Jupyter, NumPy, pandas, data cleaning, reading data from CSV files and databases, and five projects: a mean, variance and standard deviation calculator, a demographic data analyzer, a medical data visualizer, a page view time series visualizer, and a sea level predictor. **Note:** freeCodeCamp has moved this course to its [archive](https://www.freecodecamp.org/learn/archive). It's still available, but no longer updated. Its current [Python](https://www.freecodecamp.org/learn/python-v9/) and [Relational Databases](https://www.freecodecamp.org/learn/relational-databases-v9/) certifications are the maintained options.
* **Harvard's CS50 courses** (free on cs50.harvard.edu): [CS50P](https://cs50.harvard.edu/python/) for Python, [CS50 SQL](https://cs50.harvard.edu/sql/) for databases, and [CS50 AI](https://cs50.harvard.edu/ai/) for artificial intelligence with Python.
* **[Google's Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course)** (Section 8).

**Books and references**
* **[Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/)** by Jake VanderPlas. The full text is free to read online, covering IPython and Jupyter, NumPy, pandas, matplotlib and scikit-learn.
* **[OpenIntro Statistics](https://www.openintro.org/book/os/)** (Section 6).
* **Official docs:** [NumPy: Learn](https://numpy.org/learn/), [pandas: Getting started](https://pandas.pydata.org/docs/getting_started/index.html), [matplotlib tutorials](https://matplotlib.org/stable/tutorials/index.html), [scikit-learn: Getting Started](https://scikit-learn.org/stable/getting_started.html), and [Jupyter: Install](https://jupyter.org/install).

## 11. Practice: Where to Find Datasets
* **[Kaggle Datasets](https://www.kaggle.com/datasets):** thousands of community-shared datasets, many with example notebooks. Check each one's license and where its data came from.
* **[Data.gov](https://data.gov/):** the US government's open data site, run by the General Services Administration. It lists over 500,000 datasets (as of 2026), searchable in its [catalog](https://catalog.data.gov/). Many countries and cities have their own open data portals too.
* **[UCI Machine Learning Repository](https://archive.ics.uci.edu/):** classic datasets used in teaching and research.
* **scikit-learn's built-in datasets,** such as the iris example in Section 8, for quick experiments with nothing to download.
* **Your own data:** your step counts, game stats, or a spreadsheet of your spending. Data you care about makes the project more fun, but keep anything personal out of public repositories.

## 12. Projects to Build
Pick projects that answer a real question. Write up what you found in plain words, not just the code.

**Beginner**
1. **Explore a dataset:** load it, clean it, describe it, and make three charts that each answer one question.
2. **Personal spending tracker:** read a CSV of expenses and chart spending by month and category.
3. **SQL practice report:** load a CSV into SQLite and answer five questions with SQL queries.

**Intermediate**
4. **Compare two groups:** for example, weekday versus weekend sales, with a chart and an honest note on whether the difference could be chance.
5. **Time series:** plot a trend over time, such as daily temperatures or website visits, and spot seasonality.
6. **Simple prediction:** predict a number (such as house prices) with linear regression, and report how wrong it is on test data.
7. **Classification:** predict a category (such as whether a passenger survived, from Kaggle's beginner competition) and explain which features mattered.

**Bigger**
8. **End-to-end project:** collect data from a public API, store it in a database, analyze it in a notebook, and publish a short report.
9. **A small dashboard or web app** that shows your analysis. The [web development guides](https://github.com/ImmuneMoon/Learn-Web-Development-Start-Here) can help you build one.
10. **A Kaggle competition:** enter a beginner competition and compare your approach with the public notebooks afterwards.

**Show your work:** put each project in its own GitHub repository with a README that states the question, the data source and license, what you did, and what you found. GitHub displays Jupyter notebooks (`.ipynb` files) right in the browser. [Publishing to GitHub with gh](https://github.com/ImmuneMoon/Publishing-to-GitHub-with-gh) covers creating the repository, and [Web Developer Careers, Portfolio and Freelancing](https://github.com/ImmuneMoon/Web-Developer-Careers-Portfolio-and-Freelancing) covers portfolios and job hunting, much of which applies to data roles too.

## 13. Common Mistakes
* **Jumping straight to machine learning.** Most real work is SQL, cleaning and clear charts. Get those solid first.
* **Testing a model on its training data.** Always keep a test set aside (Section 8).
* **Skipping the cleaning step.** Look at `df.info()` and `df.isna().sum()` before you trust any number.
* **Confusing correlation with causation.** Two things rising together doesn't mean one causes the other.
* **Collecting courses instead of finishing projects.** One finished, well-explained project beats five half-watched courses.
* **Installing everything globally.** Use one virtual environment per project, and keep a `requirements.txt`, so your work still runs next year. See [Safer Package Installs](https://github.com/ImmuneMoon/Safer-Package-Installs-npm-and-pip) for pinning versions.
* **Publishing private or unlicensed data.** Check the license, and never publish personal data about real people.

## 14. Sources
**Courses**
* edX: [IBM Introduction to Data Science](https://www.edx.org/learn/data-science/ibm-introduction-to-data-science), [AdelaideX Programming for Data Science](https://www.edx.org/learn/data-science/university-of-adelaide-programming-for-data-science), [IBM Python Data Science Professional Certificate](https://www.edx.org/professional-certificate/ibm-python-data-science), [IBM Python Basics for Data Science](https://www.edx.org/learn/python/ibm-python-basics-for-data-science), [IBM SQL for Data Science](https://www.edx.org/learn/data-science/ibm-sql-for-data-science), [HarvardX Learning Python for Data Science](https://www.edx.org/professional-certificate/harvardx-learning-python-for-data-science), [MicroBachelors programs](https://www.edx.org/bachelors/microbachelors), and [edX data science search](https://www.edx.org/search?q=data+science&tab=course)
* edX Help Center: [What is the audit track?](https://support.edx.org/hc/en-us/articles/1500003964681-What-is-the-audit-track) and [Differences between audit and verified courses](https://support.edx.org/hc/en-us/articles/360013426573-What-are-the-differences-between-audit-free-and-verified-paid-courses)
* Harvard CS50: [CS50P](https://cs50.harvard.edu/python/), [CS50P certificate](https://cs50.harvard.edu/python/certificate/), [CS50 SQL](https://cs50.harvard.edu/sql/) and [CS50 AI](https://cs50.harvard.edu/ai/)
* [Kaggle Learn](https://www.kaggle.com/learn)
* freeCodeCamp: [Data Analysis with Python](https://www.freecodecamp.org/learn/data-analysis-with-python/), [archive](https://www.freecodecamp.org/learn/archive), [Python Certification](https://www.freecodecamp.org/learn/python-v9/) and [Relational Databases Certification](https://www.freecodecamp.org/learn/relational-databases-v9/)
* [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course)
* [Khan Academy: Statistics and probability](https://www.khanacademy.org/math/statistics-probability)
* [SQLBolt](https://sqlbolt.com/)

**Tools and documentation**
* [Jupyter: Install](https://jupyter.org/install) and [Try Jupyter](https://jupyter.org/try)
* [Google Colab](https://colab.research.google.com/)
* [NumPy: Learn](https://numpy.org/learn/)
* [pandas: Getting started](https://pandas.pydata.org/docs/getting_started/index.html)
* [matplotlib tutorials](https://matplotlib.org/stable/tutorials/index.html)
* [scikit-learn: Getting Started](https://scikit-learn.org/stable/getting_started.html)

**Books and videos**
* Jake VanderPlas, [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/)
* OpenIntro, [OpenIntro Statistics](https://www.openintro.org/book/os/)
* [StatQuest with Josh Starmer](https://www.youtube.com/@statquest)
* 3Blue1Brown, [Essence of linear algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) and [Essence of calculus](https://www.youtube.com/playlist?list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr)

**Datasets**
* [Kaggle Datasets](https://www.kaggle.com/datasets)
* [Data.gov](https://data.gov/) and its [catalog](https://catalog.data.gov/)
* [UCI Machine Learning Repository](https://archive.ics.uci.edu/)

**Careers and roadmaps**
* US Bureau of Labor Statistics, [Occupational Outlook Handbook: Data Scientists](https://www.bls.gov/ooh/math/data-scientists.htm)
* roadmap.sh: [Data Analyst](https://roadmap.sh/data-analyst), [AI and Data Scientist](https://roadmap.sh/ai-data-scientist), [Machine Learning](https://roadmap.sh/machine-learning), [Python](https://roadmap.sh/python) and [SQL](https://roadmap.sh/sql)

<!-- guide:end -->

## ☕ Support the Project

If you find this project helpful and want to support further development by Fulllion Creative Works, consider leaving a tip!

* [Donate via PayPal](https://www.paypal.com/donate/?hosted_button_id=LCDZX75HR4CLC)
* [Support on Ko-fi](https://ko-fi.com/fulllion)

---
© 2026 Fulllion Creative Works. All rights reserved.
