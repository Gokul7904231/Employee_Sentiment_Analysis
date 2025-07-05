# 📊 Employee Sentiment Analysis – Summary

This repository contains the analysis and modeling of employee sentiment based on internal email messages. The project uses NLP to label sentiments, generate insights, score employees, detect flight risks, and predict trends.

---

## 🔝 Top 3 Positive Employees (Example: July 2011)

| Rank | Employee Email                 | Score |
|------|-------------------------------|-------|
| 1    | johnny.palmer@enron.com       | +2    |
| 2    | sally.beck@enron.com          | +2    |
| 3    | patti.thompson@enron.com      | +1    |

---

## 🔻 Top 3 Negative Employees (Example: July 2011)

| Rank | Employee Email                 | Score |
|------|-------------------------------|-------|
| 1    | bobette.riner@jpgdirect.com   | –3    |
| 2    | don.baughman@enron.com        | –3    |
| 3    | john.arnold@enron.com         | –2    |

---

## 🚨 Employees Flagged as Flight Risks

These employees sent 4 or more negative emails within any rolling 30-day window:

- jeffrey.shankman@enron.com
- mike.mcconnell@enron.com
- michael.rose@enron.com
- kate.symes@enron.com
- vince.kaminski@enron.com

> ✅ Total flagged employees: 5

---

## 🔍 Key Insights

- **Negative Dominance:** Negative messages significantly outnumber positive ones, suggesting morale or engagement concerns.
- **Monthly Fluctuations:** Sentiment trends vary month to month, often showing spikes during key periods.
- **Consistent Positivity:** Some employees maintain positive sentiment over several months.
- **Early Risk Signals:** Employees flagged for flight risk showed progressive negative trends before reaching the risk threshold.

---

## ✅ Recommendations

- Introduce regular pulse surveys for high-risk departments or employees.
- Implement feedback sessions for individuals with consistent negative sentiment.
- Enhance the predictive model with department, message topic, or network data.

---

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
### 📄 Final Report

[![Click to View Report](preview_image.png)](Employee_Sentiment_Analysis_Report.pdf)


---

## 👤 Author

**Gokul A**  
Submitted to Springer Capital as part of internal assessment.
