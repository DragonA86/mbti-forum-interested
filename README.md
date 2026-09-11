# 🧠 MBTI Forum Interest Classification

An end-to-end Machine Learning pipeline for processing unstructured text data from MBTI community forums, vectorizing texts using TF-IDF and Sentence Transformers, and classifying post topics into relevant forum categories.

---

## 📌 Features & Workflow

1. **Exploratory Data Analysis (EDA):**
   - Forum distribution, label counts, and title/text length distribution.
   - Frequency analysis of 16 MBTI personality types mentioned in titles.

2. **Text Preprocessing:**
   - Removal of duplicates and special characters.
   - Stopwords removal and WordNet Lemmatization using NLTK.

3. **Feature Extraction:**
   - **TF-IDF Vectorizer:** Captures term frequency and n-gram relationships (1-2 ngrams).
   - **Sentence Transformers (`all-MiniLM-L6-v2`):** Extracts dense context embeddings.

4. **Model Building & Evaluation:**
   - Multi-class target encoding using `LabelEncoder`.
   - Classification using Logistic Regression and Support Vector Classifier (SVC).

---

## 📁 Repository Structure

- `data/`: Contains `mbti.csv` dataset.
- `notebooks/`: Jupyter Notebook containing the full pipeline code.
- `requirements.txt`: Python dependencies required to run the project.

---

## 🛠️ Installation & Usage

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/](https://github.com/)<YOUR-USERNAME>/mbti-forum-classification.git
   cd mbti-forum-classification
