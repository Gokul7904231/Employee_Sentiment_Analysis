<h1 align="center">📊 Employee Sentiment Analysis</h1>
<p align="center">
  🔍 Natural Language Processing • 📧 Email Text Mining • 📈 Predictive Modeling
</p>

---

## 📄 Visualization Report

✨ **[👉 Click here to view the Full Visualization Report (PDF)](https://github.com/Gokul7904231/Sentiment_Analysis/raw/main/Employee_Sentiment_Analysis_Visualizations.pdf)**  
🖼️ Includes EDA Charts • Rankings • Flight Risk Graphs • Model Performance

---

## 🚀 Project Overview

This project uses NLP and data science to analyze employee email messages and measure sentiment trends over time. It helps identify:
- Monthly sentiment patterns
- Top/Bottom scoring employees
- High-risk individuals (flight risk)
- Predictive trends using linear regression

---

## 🏆 Top Employees (Example: July 2011)

### ✅ Top 3 Positive Employees

| Rank | Employee Email           | Score |
|------|--------------------------|-------|
| 🥇   | johnny.palmer@enron.com  | +2    |
| 🥈   | sally.beck@enron.com     | +2    |
| 🥉   | patti.thompson@enron.com | +1    |

### ⚠️ Top 3 Negative Employees

| Rank | Employee Email               | Score |
|------|------------------------------|-------|
| 🔻   | bobette.riner@jpgdirect.com  | –3    |
| 🔻   | don.baughman@enron.com       | –3    |
| 🔻   | john.arnold@enron.com        | –2    |

---

## 🚨 Employees Flagged as Flight Risks

These employees sent **4+ negative emails** in any 30-day rolling window:

- jeffrey.shankman@enron.com  
- mike.mcconnell@enron.com  
- michael.rose@enron.com  
- kate.symes@enron.com  
- vince.kaminski@enron.com  

> 📌 Total flagged: **5**

---

## 📊 Key Insights

✅ Negative messages outnumbered positive ones, highlighting low morale  
📆 Sentiment fluctuates monthly — with dips during stress periods  
🏅 Some employees maintained consistent positivity  
🚨 Gradual negativity build-up was a strong indicator of flight risk  

---

## ✅ Recommendations

📍 Deploy pulse surveys for flagged individuals or teams  
👥 HR 1:1 sessions for consistently negative communicators  
📈 Expand model with metadata (department, topic, team size, etc.)  

---

## 📁 Project Structure

## 📁 Project Structure

```
📦 Employee-Sentiment-Analysis/
├── Sentiment_Analysis.ipynb
├── sentiment_labeled.csv
├── report.docx
├── visualizations/
│   ├── sentiment_distribution.png
│   ├── monthly_sentiment_trend.png
│   ├── top_positive_employees.png
│   ├── top_negative_employees.png
│   └── ...
├── Employee_Sentiment_Analysis_Visualizations.docx
└── README.md
```

---

## 👤 Author

**Gokul A**  
Submitted to **Springer Capital** as part of the final internship assessment.



