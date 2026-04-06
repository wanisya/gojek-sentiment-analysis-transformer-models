# 🚀 Gojek Reviews Sentiment Analysis using IndoELECTRA vs IndoBERT

## 📌 Overview

This project builds a sentiment analysis system for Indonesian text using deep learning models. The goal is to classify user reviews into sentiment categories such as positive, negative, or neutral.

The project uses modern NLP models (transformers) and covers the full process from data preparation to model evaluation.

---

## 🎯 Objectives

* Process and clean Indonesian text data
* Build a sentiment classification model
* Compare two models: IndoELECTRA and IndoBERT
* Evaluate how well the models perform

---

## 🧠 Models Used

* IndoELECTRA: ChristopherA08/IndoELECTRA
* IndoBERT: indobenchmark/indobert-base-p1

Both models are trained to understand Indonesian text and classify sentiment.

---

## ⚙️ Tools & Technologies

* Python
* PyTorch
* HuggingFace Transformers
* Scikit-learn
* Pandas & NumPy
* Matplotlib & Seaborn

---

## 📊 Dataset

The dataset used in this project is obtained from Kaggle:

👉 https://www.kaggle.com/datasets/izzahfathiyyah123/dataset-ulasan-gojek-clean

This dataset contains Indonesian user reviews of the Gojek application collected from Google Play Store.

In general, datasets like this include:

* User review text (content)
* Rating score (usually 1–5)
* Additional metadata such as date or app version ([Kaggle][1])

In this project, the data is organized into:

* **Raw data** → original reviews
* **Processed data** → cleaned text after preprocessing
* **Labeled data** → reviews with sentiment labels

---

## 🔄 Project Workflow

### 1. Data Preprocessing

* Clean text (remove symbols and noise)
* Convert text to lowercase
* Remove stopwords
* Normalize text

### 2. Data Labeling

* Assign sentiment labels (positive, negative, neutral)
* Labels can be derived from rating scores or manual labeling

### 3. Model Training

* Convert text into tokens using tokenizer
* Train models using IndoELECTRA and IndoBERT
* Optimization using AdamW

### 4. Evaluation

* Accuracy
* Precision, Recall, F1-score
* Confusion Matrix

---

## 📈 Key Insights

* The model learns quickly at the beginning but improves slowly after several epochs
* IndoELECTRA performs well but needs proper tuning
* IndoBERT gives stable results and works well as a baseline
* Good preprocessing significantly improves results

---

## ⚠️ Challenges

* Indonesian text is often noisy (slang, typos, informal words)
* Model performance can stop improving after several epochs
* Environment issues (e.g., Colab vs Kaggle dependencies)

---

## 🚀 Future Improvements

* Hyperparameter tuning (learning rate, batch size)
* Improve data quality or add more data
* Combine models (ensemble learning)
* Deploy as a web or API-based application

---

## 📁 Project Structure

sentiment-analysis-indoelectra/
│
├── data/
├── notebook/
├── results/
├── requirements.txt
└── README.md

---

## ▶️ How to Run

1. Install dependencies:
   pip install -r requirements.txt

2. Run the notebook:
   jupyter notebook

---

## 🔗 References

* Dataset: https://www.kaggle.com/datasets/izzahfathiyyah123/dataset-ulasan-gojek-clean
* IndoELECTRA: https://huggingface.co/ChristopherA08/IndoELECTRA
* IndoBERT: https://huggingface.co/indobenchmark/indobert-base-p1

---

## 👩‍💻 Author

Wani Syafitri

| LPDP Awardee | Master's in Computer Science

Focus:

Artificial Intelligence
Natural Language Processing (NLP)
AI-based Education Systems
Backend Development (PHP, JavaScript, MySQL)

---

## 📬 Contact

- GitHub: https://github.com/wanisya
- Email: wanisyf@gmail.com
- Kaggle: https://www.kaggle.com/wanisyafitri20
- LinkedIn: https://www.linkedin.com/in/wani-syafitri-3bbb90258/

---

## ⭐ If you find this project useful

Give it a star ⭐ on GitHub!

