
# 🧠 Sentiment Analysis on Social Media

This project performs **Sentiment Analysis** on social media data (Twitter) to classify posts as **positive** or **negative** using machine learning techniques.
It demonstrates text preprocessing, feature extraction using **TF-IDF**, and training several classification models.

---

## 📘 Overview

The goal of this project is to understand how people express opinions on social media platforms.
Using a large labeled dataset, we train models that can automatically determine whether a tweet’s sentiment is positive or negative.

---

## ⚙️ Features

* Data loading and preprocessing
* Text vectorization using **TF-IDF**
* Model training with:

  * **Bernoulli Naive Bayes**
  * **Logistic Regression**
  * **Linear Support Vector Machine (SVM)**
* Evaluation using accuracy and classification reports

---

## 📂 Dataset

The notebook uses the **Sentiment140 dataset**, containing 1.6 million tweets.

| Column     | Description                                  |
| :--------- | :------------------------------------------- |
| `polarity` | Sentiment label (0 = negative, 4 = positive) |
| `text`     | Tweet content                                |

Dataset file:

```
training.1600000.processed.noemoticon.csv.zip
```

---

## 🧩 Installation

To run this notebook, install the required libraries:

```bash
pip install pandas scikit-learn
```

---

## ▶️ Usage

1. Open the Jupyter Notebook:

   ```bash
   jupyter notebook Sentiment_Analysis_on_social_media_dataset.ipynb
   ```
2. Run each cell sequentially.
3. The notebook will:

   * Load the dataset
   * Preprocess the data
   * Train multiple models
   * Output evaluation metrics

---

## 📊 Model Evaluation

Metrics used:

* **Accuracy**
* **Precision**
* **Recall**
* **F1-score**

The notebook compares models to determine which performs best on the dataset.

---

## 💡 Example Output

```
Accuracy (Logistic Regression): 0.84
Accuracy (Linear SVC): 0.86
Accuracy (Naive Bayes): 0.82
```

---

## 📈 Future Improvements

* Integrate deep learning models (LSTM, BERT)
* Include neutral sentiments
* Visualize sentiment trends across topics or hashtags

---

## 🧑‍💻 Author

**Sowmya Rapolu**
Project: *Sentiment Analysis on Social Media*
Language: Python (Jupyter Notebook)

---

