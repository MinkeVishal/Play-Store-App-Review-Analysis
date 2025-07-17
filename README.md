# 📱 Play Store Review Analysis

An exploratory data analysis (EDA) project focused on analyzing user reviews, ratings, and feedback patterns from apps on the Google Play Store. This helps identify factors that influence user satisfaction and app success.

## 📊 Project Objective

The main objective of this project is to analyze Google Play Store reviews to:
- Understand user sentiment across different app categories.
- Identify patterns in ratings and reviews.
- Discover common complaints or praises from user feedback.
- Provide actionable insights for developers to improve app quality and engagement.

## 🧰 Tools & Technologies Used

- Python
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib, Seaborn, Plotly
- NLTK / TextBlob / VADER (for sentiment analysis)
- WordCloud
- Google Play Store Dataset

## 📂 Dataset

- **Source:** [Provide link if available]
- The dataset includes fields such as:
  - `App`
  - `Category`
  - `Rating`
  - `Reviews`
  - `Size`
  - `Installs`
  - `Type`
  - `Price`
  - `Content Rating`
  - `Genres`
  - `Last Updated`
  - `Current Ver`
  - `Android Ver`

## 📌 Key Features & Insights

- Cleaned and preprocessed the dataset (e.g., removing nulls, correcting types).
- Visualized app rating distributions, category-wise installs, and pricing.
- Sentiment analysis on user reviews using NLP.
- Generated WordClouds for positive and negative reviews.
- Identified top-performing categories and potential areas of improvement.

## 📈 Visualizations

Some of the key visualizations include:
- Distribution of ratings by category
- Reviews vs. Installs scatter plots
- WordClouds of common user sentiments
- Sentiment polarity breakdown (positive, negative, neutral)

## 💡 Conclusion

- Free apps tend to get more installs but not necessarily better reviews.
- Games and Communication apps have the highest user engagement.
- Many low-rated reviews mention crashes, ads, or performance.
- Sentiment analysis can help app developers understand user feedback at scale.

## 🚀 Future Work

- Time-series analysis on app updates and review trends.
- Build a sentiment classification model.
- Recommend app improvements using NLP clustering.

## 📁 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/play-store-eda.git
