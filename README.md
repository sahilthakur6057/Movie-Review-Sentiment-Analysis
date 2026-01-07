
  # Movie Review Sentiment Analysis 🎬
  
A classic **Natural Language Processing (NLP)** project that builds a binary sentiment classifier to predict whether an IMDB movie review is **Positive** or **Negative**.

The project explores and compares two text vectorization techniques:
- **Bag of Words** (CountVectorizer)
- **TF-IDF** (TfidfVectorizer)

Both paired with **Logistic Regression**. The **TF-IDF approach** delivered the best performance with **~90% test accuracy**.

## 📊 Project Highlights

- Dataset: IMDB Movie Reviews (50,000 labeled samples)
- Preprocessing: Lowercasing, punctuation removal, stopword removal, Snowball stemming
- Models: Logistic Regression (baseline)
- Evaluation: Accuracy, classification report, confusion matrix
- Key Insight: TF-IDF outperforms Bag of Words with better generalization

### Results Summary

| Technique                  | Test Accuracy | Training Accuracy | Notes                          |
|----------------------------|---------------|-------------------|--------------------------------|
| TF-IDF + Logistic Regression       | **~90%**    | ~93%             | Best balance, less overfitting |
| Bag of Words + Logistic Regression | ~88%        | ~99%             | Slight overfitting on training |

## 📁 Dataset

- **Source**: [IMDB Dataset of 50K Movie Reviews on Kaggle](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)
- **File**: `IMDB Dataset.csv`
- **Details**: 50,000 reviews (25,000 positive, 25,000 negative)

> Note: Download the CSV from Kaggle and place it in the project folder (or update the file path in the notebook).

Language: Python
Libraries: pandas, numpy, scikit-learn, NLTK

💡 Future Improvements

Experiment with lemmatization instead of stemming
Try advanced models (Naive Bayes, SVM, or BERT-based classifiers)
Hyperparameter tuning with GridSearchCV
Build a simple web app (Streamlit/Gradio) for live predictions

🙏 Acknowledgments

Dataset provided by the IMDB 50K Movie Reviews dataset on Kaggle
Inspired by standard NLP sentiment analysis practices


⭐ Star the repo if you found it helpful!
Feedback, issues, and pull requests are welcome 😊
Built by [SAHIL THAKUR]
LinkedIn Profile [https://www.linkedin.com/in/sahil-thakur-880718352]
January 2026
