**Title: Family Income \& Expenditure Analysis (Philippines)**



Author: Kristine Sinamban 

GitHub: \[ktfsinamban](https://github.com/ktfsinamban)  

Date: 2025-08-23

Last Updated: 2025-11-04

---

**Project Overview**

This repository contains a data analysis project exploring the ***'Filipino Family Income and Expenditure'*** dataset published by **Francis Paul Flores** (sourced from Kaggle). The goal is to extract meaningful insights, visualize trends, and derive actionable conclusions about how income and expenditure patterns vary across different socio‑economic groups.


**Key objectives:**

This set aims to explore and interpret patterns in household income, expenditures, and demographics. Use graphs and DataFrame operations to answer questions and uncover insights by answering the following questions: 

* Urban vs Rural Differences
How do household incomes and expenditures differ between urban and rural households? Compare NCR and Region VIII

* Impact of Education on Income
Do household heads with higher education levels earn more?

* Household Size and Spending
Do larger families spend more on food or education?

* Gender Differences in Household Economics
Is there a difference in income or spending patterns based on the sex of the household head?

* Regional Spending Patterns
Which regions spend the most on education, transportation, and food?

* Personal Exploration
Which region has the highest Average Monthly Income per Family and Region?
Examine the relationship of the number of family members and income, savings, expenditures
What is the most used water supply in the Philippines?


**Streamlit App:**
* the Steamlit app (app.py) included is an exploration of filtering using Streamlit. This does not explore all the questions asked above. 


**Dataset source**: \*Filipino Family Income and Expenditure\* (Kaggle): https://www.kaggle.com/datasets/grosvenpaul/family-income-and-expenditure



---



**Why This Matters**

* Real‑world relevance: Household income \& spending are central to economics, public policy, and social programs.
* Transferable skills: The methods used (data cleaning, filtering, visualization, reporting) are directly applicable to business reporting, insights roles, and data science.
* Storytelling with data: Beyond numbers, this project shows how to communicate findings in a clear, effective way — crucial when working with non‑technical stakeholders.



---



**Repository Structure**

├── data/

│ ├── raw/ # original CSVs/ZIP or unmodified dataset
├── notebooks/
│ ├── filename.ipynb
├── reports/
│ ├── final\_reports\_Data analysis on Family Income & Expenditure Analysis │(Philippines).pdf
│ └── final\_reports\_app.py
├── App images/
│ └── Sample of Application Image.pdf
└── README.md



---



**Tools \& Technologies Used**

* Python — core programming language  
* pandas, numpy — data manipulation \& aggregation  
* matplotlib, seaborn — for visualizations  
* Google Colab Notebooks — for exploration and prototyping  
* Version control via Git / GitHub



---



**Highlights \& Sample Findings**

* Expenditure on essential items (food, housing, utilities) constitutes a large share of budgets, particularly in lower income brackets  
* Some households have negative savings (i.e. expenditure exceeds income), highlighting financial stress  
* Regional differences: urban households tend to earn and spend more than rural ones  



---



**How to Reproduce / Run Locally** 
You will need to set up a test environment using Anaconda and VSC (with Python): https://www.anaconda.com/download
https://code.visualstudio.com/

1\. **Import libraries**

&nbsp;	import pandas as pd

&nbsp;	import seaborn as sns

&nbsp;	import matplotlib.pyplot as plt

&nbsp;	import zipfile

&nbsp;	import streamlit as st

&nbsp;	import time

&nbsp;	import os

2\. **Download the dataset**

&nbsp;	Obtain the CSV(s) from Kaggle (dataset: Filipino Family Income and Expenditure) Kaggle or from this file under data/raw/

3\. **Import the data**

&nbsp;	zip\_file\_path = r"/content/drive/MyDrive/Data sets/family expenditure.zip"

&nbsp;	file\_folder\_path = r"/content/drive/MyDrive/Data sets/family expenditure"

&nbsp;	with zipfile.ZipFile(zip\_file\_path) as zip\_ref:

&nbsp; 	zip\_ref.extractall(file\_folder\_path)

&nbsp;	file\_path = r"/content/drive/MyDrive/Data sets/family expenditure/Family Income and Expenditure.csv"

&nbsp;	df = pd.read\_csv(file\_path)

&nbsp;	pd.set\_option('display.max\_columns', None)

4\. **View the output / visuals**

&nbsp;	Generated plots \& results will be in the notebooks / script output

&nbsp;	The final report (pdf or streamlit app) synthesizes insights

&nbsp;	(Optional) Open the app.py with the test environment from Anaconda, run python -m streamlit run app.py in the command prompt terminal

---



**Why You Should Hire Me**

* I can transform messy real‑world data into insightful, polished deliverables
* I have experience in statistical reasoning, visual storytelling, and communication to non‑technical audiences
* I care about impact — not just numbers, but how insights drive decisions
* I am a designer and a developer all in one! I build products that have reached over 200M users. 



---



**Let’s Talk :D**


I’d love to discuss this project further or walk you through my code, thought process, and insights.


Feel free to reach out:

Email: ktf.sinamban@gmail.com

Website: https://kristinesinamban.com/

LinkedIn: \[Kristine Sinamban] (https://www.linkedin.com/in/kristine-sinamban/)

GitHub: \[ktfsinamban] (https://github.com/ktfsinamban)


**License & Credits**

This repository is released under the MIT License.
Dataset credit: Filipino Family Income and Expenditure by Francis Paul Flores
