# Netflix Dataset Analysis

## Author
**Shreyash Sule**  
[Email: shreyashsule22@gmail.com](mailto:shreyashsule22@gmail.com)

---

## Overview
This project analyzes the Netflix dataset, which contains information about TV Shows and Movies available on Netflix up until 2021. The dataset was sourced from Flixable, a third-party Netflix search engine, and is freely available on Kaggle.

---

## Dataset Features
The dataset includes the following columns:
- **Show ID**: Unique ID for each show.
- **Title**: Name of the show/movie.
- **Category**: TV Show or Movie.
- **Director**: Director of the show/movie.
- **Cast**: Cast members.
- **Country**: Country of origin.
- **Release Date**: Date of release on Netflix.
- **Rating**: Netflix rating (e.g., TV-14, R).
- **Duration**: Duration of the show/movie.
- **Type**: Genre or type (e.g., Comedies, Dramas).
- **Description**: Brief description of the show/movie.

---

## Objectives
1. Perform exploratory data analysis (EDA).
2. Clean and preprocess the dataset.
3. Answer specific queries about Netflix's content.
4. Visualize insights and trends.

---

## Installation and Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/shreyashsule/netflix-dataset-analysis.git
   ```
2. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Run the Jupyter Notebook or Python script provided to perform the analysis.

---

## Analysis Tasks

### **1. Data Import and Inspection**
- Loaded the dataset using `pandas`.
- Inspected the dataset using methods like `.head()`, `.tail()`, `.info()`, `.shape`, and `.dtypes`.

### **2. Data Cleaning**
- Removed duplicate records using `.duplicated()`.
- Handled missing values using `.isnull()` and visualized them with a heatmap (`seaborn`).

### **3. Exploratory Data Analysis (EDA)**
- **Q1**: Find "House of Cards" details (Show ID and Director).
- **Q2**: Determine the year with the highest number of releases.
- **Q3**: Count Movies and TV Shows in the dataset.
- **Q4**: List all Movies released in the year 2000.
- **Q5**: Display titles of TV Shows released in India.
- **Q6**: Identify the top 10 directors by content contribution.
- **Q7**: Filter data for Movies categorized as "Comedies" or content from the UK.
- **Q8**: Count Movies/Shows featuring "Tom Cruise".
- **Q9**: Explore Netflix ratings distribution and filter for specific ratings.
- **Q10**: Find the maximum duration of Movies/Shows.
- **Q11**: Identify the country with the highest number of TV Shows.
- **Q12**: Sort the dataset by Year.
- **Q13**: Filter data for Movies in "Dramas" or TV Shows in "Kids' TV".

---

## Visualizations
1. **Heatmap**: Visualized missing values using `sns.heatmap()`.
2. **Bar Graphs**:
   - Year-wise content release trends.
   - Distribution of Movies vs. TV Shows.
3. **Count Plot**: Top categories and ratings.

---

## Results
This analysis provides insights into Netflix's content, including:
- Trends in release years.
- Popular categories and genres.
- Top contributors (directors, actors).
- Insights into ratings, durations, and country-wise distributions.

---

## Dataset Source
The dataset is freely available on [Kaggle](https://www.kaggle.com) under the name "Netflix Dataset."

