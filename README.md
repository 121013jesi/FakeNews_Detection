# 📰 Fake News Detection using Machine Learning

This project is a machine learning-based system to detect whether a news article is **Fake** or **Real**. It leverages NLP (Natural Language Processing) techniques and multiple classification algorithms to identify misinformation in online news.

## 🔍 Objective

To develop a fake news detection system using Python and machine learning algorithms that can classify news articles based on their authenticity.

---

## 📚 Features

- Preprocesses and cleans raw text data
- Converts text to numerical features using TF-IDF vectorization
- Trains and evaluates multiple ML models:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - Gradient Boosting
- Allows manual testing of custom input news

---

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Natural Language Toolkit (NLTK)
- Jupyter Notebook

---

## 🧠 Models Trained

| Model              | Accuracy |
|-------------------|----------|
| Logistic Regression | ✅ High Accuracy |
| Decision Tree       | ⚠️ Moderate Accuracy |
| Random Forest       | ✅ High Accuracy |
| Gradient Boosting   | ✅ High Accuracy |

---

## 🧪 How to Run

1. **Clone the repository:**

```bash
git clone https://github.com/yourusername/fake-news-detection.git
cd fake-news-detection
Install dependencies:


pip install -r requirements.txt
Run the Jupyter Notebook:

jupyter notebook
Test your own news:

Use the manual_testing("Your news text here") function at the end of the notebook.

📁 Dataset
The dataset used is from Kaggle: Fake and Real News Dataset

🧹 Preprocessing Steps
Lowercasing text

Removing punctuation and special characters

Removing stopwords

Lemmatization

📊 Results
The best model achieved a high level of accuracy in detecting fake news, with Logistic Regression, Random Forest, and Gradient Boosting showing excellent performance.

🤖 Future Work
Deploy the model using Flask or Streamlit

Integrate with web scraping tools to test live articles

Improve accuracy with deep learning (LSTM or BERT)

📌 License
This project is licensed under the MIT License.

👩‍💻 Author
Jesika – 3rd Year CSE Student

Feel free to fork the repo, contribute, and star if you found it useful ⭐


