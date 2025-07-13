# 🌐 Website Traffic & Engagement Analysis (Python Project)

![Website_Traffic](https://github.com/Syed-Moinuddin2025/python_projects_analyses/blob/main/11_Website%20analysis%20project/Images/web.png)

## This project explores website traffic and engagement behavior using session-based analytics data. The goal is to uncover key insights from user activity, traffic sources, and engagement metrics using Python.

---

## 📂 Dataset Overview

| Column | Description |
|--------|-------------|
| `channel group` | Traffic source (e.g., Direct, Organic, Social) |
| `DateHour` | Timestamp at hourly granularity |
| `Users` | Unique users per hour |
| `Sessions` | Total sessions initiated |
| `Engaged Sessions` | Sessions with meaningful user activity |
| `Average engagement time per session` | Avg time (in seconds) users engaged during sessions |
| `Engaged sessions per user` | Ratio of engagement per user |
| `Events per session` | Avg number of actions (clicks, scrolls, etc.) per session |
| `Engagement rate` | % of sessions that were engaged |
| `Event count` | Total events triggered |
| `Hour` | Extracted hour from timestamp |

---

## 📊 Tools & Libraries Used

- Python 🐍
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (for scaling in radar chart)
- Jupyter Notebook

---

## 📌 Business Questions Answered

1️⃣ What are the overall trends in website sessions and users over time?  
2️⃣ Which marketing channel brings the highest number of users to the website?  
3️⃣ How does the number of sessions and users vary across different traffic channels?  
4️⃣ Which traffic channels show the highest average engagement time per session, and what does this imply about user behavior?  
5️⃣ How does the engagement rate vary across different marketing channels?  
6️⃣ Which channels are driving more engaged sessions compared to non-engaged ones?  
7️⃣ At what hours of the day does each channel drive the most traffic?  
8️⃣ Are there noticeable patterns in user traffic and engagement during specific hours of the day?  
9️⃣ Is there any correlation between high traffic (sessions) and high engagement rate over time?  
🔟 Which channels generate more actions/events per session, and how can this inform content or campaign strategy?

---

## 📈 Visualizations Included

- Line charts (time trends)
- Bar plots (channel comparison)
- Stacked bars (engaged vs non-engaged)
- Dual-axis plots (hourly behavior)
- Scatter plot (correlation)
- Radar chart (multi-metric channel performance)

---

## 📌 Key Insights

- Some channels consistently bring **high traffic** but low engagement → room for UX/content improvement.
- **Organic Search** and **Direct** channels often lead in both volume and engagement.
- **Hour-of-day analysis** helps identify **best timing** for publishing or campaigns.
- Radar chart reveals **well-rounded vs weak channels** across all metrics.

---

## 👨‍💻 Author

**Syed Moin**  
📎 [LinkedIn Profile](https://www.linkedin.com/in/syed-moin-hr)  
📁 [GitHub Projects Repo](https://github.com/Syed-Moinuddin2025/python_projects_analyses)

---

> ⭐ If you found this useful, don’t forget to star the repo!
