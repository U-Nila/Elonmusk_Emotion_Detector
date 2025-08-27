# Elonmusk_Emotion_Detector
Emotion detector using ML Algorithms to find the emotions in twitter post
# Elon Musk Tweet Sentiment Analysis 🚀  

This project analyzes Elon Musk's tweets (2015–2020) using **Natural Language Processing (NLP)** techniques. It performs data cleaning, visualization, sentiment analysis, and machine learning classification. Finally, it provides an interactive **Gradio web app** to test sentiment predictions on new tweets.  

---

## 📂 Dataset  

- Source: [Elon Musk Tweets Dataset (2015–2020) – Kaggle](https://www.kaggle.com/datasets/vidyapb/elon-musk-tweets-2015-to-2020)  
- Contains tweets from Elon Musk between 2015–2020.  

---

## ⚙️ Project Workflow  

### Data Loading & Preprocessing  
- Loaded dataset with Pandas  
- Handled missing values & duplicates  
- Created additional features like tweet length & year  

### Exploratory Data Analysis (EDA)  
- Distribution of tweet lengths  
- Number of tweets per year  
- Top users tweeting  
- Basic dataset statistics  

### Sentiment Analysis (Rule-based)  
- Used **TextBlob** to label tweets as `positive`, `neutral`, or `negative`.  

### Machine Learning Model  
- Train-test split (80/20)  
- Built **TF-IDF + Logistic Regression pipeline**  
- Evaluated with accuracy, classification report & confusion matrix  

### Prediction on New Tweets  
- Tested model on unseen tweets  

### Deployment with Gradio  
- Interactive web app to predict sentiment of custom input tweets  

---

## 🛠️ Tech Stack  

- **Python 🐍**  
- **Libraries**:  
  - Data: `pandas`, `numpy`  
  - Visualization: `matplotlib`, `seaborn`  
  - NLP: `textblob`, `scikit-learn`  
  - Web App: `gradio`  

---

## 📊 Results  

- **Classification Model Accuracy**: ~ (varies on split, usually 75–85%)  
- **Confusion Matrix**: shows good performance on positive/negative classes  
- Interactive demo works via **Gradio UI**  

---

## 🚀 How to Run  

1. Clone the repository  
   ```bash
   git clone https://github.com/your-username/elon-musk-sentiment.git
   cd elon-musk-sentiment
## 👨‍💻 Author  

- **UDHAYANILA U**  
- 📧 Email: [nilauthira2005@gmail.com](mailto:your.email@example.com)  
- 💼 LinkedIn: [https://www.linkedin.com/in/udhayanila-u-ba4967308/](https://www.linkedin.com/in/your-linkedin-username/)
- 🌐 GitHub: [U-Nila](https://github.com/your-username)
- 


