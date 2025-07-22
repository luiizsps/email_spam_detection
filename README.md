
# 📧 Spam Detection with Naive Bayes

This project applies **Natural Language Processing (NLP)** and the **Naive Bayes classifier** to identify whether an email is spam or not. The solution involves data preprocessing, feature extraction using `CountVectorizer`, and model training/evaluation with `BernoulliNB`.

---

## 📂 Project Structure

```
.
├── requirements.txt
├── datasets/completeSpamAssassin.csv
├── spam_detection_naiveBayes.ipynb
└── README.md                     
```

---

## 🧰 Requirements

Run:

```bash
pip install -r requirements.txt
python -m spacy download en_core_web_sm
```

---

## 🚀 How to Run

1. Clone the repository or download the notebook.
2. Open the notebook using Jupyter or Google Colab.
3. Run each cell sequentially.

---

## 📊 Results

The Naive Bayes classifier shows strong performance in detecting spam messages, particularly in terms of:

- High accuracy
- Good precision and recall for the "spam" class

---

## 🧠 Techniques Used

- **NLP Preprocessing**: tokenization, stopword removal, lemmatization
- **Feature Engineering**: Bag-of-Words model
- **Machine Learning**: Naive Bayes (MultinomialNB)

---

## ✍️ Author

Luiz Sérgio  
Student of Exact Sciences at UFRB  
📌 Specializing in AI and Machine Learning Projects
