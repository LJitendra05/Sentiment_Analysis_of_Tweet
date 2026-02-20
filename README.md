# 🐦 Sentiment Analysis of Tweets

This project performs **Sentiment Analysis on Tweets** using Machine Learning and Natural Language Processing (NLP) techniques.  
It classifies tweets into:

- ✅ Positive  
- ❌ Negative  
- 😐 Neutral  

The system includes data preprocessing, text cleaning, feature extraction, model training, and performance evaluation.

---

## 📌 Project Description

Social media platforms like Twitter generate large volumes of opinion-based textual data.  
This project aims to automatically determine the **sentiment** expressed in tweets by analyzing their textual content.

Sentiment analysis is useful for:

- Customer feedback analysis  
- Product review monitoring  
- Brand reputation management  
- Public opinion mining  
- Social media analytics  

---

## 🛠️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  
- re (Regular Expressions)  
- tqdm  
- pysentimiento  
- Natural Language Processing (NLP)

---

## 📂 Project Structure

```
Sentiment_Analysis_of_Tweet/
│
├── Sentiment_Analysis_of_Tweet.ipynb   # Main implementation file
├── Tweets.csv                          # Dataset used
└── README.md                           # Project documentation
```

---

## 🧹 Data Preprocessing Steps

The following preprocessing techniques are applied to clean tweet text:

- Convert text to lowercase  
- Remove URLs  
- Remove mentions (@username)  
- Remove hashtags  
- Remove punctuation  
- Remove stopwords  
- Tokenization  
- Lemmatization  
- Remove special characters using Regular Expressions  

---

## 🧠 Model Training

The cleaned data is transformed into numerical features using:

- TF-IDF Vectorization

Machine Learning algorithms are then applied for sentiment classification.

---

## 📊 Performance Evaluation

Model performance is evaluated using:

- Accuracy Score  
- Confusion Matrix  
- Classification Report  

Visualization is done using Matplotlib and Seaborn.

---

## ▶️ How to Run the Project

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/Sentiment_Analysis_of_Tweet.git
cd Sentiment_Analysis_of_Tweet
```

### Step 2: Install Required Libraries

```bash
pip install pandas numpy scikit-learn matplotlib seaborn tqdm pysentimiento nltk
```

### Step 3: Open Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
Sentiment_Analysis_of_Tweet.ipynb
```

Run all cells to preprocess data, train the model, and evaluate performance.

---

## 📈 Output

The trained model predicts whether a tweet expresses:

- Positive Sentiment  
- Negative Sentiment  
- Neutral Sentiment  

---

## 🔮 Future Enhancements

- Deep Learning Models (LSTM, BERT)  
- Real-time Twitter API integration  
- Web-based GUI using Streamlit  
- Deployment on cloud platforms  

---

## 📄 License

This project is developed for educational purposes.

---

## Developed by:**L Jitendra Kumar**
