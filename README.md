# 📩 SMS Spam Classifier using NLP and Machine Learning

This project is a simple yet effective **SMS Spam Classifier** built using **Natural Language Processing (NLP)** techniques and **Machine Learning**.  
It classifies a given message as **Spam** or **Ham (Not Spam)** based on its content.

---

## 🚀 Project Overview
In today’s world, SMS spam has become a major issue.  
This project demonstrates how text data can be preprocessed and modeled using **TF-IDF vectorization** and **Naive Bayes classifier** to accurately detect spam messages.

---

## 🧩 Features
✅ Cleans and preprocesses text messages (removes punctuation, stopwords, converts to lowercase)  
✅ Converts text to numerical format using **TF-IDF**  
✅ Trains and evaluates a **Naive Bayes model**  
✅ Displays model accuracy, confusion matrix, and classification report  
✅ Allows user input to classify custom messages  

---

## 🧠 Tech Stack
- Python 🐍  
- Pandas  
- NumPy  
- Scikit-learn  
- NLTK  
- Matplotlib / Seaborn (for visualization)

---

## 📊 Dataset
Used the **SMS Spam Collection Dataset** from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection)  
or available on [Kaggle](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)

---

## ⚙️ Steps to Run

```bash
# 1. Clone the repository
git clone https://github.com/<your-username>/SMS-Spam-Classifier-Using-NLP.git

# 2. Navigate to the project folder
cd SMS-Spam-Classifier-Using-NLP

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the notebook
jupyter notebook sms_spam_classifier.ipynb
