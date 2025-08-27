# FUTURE_DS_03
## 📊 Student Event Feedback Analysis 

This project is part of my **Data Science & Analytics Internship @FutureInterns**.  
The goal of Task 3 was to analyze student event feedback collected through surveys and uncover **satisfaction trends, sentiment insights, and actionable recommendations**.  

---

## 🔹 Project Overview  
- **Task:** Analyze student event feedback to uncover satisfaction trends and suggest improvements using survey data.  
- **Dataset:** Student survey responses collected via Google Forms (CSV).  
- **Deliverable:** Cleaned dataset, exploratory analysis, sentiment analysis, visual insights, and event improvement suggestions.  

---

## 🔹 Workflow  
1. **Data Collection** – Imported survey data (CSV from Google Forms).  
2. **Data Cleaning & Transformation** – Normalized columns, parsed timestamps, handled missing values, and removed duplicates.  
3. **Exploratory Data Analysis (EDA):**  
   - Rating distribution and top-rated events  
   - Event-type and department-wise satisfaction  
   - Recommendation percentages  
4. **Sentiment Analysis:**  
   - Applied **TextBlob** & **VADER** for polarity scoring  
   - Classified comments into positive, neutral, and negative sentiments  
   - Compared sentiment with ratings  
5. **Insights & Recommendations:**  
   - Top & bottom events by average rating  
   - Best-rated event types (e.g., Tech Fest, Cultural events)  
   - Improvement suggestions for scheduling, venue, audio, and seating  
6. **Export** – Saved cleaned dataset with sentiment labels.  

---

## 🔹 Skills Gained  
- Data Cleaning & Preprocessing  
- Sentiment Analysis (TextBlob & VADER)  
- Exploratory Data Analysis & Visualization  
- Extracting Insights from Surveys  
- Natural Language Processing (NLP)  

---

## 📂 Dataset & Notebook  
- 📑[View Analysis Notebook on Google Colab](https://github.com/rifaaa31/FUTURE_DS_03/blob/main/College_Event_Feedback_Analysis%20(1).ipynb)
-📊 [Download Survey Data (CSV)](https://github.com/rifaaa31/FUTURE_DS_03/blob/main/sample_student_feedback.csv)  
---    

## 🔹 Tools & Libraries  
- **Environment:** Google Colab  
- **Libraries:** `pandas`, `numpy`, `seaborn`, `matplotlib`, `TextBlob`, `vaderSentiment`, `wordcloud`  

---

## 🚀 Key Insights  
- **Top 3 Events:** Hackathon Sprint, Cultural Night, Tech Fest 2025  
- **Overall Recommendation Rate:** ~67%  
- **Sentiment Split:** 82.7% Positive, 10.9% Negative, 6.4% Neutral  
- **Suggestions:** Improve sound checks, enforce punctuality, plan larger venues, and provide clearer directions.  
