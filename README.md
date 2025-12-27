## 📌 Spam Email Classifier

This project is a **Machine Learning–based Spam Email Classifier** that detects whether an email is **Spam** or **Not Spam (Ham)** using **Natural Language Processing (NLP)** techniques.
The model is trained using **Naive Bayes** and **Support Vector Machine (SVM)** algorithms.

---

## 🧠 Problem Statement

Spam emails cause inconvenience and security risks.
The goal of this project is to **automatically classify emails** based on their content to help filter spam effectively.

---

## 📂 Dataset

* Email dataset containing **email text (subject + body)** and labels.
* Labels:

  * `1` → Spam
  * `0` → Not Spam (Ham)
* Dataset was cleaned to handle:

  * Missing values
  * Mixed label formats (text and numeric)

---

## ⚙️ Technologies Used

* Python
* Google Colab
* Pandas, NumPy
* Scikit-learn
* TF-IDF Vectorization
* Naive Bayes
* Support Vector Machine (SVM)

---

## 🔄 Project Workflow

1. Load and clean email dataset
2. Preprocess text data
3. Convert text into numerical features using **TF-IDF**
4. Split data into training and testing sets
5. Train models:

   * Naive Bayes
   * Support Vector Machine (SVM)
6. Evaluate model performance
7. Test with custom email input

---

## 📊 Model Performance

* **Naive Bayes**: Fast and efficient baseline model
* **SVM**: Achieved better accuracy and more reliable predictions

Different models may produce different predictions due to their learning mechanisms.

---

## 🧪 Sample Prediction

The trained model can predict whether a given email is spam or not using real email content.

Example:

```text
"Congratulations! You have won a free gift card. Click here to claim now."
```

---

## 📁 Repository Structure

```
Spam-Email-Classifier/
│
├── Images/
├── .gitattributes
├── README.md
├── Requirements.txt
├── Spam_Email_Classifier.ipynb
└── emails.csv
```

---
## 🚀 Conclusion

This project demonstrates the application of **NLP and machine learning** techniques in solving real-world spam detection problems.
Among the models used, **SVM performed better than Naive Bayes** for this dataset.


## 👤 Author
**Aman Sah**  
Intern at Codec Technologies
