# PYTHON DATA ANALYSIS REPO

👇 Collection of small-scale Python data analytics projects

## PROJECT 1: Global CO2 emissions analysis | [view code](https://github.com/NickTimosh/python_DA_projects/blob/main/co2_analysis.ipynb) 

🏭 The project where I combined my energy and environmental engineering experience with coding skills and data analysis techniques

<details>
<summary>The Project</summary>

---

One of the negative impacts on the environment from human activities is greenhouse gas (GHG) emissions, which lead to global warming with catastrophic consequences. 
The performed analysis allows to dive deeper into the problem and intend to assess the impact of different countries and sectors of economy in global GHG emissions. 
The analysis also aims to compare these data with the population of countries and GDP in order to identify existing patterns. 
This can be useful for benchmarking, forecasting, developing national and sectoral energy managenent plans and issuing other strategical documents and legislative framework related to environmental policy.

![225337781-e5153e21-0492-43a1-8ef1-8ad58dba272b](https://github.com/NickTimosh/python_DA_projects/assets/116592259/088170d3-c545-445f-8d03-e6bbd5266a1c)

---
</details>

<details>
<summary>Analysis Steps</summary>

---

The analysis performed within the following steps:

* importing data from a csv file to Google Colabratory
* importing pandas, numpy and matplotlib for further data processing and visualization
* data sorting and filtering
* unpivoting tables
* global historical emissions trend analysis using cumulative line chart
* share of different sectors (Energy, Industrial Processes etc.) within 30-year evolution of the emissions with a stacked column chart
* analysis of GHG emissions in sectors reported in 2018 compare to 1990 with the bar chart
* country-level analysis, considering GDP, population and corresponding emissions using scatter chart

---
</details>

<details>
<summary>Key Insights</summary>

---

* The Database provides emission time series from 1990 until 2018 for 194 countries, covering a total population of 7.5 billion inhabitants
* In 2018, reported emissions totaled 47.5 thouthand MtCO2e (excluding the effects of land use and forestry), which represents a 55 percent increase since 1990
* In 2018, Energy sector (including fuels used by transport and buildings) represent the largest source of greenhouse gas emissions worldwide (78.3 %), followed by agriculture (12.2 %), Industrial Processes (6.1%) and Waste (3.4 %)
* To be more specific, the five most emitting sub-sectors are responsible for 33 % (Electricity / Heat), 17 % (Transportation) and 13 % (Manufacturing/Construction) and 12 % (Agriculture) of the total CO2-eq emissions
* Higher GHG emissions recorded for countries with higher GDP per capita, as expected.

---
</details>

## Project 2: LastFM Dataset Analysis | [view code](https://github.com/NickTimosh/python_DA_projects/blob/main/pyspark_lastfm.ipynb)
📻 In this project, I`ve worked with the PySpark module in Python, utilizing the Google Colab environment to apply queries to a dataset related to the Last.fm website. Last.fm is an online music service where users can listen to different songs.

The dataset consists of two CSV files, namely "listening.csv" (1GB containing 13,758,905 rows) and "genre.csv" (3 MB containing 138,415 rows).

<details>
<summary>Analysis Steps</summary>

  ---
**1. Data Import with PySpark:** The first step of the analysis involved importing the dataset using PySpark. This included loading the "listening.csv" and "genre.csv" files into PySpark DataFrames.

**2. Data Cleaning:** In this step, data cleaning operations were performed to ensure the data quality. This included removing any null values and eliminating unnecessary columns that were not relevant to the analysis.

**3. Dataset Exploration:** This step focused on filtering, grouping, and aggregating the data to gain insights into popular artists, albums, and the best genres.

**4. User Listening Habits:** For each user in the dataset, this step involved determining their preferred genre and the most frequently played songs. By grouping the data by user and analyzing their listening history, the analysis aimed to understand user preferences and identify the genres and songs that were most popular among the users.

**5. Bar Chart of Genre Preferences:** To visualize the genre preferences of users, this step utilized the Matplotlib library to create a bar chart. By aggregating the data by genre and counting the occurrences, the analysis generated a bar chart that represented the distribution of genre preferences among the users.

These steps provide a high-level overview of the main analysis performed on the LastFM dataset. Each step aimed to gain insights into the dataset, understand user behavior, and visualize the findings using the Matplotlib library.

---
</details>


<details>
<summary>Key Learnings</summary>

---

Through this project, I`ve gained hands-on experience in working with PySpark, performing data analysis, leveraging distributed computing, and visualizing query results using Matplotlib. This project has allowed me to showcase my skills in data analysis, distributed computing with PySpark, and data visualization, while exploring a real-world dataset within the context of Last.fm.

---
</details>

##  Project 3: EDA Supermarket | [view code](https://github.com/NickTimosh/python_DA_projects/blob/main/EDA_supermarket.ipynb)

🏪 Exploratory Data Analysis on a supermarket sales dataset (Pandas, Seaborn)

<details>
<summary>Analysis Steps</summary>

---

1: Initial Data Exploration; 

2: Univariate Analysis; 

3: Bivariate Analysis; 

4: Dealing With Duplicate Rows and Missing Values; 

5: Correlation Analysis.

---
</details>

<details>
<summary>Key Lernings</summary>

---

* EDA techniques application on any tabular dataset using Python.
* data visualizations using Seaborn and Matplotlib
* duplicate and missing data Identification and handling

---
</details>

<details>
<summary>Credentials</summary>

---

This is my submission of project-based course Exploratory Data Analysis With Python and Pandas (Coursera)

Link to data source: https://www.kaggle.com/aungpyaeap/supermarket-salesng

---
</details>


##  Project 4: Data Science Salaries Dashboard | [view code](https://github.com/NickTimosh/python_DA_projects/blob/main/streamlit_salaries_webapp.py) | [web app](https://ds-salaries.streamlit.app/)

💻 A web app built with Python and Streamlit that provides insights into data science salaries. 

The app is deployed on Streamlit Community Cloud and is linked to this GitHub repository for seamless updates.

<details>
<summary>Features</summary>

---

* Categorizes job titles into 7 different categories;
* Displays a bar chart of average salaries based on job categories;
* Allows exploration of salaries for different years, countries, and experience levels through interactive filters.

![Screenshot 2023-07-03 164243](https://github.com/NickTimosh/python_DA_projects/assets/116592259/38f6b3bc-97fa-409a-b810-766ee47c7116)

---
</details>


<details>
<summary>Credentials</summary>

---

To see the datasource, simply visit the [Kaggle Data Science 2023 Dataset](https://www.kaggle.com/datasets/arnabchaki/data-science-salaries-2023)

Contributions to the project are welcome! If you encounter any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.

---
</details>







