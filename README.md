 PRODIGY_DS_04
A sentiment analysis and visualization project using Twitter entity dataset.
🐦 Twitter Sentiment Analysis & Visualization

This project was completed as part of my Data Science Internship at **Prodigy InfoTech**. The goal of this task was to analyze sentiment patterns in Twitter data to understand public opinion toward various entities, using the **Twitter Entity Sentiment Analysis** dataset from Kaggle.

📌 Project Overview

The project focuses on:
- Cleaning and preprocessing real-world social media data
- Visualizing sentiment trends (Positive, Negative, Neutral)
- Training a basic machine learning model to classify sentiment
- Drawing insights from the behavior and opinions expressed in tweets

🗃️ Dataset

Source: [Kaggle - Twitter Entity Sentiment Analysis](https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis)

The dataset includes:
- `tweet_id`: Unique identifier for each tweet  
- `entity`: The subject or entity the tweet is about  
- `sentiment`: Sentiment label (Positive, Negative, Neutral, etc.)  
- `text`: Raw tweet text  

 🧠 Key Features & Workflow

1. Data Loading: Handled non-standard CSV structure
2. Text Cleaning: Removed URLs, mentions, hashtags, and special characters
3. Visualization:
   - Sentiment distribution (Bar chart, Pie chart)
   - Word clouds for each sentiment
4. Modeling:
   - Used CountVectorizer for feature extraction
   - Trained a Naive Bayes classifier for sentiment prediction
   - Evaluated using Accuracy, Precision, Recall, and F1-score
5. Prediction on Validation Set:
   - Predicted sentiment labels for new/unseen tweets

📊 Visual Outputs

- 📌 **Bar Charts** for sentiment distribution  
- ☁️ **Word Clouds** to highlight frequent terms  
- 📈 **Model Metrics** for evaluating classification performance  

🛠️ Tools & Technologies

- **Python**  
- **Pandas**, **NumPy**  
- **Scikit-learn**, **NLTK**  
- **Matplotlib**, **Seaborn**, **Plotly**  
- **Jupyter Notebook / Google Colab**

🔮 Future Improvements

- Implement advanced models like Logistic Regression, SVM, or BERT  
- Perform Named Entity Recognition (NER)  
- Add time-based trend analysis


