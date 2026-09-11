# 📰 Fake News Prediction Using Machine Learning

A Machine Learning and Natural Language Processing (NLP) project that classifies news articles as **Fake** or **Real** based on their textual content.

## 📌 Project Overview

The objective of this project is to build a Machine Learning model that can identify whether a given news article is fake or real.

The project applies text preprocessing and **TF-IDF feature extraction** to convert news content into numerical features. Multiple classification algorithms are then trained and compared.

## 🔄 Machine Learning Workflow

1. Load the news dataset
2. Explore the dataset
3. Clean and preprocess the news content
4. Convert text to lowercase
5. Remove non-alphabetic characters
6. Remove English stopwords
7. Apply **Porter Stemming**
8. Convert text into numerical features using **TF-IDF**
9. Split the data into training and testing sets
10. Train multiple Machine Learning models
11. Compare model performance
12. Generate classification reports and confusion matrices

## 🧹 Text Preprocessing

The news content is processed using:

* Removal of non-alphabetic characters
* Lowercase conversion
* Tokenization
* English stopword removal
* Porter Stemming

The processed text is then transformed into numerical features using **TF-IDF Vectorization** with a maximum of **5,000 features**.

## 🤖 Machine Learning Models

Three classification algorithms are evaluated:

* **Logistic Regression**
* **Random Forest**
* **Support Vector Machine (SVM)**

The models are trained on the same TF-IDF-transformed dataset and their training and test accuracy are compared.

## 📊 Model Evaluation

The notebook evaluates the models using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

### Test Performance

| Model               | Test Accuracy |
| ------------------- | ------------: |
| Logistic Regression |     **≈ 51%** |
| Random Forest       |     **≈ 50%** |
| SVM                 |     **≈ 51%** |

The classification reports show that the current models achieve performance close to random classification on the test dataset.

## 📈 Model Comparison

The project includes a comparison of the trained models based on their training and testing accuracy.

The comparison helps identify how different Machine Learning algorithms perform on the same NLP feature representation.

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* NLTK
* Regular Expressions
* Scikit-learn
* TF-IDF Vectorization
* Logistic Regression
* Random Forest
* Support Vector Machine
* Matplotlib
* Seaborn
* Google Colab

## 📂 Project Structure

```text
fake-news-prediction/
│
├── fake_news_prediction.ipynb
└── README.md
```

## ▶️ How to Run

The project can be run using **Google Colab**.

1. Open the notebook in Google Colab.
2. Upload the required news dataset.
3. Run the notebook cells sequentially.
4. The news content will be cleaned and preprocessed.
5. TF-IDF features will be generated.
6. The dataset will be divided into training and testing sets.
7. Logistic Regression, Random Forest, and SVM models will be trained.
8. Model performance will be evaluated and compared.

## 🚀 Future Improvements

* Improve the text preprocessing pipeline
* Perform feature engineering
* Tune model hyperparameters
* Experiment with different TF-IDF configurations
* Try n-gram features
* Address potential data-quality issues
* Experiment with advanced NLP models
* Try Transformer-based models such as BERT
* Improve generalization on unseen news articles

## 👨‍💻 Author

**Harshul Sharma**
