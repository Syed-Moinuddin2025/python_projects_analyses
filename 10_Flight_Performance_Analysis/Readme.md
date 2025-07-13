# ✈️ Flight Performance Analysis Project
Project Folder: 10_Flight_Performance_Analysis
Tool Used: Python (Jupyter Notebook) | Libraries: pandas, matplotlib, seaborn

# 📌 Overview
This project analyzes real-world flight data to uncover insights into airline performance, delays, busiest routes, and airport efficiency. The goal is to assist airlines and airports in improving operations, minimizing delays, and enhancing the passenger experience.

# 🗃️ Dataset Summary
The dataset contains flight information including:

Date & Time (year, month, day, hour)

Delay data (dep_delay, arr_delay)

Flight metadata (carrier, origin, destination, flight number)

Flight duration (air_time) and distance

Airline name

# ✅ Data Cleaning Performed
Converted departure and arrival time columns to readable datetime.time format

Handled NaN values in delay and air time columns

Created new columns like route, dep_hour for analysis

# 📊 Business Questions Answered
No.	Question
Q1	Which airline has the highest average departure delay?
Q2	Which routes (origin ➝ destination) are the busiest?
Q3	Which airline has the longest average air time?
Q4	What time of day sees the most flight departures?
Q5	Which origin airport is the busiest?
Q6	Which airlines have the highest average arrival delays?
Q7	Which flights cover the longest distances?
Q8	Which routes have the highest average arrival delays?
Q9	Which airline operates the most flights?
Q10	How many flights are delayed by more than 1 hour?
Q11	How many flights arrived on time or earlier?
Q12	What is the on-time percentage per airline?
Q13	Which destination airports have the most delayed arrivals?
Q14	Which airlines cover the longest average flight distances?

# 📈 Key Visualizations
Bar charts for delays, flight volume, and route analysis

Delay rankings by airline, route, and airport

On-time performance comparison

Longest routes by distance

# 📌 Insights Gained
Hawaiian Airlines flies the longest route (JFK ➝ HNL)

Some carriers consistently outperform others in on-time performance

Delay patterns vary by time of day and airport

Certain routes are more prone to delays due to congestion or distance

📂 Project Structure
# 10_Flight_Performance_Analysis/
## │
## ├── flight_data.csv           # Cleaned dataset
## ├── 01_Flight_Performance_Analysis.ipynb
## ├── images/                   # Exported charts (optional)
## └── README.md                 # This summary file

# 👨‍💻 Author
Syed Moin
🔗 LinkedIn
📁 GitHub Project Link

