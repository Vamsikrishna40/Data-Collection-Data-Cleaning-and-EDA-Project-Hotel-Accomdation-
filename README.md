# EazyDiner Hotel Accommodation Data Collection, Cleaning, and EDA Project

---
Website Link : https://www.eazydiner.com/
````{"title":"EazyDiner Data Analysis Project - README"}
# 🏨 EazyDiner Hotel Accommodation Data Analysis  

## 📘 Project Overview  
This project is an **End-to-End Data Science Project** focused on **Hotel Accommodation Data** scraped from the [EazyDiner](https://www.eazydiner.com/) website. The objective is to demonstrate the complete lifecycle of a data science project — from **web scraping**, **data cleaning**, and **EDA (Exploratory Data Analysis)** to **visualization** and **insights** using Python and Power BI.

---

## 🧭 Problem Statement  
EazyDiner is an online restaurant booking and discovery platform. The goal of this project is to:
- Extract hotel and restaurant-related data (names, locations, cuisines, ratings, cost, etc.) from EazyDiner.  
- Clean, preprocess, and analyze the data to uncover insights about restaurant distribution, average costs, customer preferences, and city-based patterns.  
- Visualize the data using **Power BI** for interactive dashboards and storytelling.

---

## 🧰 Tools & Technologies Used  
| Category | Tools / Libraries |
|-----------|------------------|
| Programming | Python 3.x |
| Web Scraping | `requests`, `BeautifulSoup`, `Selenium` |
| Data Cleaning | `pandas`, `numpy`, `re` |
| Data Visualization | `matplotlib`, `seaborn`, `Power BI` |
| Development Environment | Jupyter Notebook / VS Code |
| Data Storage | CSV, Excel (.xls) |

---

## 📂 Project Structure  
```
📁 EazyDiner_Hotel_Accommodation_Project/
│
├── 📄 Hotel Accomdation.ipynb        # Web scraping, cleaning, and EDA notebook
├── 📄 Hotel Accomdation.html         # Exported HTML report from Jupyter
├── 📄 eazydiner_hyderabad.xls        # Sample scraped data (Hyderabad restaurants)
├── 📄 eazydiner_all_cities_full.xls  # Final combined dataset across 31 cities
├── 📄 Data Collection, Data Cleaning and EDA Project.pdf  # Official documentation
├── 📄 README.md                      # Project summary file (this file)
└── 📊 PowerBI_Dashboard.pbix         # Power BI dashboard (optional/add if available)
```

---

## 🧑‍💻 Steps Followed

### 1. **Data Collection**
- Source: [EazyDiner.com](https://www.eazydiner.com/)
- Tool: **Selenium** used to automate the extraction of restaurant details from multiple cities.  
- Data points extracted:
  - Restaurant Name  
  - Location  
  - Cuisine Type  
  - Average Cost for Two  
  - Rating  
  - Timings  
  - Offers/Discounts  
  - City Name  

### 2. **Data Cleaning**
Performed in **Pandas**:
- Removed unwanted characters, special symbols, and empty spaces.  
- Standardized column names (lowercase, underscores).  
- Treated missing and inconsistent data.  
- Converted datatypes (e.g., numeric ratings, cost).  
- Removed duplicates and irrelevant entries.

### 3. **Exploratory Data Analysis (EDA)**
Performed using **Matplotlib** and **Seaborn**:
- **Univariate Analysis**: Distribution of ratings, cost, cuisine frequency.  
- **Bivariate Analysis**: Relationship between ratings and cost, city vs average rating.  
- **Multivariate Analysis**: Correlation between numerical variables.  
- Used plots: histogram, box plot, bar plot, count plot, pie chart, and heatmap.

---

## 📈 Key Insights  
- **Hyderabad**, **Delhi NCR**, and **Mumbai** have the highest number of listed restaurants.  
- **North Indian** and **Chinese** cuisines dominate most cities.  
- The **average cost for two** varies significantly by city, with metro cities being more expensive.  
- There is a **positive correlation** between cost and rating — premium restaurants tend to have higher ratings.  

---

## 📊 Dataset Summary  
| Metric | Value |
|--------|-------|
| Total Records | 184 restaurants |
| Total Cities | 31 |
| Key Features | 8+ (Restaurant Name, City, Cuisine, Rating, Cost, etc.) |
| Data Type | Structured (.xls, .csv) |

---

## 🧩 Challenges Faced  
- Handling dynamic content using Selenium (EazyDiner loads results asynchronously).  
- Standardizing inconsistent data across multiple cities.  
- Cleaning multi-value fields like cuisines and offers.  
- Power BI integration with Excel datasets.

---

## 💡 Future Enhancements  
- Automate data refresh using APIs or scheduled scrapers.  
- Incorporate sentiment analysis on restaurant reviews.  
- Build predictive models (e.g., predict restaurant ratings or price ranges).  
- Host Power BI dashboard publicly or embed in a web app.

---

## 👤 Author  
**Vamsi Krishna**  
📧 Email: [rvamsikrishna42@gmail.com]   

---

## 🏁 Conclusion  
This project demonstrates a **complete Data Science pipeline** — from scraping raw web data to delivering structured insights and visual analytics. It showcases practical proficiency in **Python, Data Cleaning, EDA, and Power BI**, making it a valuable addition to any **Data Analyst / Data Science** portfolio.
````

