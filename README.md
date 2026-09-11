# 📰 Fake News Detection Using Machine Learning

A Machine Learning project that classifies news articles as **Fake** or **Real** using Natural Language Processing (NLP) techniques.

## 📌 Project Overview

The objective of this project is to build a Machine Learning model that can classify news articles as either **Fake News** or **Real News** based on their textual content.

The project uses text preprocessing and TF-IDF feature extraction before training a Logistic Regression classification model.

## 🔄 Machine Learning Workflow

1. Load the news dataset
2. Clean and preprocess the text
3. Remove stopwords
4. Apply Porter Stemming
5. Convert text into numerical features using TF-IDF
6. Split the dataset into training and testing data
7. Train a Logistic Regression model
8. Evaluate the model using accuracy
9. Test the model on new news data

## 🤖 Model

**Algorithm:** Logistic Regression

**Feature Extraction:** TF-IDF Vectorization

**NLP Techniques:**

* Stopword removal
* Porter Stemming
* Text preprocessing

## 📊 Results

| Dataset       |   Accuracy |
| ------------- | ---------: |
| Training Data | **72.07%** |
| Test Data     | **49.18%** |

The model achieved **49.18% accuracy on the test dataset**.

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* NLTK
* Scikit-learn
* Natural Language Processing (NLP)
* TF-IDF
* Logistic Regression
* Google Colab

## 📂 Project Structure

```text
fake-news-detection/
│
├── fake_news_prediction.ipynb
└── README.md
```

## ▶️ How to Run

The project can be run using **Google Colab**.

1. Open the notebook in Google Colab.
2. Upload the required `fake_news_dataset.csv` dataset.
3. Run the cells sequentially.
4. The notebook will preprocess the news text.
5. TF-IDF features will be generated.
6. The Logistic Regression model will be trained.
7. The model will evaluate the training and test data.
8. New news articles can be classified as Fake or Real.

## 🚀 Future Improvements

* Improve text preprocessing
* Experiment with different NLP techniques
* Try other classification algorithms
* Perform hyperparameter tuning
* Use additional evaluation metrics such as precision, recall and F1-score
* Improve test-set performance
* Explore more advanced NLP and Deep Learning models

## 👨‍💻 Author

**Harshul Sharma**
