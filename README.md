# Prison Escape Data Analysis Using Python and Libraries

> A data analysis project focused on uncovering patterns, trends, and insights from real-world prison escape incidents, with special emphasis on helicopter-assisted escapes across years and countries.

---

## Table of Contents

- [About](#about)
- [Problem Statement](#problem-statement)
- [Dataset](#dataset)
- [Built With](#built-with)
- [Project Objectives](#project-objectives)
- [Methodology](#methodology)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Analysis Workflow](#analysis-workflow)
- [Results and Insights](#results-and-insights)
- [Future Scope](#future-scope)

---

## About

**Prison Escape/ Helicopter Escape** is a data analysis project built using Python and Jupyter Notebook to explore historical prison escape data.  
The project investigates **how often helicopter-assisted prison escapes occur**, **which countries report the most incidents**, and **how these events are distributed across time**.

The goal of this project is to demonstrate **practical data analysis skills**, including data cleaning, aggregation, exploratory analysis, and insight generation, while working on a unique and real-world dataset.

---

## Problem Statement

Prison escape incidents are rare but high-impact events. Among them, helicopter-assisted escapes stand out due to their complexity and planning.

This project aims to answer questions such as:
- In which years were helicopter prison escape attempts most frequent?
- Which countries have recorded the highest number of such escape attempts?
- Are there visible trends or patterns over time?

---

## Dataset

The dataset used in this project is stored locally as: 1ex.csv (Original Dataset taken from [Link](https://en.wikipedia.org/wiki/List_of_helicopter_prison_escapes). Not able to fetch directly due to HTTP Restriction, so, loaded the table in MS Excel using Get Data, and then used further)


### Dataset Characteristics

- Real-world historical data
- Contains records of prison escape attempts
- Includes attributes such as:
  - Date / Year
  - Country
  - Escape method
  - Additional contextual information

The dataset is used strictly for analytical and educational purposes.

---

## Built With

This project is built using the following tools and libraries:

- **Python 3** — Core programming language
- **Jupyter Notebook** — Interactive data exploration
- **Pandas** — Data manipulation and analysis
- **Matplotlib / Seaborn** — Data visualization (where applicable)
- **CSV files** — Source data storage

---

## Project Objectives

The primary objectives of this project are:

1. Load and explore structured CSV data
2. Clean and preprocess raw data for analysis
3. Perform exploratory data analysis (EDA)
4. Aggregate data by year and country
5. Identify trends in helicopter prison escapes
6. Present insights in a clear and understandable format

---

## Methodology

The project follows a standard data analysis lifecycle:

1. **Data Loading**
   - Import CSV data using Pandas
2. **Data Cleaning**
   - Handle missing or inconsistent values
   - Normalize column formats
3. **Exploratory Analysis**
   - Inspect distributions and counts
4. **Aggregation**
   - Group data by year and country
5. **Insight Generation**
   - Identify peaks, patterns, and anomalies
6. **Visualization**
   - Represent findings graphically (if applicable)

---

## Project Structure
```bash
PrisonEscapeDA/
│
├── 1ex.csv
├── execution.ipynb
├── helper.py
├── README.md
├── pycache/
├── .ipynb_checkpoints/
└── anaconda_projects/
```

### File Descriptions

- `1ex.csv`  
  Contains the raw dataset used for analysis.

- `execution.ipynb`  
  Main Jupyter Notebook where all analysis is performed.

- `helper.py`  
  Utility/helper functions used for data cleaning or transformations.

- `README.md`  
  Project documentation.

---

## Getting Started

Follow these instructions to run the project locally.

### Prerequisites

Make sure you have the following installed:

- Python 3.7 or higher
- Jupyter Notebook
- Required Python libraries:
  - pandas
  - matplotlib
  - seaborn (if used)

You can install required libraries using:

### Installation
Clone the repository:

```bash 
git clone https://github.com/AyuOrniThrONE/PrisonEscapeDA.git
```
Navigate to the project directory:
```bash
cd PrisonEscapeDA
```

Launch Jupyter Notebook:
```bash
jupyter notebook
```
Open execution.ipynb

### Usage
Once the notebook is open:

- Run the cells sequentially from top to bottom
- Observe data cleaning and transformation steps
- Review generated outputs and visualizations
- Modify or extend the analysis as needed

### Analysis Workflow
The analysis is performed in the following order:
- Dataset inspection and column understanding
- Removal or correction of invalid entries
- Feature extraction (year, country, escape type)
- Grouping and counting escape events
- Identifying peak years and locations
- Summarizing insights

### Results and Insights
Key insights derived from the analysis include:
- Identification of years with the highest number of helicopter escape attempts
- Countries where such escape methods were most frequently recorded
- Overall distribution trends across time
(Exact numerical results can be viewed by running the notebook.)


### Future Scope
- Possible extensions of this project include:
- Adding predictive modeling for trend forecasting
- Integrating interactive dashboards (Plotly / Dash)
- Expanding dataset with more attributes
- Performing comparative analysis with other escape methods
