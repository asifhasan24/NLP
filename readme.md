# 🔍 Toxic Text Classification Project

This project focuses on identifying the most effective model for classifying toxic text content. The goal is to accurately detect and categorize harmful language such as **toxic**, **abusive**, **vulgar**, **menacing**, **offensive**, and **bigoted** content from user-generated text samples.

## 📂 Dataset

- Contains approximately **8,000 samples** of labeled text.
- Each text sample is annotated with one or more of the following labels:
  - `toxic`
  - `abusive`
  - `vulgar`
  - `menace`
  - `offense`
  - `bigotry`
- The dataset includes **unique/uncommon characters** that required **manual inspection and handling** during preprocessing.

## 🛠 Preprocessing

- Text cleaning (removing special characters, lowercasing, etc.)
- Manual inspection and handling of rare characters
- Tokenization and stopword removal
- Feature extraction using **Word2Vec embeddings**

## 🤖 Models Used

### 1. Logistic Regression with GridSearchCV
- Utilized **GridSearchCV** to tune hyperparameters
- Features extracted using **Word2Vec**
- Simple and interpretable baseline model

### 2. BERT (Bidirectional Encoder Representations from Transformers)
- Leveraged **pre-trained BERT embeddings**
- Fine-tuned for classification task
- Deep learning-based model that understands context and semantics better

## 📊 Evaluation

- Comprehensive evaluation performed
- Performance metrics and visualizations included in the final report (`results.pdf`)
- Metrics compared:
  - Accuracy
  - Precision
  - Recall
  - F1-Score

## 📄 Results

- All results and analysis are provided in the attached `results.pdf`
- Includes charts, confusion matrices, and comparison of both models
- Discusses strengths and weaknesses of each approach

## ✅ Conclusion

This project aims to:
- Compare traditional machine learning and deep learning approaches for text classification
- Highlight the impact of preprocessing and embeddings
- Provide a benchmark for toxic content detection in textual data
