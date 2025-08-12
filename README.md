
# Classification of Topics in Parliamentary Debates and Proceedings

## 1. Business Understanding
*The goal of this project is to classify topics in parliamentary responses to debates and proceedings using machine learning and data mining techniques.*  
*This supports:*
*- **Researchers/Analysts** – quick access to topic summaries for policy studies.*
*- **Journalists** – fast retrieval of debates on specific issues.*
*- **Parliament Staff** – efficient organization of official records.*
*- **Public** – improved transparency and navigation of proceedings.*

**Project Objectives:**
*1. Achieve ≥ 80% accuracy (or equivalent F1-score) in topic classification.*
*2. Correctly classify *unseen* parliamentary responses into relevant topics.*
*3. Ensure the process is well-documented and reproducible.*

**Constraints & Risks:**
*- Limited availability of labelled datasets.*
*- Class imbalance (some topics have fewer examples).*
*- Variations in language and vocabulary among speakers.*

**Assumptions:**
*- All transcripts are in English.*
*- Topic labels are predefined and mutually exclusive.*
*- Historical data reflects future debate topics.*

---

## 2. Data Understanding
*- **Source of Data**: (Add source links, e.g., official parliament transcripts API, datasets from Kaggle, etc.)*
*- **Data Format**: CSV / JSON / TXT containing debate transcripts and topic labels.*
*- **Data Size**: (e.g., number of rows, features, file size)*
- **Initial Observations**:
  *- Number of unique topics.*
  *- Common keywords or phrases per topic.*
  *- Missing or noisy data issues.*

---

## 3. Data Preparation
*Steps taken to prepare data:*
*- Cleaning: Removing special characters, irrelevant metadata, speaker IDs, timestamps.*
*- Tokenization: Splitting text into meaningful units.*
*- Stopword Removal: Removing common words with little semantic meaning.*
*- Lemmatization/Stemming: Reducing words to their root form.*
*- Feature Extraction: Using TF-IDF, Bag-of-Words, or embeddings (Word2Vec, BERT).*
*- Handling Class Imbalance: Oversampling/undersampling or using class weights.*

---

## 4. Modeling
*Models experimented with:*
*- Naïve Bayes*
*- Logistic Regression*
*- Support Vector Machines (SVM)*
*- Random Forest*
*- Deep Learning models (LSTM, BERT)*

**Model Selection Criteria:**
*- Accuracy*
*- F1-score*
*- Precision/Recall*
*- Computational efficiency*


## 5. Evaluation
*Evaluation metrics used:*
*- Accuracy*
*- Precision*
*- Recall*
*- F1-score*
*- Confusion Matrix*

**Best Model Performance:**
| Model       | Accuracy | Precision | Recall | F1-score |
|-------------|----------|-----------|--------|----------|
| parlResnpo  | 0.XX     | 0.XX      | 0.XX   | 0.XX     |

---

## 6. Deployment
- **Notebook**: Includes preprocessing, training, and evaluation steps.
- **GitHub Repository**: Contains source code, notebooks, and data ( public).
- **Colab Link**: (Add link to open project in Google Colab)
- Potential future deployment via:
  - Web app (Streamlit/Dash)
  - API endpoint for real-time classification



## 7. Project Management
- Version control with GitHub.
- Regular updates at CRISP-DM checkpoints.
- Branch strategy: `main` for stable releases, feature branches for development.



## 8. Team Members
| Name                | Role                         |
|---------------------|--------------------------    |
| Ezekiel Mwanza      | Data Preparation & Modelling |
| Kunda kasolo        | Data Collection & Cleaning   |
| Mwananyina Bwalya   | EDA & Feature Engineering    |
| Mulenga Kasokomona  | Modelling & Evaluation       |
| TeamWork            | Documentation & Presentation |  



## References


The CRISP-DM 1.0: Data mining guide

The CRISP-DM 2.0: CRISP-DM Guide

