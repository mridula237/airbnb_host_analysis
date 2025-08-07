# Airbnb Superhost Strategy Insights – Albany, NY

This project explores what sets Superhosts apart from regular Airbnb hosts in Albany, NY using real listing data. Through interactive visualizations and engineered metrics, we uncover how Superhosts differ in terms of pricing, reviews, and ratings.

---

##  Dataset
- **Source**: [Inside Airbnb](http://insideairbnb.com/get-the-data.html)
- **City**: Albany, New York
- **Snapshot**: January 2025
- **Filename**: `listings2.csv` (found in `/data` folder)

---

##  Objectives
- Compare Superhosts and non-Superhosts
- Understand pricing trends and review behavior
- Visualize key differences using interactive charts

---

##  Visualizations

1. 💬 Number of Reviews by Superhost Status  
2. ⭐ Review Score by Superhost Status  
3. ⚖️ Price per Review (Efficiency)  
4. 💰 Price Distribution by Superhost Status

All charts are built using Plotly and are fully interactive._

---

##  Key Insights

| Metric               | Superhost Advantage |
|----------------------|---------------------|
| Price                | Slightly higher but more consistent pricing |
| Review Score         | Consistently higher ratings with fewer low-score outliers |
| Number of Reviews    | More reviews, indicating better visibility or trust |
| Price per Review     | More value delivered per dollar on average |

---

##  Tools Used
- Python 3.9
- pandas
- plotly
- Jupyter Notebook (inside VS Code)