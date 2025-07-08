# Animal Riddles - Machine Learning Project

> A machine learning project to predict animals from creative riddles using NLP and Logistic Regression.

## Objective

To build a machine learning model that classifies animal riddles to predict the correct animal mentioned or implied in the riddles.

---

## Problem Statement

Animal riddles are short, often creative text snippets that indirectly describe an animal. The challenge is to interpret the riddle and accurately predict the corresponding animal using a machine learning model.

---

## Challenges

* Limited dataset size (~100 samples) for training
* Handling ambiguous or poetic language in riddles
* Ensuring good performance on unseen, creative riddles
* Selecting appropriate NLP techniques for short text

---

## Outcome

* Successfully built an NLP-based classification model using Logistic Regression
* Achieved meaningful prediction accuracy on a small dataset
* Designed a scalable framework for future enhancement with more data and advanced models

---

## Key Features

* Text preprocessing and cleaning
* NLP basics applied (tokenization, stopword removal, vectorization)
* Feature extraction using TF-IDF
* Model training using Logistic Regression
* Evaluation of model performance
* Predicting animals based on unseen riddles

---

## Dataset

* ~100 sample animal riddles
* The project is designed to scale and support larger datasets for improved training
* Each riddle is paired with the correct animal label
* Example:  
  **Riddle**: *"I have a mane and I roar, I’m the jungle’s mighty lord."*  
  **Label**: *Lion*

---

## ML & NLP Techniques Used

* Basic NLP preprocessing: lowercasing, punctuation removal, stopword removal
* Tokenization and vectorization using `TfidfVectorizer`
* Classifier:
  * Logistic Regression

---

## Evaluation Metrics

* Accuracy
* Classification Report
* Confusion Matrix

---

## Future Improvements

* Increase dataset size to improve model generalization
* Experiment with other classifiers (Naive Bayes, SVM)
* Try transformer models like BERT for deeper semantic understanding
* Build a web app interface for interactive riddle solving

---

## How to Use

1. Clone the repository or download the notebook
2. Open the notebook in Google Colab
3. Run the notebook step-by-step to train and test the model
4. Modify the `predict_animal(riddle)` function to test your own riddles

---

## Colab Link

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1DXDtBav40VHRHbBrbQrO5mjGO0daiLJw)

---

## Contact

Feel free to reach out via [GitHub or email](mailto:your-email@example.com) for feedback or suggestions.
