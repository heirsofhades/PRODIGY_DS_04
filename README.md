# PRODIGY_DS_04
Sentiment Analysis on Twitter data – Prodigy InfoTech Internship Task 04
### 🚀 Prodigy InfoTech – Data Science Internship  
> **Analyzing public sentiment through tweet text using NLP techniques and data visualization**

---

## 📁 Dataset
used the Twitter Sentiment dataset containing tweets labeled with sentiment (Positive, Negative, Neutral), along with associated entities.

- 📂 `twitter_training.csv` (from Kaggle)
- Columns: `id`, `entity`, `sentiment`, `tweet`

---

## 🔧 Steps Performed

1. **Loaded and inspected the dataset**
2. **Cleaned the tweet text** using regex, stopword removal, and stemming
3. **Mapped sentiment labels** and fixed inconsistencies
4. **Visualized** sentiment distribution using `Seaborn`
5. **Generated WordClouds** to explore the language used across sentiments
6. (Optional) **Grouped and plotted sentiment by entity** using `Plotly`

---

## 📊 Visualizations

- **Sentiment Distribution Bar Chart**
- **WordClouds** for Positive, Negative, and Neutral tweets

---

## 🧠 Insights

- Most tweets showed a **positive** tone overall.
- Words in **negative tweets** were highly emotional and direct.
- WordClouds clearly distinguished linguistic patterns across sentiments.
- The `Borderlands` entity showed consistently strong positive sentiment.

---

## 📌 Libraries Used

- `pandas`
- `matplotlib`
- `seaborn`
- `nltk`
- `wordcloud`
- `plotly` 

---

## 📎 How to Run

1. Clone the repo
2. Place `twitter_training.csv` in the root directory
3. Run `SentimentAnalysis_Twitter.ipynb` in Jupyter or Colab

---

