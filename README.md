

📊 Amazon Product Reviews – Sentiment & Topic Analysis
🔍 Project Overview

Amazon receives millions of customer reviews across products. Manually analyzing this feedback is impractical.
This project applies Natural Language Processing (NLP) and sentiment analysis to automatically classify customer reviews into positive, neutral, and negative sentiments, and extract dominant discussion topics.

🎯 Business Objective

Identify customer sentiment from textual reviews

Understand key themes driving satisfaction and dissatisfaction

Provide actionable insights to improve products and customer experience

📁 Dataset

Source: Amazon Product Reviews dataset

Key column used: reviews.text

Preprocessing included removal of missing values and text normalization

🧹 Text Preprocessing

Lowercasing

Removal of URLs, mentions, punctuation

Tokenization using NLTK

Stopword removal

😊 Sentiment Analysis

Tool: VADER Sentiment Analyzer

Metric: compound score

Classification rules:

Positive: score ≥ 0.05

Negative: score ≤ -0.05

Neutral: otherwise

📈 Exploratory Data Analysis
Sentiment Distribution

Insight:

Majority of reviews are positive

Smaller proportion of neutral and negative reviews

Indicates generally high customer satisfaction

☁️ Word Cloud Analysis
Positive Reviews

Neutral Reviews

Negative Reviews

📌 Business Insights from Word Clouds
🟥 Negative Reviews

Frequent mentions of device issues (screen, button, remote)

References to specific products (kindle, fire, hdx)

Price and competitor comparisons (ipad)

➡ Action: Improve hardware usability and value positioning

🟦 Neutral Reviews

Factual, experience-based language

Minor usability concerns without strong emotion

➡ Action: Address small friction points to convert neutral users

🟩 Positive Reviews

Strong emphasis on usability and features

High brand trust (amazon, alexa, easy, love)

➡ Action: Highlight these strengths in marketing campaigns

📊 Top Keywords by Sentiment

Bar charts were used to identify the top 20 most frequent words in each sentiment class.






🛠 Tools & Libraries

Python

Pandas, NumPy

NLTK

VADER Sentiment

Matplotlib, Seaborn

WordCloud

🚀 Conclusion

This project demonstrates how NLP and sentiment analysis can convert unstructured customer feedback into business-ready insights.
The results can support product improvements, customer retention strategies, and marketing decisions.

🔮 Future Improvements

Topic modeling using LDA

Sentiment prediction using ML classifiers

Aspect-based sentiment analysis

Dashboard deployment using Streamlit
