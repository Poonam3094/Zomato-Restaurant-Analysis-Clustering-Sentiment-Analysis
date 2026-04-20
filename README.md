#  Zomato Restaurant Analysis | Clustering + Sentiment Analysis

##  Project Overview
This project analyzes Zomato restaurant and customer review data to uncover insights related to pricing, ratings, cuisines, restaurant segmentation, and customer sentiment.

The goal is to help food delivery platforms and restaurant owners make data-driven decisions.

---

##  Tools & Technologies
- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- NLTK (VADER)

---

##  Techniques Used
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Hypothesis Testing
- Feature Engineering
- KMeans Clustering
- Sentiment Analysis (NLP)

---

##  Dataset Used
Two datasets were used:

1. Restaurant Metadata
   - Name
   - Cost
   - Cuisine
   - Timings
   - Collections

2. Restaurant Reviews
   - Restaurant Name
   - Review Text
   - Rating

---

##  Key Insights

### Restaurant Analysis
- Most restaurants fall in low to mid-price range.
- North Indian cuisine is most common.
- Premium restaurants are fewer in number.

### Ratings Analysis
- Ratings are skewed toward 4 and 5 stars.
- Cost has weak correlation with customer ratings.

### Clustering Results
Three restaurant segments identified:

1. Budget / Average Performers  
2. Premium Restaurants  
3. Value-for-Money Restaurants

### Sentiment Analysis
- Positive reviews align with higher ratings.
- Negative reviews align with lower ratings.

---

##  Business Recommendations
- Promote value-for-money restaurants.
- Use sentiment analysis for feedback monitoring.
- Budget restaurants should improve service quality.
- Recommend restaurants based on customer spending behavior.

---

##  Project Files
- `zomato_analysis.ipynb` → Notebook version
- `zomato_analysis.py` → Python script
- `requirements.txt` → Dependencies

---

##  How to Run

```bash
pip install -r requirements.txt
python zomato_analysis.py
