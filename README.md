# Final LLM Assessment – Sentiment Analysis of Employee Feedback

## ✅ Overview
This project performs sentiment analysis on employee feedback data and includes:
- Sentiment labeling (Positive, Negative, Neutral)
- Exploratory Data Analysis (EDA)
- Monthly sentiment scoring
- Employee ranking
- Flight risk identification
- Trend analysis using Linear Regression

## 🗂️ Files Included
- `final_dataset_with_sentiment.csv`: Dataset with sentiment labels
- `employee_ranking.csv`: Ranked employees by sentiment
- `flight_risk_employees.csv`: High-risk employees flagged
- `monthly_sentiment_trend.csv`: Sentiment trend per month
- `sentiment_distribution.png`, `monthly_sentiment_score.png`, `sentiment_trend.png`: Visualizations
- `Final_Assessment.ipynb`: Full source code and analysis
- `.env.example`: Sample format for environment variables (if used)

## 🚀 Setup Instructions
1. Clone this repository or unzip the folder.
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn textblob scikit-learn
   python -m textblob.download_corpora
