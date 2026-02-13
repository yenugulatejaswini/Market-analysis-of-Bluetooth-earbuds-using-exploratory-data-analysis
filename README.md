#  Earbuds Data Analysis Project (EDA + Web Scraping)

##  Project Overview

This project performs **web scraping, data cleaning, and exploratory data analysis (EDA)** on earbuds product listings collected from an e-commerce platform.
The goal is to analyze product features, pricing, ratings, and reviews to discover meaningful patterns and insights.

---

##  Objectives

* Scrape earbuds product data automatically
* Clean and preprocess raw scraped data
* Perform exploratory data analysis (EDA)
* Identify trends in pricing, ratings, and features
* Visualize patterns to support insights

---

##  Problem Statement

Online shopping platforms contain hundreds of earbuds with different prices, ratings, and features. Customers often find it difficult to compare products efficiently.

**Goal:**
Transform raw product data into structured insights that help understand:

* Which earbuds offer the best value
* What features are most common
* How ratings relate to price and specifications

---

## Dataset Files

| File                            | Description                         |
| ------------------------------- | ----------------------------------- |
| `earbuds.csv`                   | Raw scraped dataset                 |
| `flipkart_earbuds_1000plus.csv` | Extended dataset with 1000+ entries |
| `cleaned.csv`                   | Cleaned and processed dataset       |

---

##  Notebooks

| Notebook              | Purpose                                  |
| --------------------- | ---------------------------------------- |
| `webscraping.ipynb`   | Scrapes earbuds data from website        |
| `Data_cleaning.ipynb` | Handles missing values and preprocessing |
| `EDA.ipynb`           | Exploratory data analysis                |
| `data_analysis.ipynb` | Insights and visualizations              |

---

##  Tools & Libraries Used

* Python
* Selenium
* BeautifulSoup
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

##  Project Workflow

1. **Web Scraping**

   * Extracted earbuds product data automatically
   * Collected price, rating, brand, and features

2. **Data Cleaning**

   * Removed duplicates
   * Handled null values
   * Standardized columns

3. **Exploratory Data Analysis**

   * Price distribution analysis
   * Rating comparison
   * Feature frequency analysis

4. **Visualization**

   * Charts for trends and comparisons
   * Distribution plots
   * Correlation insights

---

##  Key Insights (Example Findings)

* Identified most common price ranges
* Observed rating trends across brands
* Detected relationship between price and rating
* Found frequently available features

---

##  How to Run the Project

### 1️ Install Requirements

```bash
pip install pandas numpy matplotlib seaborn selenium beautifulsoup4
```

### 2️ Run Notebooks

Open Jupyter Notebook and run in order:

```
webscraping.ipynb
Data_cleaning.ipynb
EDA.ipynb
data_analysis.ipynb
```

---

## Project Structure

```
earbuds/
│
├── earbuds.csv
├── flipkart_earbuds_1000plus.csv
├── cleaned.csv
│
├── webscraping.ipynb
├── Data_cleaning.ipynb
├── EDA.ipynb
└── data_analysis.ipynb
```

---

 Future Improvements

* Build interactive dashboard
* Add sentiment analysis on reviews
* Implement recommendation system
* Deploy as web application

---

 Author

**Tejaswini**

---

⭐ If you like this project, consider starring the repository!
