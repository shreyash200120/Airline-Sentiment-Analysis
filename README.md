# 🛫 Airline Sentiment Analysis

A machine learning project that classifies customer opinions about airlines as **Positive**, **Neutral**, or **Negative** based on their social media posts or reviews.  
This project uses a dataset of airline-related tweets to train and evaluate sentiment classification models.

---

## 📌 Features
- **Data Preprocessing:** Cleaning text, removing stopwords, and tokenization.
- **Feature Extraction:** TF-IDF vectorization for text representation.
- **Model Training:** Machine Learning models for sentiment classification.
- **Evaluation:** Accuracy, precision, recall, and F1-score.
- **Visualization:** Charts to show sentiment distribution and model performance.

---

## 📂 Dataset
- **Source:** [Twitter US Airline Sentiment Dataset](https://www.kaggle.com/datasets/crowdflower/twitter-airline-sentiment)
- Contains ~14,600 tweets labeled as:
  - `Positive`
  - `Neutral`
  - `Negative`

---

## 🛠️ Tech Stack
- **Language:** Python  
- **Libraries:**
  - `pandas`, `numpy` — Data handling
  - `scikit-learn` — ML models and evaluation
  - `matplotlib`, `seaborn` — Visualization
  - `nltk` — Text preprocessing

---

## 🚀 How to Run
1. **Clone this repository**
   ```bash
   git clone git@github.com:shreyash200120/Airline-Sentiment-Analysis.git
   cd Airline-Sentiment-Analysis

2. Install dependencies
pip install -r requirements.txt

3. Run the Jupyter Notebook
jupyter notebook Airline_Sentiment_Analysis.ipynb

📊 Results : 
Achieved 94% accuracy using stratified 5-fold cross-validation with TF-IDF.

Model effectively distinguishes between positive, neutral, and negative sentiments.

📌 Future Improvements
1) Experiment with deep learning models (LSTMs, Transformers).

2) Deploy as a web app for live sentiment analysis.

3) Support multilingual airline reviews.

📜 License
This project is licensed under the MIT License.
