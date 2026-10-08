# 🎬 Amazon Prime Video — Exploratory Data Analysis

## 📌 Project Overview

This project performs an **Exploratory Data Analysis (EDA)** of Amazon Prime Video's Movies and TV Shows catalog using **Python**.

The analysis explores the characteristics of the content available on Amazon Prime Video, including content type, release years, genres, ratings, countries, IMDb scores, and other relevant attributes.

The objective is to clean and analyze the raw datasets, identify meaningful patterns, and generate insights through data visualization.

---

## 🎯 Objectives

The main objectives of this project are:

- Understand the structure and characteristics of the Amazon Prime Video dataset.
- Perform data cleaning and preprocessing.
- Identify and handle duplicate records.
- Analyze missing values.
- Explore Movies vs TV Shows distribution.
- Analyze content release trends over the years.
- Explore popular genres and categories.
- Analyze ratings and age certifications.
- Examine IMDb scores and votes.
- Explore the geographical distribution of content.
- Identify meaningful patterns and trends through visualization.

---

## 🗂️ Dataset

The project uses two datasets:

### `titles.csv`

Contains information about Amazon Prime Video titles, including:

- Title
- Description
- Type
- Release Year
- Age Certification
- Runtime
- Genres
- Production Countries
- IMDb Score
- IMDb Votes
- Seasons
- Other title-related attributes

### `credits.csv`

Contains information about people associated with the titles, including:

- Person ID
- Character
- Role
- Name
- Title ID

The two datasets can be related using the **title ID**.

---

## 📊 Dataset Overview

### Titles Dataset

- **Rows:** 9,871
- **Columns:** 15

### Credits Dataset

- **Rows:** 124,235
- **Columns:** 5

The datasets were examined for duplicate records and missing values before performing the analysis.

---

## 🧹 Data Cleaning

The following data-cleaning operations were performed:

- Checked dataset dimensions.
- Inspected column data types.
- Identified duplicate records.
- Checked missing values.
- Investigated columns with significant missing data.
- Prepared the datasets for exploratory analysis.
- Combined relevant information from the datasets where required.

### Missing Values

Some important columns contained missing values, including:

- Description
- Age Certification
- Seasons
- IMDb ID
- Character

Missing values were analyzed based on their relevance to the particular analysis rather than blindly removing all incomplete records.

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

## 🔍 Exploratory Data Analysis

The analysis covers several dimensions of the Amazon Prime Video catalog.

### 1. Movies vs TV Shows

Analyzed the distribution of content types to understand whether Amazon Prime Video's catalog is primarily composed of Movies or TV Shows.

### 2. Release Year Trends

Analyzed the number of titles released across different years to identify trends in the growth of the streaming catalog.

### 3. Genre Analysis

Explored the distribution of genres to identify the most frequently occurring categories.

### 4. Age Certification

Analyzed age certifications to understand the target audience and content classification.

### 5. IMDb Analysis

Explored IMDb scores and votes to understand the ratings and popularity of titles.

### 6. Runtime Analysis

Analyzed the runtime of Movies and TV Shows to understand differences in content duration.

### 7. Country Analysis

Explored production countries to understand the geographical diversity of the Amazon Prime Video catalog.

### 8. Credits Analysis

The credits dataset was analyzed to understand the relationship between titles, actors/characters, and roles.

---

## 📈 Key Insights

The analysis provides several useful observations about Amazon Prime Video's content catalog:

- The catalog contains a significantly larger number of **Movies compared with TV Shows**.
- Content production and availability show noticeable changes across different release years.
- The platform contains a diverse range of **genres and content categories**.
- Titles have varying age certifications, indicating content targeted toward different audiences.
- IMDb scores provide an additional way to evaluate the perceived quality of titles.
- The catalog represents content from multiple production countries.
- The credits dataset provides additional information about the people and roles associated with individual titles.

---

## 🔄 Project Workflow

```text
Raw Dataset
     ↓
Data Loading
     ↓
Data Understanding
     ↓
Data Cleaning
     ↓
Missing Value Analysis
     ↓
Duplicate Analysis
     ↓
Data Transformation
     ↓
Exploratory Data Analysis
     ↓
Data Visualization
     ↓
Insights & Conclusions
```

---

## 📁 Repository Structure

```text
Amazon-EDA/
│
├── EDA Project on Amazon Prime TV Shows and Movies.ipynb
│
├── titles.csv
│
├── credits.csv
│
└── README.md
```

---

## 💻 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/shbhm152-shadow/Amazon-EDA.git
```

### 2. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 4. Open the notebook

Open:

```text
EDA Project on Amazon Prime TV Shows and Movies.ipynb
```

Make sure `titles.csv` and `credits.csv` are available in the same project directory.

---

## 💡 Skills Demonstrated

This project demonstrates practical experience with:

`Python`  
`Pandas`  
`NumPy`  
`Data Cleaning`  
`Exploratory Data Analysis`  
`Missing Value Analysis`  
`Data Visualization`  
`Matplotlib`  
`Seaborn`  
`Jupyter Notebook`  
`Data Interpretation`

---

## 🚀 Future Improvements

Possible extensions to this project include:

- Build an interactive **Power BI dashboard** using the cleaned dataset.
- Perform deeper statistical analysis.
- Analyze relationships between IMDb scores, genres, and release years.
- Perform actor/director-level analysis.
- Build a recommendation system based on content characteristics.
- Apply machine learning techniques to predict content ratings or other relevant outcomes.

---

## 👨‍💻 Author

### Shubham Kimari

**Aspiring Data Analyst**

**Skills:** Python | SQL | Power BI | Excel | Data Analysis | Data Visualization

---

⭐ If you find this project useful, feel free to explore the repository.
